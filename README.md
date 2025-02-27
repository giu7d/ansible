# Ansible

My ansible setup.

## Playbooks

### Personal

The __personal playbook__ is the setup for my personal computer.

Before using the  __personal playbook__, you must match criterias.
The following dependencies should be installed:

1. Arch Linux
2. BRTFS File system
3. Gnome


There are some `group_vars` exclusive for my computer, make sure to have this correctly setup for your system configuration.

#### Execution

To execute this playbook, you can run in two modes:

```sh
 # Development
 ansible-playbook -i inventories/dev.yaml personal_playbook.yaml -kK

 # Production
 ansible-playbook -i inventories/prod.yaml personal_playbook.yaml -kK
```


### Home Server

TO DO...