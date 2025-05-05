# LinkedIn Practice Exam 03

### Question 1  Cloud Technology and Services

Which Amazon Web Services offering enables users to find, buy, and immediately start using software solutions in their AWS environment?

AWS Config

AWS SDK

AWS Marketplace

AWS OpsWorks

#### Explanation

> The correct answer is "AWS Marketplace". AWS Marketplace allows users to find, buy, and immediately start using software solutions that run on AWS.

> "AWS Config" is incorrect. AWS Config is a service that provides resource inventory, configuration history, and configuration change notifications to enable security and governance. It does not allow users to find and buy software solutions.

> "AWS OpsWorks" is incorrect. AWS OpsWorks is a configuration management service that provides managed instances of Chef and Puppet. It allows you to use Chef and Puppet to automate how servers are configured, deployed, and managed across EC2 instances or on-premises compute environments. It does not enable users to find and buy software solutions.

> "AWS SDK" is incorrect. The AWS SDKs consist of libraries and sample code for various programming languages and platforms like Java, Python, Ruby, .NET, iOS, and Android. They help developers integrate AWS services into their applications. The SDKs do not allow you to find and buy software solutions.

---

### Question 2  Cloud Technology and Services

If you wanted to use Chef for maintain your Windows and IIS web servers within your AWS account, which AWS service would you use?

OpsWorks

CodeDeploy

Automation

AWS AppConfig

#### Explanation

> "OpsWorks" is correct. AWS OpsWorks provides managed instances of Puppet and Chef.

> "CodeDeploy" is incorrect. AWS CodeDeploy is a managed deployment service that can deploy code fully across AWS services or on-premises servers.

> "AWS AppConfig" is incorrect. AWS AppConfig provides an API and console method for applying configuration changes across AWS services from a centralized service.

> "Automation" is incorrect. Automation provides a set of predefined playbooks to do common repetitive tasks, but also allows for users to create their own playbooks that are appropriate for their specific services.

---

### Question 3  Security and Compliance

What resources should be deployed in the private subnet of an Amazon VPC for security?

Database Servers

NAT Gateways

Internet Gateways

Bastion Hosts

#### Explanation

> "Database Servers" is correct. Database servers contain confidential information, so for security they should be deployed in a private subnet. A private subnet in Amazon VPC does not have direct access to the internet.

> "NAT Gateways" is incorrect, it allows access from private subnets to the internet, so it is deployed in public subnets.

> "Bastion Hosts" is incorrect, it allows access from private subnets to the internet, so it is deployed in public subnets.

> "Internet Gateways" are incorrect, it allows communication between the VPC and the internet, so it is also deployed in public subnets.

---

### Question 4  Cloud Technology and Services

Which of the following statements about security groups is true?

Security groups allow all outbound and inbound traffic by default.

Security groups allow all outbound traffic by default, but no inbound traffic.

Security groups deny all inbound and outbound traffic by default.

Security groups allow all inbound traffic by default, but no outbound traffic.

#### Explanation

> "Security groups allow all outbound traffic by default, but no inbound traffic." is correct. By default, security groups allow all outbound traffic by default, but no inbound rules are applied.

> "Security groups allow all outbound and inbound traffic by default." is incorrect. Security groups do not allow any inbound traffic by default and each answer allows for inbound traffic.

> "Security groups allow all inbound traffic by default, but no outbound traffic." is incorrect. Security groups do not allow any inbound traffic by default and each answer allows for inbound traffic.

> "Security groups deny all inbound and outbound traffic by default." is incorrect. Security groups do not allow any inbound traffic by default and each answer allows for inbound traffic.

---

### Question 5  Security and Compliance

Which Amazon Web Services resource requires customers to be responsible for security configurations related to the infrastructure?

Amazon EC2

Amazon RDS

AWS Fargate

Amazon DynamoDB

#### Explanation

> "Amazon EC2" is correct. EC2 is an Infrastructure as a Service offering where customers are responsible for security and management of the guest operating systems.

> "Amazon DynamoDB" is incorrect. It is a managed services where AWS handles the infrastructure security.

> "Amazon RDS" is incorrect. It is a managed services where AWS handles the infrastructure security.

> "AWS Fargate" is incorrect. It is a managed services where AWS handles the infrastructure security.

---

### Question 6  Cloud concepts

What is Amazon responsible for under the AWS shared responsibility model?

Configuring third-party applications

Managing guest operating systems

Securing application access and data

Securing underlying infrastructure and foundation services

#### Explanation

> "Securing underlying infrastructure and foundation services" is correct. Under the AWS shared responsibility model, Amazon is responsible for securing the underlying infrastructure and foundation services.

> "Configuring third-party applications" is incorrect. Under the shared responsibility model, customers are responsible for configuring and managing third-party applications they use in AWS. Amazon does not configure or maintain customer applications.

> "Securing application access and data" is incorrect. Customers are responsible for securing access to their data and applications.

> "Managing guest operating systems" is incorrect. Customers are responsible for patching, updating, and securing their own guest operating systems, including software running on top of them. AWS manages the hypervisor and underlying infrastructure only.

---

### Question 7  Security and Compliance

Which authentication method should be used to programmatically access AWS resources from the AWS CLI?

Fingerprint

IAM Role

User ID and Password

Client Certificate

#### Explanation

> "IAM roles" allow secure access to AWS resources for applications without having to manage access keys. User IDs and passwords are used for IAM user access, not for programmatic access.

> "User ID and Password" is incorrect. User ID and Password does not provide API access. It provides security groups control network access.

> "Client Certificate" is incorrect. Client Certificate does not provide API access. It provides security groups control network access.

> "Fingerprint" is incorrect. Fingerprint does not provide API access. It provides security groups control network access.

---

### Question 8  Cloud Technology and Services

Your application has the potential for very high levels of traffic, and you want to get optimal performance from Elastic Load Balancing. Which type of ELB would be best suited for this application?

Application

Network

Classic

Dynamic

#### Explanation

> "Network" is correct. Network load balancing is best where performance is key and there are potentially very high levels of traffic, as it does not perform any analysis of content.

> "Application" is incorrect. Application load balancing, while giving a lot more flexibility with content inspection, is not the best choice for applications with extremely high levels of traffic.

