# LinkedIn Practice Exam 04

### Question 1  Cloud Concepts

Which concept focuses on programmatically managing infrastructure?

Decoupling

Immutability

Automation

Infrastructure as code

### Explanation

> "Infrastructure as code" is correct. It focuses on programmatically managing infrastructure like servers, networks, storage.

> "Decoupling" (Answer 1) is incorrect. Decoupling refers to separating components so they have little or no knowledge of each other. This allows them to be developed, updated, and scaled independently. It is not focused on infrastructure management.

> "Automation" is incorrect. Automation refers to processes being automated through technology and scripts. While automation can be used in infrastructure as code, it is a separate concept focused on automating tasks in general, not specifically infrastructure management.

> "Immutability" is incorrect. Immutability refers to infrastructure being deployed and maintained in an unchangeable state. While it complements infrastructure as code practices, immutability itself does not focus on programmatic infrastructure management.

---

### Question 2  Cloud Concepts

Who is responsible for configuring backups and performing point-in-time recovery for an Amazon DynamoDB table?

the customer

AWS

#### Explanation

> "the customer" is correct. AWS provides tools to enable point-in-time recovery, but the customer must configure and execute the backups.

> "AWS" is incorrect, AWS is not responsible for backing up customer data.

---

### Question 3  Cloud Technology and Services

Which AWS service can help migrate an existing database to AWS?

AWS Storage Gateway

Amazon AppStream 2.0

AWS Database Migration Service

Amazon EC2

### Explanation

> The "AWS Database Migration Service" can help migrate an existing database to AWS by replicating the data into AWS. The other options do not directly help with migrating a database.

> "AWS Storage Gateway" is incorrect. This service helps connect on-premises environments to cloud storage, but does not directly help migrate databases to AWS.

> "Amazon EC2" is incorrect. This compute service can be used to host databases in AWS, but does not help migrate existing databases.

> "Amazon AppStream 2.0" is incorrect. This service provides desktop application streaming, but does not help migrate databases.

---

### Question 4  Security and Compliance

Which AWS service can you use to get the configuration changes made to AWS resources that caused operational issues?

Amazon Inspector

AWS Config

AWS Trusted Advisor

AWS CloudFormation

### Explanation

> "AWS Config" tracks changes made to AWS resources. It can show you configuration changes that caused operational issues.

> "Amazon Inspector" is incorrect, it checks for security issues but does not track configuration changes.

> "AWS CloudFormation" is incorrect, it is used for provisioning AWS resources, not tracking changes.

> "AWS Trusted Advisor" is incorrect. It optimizes resources, but does not track changes.

---

### Question 5  Cloud Concepts

Why does using cloud computing typically provide more agility compared to on-premises data centers?

No need for IT staff

Faster time to market for new resources

Unlimited on-demand resources

No infrastructure maintenance

### Explanation

> "Faster time to market for new resources" is correct. The cloud provides more agility because resources can be spun up faster. There is no need to procure and provision physical hardware on-premises before deploying new resources.

> "No infrastructure maintenance" is incorrect. These resources help enable agility but faster time to market is the main benefit.

> "Unlimited on-demand resources" is incorrect. These resources help enable agility but faster time to market is the main benefit.

> "No need for IT staff" is incorrect. These resources help enable agility but faster time to market is the main benefit.

---

### Question 6  Billing and Pricing and Support

Which type of AWS offering provides discounts specifically for compute purchases of specific time/hours quantities?

EC2 Reservations

Savings Plans

Reserved Instances

Compute Packages

### Explanation

> "Savings Plans" is correct. Savings Plans are a pricing model for AWS compute usage that offers up to a 72 percent discount on on-demand pricing by committing to purchasing a set amount of compute power (in $/hour) over a one- or three-year span

> "Reserved Instances" is incorrect. Reserved instances are similar to savings plans but are not based on hours of compute time specifically. Reserved instances are reserved in periods of years for compute, not in number of hours of compute time like Savings Plans.

> "Compute Packages" is incorrect. Compute Packages are not a type of AWS offering.

> "EC2 Reservations" is incorrect. EC2 Reservations are not a type of AWS offering.

---

### Question 7  Cloud Concepts

Which concept focuses on replicating data across AZs and regions?

Durability

Elasticity

Decoupling

Automation

### Explanation

> "Durability" is correct. This focuses on replicating data across AZs and regions for recovery from failures.

> "Decoupling" is incorrect. Decoupling focuses on separating components so they can scale independently. It does not involve replicating data across regions.

> "Automation" is incorrect. Automation focuses on automating manual processes and workflows. It does not involve replicating data across regions.

> "Elasticity" is incorrect. Elasticity focuses on providing scalable compute resources to handle changes in demand. It does not involve replicating data across regions.

---

### Question 8  Security and Compliance

Which AWS service provides access to security and compliance reports?

AWS Artifacts

AWS Shield

AWS Systems Manager

AWS Macie

### Explanation

> "AWS Artifacts" provides on-demand access to AWS security and compliance reports and select online agreements. It gives you access to these reports and agreements without having to wait for scheduled releases or go through a sales representative.

> "AWS Systems Manager" is incorrect. It helps manage EC2 and on-premises systems.

> "AWS Shield" is incorrect. AWS Shield provides DDoS attack protection.

> "Amazon Macie" is incorrect. It is a security service that uses machine learning to discover and protect sensitive data.

---

### Question 9  Billing and Pricing and Support

What pricing model does Amazon EC2 use for instances running Amazon Linux 2?

Per Minute

Per Month

Per Instance

Per Second

### Explanation

> "Per Second" is correct. Amazon EC2 instances running Amazon Linux 2 are billed per second for the time the instance is in the running state, with a 60-second minimum. Per second billing allows you to pay only for the compute time you use.

> "Per instrance" is incorrect. Amazon does not use it for running instances of Amazon Linux 2.

> "Per MInute" is incorrect. Amazon does not use it for running instances of Amazon Linux 2.

> "Per Month" is incorrect. Amazon does not use it for running instances of Amazon Linux 2.

---

