<h1>Home Lab - Managing Users in Active Directory</h1>

<h2>Description</h2>
In this virtual machine, I demonstrate managing, implenting changes, and delegating users in Active Directory.  
<br />


<h2>Languages and Utilities Used</h2>

- <b>Windows Framework</b> 

<h2>Environments Used </h2>

- <b>Windows Server 2019</b>

<h2>Program walk-through:</h2>


- <b>Create New Organizational Unit</b> <br />
First, as a Domain Administrator, I viewed the OU named THM with five child OU's listed. I then created a new OU named "Students" by right-clicking THM selecting new then organizational unit.
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectory1.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />                                                                                                                                                    
<br />

- <b>Reviewing Users and Policies</b> <br/>
After reviewing the users in the IT department, I can see they have a limited set of polices respectable to what they are allowed to access. Password resets may also be initiated if needed. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectory2.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<br />

- <b>Deleting Extra OU's and Users</b> <br />
To complete deletion of a particular OU, I enabled from the Advanced Features in the view menu. <br/>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectory3.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
  
By default, OU's are protected against accidental deletion. To delete the OU, I need to enable the Advanced Features. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectory4.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
  
Finally, deletion can now be completed after disabling the object. <br/>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectory5.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<br />

- <b>User Delegation</b> <br />
The IT department should be granted privileges to reset other low-privelege users' passwords. Below will demonstrate on how a particular user will be granted control over other departments. First, by right-clicking on the OU, the delegate control option is chosen. <br/>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectory6.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

Phillip being the head of IT support, will be delegating control for the Sales department along with other respective departments. After clicking add, I typed in Phillip and selected to check names ensuring no errors.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectory7.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

Once the user has been added, the Control Wizard prompts for tasks to delegate. I choose the reset password option and will repeat these steps for other departments.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectory8.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<br />

- <b>Summary</b> <br />
I demonstrated using Windows Active Directory with modeling a VM to manage, delete, and create OU's. 
<br />
<br />