> "Classic" is incorrect. The classic load balancer model is no longer used and is only maintained to support some legacy instances of EC2.

> "Dynamic" is incorrect. Dynamic is not a type of load balancer with ELB.

---

### Question 9  Billing and Pricing and Support

Which two Amazon Web Services support plans provide 24/7 access to enhanced technical support?

All plans

Developer

Business

Enterprise

#### Explanation

> The "Business" and "Enterprise" support plans offer enhanced technical support 24/7 via phone, web, and chat access to Cloud Support Engineers.

> "Developer" is incorrect. The Developer support plan provides 24/7 access to customer service but only provides enhanced technical support during business hours.

> "All plans" is incorrect. Not all AWS support plans provide 24/7 enhanced technical support.

---

### Question 10  Cloud concepts

Which characteristic of cloud computing enables accessing computer system resources rapidly and elastically?

Durability

Agility

Scalability

Availability

#### Explanation

> "Scalability" is correct. It allows systems in the cloud to rapidly adjust resources up or down based on demand.

> "Agility" is incorrect. Agility is a characteristic of cloud computing, however it does not enable accessing computer system resources rapidly and elastically.

> "Availability" is incorrect. Availability is a characteristic of cloud computing, however it does not enable accessing computer system resources rapidly and elastically.

> "Durability" is incorrect. Durability is a characteristic of cloud computing, however it does not enable accessing computer system resources rapidly and elastically.

---

### Question 11  Security and Compliance

Where in the architecture should firewalling be implemented for a web hosting design using AWS?

For all access layer functions

At the core

At the perimeter

At all layers

#### Explanation

> "At the perimeter" is correct. In AWS, firewalling should be implemented at the perimeter for a web hosting architecture. The perimeter is the entry point to the architecture, so implementing firewalls there allows controlling access.

> "At all layers" is incorrect, since this would be insufficient.

> "At the core" is incorrect, since this would be insufficient.

> "For all access layer functions" is incorrect. Alone would also miss traffic to other layers.

---

### Question 12  Cloud Technology and Services

Which Amazon Web Services (AWS) compute service allows you to run a custom software on a Red Hat operating system?

AWS DynamoDB

AWS EC2

AWS S3

AWS Lambda

#### Explanation

> "AWS EC2" is correct. AWS EC2 allows you to run a custom software on various operating systems, including Red Hat. You can launch EC2 instances and install your own software.

> "AWS DynamoDB" is incorrect. AWS DynamoDB is a storage and compute service, but does not provide full operating systems to install custom software.

> "AWS Lambda" is incorrect. AWS Lambda does not provide full operating systems to install custom software.

> "AWS S3" is incorrect. AWS S3 is a storage and compute service, but does not provide full operating systems to install custom software.

---

### Question 13  Cloud concepts

What is the maximum amount of data that can be stored in Amazon S3?

1 PB

Virtually Unlimited 1 EB

100 PB

#### Explanation

> "Virtually Unlimited 1 EB" is correct. Amazon S3 allows storing virtually unlimited amounts of data, up to 1 exabyte.

> "100 PB" is incorrect. 100 PB is too small for S3.

> "1 PB" is incorrect. 1 PB is too small for S3.

---

### Question 14  Cloud concepts

What benefits does a database administrator get by using Amazon Relational Database Service (RDS)?

RDS simplifies tasks related to managing relational databases.

RDS enables users to dynamically adjust CPU and RAM resources.

RDS databases automatically scale based on load.

RDS provides extremely high reliability and durability.

#### Explanation

> "RDS simplifies tasks related to managing relational databases" is correct. Amazon RDS makes it easy for database administrators by handling common database administration tasks like backups, software patching, automatic failure detection, and recovery. So RDS simplifies the administration of relational databases.

> "RDS enables users to dynamically adjust CPU and RAM resources" is incorrect because while RDS does allow scaling of CPU and RAM resources, this is not a key benefit for database administrators. The scaling is handled automatically by RDS.

> "RDS databases automatically scale based on load" is incorrect because although RDS databases can automatically scale based on load, this auto-scaling is again not a key benefit for database administrators specifically. The auto-scaling removes some management overhead for administrators but is not a core benefit.

> "RDS provides extremely high reliability and durability" is incorrect because while RDS does provide high reliability and durability, this is a benefit for application owners more so than database administrators. The database administrators are shielded from many reliability concerns by using RDS.

---

### Question 15  Cloud Technology and Services

Which of the following are true about security groups, but not ACLs? (Choose two)

Each subnet must have a security group applied.

Rule are applied at the subnet level.

Rules are applied to only specify things allowed.

The VPC by default will allow all traffic for both inbound and outbound routes.

Traffic is automatically allowed outbound to respond to an allowed inbound rule.

#### Explanation

> "Rules are applied to only specify things allowed." and "Traffic is automatically allowed outbound to respond to an allowed inbound rule." are correct. Security groups are based on actions allowed, while ACLs can both allow and deny rules. Security groups will also automatically allow outbound responses from requests, whereas they must be explicitly allowed with ACLs.

> "Rule are applied at the subnet level." is incorrect. This is true for ACLs, but not for security groups.

> "Each subnet must have a security group applied." is incorrect. This is true for ACLs, but not for security groups.

> "The VPC by default will allow all traffic for both inbound and outbound routes." is incorrect. This is true for ACLs, but not for security groups.

---

### Question 16  Cloud concepts

Which cloud characteristic involves delivering the same resources to a large pool of customers?

Scalability

Multitenancy

Elasticity

Agility

#### Explanation

> "Multitenancy" is correct. This allows delivering the same resources to a large pool of customers in a scalable way. Customers share infrastructure while still being isolated.

> "Elasticity" is incorrect. It enables flexible resource usage, but does not directly relate to serving multiple customers.

> "Agility" is incorrect. It enables flexible resource usage, but does not directly relate to serving multiple customers.

> "Scalability" is incorrect. It enables flexible resource usage, but does not directly relate to serving multiple customers.

---

### Question 17  Cloud concepts

What are two common tasks that AWS can manage for their customers when running applications in the AWS Cloud?

Taking backups of databases

Patching database software

Design schema of your data

Customize your code

#### Explanation

