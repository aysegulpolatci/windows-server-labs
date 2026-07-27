# \# Lab 05 - Managing Domain Users and Local Administrators

# 

# \## Objective

# 

# Learn how to manage Active Directory user accounts and understand the relationship between domain users and local computer groups.

# 

# \---

# 

# \## Environment

# 

# \- Windows Server 2016

# \- Domain Name: aysegul.com

# \- Domain Controller: Server1

# \- Client Computer: PC2

# 

# \---

# 

# \## Tasks Performed

# 

# \### 1. Add a Domain User to the Local Administrators Group

# 

# A domain user account was added to the \*\*Administrators\*\* group on the client computer.

# 

# Steps:

# 

# 1\. Open Computer Management.

# 2\. Navigate to Local Users and Groups.

# 3\. Open the Administrators group.

# 4\. Click \*\*Add\*\*.

# 5\. Select a domain user from \*\*aysegul.com\*\*.

# 6\. Apply the changes.

# 

# Result:

# 

# The selected domain user obtained local administrator privileges on the client computer.

# 

# \---

# 

# \### 2. Restrict User Logon to Specific Computers

# 

# Configured an Active Directory user account so it can log on only to specific computers.

# 

# Steps:

# 

# 1\. Open Active Directory Users and Computers.

# 2\. Open the user's properties.

# 3\. Select the \*\*Account\*\* tab.

# 4\. Click \*\*Log On To\*\*.

# 5\. Choose \*\*The following computers\*\*.

# 6\. Add the allowed computer name.

# 

# Result:

# 

# The user is allowed to sign in only from the specified computer(s).

# 

# \---

# 

# \### 3. Reset a User Password

# 

# Reset the password of an Active Directory user account.

# 

# Steps:

# 

# 1\. Open Active Directory Users and Computers.

# 2\. Search for the user.

# 3\. Right-click the user.

# 4\. Select \*\*Reset Password\*\*.

# 5\. Enter the new password.

# 6\. Enable \*\*User must change password at next logon\*\* (optional).

# 

# Result:

# 

# The user's password was successfully reset.

# 

# \---

# 

# \## Skills Learned

# 

# \- Local Administrators Group Management

# \- Domain User Management

# \- Active Directory User Administration

# \- User Logon Restrictions

# \- Password Reset

# \- User Account Management

# 

# \---

# 

# \## Conclusion

# 

# This lab demonstrates common Active Directory administration tasks such as assigning local administrator permissions, restricting user logon to specific computers, and resetting user passwords. These tasks are frequently performed by Windows Server administrators in enterprise environments.

