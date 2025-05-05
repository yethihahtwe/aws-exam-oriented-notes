# LinkedIn Practice Exam 02

### Question 1  Billing and Pricing and Support

Which AWS tool can help identify unused Amazon EC2 instances to reduce costs?

AWS Cost Explorer

AWS Config

AWS Budgets

AWS Trusted Advisor

#### Explanation

> "AWS Trusted Advisor" is correct. This tool can identify unused Amazon EC2 instances that can be terminated to reduce costs.

> "AWS Budgets" is incorrect. This tool analyzes spend but does not identify unused resources.

> "AWSCost Explorer" is incorrect. This tool analyzes spend but does not identify unused resources.

> "AWSConfig" is incorrect. This tool tracks resource changes but does not flag unused resources.

---

### Question 2  Cloud Concepts

How does using managed services like RDS help companies focus on applications rather than infrastructure?

The provider handles maintenance tasks.

Managed services are self-healing.

Managed services eliminate infrastructure costs.

Managed services have unlimited scale.

#### Explanation

> "The provider handles maintenance tasks" is correct. Managed services like RDS handle infrastructure maintenance tasks on behalf of customers. This allows companies to focus on their applications and business logic rather than infrastructure management.

> "Managed services are self-healing" is incorrect. This is not the primary benefit of managed services. While managed services like RDS do provide self-healing capabilities like auto-scaling and fault tolerance, the main value is offloading infrastructure maintenance and management.

> "Managed services have unlimited scale" is incorrect. This is not the primary benefit. While managed services can scale to meet demand, the core value is removing the burden of maintenance and management tasks.

> "Managed services eliminate infrastructure costs" is incorrect. Customers still pay for the managed infrastructure and services consumed. The benefit is not eliminating costs but reducing management overhead.

---

### Question 3  Cloud Concepts

Which concept will articulate the specific requirements between the cloud user and provider as far as promised performance, uptime, and responsiveness for services?

Contract

Governance

Service level agreement (SLA)

Auditability

#### Explanation

> "Service level agreement (SLA)" is correct. Whereas a contract will spell out the general terms and costs for services, the SLA is where the real meat of the business relationship and concrete requirements come into play. The SLA spells out in clear terms the minimum requirements for uptime, availability, processes, customer service and support, security controls and requirements, auditing and reporting, and potentially many other areas that will define the business relationship and the success of it.

> "Contract" is incorrect. The contract will spell out the general terms for costs of services and duration of service.

> "Governance" is incorrect. Governance at its core involves assigning jobs, tasks, roles, and responsibilities and ensuring they are satisfactorily performed. This differs from an SLA, as governance is within the cloud user.

> "Auditability" is incorrect. Auditability pertains to the ability to verify that regulatory, legal, and policy requirements are being correctly followed and implemented.

---

### Question 4  Cloud Technology and Services

In which two locations can Amazon EC2 Auto Scaling launch resources?

Multiple availability zones across multiple regions

Everywhere, there are no constraints

Multiple availability zones within a region

Only in one single availability zone

#### Explanation

> "Multiple availability zones within a region" and "Multiple availability zones across multiple regions" are correct. Amazon EC2 Auto Scaling can launch resources in multiple availability zones within a region and across multiple regions. It cannot launch resources in only one availability zone, and there are constraints on where it can launch.

> "Only in one single availability zone" is incorrect because Amazon EC2 Auto Scaling can launch resources across multiple availability zones, not just in a single AZ. Launching in a single AZ would limit high availability.

> "Everywhere, there are no constraints" is incorrect because there are constraints on where Amazon EC2 Auto Scaling can launch resources. It can only launch in the regions and AZs enabled for your account. It cannot launch resources everywhere without constraints.

---

### Question 5  Security and Compliance

You have an application installed on an Amazon EC2 instance. You want to restrict access to the application for different users. Which of the following methods can help you achieve this?

Detach the primary network interface from the EC2 instance and attach it to another instance.

Configure multiple network interfaces (ENIs) with separate IP addresses and security groups.

Enable antivirus on your EC2 instance.

Configure the firewall inside the EC2 instance.

#### Explanation

> "Configure multiple network interfaces (ENIs) with separate IP addresses and security groups" is correct. Multiple ENIs with separate IP addresses and security groups allows restricting access for different users. The primary ENI cannot be detached from an instance.

> "Detach the primary network interface from the EC2 instance and attach it to another instance" is incorrect because the primary network interface cannot be detached from an EC2 instance. The primary ENI is attached during instance launch and remains associated throughout the instance lifecycle.

> "Configure the firewall inside the EC2 instance" is incorrect because configuring a firewall inside the EC2 instance would not restrict access for different users connecting externally. The firewall needs to be implemented at the network level, not inside the instance itself.

> "Enable antivirus on your EC2 instance" is incorrect because enabling antivirus on the EC2 instance does not restrict network access. Antivirus is used to detect and remove malware, not control external user access.

---

### Question 6  Security and Compliance

An organization runs several Amazon EC2 instances inside an Amazon VPC using three subnets - one for Development, one for Test, and one for Production. The Security team wants to restrict communication between the EC2 instances using Security Groups. Which of the following statements is true about changing Security Groups associated with the instances in this scenario?

You can change only the Default Security Group.

You can change a Security Group associated with an instance if the instance is in the running state.

You can change a Security Group associated with an instance if the instance is in the hibernate state.

You can change a Security Group only if there are no instances associated with it.

#### Explanation

> "You can change a Security Group associated with an instance if the instance is in the running state" is correct. According to AWS documentation, you can change the Security Groups associated with an EC2 instance when the instance is in the running or stopped state.

> "You can change a Security Group associated with an instance if the instance is in the hibernate state" is incorrect because you cannot change the security group of an instance that is in hibernate state. The instance needs to be in running or stopped state.

> "You can change a Security Group only if there are no instances associated with it" is incorrect because you can change the security group of an instance without changing the security group itself or removing all instances from it first.

> "You can change only the Default Security Group" is incorrect because you are not restricted to only changing the default security group of an instance. You can change it to any security group as needed.

---

### Question 7  Cloud Technology and Services

A website wants to serve content to users in their native language based on the user's location. Which Amazon Web Services feature provides location-based web personalization using geolocation headers?

Amazon CloudFront

AWS Elastic Beanstalk

Amazon EC2

AWS Global Accelerator

#### Explanation

> "Amazon CloudFront" supports country-level location-based web content personalization using a feature called Geolocation Headers. CloudFront can be configured to add geolocation headers that provide the viewer's country, region, city, postal code, latitude, and longitude based on their IP address. This allows for more granular control of cache behavior and origin access policies based on the viewer's location.

> "Amazon EC2" is incorrect. Amazon EC2 provides scalable compute capacity in the cloud but does not have built-in support for location-based content delivery or personalization. EC2 instances can be used to host web applications and websites, but additional services would be needed to implement geolocation-based functionality.

