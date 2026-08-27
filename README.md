# Samanvita

### Seamless Coalescence via One-Click Deployment

Samanvita is a B2B corporate travel orchestration platform designed to bring fragmented travel coordination into one connected workflow.

It combines AI-powered travel research, structured policy and approval workflows, one-click travel decisions, and workflow visibility to reduce manual effort and time to travel while improving user convenience.

---

## The Problem

Corporate travel coordination is often fragmented across emails, spreadsheets, travel platforms, approval chains, and manual follow-ups.

As travel volume grows, Travel Desk and Operations teams must coordinate traveller preferences, budgets, company policies, approvals, bookings, and communication across disconnected systems.

Samanvita explores a simple product question:

> **Why can't I manage all of this in one place?**

---

## Product Proposition

Samanvita is built around three principles:

### 1. One-Click Travel Decisions
Approvers can take key travel actions directly through email, reducing unnecessary navigation and coordination.

### 2. AI-Powered, Human-Controlled
AI supports travel research and recommendation generation, while deterministic business rules and human decision-making retain control over approvals.

### 3. One Connected Travel Workflow
The travel journey is orchestrated from employee request through research, approval, workflow progression, and final communication.

---

## How Samanvita Works

**1. Employee Request**  
Employee submits a guided and structured corporate travel request.

**2. AI Research Agent**  
The AI Research Agent performs contextual travel research and generates personalised options.

**3. Policy & Approval Engine**  
Deterministic rules evaluate the request and determine the appropriate approval path.

**4. Email Sent to Approver**  
Travel options and recommendations are sent directly to the designated approver.

**5. One-Click Decision**  
The approver can **BOOK, APPROVE, or DEFER** directly from the email.

**6. Workflow Progresses**  
The system tracks state changes, triggers notifications, and maintains workflow visibility.

**7. Final Booking Details**  
Confirmed itinerary and booking information are communicated to the employee.

---

## Core Product Features

| Feature | Purpose |
| --- | --- |
| **AI Research Agent** | Contextual travel research and personalised recommendations |
| **One-Click Decisions** | Enables key travel decisions directly through email |
| **Policy-Based Approvals** | Deterministic rules and role-based approval routing |
| **Structured Travel Intake** | Standardises employee travel requests and required information |
| **Workflow State Tracking** | Maintains request, approval, and booking states across the journey |
| **Automated Notifications** | Communicates relevant workflow actions and outcomes |

---

## MVP Demo

The functional front-end prototype can be explored here:

**Samanvita MVP Demo Portal:**  
https://elm-funnel-52543742.figma.site

The prototype demonstrates the user-facing experience across the Samanvita travel workflow.

---

## Product Architecture

Samanvita separates the user experience, orchestration, intelligence, and data layers.

| Layer | Implementation |
| --- | --- |
| **Front End** | Figma Make |
| **Workflow Orchestration** | n8n |
| **AI Research** | Google Gemini 3.6 Flash |
| **Data Layer** | Google Sheets |
| **Communication** | Gmail |
| **Integration** | Webhooks |

The back end is built on **n8n** and currently hosted locally for the MVP.

---

## AI Guardrails

The AI Research Agent is designed around both business logic and traveller considerations.

Key guardrails include:

- Prioritising traveller safety over minor cost savings
- Prioritising women traveller safety through secure hotels, well-lit locations, and reliable transport
- Protecting traveller privacy
- Preferring direct flights and avoiding excessive or overnight layovers where possible
- Minimising late-night arrivals and impractical travel timings
- Avoiding impossible routes or unrealistic travel schedules

AI generates recommendations, but approval authority remains deterministic and human-controlled.

---

## MVP Scope

### Included

- Structured employee travel intake
- AI-powered travel research
- Travel recommendations
- Policy-based approval logic
- Role-based approval routing
- One-click email decisions
- Workflow state management
- Automated email notifications
- Prototype travel dashboards and portals

### Out of Scope

- Live booking execution
- Payment integrations
- Enterprise travel-provider integrations
- Group bookings above 10 travellers

The MVP validates the orchestration experience rather than functioning as a production booking engine.

---

## Product Metrics

### North Star Metric — Orchestration Success Rate
Percentage of travel workflows successfully completed from request to workflow completion.

### Approval Turnaround Time
Average time required to complete travel approval workflows.

### Recommendation Acceptance Rate
Percentage of AI-generated recommendations accepted without regeneration.

Together, these measure product effectiveness, operational efficiency, and AI recommendation quality.

---

## Target Users

Samanvita is designed primarily for enterprise teams involved in coordinating and governing business travel:

**Travel Desk · Operations · HR · Administration · Finance**

Initial target organisations include Indian SaaS, IT Services, Consulting, and Engineering companies with recurring corporate travel requirements.

---

## Product Positioning

> **Seamless coalescence via one-click deployment.**

Rather than treating travel research, policy evaluation, approvals, communication, and workflow management as isolated activities, Samanvita brings them together into a connected orchestration layer.

---

## Go-to-Market Approach

The proposed GTM journey follows a focused enterprise adoption model:

**Validate → Prove → Launch → Scale**

Initial engagement would combine LinkedIn outreach and industry events with scenario-based product demonstrations and process discovery.

Adoption begins with a controlled pilot — such as one department, travel purpose, or traveller group — followed by expansion after demonstrated value.

---

## Project Context

Samanvita was **designed and built by Aditi Moudgalya** as a capstone project for the **Product Management using Generative and Agentic AI** Executive Education programme at **BITSoM × Masai**.

The project covers the product journey from problem discovery and user research through product strategy, UX, AI workflow design, MVP development, orchestration, testing, and go-to-market thinking.

---

## Documentation

Additional portfolio material for Samanvita includes:

- Product Requirements Document (PRD)
- Product Pitch Deck
- Product Architecture
- User Research
- MVP Demo

These artefacts document the product thinking, implementation decisions, scope, and evolution of the MVP.

---

## Current Status

**MVP / Functional Prototype**

The current implementation is intended to demonstrate Samanvita's core product hypothesis:

**Corporate travel research, approvals, decisions, and workflow progression can be brought together through one connected experience with one-click deployment at its centre.**
