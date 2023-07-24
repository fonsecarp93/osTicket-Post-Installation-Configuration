# osTicket-Post-Installation-Configuration
This is the list of all Virtual Machines and software that must be setup, downloaded and installed, for the osTicket system to work.

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>




Begin by logging in with the created osTicket Administrator login information
<p></p>
http://localhost/osTicket/scp/login.php

<h3>Configure Roles</h3>
Create a "Supreme Admin" Role, in the Admin Panel
Admin Panel -> Agents -> Roles
Assign ALL permissions, since this is an administrator role

<img src="https://i.imgur.com/zSZwNdo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>

<h3>Configure Departments</h3>
Create a "System Administrators" Department
Admin Panel -> Agents -> Departments

<img src="https://i.imgur.com/Rfr88mo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h3>Configure Teams</h3>
Create "Level I Support" and "Level II" Support Teams
Admin Panel -> Agents -> Teams

<img src="https://i.imgur.com/WPaphbA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h3>Allow anyone to create Tickets</h3>
Admin Panel -> Settings -> User Settings
Require registration and login to create tickets

<img src="https://i.imgur.com/hzOEESW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h3>Configure Agents (Workers)</h3>
Create two agents (Jane and John)
Admin Panel -> Agents -> Add New

Assign Jane all access and Permissions (will be an administrator)

<img src="https://i.imgur.com/60OnubT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Assign John all access and permissions, but do not set status as administrator (He will be a regular agent, not an admin)

<img src="https://i.imgur.com/rMZQdrU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h3>Configure Users (Customers)</h3>
Create two Users (Karen and Ken)
Agent Panel -> Users -> Add New

<img src="https://i.imgur.com/Fm61k2H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h3>Configure SLA</h3>
Create three different SLA's with different priority settings
Admin Panel -> Manage -> SLA
    Sev-A (1 hour, 24/7)
    Sev-B (4 hours, 24/7)
    Sev-C (8 hours, business hours)

<img src="https://i.imgur.com/eFolSg3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h3>Configure Help Topics</h3>
Create four different help topics
    Business Critical Outage
    Personal Computer Issues
    Equipment Request
    Password Reset
Admin Panel -> Manage -> Help Topics


<img src="https://i.imgur.com/1Zwa4UI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
