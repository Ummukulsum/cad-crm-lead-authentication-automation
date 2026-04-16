<div align="center">

# CAD Lead Intelligence System

AI-assisted lead qualification and authenticity workflow built for CAD Training Centre.

![Status](https://img.shields.io/badge/status-prototype-success)
![Automation](https://img.shields.io/badge/workflow-Pabbly-blue)
![AI](https://img.shields.io/badge/model-Google%20Gemini-orange)
![Stack](https://img.shields.io/badge/tools-Google%20Sheets%20%7C%20JSON-green)

</div>

---

## Overview

This project was built to improve inbound lead handling by reducing time spent reviewing low-quality submissions and helping staff prioritize genuine enquiries faster.

It combines workflow automation with AI classification to support day-to-day sales and admin operations.

---

## Business Problem

Manual lead review often included:

- Test or fake submissions  
- Incomplete contact details  
- Inconsistent phone number formats  
- No clear priority for follow-up  
- Time spent checking low-quality leads  

---

## Solution

Built an automated lead screening workflow using:

- Google Sheets  
- Pabbly Connect  
- Google Gemini  

When a new lead is received, the system analyzes the submission and returns structured outputs that help staff take the next step quickly.

<img src="assets/results-sheet.jpg" width="1000">

---

## Workflow Architecture

<img src="assets/workflow-overview.jpg" width="1000">

```text
Lead Form Submission
        ↓
Google Sheets
        ↓
Pabbly Connect Trigger
        ↓
Gemini AI Analysis
        ↓
Structured JSON Output
        ↓
Google Sheet Updated
        ↓
Staff Follow-Up
