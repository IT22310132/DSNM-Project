# Linux-based Domain Controller & Infrastructure Monitoring System

This project demonstrates the deployment of an Active Directory-compatible Domain Controller using Fedora 42 and centralized system monitoring using Zabbix. Ubuntu was used as the domain-joined client machine. The setup is implemented in a virtualized environment and showcases how to build a fully functional identity and monitoring solution with open-source tools.

## Features

- Configured Samba AD-DC on Fedora 42 to provide centralized authentication
- Integrated Kerberos and DNS for secure domain-based authentication and name resolution
- Deployed Zabbix monitoring server on the same Fedora host
- Installed and configured Zabbix agent on client machines for full system visibility
- Monitored system health metrics (CPU, disk, memory), network connectivity, and authentication service status
- Created a real-time Zabbix dashboard to visualize the health of the domain and client machines

## Technologies Used

- Fedora 42
- Ubuntu 22.04 LTS
- Samba (AD-DC)
- Kerberos
- DNS
- Zabbix 7.2 LTS
- DHCP
- SSSD
- systemd

## Why This Project

- Fedora was selected for its modern package ecosystem and strong SELinux integration, making it ideal for running critical server components.
- Ubuntu was chosen as the client OS for its wide adoption, simplicity, and excellent compatibility with enterprise environments.
- Zabbix was used for its comprehensive monitoring capabilities and integration with Linux-based infrastructures.

## Usage

This project can be used as a reference for:
- Academic or lab-based AD-DC deployments using Linux
- Monitoring infrastructure performance with Zabbix in a small-scale environment
- Understanding the integration of authentication and monitoring services in open-source systems

