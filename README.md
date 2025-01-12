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
<img src="https://i.imgur.com/fQ0LMOl.png"/>
</p>
<p>
To create a virtual machine in Azure, navigate to the Virtual Machines section and click the "Create" dropdown button, highlighted in blue.
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
Please note that the system pre-fills most tabs, and at this point, you will not need to make any changes or adjustments.
</p>
<br />

<p>
<img src="https://i.imgur.com/zNl5fus.png"/>
</p>
<p>
</p>
<br />

<p>
<img src="https://i.imgur.com/d2bOUvT.png"/>
</p>
<p>
Now, review and create Virtual Machine, and notice it states "Deployment in progress".
</p>
<br />
