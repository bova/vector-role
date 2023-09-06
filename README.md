Role Name
=========

Роль для установки Vector

Requirements
------------

Ansible >= 2.7

Role Variables
--------------

| Имя | Описание |
| ---- | ------- |
| vector_package | Название пакета |
| vector_version | Версия vector |

Dependencies
------------

Нет зависимостей

Example Playbook
----------------

```YAML
- name: Install Vector
  hosts: vector
  roles:
    - role: vector
```
	
License
-------

BSD

Author Information
------------------

Student
