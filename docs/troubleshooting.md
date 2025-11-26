# Troubleshooting

## Common Issues

### Experiment Fails to Start
- Check IAM permissions for FIS
- Verify target resources exist and are tagged
- Review experiment template syntax

### Stop Condition Triggered Early
- Review CloudWatch alarm thresholds
- Check baseline metrics
- Adjust sensitivity settings

### Rollback Not Working
- Verify rollback actions are configured
- Check IAM permissions for recovery
- Review Step Functions execution

### Blast Radius Too Large
- Add resource filters
- Use tag-based targeting
- Reduce percentage of targets
