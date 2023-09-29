This playbooks has been tested on Debian 12

Modify `hosts` file:
+ master
+ workers
+ ansible_user

Execute:
```
ansible-playbook setup_cluster.yml -K
```