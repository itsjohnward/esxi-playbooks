# esxi-playbooks
Ansible scripts to automate deployment and maintenance of my esxi configuration

To execute:

```
ansible-playbook -i hosts playbooks/main.yml --extra-vars "env=dev" -t all,test,ansible
```
