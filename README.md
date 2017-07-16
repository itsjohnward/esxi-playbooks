# esxi-playbooks
Ansible scripts to automate deployment and maintenance of my esxi configuration

To execute:

```
ansible-playbook -i hosts playbooks/deploy.yml --extra-vars "env=dev"
```
