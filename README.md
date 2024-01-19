<h1>Active Directory Home Lab</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
In this lab we're going to walk through how to create an Active Directory Home Lab Environment using Oracle Virtual Box. Configuring and running this lab will definitely help your understanding of how active directory and windows networking works, so i'd recommend running through it a couple times, ask questions where stuff is unclear and eventually try to build it on your own without watching. Please let me know if you have any questions.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle Virtual Box</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Server 2019</b>

<h2>Program walk-through:</h2>

<p align="center">
Active Directory Network Diagram: <br/>
<img src=https://i.imgur.com/T0vWgC3.png" height="80%" width="80%" alt="Active Directory Home Lab steps"/>
<br />
<br />
Download Oracle VN Virtualbox with extension pack: <br/>
https://www.virtualbox.org/wiki/Downloads
<img src=https://imgur.com/MVgav8K.png" height="80%" width="80%" alt="Active Directory Home Lab steps"/>
<br />
<br />
Download Windows 10 ISO and Windows Server 2019 ISO: <br/>
https://www.microsoft.com/en-us/software-download/windows10ISO
https://www.microsoft.com/en-us/evalcenter/download-windows-server-2019
<br />
<br />
Create Domain Controller Virtual Machine and set version to other windows 64 bit: <br/>
<img src=https://imgur.com/9NV4qRp.png" height="80%" width="80%" alt="Active Directory Home Lab steps"/>
<br />
<br />
Set to bidirectional: <br/>
<img src=https://imgur.com/8dSRKs4.png" height="80%" width="80%" alt="Active Directory Home Lab steps"/>
<br />
<br />
Under system tab set processor cores (recommended at least 2 cores to allocate): <br/>
<img src=https://imgur.com/Y3DCCNb.png" height="80%" width="80%" alt="Active Directory Home Lab steps"/>
<br />
<br />
Under network tab set adapter 1 as NAT, enable adapter 2 and set as internal network: <br/>
<img src=https://imgur.com/Er2WB1l.png" height="80%" width="80%" alt="Active Directory Home Lab steps"/>
<br />
<br />
Launch VM, add Windows Server 2019 iso: <br/>
<img src=https://imgur.com/GrzB8Xe.png" height="80%" width="80%" alt="Active Directory Home Lab steps"/>
<br />
<br />
Installing Windows Server ISO, click standard edition desktop experience for a GUI: <br/>
<img src=https://imgur.com/7esawWA.png" height="80%" width="80%" alt="Active Directory Home Lab steps"/>
<br />
<br />
Custom install then press next: <br/>
<img src=https://imgur.com/igv5O4a.png" height="80%" width="80%" alt="Active Directory Home Lab steps"/>
<br />
<br />
Set password as Password1 for this lab to keep it simple: <br/>
<img src=https://imgur.com/9OsG7oM.png" height="80%" width="80%" alt="Active Directory Home Lab steps"/>
<br />
<br />
Under devices click insert guest image for faster user experience: <br/>
<img src=https://imgur.com/suEba1v.png" height="80%" width="80%" alt="Active Directory Home Lab steps"/>
<br />
<br />
Under file explorer click this pc, then click virtualbox guest addition, then run and install the executable that ends in amd64, reboot and shut VM down: <br/>
<img src=https://imgur.com/Vtj1JUh.png" height="80%" width="80%" alt="Active Directory Home Lab steps"/>
<img src=https://imgur.com/ASFqsVo.png" height="80%" width="80%"
<br />
<br />



 
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