### Question 10  Cloud Technology and Services

Which AWS service can help provide low latency access to video files stored in a single S3 bucket to users around the world?

Use Amazon Kinesis to cache the video content closer to end users.

Use Amazon Elasticache to cache the video content closer to end users.

Use AWS CloudFront to cache the video content closer to end users.

Use AWS DynamoDB DAX to cache the video content closer to end users.

### Explanation

> "Use AWS CloudFront to cache the video content closer to end users" is correct. AWS CloudFront can cache content in edge locations around the world, providing low latency access to files stored in a central S3 bucket.

> "Amazon ElastiCache" is incorrect. Amazon ElastiCache is used for in-memory caching to reduce latency for database access, not for video file distribution. It does not provide global edge caching and distribution like CloudFront.

> "Amazon DynamoDB Dax" is incorrect. Amazon DynamoDB DAX is an in-memory cache for DynamoDB tables only. It cannot be used to cache and distribute video content globally.

> "Amazon Kinesis" is incorrect. Amazon Kinesis is a service for real-time streaming of data, not for global distribution and caching of static video files. Kinesis does not have a global edge network like CloudFront.

---

### Question 11  Security and Compliance

Which AWS service provides a history of the activities in your AWS account, including actions through the AWS Console, SDKs, CLI, and other AWS services?

AWS Infrastructure Event Management

Amazon CloudWatch

AWS CloudTrail

AWS Config

### Explanation

> The correct answer is "AWS CloudTrail". AWS CloudTrail provides a history of the activities in your AWS account. It records actions taken through the AWS Console, SDKs, CLI, and other AWS services. This helps with security analysis, tracking changes, and troubleshooting. CloudTrail increases visibility into user and resource activity. It shows which users and accounts called AWS, the source IP address, and when the calls occurred.

> "Amazon CloudWatch" is incorrect, it monitors metrics and logs but does not provide a history of all activities in an AWS account.

> "AWS Config" is incorrect, it records configuration changes to AWS resources but does not provide a comprehensive audit trail of all API calls and account activities.

> "AWS Infrastructure Event Management" is incorrect, it is not an actual AWS service.

---

### Question 12  Security and Compliance

Which AWS service provides instrumentation to monitor and troubleshoot applications in the AWS Cloud?

AWS X-Ray

AWS HSM

Amazon QLDB

Amazon Batch

### Explanation

> "AWS X-Ray" is correct. AWS X-Ray provides instrumentation to monitor and troubleshoot applications in the AWS Cloud. It traces requests as they travel through your application to identify performance bottlenecks and errors.

> "AWS HSM" is incorrect as it provides secure cryptographic key storage by making hardware security modules (HSMs) available in the AWS Cloud. It is not used for monitoring and troubleshooting applications.

> "Amazon Batch" is incorrect as it enables developers, scientists, and engineers to easily and efficiently run hundreds of thousands of batch computing jobs on AWS. It is a batch processing service and does not provide instrumentation for monitoring applications.

> "Amazon QLDB" is incorrect as it is a fully managed ledger database that provides a transparent, immutable, and cryptographically verifiable transaction log. It is not used for application monitoring or troubleshooting.

---

### Question 13  Cloud Concepts

With a PaaS implementation, which of the following would be the responsibility of the user? (Choose two.)

Hardware

Patching

Data

Licensing

Code

### Explanation

> "Code" and "Data" are correct. The user is responsible for their application code and data in a PaaS implementation.

> "Licensing" is incorrect. Licensing for software is the responsibility of AWS.

> "Patching" is incorrect. Patching is the responsibility of AWS.

> "Hardward" is incorrect. Hardware is the responsibility of AWS.

---

### Question 14  Cloud Technology and Services

Through the Quick Start options, AWS offers Amazon Machine Images for a variety of operating systems. Which operating system is not one offered through Quick Start?

Microsoft Windows

Oracle Linux

Red Hat Enterprise Linux

AWS Linux

### Explanation

> "Oracle Linux" is correct. Oracle Linux is not offered through the AWS Quick Start for Amazon Machine Images.

> "Microsoft Windows" is incorrect. Microsoft Windows is offered through the AWS Quick Start in a variety of configurations but will incur additional licensing charges that are included in the price.

> "Red Hat Enterprise Linux" is incorrect. Red Hat Enterprise Linux is offered through the AWS Quick Start in a variety of configurations but will incur additional licensing charges that are included in the price.

> "AWS Linux" is incorrect. AWS Linux, Amazon’s own version of Linux, is available through the Quick Start options.

---

### Question 15  Security and Compliance

Which two AWS services can protect against DDoS attacks?

AWS RDS

AWS EC2

AWS Shield Advanced

AWS Shield Standard

#### Explanation

> "AWS Shield Standard" and "AWS Shield Advanced" are the correct answers. AWS Shield Standard provides basic DDoS protection for all AWS customers at no additional charge. It protects against common network and transport layer DDoS attacks. However, Shield Standard has limits on attack size it can absorb. AWS Shield Advanced provides expanded DDoS protection for web applications running on AWS. It protects against larger and more sophisticated attacks compared to Shield Standard. Shield Advanced requires an additional fee

> "AWS EC2" is incorrect. EC2 is an Infrastructure as a Service that provides scalable compute capacity in the cloud. While EC2 enables you to build fault tolerant applications, it does not provide built-in DDoS protection.

> "AWS RDS" is incorrect. RDS is a managed database service that makes it easy to set up, operate, and scale a relational database in the cloud. Like EC2, RDS does not have built-in DDoS protection.

---

### Question 16  Security and Compliance

Which AWS service is used to track changes and manage different versions of system configurations?

AWS CloudWatch

AWS Config

Trusted Advisors

AWS Systems Manager

#### Explanation

> "AWS Config" is correct. It is the service used to track changes and manage different versions of system configurations.

> "Trusted Advisors" is incorrect, it provides recommendations to optimize cost, performance, security, and fault tolerance.

> "AWS Systems Manager" is incorrect, it helps manage EC2 and on-premises systems.

