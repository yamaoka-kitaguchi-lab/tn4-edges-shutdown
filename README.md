# tn4-edges-shutdown
Shut down all Tn4 JUNOS edges with Ansible.

See: https://www.juniper.net/documentation/us/en/software/junos-ansible/ansible/topics/topic-map/junos-ansible-device-halting-rebooting-shutting-down.html

## Usage of this playbook
Edit targets and check their statuses with:
```
% vim inventories/production/edges
% deadman inventories/production/edges
```

Then, type the following:
```
% pipenv run poweroff
```
