# Active-directory-home-lab
Windows Server Active Directory Home Lab demonstrating user management, security groups, authentication, and access control.
## Screenshots

### 01 - Local Server Properties
Verified the Windows Server hostname (WIN-SERVER) and domain configuration (mydomain.local).

### 02 - Active Directory Domain Services
Verified Active Directory Domain Services (AD DS) is installed and operational.

### 03 - Active Directory Organizational Units
Verified the creation of the HR, IT, and Sales Organizational Units (OUs).

### 04 - IT Organizational Unit
Verified IT users and the IT_Users security group.

### 05 - HR Organizational Unit
Verified HR users and the HR_Users security group.

### 06 - Sales Organizational Unit
Verified Sales users and the Sales_Users security group.

### 07 - Sales_Test Group Membership
Confirmed Sales_Test is a member of the Sales_Users security group.

### 08 - IT User Group Membership
Confirmed the IT user is assigned to the IT_Users security group.

### 09 - HR User Group Membership
Confirmed the HR user is assigned to the HR_Users security group.

### 10 - Windows 10 Domain Join
Verified the Windows 10 client successfully joined the mydomain.local domain.

### 11 - (If applicable)
Verified the Sales shared folder is available on the network.

### 12 - Shared Folder Access
Verified Sales_Test successfully accessed the Sales shared folder.

### 13 - Shared Folder Permission Error
Identified a permissions issue preventing Sales_Test from creating files in the Sales shared folder.

### 14 - Share Permissions Updated
Updated Share Permissions by granting the Sales_Users group Change and Read access.

### 15 - Write Permission Success
Verified Sales_Test successfully created a text document after the Share Permissions issue was resolved.

### 16 - HR Authentication Test
Verified Charnell D. Turpin successfully authenticated to the mydomain.local domain.

### 17 - Access Denied Test
Confirmed the HR user could not access the Sales shared folder, demonstrating role-based access control and the Principle of Least Privilege.
