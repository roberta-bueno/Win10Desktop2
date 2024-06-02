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
  - Go to Control Panel, Network and Internet, Change Adaptor Settings, Properties, set the IP configuration needed.
  <p align="center">
  <img src="https://github.com/roberta-bueno/Win10Desktop2/assets/135675237/174d31e0-f55c-4eba-adae-2bf4e6970942" height="60%" width="60%" alt="IP" />
  

<h3>Step 2: Install and Activate Internet Information Services (IIS) on Windows</h3>

- Open Control Panel from the bottom left
- Under Programs, On the left, select Turn Windows Features On or Off
- Check Internet Information Services (IIS) and click OK
- Go to Application Development features and check CGI
