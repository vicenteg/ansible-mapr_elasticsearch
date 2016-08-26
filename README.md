mapr_elasticsearch
=========

Install MapR's elasticsearch package.

Requirements
------------

Role Variables
--------------

See example.

Dependencies
------------


Example Playbook
----------------

```yaml
- hosts: elasticsearch
  roles:
    - { role: mapr_elasticsearch, elasticsearch_port: 9200, elasticsearch_version: 2.3.3, elasticsearch_build: "*" }
```

License
-------

Apache 2.0

Author Information
------------------

Vince Gonzalez