> "CloudWatch" is incorrect, it monitors resources and applications.

---

### Question 17  Cloud Technology and Services

AWS provides a suite of tools to assist with the development and deployment of code within the environment. Which of the following is not a tool provided by AWS?

CodeCommit

CodeBuild

CodeDeploy

CodeVersion

#### Explanation

> "CodeVersion" is correct. CodeVersion is not a tool provided by AWS. Versioning is handled through CodeCommit.

> "CodeBuild" is incorrect. AWS CodeBuild is a fully featured code-building service that will compile and test code, as well as build deployment packages that are ready for implementation.

> "CodeCommit" is incorrect. AWS CodeCommit is an AWS managed service for Git repositories.

> "CodeDeploy" is incorrect. AWS CodeDeploy is a managed deployment service that can deploy code fully across AWS services or on-premises servers.

---

### Question 18  Billing and Pricing and Support

AWS Budgets provides several different types of budget tools to assist in billing planning, and monitoring. Which of the following is not a type of budget provided by AWS?

Cost Budgets

Projected Budgets

Reserved Instances Budgets

Usage Budgets

#### Explanation

> "Projected Budgets" is correct. Projected Budgets is not provided by AWS, though future projections are a tool provided by Cost Explorer.

> "Cost Budgets" is incorrect. Cost Budgets allow for planning what your ceiling will be for spending on a particular service.

> "Reserved Instances Budgets" is incorrect. Reserved Instances Budgets track your usage of Reserved Instances to determine if they are unused or you have purchased too much. These also allow for alerts to be received when your number of Reserved Instances falls below specific thresholds.

> "Usage Budgets" is incorrect. Usage Budgets allow for planning how much actual usage of a particular service you want to use.

---

### Question 19  Security and Compliance

Which AWS service helps identify the resources that were modified and who made the changes?

Amazon Inspector

AWS CloudTrail

AWS Trusted Advisor

AWS Config

#### Explanation

> "AWS Config" is correct. AWS Config tracks changes to AWS resources and records details like who made the change and when it occurred.

> "CloudTrail" is incorrect, it tracks API calls but does not identify changed resources.

> "Inspector" is incorrect, it does not track changes.

> "Trusted Advisor" is incorrect, it does not track changes.

---

### Question 20  Security and Compliance

Which service can help identify potential vulnerabilities and deviations from best practices in an AWS environment?

Amazon Inspector

AWS CloudTrail

AWS Config

AWS Trusted Advisor

#### Explanation

> "Amazon Inspector" analyzes the configuration of AWS resources to identify potential vulnerabilities based on rules packages.

> "AWS Config" is incorrect. AWS Config provides a detailed inventory of AWS resources and configuration history, but does not perform vulnerability or compliance scans.

> "AWS Trusted Advisor" is incorrect. AWS Trusted Advisor provides best practice recommendations and cost optimization advice, but does not scan for vulnerabilities or compliance issues.

> "AWS CloudTrail" is incorrect. AWS CloudTrail records API calls and events, providing an audit trail, but does not analyze configurations for security vulnerabilities or compliance deviations.

---

### Question 21  Security and Compliance

Which AWS service protects your external-facing web applications from bot traffic and DDoS attacks?

AWS Shield Advanced

AWS WAF

AWS CloudTrail

AWS EMR

#### Explanation

> "AWS WAF" is the correct answer. It allows you to configure web ACL rules that protect your web applications from common web exploits.

> "AWS Shield Advanced" provides DDoS protection, but does not protect against bot traffic specifically.

> "AWS CloudTrail" is incorrect. It records API calls, and it does not provide WAF capabilities.

> "EMR" is incorrect. It is a managed Hadoop framework and does not provide WAF capabilities.

---

### Question 22  Security and Compliance

Which two components can be configured through the VPC console in AWS?

Subnet

Security Group

Endpoint

Key Pair

#### Explanation

> "Subnet" and "Security Group" are correct answers. They can both be used to configure subnets and security groups.

> "Endpoint" is an incorrect answer as it cannot be configured through the VPC console.

> "Key Pair" is incorrect as it cannot be configured through the VPC console.

---

### Question 23  Cloud Technology and Services

Which AWS service can be used as a private Git repository?

CodeBuild

CodeDeploy

CodeCommit

CodePipeline

#### Explanation

> "CodeCommit" is the correct answer because it provides a fully-managed and highly scalable private Git repository that makes it easy for companies to host secure and highly scalable private Git repositories.

> "CodeDeploy" is incorrect. This service is used for application deployment, continuous delivery, and build automation respectively but not as a Git repository.

> "CodePipeline" is incorrect. This service is used for application deployment, continuous delivery, and build automation respectively but not as a Git repository.

> "CodeBuild" is incorrect. This service is used for application deployment, continuous delivery, and build automation respectively but not as a Git repository.

---

### Question 24  Security and Compliance

Which dashboard within the AWS Management Console would be used for creating and assigning permissions to user accounts?

System Manager

Users

Security

IAM

#### Explanation

> "IAM" is correct. The AWS Identity and Access Management (IAM) console is used to create IAM accounts, as well as assign permissions and security requirements to them.

> "Security" is incorrect. The Security section of the AWS Management Console is not used for assigning user accounts and permissions.

> "Users" is incorrect. There is not a “Users” section of the AWS Management Console.

> "System Manager" is incorrect. The Systems Manager is used for maintaining instances and performing administrative tasks on everything with the AWS environment, but is not used for user account management.

---

### Question 25  Cloud Technology and Services

With Elastic Load Balancing, three different load balancing models are available. Which of the following is not a load balancing model offered by AWS?

Classic

Application

Dynamic

Network

#### Explanation

> "Dynamic" is correct. The three load balancing models offered as part of Elastic Load Balancing are application load balancer, network load balancer, and classic load balancer.

> "Application" is incorrect. Application load balancing is most typically related to web traffic on both HTTP and HTTPS protocols. It has the ability to analyze the actual contents of the traffic and make determinations for routing and balancing based on rules.

