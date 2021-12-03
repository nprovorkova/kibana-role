kibana-role
=========

Роль для установки Kibana

Requirements
------------

Поддерживаются только ОС семейств debian и EL.

Role Variables
--------------


| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| kibana_version | "7.14.0" | Параметр, который определяет какой версии Kibana будет установлена |

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: kibana-role }

License
-------

BSD

Author Information
------------------

Nataliya P.