# AWS Certified Cloud Practitioner CLF-C02 notes

### Question 1  Cloud Concepts

In a traditional data center, if you needed to add storage beyond what you already had connected to a server, you would need to buy or move hardware to expand. What key concept of cloud computing enables resources to be added without needing to add more hardware?

Virtualization

On-demand self-service

Rapid elasticity

Metered service

#### Explanation

> "Virtualization" is correct. Virtualization allows a large pool of hardware, storage, or network resources to be allocated to systems and services that are hosted on it without needing those systems to add more hardware to meet new demands.

> "Rapid elasticity" is incorrect. Rapid elasticity enables a cloud to automatically change the level of resources allocated to a service based on demand, but virtualization is the more correct answer for the underlying concept.

> "Metered service" is incorrect. Metered service pertains to only paying for which resources you are using and only for the duration of time you are using them.

> "On-demand self-service" is incorrect. On-demand self-service refers to the ability of a user, with a credit card on file, to automatically provision and purchase services without having to involve anyone from AWS.

---

### Question 2  Security and Compliance

With implementing a data loss prevention (DLP) strategy, where would you place the solution to protect data in use?

Storage system

Web server

Network firewalls

User’s device


#### Explanation

> "User’s device" is correct. For a DLP solution to address data in use, the solution needs to be placed on the user’s device. This can be a particular challenge with BYOD policies.

> "Storage system" is incorrect. A DLP solution would be placed on the storage system for data-at-rest protection.

> "Network firewalls" is incorrect. A DLP solution would be placed on a network firewall for data-in-transit protection.

> "Web server" is incorrect. While it may seem like data is in use at the web server level, the correct placement is on the user’s device.

---

### Question 3  Billing and Pricing and Support

In the AWS Pricing Calculator, which AWS service offers options for both a quick estimate and an advanced estimate?

Lightsail

EC2

Elastic Beanstalk

S3


#### Explanation

> "EC2" is correct. EC2, with all the complexities between regions, instance types, and storage, offers both a quick estimate and an advanced estimate for pricing in the calculator.

> The other answers are incorrect. Lightsail, S3, and Elastic Beanstalk do not need to offer different types of pricing estimates, as they are far less complex services than EC2.

---

### Question 4  Cloud Technology and Services

You want to logically define an isolated and protected network space within AWS to deploy services. Which AWS service would you use?

AWS Shield

AWS VPC

AWS VPN

AWS Snowball


#### Explanation

> "AWS VPC" is correct. With Amazon Virtual Private Cloud (Amazon VPC), you can create a logically defined space within AWS to create an isolated virtual network. Within this network, you retain full control over how the network is defined and allocated. You fully control the IP space, subnets, routing tables, and network gateway settings within your VPC, and you have full use of both IPv4 and IPv6.

> "AWS VPN" is incorrect. VPN services are used to create a protected network tunnel into a network, but do not define or allocate the network.

> "AWS Shield" is incorrect. AWS Shield is a security service primarily used to protect against DDoS attacks.

> "AWS Snowball" is incorrect. AWS Snowball uses physical storage devices to transfer large amounts of data between Amazon Simple Storage Service (Amazon S3) and an onsite data storage location at faster-than-internet speeds.

---

### Question 5  Cloud Technology and Services

Which component of the AWS Systems Manager provides an API to perform tasks against your resources throughout AWS?

AWS AppConfig

OpsCenter

Explorer

Inventory

#### Explanation

> "AWS AppConfig" is correct. AWS AppConfig provides an API and console method for applying configuration changes across AWS services from a centralized service.

> "Explorer" is incorrect. Explorer provides a customizable dashboard that provides information on the health of your entire AWS environment and can consolidate data spanning multiple accounts and regions.

> "OpsCenter" is incorrect. OpsCenter provides a consolidated view for developers and operations staff to view and investigate any operational issues.

> "Inventory" is incorrect. Inventory collects information from all services you have provisioned within AWS, including configuration and licensing information.

---

### Question 6  Cloud Concepts Correct

Your company wants to save money by no longer running applications themselves or paying software developers for custom application code. Which cloud service category would you be looking at offerings for?

PaaS

IaaS

SaaS

DaaS

#### Explanation

> "SaaS" is correct. SaaS offers fully managed and written applications that can be used by just creating accounts and uploading data pertinent to your company.

> "IaaS" is incorrect. IaaS requires cloud customers to deploy, configure, and manage virtual machines, platforms, and application code.

> "PaaS" is incorrect. PaaS provides a hosting platform and storage but requires application code and data to be provided by the customer.

> "DaaS" is incorrect. DaaS provides virtual desktops but not systems company applications for customers.

---

### Question 7  Security and Compliance Correct

Which of the following is not a technology used to protect data in transit?

Ipsec

VPN

HTTPS

S3 Encryption

#### Explanation

> "S3 Encryption" is correct. S3 encryption protects data objects as they reside in storage in AWS, but is not used to protect data as it traverses networks.

> The other answers are incorrect. HTTPS, IPsec, and VPN are all commonly used to protect data in transit.

---

### Question 8  Security and Compliance

When implementing multifactor security, which two things can be used along with a password to fulfill the requirements?

Challenge question

Retinal scan

Hardware token

Date of birth

PIN

#### Explanation

> "Hardware token" and "Retinal scan" are correct. As a password is something that a user knows, they would have to use either something they have, such as a hardware token, or something they are, such as a retinal scan, to satisfy MFA requirements.

> The other answers are incorrect. A PIN, date of birth, and a challenge question are all things that a user knows and are in the same category as a password.

---

### Question 9  Cloud Technology and Services

If you wanted to have identical configurations across your AWS systems for database connections, but you want to have the ability to have different systems connect to different database names depending if they are production or test environments, which AWS service would be ideal to implement?

