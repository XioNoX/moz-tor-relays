# Ansible configuration of the Mozilla Tor relays

Please read http://blog.mozilla.org/it/2015/01/28/deploying-tor-relays/ for context.

This playbook can deploy the followings to your servers:
- SSH users and keys
- Static IPs
- Tor instances
- syscfg tunning

Don't forget to edit the vars files.

## Prerequisites
https://github.com/david415/ansible-tor/ (with https://github.com/david415/ansible-tor/pull/5)
and
https://github.com/bennojoy/network_interface

These can be installed by running `ansible-galaxy install -r requirements.yml`

## Contact
Don't hesitate to contact me at arzhel@mozilla.com for any questions.
