Ansible Azure
=============

This role is responsible for creating the templates that Terraform uses to interact with Azure

Requirements
------------

Access to ansible-poc is required

Role Variables
--------------

- inventories/azure will be generated to attach the correct parameters to VMs we generate
- group_vars/azure will be used to translate the templates
- group_vars/vault_azure will be used to store keys

Dependencies
------------

- ansible-poc