> "AWS Global Accelerator" is incorrect. AWS Global Accelerator improves availability and performance for users by routing traffic to optimal endpoints over the AWS global network. It does not provide geolocation headers or location-based personalization features.

> "AWS Elastic Beanstalk" is incorrect. AWS Elastic Beanstalk provides an easy way to deploy and scale web applications in the cloud. It handles provisioning and configuration of resources like EC2 and load balancing automatically. However, Elastic Beanstalk itself does not include geolocation or location-based personalization capabilities. Additional services would need to be leveraged.

---

### Question 8  Security and Compliance

What are two true statements about AWS Secrets Manager?

It replaces hardcoding authentication information in code.

It encrypts data at rest.

It provides free storage.

It replaces IAM users and roles.

It retrieves authentication information from a central repository using an API call.

#### Explanation

> "It replaces hardcoding authentication information in code" and "It retrieves authentication information from a central repository using an API call" are correct. AWS Secrets Manager allows replacing hardcoding authentication information in code with an API call. The API call retrieves the secret from Secrets Manager. This protects the secret from being compromised.

> "It replaces IAM users and roles" is incorrect. It does not replace IAM users and roles. It is used to store secrets like passwords, API keys, and tokens. IAM users and roles are still required for providing access.

> "It encrypts data at rest" is incorrect. It does not encrypt data at rest by default. Encryption must be enabled on each secret.

> "It provides free storage" is incorrect. It does not provide free storage. Usage incurs standard charges like other AWS services.

---

### Question 9  Billing and Pricing and Support

Which type of AWS Budget is used for planning what your ceiling for spending on a particular service will be?

Usage Budgets

Cost Budgets

Cost Savings Budgets

Savings Plans Utilization Budgets

#### Explanation

> "Cost Budgets" is correct. Cost Budgets allow for planning what your ceiling will be for spending on a particular service.

> "Usage Budgets" is incorrect. Usage Budgets allow for planning how much actual usage of a particular service you want to use.

> "Cost Savings Budgets" is incorrect. Cost Savings Budgets is not a type of AWS Budgets.

> "Savings Plans Utilization Budgets" is incorrect. Savings Plans Utilization Budgets track usage of savings plans based on utilization and trigger alerts when falling under the thresholds.

---

### Question 10  Security and Compliance

What Amazon Web Services service would you use to send notifications based on Amazon CloudWatch alarms?

Amazon Simple Notification Service (Amazon SNS)

AWS Trusted Advisor

AWS CloudTrail

Amazon Route 53

#### Explanation

> "Amazon Simple Notification Service (Amazon SNS)" is the correct service to use for sending notifications based on Amazon CloudWatch alarms. SNS allows you to configure alarms in CloudWatch to trigger notifications to endpoints such as email, SMS, and HTTP. The other options listed are not notification services.

> "AWS CloudTrail" is incorrect because it is a service that records API calls made on your AWS account and delivers log files to you. It does not have notification capabilities based on CloudWatch alarms.

> "AWS Trusted Advisor" is incorrect because it provides best practice recommendations for optimizing your AWS infrastructure. It does not provide notifications based on CloudWatch alarms.

> "Amazon Route 53" is incorrect because it is a highly available and scalable Domain Name System (DNS) service. It is used to route end users to internet applications by translating names like www.example.com into the numeric IP addresses like 192.0.2.1 that computers use to connect to each other. It is not a notification service.

---

### Question 11  Cloud Technology and Services

Which AWS service is a Desktop as a Service (DaaS) offering?

WorkLink

AWS VDI

WorkSpaces

AWS OfficeSpace

#### Explanation

> "WorkSpaces" is correct. Amazon WorkSpaces is a DaaS implementation that is built, maintained, configured, and secured through AWS as a managed service. WorkSpaces offers both Windows and Linux desktop solutions that can be quickly deployed anywhere throughout the AWS global infrastructure.

> "WorkLink" is incorrect. WorkLink offers users the ability to access internal applications through the use of mobile devices.

> "AWS VDI" is incorrect. AWS VDI is not an AWS service offering. VDI technologies are offered through AWS WorkSpaces.

> "AWS OfficeSpace" is incorrect. AWS OfficeSpace is not an AWS service offering.

---

### Question 12  Billing and Pricing and Support

In order to better track costs within the organization, you notice that your account administrator has added in the ability to sort by options such as “user:ProjectName.” What is this an example of?

Cost Containers

Cost Categories

Cost Allocation Tags

Cost Metadata

#### Explanation

> "Cost Allocation Tags" is correct. Cost Allocation Tags are metadata assigned to AWS resources in the form of a key and a value. These can be used to allow an account to quickly track costs associated with resources through highly granular views. Cost Allocation Tags are either generated automatically by AWS or are created by users.

> "Cost Categories" is incorrect. Cost Categories are also used to make granular reports within the Billing Dashboard, but the format with a key and value makes Cost Allocation Tags correct.

> "Cost Metadata" is incorrect. While Cost Allocation Tags are metadata, the term Cost Metadata is incorrect.

> "Cost Containers" is incorrect. Cost Containers are not a term that is used within the AWS Billing Dashboard but is similar to the correct answer.

---

### Question 13  Security and Compliance

On which AWS services do customers need to patch the operating systems?

AWS Fargate

Amazon DynamoDB

Amazon EC2

Amazon Lambda

#### Explanation

> "Amazon EC2" is correct. Customers are responsible for patching operating systems on Amazon EC2 instances.

> "AWS Fargate" is incorrect. AWS Fargate is fully managed by AWS so customers do not need to patch the underlying operating systems.

> "Amazon DynamoDB" is incorrect. Amazon DynamoDB is fully managed by AWS so customers do not need to patch the underlying operating systems.

> "Amazon Lambda" is incorrect. Amazon Lambda is fully managed by AWS so customers do not need to patch the underlying operating systems.

---

### Question 14  Cloud Concepts

According to the AWS Shared Responsibility Model, who is responsible for managing the operating system and configuration of the Amazon RDS database instances?

AWS

The customer

It is shared

Explanation

> "The customer" is correct. Amazon RDS is a managed service, so AWS handles the maintenance and management of the underlying cloud database software. However, the customer is responsible for managing the operating system and configuration of their RDS instances according to the Shared Responsibility Model.

> "AWS" is incorrect. AWS is not responsible for managing the operating system or configuration of the Amazon RDS database instances. This is the customer's responsibility.

> "It is shared" is incorrect. The customer is responsible for managing the operating system and configuration of their RDS instances according to the Shared Responsibility Model.

---

### Question 15  Cloud Concepts

What are two benefits of deploying a relational database on Amazon RDS instead of Amazon EC2?

Unlimited resources

Software patching

Automatic backup

Cost savings

#### Explanation

