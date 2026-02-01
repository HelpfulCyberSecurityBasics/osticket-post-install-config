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

- Configure Roles, Departments, and Teams: This involves structuring the support organization by defining agent permissions, departmental responsibilities, and team collaborations.
- Create Agent and User Profiles: This objective focuses on adding individual agents who will manage tickets and creating user accounts for customers to submit requests.
- Allow Anyone to Submit Tickets: By unchecking the "registration required" option, the system becomes accessible to all users, enabling them to create tickets without needing to log in.
- Set Up SLAs (Service Level Agreements): This ensures that different types of tickets are handled within specific timeframes, improving response and resolution efficiency
- Define Help Topics to Organize Incoming Requests: This categorizes tickets, making it easier to route them to the appropriate teams and streamline the support process.

<h2>Configuration Steps</h2>

<p>
1.  Accessing the osTicket Admin Panel:

- The first step involves logging into the osTicket admin panel using the admin user username and password created during osTicket - Prerequisites and Installation. This provides access to all the system's configuration settings.
- (Screenshot showing the osTicket Admin Panel).
<img width="729" height="399" alt="Screenshot 2026-02-01 at 10 46 58 AM" src="https://github.com/user-attachments/assets/1163467a-42fc-4835-ad45-ff2b1aa8feb8" />
</p>
<p>
</p>
<br />

<p>
  2. Configuring Agents, Departments, and Teams:

- This segment focuses on setting up the internal structure of your support team. It includes defining roles (like "Supreme Admin"), creating departments (such as "Admins"), and organizing agents into teams (e.g., "Remote Access Team").
- (Screenshot showing the "Roles" configuration page)
- (Screenshot showing the "Departments" configuration page) 
- (Screenshot showing the "Teams" configuration page)
  <img width="591" height="299" alt="Screenshot 2026-02-01 at 12 04 13 PM" src="https://github.com/user-attachments/assets/8d7b730f-aeaf-4deb-9a1f-cc0f67312985" />
<img width="764" height="316" alt="Screenshot 2026-02-01 at 12 04 25 PM" src="https://github.com/user-attachments/assets/bf001e6c-7a3c-4caf-8110-e7a64fc9bcb0" />
<img width="745" height="228" alt="Screenshot 2026-02-01 at 12 05 24 PM" src="https://github.com/user-attachments/assets/55c670b9-5525-4faa-8d00-938c3b858dc9" />

</p>
<p>

</p>
<br />

<p>
3. Configuring Users, SLAs, and Help Topics (6:01 - 19:20):

- This final step involves preparing the system for end-users and ticket management. It covers allowing anyone to create tickets without registration, adding user profiles, setting up Service Level Agreements (SLAs) with different grace periods (e.g., "SLA A" for 1 hour), and defining help topics to categorize incoming requests (such as "Business Critical Outage" or "Personal Computer Issues").
- (Screenshot showing the "User Settings" with "Registration Required" unchecked)
- (Screenshot showing the "SLA Plans" configuration page)
- (Screenshot showing the "Help Topics" configuration page)
<img width="763" height="437" alt="Screenshot 2026-02-01 at 12 10 03 PM" src="https://github.com/user-attachments/assets/d99a046e-3a93-492c-b5c7-05d4c0afd2d4" />
<img width="746" height="227" alt="Screenshot 2026-02-01 at 12 10 46 PM" src="https://github.com/user-attachments/assets/a8ac32fd-de8a-4110-828c-caee7aaeda29" />
<img width="750" height="304" alt="Screenshot 2026-02-01 at 12 11 35 PM" src="https://github.com/user-attachments/assets/d741c6c7-bf30-4b3e-b10a-e11927a74f78" />

</p>
<p>
</p>
<br />