> "Taking backups of databases" and "Patching database software" are correct. AWS can manage common tasks like taking backups of databases and patching database software on behalf of customers running applications in the AWS Cloud. This allows customers to focus on their applications rather than infrastructure management.

> "Customize your code" is incorrect. Auditing source code and security testing are not tasks that AWS typically handles for customers.

> "Design schema of your data" is incorrect. Creating database schemas is not a task that AWS typically handles for customers.

---

### Question 18  Cloud Technology and Services

What should customers do to ensure the availability and backup of Amazon EBS volumes?

Create EBS snapshots

Create copies of EBS volumes

Delete the data and create new EBS volumes

Attach new volumes to EC2 instances

#### Explanation

> "Create EBS snapshots" is correct. EBS snapshots are incremental backups that save only the changed blocks since the last snapshot. New volumes created from snapshots are replicas of the original volume.

> "Delete the data and create new EBS volumes" is incorrect because deleting data does not backup volumes.

> "Attach new volumes to EC2 instances" is incorrect because attaching more volumes does not ensure availability if there is no snapshot.

> "Create copies of EBS volumes" is incorrect because EBS volumes cannot be copied, only replicated with snapshots.

---

### Question 19  Security and Compliance

Which AWS service can be used to capture information about inbound and outbound IP traffic on network interfaces in a VPC?

VPC Flow Logs

Site to Site VPN

VPC Peering

Transit Gateway

#### Explanation

> "VPC Flow Logs" is the correct answer. It allows you to capture information about IP traffic going into and out of network interfaces in your VPC.

> "VPC Peering" is incorrect. VPC Peering is used for connecting VPCs and on-premises networks, not capturing traffic flow information.

> "Transit Gateway" is incorrect. Transit Gateway is used for connecting VPCs and on-premises networks, not capturing traffic flow information.

> "Site to Site VPN" is incorrect. Site to Site VPN is used for connecting VPCs and on-premises networks, not capturing traffic flow information.

---

### Question 20  Billing and Pricing and Support

Which Amazon EC2 pricing option provides the largest discounts when you reserve capacity for a 1 or 3 year term?

Reserved Instances

Dedicated Instances

On-Demand Instances

Spot Instances

#### Explanation

> "Reserved Instances" provide the largest discounts compared to On-Demand pricing when you reserve capacity for a 1 or 3 year term.

> "Spot Instances" provide discounts but do not reserve capacity.

> "On-Demand Instances" can be a good option, but Reserved Instance with a term provides a larger discount.

> "Dedicated Instances" provide isolated hardware but do not offer term discounts.

---

### Question 21  Cloud concepts

Which AWS Cloud Adoption Framework perspective focuses on aligning cloud adoption with business goals?

Governance perspective

People perspective

Security perspective

Business perspective

#### Explanation

> "Business perspective" is correct. The AWS Cloud Adoption Framework has a business perspective. This perspective focuses on aligning cloud adoption with business goals and outcomes. The other perspectives do not focus on business goals.

> "Governance perspective" is incorrect as it focuses on establishing frameworks for cost optimization, compliance, and resource consistency. It does not specifically focus on aligning cloud adoption with business goals.

> "People perspective" is incorrect, it focuses on preparing and training people for organizational change related to cloud adoption. It does not focus on aligning cloud adoption with business goals.

> "Security perspective" is incorrect, it focuses on information security, data protection, and access controls. It does not focus on aligning cloud adoption with business goals.

---

### Question 22  Security and Compliance

Which two options should be used to improve the security of your AWS Management Console?

AWS Key Management Service (KMS)

Multi-factor authentication (MFA)

Strong password policies

IAM roles

#### Explanation

> "Strong password policies" and "Multi-factor authentication (MFA)" are correct. They are two methods that can improve the security of the AWS Management Console. Strong passwords make it harder for unauthorized users to guess passwords and gain access. MFA adds an extra layer of protection by requiring a second form of identification beyond just a password.

> "IAM roles" is incorrect as it control permissions but do not directly improve console security.

> "KMS" is incorrect as it encrypts data but does not improve console access.

---

### Question 23  Cloud Technology and Services

Which AWS security service will provide protection against DDoS attacks with both Standard and Advanced Tiers?

AWS Shield

AWS WAF

AWS CloudWatch

Route 53

#### Explanation

> "AWS Shield" is correct. AWS Shield provides protection from and mitigation of Distributed Denial of Service (DDoS) attacks on AWS services. It is always active and monitoring AWS services, providing continual coverage without needing to engage AWS support for assistance should an attack occur. AWS Shield comes into two different service categories: Standard and Advanced.

> "AWS WAF" is incorrect. AWS WAF is a web application firewall that protects web applications against many common attacks.

> "Route 53" is incorrect. Route 53 is the AWS DNS service, but does not provide protection for AWS services from DDoS attacks.

> "AWS CloudWatch" is incorrect. AWS CloudWatch is used to monitor the overall health of all AWS services under your account.

---

### Question 24  Cloud concepts

What benefit does Elasticity provide according to Amazon Web Services (AWS)?

It provisions new servers to meet static demand growth.

It allows systems to scale up or down based on changes in demand.

It minimizes storage needs by reducing logging and auditing activities.

It allows delivery of the same resources to a large pool of customers in a scalable way.

#### Explanation

> "It allows systems to scale up or down based on changes in demand" is correct. The concept of Elasticity allows an application to scale up or down based on demand. For example, the AWS Auto Scaling service provides this capability.

> "It minimizes storage needs by reducing logging and auditing activities" is incorrect. Elasticity does not directly affect storage, cost optimization, or design agility.

> "It allows delivering the same resources to a large pool of customers in a scalable way" is incorrect. This describes multitenancy

> "It provisions new servers to meet static demand growth" is incorrect. This describes scalability.

---

### Question 25  Security and Compliance

Which Amazon Web Services tool allows you to check Amazon EC2 instances for security vulnerabilities by analyzing them against predefined security templates?

Amazon GuardDuty

AWS Config

AWS Trusted Advisor

AWS Inspector

#### Explanation

> The "AWS Inspector" service can analyze the configuration of Amazon EC2 instances by running automated security assessments. It checks the instances against predefined rules and templates to identify potential vulnerabilities. The service does not actively monitor or protect resources like AWS Shield or AWS WAF.

