<h1>Windows 10 Machine to a Domain Guide</h1>
This guide provides an overview of the steps for adding a Windows 10 computer to a domain.<br />

<h2>Platforms and Technologies Utilized</h2>

- Oracle VM VirtualBox Manager

<h2>Operating System Used</h2>

- Windows 10 

<h2>Required Components</h2>

<ul>
  <li>Oracle VM VirtualBox</li>
  <li>Virtual Machine</li>
</ul>

<h3>Step 1: Set a static IP address to be able to add the PC to Domain</h3>
  - Go to Control Panel, View Network Status and Tasks, Change Adaptor Settings, Properties, set the IP configuration needed.
  <p align="center">
  <img src="https://github.com/roberta-bueno/Win10Desktop2/assets/135675237/174d31e0-f55c-4eba-adae-2bf4e6970942" height="60%" width="60%" alt="IP" /></p>
  

<h3>Step 2: Network Settings</h3>
  - Under Devices on VM manager go to Network Settings/Host only adapter.
  
<h3>Step 3: Add the PC to Domain</h3>
  - This PC, Properties, Rename this PC (advanced), go to change and put the domain name.
  - Add the login and password with permission to join domain.
  - Go to Active Directory Users and Computers and the Desktop will be added to the domain.

   <p align="center">
  <img src="https://github.com/roberta-bueno/Win10Desktop2/assets/135675237/8833af1c-a160-4ed1-9d9f-a0f9e6860ddd"height="60%" width="60%" alt="IP" /></p>
  <p align="center">
  <img src="https://github.com/roberta-bueno/Win10Desktop2/assets/135675237/0e579596-4188-4faa-b495-55c449661e66"height="60%" width="60%" alt="IP" /></p>
  <p align="center">
  <img src="https://github.com/roberta-bueno/Win10Desktop2/assets/135675237/de92dbfb-f9e5-4234-956d-40fef55b9b34"height="60%" width="60%" alt="IP" /></p>

  
