# Facilitator Guide — Operations Assessment

How to run a facilitated workshop for the operations domain.

---

## Pre-workshop (1 week before)

- [ ] Confirm participants (8–15 people: SRE, ops, dev leads, on-call engineers, sponsor)
- [ ] Send pre-read: link to `instrument.yaml` and 5 dimensions
- [ ] Confirm room (physical or virtual) and tools
- [ ] Send calendar invite
- [ ] Prepare score sheets (5 dimensions)

---

## Agenda (3.5 hours)

| Time | Activity | Lead |
|------|----------|------|
| 0:00 | Welcome, agenda | Facilitator |
| 0:15 | Dimension 1 — Incident Response (45 min) | SRE Lead |
| 1:00 | Dimension 2 — Observability (40 min) | Platform Engineering |
| 1:40 | Comfort break | |
| 1:55 | Dimension 3 — Deployment (45 min) | Release Manager |
| 2:40 | Dimension 4 — Reliability (40 min) | SRE Lead |
| 3:20 | Dimension 5 — Culture (30 min) | Engineering Manager |
| 3:50 | Cross-cut + actions (30 min) | All |
| 4:20 | Wrap-up | Facilitator |

---

## Per-dimension script

Same 5-step process as other assessments:

1. **Context (3 min)** — explain why this dimension matters
2. **Read questions (5–10 min)** — walk through, allow clarifying questions
3. **Individual scoring (5–10 min)** — private scoring on score sheets
4. **Surface disagreements (10–15 min)** — facilitator drives convergence
5. **Lock scores (5 min)** — sum, compute percentage, mark band

---

## Cross-cut discussion (30 min)

- Where does the incident process exist but not followed?
- Are SLOs defined but not enforced?
- Is deployment fast but risky?
- Are teams on-call but not learning from incidents?

---

## Post-workshop

Within 5 working days: fill in gap-analysis-template.md and target-state-template.md, publish to sponsor.

---

## Common challenges in operations assessments

- **SLO denial.** "We don't need SLOs." Counter: tie to customer outcomes.
- **Deployment frequency inflation.** Reporting numbers that don't match reality. Counter: ask for evidence from CI.
- **Blameless culture resistance.** Counter: share successful examples from peer orgs.
- **On-call satisfaction taboo.** "We don't survey." Counter: cite attrition correlation.

---

## Facilitator certification

Internal training: contact `assessments@technehub.com`.