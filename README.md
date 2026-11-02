# Codomax Module 2 – Linux, Networking & Cloud Infrastructure

## Project Overview
This project demonstrates the setup and configuration of an Ubuntu Linux server using Oracle VirtualBox. It covers Linux command-line operations, network configuration, firewall security, SSH remote access, and web server deployment.

## Objectives
- Practise Linux command-line operations.
- Manage files, directories, and permissions.
- Configure network connectivity and SSH access.
- Enable firewall protection.
- Deploy and test a web service on an Ubuntu server.

## Tasks Completed

### 1. Linux Environment Setup
Installed Ubuntu Server in Oracle VirtualBox and configured the virtual machine. Practised essential Linux commands for navigation, file management, user identification, and permissions.

### 2. Networking and Security
Configured NAT networking and created an SSH port-forwarding rule. Enabled the UFW firewall and allowed OpenSSH traffic.

### 3. SSH Configuration
Installed and enabled the OpenSSH server. Verified that the SSH service was active and listening on port 22. Successfully connected remotely from Windows using port forwarding.

### 4. Apache Web Server Deployment
Installed Apache2 and verified that the service was running and enabled at startup. Created a custom HTML webpage and placed it in the Apache web directory. Tested the webpage using the `curl` command.

## Technologies and Tools Used
- Ubuntu Server
- Oracle VirtualBox
- Linux Command Line
- OpenSSH
- UFW Firewall
- Apache2
- Windows Command Prompt

## Server Configuration

| Configuration | Details |
|---|---|
| Hostname | codomax-server |
| Username | aishw |
| Network Mode | NAT |
| SSH Guest Port | 22 |
| SSH Host Port | 2222 |
| Web Server | Apache2 |

## Project Screenshots
Screenshots documenting the server setup, SSH connection, firewall configuration, Apache service, and webpage deployment are included in this repository.

## Outcome
Successfully configured an Ubuntu Linux server, secured remote access, deployed a custom webpage, and verified connectivity between Windows and the virtual server.

**Status: Module 2 Practical Implementation Completed**
