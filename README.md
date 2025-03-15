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

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/QFcxUw1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/j9tnCDh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/OBXCjxJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
<img src="https://i.imgur.com/BVofBUl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<p>
<img src="https://i.imgur.com/E49EJvf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<p>
<img src="https://i.imgur.com/Jzr0mJ4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<p>
<img src="https://i.imgur.com/RRARmUl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1 - First, we need to configure differenet roles. Roles are used for making different grouping permissions to give to certain people. To achieve this, go to the "Admin Panel" then "Agents" then "Roles". Next click on "Add New Role". Name this new role as "Supreme Admin". Then go to the "Permissions" and under "Tickets", "Task", and "Knowledgebase" check everything. Afterwards, click "Add Role". The "Supreme Admin" role should show up in the "Roles" tab. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DVQ45gL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/mrckxNx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/j5BtGXI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2 - Now let's configure the departments, which will affect ticket visibility. This will let you allow departments have different levels of access to the tickets. To configure the departments, go to the "Admin Panel" then "Agents" then "Departments". After getting to the "Departments" page, click on "Add New Department". In this tutorial, a top level department called "SysAdmins". None of the other settings will be altered. Finally, scroll down and click on "Create Dept".  
Admin Panel -> Agents -> Departments
</p>
<br />

<p>
<img src="https://i.imgur.com/NfqyEBi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/wFETi6T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 3 - Now let's configure teams. Teams allow people from different departments to have the same level of access to a particular thing such as a ticket. To configure teams, go to the "Admin Panel" then "Agents" then "Teams". Next click on "Add New Team". In this tutorial, the name of the team will be "Online Banking". Finally click on "Create Team". 
</p>
<br />

<p>
<img src="https://i.imgur.com/UF7ZIUD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 4 - Now let's allow anyone to create tickets, which will allow unregistered users to be able to create tickets. Therefore, it will allow your end users to be able to create tickets without having an account. To accomplish this, go to the "Admin Panel" then "Settings" then "Users". Make sure the "Registration Required" setting is uncheck.  
</p>
<br />

<p>
<img src="https://i.imgur.com/ECeBXEL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/cmpEnbW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/T213Tpn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/jHwatLo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 5 - Let's add some agents/workers. Go to "Admin Panel" then "Agents". Next click on "Add New Agent". In this tutorial, two agents will be created. First, Jane Doe whose "Primary Department" will be "SysAdmin" and "Role" will be "Supreme Admin". She will also be in the "Online Banking Team". Once the information has been filled out, scroll down and click "Create". The next agent will be John Doe whose "Primary Department" will be "Support" and "Role" will be "View Only". 
</p>
<br />

<p>
<img src="https://i.imgur.com/2ppTspZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/TCLt2jV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 6 - Now let's add an user/customer. Go to "Agent Panel" then "Users" then click on "Add New". In this tutorial, the user will be Karen Doe. Once the info is filled, click on "Add User". 
</p>
<br />

<p>
<img src="https://i.imgur.com/XH0Gb70.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/3JVn8He.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/3RRJlxo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>  
Step 7 - Next let's configure service level agreement (SLA), which is a contract between the service provider and a customer that defines the level of service expected from the provider such as quality standards and response time. However, in this case, it affects which tickets should be prioritize first and how much time you have to finish a ticket. To configure SLA, go to "Admin Panel" then "Manage" then "SLA". Next click on "Add New SLA Plan". In this tutorial, three SLAs will be created. First will be "Sev-A" with a "Grace Period" of 1 hour with a schedule of 24/7. This means the ticket will be considered overdue in a hour even outside of under normal business hours. Once the information is filled, click on "Add Plan". The next SLA is "Sev-B" with a "Grace Period" of 4 hours with a schedule of 24/7. The final SLA is "Sev-C" with a "Grace Period" of 8 hours with normal business hours. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