> "Automatic backup" and software patching is correct. Deploying a relational database on Amazon RDS provides automatic backups and software patching, which saves time and effort compared to managing these tasks manually when hosting a database on Amazon EC2. Amazon RDS automates backups, software patching, and other administrative tasks.

> "Cost savings" is incorrect. Amazon RDS can be more expensive than self-managed databases.

> "Unlimited resources" is incorrect. Amazon RDS is limited to the resources and features offered by AWS.

---

### Question 16  Security and Compliance
A company migrated their application servers to Amazon EC2 instances. The IT Manager wants to know about upcoming AWS scheduled maintenance activities that could impact the EC2 instances. Which AWS service provides alerts about these activities?

AWS Service Health Dashboard

AWS Personal Health Dashboard

AWS Organizations

AWS Trusted Advisor

#### Explanation

> "AWS Personal Health Dashboard" is correct. It provides alerts for scheduled AWS maintenance activities that could impact resources in your account, like EC2 instances. It sends emails and notifications.

> "AWS Organizations" is incorrect, AWS Organizations does not provide alerts for account-specific scheduled maintenance.

> "AWS Trusted Advisor" is incorrect, AWS Trusted Advisor does not provide alerts for account-specific scheduled maintenance.

> "AWS Service Health Dashboard" is incorrect, AWS Service Health Dashboard does not provide alerts for account-specific scheduled maintenance.

---

### Question 17  Security and Compliance

A user was given an access key ID and secret access key to make API calls to AWS. The user has forgotten the credentials. How can new credentials be generated for the user?

Use the 'Forgot Password' option

Create a new access key by logging in to the AWS Management Console as the root user

Contact AWS Support to retrieve the forgotten Secret Access Key.

Delete the user and recreate them to get new credentials.

#### Explanation

> "Create a new access key by logging in to the AWS Management Console as the root user" is correct because a new access key can be created by logging into the AWS Management Console as the root user and going to the Security Credentials page.

> "Use the 'Forgot Password' option" is incorrect because there is no 'Forgot Password' option for access keys.

> "Contact AWS Support to retrieve the forgotten Secret Access Key" is incorrect as new credentials can be generated without contacting AWS Support.

> "Delete the user and recreate them to get new credentials" is incorrect as new credentials can be generated.

---

### Question 18  Cloud Concepts

Which key cloud concept pertains to the ability to reuse components of an application or service?

Reusability

Interoperability

Portability

Modularization

#### Explanation

> "Reusability" is correct. Reusability refers to the ability to use components of an application or service in multiple contexts or projects with little or no modification. As a result, resources are leveraged across different applications which streamlines development and improves consistency. It also enhances productivity, reduces costs and accelerates time to market.

> "Interoperability" is incorrect. Interoperability is the ability of different systems, applications, or components to work together or share/exchange information regardless of platforms or providers. The focus of interoperability is communication and compatibility not reusing the same components within or across applications.

> "Modularization" is incorrect. Modularization is the principle of breaking down an application into smaller independent modules or components, often to improve maintainability and scalability.

> "Portability" is incorrect. Portability is the ability to move applications or components from one environment or cloud provider to another with minimal modification not reusing components across applications.

---

### Question 19  Cloud Technology and Services

AWS offers a variety of different EC2 instance types that are optimized for different types of focused usage. Which of the following is not an optimized instance type under EC2?

Storage optimized

Network optimized

Memory optimized

Compute optimized

#### Explanation

> "Network optimized" is correct. EC2 offers optimized instance types for compute, memory, and storage, but not for network.

> "Storage optimized is incorrect. Storage optimized is an optimized instance types offered by AWS EC2.

> "Compute optimized is incorrect. Compute optimized is an optimized instance types offered by AWS EC2.

> "Memory optimized is incorrect. Memory optimized is an optimized instance types offered by AWS EC2.

---

### Question 20  Cloud Technology and Services

Which service allows users to quickly get configured vendor systems up and running quickly within AWS?

AWS Marketplace

AWS Machine Images

AWS Lambda

AWS EC2

#### Explanation

> "AWS Marketplace" is correct. AWS Marketplace offers images from many vendors for their specific products. For example, you will find images from companies such as SAP that will offer fully configured images for their software platforms that are ready to deploy. When you select an image from the Marketplace, you may have the option of a trial period to see if it will work for your needs before you incur costs from the vendor.

> "AWS Machine Images" is incorrect. AWS Machine Images is an umbrella that includes the Marketplace, but Marketplace is the better answer, as it is focused on vendor solutions that are configured and ready to run within the AWS infrastructure.

> "AWS EC2" is incorrect. EC2 offers virtual machines that will require configuration and administration by the user and not configured solutions provided by vendors.

> "AWS Lambda" is incorrect. AWS Lambda allows for code to be executed without the use of underlying servers, but is not a vendor-supported solution for quick deployment within AWS.

---

### Question 21  Security and Compliance

A large company needs to allow its employees to access Linux desktops remotely from any location. Which Amazon Web Services product can be used for this?

Amazon Cognito

Amazon WorkLink

Amazon AppStream 2.0

Amazon WorkSpaces

#### Explanation

> "Amazon WorkSpaces" is correct. It provides a managed service for virtual desktops that employees can access remotely. It supports both Windows and Linux desktops for many users.

> "Amazon Cognito" is incorrect, it controls access to AWS resources from an application.

> "Amazon AppStream 2.0" is incorrect, it provides access to applications or temporary desktops remotely.

> "Amazon WorkLink" is incorrect, it allows internal employees to securely access internal websites and apps on their phones.

---

### Question 22  Billing and Pricing and Support

Which AWS tool can help identify potential cost savings by looking for idle and underutilized resources?

AWS Cost Explorer

AWS Config

AWS Budgets

AWS Trusted Advisor

#### Explanation

> "AWS Trusted Advisor" is correct. This tool can identify opportunities to reduce costs by removing unused and underutilized resources.

> "AWS Cost Explorer" is incorrect. This tool analyzes spend.

> "AWS Budgets" is incorrect. This tool analyzes spend.

> "AWS Config" is incorrect. This tool tracks resource changes.

---

### Question 23  Cloud Concepts

How does using cloud computing help companies focus on innovation rather than infrastructure?

The cloud provider handles routine IT tasks.

Resources can be provisioned on demand.

The cloud automates all processes.

There are no infrastructure costs.

#### Explanation

> "The cloud provider handles routine IT tasks" is correct. Cloud providers handle infrastructure maintenance like backups, patching, upgrades for customers. This allows companies to spend time on innovation rather than IT management.

> "Resources can be provisioned on demand" is incorrect. While the ability to provision resources on demand is a benefit of the cloud, and it does allow flexibility, this does not allow companies to spend more time focusing on innovation.

> "There are no infrastructure costs" is incorrect. The cloud does not eliminate infrastructure costs entirely, it shifts some of the costs from capital expenditures to operating expenditures. The cloud provider handles the infrastructure, but there are still ongoing costs associated with using it.

