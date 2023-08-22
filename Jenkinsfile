pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                echo 'Hello Netology'
                git credentialsId: '73033305-42d9-4b05-920e-83325ca4de16', 
                url: 'git@github.com:pavelchashkov/ansible-vector-role.git',
                branch: 'main'
            }
        }
        stage('test') {
            steps {
                echo 'Run molecule test'
                sh 'molecule test'
            }
        }
    }
}
