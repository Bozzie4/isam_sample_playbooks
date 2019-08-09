# isam_sample_playbooks
Some sample playbooks for IBM Security Access Manager

## Prerequisites
These playbooks depend on :

https://github.com/IBM-Security/isam-ansible-roles
https://github.com/IBM-Security/ibmsecurity

So you need to setup an Ansible environment with the roles and custom Python modules first.

You should have setup your connection to ISAM ( with an inventory etc. ) correctly already before these playbooks make any sense.

## Usage
To use these playbooks, copy the folder into your playbooks directory , and configure your environment.


## List of plays
| name | description |
| ----------- | ---------------------------- |
| change-to-ssl-local-ldap/change-policy-to-ssl-local-ldap.yml | Modifies the setup of ISAM from local policy/local ldap to local policy/remote ssl ldap to embedded ldap, see here: https://www.gwbasics.be/blog.nsf/dx/the-only-correct-way-to-setup-the-isam-rte-with-basic-users-for-the-userlookuphelper.htm |
