# ansible-poc

Why
===

Written by https://github.com/elemantalcode, this repo contains the original
Proof of Concept code for the Ansible-generated Terraform solution, previously
used by HMCTS.

Structure
=========

Structure is changed to showcase the ability to map local vars for later use
in a single place. This is a simple Proof of Concept.

Run with:

`ansible-playbook -i inventories/localhost poc.yml --extra-vars "deploy_env=demoa"`
