# AWS Certified Practitioner Exam

## Exam 05

**Question 1**

1. A company is planning to implement Chaos Engineering to expose any blind spots that can disrupt the resiliency of the application.
*  A. AWS Fault Injection Simulator
*  B. AWS Trusted Advisor
*  C. Amazon Inspector
*  D. AWS GuardDuty

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Fault Injection Simulator</strong></p>
 <p>AWS Fault Injection Simulator is a fully managed service for running fault injection experiments on AWS that makes it easier to improve an application’s performance, observability, and resiliency. Fault injection experiments are used in chaos engineering, which is the practice of stressing an application in testing or production environments by creating disruptive events, such as a sudden increase in CPU or memory consumption, observing how the system responds, and implementing improvements. Fault injection experiment helps teams create the real-world conditions needed to uncover the hidden bugs, monitoring blind spots, and performance bottlenecks that are difficult to find in distributed systems.</p>
 <p>Fault Injection Simulator simplifies the process of setting up and running controlled fault injection experiments across a range of AWS services so teams can build confidence in their application behavior. With Fault Injection Simulator, teams can quickly set up experiments using pre-built templates that generate the desired disruptions. Fault Injection Simulator provides the controls and guardrails that teams need to run experiments in production, such as automatically rolling back or stopping the experiment if specific conditions are met. With a few clicks in the console, teams can run complex scenarios with common distributed system failures happening in parallel or building sequentially over time, enabling them to create the real-world conditions necessary to find hidden weaknesses.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Inspector</strong> - Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. Amazon Inspector automatically assesses applications for exposure, vulnerabilities, and deviations from best practices. After performing an assessment, Amazon Inspector produces a detailed list of security findings prioritized by level of severity.</p>
 <p><strong>AWS Trusted Advisor</strong> - AWS Trusted Advisors provides recommendations that help you follow AWS best practices. Trusted Advisor evaluates your account by using checks. These checks identify ways to optimize your AWS infrastructure, improve security and performance, reduce costs, and monitor service quotas. You can then follow the check recommendations to optimize your services and resources.</p>
 <p><strong>AWS GuardDuty</strong> - Amazon GuardDuty is a threat detection service that continuously monitors your AWS accounts and workloads for malicious activity and delivers detailed security findings for visibility and remediation.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/fis/features/">https://aws.amazon.com/fis/features/</a></p>
</div>

**Question 2**

2. A multinational company has just moved its infrastructure to AWS Cloud and has employees traveling to different offices around the world. How should the company set the AWS accounts?
*  A. Create 'global' permissions so users can access resources from all around the world
*  B. As employees travel, they can use other employees' accounts
*  C. There is nothing to do, IAM is a global service
*  D. Create an IAM user for each user in each region

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>There is nothing to do, IAM is a global service</strong></p>
 <p>AWS Identity and Access Management (IAM) enables you to manage access to AWS services and resources securely. Using IAM, you can create and manage AWS users and groups, and use permissions to allow and deny their access to AWS resources.</p>
 <p>IAM is a global service. Users created within IAM can access their accounts all around the world, and deploy resources in every region.</p>
 <p>Incorrect options:</p>
 <p><strong>Create an IAM user for each user in each region</strong> - IAM users can access their accounts in different regions.</p>
 <p><strong>Create 'global' permissions so users can access resources from all around the world</strong> - IAM is a global service. You can use it globally without implementing anything.</p>
 <p><strong>As employees travel, they can use other employees' accounts</strong> - You should never share IAM users.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/iam/">https://aws.amazon.com/iam/</a></p>
</div>

**Question 3**

3. Which of the following criteria are used to charge for Elastic Block Store (EBS) volumes? (Select TWO)
*  A. Provisioned IOPS
*  B. Volume type
*  C. Data type
*  D. Data transfer IN
*  E. The EC2 instance type the EBS volume is attached to

**Answer** A, B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Provisioned IOPS</strong></p>
 <p><strong>Volume Type</strong></p>
 <p>Amazon Elastic Block Store (Amazon EBS) provides persistent block storage volumes for use with Amazon EC2 instances in the AWS Cloud. Each Amazon EBS volume is automatically replicated within its Availability Zone to protect you from component failure, offering high availability and durability. Amazon EBS volumes offer the consistent and low-latency performance needed to run your workloads. With Amazon EBS, you can scale your usage up or down within minutes—all while paying a low price for only what you provision.</p>
 <p>The fundamentals charges for EBS volumes are: the volume type (based on performance), the storage volume in GB per month provisioned, the number of IOPS provisioned per month, the storage consumed by snapshots, and outbound data transfer.</p>
 <p>Incorrect options:</p>
 <p><strong>Data transfer IN</strong> - Data transfer-in is always free, including for EBS volumes.</p>
 <p><strong>The EC2 instance type the EBS volume is attached to</strong> - The EC2 instance type the EBS volume is attached to does not influence the EBS volume pricing.</p>
 <p><strong>Data type</strong> - The type of data stored on EBS volumes does not influence the price.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/ebs/pricing/">https://aws.amazon.com/ebs/pricing/</a></p>
</div>

**Question 4**

4. An e-commerce company would like to build a chatbot for its customer service using Natural Language Understand (NLU). As a Cloud Practitioner, which AWS service would you use?
*  A. Amazon SageMaker
*  B. Amazon Lex
*  C. Amazon Rekognition
*  D. Amazon Comprehend

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon Lex</strong> - Amazon Lex is a service for building conversational interfaces using voice and text. Powered by the same conversational engine as Alexa, Amazon Lex provides high-quality speech recognition and language understanding capabilities, enabling the addition of sophisticated, natural language ‘chatbots’ to new and existing applications.</p>
 <p>Amazon Lex Use Cases:</p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q2-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/lex/">https://aws.amazon.com/lex/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Rekognition</strong> - With Amazon Rekognition, you can identify objects, people, text, scenes, and activities in images and videos, as well as to detect any inappropriate content. Amazon Rekognition also provides highly accurate facial analysis and facial search capabilities that you can use to detect, analyze, and compare faces for a wide variety of user verification, people counting, and public safety use cases.</p>
 <p><strong>Amazon SageMaker</strong> - Amazon SageMaker is a fully-managed platform that enables developers and data scientists to quickly and easily build, train, and deploy machine learning models at any scale. Amazon SageMaker removes all the barriers that typically slow down developers who want to use machine learning.</p>
 <p><strong>Amazon Comprehend</strong> - Amazon Comprehend is a natural language processing (NLP) service that uses machine learning to find meaning and insights in text. Natural Language Processing (NLP) is a way for computers to analyze, understand, and derive meaning from textual information in a smart and useful way. By utilizing NLP, you can extract important phrases, sentiment, syntax, key entities such as brand, date, location, person, etc., and the language of the text.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/lex/">https://aws.amazon.com/lex/</a></p>
</div>

**Question 5**

5. A company would like to reserve EC2 compute capacity for three years to reduce costs. The company also plans to increase their workloads during this period. As a Cloud Practitioner, which EC2 Reserved Instance type would you recommend?
*  A. Scheduled Reserved Instances
*  B. Adaptable Reserved Instances
*  C. Standard Reserved Instances
*  D. Convertible Reserved Instances

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Convertible Reserved Instances</strong></p>
 <p>Purchase Convertible Reserved Instances if you need additional flexibility, such as the ability to use different instance families, operating systems, or tenancies over the Reserved Instance term. Convertible Reserved Instances provide you with a significant discount (up to 54%) compared to On-Demand Instances and can be purchased for a 1-year or 3-year term.</p>
 <p>Convertible Reserved Instances can be useful when workloads are likely to change. In this case, a Convertible Reserved Instance enables you to adapt as needs evolve while still obtaining discounts and capacity reservations.</p>
 <p>EC2 Pricing Options Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q1-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/ec2/pricing/">https://aws.amazon.com/ec2/pricing/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Standard Reserved Instances</strong> - Standard Reserved Instances provide you with a significant discount (up to 72%) compared to On-Demand Instance pricing, and can be purchased for a 1-year or 3-year term. Standard Reserved Instances do not offer as much flexibility as Convertible Reserved Instances (such as not being able to change the instance family type), and therefore are not best-suited for this use case.</p>
 <p>Review the differences between Standard Reserved Instances and Convertible Reserved Instances: <a href="https://docs.aws.amazon.com/whitepapers/latest/cost-optimization-reservation-models/standard-vs.-convertible-offering-classes.html">https://docs.aws.amazon.com/whitepapers/latest/cost-optimization-reservation-models/standard-vs.-convertible-offering-classes.html</a></p>
 <p><strong>Scheduled Reserved Instances</strong> - AWS does not support Scheduled Reserved Instances, so this option is ruled out.</p>
 <p><strong>Adaptable Reserved Instances</strong> - Adaptable Reserved Instances are not a valid type of reserved instances. It is a distractor.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/ec2/pricing/reserved-instances/pricing/">https://aws.amazon.com/ec2/pricing/reserved-instances/pricing/</a></p>
</div>

**Question 6**

6. A company using a hybrid cloud would like to store secondary backup copies of the on-premises data. Which S3 Storage Class would you use for a cost-optimal yet rapid access solution?
*  A. S3 Standard - Infrequent Access
*  B. S3 One Zone - Infrequent Access
*  C. S3 Standard - General Purposes
*  D. S3 Glacier

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>S3 One Zone - Infrequent Access</strong></p>
 <p>S3 One Zone-IA is for data that is accessed less frequently but requires rapid access when needed. Unlike other S3 Storage Classes which store data in a minimum of three Availability Zones (AZs), S3 One Zone-IA stores data in a single AZ and costs 20% less than S3 Standard-IA. S3 One Zone-IA is ideal for customers who want a lower-cost option for infrequently accessed data but do not require the availability and resilience of S3 Standard or S3 Standard-IA. It’s a good choice for storing secondary backup copies of on-premises data or easily re-creatable data. You can also use it as cost-effective storage for data that is replicated from another AWS Region using S3 Cross-Region Replication.</p>
 <p>Exam Alert:</p>
 <p>Please review this detailed comparison on S3 Storage Classes as you can expect a few questions on this aspect of S3: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q17-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/s3/storage-classes/">https://aws.amazon.com/s3/storage-classes/</a></p>
 <p>Incorrect options:</p>
 <p><strong>S3 Glacier</strong> - S3 Glacier is a secure, durable, and low-cost storage class for data archiving. You can reliably store any amount of data at costs that are competitive with or cheaper than on-premises solutions. It is not used for secondary backup copies but for archiving data.</p>
 <p><strong>S3 Standard - General Purposes</strong> - S3 Standard offers high durability, availability, and performance object storage for frequently accessed data. Because it delivers low latency and high throughput, S3 Standard is appropriate for a wide variety of use cases, including cloud applications, dynamic websites, content distribution, mobile and gaming applications, and big data analytics. However, it is not used to store secondary backup copies of on-premises data as data store in S3 Standard - General Purposes is for frequently accessed data.</p>
 <p><strong>S3 Standard - Infrequent Access</strong> - S3 Standard-IA is for data that is accessed less frequently, but requires rapid access when needed. S3 Standard-IA offers the high durability, high throughput, and low latency of S3 Standard, with a low per GB storage price and per GB retrieval fee. This combination of low cost and high performance makes S3 Standard-IA ideal for long-term storage, backups, and as a data store for disaster recovery files. It can be used for backups, but it is more expensive than S3 One Zone - Infrequent Access. Hence, S3 One Zone - Infrequent Access is a better option for secondary backup copies.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/s3/storage-classes/">https://aws.amazon.com/s3/storage-classes/</a></p>
</div>

**Question 7**

7. An organization would like to copy data across different Availability Zones (AZs) using EBS snapshots. Where are EBS snapshots stored in the AWS Cloud?
*  A. Amazon EC2
*  B. Amazon S3
*  C. Amazon EFS
*  D. Amazon RDS

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon S3</strong></p>
 <p>You can create a point-in-time snapshot of an EBS volume and use it as a baseline for new volumes or data backup. If you make periodic snapshots of a volume, the snapshots are incremental—the new snapshot saves only the blocks that have changed since your last snapshot.</p>
 <p>You can back up the data on your Amazon EBS volumes to Amazon S3 by taking point-in-time snapshots.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon EC2</strong> - Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud. It is designed to make web-scale computing easier for developers. EBS snapshots cannot be stored on Amazon EC2.</p>
 <p><strong>Amazon RDS</strong> - Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a relational database in the cloud. EBS snapshots cannot be stored on Amazon RDS.</p>
 <p><strong>Amazon EFS</strong> - Amazon Elastic File System (Amazon EFS) provides a simple, scalable, elastic file system for Linux-based workloads for use with AWS Cloud services and on-premises resources. EBS snapshots cannot be stored on Amazon EFS.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSSnapshots.html">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSSnapshots.html</a></p>
</div>

**Question 8**

8. A company needs to keep sensitive data in its own data center due to compliance but would still like to deploy resources using AWS. Which Cloud deployment model does this refer to?
*  A. Hybrid Cloud
*  B. On-premises
*  C. Private Cloud
*  D. Public Cloud

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Hybrid Cloud</strong></p>
 <p>A hybrid deployment is a way to connect infrastructure and applications between cloud-based resources and existing resources that are not located in the cloud. The most common method of hybrid deployment is between the cloud and existing on-premises infrastructure to extend, and grow, an organization's infrastructure into the cloud while connecting cloud resources to the internal system.</p>
 <p>Overview of Cloud Computing Deployment Models: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q4-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/types-of-cloud-computing/">https://aws.amazon.com/types-of-cloud-computing/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Public Cloud</strong> - A public cloud-based application is fully deployed in the cloud and all parts of the application run in the cloud. Applications in the cloud have either been created in the cloud or have been migrated from an existing infrastructure to take advantage of the benefits of cloud computing.</p>
 <p><strong>Private Cloud</strong> - Unlike a Public cloud, a Private cloud enables businesses to avail IT services that are provisioned and customized according to their precise needs. The business can further avail the IT services securely and reliably over a private IT infrastructure.</p>
 <p><strong>On-premises</strong> - This is not a cloud deployment model. When an enterprise opts for on-premises,it needs to create, upgrade, and scale the on-premise IT infrastructure by investing in sophisticated hardware, compatible software, and robust services. Also, the business needs to deploy dedicated IT staff to upkeep, scale, and manage the on-premise infrastructure continuously.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/what-is-cloud-computing/">https://aws.amazon.com/what-is-cloud-computing/</a></p>
</div>

**Question 9**

