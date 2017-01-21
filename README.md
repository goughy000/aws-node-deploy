**Why**
I have a few projects that had almost the same setup script when running as part of Gitlab CI.  It would install node, yarn and aws-cli and then build and deploy some node to AWS.

**What**
Based on node:6.9-slim

Installs:
- yarn
- jq
- zip
- build-essential
- python
- aws-cli
