
<p align="center">
 <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
  </a>
</p>

<div align="center">


# 🧠 Technologies Used
- osTicket (Help Desk Ticketing System)
- Microsoft Azure (Cloud Computing)
- Remote Desktop
- Windows 10 

# 📝 Ticket Lifecycle Stages
- Intake
- Assignment & Communication
- Working the Issue
- Resolution

# ♻️ Ticket Lifecycle Examples: From Intake to Resolution

# 🧠 Technologies Used
- osTicket (Help Desk Ticketing System)
- Microsoft Azure (Cloud Computing)
- Remote Desktop
- Windows 10 Professional x64 22H2

# 📝 Ticket Lifecycle Stages
- Intake
- Assignment & Communication
- Working the Issue
- Resolution

# ♻️ Ticket Lifecycle Examples: From Intake to Resolution

<img src="1/Screenshot 2026-09-18 131205.png" alt="Open New Ticket">

2. Proceed to fill out the following fields with the relevant ticket information:
    - **Email Address**: The email address of whoever is submitting the ticket
    - **Full Name**: The full name of whoever is submitting the ticket
    - **Help Topic**: Click on the drop-down menu and select the issue that best fits with the issue in which the ticket is regarding
    - **Issue Summary** In the first field, enter a brief title for the issue and then proceed to the second field where a more detailed description is optional but recommended

In the end-user-created ticket example below, `Ken` (best reached at `Ken@Ken.com` ) is submitting a ticket regarding her trouble to access her account .

<img src="1/Screenshot 2026-09-18 132645.png" alt="End User Ticket">
<img src="1/Screenshot 2026-09-18 132800.png" alt="End User Ticket">


### 💬 Assignment & Communication
1. Navigate to `localhost/osTicket/scp/login.php` and enter the credentials for the administrator that will assign an Agent to work on the ticket created during Intake.


2. Navigate to `Tickets` > ` Open` and then open the ticket by clicking the ticket number under the **Ticket** column.

<img src="1/Screenshot 2026-09-18 132858.png" alt="Open Ticket as Admin">

3. From here, set the **Priority**, **Assign Department**, **Assigned To**, and the **SLA Plan** values for this ticket.

In the example below, the admin first clicks on the greyed out `— Unassigned —` text that's located to the right of **Assigned To**. Then, the admin designates `John Doe` as the **Assignee**.

<img src="1/Screenshot 2026-09-19 001415.png" alt="Assign Agent to Ticket">



<img src="1/Screenshot 2026-09-19 002145.png" alt="Filled Ticket Info">

4. Within the ticket tab, you can see the thread of any updates to the ticket and submit updates upon assignment. Once finished, click the orange `Post Reply` button and the ticket gets assigned to the appropriate department and your customer gets notified of this change.

<img src="1/Screenshot 2026-09-19 003258.png" alt="Ticket Timeline">

### 🛠️ Working the Issue
1. Navigate to `localhost/osTicket/scp/login.php` and enter the credentials for the Agent that has been assigned to work on the ticket created during Intake.

<img src="1/Screenshot 2026-09-19 003632.png" alt="Agent Credentials">

2. Once logged in, the Tickets window shows. It will show the ticket number, the last time it was updated, the subject, who submitted the ticket, priority level, and who it is assigned to. The Agent must click on the ticket number to open it so that they can begin working through the problem.

<img src="1/Screenshot 2026-09-19 003925.png" alt="Tickets Window">

3. Once the ticket is opened, you can review all ticket items and the history of the ticket items. This includes who submitted the ticket, who assigned the ticket, and any other ticket activity. The bottom section is where you can leave a reply for the user who submitted the ticket and an internal note to notify management if the ticket has been resolved.



4. Once the Agent (John Doe ) has reviewed all of the ticket details and identified a solution to the problem, the Agent can then use the **Post Reply** section to write a note to the user (Ken) explaining everything, including the solution, in a professional manner.

<img src="1/Screenshot 2026-09-19 010649.png" alt="Agent Works the Issue">

### ❤️‍🩹 Resolution

1. Before the user presses the orange `Post Reply` button to send the message to the user, it is important to navigate to the **Ticket Status** drop-down menu and change the value from `Open (current)` to `Closed`.

<img src="1/Screenshot 2026-09-19 010214.png" alt="Close the Ticket">

2. Then, osTicket will take the Agent back to the Tickets tab. The Agent will then see a confirmation that the reply was posted successfully. As pictured below, ticket `#325542` by Ken is no longer showing in the **Open** tickets section. Additionally, there is a visual confirmation banner at the top that says `Ticket #671497: Reply posted successfully`.

<img src="1/Screenshot 2026-09-19 010237.png" alt="Ticket Closed Confirmation">

3. To view tickets that have been closed, Agents can navigate to `Tickets` > `Closed` > and then click the appropriate time frame that this ticket is from. From here, the Agent should see closed ticket in question.





