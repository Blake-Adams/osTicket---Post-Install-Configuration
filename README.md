<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Install and configure osTicket as a practical demonstration of IT Service Management (ITSM) tools in action.
- Implement role-based access control (RBAC) by defining roles, departments, and teams to simulate organizational support structures.
- Establish Service Level Agreements (SLAs) to enforce ticket response times and replicate enterprise-grade support policies.
- Customize user access and help desk topics to streamline ticket creation, improve workflow efficiency, and simulate real-world support scenarios.

<h2>Configuration Steps</h2>

<p>
<img width="1149" height="571" alt="image" src="https://github.com/user-attachments/assets/6b704daa-02c5-4538-88c9-2054f2379fb3" />

</p>
<br />

- Configure Roles (for grouping permissions)
- Admin Panel -> Agents -> Roles
- Create Supreme Admin and give them all permissions

</p>
<br />

<p>
<img width="1328" height="690" alt="image" src="https://github.com/user-attachments/assets/9c426e46-32d4-44d8-84ba-d2190c5bd1bd" />

</p>
<br />

- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Admin Panel -> Agents -> Departments
- We're going to choose the Top Level Department to make sure we give full access to this department.
- We will name this department SysAdmins

</p>
<br />

<p>
<img width="1322" height="708" alt="image" src="https://github.com/user-attachments/assets/3bada3b3-6520-4862-bbbf-6bfdbc486572" />

</p>
<br />

- Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking

</p>
<img width="1350" height="762" alt="image" src="https://github.com/user-attachments/assets/3463d795-d385-438e-b5d0-96f9f20b6e1b" />


</p>
<br />
Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
Registration Required: Require registration and login to create tickets 


</p>
<br />


</p>
<br />


</p>
<br />


</p>
<br />


</p>
<br />


</p>
<br />
