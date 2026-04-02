# Openframe Studios Capstone Project

## Overview
This repository contains the network infrastructure design and simulation for the Openframe Studios Capstone project, created as part of the WGU Bachelor of Science in Network Operations and Security program.

## Project Description
This project demonstrates the design, implementation, and documentation of a comprehensive network infrastructure solution using GNS3 network simulation software. The project showcases practical networking skills including network topology design, configuration, security implementation, and troubleshooting.

## Technologies Used
- **GNS3** - Network simulation and emulation platform
- **Dynamips** - Cisco router emulation
- **Network Protocols** - TCP/IP, routing protocols, switching technologies

## Project Structure
```
Openframe-Studios-Capstone/
├── New_Openframe_Studios_Capstone.gns3 # Main GNS3 project file
├── configs/                            # Device configurations
└── project-files/                      # GNS3 project artifacts (generated)
```

## Prerequisites
To open and run this network simulation, you'll need:

1. **GNS3** (version 2.2.56 or higher)
   - Download from: https://www.gns3.com/software/download

2. **Operating System Support**
   - Windows 10/11
   - macOS
   - Linux (Ubuntu, Debian, Fedora)

3. **Hardware Requirements**
   - Minimum 4GB RAM (8GB recommended)
   - Multi-core processor
   - 10GB free disk space

## Installation & Setup

### Step 1: Install GNS3
1. Download GNS3 from the official website
2. Run the installer and follow the setup wizard
3. Configure GNS3 VM or local compute settings

### Step 2: Clone the Repository
```bash
git clone https://github.com/Get-PrivilegedLogic/Openframe-Studios-Capstone.git
cd Openframe-Studios-Capstone
```

### Step 3: Open the Project
1. Launch GNS3
2. Click **File → Open Project**
3. Navigate to the cloned repository
4. Select `New_Openframe_Studios_Capstone.gns3`

### Step 4: Configure Network Devices
*Add your device configuration steps here based on your specific topology*

## Usage

### Starting the Network
1. Open the project in GNS3
2. Click the **Start All Devices** button (green play icon)
3. Wait for all devices to boot

### Accessing Devices
- Right-click on any device and select **Console** to access the CLI
- Use configured credentials to log in

### Testing Connectivity
```bash
# Example: Test connectivity between devices
ping [destination-ip]
traceroute [destination-ip]
```

## Network Topology
*Add a description or diagram of your network topology here*

### Key Components
- **Routers:** [Number and types]
- **Switches:** [Number and types]
- **End Devices:** [Workstations, servers, etc.]
- **Security Devices:** [Firewalls, etc.]

## Features Implemented
- [ ] Network Topology Design
- [ ] IP Addressing Scheme
- [ ] Routing Configuration
- [ ] Switching and VLANs
- [ ] Security Implementation
- [ ] Network Services (DHCP, DNS, etc.)
- [ ] Redundancy and High Availability
- [ ] Documentation

## Learning Outcomes
This project demonstrates proficiency in:
- Network design and architecture
- Cisco IOS configuration
- Subnet planning and IP addressing
- Routing protocol configuration
- Network security best practices
- Troubleshooting methodologies
- Technical documentation

## Troubleshooting

### Common Issues

**Issue: GNS3 can't find devices**
- Solution: Ensure you have the required IOS images or appliances installed

**Issue: Devices won't start**
- Solution: Check that GNS3 VM is running (if using VM integration)
- Solution: Verify you have sufficient RAM allocated

**Issue: Console won't open**
- Solution: Check that your terminal emulator is configured correctly

## Project Documentation
*Add links to additional documentation if available:*
- Network Diagram
- Configuration Files
- Test Results
- Project Report

## Future Enhancements
- [ ] Implement additional security features
- [ ] Add monitoring and logging solutions
- [ ] Expand network topology
- [ ] Implement automation scripts

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
**Get-PrivilegedLogic**
- GitHub: [@Get-PrivilegedLogic](https://github.com/Get-PrivilegedLogic)

## Acknowledgments
- Western Governors University
- GNS3 Community
- Openframe Studios

## Contact
For questions or feedback about this project, please open an issue or reach out through GitHub.

---

*This project was created as part of the WGU Capstone program.*