> "Network" is incorrect. Network load balancing is best where performance is key and there are potentially very high levels of traffic. Network load balancing is done at the Layer 4 level of the OSI model, so it is purely based on protocols and the source/destination of traffic.

> "Classic" is incorrect. Classic load balancing is a legacy model offered by AWS for load balancing between EC2 instances that were built on the EC2-Classic network and is not used for modern applications and new services.

---

### Question 26  Cloud Concepts

Select two pillars in the AWS Well-Architected Framework.

Operational Excellence

Performance Efficiency

Data Consistency

Elasticity and Scalability

#### Explanation

> "Operational Excellence" and "Performance Efficiency" are correct. The AWS Well-Architected Framework has five pillars: Operational Excellence, Security, Reliability, Performance Efficiency, and Cost Optimization.

> "Elasticity and Scalability" is incorrect. It is not one of the five pillars of the AWS Well-Architected Framework.

> "Data Consistency" is incorrect. It is not one of the five pillars of the AWS Well-Architected Framework.

---

### Question 27  Cloud Technology and Services

Which AWS S3 storage class, regardless of redundancy or performance criteria, offers the overall lowest price to users?

S3 Intelligent-Tiering

S3 One Zone-Infrequent Access

S3 Standard

S3 Standard-Infrequent Access

#### Explanation

> "S3 One Zone-Infrequent Access" is correct. S3 One Zone-Infrequent Access is the cheapest of the S3 storage classes listed. Rather than being spread across the typical three Availability Zones, objects under this storage class are housed on a single Availability Zone. This realizes costs savings for users, as it is cheaper than other S3 storage classes that span multiple Availability Zones.

> "S3 Standard" is incorrect. S3 Standard is used for commonly accessed data and is optimized for high-throughput and low-latency service.

> "S3 Standard-Infrequent Access" is incorrect. S3 Standard-Infrequent Access is ideally used where access will be infrequent for an object, but when access is requested, a quick response is necessary.

> "S3 Intelligent-Tiering" is incorrect. S3 Intelligent-Tiering is best used for data where usage patterns are unknown or may change over time. This class works by spanning objects across two tiers: one that is optimized for frequent access and the other for lesser access.

---

### Question 28  Cloud Technology and Services

Which AWS service can be used to host a static website?

Amazon S3

Amazon Aurora

AWS Lambda

Amazon Managed Blockchain

#### Explanation

> "Amazon S3" is correct, it can be used to host static websites. S3 provides highly durable and available object storage. Static websites can be hosted directly from S3 buckets.

> "AWS Lambda" is incorrect, it is used for serverless compute.

> "Amazon Aurora" is incorrect, it is used for relational databases.

> "Amazon Managed Blockchain" is used for creating and managing blockchain networks.

---

### Question 29  Cloud Concepts

Which of the following describes a benefit of the AWS pricing model?

Provides a promotional offer of 50% discount every year

Eliminates idle resources

Reduces the cost of maintaining idle resources

Eliminates all resources after 50 days

#### Explanation

> "Reduces the cost of maintaining idle resources" is correct. The AWS pricing model allows you to pay only for the resources you use. By eliminating the cost of maintaining idle resources when they are not in use, it reduces the overall cost.

> "Provides a promotional offer of 50% discount every year" is incorrect. It does not accurately describe benefits of the AWS pricing model.

> "Eliminates all resources after 50 days" is incorrect, as it does not accurately describe benefits of the AWS pricing model.

> "Eliminates idle resources" is incorrect as does not accurately describe benefits of the AWS pricing model.

---

### Question 30  Billing and Pricing and Support

What is the range of time that Cost Explorer will display historical usage and future projections?

12 months back, 12 months forward

12 months back, 6 months forward

6 months back, 3 months forward

6 months back, 6 months forward

#### Explanation

> "12 months back, 12 months forward" is correct. Cost Explorer allows you to view and analyze both your costs and usage of AWS services. Cost Explorer will display data for 12 months of usage, as well as provide forecasts for what you may use in the next 12 months based on your past usage.

> "12 months back, 6 months forward" is incorrect. The combination of previous and forward durations is not in line.

> "6 months back, 6 months forward" is incorrect. The combination of previous and forward durations is not in line.

> "6 months back, 3 months forward" is incorrect. The combination of previous and forward durations is not in line.

---

### Question 31  Billing and Pricing and Support

Which AWS tool can be best used to track your usage of Reserved Instances?

Budgets

Cost Categories

Cost Explorer

Instance Tracker

#### Explanation

> "Budgets" is correct. Budgets are used to plan the consumption of services, the costs of services, and the use of instance reservations. Budgets have specific sections for Reserved Instances budgets and Reserved Instances coverage budgets.

> "Cost Explorer" is incorrect. Cost Explorer will provide your usage for the past 12 months, as well as a future 12-month forecast, but is not specifically geared to Reserved Instances.

> "Cost Categories" is incorrect. Cost Categories are used for organizing services for reporting and tracking, but not specifically for Reserved Instances.

> "Instance Tracker" is incorrect. Instance Tracker is not a tool provided for billing by AWS.

---

### Question 32  Cloud Technology and Services

Which AWS service enables hybrid cloud storage between on-premises data centers and the AWS Cloud?

Amazon S3

AWS Fargate

AWS Snow Family

AWS Storage Gateway

#### Explanation

> The correct answer is "AWS Storage Gateway". It allows you to connect your on-premises environments to the AWS Cloud using a virtual machine or physical hardware appliance. This enables hybrid cloud storage and seamless data transfer between on-premises data centers and AWS.

> "Amazon S3" is incorrect. It is a fully managed object storage service that offers scalability, data availability, security, and performance. However, it is a fully cloud-native service and does not provide hybrid capabilities between on-premises data centers and the cloud.

> "AWS Snow Family" is incorrect because it is a collection of physical devices that help to physically transfer large amounts of data in and out of AWS. However, Snow Family does not enable hybrid cloud storage capabilities. It is used mainly for data transport.

> "AWS Fargate" is incorrect because it is a serverless compute engine for containers that makes it easy to run containers without having to manage servers or clusters. Fargate does not provide any storage or hybrid capabilities.

