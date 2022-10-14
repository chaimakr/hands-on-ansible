# Hands on a configuration management tool : Ansible
## First version :
We simply configured and deployed an nginx server on an azure VM using __Ansible__.
## Requirements :
A virtual machine \
Change the inventory variables _./hosts_ 
``` 
ws1 ansible_host=<IP_ADDRESS> ansible_user=<USERNAME> ansible_ssh_private_key_file=<PATH_TO_SSH_PRIVATE_KEY>
```
## How to run a playbook from cli   :

```
ansible-playbook <playbook_file_name.yml>
```
