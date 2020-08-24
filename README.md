# Setup AWS CLI

This action install aws-cli using python

## Example usage

```yaml
jobs:
  your_job:
    runs_on: ubuntu-latest
    steps:
      - name: Checkout
        use: action/checkout@v2
      - name: Install aws cli
        use: isbang/setup-awscli@v0.1.0
```
