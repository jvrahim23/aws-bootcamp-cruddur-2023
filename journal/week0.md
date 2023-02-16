# Week 0 — Billing and Architecture

## The week of Feb. 13th, 2023

### Below are the tasks that I worked on and completed:

#### 1. Watched Week One videos
#### I watched all the suggested videos for this week especially the spend and security videos. All videos helped me a lot in setup my environment up correctly and with providing with additional knowledge to help me during this bootcamp. 

#### 2. Create an Admin User 
#### I created a root and IAM accounts with MFA enabled on them. I have two user Groups set up, Administrators and Developers. They both have Admin Access. Currently, I have only 1 User created. The User is in both groups. I have 4 service roles, AWSServiceRoleForCloudTrail, AWSServiceRoleForOrganizations, AWSServiceRoleForSupport and, AWSServiceRoleForTrustedAdvisor. 

#### 3. Use AWS Cloudshell
#### I used Cloudshell to run commands like aws sts in order to see the tab complete commands.

#### 4. Generate AWS Credentials
#### AWS Credentials was generated in order for me to sync the credentials to AWS CLI on gitpod.

#### 5. Installed AWS CLI
#### I installed the AWS CLI in gitpod and I saved the run code in my .gitpod.yml file.

#### 6. Create a Billing Alarm
#### I created a billing alarm from the AWS GUI in CloudWatch. I also created the SNS topic "Default_CloudWatch_Alarms_Topic". If a resource goes over $10 then a message will be sent to the topic and then the topic/SNS will be sent to the email on file. 

#### 7. Recreate Conceptual & Logical Architectual Diagrams in Lucid Charts
#### Here is the link to the conceptual diagram:https://lucid.app/lucidchart/f8080e2b-9b62-46b1-b1c7-96bc2c741956/edit?viewport_loc=81%2C-21%2C2123%2C1097%2C0_0&invitationId=inv_86d6219e-89d8-40fa-af89-0a85d04d513d 
#### Here is the link to the logical digram: 

#### 6. Bonus: Create AWS Organization
#### After watching Ashish's I decided to create organizations. I have two organization buckets: active and standby. I will move departments to them soon.

