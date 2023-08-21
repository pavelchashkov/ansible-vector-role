netology-devops-ansible-vector
=========

Данная роль устанавливает `vector`.

Requirements
------------

None

Role Variables
--------------

- `vector_version` - версия `vector`, которая будет установлена
- `vector_config_dir` - директория с конфигурацией `vector`
- `vector_config` - полная конфигурация `vector`. Описание возможных значений [в официальной документации](https://vector.dev/docs/reference/configuration/)

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
---
- name: vector
  hosts: vector
  roles:
    - vector
```

License
-------

BSD
