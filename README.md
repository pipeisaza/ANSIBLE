# ANSIBLE
examples of using Ansible with Junos.
I'm going to explore different options with Ansible, as a tool to manage/automate Junos tasks.

ENVIRONMENT:
MACBOOKPRO OS ElCapitan with Vmware Fusion running:
ANSIBLE on Ubuntu 16.04 (2.0.0.2-2ubuntu1)
2x VSRX (junos-vsrx-12.1X47-D15.4)

INSTALLING ANSIBLE:
https://www.juniper.net/techpubs/en_US/release-independent/junos-ansible/information-products/pathway-pages/index.html

https://www.juniper.net/techpubs/en_US/junos-ansible1.0/topics/task/installation/junos-ansible-server-installing.html

https://github.com/Juniper/ansible-junos-stdlib/blob/master/README.md

HOSTS FILE:
These are the 2 vSRX VMs:

cat /etc/ansible/hosts

[juniper]
192.168.178.253 
192.168.178.254

