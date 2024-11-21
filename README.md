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
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DKPhNiy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Inside of OsTicket, different roles for different people are given whether that be a supreme admin, an agent (worker) or a systems administrator, all must be configured to allow certain people with certain privilages and others with limited privliages.
</p>
<br />

<p>
<img src="https://i.imgur.com/RtNAfkE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once roles are established, Teams will need to be made for the roles to be grouped in with different levels of the teams (Level I & II respectively). Each agent will have thier group with others will be sent tickets according to what thier team is to mainly focus on.
</p>
<br />

<p>
<img src="https://i.imgur.com/tusnM1O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
And finally, the service level agreement and help topics must be configured. To understand when the service must be completed by both the customer and the service provider. The help will determine what Department the ticket is routed to which will determine which Agents have access to the ticket.
</p>
<br />
