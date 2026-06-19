<h1>Home Lab - Managing Users in Active Directory</h1>

<h2>Description</h2>
In this virtual machine, I demonstrate managing and implenting changes in Active Directory.  
<br />


<h2>Languages and Utilities Used</h2>

- <b>Windows Framework</b> 

<h2>Environments Used </h2>

- <b>Windows Server 2019</b>

<h2>Program walk-through:</h2>


- <b>Create New Organizational Unit</b> <br />
First, as a Domain Administrator, I viewed the OU named THM with five child OU's listed. I then created a new OU named "Students" to demonstrate a new task.  <br/>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectory1.jpg" height="75%" width="75%" alt="Disk Sanitization Steps"/>
</p>
<br />                                                                                                                                                    
<br />

- <b>Reviewing Users and Policies</b> <br/> <br />
After reviewing the users in the IT department, I can see they have a limited set of polices respectable to what they are allowed to access. Password resets may also be initiated if needed. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectory2.jpg" height="40%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />
<br />

- <b>Deleting Extra OU's and Users</b> <br />
I demonstrate below how to delete a department OU from a domain. First, I enabled from the Advanced Features in the view menu. <br/>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectory3.jpg" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<br />
By default, OU's are protected against accidental deletion. To delete the OU, I need to enable the Advanced Features in the view menu. <br/>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectory4.jpg" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<br />
<br />

- <b>Querying log repository with KQL</b> <br />
A query using KQL searching for "SecurityEvent" was made to observe general logs.  <br/>
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/AzureSentinelVM/blob/main/images/ConnectVMToLogAnalyticsWorkspace4.jpg" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />
<br />

- <b>Applying specific KQL queries</b> <br />
To narrow the search results, I applied "where" in "EventID" for event "4625." Specifically, "TimeGenerated, Account, Computer, EventID, Activity, IpAddress" further narrowed down the search to filter results of interest. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/AzureSentinelVM/blob/main/images/ReviewingLogRepositoryWithFilters6.jpg" height="65%" width="65%" alt="Disk Sanitization Steps"/>
<br />
<br />

- <b>Geolocation data upload to SIEM</b> <br/>
A spreadsheet containing geolocation of IP addresses was uploaded to provide mapping ranges.<br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/AzureSentinelVM/blob/main/images/GeoIPUploadedSheet7.jpg" height="35%" width="35%" alt="Disk Sanitization Steps"/>
</p>
<br />
<br />

- <b>Sentinel workbook for map</b> <br/>
A new workbook within sentinel was created using a data from a json file. Data was then copy and pasted for a new query.<br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/AzureSentinelVM/blob/main/images/UploadGeoIPInWatchlistSentinel8.jpg" height="65%" width="65%" alt="Disk Sanitization Steps"/>
</p>
<p align="center">
<img src="https://github.com/DanielYoon82/AzureSentinelVM/blob/main/images/CreatedWorkbookInSentinelForMAp9.jpg" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />

- <b>Creation of attack map</b> <br/>
As a result, an attack map showing logs from around the world illustrated where events had taken place.<br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/AzureSentinelVM/blob/main/images/WorldMapOfLogIns10.jpg" height="65%" width="65%" alt="Disk Sanitization Steps"/>
<p align="center">
</p>
<br />
<br />

- <b>Summary</b> <br />
I demonstrated using Azure with modeling a VM to open up the network of cloud firewall to the internet. The data in the log repository was then forwarded to the log analytics workspace as a central repository. A spreadsheet containing geo data was implented in Sentinel (SIEM) to monitor log in activity using KQL filters. Finally, the result illustrated on a world map showing these events.
<br />
<br />
