# AWS Certified Practitioner Exam

## Exam 02

**Question 1**

1. Which AWS compute service provides the EASIEST way to access resizable compute capacity in the cloud with support for per-second billing and access to the underlying OS?
*  A. Amazon Lightsail
*  B. Amazon Elastic Compute Cloud (EC2)
*  C. Amazon Elastic Container Service (ECS)
*  D. AWS Lambda

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon Elastic Compute Cloud (EC2)</strong></p>
 <p>Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud with support for per-second billing. It is the easiest way to provision servers on AWS Cloud and access the underlying OS. Amazon EC2 reduces the time required to obtain and boot new server instances to minutes, allowing you to quickly scale capacity, both up and down, as your computing requirements change.</p>
 <p>Amazon EC2 Overview: <img src="./images/pt2-q41-i1.jpg"> via - <a href="https://aws.amazon.com/ec2/">https://aws.amazon.com/ec2/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Elastic Container Service (ECS)</strong> - Amazon Elastic Container Service (ECS) is a highly scalable, high-performance container management service that supports Docker containers and allows you to easily run applications on a managed cluster of Amazon EC2 instances. Technically, you can access the underlying EC2 instances, but the set up is more complex than just using the EC2 service directly, so this option is ruled out.</p>
 <p>How ECS Works: <img src="./images/product-page-diagram_ECS_1.86ebd8c223ec8b55aa1903c423fbe4e672f3daf7.png"> via - <a href="https://aws.amazon.com/ecs/">https://aws.amazon.com/ecs/</a></p>
 <p><strong>AWS Lambda</strong> - AWS Lambda lets you run code without provisioning or managing servers. You pay only for the compute time you consume. AWS Lambda is serverless, so you don't get access to the underlying OS.</p>
 <p><strong>Amazon Lightsail</strong> - Lightsail is an easy-to-use cloud platform that offers you everything needed to build an application or website, plus a cost-effective, monthly plan. Lightsail offers several preconfigured, one-click-to-launch operating systems, development stacks, and web applications, including Linux, Windows OS, and WordPress. Lightsail comes with monthly payment plans and does not support per second billing, so this option is ruled out.</p>
 <p>References: <a href="https://aws.amazon.com/ec2/">https://aws.amazon.com/ec2/</a></p>
 <p><a href="https://aws.amazon.com/ecs/">https://aws.amazon.com/ecs/</a></p>
</div>

**Question 2**

2. Which of the following solutions can you use to connect your on-premises network with AWS Cloud (Select two).
*  A. Amazon Route 53
*  B. AWS Direct Connect
*  C. Amazon VPC
*  D. Internet Gateway
*  E. AWS VPN

**Answer** B, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>AWS Direct Connect</strong> - AWS Direct Connect is a cloud service solution that makes it easy to establish a dedicated network connection from your premises to AWS. Using AWS Direct Connect, you can establish private connectivity between AWS and your datacenter, office, or colocation environment, which in many cases can reduce your network costs, increase bandwidth throughput, and provide a more consistent network experience than Internet-based connections.</p>
 <p>How AWS Direct Connect Works: <img src="./images/Product-Page-Diagram_Direct-Connect.0166400894ac5f9c921c3f7a346f55d8c42f492c.png"> via - <a href="https://aws.amazon.com/directconnect/">https://aws.amazon.com/directconnect/</a></p>
 <p><strong>AWS VPN</strong> - AWS Virtual Private Network (VPN) solutions establish secure connections between on-premises networks, remote offices, client devices, and the AWS global network. AWS VPN is comprised of two services: AWS Site-to-Site VPN and AWS Client VPN. Together, they deliver a highly-available, managed, and elastic cloud VPN solution to protect your network traffic.</p>
 <p>How AWS Client VPN Works: <img src="./images/Product-Page-Diagram_Aws-Client-VPN-Connect@2x.7e31b8a9dc7f38312794b311d37faf145adc0f96.png"> via - <a href="https://aws.amazon.com/vpn/">https://aws.amazon.com/vpn/</a></p>
 <p>How AWS Site-to-Site VPN Works: <img src="./images/product-page-diagram_Accelerated-Site-to-Site-VPN_How-it-Works@2x.89c94ea4b307abe21f82d9fd453fe3c72cacb2a3.png"> via - <a href="https://aws.amazon.com/vpn/">https://aws.amazon.com/vpn/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon VPC</strong> - Amazon Virtual Private Cloud (Amazon VPC) lets you provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define. You have complete control over your virtual networking environment, including the selection of your IP address range, creation of subnets, and configuration of route tables and network gateways. You cannot use Amazon VPC to connect your on-premises network with AWS Cloud.</p>
 <p><strong>Internet Gateway</strong> - An Internet Gateway is a horizontally scaled, redundant, and highly available VPC component that allows communication between instances in your VPC and the internet. Therefore, it imposes no availability risks or bandwidth constraints on your network traffic. You cannot use an Internet Gateway to interconnect your on-premises network with AWS Cloud, hence this option is incorrect.</p>
 <p><strong>Amazon Route 53</strong> - Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service. It is designed to give developers and businesses an extremely reliable and cost-effective way to route end users to Internet applications by translating names like www.example.com into the numeric IP addresses like 192.0.2.1 that computers use to connect. You cannot use Amazon Route 53 to connect your on-premises network with AWS Cloud.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/vpn/">https://aws.amazon.com/vpn/</a></p>
 <p><a href="https://aws.amazon.com/directconnect/">https://aws.amazon.com/directconnect/</a></p>
</div>

**Question 3**

3. A company's flagship application runs on a fleet of Amazon EC2 instances. As per the new policies, the system administrators are looking for the best way to provide secure shell access to AWS EC2 instances without opening new ports or using public IP addresses.
*  A. Amazon Inspector
*  B. Amazon Route 53
*  C. Amazon EC2 Instance Connect
*  D. AWS Systems Manager Session Manager

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Systems Manager Session Manager</strong></p>
 <p>AWS SSM Session Manager is a fully-managed service that provides you with an interactive browser-based shell and CLI experience. It helps provide secure and auditable instance management without the need to open inbound ports, maintain bastion hosts, and manage SSH keys. Session Manager helps to enable compliance with corporate policies that require controlled access to instances, increase security and auditability of access to the instances while providing simplicity and cross-platform instance access to end-users.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon EC2 Instance Connect</strong> - Amazon EC2 Instance Connect provides a simple and secure way to connect to your Linux instances using Secure Shell (SSH). With EC2 Instance Connect, you use AWS Identity and Access Management (IAM) policies and principals to control SSH access to your instances, removing the need to share and manage SSH keys. Instance Connect will need port 22 to be open for traffic. Therefore, not the correct option here.</p>
 <p><strong>Amazon Inspector</strong> - Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. Amazon Inspector automatically assesses applications for exposure, vulnerabilities, and deviations from best practices. After performing an assessment, Amazon Inspector produces a detailed list of security findings prioritized by level of severity. Inspector cannot provide secure shell access to EC2 instances.</p>
 <p><strong>Amazon Route 53</strong> - Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service. It is designed to give developers and businesses an extremely reliable and cost-effective way to route end users to Internet applications by translating names like www.example.com into the numeric IP addresses like 192.0.2.1 that computers use to connect to each other. Route 53 cannot provide secure shell access to EC2 instances.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/systems-manager/faq/">https://aws.amazon.com/systems-manager/faq/</a></p>
</div>

**Question 4**

4. Which of the following are examples of Horizontal Scalability (aka Elasticity)? (Select two)
*  A. Read Replicas in Amazon RDS
*  B. Elastic Load Balancing
*  C. Modify an EC2 instance type from t2.nano to u-12tb1.metal
*  D. Modify a Database instance to higher CPU and RAM
*  E. Add a bigger CPU to a computer

**Answer** A, B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options: <strong>Elastic Load Balancing</strong></p>
 <p><strong>Read Replicas in Amazon RDS</strong></p>
 <p>A "horizontally scalable" system is one that can increase capacity by adding more computers to the system. This is in contrast to a "vertically scalable" system, which is constrained to running its processes on only one computer; in such systems, the only way to increase performance is to add more resources into one computer in the form of faster (or more) CPUs, memory or storage. Horizontally scalable systems are oftentimes able to outperform vertically scalable systems by enabling parallel execution of workloads and distributing those across many different computers.</p>
 <p>Elastic Load Balancing - Elastic Load Balancing automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, and Lambda functions. It can handle the varying load of your application traffic in a single Availability Zone or across multiple Availability Zones. This falls under Horizontal Scaling.</p>
 <p>"Read Replicas in Amazon RDS" - Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a relational database in the cloud. Read replicas allow you to create read-only copies that are synchronized with your master database. You can also place your read replica in a different AWS Region closer to your users for better performance. Read replicas are an example of horizontal scaling of resources.</p>
 <p>Incorrect options:</p>
 <p><strong>Add a bigger CPU to a computer</strong> - As explained above, this comes under vertical scaling since the bigger resource is being added to a single computer or node.</p>
 <p><strong>Modify an EC2 instance type from t2.nano to u-12tb1.metal</strong> - Enhancing the type of a single Amazon EC2 system is also an example of vertical scaling since the extra capacity is being added to a single instance.</p>
 <p><strong>Modify a Database instance to higher CPU and RAM</strong> - This is also an example of vertical scaling since the focus is on increasing the capacity of a single machine or instance.</p>
 <p>Reference:</p>
 <p><a href="https://wa.aws.amazon.com/wat.concept.horizontal-scaling.en.html">https://wa.aws.amazon.com/wat.concept.horizontal-scaling.en.html</a></p>
</div>

**Question 5**

5. A company is using a message broker service on its on-premises application and wants to move this messaging functionality to AWS Cloud. Which of the following AWS services is the right choice to move the existing functionality easily?
*  A. Amazon Simple Queue Service (SQS)
*  B. Amazon Kinesis Data Stream
*  C. Amazon MQ
*  D. Amazon Simple Notification Service (SNS)

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon MQ</strong> - Amazon MQ is a managed message broker service for Apache ActiveMQ and RabbitMQ that makes it easy to set up and operate message brokers on AWS. Amazon MQ reduces your operational responsibilities by managing the provisioning, setup, and maintenance of message brokers for you. Because Amazon MQ connects to your current applications with industry-standard APIs and protocols, you can easily migrate to AWS without having to rewrite code.</p>
 <p>If you're using messaging with existing applications, and want to move the messaging functionality to the cloud quickly and easily, AWS recommends you consider Amazon MQ. It supports industry-standard APIs and protocols so you can switch from any standards-based message broker to Amazon MQ without rewriting the messaging code in your applications. If you are building brand new applications in the cloud, AWS recommends you consider Amazon SQS and Amazon SNS.</p>
 <p>How MQ works: <img src="./images/Amazon MQ HIW Diagram.78e380e8a97064c8f751c1569481a304644490b5.jpg"> via - <a href="https://aws.amazon.com/amazon-mq/">https://aws.amazon.com/amazon-mq/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Simple Queue Service (SQS)</strong> - Amazon Simple Queue Service (Amazon SQS) offers a reliable, highly scalable hosted queue for storing messages as they travel between computers. Amazon SQS lets you easily move data between distributed application components and helps you build applications in which messages are processed independently (with message-level ack/fail semantics), such as automated workflows.</p>
 <p><strong>Amazon Simple Notification Service (SNS)</strong> - Amazon Simple Notification Service (Amazon SNS) is a fully managed messaging service for both application-to-application (A2A) and application-to-person (A2P) communication. The A2A pub/sub functionality provides topics for high-throughput, push-based, many-to-many messaging between distributed systems, microservices, and event-driven serverless applications. Amazon SNS allows applications to send time-critical messages to multiple subscribers through a “push” mechanism, which implies that the receiving applications have to be present and running to receive the messages.</p>
 <p><strong>Amazon Kinesis data stream</strong> - Amazon Kinesis Data Streams enables you to build custom applications that process or analyze streaming data for specialized needs. You can continuously add various types of data such as clickstreams, application logs, and social media to an Amazon Kinesis data stream from hundreds of thousands of sources. Within seconds, the data will be available for your Amazon Kinesis Applications to read and process from the stream.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/amazon-mq/faqs/">https://aws.amazon.com/amazon-mq/faqs/</a></p>
</div>

**Question 6**

6. A company wants a fully managed, flexible, and scalable file storage system, with low latency access, for its Windows-based applications. Which AWS service is the right choice for the company?
*  A. Amazon FSx for Windows File Server
*  B. Amazon Elastic File System (Amazon EFS)
*  C. Amazon Elastic Block Storage (Amazon EBS)
*  D. Amazon FSx for Lustre

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option: <strong>Amazon FSx for Windows File Server</strong> - Amazon FSx for Windows File Server provides fully managed, highly reliable, and scalable file storage that is accessible over the industry-standard Service Message Block (SMB) protocol. It is built on Windows Server, delivering a wide range of administrative features such as user quotas, end-user file restore, and Microsoft Active Directory (AD) integration.</p>
 <p>To support a wide spectrum of workloads, Amazon FSx provides high levels of throughput, IOPS and consistent sub-millisecond latencies. Amazon FSx is accessible from Windows, Linux, and macOS compute instances and devices.</p>
 <p>For Windows-based applications, Amazon FSx provides fully managed Windows file servers with features and performance optimized for "lift-and-shift" business-critical application workloads including home directories (user shares), media workflows, and ERP applications. It is accessible from Windows and Linux instances via the SMB protocol.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Elastic File System (Amazon EFS)</strong> - Amazon EFS is a cloud-native fully managed file system that provides simple, scalable, elastic file storage accessible from Linux instances via the NFS protocol.</p>
 <p><strong>Amazon FSx for Lustre</strong> - For compute-intensive and fast processing workloads, like high-performance computing (HPC), machine learning, EDA, and media processing, Amazon FSx for Lustre, provides a file system that’s optimized for performance, with input and output stored on Amazon S3. FSx for Lustre is only compatible with Linux.</p>
 <p><strong>Amazon Elastic Block Storage (Amazon EBS)</strong> - Amazon EBS is an easy-to-use, high-performance, block-storage service designed for use with Amazon EC2 instances. It is a block-storage service and not a file storage service.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/fsx/windows/">https://aws.amazon.com/fsx/windows/</a></p>
</div>

**Question 7**

7. Which AWS service would you use to send alerts when the costs for your AWS account exceed your budgeted amount?
*  A. AWS Budgets
*  B. AWS Cost Explorer
*  C. AWS Organizations
*  D. AWS Pricing Calculator

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Budgets</strong></p>
 <p>AWS Budgets gives the ability to set custom budgets that alert you when your costs or usage exceed (or are forecasted to exceed) your budgeted amount. You can also use AWS Budgets to set reservation utilization or coverage targets and receive alerts when your utilization drops below the threshold you define. Budgets can be created at the monthly, quarterly, or yearly level, and you can customize the start and end dates. You can further refine your budget to track costs associated with multiple dimensions, such as AWS service, linked account, tag, and others. Budget alerts can be sent via email and/or Amazon Simple Notification Service (SNS) topic.</p>
 <p>AWS Budgets Overview: <img src="./images/pt2-q37-i1.jpg"> via - <a href="https://aws.amazon.com/aws-cost-management/aws-budgets/">https://aws.amazon.com/aws-cost-management/aws-budgets/</a></p>
 <p>Exam Alert:</p>
 <p>It is useful to note the difference between CloudWatch Billing vs Budgets:</p>
 <p>CloudWatch Billing Alarms: Sends an alarm when the actual cost exceeds a certain threshold.</p>
 <p>Budgets: Sends an alarm when the actual cost exceeds the budgeted amount or even when the cost forecast exceeds the budgeted amount.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Cost Explorer</strong> - AWS Cost Explorer has an easy-to-use interface that lets you visualize, understand, and manage your AWS costs and usage over time. AWS Cost Explorer includes a default report that helps you visualize the costs and usage associated with your top five cost-accruing AWS services, and gives you a detailed breakdown on all services in the table view. The reports let you adjust the time range to view historical data going back up to twelve months to gain an understanding of your cost trends.</p>
 <p>AWS Cost Explorer Reports: <img src="./images/pt2-q37-i2.jpg"> via - <a href="https://aws.amazon.com/aws-cost-management/aws-cost-explorer/">https://aws.amazon.com/aws-cost-management/aws-cost-explorer/</a></p>
 <p>Exam Alert:</p>
 <p>Watch out for questions on AWS Cost Explorer vs AWS Budgets. AWS Budgets can alert you when your costs exceed your budgeted amount. Cost Explorer helps you visualize and manage your AWS costs and usage over time.</p>
 <p><strong>AWS Organizations</strong> - AWS Organizations helps you centrally govern your environment as you grow and scale your workloads on AWS. Whether you are a growing startup or a large enterprise, Organizations helps you to centrally manage billing; control access, compliance, and security; and share resources across your AWS accounts.</p>
 <p><strong>AWS Pricing Calculator</strong> - AWS Pricing Calculator lets you explore AWS services and create an estimate for the cost of your use cases on AWS. You can model your solutions before building them, explore the price points and calculations behind your estimate, and find the available instance types and contract terms that meet your needs. This enables you to make informed decisions about using AWS. You can plan your AWS costs and usage or price out setting up a new set of instances and services. AWS Pricing Calculator can be accessed at <a href="https://calculator.aws/#/">https://calculator.aws/#/</a>.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/aws-cost-management/aws-budgets/">https://aws.amazon.com/aws-cost-management/aws-budgets/</a></p>
