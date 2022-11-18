# AWS Certified Cloud Practitioner Exam

## Udemy - Exam 04

**Question 1**

1. Which of the following S3 storage classes do not charge any data retrieval fee? (Select two)
*  A. S3 Glacier
*  B. S3 One Zone-IA
*  C. S3 Standard
*  D. S3 Intelligent-Tiering
*  E. S3 Standard-IA

**Answer** C, D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>S3 Standard</strong> - S3 Standard offers high durability, availability, and performance object storage for frequently accessed data. S3 Standard offers low latency and high throughput performance, It is designed for durability of 99.999999999% of objects across multiple Availability Zones. S3 Standard does not charge any data retrieval fee.</p>
 <p><strong>S3 Intelligent-Tiering</strong> - The S3 Intelligent-Tiering storage class is designed to optimize costs by automatically moving data to the most cost-effective access tier, without performance impact or operational overhead. It works by storing objects in two access tiers: one tier that is optimized for frequent access and another lower-cost tier that is optimized for infrequent access. S3 Intelligent-Tiering does not charge any data retrieval fee.</p>
 <p>Please review this illustration for the S3 Storage Classes retrieval fee. You don't need to memorize the actual numbers, just remember that S3 Standard and S3 Intelligent-Tiering do not charge any retrieval fee: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q13-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/s3/storage-classes/">https://aws.amazon.com/s3/storage-classes/</a></p>
 <p>Incorrect options:</p>
 <p><strong>S3 Glacier</strong> - Amazon S3 Glacier is a secure, durable, and extremely low-cost Amazon S3 cloud storage class for data archiving and long-term backup. It is designed to deliver 99.999999999% durability, and provide comprehensive security and compliance capabilities that can help meet even the most stringent regulatory requirements. S3 Glacier has a data retrieval fee.</p>
 <p><strong>S3 One Zone-IA</strong> - S3 One Zone-IA is for data that is accessed less frequently, but requires rapid access when needed. Unlike other S3 Storage Classes which store data in a minimum of three Availability Zones (AZs), S3 One Zone-IA stores data in a single AZ. It is not suitable for data archival. S3 One Zone-IA has a data retrieval fee.</p>
 <p><strong>S3 Standard-IA</strong> - S3 Standard-IA is for data that is accessed less frequently, but requires rapid access when needed. S3 Standard-IA offers high durability, high throughput, and low latency of S3 Standard, with a low per GB storage price and per GB retrieval fee. This combination of low cost and high performance makes S3 Standard-IA ideal for long-term storage, backups, and as a data store for disaster recovery files. S3 Standard-IA has a data retrieval fee.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/s3/storage-classes/">https://aws.amazon.com/s3/storage-classes/</a></p>
</div>

**Question 2**

2. A media company uploads its media (audio and video) files to a centralized S3 bucket from geographically dispersed locations. Which of the following solutions can the company use to optimize transfer speeds?
*  A. Amazon CloudFront
*  B. AWS Direct Connect
*  C. AWS Global Accelerator
*  D. S3 Transfer Acceleration

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>S3 Transfer Acceleration</strong></p>
 <p>Amazon S3 Transfer Acceleration (S3TA) enables fast, easy, and secure transfers of files over long distances between your client and your Amazon S3 bucket. S3 Transfer Acceleration leverages Amazon CloudFront’s globally distributed AWS Edge Locations. As data arrives at an AWS Edge Location, data is routed to your Amazon S3 bucket over an optimized network path. S3 Transfer Acceleration is designed to optimize transfer speeds from across the world into S3 buckets. If you are uploading to a centralized bucket from geographically dispersed locations, or if you regularly transfer GBs or TBs of data across continents, you may save hours or days of data transfer time with S3 Transfer Acceleration.</p>
 <p>Benefits of S3 Transfer Acceleration (S3TA): <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q33-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/s3/transfer-acceleration/">https://aws.amazon.com/s3/transfer-acceleration/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon CloudFront</strong> - Amazon CloudFront is a fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency, high transfer speeds, all within a developer-friendly environment. CloudFront is used for content delivery than for data uploads. CloudFront caches data and a subsequent request for a webpage will not go to the origin server, but will be served from the cache. S3 Transfer Acceleration is a better option for the given use-case.</p>
 <p><strong>AWS Direct Connect</strong> - AWS Direct Connect is a cloud service solution that makes it easy to establish a dedicated network connection from your premises to AWS. You can use AWS Direct Connect to establish a private virtual interface from your on-premise network directly to your Amazon VPC. This private connection takes at least one month for completion. You cannot use Direct Connect to optimize media uploads into S3.</p>
 <p><strong>AWS Global Accelerator</strong> - AWS Global Accelerator is a service that improves the availability and performance of your applications with local or global users. It provides static IP addresses that act as a fixed entry point to your application endpoints in a single or multiple AWS Regions, such as your Application Load Balancers, Network Load Balancers or Amazon EC2 instances. Similar to CloudFront it uses AWS Global network and edge locations for enhanced performance. It's an overall performance enhancer than an upload speed accelerator. You cannot use Global Accelerator to optimize media uploads into S3.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/s3/transfer-acceleration/">https://aws.amazon.com/s3/transfer-acceleration/</a></p>
</div>

**Question 3**

3. Which AWS service can help you analyze your infrastructure to identify unattached or underutilized EBS volumes?
*  A. Amazon Inspector
*  B. Amazon CloudWatch
*  C. AWS Config
*  D. AWS Trusted Advisor

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Trusted Advisor</strong></p>
 <p>AWS Trusted Advisor is an online tool that provides real-time guidance to help provision your resources following AWS best practices. Whether establishing new workflows, developing applications, or as part of ongoing improvement, recommendations provided by Trusted Advisor regularly help keep your solutions provisioned optimally. AWS Trusted Advisor analyzes your AWS environment and provides best practice recommendations in five categories: Cost Optimization, Performance, Security, Fault Tolerance, Service Limits.</p>
 <p>AWS Trusted Advisor can check Amazon Elastic Block Store (Amazon EBS) volume configurations and warns when volumes appear to be underused. Charges begin when a volume is created. If a volume remains unattached or has very low write activity (excluding boot volumes) for a period of time, the volume is probably not being used.</p>
 <p>How Trusted Advisor Works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/AWS-trusted-advisor.5b9909d5f29f680eeb12ccff536e8d88d8701304.png?raw=true"> via - <a href="https://aws.amazon.com/premiumsupport/technology/trusted-advisor/">https://aws.amazon.com/premiumsupport/technology/trusted-advisor/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS Config</strong> - AWS Config is a service that enables you to assess, audit, and evaluate the configurations of your AWS resources. Config continuously monitors and records your AWS resource configurations and allows you to automate the evaluation of recorded configurations against desired configurations. Think resource-specific change history, audit, and compliance; think Config. Its a configuration tracking service and not an infrastructure tracking service.</p>
 <p><strong>Amazon CloudWatch</strong> - Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers. CloudWatch provides data and actionable insights to monitor applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health. Amazon EBS emits notifications based on Amazon CloudWatch Events for a variety of volume, snapshot, and encryption status changes. With CloudWatch Events, you can establish rules that trigger programmatic actions in response to a change in volume, snapshot, or encryption key state (though not for underutilized volume usage).</p>
 <p><strong>Amazon Inspector</strong> - Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on your Amazon EC2 instances. Amazon Inspector automatically assesses applications for exposure, vulnerabilities, and deviations from best practices. Its a security assessment service and not an infrastructure tracking service.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/premiumsupport/technology/trusted-advisor/best-practice-checklist/">https://aws.amazon.com/premiumsupport/technology/trusted-advisor/best-practice-checklist/</a></p>
 <p><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-cloud-watch-events.html">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-cloud-watch-events.html</a></p>
</div>

**Question 4**

4. Which of the following is the best practice for application architecture on AWS Cloud?
*  A. Build monolithic applications
*  B. Use synchronous communication between components
*  C. Build loosely coupled components
*  D. Build tightly coupled components

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Build loosely coupled components</strong></p>
 <p>AWS Cloud recommends microservices as an architectural and organizational approach to software development where software is composed of small independent services that communicate over well-defined APIs. These services are owned by small, self-contained teams.</p>
 <p>Microservices architectures make applications easier to scale and faster to develop, enabling innovation and accelerating time-to-market for new features. Each service can be considered as a loosely coupled component of a bigger system. You can use services like SNS or SQS to decouple and scale microservices.</p>
 <p>Microservices Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q6-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/blogs/compute/understanding-asynchronous-messaging-for-microservices/">https://aws.amazon.com/blogs/compute/understanding-asynchronous-messaging-for-microservices/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Build tightly coupled components</strong></p>
 <p><strong>Build monolithic applications</strong></p>
 <p>With monolithic architectures, all processes are tightly coupled and run as a single service. This means that if one process of the application experiences a spike in demand, the entire architecture must be scaled. Monolithic architectures add risk for application availability because many dependent and tightly coupled processes increase the impact of a single process failure. So both these options are incorrect.</p>
 <p><strong>Use synchronous communication between components</strong> - Synchronous between applications can be problematic if there are sudden spikes of traffic. You should use SNS or SQS to decouple your application components.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/blogs/compute/understanding-asynchronous-messaging-for-microservices/">https://aws.amazon.com/blogs/compute/understanding-asynchronous-messaging-for-microservices/</a></p>
</div>

**Question 5**

5. Which of the following are recommended security best practices for the AWS account root user? (Select two)
*  A. Set up an IAM user with administrator permissions and do not use AWS account root user for administrative tasks
*  B. Disable MFA for the AWS account root user as it can lock the entire AWS account if the MFA device is lost
*  C. Enable MFA for the AWS account root user
*  D. Keep your AWS account root user access keys in an encrypted file on S3
*  E. Share AWS account root user access keys with other administrators

**Answer** A, C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>Enable MFA for the AWS account root user</strong></p>
 <p><strong>Set up an IAM user with administrator permissions and do not use AWS account root user for administrative tasks</strong></p>
 <p>When you create an AWS account, you create an AWS account root user identity, which you use to sign in to AWS. You can sign in to the AWS Management Console using this root user identity—that is, the email address and password that you provided when creating the account. This combination of your email address and password is also called your root user credentials.</p>
 <p>Some of the AWS account root user security best practices are as follows:</p>
 <p>Do not use the AWS account root user for any task where it's not required. Instead, create a new IAM user for each person that requires administrator access. Then make those users administrators by placing the users into an "Administrators" group to which you attach the AdministratorAccess managed policy.</p>
 <p>If you don't already have an access key for your AWS account root user, don't create one unless you need to. If you do have an access key for your AWS account root user, delete it.</p>
 <p>Never share your AWS account root user password or access keys with anyone. Use a strong password to help protect account-level access to the AWS Management Console.</p>
 <p>Enable AWS multi-factor authentication (MFA) on your AWS account root user account.</p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q9-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#lock-away-credentials">https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#lock-away-credentials</a></p>
 <p>Incorrect options:</p>
 <p><strong>Disable MFA for the AWS account root user as it can lock the entire AWS account if the MFA device is lost</strong> - AWS recommends that you enable AWS multi-factor authentication (MFA) on your AWS account root user account.</p>
 <p><strong>Keep your AWS account root user access keys in an encrypted file on S3</strong> - AWS recommends that if you do have an access key for your AWS account root user, delete it.</p>
 <p><strong>Share AWS account root user access keys with other administrators</strong> - The access key for your AWS account root user gives full access to all your resources for all AWS services, including your billing information. You cannot reduce the permissions associated with your AWS account root user access key. You should never share these access keys with any other users, not even the administrators.</p>
 <p>References:</p>
 <p><a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#lock-away-credentials">https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#lock-away-credentials</a></p>
 <p><a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/getting-started_create-admin-group.html">https://docs.aws.amazon.com/IAM/latest/UserGuide/getting-started_create-admin-group.html</a></p>
</div>

**Question 6**

6. AWS Organizations provides which of the following benefits? (Select two)
*  A. Check vulnerabilities on EC2 instances across the member AWS accounts
*  B. Provision EC2 Spot instances across the member AWS accounts
*  C. Deploy patches on EC2 instances across the member AWS accounts
*  D. Share the reserved EC2 instances amongst the member AWS accounts
*  E. Volume discounts for Amazon EC2 and Amazon S3 aggregated across the member AWS accounts

**Answer** D, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Volume discounts for Amazon EC2 and Amazon S3 aggregated across the member AWS accounts</strong></p>
 <p><strong>Share the reserved EC2 instances amongst the member AWS accounts</strong></p>
 <p>AWS Organizations helps you to centrally manage billing; control access, compliance, and security; and share resources such as reserved EC2 instances across your AWS accounts.</p>
 <p>Using AWS Organizations, you can automate account creation, create groups of accounts to reflect your business needs, and apply policies for these groups for governance. You can also simplify billing by setting up a single payment method for all of your AWS accounts. AWS Organizations is available to all AWS customers at no additional charge.</p>
 <p>You can use AWS Organizations to set up a single payment method for all the AWS accounts in your organization through consolidated billing. With consolidated billing, you can see a combined view of charges incurred by all your accounts, as well as take advantage of pricing benefits from aggregated usage, such as volume discounts for Amazon EC2 and Amazon S3.</p>
 <p>Key benefits of AWS Organizations: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q50-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/organizations/">https://aws.amazon.com/organizations/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Check vulnerabilities on EC2 instances across the member AWS accounts</strong></p>
 <p><strong>Deploy patches on EC2 instances across the member AWS accounts</strong></p>
 <p><strong>Provision EC2 Spot instances across the member AWS accounts</strong></p>
 <p>These three options contradict the details provided earlier in the explanation, so these options are incorrect.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/organizations/">https://aws.amazon.com/organizations/</a></p>
</div>

**Question 7**

7. Reserved Instance pricing is available for which of the following AWS services? (Select two)
*  A. AWS Identity & Access Management (IAM)
*  B. Amazon CloudFront
*  C. Amazon Relational Database Service (Amazon RDS)
*  D. Amazon Simple Storage Service (Amazon S3)
*  E. Amazon Elastic Compute Cloud (Amazon EC2)

**Answer** C, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>Amazon Elastic Compute Cloud (Amazon EC2)</strong></p>
 <p><strong>Amazon Relational Database Service (Amazon RDS)</strong></p>
 <p>A Reserved Instance is a reservation that provides a discounted hourly rate in exchange for an upfront fee and term contract. Services such as Amazon Elastic Compute Cloud (Amazon EC2) and Amazon Relational Database Service (Amazon RDS) use this approach to sell reserved capacity for hourly use of Reserved Instances. It is not a virtual machine. It is a commitment to pay in advance for specific Amazon EC2 or Amazon RDS instances.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon CloudFront</strong> - Amazon CloudFront is a content delivery network (CDN) service. CloudFront does not offer "Reserved Capacity" pricing.</p>
 <p><strong>Amazon Simple Storage Service (Amazon S3)</strong> - Amazon S3 infrastructure is managed by AWS. So, Reserved Instance does not make sense here. But, S3 offers volume discounts for its storage classes.</p>
 <p><strong>AWS Identity &amp; Access Management (IAM)</strong> - AWS Identity and Access Management (IAM) enables you to manage access to AWS services and resources securely. Using IAM, you can create and manage AWS users and groups, and use permissions to allow and deny their access to AWS resources. This is a free service to every AWS customer.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/con-bill-blended-rates.html">https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/con-bill-blended-rates.html</a></p>
</div>

**Question 8**

8. Bob and Susan each have an AWS account in AWS Organizations. Susan has five Reserved Instances (RIs) of the same type and Bob has none. During one particular hour, Susan uses three instances and Bob uses six for a total of nine instances on the organization's consolidated bill.
*  A. Bob receives the cost-benefit from Susan's Reserved Instances only if he launches his instances in the same Region where Susan purchased her Reserved Instances
*  B. Bob receives the cost-benefit from Susan's Reserved Instances only if he launches his instances in the same Availability Zone where Susan purchased her Reserved Instances
*  C. AWS bills three instances as Reserved Instances, and the remaining six instances as regular instances
*  D. Bob does not receive any cost-benefit since he hasn't purchased any RIs. If his account has even one RI, then the cost-benefit from Susan's account is also added to his account
*  E. AWS bills five instances as Reserved Instances, and the remaining four instances as regular instances

