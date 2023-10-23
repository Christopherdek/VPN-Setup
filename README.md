# VPN Setup and Usage With Proton VPN

![Proton VPN](https://github.com/Christopherdek/VPN-Setup/assets/148359456/fe3ad9c5-4985-4de0-bfea-0088cdc5c11c)

This tutorial guides you through setting up and using Proton VPN to measure different IP addresses.

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- Proton VPN
- Whatsmyipaddress.com

## Operating System Used

- Windows 10 (21H2)

## High-Level Steps

1. Create a Virtual Machine in Microsoft Azure.
2. Log into the virtual machine using Remote Desktop Connection.
3. Use whatsmyipaddress.com to grab your VM IP address.
4. Download Proton VPN, then connect to any VPN.
5. Use whatsmyipaddress.com to grab your new Proton VPN IP address.

## Actions and Observations

1. Go to [whatsmyipaddress.com](https://www.whatsmyipaddress.com/) and copy your current IP address.

   ![Current IP](https://github.com/Christopherdek/VPN-Setup/assets/148359456/66e9024c-fb7b-4a3d-a21c-4cf2d1950a85)

2. Open Microsoft Azure and search for Virtual Machine.

   ![Azure VM](https://github.com/Christopherdek/VPN-Setup/assets/148359456/f83f697c-bceb-47b2-87cb-31437199122d)

3. Select 'Create' and go to Azure Virtual Machine.

   ![Create VM](https://github.com/Christopherdek/VPN-Setup/assets/148359456/7eb1a45a-1fa5-4fc4-aedb-00c0045ac3eb)

4. Go to the Resource Group tab, click 'Create New', and name it 'Vm-practice'. Then click the blue OK button.

   ![Resource Group](https://github.com/Christopherdek/VPN-Setup/assets/148359456/d8d64682-d983-4d30-a330-bd6ff1de9e6a)

5. Go to the Virtual Machine name, type 'VMP', and choose the region. Click 'Windows 10 Pro' version.

   ![VM Configuration](https://github.com/Christopherdek/VPN-Setup/assets/148359456/c698d127-9381-434a-9cb0-80d629aad402)

6. Select the size option of '2+ virtual CPU', enter username and password.

   ![VM Size](https://github.com/Christopherdek/VPN-Setup/assets/148359456/77d58e71-fb68-4fc9-84ee-8085d071783b)

7. Review and Create tab, then click 'Create' on the bottom left side. Wait for Azure to set up the Virtual Machine.

   ![Review and Create](https://github.com/Christopherdek/VPN-Setup/assets/148359456/fd709eb3-9043-4b3e-b8f7-2c8da084d44e)

8. Type 'Virtual Machine', select 'VMP', and copy the public IP address.

   ![VM IP](https://github.com/Christopherdek/VPN-Setup/assets/148359456/98d76afb-9df4-47ce-8c20-e8a1f4e8958a)

9. Type 'Remote Desktop Connection' on your PC. Copy the IP of VMP in the Computer section, then click connect.

   ![RDP Connection](https://github.com/Christopherdek/VPN-Setup/assets/148359456/98ebab8b-511a-4755-8c02-14d62eb1d06a)

   ![RDP Connection](https://github.com/Christopherdek/VPN-Setup/assets/148359456/b6a2f5d8-330e-4a3c-8761-67d1cb6e4c85)

10. Copy the IP of VMP in the Computer section, then click connect.

   ![RDP Login](https://github.com/Christopherdek/VPN-Setup/assets/148359456/407875c7-404b-43a7-9694-b4985a01a8fd)

   ![RDP Username](https://github.com/Christopherdek/VPN-Setup/assets/148359456/89ac49fe-d249-4b18-a979-858e8f8ec2fd)

   ![RDP Confirm](https://github.com/Christopherdek/VPN-Setup/assets/148359456/cfd6eb5c-4541-465d-aa60-6c87cb144381)

11. Wait for the Virtual Machine to load with the name 'labuser'.

   ![VM Loading](https://github.com/Christopherdek/VPN-Setup/assets/148359456/6c687e00-f863-4b11-acd7-6636347ce87b)

12. Select 'No' for all options as they are not necessary.

   ![VM Options](https://github.com/Christopherdek/VPN-Setup/assets/148359456/0de54b88-1404-4572-94e9-7cb16544ec26)

13. Select 'Yes' to allow PC to be discoverable by other networks.

   ![Discoverable PC](https://github.com/Christopherdek/VPN-Setup/assets/148359456/49fdb3cd-fda5-4e7a-85b4-7f4f7952b145)

14. Open Microsoft Edge (Internet Explorer for Microsoft) and click 'start without your data'.

   ![Edge Start](https://github.com/Christopherdek/VPN-Setup/assets/148359456/c6543143-a16f-475d-bf10-0f6272d9e4c1)

   ![Edge Continue](https://github.com/Christopherdek/VPN-Setup/assets/148359456/d626098e-6ca2-49a3-b3ca-36fdbaa4c9ad)

   ![Edge Confirm](https://github.com/Christopherdek/VPN-Setup/assets/148359456/b4976b20-a391-434d-9846-f6a1f810f782)

   ![Edge Start Browsing](https://github.com/Christopherdek/VPN-Setup/assets/148359456/aa9701be-24d9-46a8-b85a-1844c20bf627)

15. In the search bar, type 'whatismyipaddress' and click the site. Go to the 'MY IP' section.

   ![Whatsmyipaddress](https://github.com/Christopherdek/VPN-Setup/assets/148359456/2a195e88-79e3-418f-a032-36c43035f7af)

   ![Current IP](https://github.com/Christopherdek/VPN-Setup/assets/148359456/a5

### Viewing Current IP Details

16. Go to the [whatismyipaddress.com](https://www.whatismyipaddress.com/) website.

   ![Current IP Details](https://github.com/Christopherdek/VPN-Setup/assets/148359456/a5ccffab-9ac1-428e-aee8-89542d7fffdf)

17. Check the IPv4 address along with the city, region, and country details. Note that your location may vary.

   ![IP Details](https://github.com/Christopherdek/VPN-Setup/assets/148359456/47f361b4-7872-4da3-8c25-5e6c2a9da278)

### Downloading Proton VPN

18. Type "protonVPN.com/free-vpn" in the search bar and scroll down to find the download link.

   ![Proton VPN Download](https://github.com/Christopherdek/VPN-Setup/assets/148359456/5820aacd-b778-4712-a691-d03581149358)

19. Select "Download Free Proton VPN."

   ![Download Proton VPN](https://github.com/Christopherdek/VPN-Setup/assets/148359456/48e96945-78a3-465d-8c1e-4b726891c382)

20. Open File Explorer, navigate to the download folder, and double-click the software to open it.

   ![Install Proton VPN](https://github.com/Christopherdek/VPN-Setup/assets/148359456/e177a713-5981-4064-821a-0dbd6bec915e)

   - Select 'Next' > 'Next' > 'Install.'

### Connecting to Proton VPN

21. Create an account in the bottom left. If you already have an account, enter your username and password.

   ![Create Proton VPN Account](https://github.com/Christopherdek/VPN-Setup/assets/148359456/1ba152a4-f24c-47d8-8e76-50e23cce714c)

22. Connect to any country of your choice. For this example, we'll pick Japan. Click the purple button.

   ![Connect to Proton VPN](https://github.com/Christopherdek/VPN-Setup/assets/148359456/7b7ac596-405d-42d4-b2bc-8a82e4544473)

23. Allow the VPN to load; this may temporarily disable your computer as the network changes.

   ![Proton VPN Loading](https://github.com/Christopherdek/VPN-Setup/assets/148359456/257ca2d6-cd08-4769-acd8-3254e75d2111)

24. If you see a 'Reconnecting' tab, don't click cancel; allow the process to complete.

   ![Proton VPN Reconnecting](https://github.com/Christopherdek/VPN-Setup/assets/148359456/081f0ec6-d756-45e9-a7dd-b42cbe1c653b)

### Checking Changed IP Details

25. Go back to whatismyipaddress.com, refresh the page, and observe your changed IP, city, region, and country.

   ![Changed IP Details](https://github.com/Christopherdek/VPN-Setup/assets/148359456/89a754bb-d7d5-4cc9-b60f-5ac2c60b4ca6)

### Disconnecting from Proton VPN

26. Go back to Proton VPN and click disconnect. Alternatively, click on any available Japanese IP on the left side.

   ![Disconnect from Proton VPN](https://github.com/Christopherdek/VPN-Setup/assets/148359456/ff9af3b4-99ee-4d02-8c5e-d5cc4245fa50)

27. Select the bar at the top left and click 'Sign Out' to log out of your Proton VPN account.

   ![Sign Out of Proton VPN](https://github.com/Christopherdek/VPN-Setup/assets/148359456/54b4fe69-68af-48c2-9646-1fcc02d269b3)

### Cleaning up Microsoft Azure Account

28. Return to Microsoft Azure, type 'Resource Groups,' click on 'Vm-practice,' enter its name in the 'Delete Resource Group' tab, and click the red delete button.

   ![Azure Cleanup](https://github.com/Christopherdek/VPN-Setup/assets/148359456/f309e4e5-8c7b-46df-897f-789a42e8d8b8)

29. Confirm the process by clicking delete again.

  ![image](https://github.com/Christopherdek/VPN-Setup/assets/148359456/8854796d-e300-49a9-a03e-583ed40beda6)
