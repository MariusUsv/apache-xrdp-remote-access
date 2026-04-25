# SOHO LAN Security and Remote Services

## Overview
This project demonstrates the implementation of a SOHO network in a virtualized environment, including a web server and remote desktop access.

## Main Components
- Ubuntu 22.04
- VirtualBox NAT and Host-Only adapters
- Apache2 on port 8008
- XRDP on port 3389

## Implemented Features
- public web directory
- protected directory with Basic authentication
- admin directory restricted by IP
- remote desktop access from Windows

## Validation
- Apache service verified
- listening ports verified
- authentication tested
- RDP connection tested successfully

## Repository Structure
- `docs/`
- `screenshots/`
- `configs/`
- `scripts/`
## Screenshots

### Apache Setup & Security
![Apache Running](screenshots/apache/01_apache_service_running.png)
![Port 8008](screenshots/apache/02_apache_ports_8008.png)
![Default Page](screenshots/apache/03_apache_default_page.png)
![403 Forbidden](screenshots/apache/04_apache_403_forbidden.png)
![User Authentication](screenshots/apache/05_htpasswd_user_created.png)

### Network Configuration
![IP Configuration](screenshots/network/07_network_ip_config.png)
![Routing Table](screenshots/network/08_ip_route_terminal.png)

### Remote Desktop (XRDP)
![XRDP Service](screenshots/xrdp/09_xrdp_service_running.png)
![Remote Connection](screenshots/xrdp/10_xrdp_remote_connection.png)

## Notes
This repository contains the implementation report and supporting configuration examples.

## Author
Student: Marius Zaharia Andronic
Facultatea: Fiesc Calculatoare – dual
