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
- Set up ticket settings like auto-close time, SLA policies, and priority levels.  

## 2. Email Configuration
- Set up email fetching (IMAP/POP) for incoming tickets.  
- Configure SMTP for outgoing email responses.  
- Ensure email piping or cron job is correctly configured for automation.  

## 3. User & Staff Management
- Create user roles, assign permissions, and add support staff.  
- Configure departments, teams, and groups for proper ticket routing.  

## 4. Ticket Workflow & SLA Policies
- Define help topics and auto-assign tickets based on department/team.  
- Set up SLA (Service Level Agreements) to manage response times.  

## 5. Security & Performance Optimization
- Enable CAPTCHA for new ticket submissions.  
- Configure authentication settings (e.g., LDAP, OAuth, or SSO).  
- Adjust server and database settings for optimal performance.  

