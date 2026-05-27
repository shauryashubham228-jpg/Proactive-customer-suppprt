# Track123 Monitoring Layer

## Purpose

Track123 acts as:
- shipment visibility layer
- courier monitoring system
- proactive alert engine

---

## Technical Understanding

### APIs Used

- shipment tracking APIs
- webhook events
- courier synchronization APIs

---

## SLA Workflow

```text
Shipment Status
      ↓
Compare With SLA
      ↓
Threshold Breach
      ↓
Trigger Alert
```

---

## SLA Examples

| Shipment Type | SLA |
|---|---|
| Metro | 3 days |
| Tier 2 | 5 days |
| International | 10 days |
