# startup-company-research-agent
Agentic Company Researcher via n8n

# Startup Company Research Agent

An AI-powered startup intelligence workflow that researches companies and automatically stores structured business information into Google Sheets.

---

# Business Problem

Sales professionals, founders, recruiters, and business analysts often spend hours researching companies before outreach.

The manual process involves:

* Searching websites
* Finding contact information
* Identifying decision makers
* Checking company size
* Determining industry

This workflow automates the entire research process and returns structured company intelligence in seconds.

---

# Workflow Architecture

```text
Manual Trigger
      │
      ▼
Research Request
      │
      ▼
OpenAI Agent
      │
      ▼
Perplexity Search
      │
      ▼
Structured Data Parser
      │
      ▼
Google Sheets
```

---

# Integrations Used

## OpenAI

Analyzes search results and structures company intelligence.

## Perplexity AI

Performs real-time company research.

## Google Sheets

Stores research output automatically.

---

# Data Collected

For every startup:

* Company Name
* Contact Email
* Employee Count
* CEO / Founder
* Industry

---

# Expected Outcomes

✅ Faster company research

✅ Structured lead database

✅ Decision maker identification

✅ Sales prospecting support

✅ Startup intelligence collection

✅ Reduced manual research time

---

# Setup Instructions

## Requirements

* n8n
* OpenAI API
* Perplexity API
* Google Sheets

---

## Import Workflow

```text
Workflows
→ Import from File
```

Upload:

```text
Startup Company Research Agent.json
```

---

## Configure Credentials

Connect:

* OpenAI
* Perplexity
* Google Sheets

---

## Configure Google Sheet

Recommended columns:

```text
Company Name
Email
Employee Count
Decision Maker
Industry
Research Date
```

---

## Run Workflow

Enter startup name:

```text
OpenAI
Stripe
Notion
Cursor
Lovable
```

Workflow automatically:

1. Researches company
2. Extracts information
3. Structures results
4. Saves to Google Sheets

---

# Ideal Use Cases

* Lead Generation
* Sales Prospecting
* Startup Research
* Market Intelligence
* Investor Research
* Business Development

---

# Author

Kenneth Soriano

AI Automation Specialist | Business Analyst | Customer Success Professional

