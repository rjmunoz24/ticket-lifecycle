<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
For this project, I used a persona named Karen to submit a support ticket through the end-user portal at localhost/osticket, while accessing the admin and analyst interface via localhost/osticket/scp/login.php. To manage and execute the project, I utilized Azure to create a resource group and set up a virtual machine, using remote desktop to interact with the system. During the investigation, I discovered that a recent update was causing an issue with the online banking system. By uninstalling the update and rolling back the system to its previous state, I was able to resolve the problem and restore normal operation.<br />

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
<img src="https://i.imgur.com/JumCd0v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Karen submitted a ticket for online banking, but no one had access. Support tech John reviewed the issue and escalated it, realizing it was more serious. He reassigned the ticket to Jane, the Sev-A lead, and added notes in the comments to keep her informed.
</p>
<br />

<p>
<img src="https://i.imgur.com/INUpZAv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Logged in as Jane in osTicket. She suspects the issue may be linked to recent updates. "We tested them thoroughly, but I'll investigate further and roll them back if I find they’re the cause."
</p>
<br />

<p>
<img src="https://i.imgur.com/FE9Ggbi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To resolve the issue, Jane accessed the backend and checked the online banking system. Jane identified that a recent update was the cause, so she uninstalled it, rolled back the system, and the problem was fixed.
</p>
<br />
