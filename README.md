# Active Directory Implementation for a Small Business

## Project Overview

This project simulates an Active Directory implementation for a small business client. The lab focuses on centralized identity management, department-based access control, password security policies, shared network folders, and domain-joined workstations.

The goal is to demonstrate technical implementation skills and consulting-style documentation for a client modernization project.

## Client Scenario

A small business with 25 employees currently uses separate local computer accounts. They need a centralized login system, stronger password rules, organized departments, shared folders, and basic access control.

The goal is to improve security, simplify employee onboarding, and reduce IT management time.

## Lab Environment

| VM | Purpose |
|---|---|
| Windows Server 2022 | Domain Controller |
| Windows 10 | Employee Workstation |

## Naming Plan

| Item | Name |
|---|---|
| Server | DC01 |
| Client | WIN10-CLIENT01 |
| Domain | consultinglab.local |
| Admin Account | labadmin |

## Active Directory Structure

Organizational Units were created to organize users, computers, and groups by business function.

```text
ConsultingLab
├── Users
│   ├── HR
│   ├── Finance
│   ├── IT
│   └── Sales
├── Computers
└── Groups