> "AWS Trusted Advisor" is incorrect. AWS Trusted Advisor provides recommendations to help optimize cost, performance, security, and fault tolerance, but does not specifically analyze EC2 instances for vulnerabilities.

> "Amazon GuardDuty" is incorrect. Amazon GuardDuty is a threat detection service that monitors for malicious activity, but does not analyze EC2 configuration for security vulnerabilities.

> "AWS Config is incorrect. AWS Config tracks changes to resources, but does not proactively scan for security vulnerabilities.

---

### Question 26  Cloud Technology and Services

Which Amazon EC2 purchasing option allows you to use your existing per-socket, per-core, or per-VM software licenses like Microsoft Windows Server?

Reserved Instance

On-Demand Instance

Dedicated Host

Dedicated Instance

#### Explanation

> The correct answer is "Dedicated Host". Dedicated Hosts allow you to use your existing per-socket, per-core, or per-VM software licenses. You can launch EC2 instances on physical servers dedicated to your use. This gives you control over instance placement to meet licensing and compliance requirements.

> "Reserved Instance" is incorrect. Reserved Instance does not support using existing licenses.

> "On-Demand" is incorrect. On-Demand does not support using existing licenses.

> "Dedicated Instance" is incorrect. Dedicated Instance does not support using existing licenses.

---

### Question 27  Cloud concepts

What is a key financial benefit of migrating systems hosted in your on-premises data center to AWS?

Opportunity to replace upfront operational expenses (OPEX) with low variable operational expenses (OPEX)

Opportunity to replace upfront capital expenses (CAPEX) with low variable costs

Opportunity to replace variable capital expenses (CAPEX) with low upfront costs

Opportunity to replace variable operational expenses (OPEX) with low upfront capital expenses (CAPEX)

#### Explanation

> "Opportunity to replace upfront capital expenses (CAPEX) with low variable costs" is correct. AWS offers the opportunity to replace the upfront capital expenses (CAPEX) of your on-premises data center with low variable costs. With AWS, businesses no longer need to plan and procure servers months in advance. Instead, they can instantly spin up servers in minutes and pay only for what they use.

> "Opportunity to replace upfront operational expenses (OPEX) with low variable operational expenses (OPEX)" is incorrect because the main benefit of migrating to AWS is replacing upfront capital expenses (CAPEX), not operational expenses (OPEX). While AWS can reduce OPEX as well, the primary benefit is reducing the need for upfront server and infrastructure costs by allowing pay-as-you-go usage.

> "Opportunity to replace variable operational expenses (OPEX) with low upfront capital expenses (CAPEX)" is incorrect because it reverses the concepts of CAPEX and OPEX. CAPEX refers to upfront capital costs like purchasing servers, while OPEX refers to ongoing operating expenses like electricity and staffing. Migrating to AWS reduces CAPEX, not OPEX.

> "Opportunity to replace variable capital expenses (CAPEX) with low upfront costs" is incorrect because it also reverses CAPEX and OPEX. The benefit of AWS is replacing upfront CAPEX with variable usage-based expenses, not replacing OPEX with upfront costs.

---

### Question 28  Security and Compliance

You are starting to move your company’s systems into AWS, and you need to make sure you have a support plan that will assist with integrating many of your common third-party applications into the AWS ecosystem. Which is the lowest-level support plan you would need to purchase for this level of support?

Developer

Integration

Business

Enterprise

#### Explanation

> "Business" is correct. The Business support plan offers third-party software support, including guidance and configuration assistance with AWS interoperability with commonly used applications, operations systems, and platforms.

> "Developer" is incorrect. The Developer support plan does not offer third-party software support.

> "Enterprise" is incorrect. The Enterprise support plan does offer third-party software support, but is a more expensive and high-level plan than the Business plan.

> "Integration" is incorrect. Integration is not a type of AWS support plan.

---

### Question 29  Cloud concepts

What are two benefits of using the Amazon Web Services (AWS) Cloud?

Go global in minutes

100% SLA

Instant migration of any service to the cloud

Fast setup of IT resources

#### Explanation

> "Go global in minutes" is correct. AWS allows you to deploy applications globally very quickly.

> "Fast setup of IT resources" is correct. AWS allows fast provisioning of computing resources on demand.

> "Instant migration of any service to the cloud" is incorrect. Migration services are a paid service not provided with AWS.

> "100% SLA" is incorrect. AWS does not provide 100% SLA.

---

### Question 30  Billing and Pricing and Support

Which of the following AWS services under the Free Tier would have limitations for 750 hours of usage for the month?

Lambda

EC2

RDS Migration Service

CloudWatch

#### Explanation

> "EC2" is correct. The EC2 service allows for 750 hours per month under the Free Tier for either Linux or Windows.

> "Lambda" is incorrect. Lambda under the Free Tier comes with 1,000,000 requests per month and up to 3.2 million seconds of compute time per month.

> "CloudWatch" is incorrect. CloudWatch allows for ten custom metrics and ten alarms, as well as 5GB of log ingestion and storage.

> "RDS Migration Service" is incorrect. The Server Migration Service allows for migrating an unlimited number of servers into AWS from either on-premises or Microsoft Azure cloud.

---

### Question 31  Billing and Pricing and Support

When doing a cost estimation for EC2 services, which other AWS service is a required component?

Lambda

S3

EBS

RDS

#### Explanation

> "EBS" is correct. AWS Elastic Block Store (EBS) serves as the disk for EC2 instances and is an integral component of it.

> "S3" is incorrect. S3 is not an integral component of EC2 and is not required to be used with it.

> "RDS" is incorrect. The AWS Relational Database Service (RDS) is completely separate from EC2 and is not require for its usage.

>"Lambda" is incorrect. Lambda is a stand-alone service that is not integral to EC2.

---

### Question 32  Security and Compliance

Which AWS service allows you to centrally manage security and compliance controls across multiple AWS accounts?

AWS Shield

AWS Organizations

AWS Inspector

AWS Config

#### Explanation

> "AWS Organizations" allows you to centrally manage policies, control access, and enforce security standards across multiple AWS accounts.

> "AWS Config" is incorrect. AWS Config provides resource inventory, configuration history, and configuration change notifications to enable security and governance. However, it does not provide central management across multiple AWS accounts.

