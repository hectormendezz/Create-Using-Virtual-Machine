
<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of Virtual Machines and how to use it.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/Rg1w7kv.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
The first step into creating a Virtual Machine (VM) is to actually create a Resource Group (RG). So, we start off by opening up Microsoft Azure and locating the "resource group" tab. This is where you will create the your RG, this acts as a folder where you can store all of your resources and things you create. I named mine "RG-1" just to keep it simple, then put the location to the most accurate location to me. 
</p>
<br />

<p>
<img src="https://i.imgur.com/4NLVlBX.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Giqocpk.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that you have completed the first step, we can now start creating the virtual machine. Look for the "Virtual Machine" tab, click on it and then you will be on creation settings page for VMs. First we will select what resource group we want this VM to be in so we can put it into the RG we already made, "RG-1", then name this virtual machine VMachine-1. Now we can add the location we want and for the software we will choose Windows 10.
</p>
In the second photo above, you will see that this is where you create an administrative username and password. My username is "HectorM" and then created my own password, this is up to you to make your own but it just has to be something you can remember because you will need it later to login to the VM. Click "Review + Create" when you are all set with your settings. 
</p>
<br />

<p>
<img src="https://i.imgur.com/Xupq0k1.jpeg" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/yG6gBG5.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
On to this next step, we will go to our virtual machine's setting page. This is where we will find the public IP Address, this is important because we need this to login into our VM on Microsoft Remote Desktop. In the pictures above you will be able to see the VM settings page and where exactly the IP Address is, which is located in the bottom right of the first picture in this step. Copy the IP address and move on to the next step.
</p>
<br />

<p>
<img src="https://i.imgur.com/IDUvPjJ.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is the final step, here you will open up your Microsoft Remote Desktop app. You can click "Add PC" and it will ask for either a host name or ip address, this is where you paste the ip address for your virtual machine. Now click on your virtual machine and a prompt should pop up asking for your login information, in some of the earlier steps we created a username and password, you should refer back to those steps for that information. Once you have now succesfully logged in to your virtual machine. You now have full access to Windows 10 and the functionality of a physical computer but only virtually. Congratulations!
</p>
<br />
