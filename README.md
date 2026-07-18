## Implementation Screenshots

### 1. Azure Resource Deployment

Created the Azure resource group and deployed the required networking resources.

![Resource Group](screenshots/01-resource-group.png)

![Virtual Machine](screenshots/17-virtual-machine.png)


### 2. Virtual Network Configuration

Configured the Azure Virtual Network and subnet structure.

![Virtual Network](screenshots/02-virtual-network.png)

![VNET Hub Subnets](screenshots/03-vnet-hub-subnets.png)


### 3. Azure VPN Gateway Deployment

Configured the VPN Gateway for secure remote connectivity.

![VPN Gateway](screenshots/04-vpn-gateway.png)


### 4. Point-to-Site VPN Configuration

Configured Point-to-Site VPN settings for remote administrators.

![Point-to-Site Configuration](screenshots/05-point-to-site-configuration.png)


### 5. Certificate-Based Authentication

Created and configured certificates for VPN authentication.

![Certificate Creation](screenshots/06-certificate-creation.png)

![VPN Client Certificate Authentication](screenshots/07-northwindvpnclient-authentication.png)


### 6. Azure VPN Client Connection

Connected the administrator workstation to Azure using the VPN client.

![Azure VPN Client](screenshots/08-azure-vpn-client.png)

![VPN Connection](screenshots/09-connection-to-azure-vm.png)


### 7. Private Network Connectivity Testing

Verified communication with the Azure VM using its private IP address.

![Private IP Address](screenshots/16-ip-address.png)

![Ping Private IP](screenshots/10-ping-private-ip.png)


### 8. Secure SSH Remote Administration

Accessed the Linux VM securely through the VPN connection.

![SSH Into Azure VM](screenshots/11-ssh-into-azure-vm.png)

![VM Testing](screenshots/12-testing-vm.png)


### 9. SSH Key Authentication Hardening

Configured SSH key authentication and tested passwordless access.

![SSH Key Configuration](screenshots/13-saved-ssh-key-on-nano.png)

![Password Authentication Removed](screenshots/14-removed-password-authentication.png)

![Passwordless SSH Test](screenshots/15-test-after-removing-password.png)
