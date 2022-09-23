# Intro

## Requirements
If multiserver deployment, ensure passwordless SSH keys are setup between server you are running this playbook on and all other servers
RHEL/CENTOS/ROCKY Linux based server (version 8 or higher preferred)

## Install Ansible and other Requirements
```
yum install epel-release ansible git -y
```

## Inventory file
You will need to modify the inventory file to point to your servers.  You can install all components on the same server or split it into multiple

## Run the installer playbook
```
ansible-playbook -i inventory install.yml
```
