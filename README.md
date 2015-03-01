Role Name
=========

This is a role for installing Apache Solr on MapR Hadoop.

Requirements
------------

MapR Hadoop should be installed already on the cluster. 

Role Variables
--------------

Dependencies
------------


Example Playbook
----------------

```
- hosts: zookeepers
- hosts: solr
  vars_files:
    - vars/global/main.yml
  roles:
    - solr
```


License
-------

MIT

Author Information
------------------

Vince Gonzalez