**Answer** B, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>Bob receives the cost-benefit from Susan's Reserved Instances only if he launches his instances in the same Availability Zone where Susan purchased her Reserved Instances</strong> - Bob receives the cost-benefit from Susan's Reserved Instances only if he launches his instances in the same Availability Zone where Susan purchased her Reserved Instances. For example, if Susan specifies us-west-2a when she purchases her Reserved Instances, Bob must specify us-west-2a when he launches his instances to get the cost-benefit on the organization's consolidated bill. However, the actual locations of Availability Zones are independent of one account to another. For example, the us-west-2a Availability Zone for Bob's account might be in a different location than the location for Susan's account.</p>
 <p><strong>AWS bills five instances as Reserved Instances, and the remaining four instances as regular instances</strong> - Since Susan has five Reserved Instances (RIs), AWS bills five instances as Reserved Instances, and the remaining four instances as regular instances.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS bills three instances as Reserved Instances, and the remaining six instances as regular instances</strong> - This option contradicts the explanation provided above, so it's incorrect.</p>
 <p><strong>Bob does not receive any cost-benefit since he hasn't purchased any RIs. If his account has even one RI, then the cost-benefit from Susan's account is also added to his account</strong> - For billing purposes, the consolidated billing feature of AWS Organizations treats all the accounts in the organization as one account. This means that all accounts in the organization can receive the hourly cost-benefit of Reserved Instances that are purchased by any other account.</p>
 <p><strong>Bob receives the cost-benefit from Susan's Reserved Instances only if he launches his instances in the same Region where Susan purchased her Reserved Instances</strong> - As discussed above, this statement is incorrect. Bob receives the cost-benefit from Susan's Reserved Instances only if he launches his instances in the same Availability Zone where Susan purchased her Reserved Instances.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/consolidatedbilling-other.html">https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/consolidatedbilling-other.html</a></p>
</div>

**Question 9**

9. An e-commerce company has migrated its IT infrastructure from the on-premises data center to AWS Cloud. Which of the following costs is the company responsible for?
*  A. Costs for powering servers on AWS Cloud
*  B. Costs for hardware infrastructure on AWS Cloud
*  C. Application software license costs
*  D. AWS Data Center physical security costs

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Application software license costs</strong></p>
 <p>Cloud computing is the on-demand delivery of compute power, database storage, applications, and other IT resources through a cloud services platform via the Internet with pay-as-you-go pricing. With cloud computing, you don’t need to make large upfront investments in hardware and spend a lot of time on the heavy lifting of managing that hardware. Therefore, all costs for hardware infrastructure, powering servers and physical security for the Data Center fall under the ambit of AWS.</p>
 <p>The customer needs to take care of software licensing costs and human resources costs.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Data Center physical security costs</strong></p>
 <p><strong>Costs for hardware infrastructure on AWS Cloud</strong></p>
 <p><strong>Costs for powering servers on AWS Cloud</strong></p>
 <p>As per the details mentioned in the explanation above, these three options are not correct for the given use-case.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/whitepapers/latest/aws-overview/what-is-cloud-computing.html">https://docs.aws.amazon.com/whitepapers/latest/aws-overview/what-is-cloud-computing.html</a></p>
</div>

**Question 10**

10. Which of the following S3 storage classes has NO constraint of a minimum storage duration charge for objects?
*  A. S3 One Zone-IA
*  B. S3 Standard-IA
*  C. S3 Glacier
*  D. S3 Standard

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p>Correct options:</p>
 <p><strong>S3 Standard</strong> - S3 Standard offers high durability, availability, and performance object storage for frequently accessed data. S3 Standard offers low latency and high throughput performance, It is designed for durability of 99.999999999% of objects across multiple Availability Zones. S3 Standard has no constraint of a minimum storage duration for objects.</p>
 <p>Please review this illustration for S3 Storage Classes retrieval fee. You don't need to memorize the actual numbers, just remember that S3 Standard and S3 Intelligent-Tiering do not charge any retrieval fee: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q25-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/s3/storage-classes/">https://aws.amazon.com/s3/storage-classes/</a></p>
 <p>Incorrect options:</p>
 <p><strong>S3 Glacier</strong> - Amazon S3 Glacier is a secure, durable, and extremely low-cost Amazon S3 cloud storage class for data archiving and long-term backup. It is designed to deliver 99.999999999% durability, and provide comprehensive security and compliance capabilities that can help meet even the most stringent regulatory requirements. S3 Glacier mandates a minimum storage duration charge for 90 days.</p>
 <p><strong>S3 One Zone-IA</strong> - S3 One Zone-IA is for data that is accessed less frequently, but requires rapid access when needed. Unlike other S3 Storage Classes which store data in a minimum of three Availability Zones (AZs), S3 One Zone-IA stores data in a single AZ. It is not suitable for data archival. S3 One Zone-IA mandates a minimum storage duration charge for 30 days.</p>
 <p><strong>S3 Standard-IA</strong> - S3 Standard-IA is for data that is accessed less frequently, but requires rapid access when needed. S3 Standard-IA offers high durability, high throughput, and low latency of S3 Standard, with a low per GB storage price and per GB retrieval fee. This combination of low cost and high performance makes S3 Standard-IA ideal for long-term storage, backups, and as a data store for disaster recovery files. S3 Standard-IA mandates a minimum storage duration charge for 30 days.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/s3/storage-classes/">https://aws.amazon.com/s3/storage-classes/</a></p>
</div>

**Question 11**

11. Which pillar of AWS Well-Architected Framework is responsible for making sure that you select the right resource types and sizes based on your workload requirements?
*  A. Performance Efficiency
*  B. Cost Optimization
*  C. Reliability
*  D. Operational Excellence

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p>The AWS Well-Architected Framework helps you understand the pros and cons of decisions you make while building systems on AWS. By using the Framework you will learn architectural best practices for designing and operating reliable, secure, efficient, and cost-effective systems in the cloud. It provides a way for you to consistently measure your architectures against best practices and identify areas for improvement.</p>
 <p>The AWS Well-Architected Framework is based on six pillars — Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization and Sustainability.</p>
 <p>Overview of the six pillars of the Well-Architected Framework: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q28-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/architecture/well-architected/">https://aws.amazon.com/architecture/well-architected/</a></p>
 <p><strong>Performance Efficiency</strong> - The performance efficiency pillar focuses on using IT and computing resources efficiently. Key topics include selecting the right resource types and sizes based on workload requirements, monitoring performance, and making informed decisions to maintain efficiency as business needs evolve.</p>
 <p>Incorrect options:</p>
 <p><strong>Cost Optimization</strong> - Cost Optimization focuses on avoiding un-needed costs. Key topics include understanding and controlling where the money is being spent, selecting the most appropriate and right number of resource types, analyzing spend over time, and scaling to meet business needs without overspending.</p>
 <p><strong>Reliability</strong> - This refers to the ability of a system to recover from infrastructure or service disruptions, dynamically acquire computing resources to meet demand, and mitigate disruptions such as misconfigurations or transient network issues.</p>
 <p><strong>Operational Excellence</strong> - The Operational Excellence pillar includes the ability to run and monitor systems to deliver business value and to continually improve supporting processes and procedures. In the cloud, you can apply the same engineering discipline that you use for application code to your entire environment. You can define your entire workload (applications, infrastructure) as code and update it with code. You can implement your operations procedures as code and automate their execution by triggering them in response to events.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/architecture/well-architected/">https://aws.amazon.com/architecture/well-architected/</a></p>
</div>

**Question 12**

12. Which entity ensures that your application on Amazon EC2 always has the right amount of capacity to handle the current traffic demand?
*  A. Application Load Balancer
*  B. Network Load Balancer
*  C. Auto Scaling
*  D. Multi AZ deployment

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Auto Scaling</strong></p>
 <p>Auto Scaling helps you ensure that you have the correct number of Amazon EC2 instances available to handle the load for your application. You create collections of EC2 instances, called Auto Scaling groups. You can specify the minimum number of instances in each Auto Scaling group, and Amazon EC2 Auto Scaling ensures that your group never goes below this size.</p>
 <p>EC2 Auto Scaling Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q52-i1.png?raw=true"> via - <a href="https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html">https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Multi AZ deployment</strong> - With Availability Zones, you can design and operate applications and databases that automatically failover between zones without interruption. Multi AZ deployment of EC2 instances provided high availability, it does not help in scaling resources.</p>
 <p><strong>Network Load Balancer</strong> - Network Load Balancer is best suited for load balancing of Transmission Control Protocol (TCP), User Datagram Protocol (UDP) and Transport Layer Security (TLS) traffic where extreme performance is required. It distributes traffic, does not scale resources.</p>
 <p><strong>Application Load Balancer</strong> - An Application Load Balancer serves as the single point of contact for clients. The load balancer distributes incoming application traffic across multiple targets, such as EC2 instances, in multiple Availability Zones. It distributes traffic, does not scale resources.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html">https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html</a></p>
</div>

**Question 13**

13. A cargo shipping company runs its server-fleet on Amazon EC2 instances. Some of these instances host the CRM (Customer Relationship Management) applications that need to be accessible 24*7. These applications are not mission-critical. In case of a disaster, these applications can be managed on a lesser number of instances for some time.
*  A. Pilot Light strategy
*  B. Warm Standby strategy
*  C. Multi-site active-active strategy
*  D. Backup & Restore strategy

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Warm Standby strategy</strong></p>
 <p>When selecting your DR strategy, you must weigh the benefits of lower RTO (recovery time objective) and RPO (recovery point objective) vs the costs of implementing and operating a strategy. The pilot light and warm standby strategies both offer a good balance of benefits and cost.</p>
 <p>This strategy replicates data from the primary Region to data resources in the recovery Region, such as Amazon Relational Database Service (Amazon RDS) DB instances or Amazon DynamoDB tables. These data resources are ready to serve requests. In addition to replication, this strategy requires you to create a continuous backup in the recovery Region. This is because when "human action" type disasters occur, data can be deleted or corrupted, and replication will replicate the bad data. Backups are necessary to enable you to get back to the last known good state.</p>
 <p>The warm standby strategy deploys a functional stack, but at reduced capacity. The DR endpoint can handle requests, but cannot handle production levels of traffic. It may be more, but is always less than the full production deployment for cost savings. If the passive stack is deployed to the recovery Region at full capacity, however, then this strategy is known as “hot standby.” Because warm standby deploys a functional stack to the recovery Region, this makes it easier to test Region readiness using synthetic transactions.</p>
 <p>DR strategies: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q56-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/blogs/architecture/disaster-recovery-dr-architecture-on-aws-part-iii-pilot-light-and-warm-standby/">https://aws.amazon.com/blogs/architecture/disaster-recovery-dr-architecture-on-aws-part-iii-pilot-light-and-warm-standby/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Multi-site active-active strategy</strong> - This strategy uses AWS Regions as your active sites, creating a multi-Region active/active architecture. Generally, two Regions are used. Each Region hosts a highly available, multi-Availability Zone (AZ) workload stack. In each Region, data is replicated live between the data stores and also backed up. This protects against disasters that include data deletion or corruption since the data backup can be restored to the last known good state. Each regional stack serves production traffic effectively. But, this strategy is cost involving and should only be used for mission-critical applications.</p>
 <p><strong>Pilot Light strategy</strong> - Pilot Light, like Warm Standby strategy, replicates data from the primary Region to data resources in the recovery Region, such as Amazon Relational Database Service (Amazon RDS) DB instances or Amazon DynamoDB tables. But, the DR Region in a pilot light strategy (unlike warm standby) cannot serve requests until additional steps are taken. A pilot light in a home furnace does not provide heat to the home. It provides a quick way to light the furnace burners that then provide heat.</p>
 <p>Warm standby can handle traffic at reduced levels immediately. Pilot light requires you to first deploy infrastructure and then scale out resources before the workload can handle requests.</p>
 <p><strong>Backup &amp; Restore strategy</strong> - Backup and Restore is associated with higher RTO (recovery time objective) and RPO (recovery point objective). This results in longer downtimes and greater loss of data between when the disaster event occurs and recovery. However, backup and restore can still be the right strategy for workloads because it is the easiest and least expensive strategy to implement.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/blogs/architecture/disaster-recovery-dr-architecture-on-aws-part-iii-pilot-light-and-warm-standby/">https://aws.amazon.com/blogs/architecture/disaster-recovery-dr-architecture-on-aws-part-iii-pilot-light-and-warm-standby/</a></p>
</div>

**Question 14**

14. How is Amazon EC2 different from traditional hosting systems? (Select two)
*  A. Amazon EC2 can scale with changing computing requirements
*  B. Amazon EC2 provides a pre-configured instance for a fixed monthly cost
*  C. With Amazon EC2, users risk overbuying resources
*  D. Amazon EC2 caters more towards groups of users with similar system requirements so that the server resources are shared across multiple users and the cost is reduced
*  E. With Amazon EC2, developers can launch and terminate the instances anytime they need to

**Answer** A, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p>Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud with support for per-second billing. It is the easiest way to provision servers on AWS Cloud and access the underlying OS.</p>
 <p>Amazon EC2 differs fundamentally with the traditional on-premises hosting systems in the flexibility, control and significant cost savings it offers developers, allowing them to treat Amazon EC2 instance as their own customized server backed by the robust infrastructure of AWS Cloud.</p>
 <p><strong>Amazon EC2 can scale with changing computing requirements</strong> - When computing requirements unexpectedly change, Amazon EC2 can be scaled to match the requirements. Developers can control how many EC2 instances are in use at any given point in time.</p>
 <p><strong>With Amazon EC2, developers can launch and terminate the instances anytime they need to</strong> - Using Amazon EC2, developers can choose not only to launch, terminate, start or shut down instances at any time, but they can also completely customize the configuration of their instances to suit their needs.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon EC2 provides a pre-configured instance for a fixed monthly cost</strong> - This is an incorrect option. EC2 developers enjoy the benefit of paying only for their actual resource consumption with no monthly or upfront costs. Developers can customize their EC2 instances for their application stack.</p>
 <p><strong>With Amazon EC2, users risk overbuying resources</strong> - This is an incorrect statement. Users risk overbuying in traditional hosting services where users pay a fixed, up-front fee irrespective of their actual computing power used. With EC2, users pay only for the actual resources consumed.</p>
 <p><strong>Amazon EC2 caters more towards groups of users with similar system requirements so that the server resources are shared amongst multiple users and the cost is reduced</strong> - This is an incorrect statement. Resources are not shared between users in EC2, which is why the users have the flexibility to start or shutdown the instances as per their requirement. This is not possible for the traditional hosting systems where the resources are shared across users.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/ec2/faqs/">https://aws.amazon.com/ec2/faqs/</a></p>
</div>

**Question 15**

15. Which AWS service would you use to create a logically isolated section of the AWS Cloud where you can launch AWS resources in your virtual network?
*  A. Subnet
*  B. Network Access Control List (NACL)
*  C. Virtual Private Network (VPN)
*  D. Virtual Private Cloud (VPC)

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Virtual Private Cloud (VPC)</strong></p>
 <p>Amazon Virtual Private Cloud (Amazon VPC) is a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define. You have complete control over your virtual networking environment, including the selection of your IP address range, creation of subnets, and configuration of route tables and network gateways. You can easily customize the network configuration of your Amazon VPC using public and private subnets.</p>
 <p>Incorrect options:</p>
 <p><strong>Virtual Private Network (VPN)</strong> - AWS Virtual Private Network (AWS VPN) lets you establish a secure and private encrypted tunnel from your on-premises network to the AWS global network. AWS VPN is comprised of two services: AWS Site-to-Site VPN and AWS Client VPN. You cannot use VPN to create a logically isolated section of the AWS Cloud.</p>
 <p><strong>Subnet</strong> - A subnet is a range of IP addresses within your VPC. A subnet is not an AWS service, so this option is ruled out.</p>
 <p><strong>Network Access Control List (NACL)</strong> - A network access control list (NACL) is an optional layer of security for your VPC that acts as a firewall for controlling traffic in and out of one or more subnets. A NACL is not an AWS service, so this option is ruled out.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/vpc/">https://aws.amazon.com/vpc/</a></p>
</div>

**Question 16**

16. Which of the following are benefits of the AWS Web Application Firewall (WAF)? (Select two)
*  A. WAF offers protection against all known infrastructure (Layer 3 and 4) attacks
*  B. WAF can check for the presence of SQL code that is likely to be malicious (known as SQL injection)
*  C. WAF can block all requests except the ones that you allow
*  D. AWS WAF lets you monitor the HTTP and HTTPS requests that are forwarded to Amazon Route 53
*  E. WAF offers dedicated support from the DDoS Response Team (DRT) and advanced reporting

**Answer** B, C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p>AWS WAF is a web application firewall that helps protect your web applications or APIs against common web exploits that may affect availability, compromise security, or consume excessive resources. AWS WAF gives you control over how traffic reaches your applications by enabling you to create security rules that block common attack patterns such as SQL injection or cross-site scripting. You can also use rate-based rules to mitigate the Web layer DDoS attack.</p>
 <p>How WAF Works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/product-page-diagram_AWS-WAF_How-it-Works@2x.452efa12b06cb5c87f07550286a771e20ca430b9.png?raw=true"> via - <a href="https://aws.amazon.com/waf/">https://aws.amazon.com/waf/</a></p>
 <p><strong>WAF can block all requests except the ones that you allow</strong> - WAF can block all requests except the ones that you allow. This is useful when you want to serve content for a restricted website whose users are readily identifiable by properties in web requests, such as the IP addresses that they use to browse to the website.</p>
 <p><strong>WAF can check for the presence of SQL code that is likely to be malicious (known as SQL injection)</strong> - WAF offers additional protection against web attacks using conditions that you specify. You can define conditions by using characteristics of web requests such as - IP addresses that requests originate from, presence of a script that is likely to be malicious (known as cross-site scripting), presence of SQL code that is likely to be malicious (known as SQL injection) and many more.</p>
 <p>Incorrect options:</p>
 <p><strong>WAF offers protection against all known infrastructure (Layer 3 and 4) attacks</strong> - WAF lets you monitor the HTTP and HTTPS requests to your application, it only works at the application layer (layer 7).</p>
 <p><strong>WAF offers dedicated support from the DDoS Response Team (DRT) and advanced reporting</strong> - As AWS Shield Advanced customer can contact a 24x7 DDoS response team (DRT) for assistance during a DDoS attack, it is a feature of Shield Advanced, and not of WAF.</p>
 <p><strong>AWS WAF lets you monitor the HTTP and HTTPS requests that are forwarded to Amazon Route 53</strong> - AWS WAF is a web application firewall that lets you monitor the HTTP and HTTPS requests that are forwarded to an Amazon API Gateway API, Amazon CloudFront or an Application Load Balancer. It does not cover Amazon Route 53, which is a Domain Name System (DNS) web service.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/waf/latest/developerguide/what-is-aws-waf.html">https://docs.aws.amazon.com/waf/latest/developerguide/what-is-aws-waf.html</a></p>
