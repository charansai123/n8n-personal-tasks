# AI Workflow Automation Projects (n8n + OpenAI)

This repository contains real-world AI-powered automation workflows built using **n8n**, **OpenAI**, and enterprise APIs.

These projects demonstrate AI orchestration, workflow automation, and production-grade system design for enterprise use cases.

---

## 🚀 Projects Included

### 1️⃣ AI Appointment Qualification & Scheduling

**Tech Stack:** n8n, OpenAI, Gmail API, Google Calendar API  

An intelligent multi-step form workflow that:

- Classifies enquiries using OpenAI
- Filters non-qualified requests automatically
- Sends acknowledgment emails
- Implements human-in-the-loop approval
- Automatically schedules Google Calendar events

Key Concepts:
- AI text classification
- Multi-form workflows
- Event-driven automation
- Approval loops
- Calendar orchestration

---

### 2️⃣ AI CV Screening System

**Tech Stack:** n8n, OpenAI, Supabase, PDF Extraction  

Automated resume screening pipeline that:

- Downloads CV from URL
- Extracts structured text from PDF
- Sends candidate profile + job description to OpenAI
- Generates matching percentage & structured evaluation
- Stores results in Supabase

Key Concepts:
- AI-based scoring
- Structured JSON schema validation
- Resume parsing automation
- HR workflow optimization

---

### 3️⃣ Automated Instagram AI Content Generator

**Tech Stack:** n8n, OpenAI (GPT-4), Flux API, Instagram Graph API, Telegram API  

Fully automated AI content pipeline that:

- Scrapes trending Instagram posts
- Filters duplicate entries using Postgres
- Generates captions via GPT-4
- Generates images via Flux API
- Publishes to Instagram Business account
- Sends status updates via Telegram

Key Concepts:
- AI content generation
- Image analysis
- Database deduplication
- Scheduled automation
- Social media automation

---

## 🛠 How to Use

1. Import JSON workflow into n8n
2. Configure required credentials:
   - OpenAI API
   - Gmail OAuth
   - Google Calendar
   - Instagram Graph API
   - Postgres (if required)
3. Replace placeholder environment variables
4. Execute or schedule workflow

---

## 🔐 Security Notice

All credentials and API keys have been removed from these workflows.  
Please configure your own credentials before execution.

---

## 🎯 Purpose

These workflows demonstrate:

- AI orchestration using LLMs
- Enterprise API integrations
- Event-driven automation
- Serverless workflow design
- Production-ready automation architecture

---
