Splunk CI/CD
---
This is a simple repository intended to prototype a CI/CD process for Splunk application deployment using Jenkins and Ansible. The repo contains a simple ansible playbook which deploys the app using a simple file copy task and also contains the jenkinsfile which defines the pipeline stages (Clone, Lint, Appinspect, Deploy).


Contents
---
* deployment	`contains basic ansible playbook`
* test-app `sample splunk app for deployment`
* jenkinsfile	`the jenkins pipeline`
