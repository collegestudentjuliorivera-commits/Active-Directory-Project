Virtual Enterprise Network with Active Directory

1. Deployed Windows 11 Virtual Machine
- Installed and configured a Windows 11 operating system within an Oracle VirtualBox virtual environment to serve as a client machine in the lab.

<img width="1920" height="1140" alt="Installing a Windows OS in a Virtual Machine" src="https://github.com/user-attachments/assets/7e16c060-f426-4454-a3c3-965fa326bb06" />

2. Provisioned Windows Server Environment
- Installed Windows Server on a separate virtual machine to act as the centralized server for the simulated enterprise network while eventually turning it into a Domain Controller. I also assigned a static IP Address to the server.
<img width="1026" height="873" alt="Build a server" src="https://github.com/user-attachments/assets/214efaef-a8ef-4686-b859-47ab91a7f48c" />
<img width="1026" height="873" alt="Servercreated" src="https://github.com/user-attachments/assets/4531e9b8-6490-47d3-a967-8c9594f6fcc9" />
<img width="1024" height="774" alt="Assigned the Server (Domain Controller) A static IP address" src="https://github.com/user-attachments/assets/7ddb62d8-df79-45dd-8fcb-07e0e8e83709" />

3. Configured Domain Controller Services
- Promoted the Windows Server instance to a Domain Controller by installing and configuring Active Directory Domain Services (AD DS), enabling centralized authentication and domain management.
<img width="1039" height="784" alt="Installed Active Directory On the Domain Controller Server" src="https://github.com/user-attachments/assets/ca5d69c5-798e-4ed3-96fa-669e29ee608f" />
<img width="1032" height="775" alt="Promoted the Server to the domain controller" src="https://github.com/user-attachments/assets/29e57d44-f1eb-4bfb-b95e-ccd402f4eaf0" />

4. Organizational Units and Directory Structure
- Created two Organizational Units (OUs) named Accounts and Groups. Within the Accounts OU, two user accounts—Mike Rivera and Elizabeth Martinez—were established. Within the Groups OU, two security groups—Finance and HR—were created to organize user roles and permissions effectively.
<img width="1018" height="774" alt="Created a Organizational Unit" src="https://github.com/user-attachments/assets/020ab690-d954-436b-9f65-a1eb3cb64f42" />
<img width="1021" height="771" alt="Created A user in the Active Directory" src="https://github.com/user-attachments/assets/f6bee2cd-5f07-4c4e-9d6c-82e765e1e84f" />
<img width="1037" height="777" alt="created two groups part2" src="https://github.com/user-attachments/assets/42ae599d-134a-40c7-b7d7-573ca0d9f88e" />

5. Virtual Machine Integration with Active Directory
- Configured a virtual machine and successfully joined it to the Active Directory domain. This was accomplished by ensuring the VM was assigned the same DNS server address as the Active Directory domain controller, enabling proper communication and authentication within the network environment.
<img width="1920" height="1140" alt="Gave the virtual machine the same DNS address as the Active directory server in order to add it to the Domain controller" src="https://github.com/user-attachments/assets/ecc822ef-a077-47ac-b302-d06b289c1d3f" />
<img width="1920" height="1140" alt="welcome to lab domain" src="https://github.com/user-attachments/assets/1be1b1e1-ed2a-4051-9eb3-111d020a63b4" />
