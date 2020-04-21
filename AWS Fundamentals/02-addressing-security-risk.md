# Course 2: Addressing Security Risks

## AWS Organizations
- Automate account creation and management
- Create groups of accounts to reflect business needs
- Govern access to AWS services resources region by policies
- Set up single payment method for all AWS accounts with solidated billing
- Share resources across accounts

Creating new organizations
- Plan ahead for the structure of organization
- Keep the master account free of any operational AWS resources
- Use AWS CloudTrail
- Apply Least Privilege practice 
- Assign policies to Organization Units
- Test new and modified policies
- Use the APIs and AWS CloudFormation

## Services
- IAM
  - Manage users, groups and permission to resources
  - Policies
    - AWS managed policy
    - Customer managed policy
    - Inline policy
- AWS Single Sign-On (SSO)
  - Centrally manage access permissions to AWS accounts
  - Create users in AWS SSO or connect to Microsoft AD DS or Azure AD to identity system
  - Access accounts and applications from one place
- Amazon Cognito
  - user sign-up
  - sign-in
  - access control
  - support social identity providers like Facebook, Google etc
- AWS Directory Service

## Network
- VPC: Virutal Private Cloud
- Route tables
  - routes determine where network traffic is directed
- AWS Direct Connect
  - establish private connectivity between AWS and other network enviroments directly

## Auditing
- Detective Control
- CloudTrail
- AWS Config
- Amazon Inspector
- Amazon Macie
- Trust Advisor
- Amazon GuardDuty
- Security Hub

## Data types

- object
  - Amazon Simple Storage Service (S3)
- Database
  - Amazon RDS
  - Amazon Timestream
  - Quantum Ledger Database
  - Neptune
- EC2 data
  - Amazon Elastic Block Store
  - Amazon Elastic File System
- Data warehouse
  - Amazon Redshift
  - Amazon Athena
- Data transfer
  - AWS Snowball
  - Snowmobile
