# NOTE:

If you are not viewing this under the Systems Engineering/ansible-cq5 repository, you are looking at a forked copy. Do **not** update it as it will be overwritten.

# ansible-cq5

Ansible module to automate configuration of Adobe CQ

## cqagent

Create and modify replication agents

## cqgroup

Create a basic group. This module doesn't handle access control lists so it's not that useful. It's more to create groups that contain other groups, e.g. a 'sysadmin' group is in the administrator group; 'developers' are in the 'readonly' group.

## cqpassword

Change a user's password. Usually used to change the admin password from the default of 'admin'

## cqpkg

Manage CQ packages

## cquser

Create and modify users

## cqbundle

Enable and disable bundles

## cqservice

Start and stop CQ instances
