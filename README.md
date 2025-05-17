# Proton-VPN-Home-Lab

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Prerequisites</h2>

- Create a Windows 10 Pro Virtual Machine in Azure <a href="https://github.com/ian-bates-it/Azure-Virtual-Machine-Setup">as shown in Chapter 1 of the Active Directory Home Lab at this link.</a>


<h2>Connect to Windows VM</h2>


<p>
<img src="https://github.com/user-attachments/assets/ac30d48e-c7f4-418c-b4f0-94f6310383ed" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Run `mstsc.exe` or search for Remote Desktop Connection in the Windows Search Bar. Enter the server IP address and connect with the user credentials for the Windows VM.
</p>
<br />


<h2>Installation Steps</h2>

On the Windows VM, download the Proton VPN from this link <a href="https://protonvpn.com/">https://protonvpn.com/</a>
<br />
Create an account and sign up for the free plan. 
<br />
Select `Download for Windows` and select the `Windows 11/10 (x64)` option as shown below. 

<p>
<img src="https://github.com/user-attachments/assets/761ae371-e2c9-492f-9934-944bd3cab2a4" height="80%" width="80%" alt="Proton Download"/>
</p>


---
<p>Accept the UAC notification and default options.</p>
<p>Here, I unchecked the option for additional Proton Services (Proton Mail, Drive and Pass).</p>
<p>I left the "Create Desktop Short" option checked. Uncheck if you don't want the Proton VPN on your desktop.</p>
<p>
<img src="https://github.com/user-attachments/assets/65bd513b-be4a-4c92-9ee4-dce03cf7c366" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

---


<h2>Using The Proton VPN App on Azure Windows VM</h2>

Log into the Proton VPN App with the account set up in the installation step above. 
<p>
<img src="https://github.com/user-attachments/assets/18cbdcd4-75bc-458f-8ad1-603089523a61" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


---

Before turning on the Proton VPN App, you can check your Windows VM's current IP address using a site like <a href="https://whatismyipaddress.com/">https://whatismyipaddress.com/</a>

<h3>My Windows VM IP Address Without Using a VPN (20.115.81.207)</h3>
<p>
<img src="https://github.com/user-attachments/assets/aa34579b-b5f5-4404-a129-8101e49408a7" height="80%" width="80%" alt="IP Address Without VPN"/>
</p>

---

Turn on the VPN Service using the Proton VPN, by clicking the <b>Connect Now</b> button as shown below:

<p>
<img src="https://github.com/user-attachments/assets/24939f71-bd35-402d-96d2-cb687a1e179d" height="80%" width="80%" alt="IP Address Without VPN"/>
</p>

---

After turning on Proton VPN, you can verify that your IP address has changed by again visiting <a href="https://whatismyipaddress.com/">https://whatismyipaddress.com/</a>
<p>

<h3>My Windows VM IP Address WITH Proton VPN has changed to 149.22.80.118</h3>
<img src="https://github.com/user-attachments/assets/d3eb37a9-1342-4b8b-82fc-dc681588d035" height="80%" width="80%" alt="IP Address WITH VPN"/>
</p>


