# megatunkki

Ansible scripts for a personal VPS. May contain highly opionated software choices, configurations to my particular taste etc. Everything is subject to radical change, or on the other hand, stagnation.

## Usage

Some configuration files have been omitted on purpose and have to be created locally.

- `ansible_hosts` - [Ansible inventory file](http://docs.ansible.com/intro_inventory.html)
- `localvars.yml` - copy the .dist file and configure to suit your case

After configuring your local settings, run the play as you would normally do with Ansible
- `ansible-playbook playbook.yml`
