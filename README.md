# ansible-adobe-cq


Ansible module to automate configuration of Adobe CQ


## cqagent

Create and modify replication agents

## cqgroup

Create a basic group. This module doesn't handle access control lists so it's not that useful. It's more to create groups that contain other groups, e.g. a 'sysadmin' group is in the administrator group; 'developers' are in the 'readonly' group.

## cqpassword

Change the admin user password. TODO: check if this is necessary, or can be done by the cquser module

## cqpkg

Manage CQ packages

## cquser

Creat and modify users
