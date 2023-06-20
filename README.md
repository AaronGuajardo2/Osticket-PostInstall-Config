<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Configuration Steps</h2>

Now that we have Osticket installed we can start configuring roles and corresponding responsibilities. 
First, go to a browser window within your Virtual Machine and type in "localhost/osTicket/scp/login.php" and log in with the user credentials you created in the Osticket-Prereq tutorial.
<p>
<img src="https://imgur.com/3JA5JQd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Once logged in navigate to the admin panel, go to Agents->Roles-> add a new role. In this instance, the role will be called "Supreme Admin". This role will have full access so check all available permissions. Next, we will add a department named "System Administrators".
<p>
<img src="https://imgur.com/Xdxkww1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://imgur.com/dDm2Zmi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://imgur.com/0aObyvI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
</p>
<br />

Next, we will create a new "Team". Go to Agents then Teams and name it Level II Support and add yourself as an Admin agent. Then we will create Jane Doe as a fictional agent who is employed by an organization and add them to the System Administrator department. This person will be tasked with troubleshooting tickets in a later tutorial.

<p>
<img src="https://imgur.com/gWfAwQd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://imgur.com/UECdlr3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
</p>
<p>
<img src="https://imgur.com/c3UDybG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />


Before we add users we are going to make sure they will be able to create and submit tickets. Go into Settings then Users and make sure Registration Required is unchecked.
</p>
<img src="https://imgur.com/fc8tTo2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>

After that, we're going to add users. Go to Agent Panel-> Users -> Add New. We can make up any name we want.
<p>
<img src="https://imgur.com/4IKWUmx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://imgur.com/3YmfN7y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://imgur.com/9oje4ef.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

Alright, now let's configure SLA. SLA plans, or Service Level Agreements, provide a length of time in which help desk admins expect tickets to be closed depending on the severity of the ticket. To configure, go to Admin Panel -> Manage -> SLA -> Add New SLA. Create 3 new SLA plans each with descending Severity level.
<p>
<img src="https://imgur.com/JkYzmHf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://imgur.com/LvV599b.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://imgur.com/Ll4034t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

Lastly, configure help topics by going to Admin Panel -> Manage -> Help Topics. Add the following: Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset. These help users categorize their tickets.
<p>
<img src="https://imgur.com/sOA4d1g.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://imgur.com/O1f9Gyf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<p>
</p>
<br />
In the next tutorial, we will simulate a ticket request from initial intake to resolution.


