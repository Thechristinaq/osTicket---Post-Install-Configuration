<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. This lab is part 2 to the "OsTicket-Prerequisites and Installation" lab<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Step 1: Configure Roles, Departments & Teams
- Step 2: Allow Users to Create Tickets
- Step 3: Configure Agents and Users
- Step 4: Configure SLA
- Step 5: Configure Help Topics

<h2>Configuration Steps</h2>

Step 1: Configure Roles, Departments & Teams

- First, log into your osTicket browser and make sure you are in the admin panel (If it shows the agent panel on the top, it means you are in the admin panel which is what we want in this step, you can go between admin and agent panels this way)
- We are going to add a role called "Supreme Admin" in which they will have all permissions and access to do every task, click agents, roles, add new role
  
![image](https://github.com/thechristinaq/Post-Install-Configuration-/assets/165831241/3b68903b-bb13-41bd-b630-9a4babf17225)

- Check all of the boxes within the tickets, tasks, knowledgebase tabs and click add role 

![image](https://github.com/thechristinaq/Post-Install-Configuration-/assets/165831241/5c9a12e9-0963-42a3-9368-317ec9c31edb)

- Head over to departments and create a System Administrators department 

![image](https://github.com/thechristinaq/Post-Install-Configuration-/assets/165831241/4dff0106-b786-4a15-83b7-e8fddd6f2cc1)

- Create a Level II Support team in teams

![image](https://github.com/thechristinaq/Post-Install-Configuration-/assets/165831241/f5fe30ba-d00f-4895-add2-0e8afc90cecf)


Step 2: Allow Users to Create Tickets 

Within your admin panel, click settings, user settings, and check the box "registration required: Require registration and login to create tickets"

![image](https://github.com/thechristinaq/Post-Install-Configuration-/assets/165831241/85760d15-19a5-4fe5-9cde-2be85a9f65d9)


Step 3: Configure Agents and Users
- In the Admin panel, click agents, add new, and create our agents "Jane" and "John"

![image](https://github.com/thechristinaq/Post-Install-Configuration-/assets/165831241/9694589d-ea30-4a14-add8-e52486d99414)

![image](https://github.com/thechristinaq/Post-Install-Configuration-/assets/165831241/c7ea92f6-2066-489c-a4ab-54dea8677188)

- We will create our users and this will be done in the Agent Panel (once you clicked agent portal, it will become admin portal as mentioned in step 1), inside the agent portal, click users, add new and create our users "Karen" and "Ken" 

![image](https://github.com/thechristinaq/Post-Install-Configuration-/assets/165831241/2b86ae60-eae5-4ba2-8c5c-d9af2010afd9)

![image](https://github.com/thechristinaq/Post-Install-Configuration-/assets/165831241/b16fc1e1-96d8-459f-a488-6476dfc8846e)


Step 4: Configure SLA
- We will head back over to the admin panel, click manage, SLA 






  