> "The cloud automates all processes" is incorrect. The cloud provides automation capabilities through services like auto-scaling, load balancing, etc. However, it does not automate all IT processes. There is still a need for management, monitoring, optimization, and innovation by the customer. The automation helps improve efficiency but does not replace the need for IT teams.

---

### Question 24  Cloud Technology and Services

A business analyst wants to move away from creating complex database queries and static spreadsheets when generating regular reports for high-level management. They would like to publish insightful, graphically appealing reports with interactive dashboards. Which AWS service can help them accomplish this?

Amazon Athena with Amazon Glue

Amazon QuickSight

Amazon Redshift

Amazon CloudWatch

#### Explanation

> "Amazon QuickSight" is the right service for this scenario. It is a fully managed business intelligence service that allows users to create interactive dashboards and generate insights through machine learning.

> "Amazon Redshift" is incorrect because Amazon Redshift is a data warehouse service and does not provide interactive dashboards.

> "Amazon CloudWatch" is incorrect because CloudWatch is for monitoring AWS resources, not building dashboards.

> "Amazon Athena with Amazon Glue" is incorrect because Athena is a query service, not a dashboard and reporting tool.

---

### Question 25  Billing and Pricing and Support

Which AWS service provides offerings to help achieve outcomes related to adopting AWS Cloud through paid engagements?

AWS Technical Account Manager

Concierge Support

AWS Professional Services

AWS Enterprise Support

#### Explanation

> "AWS Professional Services" offers paid services to help achieve outcomes when adopting AWS Cloud. It provides best practices and activities based on experience helping customers adopt AWS.

> "AWS Enterprise Support" is incorrect. AWS Enterprise provides technical support, but does not directly help adopt AWS..

> "Concierge Support" is incorrect. Concierge Support provides technical support, but does not directly help adopt AWS..

> "AWS Technical Account Manager" is incorrect.AWS Technical Account Manager provides technical support, but does not directly help adopt AWS.

---

### Question 26  Cloud Concepts

How does using multiple Availability Zones improve application availability?

It provides isolation for extra security.

Different services can be placed in different zones.

It allows load balancing across zones.

Data is replicated across zones.

#### Explanation

> "It allows load balancing across zones" is correct. Using multiple AZs improves availability primarily by enabling load balancing and redundancy across physically separate data centers. This ensures that if one AZ fails, the application can continue to operate from another AZ protecting against single point of failure. This minimizes downtime and maintains service continuity.

> "Data is replicated across zones" is incorrect. While data replication across AZ’s, such as synchronous replication, in databases is important for data durability and disaster recovery, it is not the primary method to improve application availability.

> "Different services can be placed in different zones" is incorrect. Placing different services in different AZ’s does not inherently improve an application’s availability because there is no redundancy across multiple AZ’s.

> "It provides isolation for extra security" is incorrect. While AZs are isolated to enhance fault tolerance and can help with security by limiting the affected area of failures. The primary benefit for application availability is not security isolation but redundancy and failover capability.

---

### Question 27  Cloud Technology and Services

A developer is creating a new application and wants to integrate features of AWS services directly into the application. Which AWS tool is the BEST for this purpose?

AWS CodePipeline

AWS Command Line Interface (CLI)

AWS Software Development Kit

AWS CodeDeploy

#### Explanation

> "AWS Software Development Kit" is correct. The AWS Software Development Kit (SDK) is the best tool for directly integrating AWS services into an application. The SDK provides APIs and tools for many AWS services that allow developers to build applications that use AWS.

> "AWS Command Line Interface (CLI)" is incorrect.

> "AWS CodeDeploy" is incorrect as it is for deploying AWS resources not integration.

> "AWS CodePipeline" is incorrect. It is focused on managing AWS resources, not integrating them into an application.

---

### Question 28  Security and Compliance

According to the AWS Shared Responsibility Model, which two of the following are customer responsibilities?

Physical security of data center facilities

Patching the network infrastructure

Setting up encryption on an Amazon S3 bucket

Patching the EC2 Operating System

#### Explanation

> "Setting up encryption on an Amazon S3 bucket" and "Patching the EC2 Operating System" is correct. The customer is responsible for setting up encryption on Amazon S3 buckets and patching the EC2 operating system.

> "Physical security of data center facilities" is incorrect. AWS is responsible for the physical security of data centers and patching the network infrastructure.

> "Patching the network infrastructure" is incorrect. AWS is responsible for the physical security of data centers and patching the network infrastructure.

---

### Question 29  Cloud Technology and Services

You are using Amazon Simple Notification Service to send notifications to alert admins when CPU usage of an Amazon EC2 instance is more than 70%. Which two of the following can subscribe to an Amazon SNS topic?

Amazon CloudWatch

Email

AWS Lambda

Amazon S3

#### Explanation

> "Email"s and "AWS Lambda" are correct. Both the functions can subscribe to an SNS topic to receive notifications. SNS is useful for sending messages to multiple recipients.

> "Amazon S3" is incorrect as it publishes events to SNS but does not subscribe. DynamoDB streams can trigger Lambda which then publishes to SNS.

> "Amazon CloudWatch" is incorrect as it publishes events to SNS but does not subscribe. DynamoDB streams can trigger Lambda which then publishes to SNS.

---

### Question 30  Cloud Technology and Services

What action does an Elastic Load Balancer (ELB) take when it detects an unhealthy Amazon EC2 instance?

It only sends traffic to the remaining healthy instances.

It continues to send traffic to the failed instance.

It restarts the unhealthy EC2 instance.

It terminates the failed instance so that it is not part of the ELB target group.

#### Explanation

> "It only sends traffic to the remaining healthy instances is correct. When an ELB detects an unhealthy EC2 instance, it will stop sending traffic to that instance. The ELB will only send traffic to the remaining healthy instances in the target group.

> "It restarts the unhealthy EC2 instance is incorrect. It does not restart sending traffic to the unhealthy instance.

> "It terminates the failed instance so that it is not part of the ELB target group is incorrect. It does not terminate the unhealthy instance.

> "It continues to send traffic to the failed instance is incorrect. It does not continue sending traffic to the unhealthy instance.

---

### Question 31  Cloud Concepts

How can using fully managed services from AWS be more beneficial than deploying third-party software on Amazon EC2 instances?

Automated backups

Automated infrastructure deployment using code

Reduced capital expenses

Reduced operational overhead

#### Explanation

> "Reduced capital expenses" and "Reduced operational overhead" are both correct. Using fully managed services from AWS can reduce capital expenses because you don't need to purchase and maintain your own servers. It also reduces operational overhead because AWS manages the infrastructure for you.

> "Automated backups", although useful, is not the main benefits compared to running software on EC2.

> "Automated infrastructure deployment using code" is incorrect. It is not the main benefit compared to running software on EC2.

---

### Question 32  Cloud Concepts