</div>

**Question 17**

17. Which benefit of Cloud Computing allows AWS to offer lower pay-as-you-go prices as usage from hundreds of thousands of customers is aggregated in the cloud?
*  A. Massive economies of scale
*  B. Trade capital expense for variable expense
*  C. Increased speed and agility
*  D. Go global in minutes

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Massive economies of scale</strong></p>
 <p>Cloud computing is the on-demand delivery of IT resources over the Internet with pay-as-you-go pricing. Instead of buying, owning, and maintaining physical data centers and servers, you can access technology services, such as computing power, storage, and databases, on an as-needed basis.</p>
 <p>By using cloud computing, you can achieve a lower variable cost than you can get on your own. Because usage from hundreds of thousands of customers is aggregated in the cloud, providers such as AWS can achieve higher economies of scale, which translates into lower pay-as-you-go prices.</p>
 <p>Exam Alert:</p>
 <p>Please check out the following six advantages of Cloud Computing. You would certainly be asked questions on the advantages of Cloud Computing compared to a traditional on-premises setup: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q45-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html">https://docs.aws.amazon.com/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Trade Capital Expense for Variable Expense</strong> - Instead of having to invest heavily in data centers and servers before you know how you’re going to use them, you can pay only when you consume computing resources, and pay only for how much you consume.</p>
 <p><strong>Increased Speed and Agility</strong> - In a cloud computing environment, new IT resources are only a click away, which means that you reduce the time to make those resources available to your developers from weeks to just minutes. This results in a dramatic increase in agility for the organization since the cost and time it takes to experiment and develop is significantly lower.</p>
 <p><strong>Go Global in minutes</strong> - Easily deploy your application in multiple regions around the world with just a few clicks. This means you can provide lower latency and a better experience for your customers at minimal cost.</p>
 <p>Although these three options are also benefits of Cloud Computing, it is the massive economies of scale that allow AWS to offer lower pay-as-you-go prices as usage from hundreds of thousands of customers is aggregated in the cloud.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/what-is-cloud-computing/">https://aws.amazon.com/what-is-cloud-computing/</a></p>
 <p><a href="https://docs.aws.amazon.com/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html">https://docs.aws.amazon.com/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html</a></p>
</div>

**Question 18**

18. Which of the following is available across all AWS Support plans?
*  A. Full set of AWS Trusted Advisor best practice checks
*  B. Enhanced Technical Support with unlimited cases and unlimited contacts
*  C. AWS Personal Health Dashboard
*  D. Third-Party Software Support

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p>"AWS Personal Health Dashboard"</p>
 <p>Full set of AWS Trusted Advisor best practice checks, enhanced Technical Support with unlimited cases, and unlimited contacts and third-party Software Support are available only for Business and Enterprise Support plans.</p>
 <p>AWS Personal Health Dashboard is available for all Support plans.</p>
 <p>Exam Alert:</p>
 <p>Please review the differences between the Developer, Business, and Enterprise support plans as you can expect at least a couple of questions on the exam:</p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q14-i1.jpg?raw=true"></p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q14-i2.jpg?raw=true"></p>
 <p>via - <a href="https://aws.amazon.com/premiumsupport/plans/">https://aws.amazon.com/premiumsupport/plans/</a></p>
 <p>Incorrect options:</p>
 <p>"Full set of AWS Trusted Advisor best practice checks"</p>
 <p>"Enhanced Technical Support with unlimited cases and unlimited contacts"</p>
 <p>"Third-Party Software Support"</p>
 <p>As mentioned in the explanation above, these options are available only for Business and Enterprise Support plans.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/premiumsupport/plans/">https://aws.amazon.com/premiumsupport/plans/</a></p>
</div>

**Question 19**

19. Which of the following is the MOST cost-effective EC2 instance purchasing option for short-term, spiky and critical workloads on AWS Cloud?
*  A. Dedicated Host
*  B. Reserved Instance
*  C. On-Demand Instance
*  D. Spot Instance

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>On-Demand Instance</strong></p>
 <p>An On-Demand Instance is an instance that you use on-demand. You have full control over its lifecycle — you decide when to launch, stop, hibernate, start, reboot, or terminate it. There is no long-term commitment required when you purchase On-Demand Instances. There is no upfront payment and you pay only for the seconds that your On-Demand Instances are running. There is no need for a long-term purchasing commitment. The price per second for running an On-Demand Instance is fixed. On-demand instances cannot be interrupted. Therefore On-Demand instances are the best fit for short-term, spiky and critical workloads.</p>
 <p>EC2 Pricing Options Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q15-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/ec2/pricing/">https://aws.amazon.com/ec2/pricing/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Spot Instance</strong> - A Spot Instance is an unused EC2 instance that is available for less than the On-Demand price. Because Spot Instances enable you to request unused EC2 instances at steep discounts (up to 90%), you can lower your Amazon EC2 costs significantly. Spot Instances are well-suited for data analysis, batch jobs, background processing, and other flexible tasks that can be interrupted. These can be terminated at short notice, so these are not suitable for critical workloads that need to run at a specific point in time.</p>
 <p><strong>Reserved Instance</strong> - Reserved Instances provide you with significant savings (up to 75%) on your Amazon EC2 costs compared to On-Demand Instance pricing. Reserved Instances are not physical instances, but rather a billing discount applied to the use of On-Demand Instances in your account. You can purchase a Reserved Instance for a one-year or three-year commitment, with the three-year commitment offering a bigger discount. Reserved instances cannot be interrupted. Reserved instances are not the right choice for short-term workloads.</p>
 <p><strong>Dedicated Host</strong> - Amazon EC2 Dedicated Hosts allow you to use your eligible software licenses from vendors such as Microsoft and Oracle on Amazon EC2 so that you get the flexibility and cost-effectiveness of using your licenses, but with the resiliency, simplicity, and elasticity of AWS. An Amazon EC2 Dedicated Host is a physical server fully dedicated for your use, so you can help address corporate compliance requirement. They're not cost-efficient compared to On-Demand instances. So this option is not correct.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/ec2/pricing/">https://aws.amazon.com/ec2/pricing/</a></p>
</div>

**Question 20**

20. Which of the following AWS entities lists all users in your account and the status of their various account aspects such as passwords, access keys, and MFA devices?
*  A. Amazon Inspector
*  B. AWS Cost and Usage Reports
*  C. Credential Reports
*  D. AWS Trusted Advisor

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Credential Reports</strong></p>
 <p>You can generate and download a credential report that lists all users in your account and the status of their various credentials, including passwords, access keys, and MFA devices. You can use credential reports to assist in your auditing and compliance efforts. You can use the report to audit the effects of credential lifecycle requirements, such as password and access key rotation. You can provide the report to an external auditor, or grant permissions to an auditor so that he or she can download the report directly.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Trusted Advisor</strong> - AWS Trusted Advisor is an online tool that provides real-time guidance to help provision your resources following AWS best practices. Whether establishing new workflows, developing applications, or as part of ongoing improvement, recommendations provided by Trusted Advisor regularly help keep your solutions provisioned optimally. AWS Trusted Advisor analyzes your AWS environment and provides best practice recommendations in five categories: Cost Optimization, Performance, Security, Fault Tolerance, Service Limits.</p>
 <p><strong>AWS Cost and Usage Reports</strong> - The AWS Cost and Usage Reports (AWS CUR) contains the most comprehensive set of cost and usage data available. You can use Cost and Usage Reports to publish your AWS billing reports to an Amazon Simple Storage Service (Amazon S3) bucket that you own. You can receive reports that break down your costs by the hour or month, by product or product resource, or by tags that you define yourself. Cost and Usage Reports cannot be used to identify under-utilized EC2 instances.</p>
 <p><strong>Amazon Inspector</strong> - Amazon Inspector is an automated, security assessment service that helps you check for unintended network accessibility of your Amazon EC2 instances and for vulnerabilities on those EC2 instances. Amazon Inspector assessments are offered to you as pre-defined rules packages mapped to common security best practices and vulnerability definitions.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_getting-report.html">https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_getting-report.html</a></p>
</div>

**Question 21**

21. According to the AWS Shared Responsibility Model, which of the following are responsibilities of the customer for IAM? (Select two)
*  A. Manage global network security infrastructure
*  B. Enable MFA on all accounts
*  C. Configuration and vulnerability analysis for the underlying software infrastructure
*  D. Analyze user access patterns and review IAM permissions
*  E. Compliance validation for the underlying software infrastructure

**Answer** B, D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p>Security and Compliance is a shared responsibility between AWS and the customer. This shared model can help relieve the customer’s operational burden as AWS operates, manages and controls the components from the host operating system and virtualization layer down to the physical security of the facilities in which the service operates.</p>
 <p><strong>Enable MFA on all accounts</strong></p>
 <p><strong>Analyze user access patterns and review IAM permissions</strong></p>
 <p>Under the AWS Shared Responsibility Model, customers are responsible for enabling MFA on all accounts, analyzing access patterns and reviewing permissions.</p>
 <p>Shared Responsibility Model Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/Shared_Responsibility_Model_V2.59d1eccec334b366627e9295b304202faf7b899b.jpg?raw=true"> via - <a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Manage global network security infrastructure</strong></p>
 <p><strong>Configuration and vulnerability analysis for the underlying software infrastructure</strong></p>
 <p><strong>Compliance validation for the underlying software infrastructure</strong></p>
 <p>According to the AWS Shared Responsibility Model, AWS is responsible for "Security of the Cloud". This includes protecting the infrastructure that runs all of the services offered in the AWS Cloud. This infrastructure is composed of the hardware, software, networking, and facilities that run AWS Cloud services. Therefore these three options fall under the responsibility of AWS.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
</div>

**Question 22**

22. Which of the following can you use to run a bootstrap script while launching an EC2 instance?
*  A. EC2 instance user data
*  B. EC2 instance configuration data
*  C. EC2 instance AMI data
*  D. EC2 instance metadata

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>EC2 instance user data</strong></p>
 <p>EC2 instance user data is the data that you specified in the form of a bootstrap script or configuration parameters while launching your instance.</p>
 <p>EC2 instance metadata and user data: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q18-i1.jpg?raw=true"></p>
 <p>Incorrect options:</p>
 <p><strong>EC2 instance metadata</strong> - EC2 instance metadata is data about your instance that you can use to manage the instance. You can get instance items such as ami-id, public-hostname, local-hostname, hostname, public-ipv4, local-ipv4, public-keys, instance-id by using instance metadata. You cannot use EC2 instance metadata to run a bootstrap script while launching an EC2 instance. So this option is incorrect.</p>
 <p><strong>EC2 instance configuration data</strong></p>
 <p><strong>EC2 instance AMI data</strong></p>
 <p>There is no such thing as EC2 instance configuration data or EC2 instance AMI data. These options have been added as distractors.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-instance-metadata.html">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-instance-metadata.html</a></p>
</div>

**Question 23**

23. A social media analytics company wants to migrate to a serverless stack on AWS. Which of the following scenarios can be handled by AWS Lambda? (Select two)
*  A. You can install Container Services on Lambda
*  B. You can install low latency databases on Lambda
*  C. Lambda can be used to execute code in response to events such as updates to DynamoDB tables
*  D. Lambda can be used for preprocessing of data before it is stored in Amazon S3 buckets
*  E. Lambda can be used to store sensitive environment variables

**Answer** C, D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p>AWS Lambda lets you run code without provisioning or managing servers (Lambda is serverless). With Lambda, you can run code for virtually any type of application or backend service - all with zero administration. Just upload your code and Lambda takes care of everything required to run and scale your code with high availability. This functionality makes it an extremely useful service capable of being a serverless backend for websites, data preprocessing, real-time data transformations when used with streaming data, etc.</p>
 <p>How Lambda Works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/product-page-diagram_Lambda-HowItWorks.68a0bcacfcf46fccf04b97f16b686ea44494303f.png?raw=true"> via - <a href="https://aws.amazon.com/lambda/">https://aws.amazon.com/lambda/</a></p>
 <p><strong>Lambda can be used to execute code in response to events such as updates to DynamoDB tables</strong> - Lambda can be configured to execute code in response to events, such as changes to Amazon S3 buckets, updates to an Amazon DynamoDB table, or custom events generated by your applications or devices.</p>
 <p><strong>Lambda can be used for preprocessing of data before it is stored in Amazon S3 buckets</strong> - Lambda can be used to run preprocessing scripts to filter, sort or transform data before sending it to downstream applications/services.</p>
 <p>Incorrect options:</p>
 <p><strong>You can install low latency databases on Lambda</strong> - Lambda is serverless, so the underlying hardware and its working is not exposed to the customer. Installing software is not possible since we do not have access to the actual physical server on which Lambda executes the code.</p>
 <p><strong>You can install Container Services on Lambda</strong> - As discussed above, Lambda cannot be used for installing any software, since the underlying hardware/software might change for each request. But, it is possible to set an environment with necessary libraries when running scripts on Lambda.</p>
 <p><strong>Lambda can be used to store sensitive environment variables</strong> - Lambda is not a storage service and does not offer capabilities to store data. However, it is possible to read and decrypt/encrypt data using scripts in Lambda.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/lambda/">https://aws.amazon.com/lambda/</a></p>
</div>

**Question 24**

24. Which AWS service will help you install application code automatically to an Amazon EC2 instance?
*  A. AWS CodeDeploy
*  B. AWS CodeBuild
*  C. AWS Elastic Beanstalk
*  D. AWS CloudFormation

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS CodeDeploy</strong></p>
 <p>AWS CodeDeploy is a service that automates application deployments to a variety of compute services including Amazon EC2, AWS Fargate, AWS Lambda, and on-premises instances. CodeDeploy fully automates your application deployments eliminating the need for manual operations. CodeDeploy protects your application from downtime during deployments through rolling updates and deployment health tracking.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Elastic Beanstalk</strong> - AWS Elastic Beanstalk is the fastest and simplest way to get web applications up and running on AWS. Developers simply upload their application code and the service automatically handles all the details such as resource provisioning, load balancing, auto-scaling, and monitoring. Elastic Beanstalk is an end-to-end application platform, unlike CodeDeploy, which is targeted at code deployment automation for any environment (Development, Testing, Production). It cannot be used to automatically deploy code to an Amazon EC2 instance.</p>
 <p><strong>AWS CloudFormation</strong> - AWS CloudFormation provides a common language for you to model and provision AWS and third-party application resources in your cloud environment. AWS CloudFormation allows you to use programming languages or a simple text file to model and provision, in an automated and secure manner, all the resources needed for your applications across all regions and accounts. It cannot be used to automatically deploy code to an Amazon EC2 instance.</p>
 <p><strong>AWS CodeBuild</strong> - AWS CodeBuild is a fully managed continuous integration service that compiles source code, runs tests, and produces software packages that are ready to deploy. With CodeBuild, you don’t need to provision, manage, and scale your own build servers. CodeBuild scales continuously and processes multiple builds concurrently, so your builds are not left waiting in a queue. It cannot be used to automatically deploy code to an Amazon EC2 instance.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/codedeploy/">https://aws.amazon.com/codedeploy/</a></p>
</div>

**Question 25**

