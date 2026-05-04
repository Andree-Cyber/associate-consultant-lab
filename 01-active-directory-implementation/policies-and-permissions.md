
---

# `policies-and-permissions.md`

```md
# Policies and Permissions

## Security Groups

| Group | Members | Purpose |
|---|---|---|
| HR-Users | sarah.johnson | Access to HR folder |
| Finance-Users | michael.lee | Access to Finance folder |
| IT-Admins | david.kim, labadmin | Administrative access to department folders |
| Sales-Users | jasmine.brown | Access to Sales folder |

## Shared Folder Permissions

| Folder | Authorized Access |
|---|---|
| HR | HR-Users, IT-Admins |
| Finance | Finance-Users, IT-Admins |
| Sales | Sales-Users, IT-Admins |
| Public | Domain Users |

## Password Policy

| Setting | Value |
|---|---|
| Minimum password length | 10 characters |
| Password complexity | Enabled |
| Maximum password age | 90 days |

## Account Lockout Policy

| Setting | Value |
|---|---|
| Account lockout threshold | 5 invalid attempts |
| Account lockout duration | 15 minutes |
| Reset account lockout counter | 15 minutes |

## Group Policies

| GPO | Purpose |
|---|---|
| Password Policy - Company Standard | Enforces password requirements |
| Account Lockout Policy | Protects accounts from repeated failed login attempts |
| Map Shared Drives | Automatically maps department and public shares |
| Disable Control Panel for Standard Users | Prevents standard users from changing system settings |

## Access Control Summary

The lab follows the principle of least privilege by giving users access only to the folders required for their department. IT administrators were given access to all department folders for support and administrative purposes.