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
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
</p>
<p>

1.) Firstly, understand the difference between the Agent and the Admin panel. The Admin panel is allowed unrestricted access to the setup, configuration, and management of the helpdesk environment you're working within. In contrast, agents have limited access to any settings regarding their osTicket and mainly focus on the day-to-day/resolving of tickets around the parameters set by admins.
<p>
<img width="640" alt="Screenshot 2025-03-07 at 4 04 10 PM" src="https://github.com/user-attachments/assets/be5f885e-454e-443b-b322-5e579415866c" />
</p>

</p>
2.)  Configuring roles within osTicket requires you to be in the Admin panel--> agents--> roles.  To create a new role, you would then click "Add New Role", in this tab, name the role and select the permissions you want that role to have.  Click "Add Role" to finish and put new role into effect.
<p>

ex. Admin

<img width="640" alt="Screenshot 2025-03-07 at 1 56 16 PM" src="https://github.com/user-attachments/assets/55f16da2-2270-44b2-bce6-f2a6b3222b7e" />

</p>
<img width="640" alt="Screenshot 2025-03-07 at 3 45 15 PM" src="https://github.com/user-attachments/assets/2ede6cf4-7031-456c-8ca9-04891e684cce" />

</p>
<img width="640" alt="Screenshot 2025-03-07 at 2 21 13 PM" src="https://github.com/user-attachments/assets/07643d53-de3b-4f75-9417-6fad470a3f6a" />

<p>

3.)  Next is to configure departments, go to the Admin panel--> agents--> departments.  Click "Add New Department", in this tab you set up the settings for the department.  Putting in the parent department, naming the department, defining the department's SLA/schedule, etc. are examples of settings that can be changed when creating a new department.  Click "Create Dept" to finish.

ex. Support
<p>
<img width="640" alt="Screenshot 2025-03-07 at 4 21 54 PM" src="https://github.com/user-attachments/assets/fb777578-48c6-4249-8be6-955e410004fe" />
<p>
<img width="640" alt="Screenshot 2025-03-07 at 5 00 58 PM" src="https://github.com/user-attachments/assets/66c041aa-7583-4a46-b494-a752fd0c4702" />
<img width="432" alt="Screenshot 2025-03-07 at 5 56 03 PM" src="https://github.com/user-attachments/assets/21d276ad-11f4-4f96-b742-28315f7bf31c" />








</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
