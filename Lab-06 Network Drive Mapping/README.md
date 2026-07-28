\# Lab 06 - Network Drive Mapping



\## Objective



The purpose of this lab is to map a shared network folder from a Windows Server 2016 file server to a Windows 10 client. This allows users to access shared company files through a drive letter, making file management easier and more efficient in a domain environment.



\---



\## Lab Environment



| Component | Value |

|-----------|-------|

| Server OS | Windows Server 2016 |

| Client OS | Windows 10 |

| Domain | aysegul.com |

| Server Name | Server1 |

| Server IP | 192.168.1.100 |

| Client Computer | PC2 |



\---



\## Shared Folder Structure



```

Data

└── SirketData

&#x20;   ├── IT

&#x20;   ├── PC

&#x20;   └── Sale

```



The shared folders were created on the Windows Server and made available to domain users.



\---



\## Steps



\### Step 1 - Open Map Network Drive



On the Windows 10 client:



\- Open \*\*This PC\*\*

\- Click \*\*Map Network Drive\*\*



\---



\### Step 2 - Select the Shared Folder



Browse to the shared folder on the server.



\*\*Network Path\*\*



```

\\\\192.168.1.100\\Data\\SirketData\\IT

```



\*\*Drive Letter\*\*



```

Z:

```



Enable:



\- ✔ Reconnect at sign-in



Then click \*\*Finish\*\*.



\---



\### Step 3 - Verify the Network Drive



The shared folder is successfully mapped and appears under \*\*This PC\*\* as:



```

IT (Z:)

```



Users can now access the shared folder just like a local drive.



\---



\## Result



The Windows 10 client successfully connected to the shared folder hosted on the Windows Server.



Mapped Drive:



```

Z:

```



Shared Folder:



```

\\\\192.168.1.100\\Data\\SirketData\\IT

```



The network drive is automatically reconnected whenever the user signs in.



\---



\## Screenshots



\### Browse Shared Folder



!\[Browse Shared Folder](images/map-network-drive.png)



\### Mapped Network Drive



!\[Mapped Network Drive](images/network-drive-success.png)



\---



\## Skills Learned



\- Windows File Sharing

\- SMB (Server Message Block)

\- Network Drive Mapping

\- Shared Folder Access

\- Windows File Server Administration

\- Drive Letter Assignment

\- Centralized File Management



\---



\## Conclusion



In this lab, a shared folder hosted on Windows Server 2016 was successfully mapped as a network drive on a Windows 10 client. Mapping network drives provides users with easy, centralized, and persistent access to shared resources, making it a common practice in enterprise environments.

