## Project Overview
This repository contains the report, evidence (screenshots + tool outputs), and commands used to assess exposed services and firewall behavior.

## Scope & Ethics
- Passive and controlled scanning/enumeration only
- No credential attacks, exploitation, or bypass attempts
- Lab rules and ethical guidelines followed

## Target Summary (Lab)
- Firewall: pfSense
- WAN: Dual WAN with NAT + load balancing
- Observed reachable services (from assessment): TCP/53 (DNS), TCP/80 (HTTP)

## Tools Used
- Kali Linux, Nmap, Nikto, DIRB, curl, nslookup, WhatWeb

## Repository Structure
- `report/` Final report (DOCX + PDF)
- `evidence/screenshots/` Screenshots organized by assessment phase
- `evidence/outputs/` Raw outputs saved by tool
- `commands/` Commands used in the lab
- `scope-and-notes/` Methodology and lab scope notes

## How to Navigate Evidence
Start with:
1. `report/`
2. `commands/commands.md`
3. `evidence/screenshots/` (phase-wise)
4. `evidence/outputs/` (raw tool outputs)

## Author
Student: AMMAR IQBAL  
Course: Cybersecurity
