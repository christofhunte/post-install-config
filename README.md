<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This project outlines the post-install configuration of the open-source help desk ticketing system osTicket that I created.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles (for grouping permissions)
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Configure Teams
- Allow anyone to create tickets
- Configure Agents, Users, SLA, and Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/fOmiEF3.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/CpzZXAy.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
After opening the osTicket in the Windows Virtual Machine created from the last project, I logged into the Admin panel and configured all access for a new role I created called "Supreme Admin". I gave this role permissions such as Assign, Close, Create, Delete, Edit etc. I then created a new department called "SysAdmins" and gave it "Top Level Department" status.
</p>
<br />

<p>
<img src="https://i.imgur.com/aNqVwOh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I then confingured Teams in the Agents tab such as "Online Banking" and then enabled required registration and login for users to create tickets in the user settings. I then created two new agents and assigned one to the "SysAdmins" department and the other to the regular "Support" department. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
