# Linux Networking Lab

## What I did

Configured and troubleshot networking on my RHEL virtual machine using NetworkManager and basic Linux networking commands.

## Environment
- RHEL 9
- VMware
- Interface: ens160
## Network Configuration

Configured a static IPv4 address on the RHEL virtual machine using NetworkManager.

- IP Address: 192.168.1.100/24
- Gateway: 192.168.1.1
- DNS: 192.168.1.1
- Hostname: server2.skynet.com

### Commands Used

```bash
 ip addr
 nmcli connection show
 nmcli device status
 ip route
 hostnamectl
 getent hosts google.com
```
