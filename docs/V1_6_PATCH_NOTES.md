# v1.6 Patch Notes — Default Closure Governance Spine

This patch aligns the repository root with the v1.6 integration metadata.

## Why this patch exists

The repository already contains v1.6 default-closure files, but the root README, entrypoint, manifest, and llms.txt still present a v1.5 event/authority/fixation posture. This creates a mismatch for AI ingestion: the repository appears to be v1.5 at the entrypoint while v1.6 files exist deeper in the tree.

This patch makes v1.6 the root-level route.

## Main correction

Before:

```text
v1.5 event / authority / fixation route was the front-facing route.
```

After:

```text
v1.6 default closure governance route is the front-facing route.
```

## Practical effect

The repository now answers a longer chain:

```text
Has closure occurred?
Has a low-cost path become default power?
Is the default governable?
Is it operationally editable?
Can a closed default be reopened?
Is intervention legitimate?
Would the intervention create a replacement closure?
```

## Non-deletion principle

Do not hard-delete package archives, DOI maps, provenance records, or historical changelogs unless storage constraints require it. Prefer `docs/legacy/` for older patch-layer files.