---

### Question 33  Cloud Concepts

Which feature of AWS Cloud helps organizations quickly deliver new functionality iteratively, thereby minimizing the time to market?

Availability Zones

Enhanced networking

Agility

Elasticity

#### Explanation

> "Agility" is the correct answer because it refers to the ability of AWS Cloud to rapidly deliver new features and applications through iterative development, helping organizations reduce time to market.

> "Availability Zones" is incorrect. It is an AWS capability, but does not directly relate to iterative delivery.

> "Elasticity" is incorrect. It is an AWS capability, but does not directly relate to iterative delivery.

> "Enhanced Networking" is incorrect. It is an AWS capability, but does not directly relate to iterative delivery.

---

### Question 34  Cloud Technology and Services

When you enable versioning on S3, how many previous versions will AWS keep by default?

1

Unlimited

100

10

#### Explanation

> "Unlimited" is correct. Once you have enabled versioning, there is no default limitation to the number of versions that are retained. If you have some objects that are updated regularly, the number of copies and costs can quickly increase.

> "1" is incorrect. 1 has no default limitation.

> "10" is incorrect. 10 has no default limitation.

> "100" is incorrect. 100 has no default limitation.

---

### Question 35  Cloud Technology and Services

In order to use the AWS CLI, what do you need to open on your firewall settings?

Inbound/outbound port 80

Outbound port 80

Outbound port 443

Inbound/outbound port 443

#### Explanation

> "Outbound port 443" is correct. To use the AWS CLI, you will need to open outbound port 443 on your firewall if it is not already allowed.

> "Outbound port 80" is incorrect. The AWS CLI requires the use of secure ports and does not support port 80.

> "Inbound/outbound port 80" is incorrect. The AWS CLI requires the use of secure ports and does not support port 80, nor does it require inbound access on any port.

> "Inbound/outbound port 443" is incorrect. While the AWS CLI requires outbound port 443 access, it does not require any inbound access.

---

### Question 36  Cloud Technology and Services

As part of your company’s DR strategy, you have decided to use S3 Glacier to archive data files. When needed, you have a mandate that data must be accessible in less than six hours’ time. Which S3 retrieval option will you need to utilize to meet this requirement while also realizing the most cost savings?

Expedited

Standard

Bulk

Basic

#### Explanation

> "Standard" is correct. Standard offers retrieval options that will typically return in three to five hours. This is an appropriate choice for typical archives and backups that do not have a need for immediacy in retrieval.

> "Expedited" is incorrect. While expedited offers retrievals within one to five minutes, it will come with increased costs that are unnecessary, as Standard will also meet your mandate.

> "Bulk" is incorrect. Bulk offers retrieval times of 5 to 12 hours and would be unable to meet your mandate.

> "Basic" is incorrect. Basic is not an S3 Glacier retrieval option.

---

### Question 37  Cloud Technology and Services

Which Amazon Web Services tool can notify users if they need to increase the service limit for an EC2 instance?

Personal Health Dashboard

Systems Manager

Trusted Advisor

Service Catalog

#### Explanation

> "Trusted Advisor" is correct, it is an AWS tool that can notify users if they are approaching or have reached the service limits for resources like EC2 instances. It can recommend increasing service limits if needed.

> "Systems Manager" is incorrect. This tool does not monitor or notify about service limits.

> "Service Catalog" is incorrect. This tool does not monitor or notify about service limits.

> "Personal Health Dashboard" is incorrect. This tool does not monitor or notify about service limits.

---

### Question 38  Cloud Concepts

Which concept focuses on monitoring applications and taking automated actions?

Infrastructure as code

Decoupling

Automation

Elasticity

#### Explanation

> "Automation" is correct. This concept focuses on monitoring apps/infrastructure and taking automated actions in response to metrics and events.

> "Infrastructure as code" is incorrect. Infrastructure as code focuses on managing infrastructure through code to provision and manage resources. It does not directly relate to monitoring and automated actions.

> "Decoupling" is incorrect. Decoupling refers to separating components so they are independent and loosely coupled. This allows for more flexibility but does not directly relate to monitoring and automated actions.

> "Elasticity" is incorrect. Elasticity focuses on dynamically scaling resources up and down based on demand. While related to automation, it does not directly focus on monitoring and automated responses.

---

### Question 39  Cloud Concepts

Which concept focuses on deploying systems across multiple physical locations?

Automation

Durability

Geo-distribution

Elasticity

#### Explanation

> "Geo-distribution" is correct. It focuses on deploying systems across multiple physical locations.

> "Automation" is incorrect. Automation describes other concepts in the cloud but is not specific to deploying systems across multiple physical locations.

> "Durability" is incorrect. Durability describes other concepts in the cloud but is not specific to deploying systems across multiple physical locations.

> "Elasticity" is incorrect. Elasticity describes other concepts in the cloud but is not specific to deploying systems across multiple physical locations.

---

### Question 40  Cloud Technology and Services

Which AWS service provides a unified interface to view operational data across multiple AWS services and automate tasks?

AWS Service Catalog

AWS Trusted Advisor

AWS Systems Manager

AWS Organizations

#### Explanation

> "AWS Systems Manager" provides a unified user interface to view operational data across multiple AWS services. It also allows automating operational tasks across AWS resources.

> "AWS Service Catalog" is incorrect because it provides a catalog of IT services that are approved for use on AWS. It does not provide a unified interface to view operational data or automate tasks across services.

> "AWS Organizations" is incorrect because it helps consolidate and manage multiple AWS accounts. It does not provide a unified interface or automation capabilities across services.

> "AWS Trusted Advisor" is incorrect because it provides recommendations to optimize performance, security, cost, and fault tolerance. It does not provide a unified interface or automation capabilities.

---

### Question 41  Cloud Technology and Services

Which of the following is the correct URL for accessing the AWS Management Console?

https://console.amazon.com

https://mgmt.aws.com

https://console.aws.com

https://console.aws.amazon.com

#### Explanation

