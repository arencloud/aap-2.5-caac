# aap-2.5-caac
AAP 2.5 Configuration as a Code

> **_NOTE:_**  This project is for AAP2.5 Configuration as a Code and all credentials are pseudo credentials. It is for purpose to explain how to fill inputs.

## Usage
```shell
ansible-playbook platform_configure.yml -t organizations
ansible-playbook platform_configure.yml -t teams
ansible-playbook platform_configure.yml -t authenticator
ansible-playbook platform_configure.yml -t authenticator-maps
ansible-playbook platform_configure.yml -t credentials
ansible-playbook platform_configure.yml -t credentials-types
ansible-playbook platform_configure.yml -t projects
ansible-playbook platform_configure.yml -t project-updates
ansible-playbook platform_configure.yml -t inventories
ansible-playbook platform_configure.yml -t hosts
ansible-playbook platform_configure.yml -t templates
ansible-playbook platform_configure.yml -t workflow-templates
```

NOTE: More updates will come soon