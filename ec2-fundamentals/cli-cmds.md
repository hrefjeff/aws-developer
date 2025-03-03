# Common EC2 cli commands

```bash
# List all instances
aws ec2 describe-instances --query "Reservations[*].Instances[*].[Tags[?Key=='Name'].Value|[0], InstanceId]" --output table
```
