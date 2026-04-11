# Active Directory User Management Lab

## Overview

This project demonstrates hands-on experience managing user accounts in Active Directory using PowerShell and administrative tools in a simulated enterprise environment.

---

## Objectives

* Create and manage Active Directory users
* Create and manage security groups
* Assign group memberships
* Verify configurations using command-line tools
* Perform bulk user import operations

---

## Technologies Used

* Windows Server
* Active Directory
* PowerShell
* CSVDE

---

## Key Tasks Performed

### User Account Creation

* Created multiple users using PowerShell (New-ADUser)
* Configured usernames, passwords, and account settings

### Group Management

* Created security groups using New-ADGroup
* Added users to groups using Add-ADGroupMember

### User Templates

* Created a template user for consistent account setup
* Applied group membership automatically

### Verification

* Verified group membership using dsquery and dsget
* Confirmed correct user assignments

### Bulk User Operations

* Imported users using CSV file (csvde)
* Automated account creation process

---

## Screenshots

### User Creation

![User Creation](images/users.png)

### Group Management

![Group Management](images/group.png)

### Template User

![Template User](images/template.png)

### Member Of Verification

![Member Of](images/memberof.png)

### DSQuery Verification

![DSQuery](images/dsquery.png)

### CSV Import

![CSV Import](images/csv.png)

---

## Key Skills Demonstrated

* Active Directory User Management
* PowerShell Automation
* Group Administration
* Bulk User Provisioning
* Command-Line Tools

---

## Summary

This lab demonstrates the ability to manage Active Directory users, automate administrative tasks, and verify configurations in a Windows domain environment.

