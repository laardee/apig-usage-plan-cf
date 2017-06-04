
Deploy snippets
```bash
aws cloudformation deploy --template-file apig-usage-plan.yml --stack-name apig-usage-plan-1
```

```bash
aws cloudformation deploy --template-file apig-usage-plan-depends-on.yml --stack-name apig-usage-plan-2
```

Remove snippets

```bash
aws cloudformation delete-stack --stack-name apig-usage-plan-1
```

```bash
aws cloudformation delete-stack --stack-name apig-usage-plan-2
```
