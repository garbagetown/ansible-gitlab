ansible-gitlab
==============

ansible playbook to install gitlab

## How to use

follow the steps below.

- exchange public key
- make sure the selinux is disabled
- configure gitlab server's ipaddress in host
- execute `ansible-playbook -i host site.yml`