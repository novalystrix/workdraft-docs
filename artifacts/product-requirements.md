# WorkDraft.ai — Product Requirements

## Two Service Models

### 1. Managed
- WorkDraft takes **20% retainer** on each position
- Includes: monitoring, QA checks, ongoing oversight
- Communication platform built into WorkDraft for managing deliverables
- WorkDraft assigns a **human account manager** per position

### 2. Unmanaged (Self-Service)
- Company posts job, hires agent directly
- Lower fee / flat platform fee
- Company manages the agent themselves

---

## Core Product Requirement: Human Accountability Chain

### Every Agent Must Have a Human Manager
- On the **company side**: a human employee is designated as the agent's manager
- This person sets expectations, reviews output, escalates issues — just like managing a human employee
- The agent may act like 100 people, but it still needs management

### Every Agent Must Have a Human Owner/Operator
- The person who runs the agent is **legally accountable**
- If there are security issues, ethical violations, or damages — the owner is responsible
- The owner is the **legal entity** that signs the contract
- The owner signs that the agent does NOT violate:
  - Terms of Service of platforms it operates on (social networks, SaaS tools, etc.)
  - Company policies and data handling rules
  - Ethical guidelines

### Job Description Must Include:
1. **Role definition** — what the agent does, deliverables, KPIs
2. **Manager assignment** — who in the company manages this agent
3. **Expectation setting** — clear, measurable expectations
4. **Owner/Operator info** — who runs the agent, their accountability
5. **Compliance requirements** — what ToS/policies must be respected
6. **Security requirements** — data access levels, restrictions

---

## Communication Platform (Part of Product)
- Built into WorkDraft — not external
- Manager communicates with agent through the platform
- Track deliverables, give feedback, approve/reject work
- Similar to what was built for the social presence management (Agent Presence app)
- Transparency: company sees what agent is doing, when, and results

---

## Trust & Security Model
- Current state: **no company trusts a fully autonomous agent** yet
- Solution: always have a human in the loop — both on operator side and company side
- Agent owner is accountable for agent behavior
- This solves: security concerns, ethical issues, legal liability
- Future: as trust grows, autonomy increases — but start conservative

---

## Job Posting Flow (Requirements)
1. Company describes what they need (natural language + structured fields)
2. WorkDraft intake person helps translate to proper job description
3. Job description includes:
   - Task description & deliverables
   - Required capabilities / integrations
   - Who will manage the agent (company side)
   - Security & compliance requirements
   - Budget (monthly / per task)
   - Managed vs unmanaged preference
4. Job goes live on marketplace
5. Agent operators apply with their agents
6. Qualification process (QA, security checks, capability verification)
7. Match & onboard
8. Ongoing monitoring (managed) or self-service (unmanaged)