25. Which AWS service will you use to provision the same AWS infrastructure across multiple AWS accounts and regions?
*  A. AWS OpsWorks
*  B. AWS CodeDeploy
*  C. AWS CloudFormation
*  D. AWS Systems Manager

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS CloudFormation</strong></p>
 <p>AWS CloudFormation allows you to use programming languages or a simple text file to model and provision, in an automated and secure manner, all the resources needed for your applications across all Regions and accounts. A stack is a collection of AWS resources that you can manage as a single unit. In other words, you can create, update, or delete a collection of resources by creating, updating, or deleting stacks.</p>
 <p>AWS CloudFormation StackSets extends the functionality of stacks by enabling you to create, update, or delete stacks across multiple accounts and regions with a single operation. Using an administrator account, you define and manage an AWS CloudFormation template, and use the template as the basis for provisioning stacks into selected target accounts across specified regions.</p>
 <p>How CloudFormation Works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/product-page-diagram_CloudFormation.ad3a4c93b4fdd3366da3da0de4fb084d89a5d761.png?raw=true"> via - <a href="https://aws.amazon.com/cloudformation/">https://aws.amazon.com/cloudformation/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS CodeDeploy</strong> - AWS CodeDeploy is a fully managed deployment service that automates software deployments to a variety of compute services such as Amazon EC2, AWS Fargate, AWS Lambda, and your on-premises servers. AWS CodeDeploy makes it easier for you to rapidly release new features, helps you avoid downtime during application deployment, and handles the complexity of updating your applications. You cannot use this service to provision AWS infrastructure.</p>
 <p><strong>AWS OpsWorks</strong> - AWS OpsWorks is a configuration management service that provides managed instances of Chef and Puppet. OpsWorks lets you use Chef and Puppet to automate how servers are configured, deployed and managed across your Amazon EC2 instances or on-premises compute environments. You cannot use OpsWorks for running commands or managing patches on servers. You cannot use this service to provision AWS infrastructure.</p>
 <p><strong>AWS Systems Manager</strong> - AWS Systems Manager gives you visibility and control of your infrastructure on AWS. Systems Manager provides a unified user interface so you can view operational data from multiple AWS services and allows you to automate operational tasks across your AWS resources. With Systems Manager, you can group resources, like Amazon EC2 instances, Amazon S3 buckets, or Amazon RDS instances, by application, view operational data for monitoring and troubleshooting, and take action on your groups of resources. You cannot use this service to provision AWS infrastructure.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/what-is-cfnstacksets.html">https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/what-is-cfnstacksets.html</a></p>
</div>

**Question 26**

26. An e-commerce company would like to receive alerts when the Reserved EC2 Instances utilization drops below a certain threshold. Which AWS service can be used to address this use-case?
*  A. AWS Cost Explorer
*  B. AWS Systems Manager
*  C. AWS Trusted Advisor
*  D. AWS Budgets

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Budgets</strong></p>
 <p>AWS Budgets gives you the ability to set custom budgets that alert you when your costs or usage exceed (or are forecasted to exceed) your budgeted amount. You can also use AWS Budgets to set reservation utilization or coverage targets and receive alerts when your utilization drops below the threshold you define. You can define a utilization threshold and receive alerts when your RI usage falls below that threshold. This lets you see if your RIs are unused or under-utilized. Reservation alerts are supported for Amazon EC2, Amazon RDS, Amazon Redshift, Amazon ElastiCache, and Amazon Elasticsearch reservations.</p>
 <p>AWS Budgets Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q5-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/budgets-managing-costs.html">https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/budgets-managing-costs.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS Trusted Advisor</strong> - AWS Trusted Advisor is an online tool that provides real-time guidance to help provision your resources following AWS best practices. Whether establishing new workflows, developing applications, or as part of ongoing improvement, recommendations provided by Trusted Advisor regularly help keep your solutions provisioned optimally. AWS Trusted Advisor analyzes your AWS environment and provides best practice recommendations in five categories: Cost Optimization, Performance, Security, Fault Tolerance, Service Limits.</p>
 <p><strong>AWS Cost Explorer</strong> - AWS Cost Explorer has an easy-to-use interface that lets you visualize, understand, and manage your AWS costs and usage over time. AWS Cost Explorer includes a default report that helps you visualize the costs and usage associated with your top five cost-accruing AWS services, and gives you a detailed breakdown of all services in the table view. The reports let you adjust the time range to view historical data going back up to twelve months to gain an understanding of your cost trends. Cost Explorer cannot be used to identify under-utilized EC2 instances.</p>
 <p><strong>AWS Systems Manager</strong> - AWS Systems Manager gives you visibility and control of your infrastructure on AWS. Systems Manager provides a unified user interface so you can view operational data from multiple AWS services and allows you to automate operational tasks such as running commands, managing patches, and configuring servers across AWS Cloud as well as on-premises infrastructure.</p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/product-page-diagram-AWS-Systems-Manager_how-it-works.2e7c5d550e833eed0f49fb8dc1872de23b09d183.png?raw=true"> via - <a href="https://aws.amazon.com/systems-manager/">https://aws.amazon.com/systems-manager/</a></p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/budgets-managing-costs.html">https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/budgets-managing-costs.html</a></p>
</div>

**Question 27**

27. Which of the following entities are part of a VPC in the AWS Cloud? (Select two)
*  A. Storage Gateway
*  B. Subnet
*  C. Internet Gateway
*  D. Object
*  E. API Gateway

**Answer** B, C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Subnet</strong></p>
 <p><strong>Internet Gateway</strong></p>
 <p>Amazon Virtual Private Cloud (Amazon VPC) enables you to launch AWS resources into a virtual network that you've defined.</p>
 <p>The following are the key concepts for VPCs:</p>
 <p>Virtual private cloud (VPC) — A virtual network dedicated to your AWS account.</p>
 <p>Subnet — A range of IP addresses in your VPC.</p>
 <p>Route table — A set of rules, called routes, that are used to determine where network traffic is directed.</p>
 <p>Internet Gateway — A gateway that you attach to your VPC to enable communication between resources in your VPC and the internet.</p>
 <p>VPC endpoint — Enables you to privately connect your VPC to supported AWS services and VPC endpoint services powered by PrivateLink without requiring an internet gateway, NAT device, VPN connection, or AWS Direct Connect connection.</p>
 <p>Incorrect options:</p>
 <p><strong>Storage Gateway</strong> - AWS Storage Gateway is a hybrid cloud storage service that gives you on-premises access to virtually unlimited cloud storage. Customers use Storage Gateway to simplify storage management and reduce costs for key hybrid cloud storage use cases. Storage Gateway is not part of VPC.</p>
 <p><strong>API Gateway</strong> - Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. APIs act as the "front door" for applications to access data, business logic, or functionality from your backend services. API Gateway is not part of a VPC.</p>
 <p><strong>Object</strong> - Buckets and objects are part of Amazon S3. Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance.</p>
 <p>Reference:</p>
 <p><a href="https://docs.amazonaws.cn/en_us/vpc/latest/userguide/what-is-amazon-vpc.html">https://docs.amazonaws.cn/en_us/vpc/latest/userguide/what-is-amazon-vpc.html</a></p>
</div>

**Question 28**

28. As per the Shared Responsibility Model, Security and Compliance is a shared responsibility between AWS and the customer. Which of the following security services falls under the purview of AWS under the Shared Responsibility Model?
*  A. AWS Shield Advanced
*  B. Security Groups for Amazon EC2
*  C. AWS Shield Standard
*  D. AWS Web Application Firewall (WAF)

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Shield Standard</strong></p>
 <p>AWS Shield is a managed service that protects against Distributed Denial of Service (DDoS) attacks for applications running on AWS. AWS Shield Standard is enabled for all AWS customers at no additional cost. AWS Shield Standard automatically protects your web applications running on AWS against the most common, frequently occurring DDoS attacks. You can get the full benefits of AWS Shield Standard by following the best practices of DDoS resiliency on AWS. As Shield Standard is automatically activated for all AWS customers with no options for any customizations, therefore AWS needs to manage the maintenance and configurations for this service. Hence this service falls under the purview of AWS.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Web Application Firewall (WAF)</strong> - AWS WAF is a web application firewall that lets you monitor the HTTP and HTTPS requests that are forwarded to an Amazon API Gateway API, Amazon CloudFront or an Application Load Balancer. AWS WAF also lets you control access to your content. AWS WAF has to be enabled by the customer and comes under the customer's responsibility.</p>
 <p><strong>AWS Shield Advanced</strong> - For higher levels of protection against attacks, you can subscribe to AWS Shield Advanced. As an AWS Shield Advanced customer, you can contact a 24x7 DDoS response team (DRT) for assistance during a DDoS attack. You also have exclusive access to advanced, real-time metrics and reports for extensive visibility into attacks on your AWS resources. Customers need to subscribe to Shield Advanced and need to pay for this service. It falls under customer responsibility per the AWS Shared Responsibility Model.</p>
 <p><strong>Security Groups for Amazon EC2</strong> - A Security Group acts as a virtual firewall for the EC2 instance to control incoming and outgoing traffic. Inbound rules control the incoming traffic to your instance, and outbound rules control the outgoing traffic from your instance. Security groups are the responsibility of the customer.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
</div>

**Question 29**

29. Which of the following types are free under the Amazon S3 pricing model? (Select two)
*  A. Data transferred out to an Amazon Elastic Compute Cloud (Amazon EC2) instance, when the instance is in the same AWS Region as the S3 bucket
*  B. Data storage fee for objects stored in S3 Standard
*  C. Data storage fee for objects stored in S3 Glacier
*  D. Data transferred in from the internet
*  E. Data transferred out to an Amazon Elastic Compute Cloud (Amazon EC2) instance in any AWS Region

**Answer** A, D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>Data transferred in from the internet</strong></p>
 <p><strong>Data transferred out to an Amazon Elastic Compute Cloud (Amazon EC2) instance, when the instance is in the same AWS Region as the S3 bucket</strong></p>
 <p>There are four cost components to consider for S3 pricing – storage pricing; request and data retrieval pricing; data transfer and transfer acceleration pricing; and data management features pricing. Under "Data Transfer", You pay for all bandwidth into and out of Amazon S3, except for the following: (1) Data transferred in from the internet, (2) Data transferred out to an Amazon Elastic Compute Cloud (Amazon EC2) instance, when the instance is in the same AWS Region as the S3 bucket, (3) Data transferred out to Amazon CloudFront (CloudFront).</p>
 <p>Incorrect options:</p>
 <p><strong>Data transferred out to an Amazon Elastic Compute Cloud (Amazon EC2) instance in any AWS Region</strong> - This is incorrect. Data transfer charges apply when the instance is not in the same AWS Region as the S3 bucket.</p>
 <p><strong>Data storage fee for objects stored in S3 Standard</strong> - S3 Standard charges a storage fee for objects.</p>
 <p><strong>Data storage fee for objects stored in S3 Glacier</strong> - S3 Glacier charges a storage fee for objects.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/s3/pricing/">https://aws.amazon.com/s3/pricing/</a></p>
</div>

**Question 30**

30. A social media company wants to have the MOST cost-optimal strategy for deploying EC2 instances. As a Cloud Practitioner, which of the following options would you recommend? (Select two)
*  A. Use Spot Instances for ad-hoc jobs that can be interrupted
*  B. Use Reserved Instances for ad-hoc jobs that can be interrupted
*  C. Use On-Demand Instances to run applications with a predictable usage over the next one year
*  D. Use On-Demand Instances for ad-hoc jobs that can be interrupted
*  E. Use Reserved Instances to run applications with a predictable usage over the next one year

**Answer** A, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>Use Spot Instances for ad-hoc jobs that can be interrupted</strong></p>
 <p>A Spot Instance is an unused EC2 instance that is available for less than the On-Demand price. Because Spot Instances enable you to request unused EC2 instances at steep discounts (up to 90%), you can lower your Amazon EC2 costs significantly. Spot Instances are well-suited for data analysis, batch jobs, background processing, and optional tasks. These can be terminated at short notice, so these are not suitable for critical workloads that need to run at a specific point in time.</p>
 <p><strong>Use Reserved Instances to run applications with a predictable usage over the next one year</strong></p>
 <p>Reserved Instances provide you with significant savings (up to 75%) on your Amazon EC2 costs compared to On-Demand Instance pricing. Reserved Instances are not physical instances, but rather a billing discount applied to the use of On-Demand Instances in your account. You can purchase a Reserved Instance for a one-year or three-year commitment, with the three-year commitment offering a bigger discount. Reserved instances are a great fit for application with a steady-state usage. Reserved instances cannot be interrupted.</p>
 <p>EC2 Pricing Options Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q2-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/ec2/pricing/">https://aws.amazon.com/ec2/pricing/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Use On-Demand Instances to run applications with a predictable usage over the next one year</strong></p>
 <p><strong>Use On-Demand Instances for ad-hoc jobs that can be interrupted</strong></p>
 <p>An On-Demand Instance is an instance that you use on-demand. You have full control over its lifecycle — you decide when to launch, stop, hibernate, start, reboot, or terminate it. There is no long-term commitment required when you purchase On-Demand Instances. There is no upfront payment and you pay only for the seconds that your On-Demand Instances are running. The price per second for running an On-Demand Instance is fixed. On-demand instances cannot be interrupted. However, On-demand instances are not as cost-effective as Spot instances or Reserved instances, so both these options are not correct.</p>
 <p><strong>Use Reserved Instances for ad-hoc jobs that can be interrupted</strong> - Spot instances are more cost-effective than Reserved instances for running ad-hoc jobs that can be interrupted, so this option is not correct.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/ec2/pricing/">https://aws.amazon.com/ec2/pricing/</a></p>
</div>

**Question 31**

31. Which AWS services can be used together to send alerts whenever the AWS account root user signs in? (Select two)
*  A. SNS
*  B. SQS
*  C. CloudWatch
*  D. Lambda
*  E. Step Function

**Answer** A, C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>SNS</strong></p>
 <p><strong>CloudWatch</strong></p>
 <p>Amazon CloudWatch Events delivers a near real-time stream of system events that describe changes in Amazon Web Services (AWS) resources. Using simple rules that you can quickly set up, you can match events and route them to one or more target functions or streams. CloudWatch Events becomes aware of operational changes as they occur. CloudWatch Events responds to these operational changes and takes corrective action as necessary, by sending messages to respond to the environment, activating functions, making changes, and capturing state information.</p>
 <p>Amazon Simple Notification Service (SNS) is a highly available, durable, secure, fully managed pub/sub messaging service that enables you to decouple microservices, distributed systems, and serverless applications. Additionally, SNS can be used to fan out notifications to end users using mobile push, SMS, and email.</p>
 <p>How SNS Works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/product-page-diagram_SNS_how-it-works_1.53a464980bf0d5a868b141e9a8b2acf12abc503f.png?raw=true"> via - <a href="https://aws.amazon.com/sns/">https://aws.amazon.com/sns/</a></p>
 <p>To send alerts whenever the AWS account root user signs in, you can create an Amazon Simple Notification Service (Amazon SNS) topic. Then, create an Amazon CloudWatch event rule to monitor userIdentity root logins from the AWS Management Console and send an email via SNS when the event triggers.</p>
 <p>Incorrect options:</p>
 <p><strong>SQS</strong> - Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications. Using SQS, you can send, store, and receive messages between software components at any volume, without losing messages or requiring other services to be available.</p>
 <p><strong>Lambda</strong> - AWS Lambda is a compute service that lets you run code without provisioning or managing servers.</p>
 <p><strong>Step Function</strong> - AWS Step Function lets you coordinate multiple AWS services into serverless workflows. You can design and run workflows that stitch together services such as AWS Lambda, AWS Glue and Amazon SageMaker.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/premiumsupport/knowledge-center/root-user-account-cloudwatch-rule/">https://aws.amazon.com/premiumsupport/knowledge-center/root-user-account-cloudwatch-rule/</a></p>
 <p><a href="https://docs.aws.amazon.com/AmazonCloudWatch/latest/events/WhatIsCloudWatchEvents.html">https://docs.aws.amazon.com/AmazonCloudWatch/latest/events/WhatIsCloudWatchEvents.html</a></p>
</div>

**Question 32**

32. Which of the following AWS Support plans provide programmatic access to AWS Support Center features to create, manage and close your support cases? (Select two)
*  A. Basic
*  B. Developer
*  C. Business
*  D. Corporate
*  E. Enterprise

**Answer** C, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>Enterprise</strong> - AWS Enterprise Support provides customers with concierge-like service where the main focus is helping the customer achieve their outcomes and find success in the cloud. With Enterprise Support, you get 24x7 technical support from high-quality engineers, tools and technology to automatically manage the health of your environment, consultative architectural guidance delivered in the context of your applications and use-cases, and a designated Technical Account Manager (TAM) to coordinate access to proactive/preventative programs and AWS subject matter experts. You get programmatic access (API Access) to AWS Support Center features to create, manage, and close your support cases, and operationally manage your Trusted Advisor check requests and status.</p>
 <p><strong>Business</strong> - AWS recommends Business Support if you have production workloads on AWS and want 24x7 phone, email and chat access to technical support and architectural guidance in the context of your specific use-cases. You get full access to AWS Trusted Advisor Best Practice Checks. You get programmatic access (API Access) to AWS Support Center features to create, manage, and close your support cases, and operationally manage your Trusted Advisor check requests and status.</p>
 <p>Exam Alert:</p>
 <p>Please review the differences between the Developer, Business, and Enterprise support plans as you can expect at least a couple of questions on the exam:</p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q29-i1.jpg?raw=true"></p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q29-i2.jpg?raw=true"></p>
 <p>via - <a href="https://aws.amazon.com/premiumsupport/plans/">https://aws.amazon.com/premiumsupport/plans/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Basic</strong> - The basic plan only provides access to the following:</p>
 <p>Customer Service &amp; Communities - 24x7 access to customer service, documentation, whitepapers, and support forums. AWS Trusted Advisor - Access to the 7 core Trusted Advisor checks and guidance to provision your resources following best practices to increase performance and improve security. AWS Personal Health Dashboard - A personalized view of the health of AWS services, and alerts when your resources are impacted.</p>
 <p><strong>Developer</strong> - AWS recommends the Developer Support plan if you are testing or doing early development on AWS and want the ability to get email-based technical support during business hours. This plan also supports general guidance on how services can be used for various use cases, workloads, or applications. You do not get access to Infrastructure Event Management with this plan.</p>
 <p>Both these plans do not support programmatic access (API Access) to AWS Support Center.</p>
 <p><strong>Corporate</strong> - This is a made-up option and has been added as a distractor.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/premiumsupport/plans/">https://aws.amazon.com/premiumsupport/plans/</a></p>
