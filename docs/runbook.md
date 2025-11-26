# Runbook

## Deployment

```bash
npm install && cdk deploy --context environment=prod
```

## Running Experiments

```bash
# Start chaos experiment
aws fis start-experiment --experiment-template-id EXT123

# Monitor experiment
aws fis get-experiment --id EXP456
```

## Game Day Checklist

1. Notify stakeholders
2. Verify monitoring is active
3. Confirm rollback procedures
4. Execute experiment
5. Document findings

## Maintenance

- Review experiment results weekly
- Update templates quarterly
- Test rollback procedures monthly
