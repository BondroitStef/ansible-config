ansible-config
==============

Ansible is the system that automatically installs the Zeus servers (specifically Abyss and King).
see https://docs.ansible.com

To run ansible install ansible (`brew install ansible` on OS X), clone this repository and and run the following command: `ansible-playbook --ask-vault-pass site.yml -i hosts`

The passwords are saved in vars/passwords.yml. This file can be edited
by issuing the command `ansible-vault edit passwords.yml` when in the same
directory. The password used to encrypt this is the general zeus root password that is used for everyting.
