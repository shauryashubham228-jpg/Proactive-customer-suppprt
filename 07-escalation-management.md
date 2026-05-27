# Escalation Management

## Escalation Logic

```text
IF delay > SLA
AND VIP customer
THEN escalate immediately
```

---

## Escalation Levels

| Level | Scenario |
|---|---|
| L1 | Minor delay |
| L2 | SLA breach |
| L3 | VIP issue |
| L4 | Social escalation |

---

## Acceptance Criteria

- fast escalation
- correct routing
- SLA compliance
