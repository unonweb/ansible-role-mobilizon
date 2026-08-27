ABOUT
=====

A radically simple Ansible role for **mobilizon**.
- State: Development
- System: Debian

This role assumes that a Nginx Reverse Proxy is used in a DMZ which accepts all incoming connections, handles the encryption and forwards requests to 
a) mobilizon web app itself on port 4000
b) another nginx that server static files on port 80


NOTES
=====

- https://docs.mobilizon.org/3.%20System%20administration/install/release/
- https://docs.joinmobilizon.org/administration/install/release/#database-setup
- https://framagit.org/kaihuri/mobilizon