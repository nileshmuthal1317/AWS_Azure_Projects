## Domain 2: Security and Compliance

### 2.1 Define the AWS Shared Responsibility Model

#### Recognize the Elements of the Shared Responsibility Model

The AWS Shared Responsibility Model outlines security responsibilities between AWS and customers:

- **Customer Responsibility:** Customers are responsible for securing their data in the cloud, including encryption and access control.

- **AWS Responsibility:** AWS secures the underlying infrastructure, such as data centers and network.

#### Describe the Customer’s Responsibility on AWS

Customer responsibilities may vary based on the service used:

- **Amazon RDS:** Customers are responsible for data management and access control in the database.

- **AWS Lambda:** Customers are responsible for securing the code they deploy using Lambda functions.

- **Amazon EC2:** Customers are responsible for securing the operating system and applications on the instances.

#### Describe AWS Responsibilities

AWS responsibilities include securing physical infrastructure, hardware, and networking components.

### 2.2 Define AWS Cloud Security and Compliance Concepts

#### Identify Where to Find AWS Compliance Information

- AWS provides compliance information for various regulations (e.g., HIPAA, SOC) on their compliance pages.

- Different AWS services have different compliance certifications due to varying use cases and requirements.

#### Describe How Customers Achieve Compliance on AWS

- AWS offers encryption options for data:
  - **In Transit:** Encryption of data while it's being transferred, such as using SSL/TLS.
  - **At Rest:** Encryption of data stored in services like Amazon S3 using server-side encryption.

- Encryption on AWS services is enabled by customers during configuration.

- Auditing and reporting are aided by services like Amazon CloudWatch, AWS Config, and AWS CloudTrail.

#### Describe Who Enables Encryption on AWS for a Given Service

- Customers are responsible for enabling encryption for their data and services as part of their configurations.

#### Recognize Services for Auditing and Reporting

- Logs exist for auditing and monitoring, including services like Amazon CloudWatch, AWS Config, and AWS CloudTrail.

#### Explain the Concept of Least Privileged Access

- Least Privileged Access means granting users and applications only the permissions they need to perform their tasks.

### 2.3 Identify AWS Access Management Capabilities

#### Understand the Purpose of User and Identity Management

- **Access Keys and Password Policies:** Define rules for access key usage and password complexity.

- **Multi-Factor Authentication (MFA):** Enhances security by requiring an additional form of verification beyond a password.

- **AWS Identity and Access Management (IAM):** Manages access to AWS services through users, groups, roles, and policies.

#### Tasks Requiring Use of Root Accounts

- Root accounts have full administrative privileges and are used for initial setup.

- It's recommended to use root accounts only for essential tasks and secure them using MFA.

### 2.4 Identify Resources for Security Support

#### Recognize Different Network Security Capabilities

- **Native AWS Services:** Use security groups, Network ACLs, and AWS WAF for network security.

- **3rd Party Security Products:** AWS Marketplace offers various security solutions for additional protection.

#### Recognize Documentation Resources

- Access best practices, whitepapers, and official documents through AWS Knowledge Center, Security Center, security forum, and security blogs.

- Partner Systems Integrators can provide guidance on security architecture.

#### Understand Security Checks in AWS Trusted Advisor

- AWS Trusted Advisor offers security checks to identify vulnerabilities and areas for improvement in your AWS environment.
