# Hotel-Management-Networking-Project-using-Packet-Tracer
Vic Modern Hotel Network Design (Cisco Packet Tracer)
📌 Project Overview
This project presents the design and implementation of a complete network infrastructure for Vic Modern Hotel using Cisco Packet Tracer.
The hotel consists of three floors, each containing multiple departments. The objective is to provide secure communication between departments while maintaining network segmentation through VLANs, inter-VLAN routing, and wireless connectivity.

🎯 Project Objectives
Design a scalable hotel network.
Separate departments using VLAN technology.
Implement inter-VLAN communication.
Connect all floors through routers.
Provide wireless access for employees and guests.
Configure printers for each department.
Implement IP addressing and subnetting.
Ensure communication between all departments.
🏢 Hotel Structure
First Floor
Reception Department
Store Department
Logistics Department
Second Floor
Finance Department
Human Resources (HR)
Sales & Marketing Department
Third Floor
IT Department
Administration Department
🛠 Network Components
Routers
3 Cisco Routers
One router assigned to each floor
All routers connected through Serial DCE links
Switches
1 Switch per floor
VLAN configuration on each switch
End Devices
PCs
Laptops
Smartphones
Network Printers
Wireless Devices
Wireless Access Points
Wi-Fi connectivity for laptops and mobile devices
🌐 Router Interconnection Network
Connection	Network
Router Links	10.10.10.0/30
Router Links	10.10.10.4/30
Router Links	10.10.10.8/30

These networks are used for point-to-point communication between routers.

🔒 VLAN Configuration
First Floor
Department	VLAN ID	Network
Reception	VLAN 80	192.168.8.0/24
Store	VLAN 70	192.168.7.0/24
Logistics	VLAN 60	192.168.6.0/24
Second Floor
Department	VLAN ID	Network
Finance	VLAN 50	192.168.5.0/24
HR	VLAN 40	192.168.4.0/24
Sales & Marketing	VLAN 30	192.168.3.0/24
Third Floor
Department	VLAN ID	Network
IT	VLAN 20	192.168.2.0/24
Administration	VLAN 10	192.168.1.0/24
⚙ Technologies Implemented
VLANs
Inter-VLAN Routing
Router-to-Router Serial Connections
Static Routing / Dynamic Routing
DHCP Configuration
Wireless Networking
Network Segmentation
IP Addressing
Printer Integration
Cisco Packet Tracer Simulation
📋 Features

✅ Department isolation using VLANs

✅ Communication between different VLANs

✅ Wireless connectivity for mobile devices

✅ Dedicated printer for each department

✅ Multi-floor network architecture

✅ Scalable and organized network design

✅ Centralized routing between floors

📂 Project Files
Vic-Modern-Hotel-Network/
│
├── Vic_Modern_Hotel.pkt
├── README.md
├── screenshots/
│   ├── topology.png
│   ├── vlan_configuration.png
│   ├── routing_configuration.png
│   └── connectivity_tests.png
🧪 Testing Performed

The following tests were conducted to verify network functionality:

Ping between devices in the same VLAN
Ping between different VLANs
Ping between different floors
Router-to-router connectivity verification
Wireless device connectivity testing
Printer communication testing
🚀 How to Run
Download the project files.
Open the .pkt file using Cisco Packet Tracer.
Wait for all devices to initialize.
Enter Simulation Mode or Realtime Mode.
Test connectivity using the ping command.
📖 Learning Outcomes

Through this project, the following networking concepts were applied:

VLAN Configuration
Subnetting and IP Addressing
Inter-VLAN Routing
DHCP Services
Wireless Network Deployment
Router Configuration
Switch Management
Network Troubleshooting
👨‍💻 Author

Inass

Bachelor's Student in Computer Science & Networking

Cisco Packet Tracer Project – 2026
