# Requirements

## Virtual Machines

| VM | Purpose |
|---|---|
| Windows Server 2022 | Domain Controller |
| Windows 10 | Employee Workstation |

## Naming Requirements

| Item | Name |
|---|---|
| Server | DC01 |
| Client | WIN10-CLIENT01 |
| Domain | consultinglab.local |
| Admin Account | labadmin |

## Active Directory Requirements

Create the following Organizational Unit structure:

```text
ConsultingLab
├── Users
│   ├── HR
│   ├── Finance
│   ├── IT
│   └── Sales
├── Computers
└── Groups