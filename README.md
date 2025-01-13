<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial provides a detailed overview of the prerequisites and step-by-step instructions for installing the open-source help desk ticketing system, osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 November 2021 Update (Version 21H2)

<h2>List of Prerequisites</h2>

- IIS (Internet Information Services) W/ CGI
- PHP Manager for IIS
- Microsoft URL Rewrite Module for IIS (x64)
- PHP 7.3.8 Non-Thread Safe (NTS) for Windows (x86)
- Microsoft Visual C++ 2015-2019 Redistributable (x86)
- MySQL Community Server 5.5.62

<h2>Installation Step 1: Setup a Virtual Machine in Azure </h2>

<p>
<img src="https://i.imgur.com/Dz7njNQ.png"/>
</p>
<p>
To create a virtual machine in Azure, navigate to the Virtual Machines section.
</p>
<br />

<p>
<img src="https://i.imgur.com/fQ0LMOl.png"/>
</p>
<p>
Next, click the "Create" dropdown button, highlighted in blue.
</p>
<br />

<p>
<img src="https://i.imgur.com/Nk76zt5.png"/>
</p>
<p>
Next, select "Azure Virtual Machine" on the dropdown menu.
</p>
<br />

<p>
<img src="https://i.imgur.com/DiHCgLV.png"/>
</p>
<p>
Next, enter the project details in the resource group and name it "OS-Ticket."
</p>
<br />

<p>
<img src="https://i.imgur.com/lIfT0RL.png"/>
</p>
<p>
Next, name the VM "OSticket-vm"
</p>
<br />

<p>
<img src="https://i.imgur.com/KES4AI6.png"/>
</p>
<p>
Select, the image Windows 10
</p>
<br />

<p>
<img src="https://i.imgur.com/mSZUu9b.png"/>
</p>
<p>
Select a virtual machine size that includes at least 2 vCPUs to ensure sufficient processing power for your needs.
</p>
<br />

<p>
<img src="https://i.imgur.com/0weHDLA.png"/>
</p>
<p>
Fill out the username and password fields, ensuring that the password meets the required security criteria, such as including a mix of uppercase and lowercase letters, numbers, and special characters for better protection.
</p>
<br />

<p>
<img src="https://i.imgur.com/oxVaHJj.png"/>
</p>
<p>
For licensing, please check the box.
</p>
<br />

<p>
<img src="https://i.imgur.com/zNl5fus.png"/>
</p>
<p>
Please note that the system pre-fills most tabs, and at this point, you will not need to make any changes or adjustments. Click "Next" until you reach the "Review and Create" section.
</p>
<br />

<p>
<img src="https://i.imgur.com/d2bOUvT.png"/>
</p>
<p>
Now, review and create Virtual Machine, and notice it states "Deployment in progress".
</p>
<br />

<p>
<img src="https://i.imgur.com/KIOXPBJ.png"/>
</p>
<p>
Congratulations! If all allocations are correct, you will have successfully created a virtual machine on your resource page with a valid IP address.
</p>
<br />

<h2>Installation Step 2: How to Connect to Remote Desktop and Install the osTicket Requirements. </h2>

<p>
<img src="https://i.imgur.com/5QHNzKD.png"/>
</p>
<p>
Open Remote Desktop on your computer, enter the public IP address of the virtual machine previously created on Azure, and press Connect.
</p>
<br />

<p>
<img src="https://i.imgur.com/PeMqNl3.png"/>
</p>
<p>
Enter the secure username and password you created earlier and press Enter.
</p>
<br />

<p>
<img src="https://i.imgur.com/VHiOCR6.png"/>
</p>
<p>
You should now be logging into the virtual machine on your desktop.
</p>
<br />

<p>
<img src="https://i.imgur.com/q19BpWf.png"/>
</p>
<p>
Once you are on the virtual machine desktop, open Microsoft Edge, and download all required files.
</p>
<br />

<p>
<img src="https://i.imgur.com/oTfuD6T.png"/>
</p>
<p>
Utilizing this link, we will install the requirements needed to set up osTicket.
[https://drive.usercontent.google.com/download?id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD&export=download&authuser=0]
</p>
<br />

<h2>Installation Step 3: How to Install the OS Ticket requirements </h2>

<p>
<img src="https://i.imgur.com/P8gzBzq.png"/>
</p>
<p>
Once files have been downloaded, navigate to your downloaded file, right click and select extract all.
</p>
<br />

<p>
<img src="https://i.imgur.com/HsZThTq.png"/>
</p>
<p>
Browse the destination folder and nevigate to desktop and press extract.
</p>
<br />

<p>
<img src="https://i.imgur.com/kEgCfjH.png"/>
</p>
<p>
Now, navigate to the Control Panel on your VM, notice the "Programs," section and then choose "Uninstall a program," highlighted in blue underneath "Programs."
</p>
<br />

<p>
<img src="https://i.imgur.com/RkL3bde.png"/>
</p>
<p>
In the next window, select "Turn Windows features on or off." Located on the left side of the menu.

<p>
<img src="https://i.imgur.com/DAsvV7c.png"/>
</p>
<p>
When the "Turn Windows features on or off" window opens, expand "Internet Information Services."
</p>
<br />

<p>
<img src="https://i.imgur.com/OrmkRF3.png"/>
</p>
<p>
Expand "Application Development Features," select "CGI," press "OK," and allow the system to update."
</p>
<br />

<p>
<img src="https://i.imgur.com/RJ4dkQ3.png"/>
</p>
<p>
From your desktop, open the file folder that was downloaded.
</p>
<br />

<p>
<img src="https://i.imgur.com/SuWaYMU.png"/>
</p>
<p>
Extract and install PHP Manger.
</p>
<br />

<p>
<img src="https://i.imgur.com/CGLgwDz.png"/>
</p>
<p>
Rewrite AMD file
</p>
<br />
