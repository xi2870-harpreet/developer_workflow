---
slug: aws-ec2-create
id: ptfz0retmcz2
type: challenge
title: Create an AWS EC2 instance
teaser: Every cloud starts from VM
notes:
- type: text
  contents: |-
    You're about to create an EC2 instance using AWS CLI.

    Please wait while we provision the AWS account.
tabs:
- id: m3tulxhxdjot
  title: Cloud CLI
  type: terminal
  hostname: cloud-client
- id: 9ulhgngut1or
  title: AWS Console
  type: service
  hostname: cloud-client
  path: /
  port: 80
difficulty: basic
timelimit: 600
enhanced_loading: null
---
# AWS123

👋 Introduction
===============

Use the terminal to create EC2 instance1:

```
aws ec2 run-instances --image-id ami-01685d240b8fbbfeb --instance-type t2.nano
```

To complete this challenge, press **Check**.
