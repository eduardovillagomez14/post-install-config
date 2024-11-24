<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Step 1: Add a New Role
- Step 2: Add a New Department
- Step 3: Add a New Team
- Step 4: Add a New Agent
- Step 5: Add a New SLA Plan
- S
- Item 5

<h2>Configuration Steps</h2>

<p>
<img width="965" alt="Screenshot 2024-11-24 at 3 43 06 PM" src="https://github.com/user-attachments/assets/e4a97367-8dc4-4f22-8ad9-843d200e7d52">

</p>
<p>
- Step 1: Add a New Role
<p>
Navigate to the Agents tab and select Roles.
  <p>
Under the Permissions tab, define specific permissions for tickets, tasks, and knowledgebase management.
    <p>
Examples of permissions include:
      <p>
Assign: Ability to assign tickets to agents or teams.
        <p>
Close: Ability to close tickets.
          <p>
Delete: Ability to delete tickets.
            <p>
Post Reply: Ability to post ticket replies.
              <p>
Transfer: Ability to transfer tickets between departments.
                <p>
Once permissions are set, click Add Role to finalize.
<p>  
Purpose: Roles are essential for granting agents specific capabilities within the osTicket system.
</p>
<br />

<p>
<img width="878" alt="Screenshot 2024-11-24 at 3 43 53 PM" src="https://github.com/user-attachments/assets/45df6f20-4f4b-4551-bad5-9732d4e17257">

</p>
<p>
Step 2: Add a New Department
<p>
Go to the Agents tab and click on Departments.
  <p>
Enter the department name (e.g., SysAdmins).
    <p>
Set the Status as Active and choose the department Type (Public or Private).
      <p>
Configure other settings:
        <p>
SLA: Assign the SLA for this department.
          <p>
Manager: Assign a manager if applicable.
            <p>
Ticket Assignment: Define how tickets are assigned within the department.
              <p>
Adjust auto-response and email notification settings if needed.
                <p>
Click Add Department to save.
<p>
  Purpose: Departments help organize and manage tickets by categorizing them based on specific areas or teams.
</p>
<br />

<p>
<img width="961" alt="Screenshot 2024-11-24 at 3 44 44 PM" src="https://github.com/user-attachments/assets/a691c8f7-9f93-498d-93a9-88c9129b51ff">

</p>
<p>
Step 3: Add a New Team
<p>
Navigate to the Agents tab and select Teams.
  <p>
Enter the team name (e.g., Online Banking) and set the status as Active.
    <p>
Assign a Team Lead (optional) and enable or disable assignment alerts.
      <p>
Add internal admin notes if required.
        <p>
Click Create Team to save.
<p>
Purpose: Teams group agents who collaborate on related tasks, providing better ticket handling and management.
</p>
<br />

<p>
<img width="957" alt="Screenshot 2024-11-24 at 3 45 10 PM" src="https://github.com/user-attachments/assets/eb9fc031-9ca9-479f-a0de-d33fa2f33261">

</p>
<p>
Step 4: Add a New Agent
<p>
Under the Agents tab, select Agents and click on Add New Agent.
  <p>
Fill in the agent's account details.
    <p>
Assign the agent to a Primary Department (e.g., Support/SysAdmins) and a specific role (e.g., Supreme Admin).
      <p>
Optionally, provide extended access to other departments by adding them under Extended Access.
        <p>
Click Create to add the agent.
<p>
Purpose: Agents are individual users responsible for resolving tickets. Assigning roles and departments ensures proper access control.
</p>
<br />

<p>

<img width="1117" alt="Screenshot 2024-11-24 at 3 45 50 PM" src="https://github.com/user-attachments/assets/0a4166e9-1f3b-4f9c-a590-2b3a6efc3a7f">

</p>
<p>
Step 5: Add a New SLA Plan
<p>
Go to the Manage tab and select SLA.
  <p>
Enter the SLA name (e.g., Sev-A) and set the status as Active.
    <p>
Define the Grace Period (e.g., 1 hour) for overdue tickets.
      <p>
Configure the SLA schedule and notification settings for overdue alerts.
        <p>
Add internal notes if necessary.
<p>
Click Add Plan to save.
  <p>
Purpose: SLA (Service Level Agreement) Plans define response times and ensure timely resolution of tickets.
</p>
<br />
