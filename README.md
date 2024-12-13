<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Deploying Active Directory in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>
<img src=https://i.imgur.com/H7PgUQ6.png"" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the first step, we want to login to DC-1 (Domain Controller) and install Active Directory Domain Services. Then Promote DC-1 to a Domain Controller and configure a new forest with a dom ain (mydomain.com\) was used. The default account was logged out, the Remote Desktop was re-started to ensure these changes took effect, and then logged in under the new domain, as mydomain.com\labuser, so that logging in as a domain user is allowed now. 
</p>
<br />

<p>
<img src="https://i.imgur.com/ITqySOz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this step, we created an administrative user (Admin User) and Organizational Units.
 
  *Create an Organizational Unit (OU) called _EMPLOYEES for employee users
  
  *Create an OU called _ADMINS for administrative users
  
  *Create an OU called _CLIENTS for client users.
  
  *Create a user named Jane Doe. Jane Doe will be added to the _ADMINS OU.
  
After creating these OU's, we log out of the DC-1 as labuser, and then log back in, as Jane Doe, using the domain and user name for Jane Doe (mydomain.com\jane_admin).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
