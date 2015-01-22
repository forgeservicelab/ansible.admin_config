# admin_node

Playbook for initial configuration of admin nodes. Currently supports (RH)EL variants.

**Usage**

 * Install roles with ansible-galaxy
 * Add secrets.yml containing gitlab_private_token
 * Run as follows

 ```
 ansible-playbook -s admin.yml -e h=hostname_or_ip
 ```
 
