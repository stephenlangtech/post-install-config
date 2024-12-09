<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-installation configuration of the open-source help desk ticketing system, osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/sx170cG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Great! Now that osTicket is successfully configured, we will proceed with system administration tasks, starting with configuring new roles within the help desk. This will allow you to manage user access and permissions effectively.
</p>
<br />

<p>
<img src="https://i.imgur.com/DAhGSan.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure new roles within the help desk, go to the Admin Panel -> Agents -> Roles. Click on "Add new role" and enter the name of the new role, such as Supreme Admin. This will allow you to define the permissions and responsibilities for the role. Since you are creating a Supreme Admin role, this role will be granted all permissions. Ensure all available permissions are selected for this role to provide full administrative access.
</p>
<br />

<p>
<img src="https://i.imgur.com/KzFVjJQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select the "Departments" button in the Agents tab. Here, you can create a new department, with each agent assigned to a specific department based on their role within the help desk. Create a department named "System Administrators", which will serve as the designated department for Supreme Admins. Additional settings, such as SLAs, managers, and email configurations, can be customized within the Departments tab to align with your help desk's operational needs.
</p>
<br />

<p>
<img src="https://i.imgur.com/ob4MEma.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure teams, navigate to Admin Panel -> Agents -> Teams. Teams allow you to group agents from different departments to collaborate effectively. Create a team named Level II Support and assign agents from various departments as needed.
</p>
<br />

<p>
<img src="https://i.imgur.com/TcRrhwN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To allow anyone to create tickets, go to Admin Panel -> Settings -> User Settings. Uncheck the option "Require registration and login to create tickets" to enable unregistered users to submit tickets without needing an account.
</p>
<br />

<p>
<img src="https://i.imgur.com/dwAhP3I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure agents (workers), go to Admin Panel -> Agents -> Add New. Fill in the necessary details, such as the agent's name, email, assigned role, and department, to set up their profile and permissions.
</p>
<br />

<p>
<img src="https://i.imgur.com/aYLnu3z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure users (customers), go to Agent Panel -> Users -> Add New. Add users such as Ryu and Ken by entering their details, including names and email addresses, to enable them to submit and manage their tickets.
</p>
<br />

<p>
<img src="https://i.imgur.com/YXWfwh8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure help topics for user ticket creation, navigate to Admin Panel -> Manage -> Help Topics. These topics will guide users in categorizing their tickets effectively.

</p>
<br />
