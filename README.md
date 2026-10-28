<h1> Active Directory Home Lab</h1>



<h2>Description</h2>
This project documents the creation of a virtualized Active Directory environment using Oracle VirtualBox and Windows Server 2025. The goal is to gain hands on experience with Windows Server administration, identity and access management (IAM), networking, user account management, and troubleshooting.

The lab will eventually include a Windows 11 Pro workstation joined to an Active Directory domain to simulate a small business IT environment.
<br />


<h2>Technologies and Utilities Used</h2>

- <b>Oracle VirtualBox</b> 
- <b>Windows Server 2025 Standard Evaluation (Desktop Experience)</b>
- <b>DNS — Planned</b>
- <b>Group Policy Management — Planned</b>

<h2>Lab Environments </h2>

- <table>
  <tr>
    <th>Component</th>
    <th>Configuration</th>
  </tr>
  <tr>
    <td>Host Machine</td>
    <td>Lenovo ThinkPad</td>
  </tr>
  <tr>
    <td>Hypervisor</td>
    <td>Oracle VirtualBox</td>
  </tr>
  <tr>
    <td>Virtual Machine</td>
    <td>DC01</td>
  </tr>
  <tr>
    <td>Operating System</td>
    <td>Windows Server 2025 Standard Evaluation (Desktop Experience)</td>
  </tr>
  <tr>
    <td>RAM</td>
    <td>4 GB</td>
  </tr>
  <tr>
    <td>Virtual CPUs</td>
    <td>2</td>
  </tr>
  <tr>
    <td>Virtual Hard Disk</td>
    <td>60 GB</td>
  </tr>
  <tr>
    <td>Domain</td>
    <td>ad.example.test (Planned)</td>
  </tr>
  <tr>
    <td>Client Workstation</td>
    <td>Windows 11 Pro (Planned)</td>
  </tr>
</table>

<h2>Project walk-through:</h2>
<h3>Phase 1: Windows Server 2025 Installation</h3>

<h4>Step 1: Virtual Machine Configuration</h4>

<p>
Created a virtual machine named <b>DC01</b> using Oracle
VirtualBox. Configured 4 GB RAM, 2 virtual CPUs,
a 60 GB virtual hard disk, and NAT networking.
</p>

<p align="center">
  <b>VirtualBox VM Configuration</b>
  <br/>
  <img src="https://i.imgur.com/tokCfaE.png"
       width="85%"
       alt="VirtualBox DC01 Configuration"/>
</p>

<h4>Step 2: Windows Server 2025 Installation</h4>

<p>
Installed <b>Windows Server 2025 Standard Evaluation
(Desktop Experience)</b> using the Microsoft evaluation ISO.
Verified successful installation by opening Server Manager.
</p>

<p align="center">
  <b>Windows Server Manager Dashboard</b>
  <br/>
  <img src="https://i.imgur.com/A5yzGyd.png"
       width="85%"
       alt="Windows Server 2025 Installation"/>
</p>

<h4>Step 3: Virtual Machine Snapshot</h4>

<p>
Created a snapshot named
<b>Clean Windows Server 2025 Installation</b>
to establish a recovery point before configuring
Active Directory Domain Services.
</p>

<h4>Phase 1 Outcome</h4>

<p>
Successfully deployed Windows Server 2025 in a
virtualized environment and established a recovery
point for future Active Directory configuration.
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
