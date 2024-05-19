<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img width="1127" alt="image" src="https://github.com/dteimuno/ticket-lifecycle/assets/169619672/db14acc4-88fb-4cb4-9f03-91fdfeeedf04">
</p>
<p>
Open ticket as a guest user by going to localhost/osticket. Click create a New Ticket
Create a new ticket with business critical severity
<img width="841" alt="image" src="https://github.com/dteimuno/ticket-lifecycle/assets/169619672/9ea28074-2c96-493e-9f8f-203993ad8e59">

Create another ticket with a sofwtare issue: Adobe reader not working for entire accounting department
<img width="837" alt="image" src="https://github.com/dteimuno/ticket-lifecycle/assets/169619672/dfab0981-c2ae-447c-a7a6-c35799ac85b3">

Create another ticket with a general inquiry of when the department will get new hardware
<img width="1028" alt="image" src="https://github.com/dteimuno/ticket-lifecycle/assets/169619672/3560a6b5-094e-4cb4-bf2f-a30ea3ec22d9">

</p>
<br />

<p>
<img width="976" alt="image" src="https://github.com/dteimuno/ticket-lifecycle/assets/169619672/0b7d15ee-7b3f-400c-a916-bdc1ac03b081">
</p>
<p>
Login as agent Jane Doe, not admin to be able to resolve these tickets

A successful login as an agent will show the following screen:
<img width="1201" alt="image" src="https://github.com/dteimuno/ticket-lifecycle/assets/169619672/82f4c413-42b6-43d2-9b68-9ffce008bc24">
There are no tickets for the agent Jane Doe because she does not have the permissions. Log out and login as admin to change the permissions.

Navigate to Agents Tab> Jane Doe>Access. In this tab, add Jane Doe to the support team expanding extended access clicking support and clicking add. In roles select Supreme admin. Click save changes to enable changes and new permissions:
<img width="1083" alt="image" src="https://github.com/dteimuno/ticket-lifecycle/assets/169619672/b38e6296-71ad-4396-a283-f9124f9482e1">

Log out of admin account and sign back into agent Jane Doe's account. Once you log in you see a lot of tickets in there showing the effect of the updated permissions:
<img width="979" alt="image" src="https://github.com/dteimuno/ticket-lifecycle/assets/169619672/ac5bdfba-d96f-4e62-8db7-5d88d4b7e794">

Click on the first ticket made where there was a shutdown on online banking.Click the priority and change the priority to emergency:
<img width="1131" alt="image" src="https://github.com/dteimuno/ticket-lifecycle/assets/169619672/babfdc62-0c79-47c4-979a-f5935aa39ad1">

Assign the ticket to Jane Doe by clicking Assigned To: and assigning the ticket to Jane Doe:
<img width="1077" alt="image" src="https://github.com/dteimuno/ticket-lifecycle/assets/169619672/1fa9d576-0dae-407c-a02c-ad2b027fab0b">

Change the SLA to reflect the importance of the ticket.Click SLA plan: and change to SEV-A:
<img width="1072" alt="image" src="https://github.com/dteimuno/ticket-lifecycle/assets/169619672/63510dd9-a09f-4bad-8305-194f101795e8">

Change department to reflect the best department to resolve this issue:
<img width="956" alt="image" src="https://github.com/dteimuno/ticket-lifecycle/assets/169619672/2e0d5f4f-6f5d-4141-a699-0142f1544a4d">

Comment on ticket thread to show work on ticket has begun:
<img width="964" alt="image" src="https://github.com/dteimuno/ticket-lifecycle/assets/169619672/95eba938-e710-40b1-afdb-4f4e8b40a9da">

Go back to the tickets to see the updated severity and tickets lineup:
<img width="964" alt="image" src="https://github.com/dteimuno/ticket-lifecycle/assets/169619672/f88963c3-1ab1-4e55-abcd-0b9abd73bafe">

Click on the mobile banking down ticket, comment on the resolution and change ticket status from open to resolved to conclude and close out the ticket:
<img width="950" alt="image" src="https://github.com/dteimuno/ticket-lifecycle/assets/169619672/1e105d4b-2092-47ae-97dc-cdd030053648">

The ticket has now disappeared from open tickets:
<img width="960" alt="image" src="https://github.com/dteimuno/ticket-lifecycle/assets/169619672/2fbb0430-97bf-4f24-abc8-ba9b3bd81a40">

In closed tickets subsection: Observe the closed ticket:
<img width="958" alt="image" src="https://github.com/dteimuno/ticket-lifecycle/assets/169619672/502d06c7-1bf2-42a1-86f4-c7b906e98d87">
</p>
<br />

