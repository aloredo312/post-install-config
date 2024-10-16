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

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
<img width="681" alt="Add_supreme_admin_role" src="https://github.com/user-attachments/assets/53a64307-2b11-4542-a937-83722a38fa10"> <img width="676" alt="adding_permissions" src="https://github.com/user-attachments/assets/ec248e9c-c5de-4560-96e5-6884cfe12c04">
</p>
<p>
To configure roles you have to be on the admin panel, to go to the admin panel go to the top right and you should be able to switch from "agent panel" to "admin panel". Then to add a new role, you will click on the "agents" tab. Finally click on "roles". You should see a list of roles show up, to add a new role click on "add new role" on the right, it will ask for a name, and to add permissions click on the permissions tab and you can check whatever kind of acces you want to give to the role you created. Once finished click on "add role" and it will show up on the list of roles.
</p>
<br />

<p>
<img width="675" alt="add_new_dept" src="https://github.com/user-attachments/assets/8ef317ac-5730-40ea-b914-67a90ece4d5f"> <img width="665" alt="dept_settings" src="https://github.com/user-attachments/assets/b7a2f139-6134-4664-b274-ec1bfb394711">
</p>
<p>
We can do the same with Departments. In the same admin panel if we go to the agents tab and then click on "departments", we can see a list of departments. To add a new department click on "add new department". It will ask for a bunch of settings to fill out for the department you are creating for example Department info, outgoing email and autoresponder settings, and if you click on the access tab you can add agents who will be a part of that department. Once finished filling everything out just click on "create dept".
</p>
<br />

<p>
<img width="678" alt="configure_teams" src="https://github.com/user-attachments/assets/4bb050c6-9c18-4d78-895e-e4ce37afb89d"> <img width="672" alt="adding_new_team" src="https://github.com/user-attachments/assets/bde4a619-a49a-437b-aaba-c4bb13812226">
</p>
<p>
To configure teams in the same admin panel we can go to agents and then click on "teams". A list of teams will pop up, and to add a new team click on "add new team". Fill out the information for the new team and you can add agents to the team by clicking on the members tab. Once finished click on "create team" and it will be created.
</p>
<br />

<p>
<img width="665" alt="user_settings" src="https://github.com/user-attachments/assets/9a4af421-a639-41da-ab20-eb59da45191f">
</p>
<p>
To allow anyone to create tickets we go on the admin panel, then click on the "settings" tab, go to users. Under settings you will see General settings and Authentication settings that you can change.
</p>
<br />

<p>
<img width="668" alt="adding_new_agent_account_info" src="https://github.com/user-attachments/assets/beb94a02-631c-4d35-bbc7-37be33e2eb1f">
<img width="664" alt="new_agent_access_settings" src="https://github.com/user-attachments/assets/916a25a2-c6cf-421b-b745-a51ca919c0b1">
<img width="665" alt="new_agent_permissions" src="https://github.com/user-attachments/assets/d2fc5e94-cd3f-4c2f-8f5c-beae43a349b8">
<img width="666" alt="new_agent_assign_teams" src="https://github.com/user-attachments/assets/85a780e2-6ade-4b2c-ab88-3c1687af06ff">
</p>
<p>
To add and configure agents we need to be in the admin panel, and go to agents and then we will click on "add new". Fill out the info on the account tab for the new agent. Their name, email address, their username and their password. On the access tab you can select the department they're allowed to acces and their role. In the permissions tab you can select what abilities they are able to do, create/delete new user or manage user information and more. In the teams tab you can assign agents to a team. Once finished click on create and they will be in the agents list.
</p>
<br />

<p>
<img width="667" alt="switching_agent_panel" src="https://github.com/user-attachments/assets/08777d35-6146-4aa4-9912-f9b3c898bc72">
<img width="456" alt="create_a_user" src="https://github.com/user-attachments/assets/c6390d67-26bc-47d7-ad85-04d92e2493b7">
</p>
<p>
To add users we need to switch over to the agent panel. To do this go to the upper right where it says agent panel and click it. Then to add new user go to the "users" tab click it, and then click on "add new". An email and a full name will be required to create a user. Click on create user and you will see the user show up on the list.
</p>
<br />

<p>
<img width="665" alt="configuring_sla" src="https://github.com/user-attachments/assets/6c1cf913-61c4-42ed-b972-1c3516732e6f">
</p>
<p>
To configure SLA  we need to go back to the admin panel. Then we will go to the "manage" tab, then click on SLA. You can name the plan (Sev-A, Sev-B, Sev-C). Check the circle wether it should be active or disabled, Fill the grace period in hours and select the schedule from the options in the drop down menu. Once finished with the settings click add plan.
</p>
<br />

<p>
<img width="664" alt="configure_help_topics" src="https://github.com/user-attachments/assets/61a048fa-bd91-4bcf-be92-e9c368792c9a">
</p>
<p>
To configure Help Topics, you need to go to be on the admin panel, click on the manage tab, and then click on help topics. To add new help topics click on the "add new help topics". Then you will fill out the Help topic information, Name the topic, choose the status, the type, and the parent topic. Once everything is filled out click on the "add topic" button.
</p>
<br />
