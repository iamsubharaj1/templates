# Customer Ops Templates
**Copy-ready templates to run onboarding, adoption, renewals, and escalations as stable operating loops.**

This folder is a template library for Customer Ops teams that want execution to be:
- **repeatable** (same format every week)
- **signal-driven** (thresholds trigger actions)
- **owned** (clear RACI and next steps)
- **auditable** (decisions and follow-ups are recorded)

---

## Table of contents
1. Purpose
2. What’s included
3. Template contract (quality bar)
4. Operating loops covered
5. Standard sections used in every template
6. Recommended build order (what to create first)
7. File map (template inventory)
8. Usage patterns (how to run weekly)
9. Sanitization rules (public repo safety)
10. Contribution rules (so this stays clean)

---

## 1) Purpose
Customer Ops usually fails for one of three reasons:
- execution depends on memory and individual heroics
- risk is detected late because signals are vague
- reviews create updates but no decisions

These templates solve that by enforcing a consistent execution spine:
**Outcome → Owner → Signals → Routine → Actions → Closure**

---

## 2) What’s included
This folder will contain templates for:

### A) Onboarding (time-to-value)
- milestones, gates, handoffs, and launch readiness
- risk flags during early life cycle
- stakeholder map and success criteria

### B) Adoption (habit formation)
- leading indicators, thresholds, intervention plays
- usage review routine and action register
- value proof capture (so renewals are earned)

### C) Renewals and expansion (revenue discipline)
- renewal readiness timeline (T-90 to renewal)
- risk register, save motion tracker, forecast hygiene
- expansion triggers and commercial next plays

### D) Escalations (controlled incident handling)
- severity model and response expectations
- stakeholder updates and internal coordination format
- closure and prevention loops

---

## 3) Template contract (quality bar)
A file counts as a “template” only if it meets all of these:

### Must have
- **Outcome** (definition of done)
- **Owner + RACI** (who drives, who approves)
- **Signals with thresholds** (not adjectives)
- **Routine** (frequency, checkpoints)
- **Action section** (next steps with due dates)
- **Closure** (what prevents recurrence)

### Must NOT have
- tool-specific dependencies (Notion-only, Salesforce-only)
- vague signals like “low usage” or “customer unhappy”
- long narrative without runnable structure

### Design target
- setup time: **≤ 15 minutes**
- weekly usage: **≤ 20 minutes**
- output: **clear decisions and actions**

---

## 4) Operating loops covered
Every Customer Ops activity here maps to one of these loops:

- **Onboarding loop:** Plan → Launch → Verify value → Stabilize
- **Adoption loop:** Detect drift → Intervene → Confirm recovery → Prevent repeat
- **Renewal loop:** Readiness → Risks → Save plays → Commit forecast → Close
- **Escalation loop:** Contain → Communicate → Resolve → Harden system

---

## 5) Standard sections used in every template
To keep everything consistent, templates in this folder use these sections in this order:

1. **Outcome**
2. **Scope**
3. **Owner + RACI**
4. **Signals and thresholds**
5. **Routine and checkpoints**
6. **Actions and interventions**
7. **Artifacts produced** (docs, trackers, comms)
8. **Closure and hardening**
9. **Notes** (optional)

This consistency is the feature.

---

## 6) Recommended build order
If you create only the minimum set first, create in this order:

1. **Health Signals Template**  
   Without leading indicators, everything becomes reactive.

2. **Risk Register**  
   Centralize risks with owners and due dates.

3. **Renewal Readiness Tracker**  
   Turns renewal execution into a timeline discipline.

4. **Account Plan Template**  
   Forces outcomes, stakeholder map, risks, and next plays.

5. **QBR Template (exec-ready)**  
   Converts reviews into decisions, not decks.

6. **Escalation Update Template**  
   Stabilizes comms during incidents.

---

## 7) File map (template inventory)
Create these as individual Markdown files in this folder:

### Onboarding
- `Onboarding-Success-Plan.md`
- `Onboarding-Milestones-and-Gates.md`
- `Onboarding-Risk-Checklist.md`

### Adoption
- `Health-Signals-Template.md`
- `Adoption-Weekly-Review.md`
- `Adoption-Intervention-Playbook.md`

### Renewals and expansion
- `Renewal-Readiness-Tracker.md`
- `Renewal-Risk-Register.md`
- `Save-Motion-Tracker.md`
- `Expansion-Triggers.md`

### Account execution
- `Account-Plan-Template.md`
- `QBR-Template.md`
- `Stakeholder-Map.md`

### Escalations
- `Escalation-Update-Template.md`
- `Incident-Bridge-Notes.md`
- `Postmortem-Template.md`

---

## 8) Usage patterns (how to run weekly)
These templates are designed to be used in simple weekly rituals:

- **Weekly Customer Ops Review (30–45 mins)**  
  Inputs: Health Signals + Risk Register  
  Outputs: Top risks, owners, actions, follow-ups

- **Renewal Readiness Review (weekly for renewal cohort)**  
  Inputs: Renewal Readiness Tracker + Save Motion Tracker  
  Outputs: forecast call, save plan, exec escalations

- **Escalation Bridge (as needed)**  
  Inputs: Escalation Update Template  
  Outputs: controlled comms, next update time, owner clarity

---

## 9) Sanitization rules (public repo safety)
Before committing:
- remove emails, phone numbers, customer names, internal URLs, IDs
- replace with placeholders:
  - `{{CUSTOMER_NAME}}`, `{{ACCOUNT_ID}}`, `{{CSM_NAME}}`, `{{INTEGRATION}}`

No exceptions.

---

## 10) Contribution rules (keep it clean)
- One template per file.
- Keep sections in the standard order.
- Use checklists and tables where possible.
- Prefer thresholds and examples over narrative.
- If a template depends on a tool, put tool-specific notes in a short “Tool notes” section at the bottom.

---

## Start here (if you want the strongest first commit)
Create these two files first:
- `Health-Signals-Template.md`
- `Renewal-Readiness-Tracker.md`

They make the folder immediately useful and signal real operational depth.
