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

- Configure:
  - Roles
  - Departments
  - Teams
  - Agents
  - Users
  - Service Level Agreement (SLA)
  - Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/6dc2cf76-6b1a-4ebe-8a86-6294690dc7d7"/>
</p>
<p>
First, configure the role for Supreme Admin. Making sure you are in the Admin Panel (found in the top right), we will add a new role Agents>Roles>Add New Role. Name the role "Supreme Admin" and check all boxes in Permissions before creating.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/dac8b63b-f971-45cb-9dc2-85b1d876ccab" :height=70%, width=70%"/>
</p>
<p>
Remaining in the Admin Panel, Agents>Departments>Add New Department. Name the department "System Administrators" and create.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/98930116-b31c-4479-a4fc-9182e7738030"/>
</p>
<p>
Remaining in the Admin Panel, Agents>Teams>Add New Team. Name the team "Level II Support", add appropriate members in the "Members" tab, and create team.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/91339e93-067e-423b-b89e-bd3a0fe14ece"/>
</p>
<p>
In the Admin Panel, Agents>Agents>Add New Agent. Name the agent and provide a username for the agent. In the 'Access' tab, select the department and the role and add to a team in the 'Teams' tab, if appropriate. 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/cb88dc15-e1bd-4b09-a6e9-d27a98003f6e"/>
</p>
<p>
Switching to the Agent Panel (located in the top right), we will create the users who can submit tickets. Provide the name and email of the user being added, and create.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/f97b893e-fac6-4b9e-8ac4-5148c8f4bb95"/>
</p>
<p>
Switching back to the Admin Panel, we will create the Service Level Agreements (SLA). Manage>SLA>Add New SLA. For this example, we will create three SLAs with different severities. SEV-A (1 hour, 24/7), SEV-B (4 hours, 24/7), and SEV-C (8 hours, business hours).
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/154b1aad-d80f-4c74-ba11-02645473913a"/>
</p>
<p>
Lastly, we will create the topics. In the Admin Panel, Manage>Help Topics>Add New Help Topic. For this example, we will create four topics called "Business Critical Outage", "Personal Computer Issues", "Equipment Reset", and "Password Reset".
</p>
<br />
