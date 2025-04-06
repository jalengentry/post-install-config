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
<p>
<img width="640" alt="Screenshot 2025-03-24 at 4 26 46 PM" src="https://github.com/user-attachments/assets/0ab59602-0db6-4f8f-b022-bb17ed3d0855" />

</p>
Select the permissions for the role, click "Add Role" to finish, and put the new role into effect.
<img width="640" alt="Screenshot 2025-03-24 at 4 28 45 PM" src="https://github.com/user-attachments/assets/c9acf535-3f7b-49b4-8adc-11716b55ba6c" />

<p>ex. Admin
<p>

3.)  Configuring Departments within osTicket, Admin panel-> Agents-> Department-> click "Add New Department".

<p>
<img width="958" alt="Screenshot 2025-03-20 at 3 32 19 PM" src="https://github.com/user-attachments/assets/ba5ebe8f-33c3-48c9-a296-bdcf876271d7" />
<p>
Configure the preferred settings for the department.
<img width="640" alt="Screenshot 2025-03-07 at 5 00 58 PM" src="https://github.com/user-attachments/assets/66c041aa-7583-4a46-b494-a752fd0c4702" />
  
Click "Create Dept" to finish.
<p>
<img width="432" alt="Screenshot 2025-03-07 at 5 56 03 PM" src="https://github.com/user-attachments/assets/21d276ad-11f4-4f96-b742-28315f7bf31c" />
<p>ex. Support
<p>
4.) Configuring Teams within osTicket, Admin panel-> Agents-> Teams-> click "Add New Team".
<p>
<img width="960" alt="Screenshot 2025-03-20 at 3 46 46 PM" src="https://github.com/user-attachments/assets/e3bb4b26-d791-4aac-9ac1-08470fa028b2" />
</p>
<p>
Name the team and move to members.
<p>
<img width="640" alt="Screenshot 2025-03-20 at 3 52 36 PM" src="https://github.com/user-attachments/assets/c962bfa2-d5ab-4e4e-b029-0af5b0dec010" />
</p>
<p>
Add agents as team members and click "Create Team" once finished.
<p>
<img width="959" alt="Screenshot 2025-03-20 at 4 07 45 PM" src="https://github.com/user-attachments/assets/8fe609a2-5c46-4c82-a8d7-5eed7ee2447a" />
ex. Online Banking
<p></p>
5.) Configuring Agents within osTicket, Admin panel-> Agents-> Agents-> click "Add New Agent".
<p>
<img width="959" alt="Screenshot 2025-03-24 at 3 58 01 PM" src="https://github.com/user-attachments/assets/262edc7b-3071-4678-9453-9e79f1d47924" />
</p>
<p>
Fill out personal information and create a user name for the agent.
<p>
<img width="640" alt="Screenshot 2025-03-24 at 4 09 33 PM" src="https://github.com/user-attachments/assets/9cf0ae34-a661-4385-ba82-6d83b72e7547" />
<p>
Define the agent's department and role.
<p>
<img width="640" alt="Screenshot 2025-03-24 at 4 13 38 PM" src="https://github.com/user-attachments/assets/d800a3c1-1c45-4677-804c-369fe742bb32" />
<p>
Set permissions.
<p>
<img width="640" alt="Screenshot 2025-03-24 at 4 49 43 PM" src="https://github.com/user-attachments/assets/3c488710-b955-49f1-99c3-74ae7381d6d7" />
<p>
Assign to a team and click "Create" to create a new agent profile.
<img width="640" alt="Screenshot 2025-03-24 at 4 50 45 PM" src="https://github.com/user-attachments/assets/3a3bb2d9-d1b4-43e2-bcf3-c2530e4baf93" />
<p>ex. Jalen Gentry
<p></p>
6. Configuring Users within osTicket, Agent panel-> Users-> click "Add User".
<p>
<img width="640" alt="Screenshot 2025-04-06 at 2 18 08 PM" src="https://github.com/user-attachments/assets/8bd83146-590a-4458-a440-0539cd4ca531" />

Fill out user info and click "Add User" to create a new user profile.
<p>
<img width="640" alt="Screenshot 2025-04-06 at 2 28 43 PM" src="https://github.com/user-attachments/assets/d0568faa-f1b5-4c95-851d-bac157d1f493" />
<p>ex. Karen
<p>
7. Configuring SLA within osTicket, Admin panel-> Manage-> SLA-> click "Add New SLA Plan".
<p>
<img width="640" alt="Screenshot 2025-04-06 at 2 44 31 PM" src="https://github.com/user-attachments/assets/4d3a461e-8210-4d39-83d4-b3a43543ec9b" />









