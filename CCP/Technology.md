## Domain 3: Technology

### 3.1 Define Methods of Deploying and Operating in the AWS Cloud

#### Identify Different Ways of Provisioning and Operating in the AWS Cloud

- **Programmatic Access, APIs, SDKs:** Developers can use APIs and SDKs to automate tasks and manage resources programmatically.

- **AWS Management Console:** Web-based interface to provision and manage AWS resources.

- **CLI (Command Line Interface):** Command-line tool for managing AWS resources.

- **Infrastructure as Code:** Provision and manage infrastructure using code (e.g., AWS CloudFormation).

#### Identify Different Types of Cloud Deployment Models

- **All in with Cloud/Cloud Native:** Fully leverage AWS services and design for cloud scalability and resiliency.

- **Hybrid:** Combination of on-premises infrastructure and cloud services.

- **On-Premises:** Traditional infrastructure maintained locally by the organization.

#### Identify Connectivity Options

- **VPN (Virtual Private Network):** Securely connect on-premises network to AWS over the public internet.

- **AWS Direct Connect:** Dedicated network connection between on-premises and AWS.

- **Public Internet:** Access resources directly over the public internet.

### 3.2 Define the AWS Global Infrastructure

#### Describe the Relationships Among Regions, Availability Zones, and Edge Locations

- **Regions:** Geographical areas containing multiple Availability Zones.

- **Availability Zones:** Physically separate data centers with independent power, cooling, and networking.

- **Edge Locations:** Data centers located in various parts of the world to improve content delivery.

#### Describe How to Achieve High Availability Through Multiple Availability Zones

- High availability is achieved by deploying resources across multiple Availability Zones.

- Availability Zones are isolated from each other, reducing the risk of single points of failure.

#### Describe When to Consider the Use of Multiple AWS Regions

- **Disaster Recovery/Business Continuity:** Replicate resources across regions for redundancy.

- **Low Latency for End-Users:** Serve content from the closest region to reduce latency.

- **Data Sovereignty:** Store data in regions that comply with local data regulations.

#### Describe the Benefits of Edge Locations

- **Amazon CloudFront:** Content delivery network (CDN) with edge locations for faster content delivery.

- **AWS Global Accelerator:** Improves availability and performance of applications using edge locations.

### 3.3 Identify the Core AWS Services

#### Describe Categories of Services on AWS (Compute, Storage, Network, Database)

AWS services are categorized into compute, storage, network, and database.

#### Identify AWS Compute Services

- **Compute Families:** Different instance types optimized for various use cases (e.g., general purpose, memory, compute-optimized).

- **AWS Lambda:** Serverless compute service for running code without provisioning servers.

- **Amazon Elastic Container Service (Amazon ECS):** Managed container orchestration.

- **Amazon EC2:** Virtual servers for various workloads.

- **Elasticity through Auto Scaling:** Automatically adjusts resources based on demand.

- **Load Balancers:** Distribute incoming traffic for improved availability.

#### Identify Different AWS Storage Services

- **Amazon S3:** Scalable object storage for data and backups.

- **Amazon Elastic Block Store (Amazon EBS):** Persistent block storage for EC2 instances.

- **Amazon S3 Glacier:** Low-cost archive storage.

- **AWS Snowball:** Transfer large amounts of data using physical devices.

- **Amazon Elastic File System (Amazon EFS):** Managed file storage for EC2 instances.

- **AWS Storage Gateway:** Hybrid cloud storage integration.

#### Identify AWS Networking Services

- **VPC (Virtual Private Cloud):** Isolated network environment.

- **Security Groups:** Firewall rules controlling inbound/outbound traffic.

- **Amazon Route 53:** Scalable domain name system (DNS).

- **VPN, AWS Direct Connect:** Secure network connectivity options.

#### Identify Different AWS Database Services

- **Amazon EC2 with Databases:** Install and manage databases on EC2 instances.

- **AWS Managed Databases:** Fully managed database services like Amazon RDS (relational), Amazon DynamoDB (NoSQL).

- **Amazon RDS (Relational Database Service):** Managed relational database service that automates administrative tasks like patching, backups, and scaling.

  *Example:* A company uses Amazon RDS to host its MySQL database for an e-commerce application.

- **Amazon DynamoDB:** Fully managed NoSQL database service that provides fast and predictable performance.

  *Example:* A gaming company uses Amazon DynamoDB to store user profiles and game progress for its multiplayer online game.

- **Amazon Redshift:** Fully managed data warehousing service that provides high-performance analysis of large datasets.

  *Example:* A retail company analyzes sales data using Amazon Redshift to make informed decisions about inventory management.

