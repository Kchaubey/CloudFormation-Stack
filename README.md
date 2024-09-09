# CloudFormation-Stack
Creating AWS EC2 using CFL template

Below are the steps to follow:
- Create any job freestyle or pipeline
- install the plugin for cloud formation to integrate with Jenkins
- select SCM as git
- Choose build environment as Cloud formation
- Give the required details along with AWS access and a secret Key to connect the AWS account
- automate te process using different build triggers like Poll scm, Github trigger, and webhook.
- apply and save then click on build now.
- If changing anything on the Github repo file it will automatically start the job

