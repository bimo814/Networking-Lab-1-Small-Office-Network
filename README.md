## Networking Lab #1: Small Office Network

### Project Overview

Built a small office network using Cisco Packet Tracer. Configured multiple employee computers connect through a Cisco 2960 switch and practiced assigning static IP addresses and troubleshooting network connectivity.

### Lab Environment
- Cisco Packet Tracer
- Cisco 2960 Switch
- Three employee PCs
- Ethernet Copper Straight-Through cables

### Step 1: Network Topology
Created a small LAN with three employee computers connected to a central Cisco 2960 switch.

### Step 2: IP Address Configuration

Configured static IPv4 addresses on each computer.

| Device | IPv4 Address | Subnet Mask |
|---|---|---|
| Employee-PC1 | 192.168.1.10 | 255.255.255.0 |
| Employee-PC2 | 192.168.1.11 | 255.255.255.0 |
| Employee-PC3 | 192.168.1.12 | 255.255.255.0 |

### Step 3: Network Connectivity Testing

Used the `ping` command to test communication between computers.

Example:
```cmd
ping 192.168.1.11
```

Received successful replies, confirming connectivity between devices.

### Step 4: Network Troubleshooting

**Problem:** Employee-PC3 was initially configured with an incorrect IP address: `192.168.2.12`

This placed the computer on a different network from the other employee computers.

**Resolution:** Changed the IP address to:

`192.168.1.12`

Kept the subnet mask at `255.255.255.0`.

Tested connectivity again using `ping` and successfully restored communication.

### Skills Practiced 

- Cisco Packet Tracer network simulation
- LAN configuration
- Static IPv4 addressing
- Subnet mask configuration
- Ethernet connectivity
- Network troubleshooting
- Ping connectivity testing
- Identifying incorrect IP configurations

### Project Outcome
Successfully configured and tested a small office LAN with three employee computers connected through a Cisco 2960 switch.
