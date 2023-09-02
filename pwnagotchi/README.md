# pwnagotchi.yml

## Overview
This file copies pcaps from a pwnagotchi to the user's home directory, making directories as necessary.  Required directories and tools are downloaded and installed. 

## Ansible Configuration
add this to to `/etc/ansible/hosts`

```
[pwnagotchi]
10.0.0.2
```

## Pwnagotchi Configuration
update the new network (USB Ethernet/RNDIS Gadget) with the following:

```
ip: 10.0.0.1
subnet mask: 255.255.255.0
gateway: 10.0.0.1
```
