# Project 4: Enterprise Remote Access Infrastructure with Azure VPN Gateway

## Company
Northwind Logistics Ltd.

## Business Problem

Northwind Logistics has system administrators and IT engineers working remotely across multiple locations.

Previously, Azure virtual machines were accessible through public IP addresses, creating security risks including:

- Exposure of management ports to the internet
- Unauthorized SSH login attempts
- Increased attack surface
- Lack of secure remote administration

## Solution

Implemented an enterprise remote access solution using Azure VPN Gateway and Point-to-Site VPN.

Remote administrators connect securely to Azure through a VPN tunnel and access Linux virtual machines using private IP addresses.

## Architecture

Windows Administrator Laptop

⬇️

Azure VPN Client

⬇️

Point-to-Site VPN

⬇️

Azure VPN Gateway

⬇️

Azure Virtual Network

⬇️

Ubuntu Linux VM (Private IP: 10.10.1.4)


## Technologies Used

- Microsoft Azure
- Azure Virtual Network
- Azure VPN Gateway
- Point-to-Site VPN
- Azure VPN Client
- Ubuntu 24.04 LTS
- OpenSSH
- SSH Key Authentication
- Windows PowerShell


## Implementation

### 1. Azure Network Deployment

Created:

- Resource Group
- Virtual Network
- Subnets
- Gateway Subnet
- VPN Gateway

Screenshot:

![Virtual Network](screenshots/02-virtual-network.png)


### 2. VPN Configuration

Configured:

- Point-to-Site VPN
- Certificate authentication
- Client VPN configuration
- Azure VPN Client connection

Screenshot:

![Azure VPN Client](screenshots/08-azure-vpn-client.png)


### 3. Secure VM Access

Validated:

- VPN connectivity
- Private IP communication
- SSH access through VPN

Example:

```bash
ssh acnweze@10.10.1.4