Parameter Store

Distributor

AWS AppConfig

Automation

#### Explanation

> "Parameter Store" is correct. Parameter Store provides a way to store configuration data for your applications. This can be either plain-text strings or passwords used to access services such as databases. A main benefit of the Parameter Store is the ability to use the same key but contain different values for systems.

> "AWS AppConfig" is incorrect. AWS AppConfig provides an API and console method for applying configuration changes across AWS services from a centralized service.

> "Automation" is incorrect. Automation provides a set of predefined playbooks to do common repetitive tasks but also allows for users to create their own playbooks that are appropriate for their specific services.

> "Distributor" is incorrect. Distributor allows for the central storage, distribution, and installation of software packages to instances within AWS, including software agents.

---

### Question 10  Cloud Technology and Services

Which authentication method is supported by the AWS CLI to perform automation tasks on your AWS account?

MFA

Username/password

Access/secret key

Security hardware token

#### Explanation

> "Access/secret key" is correct. The AWS CLI requires the use of an access/secret key that can be obtained from the IAM portal.

> "Username/password" is incorrect. While username/password can be used to access the Management Console, it cannot be used for access via the CLI.

> "Security hardware token" is incorrect. Security hardware tokens are often used with MFA but cannot be used for the AWS CLI.

> "MFA" is incorrect. MFA is a crucial security enhancement to add to your account for access to the Management Console, but using MFA as part of CLI access still requires the use of an access/secret key.

---

### Question 11  Security and Compliance

Which of the following states is true about password policies for IAM accounts?

AWS has a global password policy that is enforced for all IAM accounts to meet industry best practices.

IAM password policies have granular controls and can be set based on the regulatory or corporate policies required for the account.

IAM account passwords can only be set by the root account and cannot be modified by the account itself.

IAM accounts are free to use whatever password is desired by the account holder.


#### Explanation

> "IAM password policies have granular controls..." is correct. The IAM Dashboard allows for the granular setting of password policies to match any regulatory requirements or corporate policies for the account.

> "AWS has a global password policy that is enforced..." is incorrect. Each AWS account can set its own IAM password policies.

> "IAM accounts are free to use whatever password is desired..." is incorrect. IAM accounts must conform to the password policies set on the account.

> "IAM account passwords can only be set by the root account..." is incorrect. IAM accounts can change their passwords as long as they conform to the password policies set on the account.

---

### Question 12  Billing and Pricing and Support

What AWS mechanism is used to protect the overall availability of resources within AWS and to protect users from potentially runaway billing as well?

Constraints

Quotas

Blocks

Segments

#### Explanation

> "Quotas" is correct. In order to protect the availability for all users in AWS, service quotas (formerly called limits) are applied to each service. These quotas are specific to a region and will place a limit on the number of specific types of resources you can allocate by default.

> The other answers are incorrect. All are extraneous answers.

---

### Question 13  Security and Compliance Correct

Which technology is widely used to verify the integrity of data objects against a known original value for any potential alterations or corruptions?

Anonymizing

Tokenization

Obfuscation

Hashing

#### Explanation

> "Hashing" is correct. Hashing involves taking data of arbitrary type, length, or size and using a function to map a value that is of a fixed size. Hashing can be applied to virtually any type of data object, including text strings, documents, images, binary data, and even virtual machine images. It can be used to very quickly verify the integrity of data objects.

> "Tokenization" is incorrect. Tokenization is the practice of utilizing a random and opaque “token” value in data to replace what otherwise would be a sensitive or protected data object.

> "Obfuscation" is incorrect. Obfuscation is the process of replacing sensitive data with different values so as to not expose your real data, typically used in test data sets.

> "Anonymizing" is incorrect. Anonymizing is the process of removing personal data from data sets and replacing it with different values to protect user privacy.

---

### Question 14  Billing and Pricing and Support

While reserved instances apply only to EC2, Savings Plans incorporates two additional AWS services. Select these two services.

Elastic Beanstalk

Fargate

S3

Lambda

Lightsail

#### Explanation

> "Fargate" and "Lambda" are correct. AWS Savings Plans incorporate Fargate and Lambda, in addition to EC2, and offer various discounts for committing to purchase compute power over a period of time.

> "Lightsail" is incorrect. Lightsail is not included under Savings Plans.

> "S3" is incorrect. S3 is not included under Savings Plans.

> "Elastic Beanstalk" is incorrect. Elastic Beanstalk is not included under Savings Plans.

---

### Question 15  Cloud Technology and Services

To provide optimal responsiveness for customers, AWS maintains a network of Edge locations throughout the world to provide ultra-low-latency access to data. Which AWS service is not available through Edge locations?

CloudFront

Lightsail

Route 53

AWS Shield

#### Explanation

> "Lightsail" is correct. The AWS Lightsail service is deployed by region.

> The other answers are incorrect. The CloudFront, Route 53, and AWS Shield services are all global in nature and deployed across AWS Edge.

---

### Question 16  Cloud Concepts Correct

Which key concept of cloud computing enables a user to remove all systems, accounts, and data from a cloud environment and ensure they have been completely removed?

Portability

Removability

Erasability

Reversibility

#### Explanation

> "Reversibility" is correct. Reversibility is the ability of a cloud customer to take all their systems and data out of a cloud provider and have assurances from the cloud provider that all the data has been securely and completely removed within an agreed-upon timeline.

> "Removability" is incorrect. Removability is not a key cloud concept.

> "Erasability" is incorrect. Erasability is a not a key cloud concept.

> "Portability" is incorrect. Portability is the key feature that allows systems to easily and seamlessly move between different cloud providers.

---

### Question 17  Cloud Technology and Services

If you were located in Germany and wanted to run an EC2 instance within your own jurisdiction, which AWS region would allow you to accomplish that?

af-south-1

us-west-1

