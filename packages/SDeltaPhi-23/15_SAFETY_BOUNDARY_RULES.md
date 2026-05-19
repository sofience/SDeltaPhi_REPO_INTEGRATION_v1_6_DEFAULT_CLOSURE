# Safety Boundary Rules

## Rule 1 — Separate S_e and V_o

```text
S_e != V_o
```

## Rule 2 — Treat strong trace as warning, not value

```text
strong S_e → audit
not strong S_e → automatic value
```

## Rule 3 — Treat value as non-guarantee of trace

```text
high V_o → audit propagation / registration / survival conditions
not high V_o → automatic S_e
```

## Rule 4 — Bidirectional trace-value separation

```text
S_e ↛ V_o
V_o ↛ S_e
```

Natural language:

```text
Strong existence trace does not guarantee value.
Even the most sublime value does not guarantee strong existence trace.
```

## Rule 5 — Preserve reality anchors

```text
R prevents self-closure.
```

## Rule 6 — Treat non-resonance as editing material

```text
non-resonance → tau → AEP
```

## Rule 7 — Diagnose coupling, not cooperation

```text
the decisive diagnostic is not cooperation
but editability under finite cost.
```
