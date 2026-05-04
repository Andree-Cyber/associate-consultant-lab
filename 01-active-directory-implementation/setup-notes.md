
---

# `setup-notes.md`

```md
# Setup Notes

## 1. Server Setup

- Installed Windows Server 2022 Desktop Experience
- Renamed the server to DC01
- Configured static IP settings
- Installed Active Directory Domain Services
- Promoted DC01 to a domain controller
- Created the domain: consultinglab.local

## 2. Active Directory Setup

- Opened Active Directory Users and Computers
- Created the main ConsultingLab OU
- Created Users, Computers, and Groups OUs
- Created department OUs for HR, Finance, IT, and Sales

## 3. User Setup

Created the following test users:

- Sarah Johnson - sarah.johnson
- Michael Lee - michael.lee
- David Kim - david.kim
- Jasmine Brown - jasmine.brown
- Lab Admin - labadmin

## 4. Security Group Setup

Created the following security groups:

- HR-Users
- Finance-Users
- IT-Admins
- Sales-Users

Users were added to their department groups.

## 5. Shared Folder Setup

Created shared folders under:

```text
C:\CompanyShares