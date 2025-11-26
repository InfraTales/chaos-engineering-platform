# Cost Analysis (₹)

This document provides cost estimates for the **Chaos Engineering Platform** in **Indian Rupees (₹)**.

## Production Environment

| Service | Monthly Cost (₹) | Notes |
|---------|------------------|-------|
| **AWS FIS** | ₹5,000–15,000 | Fault Injection Simulator |
| **Lambda (experiments)** | ₹3,000–8,000 | Chaos orchestration |
| **Step Functions** | ₹2,000–5,000 | Experiment workflows |
| **CloudWatch** | ₹5,000–10,000 | Monitoring & dashboards |
| **SNS/EventBridge** | ₹1,000–3,000 | Alerting |
| **S3 (reports)** | ₹1,000–2,000 | Experiment results |
| **Total** | **₹17,000–43,000** | ~$210–540/month |

## Cost Optimization

- **Schedule experiments** – Run during off-peak hours
- **Target scope** – Limit blast radius to reduce monitoring costs
- **Reuse templates** – Avoid recreating experiment configurations

## Related Documentation

See `ARCHITECTURE.md` for details and `DEPLOYMENT.md` for setup.
