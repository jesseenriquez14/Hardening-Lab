<h1>Hardening Lab</h1>

<h2>Overview</h2>
In This project I provie proof of my knowlage on some of the stratagies thaty some might use when hardening a system. There are many more I know and have practiced but these are a few I choose as an example. I would consider these entry level hardening stratagies.
(Screenshots Below)
<br />
<h1>Anti-Virus</h1>
The Anti-Virus I ran on my machine was the Immunet antivirus. This open-source Antivirus I chose to use works very well on windows server virtual machines, unlike some other anti-viruses. When commencing the scan, I had over 15,000 files to scan over which took just over 30 minutes for my machine to process fully. The scan ended up coming back completely clean, partially because of the hardening that took place, but also because the scan was completely ready to be run. This program also keeps tabs on the frequency of the scans and also suggests if a scan should be run on occasion. Although scanning and keeping tabs on the safety of your machine are essential, if proper hardening is done to a server, there should be far less entering the system. Having people try to get physically into the system is essential because it almost feels like someone brute-forcing their way in is one of the only ways. Software and commands are a great way to prevent hiccups or even moments of vulnerability, but there must be multiple other safety nets in place to assist as well. This program is simply another step in protecting a server.

<h1>Hardening Process</h1>
All of these hardening practices have a clear purpose that stops a specific potential vulnerability from penetrating a system. What was interesting to me, is why all of these measures exist but are not naturally doing what they are intended to do. What is the purpose of having to enable safe measures that pre-exist in a system? I understand that at times it can prevent basic computer functions, but are we not able to have a balance? As for the strategies, I feel the process is still very important and a must for large servers everywhere, especially those that carry important information. The hardening process could be understood as a lengthy process but is absolutely necessary to protect information.

<h2>Screenshot Refrence</h2>

1. Lynis Audit Scan

2. Disabling the automatic administrative logon on to the recovery console

3. Enabling the Windows firewall in all profiles for all domains.

4. Post analysis and disabling of ports that needed to be closed

5. Disabling of NetBIOS over TCP/IP/ remove NCACN

6. Managing windows defender settings

7. Configuring allowable encryption types for Kerberos

8. Setting LAN manager authentication level and refusing LM and NTLM

9. Disabling an unneeded service

10. Removing windows components

11. Enabling EFS with NTFS on windows server

12. Anti-Virus scan results

<h2>Screenshots</h2>
<p align="center">
1: <br/>
<img src="https://i.gyazo.com/e4e8bc4527c509abfdfeae36f91a23d3.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
2:  <br/>
<img src="https://i.gyazo.com/4bfd9b3c6f6d41ee6feaa4dbedd72baf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
3: <br/>
<img src="https://i.gyazo.com/fe8df5877c825c14aad2dc0a656c497d.png" alt="Disk Sanitization Steps"/>
<br />
<br />
4:  <br/>
<img src="https://i.gyazo.com/9cffa2b43285ebc26e78c346e47aa36d.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
5:  <br/>
<img src="https://i.gyazo.com/2379f73fe48688d46d7c964eda110234.png" alt="Disk Sanitization Steps"/>
<br />
<br />
6:  <br/>
<img src="https://i.gyazo.com/0b915be12e474ea9ee14445f817d3c55.png" alt="Disk Sanitization Steps"/>
<br />
<br />
7:  <br/>
<img src="https://i.gyazo.com/64ef132cb6866e0036b9335ee3a42d45.png" alt="Disk Sanitization Steps"/>
<br />
<br />
8:  <br/>
<img src="https://i.gyazo.com/306e3e5a35c66538fa2fff3f783b1ecf.png" alt="Disk Sanitization Steps"/>
<br />
<br />
9:  <br/>
<img src="https://i.gyazo.com/96093a497d4ea8b8035c2d0b31d53150.png" alt="Disk Sanitization Steps"/>
<br />
<br />
10:  <br/>
<img src="https://i.gyazo.com/bc2b64fa545c6ddf817684abdaa0e45d.png" alt="Disk Sanitization Steps"/>
<br />
<br />
11:  <br/>
<img src="https://i.gyazo.com/399aee1770f317db14e8dd3d10f6a12d.png" alt="Disk Sanitization Steps"/>
<br />
<br />
12:  <br/>
<img src="https://i.gyazo.com/ead78931d9ad635614301e79196a9025.png" alt="Disk Sanitization Steps"/>
<br />
<br />
<h2>Enviorments and Utilities Used</h2>

- <b>Lynis Audit Scan</b> 
- <b>Immunet Anti-virus Sofware</b>
- <b>Kali Linux</b>

<h2>Environments Used </h2>

- <b>Windows 10 (VM)</b>
