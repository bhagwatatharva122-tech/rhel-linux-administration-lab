# Linux Networking Lab

## What I did

Configured and troubleshot networking on my RHEL virtual machine using NetworkManager and basic Linux networking commands.

## Environment
-RHEL 9
-VMware
-Interface: ens160
## Network Configuration

-Configured a static IPv4 address on the RHEL virtual machine using NetworkManager.
 -IP Address: 172.24.0.110/24
 G-ateway: 172.24.0.254
 -DNS: 172.24.0.254
 -Hostname: node1.domain0.example.com

### Commands Used

```bash
-ip addr
-nmcli connection show
-nmcli device status
-ip route
```
