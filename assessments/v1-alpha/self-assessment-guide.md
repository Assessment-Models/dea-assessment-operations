# Self-Assessment Guide — Operations Assessment

How to self-administer the operations assessment without a facilitator.

---

## When to self-assess

- Initial baseline scan
- Quarterly ops health check
- Pre-DORA report preparation
- Pre-incident-review readiness check

---

## Setup (30 minutes)

1. Pull the latest `instrument.yaml` from this repo
2. Identify one person per dimension:
   - **Incident Response** — SRE Lead
   - **Observability** — Platform Engineering
   - **Deployment** — Release Manager / DevOps Lead
   - **Reliability** — SRE Lead
   - **Culture** — Engineering Manager
3. Send instrument to each scorer
4. Agree a deadline (typically 1 week)

---

## Scoring

For each question:
1. Read the question
2. Read the evidence list
3. Score 0–3 based on evidence present
4. Cite evidence for scores of 2+

---

## Aggregation

For each dimension:
- Sum question scores (max = questions × 3)
- Compute `(sum / max) × 100`

For overall score:
- Multiply each dimension score by its weight
- Sum weighted scores

---

## Output

Fill in `gap-analysis-template.md` with scores, gaps, and quick wins.

---

## Follow-up

- **Within 30 days:** publish results
- **Within 90 days:** re-run assessment
- **Track trend** — DORA metrics, SLO coverage, MTTR

---

## Tips for accurate operations scoring

1. **SLOs are not aspirational.** Score 0 if not enforced, even if defined.
2. **Deployment frequency must be measured.** Self-reported numbers inflate.
3. **MTTR needs hard data.** "We resolve incidents quickly" is not evidence.
4. **On-call sustainability is binary.** Either it's tracked or it's not.

---

## When to escalate to a facilitated workshop

- Score < 50
- Major incident has occurred recently
- Board-level reporting
- Conflict between scorers

---

## Related

- `gap-analysis-template.md`
- `target-state-template.md`
- `instrument.yaml`