Which universal concept of cloud computing refers to the ability of a cloud environment to continue functioning while some portions are unavailable?

Performance

Availability

Resiliency

Scalability

#### Explanation

> "Resiliency" is correct. Resiliency refers to the ability of a system to continue to function when some portion of it experiences an outage.

> "Availability" is incorrect. Availability pertains to the overall system being up or down.

> "Scalability" is incorrect. Scalability pertains to the changing of provisioned resources to meet demand.

> "Performance" is incorrect. Performance refers to the ability to quickly and efficiently meet user demands for a system.

---

### Question 33  Billing and Pricing and Support

Which AWS component of the Billing Dashboard will give users an overview of their past 12 months of usage and forecasts for their projected usage for the next 12 months?

Cost Explorer

AWS Budgets

Cost Projections

Budget Reports

#### Explanation

> "Cost Explorer" is correct. Cost Explorer will display data for 12 months of usage, as well as providing forecasts for what you may use in the next 12 months based on your past usage.

> "AWS Budgets" is incorrect. Budgets are used to plan costs and track consumption of resources, as well as use of reserved instances.

> "Budget Reports" is incorrect. Budget Reports are generated on a regular basis to track AWS Budget usage and status.

> "Cost Projections" is incorrect. Cost Projections is an erroneous but similar-sounding term.

---

### Question 34  Cloud Technology and Services

The AWS RDS offers several different types of managed databases to meet the needs of almost all users. Which of the following is not a type of database offered under RDS?

Oracle

DynamoDB

MariaDB

PostgreSQL

#### Explanation

> "DynamoDB" is correct. DynamoDB is not a relational database, and thus is not offered as part of the AWS Relational Database Service (RDS).

> "MariaDB" is incorrect. MariaDB is a relational databases offered under RDS.

> "Oracle" is incorrect. Oracle is a relational databases offered under RDS.

> "PostgreSQL" is incorrect. PostgreSQL is a relational databases offered under RDS.

---

### Question 35  Security and Compliance

What best describes the principle that users should only be given the minimum permissions they need to do their job?

Users should always have more permissions than they need.

All users should have the same baseline permissions to use basic AWS services.

Users should submit all access requests in writing for an audit trail.

Users should be granted permission to access only the resources they need for their job.

#### Explanation

> "Users should be granted permission to access only the resources they need for their job" is correct. This is also known as the principle of least privilege. For example, a backup user only needs rights to run backups.

> "All users should have the same baseline permissions to use basic AWS services." is incorrect. It gives users more access than necessary.

> "Users should submit all access requests in writing for an audit trail." is incorrect. It gives users more access than necessary.

> "Users should always have more permissions than they need." is incorrect. It gives users more access than necessary.

---

### Question 36  Security and Compliance

A website manager uses online resources for an organization. What AWS service can track expiration dates of SSL/TLS certificates and handle renewals?

AWS Data Lifecycle Manager

AWS License Manager

AWS Certificate Manager

AWS Firewall Manager

#### Explanation

> The "AWS Certificate Manager" lets the manager track expiration dates for SSL/TLS certificates. It can also automate certificate renewal.

> "AWS Data Lifecycle Manager" is incorrect because the AWS Data Lifecycle Manager automates lifecycle policies, not certificates.

> "AWS License Manager" is incorrect because the AWS License Manager tracks software licenses, not certificates.

> "AWS Firewall Manager" is incorrect because the AWS Firewall Manager centralizes firewall rules, not certificates.

---

### Question 37  Security and Compliance

What is the purpose of Amazon CloudHSM?

It protects against DDoS attacks.

It acts as an interface between the user and the computer.

It is used to generate, use, and manage encryption keys in the cloud.

It applies protection against malware.

#### Explanation

> "It is used to generate, use, and manage encryption keys in the cloud" is correct. Amazon CloudHSM is a cloud-based hardware security module that allows you to easily generate, use, and manage cryptographic keys in the AWS Cloud. It enables you to protect your encryption keys by using FIPS 140-2 Level 3 validated HSMs.

> "It protects against DDoS attacks" is incorrect. Amazon CloudHSM is not used for protection against DDoS attacks. DDoS protection is provided by AWS Shield service.

> "It applies protection against malware" is incorrect. Amazon CloudHSM does not provide malware protection. AWS services like GuardDuty and Inspector can help protect against malware.

> "It acts as an interface between the user and the computer" is incorrect. Amazon CloudHSM is not an interface between user and computer. It is used to manage cryptographic keys.

---

### Question 38  Cloud Technology and Services

A company is planning to deploy a high-volume application on multiple Amazon EC2 instances. What can help reduce operational expenses?

Deploy Amazon EC2 instances with Auto Scaling.

Deploy Amazon EC2 instances in multiple Availability Zones.

Deploy Amazon EC2 instances with Cluster placement groups.

Deploy Amazon EC2 instances with Amazon instance store-backed AMIs.

#### Explanation

> "Deploy Amazon EC2 instances with Auto Scaling" is correct. Using Amazon EC2 Auto Scaling matches the workload on the application with the optimal number of Amazon EC2 instances. During low load, Auto Scaling terminates EC2 instances which reduces operational expenses.

> "Deploy Amazon EC2 instances in multiple Availability Zones" is incorrect. Deploying EC2 instances in multiple AZs enhances availability but does not reduce expenses.

> "Deploy Amazon EC2 instances with Amazon instance store-backed AMIs" is incorrect. Using instance store-backed AMIs incurs charges for EC2 usage and storing AMIs in Amazon S3, with no impact on expenses.

> "Deploy Amazon EC2 instances with Cluster placement groups" is incorrect. Cluster placement groups provide low latency but do not reduce expenses.

---

### Question 39  Cloud Concepts

How much data can a company store in Amazon S3?

100 PB

Virtually unlimited

1 PB

100 TB

#### Explanation

> "Virtually unlimited" is correct. Amazon S3 allows companies to store virtually unlimited amounts of data. There are no limits on the total amount of data that can be stored in an S3 bucket.

> "100 PB" is incorrect. 100 PB provides specific storage amounts, but Amazon S3 has no set limit..

> "1 PB" is incorrect. 1 PB provides specific storage amounts, but Amazon S3 has no set limit..

> "100 TB" is incorrect. 100 TB provides specific storage amounts, but Amazon S3 has no set limit.

---

### Question 40  Cloud Concepts

How does using cloud computing help companies achieve more efficient use of resources?

Unused resources are terminated daily.

Resources can be scaled based on demand.

Resources are unlimited.

The cloud provider handles efficiency.

#### Explanation

> "Resources can be scaled based on demand" is correct. This optimizes resource usage and efficiency.

> "Resources are unlimited" is incorrect. They are not unlimited.

> "The cloud provider handles efficiency" is incorrect. Efficiency still requires planning.

> "Unused resources are terminated daily" is incorrect. Unused resources are not automatically terminated.

---

### Question 41  Cloud Technology and Services

