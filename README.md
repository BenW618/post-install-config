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

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After logging into the osTicket website, I switched to the Admin panel to create a role. Under the “Agents” tab, I created a role called “Supreme Admin”.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating a role, I switched over to the “Departments” section. I then created a department called “System Administrators”.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating the department, I switched over to the “Teams” section. Next I created a team called “Level II Support” and I added myself to the members section.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating a team, I switched over to the “Agents” section. Next, I created two fake agents named Jane Doe and John Doe. I put Jane Doe in the System Administrators and Support department as a Supreme Admin. I also put this agent on the Level II Support Team. I put John Doe in the Support Department as a support agent.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating my agents, I switched over to the Agent Panel. From there, I clicked the “Users” tab and created two fake users named Ken and Karen. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I switched back to the Admin Panel and clicked the “Managers” tab. I then created three SLAs named SEV-A, SEV-B, and SEV-C. SEV-A had an active grace period of 1 hour and the schedule was 24/7. SEV-B had an active grace period of 4 hours and the schedule was 24/7. SEV-A had an active grace period of 8 hours and the schedule was M-F ; 8AM-5PM.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating the SLAs, I switched over to the “Help Topics” section. Then, I created four help topics. There was a “Business Critical Outrage”, “Personal Computer Issues”, “Equipment Request”, and “Password Reset”.
</p>
<br />
