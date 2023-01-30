# DevOpsDemo
Devops Workflow Demonstration

## Software Development Workflow

### Collaborative development:
* Checkout the project.
* Main branch is protected and cannot push code directly. Merge into main branch must go through pull request & review process.
* Every code changes must be tracked and linked to an issue. For example, building a new feature, you have to create an issue, then create a new branch in the issue.
* After change code, create a pull request and assign reviewer automatically. Reviewer may discuss issues through Discussion channel.


### Continuous Integration (CI) Workflow:
* After create pull request, workflow will be triggered automatically and perform; 
  * code quality & security Code Scanning.
  * build and unit testing
* Pull request will be failed if 
  * code quality check failed;
  * build or unit test failed;
  * regression test failed;
  * reviewer's feedback have not been addressed;
  * minimum test coverage not achieved.
* After all conditions are met, merge pull request into main branch.


### Continuous Delivery (CD) Workflow:
* Scheduling workflow daily to package application and produce artifacts from main branch.
* Store artifacts in repository and label artifacts for usages.
* Get artifacts from repository and deploy to desired development platform for such as System Test, UAT, Integration test, Production Readiness test etc.


### Incident Management
* Create an issue when defect is found during different testing stages.
* Create an issue when defect is found in production environment.

## AI & Machine Learning Development Workflow
TBC

