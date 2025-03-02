
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial provides a step-by-step guide on the lifecycle of a ticket within osTicket, an open-source help desk ticketing system. It covers the entire process—from ticket intake to resolution—demonstrating help desk operations, workflow automation, and customer service management in a structured support environment.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- Agent / User Profile Utilization

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/UfwMeH7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In osTicket, customers submit tickets through the web portal, ensuring their issues are logged and assigned for resolution.

How to Submit a Ticket:
<br>
1. Go to the osTicket Portal and click "Open a New Ticket." <br>
2. Enter Details:
A Name & Email for communication, A Help Topic to categorize the request, An Issue Details (subject & description). <br>
4. Submit the Ticket – The system generates a unique ticket ID for tracking. <br>
5. Receive Confirmation – The user gets an email notification with ticket details.
Next, the ticket moves to assignment and processing.
</p>
<br />

<p>
<img src="https://i.imgur.com/A5WCKPQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
To simulate urgent issue handling, create a high-priority ticket for a mobile/online banking outage and configure its properties: <br>

1. Open a New Ticket – Submit a ticket for the banking system outage via the Admin Panel or Customer Portal. <br>
2. Set Priority & SLA – Assign a high-priority level with an SLA ensuring a 1-hour response time. <br>
3. Assign to Department – Route the ticket to the SysAdmins or IT Support team. <br>
4. Test Role-Based Access – Verify that only authorized agents (e.g., SysAdmins, IT Support) can access or update the ticket. This process ensures critical issues are prioritized and handled by the appropriate team efficiently.
</p>
<br />

<p>
<img src="https://i.imgur.com/lLoxzHc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
To demonstrate proactive ticket management, the customer agent takes ownership of the ticket and communicates with the user:
<br>
1. Reassign the Ticket – The agent navigates to the ticket in osTicket and assigns it to themselves. <br> 
2. Post a Response – In the ticket thread, the agent updates the user, stating they are investigating the issue. <br>
3. Ensure Transparency – The agent informs the user that a potential solution has been found and follow-up will be provided. <br>
4. Maintain Engagement – The system notifies the user via email, keeping them informed throughout the resolution process. This step ensures clear communication, accountability, and user confidence in the support workflow.
</p>
<br />

<p>
<img src="https://i.imgur.com/Ij97tDd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
To complete the ticket lifecycle, the customer agent finalizes the resolution and communicates with the user:
<br>
1. Post a Final Update – The agent adds a comment detailing the solution in the ticket thread. <br>
2. Mark as Resolved – Change the ticket status to Resolved, signaling that the issue has been addressed. <br>
3. Notify the User – The system sends an email update, ensuring the customer is informed of the resolution. <br>
4. Ensure Clarity – Encourage the user to respond if further assistance is needed before officially closing the ticket. This process highlights effective ticket lifecycle management, customer communication, and IT support resolution within a structured help desk system.
</p>
<br />
