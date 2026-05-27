# Event Detection System

## Event Sources

- Track123
- Shopify
- Courier APIs
- OMS
- Warehouse systems

---

## Event Workflow

```text
Courier Update
      ↓
Track123 Receives Event
      ↓
SLA Validation
      ↓
Slack Alert Trigger
      ↓
Team Assignment
```

---

## Example Events

| Event | Meaning |
|---|---|
| shipment_delayed | Delivery issue |
| pickup_pending | Courier delay |
| rto_risk | Return risk |
| delivery_failed | Failed delivery |
