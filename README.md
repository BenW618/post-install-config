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

![Screenshot (13)](https://github.com/BenW618/post-install-config/assets/140227052/6115d4d1-b43a-4b08-8d9e-97fdc7a816b5)

</p>
<p>
After logging into the osTicket website, I switched to the Admin panel to create a role. Under the “Agents” tab, I created a role called “Supreme Admin”.
</p>
<br />

![Screenshot (15)](https://github.com/BenW618/post-install-config/assets/140227052/997e1be5-09b3-4a4c-8b7c-cbd58417416c)

</p>
<p>
After creating a role, I switched over to the “Departments” section. I then created a department called “System Administrators”.
</p>
<br />

![Screenshot (16)](https://github.com/BenW618/post-install-config/assets/140227052/df51f6b7-5103-42ae-bdce-470a23e3e9bc)

</p>
<p>
After creating the department, I switched over to the “Teams” section. Next I created a team called “Level II Support” and I added myself to the members section.
</p>
<br />

![Screenshot (18)](https://github.com/BenW618/post-install-config/assets/140227052/30dadf23-b7ed-45b0-9007-02af865a456a)

</p>
<p>
After creating a team, I switched over to the “Agents” section. Next, I created two fake agents named Jane Doe and John Doe. I put Jane Doe in the System Administrators and Support department as a Supreme Admin. I also put this agent on the Level II Support Team. I put John Doe in the Support Department as a support agent.
</p>
<br />

![Screenshot (20)](https://github.com/BenW618/post-install-config/assets/140227052/80c2cd4f-58d1-4857-b56c-37b0a4ef28ef)

</p>
<p>
After creating my agents, I switched over to the Agent Panel. From there, I clicked the “Users” tab and created two fake users named Ken and Karen. 
</p>
<br />

![Screenshot (22)](https://github.com/BenW618/post-install-config/assets/140227052/3d68a7a7-7dc4-4c41-94bc-03d89538aa13)

</p>
<p>
Next, I switched back to the Admin Panel and clicked the “Managers” tab. I then created three SLAs named SEV-A, SEV-B, and SEV-C. SEV-A had an active grace period of 1 hour and the schedule was 24/7. SEV-B had an active grace period of 4 hours and the schedule was 24/7. SEV-A had an active grace period of 8 hours and the schedule was M-F ; 8AM-5PM.
</p>
<br />

![Screenshot (24)](https://github.com/BenW618/post-install-config/assets/140227052/7c376b5c-b872-4c72-aeb3-e2896f629e77)

</p>
<p>
After creating the SLAs, I switched over to the “Help Topics” section. Then, I created four help topics. There was a “Business Critical Outrage”, “Personal Computer Issues”, “Equipment Request”, and “Password Reset”.
</p>
<br />
