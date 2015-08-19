Role Name
=========

This is a role for installing Apache Solr on MapR Hadoop.

Requirements
------------

MapR Hadoop should be installed already on the cluster. 

N.B., the node used to bootstrap zookeeper will come up in standby mode, according to MCS. Stop it and restart it to get that node to show up in the Solr Cloud view.

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
