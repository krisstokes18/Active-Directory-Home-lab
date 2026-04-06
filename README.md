# Active Directory Home Lab — In Progress. Windows Server VM lab covering user creation, permissions, and lockout recovery. Documentation coming soon.

Hands-on Active Directory lab built to demonstrate user 
provisioning, group management, account lockouts, password 
resets, and MFA simulation in a Windows Server environment.

## Why I Built This
Active Directory appears in nearly every help desk and IT 
support JD. Built this lab to show I can do it, not just 
list it.

## What It Covers
- Windows Server VM setup and AD installation
- User creation, group assignment, and permission management
- Account lockout simulation and recovery
- Password reset workflows
- MFA configuration

## Skills
Active Directory · Windows Server · IAM · User Provisioning · 
Group Policy · Identity Management

### Completed Steps
- Windows Server 2022 installed in VirtualBox
- Active Directory Domain Services role installed
- Server promoted to Domain Controller (lab.local)
- Created 3 users: jsmith, sjones, mdavis
- Created 3 Organizational Units: IT, HR, Finance
- Simulated account lockout and recovery
- Performed password reset with forced change on next login
- Created IT_Admins security group

## Screenshots

### Windows Server 2022 Installed
![Windows Server Installed](docs/windows_server_2022_installed.png)

### Active Directory Role Installed
![AD Role Installed](docs/ad_role_installation_complete.png)

### Users Created in Active Directory
![AD Users Created](docs/ad_users_created.png)

### Organizational Units
![IT Department OU](docs/IT_Department_OU.png)
![HR Department OU](docs/HR_Department_OU.png)
![Finance Department OU](docs/Finance_Department_OU.png)

### Account Lockout Simulation
![Account Active Before Lockout](docs/account_active_before_lockout.png)
![Account Disabled](docs/account_disabled_lockout.png)
![Account Unlocked](docs/account_unlocked.png)
![Disable and Re-enable via Command Line](docs/account_disable_reenable_commands.png)

### Password Reset
![Password Reset Confirmation](docs/password_reset_confirmation.png)

### Security Group
![IT Admins Group with Member](docs/IT_Admins_group_with_member.png)


## Links
- LinkedIn: https://www.linkedin.com/in/kris-stokes-it/
