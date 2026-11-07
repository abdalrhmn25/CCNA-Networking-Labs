# LAB-001: Basic Switch Configuration

## 1. Lab Overview
This lab focuses on configuring a Cisco Layer 2 switch using Cisco IOS commands in Packet Tracer.

## 2. Objectives
- Configure the switch hostname.
- Configure a management IP address.
- Configure console access.
- Configure privileged EXEC mode password.
- Verify switch interfaces and connectivity.

## 3. Network Topology
**Devices:**
- 1 Cisco 2960 Switch (SW1)
- 2 PCs (PC1, PC2)

**Connections:**
- PC1 → SW1 Fa0/1
- PC2 → SW1 Fa0/2

## 4. IP Addressing Table

| Device | IP Address | Subnet Mask |
|---|---|---|
| PC1 | 192.168.1.10 | 255.255.255.0 |
| PC2 | 192.168.1.11 | 255.255.255.0 |
| SW1 | 192.168.1.2 | 255.255.255.0 |

## 5. Configuration Tasks
1. Build the network topology.
2. Configure PC IP addresses.
3. Configure switch hostname.
4. Configure management VLAN interface.
5. Configure basic device access security.
6. Save the configuration.

## 6. Verification Commands

```cisco
show running-config
show ip interface brief
show interfaces status
show mac address-table
```

## 7. Troubleshooting
To be completed after performing and testing the lab.

## 8. Screenshots
Screenshots will be added after successful lab execution.

## 9. Packet Tracer File
`LAB-001.pkt`

## 10. Learning Outcomes
To be completed after completing the practical lab.
