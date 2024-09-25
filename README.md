# Home-Lab
Within a virtual environment, I have configured a Windows 2019 Active Directory Domain Controller server. On this server, I utilized Bad Blood from secframe to simulate an organizational environment of 2500 users, 500 groups, and 100 computers with random security misconfigurations. The main task is to create a more secure environment using a plan laid out by sec frame here (https://secframe.com/docs/ramp/what_is_redforest/).

![1709182290328](https://github.com/user-attachments/assets/875d9f4a-bf45-4df3-b97c-234105cdfc01)

In this small virtual environment, I have deployed a pfSense firewall machine as the gateway between the virtual environment and WAN, a Windows 10 workstation to test administrative changes made, a Kali linux workstation to simulate attacks on the AD server, and CrowdSec's free IDS/IPS solution engines on both the W10 workstation and domain controller.

![1709181377506](https://github.com/user-attachments/assets/afeda99d-39bc-440d-9ba1-fb8260500005)
![image](https://github.com/user-attachments/assets/f1db030e-ed00-4f68-b873-6e75c880ce72)


This lab can be restarted with random misconfigs each time for constant practice!