9. A company would like to audit requests made to an S3 bucket. As a Cloud Practitioner, which S3 feature would you recommend addressing this use-case?
*  A. S3 Versioning
*  B. S3 Access Logs
*  C. S3 Bucket Policies
*  D. S3 Cross-Region Replication (CRR)

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>S3 Access Logs</strong></p>
 <p>Server access logging provides detailed records for the requests that are made to a bucket. Server access logs are useful for many applications. For example, access log information can be useful in security and access audits.</p>
 <p>It can also help you learn about your customer base and understand your Amazon S3 bill.</p>
 <p>Incorrect options:</p>
 <p><strong>S3 Cross-Region Replication (CRR)</strong> - Replication enables automatic, asynchronous copying of objects across Amazon S3 buckets. Cross-Region replication (CRR) is used to copy objects across Amazon S3 buckets in different AWS Regions. It does not help with auditing requests made to your bucket.</p>
 <p><strong>S3 Bucket Policies</strong> - A bucket policy is a resource-based AWS Identity and Access Management (IAM) policy. You add a bucket policy to a bucket to grant other AWS accounts or IAM users access permissions for the bucket and the objects in it. Object permissions apply only to the objects that the bucket owner creates. It does not help with auditing requests made to your bucket.</p>
 <p><strong>S3 Versioning</strong> - Versioning is a means of keeping multiple variants of an object in the same bucket. You can use versioning to preserve, retrieve, and restore every version of every object stored in your Amazon S3 bucket. With versioning, you can easily recover from both unintended user actions and application failures. It does not help with auditing requests made to your bucket.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/ServerLogs.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/ServerLogs.html</a></p>
</div>

**Question 10**

10. According to the Shared Responsibility Model, which of the following is a responsibility of the customer?
*  A. Protecting hardware infrastructure
*  B. Managing DynamoDB
*  C. Firewall & networking configuration in EC2
*  D. Edge locations security

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Firewall &amp; networking configuration in EC2</strong></p>
 <p>The customers are responsible for "Security IN the cloud". In includes the configuration of the operating system, network &amp; firewall of applications.</p>
 <p>Exam Alert:</p>
 <p>Please review the Shared Responsibility Model in detail as you can expect multiple questions on the shared responsibility model in the exam: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/Shared_Responsibility_Model_V2.59d1eccec334b366627e9295b304202faf7b899b.jpg?raw=true"> via - <a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Managing DynamoDB</strong> - DynamoDB is a fully managed service. AWS operates the infrastructure layer, the operating system, and platforms, and customers access the endpoints to store and retrieve data.</p>
 <p><strong>Protecting hardware infrastructure</strong></p>
 <p><strong>Edge locations security</strong></p>
 <p>AWS is responsible for "Security OF the cloud". It includes the infrastructure, which is composed of the hardware, software, networking, and facilities that run AWS Cloud services.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
</div>

**Question 11**

11. Which security control tool can be used to deny traffic from a specific IP address?
*  A. AWS GuardDuty
*  B. VPC Flow Logs
*  C. Network ACL
*  D. Security Group

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Network ACL</strong></p>
 <p>A Network Access Control List (NACL) is an optional layer of security for your VPC that acts as a firewall for controlling traffic in and out of one or more subnets (i.e. it works at subnet level). A network ACL has separate inbound and outbound rules, and each rule can either allow or deny traffic.</p>
 <p>Network Access Control List (NACL) Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q23-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html">https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Security Group</strong> - A security group acts as a virtual firewall for your instance to control inbound and outbound traffic. Security groups act at the instance level, not at the subnet level. You can specify allow rules, but not deny rules. You can specify separate rules for inbound and outbound traffic.</p>
 <p><strong>AWS GuardDuty</strong> - Amazon GuardDuty is a threat detection service that continuously monitors for malicious or unauthorized behavior to help you protect your AWS accounts and workloads. It monitors for activity such as unusual API calls or potentially unauthorized deployments that indicate a possible account compromise. GuardDuty also detects potentially compromised instances or reconnaissance by attackers. It cannot deny traffic from a specific IP address.</p>
 <p><strong>VPC Flow Logs</strong> - VPC Flow Logs is a feature that enables you to capture information about the IP traffic going to and from network interfaces in your VPC. Flow log data can be published to Amazon CloudWatch Logs or Amazon S3. After you've created a flow log, you can retrieve and view its data in the chosen destination. However, it cannot deny traffic from a specific IP address.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html">https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html</a></p>
</div>

**Question 12**

12. A corporation would like to have a central user portal to log in to third-party business applications as well as accounts managed under AWS Organizations. As a Cloud Practitioner, which AWS service would you use for this task?
*  A. AWS Single Sign-On (SSO)
*  B. AWS Cognito
*  C. AWS Identity and Access Management (IAM)
*  D. AWS Command Line Interface (CLI)

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Single Sign-On (SSO)</strong></p>
 <p>AWS SSO is an AWS service that enables you to makes it easy to centrally manage access to multiple AWS accounts and business applications and provide users with single sign-on access to all their assigned accounts and applications from one place.</p>
 <p>With AWS SSO, you can easily manage SSO access and user permissions to all of your accounts in AWS Organizations centrally. AWS SSO allows you to create and manage user identities in AWS SSO’s identity store, or easily connect to your existing identity source including Microsoft Active Directory, Azure Active Directory (Azure AD), and Okta Universal Directory.</p>
 <p>You can use AWS SSO to quickly and easily assign and manage your employees’ access to multiple AWS accounts, SAML-enabled cloud applications (such as Salesforce, Office 365, and Box), and custom-built in-house applications, all from a central place.</p>
 <p>How AWS SSO works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q61-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/single-sign-on/">https://aws.amazon.com/single-sign-on/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS Cognito</strong> - Amazon Cognito lets you add user sign-up, sign-in, and access control to your web and mobile apps quickly and easily. With Amazon Cognito, you also have the option to authenticate users through social identity providers such as Facebook, Twitter, or Amazon, with SAML identity solutions, or by using your own identity system. It is an identity management solution for customers/developers building B2C or B2B apps for their customers.</p>
 <p><strong>AWS Identity and Access Management (IAM)</strong> - AWS Identity and Access Management (IAM) enables you to securely control access to AWS services and resources for your users. Using IAM, you can create and manage AWS users and groups, and use permissions to allow and deny their access to AWS resources. It is not used to log in but to manage users and roles.</p>
 <p><strong>AWS Command Line Interface (CLI)</strong> - The AWS Command Line Interface (CLI) is a unified tool to manage your AWS services. With just one tool to download and configure, you can control multiple AWS services from the command line and automate them through scripts. It is not a central user portal.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/single-sign-on/">https://aws.amazon.com/single-sign-on/</a></p>
</div>

**Question 13**

13. Which AWS tool can provide best practice recommendations for performance, service limits, and cost optimization?
*  A. Amazon Inspector
*  B. Amazon CloudWatch
*  C. AWS Trusted Advisor
*  D. AWS Service Health Dashboard

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Trusted Advisor</strong></p>
 <p>AWS Trusted Advisor is an online resource to help you reduce cost, increase performance, and improve security by optimizing your AWS environment. Trusted Advisor provides real-time guidance to help you provision your resources following AWS best practices.</p>
 <p>How AWS Trusted Advisor works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q22-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/premiumsupport/technology/trusted-advisor/">https://aws.amazon.com/premiumsupport/technology/trusted-advisor/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Inspector</strong> - Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on your Amazon EC2 instances. Amazon Inspector automatically assesses applications for exposure, vulnerabilities, and deviations from best practices. Nevertheless, it does not provide best practice recommendations.</p>
 <p><strong>AWS Service Health Dashboard</strong> - AWS Service Health Dashboard publishes most up-to-the-minute information on the status and availability of all AWS services in tabular form for all Regions that AWS is present in. It does not provide best practice recommendations.</p>
 <p><strong>Amazon CloudWatch</strong> - Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers. CloudWatch provides data and actionable insights to monitor applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health. This is an excellent service for building Resilient systems. Think resource performance monitoring, events, and alerts; think CloudWatch. CloudWatch does not provide best practice recommendations.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/premiumsupport/technology/trusted-advisor/">https://aws.amazon.com/premiumsupport/technology/trusted-advisor/</a></p>
</div>

**Question 14**

14. A Cloud Practitioner would like to get operational insights of its resources to quickly identify any issues that might impact applications using those resources. Which AWS service can help with this task?
*  A. AWS Personal Health Dashboard
*  B. AWS Systems Manager
*  C. AWS Trusted Advisor
*  D. Amazon Inspector

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Systems Manager</strong></p>
 <p>AWS Systems Manager allows you to centralize operational data from multiple AWS services and automate tasks across your AWS resources. You can create logical groups of resources such as applications, different layers of an application stack, or production versus development environments.</p>
 <p>With Systems Manager, you can select a resource group and view its recent API activity, resource configuration changes, related notifications, operational alerts, software inventory, and patch compliance status. You can also take action on each resource group depending on your operational needs. Systems Manager provides a central place to view and manage your AWS resources, so you can have complete visibility and control over your operations.</p>
 <p>How AWS Systems Manager works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q58-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/systems-manager/">https://aws.amazon.com/systems-manager/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Inspector</strong> - Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. It is not used to get operational insights of AWS resources.</p>
 <p><strong>AWS Personal Health Dashboard</strong> - AWS Personal Health Dashboard provides alerts and remediation guidance when AWS is experiencing events that might affect you. It is not used to get operational insights of AWS resources.</p>
 <p><strong>AWS Trusted Advisor</strong> - AWS Trusted Advisor is an online resource to help you reduce cost, increase performance, and improve security by optimizing your AWS environment. Trusted Advisor provides real-time guidance to help you provision your resources following AWS best practices. It is not used to get operational insights of AWS resources.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/systems-manager/">https://aws.amazon.com/systems-manager/</a></p>
</div>

**Question 15**

15. A data science team would like to build Machine Learning models for its projects. Which AWS service can it use?
*  A. Amazon SageMaker
*  B. Amazon Connect
*  C. Amazon Comprehend
*  D. Amazon Polly

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon SageMaker</strong> - Amazon SageMaker is a fully-managed platform that enables developers and data scientists to quickly and easily build, train, and deploy machine learning models at any scale. Amazon SageMaker removes all the barriers that typically slow down developers who want to use machine learning.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Polly</strong> - You can use Amazon Polly to turn text into lifelike speech thereby allowing you to create applications that talk. Polly's Text-to-Speech (TTS) service uses advanced deep learning technologies to synthesize natural sounding human speech.</p>
 <p><strong>Amazon Comprehend</strong> - Amazon Comprehend is a natural language processing (NLP) service that uses machine learning to find meaning and insights in text. Natural Language Processing (NLP) is a way for computers to analyze, understand, and derive meaning from textual information in a smart and useful way. By utilizing NLP, you can extract important phrases, sentiment, syntax, key entities such as brand, date, location, person, etc., and the language of the text.</p>
 <p><strong>Amazon Connect</strong> -</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/sagemaker/">https://aws.amazon.com/sagemaker/</a></p>
</div>

**Question 16**

16. Which of the following statements is the MOST accurate when describing AWS Elastic Beanstalk?
*  A. It is a Platform as a Service (PaaS) which allows you to model and provision resources needed for an application
*  B. It is an Infrastructure as a Service (IaaS) which allows you to deploy and scale web applications and services
*  C. It is an Infrastructure as Code which allows you to model and provision resources needed for an application
*  D. It is a Platform as a Service (PaaS) which allows you to deploy and scale web applications and services

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>It is a Platform as a Service (PaaS) which allows you to deploy and scale web applications and services</strong></p>
 <p>AWS Elastic Beanstalk makes it even easier for developers to quickly deploy and manage applications in the AWS Cloud. Developers simply upload their application, and Elastic Beanstalk automatically handles the deployment details of capacity provisioning, load balancing, auto-scaling, and application health monitoring.</p>
 <p>It is a Platform as a Service as you only manage the applications and the data.</p>
 <p>Please review this overview of the types of Cloud Computing: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q53-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/types-of-cloud-computing/">https://aws.amazon.com/types-of-cloud-computing/</a></p>
 <p>Incorrect options:</p>
 <p><strong>It is an Infrastructure as Code which allows you to model and provision resources needed for an application</strong> - This is the definition of AWS CloudFormation. AWS CloudFormation gives developers and systems administrators an easy way to create and manage a collection of related AWS resources, provisioning and updating them in an orderly and predictable fashion. You can use the AWS CloudFormation sample templates or create your own templates to describe your AWS resources, and any associated dependencies or runtime parameters, required to run your application.</p>
 <p><strong>It is a Platform as a Service (PaaS) which allows you to model and provision resources needed for an application</strong> - AWS Elastic Beanstalk is a Plarform as a Service. However, the service that allows you to model and provision resources needed for an application is AWS CloudFormation.</p>
 <p><strong>It is an Infrastructure as a Service (IaaS) which allows you to deploy and scale web applications and services</strong> - AWS Elastic Beanstalk allows you to deploy and scale web applications and services, but it is not an Infrastructure as a Service. With AWS Elastic Beanstalk, you do not manage the runtime, the middleware, and the operating system.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/elasticbeanstalk/">https://aws.amazon.com/elasticbeanstalk/</a></p>
</div>

**Question 17**

