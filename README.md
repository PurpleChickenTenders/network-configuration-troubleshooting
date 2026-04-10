# network-configuration-troubleshooting
📡 Network Configuration & Troubleshooting Lab
📌 Project Overview

This lab demonstrates basic network configuration and troubleshooting using a managed Cisco switch. The objective was to access the switch, verify interface status, configure a test port, connect an endpoint device, and validate network connectivity.

🛠️ Tools & Technologies Used
Cisco Managed Switch
PuTTY (Console Access)
Windows PC
Ethernet Cable
Console Cable
🎯 Skills Demonstrated
Switch access via console connection
Interface status verification
Port configuration and activation
Basic network troubleshooting
End-device connectivity validation
Configuration saving and persistence
⚙️ Lab Setup
Connected to the switch using a console cable and PuTTY
Verified device access through CLI
Selected a test port for configuration
Connected a client device via Ethernet
💻 Commands Used
enable
show running-config | include hostname
show interfaces status
configure terminal
interface fastEthernet 0/4
no shutdown
description Test-PC-Port
end
copy running-config startup-config
🔍 Troubleshooting Process
Verified physical connection (Ethernet cable and port link)
Checked interface status using CLI commands
Ensured port was not administratively down
Confirmed client device received network connectivity
Validated communication using IP configuration and ping tests
✅ Results
Successfully accessed and configured the switch
Verified active interface connection
Connected endpoint device with working network access
Confirmed connectivity through system checks and testing
Saved configuration to ensure persistence after reboot
📸 Screenshots / Proof

(Upload these to your repo)

PuTTY session (CLI access)
Interface status output
Configured port view
Connected device network status
Ping or connectivity test
🎥 Project Demo

(Upload your video or paste your YouTube link here)
Example:

[Insert Video Link Here]
📈 Project Summary (Resume Use)

Network Configuration & Troubleshooting Lab

Configured and accessed a managed Cisco switch through console connection using PuTTY
Verified interface status, enabled a test port, and connected an endpoint device
Performed basic network troubleshooting by validating link status and client connectivity
Documented commands, results, and configuration steps in a GitHub project repository
🚀 Key Takeaway

This project demonstrates foundational networking skills required for roles such as Network Engineer, Data Center Technician, and IT Support Engineer by showcasing real-world configuration and troubleshooting practices.
