# ansible_poc_1
First Anisble POC

## Usefull
```bash
ansible-playbook user_and_group_management --extra-vars "p_action=add user_name=user_nagios user_group=group_nagios group_create=2"
ansible-playbook hosts_management.yaml --extra-vars "p_action=delete ip=127.0.0.3 hostname=mos.docker.internal2"
```