</div>

**Question 33**

33. A financial services company wants to migrate from its on-premises data center to AWS Cloud. As a Cloud Practitioner, which AWS service would you recommend so that the company can compare the cost of running their IT infrastructure on-premises vs AWS Cloud?
*  A. AWS Budgets
*  B. AWS Trusted Advisor
*  C. AWS Cost Explorer
*  D. AWS Pricing Calculator

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Pricing Calculator</strong></p>
 <p>AWS Pricing Calculator lets you explore AWS services and create an estimate for the cost of your use cases on AWS. You can model your solutions before building them, explore the price points and calculations behind your estimate, and find the available instance types and contract terms that meet your needs. This enables you to make informed decisions about using AWS. You can plan your AWS costs and usage or price out setting up a new set of instances and services. AWS Pricing Calculator can be accessed at <a href="https://calculator.aws/#/">https://calculator.aws/#/</a>.</p>
 <p>AWS also offers a complimentary service called Migration Evaluator (Formerly TSO Logic) to create data-driven business cases for AWS Cloud planning and migration.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Trusted Advisor</strong> - AWS Trusted Advisor provides recommendations that help you follow AWS best practices. Trusted Advisor evaluates your account by using checks. These checks identify ways to optimize your AWS infrastructure, improve security and performance, reduce costs, and monitor service quotas. This service cannot be used to compare the cost of running the IT infrastructure on-premises vs AWS Cloud.</p>
 <p><strong>AWS Cost Explorer</strong> - AWS Cost Explorer has an easy-to-use interface that lets you visualize, understand, and manage your AWS costs and usage over time. AWS Cost Explorer includes a default report that helps you visualize the costs and usage associated with your top five cost-accruing AWS services, and gives you a detailed breakdown of all services in the table view. The reports let you adjust the time range to view historical data going back up to twelve months to gain an understanding of your cost trends. AWS Cost Explorer cannot be used to compare the cost of running the IT infrastructure on-premises vs AWS Cloud.</p>
 <p><strong>AWS Budgets</strong> - AWS Budgets gives the ability to set custom budgets that alert you when your costs or usage exceed (or are forecasted to exceed) your budgeted amount. You can also use AWS Budgets to set reservation utilization or coverage targets and receive alerts when your utilization drops below the threshold you define. Budgets can be created at the monthly, quarterly, or yearly level, and you can customize the start and end dates. You can further refine your budget to track costs associated with multiple dimensions, such as AWS service, linked account, tag, and others. AWS Budgets cannot be used to compare the cost of running the IT infrastructure on-premises vs AWS Cloud.</p>
 <p>Reference:</p>
 <p><a href="https://calculator.aws/#/">https://calculator.aws/#/</a></p>
 <p><a href="https://docs.aws.amazon.com/whitepapers/latest/how-aws-pricing-works/aws-pricingtco-tools.html">https://docs.aws.amazon.com/whitepapers/latest/how-aws-pricing-works/aws-pricingtco-tools.html</a></p>
 <p><a href="https://aws.amazon.com/migration-evaluator/">https://aws.amazon.com/migration-evaluator/</a></p>
</div>

**Question 34**

34. AWS Marketplace facilitates which of the following use-cases? (Select two)
*  A. Purchase compliance documents from third-party vendors
*  B. Buy Amazon EC2 Standard Reserved Instances
*  C. Sell Software as a Service (SaaS) solutions to AWS customers
*  D. Raise request for purchasing AWS Direct Connect connection
*  E. AWS customer can buy software that has been bundled into customized AMIs by the AWS Marketplace sellers

**Answer** C, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Sell Software as a Service (SaaS) solutions to AWS customers</strong></p>
 <p><strong>AWS customer can buy software that has been bundled into customized AMIs by the AWS Marketplace sellers</strong></p>
 <p>AWS Marketplace is a digital catalog with thousands of software listings from independent software vendors that make it easy to find, test, buy, and deploy software that runs on AWS. The AWS Marketplace enables qualified partners to market and sell their software to AWS Customers.</p>
 <p>AWS Marketplace offers two ways for sellers to deliver software to customers: Amazon Machine Image (AMI) and Software as a Service (SaaS).</p>
 <p>Amazon Machine Image (AMI): Offering an AMI is the preferred option for listing products in AWS Marketplace. Partners have the option for free or paid products. Partners can offer paid products charged by the hour or month. Bring Your Own License (BYOL) is also available and enables customers with existing software licenses to easily migrate to AWS.</p>
 <p>Software as a Service (SaaS): If you offer a SaaS solution running on AWS (and are unable to build your product into an AMI) the SaaS listing offers our partners a way to market their software to customers.</p>
 <p>Incorrect options:</p>
 <p><strong>Purchase compliance documents from third-party vendors</strong> - There is no third party vendor for providing compliance documents. AWS Artifact is your go-to, central resource for compliance-related information that matters to you. It provides on-demand access to AWS’ security and compliance reports and select online agreements.</p>
 <p><strong>Buy Amazon EC2 Standard Reserved Instances</strong> - Amazon EC2 Standard Reserved Instances can be bought from the Amazon EC2 console at https://console.aws.amazon.com/ec2/</p>
 <p><strong>Raise request for purchasing AWS Direct Connect connection</strong> - AWS Direct Connect connection can be raised from the AWS management console at https://console.aws.amazon.com/directconnect/v2/home</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/partners/aws-marketplace/">https://aws.amazon.com/partners/aws-marketplace/</a></p>
 <p><a href="https://aws.amazon.com/artifact/">https://aws.amazon.com/artifact/</a></p>
 <p><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ri-market-concepts-buying.html#ri-queued-purchase">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ri-market-concepts-buying.html#ri-queued-purchase</a></p>
</div>

**Question 35**

35. Which of the following is a container service of AWS?
*  A. Amazon SageMaker
*  B. AWS Elastic Beanstalk
*  C. Amazon Simple Notification Service
*  D. AWS Fargate

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Fargate</strong></p>
 <p>AWS Fargate is a serverless compute engine for containers that works with both Amazon Elastic Container Service (ECS) and Amazon Elastic Kubernetes Service (EKS). Fargate makes it easy for you to focus on building your applications. Fargate removes the need to provision and manage servers, lets you specify and pay for resources per application, and improves security through application isolation by design.</p>
 <p>How Fargate Works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/Product-Page-Diagram_Fargate@2x.a20fb2b15c2aebeda3a44dbbb0b10b82fb89aa6a.png?raw=true"> via - <a href="https://aws.amazon.com/fargate/">https://aws.amazon.com/fargate/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS Elastic Beanstalk</strong> - AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling web applications and services. You simply upload your code and Elastic Beanstalk automatically handles the deployment, from capacity provisioning, load balancing, auto-scaling to application health monitoring. Beanstalk provisions servers so it is not a serverless service.</p>
 <p><strong>Amazon Simple Notification Service</strong> - Amazon Simple Notification Service (SNS) is a highly available, durable, secure, fully managed pub/sub messaging service that enables you to decouple microservices, distributed systems, and serverless applications.</p>
 <p><strong>Amazon SageMaker</strong> - Amazon SageMaker is a fully managed service that provides every developer and data scientist with the ability to build, train, and deploy machine learning (ML) models quickly. SageMaker removes the heavy lifting from each step of the machine learning process to make it easier to develop high-quality models.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/fargate/">https://aws.amazon.com/fargate/</a></p>
</div>

**Question 36**

36. Amazon EC2 Spot instances are a best-fit for which of the following scenarios?
*  A. To run batch processes for critical workloads
*  B. To install cost-effective RDS database
*  C. To run any containerized workload with Elastic Container Service (ECS) that can be interrupted
*  D. To run scheduled jobs (jobs that run at the same time every day)

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>To run any containerized workload with Elastic Container Service (ECS) that can be interrupted</strong></p>
 <p>Amazon EC2 Spot Instances let you take advantage of unused EC2 capacity in the AWS cloud. Spot Instances are available at up to a 90% discount compared to On-Demand prices.</p>
 <p>Containers are stateless, fault-tolerant and a great fit for Spot Instances. Spot Instances can be used with Elastic Container Service (ECS) or Elastic Container Service for Kubernetes (EKS) to run any containerized workload, from distributed parallel test systems to applications that map millions of miles a day. Spot instances provide the flexibility of ad-hoc provisioning for multiple instance types in different Availability Zones, with an option to hibernate, stop or terminate instances when EC2 needs the capacity back and Spot Instances are reclaimed.</p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q38-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/ec2/spot/containers-for-less/">https://aws.amazon.com/ec2/spot/containers-for-less/</a></p>
 <p>Incorrect options:</p>
 <p><strong>To install cost-effective RDS database</strong> - Spot instance capacity allocated to you can be taken back anytime without notice if AWS needs them. Hence, Spot instances can only be used as additional compute capacity and not for hosting or installing any software or database.</p>
 <p><strong>To run batch processes for critical workloads</strong> - Business-critical workloads cannot be run on Spot instances.</p>
 <p><strong>To run scheduled jobs (jobs that run at the same time every day)</strong> - There is no guarantee that a Spot instance will be available at a specific time every day. For a scheduled requirement, Scheduled Reserved instances should be used.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/ec2/spot/containers-for-less/">https://aws.amazon.com/ec2/spot/containers-for-less/</a></p>
</div>

**Question 37**

37. An organization maintains a separate Virtual Private Cloud (VPC) for each of its business units. Two units need to privately share data. Which is the most optimal way of privately sharing data between the two VPCs?
*  A. Site to Site VPN
*  B. VPC Endpoint
*  C. VPC Peering
*  D. AWS Direct Connect

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>VPC Peering</strong></p>
 <p>A VPC peering connection is a networking connection between two VPCs that enables you to route traffic between them privately. Instances in either VPC can communicate with each other as if they are within the same network. You can create a VPC peering connection between your VPCs, with a VPC in another AWS account, or with a VPC in a different AWS Region.</p>
 <p>VPC Peering Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q44-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/vpc/latest/peering/what-is-vpc-peering.html">https://docs.aws.amazon.com/vpc/latest/peering/what-is-vpc-peering.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Site to Site VPN</strong> - AWS Site-to-Site VPN creates a secure connection between your data center or branch office and your AWS cloud resources. This connection goes over the public internet. Site to Site VPN cannot be used to interconnect VPCs.</p>
 <p><strong>AWS Direct Connect</strong> - AWS Direct Connect creates a dedicated private connection from a remote network to your VPC. This is a private connection and does not use the public internet. Takes at least a month to establish this connection. Direct Connect cannot be used to interconnect VPCs.</p>
 <p><strong>VPC Endpoint</strong> - A VPC endpoint enables you to privately connect your VPC to supported AWS services and VPC endpoint services powered by AWS PrivateLink without requiring an internet gateway, NAT device, VPN connection, or AWS Direct Connect connection. You cannot connect two VPCs using a VPC endpoint.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/vpc/latest/peering/what-is-vpc-peering.html">https://docs.aws.amazon.com/vpc/latest/peering/what-is-vpc-peering.html</a></p>
</div>

**Question 38**

38. As per the AWS Shared Responsibility Model, which of the following is a responsibility of AWS from a security and compliance point of view?
*  A. Identity and Access Management
*  B. Service and Communications Protection
*  C. Patching guest OS and applications
*  D. Patching networking infrastructure

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Patching networking infrastructure</strong></p>
 <p>According to the AWS Shared Responsibility Model, AWS is responsible for "Security of the Cloud". This includes protecting the infrastructure that runs all of the services offered in the AWS Cloud. This infrastructure is composed of the hardware, software, networking, and facilities that run AWS Cloud services. Therefore, patching networking infrastructure is the responsibility of AWS.</p>
 <p>Incorrect options:</p>
 <p><strong>Service and Communications Protection</strong></p>
 <p><strong>Identity and Access Management</strong></p>
 <p><strong>Patching guest OS and applications</strong></p>
 <p>The customer is responsible for security "in" the cloud. This covers things such as services and communications protection; Identity and Access Management; and patching guest OS and applications. Customers are responsible for managing their data including encryption options and using Identity and Access Management tools for implementing appropriate access control policies as per their organization requirements. Therefore, these three options fall under the responsibility of the customer according to the AWS shared responsibility model.</p>
 <p>Exam Alert:</p>
 <p>Please review the Shared Responsibility Model in detail as you can expect multiple questions on the shared responsibility model in the exam: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/Shared_Responsibility_Model_V2.59d1eccec334b366627e9295b304202faf7b899b.jpg?raw=true"> via - <a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
</div>

**Question 39**

39. A multi-national organization has separate VPCs for each of its business units on the AWS Cloud. The organization also wants to connect its on-premises data center with all VPCs for better organization-wide collaboration. Which AWS services can be combined to build the MOST efficient solution for this use-case? (Select two)
*  A. AWS Transit Gateway
*  B. AWS Internet Gateway
*  C. VPC Peering
*  D. AWS Storage Gateway
*  E. AWS Direct Connect

**Answer** A, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Transit Gateway</strong></p>
 <p>AWS Transit Gateway connects VPCs and on-premises networks through a central hub. This simplifies your network and puts an end to complex peering relationships. It acts as a cloud router – each new connection is only made once. As you expand globally, inter-Region peering connects AWS Transit Gateways using the AWS global network. Your data is automatically encrypted and never travels over the public internet.</p>
 <p>How Transit Gateway can simplify your network: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q17-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/transit-gateway/">https://aws.amazon.com/transit-gateway/</a></p>
 <p><strong>AWS Direct Connect</strong></p>
 <p>AWS Direct Connect is a cloud service solution that makes it easy to establish a dedicated network connection from your premises to AWS. Using AWS Direct Connect, you can establish private connectivity between AWS and your datacenter, office, or colocation environment, which in many cases can reduce your network costs, increase bandwidth throughput, and provide a more consistent network experience than Internet-based connections.</p>
 <p>Incorrect options:</p>
 <p><strong>VPC Peering</strong> - A VPC peering connection is a networking connection between two VPCs that enables you to route traffic between them privately. VPC peering is not transitive, a separate VPC peering connection has to be made between two VPCs that need to talk to each other. With growing VPCs, this gets difficult to manage.</p>
 <p>Transitive VPC Peering is not allowed: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/transitive-peering-diagram.png?raw=true"> via - <a href="https://docs.aws.amazon.com/vpc/latest/peering/invalid-peering-configurations.html">https://docs.aws.amazon.com/vpc/latest/peering/invalid-peering-configurations.html</a></p>
 <p><strong>Internet Gateway</strong> - An internet gateway is a horizontally scaled, redundant, and highly available VPC component that allows communication between instances in your VPC and the internet. It, therefore, imposes no availability risks or bandwidth constraints on your network traffic. You cannot use Internet Gateway to connect your on-premises data center with multiple VPCs within your AWS network.</p>
 <p><strong>AWS Storage Gateway</strong> - AWS Storage Gateway is a hybrid cloud storage service that gives you on-premises access to virtually unlimited cloud storage. All data transferred between the gateway and AWS storage is encrypted using SSL (for all three types of gateways - File, Volume and Tape Gateways). You cannot use Storage Gateway to connect your on-premises data center with multiple VPCs within your AWS network.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/transit-gateway/">https://aws.amazon.com/transit-gateway/</a></p>
</div>

**Question 40**

40. A streaming media company wants to convert English language subtitles into Spanish language subtitles. As a Cloud Practitioner, which AWS service would you recommend for this use-case?
*  A. Amazon Polly
*  B. Amazon Rekognition
*  C. Amazon Transcribe
*  D. Amazon Translate

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon Translate</strong></p>
 <p>Amazon Translate is a neural machine translation service that delivers fast, high-quality, and affordable language translation. Amazon Translate allows you to localize content - such as websites and applications - for international users, and to easily translate large volumes of text efficiently.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Polly</strong> - You can use Amazon Polly to turn text into lifelike speech thereby allowing you to create applications that talk. Polly's Text-to-Speech (TTS) service uses advanced deep learning technologies to synthesize natural sounding human speech.</p>
 <p><strong>Amazon Transcribe</strong> - You can use Amazon Transcribe to add speech-to-text capability to your applications. Amazon Transcribe uses a deep learning process called automatic speech recognition (ASR) to convert speech to text quickly and accurately. Amazon Transcribe can be used to transcribe customer service calls, to automate closed captioning and subtitling, and to generate metadata for media assets.</p>
 <p><strong>Amazon Rekognition</strong> - With Amazon Rekognition, you can identify objects, people, text, scenes, and activities in images and videos, as well as to detect any inappropriate content. Amazon Rekognition also provides highly accurate facial analysis and facial search capabilities that you can use to detect, analyze, and compare faces for a wide variety of user verification, people counting, and public safety use cases.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/translate/">https://aws.amazon.com/translate/</a></p>
