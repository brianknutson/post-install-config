<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This demonstration shows how I did post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Deparments 
- Configure Teams
- Configure Agents (Workers) 
- Configure Users (Customers)
- Configure SLAs (Service-level agreement)
- Configure Help Topics 

<h2>Configuration Steps</h2>

Step 1 - First, I needed to configure different roles. Roles are used to make different grouping permissions to give to certain people. To achieve this, I went to the "Admin Panel" then "Agents" then "Roles". Next, I clicked on "Add New Role". I named this new role as "Supreme Admin". Then I went to "Permissions" and under "Tickets", "Task", and "Knowledgebase" check everything. Afterward, I clicked "Add Role". The "Supreme Admin" role showed up in the "Roles" tab.

![image alt](https://github.com/brianknutson/post-install-config/blob/f78dcb09213c664b1e414b3ed9e989efc67db292/1.1.PNG)

![image alt](https://github.com/brianknutson/post-install-config/blob/f78dcb09213c664b1e414b3ed9e989efc67db292/1.2.PNG)

![image alt](https://github.com/brianknutson/post-install-config/blob/f78dcb09213c664b1e414b3ed9e989efc67db292/1.3.PNG)

![image alt](https://github.com/brianknutson/post-install-config/blob/f78dcb09213c664b1e414b3ed9e989efc67db292/1.4.PNG)

![image alt](https://github.com/brianknutson/post-install-config/blob/f78dcb09213c664b1e414b3ed9e989efc67db292/1.5.PNG)

![image alt](https://github.com/brianknutson/post-install-config/blob/f78dcb09213c664b1e414b3ed9e989efc67db292/1.6.PNG)

![image alt](https://github.com/brianknutson/post-install-config/blob/f78dcb09213c664b1e414b3ed9e989efc67db292/1.7.PNG)

Step 2 - I configured the departments next, which will affect ticket visibility. This will let me allow departments to have different levels of access to the tickets. To configured the departments, I went to the "Admin Panel" then "Agents" then "Departments". After getting to the "Departments" page, I clicked on "Add New Department". I created a new top-level department called "SysAdmins". None of the other settings was altered. Finally, I scrolled down and clicked on "Create Dept". Now the "SysAdmins" department shows up at the "Departments" page. 

![image alt](https://github.com/brianknutson/post-install-config/blob/835a49d4d2d79c058be4d9b8d7894b7e5e0f4e93/2.1.PNG)

![image alt](https://github.com/brianknutson/post-install-config/blob/835a49d4d2d79c058be4d9b8d7894b7e5e0f4e93/2.2.PNG)

![image alt](https://github.com/brianknutson/post-install-config/blob/835a49d4d2d79c058be4d9b8d7894b7e5e0f4e93/2.3.PNG)

![image alt](https://github.com/brianknutson/post-install-config/blob/835a49d4d2d79c058be4d9b8d7894b7e5e0f4e93/2.4.PNG)


Step 3 - Next, I configured teams. Teams allow people from different departments to have the same level of access to a particular thing such as a ticket. To configure teams, I went to the "Admin Panel" then "Agents" then "Teams". Next, I clicked on "Add New Team". In this demonstration, the name of the team will be "Online Banking". Finally, I clicked on "Create Team". 

![image alt](https://github.com/brianknutson/post-install-config/blob/c7faf5c83031f36ec5bb9770bcae609b5ac9b791/3.1.PNG)

![image alt](https://github.com/brianknutson/post-install-config/blob/c7faf5c83031f36ec5bb9770bcae609b5ac9b791/3.2.PNG)

Step 4 - I wanted to allow anyone to create tickets, which will allow unregistered users to be able to create tickets. Therefore, it will allow my end users to be able to create tickets without having an account. To accomplish this, I went to the "Admin Panel" then "Settings" then "Users". I made sure the "Registration Required" setting is unchecked.  

![image alt](https://github.com/brianknutson/post-install-config/blob/77aef9b752da7d75e3911aac8ef013b81fb709f5/Capture.PNG)

Step 5 - Next, I added some agents/workers. I went to "Admin Panel" then "Agents". Next, I clicked on "Add New Agent". In this demonstration, two agents were created. First, Jane Doe whose "Primary Department" was "SysAdmin" and "Role" was "Supreme Admin". She was also in the "Online Banking Team". Once the information has been filled out, I scrolled down and clicked "Create". The next agent was John Doe whose "Primary Department" was "Support" and "Role" was "View Only". 

![image alt](https://github.com/brianknutson/post-install-config/blob/6672acf6a38580d85630640bef58f9481726721a/3.51.PNG)

![image alt](https://github.com/brianknutson/post-install-config/blob/6672acf6a38580d85630640bef58f9481726721a/3.52.PNG)

![image alt](https://github.com/brianknutson/post-install-config/blob/6672acf6a38580d85630640bef58f9481726721a/3.53.PNG)

![image alt](https://github.com/brianknutson/post-install-config/blob/6672acf6a38580d85630640bef58f9481726721a/3.54.PNG)

Step 6 - I needed to add a user/customer. So I went to "Agent Panel" then "Users" then clicked on "Add New". In this demonstration, the user will be Karen Doe. Once the info was filled in, I clicked on "Add User". 

![image alt](https://github.com/brianknutson/post-install-config/blob/adb8a9b57955ac7a2a5ad3a842ee952b1f3c7c58/3.61.PNG)

![image alt](https://github.com/brianknutson/post-install-config/blob/adb8a9b57955ac7a2a5ad3a842ee952b1f3c7c58/3.62.PNG)

Step 7 - Next, I configured some service-level agreements (SLAs), which is a contract between the service provider and a customer that defines the level of service expected from the provider such as quality standards and response time. Therefore, it affects which tickets should be prioritized first and how much time you have to finish a ticket. To configured SLAs, I went to "Admin Panel" then "Manage" then "SLA". Next, I clicked on "Add New SLA Plan". In this demonstration, three SLAs was created. First was be "Sev-A" with a "Grace Period" of 1 hour with a schedule of 24/7. This means the ticket was to be considered overdue in an hour even outside of normal business hours. Once the information was filled in, I clicked on "Add Plan". The next SLA was "Sev-B" with a "Grace Period" of 4 hours with a schedule of 24/7. The final SLA was "Sev-C" with a "Grace Period" of 8 hours with normal business hours. 

![image alt](https://github.com/brianknutson/post-install-config/blob/84f5f5ca628b21645dc99822d3de05f4eddd1f34/7.1.PNG)

![image alt](https://github.com/brianknutson/post-install-config/blob/84f5f5ca628b21645dc99822d3de05f4eddd1f34/7.2.PNG)

![image alt](https://github.com/brianknutson/post-install-config/blob/84f5f5ca628b21645dc99822d3de05f4eddd1f34/7.3.PNG)

Step 8 - Finally, I configureed some help topics, which help explain what issue users may be facing when creating a ticket. To make help topics, I went to "Admin Panel" then "Manage" then "Help Topics". Next, I clicked on "Add New Help Topic". I created five different help topics. The first four was "Business Critical Outage", "Personal Computer Issues", "Password Reset", and "Other". All four had the "Parent Topic" as "Report a Problem". Once I was done setting up one of the help topics, I clicked on "Add Topic" to add it to the list of help topics. The fifth topic was called "Equipment Request" with the "Parent Topic" as "General Inquiry".   

![image alt](https://github.com/brianknutson/post-install-config/blob/658f955e78ec6293a69215458f329c386bb27cfc/8.1.PNG)

![image alt](https://github.com/brianknutson/post-install-config/blob/658f955e78ec6293a69215458f329c386bb27cfc/8.2.PNG)

![image alt](https://github.com/brianknutson/post-install-config/blob/658f955e78ec6293a69215458f329c386bb27cfc/8.3.PNG)
