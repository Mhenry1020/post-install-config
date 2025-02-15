<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com/watch?v=mbckqBHjLxM)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>





## 1. System Settings & Preferences
- Configure the helpdesk name, default email, and time zone.
- ![image](https://github.com/user-attachments/assets/18537b82-0a51-4215-87be-b71b02b32f5b) ![image](https://github.com/user-attachments/assets/e57e251e-6d46-451b-a4a2-b16910542478)

 
- Set up ticket settings like auto-close time, SLA policies, and priority levels.  

## 2. Email Configuration
- Set up email fetching (IMAP/POP) for incoming tickets.  
- Configure SMTP for outgoing email responses.  
- Ensure email piping or cron job is correctly configured for automation.  

## 3. User & Staff Management
- Create user roles, assign permissions, and add support staff.
![image](https://github.com/user-attachments/assets/4d5d1c38-6dca-40a7-ae0f-3b31611a2616)
![image](https://github.com/user-attachments/assets/601013a1-f128-4a82-b69c-2e73820ddb21)

![image](https://github.com/user-attachments/assets/3f32b48e-0559-4d63-88a9-90cfcbde75f5)

- Configure departments, teams, and groups for proper ticket routing.(Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
![image](https://github.com/user-attachments/assets/8701a0da-e700-4ebd-ace4-5280ddac5b82)
![image](https://github.com/user-attachments/assets/d611535b-2666-49ac-9734-8c5634c53370)



## 4. Ticket Workflow & SLA Policies
- Define help topics and auto-assign tickets based on department/team.  ![image](https://github.com/user-attachments/assets/cd03949c-20ff-4480-95ac-f1ca0f21e68b)

- Set up SLA (Service Level Agreements) to manage response times.  ![image](https://github.com/user-attachments/assets/bc9ed0f3-4b63-4263-88ba-4a94721f3801) ![image](https://github.com/user-attachments/assets/66439346-c1f6-4ceb-b938-5d6e329d3ff2)



## 5. Security & Performance Optimization
- Enable CAPTCHA for new ticket submissions.  
- Configure authentication settings (e.g., LDAP, OAuth, or SSO).  
- Adjust server and database settings for optimal performance.  

