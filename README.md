# Minecraft Server Installer
Ansible playbook to install and run Minecraft Server on CentOS or Ubuntu Server.

## Playbook Usage
Before the playbook use, edit the `hosts.yml` file to change variables for `MC Server Properties` file.

Use the command below to run the playbook:
```
ansible-playbook -i hosts.yml deploy-mc-server.yml
```

### File Structure
```
minecraft-server-ansible
├── LICENSE
├── README.md
├── deploy-mc-server.yml
├── hosts.yml
└── roles
    ├── get
    │   └── tasks
    │       └── main.yml
    ├── run
    │   ├── tasks
    │   │   └── main.yml
    │   └── templates
    │       ├── eula.j2
    │       ├── run-server.j2
    │       └── server.properties.j2
    └── set
        └── tasks
            └── main.yml

8 directories, 10 files
```
