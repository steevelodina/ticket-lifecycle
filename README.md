![image](https://github.com/steevelodina/ticket-lifecycle/assets/173463043/8d51c1ae-903b-4b3c-b6a6-008b5c6adec6)

-osTicket - Ticket Lifecycle: Intake Through Resolution

This tutorial provides a detailed explanation of the entire process a ticket goes through within the open-source helpdesk ticketing system osTicket, from the moment it is submitted to when it is finally resolved. To start, I will demonstrate how a ticket is created by a user facing a real issue. Then, I will show how an agent accesses the ticketing system to begin the process of resolving the ticket.

Environments and Technologies Used
Microsoft Azure (Virtual Machines/Compute)
Remote Desktop (macOS)
Internet Information Services (IIS)
Operating Systems Used
Windows 10 (21H2)
Ticket Lifecycle Stages
Intake
Assignment and Communication
Working the Issue
Resolution
Lifecycle Stages
Stage 1. ) Intake - Creating Tickets
The first thing we will do is create a ticket from the user end of the osTicket platform.

Open osTicket: http://localhost/osTicket/

Select: Open a New Ticket
![image](https://github.com/steevelodina/ticket-lifecycle/assets/173463043/3a8d7e91-da8a-45c5-9e9e-a4d2dc7cce11)



Insert the following ticket information:

Email Address: Karen@osticket.com

Name: Karen Karen

Help Topic: Business Critical Outage

Issue Summary: Entire mobile online banking is down

Ticket Details: Customers are reporting they are getting a 404 error when browsing to online banking.

Click: Create Ticket
![image](https://github.com/steevelodina/ticket-lifecycle/assets/173463043/b60795a5-6811-4d87-91db-22cd7f1538ed)



Note: When mobile online banking is down, it can lead to a major loss in revenue for the company.

Step 2. ) Assignment and Communication
Login to osTicket as an Agent: (User: jane.doe / jane.doe@gmail.com)
![image](https://github.com/steevelodina/ticket-lifecycle/assets/173463043/1b6fce67-dfec-494f-b60c-82577cd77c94)


Click: The entire mobile online banking is down (this is the ticket we just created on the user end as Karen)
![image](https://github.com/steevelodina/ticket-lifecycle/assets/173463043/f184e6d8-3a36-40ae-b855-15e3630b306e)


For the ticket to be handled properly, information regarding the severity level can be changed. Because the entire mobile banking is down and critical to business impact, we will change the priority of this ticket to EMERGENCY and the SLA to SEV-A.

![image](https://github.com/steevelodina/ticket-lifecycle/assets/173463043/7af5fb2b-b872-45bf-aeca-7e858f7eb46e)


Priority: Emergency

Type In: Business Impacting Event

Click: Update

We will also transfer the ticket to the system administrators department and then assign it to an agent, who in this case will be ourselves, Jane Doe.

Click: Department

Select: System Administrators

Details: Sys Admins responsible for mobile banking infrastructure

Click: Transfer
![image](https://github.com/steevelodina/ticket-lifecycle/assets/173463043/9e52e232-0213-4492-8880-b60819ece961)

isolated

Assigned to: Jane Doe

Click: Assign
![image](https://github.com/steevelodina/ticket-lifecycle/assets/173463043/fb18ece7-cf1e-4629-8430-0f0dd7d4d8b5)

isolated
SLA Plan: SEV-A

Details: Business Impacting, Critical Event

Click: Update
![image](https://github.com/steevelodina/ticket-lifecycle/assets/173463043/27c6b6f7-ad4a-405d-a54a-05f6b432c83b)

isolated
Note: Make sure your ticket information matches the image below and continue to the next step.

isolated
Note: This is where you will see the history and updates of the tickets. ↓
![image](https://github.com/steevelodina/ticket-lifecycle/assets/173463043/0fb475f6-8fb5-41e2-9d73-6de8f5a68335)

isolated
Stage 3. ) Working the Issue
On the back end, Jane is working with the System Adminstrator team to resolve the issue.

Response Text Box: Coordinating with Sys Admin Team to bring mobile banking back online.

Select: Post Reply
![image](https://github.com/steevelodina/ticket-lifecycle/assets/173463043/4dc3cf6f-8d47-42f8-9153-253492af21c6)

isolated
**Note: *The organization you work for will determine the type of details you type into the description.**

Stage 4. ) Resolution
Return to the ticket and update the end user once the issue is resolved.

Response Text Box: Jerry from System Engineering found and connected a failed load balancer. Mobile banking should be back up.

Ticket Status: Resolved

Select: Post Reply
![image](https://github.com/steevelodina/ticket-lifecycle/assets/173463043/9b201625-c083-44e9-923c-080d6bbfd2f1)

isolated
The ticket should now be on the "closed" tab since it has been resolved.
![image](https://github.com/steevelodina/ticket-lifecycle/assets/173463043/e681d526-f508-4c8e-923e-3b89a156cec0)

isolated
🎉🎉🎉 Congratulations! You have successfully resolved your first ticket as a help desk support agent!




