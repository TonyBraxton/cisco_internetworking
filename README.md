#Networking-Project--VLSM--VLANs-and-WLC-Configuration
 designing and implementing a complex network topology

## Project Overview
This project involves designing and implementing a complex network topology with the following key components:
- VLSM addressing scheme for subnetting and efficient IP allocation.
- Configuration of VLANs across multiple sites.
- Wireless LAN Controller (WLC) setup with lightweight access points.
- Integration of DHCP services for IP assignment to wireless devices.
- Simulation and configuration of all devices using Cisco Packet Tracer.

---

## 📁 Project Structure

## Key Objectives
- Design an optimized VLSM addressing scheme based on provided subnet requirements.
- Configure VLANs to segment wired and wireless traffic effectively.
- Deploy and configure WLCs (B1-WLC/B2-WLC) with the following:
  - System Names: `B1-WLC` and `B2-WLC`
  - Management IPs: `192.168.100.30/24` and `192.168.200.30/24`
  - Default Gateways: `192.168.100.1` and `192.168.200.1`
  - Admin credentials: `admin / Cisco123`
- Enable DHCP for the lightweight access points connected to the B1ML switch.
- Establish inter-site connectivity via routers using interfaces:
  - `g0/0/0` to Site 1 ML Switch
  - `g0/0/1` to Site 2 ML Switch

---

## Wireless LAN Controller (WLC) Configuration
- **WLC Names:** `B1-WLC` and `B2-WLC`
- **VLAN Configuration:**
  - VLAN 100: Management VLAN for B1-WLC
  - VLAN 200: Management VLAN for B2-WLC
- **DHCP for Access Points:** Enabled on VLAN 100

---

## Router & Switch Configuration Highlights
- **Inter-VLAN Routing:** Configured on the router to enable communication between VLANs.
- **ML Switch Port Configurations:**
  - Trunk ports for VLAN propagation.
  - Access ports for end devices and APs.

---

## Simulation in Cisco Packet Tracer
- **File Name:** `Network_Topology.pkt`
- The final configuration is stored in `Final_Configuration.pkt` with all devices configured.

---

## Project Report
For detailed insights and step-by-step configuration, refer to the [Project Report](docs/Project_Report.pdf).

---

## Troubleshooting & Considerations
- Verify DHCP bindings to ensure access points receive IPs correctly.
- Check VLAN tagging and trunk configurations on the ML switches.
- Test wireless connectivity after WLC and AP configuration.

---

## Contributors
- [Tony Braxton Tchio Ngoumeza] - Network Design, network Configuration & report input
- [Deven Chandel]-derived elements missing from Addressing table & report input

---

## Contact
If you encounter any issues, feel free to reach out via [tngoumeza@gmail.com].