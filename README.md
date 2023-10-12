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

- Step 1: create two virtual machines
- Step 2: Observe ICMP traffic 
- Step 3: Observe SSH Traffic
- Step 4: Observe DHCP traffic
- Step 5: Observe DNS Traffic
- Step 6: Obserce RDP Traffic

<h2>Actions and Observations</h2>

![Screenshot 2023-08-27 201827](https://github.com/jeredforte/Securitygroups/assets/143118208/69c3948c-673a-462f-ab86-7db9ef4b5eb5)
First create a resource group that has two virtual machines on the same virtual network and subnet. Make one of them windows 10 and the other linux
</p>
<br />


![Screenshot 2023-08-27 205152](https://github.com/jeredforte/Securitygroups/assets/143118208/2b98c16b-54e5-478b-81d9-9fff5e807057)
use remote destop to acess your window 10 virtual machine and open wireshark and filter for ICMP track. retrive the private IP address from your Linux and attempt to ping it observe the ping request and replys.
</p>
<br />

<p>
</p>
<br /># Securitygroups
