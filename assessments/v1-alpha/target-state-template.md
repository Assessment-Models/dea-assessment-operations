# Target State Design Template — Operations Assessment

Use after gap analysis to define the desired future state for the **operations** domain.

---

## Current State

- **Maturity band:** <from gap analysis>
- **Top 3 gaps:** <from gap analysis>
- **Key risks:** <incidents, outages, on-call burnout, deployment failures>

---

## Target State (12 months)

### Vision statement

<one paragraph — e.g., "All production services have SLOs, deployment is > 10/day with < 15% change failure rate, MTTR for sev-1 is < 30 min, chaos engineering is practiced quarterly">

### Maturity goal

- **Target band:** <Managed | Quantitatively Managed | Optimising>
- **Target score:** __ / 100
- **By when:** YYYY-MM-DD

### Outcomes (measurable)

1. <outcome + metric>
2. <outcome + metric>
3. <outcome + metric>

---

## Roadmap

### Quarter 1 (months 1–3) — Foundation

| Initiative | Owner | Metric | Done when |
|------------|-------|--------|-----------|
| Document incident process | | | |
| Centralise logs/metrics | | | |
| Define first 5 SLOs | | | |

### Quarter 2 (months 4–6) — Standardisation

| Initiative | Owner | Metric | Done when |
|------------|-------|--------|-----------|
| SLO coverage > 50% | | | |
| Deployment automation > 80% | | | |
| Post-mortem process enforced | | | |

### Quarter 3 (months 7–9) — Reliability

| Initiative | Owner | Metric | Done when |
|------------|-------|--------|-----------|
| First game day | | | |
| Error budget policy | | | |
| Auto-remediation library started | | | |

### Quarter 4 (months 10–12) — Culture

| Initiative | Owner | Metric | Done when |
|------------|-------|--------|-----------|
| Shared dev/ops on-call | | | |
| Blameless culture charter | | | |
| Quarterly ops health report | | | |

---

## Investment

- **People:** <SRE team, on-call rotations>
- **Budget:** <observability stack, chaos tools>
- **Tooling:** <tracing, feature flags, deployment automation>
- **Training:** <SRE training, incident command training>

---

## Dependencies

- Engineering leadership buy-in
- Service team capacity for SLO definition
- Vendor or platform tooling procurement

---

## Risks

| Risk | Likelihood | Impact | Mitigation |
|------|-----------|--------|------------|
| Sev-1 incident during rollout | M | H | Progressive SLO rollout |
| On-call burnout | M | H | Rotation health monitoring |
| SLOs become vanity | M | M | Link SLOs to release decisions |
| Tooling lock-in | L | M | Open standards preferred |

---

## Sign-off

- **Domain owner:** ____________________ Date: __________
- **Sponsor:** ____________________ Date: __________
- **Architecture review board:** ____________________ Date: __________