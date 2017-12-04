# ansible-workshop
Ansible workshop - hopefully generic enough that others can use it


Contains simple Ansible stuff, enough to get started.

This is not suitable for production, but should be usable for learning Ansible.

# Expected usage

1. clone the repository
2. create your own inventory file, copy the existing one to hosts.yourname
3. install Ansible on your own system

then you can play with the sample tasks.

# Requires a couple of servers

We added 4 Ubuntu servers and 1 OpenBSD VM to an Ubuntu laptop running KVM

# Warnings

This is not for production use, for example:
* We use a plain straight-forward approach without real roles
* Users can quickly edit playbooks and see stuff working
* They also mess about with the /etc/hosts file
* The OpenBSD example pf.conf should probably be split into multiple

The presentation about this is in my other repo:
security-courses/presentations/misc/ansible-workshop
