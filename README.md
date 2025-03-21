# Small Business Network Setup in Cisco Packet Tracer

This project demonstrates the design and configuration of a small business network using Cisco Packet Tracer, a network simulation tool. The setup includes a router, a switch, and multiple PCs, with an additional PC to test security features. It showcases foundational networking skills relevant to CompTIA A+, Network+, and CCNA certifications, preparing me for entry-level IT roles in Arizona’s tech hub.

## Project Overview
- **Components**:
  - 1 Router (Cisco 2911)
  - 1 Switch (Cisco 2950-24)
  - Multiple PCs (including one for security testing)
- **Connections**:
  - Router to Switch via FastEthernet0/0 using a Copper Straight-Through cable.
  - PCs to Switch using Copper Straight-Through cables, forming a star topology.

## Key Tasks Completed
- **Network Topology Design**: Built a functional network layout connecting a router, switch, and end devices.
- **Manual IP Configuration**: Assigned static IP addresses to PCs (e.g., `192.168.1.10/24`) and confirmed connectivity with ping commands.
- **DHCP Configuration**: Set up the router as a DHCP server to dynamically assign IP addresses (e.g., `192.168.1.100–101`), simplifying network management.
- **Firewall Security**: Implemented an access control list (ACL) to block unauthorized external traffic (e.g., `192.168.2.0/24`) while allowing internal communication, strengthening network security.

## Challenges and Resolutions
During the project, I encountered several issues that required troubleshooting:  
- **Ping Failures**: Initial connectivity tests failed due to a downed router interface. I enabled it using the `no shutdown` command, restoring communication.  
- **DHCP Issues**: PCs did not receive IP addresses initially. I corrected the DHCP pool configuration to match the network subnet (`192.168.1.0/24`), ensuring proper IP distribution.  
- **ACL Adjustments**: The firewall rule blocked internal traffic by mistake. I refined the ACL to target only the external interface (`FastEthernet0/0`), fixing the issue without compromising security.  

## Skills Demonstrated
- Network topology design and configuration
- IP addressing (static and DHCP)
- Basic network security with ACLs
- Troubleshooting and problem-solving

## Files Included
- `Small_Business_Network_Setup.pkt`: The Cisco Packet Tracer project file.
- **Screenshots**:
  - **Network Topology**:  
    ![Network Topology](Network%20Topology.png)  
  - **Manual IP Ping Test**:  
    ![Manual IP Ping Test](MANUAL%20IP%20PING%20Test.png)  
  - **DHCP Configuration**:  
    ![DHCP Configuration](DHCP%20Configuration.png)  
  - **DHCP Assigned IP**:  
    ![DHCP Assigned IP](DHCP%20Assigned%20IP.png)  
  - **DHCP Ping Test**:  
    ![DHCP Ping Test](DHCP%20PING%20Test.png)  
  - **Firewall Rule Configuration**:  
    ![Firewall Rule Configuration](Firewall%20Rule%20Configuration.png)  
  - **Blocked Ping Test**:  
    ![Blocked Ping Test](BLOCKED%20PING%20Test.png)  
  - **Allowed Ping Test**:  
    ![Allowed Ping Test](ALLOWED%20PING%20Test.png)
    
## How to View
1. Install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer).
2. Download and open the `.pkt` file to explore the network design.

## Next Steps
I plan to expand this project by adding VLANs to segment traffic and implementing more advanced security measures like VPNs, aligning with my pursuit of the CCNA certification.

---
**Manuel Benavides**  
Email: [ManuelB.Tech@gmail.com](mailto:ManuelB.Tech@gmail.com)  
LinkedIn: [Add your LinkedIn URL here if you have one]
