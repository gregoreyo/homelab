# Homelab

Welcome to my Homelab repository! This space is a comprehensive overview of my homelab, including hardware specifications, software configurations, network diagrams, and project details.

This repository is a living document as I experiment with new technologies, refine existing setups, and tackle new challenges. My goal is to create a resource that helps me maintain my homelab and provides valuable insights and examples for others looking to build or expand their own environments.

## Table of Contents

- [Hardware](#hardware)
- [Software](#software)
- [Networking](#networking)
- [Services](#services)
- [Projects](#projects)

## Hardware

This section details the physical hardware components of my homelab.

- **Servers:**
    - [Desktop Tower (Custom Built)](hardware/servers/desktop_tower.md) - Specifications, purpose, and configuration.
    - [Intel NUC (Model)](hardware/servers/intel_nuc.md) - Specifications, purpose, and configuration.
- **Networking Equipment:**
    - [pfSense Router (Model)](hardware/networking/pfsense_router.md) - Configuration and settings.
    - [Dumb Switch (Model)](hardware/networking/dumb_switch.md) - Configuration and basic setup.
    - [Access Point (Model)](hardware/networking/access_point.md) - Configuration and settings.
- **Storage:**
    - [Synology NAS (Model)](hardware/storage/synology_nas.md) - Configuration and storage setup.
    - [External Drives](hardware/storage/external_drives.md) - Details on connected external storage.
- **Other Devices:**
    - [Cheap UPS (Model)](hardware/other/cheap_ups.md) - Configuration and monitoring.
    - [ZimaBoard (Model)](hardware/other/zimaboard.md) - Purpose and setup.

## Software

This section outlines the software used in the homelab, including operating systems, virtualization platforms, and applications.

- **Operating Systems:**
    - [Linux (Distribution)](software/os/linux.md) - Configuration and customizations.
    - [Windows Server (Version)](software/os/windows_server.md) - Configuration and roles.
    - ...
- **Virtualization:**
    - [Proxmox VE](software/virtualization/proxmox.md) - Configuration and VM setup.
    - [Docker](software/virtualization/docker.md) - Container configurations and usage.
    - [Kubernetes](software/virtualization/kubernetes.md) - Cluster setup and deployments.
    - ...
- **Applications:**
    - [Plex](software/applications/plex.md) - Configuration and library setup.
    - [Nextcloud](software/applications/nextcloud.md) - Configuration and usage.
    - [Home Assistant](software/applications/home_assistant.md) - Configuration and automations.
    - ...

## Networking

This section describes the network configuration, including IP addressing, VLANs, and firewall rules.

- [Network Diagram](networking/network_diagram.md) - Visual representation of the network topology.
- [IP Addressing](networking/ip_addressing.md) - IP address assignments and subnets.
- [VLANs](networking/vlans.md) - VLAN configuration and purpose.
- [Firewall Rules](networking/firewall.md) - Firewall configuration and security policies.
- [DNS Configuration](networking/dns.md) - DNS server setup and records.
- [VPN Configuration](networking/vpn.md) - VPN setup and remote access.

## Services

This section documents the various services running in the homelab.

- [Web Server](services/web_server.md) - Configuration and hosted websites.
- [Media Server](services/media_server.md) - Media streaming and management.
- [File Server](services/file_server.md) - File sharing and storage.
- [Database Server](services/database_server.md) - Database configuration and usage.
- [Monitoring](services/monitoring.md) - Monitoring tools and setup.
- [Backup](services/backup.md) - Backup strategies and configurations.

## Projects

This section details specific projects undertaken in the homelab.

- [Project 1: VirtualBox Network Setup](projects/virtualbox_network_setup.md) - Setting up VirtualBox and networking VMs.
    - **Description:** This project was about setting up VirtualBox on the Desktop tower and configuring virtual machines to communicate with each other and the host network.
    - **Implementation:**
        - Installed VirtualBox on the host machine.
        - Created multiple virtual machines with different operating systems.
        - Configured VirtualBox network settings using internal and bridged adapters.
        - Configured static IP addresses for the VMs.
        - Tested network connectivity between VMs and the host.
    - **Outcome:** A working VirtualBox environment with networked VMs, allowing for testing and development in an isolated environment.

- [Project 2: Proxmox VE Setup](projects/proxmox_setup.md) - Setting up and configuring Proxmox VE for virtualization.
    - **Description:** This project focused on installing and configuring Proxmox VE on the desktop tower to create a robust virtualization environment.
    - **Implementation:**
        - Installed Proxmox VE from a bootable USB drive.
        - Configured network settings and storage pools.
        - Created initial virtual machines for various services.
        - Setup backups for the VMs.
    - **Outcome:** A stable and efficient virtualization platform, allowing for easy management of multiple virtual machines and services.

- [Project 3: Minecraft Server](projects/minecraft_server.md) - Setting up a dedicated Minecraft server.
    - **Description:** This project involved setting up a Minecraft server to play with friends and family.
    - **Implementation:**
        - Created a Linux VM on Proxmox VE.
        - Installed Java and the Minecraft server software.
        - Configured server settings, including memory allocation and port forwarding.
        - Setup a dynamic DNS to access the server remotely.
        - Implemented backups for the world data.
    - **Outcome:** A functional and accessible Minecraft server, providing a fun and engaging experience for multiple players.

- [Project 4 (Name)](projects/project4.md) - Description, implementation, and outcomes.
- ...
