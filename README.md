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
- Configure Agents(workers)
- Configure Users(Customers)
- Configure SLA
- Configure Help Topics 

<h2>Configuration Steps</h2>


<p>
When setting up osTicket by default you are the Admin user. The Admin panel is where you have root-like controls over the entire system. The agent panel is a user of the ticketing system, you can think of an agent as the workers, the people who are going to work the tickets that are being submitted by end users as well as other staff members. NOTE: As you can see in the top right corner you know the view is Admin because you see the option to view in the Agent window.  
</p>
<br />

![image](https://github.com/Algoroy27/post-install-config/assets/137920855/e7ccc97e-0f1c-4d2c-964a-51869076b070)

<p>
1. Configuring roles. Roles are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access. An unlimited number of roles can be created and assigned to Agents with access to various departments.
</p>
<br />

![image](https://github.com/Algoroy27/post-install-config/assets/137920855/f54bb3f4-0fea-4301-bbf8-3c7c222c06db)

<p>
Here we created a super Admin that has permission to everything within the platform. Next, we are going to configure some departments. As you can see we have created a Sys Admin department, along with a Break Glass Department.  
</p>

![image](https://github.com/Algoroy27/post-install-config/assets/137920855/aae975ee-f9a3-40aa-a09f-e0e3ea5e02ec)

![image](https://github.com/Algoroy27/post-install-config/assets/137920855/1afcc109-53fc-40c5-a7f2-52c5eca41d66)

<br>
Next, we need to configure teams. Teams are important when special tickets come into the queue. There may be keep personnel that is needed to handle tickets that may require a level 2 helpdesk tech to solve or there are certain teams that have to be formed that span across different departments and their input is needed to meet requirements. 

![image](https://github.com/Algoroy27/post-install-config/assets/137920855/19e783f7-d59e-477f-9ec7-e0ba8457b0b5)


Here I created a level 2 support team.

Now we need to allow anyone to create a ticket 

![image](https://github.com/Algoroy27/post-install-config/assets/137920855/1b089faf-27b2-4970-a903-00a77039e93d)


Let's add some agents to our help desk system

![image](https://github.com/Algoroy27/post-install-config/assets/137920855/52e7d46d-48f3-4470-91ea-2f0eb4f6a4d4)

When adding agents you can assign them roles and permissions as well as what team you want them on. 

Next, we going to add users to our help desk system, they are essentially the customers of the platform, different employees from various departments


To add users we need to click on the agent view and then select the user tab.

![image](https://github.com/Algoroy27/post-install-config/assets/137920855/937b5279-e22c-4cb9-bed9-e0e9de9497ab)


