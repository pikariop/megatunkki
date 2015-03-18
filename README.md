# megatunkki

Ansible scripts for a personal VPS. May contain highly opionated software choices, configurations to my particular taste etc. Everything is subject to radical change, or on the other hand, stagnation.

## Usage

The inventory file has been omitted on purpose. You need to create one first if you wish to use this repo. By default, the file is named `ansible_hosts` (see `.gitignore`, `ansible.cfg`). See [Ansible docs](http://docs.ansible.com/intro_inventory.html) for more info on inventories.

After configuring your inventory, run the play as you would normally do with Ansible
- `ansible-playbook playbook.yml`