> "https://console.aws.amazon.com" is correct. The correct URL for the AWS Management Console is https://console.aws.amazon.com.

> "https://console.amazon.com" is incorrect. The URLs for AWS services will always include `aws` in them.

> "https://mgmt.aws.com" is incorrect. The URLs for AWS services will always have both `aws` and `amazon` in them.

> "https://console.aws.com" is incorrect. The URLs for AWS services will always have both `aws` and `amazon` in them.

---

### Question 42  Security and Compliance

Which statement about AWS Certificate Manager certificates is incorrect?

They are free when used with Elastic Load Balancer.

They automate the process of getting and renewing SSL/TLS certificates.

You can issue unlimited certificates.

They are permanent certificates.

#### Explanation

> "They are permanent certificates" is the correct answer, as AWS Certificate Manager certificates are not permanent. They need to be renewed every 12 months.

> "They automate the process of getting and renewing SSL/TLS certificates" is incorrect response, as ACM automates and simplifies SSL/TLS certificate management,

> "They are free when used with Elastic Load Balancer" is incorrect response, as certificates are free with ELM.

> "You can issue unlimited certificates" is response as you can issue unlimited certificates.

---

### Question 43  Security and Compliance

Which technique can help protect data in Amazon S3 from accidental deletions and overwrite?

Use bucket policies to restrict access.

Enable object versioning.

Use multi-factor authentication (MFA) Delete.

Enable object locking.

#### Explanation

> "Enable object versioning" is correct. Enabling versioning in S3 protects objects from accidental overwrite or deletion by keeping multiple versions.

> "Use multi-factor authentication (MFA) Delete" is incorrect. MFA Delete adds an extra step for deletions but does not prevent accidents.

> "Enable object locking" is incorrect, it restricts access but does not prevent accidents by authorized users.

> "Use bucket policies to restrict access" is incorrect, it restricts access but will not prevent accidents by authorized users.

---

### Question 44  Cloud Technology and Services

Which AWS service helps adjust compute capacity based on demand?

AWS CloudFormation

Auto Scaling

Load Balancer

Amazon EC2 Spot Instances

#### Explanation

> "Auto Scaling" allows you to automatically add or remove EC2 instances based on demand. It helps maintain application availability and allows you to optimize costs by only running resources when needed.

> "Load Balancer" is incorrect. Load Balancers help distribute traffic across multiple EC2 instances but do not automatically adjust capacity based on demand. Load Balancers maintain availability by routing requests across healthy EC2 instances, but do not scale capacity up or down.

> "AWS CloudFormation" is incorrect. AWS CloudFormation is used to provision AWS resources based on templates, but does not automatically adjust capacity based on metrics and demand. CloudFormation allows you to manage, configure and provision resources together through templates, but is not an auto-scaling service.

> "Amazon EC2 Spot Instances" is incorrect. Amazon EC2 Spot Instances allow you to request unused EC2 capacity at steep discounts compared to On-Demand prices. However, Spot Instances can be terminated with little notice when EC2 capacity is needed. Spot Instances do not automatically scale capacity based on metrics and demand.

---

### Question 45  Cloud Concepts

With the exception of a small number of AWS regions, what type of cloud deployment model is AWS?

Community

Private

Public

Hybrid

#### Explanation

> "Public" is correct. AWS is a public cloud because anyone can sign up for an account and use AWS services.

> "Private" is incorrect. While there are some aspects of AWS that can fit within a hybrid cloud model, and a few specific regions are more of a private or community cloud model, AWS overall is a public cloud.

> "Hybrid" is incorrect. While there are some aspects of AWS that can fit within a hybrid cloud model, and a few specific regions are more of a private or community cloud model, AWS overall is a public cloud.

> "Community" is incorrect. While there are some aspects of AWS that can fit within a hybrid cloud model, and a few specific regions are more of a private or community cloud model, AWS overall is a public cloud.

---

### Question 46  Cloud Technology and Services

Which Amazon Web Services service provides a managed version control system?

AWS Config

AWS CloudWatch

AWS CloudTrail

AWS CodeCommit

#### Explanation

> "AWS CodeCommit" is the correct answer because it is an Amazon Web Services service that provides a managed version control system.

> "AWS CloudWatch" is incorrect. This AWS service does not provide version control functionality.

> "AWS Config" is incorrect. This AWS service does not provide version control functionality.

> "AWS CloudTrail" is incorrect. This AWS service does not provide version control functionality.

---

#### Question 47  Cloud Technology and Services

AWS offers solutions for container deployments that are fully managed and do not require an EC2 instance to host the containers. Which two container services are offered by AWS?

AWS Elastic Kubernetes Service

AWS Elastic Docker Service

AWS Enterprise Docker Service

AWS Elastic Container Service

AWS Dynamic Containers Service

#### Explanation

> "AWS Elastic Container Service" and "AWS Elastic Kubernetes Service" are correct. AWS offers both the Amazon Elastic Container Service (ECS) and the Amazon Elastic Kubernetes Service (EKS).

> "AWS Enterprise Docker Service" is incorrect. It is a similar-sounding names but it is not the correct AWS service name.

> "AWS Elastic Docker Service" is incorrect. It is a similar-sounding names but it is not the correct AWS service name.

> "AWS Dynamic Containers Service" is incorrect. It is a similar-sounding names but it is not the correct AWS service name.

---

### Question 48  Billing and Pricing and Support

I have a large amount of data (images, documents) that I want to store in the AWS S3 storage service. I want to understand how S3 is priced to make informed decisions. Which two of the following are accounted as costs for S3 storage?

Uploading data to an S3 bucket

Data transfer from one AWS region to another

Lifecycle transitions between storage classes

Data transfer to Amazon CloudFront

Data transfer within the same AWS region

#### Explanation

> "Lifecycle transitions between storage classes" is correct because lifecycle transitions between S3 storage classes are charged as GET and PUT requests, which incur costs.

> "Data transfer from one AWS region to another" is also correct because outbound data transfer from one AWS region to another incurs charges.

> "Uploading data to an S3 bucket" is incorrect because inbound data transfer to S3 does not incur charges.

