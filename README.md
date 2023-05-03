<p align="center">
<img src="https://i.imgur.com/TpTvrlK.png" alt="osTicket logo"/>
</p>

<h1>Active Directory Bulk User Creation</h1>




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Powershell ISE

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)


<h2>Practice</h2>
We are going to practice our new skills by creating many users and apply what we learned about active directory.

<p>
<img src="https://i.imgur.com/KlwI3VA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/vj32xA3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We will create 1000 users via Powershell ISE using a script. We will do this by entering the script above and running it. 
</p>
<br />

<p>
<img src="https://i.imgur.com/icqAkuA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We will go back to "Active Directory Users and Computers"->mydomain.com->_EMPLOYEES->*choose any user, just write down the name to remember it*->right click->properties->copy name.
</p>
<br />

<p>
<img src="https://i.imgur.com/XLGdVAn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We will connect to Client-1's machine with the username that we chose from the "_EMPLOYEES" organizatonal unit from DC-1. Our username will be "mydomain.com\[username]" and our generic password was "Password1". When we successfully login, we can go to the command line an type "whoami" just to confirm we are logged in as a new user.
</p>
<br />

<p>
<img src="https://i.imgur.com/rc3gvv7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We can use Active Directory to unlock people's accounts if they ever get their account locked. We can choose any user from the "_EMPLOYEES" folder->right click->properties->account->unlock account. You can also reset users' passwords by right clicking on their name->reset password
</p>
<br />
