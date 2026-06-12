# 👥 SignalGrowth — AI-Powered HR Recruitment Operating System

> A production-grade, memory-driven AI platform for managing the complete hiring lifecycle — from resume parsing to employee performance tracking — with a human-in-the-loop design that keeps final decisions with the operator.

**Live Platform:** [app.signalgrowth.in](https://app.signalgrowth.in) &nbsp;|&nbsp; **Company:** [signalgrowth.in](https://signalgrowth.in)

---

## 📽️ Demo Video

| Demo | Link |
|------|------|
| HR Agent — Full walkthrough | [Watch on YouTube](https://youtube.com/watch?v=EpdX-zrn6d4) |

---

## 🧠 What This System Does

Traditional HR systems are forms and spreadsheets. This is a **memory-driven AI HR operating system** where candidate evaluations, employee data, attendance patterns, and performance signals are stored, tracked, and surfaced intelligently — without the AI ever guessing or fabricating information.

Every output is grounded in **verified stored data only**. The AI provides decision support; humans make the final call.

---

## 🏗️ System Architecture

```
┌─────────────────────────────────────────────────────┐
│              HR DASHBOARD / CLIENT UI               │
└───────────────────────┬─────────────────────────────┘
                        │ REST API
┌───────────────────────▼─────────────────────────────┐
│                    API LAYER                        │
│              Node.js + Express.js                   │
└──────┬────────────────┬──────────────────┬──────────┘
       │                │                  │
┌──────▼──────┐ ┌───────▼───────┐ ┌────────▼─────────┐
│  RECRUITMENT│ │   EMPLOYEE    │ │    PERFORMANCE   │
│   MODULE    │ │   LIFECYCLE   │ │   INTELLIGENCE   │
│             │ │    MODULE     │ │      MODULE      │
│ Resume Parse│ │ Attendance    │ │ High performers  │
│ Candidate   │ │ Leave tracking│ │ Risk indicators  │
│ Matching    │ │ Activity log  │ │ Trend analysis   │
│ Talent Pool │ │ Payroll logic │ │ Recommendations  │
└──────┬──────┘ └───────┬───────┘ └────────┬─────────┘
       │                │                  │
┌──────▼────────────────▼──────────────────▼──────────┐
│                  AI DECISION LAYER                  │
│         OpenAI GPT-4o + Structured Context          │
│      Responses bound strictly to stored data        │
└───────────────────────┬─────────────────────────────┘
                        │
┌───────────────────────▼─────────────────────────────┐
│                  DATA STORAGE                       │
│   PostgreSQL — Candidates │ Employees │ HR Decisions│
│   Long-term memory: evaluation history, patterns    │
└─────────────────────────────────────────────────────┘
```

---

## ⚙️ Core Features

### Recruitment Module
- **Structured resume parsing** — unstructured candidate data converted into standardised, queryable profiles
- **Contextual candidate matching** — matches candidates to open roles based on stored evaluation criteria
- **Reusable talent memory** — past candidates stored with full evaluation history for future role matching and faster rehiring cycles
- Recruitment lifecycle tracking from application to offer

### Employee Lifecycle Management
- Daily work activity logging
- Attendance pattern tracking with anomaly detection
- Leave behaviour analysis (types, frequency, patterns)
- Full employee history from hire date

### Performance Intelligence
- Identifies **high performers, improving employees, and at-risk indicators** (low engagement, attendance drops)
- Data-backed performance trend analysis over configurable time windows
- Avoids subjective bias — every insight tied to logged data

### Payroll Logic Engine
- Calculates compensation based on attendance records
- Applies leave deductions per company policy
- Handles structured compensation rules and overrides

### Human-in-the-Loop Design
- AI provides **insights and recommendations**, never autonomous decisions
- Every hiring and HR decision remains with the operator
- Full audit trail of AI recommendations vs. human decisions

### Long-Term Memory System
- Complete candidate history preserved across hiring cycles
- Employee data and HR decisions stored for longitudinal analysis
- Enables pattern recognition across multiple hiring rounds

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend Runtime | Node.js |
| API Framework | Express.js |
| Database | PostgreSQL |
| AI Model | OpenAI GPT-4o |
| Orchestration | LangChain |
| Authentication | JWT + RBAC |
| Infrastructure | VPS, PM2, NGINX |

---

## 🔒 Architecture Advantage

- **Hallucination-free** — AI restricted to structured stored data, cannot fabricate candidate or employee information
- **Complete data ownership** — all candidate and employee data on private VPS, never on third-party servers
- **Multi-company ready** — designed for multi-role, multi-tenant scale with isolated data per organisation
- **LangGraph-ready** — architecture supports future multi-agent expansion for autonomous recruitment workflows

---

## 🚀 Part of the SignalGrowth Platform

This HR OS is one of four AI systems built on the SignalGrowth platform:

| System | Description |
|--------|-------------|
| [Sales OS](https://github.com/AliasgarRaj19/signalgrowth-sales-os) | AI-powered lead lifecycle and pipeline management |
| **HR Recruitment OS** | ← You are here |
| [SignalGrowth Platform](https://github.com/AliasgarRaj19/signalgrowth-platform) | Multi-tenant SaaS architecture overview |

---

## 👤 Built By

**Aliasgar Raj** — AI Systems Builder & Founder, SignalGrowth

- 🌐 [signalgrowth.in](https://signalgrowth.in)
- 💼 [linkedin.com/in/aliasgarraj](https://linkedin.com/in/aliasgarraj)
- 📧 askaliasgarnow@gmail.com

> *Available for consulting engagements, full-time roles, and custom AI system builds.*
