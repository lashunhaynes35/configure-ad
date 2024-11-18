<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Domain Controller configuration
- DNS Settings changed to Private
- DNS Private IP address ping
- Conformation of DNS Private IP address is set 

<h2>Deployment and Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/73ab3f43-709e-42e6-9e00-a1754a54951d)
Changing domain controller Private IP address to Static 


![image](https://github.com/user-attachments/assets/804ac8d0-9755-4b50-8bc7-7c48ce1d7f8c)
Changing DNS settings to Private IP address.


![image](https://github.com/user-attachments/assets/fd442245-a534-4b31-9245-5526a59bab30)
Ping DNS Private IP address.


![image](https://github.com/user-attachments/assets/c9a3b207-7aaf-44f7-b860-a8e8fb071a03)
ipconfig /all shows DNS server is private.


