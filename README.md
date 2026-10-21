# 🏥 Hospital Network Design

A secure, scalable, and cost-effective hospital network infrastructure designed for **Melbourne Health Services** using **Cisco Packet Tracer**.

The project focuses on reliable communication between hospital departments through hierarchical network architecture, VLAN segmentation, dynamic routing, IP address management, and network security.

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Problem Statement](#-problem-statement)
- [Project Objectives](#-project-objectives)
- [Network Design and Methodology](#-network-design-and-methodology)
- [Key Features](#-key-features)
- [Repository Contents](#-repository-contents)
- [Tools and Technologies](#-tools-and-technologies)
- [Implementation and Testing](#-implementation-and-testing)
- [Expected Outcomes](#-expected-outcomes)
- [Getting Started](#-getting-started)
- [Contributing](#-contributing)
- [Contact](#-contact)

## 📌 Project Overview

Melbourne Health Services operates across multiple locations and requires a reliable network infrastructure to support secure communication and efficient data exchange.

This project proposes a hierarchical network design implemented in Cisco Packet Tracer. It combines network segmentation, dynamic routing, IP address management, and security configurations to improve reliability, scalability, and operational efficiency.

## ❗ Problem Statement

Dependence on third-party IT services can introduce challenges related to cost, network administration, and data security. A well-structured network infrastructure can improve internal control, support secure communication, and provide a foundation for future expansion.

## 🎯 Project Objectives

- Design a hierarchical hospital network topology.
- Organize departmental traffic using VLANs and subnetting.
- Configure dynamic routing with OSPF.
- Automate IP address allocation through DHCP.
- Improve network security using ACLs and port security.
- Explore VPN-based secure communication.
- Test connectivity and validate network configurations.

## 🖧 Network Design and Methodology

### 1. Hierarchical Network Architecture

The proposed topology uses a layered architecture consisting of:

- **Core Routers:** Support communication between network segments.
- **Multilayer Switches:** Enable inter-VLAN routing and traffic management.
- **Access Switches:** Connect end devices to the network.
- **End Devices:** Represent hospital users and departmental systems.

### 2. VLANs and Subnetting

Departmental segmentation helps organize network traffic, manage IP address ranges, and limit unnecessary communication between network segments.

### 3. Network Security

Planned security measures include:

- Access Control Lists (ACLs) for traffic filtering.
- Port security to restrict unauthorized device connections.
- VPN solutions for secure communication where configured.

### 4. Dynamic Routing with OSPF

Open Shortest Path First (OSPF) is used to support dynamic route discovery and exchange between participating routers.

### 5. DHCP and IP Address Management

DHCP provides automatic IP address allocation to client devices, while static addressing can be used for selected infrastructure devices that require stable addresses.

### 6. Monitoring and Testing

Connectivity and configuration testing help identify routing issues, verify IP allocation, and evaluate communication between network segments.

## ✨ Key Features

- Hierarchical network topology
- Departmental VLAN segmentation
- IP addressing and subnet planning
- OSPF dynamic routing
- DHCP configuration
- ACL-based traffic control
- Port-security configuration
- Redundancy planning
- Network connectivity testing

*Note: Features described as planned or proposed should be considered implemented only where supported by the included Packet Tracer project and configuration files.*

## 📂 Repository Contents

| File | Description |
|---|---|
| `hospital_network_system_main.pkt` | Cisco Packet Tracer network project |
| `IP ADDRESS.pdf` | IP addressing documentation |
| `configuration(copy_paste_in_project).txt` | Network configuration commands |
| `hospital network system_proposal.pdf` | Project proposal |
| `hospital requirements(case_study).pdf` | Hospital network case study and requirements |
| `Hospital Network System presentation.pptx` | Project presentation |
| `screenshot of configuration.pptx` | Configuration screenshots and documentation |

## 🛠️ Tools and Technologies

- **Cisco Packet Tracer** — Network topology design and simulation
- **OSPF** — Dynamic routing
- **VLANs and Subnetting** — Network segmentation and addressing
- **DHCP** — Automatic IP address allocation
- **ACLs and Port Security** — Network access control
- **VPN** — Proposed secure communication between locations

## 🧪 Implementation and Testing

The project workflow includes:

1. Design the network topology in Cisco Packet Tracer.
2. Configure routers, multilayer switches, and access switches.
3. Assign VLANs and IP address ranges.
4. Configure OSPF routing and DHCP services.
5. Apply the required security configurations.
6. Test device connectivity and routing between network segments.
7. Review the results and document configuration details.

## 📈 Expected Outcomes

- Improved network organization and traffic management.
- More controlled access to network resources.
- Efficient IP address allocation.
- Reliable communication between participating network segments.
- A scalable foundation for future hospital network expansion.
- Reduced dependence on external network administration for routine tasks.

## 🚀 Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/usmana0820/Hospital-Network-Design.git
   ```

2. Open `hospital_network_system_main.pkt` in Cisco Packet Tracer.
3. Review the network topology and IP addressing documentation.
4. Inspect the configuration commands provided in the repository.
5. Run connectivity tests and verify the configurations supported by the project.

**Requirements:** A compatible installation of Cisco Packet Tracer.

## 🤝 Contributing

Contributions and suggestions are welcome.

1. Fork this repository.
2. Create a feature branch: `git checkout -b feature-branch`
3. Commit your changes: `git commit -m "Describe your changes"`
4. Push your branch: `git push origin feature-branch`
5. Open a pull request.

## 👩‍💻 Author

**Usmana Zulfiqar**

- GitHub: [@usmana0820](https://github.com/usmana0820)
- Email: [usmanazulfiqar20@gmail.com](mailto:usmanazulfiqar20@gmail.com)

## 📄 License

No license is specified in the repository information provided. Add a `LICENSE` file if you intend to publish the project under an open-source license.