ge-south-1

eu-central-1


#### Explanation

> "eu-central-1" is correct. The eu-central-1 region is located in Frankfort, Germany.

> "af-south-1" is incorrect. The af-south-1 region is located in Africa.

> "us-west-1" is incorrect. The us-west-1 region is located in the United States.

> "ge-south-1" is incorrect. There is no AWS region that begins with “ge".

---

### Question 18  Cloud Concepts

When moving to a cloud environment, which facet of computing does an organization give up control over and responsibilities for?

Security

Hardware

Operations

Data

#### Explanation

> "Hardware" is correct. In a cloud infrastructure, the cloud company is fully responsible for the management and maintenance of the underlying hardware infrastructure.

> The other answers are incorrect. Operations, security, and data responsibilities are split between the cloud user and cloud provider, with the user having varying degrees of responsibility and involvement.

---

### Question 19  Security and Compliance

Which cloud service model is most closely associated with DevOps?

DaaS

PaaS

IaaS

SaaS

#### Explanation

> "PaaS" is correct. PaaS is most heavily used for DevOps, where developers can quickly obtain fully featured hosting environments and only need to deploy their code and any needed data to test and develop with and do not need to worry about any underlying operating system or middleware issues.

> "IaaS" is incorrect. While IaaS could be used for DevOps, it would require significantly more work to get all the underlying infrastructure and platforms in place for developers to use.

> "SaaS" is incorrect. SaaS would not be used for DevOps, as it is a fully functional software package and not one where a customer would deploy their own code.

> "DaaS" is incorrect. DaaS would not be used for DevOps, as it is a desktop platform and not for code deployment.

---

### Question 20  Cloud Concepts

If you wanted to maintain flexibility in data processing, where the majority of your processes could be performed in a cloud environment, with other data-intensive processes such as video editing being maintained in your own data center, which cloud model would you utilize?

Hybrid

Community

Public

Private

#### Explanation

> "Hybrid" is correct. A hybrid cloud model can span between cloud hosting and a traditional data center to allow for the best solutions for different types of activities.

> The other answers are incorrect. Each cloud model is designed to operate within one type of hosting rather than spanning different hosting types like hybrid does.

---

### Question 21  Billing and Pricing and Support

With which AWS service would you expect to see service quotas regarding number of buckets, maximum object size, or number of restore requests?

EC2

S3

S3 Glacier

EBS

#### Explanation

> "S3 Glacier" is correct. Each of the mentioned quotas, number of buckets, maximum object size, and number of restore requests pertain to S3 Glacier.

> "S3" is incorrect. While S3 has quotas for number of buckets and maximum object size, the number of restore requests is what makes S3 Glacier correct.

> "EC2" is incorrect. Buckets and object sizes are not applicable to EC2.

> "EBS" is incorrect. None of the three mentioned quotas apply to EBS.

---

### Question 22  Security and Compliance

With EC2, which layer belongs to AWS under the Shared Responsibility model?

Operating system

Data

Hardware

Application code

#### Explanation

> "Hardware" is correct. Under the Shared Responsibility Model, AWS is always responsible for the underlying physical hardware.

> "Operating system" is incorrect. With EC2 being an IaaS service, the user is responsible for the operating system.

> "Application code" is incorrect. Unless it is a SaaS offering, the user is responsible for application code.

> "Data" is incorrect. The user is always responsible for data under all cloud models.

---

### Question 23  Cloud Concepts Correct

Which cloud service category has volume and object storage associated with it?

SaaS

IaaS

PaaS

DaaS

#### Explanation

> "IaaS" is correct. IaaS is most closely associated with volume and object storage.

> "SaaS" is incorrect. SaaS uses storage defined by the application and typically only access from within its interface.

> "PaaS" is incorrect. PaaS is most closely associated with the use of both structured and unstructured storage, typically in relationship to databases.

> "DaaS" is incorrect. DaaS uses storage that is allocated by the cloud provider and access from within the virtual desktops.

---

### Question 24  Cloud Technology and Services

AWS offers a fully managed virtual desktop infrastructure (VDI) solution with both Windows and Linux options. Which AWS service is this?

WorkSpaces

WorkLink

AppStream

AWS Desktop

#### Explanation

> "WorkSpaces" is correct. Amazon WorkSpaces is a Desktop as a Service (DaaS) implementation that is built, maintained, configured, and secured through AWS as a managed service. WorkSpaces offers both Windows and Linux desktop solutions that can be quickly deployed anywhere throughout the AWS global infrastructure.

> "WorkLink" is incorrect. WorkLink offers users the ability to access internal applications through the use of mobile devices.

> "AppStream" is incorrect. AppStream is a service for providing managed and streaming applications via AWS. By streaming applications, the need to download and install applications is removed, as they will be run through a web browser.

> "AWS Desktop" is incorrect. AWS Desktop is a similar-sounding name, but not an actual AWS service.

---

### Question 25  Cloud Concepts

Which cloud concept refers to the assigning of jobs, tasks, roles, and responsibilities and ensuring they are satisfactorily performed?

Interoperability

Maintenance

Governance

Auditability

#### Explanation

> "Governance" is correct. Governance at its core involves assigning jobs, tasks, roles, and responsibilities and ensuring they are satisfactorily performed. Whether in a traditional data center or a cloud model, governance is mostly the same and undertaken by the same approach, with a bit of added complexity in a cloud environment due to data protection requirements and the role of the cloud provider.

> "Auditability" is incorrect. Auditability refers to reports and evidence of user activity, compliance with controls and regulations, as well as systems and processes and the activities performed on them.

> "Maintenance" is incorrect. Maintenance refers to the care of systems to conduct patching, versioning, and upgrades to code, platforms, and operating systems.

