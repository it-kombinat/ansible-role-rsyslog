rsyslog
=========

Provides rsyslog for your system and enabling an syslog generator script as service.

Requirements
------------

 - Ansible >= 2.4
 - Access to a repository containing packages, likely on the internet.

Role Variables
--------------

| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
| `rsyslog_remote` |  server1.example.com | rsyslog server |
| `syslog_gen_service` | true  | Enable syslog generator script |

License
-------

Apache License, Version 2.0

Author Information
------------------

IT-KOMBINAT.ORG