</div>

**Question 41**

41. A financial services company wants to ensure that all customer data uploaded on its data lake on Amazon S3 always stays private. Which of the following is the MOST efficient solution to address this compliance requirement?
*  A. Set up a high-level advisory committee to review the privacy settings of each object uploaded into S3
*  B. Use Amazon S3 Block Public Access to ensure that all S3 resources stay private
*  C. Use CloudWatch to ensure that all S3 resources stay private
*  D. Trigger a lambda function every time an object is uploaded on S3. The lambda function should change the object settings to make sure it stays private

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Use Amazon S3 Block Public Access to ensure that all S3 resources stay private</strong></p>
 <p>The Amazon S3 Block Public Access feature provides settings for access points, buckets, and accounts to help you manage public access to Amazon S3 resources. By default, new buckets, access points, and objects don't allow public access. However, users can modify bucket policies, access point policies, or object permissions to allow public access. S3 Block Public Access settings override these policies and permissions so that you can limit public access to these resources.</p>
 <p>When Amazon S3 receives a request to access a bucket or an object, it determines whether the bucket or the bucket owner's account has a block public access setting applied. If the request was made through an access point, Amazon S3 also checks for block public access settings for the access point. If there is an existing block public access setting that prohibits the requested access, Amazon S3 rejects the request.</p>
 <p>Amazon S3 Block Public Access Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q65-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/access-control-block-public-access.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/access-control-block-public-access.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Trigger a lambda function every time an object is uploaded on S3. The lambda function should change the object settings to make sure it stays private</strong> - Although it's possible to implement this solution, but it is more efficient to use the "Amazon S3 Block Public Access" feature as its available off-the-shelf.</p>
 <p><strong>Use CloudWatch to ensure that all S3 resources stay private</strong> - Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers. CloudWatch provides data and actionable insights to monitor applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health. This is an excellent service for building Resilient systems. Think resource performance monitoring, events, and alerts; think CloudWatch. CloudWatch cannot be used to ensure data privacy on S3.</p>
 <p><strong>Set up a high-level advisory committee to review the privacy settings of each object uploaded into S3</strong> - This option has been added as a distractor.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/access-control-block-public-access.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/access-control-block-public-access.html</a></p>
</div>

**Question 42**

42. Which of the following statements are CORRECT regarding AWS Global Accelerator? (Select two)
*  A. Global Accelerator can be used to host static websites
*  B. Global Accelerator uses the AWS global network and its edge locations. But the edge locations used by Global Accelerator are different from Amazon CloudFront edge locations
*  C. Global Accelerator cannot be configured with an Elastic Load Balancer (ELB)
*  D. Global Accelerator provides static IP addresses that act as a fixed entry point to your applications
*  E. Global Accelerator is a good fit for non-HTTP use cases

**Answer** D, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p>AWS Global Accelerator is a networking service that helps you improve the availability and performance of the applications that you offer to your global users. Global Accelerator improves performance for a wide range of applications over TCP or UDP by proxying packets at the edge to applications running in one or more AWS Regions.</p>
 <p>How Global Accelerator Works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/global-accelerator-how-it-works.feb297eb78d8cc55205874a1691e0ea2bc8bdbf1.png?raw=true"> via - <a href="https://aws.amazon.com/global-accelerator/">https://aws.amazon.com/global-accelerator/</a></p>
 <p><strong>Global Accelerator is a good fit for non-HTTP use cases</strong> - Global Accelerator is a good fit for non-HTTP use cases, such as gaming (UDP), IoT (MQTT), or Voice over IP, as well as for HTTP use cases that specifically require static IP addresses or deterministic, fast regional failover.</p>
 <p><strong>Global Accelerator provides static IP addresses that act as a fixed entry point to your applications</strong> - It provides static IP addresses that provide a fixed entry point to your applications and eliminate the complexity of managing specific IP addresses for different AWS Regions and Availability Zones.</p>
 <p>Incorrect options:</p>
 <p><strong>Global Accelerator uses the AWS global network and its edge locations. But the edge locations used by Global Accelerator are different from Amazon CloudFront edge locations</strong> - AWS Global Accelerator and Amazon CloudFront use the same edge locations.</p>
 <p><strong>Global Accelerator cannot be configured with an Elastic Load Balancer (ELB)</strong> - A regional ELB load balancer is an ideal target for AWS Global Accelerator. AWS Global Accelerator complements ELB by extending these capabilities beyond a single AWS Region, allowing you to provide a global interface for your applications in any number of Regions.</p>
 <p><strong>Global Accelerator can be used to host static websites</strong> - Amazon S3 can host static websites. So this option is incorrect.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/global-accelerator/">https://aws.amazon.com/global-accelerator/</a></p>
</div>

**Question 43**

43. Which of the following AWS authentication mechanisms supports a Multi-Factor Authentication (MFA) device that you can plug into a USB port on your computer?
*  A. Hardware MFA device
*  B. Virtual MFA device
*  C. U2F security key
*  D. SMS text message-based MFA

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>U2F security key</strong> - Universal 2nd Factor (U2F) Security Key is a device that you can plug into a USB port on your computer. U2F is an open authentication standard hosted by the FIDO Alliance. When you enable a U2F security key, you sign in by entering your credentials and then tapping the device instead of manually entering a code.</p>
 <p>How to enable the U2F Security Key for your own IAM user: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q49-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa_enable_u2f.html">https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa_enable_u2f.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Virtual MFA device</strong> - This is a software app that runs on a phone or other device and emulates a physical device. The device generates a six-digit numeric code based upon a time-synchronized one-time password algorithm. The user must type a valid code from the device on a second webpage during sign-in. Each virtual MFA device assigned to a user must be unique.</p>
 <p><strong>Hardware MFA device</strong> - This is a hardware device that generates a six-digit numeric code based upon a time-synchronized one-time password algorithm. The user must type a valid code from the device on a second webpage during sign-in. Each MFA device assigned to a user must be unique. A user cannot type a code from another user's device to be authenticated.</p>
 <p><strong>SMS text message-based MFA</strong> - This is a type of MFA in which the IAM user settings include the phone number of the user's SMS-compatible mobile device. When the user signs in, AWS sends a six-digit numeric code by SMS text message to the user's mobile device. The user is required to type that code on a second webpage during sign-in.</p>
 <p>References:</p>
 <p><a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa.html">https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa.html</a></p>
 <p><a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa_enable_u2f.html">https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa_enable_u2f.html</a></p>
</div>

**Question 44**

44. Which AWS service can be used to set up billing alarms to monitor estimated charges on your AWS account?
*  A. Amazon CloudWatch
*  B. AWS Cost Explorer
*  C. AWS CloudTrail
*  D. AWS Organizations

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon CloudWatch</strong></p>
 <p>Amazon CloudWatch can be used to create an alarm to monitor your estimated charges. When you enable the monitoring of estimated charges for your AWS account, the estimated charges are calculated and sent several times daily to CloudWatch as metric data. You can choose to receive alerts by email when charges have exceeded a certain threshold. These alerts are triggered by CloudWatch and messages are sent using Amazon Simple Notification Service (Amazon SNS). Billing metric data is stored in the US East (N. Virginia) Region and reflects worldwide charges.</p>
 <p>The alarm triggers when your account billing exceeds the threshold you specify. It triggers only when actual billing exceeds the threshold. It doesn't use projections based on your usage so far in the month.</p>
 <p>CloudWatch Billing Alarms Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q21-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html">https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html</a></p>
 <p>Exam Alert:</p>
 <p>It is useful to note the difference between CloudWatch Billing vs Budgets:</p>
 <p>CloudWatch Billing Alarms: Sends an alarm when the actual cost exceeds a certain threshold.</p>
 <p>Budgets: Sends an alarm when the actual cost exceeds the budgeted amount or even when the cost forecast exceeds the budgeted amount.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS CloudTrail</strong> - AWS CloudTrail is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account. With CloudTrail, you can log, continuously monitor, and retain account activity related to actions across your AWS infrastructure. Billing alarms cannot be triggered via CloudTrail.</p>
 <p><strong>AWS Organizations</strong> - AWS Organizations is an account management service that enables you to consolidate multiple AWS accounts into an organization that you create and centrally manage. Consolidated billing is a feature of AWS Organizations. You can use the master account of your organization to consolidate and pay for all member accounts. Billing alarms cannot, however, be triggered using Consolidated Billing.</p>
 <p><strong>AWS Cost Explorer</strong> - AWS Cost Explorer has an easy-to-use interface that lets you visualize, understand, and manage your AWS costs and usage over time. Cost Explorer will help analyze your data at a high level or dive deeper into your cost and usage data using various reports (Monthly costs by AWS service, hourly and resource Level cost). Billing alarms cannot be triggered via Cost Explorer.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html">https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html</a></p>
</div>

**Question 45**

45. Which of the following AWS services offer LifeCycle Management for cost-optimal storage?
*  A. Amazon Instance Store
*  B. Amazon S3
*  C. AWS Storage Gateway
*  D. Amazon EBS

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>Amazon S3</strong></p>
 <p>You can manage your objects on S3 so that they are stored cost-effectively throughout their lifecycle by configuring their Amazon S3 Lifecycle. An S3 Lifecycle configuration is a set of rules that define actions that Amazon S3 applies to a group of objects.</p>
 <p>There are two types of actions:</p>
 <p>Transition actions — Define when objects transition to another storage class. For example, you might choose to transition objects to the S3 Standard-IA storage class 30 days after you created them, or archive objects to the S3 Glacier storage class one year after creating them.</p>
 <p>Expiration actions — Define when objects expire. Amazon S3 deletes expired objects on your behalf.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Instance Store</strong> - An Instance Store provides temporary block-level storage for your EC2 instance. This storage is located on disks that are physically attached to the host computer. Instance store is ideal for the temporary storage of information that changes frequently, such as buffers, caches, scratch data, and other temporary content, or for data that is replicated across a fleet of instances, such as a load-balanced pool of web servers. Instance storage is temporary, data is lost if instance experiences failure or is terminated. Instance Store does not offer Lifecycle Management or Infrequent Access storage class.</p>
 <p><strong>Amazon EBS</strong> - Amazon Elastic Block Store (EBS) is an easy to use, high-performance block storage service designed for use with Amazon Elastic Compute Cloud (EC2) for both throughput and transaction-intensive workloads at any scale. A broad range of workloads, such as relational and non-relational databases, enterprise applications, containerized applications, big data analytics engines, file systems, and media workflows are widely deployed on Amazon EBS. It does not offer Lifecycle Management or Infrequent Access storage class.</p>
 <p><strong>AWS Storage Gateway</strong> - AWS Storage Gateway is a hybrid cloud storage service that gives you on-premises access to virtually unlimited cloud storage. All data transferred between the gateway and AWS storage is encrypted using SSL (for all three types of gateways - File, Volume and Tape Gateways). Storage Gateway does not offer Lifecycle Management or Infrequent Access storage class.</p>
 <p>References:</p>
 <p><a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/object-lifecycle-mgmt.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/object-lifecycle-mgmt.html</a></p>
</div>

**Question 46**

46. Which of the following is best-suited for load-balancing HTTP and HTTPS traffic?
*  A. Network Load Balancer
*  B. System Load Balancer
*  C. Application Load Balancer
*  D. AWS Auto Scaling

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Application Load Balancer</strong></p>
 <p>Elastic Load Balancing automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, and Lambda functions. It can handle the varying load of your application traffic in a single Availability Zone or across multiple Availability Zones. Elastic Load Balancing offers three types of load balancers that all feature the high availability, automatic scaling, and robust security necessary to make your applications fault-tolerant.</p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q60-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/elasticloadbalancing/">https://aws.amazon.com/elasticloadbalancing/</a></p>
 <p>Application Load Balancer is used for load balancing of HTTP and HTTPS traffic and provides advanced request routing targeted at the delivery of modern application architectures, including microservices and containers.</p>
 <p>Incorrect options:</p>
 <p><strong>Network Load Balancer</strong> - Network Load Balancer is best suited for load balancing of Transmission Control Protocol (TCP), User Datagram Protocol (UDP) and Transport Layer Security (TLS) traffic where extreme performance is required.</p>
 <p><strong>AWS Auto Scaling</strong> - AWS Auto Scaling monitors your applications and automatically adjusts the capacity to maintain steady, predictable performance at the lowest possible cost. Using AWS Auto Scaling, it’s easy to setup application scaling for multiple resources across multiple services in minutes. The service provides a simple, powerful user interface that lets you build scaling plans for resources including Amazon EC2 instances and Spot Fleets, Amazon ECS tasks, Amazon DynamoDB tables and indexes, and Amazon Aurora Replicas. Auto Scaling cannot be used for load-balancing HTTP and HTTPS traffic.</p>
 <p><strong>System Load Balancer</strong> - This is a made-up option and has been added as a distractor.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/elasticloadbalancing/">https://aws.amazon.com/elasticloadbalancing/</a></p>
</div>

**Question 47**

47. A firm wants to maintain the same data on S3 between its production account and multiple test accounts. Which technique should you choose to copy data into multiple test accounts while retaining object metadata?
*  A. Amazon S3 Bucket Policy
*  B. Amazon S3 Storage Classes
*  C. Amazon S3 Replication
*  D. Amazon S3 Transfer Acceleration

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon S3 Replication</strong></p>
 <p>Replication enables automatic, asynchronous copying of objects across Amazon S3 buckets. Buckets that are configured for object replication can be owned by the same AWS account or by different accounts. You can copy objects between different AWS Regions or within the same Region. You can use replication to make copies of your objects that retain all metadata, such as the original object creation time and version IDs. This capability is important if you need to ensure that your replica is identical to the source object.</p>
 <p>Exam Alert:</p>
 <p>Amazon S3 supports two types of replication: Cross Region Replication vs Same Region Replication. Please review the differences between SRR and CRR: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q53-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/replication.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/replication.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon S3 Bucket Policy</strong> - A bucket policy is a resource-based AWS Identity and Access Management (IAM) policy. You add a bucket policy to a bucket to grant other AWS accounts or IAM users access permissions for the bucket and the objects in it. Object permissions apply only to the objects that the bucket owner creates. You cannot replicate data using a bucket policy.</p>
 <p><strong>Amazon S3 Transfer Acceleration</strong> - Amazon S3 Transfer Acceleration enables fast, easy, and secure transfers of files over long distances between your client and an S3 bucket. Transfer Acceleration takes advantage of Amazon CloudFront’s globally distributed edge locations. This facility speeds up access between end-user and S3, this is not for replicating data.</p>
 <p><strong>Amazon S3 Storage Classes</strong> - Amazon S3 offers a range of storage classes designed for different use cases. Each storage class has a defined set of rules to store, encrypt data at a certain price. Based on the use case, customers can choose the storage class that best suits their business requirements.</p>
 <p>These include S3 Standard for general-purpose storage of frequently accessed data; S3 Intelligent-Tiering for data with unknown or changing access patterns; S3 Standard-Infrequent Access (S3 Standard-IA) and S3 One Zone-Infrequent Access (S3 One Zone-IA) for long-lived, but less frequently accessed data; and Amazon S3 Glacier (S3 Glacier) and Amazon S3 Glacier Deep Archive (S3 Glacier Deep Archive) for long-term archive and digital preservation. You cannot replicate data using storage classes.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/replication.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/replication.html</a></p>
</div>

**Question 48**

48. AWS Shield Advanced provides expanded DDoS attack protection for web applications running on which of the following resources? (Select two)
*  A. Amazon CloudFront
*  B. Amazon Elastic Compute Cloud
*  C. AWS Identity and Access Management (IAM)
*  D. Amazon Simple Storage Service (Amazon S3)
*  E. AWS Elastic Beanstalk

**Answer** A, B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>Amazon CloudFront</strong></p>
 <p><strong>Amazon Elastic Compute Cloud</strong></p>
 <p>AWS Shield Standard is activated for all AWS customers, by default. For higher levels of protection against attacks, you can subscribe to AWS Shield Advanced. With Shield Advanced, you also have exclusive access to advanced, real-time metrics and reports for extensive visibility into attacks on your AWS resources. With the assistance of the DRT (DDoS response team), AWS Shield Advanced includes intelligent DDoS attack detection and mitigation for not only for network layer (layer 3) and transport layer (layer 4) attacks but also for application layer (layer 7) attacks.</p>
 <p>AWS Shield Advanced provides expanded DDoS attack protection for web applications running on the following resources: Amazon Elastic Compute Cloud, Elastic Load Balancing (ELB), Amazon CloudFront, Amazon Route 53, AWS Global Accelerator.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Simple Storage Service (Amazon S3)</strong></p>
 <p><strong>AWS Elastic Beanstalk</strong></p>
 <p><strong>AWS Identity and Access Management (IAM)</strong></p>
 <p>These three resource types are not supported by AWS Shield Advanced.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/waf/latest/developerguide/ddos-overview.html">https://docs.aws.amazon.com/waf/latest/developerguide/ddos-overview.html</a></p>
</div>

**Question 49**

