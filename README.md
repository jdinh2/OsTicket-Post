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

<p>
<img src="https://i.gyazo.com/a5c971cef87f30745668561f46b27642.png" height="80%" width="80%" alt="Create a team"/>
</p>
<p>

Adjust our user settings, Admin Panel -> Settings -> User Settings -> Make sure Registration required is unchecked to allow anyone to create a ticket. 

</p>
<br />

<p>

<img src="https://i.gyazo.com/1f42d61a26b9bead56a17d3333d13166.png" height="80%" width="80%" alt="Add Agent"/>

</p>

<p>

Now we will create agents, Admin Panel -> Agents -> Add New Agent. In the access tab, you can assign a department and role for the agent. So we will assign the Supreme Admin role and System Administrator department created earlier. In the teams tab we can assign the agent to a team, to either Level I or Level II, and then we can create our agent. 

</p>

<br />

<p>

<img src="https://i.gyazo.com/f16e638511633d1ddfc4250714c97d46.png" height="80%" width="80%" alt="Add Agent"/>

</p>
<p>

After creating some agents we will create users. Users are customers who create tickets when they are having issues. A user is identified with their E-mail address. To create a user go to Agent Panel ->Users->User Directory->Add new.

</p>

<br />

<p>

<img src="https://i.gyazo.com/72719a873ce48b08739e5f279a0941d7.png" height="80%" width="80%" alt="Add Agent"/>

</p>
<p>
  
SLAs Plans provide a length of time in which the help desk is expected to take in order to solve a specific ticket. SLA Plans are created by going to Admin Panel->Manage->SLA Plans. Each SLA has a schedule and within that schedule there is a grace period. For this tutorial I've created SEV-A, SEV-B, SEV-C. In this example SEV-B has a 24/7 and a four hour grace period. SEV-A is 24/7 with a one hour grace period and SEV-C is business hours with an eight hour grace period. 

</p>

<br />

<p>

<img src="https://i.gyazo.com/d003a8591329684bff1048fe0ba76d08.png" height="80%" width="80%" alt="Add Agent"/>

</p>
<p>
  
Help topics help users categorize their tickets. In the example below we have made a help topic for " Password Reset" this can be if customers want to request to reset their password. 


</p>