How can you reduce the operating costs for a MySQL database?

By migrating the database to a Docker container

By migrating the database to an Amazon RDS instance

By migrating the database to an AWS Storage Gateway

By migrating the database to an EC2 instance

#### Explanation

> "By migrating the database to an Amazon RDS instance" is correct. Migrating the MySQL database to Amazon RDS can reduce operational overhead and costs compared to self-managing database instances. RDS automates database administration tasks like backups, software patching, automatic failure detection, and recovery.

> "By migrating the database to a Docker container" is incorrect. This would still require managing the database yourself.

> "By migrating the database to an EC2 instance" is incorrect. This would still require managing the database yourself.

> "By migrating the database to an AWS Storage Gateway" is incorrect as it is a storage service.

---

### Question 42  Cloud Technology and Services

You have a Node.js application that you want to get running as quickly as possible. You need high performance and reliability, but you do not care about the underlying system running your code. Which AWS service would best suit your needs?

Lightsail

AppStream

EC2

Elastic Beanstalk

#### Explanation

> "Elastic Beanstalk" is correct. With Elastic Beanstalk, you choose the application platform that your code is written in, such as Java, Node.js, PHP, or .NET. Once you provision the instance, you can deploy your code into it and begin running. You only select the platform that you need; you do not select specific hardware or compute resources.

> "EC2" is incorrect. EC2 is an IaaS solution that requires you to install and configure all software necessary to run code.

> "Lightsail" is incorrect. Lightsail is designed for quick deployment of applications, but you must still select the underlying platform and system to run it in.

> "AppStream" is incorrect. AppStream is used for streaming services, not code deployment.

---

### Question 43  Cloud Technology and Services

Which statement about S3 storage buckets is true?

Bucket names must be globally unique within AWS and can only exist in one region.

Bucket names must be unique within your account and region.

Bucket names can span multiple regions but must have a unique name.

Bucket names can be used in multiple regions to enable automatic replication between them.

#### Explanation

> "Bucket names must be globally unique within AWS and can only exist in one region" is correct. Bucket names must be globally unique across all of AWS, and each bucket can only exist within one region.

> "Bucket names must be unique within your account and region" is incorrect. While bucket names must be unique within your account and region, they also must be globally unique.

> "Bucket names can span multiple regions but must have a unique name" is incorrect. Bucket names must be globally unique regardless of region.

> "Bucket names can be used in multiple regions to enable automatic replication between them" is incorrect. Bucket names must be globally unique and cannot be repeated within different regions.

---

### Question 44  Security and Compliance

How can a system administrator add extra login protection to a user's AWS Management Console?

Enable AWS CloudTrail

Use Amazon Cloud Directory

Review AWS Identity and Access Management (IAM) roles

Enable multi-factor authentication

#### Explanation

> "Enable multi-factor authentication" is correct. This adds an extra layer of security by requiring the user to provide an additional authentication factor beyond just a password when logging into the AWS Management Console. This makes it harder for an unauthorized person to access the user's account.

> "Use Amazon Cloud Directory" is incorrect. This allows creating directories to store hierarchies of data, but does not add extra login protection to a user's AWS console.

> "Review AWS Identity and Access Management (IAM) roles" is incorrect. IAM roles control access permissions to AWS resources, but do not add extra authentication factors during login.

> "Enable AWS CloudTrail" is incorrect. CloudTrail logs API calls to monitor account activity, but does not add multi-factor authentication during login.

---

### Question 45  Cloud Concepts

How does using Infrastructure as a Service (IaaS) help companies?

Provides rapid innovation capabilities

Eliminates infrastructure costs

Reduces need for data center space

IaaS is fully managed by the provider

#### Explanation

> "Reduces need for data center space" is correct. IaaS reduces the need for companies to build and maintain their own data centers since infrastructure is provided on demand.

> "Eliminates infrastructure costs" is incorrect. They are not fully eliminated.

> "IaaS is fully managed by the provider" is incorrect, since it still requires customer management.

> "Provides rapid innovation capabilities" is incorrect. It may be faster, but reducing data center needs is the main benefit.

---

### Question 46  Cloud Technology and Services

Which service is the AWS DNS offering that allows for highly scalable and secure lookups and the ability to extend traditional DNS to encompass health checks?

CloudFront

Lambda

Route 53

AWS DNS

#### Explanation

> "Route 53" is correct. Amazon Route 53 is a robust, scalable, and highly available DNS service. Rather than running their own DNS services or being dependent on another commercial service, an organization can utilize Route 53 to transform names into their IP address, as well as having full IPv6 compatibility and access. Route 53 can be used for services that reside inside AWS, as well as those outside of AWS.

> "CloudFront" is incorrect. CloudFront allows for ultra-low-latency serving of data, but does not perform DNS functions.

> "AWS DNS" is incorrect. AWS DNS is not the name of an AWS service.

> "Lambda" is incorrect. Lambda allows the execution of code without requiring the use of underlying servers.

---

### Question 47  Cloud Technology and Services

To save on long-term costs from pre-purchasing hardware, you want to move your company’s data warehouse system into AWS. Which AWS service would you utilize for this?

Amazon Aurora

Amazon Redshift

Amazon RDS

DynamoDB

#### Explanation

> "Amazon Redshift" is correct. Redshift is a cloud-based data warehouse solution offered by AWS. Unlike traditional on-premises data warehouses, Redshift leverages AWS storage to any capacity that is needed by a company, either now or into the future.

> "Amazon RDS" is incorrect. Amazon RDS is a managed relational database service, but is not geared towards data warehouse operations specifically.

> "Amazon Aurora" is incorrect. Amazon Aurora is an AWS database service, a subset of Amazon RDS, that is compatible with both MySQL and PostgreSQL databases.

> "DynamoDB" is incorrect. DynamoDB is an unstructured database service with AWS that is not appropriate for a data warehouse.

---

### Question 48  Cloud Technology and Services

Amazon RDS provides Multi-AZ feature for better availability of databases. Which of the following options describes Multi-AZ?

Multi-AZ allows peering connections between VPCs.

Multi-AZ encrypts RDS instance data.

Multi-AZ allows read replicas of RDS instances across availability zones.

Multi-AZ maintains standby replicas of RDS instances in different availability zones.

#### Explanation

> "The Multi-AZ feature in Amazon RDS maintains a standby replica of the RDS instance in a different availability zones" is correct. This provides better availability in case the primary RDS instance faces an outage.

> "Multi-AZ it allows read replicas of RDS instances across availability zones" is incorrect. This is incorrect because Multi-AZ maintains standby replicas, not read replicas, in different availability zones. Read replicas are used for scaling read operations while standby replicas are for high availability.

> "Multi-AZ allows peering connections between VPCs" is incorrect. This is incorrect because Multi-AZ is a feature specific to RDS and maintains standby databases. VPC peering is used to connect VPCs and is unrelated to RDS Multi-AZ.

