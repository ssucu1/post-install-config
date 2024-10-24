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

- Item 1: Admin Panel Setup
- Item 2: Create Departments, Teams
- Item 3: Congfigure Agents (workers)
- Item 4: Configure SLA
- Item 5: Configure Help Topics

<h2>Configuration Steps</h2>

<p>
Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin
</p>
<br />

![image](https://github.com/user-attachments/assets/16999d20-003e-4ec6-b760-af5b473ff168)

<p>
  Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins

</p>
<br />

![image](https://github.com/user-attachments/assets/a449912f-e4d2-49f3-b71d-2ba4be81dfb0)

<p>
  Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking

</p>
<br />

![image](https://github.com/user-attachments/assets/75406841-baa1-495f-9e7b-12f634c0d081)

<p>
Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)
</p>

![image](https://github.com/user-attachments/assets/af15b328-bb9d-43b5-8b8a-57431960a588)

<p>
  Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other
</p>
<br/>

![image](https://github.com/user-attachments/assets/cda4a52d-945b-490f-aa90-d6e5a7712125)