</div>

**Question 8**

8. A social media company wants to protect its web application from common web exploits such as SQL injection and cross-site scripting. Which of the following AWS services can be used to address this use-case?
*  A. Amazon GuardDuty
*  B. AWS CloudWatch
*  C. AWS Web Application Firewall (WAF)
*  D. Amazon Inspector

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Web Application Firewall (WAF)</strong></p>
 <p>AWS WAF is a web application firewall that helps protect your web applications or APIs against common web exploits that may affect availability, compromise security, or consume excessive resources. AWS WAF gives you control over how traffic reaches your applications by enabling you to create security rules that block common attack patterns such as SQL injection or cross-site scripting. You can also use rate-based rules to mitigate the Web layer DDoS attack.</p>
 <p>How WAF Works: <img src="./images/product-page-diagram_AWS-WAF_How-it-Works@2x.452efa12b06cb5c87f07550286a771e20ca430b9.png"> via - <a href="https://aws.amazon.com/waf/">https://aws.amazon.com/waf/</a></p>
 <p>An SQL injection attack works by exploiting any one of the known SQL vulnerabilities that allow the SQL server to run malicious code. For example, if a SQL server is vulnerable to an injection attack, it may be possible for an attacker to go to a website's search box and type in code that would force the site's SQL server to dump all of its stored usernames and passwords for the site.</p>
 <p>Similar to an SQL injection attack, a cross-site scripting attack also involves injecting malicious code into a website, but in this case, the website itself is not being attacked. Instead, the malicious code the attacker has injected only runs in the user's browser when they visit the attacked website, and it goes after the visitor directly, not the website.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon GuardDuty</strong></p>
 <p>GuardDuty is a threat detection service that monitors malicious activity and unauthorized behavior to protect your AWS account. GuardDuty analyzes billions of events across your AWS accounts from AWS CloudTrail (AWS user and API activity in your accounts), Amazon VPC Flow Logs (network traffic data), and DNS Logs (name query patterns). GuardDuty cannot be used to protect from web exploits such as SQL injection and cross-site scripting.</p>
 <p>How GuardDuty Works: <img src="./images/product-page-diagram-Amazon-GuardDuty_how-it-works.4370200b49eddc34d3a55c52c584484ceb2d532b.png"> via - <a href="https://aws.amazon.com/guardduty/">https://aws.amazon.com/guardduty/</a></p>
 <p><strong>Amazon Inspector</strong> - Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. Amazon Inspector automatically assesses applications for exposure, vulnerabilities, and deviations from best practices. Amazon Inspector cannot be used to protect from web exploits such as SQL injection and cross-site scripting.</p>
 <p><strong>Amazon CloudWatch</strong> - Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers. CloudWatch provides data and actionable insights to monitor applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health. This is an excellent service for building Resilient systems. Think resource performance monitoring, events, and alerts; think CloudWatch. CloudWatch cannot be used to protect from web exploits such as SQL injection and cross-site scripting.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/waf/">https://aws.amazon.com/waf/</a></p>
</div>

**Question 9**

9. An IT company wants to run a log backup process every Monday at 2 AM. The usual runtime of the process is 5 minutes. As a Cloud Practitioner, which AWS services would you recommend to build a serverless solution for this use-case? (Select two)
*  A. Systems Manager
*  B. Lambda
*  C. CloudWatch
*  D. EC2 Instance
*  E. Step Function

**Answer** B, C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>CloudWatch</strong> - Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers. CloudWatch provides data and actionable insights to monitor applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health.</p>
 <p><strong>Lambda</strong> - AWS Lambda lets you run code without provisioning or managing servers. You pay only for the compute time you consume. The lambda has a maximum execution time of 15 minutes, so it can be used to run this log backup process.</p>
 <p>To build the solution for the given use-case, you can create a CloudWatch Events rule that triggers on a schedule via a cron expression. You can then set the Lambda as the target for this rule.</p>
 <p>Incorrect options:</p>
 <p><strong>Systems Manager</strong> - AWS Systems Manager gives you visibility and control of your infrastructure on AWS. Systems Manager provides a unified user interface so you can view operational data from multiple AWS services and allows you to automate operational tasks across your AWS resources. With Systems Manager, you can group resources, like Amazon EC2 instances, Amazon S3 buckets, or Amazon RDS instances, by application, view operational data for monitoring and troubleshooting, and take action on your groups of resources. Secrets Manager cannot be used to run a process on a schedule.</p>
 <p><strong>EC2 Instance</strong> - Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud with support for per-second billing. It is the easiest way to provision servers on AWS Cloud and access the underlying OS. As the company wants a serverless solution, so this option is ruled out.</p>
 <p><strong>Step Function</strong> - AWS Step Function lets you coordinate multiple AWS services into serverless workflows. You can design and run workflows that stitch together services such as AWS Lambda, AWS Glue and Amazon SageMaker. Step Function cannot be used to run a process on a schedule.</p>
 <p>Reference:</p>
 <p><a href="https://wa.aws.amazon.com/wat.concepts.wa-concepts.en.html">https://wa.aws.amazon.com/wat.concepts.wa-concepts.en.html</a></p>
</div>

**Question 10**

10. An online gaming company wants to block users from certain geographies from accessing its content. Which AWS services can be used to accomplish this task? (Select two)
*  A. CloudWatch
*  B. AWS Shield
*  C. AWS Protect
*  D. AWS WAF
*  E. Route 53

**Answer** D, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>AWS WAF</strong></p>
 <p>AWS WAF is a web application firewall that helps protect web applications from attacks by allowing you to configure rules that allow, block, or monitor (count) web requests based on conditions that you define. These conditions include IP addresses, HTTP headers, HTTP body, URI strings, SQL injection, and cross-site scripting. You can use the IP address based match rule to block specific geographies. The accuracy of the IP Address to country lookup database varies by Region. Based on recent tests, AWS mentions that the overall accuracy for the IP address to country mapping is 99.8%.</p>
 <p>How WAF Works: <img src="./images/product-page-diagram_AWS-WAF_How-it-Works@2x.452efa12b06cb5c87f07550286a771e20ca430b9.png"> via - <a href="https://aws.amazon.com/waf/">https://aws.amazon.com/waf/</a></p>
 <p><strong>Route 53</strong></p>
 <p>Route 53 is Amazon's Domain Name System (DNS) web service. You can use Route 53 geolocation routing policy to block certain geographies. When you use geolocation routing, you can localize your content and present some or all of your website in the language of your users. You can also use geolocation routing to restrict the distribution of content to only the locations in which you have distribution rights.</p>
 <p>Incorrect options:</p>
 <p><strong>CloudWatch</strong> - Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers. CloudWatch provides data and actionable insights to monitor applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health. This is an excellent service for building Resilient systems. Think resource performance monitoring, events, and alerts; think CloudWatch. CloudWatch cannot be used to block users from certain geographies.</p>
 <p><strong>AWS Shield</strong> - AWS Shield is a managed Distributed Denial of Service (DDoS) protection service that safeguards applications running on AWS. AWS Shield provides always-on detection and automatic inline mitigations that minimize application downtime and latency, so there is no need to engage AWS Support to benefit from DDoS protection. AWS Shield cannot be used to block users from certain geographies.</p>
 <p><strong>AWS Protect</strong> - This is no such thing as AWS Protect and it has been added as a distractor.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/waf/faqs/">https://aws.amazon.com/waf/faqs/</a></p>
 <p><a href="https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html">https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html</a></p>
</div>

**Question 11**

11. Which of the following AWS services allows a database to have flexible schema and supports document data models?
*  A. Amazon Redshift
*  B. Amazon RDS for PostgreSQL
*  C. Amazon Aurora
*  D. Amazon DynamoDB

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon DynamoDB</strong></p>
 <p>Amazon DynamoDB is a NoSQL database that supports key-value and document data models and enables developers to build modern, serverless applications that can start small and scale globally to support petabytes of data and tens of millions of read and write requests per second. DynamoDB supports both key-value and document data models. This enables DynamoDB to have a flexible schema, so each row can have any number of columns at any point in time. This allows you to easily adapt the tables as your business requirements change, without having to redefine the table schema as you would in relational databases.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon RDS for PostgreSQL</strong> - Amazon RDS for PostgreSQL is an AWS service for relational databases. Schema change on a relational database is not easy and straight-forward as it is on a NoSQL database. RDS for PostgreSQL does not support flexible schema.</p>
 <p><strong>Amazon Redshift</strong> - Amazon Redshift is a fully-managed petabyte-scale cloud-based data warehouse product designed for large scale data set storage and analysis. Amazon Redshift does not support flexible schema.</p>
 <p><strong>Amazon Aurora</strong> - Amazon Aurora is an AWS service for relational databases. Schema change on a relational database is not easy and straight-forward as it is on a NoSQL database. Aurora does not support flexible schema.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/dynamodb/features/">https://aws.amazon.com/dynamodb/features/</a></p>
</div>

**Question 12**

12. As per the AWS shared responsibility model, which of the following is a responsibility of AWS from a security and compliance point of view?
*  A. Server-side Encryption
*  B. Edge Location Management
*  C. Customer Data
*  D. Identity and Access Management

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Edge Location Management</strong></p>
 <p>Security and Compliance is a shared responsibility between AWS and the customer. This shared model can help relieve the customer’s operational burden as AWS operates, manages, and controls the components from the host operating system and virtualization layer down to the physical security of the facilities in which the service operates.</p>
 <p>AWS is responsible for security "of" the cloud. This covers their global infrastructure elements including Regions, Availability Zones, and Edge Locations.</p>
 <p>Incorrect options:</p>
 <p><strong>Customer Data</strong></p>
 <p><strong>Identity and Access Management</strong></p>
 <p><strong>Server-side Encryption</strong></p>
 <p>The customer is responsible for security "in" the cloud. Customers are responsible for managing their data including encryption options and using Identity and Access Management tools for implementing appropriate access control policies as per their organization requirements. For abstracted services, such as Amazon S3 and Amazon DynamoDB, AWS operates the infrastructure layer, the operating system, and platforms, and customers access the endpoints to store and retrieve data. Therefore, these three options fall under the responsibility of the customer according to the AWS shared responsibility model.</p>
 <p>Exam Alert:</p>
 <p>Please review the Shared Responsibility Model in detail as you can expect multiple questions on the shared responsibility model in the exam: <img src="./images/Shared_Responsibility_Model_V2.59d1eccec334b366627e9295b304202faf7b899b.jpg"> via - <a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
</div>

**Question 13**

13. The AWS Well-Architected Framework provides guidance on building cloud based applications using AWS best practices. Which of the following options are the pillars mentioned in the AWS Well-Architected Framework? (Select two)
*  A. Elasticity
*  B. Availability
*  C. Cost Optimization
*  D. Reliability
*  E. Scalability

**Answer** C, D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Reliability</strong></p>
 <p><strong>Cost Optimization</strong></p>
 <p>The Well-Architected Framework provides guidance on building secure, high-performing, resilient, and efficient infrastructure for cloud based applications. Based on six pillars — operational excellence, security, reliability, performance efficiency, cost optimization and sustainability — the Framework provides a consistent approach for customers and partners to evaluate architectures, and implement designs that will scale over time.</p>
 <p>Incorrect options:</p>
 <p><strong>Elasticity</strong> - Elasticity is the ability to acquire resources as you need them and release resources when you no longer need them. In the cloud, you want to do this automatically.</p>
 <p><strong>Availability</strong> - A system that is available is capable of delivering the designed functionality at a given point in time. Highly available systems are those that can withstand some measure of degradation while still remaining available.</p>
 <p><strong>Scalability</strong> - A measurement of a system's ability to grow to accommodate an increase in demand.</p>
 <p>These three options are not part of the AWS Well-Architected Framework.</p>
 <p>Reference:</p>
 <p><a href="https://d1.awsstatic.com/whitepapers/architecture/AWS_Well-Architected_Framework.pdf">https://d1.awsstatic.com/whitepapers/architecture/AWS_Well-Architected_Framework.pdf</a></p>
</div>

**Question 14**

14. Which of the following AWS services are global in scope? (Select two)
*  A. Amazon Elastic Compute Cloud (Amazon EC2)
*  B. Amazon S3
*  C. AWS Identity and Access Management (IAM)
*  D. Amazon Relational Database Service (Amazon RDS)
*  E. Amazon CloudFront

**Answer** C, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>AWS Identity and Access Management (IAM)</strong></p>
 <p><strong>Amazon CloudFront</strong></p>
 <p>Most of the services that AWS offers are Region specific. But few services, by definition, need to be in a global scope because of the underlying service they offer. AWS IAM, Amazon CloudFront, Route 53 and WAF are some of the global services.</p>
 <p>AWS Identity and Access Management (IAM) enables you to manage access to AWS services and resources securely. Using IAM, you can create and manage AWS users and groups, and use permissions to allow and deny their access to AWS resources.</p>
 <p>Amazon CloudFront is a fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency, high transfer speeds, all within a developer-friendly environment.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Relational Database Service (Amazon RDS)</strong> - Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a relational database in the cloud. This is a regional service.</p>
 <p><strong>Amazon Elastic Compute Cloud (Amazon EC2)</strong> - Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud. It comes under Infrastructure as a Service type of Cloud Computing. This is a regional service.</p>
 <p>Exam Alert:</p>
 <p><strong>Amazon S3</strong> - Amazon S3 is a unique service in the sense that it follows a global namespace but the buckets are regional. You specify an AWS Region when you create your Amazon S3 bucket. This is a regional service.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/iam/faqs/">https://aws.amazon.com/iam/faqs/</a></p>
 <p><a href="https://aws.amazon.com/cloudfront/faqs/">https://aws.amazon.com/cloudfront/faqs/</a></p>
</div>

**Question 15**

15. Which AWS service publishes up-to-the-minute information on the general status and availability of all AWS services in all the Regions of AWS Cloud?
*  A. Amazon CloudWatch
*  B. AWS Personal Health Dashboard
*  C. AWS Service Health Dashboard
*  D. AWS CloudFormation

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option: <strong>AWS Service Health Dashboard</strong></p>
 <p>AWS Service Health Dashboard publishes most up-to-the-minute information on the status and availability of all AWS services in tabular form for all Regions that AWS is present in. You can check on this page <a href="https://status.aws.amazon.com/">https://status.aws.amazon.com/</a> to get current status information.</p>
 <p>AWS Service Health Dashboard Overview: <img src="./images/pt2-q6-i1.jpg"> via - <a href="https://status.aws.amazon.com/">https://status.aws.amazon.com/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS CloudFormation</strong> - AWS CloudFormation allows you to use programming languages or a simple text file to model and provision, in an automated and secure manner, all the resources needed for your applications across all Regions and accounts. Think infrastructure as code; think CloudFormation. CloudFormation does not provide the general status of AWS services availability for all Regions.</p>
 <p><strong>AWS Personal Health Dashboard</strong> - AWS Personal Health Dashboard provides alerts and remediation guidance when AWS is experiencing events that may impact you.</p>
 <p>AWS Personal Health Dashboard Overview: <img src="./images/pt2-q6-i2.jpg"> via - <a href="https://status.aws.amazon.com/">https://status.aws.amazon.com/</a></p>
 <p>Exam Alert:</p>
 <p>While the Service Health Dashboard displays the general status of AWS services, Personal Health Dashboard gives you a personalized view of the performance and availability of the AWS services underlying your AWS resources.</p>
 <p><strong>Amazon CloudWatch</strong> - Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers. CloudWatch provides data and actionable insights to monitor applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health. This is an excellent service for building Resilient systems. Think resource performance monitoring, events, and alerts; think CloudWatch. CloudWatch does not provide the general status of AWS services availability for all Regions.</p>
 <p>Reference:</p>
 <p><a href="https://status.aws.amazon.com/">https://status.aws.amazon.com/</a></p>
</div>

**Question 16**