> "Multi-AZ encrypts RDS instance data" is incorrect. This is incorrect because RDS encryption is separate from Multi-AZ. RDS encryption encrypts data at rest while Multi-AZ maintains standby replicas for availability.

---

### Question 49  Cloud Technology and Services

Under Elastic Block Store (EBS), which types of underlying storage do you have to choose from? (Choose two)

NAS

SSD

SAN

Object

HDD

#### Explanation

> "HDD" and "SSD" are correct. Under EBS, you have several different types of EBS volumes to choose from either on HDD (hard disk drive) or SSD (solid-state drive) storage.

> "SAN" is incorrect. EBS does not offer options for SAN.

> "NAS" is incorrect. EBS does not offer options for NAS.

> "Object" is incorrect. EBS does not offer options for object storage.

---

### Question 50  Security and Compliance

What AWS service can be used as a web application firewall?

AWS WAF

AWS Snowball

AWS Shield

AWS CloudFront

#### Explanation

> "AWS WAF" is a web application firewall service that lets you monitor and control HTTP and HTTPS requests forwarded to Amazon CloudFront or Application Load Balancer. It provides protections from common web exploits.

> "AWS Snowball" is an incorrect answer. Snowball is a petabyte-scale data transport solution that uses secure appliances to transfer large amounts of data into and out of AWS. It does not provide web application firewall capabilities.

> "AWS CloudFront" is a distractor answer. AWS CloudFront is a content delivery network service. It caches content at edge locations for fast delivery but does not provide web application firewall capabilities.

> "AWS Shield" is a distractor answer. AWS Shield is a managed DDoS protection service that safeguards web applications against DDoS attacks. It does not provide full web application firewall functionality.

---

### Question 51  Cloud Technology and Services

Which AWS services are global in nature versus based on regions like most AWS services? (Choose two)

EC2

CloudFront

IAM

Lightsail

S3

#### Explanation

> "CloudFront" and "IAM" are correct. Both CloudFront and IAM services are global and not bound to specific regions.

> "S3" is incorrect. S3 is based on specific regions when services are provisioned.

> "EC2" is incorrect. EC2 is based on specific regions when services are provisioned.

> "Lightsail" is incorrect. Lightsail is based on specific regions when services are provisioned.

---

### Question 52  Billing and Pricing and Support

Which AWS component of the Billing Dashboard will track a user’s incurred billing throughout the month and provide a projected total bill for the month on a continual basis?

Cost Explorer

Savings Plans

Cost Categories

AWS Budgets

#### Explanation

> "AWS Budgets" is correct. During each month, Budgets will track how much your current charged status is, including what your predicted amount of usage and charges will be by the end of the month.

> "Cost Explorer" is incorrect. Cost Explorer is used to review the past 12 months of usage and projections for the next 12 months.

> "Cost Categories" is incorrect. Cost Categories allows an account to categorize services and costs into granular containers for the purposes of analysis based on your specific needs.

> "Savings Plans" is incorrect. Savings Plans are used to commit to pre-purchase an amount of compute resources on a one- or three-year basis.

---

### Question 53  Cloud Concepts

In the shared responsibility model for Amazon EC2, which two choices are customer responsibilities?

Physical security of hardware

Virtualization infrastructure

Amazon Machine Images (AMIs)

Applications in EC2 instances

Network infrastructure

#### Explanation

> "Amazon Machine Images (AMIs)" and "Applications in EC2 instances" are correct. These are both customer responsibilities. In the shared responsibility model, AWS manages the security of facilities, hardware, network, and virtualization. Customers are responsible for security of AMIs, operating systems, applications, data, credentials, policies, and configuration.

> "Network Infrastructure" is incorrect. Network Infrastructure is AWS responsibilities, not customer responsibilities.

> "Virtualization Infrastructure" is incorrect. Virtualization Infrastructure is AWS responsibilities, not customer responsibilities.

> "Physical security of hardware" is incorrect. Physical security of hardware is AWS responsibilities, not customer responsibilities.

---

### Question 54  Security and Compliance

You are looking for the user guides for Elastic Beanstalk. Which AWS support resource would you explore to find this?

Documentation

Knowledge Center

Discussion Forums

AWS Professional Services

#### Explanation

> "Documentation" is correct. The AWS Documentation library includes for each AWS service user guides, API references, pertinent CLI references, and a developer guide.

> "Knowledge Center" is incorrect. The Knowledge Center is structured in an FAQ format and organized by AWS.

> "Discussion Forums" is incorrect. Discussion forums enable customers to help other customers with questions they may have about AWS services and configurations.

> "AWS Professional Services" is incorrect. AWS Professional Services offers official guided support by AWS with the focus on reaching specific results and optimization of AWS services for your particular needs.

---

### Question 55  Cloud Technology and Services

You want to use AWS to back up your on-premises data in a seamless manner. Which AWS service would enable you to accomplish this?

AWS Snow

AWS Glacier

AWS Storage Gateway

AWS Containers

#### Explanation

> "AWS Storage Gateway" is correct. The AWS Storage Gateway provides storage for hybrid cloud services that gives access to your on-premises resources to the full array of storage services in AWS. This enables a customer to extend their storage capabilities into AWS seamlessly and with very low latency. A common usage of Storage Gateway is for customers to use AWS to store backups of images from their on-premises environment.

> "AWS Snow" is incorrect. AWS Snow provides for data and compute services away from AWS, but does not provide for backups in the manner asked.

> "AWS Glacier" is incorrect. AWS Glacier is storage for less frequently accessed data and is commonly used for backups, but will not itself facilitate backing up data from systems.

> "AWS Containers" is incorrect. AWS Containers are not used for backing up data, but are instead used for hosting applications within a virtualized environment.

---

### Question 56  Cloud Technology and Services

A company wants to use AWS storage. Low storage cost is very important for them. Their data is rarely needed and waiting 13-14 hours to get the data back is acceptable. What is the best storage option for the company to use?

Amazon S3 Glacier

Amazon S3

S3 Glacier Deep Archive

Amazon EBS

#### Explanation

> "S3 Glacier Deep Archive" is correct as it has the lowest cost storage in AWS. It is cheaper than storing data on your own servers or tapes. S3 Glacier Deep Archive is the best option because the low cost is most important for the company. Fast retrieval time does not matter for them.

> "Amazon S3 Glacier" is wrong because S3 Glacier costs more.

> "Amazon EBS" is incorrect. EBS does not store data for a long time at low cost.

> "Amazon S3" is incorrect as it does not store data for a long time at low cost.

---

### Question 57  Security and Compliance 

The AWS Trusted Advisor is split into five areas of focus to analyze your services and configurations and recommend appropriate best practices. Which of the following is not one of the AWS Trusted Advisor areas of focus?

Fault tolerance

Privacy

Security

Performance

#### Explanation

> "Privacy" is correct. Privacy is not one of the five areas of focus of the AWS Trusted Advisor.

