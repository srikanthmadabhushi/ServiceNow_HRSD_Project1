# ServiceNow_HRSD_Project1
# ServiceNow HRSD | AI-Powered Case Categorization (Yokohama PDI)

## Overview
This project simulates **AI-driven case categorization** for HR teams.  
When employees create HR Cases, Flow Designer automatically analyzes the short description and classifies the case into **Benefits, Payroll, Leave, Access, or General**.

## Flow Logic
1. **Trigger:** HR Case created or updated  
2. **If:** Short description contains "benefit", "payroll", "leave", or "access" (case-insensitive)  
3. **Then:** Update Category & AI Notes accordingly  
4. **Else:** Default category = General  

## Highlights
- Built on **ServiceNow Yokohama PDI** (no HR plugin required)
- Simulates Predictive Intelligence logic
- Fully no-code using **Flow Designer**
- Captures AI reasoning in “AI Notes”

## Diagram
![Flow Diagram](Diagrams/HRSD_AI_Categorization.png)

## Outcome
HR cases are automatically categorized based on their short description,
reducing manual triage and showcasing **AI workflow simulation** inside ServiceNow.
