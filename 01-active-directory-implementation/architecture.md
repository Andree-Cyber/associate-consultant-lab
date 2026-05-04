
---

# `architecture.md`

```md
# Architecture

## Lab Design

This lab uses a simple client-server Active Directory design. A Windows Server 2022 virtual machine acts as the domain controller for the `consultinglab.local` domain. A Windows 10 virtual machine acts as an employee workstation joined to the domain.

## Network Layout

| System | Hostname | Role |
|---|---|---|
| Windows Server 2022 | DC01 | Domain Controller, DNS, File Share Server |
| Windows 10 | WIN10-CLIENT01 | Domain-Joined Workstation |

## Domain

```text
consultinglab.local