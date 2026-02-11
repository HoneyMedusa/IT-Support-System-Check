# IT-Support-System-Check
Technical Support basic troubleshooting of internet connectivity issues.

Name: Raeesah Adams

Date: 11/02/2025

System Specifications
Operating System: Windows 10 Pro
Version: 10.0.19045 Build 19045
System Type: 64-bit
Processor: Intel(R) Core(TM) i5 - 2400 CPU@3.10GHz 4 core(s) 4 Logical pro
Installed RAM: 4.00GB
Connection Type: Wi-Fi
IPv4 Address: 172.20.7.51
Default Gateway: 172.20.6.1
Ping test to google.com was successful and Network was active.

System info: <img width="1366" height="768" alt="system-info png" src="https://github.com/user-attachments/assets/c2dc5db0-45d8-4afb-a810-750ede7f6679" />
System info CMD: <img width="1366" height="728" alt="system-info-cmd" src="https://github.com/user-attachments/assets/8e63099d-8fa3-4a60-9bf2-fc01c5410fdc" />
IP Address : <img width="1366" height="728" alt="IP Address" src="https://github.com/user-attachments/assets/5fc35873-56b5-4403-a238-0d8f2595a3f1" />
IP Address CMD : <img width="1366" height="728" alt="IP Address cmd" src="https://github.com/user-attachments/assets/3606aa45-bd92-4e9c-ae4d-2a2b0c892601" />
Internet Connectivity : <img width="1366" height="728" alt="Internet connectivity" src="https://github.com/user-attachments/assets/0a0240a3-084d-4e18-9e3a-e2d868c8adc5" />


Simulated Issue
The network adapter was manually disabled to simulate an internet disconnection.
Result: Internet connection lost, ping request failed

Network disabled : <img width="1366" height="728" alt="Network Disabled" src="https://github.com/user-attachments/assets/07270fd1-27b3-43e5-bb90-414f69abcef9" />
Network disabled CMD : <img width="975" height="512" alt="Network disabled cmd" src="https://github.com/user-attachments/assets/c0482c0b-f26f-41bb-9eb7-0f0b8319135e" />

Troubleshooting Steps Taken: Re-enabled network adapter

Released and renewed IP address using: ipconfig /release ; ipconfig /renew

Verified connection using: ping google.com
Result : internet connectivity was successfully restored.

Trouble-shooting : <img width="1366" height="728" alt="Troubleshooting" src="https://github.com/user-attachments/assets/ab2bc096-b100-4d23-accd-a83d362b3e1e" />

Network restored : <img width="1366" height="728" alt="Network restored" src="https://github.com/user-attachments/assets/7a72bbec-bf3c-4585-8cd1-e2fb590c4770" />
Network restored CMD : <img width="977" height="510" alt="Network restored cmd" src="https://github.com/user-attachments/assets/144a0d07-0813-44af-bba1-729061cc1135" />

Conclusion
The issue was caused by a disabled network adapter.
Re-enabling the adapter and renewing the IP configuration restored internet access successfully.
