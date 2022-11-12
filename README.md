Hadoop playbook
===============

This playbook install & configure hadoop cluster for 3 nodes


Dependencies
------------

 - OS Debian 11
 - Python version 3.9


Variables
---------

| Name | Description | Default Value |
|------|-------------|---------------|
| hadoop_version | hadoop version | 3.3.1 |
| activation_version | javax activation file version | 1.2.0 |
| node_ip01 | ip address of primary node | CHANGEME |
| node_ip02 | ip address of slave node | CHANGEME |
| node_ip03 | ip address of slave node | CHANGEME |
| node_name01 | dns name of primary node | node01 |
| node_name02 | dns name of slave node | node02 |
| node_name03 | dns name of slave node | node03 |


License
-------

BSD-3-Clause


Author Information
------------------

https://github.com/Borodatko
