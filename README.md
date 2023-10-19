# VPN Setup and Usage With Proton VPN

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/fe3ad9c5-4985-4de0-bfea-0088cdc5c11c)


In this tutorial, we are going to make a VPN using Proton VPN and measure the different IP addresses. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- Proton VPN
- Whatsmyipaddress.com


<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Use whatsmyipaddress.com to grab your current IP address
- Create a Virtual Machine in Microsoft Azure
- Log into the virtual machine using Remote Desktop Connection
- Use whatsmyipaddress.com to grab your VM IP address
- Download Proton VPN then connect to any VPN
- Use whatsmyipaddress.com to grab your new Proton VPN IP address


<h2>Actions and Observations</h2>

<p>
Go to whatismyipaddress.com and copy your current IP address.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/66e9024c-fb7b-4a3d-a21c-4cf2d1950a85)

<p>
Open Microsoft Azure and search Virtual Machine.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/f83f697c-bceb-47b2-87cb-31437199122d)

<p>
Select 'Create' and go to Azure Virtual Machine.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/7eb1a45a-1fa5-4fc4-aedb-00c0045ac3eb)

<p>
Go to the Resource Group tab and click 'Create New', the name will be Vm-practice. then click the blue OK button.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/d8d64682-d983-4d30-a330-bd6ff1de9e6a)

<p>
Now go to the Virtual Machine name and type VMP, For the region I will put there is the option to select a different location to the one you are in. Image click Windows 10 Pro version.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/c698d127-9381-434a-9cb0-80d629aad402)

<p>
Select size option of 2+ virtual CPU, Enter username and password.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/77d58e71-fb68-4fc9-84ee-8085d071783b)

<p>
Review and Create tab and click Create on the bottom left side.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/fd709eb3-9043-4b3e-b8f7-2c8da084d44e)

<p>
Wait for Azure to set up the Virtual Machine, usually takes a minute or two.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/5755c1b0-a933-43f0-b50c-278795d01a35)

<p>
Type Virtual Machine and you will see VMP was created, select the VM.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/ba97be3c-6633-4f74-9c90-5c93e478a565)

<p>
Now go copy the public IP address.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/98d76afb-9df4-47ce-8c20-e8a1f4e8958a)

<p>
Type Remote Desktop Connection on your pc.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/98ebab8b-511a-4755-8c02-14d62eb1d06a)
![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/b6a2f5d8-330e-4a3c-8761-67d1cb6e4c85)

<p>
Now copy the IP of VMP in the Computer section, then click connect.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/407875c7-404b-43a7-9694-b4985a01a8fd)

<p>
Now for your username type labuser, and the password section type in your password then click the blue ok button.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/89ac49fe-d249-4b18-a979-858e8f8ec2fd)

<p>
Now click yes to log into the VM.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/cfd6eb5c-4541-465d-aa60-6c87cb144381)

<p>
wait for the Virtual Machine to load with the name labuser.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/6c687e00-f863-4b11-acd7-6636347ce87b)

<p>
Select no for all of the options as they are not necessary in this case.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/0de54b88-1404-4572-94e9-7cb16544ec26)

<p>
Select 'yes' to allow PC to be discoverable by other networks.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/49fdb3cd-fda5-4e7a-85b4-7f4f7952b145)

<p>
Open Microsoft Edge (Internet Explorer for Microsoft) and click 'start without your data'.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/c6543143-a16f-475d-bf10-0f6272d9e4c1)

<p>
Select 'continue without this data'. 
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/d626098e-6ca2-49a3-b3ca-36fdbaa4c9ad)

<p>
Confirm and continue.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/b4976b20-a391-434d-9846-f6a1f810f782)

<p>
Then click confirm and start browsing.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/aa9701be-24d9-46a8-b85a-1844c20bf627)

<p>
In the search bar type whatismyipaddress in the search bar and click the site.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/2a195e88-79e3-418f-a032-36c43035f7af)

<p>
Then go to the MY IP section.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/a5ccffab-9ac1-428e-aee8-89542d7fffdf)

<p>
Then you will see the IPv4 and the city, region, and country, mine is Dublin-Ireland, and yours may be elsewhere.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/47f361b4-7872-4da3-8c25-5e6c2a9da278)


<p>
Then type protonVPN.com/free-vpn in the search bar and scroll down till you see download VPN.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/5820aacd-b778-4712-a691-d03581149358)

<p>
Select Download Free Proton VPN.
</p>
<br />#

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/48e96945-78a3-465d-8c1e-4b726891c382)

<p>
Go to File Explorer, go to the download folder, and double-click the software to open it.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/e177a713-5981-4064-821a-0dbd6bec915e)

<p>
Select the 'next' > 'next' > 'install'.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/3b3fff03-1b10-4ed2-963b-782beed3eebc)

<p>
Create an account in the bottom left, if you have an account type your username and password.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/1ba152a4-f24c-47d8-8e76-50e23cce714c)

<p>
Connect to any country you want, for this I will pick Japan, then click the purple button.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/7b7ac596-405d-42d4-b2bc-8a82e4544473)

<p>
let the VPN load, this may temporarily disable your computer as the network changes.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/257ca2d6-cd08-4769-acd8-3254e75d2111)

<p>
If you see a Reconnecting tab don't click cancel, allow the process to complete.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/081f0ec6-d756-45e9-a7dd-b42cbe1c653b)

<p>
Now go back to whatisyouripaddress.com and refresh the page and you will see your IP, city, region, and country changed.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/89a754bb-d7d5-4cc9-b60f-5ac2c60b4ca6)

<p>
Go back to Proton VPN and click disconnect, you can also click on any of Japan's IP that are available on the left side once you click the arrow to expand the available IP.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/ff9af3b4-99ee-4d02-8c5e-d5cc4245fa50)

<p>
Select the bar at the top left and click sign out to sign out of your account
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/54b4fe69-68af-48c2-9646-1fcc02d269b3)


<p>
Now clean up your Microsoft Azure account, go back to Microsoft Azure and type Resource Groups click on Vm-practice and type it in the delete resource group tab then click the delete red tab
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/f309e4e5-8c7b-46df-897f-789a42e8d8b8)

<p>
Confirm the process by clicking delete again.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/8b3bf973-3494-4016-821d-5f6adb5a0a70)

<p>
Now go to the next resource group if you have one and click delete 'resource group'.
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/171c19ff-19ab-4e2b-8a1c-eab05a034c65)


<p>
Then type the name in and click the red delete button
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/46be2ca7-2ed2-4e1d-b1b6-fc9acbf03969)


<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/4deb6184-898a-4457-b51f-7b3f1e410b7f"/>
</p>
<p>
Then to finish the process click delete again 
</p>
<br />

![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/8854796d-e300-49a9-a03e-583ed40beda6)

END!
