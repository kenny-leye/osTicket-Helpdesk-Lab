<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

## osTicket - Post-Install Configuration ##
> This project outlines a post-install configuration demonstration of the open-source help desk ticketing system osTicket.
 - 🔗 Admin & Agent Login Page: `http://localhost/osTicket/scp/login.php`
 - 🔗 End User's osTicket Page: `http://localhost/osTicket` <br />
---

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b>

<h2>Post-Install Configuration Objectives</h2>

1. Configure Roles ✔️
  - Grouping Permissions
    > Admin Panel -> Agents -> Roles, create 'Supreme Admin' Role
2. Configure Departments ✔️
  - Ticket Visibility, Help Desk vs SysAdmins vs Networking 
    > Admin Panel -> Agents -> Departments, create 'SysAdmins' Department
3. Configure Teams ✔️
  - Pull Agents from different Departments 
    > Admin Panel -> Agents -> Teams, create 'Online Banking' Team
4. Allow all to create a ticket ✔️
    > Admin Panel -> Settings -> User Settings, uncheck 'unregistered users can create tickets' 
5. Configure Agents 'empolyees' & Configure Users 'customers' ✔️
  - Jane Doe, Department: SysAdmins & John Doe, Department: Support
    > Admin Panel -> Agents -> Add New
  - Ken & Karen
    > Agent Panel -> Users -> Add New
6. Configure SLA ✔️
  - Sev-A, Grace Period: 1 hour, Schedule: 24/7
  - Sev-B, Grace Period: 4 hours, Schedule: 24/7
  - Sev-C, Grace Period: 8 hours, Schedule: Business Hours
     > Admin Panel -> Manage -> SLA
7. Configure Help Topics for Users creating tickets ✔️
  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request
  - Password Reset
  - Other
    > Admin Panel -> Manage -> Help Topics
---
<h2>Configuration Steps</h2>

<img src="Screenshot 2026-09-18 012420.png"/>
<img src="Screenshot 2026-09-18 012625.png"/>
<img src="Screenshot 2026-09-18 012639.png"/>


1️⃣ Configure Roles, Departments, and Teams ⤵️
> 1. To group permissions, sign in to Admin Login Page. Follow path Admin Panel -> Agents -> Roles, click `Add New Agent`. Enter **Name**, **Email**, and check desired permissions on next tab.
> 2. To configure ticket visibility, follow path Admin Panel -> Agents -> Departments, click `Add New Department`. Choose **Parent** department from dropdown, fill out **Name**, and select **Type**. Configure other optional department settings if needed. 
> 3. To assign different Agents to specific teams within department and roles, follow path Admin Panel -> Agents -> Teams,  click `Add New Team`. Enter **Name** and **Status**.
---
<img src="Screenshot 2026-09-18 012710.png"/>
<img src="Screenshot 2026-09-18 012757.png"/>


2️⃣ Configure User Settings, Agents, and End Users ⤵️
> 1. To allow anyone the ability to create and submit a ticket, follow path Admin Panel -> Settings -> User Settings and ensure `Require registration and login to create tickets` box is unchecked.
> 2. To configure Agents follow path Admin Panel -> Agents -> click `Add Agent`. Enter **Name**, **Email Address**, and **Username**. Click `Set Password`, Uncheck `Send the agent a password reset email` to set Agents password and click `Update`. Assign desired Access, Permissions and/or Teams by clicking in corresponding tabs.
> 3. To configure Users follow path Agent Panel -> Users -> `Add User`. Enter user's **Email** and **Name**.
---
<img src="Screenshot 2026-09-18 012820.png"/>
<img src="Screenshot 2026-09-18 012912.png"/>

3️⃣ Configure Service Level Agreements and Help Topics 🏁
> 1. To create new SLA follow path Admin Panel -> Manage -> SLA, click `Add New SLA Plan`. Enter **Name**, **Grace Period**, and select **Status**.
> 2. To configure Help Topics for users creating tickets follow path Admin Panel -> Manage -> Help Topics, click `Add New Help Topic`. Enter **Topic**, select **Status** and **Type**.
---
