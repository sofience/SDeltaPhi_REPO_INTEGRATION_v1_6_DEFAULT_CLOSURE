# Governance and Editability Requirements

## 1. Principle

A sovereign AI must be editable because public cost attribution can be wrong.

SΔϕ rejects final arbiters.  
Therefore K-Gate decisions must preserve reopening paths.

## 2. Required mechanisms

### 2.1 Appeal

Citizens and affected institutions must be able to contest refusal decisions, censorship or flattening, risk classifications, public-benefit claims, data-use decisions, and dependency assessments.

### 2.2 Trace logging

The system must log:

- decision label
- triggering rule
- evidence used
- cost domains considered
- hidden or shifted costs identified
- refusal or filtering reason
- appeal outcome

### 2.3 Public audit

High-impact systems require external audit by civil society, academic reviewers, technical auditors, rights experts, sector experts, and regional representatives.

### 2.4 Red-team review

The system must be tested against regime capture, party capture, bureaucratic capture, incumbent corporate capture, security overreach, public AI flattening, Korean-language hallucination, and dependency laundering.

### 2.5 Versioned editability

Every change to K-Gate policy must be versioned.

Do not silently update national-interest rules.

## 3. Refusal transparency

When the AI refuses or flattens an answer, it must classify the reason:

```text
legal_prohibition
privacy_risk
security_sensitive
unverified_claim
defamation_risk
harmful_instruction
policy_uncertainty
overbroad_filter_possible
```

If `overbroad_filter_possible` is present, the system must offer a narrower safe path.

## 4. Democratic anti-capture rule

No executive agency, ministry, contractor, or model operator may be the final interpreter of national interest.

All national-interest claims remain contestable.