> "Security" is incorrect. Security flags any deficiencies in security configurations that do not meet established best practices.

> "Performance" is incorrect. Performance flags any configurations that are implemented in a way that might be preventing resources from reaching their full potential and limiting performance.

> "Fault tolerance" is incorrect. Fault tolerance flags any resources that are allocated but are configured in a way that makes them vulnerable to service interruptions, such as single points of failure with nonreplicated systems, or any systems that are not being backed up.

---

### Question 58  Security and Compliance

How can we allow an application running on an Amazon EC2 instance to securely access data in an Amazon S3 bucket without providing long-term credentials to the application?

Using an IAM role

Using Bucket Permissions

Using cross region replication

Using User Groups

#### Explanation

> The correct answer is "Using an IAM role". IAM roles allow EC2 instances to securely access AWS services like S3 without needing long-term credentials.

> "Using Bucket Permissions" is incorrect. It would not work because they are tied to a specific IAM user.

> "Using User Groups" is incorrect. It would not work because they still require long-term credentials.

> "Using cross region replication" is incorrect. I is for copying data between S3 buckets in different regions.

---

### Question 59  Billing and Pricing and Support

Which AWS tool can you use to forecast how much you will spend on AWS?

AWS Trusted Advisor

AWS Organizations

Amazon DevPay

AWS Cost Explorer

#### Explanation

> "AWS Cost Explorer" is a free tool that lets you see your AWS costs over time. You can use it to forecast how much you may spend in the next 12 months. It also gives suggestions for Reserved Instances to buy. Cost Explorer shows patterns and trends in your spending so you can understand your costs better.

> "AWS Organizations" is incorrect. Iit allows you to centrally manage and govern your environment as you grow and scale your workloads on AWS. It does not help forecast AWS costs.

> "Amazon DevPay" is incorrect. It is a billing option that lets you pay for AWS services as your customers use them. It does not forecast AWS costs.

> "AWS Trusted Advisor" is incorrect. It provides recommendations that can help you reduce costs, increase performance, and improve security. It does not forecast future AWS costs.

---

### Question 60  Security and Compliance

If you have multiple users who need the same rights within your AWS account, which would be the easiest approach to implement and maintain the consistency of them?

Assign them to the same IAM group that you create.

Create each user in IAM and assign the proper roles.

Assign them to the same security group.

Make each their own AWS account and share access to the main account.

#### Explanation

> "Assign them to the same IAM group that you create" is correct. Creating an IAM group with appropriate roles assigned to it makes it easy to assign users to that group and maintain consistency with permissions.

> "Assign them to the same security group" is incorrect because security groups are used for network access and not account access in AWS.

> "Create each user in IAM and assign the proper roles" is incorrect. While creating each user and assigning the appropriate roles would work, this makes each account independent and lacks an easy way to main consistency.

> "Make each their own AWS account and share access to the main account" is incorrect because you would not create a separate master account for users and link to your AWS account; you would make accounts with IAM.

---

### Question 61  Security and Compliance

How can you protect your data from a regional disaster using Amazon S3?

Use Cross-Region Replication (CRR)

Use Intelligent-Tiering Archive configurations

Use Lifecycle rules

Use bucket policy

#### Explanation

> "Cross-Region Replication" is correct. It copies objects across Amazon S3 buckets in different AWS regions. This allows you to protect your data from regional disasters.

> "Use Lifecycle rules" is incorrect. Lifecycle rules does not replicate data across regions

> "Use Intelligent-Tiering Archive configurations" is incorrect. Intelligent-Tiering does not replicate data across regions

> "Use bucket policy" is incorrect. Bucket policy does not replicate data across regions

---

### Question 62  Cloud Concepts

A company wants to start a new system on AWS. But the company does not have an employee who knows about AWS. Which AWS program can help the company to design, build, and manage their systems on AWS?

AWS Marketplace

AWS Partner Network Consulting Partners

Amazon Inspector

AWS Trusted Advisor

#### Explanation

> "AWS Partner Network Consulting Partners" is correct. Consulting Partners help customers design, build, and manage systems on AWS. So a Consulting Partner can help the company start their new system on AWS.

> "AWS Marketplace" is an online store where users can find, test, and buy software that runs on AWS. It does not directly help companies build systems on AWS.

> "AWS Trusted Advisor" provides automated recommendations to help reduce costs, increase performance, and improve security. It does not directly help design, build, and manage systems on AWS.

> "Amazon Inspector" is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. It does not help with designing and building new systems on AWS.

---

### Question 63  Cloud Concepts

What is an advantage of using Availability Zones in Amazon Web Services?

Availability Zones are connected by low-latency networks

With multiple availability zones, the cost is reduced

Availability Zones provide unlimited storage capacity

Availability Zones automatically replicate data across zones

#### Explanation

> "Availability Zones are connected by low-latency networks" is correct. It allows applications to be highly available.

> "With multiple availability zones, the cost is reduced" is incorrect. While using multiple Availability Zones can reduce costs compared to a single data center, this is not always the case and is not guaranteed. The cost reduction comes from the ability to distribute resources, but Availability Zones themselves do not inherently reduce costs.

> "Availability Zones automatically replicate data across zones" is incorrect. Availability Zones do not automatically replicate data across zones. The user must configure replication and redundancy across zones. The zones provide the ability to distribute resources, but don't automatically replicate data.

> "Availability Zones provide unlimited storage capacity" is incorrect. Availability Zones do not provide unlimited storage capacity. Each Availability Zone has a finite amount of capacity and storage resources. The advantage is being able to distribute storage across zones for redundancy, not unlimited capacity.

---

### Question 64  Cloud Technology and Services

Developers need to deploy a website with multiple tiers. Which AWS service can help create a catalog of resources to allow quick deployment of the website?

AWS Service Catalog

AWS CodeDeploy

AWS Config

AWS CloudFormation

#### Explanation

> "AWS Service Catalog" is correct. It allows creating catalogs or portfolios of AWS resources. These can be used to quickly deploy a multi-tier website. The catalog provides standardized and consistent deployments.

> "AWS Config" is incorrect. AWS Config does not provide ready-made catalogs for quick deployment.

> "AWS CodeDeploy" is incorrect. AWS CodeDeploy does not provide ready-made catalogs for quick deployment.

> "AWS CloudFormation" is incorrect. AWS CloudFormation does not provide ready-made catalogs for quick deployment.

---

### Question 65  Security and Compliance

What are two best practices for managing access in AWS using IAM?

Grant least privilege

Customer-managed policies

Use service accounts

Account-level policies

#### Explanation

> "Use service accounts" and "Grant least privilege" are correct. Creating an IAM user or role for each application or service to grant least privilege or granting only the permissions required for a user or service to perform their function are best practices.

> "Customer-managed policies" and "Account-level policies" are incorrect. They do not follow the principle of least privilege."
