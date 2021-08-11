# tn4-edges-shutdown
Shut down all Tn4 JUNOS edges with Ansible.

See: https://www.juniper.net/documentation/us/en/software/junos-ansible/ansible/topics/topic-map/junos-ansible-device-halting-rebooting-shutting-down.html

## Usage of this playbook
Clone this repository and setup ansible.
```
% git clone https://github.com/yamaoka-kitaguchi-lab/tn4-edges-shutdown
% cd tn4-edges-shutdown
% pipenv update
% pipenv run install
```

Edit targets and check their statuses with:
```
% vim inventories/production/edges
% deadman inventories/production/edges
```

Type the next, and all SWs will be down.
```
% pipenv run poweroff
```