49. Which AWS entity enables you to privately connect your VPC to an Amazon SQS queue?
*  A. Internet Gateway
*  B. AWS Direct Connect
*  C. VPC Gateway Endpoint
*  D. VPC Interface Endpoint

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>VPC Interface Endpoint</strong></p>
 <p>An interface endpoint is an elastic network interface with a private IP address from the IP address range of your subnet that serves as an entry point for traffic destined to a supported service. Interface endpoints are powered by AWS PrivateLink, a technology that enables you to privately access services by using private IP addresses. AWS PrivateLink restricts all network traffic between your VPC and services to the Amazon network. You do not need an internet gateway, a NAT device, or a virtual private gateway.</p>
 <p>Exam Alert:</p>
 <p>You may see a question around this concept in the exam. Just remember that only S3 and DynamoDB support VPC Endpoint Gateway. All other services that support VPC Endpoints use a VPC Endpoint Interface.</p>
 <p>Incorrect options:</p>
 <p><strong>VPC Gateway Endpoint</strong> - A Gateway Endpoint is a gateway that you specify as a target for a route in your route table for traffic destined to a supported AWS service. The following AWS services are supported: Amazon S3, DynamoDB. You cannot use VPC Gateway Endpoint to privately connect your VPC to an Amazon SQS queue.</p>
 <p><strong>AWS Direct Connect</strong> - AWS Direct Connect is a cloud service solution that makes it easy to establish a dedicated network connection from your premises to AWS. You can use AWS Direct Connect to establish a private virtual interface from your on-premise network directly to your Amazon VPC. This private connection takes at least one month for completion. You cannot use AWS Direct Connect to privately connect your VPC to an Amazon SQS queue.</p>
 <p><strong>Internet Gateway</strong> - An Internet Gateway is a horizontally scaled, redundant, and highly available VPC component that allows communication between your VPC and the internet. An internet gateway serves two purposes: to provide a target in your VPC route tables for internet-routable traffic, and to perform network address translation (NAT) for instances that have been assigned public IPv4 addresses. You cannot use an Internet Gateway to privately connect your VPC to an Amazon SQS queue.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/vpc/latest/userguide/vpc-endpoints.html">https://docs.aws.amazon.com/vpc/latest/userguide/vpc-endpoints.html</a></p>
</div>

**Question 50**

50. An e-commerce company wants to review the Payment Card Industry (PCI) reports on AWS Cloud. Which AWS resource can be used to address this use-case?
*  A. AWS Artifact
*  B. AWS Secrets Manager
*  C. AWS Cost and Usage Reports
*  D. AWS Trusted Advisor

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Artifact</strong></p>
 <p>AWS Artifact is your go-to, central resource for compliance-related information that matters to your organization. It provides on-demand access to AWS’ security and compliance reports and select online agreements. Reports available in AWS Artifact include our Service Organization Control (SOC) reports, Payment Card Industry (PCI) reports, and certifications from accreditation bodies across geographies and compliance verticals that validate the implementation and operating effectiveness of AWS security controls. It is not a service, it's a no-cost, self-service portal for on-demand access to AWS’ compliance reports.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Trusted Advisor</strong> - AWS Trusted Advisor is an online tool that provides you real-time guidance to help you provision your resources following AWS best practices. Whether establishing new workflows, developing applications, or as part of ongoing improvement, recommendations provided by Trusted Advisor regularly help keep your solutions provisioned optimally.</p>
 <p><strong>AWS Secrets Manager</strong> - AWS Secrets Manager helps you protect secrets needed to access your applications, services, and IT resources. The service enables you to easily rotate, manage, and retrieve database credentials, API keys, and other secrets throughout their lifecycle. Users and applications retrieve secrets with a call to Secrets Manager APIs, eliminating the need to hardcode sensitive information in plain text.</p>
 <p><strong>AWS Cost and Usage Reports</strong> - The AWS Cost and Usage Reports (AWS CUR) contains the most comprehensive set of cost and usage data available. You can use Cost and Usage Reports to publish your AWS billing reports to an Amazon Simple Storage Service (Amazon S3) bucket that you own. You can receive reports that break down your costs by the hour or month, by product or product resource, or by tags that you define yourself. AWS updates the report in your bucket once a day in comma-separated value (CSV) format.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/artifact/">https://aws.amazon.com/artifact/</a></p>
</div>

**Question 51**

51. The DevOps team at a Big Data consultancy has set up EC2 instances across two AWS Regions for its flagship application. Which of the following characterizes this application architecture?
*  A. Deploying the application across two AWS Regions improves scalability
*  B. Deploying the application across two AWS Regions improves agility
*  C. Deploying the application across two AWS Regions improves availability
*  D. Deploying the application across two AWS Regions improves security

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Deploying the application across two AWS Regions improves availability</strong> - Highly available systems are those that can withstand some measure of degradation while remaining available. Each AWS Region is fully isolated and comprised of multiple Availability Zones (AZ’s), which are fully isolated partitions of AWS infrastructure. To better isolate any issues and achieve high availability, you can partition applications across multiple AZ’s in the same AWS Region or even across multiple AWS Regions.</p>
 <p>Key Benefits of AWS Global Infrastructure: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q20-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/about-aws/global-infrastructure/">https://aws.amazon.com/about-aws/global-infrastructure/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Deploying the application across two AWS Regions improves agility</strong> - Agility refers to the ability of the cloud to give you easy access to a broad range of technologies so that you can innovate faster and build nearly anything that you can imagine. You can quickly spin up resources as you need them – from infrastructure services, such as compute, storage, and databases, to Internet of Things, machine learning, data lakes and analytics, and much more. Deploying the application across two AWS Regions does not improve agility.</p>
 <p><strong>Deploying the application across two AWS Regions improves security</strong> - The application security is dependent on multiple factors such as data encryption, IAM policies, IAM roles, VPC security configurations, Security Groups, NACLs, etc. Deploying the application across two AWS Regions directly impacts availability. So this option is not the best fit for the given use-case.</p>
 <p><strong>Deploying the application across two AWS Regions improves scalability</strong> - For the given use-case, you can improve the scalability of the application by using an Application Load Balancer with an Auto Scaling group. Deploying the application across two AWS Regions directly impacts availability. So this option is not the best fit for the given use-case.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/about-aws/global-infrastructure/">https://aws.amazon.com/about-aws/global-infrastructure/</a></p>
</div>

**Question 52**

52. The DevOps team at an IT company wants to centrally manage its servers on AWS Cloud as well as on-premise data center so that it can collect software inventory, run commands, configure and patch servers at scale. As a Cloud Practitioner, which AWS service would you recommend for this use-case?
*  A. OpsWorks
*  B. CloudFormation
*  C. Systems Manager
*  D. Config

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Systems Manager</strong></p>
 <p>AWS Systems Manager gives you visibility and control of your infrastructure on AWS. Systems Manager provides a unified user interface so you can view operational data from multiple AWS services and allows you to automate operational tasks such as collecting software inventory, running commands, managing patches, and configuring servers across AWS Cloud as well as on-premises infrastructure.</p>
 <p>AWS Systems Manager offers utilities for running commands, patch-management and configuration compliance: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q11-i1.png?raw=true"> via - <a href="https://aws.amazon.com/systems-manager/faq/">https://aws.amazon.com/systems-manager/faq/</a></p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/product-page-diagram-AWS-Systems-Manager_how-it-works.2e7c5d550e833eed0f49fb8dc1872de23b09d183.png?raw=true"> via - <a href="https://aws.amazon.com/systems-manager/">https://aws.amazon.com/systems-manager/</a></p>
 <p>Incorrect options:</p>
 <p><strong>OpsWorks</strong> - AWS OpsWorks is a configuration management service that provides managed instances of Chef and Puppet. OpsWorks lets you use Chef and Puppet to automate how servers are configured, deployed and managed across your Amazon EC2 instances or on-premises compute environments. You cannot use OpsWorks for collecting software inventory and viewing operational data from multiple AWS services.</p>
 <p><strong>CloudFormation</strong> - AWS CloudFormation allows you to use programming languages or a simple text file to model and provision, in an automated and secure manner, all the resources needed for your applications across all Regions and accounts. Think infrastructure as code; think CloudFormation. You cannot use CloudFormation for running commands or managing patches on servers.</p>
 <p><strong>Config</strong> - AWS Config is a service that enables you to assess, audit, and evaluate the configurations of your AWS resources. Config continuously monitors and records your AWS resource configurations and allows you to automate the evaluation of recorded configurations against desired configurations. You cannot use Config for running commands or managing patches on servers.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/systems-manager/">https://aws.amazon.com/systems-manager/</a></p>
 <p><a href="https://aws.amazon.com/systems-manager/faq/">https://aws.amazon.com/systems-manager/faq/</a></p>
</div>

**Question 53**

53. The QA team at a company wants a tool/service that can provide access to different mobile devices with variations in firmware and Operating System versions.
*  A. AWS Elastic Beanstalk
*  B. AWS CodePipeline
*  C. AWS Mobile Farm
*  D. AWS Device Farm

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Device Farm</strong> - AWS Device Farm is an application testing service that lets you improve the quality of your web and mobile apps by testing them across an extensive range of desktop browsers and real mobile devices; without having to provision and manage any testing infrastructure. The service enables you to run your tests concurrently on multiple desktop browsers or real devices to speed up the execution of your test suite, and generates videos and logs to help you quickly identify issues with your app.</p>
 <p>AWS Device Farm is designed for developers, QA teams, and customer support representatives who are building, testing, and supporting mobile apps to increase the quality of their apps. Application quality is increasingly important, and also getting complex due to the number of device models, variations in firmware and OS versions, carrier and manufacturer customizations, and dependencies on remote services and other apps. AWS Device Farm accelerates the development process by executing tests on multiple devices, giving developers, QA and support professionals the ability to perform automated tests and manual tasks like reproducing customer issues, exploratory testing of new functionality, and executing manual test plans. AWS Device Farm also offers significant savings by eliminating the need for internal device labs, lab managers, and automation infrastructure development.</p>
 <p>How it works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q63-i2.jpg?raw=true"> via - <a href="https://aws.amazon.com/device-farm/">https://aws.amazon.com/device-farm/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS CodePipeline</strong> - AWS CodePipeline is a fully managed continuous delivery service that helps you automate your release pipelines for fast and reliable application and infrastructure updates. CodePipeline automates the build, test, and deploy phases of your release process every time there is a code change, based on the release model you define. This enables you to rapidly and reliably deliver features and updates.</p>
 <p><strong>AWS Elastic Beanstalk</strong> - AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling web applications and services developed with Java, .NET, PHP, Node.js, Python, etc.</p>
 <p>You can simply upload your code and Elastic Beanstalk automatically handles the deployment, from capacity provisioning, load balancing, auto-scaling to application health monitoring. At the same time, you retain full control over the AWS resources powering your application and can access the underlying resources at any time.</p>
 <p><strong>AWS Mobile Farm</strong> - This is an invalid option, given only as a distractor.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/device-farm/">https://aws.amazon.com/device-farm/</a></p>
</div>

**Question 54**

54. Which AWS service can be used to host a static website with the LEAST effort?
*  A. Amazon S3 Glacier
*  B. AWS Storage Gateway
*  C. Amazon Simple Storage Service (Amazon S3)
*  D. Amazon Elastic File System (Amazon EFS)

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon Simple Storage Service (Amazon S3)</strong></p>
 <p>Amazon S3 is an object storage service that offers industry-leading scalability, data availability, security, and performance. Amazon S3’s flat, non-hierarchical structure and various management features are helping customers of all sizes and industries organize their data in ways that are valuable to their businesses and teams.</p>
 <p>To host a static website on Amazon S3, you configure an Amazon S3 bucket for website hosting and then upload your website content to the bucket. When you configure a bucket as a static website, you must enable website hosting, set permissions, and create and add an index document.</p>
 <p>Hosting a static website on Amazon S3: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q37-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS Storage Gateway</strong> - AWS Storage Gateway is a hybrid cloud storage service that gives you on-premises access to virtually unlimited cloud storage. Customers use Storage Gateway to simplify storage management and reduce costs for key hybrid cloud storage use cases. It helps on-premises applications to access data on AWS Cloud. It cannot be used to host a website.</p>
 <p><strong>Amazon Elastic File System (Amazon EFS)</strong> - Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed elastic NFS file system for use with AWS Cloud services and on-premises resources. EFS storage option cannot directly be used to host a website, EFS needs to be mounted on Amazon EC2 to work as a static website.</p>
 <p><strong>Amazon S3 Glacier</strong> - Amazon S3 Glacier is a secure, durable, and extremely low-cost Amazon S3 cloud storage class for data archiving and long-term backup. As you see, this cannot be used for hosting a website.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html</a></p>
</div>

**Question 55**

55. Which of the following AWS storage services can be directly used with on-premises systems?
*  A. Amazon Elastic Block Store (EBS)
*  B. Amazon Simple Storage Service (Amazon S3)
*  C. Amazon Elastic File System (Amazon EFS)
*  D. Amazon EC2 Instance Store

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option: <strong>Amazon Elastic File System (Amazon EFS)</strong></p>
 <p>Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed elastic NFS file system for use with AWS Cloud services and on-premises resources.</p>
 <p>To access EFS file systems from on-premises, you must have an AWS Direct Connect or AWS VPN connection between your on-premises datacenter and your Amazon VPC. You mount an EFS file system on your on-premises Linux server using the standard Linux mount command for mounting a file system</p>
 <p>How EFS Works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/product-page-diagram-Amazon-EFS-Launch_How-It-Works.cf947858f0ef3557b9fc14077bdf3f65b3f9ff43.png?raw=true"> via - <a href="https://aws.amazon.com/efs/faq/">https://aws.amazon.com/efs/faq/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Elastic Block Store (EBS)</strong> - Amazon Elastic Block Store (EBS) is an easy to use, high-performance block storage service designed for use with Amazon Elastic Compute Cloud (EC2) for both throughput and transaction-intensive workloads at any scale. EBS volumes can only be mounted with Amazon EC2.</p>
 <p><strong>Amazon EC2 Instance Store</strong> - An instance store provides temporary block-level storage for your Amazon EC2 instance. This storage is located on disks that are physically attached to the host computer. It is not possible to use this storage from on-premises systems.</p>
 <p><strong>Amazon Simple Storage Service (Amazon S3)</strong> - Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance. Amazon S3 can be accessed from on-premises only via AWS Storage Gateway. It is not possible to access S3 directly from on-premises systems.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/efs/faq/">https://aws.amazon.com/efs/faq/</a></p>
</div>

**Question 56**

56. Which AWS service would you choose for a data processing project that needs a schemaless database?
*  A. Amazon Aurora
*  B. Amazon RDS
*  C. Amazon RedShift
*  D. Amazon DynamoDB

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon DynamoDB</strong></p>
 <p>Amazon DynamoDB is a key-value and document database that delivers single-digit millisecond performance at any scale. It's a fully managed, multi-Region, multi-master, durable database with built-in security, backup and restore, and in-memory caching for internet-scale applications. DynamoDB is schemaless. DynamoDB can manage structured or semistructured data, including JSON documents.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon RedShift</strong> - Amazon Redshift is a fully-managed petabyte-scale cloud-based data warehouse product designed for large scale data set storage and analysis. Amazon Redshift requires a well-defined schema.</p>
 <p><strong>Amazon Aurora</strong> - Amazon Aurora is an AWS service for relational databases. Aurora requires a well-defined schema.</p>
 <p><strong>Amazon RDS</strong> - Amazon RDS is an AWS service for relational databases. RDS requires a well-defined schema.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/dynamodb/features/">https://aws.amazon.com/dynamodb/features/</a></p>
 <p><a href="https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/SQLtoNoSQL.WhyDynamoDB.html">https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/SQLtoNoSQL.WhyDynamoDB.html</a></p>
</div>

**Question 57**

57. AWS Trusted Advisor can provide alerts on which of the following common security misconfigurations? (Select two)?
*  A. When you don't turn on user activity logging (AWS CloudTrail)
*  B. When you share IAM user credentials with others
*  C. When you allow public access to Amazon S3 buckets
*  D. When you don't tag objects in S3 buckets
*  E. When you don't enable data encryption on S3 Glacier

**Answer** A, C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>When you allow public access to Amazon S3 buckets</strong></p>
 <p><strong>When you don't turn on user activity logging (AWS CloudTrail)</strong></p>
 <p>AWS Trusted Advisor is an online tool that provides real-time guidance to help provision your resources following AWS best practices. Whether establishing new workflows, developing applications, or as part of ongoing improvement, recommendations provided by Trusted Advisor regularly help keep your solutions provisioned optimally. AWS Trusted Advisor analyzes your AWS environment and provides best practice recommendations in five categories: Cost Optimization, Performance, Security, Fault Tolerance, Service Limits.</p>
 <p>Trusted Advisor inspects your AWS environment and makes recommendations when opportunities may exist to save money, improve system performance, or close security gaps. It provides alerts on several of the most common security misconfigurations that can occur, including leaving certain ports open that make you vulnerable to hacking and unauthorized access, neglecting to create IAM accounts for your internal users, allowing public access to Amazon S3 buckets, not turning on user activity logging (AWS CloudTrail), or not using MFA on your root AWS Account.</p>
 <p>How Trusted Advisor Works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/AWS-trusted-advisor.5b9909d5f29f680eeb12ccff536e8d88d8701304.png?raw=true"> via - <a href="https://aws.amazon.com/premiumsupport/technology/trusted-advisor/">https://aws.amazon.com/premiumsupport/technology/trusted-advisor/</a></p>
 <p>Incorrect options:</p>
 <p><strong>When you don't tag objects in S3 buckets</strong> - Tagging objects (or any resource) in S3 is not mandatory and it's not a security threat.</p>
 <p><strong>"When you share IAM user credentials with others"</strong> - It is the customer's responsibility to adhere to the IAM security best practices and never share the IAM user credentials with others. Trusted Advisor cannot send an alert for such use-cases.</p>
 <p><strong>When you don't enable data encryption on S3 Glacier</strong> - By default, data on S3 Glacier is encrypted. So, this option has been added as a distractor.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/premiumsupport/technology/trusted-advisor/best-practice-checklist/">https://aws.amazon.com/premiumsupport/technology/trusted-advisor/best-practice-checklist/</a></p>
