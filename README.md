<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Create a Resource Group inside of Microsoft Azure
- Create a Virtual Network within Microsoft Azure
- Create a Subnet inside of the Virtual Network
- Create 2 Virtual Machines from Microsoft Azure, one of the VM's is running Windows 10 pro and the other VM is running Linux Ubuntu

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/aHsW17t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Through Microsoft Azure Cloud Computing, I am able to go into NSG(Network Security Groups) and allow certain kind of traffic through. Such in this case, I am denying any traffic that protocol ICMP is sending over. I have also prioritized the protocol ICMP to be the first to receive any data, coming right before SSH protocol.
</p>
<br />

<p>
<img src="https://i.imgur.com/aHsW17t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