16. Which service gives a personalized view of the status of the AWS services that are part of your Cloud architecture so that you can quickly assess the impact on your business when AWS service(s) are experiencing issues?
*  A. AWS Inspector
*  B. Amazon CloudWatch
*  C. AWS Service Health Dashboard
*  D. AWS Personal Health Dashboard

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option: <strong>AWS Personal Health Dashboard</strong></p>
 <p>AWS Personal Health Dashboard provides alerts and remediation guidance when AWS is experiencing events that may impact you. With Personal Health Dashboard, alerts are triggered by changes in the health of your AWS resources, giving you event visibility, and guidance to help quickly diagnose and resolve issues.</p>
 <p>AWS Personal Health Dashboard Overview: <img src="./images/pt2-q18-i1.jpg"> via - <a href="https://status.aws.amazon.com/">https://status.aws.amazon.com/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Inspector</strong> - Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. Amazon Inspector automatically assesses applications for exposure, vulnerabilities, and deviations from best practices. Amazon Inspector cannot be used to prevent Distributed Denial-of-Service (DDoS) attack. It cannot provide the status of your AWS resources.</p>
 <p><strong>Amazon CloudWatch</strong> - Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers. CloudWatch provides data and actionable insights to monitor applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health. This is an excellent service for building Resilient systems. Think resource performance monitoring, events, and alerts; think CloudWatch. It cannot provide the status of your AWS resources.</p>
 <p><strong>AWS Service Health Dashboard</strong> - AWS Service Health Dashboard publishes most up-to-the-minute information on the status and availability of all AWS services in tabular form for all Regions that AWS is present in. You can check on this page (https://status.aws.amazon.com/) any time to get current status information or subscribe to an RSS feed to be notified of interruptions to each service.</p>
 <p>AWS Service Health Dashboard Overview: <img src="./images/pt2-q18-i2.jpg"> via - <a href="https://status.aws.amazon.com/">https://status.aws.amazon.com/</a></p>
 <p>Exam Alert:</p>
 <p>While the Service Health Dashboard displays the general status of AWS services, Personal Health Dashboard gives you a personalized view of the performance and availability of the AWS services underlying your AWS resources.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/premiumsupport/technology/personal-health-dashboard/">https://aws.amazon.com/premiumsupport/technology/personal-health-dashboard/</a></p>
</div>

**Question 17**

17. Which AWS service should be used when you want to run container applications, but want to avoid the operational overhead of scaling, patching, securing, and managing servers?
*  A. Amazon Elastic Container Service - EC2 launch type
*  B. Amazon Elastic Container Service - Fargate launch type
*  C. Amazon Elastic Compute Cloud (Amazon EC2)
*  D. AWS Lambda

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon Elastic Container Service - Fargate launch type</strong></p>
 <p>AWS Fargate is a serverless compute engine for containers. It works with both Amazon Elastic Container Service (ECS) and Amazon Elastic Kubernetes Service (EKS). Fargate makes it easy for you to focus on building your applications. Fargate removes the need to provision and manage servers, lets you specify and pay for resources per application, and improves security through application isolation by design. Fargate allocates the right amount of compute, eliminating the need to choose instances and scale cluster capacity. You only pay for the resources required to run your containers, so there is no over-provisioning and paying for additional servers. Fargate runs each task or pod in its kernel providing the tasks and pods their own isolated compute environment. This enables your application to have workload isolation and improved security by design.</p>
 <p>How Fargate Works: <img src="./images/Product-Page-Diagram_Fargate@2x.a20fb2b15c2aebeda3a44dbbb0b10b82fb89aa6a.png"> via - <a href="https://aws.amazon.com/fargate/">https://aws.amazon.com/fargate/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Elastic Container Service - EC2 launch type</strong> - Amazon Elastic Container Service (Amazon ECS) is a highly scalable, fast, container management service that makes it easy to run, stop, and manage Docker containers and allows you to easily run applications on a managed cluster of Amazon EC2 instances. Unlike Fargate, this is not a fully managed service and you need to manage the underlying servers yourself.</p>
 <p><strong>AWS Lambda</strong> - AWS Lambda is a compute service that lets you run code without provisioning or managing servers. AWS Lambda executes your code only when needed and scales automatically, from a few requests per day to thousands per second. Lambda does not support running container applications.</p>
 <p><strong>Amazon Elastic Compute Cloud (Amazon EC2)</strong> - Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud, per-second billing, and access to the underlying OS. It is designed to make web-scale cloud computing easier for developers. Maintenance of the server and its software has to be done by the customer, so this option is ruled out.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/fargate/">https://aws.amazon.com/fargate/</a></p>
</div>

**Question 18**

18. A multi-national company wants to migrate its IT infrastructure to AWS Cloud and is looking for a concierge support team as well as a response time of around an hour in case the systems go down. As a Cloud Practitioner, which of the following support plans would you recommend to the company?
*  A. Enterprise
*  B. Individual
*  C. Business
*  D. Developer

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Enterprise</strong></p>
 <p>The Concierge Support Team is only available for the Enterprise Support plan. The Concierge Team are AWS billing and account experts that specialize in working with enterprise accounts. They will quickly and efficiently assist you with your billing and account inquiries. Enterprise Support plan provides a response time of fewer than 15 minutes for business-critical systems and provides a response time of less than an hour for production systems related outage. So this is the correct option.</p>
 <p>Exam Alert:</p>
 <p>Please review the differences between the Developer, Business, and Enterprise support plans as you can expect at least a couple of questions on the exam:</p>
 <p><img src="./images/pt2-q35-i1.jpg"></p>
 <p><img src="./images/pt2-q35-i2.jpg"></p>
 <p>via - <a href="https://aws.amazon.com/premiumsupport/plans/">https://aws.amazon.com/premiumsupport/plans/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Developer</strong> - Concierge Support Team is only available for Enterprise Support plan so this option is incorrect.</p>
 <p><strong>Business</strong> - Concierge Support Team is only available for Enterprise Support plan so this option is incorrect.</p>
 <p><strong>Individual</strong> - This is a made-up option and has been added as a distractor.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/premiumsupport/plans/">https://aws.amazon.com/premiumsupport/plans/</a></p>
</div>

**Question 19**

19. Which policy describes prohibited uses of the web services offered by Amazon Web Services?
*  A. AWS Applicable Use Policy
*  B. AWS Acceptable Use Policy
*  C. AWS Fair Use Policy
*  D. AWS Trusted Advisor

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Acceptable Use Policy</strong></p>
 <p>The Acceptable Use Policy describes prohibited uses of the web services offered by Amazon Web Services, Inc. and its affiliates (the “Services”) and the website located at http://aws.amazon.com (the “AWS Site”). This policy is present at https://aws.amazon.com/aup/ and is updated on a need basis by AWS.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Trusted Advisor</strong> - AWS Trusted Advisor is an online tool that provides you real-time guidance to help you provision your resources following AWS best practices on cost optimization, security, fault tolerance, service limits, and performance improvement. Whether establishing new workflows, developing applications, or as part of ongoing improvement, recommendations provided by Trusted Advisor regularly help keep your solutions provisioned optimally. Trusted Advisor does not describe prohibited uses of the web services offered by Amazon Web Services.</p>
 <p><strong>AWS Fair Use Policy</strong> - This is a made-up option and has been added as a distractor.</p>
 <p><strong>AWS Applicable Use Policy</strong> - This is a made-up option and has been added as a distractor.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/aup/">https://aws.amazon.com/aup/</a></p>
</div>

**Question 20**

20. A customer has created a VPC and a subnet within AWS Cloud. Which of the following statements is correct?
*  A. Both the VPC and the subnet span only one Availability Zone in the Region
*  B. Both the VPC and the subnet span all of the Availability Zones in the Region
*  C. A VPC spans all of the Availability Zones in the Region whereas a subnet spans only one Availability Zone in the Region
*  D. A subnet spans all of the Availability Zones in the Region whereas a VPC spans only one Availability Zone in the Region

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>A VPC spans all of the Availability Zones in the Region whereas a subnet spans only one Availability Zone in the Region</strong></p>
 <p>Amazon Virtual Private Cloud (Amazon VPC) is a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define. You have complete control over your virtual networking environment, including the selection of your IP address range, creation of subnets, and configuration of route tables and network gateways. A VPC spans all of the Availability Zones in the Region.</p>
 <p>A subnet is a range of IP addresses within your VPC. A subnet spans only one Availability Zone in the Region.</p>
 <p>VPC and Subnet Overview: <img src="./images/pt2-q49-i1.jpg"> via - <a href="https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html">https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Both the VPC and the subnet span all of the Availability Zones in the Region</strong></p>
 <p><strong>Both the VPC and the subnet span only one Availability Zone in the Region</strong></p>
 <p><strong>A subnet spans all of the Availability Zones in the Region whereas a VPC spans only one Availability Zone in the Region</strong></p>
 <p>These three options contradict the details provided earlier in the explanation, so these options are incorrect.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html">https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html</a></p>
</div>

**Question 21**

21. Which AWS EC2 pricing model is the most cost-effective and flexible with no requirement for a long term resource commitment or upfront payment but still guarantees that instance would not be interrupted?
*  A. Reserved Instances
*  B. Dedicated Hosts
*  C. Spot Instances
*  D. On-demand Instances

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>On-Demand Instances</strong> - An On-Demand Instance is an instance that you use on-demand. You have full control over its lifecycle — you decide when to launch, stop, hibernate, start, reboot, or terminate it. There is no long-term commitment required when you purchase On-Demand Instances. There is no upfront payment and you pay only for the seconds that your On-Demand Instances are running. The price per second for running an On-Demand Instance is fixed. On-demand instances cannot be interrupted.</p>
 <p>EC2 Pricing Options Overview: <img src="./images/pt2-q31-i1.jpg"> via - <a href="https://aws.amazon.com/ec2/pricing/">https://aws.amazon.com/ec2/pricing/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Reserved Instances</strong> - Reserved Instances provide you with significant savings on your Amazon EC2 costs compared to On-Demand Instance pricing. Reserved Instances are not physical instances, but rather a billing discount applied to the use of On-Demand Instances in your account. You can purchase a Reserved Instance for a one-year or three-year commitment, with the three-year commitment offering a bigger discount. You will be charged for the entire duration, irrespective of your usage, so this option is not correct for running weekly workloads. So this option is not correct for the given use-case.</p>
 <p><strong>Spot Instances</strong> - A Spot Instance is an unused EC2 instance that is available for less than the On-Demand price. Because Spot Instances enable you to request unused EC2 instances at steep discounts, you can lower your Amazon EC2 costs significantly. Spot Instances are well-suited for data analysis, batch jobs, background processing, and optional tasks. These can be terminated at short notice, so these are not suitable for critical workloads that need to run at a specific point in time. So this option is not correct for the given use-case.</p>
 <p><strong>Dedicated Hosts</strong> - Amazon EC2 Dedicated Hosts allow you to use your eligible software licenses from vendors such as Microsoft and Oracle on Amazon EC2 so that you get the flexibility and cost-effectiveness of using your licenses, but with the resiliency, simplicity, and elasticity of AWS. An Amazon EC2 Dedicated Host is a physical server fully dedicated for your use, so you can help address corporate compliance requirement. They're not cost-efficient compared to On-Demand instances. So this option is not correct.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/ec2/pricing/">https://aws.amazon.com/ec2/pricing/</a></p>
</div>

**Question 22**

22. An e-commerce company wants to assess its applications deployed on EC2 instances for vulnerabilities and deviations from AWS best practices. Which AWS service can be used to facilitate this?
*  A. AWS Secrets Manager
*  B. AWS Trusted Advisor
*  C. AWS CloudHSM
*  D. Amazon Inspector

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon Inspector</strong></p>
 <p>Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. Amazon Inspector automatically assesses applications for exposure, vulnerabilities, and deviations from best practices.</p>
 <p>Overview of Amazon Inspector: <img src="./images/pt2-q28-i1.jpg"> via - <a href="https://aws.amazon.com/inspector/">https://aws.amazon.com/inspector/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS Secrets Manager</strong> - AWS Secrets Manager helps you protect secrets needed to access your applications, services, and IT resources. The service enables you to easily rotate, manage, and retrieve database credentials, API keys, and other secrets throughout their lifecycle. Users and applications retrieve secrets with a call to Secrets Manager APIs, eliminating the need to hardcode sensitive information in plain text. Secrets Manager cannot be used for security assessment of applications deployed on AWS.</p>
 <p><strong>AWS CloudHSM</strong> - AWS CloudHSM is a cloud-based hardware security module (HSM) that enables you to easily generate and use your encryption keys on the AWS Cloud. With CloudHSM, you can manage your encryption keys using FIPS 140-2 Level 3 validated HSMs. It is a fully-managed service that automates time-consuming administrative tasks for you, such as hardware provisioning, software patching, high-availability, and backups. CloudHSM cannot be used for the security assessment of applications deployed on AWS.</p>
 <p><strong>AWS Trusted Advisor</strong> - AWS Trusted Advisor is an online tool that provides you real-time guidance to help you provision your resources following AWS best practices on cost optimization, security, fault tolerance, service limits, and performance improvement. Whether establishing new workflows, developing applications, or as part of ongoing improvement, recommendations provided by Trusted Advisor regularly help keep your solutions provisioned optimally. Trusted Advisor cannot be used for assessing vulnerabilities for applications deployed on AWS.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/inspector/">https://aws.amazon.com/inspector/</a></p>
</div>

**Question 23**

23. Which AWS support plan provides access to a Technical Account Manager (TAM)?
*  A. Enterprise
*  B. Developer
*  C. Business
*  D. Business & Enterprise

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p>"Enterprise"</p>
 <p>AWS offers three different support plans to cater to each of its customers - Developer, Business, and Enterprise Support plans. A basic support plan is included for all AWS customers.</p>
 <p>AWS Enterprise Support provides customers with concierge-like service where the main focus is helping the customer achieve their outcomes and find success in the cloud. With Enterprise Support, you get 24x7 technical support from high-quality engineers, tools and technology to automatically manage the health of your environment, consultative architectural guidance delivered in the context of your applications and use-cases, and a designated Technical Account Manager (TAM) to coordinate access to proactive/preventative programs and AWS subject matter experts.</p>
 <p>Exam Alert:</p>
 <p>Please review the differences between the Developer, Business, and Enterprise support plans as you can expect at least a couple of questions on the exam:</p>
 <p><img src="./images/pt2-q33-i1.jpg"></p>
 <p><img src="./images/pt2-q33-i2.jpg"></p>
 <p>via - <a href="https://aws.amazon.com/premiumsupport/plans/">https://aws.amazon.com/premiumsupport/plans/</a></p>
 <p>Incorrect options:</p>
 <p>"Developer" - AWS recommends Developer Support if you are testing or doing early development on AWS and want the ability to get technical support during business hours as well as general architectural guidance as you build and test.</p>
 <p>"Business" - AWS recommends Business Support if you have production workloads on AWS and want 24x7 access to technical support and architectural guidance in the context of your specific use-cases.</p>
 <p>"Business &amp; Enterprise" - This is an invalid option and has been added as a distractor. An Enterprise plan will include all the facilities offered by Developer and Business Support plans already.</p>
 <p>Reference: https://aws.amazon.com/premiumsupport/plans/enterprise/</p>
</div>

**Question 24**

24. An organization has a complex IT architecture involving a lot of system dependencies and it wants to track the history of changes to each resource. Which AWS service will help the organization track the history of configuration changes for all the resources?
*  A. AWS Service Catalog
*  B. AWS CloudTrail
*  C. AWS CloudFormation
*  D. AWS Config

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Config</strong></p>
 <p>AWS Config is a service that enables you to assess, audit, and evaluate the configurations of your AWS resources. Config continuously monitors and records your AWS resource configurations and allows you to automate the evaluation of recorded configurations against desired configurations. Think resource-specific history, audit, and compliance; think Config.</p>
 <p>With AWS Config, you can do the following: 1. Evaluate your AWS resource configurations for desired settings. 2. Get a snapshot of the current configurations of the supported resources that are associated with your AWS account. 3. Retrieve configurations of one or more resources that exist in your account. 4. Retrieve historical configurations of one or more resources. 5. Receive a notification whenever a resource is created, modified, or deleted. 6.View relationships between resources. For example, you might want to find all resources that use a particular security group.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Service Catalog</strong> - AWS Service Catalog allows organizations to create and manage catalogs of IT services that are approved for use on AWS. These IT services can include everything from virtual machine images, servers, software, and databases to complete multi-tier application architectures. You cannot use Service Catalog to track changes to each resource on AWS.</p>
 <p><strong>AWS CloudFormation</strong> - AWS CloudFormation provides a common language to model and provision AWS and third-party application resources in your cloud environment. AWS CloudFormation allows you to use programming languages or a simple text file to model and provision, in an automated and secure manner, all the resources needed for your applications across all Regions and accounts. Think infrastructure as code; think CloudFormation. You cannot use CloudFormation to track changes to each resource on AWS.</p>
 <p><strong>AWS CloudTrail</strong> - AWS CloudTrail is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account. With CloudTrail, you can log, continuously monitor, and retain account activity related to actions across your AWS infrastructure. CloudTrail provides the event history of your AWS account activity, including actions taken through the AWS Management Console, AWS SDKs, command-line tools, and other AWS services. Think account-specific activity and audit; think CloudTrail. You cannot use CloudTrail to track changes to each resource on AWS.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/config/latest/developerguide/WhatIsConfig.html">https://docs.aws.amazon.com/config/latest/developerguide/WhatIsConfig.html</a></p>
</div>

**Question 25**

25. An organization is planning to move its infrastructure from the on-premises datacenter to AWS Cloud. As a Cloud Practioner, which options would you recommend so that the organization can identify the right AWS services to build solutions on AWS Cloud (Select two)?
*  A. AWS Organizations
*  B. AWS Service Catalog
*  C. AWS Partner Network
*  D. Amazon CloudWatch
*  E. AWS CloudTrail

**Answer** B, C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>AWS Service Catalog</strong> - AWS Service Catalog allows organizations to create and manage catalogs of IT services that are approved for use on AWS. These IT services can include everything from virtual machine images, servers, software, and databases to complete multi-tier application architectures.</p>
 <p><strong>AWS Partner Network</strong> - Organizations can take help from the AWS Partner Network (APN) to identify the right AWS services to build solutions on AWS Cloud. APN is the global partner program for technology and consulting businesses that leverage Amazon Web Services to build solutions and services for customers.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Organizations</strong> - AWS Organizations helps you centrally govern your environment as you grow and scale your workloads on AWS. Organizations help you to centrally manage billing; control access, compliance, and security; and share resources across your AWS accounts. AWS Organizations cannot help in identifying the right AWS services to build solutions on AWS Cloud.</p>
 <p><strong>Amazon CloudWatch</strong> - Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers. CloudWatch provides data and actionable insights to monitor your applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health. Think resource performance monitoring, events, and alerts; think CloudWatch. CloudWatch cannot help in identifying the right AWS services to build solutions on AWS Cloud.</p>
 <p><strong>AWS CloudTrail</strong> - AWS CloudTrail is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account. With CloudTrail, you can log, continuously monitor, and retain account activity related to actions across your AWS infrastructure. Think account-specific activity and audit; think CloudTrail. CloudTrail cannot help in identifying the right AWS services to build solutions on AWS Cloud.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/servicecatalog/">https://aws.amazon.com/servicecatalog/</a></p>
 <p><a href="https://aws.amazon.com/partners/">https://aws.amazon.com/partners/</a></p>
</div>

**Question 26**

26. Which of the following statements is INCORRECT about AWS Auto Scaling?
*  A. You can automatically register new instances to a Load Balancer
*  B. You can automatically deploy AWS Shield when a DDoS attack is detected
*  C. You can scale out and add more EC2 instances to match an increase in demand as well as scale in and remove EC2 instances to match a reduced demand
*  D. You can automatically remove unhealthy instances

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>You can automatically deploy AWS Shield when a DDoS attack is detected</strong></p>
 <p>AWS Auto Scaling is helpful during a DDoS attack, as it can scale out resources fast. But, it cannot automatically deploy AWS Shield service onto its group of resources.</p>
 <p>Incorrect options:</p>
 <p>AWS Auto Scaling monitors your applications and automatically adjusts the capacity to maintain steady, predictable performance at the lowest possible cost. Using AWS Auto Scaling, it’s easy to setup application scaling for multiple resources across multiple services in minutes. The service provides a simple, powerful user interface that lets you build scaling plans for resources including Amazon EC2 instances and Spot Fleets, Amazon ECS tasks, Amazon DynamoDB tables and indexes, and Amazon Aurora Replicas.</p>
 <p><strong>You can scale out and add more EC2 instances to match an increase in demand as well as scale in and remove EC2 instances to match a reduced demand</strong> - As explained above, it can scale out resources on-demand as well as scale in resources to match reduced demand.</p>
 <p><strong>You can automatically remove unhealthy instances</strong> - Based on health checks, Auto Scaling can remove unhealthy instances.</p>
 <p><strong>You can automatically register new instances to a Load Balancer</strong> - During a scale-out process, Auto scaling can spin up new instances and register them with the Load Balancer, also part of the Scaling group.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/autoscaling/">https://aws.amazon.com/autoscaling/</a></p>
</div>

**Question 27**

27. Which AWS technology/service helps you to scale your resources to match supply with demand while still keeping your cloud solution cost-effective?
*  A. AWS OpsWorks
*  B. AWS Cost Explorer
*  C. AWS CloudFormation
*  D. AWS Auto Scaling

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option: <strong>AWS Auto Scaling</strong></p>
 <p>AWS Auto Scaling monitors applications and automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost. Using AWS Auto Scaling, it’s easy to setup application scaling for multiple resources across multiple services in minutes. The service provides a simple, powerful user interface that lets you build scaling plans for resources including Amazon EC2 instances and Spot Fleets, Amazon ECS tasks, Amazon DynamoDB tables and indexes, and Amazon Aurora Replicas. AWS Auto Scaling makes scaling simple with recommendations that allow you to optimize performance, costs, or balance between them.</p>
 <p>How Auto Scaling Works: <img src="./images/aws-auto-scaling-how-it-works-diagram.d42779c774d634883bdcd0463de7bd86f6e2231d.png"> via - <a href="https://aws.amazon.com/autoscaling/">https://aws.amazon.com/autoscaling/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS Cost Explorer</strong> - AWS Cost Explorer lets you explore your AWS costs and usage at both a high level and at a detailed level of analysis, and empowering you to dive deeper using many filtering dimensions (e.g., AWS Service, Region, Linked Account). It's a handy tool to keep track of costs of AWS resources, but auto-scaling is not part of its feature set.</p>
 <p><strong>AWS OpsWorks</strong> - AWS OpsWorks is a configuration management service that provides managed instances of Chef and Puppet. Chef and Puppet are automation platforms that allow you to use code to automate the configurations of your servers. OpsWorks lets you use Chef and Puppet to automate how servers are configured, deployed and managed across your Amazon EC2 instances or on-premises compute environments. OpsWorks cannot auto-scale resources.</p>
 <p><strong>AWS CloudFormation</strong> - AWS CloudFormation allows you to use programming languages or a simple text file to model and provision, in an automated and secure manner, all the resources needed for your applications across all Regions and accounts. Think infrastructure as code; think CloudFormation. CloudFormation cannot auto-scale resources.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/autoscaling/">https://aws.amazon.com/autoscaling/</a></p>
 <p><a href="https://aws.amazon.com/aws-cost-management/aws-cost-explorer/">https://aws.amazon.com/aws-cost-management/aws-cost-explorer/</a></p>
 <p><a href="https://aws.amazon.com/opsworks/">https://aws.amazon.com/opsworks/</a></p>
 <p><a href="https://aws.amazon.com/cloudformation/">https://aws.amazon.com/cloudformation/</a></p>
</div>

**Question 28**

28. A gaming company is looking at a technology/service that can deliver a consistent low-latency gameplay to ensure a great user experience for end-users in various locations.
*  A. AWS Wavelength
*  B. AWS Local Zones
*  C. AWS Direct Connect
*  D. AWS Edge Locations

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Local Zones</strong></p>
 <p>AWS Local Zones allow you to use select AWS services, like compute and storage services, closer to more end-users, providing them very low latency access to the applications running locally. AWS Local Zones are also connected to the parent region via Amazon’s redundant and very high bandwidth private network, giving applications running in AWS Local Zones fast, secure, and seamless access to the rest of AWS services.</p>
 <p>You should use AWS Local Zones to deploy workloads closer to your end-users for low-latency requirements. AWS Local Zones have their connection to the internet and support AWS Direct Connect, so resources created in the Local Zone can serve local end-users with very low-latency communications.</p>
 <p>Various AWS services such as Amazon Elastic Compute Cloud (EC2), Amazon Virtual Private Cloud (VPC), Amazon Elastic Block Store (EBS), Amazon FSx, Amazon Elastic Load Balancing, Amazon EMR, Amazon ElastiCache, and Amazon Relational Database Service (RDS) are available locally in the AWS Local Zones. You can also use services that orchestrate or work with local services such as Amazon EC2 Auto Scaling, Amazon EKS clusters, Amazon ECS clusters, Amazon EC2 Systems Manager, Amazon CloudWatch, AWS CloudTrail, and AWS CloudFormation. AWS Local Zones also provide a high-bandwidth, secure connection to the AWS Region, allowing you to seamlessly connect to the full range of services in the AWS Region through the same APIs and toolsets.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Edge Locations</strong> - An AWS Edge location is a site that CloudFront uses to cache copies of the content for faster delivery to users at any location.</p>
 <p><strong>AWS Wavelength</strong> - AWS Wavelength extends the AWS cloud to a global network of 5G edge locations to enable developers to innovate and build a whole new class of applications that require ultra-low latency. Wavelength Zones provide a high-bandwidth, secure connection to the parent AWS Region, allowing developers to seamlessly connect to the full range of services in the AWS Region through the same APIs and toolsets.</p>
 <p><strong>AWS Direct Connect</strong> - AWS Direct Connect is a cloud service that links your network directly to AWS, bypassing the internet to deliver more consistent, lower-latency performance. When creating a new connection, you can choose a hosted connection provided by an AWS Direct Connect Delivery Partner, or choose a dedicated connection from AWS—and deploy at over 100 AWS Direct Connect locations around the world. AWS Direct Connect provides consistently high bandwidth, low-latency access and it is generally used between on-premises data centers and AWS network. Direct Connect is overkill for the given requirement.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/about-aws/global-infrastructure/localzones/">https://aws.amazon.com/about-aws/global-infrastructure/localzones/</a></p>
</div>

**Question 29**

29. Which of the following options can be used to access and manage all AWS services (Select three)?
*  A. AWS Software Developer Kit (SDK)
*  B. AWS Systems Manager
*  C. Amazon API Gateway
*  D. AWS Management Console
*  E. AWS Secrets Manager
*  F. AWS Command Line Interface (CLI)

**Answer** A, D, F

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p>AWS services can be accessed in three different ways:</p>
 <p><strong>AWS Management Console</strong> - This is a simple web interface for accessing AWS services.</p>
 <p><strong>AWS Command Line Interface (CLI)</strong> - You can access AWS services from the command line and automate service management with scripts.</p>
 <p><strong>AWS Software Developer Kit (SDK)</strong> - You can also access via AWS SDK that provides language-specific abstracted APIs for AWS services.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Systems Manager</strong> - AWS Systems Manager gives you visibility and control of your infrastructure on AWS. Systems Manager provides a unified user interface so you can view operational data from multiple AWS services and allows you to automate operational tasks across your AWS resources. With Systems Manager, you can group resources, like Amazon EC2 instances, Amazon S3 buckets, or Amazon RDS instances, by application, view operational data for monitoring and troubleshooting, and take action on your groups of resources.</p>
 <p><strong>AWS Secrets Manager</strong> - AWS Secrets Manager helps you protect secrets needed to access your applications, services, and IT resources. The service enables you to easily rotate, manage, and retrieve database credentials, API keys, and other secrets throughout their lifecycle. Users and applications retrieve secrets with a call to Secrets Manager APIs, eliminating the need to hardcode sensitive information in plain text.</p>
 <p><strong>Amazon API Gateway</strong> - Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.</p>
</div>

**Question 30**

30. Which of the following AWS services are part of the AWS Foundation services for the Reliability pillar of the Well-Architected Framework in AWS Cloud? (Select two)
*  A. AWS CloudFormation
*  B. AWS CloudTrail
*  C. Amazon CloudWatch
*  D. AWS Service Quotas
*  E. AWS Trusted Advisor

**Answer** D, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>AWS Trusted Advisor</strong></p>
 <p><strong>AWS Service Quotas</strong></p>
 <p>Foundations are part of the Reliability pillar of the AWS Well-Architected Framework. AWS states that before architecting any system, foundational requirements that influence reliability should be in place. The services that are part of foundations are: Amazon VPC, AWS Trusted Advisor, AWS Service Quotas (formerly called AWS Service Limits).</p>
 <p>AWS Trusted Advisor is an online tool that provides you real-time guidance to help you provision your resources following AWS best practices on cost optimization, security, fault tolerance, service limits, and performance improvement. Whether establishing new workflows, developing applications, or as part of ongoing improvement, recommendations provided by Trusted Advisor regularly help keep your solutions provisioned optimally.</p>
 <p>Service Quotas enables you to view and manage your quotas for AWS services from a central location. Quotas, also referred to as limits in AWS, are the maximum values for the resources, actions, and items in your AWS account. Each AWS service defines its quotas and establishes default values for those quotas.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS CloudTrail</strong> - AWS CloudTrail is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account. With CloudTrail, you can log, continuously monitor, and retain account activity related to actions across your AWS infrastructure. CloudTrail provides the event history of your AWS account activity, including actions taken through the AWS Management Console, AWS SDKs, command-line tools, and other AWS services. Think account-specific activity and audit; think CloudTrail.</p>
 <p><strong>AWS CloudFormation</strong> - AWS CloudFormation provides a common language to model and provision AWS and third-party application resources in your cloud environment. AWS CloudFormation allows you to use programming languages or a simple text file to model and provision, in an automated and secure manner, all the resources needed for your applications across all Regions and accounts. Think infrastructure as code; think CloudFormation.</p>
 <p><strong>Amazon CloudWatch</strong> - Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers. CloudWatch provides data and actionable insights to monitor applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health. This is an excellent service for building Resilient systems. Think resource performance monitoring, events, and alerts; think CloudWatch.</p>
 <p>Reference:</p>
 <p><a href="https://wa.aws.amazon.com/wat.pillar.reliability.en.html">https://wa.aws.amazon.com/wat.pillar.reliability.en.html</a></p>
</div>

**Question 31**

31. Which of the following statements are correct about the AWS account root user (Select two)
*  A. Root user credentials should only be shared with managers requiring administrative responsibilities to complete their jobs
*  B. Root account gets unrestricted permissions when the account is created, but these can be restricted using IAM policies
*  C. Root user access credentials are the email address and password used to create the AWS account
*  D. Root user account password cannot be changed once it is set
*  E. It is highly recommended to enable Multi Factor Authentication (MFA) for root user account

**Answer** C, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>Root user access credentials are the email address and password used to create the AWS account</strong></p>
 <p><strong>It is highly recommended to enable Multi Factor Authentication (MFA) for root user account</strong></p>
 <p>The Email address and the password used for signing up for AWS services are the AWS account root user credentials. Root account, therefore, has full permissions on all AWS resources under that account. Restricting root account access is not possible. As a best practice, Multi-Factor Authentication (MFA) should be set on the root account. The root account password can be changed after account creation. For all employees performing various administrative jobs, create individual user accounts using AWS IAM, and give administrative permissions as needed.</p>
 <p>AWS Root Account Security Best Practices:</p>
 <p><img src="./images/pt2-q54-i1.jpg"> via - <a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/id_root-user.html">https://docs.aws.amazon.com/IAM/latest/UserGuide/id_root-user.html</a></p>
 <p><img src="./images/pt2-q54-i2.jpg"> via - <a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#lock-away-credentials">https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#lock-away-credentials</a></p>
 <p>Incorrect options:</p>
 <p><strong>Root user account password cannot be changed once it is set</strong> - This is incorrect. Like any other user credentials, the root password can be changed after creation.</p>
 <p><strong>Root user credentials should only be shared with managers requiring administrative responsibilities to complete their jobs</strong> - This is a dangerous practice. Root user credentials should only be used only for some limited account-specific activity and root credentials should be never be shared with anyone.</p>
 <p><strong>Root account gets unrestricted permissions when the account is created, but these can be restricted using IAM policies</strong> - Root account permissions cannot be restricted, whoever has access to these credentials can perform any operation for that AWS account. The root user credentials should be kept safely.</p>
 <p>References:</p>
 <p><a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/id_root-user.html">https://docs.aws.amazon.com/IAM/latest/UserGuide/id_root-user.html</a></p>
 <p><a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html">https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html</a></p>
</div>

**Question 32**

32. What is the primary benefit of deploying an RDS database in a Multi-AZ configuration?
*  A. Multi-AZ improves database performance for read-heavy workloads
*  B. Multi-AZ protects the database from a regional failure
*  C. Multi-AZ reduces database usage costs
*  D. Multi-AZ enhances database availability

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Multi-AZ enhances database availability</strong></p>
 <p>Amazon RDS Multi-AZ deployments provide enhanced availability and durability for RDS database (DB) instances, making them a natural fit for production database workloads. When you provision a Multi-AZ DB Instance, Amazon RDS automatically creates a primary DB Instance and synchronously replicates the data to a standby instance in a different Availability Zone (AZ).</p>
 <p>In case of an infrastructure failure, Amazon RDS performs an automatic failover to the standby so that you can resume database operations as soon as the failover is complete.</p>
 <p>How Multi-AZ Works: <img src="./images/multi-az-deployments.bda9d7bf45a74103d0331a985baf2c5fb838a0fa.png"> via - <a href="https://aws.amazon.com/rds/features/multi-az/">https://aws.amazon.com/rds/features/multi-az/</a></p>
 <p>Exam Alert:</p>
 <p>Please review the differences between Multi-AZ, Multi-Region and Read Replica deployments for RDS: <img src="./images/pt2-q17-i1.jpg"> via - <a href="https://aws.amazon.com/rds/features/multi-az/">https://aws.amazon.com/rds/features/multi-az/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Multi-AZ improves database performance for read-heavy workloads</strong> - Read Replicas allow you to create read-only copies that are synchronized with your master database. Read Replicas are used for improved read performance. Therefore, this option is incorrect.</p>
 <p><strong>Multi-AZ protects the database from a regional failure</strong> - You need to use RDS in Multi-Region deployment configuration to protect from a regional failure. Multi-AZ cannot protect from a regional failure.</p>
 <p><strong>Multi-AZ reduces database usage costs</strong> - Multi-AZ RDS increases the database costs compared to the standard deployment. So this option is incorrect.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/rds/features/multi-az/">https://aws.amazon.com/rds/features/multi-az/</a></p>
</div>

**Question 33**

33. Which of the following AWS services are always free to use (Select two)?
*  A. Elastic Compute Cloud (Amazon EC2)
*  B. AWS Auto Scaling
*  C. Simple Storage Service (Amazon S3)
*  D. Identity and Access Management (IAM)
*  E. DynamoDB

**Answer** B, D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>Identity and Access Management (IAM)</strong> - AWS Identity and Access Management (IAM) enables you to manage access to AWS services and resources securely. Using IAM, you can create and manage AWS users and groups, and use permissions to allow and deny their access to AWS resources. IAM is a feature of your AWS account offered at no additional charge.</p>
 <p><strong>AWS Auto Scaling</strong> - AWS Auto Scaling monitors your applications and automatically adjusts the capacity to maintain steady, predictable performance at the lowest possible cost. Using AWS Auto Scaling, it’s easy to setup application scaling for multiple resources across multiple services in minutes. AWS Auto Scaling is available at no additional charge. You pay only for the AWS resources needed to run your applications and Amazon CloudWatch monitoring fees.</p>
 <p>Incorrect options:</p>
 <p><strong>Elastic Compute Cloud (Amazon EC2)</strong> - Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud. It is designed to make web-scale cloud computing easier for developers. This is not a free service. You pay for what you use or depending on the plan you choose.</p>
 <p><strong>Simple Storage Service (Amazon S3)</strong> - Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance. S3 service is not free and you pay to depend on the storage class you choose for your data.</p>
 <p><strong>DynamoDB</strong> - Amazon DynamoDB is a key-value and document database that delivers single-digit millisecond performance at any scale. It's a fully managed, multi-Region, multi-master, durable database with built-in security, backup and restore, and in-memory caching for internet-scale applications. DynamoDB is not free and you are charged for reading, writing, and storing data in your DynamoDB tables, along with any optional features you choose to enable.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/iam/">https://aws.amazon.com/iam/</a></p>
 <p><a href="https://aws.amazon.com/autoscaling/">https://aws.amazon.com/autoscaling/</a></p>
</div>

**Question 34**

34. Which of the following statement is correct for a Security Group and a Network Access Control List?
*  A. Security Group acts as a firewall at the subnet level whereas Network Access Control List acts as a firewall at the instance level
*  B. Security Group acts as a firewall at the VPC level whereas Network Access Control List acts as a firewall at the AZ level
*  C. Security Group acts as a firewall at the instance level whereas Network Access Control List acts as a firewall at the subnet level
*  D. Security Group acts as a firewall at the AZ level whereas Network Access Control List acts as a firewall at the VPC level

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Security Group acts as a firewall at the instance level whereas Network Access Control List acts as a firewall at the subnet level</strong></p>
 <p>A security group acts as a virtual firewall for your instance to control inbound and outbound traffic. When you launch an instance in a VPC, you can assign up to five security groups to the instance. Security groups act at the instance level, not the subnet level. A network access control list (ACL) is an optional layer of security for your VPC that acts as a firewall for controlling traffic in and out of one or more subnets (i.e. it works at subnet level).</p>
 <p>Security Group Overview: <img src="./images/pt2-q52-i1.jpg"> via - <a href="https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html">https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html</a></p>
 <p>Network Access Control List (NACL) Overview: <img src="./images/pt2-q52-i2.jpg"> via - <a href="https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html">https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Security Group acts as a firewall at the subnet level whereas Network Access Control List acts as a firewall at the instance level</strong> - As explained above, the security group acts at the instance level and ACL is at the subnet level.</p>
 <p><strong>Security Group acts as a firewall at the VPC level whereas Network Access Control List acts as a firewall at the AZ level</strong> - As explained above, the security group acts at the instance level and ACL is at the subnet level.</p>
 <p><strong>Security Group acts as a firewall at the AZ level whereas Network Access Control List acts as a firewall at the VPC level</strong> - As explained above, the security group acts at the instance level and ACL is at the subnet level.</p>
 <p>References:</p>
 <p><a href="https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html">https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html</a></p>
 <p><a href="https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html">https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html</a></p>
</div>

**Question 35**

35. Which of the following statements are true about AWS Lambda? (Select two)
*  A. AWS Lambda lets you run code without provisioning or managing servers
*  B. Allows you to orchestrate and manage Docker containers to facilitate complex containerized applications on AWS
*  C. You pay for the compute time you consume
*  D. Allows you to install databases on the underlying serverless Operating System
*  E. AWS Lambda provides access to the underlying operating system to control its behavior through code

**Answer** A, C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>AWS Lambda lets you run code without provisioning or managing servers</strong></p>
 <p><strong>You pay for the compute time you consume</strong></p>
 <p>AWS Lambda is a compute service that lets you run code without provisioning or managing servers. AWS Lambda executes your code only when needed and scales automatically, from a few requests per day to thousands per second. You pay for the compute time and the number of requests for your Lambda function - there is no charge when your code is not running. With AWS Lambda, you can run code for virtually any type of application or backend service - all with zero administration. AWS Lambda runs your code on a high-availability compute infrastructure and performs all of the administration of the compute resources, including server and operating system maintenance, capacity provisioning and automatic scaling, code monitoring and logging.</p>
 <p>How Lambda Works: <img src="./images/product-page-diagram_Lambda-HowItWorks.68a0bcacfcf46fccf04b97f16b686ea44494303f.png"> via - <a href="https://aws.amazon.com/lambda/">https://aws.amazon.com/lambda/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Allows you to install databases on the underlying serverless Operating System</strong> - Lambda is a serverless compute service offered by AWS. Since the underlying hardware is only provisioned for the time of compute, it is not possible to install a database.</p>
 <p><strong>Allows you to orchestrate and manage Docker containers to facilitate complex containerized applications on AWS</strong> - Lambda is a serverless compute service offered by AWS. While Lambda can be used to package and deploy Lambda functions as container images of up to 10 GB in size. But Lambda cannot be used to orchestrate and manage Docker containers. ECS is better suited for this use-case.</p>
 <p><strong>AWS Lambda provides access to the underlying operating system to control its behavior through code</strong> - AWS Lambda is a serverless compute service offered by AWS. It is serverless, so the underlying operating system is not accessible. Amazon Beanstalk or Amazon EC2 services should be used if you need to access the underlying operating system.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/lambda/latest/dg/welcome.html">https://docs.aws.amazon.com/lambda/latest/dg/welcome.html</a></p>
</div>

**Question 36**

36. The engineering team at an IT company wants to monitor the CPU utilization for its fleet of EC2 instances and send an email to the administrator if the utilization exceeds 80%. As a Cloud Practitioner, which AWS services would you recommend to build this solution? (Select two)
*  A. CloudTrail
*  B. Lambda
*  C. SNS
*  D. CloudWatch
*  E. SQS

**Answer** C, D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>CloudWatch</strong> - Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers. CloudWatch provides data and actionable insights to monitor applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health. You can create an CloudWatch alarm that sends an email message using Amazon SNS when the alarm changes state from OK to ALARM. The alarm changes to the ALARM state when the average CPU use of an EC2 instance exceeds a specified threshold for consecutive specified periods.</p>
 <p><strong>SNS</strong> - Amazon Simple Notification Service (SNS) is a highly available, durable, secure, fully managed pub/sub messaging service that enables you to decouple microservices, distributed systems, and serverless applications.</p>
 <p>How SNS Works: <img src="./images/product-page-diagram_SNS_how-it-works_1.53a464980bf0d5a868b141e9a8b2acf12abc503f.png"> via - <a href="https://aws.amazon.com/sns/">https://aws.amazon.com/sns/</a></p>
 <p>Incorrect options:</p>
 <p><strong>CloudTrail</strong> - AWS CloudTrail is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account. With CloudTrail, you can log, continuously monitor, and retain account activity related to actions across your AWS infrastructure. Think account-specific activity and audit; think CloudTrail. CloudTrail cannot be used to monitor CPU utilization for EC2 instances or send emails.</p>
 <p><strong>Lambda</strong> - AWS Lambda lets you run code without provisioning or managing servers. You pay only for the compute time you consume. Lambda cannot be used to monitor CPU utilization for EC2 instances or send emails.</p>
 <p><strong>SQS</strong> - Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications. SQS offers two types of message queues - Standard queues vs FIFO queues. SQS cannot be used to monitor CPU utilization for EC2 instances or send emails.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/cloudwatch/">https://aws.amazon.com/cloudwatch/</a></p>
 <p><a href="https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/US_AlarmAtThresholdEC2.html">https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/US_AlarmAtThresholdEC2.html</a></p>
</div>

**Question 37**

37. What are the fundamental drivers of cost with AWS Cloud?
*  A. Compute, Storage and Outbound Data Transfer
*  B. Compute, Databases and Outbound Data Transfer
*  C. Compute, Storage and Inbound Data Transfer
*  D. Compute, Databases and Inbound Data Transfer

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>Compute, Storage and Outbound Data Transfer</strong></p>
 <p>There are three fundamental drivers of cost with AWS: compute, storage, and outbound data transfer. In most cases, there is no charge for inbound data transfer or data transfer between other AWS services within the same region. Outbound data transfer is aggregated across services and then charged at the outbound data transfer rate.</p>
 <p>AWS Cloud Pricing Fundamentals: <img src="./images/pt2-q42-i1.jpg"> via - <a href="https://d0.awsstatic.com/whitepapers/aws_pricing_overview.pdf">https://d0.awsstatic.com/whitepapers/aws_pricing_overview.pdf</a></p>
 <p>Incorrect options:</p>
 <p><strong>Compute, Storage and Inbound Data Transfer</strong></p>
 <p><strong>Compute, Databases and Outbound Data Transfer</strong></p>
 <p><strong>Compute, Databases and Inbound Data Transfer</strong></p>
 <p>These three options contradict the details provided earlier in the explanation, so these options are incorrect.</p>
 <p>Reference:</p>
 <p><a href="https://d0.awsstatic.com/whitepapers/aws_pricing_overview.pdf">https://d0.awsstatic.com/whitepapers/aws_pricing_overview.pdf</a></p>
</div>

**Question 38**

38. A developer has written a simple web application in PHP and he wants to just upload his code to AWS Cloud and have AWS handle the deployment automatically but still wants access to the underlying operating system for further enhancements. As a Cloud Practioner, which of the following AWS services would you recommend for this use-case?
*  A. AWS CloudFormation
*  B. AWS Elastic Container Service (ECS)
*  C. AWS Elastic Beanstalk
*  D. Amazon EC2

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Elastic Beanstalk</strong></p>
 <p>AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling web applications and services developed with Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker on familiar servers such as Apache, Nginx, Passenger, and IIS. Simply upload your code and Elastic Beanstalk automatically handles the deployment, from capacity provisioning, load balancing, auto-scaling to application health monitoring. At the same time, you retain full control over the AWS resources powering your application and can access the underlying resources at any time. There is no additional charge for Elastic Beanstalk - you pay only for the AWS resources needed to store and run your applications.</p>
 <p>Key Benefits of Elastic Beanstalk: <img src="./images/pt2-q45-i1.jpg"> via - <a href="https://aws.amazon.com/elasticbeanstalk/">https://aws.amazon.com/elasticbeanstalk/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS CloudFormation</strong> - AWS CloudFormation allows you to use programming languages or a simple text file (in YAML or JSON format) to model and provision, in an automated and secure manner, all the resources needed for your applications across all Regions and accounts. Think infrastructure as code; think CloudFormation. This is very different from Beanstalk where you just upload your application code and Beanstalk automatically figures out what resources are required to deploy that application. In CloudFormation, you have to explicitly specify which resources you want to provision.</p>
 <p><strong>Amazon EC2</strong> - Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud, per-second billing, and access to the underlying OS. It is designed to make web-scale cloud computing easier for developers. Maintaining the server and its software has to be done by the customer. EC2 cannot handle the application deployment automatically, so this option is not correct.</p>
 <p><strong>AWS Elastic Container Service (ECS)</strong> - Amazon Elastic Container Service (Amazon ECS) is a highly scalable, fast, container management service that makes it easy to run, stop, and manage Docker containers on a cluster. ECS cannot handle the application deployment automatically, so this option is not correct.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/elasticbeanstalk/">https://aws.amazon.com/elasticbeanstalk/</a></p>
</div>

**Question 39**

39. Which of the following AWS services can be used to prevent Distributed Denial-of-Service (DDoS) attack? (Select three)
*  A. AWS WAF
*  B. AWS Trusted Advisor
*  C. AWS Shield
*  D. AWS CloudHSM
*  E. Amazon Inspector
*  F. Amazon CloudFront with Route 53

**Answer** A, C, F

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>AWS Shield</strong> - AWS Shield is a managed Distributed Denial of Service (DDoS) protection service that safeguards applications running on AWS. AWS Shield provides always-on detection and automatic inline mitigations that minimize application downtime and latency, so there is no need to engage AWS Support to benefit from DDoS protection.</p>
 <p><strong>AWS WAF</strong> - By using AWS WAF, you can configure web access control lists (Web ACLs) on your CloudFront distributions or Application Load Balancers to filter and block requests based on request signatures. Besides, by using AWS WAF's rate-based rules, you can automatically block the IP addresses of bad actors when requests matching a rule exceed a threshold that you define.</p>
 <p><strong>Amazon CloudFront with Route 53</strong> - AWS hosts CloudFront and Route 53 services on a distributed network of proxy servers in data centers throughout the world called edge locations. Using the global Amazon network of edge locations for application delivery and DNS service plays an important part in building a comprehensive defense against DDoS attacks for your dynamic web applications.</p>
 <p>How AWS Shield, WAF, and CloudFront with Route 53 help mitigate DDoS attacks: <img src="./images/pt2-q30-i1.jpg"> via - <a href="https://aws.amazon.com/blogs/security/how-to-protect-dynamic-web-applications-against-ddos-attacks-by-using-amazon-cloudfront-and-amazon-route-53/">https://aws.amazon.com/blogs/security/how-to-protect-dynamic-web-applications-against-ddos-attacks-by-using-amazon-cloudfront-and-amazon-route-53/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS CloudHSM</strong> - AWS CloudHSM is a cloud-based hardware security module (HSM) that enables you to easily generate and use your encryption keys on the AWS Cloud. With CloudHSM, you can manage your encryption keys using FIPS 140-2 Level 3 validated HSMs. It is a fully-managed service that automates time-consuming administrative tasks for you, such as hardware provisioning, software patching, high-availability, and backups. CloudHSM cannot be used to prevent Distributed Denial-of-Service (DDoS) attack.</p>
 <p><strong>AWS Trusted Advisor</strong> - AWS Trusted Advisor is an online tool that provides you real-time guidance to help you provision your resources following AWS best practices on cost optimization, security, fault tolerance, service limits and performance improvement. Whether establishing new workflows, developing applications, or as part of ongoing improvement, recommendations provided by Trusted Advisor regularly help keep your solutions provisioned optimally. Trusted Advisor cannot be used to prevent Distributed Denial-of-Service (DDoS) attack.</p>
 <p><strong>Amazon Inspector</strong> - Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. Amazon Inspector automatically assesses applications for exposure, vulnerabilities, and deviations from best practices. Amazon Inspector cannot be used to prevent Distributed Denial-of-Service (DDoS) attack.</p>
 <p>References:</p>
 <p><a href="https://docs.aws.amazon.com/waf/latest/developerguide/ddos-overview.html">https://docs.aws.amazon.com/waf/latest/developerguide/ddos-overview.html</a></p>
 <p><a href="https://aws.amazon.com/shield/">https://aws.amazon.com/shield/</a></p>
 <p><a href="https://d1.awsstatic.com/whitepapers/Security/DDoS_White_Paper.pdf">https://d1.awsstatic.com/whitepapers/Security/DDoS_White_Paper.pdf</a></p>
 <p><a href="https://aws.amazon.com/blogs/security/how-to-protect-dynamic-web-applications-against-ddos-attacks-by-using-amazon-cloudfront-and-amazon-route-53/">https://aws.amazon.com/blogs/security/how-to-protect-dynamic-web-applications-against-ddos-attacks-by-using-amazon-cloudfront-and-amazon-route-53/</a></p>
</div>

**Question 40**

40. A retail company has multiple AWS accounts for each of its departments. Which of the following AWS services can be used to set up consolidated billing and a single payment method for these AWS accounts?
*  A. AWS Budgets
*  B. AWS Organizations
*  C. AWS Secrets Manager
*  D. AWS Cost Explorer

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Organizations</strong></p>
 <p>AWS Organizations helps you to centrally manage billing; control access, compliance, and security; and share resources across your AWS accounts. Using AWS Organizations, you can automate account creation, create groups of accounts to reflect your business needs, and apply policies for these groups for governance. You can also simplify billing by setting up a single payment method for all of your AWS accounts. AWS Organizations is available to all AWS customers at no additional charge.</p>
 <p>Key Features of AWS Organizations: <img src="./images/pt2-q36-i1.jpg"> via - <a href="https://aws.amazon.com/organizations/">https://aws.amazon.com/organizations/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS Cost Explorer</strong> - AWS Cost Explorer has an easy-to-use interface that lets you visualize, understand, and manage your AWS costs and usage over time. AWS Cost Explorer includes a default report that helps you visualize the costs and usage associated with your top five cost-accruing AWS services, and gives you a detailed breakdown of all services in the table view. The reports let you adjust the time range to view historical data going back up to twelve months to gain an understanding of your cost trends. You cannot use Cost Explorer to set up consolidated billing and a single payment method for multiple AWS accounts.</p>
 <p><strong>AWS Budgets</strong> - AWS Budgets gives the ability to set custom budgets that alert you when your costs or usage exceed (or are forecasted to exceed) your budgeted amount. You can also use AWS Budgets to set reservation utilization or coverage targets and receive alerts when your utilization drops below the threshold you define. Budgets can be created at the monthly, quarterly, or yearly level, and you can customize the start and end dates. You can further refine your budget to track costs associated with multiple dimensions, such as AWS service, linked account, tag, and others. You cannot use AWS Budgets to set up consolidated billing and a single payment method for multiple AWS accounts.</p>
 <p><strong>AWS Secrets Manager</strong> - AWS Secrets Manager helps you protect secrets needed to access your applications, services, and IT resources. The service enables you to easily rotate, manage, and retrieve database credentials, API keys, and other secrets throughout their lifecycle. You cannot use Secrets Manager to set up consolidated billing and a single payment method for multiple AWS accounts.</p>
 <p>Reference: https://aws.amazon.com/organizations/</p>
</div>

**Question 41**

41. Which AWS service helps with global application availability and performance using the AWS global network?
*  A. Amazon CloudFront
*  B. Amazon Route 53
*  C. Global Accelerator
*  D. Elastic Load Balancer

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Global Accelerator</strong></p>
 <p>AWS Global Accelerator is a service that improves the availability and performance of your applications with local or global users. It provides static IP addresses that act as a fixed entry point to your application endpoints in a single or multiple AWS Regions, such as your Application Load Balancers, Network Load Balancers, or Amazon EC2 instances. AWS Global Accelerator uses the AWS global network to optimize the path from your users to your applications, improving the performance of your traffic by as much as 60%.</p>
 <p>Global Accelerator improves performance for a wide range of applications over TCP or UDP by proxying packets at the edge to applications running in one or more AWS Regions. Global Accelerator is a good fit for non-HTTP use cases, such as gaming (UDP), IoT (MQTT), or Voice over IP, as well as for HTTP use cases that specifically require static IP addresses or deterministic, fast regional failover.</p>
 <p>How Global Accelerator Works: <img src="./images/pt2-q56-i1.jpg"> via - <a href="https://aws.amazon.com/global-accelerator/">https://aws.amazon.com/global-accelerator/</a></p>
 <p>Exam Alert:</p>
 <p>Please review the differences between CloudFront and Global Accelerator: <img src="./images/pt2-q56-i2.jpg"> via - <a href="https://aws.amazon.com/global-accelerator/faqs/">https://aws.amazon.com/global-accelerator/faqs/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon CloudFront</strong> - Amazon CloudFront is a fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency, high transfer speeds, all within a developer-friendly environment. CloudFront cannot be used to improve application availability and performance using the AWS global network.</p>
 <p><strong>Elastic Load Balancer</strong> - Elastic Load Balancer distributes incoming application or network traffic across multiple targets, such as Amazon EC2 instances, containers, and IP addresses, in multiple Availability Zones. Elastic Load Balancing scales your load balancer as traffic to your application changes over time. It can automatically scale to the vast majority of workloads. Elastic Load Balancer cannot be used to improve application availability and performance using the AWS global network.</p>
 <p><strong>Amazon Route 53</strong> - Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service. It is designed to give developers and businesses an extremely reliable and cost-effective way to route end users to Internet applications by translating names like www.example.com into the numeric IP addresses like 192.0.2.1 that computers use to connect. Route 53 cannot be used to improve application availability and performance using the AWS global network.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/global-accelerator/">https://aws.amazon.com/global-accelerator/</a></p>
</div>

**Question 42**

42. Which of the following statement is correct regarding the AWS pricing policy for data transfer charges into or out of an AWS Region?
*  A. Both inbound data transfer and outbound data transfer are charged
*  B. Only inbound data transfer is charged
*  C. Neither inbound nor outbound data transfer are charged
*  D. Only outbound data transfer is charged

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Only outbound data transfer is charged</strong></p>
 <p>One of the main benefits of cloud services is the ability it gives you to optimize costs to match your needs, even as those needs change. AWS services do not have complex dependencies or licensing requirements, so you can get exactly what you need to build innovative, cost-effective solutions using the latest technology.</p>
 <p>There are three fundamental drivers of cost with AWS: compute, storage, and outbound data transfer. These characteristics vary somewhat, depending on the AWS product and pricing model you choose. Outbound data to the internet from all AWS regions is billed at region-specific, tiered data transfer rates. Inbound data transfer into all AWS regions from the internet is free.</p>
 <p>Incorrect options:</p>
 <p><strong>Only inbound data transfer is charged</strong></p>
 <p><strong>Both inbound data transfer and outbound data transfer are charged</strong></p>
 <p><strong>Neither inbound nor outbound data transfer are charged</strong></p>
 <p>These three options contradict the explanation provided above, so these options are incorrect.</p>
 <p>Reference:</p>
 <p><a href="https://d0.awsstatic.com/whitepapers/aws_pricing_overview.pdf">https://d0.awsstatic.com/whitepapers/aws_pricing_overview.pdf</a></p>
</div>

**Question 43**

43. A data analytics company has some data stored on Amazon S3 and wants to do SQL based analysis on this data with minimum effort. As a Cloud Practitioner, which of the following AWS services will you suggest for this use case?
*  A. Amazon Aurora
*  B. DynamoDB
*  C. Redshift
*  D. Amazon Athena

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon Athena</strong></p>
 <p>Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. Athena is serverless, so there is no infrastructure to manage, and you pay only for the queries that you run.</p>
 <p>Key features of Amazon Athena: <img src="./images/pt2-q55-i1.jpg"> via - <a href="https://aws.amazon.com/athena/">https://aws.amazon.com/athena/</a></p>
 <p>To use Athena, simply point to your data in Amazon S3, define the schema, and start querying using standard SQL. Most results are delivered within seconds. With Athena, there’s no need for complex ETL jobs to prepare your data for analysis. This makes it easy for anyone with SQL skills to quickly analyze large-scale datasets.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Aurora</strong> - Amazon Aurora is a MySQL and PostgreSQL-compatible relational database built for the cloud, that combines the performance and availability of traditional enterprise databases with the simplicity and cost-effectiveness of open source databases. You cannot use Aurora for SQL analysis on S3 based data.</p>
 <p><strong>Redshift</strong> - Amazon Redshift is the most popular and fastest cloud data warehouse. Though analytics can be run on Redshift, in the current use case, old data is residing on S3, and Athena is the right choice since analytics can be run directly while data is sitting on S3. You cannot use Redshift for SQL analysis on S3 based data.</p>
 <p><strong>DynamoDB</strong> - Amazon DynamoDB is a key-value and document database that delivers single-digit millisecond performance at any scale. It's a fully managed, multi-Region, multi-master, durable database with built-in security, backup and restore, and in-memory caching for internet-scale applications. You cannot use DynamoDB for SQL analysis on S3 based data.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/athena/">https://aws.amazon.com/athena/</a></p>
</div>

**Question 44**

44. Which characteristic of Cloud Computing imparts the ability to acquire resources as you need and release when you no longer need them?
*  A. Elasticity
*  B. Reliability
*  C. Durability
*  D. Resiliency

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option: <strong>Elasticity</strong></p>
 <p>The ability to acquire resources as you need and release when they are no longer needed is termed as Elasticity of the Cloud. With cloud computing, you don’t have to over-provision resources upfront to handle peak levels of business activity in the future. Instead, you provision the number of resources that you need. You can scale these resources up or down instantly to grow and shrink capacity as your business needs change.</p>
 <p>What is Elasticity: <img src="./images/pt2-q7-i1.jpg"> via - <a href="https://aws.amazon.com/what-is-cloud-computing/">https://aws.amazon.com/what-is-cloud-computing/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Reliability</strong> - Refers to the ability of a system to recover from infrastructure or service disruptions, by dynamically acquiring computing resources to meet demand, and mitigate disruptions.</p>
 <p><strong>Durability</strong> - Refers to the ability of a system to assure data is stored and data remains consistently on the system as long as it is not changed by legitimate access, i.e. data should not get corrupt or disappear from the cloud because of a system malfunction.</p>
 <p><strong>Resiliency</strong> - Describes the ability of a system to recover from a failure induced by the load (data or network), attacks, and failures (hardware, software, or network failures).</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/what-is-cloud-computing/">https://aws.amazon.com/what-is-cloud-computing/</a></p>
 <p><a href="https://wa.aws.amazon.com/wat.concept.elasticity.en.html">https://wa.aws.amazon.com/wat.concept.elasticity.en.html</a></p>
</div>

**Question 45**

45. Due to regulatory and compliance reasons, an organization is supposed to use a hardware device for any data encryption operations in the cloud. Which AWS service can be used to meet this compliance requirement?
*  A. AWS Key Management Service (KMS)
*  B. AWS CloudHSM
*  C. AWS Trusted Advisor
*  D. AWS Secrets Manager

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS CloudHSM</strong></p>
 <p>AWS CloudHSM is a cloud-based Hardware Security Module (HSM) that enables you to easily generate and use your encryption keys on the AWS Cloud. With CloudHSM, you can manage your encryption keys using FIPS 140-2 Level 3 validated HSMs. It is a fully-managed service that automates time-consuming administrative tasks for you, such as hardware provisioning, software patching, high-availability, and backups.</p>
 <p>Please review this detailed description of how CloudHSM works: <img src="./images/pt2-q14-i1.jpg"> via - <a href="https://aws.amazon.com/cloudhsm/">https://aws.amazon.com/cloudhsm/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS Key Management Service (KMS)</strong> - AWS Key Management Service (KMS) makes it easy for you to create and manage cryptographic keys and control their use across a wide range of AWS services and in your applications. AWS KMS is a secure and resilient service that uses hardware security modules that have been validated under FIPS 140-2, or are in the process of being validated, to protect your keys. KMS cannot be used as a Hardware Security Module for data encryption operations in AWS Cloud.</p>
 <p><strong>AWS Secrets Manager</strong> - AWS Secrets Manager helps you protect secrets needed to access your applications, services, and IT resources. The service enables you to easily rotate, manage, and retrieve database credentials, API keys, and other secrets throughout their lifecycle. Users and applications retrieve secrets with a call to Secrets Manager APIs, eliminating the need to hardcode sensitive information in plain text. Secrets Manager cannot be used as a Hardware Security Module for data encryption operations in AWS Cloud.</p>
 <p><strong>AWS Trusted Advisor</strong> - AWS Trusted Advisor is an online tool that provides you real-time guidance to help you provision your resources following AWS best practices on cost optimization, security, fault tolerance, service limits, and performance improvement. Whether establishing new workflows, developing applications, or as part of ongoing improvement, recommendations provided by Trusted Advisor regularly help keep your solutions provisioned optimally.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/cloudhsm/">https://aws.amazon.com/cloudhsm/</a></p>
</div>

**Question 46**

46. Which AWS Route 53 routing policy would you use to improve the performance for your customers by routing the requests to the AWS endpoint that provides the fastest experience?
*  A. Latency routing policy
*  B. Failover routing policy
*  C. Weighted routing policy
*  D. Simple routing policy

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Latency routing policy</strong></p>
 <p>Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service. It is designed to give developers and businesses an extremely reliable and cost-effective way to route end users to Internet applications by translating names like www.example.com into the numeric IP addresses like 192.0.2.1 that computers use to connect to each other.</p>
 <p>If your application is hosted in multiple AWS Regions, you can use latency routing policy to improve the performance for your users by serving their requests from the AWS Region that provides the lowest latency. To use latency-based routing, you create latency records for your resources in multiple AWS Regions. When Route 53 receives a DNS query for your domain or subdomain (example.com or acme.example.com), it determines which AWS Regions you've created latency records for, determines which region gives the user the lowest latency, and then selects a latency record for that region. Route 53 responds with the value from the selected record, such as the IP address for a web server.</p>
 <p>Route 53 Routing Policy Overview: <img src="./images/pt2-q51-i1.jpg"> via - <a href="https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html">https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Failover routing policy</strong> - This routing policy is used when you want to configure active-passive failover.</p>
 <p><strong>Weighted routing policy</strong> - This routing policy is used to route traffic to multiple resources in proportions that you specify.</p>
 <p><strong>Simple routing policy</strong> - With simple routing, you typically route traffic to a single resource, for example, to a web server for your website.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html">https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html</a></p>
</div>

**Question 47**

47. Which AWS service enables users to find, buy, and immediately start using software solutions in their AWS environment?
*  A. AWS OpsWorks
*  B. AWS Config
*  C. AWS Marketplace
*  D. AWS Systems Manager

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Marketplace</strong></p>
 <p>AWS Marketplace is a digital catalog with thousands of software listings from independent software vendors that make it easy to find, test, buy, and deploy software that runs on AWS. AWS Marketplace includes thousands of software listings from popular categories such as security, networking, storage, machine learning, IoT, business intelligence, database, and DevOps. You can use AWS Marketplace as a buyer (subscriber) or as a seller (provider), or both. Anyone with an AWS account can use AWS Marketplace as a consumer and can register to become a seller.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Config</strong> - AWS Config is a service that enables you to assess, audit, and evaluate the configurations of your AWS resources. Config continuously monitors and records your AWS resource configurations and allows you to automate the evaluation of recorded configurations against desired configurations. Think resource-specific history, audit, and compliance; think Config.</p>
 <p><strong>AWS OpsWorks</strong> - AWS OpsWorks is a configuration management service that provides managed instances of Chef and Puppet. OpsWorks lets you use Chef and Puppet to automate how servers are configured, deployed and managed across your Amazon EC2 instances or on-premises compute environments.</p>
 <p><strong>AWS Systems Manager</strong> - AWS Systems Manager gives you visibility and control of your infrastructure on AWS. Systems Manager provides a unified user interface so you can view operational data from multiple AWS services and allows you to automate operational tasks across your AWS resources. With Systems Manager, you can group resources, like Amazon EC2 instances, Amazon S3 buckets, or Amazon RDS instances, by application, view operational data for monitoring and troubleshooting, and take action on your groups of resources.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/marketplace/latest/buyerguide/what-is-marketplace.html">https://docs.aws.amazon.com/marketplace/latest/buyerguide/what-is-marketplace.html</a></p>
</div>

**Question 48**

48. A fleet of Amazon EC2 instances spread across different Availability Zones needs to access, edit and share file-based data stored centrally on a system. As a Cloud Practitioner, which AWS service would you recommend for this use-case?
*  A. Elastic Block Store (EBS) Volume
*  B. Elastic File System (EFS)
*  C. EC2 Instance Store
*  D. Amazon S3

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Elastic File System (EFS)</strong></p>
 <p>Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed, elastic NFS file system. It is built to scale on-demand to petabytes without disrupting applications, growing and shrinking automatically as you add and remove files, eliminating the need to provision and manage capacity to accommodate growth. Amazon EFS is designed to provide massively parallel shared access to thousands of Amazon EC2 instances, enabling your applications to achieve high levels of aggregate throughput and IOPS with consistent low latencies.</p>
 <p>How EFS Works: <img src="./images/product-page-diagram-Amazon-EFS-Launch_How-It-Works.cf947858f0ef3557b9fc14077bdf3f65b3f9ff43.png"> via - <a href="https://aws.amazon.com/efs/">https://aws.amazon.com/efs/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Elastic Block Store (EBS) Volume</strong> - Amazon Elastic Block Store (EBS) is an easy to use, high-performance block storage service designed for use with Amazon Elastic Compute Cloud (EC2) for both throughput and transaction-intensive workloads at any scale. A broad range of workloads, such as relational and non-relational databases, enterprise applications, containerized applications, big data analytics engines, file systems, and media workflows are widely deployed on Amazon EBS. An EBS can only be mounted to one EC2 instance at a time, so this option is not correct for the given use-case.</p>
 <p><strong>EC2 Instance Store</strong> - An instance store provides temporary block-level storage for your EC2 instance. This storage is located on disks that are physically attached to the host computer. Instance store is ideal for the temporary storage of information that changes frequently, such as buffers, caches, scratch data, and other temporary content, or for data that is replicated across a fleet of instances, such as a load-balanced pool of web servers. Instance storage is temporary, data is lost if instance experiences failure or is terminated. EC2 instance store cannot be used for file sharing between instances.</p>
 <p><strong>Amazon S3</strong> - Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance. This means customers of all sizes and industries can use it to store and protect any amount of data for a range of use cases, such as websites, mobile applications, backup and restore, archive, enterprise applications, IoT devices, and big data analytics. As S3 is object-based storage, so it cannot be used for file sharing between instances.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/efs/">https://aws.amazon.com/efs/</a></p>
</div>

**Question 49**

49. Which of the following AWS services comes under the Software as a Service (SaaS) Cloud Computing Type?
*  A. Amazon EC2
*  B. AWS Elastic Beanstalk
*  C. Elastic Load Balancing
*  D. Amazon Rekognition

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option: <strong>Amazon Rekognition</strong></p>
 <p>Cloud Computing can be broadly divided into three types - Infrastructure as a Service (IaaS), Platform as a Service (PaaS), Software as a Service (SaaS).</p>
 <p>IaaS contains the basic building blocks for cloud IT. It typically provides access to networking features, computers (virtual or on dedicated hardware), and data storage space. IaaS gives the highest level of flexibility and management control over IT resources. <strong>Examples - Amazon EC2 (on AWS), GCP, Azure, Rackspace, Digital Ocean, Linode.</strong></p>
 <p>PaaS removes the need to manage underlying infrastructure (usually hardware and operating systems) and allows you to focus on the deployment and management of your applications. You don’t need to worry about resource procurement, capacity planning, software maintenance, patching, or any of the other undifferentiated heavy lifting involved in running your application. <strong>Examples - Elastic Beanstalk (on AWS), Heroku, Google App Engine (GCP), Windows Azure (Microsoft).</strong></p>
 <p>SaaS provides you with a complete product that is run and managed by the service provider. With a SaaS offering, you don’t have to think about how the service is maintained or how the underlying infrastructure is managed. You only need to think about how you will use that particular software. <strong>Examples - Amazon Rekognition, Google Apps (Gmail), Dropbox, Zoom.</strong></p>
 <p>Overview of Cloud Computing Types: <img src="./images/pt2-q1-i1.jpg"> via - <a href="https://aws.amazon.com/types-of-cloud-computing/">https://aws.amazon.com/types-of-cloud-computing/</a></p>
 <p>You can use Amazon Rekognition to add image and video analysis to your applications using proven, highly scalable, deep learning technology that requires no machine learning expertise. With Amazon Rekognition, you can identify objects, people, text, scenes, and activities in images and videos as well as detect any inappropriate content. Rekognition is an example of Software as a Service model.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon EC2</strong> - Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud. Hence, it comes under Infrastructure as a Service type of Cloud Computing.</p>
 <p><strong>AWS Elastic Beanstalk</strong> - AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling web applications and services. You simply upload your code and Elastic Beanstalk automatically handles the deployment, from capacity provisioning, load balancing, auto-scaling to application health monitoring. Per the definitions above, Elastic Beanstalk falls under the Platform as a Service type.</p>
 <p><strong>Elastic Load Balancing</strong> - Elastic Load Balancing automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, and Lambda functions. It can handle the varying load of your application traffic in a single Availability Zone or across multiple Availability Zones. This has been added as a distractor.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/elasticbeanstalk/">https://aws.amazon.com/elasticbeanstalk/</a></p>
 <p><a href="https://aws.amazon.com/what-is-cloud-computing/">https://aws.amazon.com/what-is-cloud-computing/</a></p>
</div>

**Question 50**

50. Which of the following AWS services is essential for implementing security of resources in AWS Cloud?
*  A. AWS WAF
*  B. AWS Identity and Access Management (IAM)
*  C. Amazon CloudWatch
*  D. AWS Shield

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Identity and Access Management (IAM)</strong></p>
 <p>AWS Identity and Access Management (IAM) enables you to manage access to AWS services and resources securely. Using IAM, you can create and manage AWS users and groups, and use permissions to allow and deny their access to AWS resources. IAM enables security best practices by allowing you to grant unique security credentials to users and groups to specify which AWS service APIs and resources they can access. These features make IAM an important service for the overall security of AWS resources in your account. IAM is secure by default; users have no access to AWS resources until permissions are explicitly granted.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon CloudWatch</strong> - Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers. CloudWatch provides data and actionable insights to monitor applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health. This is an excellent service for building Resilient systems. Think resource performance monitoring, events, and alerts; think CloudWatch.</p>
 <p><strong>AWS Shield</strong> - AWS Shield is a managed Distributed Denial of Service (DDoS) protection service that safeguards applications running on AWS. AWS Shield provides always-on detection and automatic inline mitigations that minimize application downtime and latency, so there is no need to engage AWS Support to benefit from DDoS protection. AWS Shield cannot be used to handle resource-specific security on AWS.</p>
 <p><strong>AWS WAF</strong> - By using AWS WAF, you can configure web access control lists (Web ACLs) on your CloudFront distributions or Application Load Balancers to filter and block requests based on request signatures. Besides, by using AWS WAF's rate-based rules, you can automatically block the IP addresses of bad actors when requests matching a rule exceed a threshold that you define. AWS WAF cannot be used to handle resource-specific security on AWS.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/iam/">https://aws.amazon.com/iam/</a></p>
</div>

**Question 51**

51. Multi AZ (Availability Zone) deployment is an example of which of the following?
*  A. High Availability
*  B. Horizontal Scaling
*  C. Vertical Scaling
*  D. Performance Efficiency

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>High Availability</strong> - A system that is available is capable of delivering the designed functionality at a given point in time. Highly available systems are those that can withstand some measure of degradation while still remaining available. On AWS Cloud, you can run instances for an application across multi AZ to achieve High Availability.</p>
 <p>Incorrect options:</p>
 <p><strong>Horizontal Scaling</strong> - A "horizontally scalable" system is one that can increase capacity by adding more computers to the system. This is in contrast to a "vertically scalable" system, which is constrained to running its processes on only one computer; in such systems, the only way to increase performance is to add more resources into one computer in the form of faster (or more) CPUs, memory or storage. Horizontally scalable systems are oftentimes able to outperform vertically scalable systems by enabling parallel execution of workloads and distributing those across many different computers. Auto Scaling Group is an example of Horizontal Scaling on AWS.</p>
 <p><strong>Vertical Scaling</strong> - Vertical Scaling is adding more resources (like CPU, RAM) to a single node or machine. Example- Resizing an instance of EC2.</p>
 <p><strong>Performance Efficiency</strong> - Is the ability to use computing resources efficiently to meet system requirements and to maintain that efficiency as demand changes and technologies evolve.</p>
 <p>References:</p>
 <p><a href="https://wa.aws.amazon.com/wat.concept.availability.en.html">https://wa.aws.amazon.com/wat.concept.availability.en.html</a></p>
 <p><a href="https://wa.aws.amazon.com/wat.concept.horizontal-scaling.en.html">https://wa.aws.amazon.com/wat.concept.horizontal-scaling.en.html</a></p>
</div>

**Question 52**

52. Which tool will help you review your workloads against current AWS best practices for cost optimization, security, and performance improvement and then obtain advice to architect them better?
*  A. AWS Cost Explorer
*  B. Amazon Inspector
*  C. AWS Trusted Advisor
*  D. Amazon CloudWatch

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option: <strong>AWS Trusted Advisor</strong></p>
 <p>AWS Trusted Advisor is an online tool that provides you real-time guidance to help you provision your resources following AWS best practices on cost optimization, security, fault tolerance, service limits, and performance improvement. Whether establishing new workflows, developing applications, or as part of ongoing improvement, recommendations provided by Trusted Advisor regularly help keep your solutions provisioned optimally. All AWS customers get access to the seven core Trusted Advisor checks to help increase the security and performance of the AWS environment.</p>
 <p>How Trusted Advisor Works: <img src="./images/AWS-trusted-advisor.5b9909d5f29f680eeb12ccff536e8d88d8701304.png"> via - <a href="https://aws.amazon.com/premiumsupport/technology/trusted-advisor/">https://aws.amazon.com/premiumsupport/technology/trusted-advisor/</a></p>
 <p>AWS Trusted Advisor Recommendations: <img src="./images/pt2-q3-i1.jpg"> via - <a href="https://aws.amazon.com/premiumsupport/technology/trusted-advisor/">https://aws.amazon.com/premiumsupport/technology/trusted-advisor/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS Cost Explorer</strong> - AWS Cost Explorer lets you explore your AWS costs and usage at both a high level and at a detailed level of analysis, and empowering you to dive deeper using several filtering dimensions (e.g., AWS Service, Region, Linked Account). Cost Explorer does not offer any recommendations vis-a-vis AWS best practices for cost optimization, security, and performance improvement.</p>
 <p><strong>Amazon CloudWatch</strong> - Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers. CloudWatch provides data and actionable insights to monitor applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health. This is an excellent service for building Resilient systems. Think resource performance monitoring, events, and alerts; think CloudWatch. CloudWatch does not offer any recommendations vis-a-vis AWS best practices for cost optimization, security, and performance improvement.</p>
 <p><strong>Amazon Inspector</strong> - Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. Amazon Inspector automatically assesses applications for exposure, vulnerabilities, and deviations from best practices. Amazon Inspector cannot be used to prevent Distributed Denial-of-Service (DDoS) attack. Inspector does not offer any recommendations vis-a-vis AWS best practices for cost optimization, security, and performance improvement.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/premiumsupport/technology/trusted-advisor/">https://aws.amazon.com/premiumsupport/technology/trusted-advisor/</a></p>
</div>

**Question 53**

53. AWS Compute Optimizer delivers recommendations for which of the following AWS resources? (Select two)
*  A. AWS Lambda functions, Amazon Simple Storage Service (Amazon S3)
*  B. Amazon EC2 instances, Amazon EC2 Auto Scaling groups
*  C. Amazon EBS volumes, AWS Lambda functions
*  D. Amazon Elastic File System (Amazon EFS), AWS Lambda functions
*  E. Amazon EC2 instances, Amazon Elastic File System (Amazon EFS)

**Answer** B, C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>Amazon EC2 instances, Amazon EC2 Auto Scaling groups</strong></p>
 <p><strong>Amazon EBS volumes, AWS Lambda functions</strong></p>
 <p>AWS Compute Optimizer helps you identify the optimal AWS resource configurations, such as Amazon EC2 instance types, Amazon EBS volume configurations, and AWS Lambda function memory sizes, using machine learning to analyze historical utilization metrics. AWS Compute Optimizer delivers recommendations for selected types of EC2 instances, EC2 Auto Scaling groups, EBS volumes, and Lambda functions.</p>
 <p>Compute Optimizer calculates an individual performance risk score for each resource dimension of the recommended instance, including CPU, memory, EBS throughput, EBS IOPS, disk throughput, disk throughput, network throughput, and network packets per second (PPS).</p>
 <p>AWS Compute Optimizer provides EC2 instance type and size recommendations for EC2 Auto Scaling groups with a fixed group size, meaning desired, minimum, and maximum are all set to the same value and have no scaling policy attached.</p>
 <p>AWS Compute Optimizer supports IOPS and throughput recommendations for General Purpose (SSD) (gp3) volumes and IOPS recommendations for Provisioned IOPS (io1 and io2) volumes.</p>
 <p>Compute Optimizer helps you optimize two categories of Lambda functions. The first category includes Lambda functions that may be over-provisioned in memory sizes. The second category includes compute-intensive Lambda functions that may benefit from additional CPU power.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon EC2 instances, Amazon Elastic File System (Amazon EFS)</strong></p>
 <p><strong>Amazon Elastic File System (Amazon EFS), AWS Lambda functions</strong></p>
 <p><strong>AWS Lambda functions, Amazon Simple Storage Service (Amazon S3)</strong></p>
 <p>AWS Compute Optimizer does not provide optimization recommendations for S3 and EFS, so these options are incorrect.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/compute-optimizer/faqs/">https://aws.amazon.com/compute-optimizer/faqs/</a></p>
</div>

**Question 54**

54. Which of the following use-cases is NOT supported by Amazon Rekognition?
*  A. Identify person in a photo
*  B. Detect text in a photo
*  C. Quickly resize photos to create thumbnails
*  D. Label objects in a photo

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>Quickly resize photos to create thumbnails</strong> - You cannot use Rekognition to resize photos to create thumbnails.</p>
 <p>With Amazon Rekognition, you can identify objects, people, text, scenes, and activities in images and videos, as well as detect any inappropriate content. Amazon Rekognition also provides highly accurate facial analysis and facial search capabilities that you can use to detect, analyze, and compare faces for a wide variety of user verification, people counting, and public safety use cases.</p>
 <p>Amazon Rekognition Use-Cases:</p>
 <p><img src="./images/pt2-q65-i1.jpg"> via - <a href="https://aws.amazon.com/rekognition/">https://aws.amazon.com/rekognition/</a></p>
 <p><img src="./images/pt2-q65-i2.jpg"> via - <a href="https://aws.amazon.com/rekognition/">https://aws.amazon.com/rekognition/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Identify person in a photo</strong></p>
 <p><strong>Detect text in a photo</strong></p>
 <p><strong>Label objects in a photo</strong></p>
 <p>As mentioned in the explanation above, Amazon Rekognition can be used to build solutions for these use-cases.</p>
 <p>Reference: <a href="https://aws.amazon.com/rekognition/">https://aws.amazon.com/rekognition/</a></p>
</div>

**Question 55**

55. Which of the following is correct about AWS "Developer" Support plan?
*  A. Allows one contact to open a limited number of cases per month
*  B. Allows unlimited contacts to open a limited number of cases per month
*  C. Allows one contact to open unlimited cases
*  D. Allows unlimited contacts to open unlimited cases

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Allows one contact to open unlimited cases</strong></p>
 <p>AWS Developer Support plan allows one primary contact to open unlimited cases.</p>
 <p>Incorrect options:</p>
 <p><strong>Allows one contact to open a limited number of cases per month</strong> - As mentioned earlier, the AWS Developer Support plan allows one primary contact to open unlimited cases. So this option is incorrect.</p>
 <p><strong>Allows unlimited contacts to open unlimited cases</strong> - This is supported by AWS "Business" and "Enterprise" Support plans. So this is incorrect for AWS "Developer" Support plan.</p>
 <p><strong>Allows unlimited contacts to open a limited number of cases per month</strong> - This is a made-up option and has been added as a distractor.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/premiumsupport/plans/">https://aws.amazon.com/premiumsupport/plans/</a></p>
</div>

**Question 56**

56. Which of the following is the correct statement regarding the AWS Storage services?
*  A. S3 is object based storage, EBS is file based storage and EFS is block based storage
*  B. S3 is file based storage, EBS is block based storage and EFS is object based storage
*  C. S3 is object based storage, EBS is block based storage and EFS is file based storage
*  D. S3 is block based storage, EBS is object based storage and EFS is file based storage

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>S3 is object based storage, EBS is block based storage and EFS is file based storage</strong></p>
 <p>Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed, elastic NFS file system.</p>
 <p>Amazon Elastic Block Store (EBS) is an easy to use, high-performance block storage service designed for use with Amazon Elastic Compute Cloud (EC2) for both throughput and transaction-intensive workloads at any scale.</p>
 <p>Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance.</p>
 <p>Incorrect options:</p>
 <p><strong>S3 is block based storage, EBS is object based storage and EFS is file based storage</strong></p>
 <p><strong>S3 is object based storage, EBS is file based storage and EFS is block based storage</strong></p>
 <p><strong>S3 is file based storage, EBS is block based storage and EFS is object based storage</strong></p>
 <p>These three options contradict the details provided earlier in the explanation, so these options are incorrect.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/s3/">https://aws.amazon.com/s3/</a></p>
 <p><a href="https://aws.amazon.com/ebs/">https://aws.amazon.com/ebs/</a></p>
 <p><a href="https://aws.amazon.com/efs/">https://aws.amazon.com/efs/</a></p>
</div>

**Question 57**

57. Which AWS service can be used to provision resources to run big data workloads on Hadoop clusters?
*  A. Amazon EC2
*  B. Amazon EMR
*  C. AWS Batch
*  D. AWS Step Function

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon EMR</strong> - Amazon EMR is the industry-leading cloud big data platform for processing vast amounts of data using open source tools such as Hadoop, Apache Spark, Apache Hive, Apache HBase, Apache Flink, Apache Hudi, and Presto. Amazon EMR can be used to provision resources to run big data workloads on Hadoop clusters.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Step Function</strong> - AWS Step Function lets you coordinate multiple AWS services into serverless workflows. You can design and run workflows that stitch together services such as AWS Lambda, AWS Glue and Amazon SageMaker.</p>
 <p>AWS Step Functions Overview: <img src="./images/sfn_how-it-works.f795601e8338db32506b9abb01e71704f483fc81.png"> via - <a href="https://aws.amazon.com/step-functions/">https://aws.amazon.com/step-functions/</a></p>
 <p><strong>AWS Batch</strong></p>
 <p>You can use AWS Batch to plan, schedule and execute your batch computing workloads across the full range of AWS compute services. AWS Batch dynamically provisions the optimal quantity and type of compute resources (e.g., CPU or memory optimized instances) based on the volume and specific resource requirements of the batch jobs submitted. AWS Batch provisions compute resources and optimizes the job distribution based on the volume and resource requirements of the submitted batch jobs.</p>
 <p>Please review the common use-cases for AWS Batch: <img src="./images/pt2-q64-i1.jpg"> via - <a href="https://aws.amazon.com/batch/">https://aws.amazon.com/batch/</a></p>
 <p>Exam Alert:</p>
 <p>Understand the difference between AWS Step Functions and AWS Batch. You may get questions to choose one over the other. AWS Batch runs batch computing workloads by provisioning the compute resources. AWS Step Function does not provision any resources. Step Function only orchestrates AWS services required for a given workflow. You cannot use Step Functions to plan, schedule and execute your batch computing workloads by provisioning underlying resources.</p>
 <p><strong>Amazon EC2</strong> - Amazon EC2 is a web service that provides secure, resizable compute capacity in the AWS cloud. You can use EC2 to provision virtual servers on AWS Cloud. You cannot use EC2 to plan, schedule and execute your batch computing workloads by provisioning underlying resources.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/emr/">https://aws.amazon.com/emr/</a></p>
 <p><a href="https://aws.amazon.com/batch/">https://aws.amazon.com/batch/</a></p>
 <p><a href="https://aws.amazon.com/step-functions/">https://aws.amazon.com/step-functions/</a></p>
</div>

**Question 58**

58. As per the AWS shared responsibility model, which of the following is a responsibility of the customer from a security and compliance point of view?
*  A. Configuration management for AWS global infrastructure
*  B. Availability Zone infrastructure management
*  C. Patching/fixing flaws within the AWS infrastructure
*  D. Managing patches of the guest operating system on Amazon EC2

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Managing patches of the guest operating system on Amazon EC2</strong></p>
 <p>Security and Compliance is a shared responsibility between AWS and the customer. This shared model can help relieve the customer’s operational burden as AWS operates, manages, and controls the components from the host operating system and virtualization layer down to the physical security of the facilities in which the service operates.</p>
 <p>As per the AWS shared responsibility model, the customer is responsible for security "in" the cloud. Customers that deploy an Amazon EC2 instance are responsible for the management of the guest operating system (including updates and security patches), any application software or utilities installed by the customer on the instances, and the configuration of the AWS-provided firewall (called a security group) on each instance.</p>
 <p>Exam Alert:</p>
 <p>Please review the Shared Responsibility Model in detail as you can expect multiple questions on the shared responsibility model in the exam: <img src="./images/Shared_Responsibility_Model_V2.59d1eccec334b366627e9295b304202faf7b899b.jpg"> via - <a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Configuration management for AWS global infrastructure</strong></p>
 <p><strong>Availability Zone infrastructure management</strong></p>
 <p><strong>Patching/fixing flaws within the AWS infrastructure</strong></p>
 <p>AWS is responsible for “Security of the Cloud”. AWS is responsible for protecting the infrastructure that runs all of the services offered in the AWS Cloud. This infrastructure is composed of the hardware, software, networking, and facilities that run AWS Cloud services. Hence, all of the above options - Configuration management for AWS global infrastructure, Availability Zone infrastructure management, and patching/fixing flaws within the AWS infrastructure are responsibilities of AWS.</p>
 <p>Reference: <a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
</div>

**Question 59**

59. What are the different gateway types supported by AWS Storage Gateway service?
*  A. Tape Gateway, Object Gateway and Volume Gateway
*  B. Tape Gateway, File Gateway and Volume Gateway
*  C. Object Gateway, File Gateway and Block Gateway
*  D. Tape Gateway, File Gateway and Block Gateway

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Tape Gateway, File Gateway and Volume Gateway</strong></p>
 <p>AWS Storage Gateway is a hybrid cloud storage service that connects your existing on-premises environments with the AWS Cloud. Customers use Storage Gateway to simplify storage management and reduce costs for key hybrid cloud storage use cases. These include moving tape backups to the cloud, reducing on-premises storage with cloud-backed file shares, providing low latency access to data in AWS for on-premises applications, as well as various migration, archiving, processing, and disaster recovery use cases.</p>
 <p>AWS Storage Gateway service provides three different types of gateways – Tape Gateway, File Gateway, and Volume Gateway – that seamlessly connect on-premises applications to cloud storage, caching data locally for low-latency access.</p>
 <p>Gateway Storage Types Overview: <img src="./images/pt2-q63-i1.jpg"> via - <a href="https://aws.amazon.com/storagegateway/features/">https://aws.amazon.com/storagegateway/features/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Object Gateway, File Gateway and Block Gateway</strong></p>
 <p><strong>Tape Gateway, Object Gateway and Volume Gateway</strong></p>
 <p><strong>Tape Gateway, File Gateway and Block Gateway</strong></p>
 <p>Block Gateway and Object Gateway are made-up options, so these three options are incorrect.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/storagegateway/features/">https://aws.amazon.com/storagegateway/features/</a></p>
</div>

**Question 60**

60. Access Key ID and Secret Access Key are tied to which of the following AWS Identity and Access Management entities?
*  A. AWS Policy
*  B. IAM Role
*  C. IAM Group
*  D. IAM User

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option: <strong>IAM User</strong></p>
 <p>Access keys are long-term credentials for an IAM user or the AWS account root user. You can use access keys to sign programmatic requests to the AWS CLI or AWS API (directly or using the AWS SDK). Access keys consist of two parts: an access key ID (for example, AKIAIOSFODNN7EXAMPLE) and a secret access key (for example, wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY). As a user name and password, you must use both the access key ID and secret access key together to authenticate your requests. Access Keys are secret, just like a password. You should never share them.</p>
 <p>Incorrect options:</p>
 <p><strong>IAM Role</strong> - An IAM role is similar to an IAM user, in that it is an AWS identity with permission policies that determine what the identity can and cannot do in AWS. However, instead of being uniquely associated with one person, a role is intended to be assumable by anyone who needs it.</p>
 <p><strong>IAM Group</strong> - An IAM group is a collection of IAM users. Groups let you specify permissions for multiple users, which can make it easier to manage the permissions for those users.</p>
 <p><strong>AWS Policy</strong> - You manage access in AWS by creating policies and attaching them to IAM identities (users, groups of users, or roles) or AWS resources. A policy is an object in AWS that, when associated with an identity or resource, defines their permissions.</p>
 <p>Access keys are not tied to the IAM role, IAM group, or AWS policy. So all three options are incorrect.</p>
 <p>Reference: <a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_access-keys.html">https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_access-keys.html</a></p>
</div>

**Question 61**

61. According to the AWS Shared Responsibility Model, which of the following are responsibilities of the customer for Amazon RDS?
*  A. Database encryption
*  B. Applying patches to the RDS database
*  C. Managing the underlying server hardware on which RDS runs
*  D. Applying patches to the underlying OS

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p>Security and Compliance is a shared responsibility between AWS and the customer. This shared model can help relieve the customer’s operational burden as AWS operates, manages and controls the components from the host operating system and virtualization layer down to the physical security of the facilities in which the service operates.</p>
 <p><strong>Database encryption</strong> - Under the shared model, customers are responsible for managing their data, including data encryption.</p>
 <p>Shared Responsibility Model Overview: <img src="./images/Shared_Responsibility_Model_V2.59d1eccec334b366627e9295b304202faf7b899b.jpg"> via - <a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
 <p>Incorrect options:</p>
 <p>According to the AWS Shared Responsibility Model, AWS is responsible for "Security of the Cloud". This includes protecting the infrastructure that runs all of the services offered in the AWS Cloud. This infrastructure is composed of the hardware, software, networking, and facilities that run AWS Cloud services.</p>
 <p>Amazon Relational Database Service (Amazon RDS) is a managed service that makes it easy to set up, operate, and scale a relational database in the cloud.</p>
 <p><strong>Managing the underlying server hardware on which RDS runs</strong> - Since RDS is a managed service, the underlying infrastructure is the responsibility of AWS.</p>
 <p><strong>Applying patches to the RDS database</strong> - Since RDS is a managed service, the underlying infrastructure is the responsibility of AWS.</p>
 <p><strong>Applying patches to the underlying OS</strong> - Since RDS is a managed service, the underlying infrastructure is the responsibility of AWS.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
</div>

**Question 62**

62. Which AWS service can be used to store, manage, and deploy Docker container images?
*  A. Amazon Elastic Container Registry (ECR)
*  B. Amazon EC2
*  C. Amazon Lambda
*  D. Amazon Elastic Container Service (ECS)

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon Elastic Container Registry (ECR)</strong> - Amazon Elastic Container Registry (ECR) can be used to store, manage, and deploy Docker container images. Amazon ECR eliminates the need to operate your container repositories. You can then pull your docker images from ECR and run those on Amazon Elastic Container Service (ECS).</p>
 <p>Please see this schematic diagram to understand how ECR works: <img src="./images/Product-Page-Diagram_Amazon-ECR.bf2e7a03447ed3aba97a70e5f4aead46a5e04547.png"> via - <a href="https://aws.amazon.com/ecr/">https://aws.amazon.com/ecr/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Elastic Container Service (ECS)</strong> - Amazon Elastic Container Service (Amazon ECS) is a highly scalable, fast, container management service that makes it easy to run, stop, and manage Docker containers on a cluster. You cannot use ECS to store and deploy docker container images.</p>
 <p>Please see this schematic diagram to understand how ECS works: <img src="./images/product-page-diagram_ECS_1.86ebd8c223ec8b55aa1903c423fbe4e672f3daf7.png"> via - <a href="https://aws.amazon.com/ecs/">https://aws.amazon.com/ecs/</a></p>
 <p><strong>Amazon EC2</strong> - Amazon EC2 is a web service that provides secure, resizable compute capacity in the AWS cloud. You can use EC2 to provision virtual servers on AWS Cloud. You cannot use EC2 to store and deploy docker container images.</p>
 <p><strong>Amazon Lambda</strong> - AWS Lambda lets you run code without provisioning or managing servers. You pay only for the compute time you consume. You cannot use Lambda to store and deploy docker container images.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/ecr/">https://aws.amazon.com/ecr/</a></p>
 <p><a href="https://aws.amazon.com/ecs/">https://aws.amazon.com/ecs/</a></p>
</div>

**Question 63**

63. A photo sharing web application wants to store thumbnails of user-uploaded images on Amazon S3. The thumbnails are rarely used but need to be immediately accessible from the web application. The thumbnails can be regenerated easily if they are lost. Which is the most cost-effective way to store these thumbnails on S3?
*  A. Use S3 One-Zone Infrequent Access (One-Zone IA) to store the thumbnails
*  B. Use S3 Standard to store the thumbnails
*  C. Use S3 Glacier to store the thumbnails
*  D. Use S3 Standard Infrequent Access (Standard-IA) to store the thumbnails

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Use S3 One-Zone Infrequent Access (One-Zone IA) to store the thumbnails</strong></p>
 <p>S3 One Zone-IA is for data that is accessed less frequently but requires rapid access when needed. Unlike other S3 Storage Classes which store data in a minimum of three Availability Zones (AZs), S3 One Zone-IA stores data in a single AZ and costs 20% less than S3 Standard-IA. S3 One Zone-IA offers the same high durability, high throughput, and low latency of S3 Standard, with a low per GB storage price and per GB retrieval fee. Although S3 One Zone-IA offers less availability than S3 Standard but that's not an issue for the given use-case since the thumbnails can be regenerated easily.</p>
 <p>As the thumbnails are rarely used but need to be rapidly accessed when required, so S3 One Zone-IA is the best choice for this use-case.</p>
 <p>Exam Alert:</p>
 <p>Please review this detailed comparison on S3 Storage Classes as you can expect a few questions on this aspect of S3: <img src="./images/pt2-q16-i1.jpg"> via - <a href="https://aws.amazon.com/s3/storage-classes/">https://aws.amazon.com/s3/storage-classes/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Use S3 Standard Infrequent Access (Standard-IA) to store the thumbnails</strong> - S3 Standard-IA storage class is for data that is accessed less frequently but requires rapid access when needed. S3 Standard-IA matches the high durability, high throughput, and low latency of S3 Standard, with a low per GB storage price and per GB retrieval fee. S3 One Zone-IA costs 20% less than S3 Standard-IA, so this option is incorrect.</p>
 <p><strong>Use S3 Standard to store the thumbnails</strong> - S3 Standard offers high durability, availability, and performance object storage for frequently accessed data. As described above, S3 One Zone-IA is a better fit than S3 Standard, hence using S3 standard is ruled out for the given use-case.</p>
 <p><strong>Use S3 Glacier to store the thumbnails</strong> - S3 Glacier is a secure, durable, and low-cost storage class for data archiving. Although Glacier is cheaper than One Zone-IA, however the retrieval time ranges from a minute to hours, so this option is also ruled out for the given use-case.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/s3/storage-classes/">https://aws.amazon.com/s3/storage-classes/</a></p>
</div>

**Question 64**

64. An organization deploys its IT infrastructure in a combination of its on-premises data center along with AWS Cloud. How would you categorize this deployment model?
*  A. Mixed deployment
*  B. Hybrid deployment
*  C. Cloud deployment
*  D. Private deployment

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Hybrid deployment</strong></p>
 <p>A hybrid deployment is a way to connect your on-premises infrastructure to the cloud. The most common method of hybrid deployment is between the cloud and existing on-premises infrastructure to extend an organization's infrastructure into the cloud while connecting cloud resources to internal systems.</p>
 <p>Overview of Cloud Computing Deployment Models: <img src="./images/pt2-q19-i1.jpg"> via - <a href="https://aws.amazon.com/types-of-cloud-computing/">https://aws.amazon.com/types-of-cloud-computing/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Cloud deployment</strong> - For this type of deployment, a cloud-based application is fully deployed in the cloud, and all parts of the application run in the cloud. Applications in the cloud have either been created in the cloud or have been migrated from an existing infrastructure to take advantage of the benefits of cloud computing.</p>
 <p><strong>Private deployment</strong> - For this deployment model, resources are deployed on-premises using virtualization technologies. On-premises deployment does not provide many of the benefits of cloud computing but is sometimes sought for its ability to provide dedicated resources.</p>
 <p><strong>Mixed deployment</strong> - This is a made-up option and has been added as a distractor.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/types-of-cloud-computing/">https://aws.amazon.com/types-of-cloud-computing/</a></p>
 <p><a href="https://aws.amazon.com/hybrid/">https://aws.amazon.com/hybrid/</a></p>
</div>

**Question 65**

65. A startup is looking for 24x7 phone based technical support for his AWS account. Which of the following is the MOST cost-effective AWS support plan for this use-case?
*  A. Basic
*  B. Enterprise
*  C. Developer
*  D. Business

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p>AWS offers three different support plans to cater to each of its customers - Developer, Business, and Enterprise Support plans.</p>
 <p>A basic support plan is included for all AWS customers.</p>
 <p><strong>Business</strong> - AWS recommends Business Support if you have production workloads on AWS and want 24x7 phone, email and chat access to technical support and architectural guidance in the context of your specific use-cases. Enterprise Support plan also provides 24x7 phone, email and chat access to technical support however it's much costlier than Business Support plan. Developer plan does not provide 24x7 phone based technical support. Therefore Business Support plan is the correct option for the given use-case.</p>
 <p>Exam Alert:</p>
 <p>Please review the differences between the Developer, Business, and Enterprise support plans as you can expect at least a couple of questions on the exam:</p>
 <p><img src="./images/pt2-q38-i1.jpg"></p>
 <p><img src="./images/pt2-q38-i2.jpg"></p>
 <p>via - <a href="https://aws.amazon.com/premiumsupport/plans/">https://aws.amazon.com/premiumsupport/plans/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Basic</strong> - The basic plan only provides access to the following:</p>
 <p>Customer Service &amp; Communities - 24x7 access to customer service, documentation, whitepapers, and support forums. AWS Trusted Advisor - Access to the 7 core Trusted Advisor checks and guidance to provision your resources following best practices to increase performance and improve security. AWS Personal Health Dashboard - A personalized view of the health of AWS services, and alerts when your resources are impacted.</p>
 <p><strong>Developer</strong> - AWS recommends Developer Support if you are testing or doing early development on AWS and want the ability to get email based technical support during business hours as well as general architectural guidance as you build and test. This plan does not support 24x7 phone based technical support.</p>
 <p><strong>Enterprise</strong> - AWS Enterprise Support provides customers with concierge-like service where the main focus is helping the customer achieve their outcomes and find success in the cloud. With Enterprise Support, you get 24x7 technical support from high-quality engineers, tools and technology to automatically manage the health of your environment, consultative architectural guidance delivered in the context of your applications and use-cases, and a designated Technical Account Manager (TAM) to coordinate access to proactive/preventative programs and AWS subject matter experts. Enterprise Support plan provides 24x7 phone, email and chat access to technical support however it's much costlier than Business Support plan.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/premiumsupport/plans/">https://aws.amazon.com/premiumsupport/plans/</a></p>
</div>
