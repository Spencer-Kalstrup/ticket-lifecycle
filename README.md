<p align="center"><img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/></p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.
<br />

<h2>Environments and Technologies Used</h2>
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
<br />

<h2>Operating Systems Used </h2>
- Windows 10</b> (21H2)
<br />

<h2>Important Links</h2>
<a href="http://localhost/osTicket/scp/login.php">Admin Login</a>

<a href="http://localhost/osTicket">User URL</a>
<br />

<h2>Ticket Lifecycle Stages</h2>

-  Intake

-  Assignment and Communication
  
-  Working the Issue

-  Resolution
<br />

<h2>Prep</h2>
Login as an admin, delete the "Maintenance" department by navigating to the "Agents" tab, then click the "Departments" tab.
<p><img src="https://i.imgur.com/8OU49VF.png" height="80%" width="80%"/></p>
<br />

Check the box next to "Maintenance", then click the dropdown box next to the "More" icon
<p><img src="https://i.imgur.com/E0KuOPE.png" height="80%" width="80%"/></p>
<br />

Select "Delete" and delete the department
<p><img src="https://i.imgur.com/TEi7aOn.png" height="80%" width="80%"/></p>
We are now ready to start the lab!
<br />



<h2>Intake</h2>
As an <a href="http://localhost/osTicket">end user</a>, create the following ticket :
"Entire mobile/online banking system is down"
<p><img src="https://i.imgur.com/DPVdoBt.png" height="80%" width="80%"/></p>
<p><img src="https://i.imgur.com/4Nd24yX.png" height ="80%" width="80%"/></p>
<br />



<h2>Assignment and Communication</h2>

In the Virtual MAchine, go back to the <a href="http://localhost/osTicket/scp/login.php">Admin Login</a>. Log in as John Doe.
<p><img src="https://i.imgur.com/YKFpeqy.jpeg" height="80%" width="80%"/></p>
<br />

Click on the new Ticket
<p><img src="https://i.imgur.com/uE5qkaV.png" height="80%" width="80%"/></p>
<br />

Observe the priority, department, SLA, and who the ticket was Assigned to. Notice John is unable to do anything to the ticket except leave an internal note. This is because his role is assigned "View Only" permissions
<p><img src="https://i.imgur.com/bszilN5.png" height="80%" width="80%"/></p>
<br />

Logout and Login as an admin. Open the ticket in the admin account. Observe the priority, SLA, and who the ticket was assigned to. We can now make changes to all of these options because the admin account has more permissions than John.
<p><img src="https://i.imgur.com/glpxT09.png" height="80%" Width="80%"/></p>
<br />

Change the department to SysAdmins so Jane can work on the ticket.
<p><img src="https://i.imgur.com/WTkV09w.png" height="80%" Width="80%"/></p>
<br />

Notice the admin account no longer has access to the ticket. This is because the admin account is not part of the SysAdmin department.
<p><img src="https://i.imgur.com/bbgqcXg.png" height="80%" Width="80%"/></p>
<br />



<h2>Working the Issue</h2>

Login as Jane Doe. Open the ticket.
<p><img src="https://i.imgur.com/zNHEpTW.png" height="80%" width="80%"/></p>
<br />

Click "Unassigned"
<p><img src="https://i.imgur.com/ckgQ7WP.png" height="80%" Width="80%"/></p>
<br />

Assign "Jane Doe"
<p><img src="https://i.imgur.com/m5QBEEy.png" height="80%" Width="80%"/></p>
<br />

Click "SLA Plan: Default SLA"
<p><img src="https://i.imgur.com/dP1rVzW.png" height="80%" Width="80%"/></p>
<br />

Assign Sev-A
<p><img src="https://i.imgur.com/q7xnIs3.png" height="80%" Width="80%"/></p>
<br />



<h2>Resolution</h2>
Write any notes regarding how the ticket was resolved if the same issue occurs in the future
<p><img src="https://i.imgur.com/M4fveLn.png" height="80%" Width="80%"/></p>
<br />
Click "Status: Open"
<p><img src="https://i.imgur.com/oxkJ6nl.png" height="80%" Width="80%"/></p>
<br />
Mark the ticket "Closed" to close out the ticket
<p><img src="https://i.imgur.com/xMYQbZO.png" height="80%" Width="80%"/></p>
<br />
