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
7. Verified successful domain controller promotion using Active Directory Users and Computers.
8. Created an Employees organizational unit (OU).
9. Created and managed domain user accounts.
10. Performed a password reset with a required password change at next logon.
11. Disabled and re-enabled a user account.
12. Created an IT-Support global security group.
13. Added three users to the security group and verified their membership.
## Next Steps

- [ ] Validate Active Directory DNS functionality.
- [ ] Simulate and troubleshoot locked user accounts.
- [ ] Practice unlocking accounts in Active Directory.
- [ ] Create additional organizational units and security groups.
- [ ] Explore Group Policy Objects (GPOs).
- [ ] Document troubleshooting procedures and add supporting screenshots.

## Project Status
In progress — Windows Server 2025 domain controller deployed and Active Directory user and group management exercises completed. Additional DNS validation, account troubleshooting, and access management labs planned.
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
### Employees Organizational Unit

The Employees OU contains three test user accounts and the IT-Support security group.

![Active Directory Employees OU showing user accounts and IT-Support security group](screenshots/active-directory-employees-ou.png)
