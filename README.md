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

<p>
<img src="https://i.gyazo.com/324244ae5519924638dad9bac9d58945.png" height="80%" width="80%" alt="Add New Role"/>
</p>
<p>
For this instance, we will create the role "Supreme Admin". Go into the Admin Panel -> Agents -> Roles -> Add New Role. In Permissions, we will enable everything. Do the same for the "Tickets" and "Knowledge Base" tabs. 
  
</p>
<br />
<p>
<img src="https://i.gyazo.com/93e746965e8bf9fcb44cc000c43cafd5.png" height="80%" width="80%" alt="Add New Department"/>
</p>
<p>

Next, we go back to the Admin Panel -> Agents -> Departments -> Add New Department and will add "System Administrators". Default values are fine in this instance. 


</p>
<br />

<p>
<img src="https://i.gyazo.com/bd7792055bfa01e4dc41523a3e46900e.png" height="80%" width="80%" alt="Create a team"/>
</p>
<p>

Now go to Agents -> Teams -> Create a team. We will create Level I and Level II support. 


</p>
<br />



