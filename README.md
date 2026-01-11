# Automated Reconciliation Report Workflow

![Workflow Diagram](https://github.com/user-attachments/assets/5b823b8c-bd6e-4f32-9a5b-bc336bd11bf0)

## Overview
This project demonstrates an **Automated Reconciliation Report** workflow using Alteryx (portfolio-safe version with dummy data).  
The workflow automates the extraction, reconciliation, and reporting of ticket data between multiple sources, producing a ready-to-share report while ensuring accuracy and reducing manual effort.  

> ⚠️ **Note:** This repository uses **dummy data for demonstration**. The production workflow is company-owned and confidential.

---

## Purpose
- Automate daily reconciliation of tickets from multiple systems (Website A & B).  
- Detect anomalies and ensure consistency across data sources.  
- Generate clean, structured reports (PDF/Excel) with summary metrics.  

---

## Key Features
- Automatic extraction of 10-digit tickets from multiple sources.  
- Data transformation and anomaly detection (e.g., malformed or missing tickets).  
- Report generation using **Report Text tool in Expert Mode (PCXL)**:
  - Headers, instructions, and summary text
  - Line breaks (`<BR/>`) and dynamic info (date, total tickets, anomalies)
  - Tables showing matched, missing, and anomalous tickets
- Automatic output (PDF/Excel) with folder saving capability.  
- Portfolio-safe design demonstrating workflow logic without exposing production data.  

---

## Workflow Steps
1. **Load Input Data:** Import dummy CSVs for Website A and B tickets.  
2. **Clean & Process:** Filter, normalize, and detect anomalies in the dataset.  
3. **Reconcile Tickets:** Match tickets and flag missing or malformed entries.  
4. **Generate Report:** Format tables and summaries using Report Text and Table tools.  
5. **Output Automatically:** Render PDF/Excel report with summary metrics.  

---

## Business Impact
- **Saves time:** Eliminates manual ticket comparisons.  
- **Reduces errors:** Automated anomaly detection ensures accuracy.  
- **Professional reports:** Clean formatting, ready for managers.  
- **Scalable:** Can run daily or adapt to multiple sources.  

---

## Demo & Repository
- **Diagram:** ![Workflow Diagram](https://github.com/user-attachments/assets/abac45c6-5367-4f60-92b0-e4595f130718)  
- **Demo Video:** [YouTube Demo](https://youtube.com/your-demo-video)  
- **GitHub Repository:** This repository contains a portfolio-safe workflow using dummy data.

