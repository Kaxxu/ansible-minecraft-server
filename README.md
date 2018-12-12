# Minecraft Server Installer
Ansible playbook to install and run Minecraft Server on CentOS or Ubuntu Server.

## Playbook Usage
Before the playbook use, edit the `hosts.yml` file to change variables for `MC Server Properties` file.

Use the command below to run the playbook:
```
ansible-playbook -i hosts.yml deploy-mc-server.yml
```