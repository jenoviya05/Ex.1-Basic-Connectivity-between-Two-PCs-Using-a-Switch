## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 27.10.26		

# Objective :

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required :
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram :

Insert the network topology from Packet Tracer (Screenshot or drawing)

<img width="1916" height="1076" alt="Screenshot 2026-10-27 172626" src="https://github.com/user-attachments/assets/30864d81-b400-4e99-99e0-bfe8eb7a9124" />


________________________________________
# IP Addressing Table (if applicable) :
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure :
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any) :

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results) :

Insert screenshots showing ping success, configuration, or simulation results.

## CONFIGURATION : 

<img width="1917" height="1078" alt="Screenshot 2026-10-27 172859" src="https://github.com/user-attachments/assets/77b15e10-8e60-4116-a193-183647fc8bec" />




<img width="1917" height="1078" alt="Screenshot 2026-10-27 172912" src="https://github.com/user-attachments/assets/befa6f5b-e041-44cb-9b8d-0ae47c5e6e57" />




<img width="1917" height="1078" alt="Screenshot 2026-10-27 172959" src="https://github.com/user-attachments/assets/282ada28-44e3-4c79-8e29-4e8eb7d03bd2" />



## PING :


<img width="1917" height="1078" alt="Screenshot 2026-10-27 172701" src="https://github.com/user-attachments/assets/f3fa179e-da8e-443e-ae5c-04a75fe032ac" />



<img width="1917" height="1078" alt="Screenshot 2026-10-27 172734" src="https://github.com/user-attachments/assets/0b1f9898-85d8-484f-b0f6-663e091cdab9" />



## SWITCH CONFIG :



<img width="1917" height="1078" alt="Screenshot 2026-10-27 172932" src="https://github.com/user-attachments/assets/dd6755d7-9526-4d90-a32c-c9331153e724" />


________________________________________
# Result :
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
