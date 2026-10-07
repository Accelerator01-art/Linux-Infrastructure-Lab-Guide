Enterprise Linux & Windows Infrastructure Lab Guide
Overview
This repository contains technical documentation and lab guides developed during my tenure as a Student Tutor for the Introduction to Operating Systems (INOS) module. The guide demonstrates the end-to-end deployment, configuration, and management of a virtualized multi-OS enterprise environment.

Architecture
Hypervisor: Oracle VirtualBox

Servers: Ubuntu Server 22.04 LTS (LinServer)

Clients: Fedora Workstation (LinClient), Windows 10 (WinClient)

Core Technologies & Configurations Demonstrated
Networking: Static IP mapping, Netplan configuration, and cross-VM ICMP validation.

Storage Management: Disk partitioning, filesystem formatting (mkfs.ext2), and persistent volume mounting (/etc/fstab).

Systems Administration: Target runlevel management, repository configurations, and package administration.

Security & Access: User group provisioning, password aging enforcement, and POSIX Extended Access Control Lists (ACLs).

Automation & Monitoring: Dynamic Bash login scripts, automated system resource auditing, and Crontab scheduling.

Web Services: Apache web server infrastructure and intranet portal deployment.

Purpose
This documentation serves to assist students in practical, hands-on open-source operating system environments, providing a baseline for standard operating procedures (SOPs) in a junior infrastructure role.