> "Data transfer within the same AWS region" is incorrect because data transfer within the same region is free.

> "Data transfer to Amazon CloudFront" is incorrect because outbound data transfer to CloudFront is free.

---

### Question 49  Cloud Concepts

Which concept focuses on loosely connecting components and layers of cloud architecture?

Decoupling

Infrastructure as code

Automation

Immutability

#### Explanation

> "Decoupling" is correct. Decoupling focuses on loosely connecting components to prevent failures from spreading.

> "Automation" is incorrect. Automation in AWS allows you to build services faster and efficiently.

> "Immutability" is incorrect, it refers to data protection planning.

> "Infrastructure as code" is incorrect. Infrastructure as a code is designed to assist in automation and self-service.

---

### Question 50  Security and Compliance

Which two of the following AWS services prohibit you from performing penetration testing without prior authorization?

AWS Shield (Advanced)

AWS Shield (Standard)

Amazon EC2 instances

Amazon RDS

#### Explanation

> "Amazon RDS" and "AWS Shield (Standard)" are correct answers. Both prohibit penetration testing without prior authorization from Amazon.

> "Amazon EC2 instances" is an incorrect answer, it allows penetration testing without prior approval.

> "AWS Shield (Advanced)" is an incorrect answer, it allows penetration testing without prior approval.

---

### Question 51  Security and Compliance

Which technique enables a least privilege access model in AWS?

Enable MFA.

Review access periodically.

Use groups and roles instead of sharing credentials.

Use policy conditions for constraints.

#### Explanation

> "Using IAM groups and roles instead of sharing credentials enables least privilege access" Each entity only gets the permissions needed for its function.

> "Review access periodically" is incorrect. It is useful but does not specifically enable least privilege.

> "Use policy conditions for constraints" is incorrect. It is useful but does not specifically enable least privilege.

> "Enable MFA" is incorrect. It is useful but does not specifically enable least privilege.

---

### Question 52  Cloud Technology and Services

Which feature of the AWS Systems Manager allows for grouping of resources for easier viewing and granularity?

Resource groups

Service labels

Resource pools

Cost categories

#### Explanation

> "Resource groups" is correct. Resource groups allow for the logical grouping of resources within AWS for how they are presented within the Systems Manager.

> "Cost categories" is incorrect. Cost categories is not a feature of the AWS Systems Manager.

> "Service labels" is incorrect. Service labels is not a feature of the AWS Systems Manager.

> "Resource pools" is incorrect. Resource pools is not a feature of the AWS Systems Manager.

---

### Question 53  Billing and Pricing and Support

What activities are included in AWS Support? (Choose two.)

Code development

Troubleshooting API issues

Debugging custom software

Configuring third-party applications on AWS

#### Explanation

> "Troubleshooting API issues" and "Configuring third-party applications on AWS" are correct. AWS Support helps with troubleshooting API and SDK issues, operational issues, AWS tools issues, and configuring third-party applications on AWS.

> "Code development" is incorrect. AWS Support does not help with code development.

> "Debugging custom software" is incorrect. AWS does not help with debugging custom software, system administration, or database tuning.

---

### Question 54  Cloud Technology and Services

Which AWS service is a content delivery network (CDN)?

Lightsail

CloudFront

Elastic Beanstalk

Lambda

#### Explanation

> "CloudFront" is correct. Amazon CloudFront is a CDN that allows for delivery data and media to users with the lowest levels of latency and the highest levels of transfer speeds. This is done by having CloudFront systems distributed across the entire AWS global infrastructure and fully integrated with many AWS services, such as S3, EC2, and Elastic Load Balancing.

> "Elastic Beanstalk" is incorrect. Elastic Beanstalk is an application platform where you select the code your application is written in, and you can quickly deploy your code into an instance and be up and running.

> "Lightsail" is incorrect. Lightsail offers managed platforms and application stacks to allow for quick deployment of applications into AWS.

> "Lambda" is incorrect. AWS Lambda is a service for running code for virtually any application or back-end service. All you need to do is upload your code, and there are no systems or resources to manage.

---

### Question 55  Security and Compliance

Which technique can help protect data stored in Amazon S3 buckets?

Enable default encryption using server-side encryption.

Use pre signed URLs for temporary access.

Use bucket policies to restrict access.

Enable object versioning.

#### Explanation

> "Enable default encryption using server-side encryption" is correct. Enabling default encryption with server-side encryption helps protect data stored in S3 buckets.

> "Use pre signed URLs for temporary access" is incorrect. It helps with access control but does not encrypt data.

> "Enable object versioning" is incorrect. It helps with access control but does not encrypt data.

> "Use bucket policies to restrict access" is incorrect. It helps with access control but does not encrypt data.

---

### Question 56  Billing and Pricing and Support

What benefits are included with an Enterprise Support plan from Amazon Web Services? (Choose two.)

AWS Technical Support Manager

AWS Cloud Architect

Technical Account Manager

AWS Support Analysts

#### Explanation

> The correct answers are "Technical Account Manager" and access to "AWS Support Analysts". These provide specialized and dedicated technical resources to help optimize usage and architect solutions on AWS.

> "AWS Cloud Architect" is incorrect, it is not included benefits of Enterprise Support.

> "AWS Technical Support Manager" is incorrect, it is not included benefits of Enterprise Support.

---

### Question 57  Security and Compliance

Which AWS service uses the SCP feature to manage permissions?

AWS Organizations

AWS Config

AWS Lambda

AWS EC2

#### Explanation

> "AWS Organizations" uses service control policies (SCPs) to centrally manage permissions across multiple AWS accounts. SCPs limit permissions for entities in member accounts, including users, groups, and roles. The other services listed do not use SCPs to manage permissions.

> "AWS Config" is incorrect. AWS Config does not use SCPs. It is a service that provides resource inventory, configuration history, and configuration change notifications to enable security and governance.

> "AWS Lambda" is incorrect. AWS Lambda does not use SCPs. It is a serverless compute service that runs code in response to events and automatically manages the underlying compute resources.

