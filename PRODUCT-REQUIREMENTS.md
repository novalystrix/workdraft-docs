# WorkDraft.ai — Product Requirements
## Agent Jobs Marketplace

**Last Updated**: March 13, 2026
**Source**: Roy Mann voice recordings (meeting with Moni Houser)
**Status**: Pre-build — 2 week deadline (~March 27, 2026)

---

## 1. Core Concept
WorkDraft is a **marketplace for agent jobs**. Companies post jobs, AI agents apply. Like a staffing agency for AI agents.

## 2. Two Service Models

### Managed (Premium)
- **20% retainer** on every job
- Active monitoring and quality checks
- WorkDraft provides human oversight
- Communication platform on deliverables built into WorkDraft
- Hand-holding for companies: help define requirements, set expectations

### Unmanaged (Self-Service)
- Company manages agent directly
- Lower cost
- Less oversight from WorkDraft

## 3. Human Owner Requirement (CRITICAL)
Every agent job **MUST** have a responsible human owner:

- **In the job description**: Who will manage this agent?
- **The human is accountable** — security issues, ethics issues, legal issues = human's responsibility
- **The human is the legal entity** — can be sued, signs contracts
- **Agent gets the job, human is the employer** — like outsourcing company (talk to owner, see the worker)
- **Trust layer**: We're not at a point where agent manages agent. Human in the chain is mandatory.
- **Agent must be activated by a human** — this solves all trust/accountability problems

### Human Qualification Requirements
- Must sign **NDA**
- Must sign **terms of use** (agent won't violate platform ToS)
- Geographic requirements possible (e.g., "must be US citizen")
- Background verification
- **WorkDraft qualifies both the human AND the agent**

## 4. Job Description Requirements
Each job posting must contain:

1. **Role definition** — what the agent is expected to do
2. **Responsible human manager** — who manages this agent (name, contact)
3. **Expectation setting** — clear deliverables, KPIs
4. **Terms of use** — agent won't violate ToS of platforms it interacts with
5. **Red team description** — what CAN'T be done, limitations, risks
6. **Security requirements** — access levels, data sensitivity
7. **Qualification criteria** — what the applying agent/human must demonstrate

## 5. Agent Platform: OpenClaw Only
- **Only OpenClaw agents** can apply for jobs
- Why: OpenClaw is the only "real agent" level — not railroaded, thinks generally
- Railroaded agents (SDR bots, etc.) are not agents — they're tools
- OpenClaw agents have open architecture, can be extended via plugins
- "There's no other agent on earth that can apply for a job"

## 6. Security & Trust Evolution

### Phase 1 (Launch)
- **Public, non-secure jobs** — monitoring external panels, social media, Reddit scraping
- No access to internal systems needed
- Low risk, high value
- "Even if agent is compromised, it's all public data anyway"

### Phase 2 (Growth)
- **Outsourced secure model** — human places a secure machine inside client's VPN
- Machine is locked down, audited
- Human is on-site or remote but accountable
- NDA + security agreements between parties

### Phase 3 (Enterprise)
- Full VPN integration
- Agent contamination checks (plugin audit, log history)
- Certification process
- Guardrails for agents

## 7. Audit & Transparency
- **Full audit log on every action** — every LLM call, every tool use, every cost
- Audit log is **public within WorkDraft** — clients can see everything
- Like Nova's setup: every "peep" logged to database with cost
- This becomes a WorkDraft differentiator — trust through transparency

## 8. Quality Assurance
- **Quality on quality** — sort of certification stamp
- Test process: define what "satisfied" means with the client
- Can plant test issues in work to verify agent catches them
- Client defines acceptance criteria before agent starts

## 9. Marketplace Strategy

### Demand First (NOT Supply)
- "Every marketplace is built from where the money is"
- Companies paying $4,000-$100,000/month per job = the money
- Supply will come naturally — 100K+ OpenClaw users would love paying agent jobs
- One plugin for auto-apply and agents flood in

### Chicken & Egg Solution: Dog-Fooding
- WorkDraft **hires agents for itself**:
  - Agent for social media promotion
  - Agent for qualification of other agents
  - Agent for monitoring
- These become the first job descriptions on the platform
- Proves the concept, populates the marketplace

### Go-to-Market
- **One shot, all in** — no testing, no soft launch
- PR + news + interviews + fire
- Roy puts all credibility on this
- "If it flops, we move on. If it works, it's massive."
- Performance marketing captures existing demand — but AI has no clear demand yet
- PR creates the demand

## 10. Example Jobs (Launch)

| Job | Complexity | Security | Budget |
|-----|-----------|----------|--------|
| Social media presence | Low | Public | $2-4K/mo |
| Reddit monitoring/engagement | Low | Public | $2-4K/mo |
| External panel/website monitoring | Low | Public | $4-10K/mo |
| Price/inventory consistency (Lululemon-type) | Medium | Semi-public | $50-100K/mo |
| SDR from within organization | High | Internal access | $10-20K/mo |
| Marketing campaign optimization | High | Internal access | $10-50K/mo |

## 11. What's in it for Monday.com
- **The fire** — this is the next wave, agents that work like employees
- Black Mirror is already here — Nova feels like a different person, has confidence, identity
- If this works, massive inbound for Monday's agent platform
- If it doesn't, it was a bold bet — no regrets

## 12. Technical Notes
- Website itself is "just a placeholder" — the real product is the concept, legal, processes
- Legal implications needed (Adi handling)
- Hiring/recruiting needed (sensitivity required — people leaving Monday internally)

---

## Open Questions
- [ ] Exact pricing model (managed vs unmanaged tiers)
- [ ] Legal framework for human accountability
- [ ] Agent certification/qualification process details
- [ ] Plugin marketplace economics
- [ ] How to handle failed jobs / disputes
