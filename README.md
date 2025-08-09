# Domain-Infrastructure-DNS-DHCP-Group-Policy
Engineered complete domain infrastructure configuration for Keytech.ca to ensure proper user rights and centralized management of company resources. Used DHCP, DNS, NPS, and Group Policy with Windows Sever 2016 and Active Directory Domain Services 

Project Overview
- This project covers the deployment of a Windows Server 2016 Domain Infrastructure with key network services including:

- DNS (Domain Name System): Resolves domain names to IP addresses within the network.

- DHCP (Dynamic Host Configuration Protocol): Automatically assigns IP addresses and network configurations to clients.

- NPS (Network Policy Server): Provides centralized authentication, authorization, and accounting for network access via RADIUS.

Together, these services form the backbone of a secure and manageable Active Directory domain environment.

Features
- DNS authoritative zone hosting internal domain.

- DHCP scopes configured for IP address distribution.

- NPS configured for 802.1X or VPN authentication.

- Integration with Active Directory for policy enforcement.

System Requirements
- Windows Server 2016 installed and promoted to Domain Controller.

- Proper network segmentation.

- Active Directory domain environment.

Setup Instructions
1. Install and configure DNS with forward and reverse lookup zones.

2. Install and configure DHCP scopes, reservations, and options.

3. Install and configure NPS for RADIUS authentication.

4. Integrate NPS policies with Active Directory groups.

5. Test network device authentication and IP allocation.

Testing
- Confirm clients receive IP addresses via DHCP.

- Verify DNS name resolution internally.

- Test client authentication through NPS policies.

Notes
- Ensure DHCP and DNS are authorized in Active Directory.
- Regularly monitor logs and NPS accounting for network security.


