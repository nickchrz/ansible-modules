# ansible-modules
Modules created to support functionality required for projects I have worked on.

rds_cluster_param_group.py
--------------------------
Support for creating Aurora database cluster parameter groups seems to be missing from Ansible.  In this module I adapated the rds_cluster_param.py (https://github.com/ansible/ansible-modules-core/blob/devel/cloud/amazon/rds_param_group.py) module to perform this task.

rds_cluster.py
--------------
Adapting rds_cluster.py (https://github.com/ansible/ansible-modules-core/blob/devel/cloud/amazon/rds_cluster.py) to be able to accept a database database cluster parameter group.
