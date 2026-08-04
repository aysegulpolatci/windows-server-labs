\# Lab 07- Group Policy Management (GPO)



\## Objective



This lab demonstrates how to create and configure a Group Policy Object (GPO) in Windows Server 2016 to manage user restrictions within an Active Directory domain.



\---



\## Lab Environment



\- Windows Server 2016

\- Active Directory Domain Services (AD DS)

\- Group Policy Management Console (GPMC)

\- Domain: aysegul.com

\- Computer Name: Server1



\---



\## Tasks Performed



\### 1. Created a New Group Policy Object



\- Opened \*\*Group Policy Management\*\*

\- Navigated to the target Organizational Unit (OU)

\- Created a new GPO named:



```

IT için ilk policy

```



\---



\### 2. Edited the Group Policy



Opened the policy using \*\*Edit\*\* and navigated to:



```

User Configuration

&#x20;└── Policies

&#x20;     └── Administrative Templates

&#x20;          └── Windows Components

&#x20;               └── File Explorer

```



\---



\### 3. Configured Drive Restrictions



Configured the following policy:



```

Hide these specified drives in My Computer

```



Settings:



\- Enabled

\- Restrict C drive only



Purpose:



\- Hide the C: drive from File Explorer.

\- Prevent users from easily browsing the system drive.

\- Increase user restrictions within the domain.



\---



\## Skills Practiced



\- Active Directory

\- Group Policy Management

\- Group Policy Objects (GPO)

\- User Configuration Policies

\- File Explorer Administrative Templates

\- Windows Server 2016 Administration



\---



\## Commands Used



No PowerShell commands were required.



Configuration was completed using the Group Policy Management Console (GPMC).



\---



\## Technologies Used



\- Windows Server 2016

\- Active Directory

\- Group Policy Management

\- GPMC

