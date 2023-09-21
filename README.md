
# Ansible HAProxy Cluster Manager

An Ansible Playbook to install, configure and manage a HAProxy Cluster

Software Used in this Playbook:

    - HAProxy
    - Keelalived
    - inotify-tools
    - acme.sh (Thanks to: https://github.com/nickjj/ansible-acme-sh)

This Playbook install HAProxy in desired Version, adds a default config to it and clusters everythink with Keepalived

Also requesting Lets Encrypt Certificates with acme.sh and automaticaly publishing Certificates to all members incl. auto Renew

Will add more description soon.