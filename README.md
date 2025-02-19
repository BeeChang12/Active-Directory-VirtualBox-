# Active-Directory-VirtualBox

I want to express my gratitude to Josh Madakor for his excellent tutorial on setting up a comprehensive Active Directory lab on your personal computer using VirtualBox. Configuring and running this lab greatly improved my understanding of Active Directory and Windows networking. To deepen my knowledge, I analyzed and deconstructed the setup multiple times, reinforcing my foundational skills. After several repetitions, I challenged myself to build the lab without referring to the tutorial, further solidifying my expertise.

https://www.youtube.com/watch?v=MHsI8hJmggI&ab_channel=JoshMadakor

A logical diagram of the lab.
![image](https://github.com/user-attachments/assets/981101d0-acd5-456f-99a4-7f9f159fb64e)


# Here’s a high-level summary of the video content:

- Step 1: Install Oracle VirtualBox to run virtual machines.
- Step 2: Download Windows 10 and Server 2019 ISOs for setting up separate virtual machines.
- Step 3: Create the first virtual machine (domain controller) with two network adapters—one for internet access and another for a VirtualBox private network.
- Step 4: Install Server 2019, configure internal network IP addresses, name the server, and set up Active Directory to establish the domain.
- Step 5: Enable routing so that private network clients can access the internet through the domain controller.
- Step 6: Configure DHCP on the domain controller to automatically assign IP addresses to Windows 10 machines.
- Step 7: Use a PowerShell script to generate 1,000 Active Directory user accounts.
- Step 8: Create another virtual machine, install Windows 10, connect it to the private VirtualBox network, name it “client1,” and join it to the domain.
- Step 9: Log into the Windows 10 machine using a domain account.

# Summary
- This tutorial establishes a basic Windows networking environment with Active Directory and essential networking services.
