\# Lab 08 - Print Server and Printer Deployment with Group Policy



\## Objective



This lab demonstrates how to install the Print Server role on Windows Server 2016, create a shared printer, and automatically deploy the printer to domain users or computers using Group Policy.



\---



\## Lab Environment



\- Windows Server 2016

\- Windows 10 Client

\- Active Directory Domain Services

\- Group Policy Management

\- Print Management

\- Domain: aysegul.com

\- Server Name: Server1

\- Server IP: 192.168.1.100



\---



\## Tasks Performed



\### 1. Installed Print Server Role



Installed the following role:



```

Print and Document Services

```



Sub-role:



```

Print Server

```



\---



\### 2. Created a Shared Printer



Opened:



```

Print Management

```



Added a new printer:



```

IT Canon Inkjet 0253

```



Shared printer path:



```

\\\\Server1\\IT

```



\---



\### 3. Deployed Printer with Group Policy



Opened:



```

Print Management

```



Selected:



```

Deploy with Group Policy

```



Configured deployment to users or computers using a Group Policy Object (GPO).



\---



\### 4. Client Verification



On Windows 10 client machine:



```

ITPC01.aysegul.com

```



Verified:



\- Printer automatically appeared

\- Printer connection succeeded

\- Users could access the shared printer

\- Printer was available for use



\---



\## Skills Practiced



\- Windows Server Roles

\- Print Server Management

\- Printer Sharing

\- Group Policy Deployment

\- Active Directory

\- Windows Client Management



\---



\## Technologies Used



\- Windows Server 2016

\- Active Directory

\- Group Policy

\- Print Management

\- Windows 10



\---



\## Result



Successfully installed and configured a Print Server, shared a network printer, and automatically deployed it to domain clients using Group Policy.

