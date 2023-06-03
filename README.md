<p align="center">
<img src="https://i.imgur.com/iUHgW7D.jpg" alt="Traffic Examination"/>
</p>

<h1>Installing A VPN On An Azure Virtual Machine</h1>
In this tutorial, we will install proton vpn on our Azure virtual machine and check it's IP address pre and post installation. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- whatsmyipaddress.com
- ProtonVPN


<h2>Operating System Used </h2>
- Windows 10 (22H2)

<h2>High-Level Steps</h2>

- Step 1: Create a subscription using your Microsoft account in Microsoft Azure   
- Step 2: Create a VM in Microsoft Azure 
- Step 3: Setup remote desktop to access Azure VM  
- Step 4: Test connection to VM using command prompt 
- Step 5: Use an internet Browser to download a VPN 

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/eNdY7X9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The first thing we must do when downloading a VPN on a VM is to create a VM. BY using my Microsoft Azure subscription I created a VM that uses a differnt loctaion than my current desktop. Then we must remote desktop into the VM. 
</p>
<br />

<p>
<img src="https://i.imgur.com/B5KkCOi.png" height="55%" width="80%" alt="Disk Sanitization Steps"/>
</p>
After using remote desktop to connect to the VM I checked the VMs IP address using whatismyipaddress.com to make sure the location I choose in the creation of the VM matched the IP address appearing in the websites report. 
</p>
<br />

<p>
<img src="https://i.imgur.com/kVjB1xG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  <p>
Now that I've checked the VMs IP address we can now download Proton VPN. First create an account then procced to the free version of the Proton VPN download. 
</p>
<br />

<p>
  <img src="https://i.imgur.com/qdC4Ek0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
<img src="https://i.imgur.com/WmQhTWa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
After downloading the application and either pressing quick connect or connecting to a specific country/region the connection to the VM might drop due to the VM and VPNs internet connection classhing. Now that you have connected to the region of your choosing you can go back to the website whatismyipaddress.com to check your new IP address. 
</p>
<br />


<p>
  <img src="https://i.imgur.com/HnsAzKU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
<img src="https://i.imgur.com/RwdhJKr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
That is how you install a VPN on to Microsofts Azure VM. Once you finish make sure to delete all the resources used in the creation of the VM so as not to accrue any charges simply from the existence of the VM.  
</p>
<br />
