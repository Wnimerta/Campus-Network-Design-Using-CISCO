# Campus Network Design Project

Welcome to the GitHub repository for the **Campus Network Design Project**! This project demonstrates a complete network design for the **Sukkur IBA Main Campus** and its **EDC Branch Campus** using **Cisco Packet Tracer**. The project showcases a scalable and efficient network configuration with VLANs, RIP routing, DHCP, and IP addressing.

## Project Overview
This project's objective is to establish a robust campus-wide network that ensures seamless communication between departments, campuses, and external services.

### Main Campus:
- **8 Departments** across **4 buildings**.
- Each department has:
  - 1 PC
  - 1 Printer
  - Connected to a **Cisco 2960 switch**.
- All department switches are connected to a **Cisco 3650-24PS switch**.

### EDC Branch Campus:
- **Two floors**: Ground and First Floor.
- Each floor has:
  - 1 PC
  - 1 Printer
  - Connected to a **Cisco 2960 switch**.
- All switches connect to a **Cisco 3650 switch**.

### Core Network Design:
- **Cisco 2911 routers** connect:
  - Main Campus
  - EDC Branch Campus
  - Cloud Network.
- The cloud network hosts an **email server** connected via a router.

## Technical Details
### IP Configuration:
- PCs: **192.168.1.2 to 192.168.100.2**
- Cloud Router IP: **20.0.0.0/30**
- Main Campus Router IP: **10.10.10.4/30**
- EDC Campus Router IP: **10.10.10.0/30**

### Features:
- **VLANs:** VLAN IDs 10 to 100 for department segmentation.
- **Routing Protocol:** RIP for inter-network communication.
- **DHCP:** Dynamic IP address allocation for devices.

### Testing and Verification:
- Successful pinging between all devices to ensure proper connectivity.
- Configurations implemented entirely through the **Command Line Interface (CLI)**.

## Tools and Technologies
- **Cisco Packet Tracer**
- **Cisco 2960 Switches**
- **Cisco 3650 Switches**
- **Cisco 2911 Routers**

``
## Acknowledgments
This project was developed as part of my coursework in **Computer Systems Engineering**. 

### Reference:
I followed this [YouTube tutorial](https://youtu.be/qIbhkmTB8Q8?si=dj_vZdvYBaqzFFdl) to help complete this project.

This project has been a great learning experience, strengthening my skills in network design and simulation. I’ve also created a detailed YouTube vlog explaining the entire process!
👉 YouTube Vlog: [Watch My Vlog Here](https://youtu.be/0zQJY3nXtJ0?si=FFmz-YhlPet9iBid)
## License
This project is licensed under the MIT License. See the LICENSE file for details.

