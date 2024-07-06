# osTicket Configuration
<!-- <img src="" height="50%" width="50%" alt=""/> -->
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%"alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>
- Microsoft Azure (Virtual Machines/Compute)<br/>
- Remote Desktop<br/>
- Internet Information Services (IIS)<br/>

<h2>Operating Systems Used </h2>
- Windows 10 (21H2)

<h2>Post-Install Configuration Objectives</h2>
- Configure Roles<br/>
- Configure Departments<br/>
- Configure Teams<br/>
- Configure Agents<br/>
- Configure Users<br/>
- Configure SLA<br/>
- Configure Help Topics<br/>

<h2>Configuration Steps</h2>

<h3 align="center">Configure Roles</h3>
<p>
  <h4>Admin Panel -> Agents -> Roles -> Add New Role.</h4>
  Supreme Admin
  <img src="https://i.imgur.com/agEjxlI.png" height="50%" width="50%" alt="Definition"/>
  <img src="https://i.imgur.com/326mN73.png" height="50%" width="50%" alt="permissions tickets"/>
  <img src="https://i.imgur.com/AcY7CRu.png" height="50%" width="50%" alt="permissions tasks"/>
  <img src="https://i.imgur.com/SJvi6Xq.png" height="50%" width="50%" alt="permissions knowledgebase"/>
  <img src="https://i.imgur.com/2skWycK.png" height="50%" width="50%" alt="new role added"/>
</p>
<br />
<h3 align="center">Configure Departments</h3>
<p>
  <h4>Admin Panel -> Agents -> Departments -> Add New Department.</h4>
  <h4>System Administrators:</h4>
  <img src="https://i.imgur.com/CNaH0Y7.png" height="50%" width="50%" alt="sys admin"/>
</p>
<br />
<h3 align="center">Configure Teams</h3>
<p>
  <h4>Admin Panel -> Agents -> Teams -> Add New Team.</h4>
  Level II Support:
  <img src="https://i.imgur.com/lGtLOcM.png" height="50%" width="50%" alt="level II support"/>
</p>
<br />

<h3 align="center">Allow anyone to create ticket</h3>
<p>
  <h4>Admin Panel -> Settings -> User Settings.</h4>
  Ensure "Require registration and login to create tickets" box is not selected:
  <img src="https://i.imgur.com/5NRQ7Yz.png" height="50%" width="50%" alt="user settings"/>
</p>
<br />
<h3 align="center">Configure Agents (workers)</h3>
<p>
  <h4>Admin Panel -> Agents -> Add New.</h4>
  Jane Doe:
  <img src="https://i.imgur.com/zqOycRj.png" height="50%" width="50%" alt="agent one account"/>
  <img src="https://i.imgur.com/cTsn1NE.png" height="50%" width="50%" alt="agent one access"/>
  John Doe:
  <img src="https://i.imgur.com/UForoLL.png" height="50%" width="50%" alt="agent two account"/>
  <img src="https://i.imgur.com/LkA0apR.png" height="50%" width="50%" alt="agent two access"/>
</p>
<br/>
<h3 align="center">Configure Users (customers)</h3>
<p>
  <h4>Agent Panel -> Users -> Add New.</h4>
  Create users by inputting email address and full name.
  <img src="https://i.imgur.com/qgwRKBl.png" height="50%" width="50%" alt="user one"/>
</p>
<br />
<h3 align="center">Configure SLA</h3>
<p>
  <h4>Admin Panel -> Manage -> SLA -> Add New SLA Plan.</h4>
  Sev-A (1 hour, 24/7).<br/>
  <img src="https://i.imgur.com/9pKXq4h.png" height="50%" width="50%" alt="sev a"/>
  Sev-B (4 hours, 24/7).<br/>
  <img src="https://i.imgur.com/TKLk0yD.png" height="50%" width="50%" alt="sev b"/>
  Sev-C (8 hours, business hours).<br/>
  <img src="https://i.imgur.com/P0alA4g.png" height="50%" width="50%" alt="sev c"/>
</p>
<br />
<h3 align="center">Configure Help Topics</h3>
<p>
  <h4>Admin Panel -> Manage -> Help Topics -> Add New Help Topics -> Complete Fields.</h4>
  <img src="https://i.imgur.com/Y5RYc8P.png" height="50%" width="50%" alt="help topics"/>
</p>
<br />
<p>
  This concludes configuring osTicket. I hope this tutorial taught you how to configure some elements in osTicket. Thank you for stopping by and checking out this tutorial. Have a wonderful day.
</p>