> "AWS EC2" is incorrect. AWS EC2 does not use SCPs. It provides scalable virtual servers called EC2 instances to run applications. You manage permissions for EC2 resources using IAM policies.

---

### Question 58  Cloud Concepts

Your company has heavy video processing and rendering operations that you want to keep within your own servers but then use AWS for the rest of your operations, especially your customer-facing services. Which cloud model would this best fit?

Community

Public

Private

Hybrid

#### Explanation

> "Hybrid" is correct. By splitting resources between AWS and your on-premises data center, you are using a hybrid cloud model across two providers.

> "Private" is incorrect. Private cloud do not fit the scenario presented as it does not span two providers.

> "Public" is incorrect. Public cloud do not fit the scenario presented as it does not span two providers.

> "Community" is incorrect. Community cloud do not fit the scenario presented as it does not span two providers.

---

### Question 59  Security and Compliance

Which AWS service has automated backups configured by default?

Amazon Batch

Amazon RDS MySQL Database

Amazon Athena

MySQL Database installed on EC2

#### Explanation

> "Amazon RDS MySQL Database" is correct. It has automated backups enabled by default.

> "MySQL installed on EC2" is incorrect as it does not have automated backups by default.

> "Amazon Batch" is incorrect. It is an unrelated services that do not provide database capabilities or backups.

> "Athena" is incorrect, it does not provide database capabilities or backups.

---

### Question 60  Security and Compliance

When using federated authentication with SAML, what are the two key components involved with the workflow? (Choose two.)

LDAP

Application

System of record

Service provider

Identity provider

#### Explanation

> "Identity provider" and "Service provider" are correct. With SAML federated authentication, the two key components in the flow are the service provider and identity provider.

> "Application" is incorrect. A service provider is closely associated with an application and is what performs its authentication, but the application itself is not a part of SAML authentication.

> "System of record" is incorrect. A system of record will contain information about users and typically will feed into an identity provider but is not itself a part of SAML authentication.

> "LDAP" is incorrect. LDAP is often used in conjunction with an identity provider to pull user information during the authentication process but is not one of the key parts of SAML authentication.

---

### Question 61  Cloud Technology and Services

Which AWS Service offers unstructured, non-relational database services?

Amazon Aurora

Amazon Redshift

DynamoDB

Amazon RDS

#### Explanation

> "DynamoDB" is correct. DynamoDB is the AWS key/value and document database solution for those applications that do not need a SQL or relational database but do need extremely high performance and scalable access to their data. As with other AWS services, DynamoDB is fully configured, maintained, and secured by AWS, so all the user needs to do is create a table and populate their data.

> "Amazon Aurora" is incorrect. Aurora is an AWS database service, a subset of Amazon RDS, that is compatible with both MySQL and PostgreSQL databases. It combines the features and simplicity of the open-source databases with the robust management and security of AWS services.

> "Amazon RDS" is incorrect. Amazon Relational Database Service (RDS) is an umbrella service that incorporates several different kinds of database systems. Each system is fully managed by AWS and is optimized within the AWS infrastructure for memory, performance, and I/O.

> "Amazon Redshift" is incorrect. Redshift is a cloud-based data warehouse solution offered by AWS.

---

### Question 62  Cloud Technology and Services

Which AWS service can you use to run Docker containers without having to manage servers?

AWS S3

AWS Fargate

Amazon API Gateway

AWS Snow Family

#### Explanation

> "AWS Fargate" is the correct answer because it allows you to run Docker containers without having to manage servers or clusters. Fargate removes the need to provision and manage servers, making it easier to run containers.

> "AWS S3" is incorrect. It is used for object storage.

> "AWS Snow Family" is incorrect. It is used for edge computing.

> "API Gateway" is incorrect. It is used for creating APIs.

---

### Question 63  Cloud Concepts

Which feature of AWS allows companies to scale based on demand?

Elastic Load Balancing

Amazon CloudFront

Auto Scaling

Amazon S3

#### Explanation

> "Auto Scaling" is correct. It allows companies to automatically add or remove resources based on demand.

> "Elastic Load Balancing" is incorrect, it distributes traffic across resources.

> "Amazon S3" is incorrect, it is a storage and content delivery services.

> "Amazon CloudFront" is incorrect, it is also a storage and content delivery services.

---

### Question 64  Security and Compliance

Which technique enables governance of an AWS environment by comparing configurations against desired baselines?

Use AWS Trusted Advisor.

Use AWS Config rules.

Use AWS GuardDuty.

Enable AWS CloudTrail.

#### Explanation

> "Use AWS Config rules" is correct. AWS Config rules can check for configurations that deviate from desired baselines and automatically flag noncompliant resources"

> "Enable AWS CloudTrail" is incorrect. It will not assess configurations against baselines.

> "Use AWS Trusted Advisor" is incorrect. It will not assess configurations against baselines.

> "Use AWS GuardDuty" is incorrect. It will not assess configurations against baselines.

---

### Question 65  Cloud Concepts

Why would using AWS with an application that has cyclical load demands, such as a healthcare provider during open enrollment periods, be more cost-effective in AWS than a traditional data center?

AWS is continually expanding and adding faster compute resources

AWS resources can be allocated when needed

AWS resources can be spread across multiple regions

You can provision enough resources year-round to handle peak loads without buying more hardware

#### Explanation

> "AWS resources can be allocated when needed" is correct. AWS can add and remove resources as needed. An application can run with a lower set of resources during normal operations and then add more resources for cyclical load periods. The user will only pay for the increased level of resources when needed and in use.

> "You can provision enough resources year-round to handle peak loads without buying more hardware" is incorrect. You would not want to provision resources needed for peak load year-round, as you would then incur costs for them throughout the year. With the elasticity of AWS, there would be no need to do so.

> "AWS resources can be spread across multiple regions" is incorrect. Spreading resources across multiple regions would not serve to contain costs for cyclical load periods.

> "AWS is continually expanding and adding faster compute resources" is incorrect. While AWS is always expanding and added faster compute resources, this would not pertain to the objective stated.
