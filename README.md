<div align="right">
 
![week 17](https://img.shields.io/github/actions/workflow/status/Kyle-Gortych-Kenzie-Group-Work-T3/week17/main.yml?label=main) ![week 17](https://img.shields.io/github/actions/workflow/status/Kyle-Gortych-Kenzie-Group-Work-T3/week17/original.yml?label=original)

</div>

# Week17

descript

## Changes
<details>
<summary>Diff with original branch</summary>

<details>
<summary>blank.java</summary>
 
```diff
blank
```
</details>

</details>

<div align="center">
 
### :hammer_and_wrench: Tools :

| Build System | Languages | Database | Cloud Service |
| ------------ | --------- | --------- | ------------- |
| <img src="https://img.shields.io/badge/Gradle-white?style=plastic&logo=gradle&logoColor=black" title="gradle" alt="gradle" height="30"/> | <img src="https://custom-icon-badges.demolab.com/badge/Java-white.svg?&sytle=plastic&logo=java" title="Java" alt="Java" height="30"/> | <img src="https://img.shields.io/badge/DynamoDB-white?style=plastic&logo=Amazon%20DynamoDB&logoColor=black" title="dynamodb" alt="dynamodb" height="30"/> | <img src="https://img.shields.io/badge/AWS-white?style=plastic&logo=amazon-aws&logoColor=black" title="AWS" alt="AWS" height="30"/> |
</div>
<br>

### AWS Deploy DynamoDB Tables

```console
aws cloudformation create-stack --stack-name groupwork-events --template-body file://GroupWork/KenzieEventPlanner/events_table.yaml --capabilities CAPABILITY_IAM &&
aws cloudformation create-stack --stack-name groupwork-invites --template-body file://GroupWork/KenzieEventPlanner/invites_table.yaml --capabilities CAPABILITY_IAM &&
aws cloudformation create-stack --stack-name groupwork-members --template-body file://GroupWork/KenzieEventPlanner/members_table.yaml --capabilities CAPABILITY_IAM
```

### Gradle Testing

```console
./gradlew groupwork-kenzieeventplanner-phase0 &&
./gradlew groupwork-kenzieeventplanner-phase2 &&
./gradlew groupwork-kenzieeventplanner-phase3 &&
./gradlew groupwork-kenzieeventplanner-phase4
```
<br>

<a href="your-gmail-link?">:mailbox:</a> How to reach the maintainer
