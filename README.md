# ansible-modules
Ansible modules

rds_cluster_param_group.py
--------------------------
Support for creating Aurora database parameter groups seems to be missing from Ansible.  In this module I adapated the rds_cluster_param.py (https://github.com/ansible/ansible-modules-core/blob/devel/cloud/amazon/rds_param_group.py) module to perform this task.
