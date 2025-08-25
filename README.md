<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://youtu.be/WvzJUFj1EYw)

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

- Configure Roles (for grouping permissions)
- Admin Panel -> Agents -> Roles
- Create Supreme Admin and give them all permissions

<br />
  
<img width="1149" height="571" alt="image" src="https://github.com/user-attachments/assets/6b704daa-02c5-4538-88c9-2054f2379fb3" />

</p>
<br />

- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Admin Panel -> Agents -> Departments
- We're going to choose the Top Level Department to make sure we give full access to this department.
- We will name this department SysAdmins

</p>
<br />

<p>
<img width="1328" height="690" alt="image" src="https://github.com/user-attachments/assets/9c426e46-32d4-44d8-84ba-d2190c5bd1bd" />

</p>
<br />

- Configure Teams
- Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
- Online Banking

</p>
<br />

<p>
<img width="1322" height="708" alt="image" src="https://github.com/user-attachments/assets/3bada3b3-6520-4862-bbbf-6bfdbc486572" />

</p>
<br />

- Allow anyone to create tickets
- Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
- Registration Required: Require registration and login to create tickets

<br />

</p>
<img width="1350" height="762" alt="image" src="https://github.com/user-attachments/assets/3463d795-d385-438e-b5d0-96f9f20b6e1b" />


</p>
<br />

- Configure Agents (workers)
- Admin Panel -> Agents -> Add New
- Jane (Dept: SysAdmins)
- John (Dept: Support)

<br />
</p>
<img width="1354" height="764" alt="image" src="https://github.com/user-attachments/assets/73fe0ac7-dded-4195-a500-d535df468445" />

<img width="1359" height="767" alt="image" src="https://github.com/user-attachments/assets/14c44c4e-43d7-4991-811b-3eb2c2b8dd3f" />


</p>
<br />

- Configure Users (customers)
- Agent Panel -> Users -> Add New
- Karen
- Ken




</p>
<br />

<img width="1362" height="767" alt="image" src="https://github.com/user-attachments/assets/bb45e40c-b3b3-49ec-a08e-c7cb2dcb3807" />

</p>
<br />

- Configure SLA
- Admin Panel -> Manage -> SLA
- Sev-A (Grace Period: 1 hour, Schedule: 24/7)
- Sev-B (Grace Period: 4 hours, Schedule: 24/7)
- Sev-C (Grace Period: 8 hours, Business Hours)


</p>
<br />
<img width="1365" height="767" alt="image" src="https://github.com/user-attachments/assets/a8d2475e-7f25-4d17-8fb5-b595da519757" />
<img width="1365" height="752" alt="image" src="https://github.com/user-attachments/assets/66786fa8-8b9c-4357-b76f-2e7c17ada3fb" />
<img width="1365" height="767" alt="image" src="https://github.com/user-attachments/assets/e70a11e3-833c-4041-a21e-7ecc2e98dfd4" />


</p>
<br />

- Configure Help Topics (For when users create a ticket)
- Admin Panel -> Manage -> Help Topics
- Business Critical Outage
- Personal Computer Issues
- Equipment Request
- Password Reset
- Other



</p>
<br />
<img width="1365" height="767" alt="image" src="https://github.com/user-attachments/assets/bc68e65a-7afb-4fea-b1a0-3eee280aa003" />
<img width="1365" height="767" alt="image" src="https://github.com/user-attachments/assets/967c58fd-c760-4331-8140-6718f365ac04" />
<img width="1365" height="767" alt="image" src="https://github.com/user-attachments/assets/936d0f8c-0871-4d81-8adf-f3b7adf9678f" />
<img width="1365" height="767" alt="image" src="https://github.com/user-attachments/assets/db94fe51-eaa3-48f9-aac9-297614a654f9" />
<img width="1365" height="767" alt="image" src="https://github.com/user-attachments/assets/4facddbb-22d6-42b9-be74-4afda0fc14be" />




</p>
<br />




</p>
<br />