> "AWS Inspector" is incorrect. AWS Inspector checks applications for security vulnerabilities and deviations from best practices. However, it does not provide central security management across accounts.

> "AWS Shield" is incorrect. AWS Shield provides DDoS attack protection. However, it is not related to central security management across accounts.

---

### Question 33  Security and Compliance

Which AWS service allows traffic from the internet to access resources in a VPC?

Internet Gateway

Transit Gateway

Network Access Control List (NaCl)

NAT Gateway

#### Explanation

> "Internet Gateway" is correct. This service allows inbound traffic from the internet to access resources in a VPC.

> "Network Access Control List (NaCl)" is incorrect. Network Access Control List (NaCl) does not provide direct internet access to a VPC.

> "NAT Gateway" is incorrect. NAT Gateway does not provide direct internet access to a VPC.

> "Transit Gateway" is incorrect. Transit Gateway does not provide direct internet access to a VPC.

---

### Question 34  Security and Compliance

Which AWS database service encrypts data at rest by default?

Amazon Redshift

Amazon Aurora

Amazon RDS

Amazon DynamoDB

#### Explanation

> "Amazon DynamoDB" is correct, it encrypts data at rest by default.

> "Amazon RDS" is incorrect. Amazon RDS is a database service that require enabling encryption at an additional cost.

> "Amazon Redshift" is incorrect. Amazon Redshift is a database service that require enabling encryption at an additional cost.

> "Amazon Aurora" is incorrect. Amazon Aurora is a database service that require enabling encryption at an additional cost.

---

### Question 35  Billing and Pricing and Support

Which type of AWS Reserved Instance offers the smaller cost savings?

Standard

Convertible

Flexible

Limited

#### Explanation

> "Convertible" is correct. Convertible Reserved Instances offer up to 54 percent savings compared to on-demand pricing, but offer the ability to change the attributes later, as long as the new attributes are equal to or greater than the original Reserve Instance.

> "Limited" is incorrect. Limited is not a type of Reserved Instance.

> "Standard" is incorrect. Standard Reserved Instances offer up to 72 percent savings compared to on-demand pricing.

> "Flexible" is incorrect. Flexible is not a type of Reserved Instance.

---

### Question 36  Cloud Technology and Services

Which Amazon Web Services (AWS) service is designed for time series data analytics?

Amazon Timestream

Amazon ElasticSearch

Amazon Kinesis

Amazon DynamoDB

#### Explanation

> "Amazon Timestream" is the correct answer. It is an AWS service designed specifically for time series data analytics.

> "Amazon ElasticSearch" is incorrect. Amazon ElasticSearch can be used for analytics but is not purpose-built for time series data.

> "Amazon DynamoDB" is incorrect. Amazon DynamoDB can be used for analytics but is not purpose-built for time series data.

> "Amazon Kinesis" is incorrect. Amazon Kinesis can be used for analytics but is not purpose-built for time series data.

---

### Question 37  Cloud Technology and Services

What are two services offered by Amazon Route 53?

Caching

Domain Name System (DNS)

Traffic Flow

Data Storage

#### Explanation

> "Domain Name System (DNS)" and "Traffic Flow" services are correct. Amazon Route 53 offers Domain Name System (DNS) and Traffic Flow services.

> "Data Storage" is incorrect. Data Storage is not services offered by Route 53.

> "Caching" is incorrect. Caching is not services offered by Route 53.

---

### Question 38  Security and Compliance

Which Amazon Web Services service allows you to assign a policy to a user group?

CloudFormation

IAM

S3

EC2

#### Explanation

> The correct answer is "IAM". IAM allows you to create user groups and assign policies to control permissions for those groups.

> "S3" is incorrect. S3 is another AWS service but it cannot be used to assign policies to groups.

> "EC2" is incorrect. EC2 is another AWS service but it cannot be used to assign policies to groups.

> "CloudFormation" is incorrect. CloudFormation is another AWS service but it cannot be used to assign policies to groups.

---

### Question 39  Cloud concepts

What are two benefits of using AWS Elastic Load Balancing?

Pay-per-use pricing

High availability

Reduced management overhead

Automated scaling

#### Explanation

> "High availability" and Automated scaling" are correct. Elastic Load Balancing provides two key benefits: high availability by distributing requests across multiple EC2 instances, and automated scaling by adding or removing EC2 instances based on demand. Load balancers improve availability by routing traffic away from failed or unhealthy instances. The elasticity automatically adds or removes EC2 instances based on traffic levels.

> "Reduced management overhead" is incorrect. While using Elastic Load Balancing can reduce some management overhead compared to managing EC2 instances directly, this is not considered one of the key benefits. The main benefits are around high availability and automated scaling.

> "Pay-per-use pricing" is incorrect. While AWS does provide pay-per-use pricing in general, this is not a specific benefit of using Elastic Load Balancing. The pricing model for ELB is separate from EC2 instance pricing.

---

### Question 40  Cloud Technology and Services

At what level are security groups applied?

VPC

Account

Instance

Subnet

#### Explanation

> "Instance" is correct. Security groups are applied to the actual instance within AWS for maximum flexibility and granularity.

> "VPC" is incorrect. No security controls are applied at the VPC level within AWS—they are all applied to components within the VPC.

> "Subnet" is incorrect. ACLs are applied at the subnet level, but not security groups.

> "Account" is incorrect. Security controls are applied at network and instance levels, not at the account level.

---

### Question 41  Security and Compliance 

Which Amazon Web Services security tool uses an agent installed on Amazon Elastic Compute Cloud instances to check for vulnerabilities or unexpected changes in the application?

Amazon Inspector

Amazon Macie

Amazon Glacier

#### Explanation

> "Amazon Inspector" is correct. It uses an agent installed on Amazon EC2 instances to check for vulnerabilities or unexpected deviations in the application.

> "Amazon Macie" is incorrect. It is a security service that uses machine learning to discover and protect sensitive data.

> "Amazon Glacier" is incorrect. It is a low-cost cloud storage service for data archiving and long-term backup.

---

### Question 42  Cloud Technology and Services

Which Amazon Web Services networking service enables a company to create a private virtual network within AWS?

Amazon Route 53

AWS Direct Connect

AWS Config