17. A start-up would like to monitor its cost on the AWS Cloud and would like to choose an optimal Savings Plan. As a Cloud Practitioner, which AWS service would you use?
*  A. AWS Pricing Calculator
*  B. AWS Cost and Usage Reports
*  C. AWS Cost Explorer
*  D. AWS Budgets

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Cost Explorer</strong></p>
 <p>AWS Cost Explorer lets you explore your AWS costs and usage at both a high level and at a detailed level of analysis, and empowering you to dive deeper using several filtering dimensions (e.g., AWS Service, Region, Linked Account, etc.) AWS Cost Explorer also gives you access to a set of default reports to help you get started, while also allowing you to create custom reports from scratch.</p>
 <p>Customers can receive Savings Plan recommendations at the member (linked) account level in addition to the existing AWS organization-level recommendations in AWS Cost Explorer.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Cost and Usage Reports</strong> - The AWS Cost &amp; Usage Report is a single location for accessing comprehensive information about your AWS costs and usage. It does not provide Savings Plan recommendations.</p>
 <p><strong>AWS Pricing Calculator</strong> - AWS Pricing Calculator lets you explore AWS services, and create an estimate for the cost of your use cases on AWS. It does not provide Savings Plan recommendations.</p>
 <p><strong>AWS Budgets</strong> - AWS Budgets gives you the ability to set custom budgets that alert you when your costs or usage exceed (or are forecasted to exceed) your budgeted amount. You can also use AWS Budgets to set RI utilization or coverage targets and receive alerts when your utilization drops below the threshold you define. It does not provide Savings Plan recommendations.</p>
 <p>Exam Alert:</p>
 <p>Please review the differences between "AWS Cost and Usage Reports" and "AWS Cost Explorer". Think of "AWS Cost and Usage Reports" as a cost management tool providing the most detailed cost and usage data for your AWS account. It can provide reports that break down your costs by the hour into your S3 bucket. On the other hand, "AWS Cost Explorer" is more of a high-level cost management tool that helps you visualize the costs and usage associated with your AWS account.</p>
 <p>"AWS Cost Explorer" vs "AWS Cost and Usage Reports": <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q46-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/aws-cost-management/aws-cost-explorer/">https://aws.amazon.com/aws-cost-management/aws-cost-explorer/</a></p>
 <p>![AWS Cost and Usage Reportshttps://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt5-q46-i2.jpg?raw=true) via - <a href="https://aws.amazon.com/aws-cost-management/aws-cost-and-usage-reporting/">https://aws.amazon.com/aws-cost-management/aws-cost-and-usage-reporting/</a></p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/about-aws/whats-new/2020/03/aws-cost-explorer-now-offers-savings-plans-recommendations-for-member-linked-accounts/">https://aws.amazon.com/about-aws/whats-new/2020/03/aws-cost-explorer-now-offers-savings-plans-recommendations-for-member-linked-accounts/</a></p>
 <p><a href="https://docs.aws.amazon.com/cur/latest/userguide/what-is-cur.html">https://docs.aws.amazon.com/cur/latest/userguide/what-is-cur.html</a></p>
 <p><a href="https://aws.amazon.com/aws-cost-management/aws-cost-explorer/">https://aws.amazon.com/aws-cost-management/aws-cost-explorer/</a></p>
 <p><a href="https://aws.amazon.com/aws-cost-management/aws-cost-and-usage-reporting/">https://aws.amazon.com/aws-cost-management/aws-cost-and-usage-reporting/</a></p>
</div>

**Question 18**

18. Which of the following services are provided by Amazon Route 53? (Select TWO)
*  A. IP routing
*  B. Transfer acceleration
*  C. Health checks and monitoring
*  D. Domain registration
*  E. Load balancing

**Answer** C, D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Domain registration</strong></p>
 <p><strong>Health checks and monitoring</strong></p>
 <p>Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service. It is designed to give developers and businesses an extremely reliable and cost-effective way to route end users to Internet applications by translating names like www.example.com into the numeric IP addresses like 192.0.2.1 that computers use to connect to each other.</p>
 <p>Amazon Route 53 offers domain name registration services, where you can search for and register available domain names or transfer in existing domain names to be managed by Route 53.</p>
 <p>Amazon Route 53 can monitor the health and performance of your application as well as your web servers and other resources.</p>
 <p>Incorrect options:</p>
 <p><strong>IP routing</strong> - Despite its name, Amazon Route 53 does not offer IP routing. However, it can route traffic based on multiple criteria, such as endpoint health, geographic location, and latency, using routing policies.</p>
 <p><strong>Load balancing</strong> - It is a feature of Elastic Load Balancing (ELB) and not Amazon Route 53. Elastic Load Balancing automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, and Lambda functions. It can handle the varying load of your application traffic in a single Availability Zone or across multiple Availability Zones.</p>
 <p><strong>Transfer acceleration</strong> - Transfer acceleration is a feature of Amazon S3. Amazon S3 Transfer Acceleration can speed up content transfers to and from Amazon S3 by as much as 50-500% for long-distance transfer of larger objects.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/route53/">https://aws.amazon.com/route53/</a></p>
</div>

**Question 19**

19. A company needs to use a secure online data transfer tool/service that can automate the ongoing transfers from on-premises systems into AWS while providing support for incremental data backups.
*  A. AWS Snowmobile
*  B. AWS DataSync
*  C. AWS Storage Gateway
*  D. AWS Snowcone

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS DataSync</strong></p>
 <p>AWS DataSync is a secure online data transfer service that simplifies, automates, and accelerates copying terabytes of data to and from AWS storage services. Easily migrate or replicate large data sets without having to build custom solutions or oversee repetitive tasks. DataSync can copy data between Network File System (NFS) shares, or Server Message Block (SMB) shares, self-managed object storage, AWS Snowcone, Amazon Simple Storage Service (Amazon S3) buckets, Amazon Elastic File System (Amazon EFS) file systems, and Amazon FSx for Windows File Server file systems.</p>
 <p>You can use AWS DataSync for ongoing transfers from on-premises systems into or out of AWS for processing. DataSync can help speed up your critical hybrid cloud storage workflows in industries that need to move active files into AWS quickly. This includes machine learning in life sciences, video production in media and entertainment, and big data analytics in financial services. DataSync provides timely delivery to ensure dependent processes are not delayed. You can specify exclude filters, include filters, or both, to determine which files, folders or objects get transferred each time your task runs.</p>
 <p>AWS DataSync employs an AWS-designed transfer protocol—decoupled from the storage protocol—to accelerate data movement. The protocol performs optimizations on how, when, and what data is sent over the network. Network optimizations performed by DataSync include incremental transfers, in-line compression, and sparse file detection, as well as in-line data validation and encryption.</p>
 <p>Data Transfer between on-premises and AWS using DataSync: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q34-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/datasync/">https://aws.amazon.com/datasync/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS Storage Gateway</strong> - AWS Storage Gateway is a set of hybrid cloud services that give you on-premises access to virtually unlimited cloud storage. Customers use Storage Gateway to integrate AWS Cloud storage with existing on-site workloads so they can simplify storage management and reduce costs for key hybrid cloud storage use cases. These include moving backups to the cloud, using on-premises file shares backed by cloud storage, and providing low latency access to data in AWS for on-premises applications.</p>
 <p><strong>AWS Snowmobile</strong> - AWS Snowmobile is an Exabyte-scale data transfer service used to move extremely large amounts of data to AWS. You can transfer up to 100PB per Snowmobile, a 45-foot long ruggedized shipping container, pulled by a semi-trailer truck. Snowmobile makes it easy to move massive volumes of data to the cloud, including video libraries, image repositories, or even a complete data center migration.</p>
 <p><strong>AWS Snowcone</strong> - AWS Snowcone is the smallest member of the AWS Snow Family of edge computing, edge storage, and data transfer devices. Weighing in at 4.5 pounds (2.1 kg), AWS Snowcone is equipped with 8 terabytes of usable storage, while AWS Snowcone Solid State Drive (SSD) supports 14 terabytes of usable storage. Both referred to as Snowcone, the device is ruggedized, secure, and purpose-built for use outside of a traditional data center. Its small form factor makes it a perfect fit for tight spaces or where portability is a necessity and network connectivity is unreliable. You can use Snowcone in backpacks on first responders, or for IoT, vehicular, and drone use cases. You can execute compute applications at the edge, and you can ship the device with data to AWS for offline data transfer, or you can transfer data online with AWS DataSync from edge locations.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/datasync/">https://aws.amazon.com/datasync/</a></p>
 <p><a href="https://aws.amazon.com/datasync/features/">https://aws.amazon.com/datasync/features/</a></p>
</div>

**Question 20**

20. Which types of monitoring can be provided by Amazon CloudWatch? (Select TWO)
*  A. Application performance
*  B. Resource utilization
*  C. API access
*  D. Performance and availability of AWS services
*  E. Account management

**Answer** A, B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Application performance</strong></p>
 <p><strong>Resource utilization</strong></p>
 <p>Amazon CloudWatch is a monitoring service for AWS cloud resources and the applications you run on AWS. You can use Amazon CloudWatch to collect and track metrics, collect and monitor log files, and set alarms. Amazon CloudWatch can monitor AWS resources such as Amazon EC2 instances, Amazon DynamoDB tables, and Amazon RDS DB instances, as well as custom metrics generated by your applications and services, and any log files your applications generate.</p>
 <p>You can use Amazon CloudWatch to gain system-wide visibility into resource utilization, application performance, and operational health. You can use these insights to react and keep your application running smoothly.</p>
 <p>How Amazon CloudWatch works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q52-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/cloudwatch/">https://aws.amazon.com/cloudwatch/</a></p>
 <p>Incorrect options:</p>
 <p><strong>API access</strong> - Recording API calls is a feature of CloudTrail, not CloudWatch.</p>
 <p><strong>Performance and availability of AWS services</strong> - The Personal Health Dashboard gives you a personalized view into the performance and availability of the AWS services underlying your AWS resources, not CloudWatch.</p>
 <p><strong>Account management</strong> - Identity and Access Management (IAM) is usually used to manage accounts, not CloudWatch.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/cloudwatch/features/">https://aws.amazon.com/cloudwatch/features/</a></p>
 <p><a href="https://aws.amazon.com/cloudwatch/">https://aws.amazon.com/cloudwatch/</a></p>
</div>

**Question 21**

21. Which of the following AWS services can be used to generate, use, and manage encryption keys on the AWS Cloud?
*  A. AWS CloudHSM
*  B. AWS Secrets Manager
*  C. AWS GuardDuty
*  D. Amazon Inspector

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS CloudHSM</strong></p>
 <p>The AWS CloudHSM service helps you meet corporate, contractual, and regulatory compliance requirements for data security by using a dedicated Hardware Security Module (HSM) instances within the AWS cloud.</p>
 <p>CloudHSM allows you to securely generate, store, and manage cryptographic keys used for data encryption in a way that keys are accessible only by you.</p>
 <p>How AWS CloudHSM works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q45-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/cloudhsm/">https://aws.amazon.com/cloudhsm/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Inspector</strong> - Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. Amazon Inspector automatically assesses applications for exposure, vulnerabilities, and deviations from best practices. It cannot be used to generate, use, and manage encryption keys.</p>
 <p><strong>AWS GuardDuty</strong> - Amazon GuardDuty is a threat detection service that continuously monitors for malicious or unauthorized behavior to help you protect your AWS accounts and workloads. It cannot be used to generate, use, and manage encryption keys.</p>
 <p><strong>AWS Secrets Manager</strong> - AWS Secrets Manager helps you protect secrets needed to access your applications, services, and IT resources. The service enables you to easily rotate, manage, and retrieve database credentials, API keys, and other secrets throughout their lifecycle. It is integrated with AWS CloudHSM to generate, use, and manage encryption keys.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/cloudhsm/">https://aws.amazon.com/cloudhsm/</a></p>
</div>

**Question 22**

22. A growing start-up has trouble identifying and protecting sensitive data at scale. Which AWS fully managed service can assist with this task?
*  A. AWS Secrets Manager
*  B. AWS Artifact
*  C. AWS KMS
*  D. Amazon Macie

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon Macie</strong></p>
 <p>Amazon Macie is a fully managed data security and data privacy service that uses machine learning and pattern matching to discover and protect your sensitive data in AWS.</p>
 <p>Amazon Macie uses machine learning and pattern matching to cost-efficiently discover sensitive data at scale. Macie automatically detects a large and growing list of sensitive data types, including personally identifiable information (PII) such as names, addresses, and credit card numbers. It also gives you constant visibility of the data security and data privacy of your data stored in Amazon S3.</p>
 <p>How Amazon Macie works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q40-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/macie/">https://aws.amazon.com/macie/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS Artifact</strong> - AWS Artifact is your go-to, central resource for compliance-related information that matters to you. It provides on-demand access to AWS’ security and compliance reports and select online agreements. It is not used to discover and protect sensitive data in AWS.</p>
 <p><strong>AWS Secrets Manager</strong> - AWS Secrets Manager helps you protect secrets needed to access your applications, services, and IT resources. The service enables you to easily rotate, manage, and retrieve database credentials, API keys, and other secrets throughout their lifecycle. It is not used to discover and protect sensitive data in AWS.</p>
 <p><strong>AWS KMS</strong> - AWS Key Management Service (KMS) makes it easy for you to create and manage keys and control the use of encryption across a wide range of AWS services and in your applications. It is not used to discover and protect sensitive data in AWS.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/macie/">https://aws.amazon.com/macie/</a></p>
</div>

**Question 23**

23. According to the Well-Architected Framework, which of the following action is recommended in the Security pillar?
*  A. Use AWS CloudFormation to automate security best practices
*  B. Use Amazon CloudWatch to measure overall efficiency
*  C. Use AWS KMS to encrypt data
*  D. Use AWS Cost Explorer to view and track your usage in detail

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Use AWS KMS to encrypt data</strong></p>
 <p>The Security pillar includes the ability to protect information, systems, and assets while delivering business value through risk assessments and mitigation strategies.</p>
 <p>Encrypting data is part of the design principle "Protect data in transit and at rest": Classify your data into sensitivity levels and use mechanisms, such as encryption, tokenization, and access control where appropriate.</p>
 <p>AWS Key Management Service (AWS KMS) makes it easy for you to create and control keys used for encryption. It is a key service of the Security pillar.</p>
 <p>The AWS Well-Architected Framework helps you understand the pros and cons of decisions you make while building systems on AWS. By using the Framework you will learn architectural best practices for designing and operating reliable, secure, efficient, and cost-effective systems in the cloud. It provides a way for you to consistently measure your architectures against best practices and identify areas for improvement.</p>
 <p>The AWS Well-Architected Framework is based on six pillars — Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization and Sustainability.</p>
 <p>Overview of the six pillars of the Well-Architected Framework:</p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q38-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/architecture/well-architected/">https://aws.amazon.com/architecture/well-architected/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Use AWS Cost Explorer to view and track your usage in detail</strong> - AWS Cost Explorer has an easy-to-use interface that lets you visualize, understand, and manage your AWS costs and usage over time. Using Cost Explorer to view and track your usage in detail relates more to the Cost Optimization pillar.</p>
 <p><strong>Use Amazon CloudWatch to measure overall efficiency</strong> - Amazon CloudWatch is a monitoring and management service built for developers, system operators, site reliability engineers (SRE), and IT managers. Using Amazon CloudWatch to measure overall efficiency relates more to the Reliability pillar.</p>
 <p><strong>Use AWS CloudFormation to automate security best practices</strong> - AWS CloudFormation provides a common language for you to model and provision AWS and third-party application resources in your cloud environment. It is not used to automate security best practices. If you want to automate security best practices, you should use Amazon Inspector.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/architecture/well-architected/">https://aws.amazon.com/architecture/well-architected/</a></p>
</div>

**Question 24**

24. According to the Well-Architected Framework, which of the following statements are recommendations in the Operational Excellence pillar? (Select two)
*  A. Use serverless architectures
*  B. Enable traceability
*  C. Anticipate failure
*  D. Automatically recover from failure
*  E. Make frequent, small, reversible changes

**Answer** C, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Anticipate failure</strong></p>
 <p><strong>Make frequent, small, reversible changes</strong></p>
 <p>The Operational Excellence pillar includes the ability to run and monitor systems to deliver business value and to continually improve supporting processes and procedures.</p>
 <p>Perform “pre-mortem” exercises to identify potential sources of failure so that they can be removed or mitigated. Test your failure scenarios and validate your understanding of their impact. Test your response procedures to ensure that they are effective, and that teams are familiar with their execution. Set up regular game days to test workloads and team responses to simulated events.</p>
 <p>Design workloads to allow components to be updated regularly. Make changes in small increments that can be reversed if they fail (without affecting customers when possible).</p>
 <p>The AWS Well-Architected Framework helps you understand the pros and cons of decisions you make while building systems on AWS. By using the Framework you will learn architectural best practices for designing and operating reliable, secure, efficient, and cost-effective systems in the cloud. It provides a way for you to consistently measure your architectures against best practices and identify areas for improvement.</p>
 <p>The AWS Well-Architected Framework is based on six pillars — Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization and Sustainability.</p>
 <p>Overview of the six pillars of the Well-Architected Framework:</p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q19-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/architecture/well-architected/">https://aws.amazon.com/architecture/well-architected/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Enable traceability</strong> - Monitor, alert, and audit actions and changes to your environment in real-time. Integrate logs and metrics with systems to automatically respond and take action. It is a design principle of the Security pillar.</p>
 <p><strong>Automatically recover from failure</strong> - By monitoring a system for key performance indicators (KPIs), you can trigger automation when a threshold is breached. This allows for automatic notification and tracking of failures, and for automated recovery processes that work around or repair the failure. With more sophisticated automation, it's possible to anticipate and remediate failures before they occur. It is a design principle of the Reliability pillar.</p>
 <p><strong>Use serverless architectures</strong> - In the cloud, serverless architectures remove the need for you to run and maintain servers to carry out traditional compute activities. For example, storage services can act as static websites, removing the need for web servers, and event services can host your code for you. This not only removes the operational burden of managing these servers, but also can lower transactional costs because these managed services operate at cloud scale. It is a design principle of the Performance Efficiency pillar.</p>
 <p>Reference:</p>
 <p><a href="https://wa.aws.amazon.com/index.en.html">https://wa.aws.amazon.com/index.en.html</a></p>
</div>

**Question 25**

25. Which of the following billing timeframes is applied when running a Windows EC2 on-demand instance?
*  A. Pay per day
*  B. Pay per hour
*  C. Pay per second
*  D. Pay per minute

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Pay per second</strong></p>
 <p>With On-Demand instances you only pay for EC2 instances you use. The use of On-Demand instances frees you from the costs and complexities of planning, purchasing, and maintaining hardware and transforms what are commonly large fixed costs into much smaller variable costs.</p>
 <p>When running a Windows EC2 on-demand instance, pay per second pricing is applied.</p>
 <p>Incorrect options:</p>
 <p><strong>Pay per hour</strong> - When running a Windows EC2 on-demand instance, pay per second pricing is applied. Windows based EC2 instances used to follow pay-per-hour pricing earlier.</p>
 <p><strong>Pay per minute</strong> - Pay per minute pricing is not available for Windows EC2 on-demand instances, or any other type of on-demand EC2 instance.</p>
 <p><strong>Pay per day</strong> - Pay per day pricing is not available for Windows EC2 on-demand instances, or any other type of on-demand EC2 instance.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/ec2/pricing/">https://aws.amazon.com/ec2/pricing/</a></p>
</div>

**Question 26**

26. Which of the following IAM Security Tools allows you to review permissions granted to a user?
*  A. IAM policies
*  B. IAM credentials report
*  C. Multi-Factor Authentication (MFA)
*  D. IAM access advisor

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>IAM access advisor</strong></p>
 <p>Access advisor shows the service permissions granted to a user and when those services were last accessed. You can use this information to revise your policies. To summarize, you can identify unnecessary permissions so that you can revise your IAM policies accordingly.</p>
 <p>Incorrect options:</p>
 <p><strong>IAM credentials report</strong> - You can generate and download a credential report that lists all users in your account and the status of their various credentials, including passwords, access keys, and MFA devices. It is not used to review permissions granted to a user.</p>
 <p><strong>IAM policies</strong> - IAM policies define permissions for an action regardless of the method that you use to perform the operation.</p>
 <p><strong>Multi-Factor Authentication (MFA)</strong> - AWS Multi-Factor Authentication (MFA) is a simple best practice that adds an extra layer of protection on top of your user name and password. With MFA enabled, when a user signs in to an AWS Management Console, they will be prompted for their user name and password (the first factor—what they know), as well as for an authentication code from their AWS MFA device (the second factor—what they have). Taken together, these multiple factors provide increased security for your AWS account settings and resources. It cannot be used to review permissions granted.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/about-aws/whats-new/2019/06/now-use-iam-access-advisor-with-aws-organizations-to-set-permission-guardrails-confidently/">https://aws.amazon.com/about-aws/whats-new/2019/06/now-use-iam-access-advisor-with-aws-organizations-to-set-permission-guardrails-confidently/</a></p>
</div>

**Question 27**

27. Which AWS service can be used to send, store, and receive messages between software components at any volume to decouple application tiers?
*  A. AWS Elastic Beanstalk
*  B. Amazon SNS
*  C. AWS Organizations
*  D. Amazon SQS

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon SQS</strong></p>
 <p>Amazon Simple Queue Service (Amazon SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications. SQS eliminates the complexity and overhead associated with managing and operating message-oriented middleware, and empowers developers to focus on differentiating work.</p>
 <p>Using SQS, you can send, store, and receive messages between software components at any volume, without losing messages or requiring other services to be available.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon SNS</strong> - Amazon Simple Notification Service (Amazon SNS) is a highly available, durable, secure, fully managed pub/sub messaging service that enables you to decouple microservices, distributed systems, and serverless applications.</p>
 <p>Please review this reference architecture for building a decoupled order processing system using SNS and SQS: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/OrderDispatcher2-1024x718.png?raw=true"> via - <a href="https://aws.amazon.com/blogs/compute/building-loosely-coupled-scalable-c-applications-with-amazon-sqs-and-amazon-sns/">https://aws.amazon.com/blogs/compute/building-loosely-coupled-scalable-c-applications-with-amazon-sqs-and-amazon-sns/</a></p>
 <p><strong>AWS Elastic Beanstalk</strong> - AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling web applications and services. You can simply upload your code, and AWS Elastic Beanstalk automatically handles the deployment, from capacity provisioning, load balancing, and auto-scaling to application health monitoring. It is not used to send, store, and receive message between software components.</p>
 <p><strong>AWS Organizations</strong> - AWS Organizations offers policy-based management for multiple AWS accounts. With Organizations, you can create groups of accounts, automate account creation, apply and manage policies for those groups. Organizations enables you to centrally manage policies across multiple accounts, without requiring custom scripts and manual processes. It is not used to send, store, and receive message between software components.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/sqs/">https://aws.amazon.com/sqs/</a></p>
</div>

**Question 28**

28. A company would like to move its infrastructure to AWS Cloud. Which of the following should be included in the Total Cost of Ownership (TCO) estimate? (Select TWO)
*  A. Number of end-users
*  B. Electronic equipment at office
*  C. Server administration
*  D. Power/Cooling
*  E. Application advertising

**Answer** C, D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Server administration</strong></p>
 <p><strong>Power/Cooling</strong></p>
 <p>AWS Pricing Calculator lets you explore AWS services and create an estimate for the cost of your use cases on AWS. You can model your solutions before building them, explore the price points and calculations behind your estimate, and find the available instance types and contract terms that meet your needs. This enables you to make informed decisions about using AWS. You can plan your AWS costs and usage or price out setting up a new set of instances and services. AWS Pricing Calculator can be accessed at <a href="https://calculator.aws/#/">https://calculator.aws/#/</a>.</p>
 <p>AWS Pricing Calculator compares the cost of your applications in an on-premises or traditional hosting environment to AWS: server, storage, network, IT labor. Therefore, you need to include every element relevant to these points of comparison.</p>
 <p>Server administration is included in the IT labor costs.</p>
 <p>Power/Cooling are included in the server, storage and network cost.</p>
 <p>Incorrect options:</p>
 <p><strong>Application advertising</strong> - The application advertising is not relevant for a Total Cost of Ownership (TCO) estimate.</p>
 <p><strong>Number of end-users</strong> - The number of end-users is not relevant for a Total Cost of Ownership (TCO) estimate.</p>
 <p><strong>Electronic equipment at office</strong> - The electronic equipment at the office is not relevant for a Total Cost of Ownership (TCO) estimate.</p>
 <p>References:</p>
 <p><a href="https://calculator.aws/#/">https://calculator.aws/#/</a></p>
 <p><a href="https://aws.amazon.com/blogs/aws/new-cloud-tco-comparison-calculator-for-web-applications/">https://aws.amazon.com/blogs/aws/new-cloud-tco-comparison-calculator-for-web-applications/</a></p>
</div>

**Question 29**

29. Which Amazon EC2 Auto Scaling feature can help with fault tolerance?
*  A. Having the right amount of computing capacity
*  B. Replacing unhealthy EC2 instances
*  C. Distributing load to EC2 instances
*  D. Lower cost by adjusting the number of EC2 instances

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Replacing unhealthy EC2 instances</strong></p>
 <p>Amazon EC2 Auto Scaling helps you maintain application availability and allows you to automatically add or remove EC2 instances according to conditions you define. You can use the fleet management features of EC2 Auto Scaling to maintain the health and availability of your fleet. You can also use the dynamic and predictive scaling features of EC2 Auto Scaling to add or remove EC2 instances.</p>
 <p>Amazon EC2 Auto Scaling can detect when an instance is unhealthy, terminate it, and replace it with a new one.</p>
 <p>Incorrect options:</p>
 <p><strong>Lower cost by adjusting the number of EC2 instances</strong> - Amazon EC2 Auto Scaling adds instances only when needed, and can scale across purchase options to optimize performance and cost. However, this will not help with fault tolerance.</p>
 <p><strong>Distributing load to EC2 instances</strong> - Even though this helps with fault tolerance and is often used with Amazon EC2 Auto Scaling, it is a feature of Elastic Load Balancing (ELB) and not Amazon EC2 Auto Scaling. Elastic Load Balancing automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, and Lambda functions. It can handle the varying load of your application traffic in a single Availability Zone or across multiple Availability Zones.</p>
 <p><strong>Having the right amount of computing capacity</strong> - Amazon EC2 Auto Scaling ensures that your application always has the right amount of compute, so your application can handle the workload.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/ec2/autoscaling/">https://aws.amazon.com/ec2/autoscaling/</a></p>
</div>

**Question 30**

30. A Cloud Practitioner would like to deploy identical resources across all regions and accounts using templates while estimating costs. Which AWS service can assist with this task?
*  A. AWS CloudFormation
*  B. Amazon LightSail
*  C. AWS CodeDeploy
*  D. AWS Directory Service

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS CloudFormation</strong></p>
 <p>AWS CloudFormation gives developers and systems administrators an easy way to create and manage a collection of related AWS resources, provisioning and updating them in an orderly and predictable fashion.</p>
 <p>You can use the AWS CloudFormation sample templates or create your own templates to describe your AWS resources, and any associated dependencies or runtime parameters, required to run your application. This provides a single source of truth for all your resources and helps you to standardize infrastructure components used across your organization, enabling configuration compliance and faster troubleshooting.</p>
 <p>CloudFormation templates allow you to estimate the cost of your resources.</p>
 <p>How AWS CloudFormation works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q60-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/cloudformation/">https://aws.amazon.com/cloudformation/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS Directory Service</strong> - AWS Directory Service for Microsoft Active Directory, also known as AWS Managed Microsoft AD, enables your directory-aware workloads and AWS resources to use managed Active Directory in the AWS Cloud. It is not used to deploy resources.</p>
 <p><strong>Amazon LightSail</strong> - Amazon Lightsail is designed to be the easiest way to launch and manage a virtual private server with AWS. It is not best suited when deploying more complex resources, while CloudFormation can.</p>
 <p><strong>AWS CodeDeploy</strong> - AWS CodeDeploy is a service that automates code deployments to any instance, including EC2 instances and instances running on-premises. Unlike CloudFormation, it does not deal with infrastructure configuration and orchestration.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/cloudformation/">https://aws.amazon.com/cloudformation/</a></p>
</div>

**Question 31**

31. A company would like to create a private, high bandwidth network connection between its on-premises data centers and AWS Cloud. As a Cloud Practitioner, which of the following options would you recommend?
*  A. VPC Endpoints
*  B. Site-to-Site VPN
*  C. Direct Connect
*  D. VPC Peering

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Direct Connect</strong></p>
 <p>AWS Direct Connect is a cloud service solution that makes it easy to establish a dedicated network connection from your premises to AWS. Using AWS Direct Connect, you can establish private connectivity between AWS and your datacenter, office, or colocation environment, which in many cases can reduce your network costs, increase bandwidth throughput, and provide a more consistent network experience than Internet-based connections.</p>
 <p>How AWS Direct Connect works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q21-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/directconnect/">https://aws.amazon.com/directconnect/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Site-to-Site VPN</strong> - By default, instances that you launch into an Amazon VPC can't communicate with your own (remote) network. You can enable access to your remote network from your VPC by creating an AWS Site-to-Site VPN (Site-to-Site VPN) connection, and configuring routing to pass traffic through the connection. It uses the public internet and is therefore not suited for this use case.</p>
 <p><strong>VPC Endpoints</strong> - A VPC endpoint enables you to privately connect your VPC to supported AWS services and VPC endpoint services powered by AWS PrivateLink without requiring an internet gateway, NAT device, VPN connection, or AWS Direct Connect connection. It does not connect your on-premises data centers and AWS Cloud.</p>
 <p><strong>VPC Peering</strong> - A VPC peering connection is a networking connection between two VPCs that enables you to route traffic between them using private IPv4 addresses or IPv6 addresses. It is used to connect VPCs together, and not on-premises data centers and AWS Cloud.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/directconnect/">https://aws.amazon.com/directconnect/</a></p>
</div>

**Question 32**

32. Which AWS tool/service will help you define your cloud infrastructure using popular programming languages such as Python and JavaScript?
*  A. AWS Cloud Development Kit (CDK)
*  B. AWS CloudFormation
*  C. AWS CodeBuild
*  D. AWS Elastic Beanstalk

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Cloud Development Kit (CDK)</strong> - The AWS Cloud Development Kit (AWS CDK) is an open-source software development framework to define your cloud application resources using familiar programming languages.</p>
 <p>AWS CDK uses the familiarity and expressive power of programming languages for modeling your applications. It provides you with high-level components called constructs that preconfigure cloud resources with proven defaults, so you can build cloud applications without needing to be an expert. AWS CDK provisions your resources in a safe, repeatable manner through AWS CloudFormation. It also enables you to compose and share your own custom constructs that incorporate your organization's requirements, helping you start new projects faster.</p>
 <p>In short, you use the AWS CDK framework to author AWS CDK projects which are executed to generate CloudFormation templates.</p>
 <p>How CDK works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q50-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/cdk/">https://aws.amazon.com/cdk/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS Elastic Beanstalk</strong> - AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling web applications and services developed with Java, .NET, PHP, Node.js, Python etc. You can simply upload your code in a programming language of your choice and Elastic Beanstalk automatically handles the deployment, from capacity provisioning, load balancing, auto-scaling to application health monitoring.</p>
 <p><strong>AWS CloudFormation</strong> - AWS CloudFormation is a service that gives developers and businesses an easy way to create a collection of related AWS and third-party resources, and provision and manage them in an orderly and predictable fashion. AWS CloudFormation is designed to allow resource lifecycles to be managed repeatably, predictable, and safely, while allowing for automatic rollbacks, automated state management, and management of resources across accounts and regions. AWS CDK helps code the same in higher-level languages and converts them into CloudFormation templates.</p>
 <p><strong>AWS CodeBuild</strong> - AWS CodeBuild is a fully managed continuous integration service that compiles source code, runs tests, and produces software packages that are ready to deploy. With CodeBuild, you don’t need to provision, manage, and scale your own build servers. CodeBuild scales continuously and processes multiple builds concurrently, so your builds are not left waiting in a queue.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/cdk/">https://aws.amazon.com/cdk/</a></p>
</div>

**Question 33**

33. A research lab needs to be notified in case of a configuration change for security and compliance reasons. Which AWS service can assist with this task?
*  A. Amazon Inspector
*  B. AWS Secrets Manager
*  C. AWS Config
*  D. AWS Trusted Advisor

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Config</strong></p>
 <p>AWS Config is a service that enables you to assess, audit, and evaluate the configurations of your AWS resources. Config continuously monitors and records your AWS resource configurations and allows you to automate the evaluation of recorded configurations against desired configurations. With Config, you can review changes in configurations and relationships between AWS resources, dive into detailed resource configuration histories, and determine your overall compliance against the configurations specified in your internal guidelines. This enables you to simplify compliance auditing, security analysis, change management, and operational troubleshooting.</p>
 <p>How AWS Config works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q33-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/config/">https://aws.amazon.com/config/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Inspector</strong> - Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on your Amazon EC2 instances. Amazon Inspector automatically assesses applications for exposure, vulnerabilities, and deviations from best practices. It cannot notify configuration changes.</p>
 <p><strong>AWS Trusted Advisor</strong> - AWS Trusted Advisor is an online resource to help you reduce cost, increase performance, and improve security by optimizing your AWS environment. Trusted Advisor provides real-time guidance to help you provision your resources following AWS best practices. It cannot notify configuration changes.</p>
 <p><strong>AWS Secrets Manager</strong> - AWS Secrets Manager helps you protect secrets needed to access your applications, services, and IT resources. The service enables you to easily rotate, manage, and retrieve database credentials, API keys, and other secrets throughout their lifecycle. It cannot notify configuration changes.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/config/">https://aws.amazon.com/config/</a></p>
</div>

**Question 34**

34. The development team at a company manages 300 microservices and it is now trying to automate the code reviews to improve the code quality. Which tool/service is the right fit for this requirement?
*  A. Amazon CodeGuru
*  B. AWS Trusted Advisor
*  C. AWS X-Ray
*  D. AWS CodeBuild

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon CodeGuru</strong> - Amazon CodeGuru is a developer tool that provides intelligent recommendations to improve code quality and identify an application’s most expensive lines of code. Integrate CodeGuru into your existing software development workflow to automate code reviews during application development, continuously monitor application performance in production, provide recommendations and visual clues for improving code quality and application performance, and reduce overall cost.</p>
 <p>CodeGuru Reviewer uses machine learning and automated reasoning to identify critical issues, security vulnerabilities, and hard-to-find bugs during application development and provides recommendations to improve code quality.</p>
 <p>CodeGuru Profiler pinpoints an application’s most expensive lines of code by helping developers understand the runtime behavior of their applications, identify and remove code inefficiencies, improve performance, and significantly decrease compute costs.</p>
 <p>How CodeGuru works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/Product-Page-Diagram_CodeGuru.4d70717197b2bbd7bb11c44e8c9c351dbc12f821.png?raw=true"> via - <a href="https://aws.amazon.com/codeguru/">https://aws.amazon.com/codeguru/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS X-Ray</strong> - AWS X-Ray helps developers analyze and debug production, distributed applications, such as those built using a microservices architecture. With X-Ray, you can understand how your application and its underlying services are performing to identify and troubleshoot the root cause of performance issues and errors. X-Ray provides an end-to-end view of requests as they travel through your application, and shows a map of your application’s underlying components.</p>
 <p><strong>AWS CodeBuild</strong> - AWS CodeBuild is a fully managed continuous integration service that compiles source code, runs tests, and produces software packages that are ready to deploy. With CodeBuild, you don’t need to provision, manage, and scale your own build servers. CodeBuild scales continuously and processes multiple builds concurrently, so your builds are not left waiting in a queue.</p>
 <p><strong>AWS Trusted Advisor</strong> - AWS Trusted Advisors provides recommendations that help you follow AWS best practices. Trusted Advisor evaluates your account by using checks. These checks identify ways to optimize your AWS infrastructure, improve security and performance, reduce costs, and monitor service quotas.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/codeguru/">https://aws.amazon.com/codeguru/</a></p>
</div>

**Question 35**

35. Which of the following options are the benefits of using AWS Elastic Load Balancing (ELB)? (Select TWO)
*  A. Agility
*  B. High availability
*  C. Fault tolerance
*  D. Less costly
*  E. Storage

**Answer** B, C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>High availability</strong></p>
 <p><strong>Fault tolerance</strong></p>
 <p>Elastic Load Balancing (ELB) automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, and IP addresses. It can handle the varying load of your application traffic in a single Availability Zone or across multiple Availability Zones.</p>
 <p>Elastic Load Balancing offers three types of load balancers that all feature the high availability, automatic scaling, and robust security necessary to make your applications fault-tolerant: Application Load Balancer (best suited for HTTP and HTTPS traffic), Network Load Balancer (best suited for TCP traffic), and Classic Load Balancer.</p>
 <p>Incorrect options:</p>
 <p><strong>Agility</strong> - Agility refers to new IT resources being only a click away, which means that you reduce the time to make those resources available to your developers from weeks to just minutes.&nbsp;AWS Elastic Load Balancing does not help with agility.</p>
 <p><strong>Less costly</strong> - AWS Elastic Load Balancing does not help with reducing costs.</p>
 <p><strong>Storage</strong> - AWS Elastic Load Balancing does not offer storage benefits. It is not a storage-related service.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/elasticloadbalancing/">https://aws.amazon.com/elasticloadbalancing/</a></p>
</div>

**Question 36**

36. Which service/tool will you use to create and provide trusted users with temporary security credentials that can control access to your AWS resources?
*  A. AWS Single Sign-On (SSO)
*  B. AWS Web Application Firewall (AWS WAF)
*  C. AWS Security Token Service (AWS STS)
*  D. Amazon Cognito

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Security Token Service (AWS STS)</strong> - AWS Security Token Service (AWS STS) is a web service that enables you to request temporary, limited-privilege credentials for AWS Identity and Access Management (IAM) users or for users that you authenticate (federated users).</p>
 <p>You can use the AWS Security Token Service (AWS STS) to create and provide trusted users with temporary security credentials that can control access to your AWS resources. Temporary security credentials work almost identically to the long-term access key credentials that your IAM users can use, with the following differences:</p>
 <ol>
  <li><p>Temporary security credentials are short-term, as the name implies. They can be configured to last for anywhere from a few minutes to several hours. After the credentials expire, AWS no longer recognizes them or allows any kind of access from API requests made with them.</p></li>
  <li><p>Temporary security credentials are not stored with the user but are generated dynamically and provided to the user when requested. When (or even before) the temporary security credentials expire, the user can request new credentials, as long as the user requesting them still has permissions to do so.</p></li>
 </ol>
 <p>Temporary security credentials are generated by AWS STS. By default, AWS STS is a global service with a single endpoint at https://sts.amazonaws.com. However, you can also choose to make AWS STS API calls to endpoints in any other supported Region.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Cognito</strong> - Amazon Cognito is a higher level of abstraction than STS. Amazon Cognito supports the same identity providers as AWS STS, and also supports unauthenticated (guest) access, and lets you migrate user data when a user signs in. Amazon Cognito also provides API operations for synchronizing user data so that it is preserved as users move between devices. Cognito helps create the user database, which is not possible with STS.</p>
 <p><strong>AWS Single Sign-On (SSO)</strong> - AWS Single Sign-On (SSO) makes it easy to centrally manage access to multiple AWS accounts and business applications and provide users with single sign-on access to all their assigned accounts and applications from one place. With AWS SSO, you can easily manage access and user permissions to all of your accounts in AWS Organizations centrally. AWS SSO configures and maintains all the necessary permissions for your accounts automatically, without requiring any additional setup in the individual accounts.</p>
 <p><strong>AWS Web Application Firewall (AWS WAF)</strong> - AWS WAF is a web application firewall that helps protect your web applications or APIs against common web exploits and bots that may affect availability, compromise security, or consume excessive resources. AWS WAF gives you control over how traffic reaches your applications by enabling you to create security rules that control bot traffic and block common attack patterns, such as SQL injection or cross-site scripting.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_temp.html">https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_temp.html</a></p>
</div>

**Question 37**

37. According to the Shared Responsibility Model, which of the following are responsibilities of AWS? (Select two)
*  A. Encrypting application data
*  B. Network operability
*  C. Configuring IAM Roles
*  D. Data center security
*  E. Installing security patches of the guest operating system (OS)

**Answer** B, D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Data center security</strong></p>
 <p><strong>Network operability</strong></p>
 <p>AWS responsibility “Security OF the Cloud” - AWS is responsible for protecting the infrastructure that runs all of the services offered in the AWS Cloud. This infrastructure is composed of the hardware, software, networking, and facilities that run AWS Cloud services.</p>
 <p>Exam Alert:</p>
 <p>Please review the Shared Responsibility Model in detail as you can expect multiple questions on the shared responsibility model in the exam: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/Shared_Responsibility_Model_V2.59d1eccec334b366627e9295b304202faf7b899b.jpg?raw=true"> via - <a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Installing security patches of the guest operating system (OS)</strong> - The customers are responsible for patching their guest OS.</p>
 <p>Please review the IT controls under the Shared Responsibility Model: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q8-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
 <p><strong>Encrypting application data</strong> - The customers are responsible for encrypting application data.</p>
 <p><strong>Configuring IAM Roles</strong> - The customers are responsible for configuring IAM Roles.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
</div>

**Question 38**

38. Which of the following options is NOT a feature of Amazon Inspector?
*  A. Inspect running operating systems (OS) against known vulnerabilities
*  B. Analyze against unintended network accessibility
*  C. Track configuration changes
*  D. Automate security assessments

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Track configuration changes</strong></p>
 <p>Tracking configuration changes is a feature of AWS Config.</p>
 <p>AWS Config is a service that enables you to assess, audit, and evaluate the configurations of your AWS resources. Config continuously monitors and records your AWS resource configurations and allows you to automate the evaluation of recorded configurations against desired configurations.</p>
 <p>How AWS Config works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q59-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/config/">https://aws.amazon.com/config/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Automate security assessments</strong></p>
 <p><strong>Analyze against unintended network accessibility</strong></p>
 <p><strong>Inspect running operating systems (OS) against known vulnerabilities</strong></p>
 <p>These options are all features of Amazon Inspector.</p>
 <p>Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. Amazon Inspector automatically assesses applications for exposure, vulnerabilities, and deviations from best practices.</p>
 <p>Amazon Inspector security assessments help you check for unintended network accessibility of your Amazon EC2 instances and for vulnerabilities on those EC2 instances.</p>
 <p>Amazon Inspector also offers predefined software called an agent that you can optionally install in the operating system of the EC2 instances that you want to assess. The agent monitors the behavior of the EC2 instances, including network, file system, and process activity. It also collects a wide set of behavior and configuration data (telemetry).</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/config/">https://aws.amazon.com/config/</a></p>
 <p><a href="https://aws.amazon.com/inspector/">https://aws.amazon.com/inspector/</a></p>
</div>

**Question 39**

39. Which of the following statements is an AWS best practice when architecting for the Cloud?
*  A. Servers, not services
*  B. Close coupling
*  C. Security comes last
*  D. Automation

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Automation</strong></p>
 <p>Automation should be implemented to improve both your system's stability and the efficiency of your organization. There are many services to automate application architecture (AWS Elastic Beanstalk, Auto Scaling, AWS Lambda, etc.) to ensure more resiliency, scalability, and performance.</p>
 <p>Incorrect options:</p>
 <p><strong>Servers, not services</strong> - The correct best practice is: "Services, not servers". AWS recommends to develop, manage, and operate applications, especially at scale, using the broad set of compute, storage, database, analytics, applications, and deployment services offered by AWS to move faster and lower IT costs.</p>
 <p><strong>Close coupling</strong> - The correct best practice is: "Loose coupling". AWS recommends that, as application complexity increases, IT systems should be designed in a way that reduces interdependencies. Therefore, a change or a failure in one component should not cascade to other components.</p>
 <p><strong>Security comes last</strong> - AWS allows you to improve your security in many, more simple ways. Therefore, you should take advantage of this and implement a high level of security.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/architecture/well-architected/">https://aws.amazon.com/architecture/well-architected/</a></p>
</div>

**Question 40**

40. Adding more CPU/RAM to an Amazon EC2 instance represents which of the following?
*  A. Horizontal scaling
*  B. Managing increasing volumes of data
*  C. Vertical scaling
*  D. Loose coupling

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Vertical scaling</strong></p>
 <p>A "vertically scalable" system, which is constrained to running its processes on only one computer; in such systems, the only way to increase performance is to add more resources into one computer in the form of faster (or more) CPUs, memory or storage.</p>
 <p>Incorrect options:</p>
 <p><strong>Horizontal scaling</strong> - A "horizontally scalable" system is one that can increase capacity by adding more computers to the system.</p>
 <p><strong>Managing increasing volumes of data</strong> - Traditional data storage and analytics tools can no longer provide the agility and flexibility required to deliver relevant business insights. That’s why many organizations are shifting to a data lake architecture. A data lake is an architectural approach that allows you to store massive amounts of data in a central location so that it's readily available to be categorized, processed, analyzed, and consumed by diverse groups within your organization.</p>
 <p><strong>Loose coupling</strong> - As application complexity increases, a desirable attribute of an IT system is that it can be broken into smaller, loosely coupled components. This means that IT systems should be designed in a way that reduces interdependencies—a change or a failure in one component should not cascade to other components.</p>
 <p>Reference:</p>
 <p><a href="https://wa.aws.amazon.com/wat.concept.horizontal-scaling.en.html">https://wa.aws.amazon.com/wat.concept.horizontal-scaling.en.html</a></p>
</div>

**Question 41**

41. Which of the following statements is INCORRECT regarding EBS Volumes?
*  A. EBS Volumes are bound to a specific Availability Zone (AZ)
*  B. EBS Volumes can persist data after their termination
*  C. EBS Volumes can be bound to several Availability Zones (AZs)
*  D. EBS Volumes can be mounted to one instance at a time

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>EBS Volumes can be bound to several Availability Zones (AZs)</strong></p>
 <p>An Amazon EBS volume is a durable, block-level storage device that you can attach to your instances. After you attach a volume to an instance, you can use it as you would use a physical hard drive.</p>
 <p>When using EBS Volumes, the volume and the instance must be in the same Availability Zone.</p>
 <p>Incorrect options:</p>
 <p><strong>EBS Volumes can be mounted to one instance at a time</strong> - At the Certified Cloud Practitioner level, EBS Volumes can be mounted to one instance at a time. It is also possible that an EBS Volume is not mounted to an instance.</p>
 <p><strong>EBS Volumes are bound to a specific Availability Zone (AZ)</strong> - As mentioned, when using EBS Volumes, the volume and the instance must be in the same Availability Zone.</p>
 <p><strong>EBS Volumes can persist data after their termination</strong> - Unlike EC2 instance store, an EBS volume is off-instance storage that can persist independently from the life of an instance.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-volumes.html">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-volumes.html</a></p>
</div>

**Question 42**

42. A company would like to move 50 petabytes (PBs) of data from its on-premises data centers to AWS in the MOST cost-effective way. As a Cloud Practitioner, which of the following solutions would you choose?
*  A. AWS Snowball Edge
*  B. AWS Storage Gateway
*  C. AWS Snowball
*  D. AWS Snowmobile

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Snowmobile</strong></p>
 <p>AWS Snowmobile is an Exabyte-scale data transfer service used to move extremely large amounts of data to AWS. You can transfer up to 100PB per Snowmobile, a 45-foot long ruggedized shipping container, pulled by a semi-trailer truck. Snowmobile makes it easy to move massive volumes of data to the cloud, including video libraries, image repositories, or even a complete data center migration. Transferring data with Snowmobile is more secure, fast and cost-effective.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Snowball Edge</strong> - Snowball Edge is an edge computing and data transfer device provided by the AWS Snowball service. It has on-board storage and compute power that provides select AWS services for use in edge locations. However, one Snowball Edge only provides up to 100 TB of capacity. Therefore, to transfer 50 PBs, AWS Snowball Edge is not the most cost-effective option.</p>
 <p><strong>AWS Snowball</strong> - AWS Snowball is a petabyte-scale data transport solution that uses secure appliances to transfer large amounts of data into and out of AWS. The use of Snowball addresses common challenges with large- scale data transfers including high network costs, long transfer times, and security concerns. Transferring data with Snowball is simple, fast, secure, and can be as little as one-fifth the cost of high-speed Internet. However, one Snowball only provides up to 80 TB of capacity. Therefore, to transfer 50 PBs, AWS Snowball is not the most cost-effective option.</p>
 <p><strong>AWS Storage Gateway</strong> - AWS Storage Gateway is a hybrid storage service that enables your on-premises applications to seamlessly use AWS cloud storage. You can use the service for backup and archiving, disaster recovery, cloud data processing, storage tiering, and migration. However, data transfer through AWS Storage Gateway takes longer even with great bandwidth. Moreover, to transfer 50 PBs of data, it will be more expensive than using AWS Snowmobile.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/snowmobile/">https://aws.amazon.com/snowmobile/</a></p>
</div>

**Question 43**

43. Which AWS serverless service allows you to prepare data for analytics?
*  A. AWS Glue
*  B. Amazon Redshift
*  C. Amazon EMR
*  D. Amazon Athena

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Glue</strong></p>
 <p><strong>AWS Glue</strong> - AWS Glue is a fully managed extract, transform, and load (ETL) service that makes it easy for customers to prepare and load their data for analytics. AWS Glue job is meant to be used for batch ETL data processing.</p>
 <p>How AWS Glue works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q42-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/glue/">https://aws.amazon.com/glue/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Athena</strong> - Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. Athena is serverless, so there is no infrastructure to manage, and you pay only for the queries that you run. Athena is used for analytics and not to prepare data for analytics.</p>
 <p><strong>Amazon Redshift</strong> - Amazon Redshift is a fast, scalable data warehouse that makes it simple and cost-effective to analyze all your data across your data warehouse and data lake. Redshift is used for analytics and not to prepare data for analytics.</p>
 <p><strong>Amazon EMR</strong> - Amazon EMR provides a managed Hadoop framework that makes it easy, fast, and cost-effective to process vast amounts of data across dynamically scalable Amazon EC2 instances. EMR is used for analytics and not to prepare data for analytics.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/glue/">https://aws.amazon.com/glue/</a></p>
</div>

**Question 44**

44. Which of the following are advantages of using the AWS Cloud? (Select TWO)
*  A. Trade operational expense for capital expense
*  B. AWS is responsible for security in the cloud
*  C. Limited scaling
*  D. Stop guessing about capacity
*  E. Increase speed and agility

**Answer** D, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Increase speed and agility</strong></p>
 <p><strong>Stop guessing about capacity</strong></p>
 <p>Exam Alert:</p>
 <p>Please check out the following six advantages of Cloud Computing. You would certainly be asked questions on the advantages of Cloud Computing compared to a traditional on-premises setup:</p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q63-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html">https://docs.aws.amazon.com/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Limited scaling</strong> - Scaling is not limited in the cloud. You can access as much or as little capacity as you need, and scale up and down as required with only a few minutes’ notice.</p>
 <p><strong>AWS is responsible for security in the cloud</strong> - AWS is responsible for security OF the cloud, which means AWS is responsible for protecting the infrastructure that runs all the services offered in the AWS Cloud.</p>
 <p><strong>Trade operational expense for capital expense</strong> - In the cloud, you trade capital expense (CAPEX) for the operational expense (OPEX). Instead of having to invest heavily in data centers and servers before you know how you’re going to use them, you can pay only when you consume computing resources, and pay only for how much you consume.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html">https://docs.aws.amazon.com/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html</a></p>
</div>

**Question 45**

45. Which of the following statements is CORRECT regarding the scope of an Amazon Virtual Private Cloud (VPC)?
*  A. A VPC spans all Availability Zones (AZs) in all regions
*  B. A VPC spans all Availability Zones (AZs) within a region
*  C. A VPC spans all subnets in all regions
*  D. A VPC spans all regions within an Availability Zone (AZ)

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>A VPC spans all Availability Zones (AZs) within a region</strong></p>
 <p>Amazon Virtual Private Cloud (Amazon VPC) lets you provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define. You have complete control over your virtual networking environment, including selection of your own IP address range, creation of subnets, and configuration of route tables and network gateways.</p>
 <p>A VPC spans all Availability Zones (AZs) within a region.</p>
 <p>Incorrect options:</p>
 <p><strong>A VPC spans all subnets in all regions</strong> - A VPC is located within a region.</p>
 <p><strong>A VPC spans all Availability Zones (AZs) in all regions</strong> - A VPC is located within a region.</p>
 <p><strong>A VPC spans all regions within an Availability Zone (AZ)</strong> - AWS has the concept of a Region, which is a physical location around the world where AWS clusters data centers. Each AWS Region consists of multiple (two or more), isolated, and physically separate AZ's within a geographic area. An Availability Zone (AZ) is one or more discrete data centers with redundant power, networking, and connectivity in an AWS Region. Therefore, regions cannot be within an Availability Zone. Moreover, a VPC is located within a region.</p>
 <p>AWS Regions and Availability Zones Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q24-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/about-aws/global-infrastructure/regions_az/">https://aws.amazon.com/about-aws/global-infrastructure/regions_az/</a></p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/vpc/">https://aws.amazon.com/vpc/</a></p>
</div>

**Question 46**

46. Which of the following are the best practices when using AWS Organizations? (Select TWO)
*  A. Create accounts per department
*  B. Never use tags for billing
*  C. Disable CloudTrail on several accounts
*  D. Do not use AWS Organizations to automate AWS account creation
*  E. Restrict account privileges using Service Control Policies (SCP)

**Answer** A, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Create accounts per department</strong></p>
 <p><strong>Restrict account privileges using Service Control Policies (SCP)</strong></p>
 <p>AWS Organizations helps you centrally govern your environment as you grow and scale your workloads on AWS. Whether you are a growing startup or a large enterprise, Organizations helps you to centrally manage billing; control access, compliance, and security; and share resources across your AWS accounts.</p>
 <p>Using AWS Organizations, you can automate account creation, create groups of accounts to reflect your business needs, and apply policies for these groups for governance. You can also simplify billing by setting up a single payment method for all of your AWS accounts. Through integrations with other AWS services, you can use Organizations to define central configurations and resource sharing across accounts in your organization. AWS Organizations is available to all AWS customers at no additional charge.</p>
 <p>You should create accounts per department based on regulatory restrictions (using SCP) for better resource isolation, and to have separate per-account service limits.</p>
 <p>AWS Organizations allows you to restrict what services and actions are allowed in your accounts. You can use Service Control Policies (SCPs) to apply permission guardrails on AWS Identity and Access Management (IAM) users and roles.</p>
 <p>Incorrect options:</p>
 <p><strong>Never use tags for billing</strong> - You should use tags standards to categorize AWS resources for billing purposes.</p>
 <p><strong>Disable CloudTrail on several accounts</strong> - You should enable CloudTrail to monitor activity on all accounts for governance, compliance, risk, and auditing purposes.</p>
 <p><strong>Do not use AWS Organizations to automate AWS account creation</strong> - AWS Organizations helps you simplify IT operations by automating AWS account creation and management. The Organizations APIs enable you to create new accounts programmatically, and to add the new accounts to a group. The policies attached to the group are automatically applied to the new account.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/organizations/">https://aws.amazon.com/organizations/</a></p>
</div>

**Question 47**

47. A production company would like to establish an AWS managed VPN service between its on-premises network and AWS. Which item needs to be set up on the company's side?
*  A. A virtual private gateway
*  B. A customer gateway
*  C. A security group
*  D. A VPC endpoint interface

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>A customer gateway</strong></p>
 <p>A customer gateway device is a physical or software appliance on your side of a Site-to-Site VPN connection. You or your network administrator must configure the device to work with the Site-to-Site VPN connection.</p>
 <p>You can enable access to your remote network from your VPC by creating an AWS Site-to-Site VPN (Site-to-Site VPN) connection, and configuring routing to pass traffic through the connection.</p>
 <ul>
  <li>Schema: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q41-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/vpn/latest/s2svpn/your-cgw.html">https://docs.aws.amazon.com/vpn/latest/s2svpn/your-cgw.html</a></li>
 </ul>
 <p>Incorrect options:</p>
 <p><strong>A security group</strong> - A security group acts as a virtual firewall for your instance to control inbound and outbound traffic. It is not a component of a connection between on-premises network and AWS.</p>
 <p><strong>A VPC endpoint interface</strong> - An interface VPC endpoint (interface endpoint) enables you to connect to services powered by AWS PrivateLink. It is not a component of a connection between on-premises network and AWS.</p>
 <p><strong>A virtual private gateway</strong> - A virtual private gateway device is a physical or software appliance on AWS side of a Site-to-Site VPN connection.</p>
 <p>References:</p>
 <p><a href="https://docs.aws.amazon.com/vpn/latest/s2svpn/your-cgw.html">https://docs.aws.amazon.com/vpn/latest/s2svpn/your-cgw.html</a></p>
 <p><a href="https://docs.aws.amazon.com/vpn/latest/s2svpn/VPC_VPN.html">https://docs.aws.amazon.com/vpn/latest/s2svpn/VPC_VPN.html</a></p>
</div>

**Question 48**

48. A production company with predictable usage would like to reduce the cost of its Amazon EC2 instances by using reserved instances. Which of the following length terms are available for Amazon EC2 reserved instances? (Select TWO)
*  A. 3 years
*  B. 6 months
*  C. 5 years
*  D. 1 year
*  E. 2 years

**Answer** A, D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>1 year</strong></p>
 <p><strong>3 years</strong></p>
 <p>Reserved Instances provide you with a significant discount (up to 75%) compared to On-Demand instance pricing. Besides, when Reserved Instances are assigned to a specific Availability Zone, they provide a capacity reservation, giving you additional confidence in your ability to launch instances when you need them.</p>
 <p>Standard and Convertible reserved instances can be purchased for a 1-year or 3-year term.</p>
 <p>EC2 Pricing Options Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q35-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/ec2/pricing/">https://aws.amazon.com/ec2/pricing/</a></p>
 <p>Incorrect options:</p>
 <p><strong>6 months</strong> - It is not possible to reserve instances for 6 months.</p>
 <p><strong>5 years</strong> - It is not possible to reserve instances for 5 years.</p>
 <p><strong>2 years</strong> - It is not possible to reserve instances for 2 years.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/ec2/pricing/">https://aws.amazon.com/ec2/pricing/</a></p>
</div>

**Question 49**

49. A start-up would like to quickly deploy a popular technology on AWS. As a Cloud Practitioner, which AWS tool would you use for this task?
*  A. AWS Whitepapers
*  B. AWS Forums
*  C. AWS CodeDeploy
*  D. AWS Quick Starts references

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Quick Starts references</strong></p>
 <p>Quick Starts are built by AWS solutions architects and partners to help you deploy popular technologies on AWS, based on AWS best practices for security and high availability. These accelerators reduce hundreds of manual procedures into just a few steps, so you can build your production environment quickly and start using it immediately.</p>
 <p>Each Quick Start includes AWS CloudFormation templates that automate the deployment and a guide that discusses the architecture and provides step-by-step deployment instructions.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Forums</strong> - AWS Forums is an AWS community platform where people can help each other. It is not used to deploy technologies on AWS.</p>
 <p><strong>AWS CodeDeploy</strong> - AWS CodeDeploy is a service that automates code deployments to any instance, including EC2 instances and instances running on-premises. It is not suited to rapidly deploy popular technologies on AWS ready to used immediately.</p>
 <p><strong>AWS Whitepapers</strong> - AWS Whitepapers are technical content authored by AWS and the AWS community to expand your knowledge of the cloud. They include technical whitepapers, technical guides, reference material, and reference architectures diagrams. You can find useful content for your deployment, but it is not a service that will deploy technologies.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/quickstart/">https://aws.amazon.com/quickstart/</a></p>
</div>

**Question 50**

50. Which AWS service can inspect CloudFront distributions running on any HTTP web-server?
*  A. AWS WAF
*  B. AWS Elastic Load Balancer
*  C. Amazon Inspector
*  D. AWS GuardDuty

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS WAF</strong></p>
 <p>AWS WAF is a web application firewall that helps protect web applications from attacks by allowing you to configure rules that allow, block, or monitor (count) web requests based on conditions that you define. These conditions include IP addresses, HTTP headers, HTTP body, URI strings, SQL injection and cross-site scripting.</p>
 <p>AWS WAF is a web application firewall that lets you monitor the HTTP and HTTPS requests that are forwarded to CloudFront, and lets you control access to your content.</p>
 <p>When you use AWS WAF on Amazon CloudFront, your rules run in all AWS Edge Locations, located around the world close to your end-users. This means security doesn’t come at the expense of performance. Blocked requests are stopped before they reach your web servers.</p>
 <p>How AWS WAF works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q49-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/waf/">https://aws.amazon.com/waf/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS GuardDuty</strong> - Amazon GuardDuty is a threat detection service that continuously monitors for malicious or unauthorized behavior to help you protect your AWS accounts and workloads. It does not inspect CloudFront distributions.</p>
 <p><strong>Amazon Inspector</strong> - Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. Amazon Inspector automatically assesses applications for exposure, vulnerabilities, and deviations from best practices. Amazon Inspector security assessments help you check for unintended network accessibility of your Amazon EC2 instances and for vulnerabilities on those EC2 instances.</p>
 <p><strong>AWS Elastic Load Balancer</strong> - Elastic Load Balancing (ELB) automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, and IP addresses. It does not inspect CloudFront distributions.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/waf/">https://aws.amazon.com/waf/</a></p>
</div>

**Question 51**

51. Which AWS service can be used to subscribe to an RSS feed to be notified of the status of all AWS service interruptions?
*  A. AWS Lambda
*  B. AWS Personal Health Dashboard
*  C. Amazon SNS
*  D. AWS Service Health Dashboard

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Service Health Dashboard</strong></p>
 <p>AWS Service Health Dashboard publishes most up-to-the-minute information on the status and availability of all AWS services in tabular form for all Regions that AWS is present in. You can check on this page <a href="https://status.aws.amazon.com/">https://status.aws.amazon.com/</a> to get current status information.</p>
 <p>AWS Service Health Dashboard offers the possibility to subscribe to an RSS feed to be notified of interruptions to each service.</p>
 <p>AWS Service Health Dashboard Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q55-i1.jpg?raw=true"> via - <a href="https://status.aws.amazon.com/">https://status.aws.amazon.com/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon SNS</strong> - Amazon Simple Notification Service (Amazon SNS) is a highly available, durable, secure, fully managed pub/sub messaging service that enables you to decouple microservices, distributed systems, and serverless applications. It can be used to deliver notifications, but it does not provide current services' status.</p>
 <p><strong>AWS Personal Health Dashboard</strong> - AWS Personal Health Dashboard provides alerts and remediation guidance when AWS is experiencing events that may impact you. It does not provide updates about the general status for all AWS services.</p>
 <p>AWS Personal Health Dashboard Overview:</p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q55-i2.jpg?raw=true"> via - <a href="https://status.aws.amazon.com/">https://status.aws.amazon.com/</a></p>
 <p>Exam Alert:</p>
 <p>While the Service Health Dashboard displays the general status of AWS services, Personal Health Dashboard gives you a personalized view of the performance and availability of the AWS services underlying your AWS resources.</p>
 <p><strong>AWS Lambda</strong> - AWS Lambda lets you run code without provisioning or managing servers. It does not provide all AWS services' status.</p>
 <p>Reference:</p>
 <p><a href="https://status.aws.amazon.com/">https://status.aws.amazon.com/</a></p>
</div>

**Question 52**

52. A media company wants to enable customized content suggestions for the users of its movies streaming platform. Which AWS service can provide these personalized recommendations based on the historic data?
*  A. Amazon SageMaker
*  B. Amazon Comprehend
*  C. Amazon Personalize
*  D. Amazon Customize

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon Personalize</strong> - Amazon Personalize enables developers to build applications with the same machine learning (ML) technology used by Amazon.com for real-time personalized recommendations. Amazon Personalize can be used to personalize the end-user experience over any digital channel. Examples include product recommendations for e-commerce, news articles and content recommendation for publishing, media and social networks, hotel recommendations for travel websites, credit card recommendations for banks, and match recommendations for dating sites. These recommendations and personalized experiences can be delivered over websites, mobile apps, or email/messaging. Amazon Personalize can also be used to customize the user experience when user interaction is over a physical channel, e.g., a meal delivery company could personalize weekly meals to users in a subscription plan.</p>
 <p>Amazon Personalize supports the following key use cases:</p>
 <ol>
  <li>Personalized recommendations</li>
  <li>Similar items</li>
  <li>Personalized reranking i.e. rerank a list of items for a user</li>
  <li>Personalized promotions/notifications</li>
 </ol>
 <p>Incorrect options:</p>
 <p><strong>Amazon SageMaker</strong> - Amazon SageMaker is a fully managed service that provides every developer and data scientist with the ability to build, train, and deploy machine learning (ML) models quickly. SageMaker removes the heavy lifting from each step of the machine learning process to make it easier to develop high-quality models.</p>
 <p><strong>Amazon Customize</strong> - There is no such service as Amazon Customize. This option has been added as a distractor.</p>
 <p><strong>Amazon Comprehend</strong> - Amazon Comprehend is a natural-language processing (NLP) service that uses machine learning to uncover information in unstructured data. Instead of combing through documents, the process is simplified and unseen information is easier to understand.</p>
 <p>The service can identify critical elements in data, including references to language, people, and places, and the text files can be categorized by relevant topics. In real-time, you can automatically and accurately detect customer sentiment in your content.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/personalize/">https://aws.amazon.com/personalize/</a></p>
</div>

**Question 53**

53. An engineering team is new to the AWS Cloud and it would like to launch a dev/test environment with low monthly pricing. Which AWS service can address this use-case?
*  A. Amazon ECS
*  B. AWS CloudFormation
*  C. Amazon EC2
*  D. Amazon LightSail

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon Lightsail</strong></p>
 <p>Amazon Lightsail is designed to be the easiest way to launch and manage a virtual private server with AWS. Lightsail plans include everything you need to jumpstart your project – a virtual machine, SSD- based storage, data transfer, DNS management, and a static IP address – for a low, predictable price. It is not used to run batch jobs.</p>
 <p>It is great for people with little cloud experience to launch quickly a popular IT solution ready to use immediately.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS CloudFormation</strong> - AWS CloudFormation gives developers and systems administrators an easy way to create and manage a collection of related AWS resources, provisioning and updating them in an orderly and predictable fashion. Using CloudFormation requires experience as resources are deployed within a VPC.</p>
 <p><strong>Amazon EC2</strong> - Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud. It is designed to make web-scale computing easier for developers. Deploying a dev/test environment with Amazon EC2 requires experience as instances are deployed within a VPC.</p>
 <p><strong>Amazon ECS</strong> - Amazon Elastic Container Service (Amazon ECS) is a highly scalable, high- performance container orchestration service that supports Docker containers and allows you to easily run and scale containerized applications on AWS. Amazon ECS eliminates the need for you to install and operate your own container orchestration software, manage and scale a cluster of virtual machines, or schedule containers on those virtual machines. Using ECS requires experience.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/lightsail/">https://aws.amazon.com/lightsail/</a></p>
</div>

**Question 54**

54. Which AWS service allows you to quickly and easily add user sign-up, sign-in, and access control to web and mobile applications?
*  A. AWS Identity and Access Management (IAM)
*  B. AWS Organizations
*  C. AWS Single Sign-On (SSO)
*  D. Amazon Cognito

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon Cognito</strong></p>
 <p>Amazon Cognito lets you add user sign-up, sign-in, and access control to your web and mobile apps quickly and easily. With Amazon Cognito, you also have the option to authenticate users through social identity providers such as Facebook, Twitter, or Amazon, with SAML identity solutions, or by using your own identity system.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Identity and Access Management (IAM)</strong> - AWS Identity and Access Management (IAM) enables you to securely control access to AWS services and resources for your users. Using IAM, you can create and manage AWS users and groups, and use permissions to allow and deny their access to AWS resources. It does not provide user sign-up, sign-in, and access control to web and mobile applications.</p>
 <p><strong>AWS Single Sign-On (SSO)</strong> - AWS Single Sign-On (SSO) is a cloud SSO service that makes it easy to centrally manage SSO access to multiple AWS accounts and business applications. With just a few clicks, you can enable a highly available SSO service without the upfront investment and on-going maintenance costs of operating your own SSO infrastructure. With AWS SSO, you can easily manage SSO access and user permissions to all of your accounts in AWS Organizations centrally. It does not provide user sign-up, sign-in, and access control to web and mobile applications.</p>
 <p><strong>AWS Organizations</strong> - AWS Organizations offers policy-based management for multiple AWS accounts. With Organizations, you can create groups of accounts, automate account creation, apply and manage policies for those groups. Organizations enables you to centrally manage policies across multiple accounts, without requiring custom scripts and manual processes. It does not provide user sign-up, sign-in, and access control to web and mobile applications.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/cognito/">https://aws.amazon.com/cognito/</a></p>
</div>

**Question 55**

55. An engineering team would like to cost-effectively run hundreds of thousands of batch computing workloads on AWS. As a Cloud Practitioner, which AWS service would you use for this task?
*  A. Amazon Lightsail
*  B. AWS Lambda
*  C. AWS Batch
*  D. AWS Fargate

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Batch</strong></p>
 <p>AWS Batch enables developers, scientists, and engineers to easily and efficiently run hundreds of thousands of batch computing jobs on AWS.</p>
 <p>You can use AWS Batch to plan, schedule, and execute your batch computing workloads across the full range of AWS compute services. AWS Batch dynamically provisions the optimal quantity and type of compute resources (e.g., CPU or memory optimized instances) based on the volume and specific resource requirements of the batch jobs submitted. AWS Batch provisions compute resources and optimizes the job distribution based on the volume and resource requirements of the submitted batch jobs.</p>
 <p>Please review the common use-cases for AWS Batch:</p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q43-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/batch/">https://aws.amazon.com/batch/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS Lambda</strong> - AWS Lambda lets you run code without provisioning or managing servers. It can be used to run batch jobs, but has a time limit, and limited runtimes. It is usually used for smaller batch jobs.</p>
 <p><strong>Amazon Lightsail</strong> - Amazon Lightsail is designed to be the easiest way to launch and manage a virtual private server with AWS. Lightsail plans include everything you need to jumpstart your project – a virtual machine, SSD- based storage, data transfer, DNS management, and a static IP address – for a low, predictable price. It is not used to run batch jobs.</p>
 <p><strong>AWS Fargate</strong> - AWS Fargate is a compute engine for Amazon ECS that allows you to run containers without having to manage servers or clusters. You can run batch jobs on Fargate, but it is more expensive than AWS Batch.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/batch/">https://aws.amazon.com/batch/</a></p>
</div>

**Question 56**

56. A company based in Sydney hosts its application on EC2 instances in ap-southeast-2. They would like to deploy the same EC2 instances in eu-south-1. Which of the following AWS entities can address this use-case?
*  A. AWS Lambda
*  B. Elastic Load Balancing (ELB)
*  C. EBS snapshots
*  D. Amazon Machine Image (AMI)

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon Machine Image (AMI)</strong></p>
 <p>An Amazon Machine Image (AMI) provides the information required to launch an instance. You must specify an AMI when you launch an instance. You can launch multiple instances from a single AMI when you need multiple instances with the same configuration.</p>
 <p>How to use an AMI: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q13-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Elastic Load Balancing (ELB)</strong> - Elastic Load Balancing automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, and Lambda functions. It can handle the varying load of your application traffic in a single Availability Zone or across multiple Availability Zones. It cannot be used to deploy the same EC2 instances across different Availability Zones (AZs).</p>
 <p><strong>AWS Lambda</strong> - AWS Lambda lets you run code without provisioning or managing servers. It cannot be used to deploy the same EC2 instances across different Availability Zones (AZs).</p>
 <p><strong>EBS snapshots</strong> - An EBS snapshot is a point-in-time copy of your Amazon EBS volume. EBS snapshots are one of the components of an AMI, but EBS snapshots alone cannot be used to deploy the same EC2 instances across different Availability Zones (AZs).</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html</a></p>
</div>

**Question 57**

57. Which AWS service can be used to view the most comprehensive billing details for the past month?
*  A. AWS Cost Explorer
*  B. AWS Budgets
*  C. AWS Pricing Calculator
*  D. AWS Cost and Usage Reports

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Cost &amp; Usage Reports</strong></p>
 <p>The AWS Cost and Usage Reports (AWS CUR) contains the most comprehensive set of cost and usage data available. You can use Cost and Usage Reports to publish your AWS billing reports to an Amazon Simple Storage Service (Amazon S3) bucket that you own. You can receive reports that break down your costs by the hour or month, by product or product resource, or by tags that you define yourself.</p>
 <p>AWS Cost and Usage Reports Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q15-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/cur/latest/userguide/what-is-cur.html">https://docs.aws.amazon.com/cur/latest/userguide/what-is-cur.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS Budgets</strong> - AWS Budgets gives the ability to set custom budgets that alert you when your costs or usage exceed (or are forecasted to exceed) your budgeted amount. You can also use AWS Budgets to set reservation utilization or coverage targets and receive alerts when your utilization drops below the threshold you define. Budgets can be created at the monthly, quarterly, or yearly level, and you can customize the start and end dates. You can further refine your budget to track costs associated with multiple dimensions, such as AWS service, linked account, tag, and others. AWS Budgets cannot provide billing details for the past month.</p>
 <p><strong>AWS Cost Explorer</strong> - AWS Cost Explorer has an easy-to-use interface that lets you visualize, understand, and manage your AWS costs and usage over time. AWS Cost Explorer includes a default report that helps you visualize the costs and usage associated with your top five cost-accruing AWS services, and gives you a detailed breakdown of all services in the table view. The reports let you adjust the time range to view historical data going back up to twelve months to gain an understanding of your cost trends. AWS Cost Explorer cannot provide granular billing details for the past month.</p>
 <p><strong>AWS Pricing Calculator</strong> - AWS Pricing Calculator lets you explore AWS services and create an estimate for the cost of your use cases on AWS. You can model your solutions before building them, explore the price points and calculations behind your estimate, and find the available instance types and contract terms that meet your needs. This enables you to make informed decisions about using AWS. You can plan your AWS costs and usage or price out setting up a new set of instances and services. AWS Pricing Calculator cannot provide billing details for the past month.</p>
 <p>Exam Alert:</p>
 <p>Please review the differences between "AWS Cost and Usage Reports" and "AWS Cost Explorer". Think of "AWS Cost and Usage Reports" as a cost management tool providing the most detailed cost and usage data for your AWS account. It can provide reports that break down your costs by the hour into your S3 bucket. On the other hand, "AWS Cost Explorer" is more of a high-level cost management tool that helps you visualize the costs and usage associated with your AWS account.</p>
 <p>"AWS Cost Explorer" vs "AWS Cost and Usage Reports": <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q15-i2.jpg?raw=true"> via - <a href="https://aws.amazon.com/aws-cost-management/aws-cost-explorer/">https://aws.amazon.com/aws-cost-management/aws-cost-explorer/</a></p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q15-i3.jpg?raw=true"> via - <a href="https://aws.amazon.com/aws-cost-management/aws-cost-and-usage-reporting/">https://aws.amazon.com/aws-cost-management/aws-cost-and-usage-reporting/</a></p>
 <p>References:</p>
 <p><a href="https://docs.aws.amazon.com/cur/latest/userguide/what-is-cur.html">https://docs.aws.amazon.com/cur/latest/userguide/what-is-cur.html</a></p>
 <p><a href="https://aws.amazon.com/aws-cost-management/aws-cost-explorer/">https://aws.amazon.com/aws-cost-management/aws-cost-explorer/</a></p>
 <p><a href="https://aws.amazon.com/aws-cost-management/aws-cost-and-usage-reporting/">https://aws.amazon.com/aws-cost-management/aws-cost-and-usage-reporting/</a></p>
</div>

**Question 58**

58. A brand new startup would like to remove its need to manage the underlying infrastructure and focus on the deployment and management of its applications. Which type of Cloud Computing does this refer to?
*  A. On-premises
*  B. Infrastructure as a Service (IaaS)
*  C. Software as a Service (SaaS)
*  D. Platform as a Service (PaaS)

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Platform as a Service (PaaS)</strong></p>
 <p>Cloud Computing can be broadly divided into three types - Infrastructure as a Service (IaaS), Platform as a Service (PaaS), Software as a Service (SaaS).</p>
 <p>PaaS removes the need to manage underlying infrastructure (usually hardware and operating systems) and allows you to focus on the deployment and management of your applications. You don’t need to worry about resource procurement, capacity planning, software maintenance, patching, or any of the other undifferentiated heavy lifting involved in running your application.</p>
 <p>Please review this overview of the types of Cloud Computing: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q5-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/types-of-cloud-computing/">https://aws.amazon.com/types-of-cloud-computing/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Infrastructure as a Service (IaaS)</strong> - IaaS contains the basic building blocks for cloud IT. It typically provides access to networking features, computers (virtual or on dedicated hardware), and data storage space. IaaS gives the highest level of flexibility and management control over IT resources.</p>
 <p><strong>Software as a Service (SaaS)</strong> - SaaS provides you with a complete product that is run and managed by the service provider. With a SaaS offering, you don’t have to think about how the service is maintained or how the underlying infrastructure is managed. You only need to think about how you will use that particular software. AWS Rekognition is an example of a SaaS service.</p>
 <p><strong>On-premises</strong> - When an enterprise opts for on-premises, it needs to create, upgrade, and scale the on-premise IT infrastructure by investing in sophisticated hardware, compatible software, and robust services. Also, the business needs to deploy dedicated IT staff to upkeep, scale, and manage the on-premise infrastructure continuously.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/types-of-cloud-computing/">https://aws.amazon.com/types-of-cloud-computing/</a></p>
</div>

**Question 59**

59. A company would like to optimize Amazon EC2 costs. Which of the following actions can help with this task? (Select TWO)
*  A. Set up Auto Scaling groups to align the number of instances with demand
*  B. Build its own servers
*  C. Purchase EC2 Reserved instances
*  D. Opt for a higher AWS Support plan
*  E. Vertically scale the EC2 instances

**Answer** A, C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Set up Auto Scaling groups to align the number of instances with demand</strong></p>
 <p><strong>Purchase EC2 Reserved instances</strong></p>
 <p>An Auto Scaling group contains a collection of Amazon EC2 instances that are treated as a logical grouping for automatic scaling and management. You can adjust its size to meet demand, either manually or by using automatic scaling.</p>
 <p>AWS Auto Scaling can help you optimize your utilization and cost efficiencies when consuming AWS services so you only pay for the resources you need.</p>
 <p>How AWS Auto Scaling works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q64-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/autoscaling/">https://aws.amazon.com/autoscaling/</a></p>
 <p>Amazon EC2 Reserved Instances (RI) provide a significant discount (up to 72%) compared to On-Demand pricing and provide a capacity reservation when used in a specific Availability Zone.</p>
 <p>EC2 Pricing Options Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q64-i2.jpg?raw=true"> via - <a href="https://aws.amazon.com/ec2/pricing/">https://aws.amazon.com/ec2/pricing/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Vertically scale the EC2 instances</strong> - Vertically scaling EC2 instances (increasing one computer performance by adding CPUs, memory, and storage) is limited and is way more expensive than scaling horizontally (adding more computers to the system).</p>
 <p><strong>Opt for a higher AWS Support plan</strong> - The AWS Support plans do not help with EC2 costs.</p>
 <p><strong>Build its own servers</strong> - Building your own servers is more expensive than using EC2 instances in the cloud. You're more likely to spend more money than saving money.</p>
 <p>References:</p>
 <p><a href="https://docs.aws.amazon.com/autoscaling/ec2/userguide/AutoScalingGroup.html">https://docs.aws.amazon.com/autoscaling/ec2/userguide/AutoScalingGroup.html</a></p>
 <p><a href="https://aws.amazon.com/ec2/pricing/reserved-instances/">https://aws.amazon.com/ec2/pricing/reserved-instances/</a></p>
 <p><a href="https://wa.aws.amazon.com/wat.concept.horizontal-scaling.en.html">https://wa.aws.amazon.com/wat.concept.horizontal-scaling.en.html</a></p>
 <p><a href="https://aws.amazon.com/autoscaling/">https://aws.amazon.com/autoscaling/</a></p>
</div>

**Question 60**

60. A company would like to define a set of rules to manage objects cost-effectively between storage classes. As a Cloud Practitioner, which Amazon S3 feature would you use?
*  A. S3 Transfer Acceleration
*  B. S3 Bucket policies
*  C. S3 Cross-Region Replication (CRR)
*  D. S3 Lifecycle management

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>S3 Lifecycle management</strong></p>
 <p>To manage your objects so that they are stored cost-effectively throughout their lifecycle, configure their Amazon S3 Lifecycle. An S3 Lifecycle configuration is a set of rules that define actions that Amazon S3 applies to a group of objects. There are two types of actions: Transition actions (define when objects transition to another storage class) and expiration actions (define when objects expire. Amazon S3 deletes expired objects on your behalf).</p>
 <p>In this particular use-case, you would use a transition action.</p>
 <p>Incorrect options:</p>
 <p><strong>S3 Transfer Acceleration</strong> - Amazon S3 Transfer Acceleration enables fast, easy, and secure transfers of files over long distances between your client and an S3 bucket. It is not used to move objects between storage classes.</p>
 <p><strong>S3 Bucket policies</strong> - A bucket policy is a resource-based AWS Identity and Access Management (IAM) policy. You add a bucket policy to a bucket to grant other AWS accounts or IAM users access permissions for the bucket and the objects in it. Object permissions apply only to the objects that the bucket owner creates. It is not used to move objects between storage classes.</p>
 <p><strong>S3 Cross-Region Replication (CRR)</strong> - Replication enables automatic, asynchronous copying of objects across Amazon S3 buckets. Cross-Region replication (CRR) is used to copy objects across Amazon S3 buckets in different AWS Regions. It is not used to move objects between storage classes.</p>
 <p>References:</p>
 <p><a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/object-lifecycle-mgmt.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/object-lifecycle-mgmt.html</a></p>
 <p><a href="https://aws.amazon.com/s3/">https://aws.amazon.com/s3/</a></p>
</div>

**Question 61**

61. A company would like to separate cost for AWS services by the department for cost allocation. Which of the following is the simplest way to achieve this task?
*  A. Create tags for each department
*  B. Create different VPCs for different departments
*  C. Create different accounts for different departments
*  D. Create one account for all departments and share this account

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Create tags for each department</strong></p>
 <p>You can assign metadata to your AWS resources in the form of tags. Each tag is a label consisting of a user-defined key and value. Tags can help you manage, identify, organize, search for, and filter resources. You can create tags to categorize resources by purpose, owner, environment, or other criteria.</p>
 <p>Typically, you use business tags such as cost center/business unit, customer, or project to associate AWS costs with traditional cost-allocation dimensions. But a cost allocation report can include any tag. This lets you associate costs with technical or security dimensions, such as specific applications, environments, or compliance programs.</p>
 <p>Example of tagging for cost optimization: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q62-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/general/latest/gr/aws_tagging.html">https://docs.aws.amazon.com/general/latest/gr/aws_tagging.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Create different accounts for different departments</strong> - Users can belong to several departments. Therefore, having different accounts for different departments would imply some users having several accounts. This is contrary to the security best practice: one physical user = one account. Also, it is much simpler to set up tags for tracking costs for each department.</p>
 <p><strong>Create one account for all departments and share this account</strong> - Sharing accounts is not a security best practice, and is not recommended.</p>
 <p><strong>Create different VPCs for different departments</strong> - Creating different VPCs will not help with separating costs.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/general/latest/gr/aws_tagging.html">https://docs.aws.amazon.com/general/latest/gr/aws_tagging.html</a></p>
</div>

**Question 62**

62. According to the Shared Responsibility Model, which of the following is both the responsibility of AWS and the customer? (Select two)
*  A. Operating system (OS) configuration
*  B. Disposal of disk drives
*  C. Configuration management
*  D. Data center security
*  E. Customer data

**Answer** A, C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Configuration management</strong></p>
 <p>Shared Controls – Controls which apply to both the infrastructure layer and customer layers, but in completely separate contexts or perspectives. In a shared control, AWS provides the requirements for the infrastructure and the customer must provide their own control implementation within their use of AWS services.</p>
 <p>Configuration Management – AWS maintains the configuration of its infrastructure devices, but a customer is responsible for configuring their own guest operating systems, databases, and applications.</p>
 <p><strong>Operating system (OS) configuration</strong></p>
 <p>The customers are responsible for "Security IN the cloud". It includes customer data, as well as the guest operating system configuration.</p>
 <p>OS configuration as a whole is a shared responsibility, but be careful: the host OS configuration is the responsibility of AWS, and the guest OS configuration is the responsibility of the customer.</p>
 <p>Exam Alert:</p>
 <p>Please review the Shared Responsibility Model in detail as you can expect multiple questions on the shared responsibility model in the exam: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/Shared_Responsibility_Model_V2.59d1eccec334b366627e9295b304202faf7b899b.jpg?raw=true"> via - <a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Customer data</strong></p>
 <p><strong>Data center security</strong></p>
 <p><strong>Disposal of disk drives</strong></p>
 <p>AWS is responsible for "Security OF the cloud". It includes the infrastructure, which is composed of the hardware, software, networking, and facilities that run AWS Cloud services. It includes the disposal and the replacement of disk drives as well as data center security.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
</div>

**Question 63**

63. The IT infrastructure at a university is deployed on AWS Cloud and it's experiencing a read-intensive workload. As a Cloud Practitioner, which AWS service would you use to take the load off databases?
*  A. Amazon ElastiCache
*  B. Amazon EMR
*  C. AWS Glue
*  D. Amazon Relational Database Service (RDS)

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon ElastiCache</strong></p>
 <p>Amazon ElastiCache is a web service that makes it easy to deploy, operate, and scale an in-memory cache in the cloud. The service improves the performance of web applications by allowing you to retrieve information from fast, managed, in-memory caches, instead of relying entirely on slower disk-based databases.</p>
 <p>If EC2 instances are intensively reading data from a database, ElastiCache can cache some values to take the load off the database.</p>
 <p>How Amazon ElastiCache works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q25-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/elasticache/">https://aws.amazon.com/elasticache/)</a>)</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Relational Database Service (RDS)</strong> - Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while automating time-consuming administration tasks such as hardware provisioning, database setup, patching and backups. It frees you to focus on your applications so you can give them the fast performance, high availability, security and compatibility they need. It cannot be used to take the load off databases. However, ElastiCache is often used with RDS to take the load off RDS.</p>
 <p><strong>AWS Glue</strong> - AWS Glue is a fully managed extract, transform, and load (ETL) service that makes it easy for customers to prepare and load their data for analytics. AWS Glue job is meant to be used for batch ETL data processing. It cannot be used to take the load off the databases.</p>
 <p><strong>Amazon EMR</strong> - Amazon EMR provides a managed Hadoop framework that makes it easy, fast, and cost-effective to process vast amounts of data across dynamically scalable Amazon EC2 instances. It cannot be used to take the load off the databases.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/elasticache/">https://aws.amazon.com/elasticache/</a></p>
</div>

**Question 64**

64. Which of the following AWS Support plans is the MOST cost-effective when getting enhanced technical support by Cloud Support Engineers?
*  A. Enterprise
*  B. Developer
*  C. Basic
*  D. Business

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Business</strong></p>
 <p>AWS recommends Business Support if you have production workloads on AWS and want 24x7 phone, email and chat access to technical support and architectural guidance in the context of your specific use-cases. You get full access to AWS Trusted Advisor Best Practice Checks. It is also the cheapeast support plan to provide enhanced technical support by Cloud Support Engineers.</p>
 <p>AWS Business Support Plan Offerings: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q28-i1.jpg?raw=true"></p>
 <p>Exam Alert:</p>
 <p>Please review the differences between the Developer, Business, and Enterprise support plans as you can expect at least a couple of questions on the exam:</p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q28-i2.jpg?raw=true"></p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/AWS Certified Cloud Practitioner - 6 Practice Exams/exam01/images/pt5-q28-i3.jpg?raw=true"></p>
 <p>via - <a href="https://aws.amazon.com/premiumsupport/plans/">https://aws.amazon.com/premiumsupport/plans/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Developer</strong> - AWS recommends Developer Support if you are testing or doing early development on AWS and want the ability to get technical support during business hours as well as general architectural guidance as you build and test. It provides enhanced technical support, but by Cloud Support Associates.</p>
 <p><strong>Basic</strong> - A basic support plan is included for all AWS customers. It does not provide enhanced technical support.</p>
 <p><strong>Enterprise</strong> - AWS Enterprise Support provides customers with concierge-like service where the main focus is helping the customer achieve their outcomes and find success in the cloud. With Enterprise Support, you get 24x7 technical support from high-quality engineers, tools and technology to automatically manage the health of your environment, consultative architectural guidance delivered in the context of your applications and use-cases, and a designated Technical Account Manager (TAM) to coordinate access to proactive/preventative programs and AWS subject matter experts. It provides enhanced technical support by Cloud Support Engineers, but is more expensive than the Business support plan.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/premiumsupport/plans/">https://aws.amazon.com/premiumsupport/plans/</a></p>
 <p><a href="https://aws.amazon.com/premiumsupport/plans/business/">https://aws.amazon.com/premiumsupport/plans/business/</a></p>
</div>

**Question 65**

65. A developer would like to automate operations on his on-premises environment using Chef and Puppet. Which AWS service can help with this task?
*  A. AWS Batch
*  B. AWS OpsWorks
*  C. AWS CloudFormation
*  D. AWS CodeDeploy

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS OpsWorks</strong></p>
 <p>AWS OpsWorks is a configuration management service that provides managed instances of Chef and Puppet. Chef and Puppet are automation platforms that allow you to use code to automate the configurations of your servers. OpsWorks lets you use Chef and Puppet to automate how servers are configured, deployed, and managed across your Amazon EC2 instances or on-premises compute environments.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS CloudFormation</strong> - AWS CloudFormation gives developers and systems administrators an easy way to create and manage a collection of related AWS resources, provisioning and updating them in an orderly and predictable fashion. It does not use Chef and Puppet and is more focused on what and how AWS resources are procured.</p>
 <p><strong>AWS CodeDeploy</strong> - AWS CodeDeploy is a service that automates code deployments to any instance, including EC2 instances and instances running on premises. It does not use Chef and Puppet, and does not deal with infrastructure configuration and orchestration.</p>
 <p><strong>AWS Batch</strong> - AWS Batch enables developers, scientists, and engineers to easily and efficiently run hundreds of thousands of batch computing jobs on AWS. It is not used to automate operations on his on-premises environment using Chef and Puppet.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/opsworks/">https://aws.amazon.com/opsworks/</a></p>
</div>