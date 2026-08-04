\# Lab 9 - DHCP Server Configuration and Client Lease Management



\## Objective



This lab demonstrates how to configure a DHCP Server in Windows Server 2016, create an IP address scope, configure exclusions, and verify client IP leases.



\---



\## Lab Environment



\- Windows Server 2016

\- Windows 10 Client

\- DHCP Server

\- Domain: aysegul.com

\- Server Name: Server1

\- Server IP: 192.168.1.100



\---



\## Network Information



Network:



```

192.168.1.0/24

```



DHCP Scope:



```

192.168.1.1 - 192.168.1.254

```



Exclusions:



```

192.168.1.1 - 192.168.1.10

192.168.1.100

```



Purpose of Exclusions:



\- Reserve addresses for network devices

\- Keep server IP addresses static

\- Prevent IP conflicts



\---



\## Tasks Performed



\### 1. Installed DHCP Server Role



Installed:



```

DHCP Server

```



Authorized the DHCP server in Active Directory.



\---



\### 2. Created DHCP Scope



Configured:



\- Scope Name

\- Start IP Address

\- End IP Address

\- Subnet Mask



\---



\### 3. Configured Exclusions



Excluded:



```

192.168.1.1 - 192.168.1.10

192.168.1.100

```



\---



\### 4. Activated Scope



Activated the DHCP scope and enabled automatic IP distribution.



\---



\### 5. Verified Address Leases



Client computer:



```

ITPC01.aysegul.com

```



Received:



```

192.168.1.11

```



Verified from:



```

Address Leases

```



\---



\## Skills Practiced



\- DHCP Server Installation

\- Scope Configuration

\- IP Address Management

\- Exclusions

\- Address Leases

\- Network Administration



\---



\## Technologies Used



\- Windows Server 2016

\- DHCP Server

\- Active Directory

\- Windows 10



\---



\## Result



Successfully configured a DHCP server, created an IP address pool, configured exclusions, and verified client IP lease assignments.

