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

1.) The Agent vs. the Admin panel. The Admin panel is allowed unrestricted access to the helpdesk environment's setup, configuration, and management. The Agent panel mainly focuses on the day-to-day/resolution of tickets.
<p>
<img width="640" alt="Screenshot 2025-03-07 at 4 04 10 PM" src="https://github.com/user-attachments/assets/be5f885e-454e-443b-b322-5e579415866c" />
</p>

</p>
2.)  Configuring Roles within osTicket, Admin panel-> Agents-> Roles-> click "Add New Role".
<p>
</p>
<img width="961" alt="Screenshot 2025-03-20 at 3 31 59 PM" src="https://github.com/user-attachments/assets/f409474b-31d9-454f-9818-0e40ec40dda2" />

</p>
Name the role.
<img width="640" alt="Screenshot 2025-03-07 at 3 45 15 PM" src="https://github.com/user-attachments/assets/2ede6cf4-7031-456c-8ca9-04891e684cce" />

</p>
Select the permissions for the role, click "Add Role" to finish, and put the new role into effect.
<img width="640" alt="Screenshot 2025-03-07 at 2 21 13 PM" src="https://github.com/user-attachments/assets/07643d53-de3b-4f75-9417-6fad470a3f6a" />
<p>ex. Admin
<p>

3.)  Configure Departments within osTicket, Admin panel-> Agents-> Department-> click "Add New Department".

<p>
<img width="958" alt="Screenshot 2025-03-20 at 3 32 19 PM" src="https://github.com/user-attachments/assets/ba5ebe8f-33c3-48c9-a296-bdcf876271d7" />
<p>
Configure the preferred settings for the department.
<img width="640" alt="Screenshot 2025-03-07 at 5 00 58 PM" src="https://github.com/user-attachments/assets/66c041aa-7583-4a46-b494-a752fd0c4702" />
  
Click "Create Dept" to finish.
<p>
<img width="432" alt="Screenshot 2025-03-07 at 5 56 03 PM" src="https://github.com/user-attachments/assets/21d276ad-11f4-4f96-b742-28315f7bf31c" />
<p>ex. Support

4.) Configure Teams within osTicket, Admin panel-> Agents-> Teams-> click "Add New Team".
<br />

<p>
<img width="960" alt="Screenshot 2025-03-20 at 3 46 46 PM" src="https://github.com/user-attachments/assets/e3bb4b26-d791-4aac-9ac1-08470fa028b2" />
</p>
<p>
Name the team and move to members.
<img width="640" alt="Screenshot 2025-03-20 at 3 52 36 PM" src="https://github.com/user-attachments/assets/c962bfa2-d5ab-4e4e-b029-0af5b0dec010" />
</p>
<p>
Add agents as members to the team and once finished click "Create Team".
<img width="959" alt="Screenshot 2025-03-20 at 4 07 45 PM" src="https://github.com/user-attachments/assets/8fe609a2-5c46-4c82-a8d7-5eed7ee2447a" />
</p>
<br />
