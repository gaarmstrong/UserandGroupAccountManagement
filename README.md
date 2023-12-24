<h1>User and Group Account Management</h1>


<h2>Description</h2>
developing hands-on skills to administer local and domain users.

There are two types of user accounts in Windows:

1. Local user account
2. Domain user account

   
A local user account is restricted to the operating system on which it was created. The local user cannot perform tasks outside of the local system, for example, this account cannot be used on another desktop computer or laptop, even if it has been created on the same network. These types of accounts are normally used by home users or a small network without an Active Directory server. It is also important to note that a local user cannot be part of any domain group, such as domain users. Its scope is strictly limited to the local computer on which it is created.

A domain user account is used to log onto a domain to access resources on the domain, for example, file shares. Specific permissions are assigned to these types of accounts to ensure the user only has access to these specific resources. Domain users are centrally managed through a system known as Active Directory, which is installed on a server called a Domain Controller.

A Domain Controller is used for the authentication and authorization of the users on the network.
Domain users can be managed using a graphical tool on the Domain controller, which is known as Active Directory Users and Computers.

Another more advanced method for managing users and groups is by the use of PowerShell, which instead of having a graphical tool, a terminal is used to type commands to manage users and groups.

In this exercise, I created local, and domain user accounts using a graphical tool on a local computer system, and through Active Directory Users and Computers on the Domain Controller.
<br />


<h2>Learning Outcomes</h2>

- <b>Create a Local User</b>
- <b>Manage a User Account Permissions</b>
- <b>Create a Domain User Account</b>
- <b>Add a Domain User to a Domain Group</b> 

<h2>Environments Used </h2>

- <b>PLABDC01 - (Windows Server 2019 - Domain Controller)</b>
- <b>PLABWIN101 - (Windows 10 - Domain Member)</b>

<h2>Walk-through:</h2>

<p align="center">
Task 1 :Create a Local User <br/>
<img src="https://i.imgur.com/BOGnUgC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/ygp76tM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
