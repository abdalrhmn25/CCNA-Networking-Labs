
# LAB-001: Basic Router Security Configuration

## 1. Lab Overview
This lab focuses on basic router security configuration using Cisco Packet Tracer.

## 2. Objectives
- Connect two routers using GigabitEthernet0/0.
- Configure router hostnames.
- Set an enable password.
- Examine password visibility in the running configuration.
- Enable password encryption.
- Disable password encryption and observe the difference.

## 3. Network Topology
- Router 1: R1 (Cisco 1941)
- Router 2: R2 (Cisco 1941)
- Connection: GigabitEthernet0/0 to GigabitEthernet0/0

## 4. Configuration Commands

### Configure R1
```bash
enable
configure terminal
hostname R1
enable password cisco
service password-encryption
no service password-encryption
end
```

### Configure R2
```bash
enable
configure terminal
hostname R2
enable password cisco
service password-encryption
no service password-encryption
end
```

## 5. Verification
Commands used:
```bash
show running-config
show startup-config
show ip interface brief
```

## 6. Key Learning Outcomes
- Configuring basic router settings.
- Understanding the enable password.
- Observing password encryption in Cisco IOS.
- Understanding the effect of the service password-encryption command.

## 7. Lab Source
Jeremy's IT Lab - CCNA Routing & Switching Packet Tracer Labs.

## 8. Tools
- Cisco Packet Tracer
- Cisco IOS
