[README.md](https://github.com/user-attachments/files/27063444/README.md)
# Azani Internet Service Provider (ISP) Information System

![Project Status](https://img.shields.io/badge/status-active-brightgreen.svg)
![KCSE Year](https://img.shields.io/badge/KCSE-2026-blue.svg)

## Overview
This repository contains the system documentation and database implementation for the **KCSE 2026 Computer Studies Project (Paper 451/3)**. The project focuses on building an information management system for **Azani ISP**, a company providing internet bandwidth, LAN infrastructure, and IT equipment to educational institutions across Kenya.

As part of the SAJI tech ecosystem, this repository is structured to maintain clean version control, comprehensive documentation, and modularity.

## Milestones
The project is divided into two primary deliverables as per KNEC guidelines:
- **Milestone 1:** System Documentation (System Analysis, ERD, Data Dictionary, Flowcharts, Normalization).
- **Milestone 2:** System Implementation (Microsoft Access Database with Tables, Queries, Forms, and Reports).

## Features
- **Client Management:** Registration and tracking of educational institutions (primary, junior, senior schools, and colleges).
- **Bandwidth Subscriptions:** Management of internet packages (4 Mbps to 50 Mbps).
- **Hardware Sourcing & Sales:** Processing computer equipment orders, tracking deliveries from suppliers, and managing retail operations for institutional clients.
- **LAN Installations:** Managing networking infrastructure deployments and tracking installation costs.
- **Billing & Payments:** Automated calculations for subscriptions, upgrade discounts, overdue fines, and aggregated revenue tracking.

## Repository Structure
```text
├── docs/
│   ├── milestone_1_documentation.docx
│   ├── system_flowcharts.pdf
│   └── ER_diagrams.png
├── database/
│   └── azani_isp_system.accdb
├── src/
│   └── sql_queries_backup.sql    # Exported queries for native terminal review
├── config/
│   └── continue_context.json     # Context file for local LLM assistants
├── .gitignore
└── README.md
```

## Development Environment
- **Primary Platform:** Microsoft Access 2016+ (Windows)
- **Documentation:** Microsoft Word / Markdown
- **AI Assistance:** Context configurations are designed to be read by the Continue VS Code extension for optimization with Llama 3.2 1B models locally.

### Native Execution & Export Notes
While the core KNEC project is bound to MS Access for examination purposes, SQL queries and data models are continuously exported to the `src/` directory. This allows for seamless review natively within a terminal environment on Mint 22 using standard text tools, bypassing the need to launch a GUI for quick code checks.

## Setup Instructions
1. Clone the repository to your local machine.
2. Ensure you have Microsoft Office (Access) installed for the database component.
3. Open `database/azani_isp_system.accdb`.
4. Enable macros and active content if prompted by Access security settings.