Amazon Virtual Private Cloud (Amazon VPC)

#### Explanation

> The correct answer is "Amazon Virtual Private Cloud (Amazon VPC)". Amazon VPC enables companies to create a private virtual network within AWS and have full control over the virtual networking environment.

> "Amazon Route 53" is incorrect. Amazon Route 53 is a AWS services that does not provide private virtual networking capabilities.

> "AWS Direct Connect" is incorrect. AWS Direct Connect is a AWS services that does not provide private virtual networking capabilities.

> "AWS Config" is incorrect. AWS Config is a AWS services that does not provide private virtual networking capabilities.

---

### Question 43  Billing and Pricing and Support

Which Amazon Web Services service can you use to create billing alarms?

AWS Systems Manager

Amazon CloudWatch

Amazon CloudFront

Amazon CloudFormation

#### Explanation

> The correct answer is "Amazon CloudWatch". It can be used to create billing alarms that notify you when your AWS charges exceed thresholds you define. CloudWatch alarms watch a single metric over a time period you specify, and perform one or more actions based on the value of the metric relative to a given threshold over a number of time periods.

> "Amazon CloudFormation" is incorrect. This service is used for provisioning AWS resources

> "Amazon CloudFront" is incorrect. This service is a content delivery network

> "AWS Systems Manager" is incorrect. This service is used to manage AWS resources.

---

### Question 44  Cloud Technology and Services

Which AWS service allows a customer to mirror their corporate network within AWS with the same types of topographies?

CloudFront

AWS VPC

AWS VPN

Route 53

#### Explanation

> "AWS VPC" is correct. The AWS Virtual Private Cloud allows a user to mirror corporate networks with the same types of topographies, subnets, and IP addressing that they currently use.

> "AWS VPN" is incorrect. AWS Virtual Private Network (VPN) allows users to securely tunnel network connections into AWS, but is not a network topography.

> "Route 53" is incorrect. Route 53 is the AWS DNS service, not a network infrastructure service.

> "CloudFront" is incorrect. CloudFront is used for content delivery and is not a network infrastructure service.

---

### Question 45  Cloud Technology and Services

Which feature of the AWS Systems Manager provides an automatically created display of operational data from throughout your account?

Explorer

Insights Dashboard

AWS AppConfig

Inventory

#### Explanation

> "Insights Dashboard" is correct. Insights Dashboard is an automatically created visual dashboard of operational data from throughout your AWS account. As service data is consolidated, the dashboard is automatically populated and organized with common views into CloudTrail data, configurations, inventory, and compliance.

> "AWS AppConfig" is incorrect. AWS AppConfig provides an API and console method for applying configuration changes across AWS services from a centralized service.

> "Explorer" is incorrect. Explorer is a customizable dashboard that provides information on the health of your entire AWS environment.

> "Inventory" is incorrect. Inventory collects information from all services you have provisioned within AWS, including configuration and licensing information. It enables a central location to view and track all assets.

---

### Question 46  Cloud concepts

What AWS services and resources are contained within an Amazon Virtual Private Cloud (VPC)?

Resources across multiple Availability Zones in a single region

Only resources in a single Availability Zone

Resources across multiple AWS regions and your on-premises networks

Resources across multiple regions

#### Explanation

> "Resources across multiple Availability Zones in a single region" is correct. An Amazon VPC spans multiple Availability Zones within a single region. It does not extend across multiple regions. This allows resources in the VPC to maintain high availability by distributing them across multiple AZs in a region.

> "Only resources in a single Availability Zone" is incorrect because a VPC contains resources across multiple Availability Zones within a region, not just a single AZ.

> "Resources across multiple regions" is incorrect because a VPC exists within a single region and does not span multiple regions. Resources in different regions would be completely isolated from each other.

> "Resources across multiple AWS regions and your on-premises networks" is incorrect because a VPC contains resources only within the AWS cloud infrastructure, not on-premises networks. To connect a VPC to an on-premises network requires configuring AWS Direct Connect, VPN, or Transit Gateway connections.

---

### Question 47  Cloud Technology and Services

What Amazon Web Services feature enables fast, secure transfers of files over long distances between your computer and your Amazon S3 storage bucket?

File Transfer

HTTP Transfer

S3 Acceleration

Amazon S3 Transfer Acceleration

#### Explanation

> The "Amazon S3 Transfer Acceleration" feature uses the globally distributed Amazon CloudFront network. This allows fast transfers of files between your computer and an S3 bucket, even over long distances. The data is routed optimally using the CloudFront edge locations.

> "File Transfer" is incorrect because there is no "File Transfer" feature in AWS specifically for transferring files to S3.

> "HTTP Transfer" is incorrect because while S3 uses HTTP for transfers, there is no specific "HTTP Transfer" feature for accelerating transfers. Standard HTTP transfers can be slow over long distances.

> "S3 Acceleration" is a distractor and not an actual AWS feature name. The correct name is S3 Transfer Acceleration.

---

### Question 48  Cloud Technology and Services

Which AWS tool will allow you to execute commands on servers within AWS without having to use SSH or PowerShell?

Distributor

Run Command

AWS AppConfig

CodeDeploy

#### Explanation

> "Run Command" is correct. Run Command provides a way to run commands on servers within AWS without having to actually access them via SSH or PowerShell.

> "Distributor" is incorrect. Distributor allows for the central storage, distribution, and installation of software packages to instances within AWS, including software agents.

> "CodeDeploy" is incorrect. AWS CodeDeploy is a managed deployment service that can deploy code fully across AWS services or on-premises servers.

> "AWS AppConfig" is incorrect. AWS AppConfig provides an API and console method for applying configuration changes across AWS services from a centralized service.

---

### Question 49  Cloud Technology and Services

Amazon CloudFront allows for ultra-low-latency data transmissions. Which AWS technology does CloudFront leverage to achieve this?

Regions

ELB

Edge locations

Availability Zones

#### Explanation

> "Edge locations" is correct. To provide optimal responsiveness for customers, AWS maintains a network of Edge locations throughout the world to provide ultra-low-latency access to data. These locations are geographically dispersed throughout the world to be close to customers and organizations in order to provide the fastest response times. Unlike regular AWS regions and Availability Zones, Edge locations are optimized to perform a narrow set of tasks and duties, allowing them to be optimally tuned and maintained for their intended focus, without being burdened by the full range of AWS services.

