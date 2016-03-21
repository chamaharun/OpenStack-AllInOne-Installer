# OpenStack-AllInOne-Installer
This ansible-playbook installs OpenStack on your CentOS7.

## Useage


``` $ ansible-playbook -i hosts openstack-installer.yml ```

If The target servers need password to login as root,
``` --ask-pass ```
option is needed.
Or the case of publickey authentication,
``` --private-key=/path_to_the_private_key/ ```
option is useful.
