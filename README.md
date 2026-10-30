# Active Directory Home Lab

## Project Overview
This project documents my hands-on experience building a Windows Server 2025 Active Directory lab using Oracle VirtualBox. The goal is to develop practical IT support, Windows Server administration, networking, and identity management skills.

## Lab Environment
- Virtualization: Oracle VirtualBox
- Operating System: Windows Server 2025
- Server Name: DC01
- Active Directory Domain: corp.example.test
- Network Configuration: NAT
- Static IPv4 Address: 10.0.2.15
- Subnet Mask: 255.255.255.0
- Default Gateway: 10.0.2.2
- Preferred DNS Server: 10.0.2.15

## Work Completed
1. Configured a Windows Server 2025 virtual machine in VirtualBox.
2. Configured a static IPv4 address and DNS settings.
3. Installed the Active Directory Domain Services role.
4. Configured a new Active Directory forest named corp.example.test.
5. Passed the domain controller prerequisite checks.
6. Started domain controller promotion and observed the server restart.

## Next Steps
- Verify successful domain controller promotion.
- Validate Active Directory and DNS functionality.
- Create and manage domain user accounts.
- Practice common IT Help Desk tasks, including password resets and account unlocks.
- Document troubleshooting procedures and screenshots.

## Project Status
In progress — domain controller verification pending.
## Lab Screenshots

### Active Directory Prerequisites Check

![Active Directory Prerequisites Check](screenshots/active-directory-prerequisites-check.jpg)
## Active Directory User and Group Management

### User Account Management
- Created an Employees organizational unit (OU) to organize domain user accounts.
- Provisioned test user accounts for Peter Parker, Miles Morales, and Gwen Stacy.
- Practiced resetting user passwords and requiring password changes at next logon.
- Disabled and re-enabled a user account to simulate temporary employee leave.
- Deleted an unused test account.

### Security Group Management
- Created an IT-Support global security group.
- Added three domain users to the security group.
- Verified group membership using Active Directory Users and Computers.

### Skills Practiced
- Active Directory Domain Services (AD DS)
- User provisioning and account lifecycle management
- Password administration
- Security group creation and membership management
- Basic identity and access management (IAM)
### Security Group Membership Verification

![IT-Support security group showing Peter Parker, Miles Morales, and Gwen Stacy](screenshots/it-support-group-members.png)
