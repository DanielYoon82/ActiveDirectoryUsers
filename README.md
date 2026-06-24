<h1>Home Lab - Managing Users in Active Directory</h1>

<h2>Description</h2>
In this virtual machine I demonstrate user management, unlocking an account, and password reset in Active Directory.  
<br />


<h2>Languages and Utilities Used</h2>

- <b>Windows 10</b> 

<h2>Environments Used </h2>

- <b>Windows Server 2019</b>

<h2>Program walk-through:</h2>


- <b>Create New User Account</b> <br />
John Doe is a new hire for the head of the Sales Department. I am assigned to create him as a new user for onboarding. First, I right-click on the Sales OU, then select user.
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser1.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br /> 

I proceed with inputting his name and logon name (according to policies for this simulated company). <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser2.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

A temporary password is set for the user in which they must change with their own unique one thereafter. Setting up the new user is now complete. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser3.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Congifuring Group Membership</b> <br/>
The head of the Marketing Department requested to add the new hire added to their group. I right-click on the new user and choose properties.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser4.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

The "Member Of" tab was chosen then a group added. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser5.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

"Check Names" option was chosen for marketing to verify the group was correct completing group configuration.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser6.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Deleting and Disabling User Accounts</b> <br/>
HR has notified me that one employee will no longer will be with the company and another will be taking a temporary leave. I am tasked with deleting and disabling their accounts. First, I will delete Robert's account to take effect immediately. I right-click on the user and choose delete.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser7.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

For the user that will be taking a temporary leave, I right-click and choose disable. Upon the employee's return, I will enable the user to restore accessibility. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser8.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Unlocking Account and Resetting Password</b> <br/>
An employee called and stated that her account has been locked out due to multuple log in attempts and forgetting her password. A request was made to also reset the password. I first right-click on users and find the name.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser9.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

I navigate to the account tab and choose the box "Unlock Account" and click apply successfully unlocking the account. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser10.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

I then proceed with right-clicking the user and choose the reset password option. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser11.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

Password has been chosen and the user has been notified to change the password at next logon achieving user resolution. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser12.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Summary</b> <br />
I demonstrated using Windows Active Directory with modeling a VM in creating, configuring, deleting, and disabling user accounts. In addition, unlocking and resetting a password was carried out using real-world scenarios. These common tasks are vital to user management protocol and done offhand frequently. 
<br />
<br />
