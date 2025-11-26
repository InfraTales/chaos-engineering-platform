# Security Overview

Security posture of the **Chaos Engineering Platform**.

## Access Controls

- **IAM roles**: Least-privilege for FIS experiments
- **Blast radius**: Configurable scope limits
- **Approval workflows**: Required for production experiments
- **Audit logging**: All experiments logged to CloudTrail

## Safety Mechanisms

- **Stop conditions**: Automatic rollback on thresholds
- **Time limits**: Maximum experiment duration
- **Resource tagging**: Only tagged resources affected
- **Rollback procedures**: Automated recovery

## Compliance

Supports SOC 2 and internal audit requirements.

> See `SECURITY.md` in project root for details.
