
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://youtu.be/HGywPhfKt4E?si=OjpsZYRVnVBeYrUL)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)

![image](https://github.com/techwithterrence/post-install-config/assets/174138674/8d55481f-af6b-4d4b-ad09-ed9304909860)

  
- Remote Desktop

- ![image](https://github.com/techwithterrence/post-install-config/assets/174138674/83ea362c-76a5-4e88-9e74-31ab7dd919da)


- Internet Information Services (IIS)

  ![image](https://github.com/techwithterrence/post-install-config/assets/174138674/ddaa4410-624a-4543-9bf3-d6cdcff244e3)


<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)


<h2>Configuration Steps</h2>  



- Configure Roles
Admin Panel -> Agents -> Roles
Supreme Admin

- Configure Departments
Admin Panel -> Agents -> Departments
System Administrators

- Configure Teams
Admin Panel -> Agents -> Teams
Level I Support
Level II Support
Allow anyone to create tickets
Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets

- Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane
John

- Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken

- Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)

- Configure Help Topics
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset


