<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLAs
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/mVPaq3y.png" height="40%" width="40%" alt="osticket-loginpage"/>
</p>
<p>
Log in to your Help Desk portal with the information you created during the first phase
</p>
<br />
<br />

<p>
<img src="https://i.imgur.com/JSi2aUS.jpg" height="50%" width="50%" alt="osticket main page"/>
</p>
<p>
In your portal ensure click in the top right to get to the admin panel to make sure you are running as an Admin and not an Agent. </p>
<p>
</p>
<br />
<br />

<p><h3>Configure Roles </p></h3>
<p>
<img src="https://i.imgur.com/S0l9LzL.jpg" height="50%" width="50%" alt="New roles configuration"/>
</p>
<p>
On the Admin Panel, go to Agents, hit "Roles" and "add new role" on the right hand side
</p>
<br />
<br />


<p>
<img src="https://i.imgur.com/pPr54Pz.png" height="50%" width="50%" alt="New roles configuration"/>
</p>
<p>
Name the role Supreme Admin, then click on the permissions tab
</p>
<br />
<br />


<p>
<img src="https://i.imgur.com/AJDqDoa.png" height="40%" width="40%" alt="New roles configuration"/>
</p>
<p>
In this tab you can assign certain permissions for each role you create. For the Supreme Admin, check every box so it has access to everything.
</p>
<br />
<br />



<p><h3>Configure Departments </p></h3>
<p>
<img src="https://i.imgur.com/EJ2Hp3w.jpg" height="50%" width="50%" alt="New Department configuration"/>
</p>
<p>
On the Agents panel, click on Departments and click on "Add New Department."
</p>
<br />
<br />



<p>
<img src="https://i.imgur.com/OdBxghg.png" height="50%" width="50%" alt="New department configuration"/>
</p>
<p>
Name it "System Administrators" and keep all other settings the same. 
</p>
<br />
<br />


<p><h3>Configure Teams </p></h3>
<p>
<img src="https://i.imgur.com/6EhQjGW.jpgg" height="50%" width="50%" alt="New Teams configuration"/>
</p>
<p>
Click on Teams and click "Add New Team" - Add a "New Team", name it Level II Support, then click on "Create Team"
</p>
<br />
<br />


<p>
<img src="https://i.imgur.com/NcpXWVe.png" height="50%" width="50%" alt="New Teams configuration"/>
</p>
<p>
</p>
<br />
<br />


<p><h3>Allow anyone to create a ticket </p></h3>
<p>
<img src="https://i.imgur.com/B2wO1nf.png" height="50%" width="50%" alt="New tickets creation"/>
</p>
<p>
Admin Panel -> Settings -> User Settings - On "Registration Required" leave that unchecked so folks can create tickets anonymously if needed
</p>
<br />
<br />

<p><h3>Configure Agents (workers)</p></h3>
<p>
<img src="https://i.imgur.com/etG9waP.png" height="50%" width="50%" alt="New agents configuration"/>
</p>
<p>
Go to Agents > Add New Agent. </p>
<p>
Create the agent "jane doe" and set the Agent's password to "Password1" and uncheck the boxes to prevent the Agent from needing to reset password or change password after login
</p>
<br />
<br />


<p>
<img src="https://i.imgur.com/ak91yZ7.png" height="40%" width="40%" alt="New agents configuration"/>
</p>
<p>
Go to the access tab, to set the agents Primary Department.
</p>
<br />
<br />


<p><h3>Configure Users (customers) </p></h3>

<p>
<img src="https://i.imgur.com/x3XsjLN.png" height="50%" width="50%" alt="New users configuration"/>
</p>
<p>
Switch to the agent panel in the top right and then go to Users > Add New User. Users are creators of the tickets such as employees in the office who need computer help etc.
</p>
<br />
<br />


<p><h3>Configure SLA (Service Level Agreements) </p></h3>
<p>
<img src="https://i.imgur.com/lU6J8kH.png" height="50%" width="50%" alt="New SLA configuration"/>
</p>
<p>
In the Admin Panel click -> Manage -> SLA - Service Level Agreements provide a length of time for when tickets are expected to be closed. They can also be assigned to specific Departments.
</p>
<br />
<br />


<p><h3>Configure Help Topics </p></h3>
<p>
<img src="https://i.imgur.com/5ZngelB.jpg" height="50%" width="50%" alt="New Help Topics configuration"/>
</p>
<p>
In the Admin Panel click > Manage -> Help Topics > Add New Help Topic
</p>
<br />
<br />
You will create four different Help Topics based on the potential severity a ticket could have, from lowest to highest priority - "Business Critical Outage" - "Personal Computer Issues" "Equipment Reset" "Password Reset"
</p>
<br />
<br />
<p>
<img src="https://i.imgur.com/RGVtVMd.png" height="50%" width="50%" alt="New Help Topics configuration"/>
</p>
<p>
Example of Adding a New Help Topic
</p>
<br />
<br />

<p>
This is the end of the lab
</p>
<br />
<br />
<br />
<br />