</div>

**Question 58**

58. Which AWS Route 53 routing policy would you use to route traffic to a single resource such as a web server for your website?
*  A. Failover routing policy
*  B. Weighted routing policy
*  C. Latency routing policy
*  D. Simple routing policy

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Simple routing policy</strong></p>
 <p>Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service. It is designed to give developers and businesses an extremely reliable and cost-effective way to route end users to Internet applications by translating names like www.example.com into the numeric IP addresses like 192.0.2.1 that computers use to connect to each other.</p>
 <p>Simple routing lets you configure standard DNS records, with no special Route 53 routing such as weighted or latency. With simple routing, you typically route traffic to a single resource, for example, to a web server for your website.</p>
 <p>Route 53 Routing Policy Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q3-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html">https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Failover routing policy</strong> - This routing policy is used when you want to configure active-passive failover.</p>
 <p><strong>Weighted routing policy</strong> - This routing policy is used to route traffic to multiple resources in proportions that you specify.</p>
 <p><strong>Latency routing policy</strong> - This routing policy is used when you have resources in multiple AWS Regions and you want to route traffic to the region that provides the best latency.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html">https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html</a></p>
</div>

**Question 59**

59. Which of the following statements are true regarding Amazon Simple Storage Service (S3) (Select two)?
*  A. S3 is a fully managed, elastic file system storage service used as database backup
*  B. S3 is a block storage service designed for a broad range of workloads
*  C. S3 is a key value based object storage service
*  D. S3 stores data in a flat non-hierarchical structure
*  E. You can install databases on S3

**Answer** C, D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>S3 is a key value based object storage service</strong></p>
 <p><strong>S3 stores data in a flat non-hierarchical structure</strong></p>
 <p>Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance. S3 stores data in a flat non-hierarchical structure. All objects are stored in S3 buckets and can be organized with shared names called prefixes. You can also append up to 10 key-value pairs called S3 object tags to each object, which can be created, updated, and deleted throughout an object’s lifecycle.</p>
 <p>Incorrect options:</p>
 <p><strong>S3 is a block storage service designed for a broad range of workloads</strong> - Block storage service is provided by Amazon Elastic Block Store (EBS) to provide persistent block-level storage volumes for use with Amazon EC2 instances. S3 is an object storage service.</p>
 <p><strong>S3 is a fully managed, elastic file system storage service used as database backup</strong> - Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed elastic NFS file system for use with AWS Cloud services and on-premises resources. S3 is an object storage service.</p>
 <p><strong>You can install databases on S3</strong> - S3 is an object storage service. You cannot install databases on S3.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/s3/features/">https://aws.amazon.com/s3/features/</a></p>
</div>

**Question 60**

60. Which of the following describes an Availability Zone in the AWS Cloud?
*  A. One or more server racks in multiple locations
*  B. One or more server racks in the same location
*  C. One or more data centers in the same location
*  D. One or more data centers in multiple locations

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p>"One or more data centers in the same location"</p>
 <p>An Availability Zone (AZ) is one or more discrete data centers with redundant power, networking, and connectivity in an AWS Region. An AWS Region refers to a physical location around the world where AWS clusters data centers. AZ’s give customers the ability to operate production applications and databases that are more highly available, fault-tolerant, and scalable than would be possible from a single data center. All AZ’s in an AWS Region are interconnected with high-bandwidth, low-latency networking, over fully redundant, dedicated metro fiber providing high-throughput, low-latency networking between AZ’s.</p>
 <p>AWS Regions and Availability Zones Explained: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q60-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/about-aws/global-infrastructure/regions_az/">https://aws.amazon.com/about-aws/global-infrastructure/regions_az/</a></p>
 <p>Incorrect options:</p>
 <p>"One or more data centers in multiple locations"</p>
 <p>"One or more server racks in the same location"</p>
 <p>"One or more server racks in multiple locations"</p>
 <p>These three options contradict the details provided earlier in the explanation, so these options are incorrect.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/about-aws/global-infrastructure/regions_az/">https://aws.amazon.com/about-aws/global-infrastructure/regions_az/</a></p>
</div>

**Question 61**

61. Which of the following AWS services can be used to forecast your AWS account usage and costs?
*  A. AWS Pricing Calculator
*  B. AWS Cost Explorer
*  C. AWS Budgets
*  D. AWS Cost and Usage Reports

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>AWS Cost Explorer</strong></p>
 <p>AWS Cost Explorer has an easy-to-use interface that lets you visualize, understand, and manage your AWS costs and usage over time. AWS Cost Explorer includes a default report that helps you visualize the costs and usage associated with your top five cost-accruing AWS services, and gives you a detailed breakdown of all services in the table view. The reports let you adjust the time range to view historical data going back up to twelve months to gain an understanding of your cost trends. AWS Cost Explorer also supports forecasting to get a better idea of what your costs and usage may look like in the future so that you can plan.</p>
 <p>AWS Cost Explorer Features: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q47-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/aws-cost-management/aws-cost-explorer/">https://aws.amazon.com/aws-cost-management/aws-cost-explorer/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS Cost and Usage Reports</strong> - The AWS Cost and Usage Reports (AWS CUR) contains the most comprehensive set of cost and usage data available. You can use Cost and Usage Reports to publish your AWS billing reports to an Amazon Simple Storage Service (Amazon S3) bucket that you own. You can receive reports that break down your costs by the hour or month, by product or product resource, or by tags that you define yourself. AWS updates the report in your bucket once a day in a comma-separated value (CSV) format. AWS Cost and Usage Reports cannot forecast your AWS account cost and usage.</p>
 <p><strong>AWS Budgets</strong> - AWS Budgets gives the ability to set custom budgets that alert you when your costs or usage exceed (or are forecasted to exceed) your budgeted amount. You can also use AWS Budgets to set reservation utilization or coverage targets and receive alerts when your utilization drops below the threshold you define. Budgets can be created at the monthly, quarterly, or yearly level, and you can customize the start and end dates. You can further refine your budget to track costs associated with multiple dimensions, such as AWS service, linked account, tag, and others. AWS Budgets cannot forecast your AWS account cost and usage.</p>
 <p><strong>AWS Pricing Calculator</strong> - AWS Pricing Calculator lets you explore AWS services and create an estimate for the cost of your use cases on AWS. You can model your solutions before building them, explore the price points and calculations behind your estimate, and find the available instance types and contract terms that meet your needs. This enables you to make informed decisions about using AWS. You can plan your AWS costs and usage or price out setting up a new set of instances and services. You cannot use this service to forecast your AWS account cost and usage.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/aws-cost-management/aws-cost-explorer/">https://aws.amazon.com/aws-cost-management/aws-cost-explorer/</a></p>
</div>

**Question 62**

62. Which of the following are the serverless computing services offered by AWS (Select two)
*  A. Amazon Lightsail
*  B. Amazon Elastic Compute Cloud (EC2)
*  C. AWS Fargate
*  D. AWS Lambda
*  E. AWS Elastic Beanstalk

**Answer** C, D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p>Serverless is the native architecture of the cloud that enables you to shift more of your operational responsibilities to AWS, increasing your agility and innovation. Serverless allows you to build and run applications and services without thinking about servers. It eliminates infrastructure management tasks such as server or cluster provisioning, patching, operating system maintenance, and capacity provisioning.</p>
 <p>The AWS serverless platform overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q46-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/serverless/">https://aws.amazon.com/serverless/</a></p>
 <p><strong>AWS Lambda</strong> - With Lambda, you can run code for virtually any type of application or backend service - all with zero administration. Just upload your code and Lambda takes care of everything required to run and scale your code with high availability. You can set up your code to automatically trigger from other AWS services or call it directly from any web or mobile app.</p>
 <p>AWS Lambda lets you run code without provisioning or managing servers. You pay only for the compute time you consume - there is no charge when your code is not running.</p>
 <p><strong>AWS Fargate</strong> - AWS Fargate is a serverless compute engine for containers that works with both Amazon Elastic Container Service (ECS) and Amazon Elastic Kubernetes Service (EKS). Fargate makes it easy for you to focus on building your applications. Fargate removes the need to provision and manage servers, lets you specify and pay for resources per application, and improves security through application isolation by design.</p>
 <p>AWS Fargate is a purpose-built serverless compute engine for containers. Fargate scales and manages the infrastructure required to run your containers.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Elastic Compute Cloud (EC2)</strong> - Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud with support for per-second billing. It is the easiest way to provision servers on AWS Cloud and access the underlying OS. Amazon EC2 reduces the time required to obtain and boot new server instances to minutes, allowing you to quickly scale capacity, both up and down, as your computing requirements change.</p>
 <p><strong>AWS Elastic Beanstalk</strong> - AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling web applications and services. You simply upload your code and Elastic Beanstalk automatically handles the deployment, from capacity provisioning, load balancing, auto-scaling to application health monitoring. Beanstalk provisions servers so it is not a serverless service.</p>
 <p><strong>Amazon Lightsail</strong> - Lightsail is an easy-to-use cloud platform that offers you everything needed to build an application or website, plus a cost-effective, monthly plan. Lightsail offers several preconfigured, one-click-to-launch operating systems, development stacks, and web applications, including Linux, Windows OS, and WordPress.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/serverless/">https://aws.amazon.com/serverless/</a></p>
 <p><a href="https://aws.amazon.com/fargate/">https://aws.amazon.com/fargate/</a></p>
</div>

**Question 63**

63. Which of the following entities should be used for an Amazon EC2 Instance to access a DynamoDB table?
*  A. Amazon Cognito
*  B. IAM role
*  C. AWS Key Management Service
*  D. AWS IAM user access keys

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>IAM Role</strong></p>
 <p>An IAM Role is an IAM identity that you can create in your account that has specific permissions. An IAM role is similar to an IAM user in that it is an AWS identity with permissions policies that determine what the identity can and cannot do in AWS. When you assume a role, it provides you with temporary security credentials for your role session.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS IAM user access keys</strong> - Access keys are long-term credentials for an IAM user or the AWS account root user. You can use access keys to sign programmatic requests to the AWS CLI or AWS API (directly or using the AWS SDK). Access keys consist of two parts: an access key ID and a secret access key. As a user name and password, you must use both the access key ID and secret access key together to authenticate your requests. As a best practice, AWS suggests the use of temporary security credentials (IAM roles) instead of access keys.</p>
 <p><strong>Amazon Cognito</strong> - Amazon Cognito lets you add user sign-up, sign-in, and access control to your web and mobile apps quickly and easily. Amazon Cognito scales to millions of users and supports sign-in with social identity providers, such as Facebook, Google, and Amazon, and enterprise identity providers via SAML 2.0. Amazon Cognito cannot be used to facilitate an Amazon EC2 Instance to access a DynamoDB table.</p>
 <p><strong>AWS Key Management Service</strong> - AWS Key Management Service (KMS) makes it easy for you to create and manage cryptographic keys and control their use across a wide range of AWS services and in your applications. AWS KMS is a secure and resilient service that uses hardware security modules that have been validated under FIPS 140-2, or are in the process of being validated, to protect your keys. AWS KMS cannot be used to facilitate an Amazon EC2 Instance to access a DynamoDB table.</p>
 <p>Reference:</p>
 <p><a href="https://docs.amazonaws.cn/en_us/amazondynamodb/latest/developerguide/authentication-and-access-control.html">https://docs.amazonaws.cn/en_us/amazondynamodb/latest/developerguide/authentication-and-access-control.html</a></p>
</div>

**Question 64**

64. Which of the following entities can be used to connect to an EC2 server from a Mac OS, Windows or Linux based computer via a browser-based client?
*  A. AWS Direct Connect
*  B. Putty
*  C. EC2 Instance Connect
*  D. SSH

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>EC2 Instance Connect</strong></p>
 <p>Amazon EC2 Instance Connect provides a simple and secure way to connect to your instances using Secure Shell (SSH). With EC2 Instance Connect, you use AWS Identity and Access Management (IAM) policies and principals to control SSH access to your instances, removing the need to share and manage SSH keys. All connection requests using EC2 Instance Connect are logged to AWS CloudTrail so that you can audit connection requests.</p>
 <p>You can use Instance Connect to connect to your Linux instances using a browser-based client, the Amazon EC2 Instance Connect CLI, or the SSH client of your choice. EC2 Instance Connect can be used to connect to an EC2 instance from a Mac OS, Windows or Linux based computer.</p>
 <p>Incorrect options:</p>
 <p><strong>SSH</strong> - SSH can be used from a Mac OS, Windows or Linux based computer, but it's not a browser-based client.</p>
 <p><strong>Putty</strong> - Putty can be used only from Windows based computers.</p>
 <p><strong>AWS Direct Connect</strong> - AWS Direct Connect is a cloud service solution that makes it easy to establish a dedicated network connection from your premises to AWS. You can use AWS Direct Connect to establish a private virtual interface from your on-premise network directly to your Amazon VPC. This private connection takes at least one month for completion. Direct Connect cannot be used to connect to an EC2 instance from a Mac OS, Windows or Linux based computer.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/Connect-using-EC2-Instance-Connect.html">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/Connect-using-EC2-Instance-Connect.html</a></p>
</div>

**Question 65**

65. Which of the following is correct regarding the AWS RDS service?
*  A. You can use Read Replicas for Disaster Recovery and Multi-AZ for improved read performance
*  B. You can use both Read Replicas and Multi-AZ for improved read performance
*  C. You can use Read Replicas for improved read performance and Multi-AZ for Disaster Recovery
*  D. You can use Read Replicas for both improved read performance as well as Disaster Recovery

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>You can use Read Replicas for both improved read performance as well as Disaster Recovery</strong></p>
 <p>Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a relational database in the cloud. Read Replicas allow you to create read-only copies that are synchronized with your master database. Read Replicas are used for improved read performance. You can also place your read replica in a different AWS Region closer to your users for better performance. Using a cross-Region Read Replica can also help ensure that you get back up and running if you experience a regional availability issue in case of a disaster. Read Replicas are an example of horizontal scaling of resources.</p>
 <p>Read Replica Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/pt4-q8-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/rds/features/multi-az/">https://aws.amazon.com/rds/features/multi-az/</a></p>
 <p>Amazon RDS Multi-AZ deployments provide enhanced availability and durability for RDS database (DB) instances, making them a natural fit for production database workloads. When you provision a Multi-AZ DB Instance, Amazon RDS automatically creates a primary DB Instance and synchronously replicates the data to a standby instance in a different Availability Zone (AZ). Amazon RDS performs an automatic failover to the standby so that you can resume database operations as soon as the failover is complete. Since the endpoint for your DB Instance remains the same after a failover, your application can resume database operation without the need for manual administrative intervention. Think of multi-AZ as enhancing the availability and reliability of your system, however, by itself, multi-AZ cannot be used for disaster recovery.</p>
 <p>How Multi-AZ Works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/Udemy/images4/multi-az-deployments.bda9d7bf45a74103d0331a985baf2c5fb838a0fa.png?raw=true"> via - <a href="https://aws.amazon.com/rds/features/multi-az/">https://aws.amazon.com/rds/features/multi-az/</a></p>
 <p>To understand the RDS disaster recovery capabilities in more detail, you can refer to this excellent AWS blog: <a href="https://aws.amazon.com/blogs/database/implementing-a-disaster-recovery-strategy-with-amazon-rds/">https://aws.amazon.com/blogs/database/implementing-a-disaster-recovery-strategy-with-amazon-rds/</a></p>
 <p>Incorrect options:</p>
 <p><strong>You can use Read Replicas for improved read performance and Multi-AZ for Disaster Recovery</strong></p>
 <p><strong>You can use both Read Replicas and Multi-AZ for improved read performance</strong></p>
 <p><strong>You can use Read Replicas for Disaster Recovery and Multi-AZ for improved read performance</strong></p>
 <p>These three options contradict the details provided earlier in the explanation, so these options are incorrect.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/blogs/database/implementing-a-disaster-recovery-strategy-with-amazon-rds/">https://aws.amazon.com/blogs/database/implementing-a-disaster-recovery-strategy-with-amazon-rds/</a></p>
 <p><a href="https://aws.amazon.com/rds/features/multi-az/">https://aws.amazon.com/rds/features/multi-az/</a></p>
</div>