> "Regions" is incorrect. While regions can be chosen to move data closer to customers, they are not optimized in the way Edge locations are for ultra-low latency.

> "Availability Zones" is incorrect. Availability Zones provide for redundancy and scalability within a region and will not serve the same purpose as Edge locations for ultra-low latency.

> "ELB" is incorrect. ELB is designed for redundant applications and optimizing resources across multiple environments, but is not designed for ultra-low latency like Edge locations.

---

### Question 50  Cloud Technology and Services

Which Amazon Web Services service is designed for time series data and operational analytics?

Amazon Timestream

Amazon ElasticSearch

Amazon Kinesis

Amazon DynamoDB

#### Explanation

> "Amazon Timestream" is the correct answer because it is a purpose-built time series database service designed for efficiently storing and analyzing time series data from sources like IoT devices, application logs, etc. It has native support for time series data types and analytics.

> "Amazon ElasticSearch" is incorrect because it is a search and analytics engine, not specifically designed for time series data. While it can ingest time series data, it does not have native support for time series specific features like temporal aggregations.

> "Amazon DynamoDB" is incorrect because it is a key-value and document database, focused on performance at any scale. It is not optimized for time series workloads that require ordering and analyzing data over time.

> "Amazon Kinesis" is incorrect because it is a platform for streaming data on AWS, useful for real-time data intake and processing. However, it does not have built-in support for managing and querying time series data over longer periods.

---

### Question 51  Security and Compliance

Which Amazon Web Services service is regional?

Amazon CloudFront

AWS Identity and Access Management (IAM)

Amazon Elastic File System (EFS)

Amazon Route 53

#### Explanation

> "Amazon Elastic File System (EFS)" is correct. EFS is a regional service.

> "AWS Identity and Access Management (IAM)" is incorrect. AWS Identity and Access Management (IAM) is a global service.

> "Amazon Route 53" is incorrect. Amazon Route 53 is a global service.

> "Amazon CloudFront" is incorrect. Amazon CloudFront is a global service.

---

### Question 52  Billing and Pricing and Support

Which Amazon EC2 pricing model allows customers to use existing server-bound software licenses?

On-Demand Instances

Spot Instances

Dedicated Hosts

Reserved Instances

#### Explanation

> "Dedicated Hosts" is correct. It allow customers to use their existing server-bound software licenses by dedicating a physical server to their use.

> "Reserved Instances" provide a discount compared to On-Demand pricing but do not allow using existing licenses.

> "Spot Instances" are a cost-effective option but do not guarantee availability or allow using existing licenses.

> "On-Demand Instances" are billed per second of usage but do not allow using existing licenses.

---

### Question 53  Security and Compliance 

Which AWS service allows internet traffic to access resources in a VPC?

Internet Gateway

Network Access Control List (NaCl)

NAT Gateway

#### Explanation

> "Internet Gateway" is correct. It allows inbound internet traffic to access resources in a VPC.

> The "NAT Gateway" is incorrect. It allows outbound internet access for resources in private subnets, but does not allow inbound traffic.

> "Network Access Control List (NaCl)" is incorrect. They control traffic at the subnet level but do not allow internet access.

---

### Question 54  Cloud concepts

Which characteristic of the AWS Cloud enables companies to innovate faster?

High Availability

Cost Savings

Security

Agility

#### Explanation

> "Agility" is correct. Agility enables companies to innovate faster on AWS by allowing them to experiment and iterate quickly.

> "High Availability" is incorrect. High Availability is another benefits of AWS Cloud, but not directly related to innovating faster.

> "Security" is incorrect. Security is another benefits of AWS Cloud, but not directly related to innovating faster.

> "Cost Savings" is incorrect. Cost Savings is another benefits of AWS Cloud, but not directly related to innovating faster.

---

### Question 55  Security and Compliance

Where can a user find the policies and rules about prohibited actions when using AWS infrastructure and services?

AWS Trusted Advisor

AWS Acceptable Use Policy

AWS Identity and Access Management (IAM)

AWS Billing Console

#### Explanation

> "AWS Acceptable Use Policy" is correct. It provides the rules and policies about prohibited actions when using AWS infrastructure and services.

> "AWS Trusted Advisor" is incorrect, it will only provide best policies information.

> "AWS Identity and Access Management (IAM)" is incorrect, it will provide user access controls.

> "AWS Billing Console" is incorrect. Billing will not provide the policies on prohibited actions.

---

### Question 56  Billing and Pricing and Support

Which of the following statements best explains AWS Service Quotas?

Service Quotas only apply to compute and storage instances across AWS.

Service Quotas is specific to a region and will place default limits on the number of specific types of resources you can allocate.

Service Quotas sets limitations on the amount of AWS services that may be allocated across AWS for a specific account.

Service Quotas places limits on AWS Services within an account but can always be increased for a fee specific to that service.

#### Explanation

> "Service Quotas is specific to a region and will place default limits on the number of specific types of resources you can allocate." is correct. In order to protect the availability for all users in AWS, Service Quotas (formerly called Limits) applies to each service. These quotas are specific to a region and will place a limit on the number of specific types of resources you can allocate by default.

> "Service Quotas sets limitations on the amount of AWS services that may be allocated across AWS for a specific account." is incorrect. While Service Quotas does set limitations on AWS services, this answer is incorrect, as it is does not specify that they are implemented at the region level.

> "Service Quotas only apply to compute and storage instances across AWS." is incorrect. AWS Service Quotas applies to most AWS services, not just compute and storage instances.

> "Service Quotas places limits on AWS Services within an account but can always be increased for a fee specific to that service." is incorrect. AWS Service Quotas can usually be automatically increased upon request. Some requests require AWS personnel to approve the increase, but they are not done on a fee basis.

---

### Question 57  Security and Compliance

Which AWS service can be used to track user activity in AWS?

Amazon Beanstalk

AWS CloudWatch

AWS CloudTrail

Amazon Elastic Cache

#### Explanation

> "AWS CloudTrail" is the correct answer because it is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account. It records AWS API calls for your account and delivers log files to you.

> "Amazon Elastic Cache" is incorrect, it is a caching service.

