# Week 0 — Billing and Architecture

## Required Homework

### Install And Verify AWS CLI 
 
I used my local environment on windows because I was unable to use Gitpod or Github codespaces due to browser issues.

I followed the following instructions for the configuration of my local machine on windows.

I did the following steps to install my AWS CLI.

I installed the AWS CLI for windows 10 via command in **Command Prompt**:

I followed the instructions on the [AWS CLI Install Documentation Page](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)


![Installing AWS CLI](assets/wk0-proof-of-aws-cli-installation.png)

```
msiexec.exe /i https://awscli.amazonaws.com/AWSCLIV2.msi
```

I attempted to run the command by typing in 'aws' but got an error which by my closing and reopening the command prompt later worked.

![Proof of Working AWS CLI](assets/wk0-proof-of-aws-cli.png)

### Create a Budget

I created a zero spend budget and a credit spend budget.
I created both for $1 because I cannot afford any kind of spend.

![Image of the Budget Alarm](assets/budget-alarm.png)

### Recreate Logical Architectural Diagram

![cruddur logical design](assets/logical-recreation-architecture-diagram.png)




