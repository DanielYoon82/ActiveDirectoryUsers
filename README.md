<h1>Home Lab - Managing Users in Active Directory</h1>

<h2>Description</h2>
In this virtual machine I demonstrate user management and a password reset in Active Directory.  
<br />


<h2>Languages and Utilities Used</h2>

- <b>Windows Framework</b> 

<h2>Environments Used </h2>

- <b>Windows Server 2019</b>

<h2>Program walk-through:</h2>


- <b>Create New User Account</b> <br />
John Doe is a new hire for the head of the Sales Department. I am assigned to create him as a new user for onboarding. First, I right-click on the Sales OU, then select user.
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser1.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br /> 

I proceed with inputting his name and logon name. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser2.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

A temporary password is set for the user in which they must change with their own unique one thereafter. Setting up the new user is now complete. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser3.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Congifuring Group Membership</b> <br/>
The head of the Sales Department asked to have the new hire added to their department. I right-click on the new user and choose properties.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser4.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

The "Member Of" tab was chosen then a group added. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser5.jpg.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<br />

- <b>Summary</b> <br />
I demonstrated using Windows Active Directory with modeling a VM to manage, delete, and create OU's. I created an OU and enabled the advanced features to allow a removal of an OU as well. Password reset priveleges was given using steps to delegate control towards applicable departments. Adjustments within Active Directory is an ever-constant effort as these instances can occur in a real-world setting. 
<br />
<br />
