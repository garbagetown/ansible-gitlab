ansible-gitlab
==============

ansible playbook to install gitlab

## How to use

follow the steps below.

- exchange public key
- make sure the selinux is disabled
- configure gitlab server's fadn in hosts and group_vars
- execute `ansible-playbook -i host site.yml`


### see also

- [Trouble Shooting Guide · gitlabhq/gitlab-public-wiki Wiki](https://github.com/gitlabhq/gitlab-public-wiki/wiki/Trouble-Shooting-Guide#could-not-read-from-remote-repository)