> "Amazon Beanstalk" is incorrect, it is a platform service.

> "AWS CloudWatch" is incorrect, it monitors resources and applications.

---

### Question 58  Cloud Technology and Services

You update the CIDR block on one of your subnets from /16 to /24. What is the resulting impact on the subnet?

The subnet is opened to the public Internet.

The number of IP addresses available within it decreases.

The number of IP addresses available within it increases.

The use of IPv6 addresses is permitted.

#### Explanation

> "The number of IP addresses available within it decreases." is correct. AWS supports CIDR blocks ranging from /16 to /28 for subnets. The larger the number, the smaller the number of available IP address within the subnet.

> "The number of IP addresses available within it increases." is incorrect. By moving to a larger number of a CIDR block, you decrease the number of IP addresses available.

> "The use of IPv6 addresses is permitted." is incorrect. The CIDR block has no bearing on IPv6 addresses or their availability.

> "The subnet is opened to the public Internet." is incorrect. The CIDR block pertains only to IP addresses and has no bearing on any security policies.

---

### Question 59  Cloud concepts

Which concept focuses on building applications from small, loosely coupled components?

Elasticity

Availability

Microservices

Scalability

#### Explanation

> "Microservices" is correct. Microservices architecture builds applications from small, modular components that work together. This provides agility and flexibility.

> "Elasticity" is incorrect. Elasticity is a benefit of cloud use, but does not directly relate to component-based application design.

> "Scalability" is incorrect. Scalability is a benefit of cloud use, but does not directly relate to component-based application design.

> "Availability" is incorrect. Availability is a benefit of cloud use, but does not directly relate to component-based application design.

---

### Question 60  Security and Compliance

Which Amazon Web Services tool can identify the user that terminated an Amazon EC2 instance?

Amazon Inspector

AWS Trusted Advisor

AWS Config

AWS CloudTrail

#### Explanation

> "AWS CloudTrail" records API calls made on your account, including calls to terminate EC2 instances. It captures information like the identity of the API caller, time of API call, source IP address etc. So CloudTrail can be used to identify the user that terminated an EC2 instance.

> "AWS Trusted Advisor" is incorrect, it does not identify users who made API calls. It provides recommendations to help optimize cost, performance, security, and fault tolerance, but does not log API calls.

> "AWS Config" is incorrect, it records configuration changes to AWS resources, but does not log API calls or capture the identity of the caller. So it cannot identify who terminated an EC2 instance.

> "Amazon Inspector" is incorrect, it is a security assessment service that checks for vulnerabilities and deviations from best practices in EC2 instances. It does not log API calls or capture the caller identity.

---

### Question 61  Security and Compliance

Which report, offered in CSV format, can be downloaded to audit your list of users, their access permissions, and other information about logins?

User report

Credential report

User audit

IAM report

#### Explanation

> "Credential report" is correct. The credential report is offered in CSV download and will contain what users you have, what access they have, when they last logged in, and their status of being issued keys and when they were last rotated.

> "User report" is incorrect. User report is a similar-sounding terms, but credential report is the correct name.

> "User audit" is incorrect. User audit is a similar-sounding terms, but credential report is the correct name.

> "IAM report" is incorrect. IAM report is a similar-sounding terms, but credential report is the correct name.

---

### Question 62  Cloud Technology and Services

Which Amazon Web Services feature allows customers to create a copy of their Lightsail instance in EC2?

LightSail Copy

LightSail-EC2 snapshot

LightSail Backup

Upgrade to EC2

#### Explanation

> "Upgrade to EC2" is correct. The 'Upgrade to EC2' feature allows Lightsail customers to create a copy of their Lightsail instance in EC2.

> "LightSail Backup" is incorrect because this feature allows you to create backups of your Lightsail instances, but does not allow you to create a copy in EC2.

> "LightSail Copy" is incorrect because this is not a valid Lightsail or EC2 feature. There is no ability to directly copy a Lightsail instance within the Lightsail service.

> "LightSail-EC2 snapshot" is incorrect because you cannot directly create an EC2 instance from a Lightsail snapshot. The snapshot would first need to be exported to create an image, and then launched as an EC2 instance.

---

### Question 63  Security and Compliance

Which Amazon Web Services tool can be used to monitor, store and access log files created by EC2 instances and on-premises servers?

Amazon CloudWatch Logs

AWS Global Accelerator

AWS Organization

Amazon CloudFront

#### Explanation

> "Amazon CloudWatch Logs" is correct. It can be used to monitor, store, and access log files generated by EC2 instances and on-premises servers. It allows you to centralize logs for monitoring and analysis.

> "AWS Organization" is incorrect. AWS Organization is a different AWS service that does not provide log management capabilities.

> "Amazon CloudFront" is incorrect. Amazon CloudFront is a different AWS service that does not provide log management capabilities.

> "AWS Global Accelerator" is incorrect. AWS Global Accelerator is a different AWS service that does not provide log management capabilities.

---

### Question 64  Cloud concepts

Which cloud deployment model involves using public cloud resources in addition to keeping some servers on-premises?

Private cloud

Community cloud

Hybrid cloud

Public cloud

#### Explanation

> "A hybrid cloud model" is correct. It involves using public cloud resources while still maintaining some on-premises infrastructure.

> "Private cloud" is incorrect as it uses internal resources only.

> "Public cloud" is incorrect as it is fully hosted by a cloud provider.

> "Community cloud" is incorrect as it is shared by organizations with similar requirements.

---

### Question 65  Cloud Technology and Services

Which feature of the AWS Systems Manager provides a way to store and push software packages out to your AWS instances?

AWS AppConfig

Explorer

Inventory

Distributor

#### Explanation

> "Distributor" is correct. Distributor allows for the central storage, distribution, and installation of software packages to instances within AWS, including software agents. You can use Distributor to push out software files and then use Run Command to automate installation and configuration of them.

> "AWS AppConfig" is incorrect. AWS AppConfig provides an API and console method for applying configuration changes across AWS services from a centralized service.

> "Explorer" is incorrect. Explorer is a customizable dashboard that provides information on the health of your entire AWS environment.

> "Inventory" is incorrect. Inventory collects information from all services you have provisioned within AWS, including configuration and licensing information. It enables a central location to view and track all assets.
