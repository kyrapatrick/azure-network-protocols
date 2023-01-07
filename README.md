<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
Observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />




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

- Create Azure virtual machines:Windows 10; Ubuntu 
- Understand Firewalls via Network Security Groups
- Install protocol analyzer Wireshark
- Work with various Ports & Protocols

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/U4ctsEI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install and open Wireshark.
</p>
<br />

<p>
<img src="https://i.imgur.com/B4rAxF0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Windows 10 and Ubuntu virtual machines shown along with netwotwork security groups.
</p>
<br />

<p>
<img src="https://i.imgur.com/FAjFSR7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Observe ICMP traffic.
</p>
<br />
<p>
<img src="https://i.imgur.com/vh00orG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Disable ICMP inbound traffic in Ubuntu virtual machine Network Security Group.
</p>
<br />
<img src="https://i.imgur.com/BYpA9BH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Observe SSH traffic.
</p>
<br />
<p>
<img src="https://i.imgur.com/U0vQNHB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Observe DHCP traffic.
</p>
<br />
<p>
<img src="https://i.imgur.com/E4TY41a.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Observe DNS traffic.
</p>
<br />
<p>
<img src="https://i.imgur.com/HQlkDEa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Observe RDP traffic via filtering TCP Port 3389.
</p>
<br />
<p>
<img src="https://i.imgur.com/WKXVThb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Observe Observe Ubuntu commands.
</p>
<br />

