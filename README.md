
# Build a simple network

A brief description of what this project does and who it's for


**Addressing table :**

| Devices | LAN | IP | Mask |
|---------|-----|----|------|
| PC-Robert | Eth | 192.168.1.10 | 255.255.255.0 | 
| PC-Camille | Eth | 192.168.1.11 | 255.255.255.0 |
| PC-Renaud | Eth | 192.168.1.12 | 255.255.255.0 |

**Resource Requirements :**
- 1 switch (Cisco 2960 with Cisco IOS version 15.0(2) image lanbasek9 or similar)
- 3 PCs (Windows 10)
- Three Ethernet cables

**Goals :**
* to be able to create a simple network
* to be able to configure interconnectivity between hosts
* to be able to connect hosts to the internet


## Write-up

1) To know IOS version in switch CLI 
```bashhow version 
show version
```
