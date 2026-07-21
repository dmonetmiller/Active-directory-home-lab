# Active Directory Home Lab

## Objective

The purpose of this Active Directory Home Lab was to build and administer a Windows Server environment in a controlled setting using Oracle VirtualBox. This project focused on understanding core Active Directory concepts, including Organizational Units (OUs), user and group management, domain authentication, shared folder permissions, and role-based access control.

The lab was designed to simulate a real-world enterprise environment and provide hands-on experience with Active Directory administration, troubleshooting, and Windows networking concepts commonly used in IT Support and Systems Administration roles.

---

## Skills Learned

- Active Directory User and Group Management
- Organizational Unit (OU) Administration
- Domain Authentication and Authorization
- Security Group Configuration
- NTFS and Share Permissions
- Windows Server Administration
- Access Control and Least Privilege
- Windows 10 Domain Join
- Troubleshooting Authentication and Permission Issues
- Technical Documentation
- Project Documentation

---

## Tools Used

- Oracle VirtualBox
- Windows Server 2022
- Windows 10
- Active Directory Domain Services (AD DS)
- Active Directory Users and Computers
- File Explorer
- NTFS Permissions
- Share Permissions

---

## Lab Environment

| Component | Description |
|----------|----------|
| Server | WIN-SERVER |
| Client | Windows 10 |
| Domain | mydomain.local |
| Organizational Units | HR, IT, Sales |
| Security Groups | HR_Users, IT_Users, Sales_Users |
| Virtualization Platform | Oracle VirtualBox |

---

## Key Accomplishments

- Deployed a Windows Server Active Directory environment.
- Created and managed Organizational Units (HR, IT, and Sales).
- Created domain users and security groups.
- Joined a Windows 10 client to the domain.
- Configured and troubleshot Share and NTFS permissions.
- Validated domain authentication across multiple users.
- Demonstrated role-based access control.
- Applied the Principle of Least Privilege.
- Documented the project using 17 screenshots.

---

## Screenshots

### 01 - Local Server Properties

Verified the Windows Server hostname (WIN-SERVER) and domain configuration (mydomain.local).

![Local Server Properties](screenshots/01-Local-Server-Properties.png)

### 02 - Active Directory Domain Services

Verified Active Directory Domain Services (AD DS) is installed and operational.

![Active Directory Domain Services](screenshots/02-AD-DS.png)

### 03 - Active Directory Organizational Units

Verified the creation of the HR, IT, and Sales Organizational Units (OUs).

![Active Directory Organizational Units](screenshots/03-Active-Directory-OUs.png)

### 04 - IT Organizational Unit

Verified IT users and the IT_Users security group.

![IT Organizational Unit](screenshots/04-IT-OU-Users-and-Group.png)

### 05 - HR Organizational Unit

Verified HR users and the HR_Users security group.

![HR Organizational Unit](screenshots/05-HR-OU-Users-and-Group.png)

### 06 - Sales Organizational Unit

Verified Sales users and the Sales_Users security group.

![Sales Organizational Unit](screenshots/06-Sales-OU-Users-and-Group.png)

### 07 - Sales_Test Group Membership

Confirmed Sales_Test is a member of the Sales_Users security group.

![Sales_Test Group Membership](screenshots/07-Sales-Test-Group-Membership.png)

### 08 - IT User Group Membership

Confirmed the IT user is assigned to the IT_Users security group.

![IT User Group Membership](screenshots/08-IT-User-Group-Membership.png)

### 09 - HR User Group Membership

Confirmed the HR user is assigned to the HR_Users security group.

![HR User Group Membership](screenshots/09-HR-User-Group-Membership.png)

### 10 - Windows 10 Domain Join

Verified the Windows 10 client successfully joined the mydomain.local domain.

![Windows 10 Domain Join](screenshots/10-Windows10-Client-Domain-Joined.png)

### 11 - Sales Shared Folder

Verified the Sales shared folder is available on the network.

![Sales Shared Folder](screenshots/11-Sales-Share-Visible.png)

### 12 - Shared Folder Access

Verified Sales_Test successfully accessed the Sales shared folder.

![Shared Folder Access](screenshots/12-Sales-Share-Opened.png)

### 13 - Shared Folder Permission Error

Identified a permissions issue preventing Sales_Test from creating files in the Sales shared folder.

![Shared Folder Permission Error](screenshots/13-Sales-Write-Permission-Error.png)

### 14 - Share Permissions Updated

Updated Share Permissions by granting the Sales_Users group Change and Read access.

![Share Permissions Updated](screenshots/14-Sales-Share-Permissions-Updated.png)

### 15 - Write Permission Success

Verified Sales_Test successfully created a text document after the Share Permissions issue was resolved.

![Write Permission Success](screenshots/15-Sales-Write-Permission-Success.png)

### 16 - HR Authentication Test

Verified Charnell D. Turpin successfully authenticated to the mydomain.local domain.

![HR Authentication Test](screenshots/16-HR-Authentication-Test.png)

### 17 - Access Denied Test

Confirmed the HR user could not access the Sales shared folder, demonstrating role-based access control and the Principle of Least Privilege.

![Access Denied Test](screenshots/17-HR-Access-Denied-Sales-Share.png)

---

## Documentation

- Active Directory documentation.docx

---

## Project Status

- Status: Complete
- Version: 1.0
- Started: July 9, 2026
- Completed: July 16, 2026
