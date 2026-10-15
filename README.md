## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 		

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram
<img width="1917" height="1078" alt="Screenshot 2026-10-15 172841" src="https://github.com/user-attachments/assets/d5ac8238-514b-47c9-9091-064d7b143869" />


________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any)

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results)
<img width="1917" height="1076" alt="Screenshot 2026-10-15 172042" src="https://github.com/user-attachments/assets/7c9cfa90-b0a9-46ad-ac6f-7d31b8bbace6" />																													
<img width="1917" height="1075" alt="Screenshot 2026-10-15 172104" src="https://github.com/user-attachments/assets/5183a7bb-7d5e-414e-aebb-bbb036de324f" />

# PING
<img width="1912" height="1072" alt="Screenshot 2026-10-15 172427" src="https://github.com/user-attachments/assets/ab495084-3242-456e-b506-e3083d8c9de6" />

________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
