# post-install-config
Here's a similar passage with different content:

---

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Configuration Guide after Installation</h1>
This guide illustrates the post-installation configuration steps for osTicket, the open-source help desk ticketing system.<br />

<h2>Environments and Technologies Utilized</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating System Utilized</h2>

- Windows 10 (21H2)

<h2>Configuration Steps</h2>
<h3> Step 1: Setting up Roles </h3> Start by configuring roles in the Admin Panel. Navigate to "Agents" > "Roles" > "Add New Role". Create a role named "Supreme Admin" with full access permissions across the board.
</p>
<br />
<img src="https://i.imgur.com/GCKAE7u.png" height="80%" width="80%" alt="Roles permissions"/>
</p>
<p>
<h3> Step 2: Department Configuration </h3> Proceed to create departments in the Admin Panel under "Agents" > "Departments" > "Add New Department". Establish a department named "System Administrators" with default settings.
</p>
<br />
<img src="https://i.imgur.com/d0dogVG.png" height="80%" width="80%" alt="System Admins"/>
</p>
<p>
<h3> Step 3: Team Setup </h3> Create teams to facilitate collaboration among agents from different departments. Go to "Agents" > "Teams" > "Add New Team". Form a team named "Level II Support" and include members accordingly.
</p>
<br />

<img src="https://i.imgur.com/P0wKPVo.png" height="80%" width="80%" alt="Level II Support"/>
</p>
<p>
<h3> Step 4: Ticket Creation Settings </h3> Allow ticket creation without requiring registration or login. Navigate to "Settings" > "Users" > "Settings" and deselect "Require registration and login to create tickets".
</p>
<br />
<img src="https://i.imgur.com/rzXZ60d.png" height="80%" width="80%" alt="Anyone can create"/>
</p>
<p>
<h3> Step 5: Agent Configuration </h3> Add agents responsible for ticket resolution. In the Admin Panel under "Agents", click "Add New Agent" to create agents like "Jane Doe" and "John Doe", assigning roles, departments, and teams accordingly.
</p>
<br />
<img src="https://i.imgur.com/trv3weH.png" height="80%" width="80%" alt="New agents"/>
</p>
<p>
<h3> Step 6: User Setup </h3> Configure users who will be opening tickets. Switch to the "Agent Panel", go to "Users", and click "Create New User" to add users such as "Karen Karen" and "Ken".
</p>
<br />
<img src="https://i.imgur.com/GFUOmmu.png" height="80%" width="80%" alt="New Users"/>
</p>
<p>
<h3> Step 7: Service Level Agreements (SLAs) </h3> Define SLA plans to prioritize requests and set resolution timeframes. Navigate to "Admin Panel" > "Manage" > "SLA" to create SLA plans such as "SEV A", "SEV B", and "SEV C" with corresponding grace periods and schedules.
</p>
<br />
<img src="https://i.imgur.com/pnthCaA.png" height="80%" width="80%" alt="SLAs"/>
</p>
<p>
<h3> Step 8: Help Topics Configuration </h3> Streamline ticket assignments by configuring help topics. In the Admin Panel, navigate to "Manage" > "Help Topics" and create topics like "Business Critical Outage", "Personal Computer Issues", "Equipment Request", and "Password Reset".
</p>
<br />
<img src="https://i.imgur.com/N7dOIZu.png" height="80%" width="80%" alt="Help Topics"/>
</p>
<p>
<br />
<br/>
<h2> Congratulations! osTicket is now fully configured and ready for use! </h2>
