<h2> Active Directory Password Reset </h2>

<h2>Summary</h2>
How to Reset a Password in Active Directory. User Dwayne Plumb forgot his password and as a System Adminstrator we will help Dwayne with this issue. This outlines the steps to reset his password. 


<h2>Technology Used</h2>

- <b>Virtual Box</b> 
- <b>Windows Server 2019.iso</b>
- <b>Windows 10 Enterprise 64 bit.iso</b>

<h2>Environments Used </h2>

- <b>VM's (Virtual Machines) </b> 

<h2> Walk-through:</h2>

<p align="center">
<b>Step 1: Log into the Active Director DM(Domain Controller)</b>
<br> <br> <br/>
<br><img src="https://i.imgur.com/N2YfCin.png" height="80%" width="80%" alt="Domain Controller Main Page"/><br />

<p align="center"> 
<br><b>Step 2: In the top right corner click Tools > Active Directory Users and Computers  
<br><img src="https://i.imgur.com/ijMQuTH.png" height="80%" width="80%" alt="Users Compt"/>

<p align="center"> 
<br><b>Step 3: Find DPlumb in the Users Box and Right Click > Properties
<br><img src="https://i.imgur.com/jeCJuDh.png" height="80%" width="80%" alt="Dplumb"/>



<p align="center"> 
<br><b>Step 4: At the top of the Window Find Account and Click it. On the lower part of the box a check box lists is present. Make sure never expires is not checked. Then Click Okay
<br><img src="https://i.imgur.com/a5V3M4A.png" height="80%" width="80%" alt="Dplumb Account"/>


<p align="center"> 
<br><b>Step 5: After Clicking Okay Right Click again on DPlumb and Click Reset Password
<br><img src="https://i.imgur.com/2JZczmT.png" height="80%" width="80%" alt="Password Reset"/>

  
<p align="center"> 
<br><b>Step 6: Password Reset window will appear and check "User must change password at next logon". Then click okay.
<br><br><img src="https://i.imgur.com/SnKkBkI.png" height="80%" width="80%" alt="Password Reset 2"/></p>


<p align="center"> 
<br><b>Step 7: DPlump at his workstation. Now can choose his own password.
  
<br<br><img src="https://i.imgur.com/h2Hnc59.png" height="80%" width="80%" alt="Password Reset 3"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

