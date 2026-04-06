# Active Directory Home Lab

Hands-on Windows Server lab built to simulate real help desk 
and IT support scenarios using Active Directory Domain Services.

## Why I Built This

Active Directory shows up in nearly every help desk and IT 
support job description. I built this lab to demonstrate I 
can actually do the work not just list it as a skill.

## What I Built

- Installed Windows Server 2022 in VirtualBox and promoted 
  it to a Domain Controller (lab.local)
- Created users (jsmith, sjones, mdavis) and organized them 
  into department Organizational Units: IT, HR, and Finance
- Simulated account lockout and recovery using both the GUI 
  and command line
- Performed a password reset with forced change on next login
- Created an IT_Admins security group and assigned a member

## STAR Breakdown

**Situation:** A user calls the help desk saying they cannot 
log into their account. The account has been flagged and 
locked due to failed login attempts.

**Task:** Locate the user in Active Directory, confirm the 
account is locked, reset access, and ensure the user can 
log back in securely.

**Action:** Opened Active Directory Users and Computers, 
located the user account, unlocked it via the Account tab, 
and reset the password with a forced change on next login. 
Also demonstrated the same workflow via command line using 
net user commands for environments without GUI access.

**Result:** Account restored with a new secure password. 
User can log back in and is required to set their own 
password on first login — following least privilege and 
security best practices.

## Skills Demonstrated

Active Directory · Windows Server · Identity and Access 
Management · User Provisioning · Organizational Units · 
Group Policy · Password Reset · Account Lockout Recovery · 
Command Line Administration

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
