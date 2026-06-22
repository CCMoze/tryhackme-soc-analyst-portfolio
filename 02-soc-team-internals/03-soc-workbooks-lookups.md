# SOC Workbooks and Lookups
Discover useful corporate resources to help you structure and simplify L1 alert triage.
https://tryhackme.com/room/socworkbookslookups

---

## Learning Objectives
- Familiarise yourself with SOC investigation workbooks
- Learn where to find and how to use asset inventory in SOC
- Understand the importance of corporate network diagrams
- Practice workflow building inside an interactive interface


---

## Key Concepts

### Assets & Identities
#### Identity Inventory
An identity inventory contains information about users and accounts within an organization, including:

- Employee roles
- Departments
- Contact information
- Privilege levels

✅ Key Idea:

When investigating an alert, analysts can use these to determine if the activity is expected/suspicious or not
- Active Directory, Excel spreadsheet

---

### Asset Inventories

Asset inventories contain information about systems and devices within an organization.

Examples:

- Workstations
- Servers
- Cloud resources
- Critical infrastructure

✅ Key Idea:

Understanding the purpose of a system helps analysts determine the potential impact of a compromise.

---

### Network Diagrams

Network diagrams provide visibility into how systems are connected.

They can help analysts identify:

- Network segments
- Exposed services
- System locations
- Communication paths

✅ Key Idea:

Network context helps determine whether activity is expected or potentially malicious.

---

### Lookups

Lookups are used to enrich alert data with additional context.

Common examples include:

- User lookups
- Asset lookups
- IP lookups
- Threat intelligence lookups

✅ Key Idea:

Alerts become much easier to investigate when they include information about the user, system, and network involved. 【4-af1e83】【2-b5a5db】

---

### SOC Workbooks

A SOC workbook (also called a playbook or runbook) is a structured guide for investigating specific alert types.

Workbooks help analysts:

- Follow consistent investigation steps
- Reduce mistakes
- Improve triage quality
- Speed up investigations

✅ Key Idea:

Workbooks allow junior analysts to perform investigations using repeatable processes developed by more experienced team members.

---

## Practical Exercises

The room included workbook-based investigations involving:

- Suspicious email attachments
- PowerShell activity
- Internal network activity

The exercises demonstrated how inventories, lookups, and documented workflows help analysts reach a consistent verdict.

---

## What I Learned

- Context is critical during alert triage
- Asset and identity inventories help explain who and what is involved in an alert
- Network diagrams provide valuable investigative context
- Workbooks create consistency across SOC teams
- Lookups help analysts investigate alerts more efficiently

---

## Screenshots
<img width="1300" height="526" alt="image" src="https://github.com/user-attachments/assets/f45ab4d3-506e-415c-9534-4ba8793fa21b" />
<img width="1300" height="700" alt="image" src="https://github.com/user-attachments/assets/7eff5cfd-3c1e-40b0-900a-842eb6ed051c" />


## Tags

SOC Analyst, Alert Triage, Workbooks, Playbooks, Runbooks, Asset Management, Identity Management, Threat Intelligence, Blue Team, TryHackMe
``
