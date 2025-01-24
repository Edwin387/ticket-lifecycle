<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10</b> (22H2)

<h2>Ticket Lifecycle Stages</h2>

1. **Intake**
2. **Assignment and Communication**
3. **Working the Issue**
4.  **Resolution**

<h2>Lifecycle Stages</h2>

<h3>1.) Create Tickets as End-Users</h3>

- **Scenario 1:** Create a ticket as an end-user with the following details:
-  **Subject:** "Online banking system is down"
-  **Deatils:** Describe the issue briefly (e.g., "The entire online banking system is down, preventing users from accessing their accounts.")
  
![image](https://github.com/Edwin387/ticket-lifecycle/blob/main/shot%2049.PNG?raw=true)


<h3>2.) Observe Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Agent (john)**.
- Observe the ticket's properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned

![image](https://github.com/Edwin387/ticket-lifecycle/blob/main/Shot%2057.PNG?raw=true)

<h3>3.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
-  **SLA:** Sev-A (1 hour, 24/7).
-  **Assigned To:** John Doe/Online Banking Department.

![image](https://github.com/Edwin387/ticket-lifecycle/blob/main/Shot%2061.PNG?raw=true)

<h3>4.) Verify Ticket Permissions</h3>

- Log back in as **Help Desk Agent (john)**.
- Attempt to view or modify the ticket. Verify whether the changes are accessible or editable. 

<h3>5.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (jane)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

![image](https://github.com/Edwin387/ticket-lifecycle/blob/main/Shot%2052.PNG?raw=true)

---

<h3>6.) Create Another Ticket as End-Users</h3>

- **Scenario 2:** Create a ticket as an end-user with the following details:
   - **Subject:** "Password Reset"
     - **Details:** Describe the issue briefly (e.g, "A user is unable to log into access their account, and the user needs their password reset.")

![image](https://github.com/Edwin387/ticket-lifecycle/blob/main/shot%2045.PNG?raw=true)


<h3>7.) Observe Ticket Properties as Help Desk Agent</h3>
-Observe the ticket's properties:
 - **Priority:** Default value.
 - **Department:** Default department.
 - **SLA:** Default SLA.
 - **Assigned To:** Not yet assigned.

![image](https://github.com/Edwin387/ticket-lifecycle/blob/main/shot%2046.PNG?raw=true)


<h3>8.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
-  **SLA:** Sev-B (4 hours, 24/7).
-  **Department:** Support.

![image](https://github.com/Edwin387/ticket-lifecycle/blob/main/shot%2047.PNG?raw=true)

<h3>9.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (john)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

![image](https://github.com/Edwin387/ticket-lifecycle/blob/main/shot%2048.PNG?raw=true)

---

<h3>10.) Create a Final Ticket as End-Users</h3>

- **Scenario 3:** Create a ticket as an end-user with the following details:
- **Subject:** "Applications Malfunctioning"
- **Details:** Describe the issue briefly (e.g., "Employees report applications malfunctioning on their computers, it needs urgent attention.")

![image](https://github.com/Edwin387/ticket-lifecycle/blob/main/Shot%2053.PNG?raw=true)
  
<h3>11.) Observe Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Agent (john)**
- Observe the ticket's properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.

![image](https://github.com/Edwin387/ticket-lifecycle/blob/main/Shot%2054.PNG?raw=true)

<h3>12.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
- **SLA:** Sev-B (4 hours,24/7).
- **Department:** Support.

![image](https://github.com/Edwin387/ticket-lifecycle/blob/main/Shot%2056.PNG?raw=true)

<h3>13.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (john)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

---

<h2>Conclusion</h2>

By following these steps, you have successfully demonstrated the lifecycle of a ticket from intake to resolution within osTicket. This lab highlights the importance of ticket properties, proper assignment, and resolution processes in a help desk environment. 