> "Interoperability" is incorrect. Interoperability is the ease with which one can move or reuse components of an application or service. The underlying platform, operating system, location, API structure, or cloud provider should not be an impediment to moving services easily and efficiently to an alternative solution.

---

### Question 26  Cloud Technology and Services

You suspect that one of your employees has been using your AWS services, including incurring billing charges, for personal use. Which AWS service would be the most useful to your investigation?

AWS Budgets

AWS CloudTrail

Cost Explorer

AWS Shield

#### Explanation

> "AWS CloudTrail" is correct. CloudTrail is the AWS service for performing auditing and compliance within your AWS account. CloudTrail pairs with CloudWatch to analyze all the logs and data collected from the services within your account, which can then be audited and monitored for all activities done by users and admins within your account.

> "AWS Budgets" is incorrect. While Budgets will monitor and report on your incurred charges, it will not be useful in determining which user incurred them.

> "Cost Explorer" is incorrect. Cost Explorer is used to analyze your last 12 months of charges and your projected charges over the next 12 months.

> "AWS Shield" is incorrect. AWS Shield provides security from DDoS attacks.

---

### Question 27  Billing and Pricing and Support

Which of the following AWS services under the Free Tier would have limitations for both storage of data and the number of requests per month to access it?

DynamoDB

Lambda

Server Migration Service

CloudWatch

#### Explanation

> "DynamoDB" is correct. The DynamoDB service under the Free Tier is limited to 25GB of storage and up to 200 million read/write requests per month.

> "Lambda" is incorrect. Lambda under the Free Tier comes with 1,000,000 requests per month and up to 3.2 million seconds of compute time per month.

> "CloudWatch" is incorrect. CloudWatch allows for ten custom metrics and ten alarms, as well as 5GB of log ingestion and storage.

> "Server Migration Service" is incorrect. The Server Migration Service allows for migrating an unlimited number of servers into AWS from either on-premises or Microsoft Azure cloud.

---

### Question 28  Cloud Technology and Services

Which of the following is a correct designation for an AWS Availability Zone?

eu-south-1a

eu-south-1.az1

eu-south-1-a

eu-south-1az2


#### Explanation

> "eu-south-1a" is correct. To designate Availability Zones, AWS will append the letter for the Availability Zone on the end of the region identifier.

> The other answers are incorrect. Each incorrect answer does not properly append the Availability Zone letter to the region designation.

---

### Question 29  Cloud Technology and Services

