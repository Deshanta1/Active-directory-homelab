# Active-directory-homelab
Practicing IT admin basics in a Windows Server 2019 lab - creating users, assigning groups, managing passwords, and setting up AD like it's a real network.

# Active Directory Home Lab (Windows Server 2019)

This project simulates a basic enterprise setup using Active Directory on Windows Server 2019. I used a local VM to practice identity and access management tasks like user creation, group assignments, password resets, and policy enforcement.

---

## Lab Environment

- Windows Server 2019 (VM on Oracle VirtualBox)
- Active Directory Domain Services (AD DS) role installed
- Local Admin privileges

---

## Lab Setup Steps

### 1. Install and Configure AD DS

- Promoted Windows Server 2019 to a domain controller.
- Created a new domain: `homelab.local`
- Verified AD DS and DNS roles were installed.


### 2. Create Organizational Units (OUs)

- Created OUs for structure:
  - `Users`
  - `IT`
  - `HR`
  - `Test Accounts`


### 3. Create and Manage Users

- Created multiple users with realistic usernames and job titles.
- Configured properties like descriptions, departments, and contact info.



### 4. Create and Assign Security Groups

- Created security groups (e.g., `IT_Admins`, `HR_ReadOnly`).
- Assigned users to appropriate groups based on role.


### 5. Password Policies & Resets

- Applied basic password policy (expiration, complexity).
- Demonstrated how to reset a user’s password and force password change at next logon.



## Skills Practiced

- Active Directory setup and management  
- User and group administration  
- Organizational Unit structuring  
- Windows Server 2019 configuration

---

## Takeaways

- Practiced real-world user/group workflows in a secure environment.
- Simulated IT admin tasks often handled in help desk, system admin, or SOC support roles.
- Learned how AD ties into authentication, access control, and policy enforcement.

---

## What’s Next?

- Combine this lab with Nessus scanning and POA&M reporting for a hybrid GRC/technical workflow.

