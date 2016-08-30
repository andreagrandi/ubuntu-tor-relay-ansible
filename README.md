# ubuntu-tor-relay-ansible
Ansible playbook to setup a TOR relay on Ubuntu

## Usage

```
ansible-playbook -i '<ip_address_of_server>,' -K tor-relay.yml
```

### Example

```
ansible-playbook -i '192.168.1.2,' -K tor-relay.yml
```