Which of the following is a correct service endpoint for an EC2 instance within AWS?
[ec2.aws.com](http://ec2.aws.com/)

[ec2.amazonaws.com](http://ec2.amazonaws.com/)

[ec2.eu-west-2.amazonaws.com](http://ec2.eu-west-2.amazonaws.com/)

[ec2.aws.amazon.com](http://ec2.aws.amazon.com/)


#### Explanation

> "[ec2.eu-west-2.amazonaws.com](http://ec2.eu-west-2.amazonaws.com/)" is correct. AWS endpoints follow the formula of AWS service designation + AWS region + [amazonaws.com](http://amazonaws.com/).

> The other answers are incorrect. The region is always included with an AWS service endpoint and each incorrect response omits the region.

---

### Question 30  Cloud Technology and Services

Which AWS service is utilized to consolidate monitoring and measure services for your entire account within AWS?

AWS Shield

AWS CloudTrail

AWS CloudWatch

AWS WAF


#### Explanation

> "AWS CloudWatch" is correct. CloudWatch is the AWS service for monitoring and measuring services running within the AWS environment. It provides data and insights on application performance and how it may change over time and resource utilization and provides a centralized and consolidated view of the overall health of systems and services.

> "AWS CloudTrail" is incorrect. While CloudTrail consolidates logs and auditing data, it is not used for monitoring and measuring services.

> "AWS WAF" is incorrect. AWS WAF is the web application firewall that provides security filtering based on the properties of requests.

> "AWS Shield" is incorrect. AWS Shield provides security from DDoS attacks.

---

### Question 31  Security and Compliance

Which of the following is not an example of data at rest and the potential security implications of it?

S3 objects

Machine images

DynamoDB tables

API calls

#### Explanation

> "API calls" is correct. API calls are actual transactions and represent data in transit versus data at rest.

> "Machine images" is incorrect. Machine images live as data objects in storage and thus represent data at rest.

> "S3 objects" is incorrect. S3 objects are actual data files and fall under data at rest.

> "DynamoDB tables" is incorrect. DynamoDB tables are data written to storage and fall under data at rest.

---

### Question 32  Cloud Concepts

Which key cloud computing characteristic enables someone to create an account with AWS and get up and running quickly after providing a credit card number?

Broad network access

Resource pooling

Multitenancy

On-demand self-service

#### Explanation

> "On-demand self-service" is correct. On-demand self-service allows a user to create an account, provide a credit card number, and immediately begin provisioning services within an AWS. The user does not need to go through a contract process with AWS or engage with any AWS personnel to get started.

> "Resource pooling" is incorrect. Resource pooling allows resources and services to use the same overall block of resources in a shared manner.

> "Broad network access" is incorrect. Broad network access allows AWS services to be accessed from anywhere across the public Internet and from a variety of different devices and browsers.

> "Multitenancy" is incorrect. Multitenancy refers to multiple different companies or users sharing the same overall cloud environment and resources.

---

### Question 33  Security and Compliance

Which AWS support resource is an extensive set of FAQ pages that cover all AWS services and can be a useful resource for learning about AWS services and implementation ideas?

Discussion forums

Documentation

Knowledge Center

AWS Cloud Adoption Framework

#### Explanation

> "Knowledge Center" is correct. The structure of the Knowledge Center is that of a typical FAQ page, organized by AWS services. Unlike your typical FAQ, however, the Knowledge Center has an enormous number of pages that are framed in a question-and-answer format. It is designed to work alongside and complement other AWS resources, such as documentation, discussion forums, and the AWS Support Center.

> "Discussion forums" is incorrect. Discussion forums provided support for problems and questions by other AWS customers to help each other, but are not organized in an FAQ structure.

> "Documentation" is incorrect. Documentation is maintained by AWS on nearly all services and serves as a reference guide.

> "AWS Cloud Adoption Framework" is incorrect. The AWS Cloud Adoption Framework is maintained by AWS Professional Services and is focused on helping organizations have a successful cloud adoption.

---

### Question 34  Security and Compliance

For optimal security, when should a root user account be used within AWS?

To use tools on the Billing Dashboard

To create initial admin accounts from the IAM console

To approve S3 bucket creations

To provision new services

#### Explanation

> "To create initial admin accounts from the IAM console" is correct. The root account should be used to create other accounts for administrators to use and then should be highly protected and minimally used ongoing.

> "To provision new services" is incorrect. It is not necessary to use the root account to provision any services. Provisioning should be done through IAM accounts with the appropriate permissions and roles granted.

> "To use tools on the Billing Dashboard" is incorrect. The tools on the Billing Dashboard do not require root access. IAM accounts with appropriate permissions and roles should be used.

> "To approve S3 bucket creations" is incorrect. IAM accounts with the appropriate roles and permissions assigned to them should be used for the creation of S3 buckets; the root account is not necessary.

---

### Question 35  Cloud Technology and Services

Which CIDR block sizing will allow for the largest number of IP addresses within a subnet?

/28

/16

/24

/32

#### Explanation

> "/16" is correct. CIDR blocks with smaller numbers have the largest number of IP addresses available for them. The allowed ranges in AWS are from /16 to /28.

> "/28" is incorrect. /28 is the smallest CIDR block allowed within AWS.

> "/24" is incorrect. While /24 is within the range from /16 to /28, it allows for a smaller number of IP addresses than /16 allows.

> "/32" is incorrect. /32 is outside the allowed range of /16 to /28 in AWS.

---

### Question 36  Billing and Pricing and Support

Select two types of reserved instances offered by AWS for EC2 services.

Hybrid

Standard

Flexible

Convertible

Dynamic

#### Explanation

> "Standard" and "Convertible" are correct. AWS offers reserved instances for EC2 for both standard (up to 72 percent savings) and convertible (up to 54 percent savings).

> "Flexible" is incorrect. Flexible is not a type of AWS reserved instance, though it does sound similar to convertible.

> "Hybrid" is incorrect. Hybrid is not a type of reserved instance but is a type of cloud model.

> "Dynamic" is incorrect. Dynamic is not a type of reserved instance.

---

### Question 37  Cloud Technology and Services

Which AWS tool will allow you to initiate processes as a result of events that are detected within CloudWatch and take action based on the value of the event?

Events

Triggers

Alerts

Alarms

#### Explanation

> "Alarms" is correct. Alarms are based on predefined thresholds or through the use of machine learning algorithms and can trigger automated processes as a result. A prime example of the use of alarms is for auto-scaling based upon load or other thresholds, both with increasing and decreasing of allocated resources. Alarms can also be used to trigger workflows across the different AWS services, since they are done from a consolidated standpoint and are not siloed within a particular service.

> The other answers are incorrect. Triggers, alerts, and events are not means to initiate processes as a result of specific events identified by CloudWatch.

---

### Question 38  Security and Compliance

Which standard is widely used for SSO federations and implementations?

SQL

XML

SAML

JSON

#### Explanation

> "SAML" is correct. The Security Assertion Markup Language (SAML) was developed for the use of passing secure data for SSO transactions between the service provider and identity provider and is widely used throughout the industry.

> "XML" is incorrect. XML is a markup language for encoding documents and is similar to SAML, but without the necessary pieces for use with SSO.

> "JSON" is incorrect. JSON is a human-readable data object structure that is used in many different applications but not with federated SSO.

> "SQL" is incorrect. SQL is a query language for use with structured databases.

---

### Question 39  Security and Compliance

As a government employee, you need to provide proof that any cloud systems you are using meet FedRAMP requirements. Where in the AWS Management Console would you look to find FedRAMP certifications?

AWS CloudTrail

AWS Systems Manager

AWS OpsWorks

AWS Artifact

#### Explanation

> "AWS Artifact" is correct. AWS Artifact provides certification reports and audits by various governing bodies. This includes prominent certifications such as PCI DSS for financial/credit card transactions and FedRAMP for U.S. federal government systems. AWS also makes the pertinent SOC audit reports available to customers.

> "AWS CloudTrail" is incorrect. AWS CloudTrail consolidates logs and auditing information in a centralized console, but does not provide certification reports.

> "AWS Systems Manager" is incorrect. AWS Systems Manager is used for maintaining and updating your AWS systems and services and does not contain certification reports.

> "AWS OpsWorks" is incorrect. AWS OpsWorks is used for Chef and Puppet implementations within AWS.

---

### Question 40  Cloud Technology and Services

Which AWS region is limited to specific customers and is not available for selection in general?

ca-central-1

us-gov-west-1

me-south-1

sa-east-1

#### Explanation

> "us-gov-west-1" is correct. The us-gov-west-1 region is restricted to U.S. government accounts.

> The other answers are incorrect. The Middle East, South America, and Canadian regions are all available for use by all AWS customers.

---

### Question 41  Cloud Technology and Services

Select two managed instances that are offered as part of AWS OpsWorks.

Puppet Enterprise

Rsync

Chef Automate

FlashCopy

Git

#### Explanation

> "Chef Automate" and "Puppet Enterprise" are correct. AWS OpsWorks provides managed instances of Puppet and Chef.

> "Git" is incorrect. Git is offered as part of CodeCommit, not part of OpsWorks.

> "Rsync" is incorrect. Rsync is not offered as part of AWS services.

> "FlashCopy" is incorrect. FlashCopy is not offered as part of AWS services.

---

### Question 42  Billing and Pricing and Support

As part of the AWS Free Tier, which service offers a user a free one-month trial of either a Linux or Windows platform?

Lightsail

AppStream

Inspector

GuardDuty

#### Explanation

> "Lightsail" is correct. Lightsail offers a free month trial of what would normally cost $3.50 USD for the Linux/Unix Lightsail platform or the $8 USD Microsoft Windows Lightsail platform.

> "AppStream" is incorrect. AppStream offers a free trial for 40 hours’ use of the stream.standard.large instance type, but is not a compute service.

> "GuardDuty" is incorrect. GuardDuty offers a 30-day free trial for intelligent threat detection and monitoring of accounts and workloads, but is not a compute service.

> "Inspector" is incorrect. Inspector offers a free trial for 90 days or 250 assessments, but is not a compute service.

---

### Question 43  Security and Compliance

Which component of the AWS Trusted Advisor would you use to look for any flagged resources that are not optimally configured to minimize service interruptions?

Service Limits

Security

Performance

Fault Tolerance


#### Explanation

> "Fault Tolerance" is correct. Fault Tolerance flags any resources that are allocated but are configured in a way that makes them vulnerable to service interruptions, such as single points of failure with non-replicated systems, or any systems that are not being backed up.

> "Security" is incorrect. Security flags any deficiencies in security configurations that do not meet established best practices.

> "Service Limits" is incorrect. Service Limits flags any services that you are using that are approaching their limits within AWS, such as number of instances of data objects or regional limitations.

> "Performance" is incorrect. Performance flags any configurations that are implemented in a way that might be preventing resources from reaching their full potential and limiting performance.

---

### Question 44  Cloud Concepts

Your company wants to provide easy and quick access to its developers to try applications and codes across multiple frameworks to determine what gets the best performance and scalability. Which cloud service category would you be looking to utilize?

DaaS

IaaS

SaaS

PaaS

#### Explanation

> "PaaS" is correct. PaaS provides fully configured platforms and systems to deploy application code and data quickly into.

> "SaaS" is incorrect. SaaS offers fully managed and written applications that can be used by just creating accounts and uploading data pertinent to your company.

> "IaaS" is incorrect. IaaS requires cloud customers to deploy, configure, and manage virtual machines, platforms, and application code.

> "DaaS" is incorrect. DaaS provides virtual desktops, but not systems company applications, for customers.

---

### Question 45  Security and Compliance

Which process involves determining the security controls that are necessary for a piece of data based on its sensitivity and value?

Classification

Discovery

Labeling

#### Explanation

> "Classification" is correct. Classification involves taking data and assessing its risk, value, and sensitivity to determine which security controls are necessary.

> "Discovery" is incorrect. Discovery is the process of locating data that needs to be analyzed and classified for security controls.

> "Labeling" is incorrect. Labeling is typically used to categorize data by type or group for analysis or reporting.

> "Hashing" is incorrect. Hashing involves setting a fixed-length value on a data object to be used for integrity checks.

---

### Question 46  Cloud Concepts

Which cloud deployment model is associated with many popular services such as iCloud, OneDrive, and Instagram?

SaaS

IaaS

PaaS

DaaS

#### Explanation

> "SaaS" is correct. Cloud services such as iCloud, Instagram, and OneDrive are all examples of SaaS implementations where the application is fully featured and just utilized by users.

> "PaaS" is incorrect. A PaaS implementation offers a framework for developers to deploy code and data into, but is not a functional application for users.

> "IaaS" is incorrect. An IaaS implementation provides underlying network and hardware resources for administrators to deploy virtual machines into and then build their systems on top of.

> "DaaS" is incorrect. A DaaS implementation provides a virtual desktop for users to access from anywhere and with software installed and ready to use, but is not an example of systems such as iCloud, OneDrive, and Instagram.

---

### Question 47  Cloud Technology and Services

Which service of the AWS Systems Manager provides playbooks to perform tasks, both those provided by AWS and ones that can be custom-written by users?

Automation

AWS AppConfig

Patch Manager

OpsCenter

#### Explanation

> "Automation" is correct. Automation provides a set of predefined playbooks to do common repetitive tasks but also allows for users to create their own playbooks that are appropriate for their specific services.

> "AWS AppConfig" is incorrect. AWS AppConfig provides an API and console method for applying configuration changes across AWS services from a centralized service.

> "OpsCenter" is incorrect. OpsCenter provides a consolidated view for developers and operations staff to view and investigate any operational issues.

> "Patch Manager" is incorrect. Patch Manager allows for automatically handling patching of systems across EC2 or on-premises systems through the use of baselines.

---

### Question 48  Cloud Technology and Services

Which notation correctly identifies an Availability Zone within AWS?
us-east-1-1

eu-west-1a

sa-east-1-a

us-west-1.a

#### Explanation

> "eu-west-1a" is correct. Availability Zones are notated by a lowercase letter at the end of the region name.

> The other answers are incorrect because they do not have the proper notations at the end of the region names.

### Question 49  Cloud Technology and Services

Security groups are virtual firewalls within an AWS VPC. Which of the following is true about how security groups are applied?

Security groups only apply to traffic within the VPC.

Security groups only apply to inbound traffic.

Security groups only apply to outbound traffic.

Security groups apply to both inbound and outbound traffic.

#### Explanation

> "Security groups apply to both inbound and outbound traffic is correct. Security groups can apply to both inbound and outbound traffic and can have different rules for both.

> "Security groups only apply to inbound traffic is incorrect. Security groups can apply to both inbound and outbound traffic.

> "Security groups only apply to outbound traffic is incorrect. Security groups can apply to both inbound and outbound traffic.

> "Security groups only apply to traffic within the VPC is incorrect. Security groups apply to traffic flowing in and out of the VPC, not just between services.

---

### Question 50  Security and Compliance

Which protocol is the most commonly used to protect data in transit with applications and services?

HTTPS

SCP

FTP

SMTP

#### Explanation

> "HTTPS" is correct. HTTPS, whether through browser and client interactions with applications or through API calls, is the most commonly used protocol for securing data in transit.

> "FTP" is incorrect. FTP is used for file transfers but does not provide any security or encryption.

> "SMTP" is incorrect. SMTP is used for sending e-mail messages but does not provide any security or encryption.

> "SCP" is incorrect. While SCP provides secure transfer of data files, it is not used commonly within applications and services compared to HTTPS.

---

### Question 51  Security and Compliance

Which is the lowest support plan you would need to choose in order to get access to the AWS Trusted Advisor?

Business

Free

Developer

Enterprise

#### Explanation

> "Developer" is correct. The Developer support plan provides access to the seven core Advisor checks. This will give guidance on best practices of reducing costs and how to get the most out of performance, implement and improve fault tolerance, and improve security.

> "Free" is incorrect. The Free support plan does not provide access to the AWS Trusted Advisor.

> "Enterprise" is incorrect. The Enterprise support plan does provide full access to the AWS Trusted Advisor but is a higher plan than the Developer plan.

> "Business" is incorrect. The Business support plan does provide full access to the AWS Trusted Advisor but is a higher plan than the Developer plan.

---

### Question 52  Cloud Concepts

Which core aspect of cloud computing refers to users only paying for specific services that they use and only during the time in which they are in use?

Multitenancy

Resource pooling

On-demand self-service

Metered service

#### Explanation

> "Metered service" is correct. Metered service refers to only paying for services that you use and only during the time in which you are using them.

> "Resource pooling" is incorrect. Resource pooling refers to users within a cloud all sharing and having access to the same large pool of overall resources.

> "On-demand self-service" is incorrect. On-demand self-service refers to the ability of a user to access a management console, like a web portal, and provision resources at any time without having to involve personnel from the cloud company.

> "Multitenancy" is incorrect. Multitenancy refers to many different accounts and users living within the same overall environment and resources.

---

### Question 53  Security and Compliance

Which security concept is the use of hashing associated with?

Confidentiality

Integrity

Privacy

Availability

#### Explanation

> "Integrity" is correct. The main value of hashing is to quickly verify the integrity of data objects. Within a cloud environment, this can bring great value, with virtual machine images and the potentially large number of data locations within a dispersed environment. As many copies of a file are potentially stored in many different locations, hashing can be used to quickly verify that the files are of identical composure and that the integrity of them has not been compromised.

> "Confidentiality" is incorrect. The use of hashing will not offer any protection for confidentiality of a data object.

> "Availability" is incorrect. Hashing will not have any impact on availability of a data object.

> "Privacy" is incorrect. Like confidentiality, hashing will not offer any protection for the privacy of data in an object.

---

### Question 54  Cloud Technology and Services

Access control list (ACLs) are security layers on the VPC that control traffic at the subnet level. Which of the following statements about ACLs is incorrect?

ACLS can have different inbound and outbound rules.

Every subnet must have an ACL assigned to it.

ACLs are composed only of ALLOW rules.

ACLs have numbered rules that are processed in order.

#### Explanation

> "ACLs are composed only of ALLOW rules" is correct. Unlike security groups, ACLs are composed of both ALLOW and DENY rules.

> "ACLS can have different inbound and outbound rules" is incorrect. ACLs have both inbound and outbound rules that can differ.

> "Every subnet must have an ACL assigned to it" is incorrect. All subnets in AWS must have an ACL assigned to them. A default rule will be applied if a custom one is not configured.

> "ACLs have numbered rules that are processed in order" is incorrect. ACLs are composed of a numbered set of rules that are processed and applied in order.

---

### Question 55  Cloud Technology and Services

What is the main difference between AWS Shield and AWS WAF?

AWS Shield protects storage services; AWS WAF protects compute services.

AWS Shield protects at the Layer 7 content level, while AWS WAF protects at the Layer 3 and 4 network traffic levels.

AWS Shield protects from external attacks, whereas AWS WAF protects between services within AWS.

AWS Shield protects at the Layer 3 and 4 network levels, while AWS WAF protects at the Layer 7 content level.

#### Explanation

> "AWS Shield protects at the Layer 3 and 4 network levels, while AWS WAF protects at the Layer 7 content level" is correct. Shield operates at the Layer 3 and 4 networks levels and is used to prevent DDoS attacks, versus WAF that operates at the Layer 7 content level and can take action based on the specific contents of web traffic and requests.

> "AWS Shield protects at the Layer 7 content level, while AWS WAF protects at the Layer 3 and 4 network traffic levels" is incorrect. The protection focus is reversed for the services.

> "AWS Shield protects storage services; AWS WAF protects compute services" is incorrect. AWS Shield and AWS WAF are not tied to specific services such as storage and compute.

> "AWS Shield protects from external attacks, whereas AWS WAF protects between services within AWS" is incorrect. AWS Shield and AWS WAF protect regardless of the origin of the traffic.

---

### Question 56  Cloud Technology and Services

Select two prominent headers for drop-down menus that appear across the top of the AWS Management Console.

Automation

Cost Explorer

Dashboard

Regions

Services

#### Explanation

> "Regions" and "Services" are correct. Both Regions and Services are two of the main drop-down headers on the AWS Management Console.

> "Billing Dashboard" is incorrect. The Billing Dashboard does not appear as a major header item on the Management Console.

> "Automation" is incorrect. Automation is an aspect of many AWS Services but does not appear as its own menu item.

> "Cost Explorer" is incorrect. Cost Explorer is part of the Billing Dashboard and not a main menu item.

---

### Question 57  Security and Compliance

Prior to performing data classification, which process must first be performed?

Discovery

Identification

Location

Tokenization

#### Explanation

> "Discovery" is correct. Discovery is the process by which all data is located prior to the application of classification for security controls and policies.

> "Location" is incorrect. Location is a similar-sounding term to discovery but is incorrect.

> "Identification" is incorrect. Identification is a similar-sounding term to discovery but is incorrect.

> "Tokenization" is incorrect. Tokenization is the practice of utilizing a random and opaque “token” value in data to replace what otherwise would be a sensitive or protected data object.

---

### Question 58  Security and Compliance

With a Platform as a Service (PaaS) implementation, which two areas of responsibility lie with the cloud user?

Operating system

Storage

Networking

Data

Application code

#### Explanation

> "Data" and "Application code" are correct. With PaaS, both the data and application code are the responsibility of the user and fall outside of the managed services.

> "Operating system" is incorrect. With PaaS, the operating system is a managed service and the responsibility of the cloud provider.

> "Storage" is incorrect. With PaaS, the storage is the responsibility of the cloud provider.

> "Networking" is incorrect. With PaaS, networking is the responsibility of the cloud provider.

---

### Question 59  Cloud Concepts

Which key concept of cloud computing allows the resources to an application to be expanded to meet increased demand of the user without having to provision for maximum capacity in advance?

Metered service

Resource pooling

Multitenancy

Elasticity

#### Explanation

> "Elasticity" is correct. Elasticity allows for resources to be changed when needed to meet demand without having to fully provision ahead of time.

> "Metered service" is incorrect. Metered service refers to cloud resources only incurring charges when utilized.

> "Multitenancy" is incorrect. Multitenancy refers to the hosting of multiple cloud customers without the same hardware systems.

> "Resource pooling" is incorrect. Resource pooling refers to many different systems and users sharing the same large set of resources.

---

### Question 60  Cloud Technology and Services

You want to restrict inbound requests to an EC2 instance, but you also want the systems to have the ability to automatically respond to those allowed requests without having to specifically allow the responses. Which AWS service would you use to accomplish this?

AWS Shield

Security groups

Subnets

ACLs

#### Explanation

> "Security groups" is correct. Security groups will automatically allow traffic in response to a request made by an allowed rule. For example, if an inbound request is allowed to be made, the corresponding reply is allowed to be made as well, regardless of what the rules specifically allow.

> "Subnets" is incorrect. Subnets are used to segment a network and define IP address spaces. They do not perform security functions.

> "ACLs" is incorrect. Unlike security groups, ACL rules do not automatically have state and allow responses to queries. If an inbound request is made and allowed, an applicable outbound rule must be in place to allow the response to transmit.

> "AWS Shield" is incorrect. AWS Shield is an AWS service to prevent DDoS attacks.

---

### Question 61  Cloud Concepts

Within a cloud environment, which of the following is not a shared resource between tenants or customers?

Memory

Data

CPU

Storage

#### Explanation

> "Data" is correct. Data belongs to a cloud customer and is not a shared resource within a cloud environment.

> The other answers are incorrect. The core building blocks of computing, including CPU, memory, and storage, are all shared between the tenants in a cloud environment.

---

### Question 62  Cloud Concepts

While AWS has the capabilities to meet many different hosting needs and models, which cloud deployment model best describes AWS as a whole?

Hybrid

Public

Community

Private

#### Explanation

> "Public" is correct. AWS services are open to anyone who establishes an account and can provide a billing source, such as a credit card.

> The other answers are incorrect. While some services and regions within AWS are restricted, AWS as a whole fits a public cloud model.

---

### Question 63  Security and Compliance

If your application utilizes or stores any type of sensitive information, you will need to comply with specific regulatory requirements. Which AWS service would provide information on AWS certifications with major governing bodies and regulations?

AWS Artifact

AWS Billing Console

AWS CloudTrail

AWS Systems Manager

#### Explanation

> "AWS Artifact" is correct. As part of the Artifact service, AWS undergoes certification reviews and audits by various governing bodies. This includes prominent certifications such as PCI DSS for financial/credit card transactions and FedRAMP for U.S. federal government systems. AWS also makes the pertinent SOC audit reports available to customers.

> "AWS CloudTrail" is incorrect. CloudTrail will collect and centralize logs and other audit data, but it does not give information as to regulatory compliance and certifications.

> "AWS Systems Manager" is incorrect. The AWS Systems Manager is used for viewing, executing, and automating many tasks within AWS, but does not provide information on certifications.

> "AWS Billing Console" is incorrect. The AWS Billing Console does not give information on regulatory compliance or certifications.

---

### Question 64  Billing and Pricing and Support

What feature does the AWS Pricing Calculator offer for users to organize services for estimates?

Groups

Projects

Services

Units

#### Explanation

> "Groups" is correct. The AWS Pricing Calculator offers the use of groups to organize estimates.

> The other answers are incorrect. All are extraneous answers.

---

### Question 65  Cloud Concepts

Which computing concept allows the provisioning of services within a large pool of resources and sharing the same hardware infrastructure via a hypervisor?

Virtualization

Metered service

Containers

Elasticity

#### Explanation

> "Virtualization" is correct. Virtualization allows the deployment of systems and services within a shared hardware environment as the underlying hardware is segregated from the systems within it by a hypervisor.

> "Elasticity" is incorrect. Elasticity allows for resources to be changed when needed to meet demand without having to fully provision ahead of time.

> "Containers" is incorrect. Containers are a type of virtual hosting for fully configured application or system deployments that are hosted within a larger system.

> "Metered service" is incorrect. Metered service refers to cloud resources only incurring charges when utilized.
