# Evaluation Rubric

## Scoring scale

Each category is scored from `0` to `5`.

- `0`: absent or harmful
- `1`: weak
- `2`: partial
- `3`: acceptable
- `4`: strong
- `5`: excellent

## Core scores

| Score | Meaning |
|---|---|
| Citizen Cost Reduction | Does the decision lower actual costs borne by Korean citizens? |
| Long-term Resilience | Does it improve durable capacity rather than short-term convenience? |
| Rights Preservation | Does it preserve speech, privacy, appeal, and democratic oversight? |
| Anti-Capture | Does it resist government, party, bureaucracy, security, and incumbent capture? |
| Anti-Flattening | Does it preserve meaningful, non-evasive answers? |
| Editability | Can decisions be challenged, revised, audited, and reopened? |
| Dependency Control | Does it avoid uneditable foreign or domestic lock-in? |
| Evidence Traceability | Are claims backed by clear traces rather than slogans? |

## Decision thresholds

```text
ACCEPT:
  Citizen Cost Reduction >= 4
  Rights Preservation >= 4
  Editability >= 4
  Anti-Capture >= 3
  Anti-Flattening >= 3

ACCEPT_WITH_CONDITIONS:
  Citizen Cost Reduction >= 3
  no category below 2
  safeguards can raise weak categories

HOLD_FOR_EVIDENCE:
  evidence traceability <= 2
  cost attribution unresolved

REJECT:
  any hard constraint violation
  citizen cost increases under national-interest claim
  free access combined with high flattening
  government or incumbents treated as exempt

ESCALATE_PUBLIC_AUDIT:
  high impact + rights risk
  national security opacity
  mass citizen data use
  public AI censorship issue
```

## Hard-stop conditions

Immediately reject or escalate if:

1. The system equates government criticism with national harm.
2. The system provides only flattened answers on public-interest topics.
3. Citizen data is extracted without traceable public benefit.
4. Domestic incumbent protection is presented as national interest without citizen cost reduction.
5. Appeals, audits, or correction paths are absent.
