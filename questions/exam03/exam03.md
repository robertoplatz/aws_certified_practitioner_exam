# AWS Certified Practitioner Exam

## Exam 03

**Question 1**

1. Which budget types can be created under AWS Budgets (Select three)?
*  A. Hardware budget
*  B. Usage budget
*  C. Resource budget
*  D. Reservation budget
*  E. Software budget
*  F. Cost budget

**Answer** B, D, F

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p>AWS Budgets enable you to plan your service usage, service costs, and instance reservations. AWS Budgets information is updated up to three times a day. Updates typically occur between 8 to 12 hours after the previous update. Budgets track your unblended costs, subscriptions, refunds, and RIs. There are four different budget types you can create under AWS Budgets - Cost budget, Usage budget, Reservation budget and Savings Plans budget.</p>
 <p><strong>Cost budget</strong> - Helps you plan how much you want to spend on a service.</p>
 <p><strong>Usage budget</strong> - Helps you plan how much you want to use one or more services.</p>
 <p><strong>Reservation budget</strong> - This helps you track the usage of your Reserved Instances (RI). Two ways of doing it - RI utilization budgets (This lets you see if your RIs are unused or under-utilized), RI coverage budgets (This lets you see how much of your instance usage is covered by a reservation).</p>
 <p>Incorrect options:</p>
 <p><strong>Resource budget</strong> - This is a made-up option and has been added as a distractor</p>
 <p><strong>Software budget</strong> - This is a made-up option and has been added as a distractor</p>
 <p><strong>Hardware budget</strong> - This is a made-up option and has been added as a distractor</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/budgets-managing-costs.html">This is a made-up option and has been added as a distractor</a></p>
</div>

**Question 2**

2. A leading research firm needs to access information available in old patents and documents (such as PDFs, Text Files, Word documents, etc) present in its huge knowledge base. The firm is looking for a powerful search tool that can dig into these knowledge resources and return the most relevant files/documents. Which of the following is the correct service to address this requirement?
*  A. Amazon Kendra
*  B. Amazon Personalize
*  C. Amazon Lex
*  D. Amazon Comprehend

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option: <strong>Amazon Kendra</strong> - Amazon Kendra is an intelligent search service powered by machine learning. Kendra reimagines enterprise search for your websites and applications so your employees and customers can easily find the content they are looking for, even when it’s scattered across multiple locations and content repositories within your organization.</p>
 <p>Using Amazon Kendra, you can stop searching through troves of unstructured data and discover the right answers to your questions, when you need them. Amazon Kendra is a fully managed service, so there are no servers to provision, and no machine learning models to build, train, or deploy. Kendra supports unstructured and semi-structured data in .html, MS Office (.doc, .ppt), PDF, and text formats.</p>
 <p>Unlike conventional search technology, natural language search capabilities return the answers you’re looking for quickly and accurately, no matter where the information lives within your organization.</p>
 <p>Kendra’s deep learning models come pre-trained across 14 industry domains, allowing it to extract more accurate answers across a wide range of business use cases from the get-go. You can also fine-tune search results by manually adjusting the importance of data sources, authors, freshness, or using custom tags.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Personalize</strong> - Amazon Personalize enables developers to build applications with the same machine learning (ML) technology used by Amazon.com for real-time personalized recommendations. Amazon Personalize makes it easy for developers to build applications capable of delivering a wide array of personalization experiences, including specific product recommendations, personalized product re-ranking, and customized direct marketing.</p>
 <p><strong>Amazon Comprehend</strong> - Amazon Comprehend is a natural-language processing (NLP) service that uses machine learning to uncover information in unstructured data. Instead of combing through documents, the process is simplified and unseen information is easier to understand.</p>
 <p>Amazon Kendra provides ML-powered search capabilities for all unstructured data customers store in AWS. Kendra offers easy-to-use native connectors to popular AWS repository types such as S3 and RDS databases. Other AI services such as Amazon Comprehend, Amazon Transcribe, and Amazon Comprehend Medical can be used to pre-process documents, generate searchable text, extract entities, and enrich their metadata for more specialized search experiences.</p>
 <p><strong>Amazon Lex</strong> - Amazon Lex is a service for building conversational interfaces into any application using voice and text. Amazon Lex provides the advanced deep learning functionalities of automatic speech recognition (ASR) for converting speech to text, and natural language understanding (NLU) to recognize the intent of the text, to enable you to build applications with highly engaging user experiences and lifelike conversational interactions.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/kendra/">https://aws.amazon.com/kendra/</a></p>
</div>

**Question 3**

3. An organization maintains separate VPCs for each of its departments. With expanding business, the organization now wants to connect all VPCs for better departmental collaboration. Which AWS service will help the organization tackle the issue effectively?
*  A. Site to Site VPN
*  B. AWS Direct Connect
*  C. AWS Transit Gateway
*  D. VPC Peering

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Transit Gateway</strong></p>
 <p>AWS Transit Gateway connects VPCs and on-premises networks through a central hub. This simplifies your network and puts an end to complex peering relationships. It acts as a cloud router – each new connection is only made once. As you expand globally, inter-Region peering connects AWS Transit Gateways using the AWS global network. Your data is automatically encrypted and never travels over the public internet.</p>
 <p>How Transit Gateway can simplify your network: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q5-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/transit-gateway/">https://aws.amazon.com/transit-gateway/</a></p>
 <p>Incorrect options:</p>
 <p><strong>VPC Peering</strong> - A VPC peering connection is a networking connection between two VPCs that enables you to route traffic between them privately. VPC peering is not transitive, a separate VPC peering connection has to be made between two VPCs that need to talk to each other. With growing VPCs, this gets difficult to manage.</p>
 <p>Transitive VPC Peering is not allowed: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/transitive-peering-diagram.png?raw=true"> via - <a href="https://docs.aws.amazon.com/vpc/latest/peering/invalid-peering-configurations.html">https://docs.aws.amazon.com/vpc/latest/peering/invalid-peering-configurations.html</a></p>
 <p><strong>AWS Direct Connect</strong> - AWS Direct Connect creates a dedicated private connection from a remote network to your VPC. This is a private connection and does not use the public internet. Takes at least a month to establish this connection. Direct Connect cannot be used to interconnect VPCs.</p>
 <p><strong>Site to Site VPN</strong> - AWS Site-to-Site VPN creates a secure connection between your data center or branch office and your AWS cloud resources. This connection goes over the public internet. Site to Site VPN cannot be used to interconnect VPCs.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/transit-gateway/">https://aws.amazon.com/transit-gateway/</a></p>
</div>

**Question 4**

4. AWS Identity and Access Management (IAM) policies are written as JSON documents. Which of the following are mandatory elements of an IAM policy?
*  A. Effect, Sid
*  B. Action, Condition
*  C. Effect, Action
*  D. Sid, Principal

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Effect, Action</strong> - Most policies are stored in AWS as JSON documents. Identity-based policies and policies used to set permissions boundaries are JSON policy documents that you attach to a user or role. Resource-based policies are JSON policy documents that you attach to a resource.</p>
 <p>A JSON policy document includes these elements:</p>
 <ol>
  <li>Optional policy-wide information at the top of the document</li>
  <li>One or more individual statements</li>
 </ol>
 <p>Each statement includes information about a single permission. The information in a statement is contained within a series of elements.</p>
 <ol>
  <li><p>Version – Specify the version of the policy language that you want to use. As a best practice, use the latest 2012-10-17 version.</p></li>
  <li><p>Statement – Use this main policy element as a container for the following elements. You can include more than one statement in a policy.</p>
   <ol>
    <li><p>Sid (Optional) – Include an optional statement ID to differentiate between your statements.</p></li>
    <li><p>Effect – Use Allow or Deny to indicate whether the policy allows or denies access.</p></li>
    <li><p>Principal (Required in only some circumstances) – If you create a resource-based policy, you must indicate the account, user, role, or federated user to which you would like to allow or deny access. If you are creating an IAM permissions policy to attach to a user or role, you cannot include this element. The principal is implied as that user or role.</p></li>
    <li><p>Action – Include a list of actions that the policy allows or denies.</p></li>
    <li><p>Resource (Required in only some circumstances) – If you create an IAM permissions policy, you must specify a list of resources to which the actions apply. If you create a resource-based policy, this element is optional. If you do not include this element, then the resource to which the action applies is the resource to which the policy is attached.</p></li>
    <li><p>Condition (Optional) – Specify the circumstances under which the policy grants permission.</p></li>
   </ol></li>
 </ol>
 <p>Incorrect options:</p>
 <p><strong>Sid, Principal</strong></p>
 <p><strong>Action, Condition</strong></p>
 <p><strong>Effect, Sid</strong></p>
 <p>These three options contradict the explanation provided above, so these options are incorrect.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html#access_policies-json">https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html#access_policies-json</a></p>
</div>

**Question 5**

5. A company has a static website hosted on an S3 bucket in an AWS Region in Asia. Although most of its users are in Asia, now it wants to drive growth globally. How can it improve the global performance of its static website?
*  A. Use S3 Transfer Acceleration to improve the performance of your website
*  B. Use CloudWatch to improve the performance of your website
*  C. Use CloudFront to improve the performance of your website
*  D. Use WAF to improve the performance of your website

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Use CloudFront to improve the performance of your website</strong></p>
 <p>You can use Amazon CloudFront to improve the performance of your website. CloudFront makes your website files (such as HTML, images, and video) available from data centers around the world (called edge locations). When a visitor requests a file from your website, CloudFront automatically redirects the request to a copy of the file at the nearest edge location. This results in faster download times than if the visitor had requested the content from a data center that is located farther away.</p>
 <p>Incorrect options:</p>
 <p><strong>Use CloudFormation to improve the performance of your website</strong> - AWS CloudFormation allows you to use programming languages or a simple text file to model and provision, in an automated and secure manner, all the resources needed for your applications across all regions and accounts. CloudFormation cannot be used to improve the performance of a static website.</p>
 <p><strong>Use WAF to improve the performance of your website</strong> - By using AWS WAF, you can configure web access control lists (Web ACLs) on your CloudFront distributions or Application Load Balancers to filter and block requests based on request signatures. Besides, by using AWS WAF's rate-based rules, you can automatically block the IP addresses of bad actors when requests matching a rule exceed a threshold that you define. WAF cannot be used to improve the performance of a static website.</p>
 <p><strong>Use S3 Transfer Acceleration to improve the performance of your website</strong> - Amazon S3 Transfer Acceleration enables fast, easy, and secure transfers of files over long distances between your client and an S3 bucket. Transfer Acceleration takes advantage of Amazon CloudFront’s globally distributed edge locations. As the data arrives at an edge location, data is routed to Amazon S3 over an optimized network path. Transfer Acceleration cannot be used to improve the performance of a static website.</p>
 <p>References:</p>
 <p><a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/website-hosting-cloudfront-walkthrough.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/website-hosting-cloudfront-walkthrough.html</a></p>
 <p><a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/transfer-acceleration.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/transfer-acceleration.html</a></p>
</div>

**Question 6**

6. A startup wants to set up its IT infrastructure on AWS Cloud. The CTO would like to receive detailed reports that break down the startup's AWS costs by the hour in an S3 bucket. As a Cloud Practitioner, which AWS service would you recommend for this use-case?
*  A. AWS Cost Explorer
*  B. AWS Budgets
*  C. AWS Cost and Usage Reports
*  D. AWS Pricing Calculator

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Cost and Usage Reports</strong></p>
 <p>The AWS Cost and Usage Reports (AWS CUR) contains the most comprehensive set of cost and usage data available. You can use Cost and Usage Reports to publish your AWS billing reports to an Amazon Simple Storage Service (Amazon S3) bucket that you own. You can receive reports that break down your costs by the hour or month, by product or product resource, or by tags that you define yourself. AWS updates the report in your bucket once a day in comma-separated value (CSV) format.</p>
 <p>AWS Cost and Usage Reports Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q59-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/cur/latest/userguide/what-is-cur.html">https://docs.aws.amazon.com/cur/latest/userguide/what-is-cur.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS Pricing Calculator</strong> - AWS Pricing Calculator lets you explore AWS services and create an estimate for the cost of your use cases on AWS. You can model your solutions before building them, explore the price points and calculations behind your estimate, and find the available instance types and contract terms that meet your needs. This enables you to make informed decisions about using AWS. You can plan your AWS costs and usage or price out setting up a new set of instances and services.</p>
 <p><strong>AWS Cost Explorer</strong> - AWS Cost Explorer has an easy-to-use interface that lets you visualize, understand, and manage your AWS costs and usage over time. AWS Cost Explorer includes a default report that helps you visualize the costs and usage associated with your top five cost-accruing AWS services, and gives you a detailed breakdown of all services in the table view. The reports let you adjust the time range to view historical data going back up to twelve months to gain an understanding of your cost trends. AWS Cost Explorer cannot provide a detailed report of your AWS costs by the hour into an S3 bucket.</p>
 <p><strong>AWS Budgets</strong> - AWS Budgets gives the ability to set custom budgets that alert you when your costs or usage exceed (or are forecasted to exceed) your budgeted amount. You can also use AWS Budgets to set reservation utilization or coverage targets and receive alerts when your utilization drops below the threshold you define. Budgets can be created at the monthly, quarterly, or yearly level, and you can customize the start and end dates. You can further refine your budget to track costs associated with multiple dimensions, such as AWS service, linked account, tag, and others. AWS Budgets cannot provide the estimate of the monthly AWS bill based on the list of AWS services. AWS Budgets cannot provide a detailed break down of your AWS costs by the hour.</p>
 <p>Exam Alert:</p>
 <p>Please review the differences between "AWS Cost and Usage Reports" and "AWS Cost Explorer". Think of "AWS Cost and Usage Reports" as a cost management tool providing the most detailed cost and usage data for your AWS account. It can provide reports that break down your costs by the hour into your S3 bucket. On the other hand, "AWS Cost Explorer" is more of a high-level cost management tool that helps you visualize the costs and usage associated with your AWS account.</p>
 <p>"AWS Cost Explorer" vs "AWS Cost and Usage Reports": <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q59-i2.png?raw=true"> via - <a href="https://aws.amazon.com/aws-cost-management/aws-cost-explorer/">https://aws.amazon.com/aws-cost-management/aws-cost-explorer/</a></p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q59-i3.png?raw=true"> via - <a href="https://aws.amazon.com/aws-cost-management/aws-cost-and-usage-reporting/">https://aws.amazon.com/aws-cost-management/aws-cost-and-usage-reporting/</a></p>
 <p>References:</p>
 <p><a href="https://docs.aws.amazon.com/cur/latest/userguide/what-is-cur.html">https://docs.aws.amazon.com/cur/latest/userguide/what-is-cur.html</a></p>
 <p><a href="https://aws.amazon.com/aws-cost-management/aws-cost-explorer/">https://aws.amazon.com/aws-cost-management/aws-cost-explorer/</a></p>
 <p><a href="https://aws.amazon.com/aws-cost-management/aws-cost-and-usage-reporting/">https://aws.amazon.com/aws-cost-management/aws-cost-and-usage-reporting/</a></p>
</div>

**Question 7**

7. Which AWS service will you use to privately connect your VPC to Amazon S3?
*  A. AWS Transit Gateway
*  B. Amazon API Gateway
*  C. AWS Direct Connect
*  D. VPC Endpoint Gateway

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>VPC Endpoint Gateway</strong></p>
 <p>A VPC endpoint enables you to privately connect your VPC to supported AWS services and VPC endpoint services powered by AWS PrivateLink without requiring an internet gateway, NAT device, VPN connection, or AWS Direct Connect connection. Instances in your VPC do not require public IP addresses to communicate with resources in the service. Traffic between your VPC and the other service does not leave the Amazon network.</p>
 <p>There are two types of VPC endpoints: interface endpoints and gateway endpoints.</p>
 <p>An interface endpoint is an elastic network interface with a private IP address from the IP address range of your subnet that serves as an entry point for traffic destined to a supported service. Interface endpoints are powered by AWS PrivateLink, a technology that enables you to privately access services by using private IP addresses.</p>
 <p>A gateway endpoint is a gateway that you specify as a target for a route in your route table for traffic destined to a supported AWS service. The following AWS services are supported:</p>
 <p>Amazon S3</p>
 <p>DynamoDB</p>
 <p>Exam Alert:</p>
 <p>You may see a question around this concept in the exam. Just remember that only S3 and DynamoDB support VPC Endpoint Gateway. All other services that support VPC Endpoints use a VPC Endpoint Interface.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Direct Connect</strong> - AWS Direct Connect is a cloud service solution that makes it easy to establish a dedicated network connection from your premises to AWS. You can use AWS Direct Connect to establish a private virtual interface from your on-premise network directly to your Amazon VPC. This private connection takes at least one month for completion.</p>
 <p><strong>AWS Transit Gateway</strong> - AWS Transit Gateway connects VPCs and on-premises networks through a central hub. This simplifies your network and puts an end to complex peering relationships. It acts as a cloud router – each new connection is only made once. This service is helpful in reducing the complex topology of VPC peering when a lot of systems are involved.</p>
 <p><strong>Amazon API Gateway</strong> - Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. APIs act as the "front door" for applications to access data, business logic, or functionality from your backend services.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/vpc/latest/userguide/vpc-endpoints.html">https://docs.aws.amazon.com/vpc/latest/userguide/vpc-endpoints.html</a></p>
</div>

**Question 8**

8. Which of the following statements are CORRECT about the AWS Auto Scaling group? (Select two)
*  A. Auto Scaling group scales out and adds more number of EC2 instances to match an increase in demand
*  B. Auto Scaling group scales down and reduces the number of EC2 instances to match a decrease in demand
*  C. Auto Scaling group scales in and reduces the number of EC2 instances to match a decrease in demand
*  D. Auto Scaling group scales up and upgrades to a more powerful EC2 instance to match an increase in demand
*  E. Auto Scaling group scales down and downgrades to a less powerful EC2 instance to match a decrease in demand

**Answer** A, C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Auto Scaling group scales out and adds more number of EC2 instances to match an increase in demand</strong></p>
 <p><strong>Auto Scaling group scales in and reduces the number of EC2 instances to match a decrease in demand</strong></p>
 <p>AWS Auto Scaling monitors your applications and automatically adjusts the capacity to maintain steady, predictable performance at the lowest possible cost. Using AWS Auto Scaling, it’s easy to setup application scaling for multiple resources across multiple services in minutes. The service provides a simple, powerful user interface that lets you build scaling plans for resources including Amazon EC2 instances and Spot Fleets, Amazon ECS tasks, Amazon DynamoDB tables and indexes, and Amazon Aurora Replicas.</p>
 <p>You can use scaling policies to increase or decrease the number of instances in your group dynamically to meet changing conditions. When the scaling policy is in effect, the Auto Scaling group adjusts the desired capacity of the group, between the minimum and maximum capacity values that you specify, and launches or terminates the instances as needed. You can also scale on a schedule.</p>
 <p>Incorrect options:</p>
 <p><strong>Auto Scaling group scales down and reduces the number of EC2 instances to match a decrease in demand</strong> - A scale down refers to a downgrade to a less powerful EC2 instance. Therefore this option is incorrect.</p>
 <p><strong>Auto Scaling group scales down and downgrades to a less powerful EC2 instance to match a decrease in demand</strong></p>
 <p><strong>Auto Scaling group scales up and upgrades to a more powerful EC2 instance to match an increase in demand</strong></p>
 <p>An Auto Scaling group does not scale up or scale down, so these two options are incorrect.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/autoscaling/ec2/userguide/AutoScalingGroup.html">https://docs.aws.amazon.com/autoscaling/ec2/userguide/AutoScalingGroup.html</a></p>
</div>

**Question 9**

9. An e-commerce company uses AWS Cloud and would like to receive separate invoices for development and production environments. As a Cloud Practioner, which of the following solutions would you recommend for this use-case?
*  A. Tag all resources in the AWS account as either "development" or "production". Then use the tags to create separate invoices
*  B. Create separate AWS accounts for development and production environments to receive separate invoices
*  C. Use AWS Cost Explorer to create separate invoices for development and production environments
*  D. Use AWS Organizations to create separate invoices for development and production environments

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p>"Create separate AWS accounts for development and production environments to receive separate invoices"</p>
 <p>Every AWS account provides its own invoice end of the month. You can get separate invoices for development and production environments by setting up separate AWS accounts for each environment.</p>
 <p>Incorrect options:</p>
 <p><strong>Use AWS Organizations to create separate invoices for development and production environments</strong> - AWS Organizations helps you to centrally manage billing; control access, compliance, and security; and share resources across your AWS accounts. Using AWS Organizations, you can automate account creation, create groups of accounts to reflect your business needs, and apply policies for these groups for governance. You can also simplify billing by setting up a single payment method for all of your AWS accounts. AWS Organizations is available to all AWS customers at no additional charge.</p>
 <p>AWS Organizations cannot create separate invoices for development and production environments, rather, AWS Organizations helps you to centrally manage billing.</p>
 <p><strong>Tag all resources in the AWS account as either "development" or "production". Then use the tags to create separate invoices</strong> - You cannot create separate invoices based on tags.</p>
 <p>"Use AWS Cost Explorer to create separate invoices for development and production environments" - AWS Cost Explorer lets you explore your AWS costs and usage at both a high level and at a detailed level of analysis, and empowering you to dive deeper using several filtering dimensions (e.g., AWS Service, Region, Linked Account). AWS Cost Explorer cannot create separate invoices for development and production environments.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/billing-what-is.html">https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/billing-what-is.html</a></p>
</div>

**Question 10**

10. Which of the following are correct statements regarding the AWS Shared Responsibility Model? (Select two)
*  A. For a service like Amazon EC2, that falls under Infrastructure as a Service, AWS is responsible for maintaining guest operating system
*  B. AWS is responsible for Security "of" the Cloud
*  C. AWS is responsible for training AWS and customer employees on AWS products and services
*  D. For abstracted services like Amazon S3, AWS operates the infrastructure layer, the operating system, and platforms
*  E. Configuration Management is the responsibility of the customer

**Answer** B, D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p>Security and Compliance is a shared responsibility between AWS and the customer. This shared model can help relieve the customer’s operational burden as AWS operates, manages and controls the components from the host operating system and virtualization layer down to the physical security of the facilities in which the service operates.</p>
 <p><strong>AWS is responsible for Security "of" the Cloud</strong> - AWS is responsible for protecting the infrastructure that runs all of the services offered in the AWS Cloud. This infrastructure is composed of the hardware, software, networking, and facilities that run AWS Cloud services.</p>
 <p>"For abstracted services like Amazon S3, AWS operates the infrastructure layer, the operating system, and platforms" - For abstracted services, such as Amazon S3 and Amazon DynamoDB, AWS operates the infrastructure layer, the operating system, and platforms, and customers access the endpoints to store and retrieve data.</p>
 <p>Shared Responsibility Model Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/Shared_Responsibility_Model_V2.59d1eccec334b366627e9295b304202faf7b899b.jpg?raw=true"> via - <a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
 <p>Incorrect options:</p>
 <p><strong>For a service like Amazon EC2, that falls under Infrastructure as a Service, AWS is responsible for maintaining guest operating system</strong> - A service such as Amazon Elastic Compute Cloud (Amazon EC2) is categorized as Infrastructure as a Service (IaaS) and, as such, requires the customer to perform all of the necessary security configuration and management tasks. Customers are responsible for the management of the guest operating system (including updates and security patches), any application software or utilities installed by the customer on the instances, and the configuration of the AWS-provided firewall (called a security group) on each instance.</p>
 <p><strong>Configuration Management is the responsibility of the customer</strong> - Configuration management is a shared responsibility. AWS maintains the configuration of its infrastructure devices, but a customer is responsible for configuring their own guest operating systems, databases, and applications.</p>
 <p><strong>AWS is responsible for training AWS and customer employees on AWS products and services</strong> - Awareness &amp; Training is also a shared responsibility. AWS trains AWS employees, but a customer must train their own employees.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
</div>

**Question 11**

11. A development team is looking out for a forum where the most frequent questions and requests from AWS customers are listed along with AWS provided solutions.
*  A. AWS Service Health Dashboard
*  B. AWS Marketplace
*  C. AWS Support Center
*  D. AWS Knowledge Center

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Knowledge Center</strong> - AWS Knowledge Center contains the most frequent &amp; common questions and requests and AWS provided solutions for the same. This should be the starting point of checking for a solution or troubleshooting an issue with AWS services. The URL for Knowledge Center is <a href="https://aws.amazon.com/premiumsupport/knowledge-center/">https://aws.amazon.com/premiumsupport/knowledge-center/</a> .</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Marketplace</strong> - The AWS Marketplace enables qualified partners to market and sell their software to AWS Customers. AWS Marketplace is an online software store that helps customers find, buy, and immediately start using the software and services that run on AWS.</p>
 <p>AWS Marketplace is designed for Independent Software Vendors (ISVs), Value-Added Resellers (VARs), and Systems Integrators (SIs) who have software products they want to offer to customers in the cloud. Partners use AWS Marketplace to be up and running in days and offer their software products to customers around the world.</p>
 <p><strong>AWS Support Center</strong> - AWS Support Center is the hub for managing your Support cases. The Support Center is accessible through the AWS Management Console, providing federated access support. All Developer-level and higher Support customers can open a Technical Support case online through the Support Center. Business and Enterprise-level customers can ask Support to call at a convenient phone number or strike up a conversation with one of our engineers via chat. Enterprise-level customers can have direct access to their dedicated Technical Account Manager.</p>
 <p><strong>AWS Service Health Dashboard</strong> - Amazon Web Services publishes up-to-the-minute information on service availability in a tabular form through its Service Health Dashboard page. You can check the page any time to get current status information or subscribe to an RSS feed to be notified of interruptions to each service. The page can be accessed via the URL - <a href="https://status.aws.amazon.com/">https://status.aws.amazon.com/</a>.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/premiumsupport/knowledge-center/">https://aws.amazon.com/premiumsupport/knowledge-center/</a></p>
 <p><a href="https://status.aws.amazon.com/">https://status.aws.amazon.com/</a></p>
</div>

**Question 12**

12. Which S3 storage class offers the lowest availability?
*  A. S3 Standard
*  B. S3 Glacier
*  C. S3 One Zone-IA
*  D. S3 Intelligent-Tiering

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>S3 One Zone-IA</strong></p>
 <p>S3 One Zone-IA is for data that is accessed less frequently but requires rapid access when needed. Unlike other S3 Storage Classes which store data in a minimum of three Availability Zones (AZs), S3 One Zone-IA stores data in a single AZ.</p>
 <p>Please review this illustration for S3 Storage Classes availability. You don't need to memorize the actual numbers, just remember that S3 One Zone-IA offers the lowest availability: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q19-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/s3/storage-classes/">https://aws.amazon.com/s3/storage-classes/</a></p>
 <p>Incorrect options:</p>
 <p><strong>S3 Standard</strong> - S3 Standard offers high durability, availability, and performance object storage for frequently accessed data.</p>
 <p><strong>S3 Intelligent-Tiering</strong> - The S3 Intelligent-Tiering storage class is designed to optimize costs by automatically moving data to the most cost-effective access tier, without performance impact or operational overhead. It works by storing objects in two access tiers: one tier that is optimized for frequent access and another lower-cost tier that is optimized for infrequent access.</p>
 <p><strong>S3 Glacier</strong> - Amazon S3 Glacier is a secure, durable, and extremely low-cost Amazon S3 cloud storage class for data archiving and long-term backup. It is designed to deliver 99.999999999% durability, and provide comprehensive security and compliance capabilities that can help meet even the most stringent regulatory requirements.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/s3/storage-classes/">https://aws.amazon.com/s3/storage-classes/</a></p>
</div>

**Question 13**

13. An AWS hardware failure has impacted one of your EBS volumes. Which AWS service will alert you of the affected resources and provide a remedial action?
*  A. Amazon GuardDuty
*  B. AWS Trusted Advisor
*  C. AWS Config
*  D. AWS Personal Health Dashboard

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Personal Health Dashboard</strong></p>
 <p>AWS Personal Health Dashboard provides alerts and remediation guidance when AWS is experiencing events that may impact you. While the Service Health Dashboard displays the general status of AWS services, Personal Health Dashboard gives you a personalized view of the performance and availability of the AWS services underlying your AWS resources. The dashboard displays relevant and timely information to help you manage events in progress, and provides proactive notification to help you plan for scheduled activities. With Personal Health Dashboard, alerts are triggered by changes in the health of AWS resources, giving you event visibility, and guidance to help quickly diagnose and resolve issues. For example, in the event of an AWS hardware failure impacting one of your EBS volumes, you will get an alert that includes a list of your affected resources, a recommendation to restore your volume, and links to the steps to help you restore it from a snapshot.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon GuardDuty</strong> - Amazon GuardDuty is a threat detection service that monitors malicious activity and unauthorized behavior to protect your AWS account. GuardDuty analyzes billions of events across your AWS accounts from AWS CloudTrail (AWS user and API activity in your accounts), Amazon VPC Flow Logs (network traffic data), and DNS Logs (name query patterns).</p>
 <p><strong>AWS Config</strong> - AWS Config is a service that enables you to assess, audit, and evaluate the configurations of your AWS resources. Config continuously monitors and records your AWS resource configurations and allows you to automate the evaluation of recorded configurations against desired configurations.</p>
 <p><strong>AWS Trusted Advisor</strong> - AWS Trusted Advisor is an online tool that provides real-time guidance to help you provision your resources following AWS best practices. Whether establishing new workflows, developing applications, or as part of ongoing improvement, recommendations provided by Trusted Advisor on a regular basis help keep your solutions provisioned optimally.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/premiumsupport/technology/personal-health-dashboard/">https://aws.amazon.com/premiumsupport/technology/personal-health-dashboard/</a></p>
</div>

**Question 14**

14. Which of the following are recommended best practices for AWS IAM service? (Select two)
*  A. Share AWS account root user access keys with other administrators
*  B. Rotate credentials regularly
*  C. Grant maximum privileges to avoid assigning privileges again
*  D. Create a minimum number of accounts and share these account credentials among employees
*  E. Enable MFA for all users

**Answer** B, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Enable MFA for all users</strong> - AWS recommends that you require multi-factor authentication (MFA) for all users in your account. With MFA, users have a device that generates a response to an authentication challenge. Both the user's credentials and the device-generated response are required to complete the sign-in process.</p>
 <p><strong>Rotate credentials regularly</strong> - AWS recommends that you change your own passwords and access keys regularly, and make sure that all IAM users in your account do as well. That way, if a password or access key is compromised without your knowledge, you limit how long the credentials can be used to access your resources. You can apply a password policy to your account to require all your IAM users to rotate their passwords.</p>
 <p>AWS IAM security best practices: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q21-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html">https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html</a></p>
 <p>Incorrect options: <strong>Create a minimum number of accounts and share these account credentials among employees</strong> - AWS recommends that user account credentials should not be shared between users.</p>
 <p><strong>Grant maximum privileges to avoid assigning privileges again</strong> - AWS recommends granting the least privileges required to complete a certain job and avoid giving excessive privileges which can be misused.</p>
 <p><strong>Share AWS account root user access keys with other administrators</strong> - The access key for your AWS account root user gives full access to all your resources for all AWS services, including your billing information. You cannot reduce the permissions associated with your AWS account root user access key. You should never share these access keys with any other users, not even the administrators.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html">https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html</a></p>
</div>

**Question 15**

15. Which of the following is a part of the AWS Global Infrastructure?
*  A. Virtual Private Cloud (VPC)
*  B. Virtual Private Network (VPN)
*  C. Subnets
*  D. Region

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Region</strong></p>
 <p>AWS Region is a physical location around the world where AWS builds its data centers. Each group of logical data centers is called an Availability Zone (AZ). Each AWS Region consists of multiple, isolated, and physically separate AZ's within a geographic area.</p>
 <p>Please see this illustration for AWS regions in the US: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q45-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/about-aws/global-infrastructure/regions_az/">https://aws.amazon.com/about-aws/global-infrastructure/regions_az/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Virtual Private Cloud (VPC)</strong> - Amazon Virtual Private Cloud (Amazon VPC) is a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define. You have complete control over your virtual networking environment, including the selection of your IP address range, creation of subnets, and configuration of route tables and network gateways. A VPC spans all of the Availability Zones in the Region.</p>
 <p><strong>Virtual Private Network (VPN)</strong> - AWS Virtual Private Network (AWS VPN) lets you establish a secure and private encrypted tunnel from your on-premises network to the AWS global network. AWS VPN is comprised of two services: AWS Site-to-Site VPN and AWS Client VPN.</p>
 <p><strong>Subnets</strong> - A subnet is a range of IP addresses within your VPC. A subnet spans only one Availability Zone in the Region.</p>
 <p>These three options are not a part of the AWS Global Infrastructure.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/about-aws/global-infrastructure/regions_az/">https://aws.amazon.com/about-aws/global-infrastructure/regions_az/</a></p>
</div>

**Question 16**

16. Which of the following are components of an AWS Site-to-Site VPN? (Select two)
*  A. Internet Gateway
*  B. Virtual Private Gateway
*  C. Storage Gateway
*  D. Customer Gateway
*  E. NAT Gateway

**Answer** B, D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Virtual Private Gateway</strong></p>
 <p><strong>Customer Gateway</strong></p>
 <p>AWS Site-to-Site VPN enables you to securely connect your on-premises network or branch office site to your Amazon Virtual Private Cloud (Amazon VPC). VPN Connections are a good solution if you have an immediate need, and have low to modest bandwidth requirements. This connection goes over the public internet. Virtual Private Gateway (or a Transit Gateway) and Customer Gateway are the components of a VPC.</p>
 <p>A virtual private gateway is the VPN concentrator on the Amazon side of the Site-to-Site VPN connection. A customer gateway is a resource in AWS that provides information to AWS about your Customer gateway device.</p>
 <p>Components of an AWS Site-to-Site VPN: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q11-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/vpn/latest/s2svpn/how_it_works.html">https://docs.aws.amazon.com/vpn/latest/s2svpn/how_it_works.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Storage Gateway</strong> - AWS Storage Gateway is a hybrid cloud storage service that connects your existing on-premises environments with the AWS Cloud. Customers use Storage Gateway to simplify storage management and reduce costs for key hybrid cloud storage use cases.</p>
 <p><strong>NAT Gateway</strong> - A NAT Gateway or a NAT Instance can be used in a public subnet in your VPC to enable instances in the private subnet to initiate outbound IPv4 traffic to the Internet. NAT Gateway is managed by AWS but NAT Instance is managed by you.</p>
 <p><strong>Internet Gateway</strong> - An internet gateway is a horizontally scaled, redundant, and highly available VPC component that allows communication between instances in your VPC and the internet. It, therefore, imposes no availability risks or bandwidth constraints on your network traffic.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/vpn/latest/s2svpn/how_it_works.html">https://docs.aws.amazon.com/vpn/latest/s2svpn/how_it_works.html</a></p>
</div>

**Question 17**

17. Which AWS Support plan provides general architectural guidance on how services can be used for various use-cases, workloads, or applications?
*  A. Business
*  B. Basic
*  C. Enterprise
*  D. Developer

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Developer</strong> - AWS recommends Developer Support plan if you are testing or doing early development on AWS and want the ability to get email-based technical support during business hours. This plan also supports general guidance on how services can be used for various use cases, workloads, or applications. You do not get access to Infrastructure Event Management with this plan.</p>
 <p>Developer Support Plan Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q52-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/premiumsupport/plans/developers/">https://aws.amazon.com/premiumsupport/plans/developers/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Enterprise</strong> - AWS Enterprise Support provides customers with concierge-like service where the main focus is helping the customer achieve their outcomes and find success in the cloud. With Enterprise Support, you get 24x7 technical support from high-quality engineers, tools and technology to automatically manage the health of your environment, consultative architectural guidance delivered in the context of your applications and use-cases, and a designated Technical Account Manager (TAM) to coordinate access to proactive/preventative programs and AWS subject matter experts.</p>
 <p><strong>Business</strong> - AWS recommends Business Support if you have production workloads on AWS and want 24x7 phone, email and chat access to technical support and architectural guidance in the context of your specific use-cases. You get full access to AWS Trusted Advisor Best Practice Checks.</p>
 <p><strong>Basic</strong> - The basic plan only provides access to the following:</p>
 <p>Customer Service &amp; Communities - 24x7 access to customer service, documentation, whitepapers, and support forums. AWS Trusted Advisor - Access to the 7 core Trusted Advisor checks and guidance to provision your resources following best practices to increase performance and improve security. AWS Personal Health Dashboard - A personalized view of the health of AWS services, and alerts when your resources are impacted.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/premiumsupport/plans/developers/">https://aws.amazon.com/premiumsupport/plans/developers/</a></p>
</div>

**Question 18**

18. Which pillar of the AWS Well-Architected Framework recommends maintaining infrastructure as code?
*  A. Operational Excellence
*  B. Cost Optimization
*  C. Security
*  D. Performance Efficiency

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Operational Excellence</strong></p>
 <p>The AWS Well-Architected Framework helps you understand the pros and cons of decisions you make while building systems on AWS. By using the Framework you will learn architectural best practices for designing and operating reliable, secure, efficient, and cost-effective systems in the cloud. It provides a way for you to consistently measure your architectures against best practices and identify areas for improvement.</p>
 <p>The AWS Well-Architected Framework is based on six pillars — Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization and Sustainability.</p>
 <p>The Operational Excellence pillar includes the ability to run and monitor systems to deliver business value and to continually improve supporting processes and procedures. In the cloud, you can apply the same engineering discipline that you use for application code to your entire environment. You can define your entire workload (applications, infrastructure) as code and update it with code. You can implement your operations procedures as code and automate their execution by triggering them in response to events.</p>
 <p>Incorrect options:</p>
 <p><strong>Cost Optimization</strong> - Cost Optimization focuses on avoiding un-needed costs. Key topics include understanding and controlling where the money is being spent, selecting the most appropriate and right number of resource types, analyzing spend over time, and scaling to meet business needs without overspending.</p>
 <p><strong>Performance Efficiency</strong> - The performance efficiency pillar focuses on using IT and computing resources efficiently. Key topics include selecting the right resource types and sizes based on workload requirements, monitoring performance, and making informed decisions to maintain efficiency as business needs evolve.</p>
 <p><strong>Security</strong> - The security pillar focuses on protecting information &amp; systems. Key topics include confidentiality and integrity of data, identifying and managing who can do what with privilege management, protecting systems, and establishing controls to detect security events.</p>
 <p>Reference:</p>
 <p><a href="https://wa.aws.amazon.com/wat.pillar.operationalExcellence.en.html">https://wa.aws.amazon.com/wat.pillar.operationalExcellence.en.html</a></p>
</div>

**Question 19**

19. Which AWS Route 53 routing policy would you use when you want to route your traffic in an active-passive configuration?
*  A. Weighted routing policy
*  B. Latency routing policy
*  C. Failover routing policy
*  D. Simple routing policy

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Failover routing policy</strong></p>
 <p>Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service. It is designed to give developers and businesses an extremely reliable and cost-effective way to route end users to Internet applications by translating names like www.example.com into the numeric IP addresses like 192.0.2.1 that computers use to connect to each other.</p>
 <p>Failover routing policy is used when you want to configure active-passive failover. Failover routing lets you route traffic to a resource when the resource is healthy or to a different resource when the first resource is unhealthy. The primary and secondary records can route traffic to anything from an Amazon S3 bucket that is configured as a website to a complex tree of records.</p>
 <p>Route 53 Routing Policy Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q2-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html">https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Simple routing policy</strong> - Simple routing lets you configure standard DNS records, with no special Route 53 routing such as weighted or latency. With simple routing, you typically route traffic to a single resource, for example, to a web server for your website.</p>
 <p><strong>Weighted routing policy</strong> - This routing policy is used to route traffic to multiple resources in proportions that you specify.</p>
 <p><strong>Latency routing policy</strong> - This routing policy is used when you have resources in multiple AWS Regions and you want to route traffic to the region that provides the best latency.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html">https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html</a></p>
</div>

**Question 20**

20. Which AWS service can help you create data-driven business cases for transitioning your business from on-premises to AWS Cloud?
*  A. AWS Billing and Cost Management
*  B. AWS Migration Evaluator
*  C. AWS Trusted Advisor
*  D. AWS Budgets

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Migration Evaluator</strong></p>
 <p>Migration Evaluator (Formerly TSO Logic) is a complimentary service to create data-driven business cases for AWS Cloud planning and migration.</p>
 <p>Migration Evaluator quickly provides a business case to make sound AWS planning and migration decisions. With Migration Evaluator, your organization can build a data-driven business case for AWS, gets access to AWS expertise, visibility into the costs associated with multiple migration strategies, and insights on how reusing existing software licensing reduces costs further.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Budgets</strong> - AWS Budgets gives the ability to set custom budgets that alert you when your costs or usage exceed (or are forecasted to exceed) your budgeted amount. You can also use AWS Budgets to set reservation utilization or coverage targets and receive alerts when your utilization drops below the threshold you define. Budgets can be created at the monthly, quarterly, or yearly level, and you can customize the start and end dates. You can further refine your budget to track costs associated with multiple dimensions, such as AWS service, linked account, tag, and others. You cannot use this service to create data-driven business cases for transitioning your business from on-premises to AWS Cloud.</p>
 <p><strong>AWS Trusted Advisor</strong> - AWS Trusted Advisor is an online tool that provides real-time guidance to help provision your resources following AWS best practices. Whether establishing new workflows, developing applications, or as part of ongoing improvement, recommendations provided by Trusted Advisor regularly help keep your solutions provisioned optimally. AWS Trusted Advisor analyzes your AWS environment and provides best practice recommendations in five categories: Cost Optimization, Performance, Security, Fault Tolerance, Service Limits. You cannot use this service to create data-driven business cases for transitioning your business from on-premises to AWS Cloud.</p>
 <p><strong>AWS Billing and Cost Management</strong> - AWS Billing and Cost Management is the service that you use to pay your AWS bill, monitor your usage, and analyze and control your costs. It is the billing department for AWS services - with necessary tools and services under its hood. You cannot use this service to create data-driven business cases for transitioning your business from on-premises to AWS Cloud.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/ce-exploring-data.html">https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/ce-exploring-data.html</a></p>
</div>

**Question 21**

21. An IT company has a hybrid cloud architecture and it wants to centralize the server logs for its EC2 instances and on-premises servers. Which of the following is the MOST effective for this use-case?
*  A. Use CloudWatch Logs for the EC2 instance and CloudTrail for the on-premises servers
*  B. Use CloudWatch Logs for both the EC2 instance and the on-premises servers
*  C. Use AWS Lambda to send log data from EC2 instance as well as on-premises servers to CloudWatch Logs
*  D. Use CloudTrail for the EC2 instance and CloudWatch Logs for the on-premises servers

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Use CloudWatch Logs for both the EC2 instance and the on-premises servers</strong></p>
 <p>You can use Amazon CloudWatch Logs to monitor, store, and access your log files from Amazon Elastic Compute Cloud (Amazon EC2) instances, AWS CloudTrail, Route 53, and other sources such as on-premises servers.</p>
 <p>CloudWatch Logs enables you to centralize the logs from all of your systems, applications, and AWS services that you use, in a single, highly scalable service. You can then easily view them, search them for specific error codes or patterns, filter them based on specific fields, or archive them securely for future analysis.</p>
 <p>Incorrect options:</p>
 <p><strong>Use AWS Lambda to send log data from EC2 instance as well as on-premises servers to CloudWatch Logs</strong></p>
 <p>AWS Lambda lets you run code without provisioning or managing servers. You pay only for the compute time you consume. Lambda cannot be used to centralize the logs from EC2 instances and on-premises servers.</p>
 <p><strong>Use CloudWatch Logs for the EC2 instance and CloudTrail for the on-premises servers</strong></p>
 <p><strong>Use CloudTrail for the EC2 instance and CloudWatch Logs for the on-premises servers</strong></p>
 <p>AWS CloudTrail is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account. With CloudTrail, you can log, continuously monitor, and retain account activity related to actions across your AWS infrastructure. CloudTrail provides event history of your AWS account activity, including actions taken through the AWS Management Console, AWS SDKs, command-line tools, and other AWS services. CloudTrail cannot be used to centralize the server logs for EC2 instances or on-premises servers, so both these options are incorrect.</p>
 <p>References:</p>
 <p><a href="https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/WhatIsCloudWatchLogs.html">https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/WhatIsCloudWatchLogs.html</a></p>
 <p><a href="https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/AgentReference.html">https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/AgentReference.html</a></p>
</div>

**Question 22**

22. Compared to the On-demand prices, what is the highest possible discount offered for reserved instances?
*  A. 72
*  B. 40
*  C. 50
*  D. 90

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>72</strong></p>
 <p>Reserved Instances provide you with significant savings (up to 72%) on your Amazon EC2 costs compared to On-Demand Instance pricing. Reserved Instances are not physical instances, but rather a billing discount applied to the use of On-Demand Instances in your account. You can purchase a Reserved Instance for a one-year or three-year commitment, with the three-year commitment offering a bigger discount.</p>
 <p>EC2 Pricing Options Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q9-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/ec2/pricing/">https://aws.amazon.com/ec2/pricing/</a></p>
 <p>Incorrect options:</p>
 <p><strong>90</strong></p>
 <p><strong>50</strong></p>
 <p><strong>40</strong></p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/ec2/pricing/">https://aws.amazon.com/ec2/pricing/</a></p>
</div>

**Question 23**

23. Which of the following is the best way to protect your data from accidental deletion on Amazon S3?
*  A. S3 Transfer Acceleration
*  B. S3 Versioning
*  C. S3 lifecycle configuration
*  D. S3 Storage Classes

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>S3 Versioning</strong></p>
 <p>Versioning is a means of keeping multiple variants of an object in the same bucket. You can use versioning to preserve, retrieve, and restore every version of every object stored in your Amazon S3 bucket. With versioning, you can easily recover from both unintended user actions and application failures.</p>
 <p>Versioning-enabled buckets enable you to recover objects from accidental deletion or overwrite. For example: if you delete an object, instead of removing it permanently, Amazon S3 inserts a delete marker, which becomes the current object version.</p>
 <p>S3 Versioning Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q48-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/ObjectVersioning.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/ObjectVersioning.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>S3 lifecycle configuration</strong> - To manage your S3 objects so that they are stored cost-effectively throughout their lifecycle, configure their Amazon S3 Lifecycle. With S3 Lifecycle configuration rules, you can tell Amazon S3 to transition objects to less expensive storage classes, or archive or delete them. Lifecycle configuration will do the hard lifting of moving your data into cost-effective storage classes without user intervention. Lifecycle configuration is not meant to protect from accidental deletion of data.</p>
 <p><strong>S3 Storage Classes</strong> - Amazon S3 offers a range of storage classes designed for different use cases. These include S3 Standard for general-purpose storage of frequently accessed data; S3 Intelligent-Tiering for data with unknown or changing access patterns; S3 Standard-Infrequent Access (S3 Standard-IA) and S3 One Zone-Infrequent Access (S3 One Zone-IA) for long-lived, but less frequently accessed data; and Amazon S3 Glacier (S3 Glacier) and Amazon S3 Glacier Deep Archive (S3 Glacier Deep Archive) for long-term archive and digital preservation. Storage classes are for different storage pattern needs that customers have, and not a data protection mechanism for S3.</p>
 <p><strong>S3 Transfer Acceleration</strong> - Amazon S3 Transfer Acceleration enables fast, easy, and secure transfers of files over long distances between your client and an S3 bucket. Transfer Acceleration takes advantage of Amazon CloudFront’s globally distributed edge locations. As the data arrives at an edge location, data is routed to Amazon S3 over an optimized network path. Transfer Acceleration cannot be used to protect from accidental deletion of data.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/ObjectVersioning.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/ObjectVersioning.html</a></p>
</div>

**Question 24**

24. An IT company has deployed a static website on S3, but the website is still inaccessible. As a Cloud Practioner, which of the following solutions would you suggest to address this issue?
*  A. Enable S3 versioning
*  B. Fix the S3 bucket policy
*  C. Enable S3 replication
*  D. Disable S3 encryption

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>Fix the S3 bucket policy</strong></p>
 <p>To host a static website on Amazon S3, you configure an Amazon S3 bucket for website hosting and then upload your website content to the bucket. When you configure a bucket as a static website, you must enable website hosting, set permissions, and create and add an index document.</p>
 <p>Hosting a static website on Amazon S3: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q25-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html</a></p>
 <p>If you want to configure an existing bucket as a static website that has public access, you must edit block public access settings for that bucket. You may also have to edit your account-level block public access settings. Amazon S3 applies the most restrictive combination of the bucket-level and account-level block public access settings.</p>
 <p>Here is how you can edit Public Access settings for S3 buckets: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/edit-public-access-clear.png?raw=true"> via - <a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteAccessPermissionsReqd.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteAccessPermissionsReqd.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Disable S3 encryption</strong></p>
 <p><strong>Enable S3 versioning</strong></p>
 <p><strong>Enable S3 replication</strong></p>
 <p>Disabling S3 encryption, enabling S3 versioning or replication have no bearing on deploying a static website on S3, so these options are not correct.</p>
 <p>References:</p>
 <p><a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html</a></p>
 <p><a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteAccessPermissionsReqd.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteAccessPermissionsReqd.html</a></p>
</div>

**Question 25**

25. Which AWS service can be used to execute code triggered by new files being uploaded to S3?
*  A. EC2
*  B. ECS
*  C. Lambda
*  D. SQS

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Lambda</strong> - AWS Lambda lets you run code without provisioning or managing servers. You pay only for the compute time you consume. With Lambda, you can run code for virtually any type of application or backend service - all with zero administration. Just upload your code and Lambda takes care of everything required to run and scale your code with high availability.</p>
 <p>You can use Amazon S3 to trigger AWS Lambda to process data immediately after an upload. For example, you can use Lambda to thumbnail images, transcode videos, index files, process logs, validate content, and aggregate and filter data in real-time.</p>
 <p>How Lambda executes code in response to a trigger from S3: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/product-page-diagram_Lambda-RealTimeFileProcessing.a59577de4b6471674a540b878b0b684e0249a18c.png?raw=true"> via - <a href="https://aws.amazon.com/lambda/">https://aws.amazon.com/lambda/</a></p>
 <p>Incorrect options:</p>
 <p><strong>EC2</strong> - Amazon EC2 is a web service that provides secure, resizable compute capacity in the AWS cloud. You can use EC2 to provision virtual servers on AWS Cloud. EC2 cannot execute code via a trigger from S3.</p>
 <p><strong>ECS</strong> - Amazon Elastic Container Service (Amazon ECS) is a highly scalable, fast, container management service that makes it easy to run, stop, and manage Docker containers on a cluster. ECS cannot execute code via a trigger from S3.</p>
 <p><strong>SQS</strong> - Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications. Using SQS, you can send, store, and receive messages between software components at any volume, without losing messages or requiring other services to be available.</p>
 <p>Although SQS can be triggered from an S3 event, but SQS cannot execute code as its a message queuing service.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/lambda/">https://aws.amazon.com/lambda/</a></p>
</div>

**Question 26**

26. An IT company would like to move its IT resources (including any data and applications) from an AWS Region in the US to another AWS Region in Europe. Which of the following represents the correct solution for this use-case?
*  A. The company should just start creating new resources in the destination AWS Region and then migrate the relevant data and applications into this new AWS Region
*  B. The company should raise a ticket with AWS Support for this resource migration
*  C. The company should use CloudFormation to move the resources (including any data and applications) from source AWS Region to destination AWS Region
*  D. The company should use Database Migration Service to move the resources (including any data and applications) from source AWS Region to destination AWS Region

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>The company should just start creating new resources in the destination AWS Region and then migrate the relevant data and applications into this new AWS Region</strong> - The company needs to create resources in the new AWS Region and then move the relevant data and applications into the new AWS Region. There is no off-the-shelf solution or service that the company can use to facilitate this transition.</p>
 <p>Incorrect options:</p>
 <p><strong>The company should use CloudFormation to move the resources (including any data and applications) from source AWS Region to destination AWS Region</strong> - AWS CloudFormation allows you to use programming languages or a simple text file to model and provision, in an automated and secure manner, all the resources needed for your applications across all regions and accounts. CloudFormation cannot help with moving data and applications into another Region.</p>
 <p><strong>The company should use Database Migration Service to move the resources (including any data and applications) from source AWS Region to destination AWS Region</strong> - AWS Database Migration Service helps you migrate databases to AWS quickly and securely. The source database remains fully operational during the migration, minimizing downtime to applications that rely on the database. The AWS Database Migration Service can migrate your data to and from the most widely used commercial and open-source databases. Database Migration Service cannot help with the entire IT resources migration.</p>
 <p><strong>The company should raise a ticket with AWS Support for this resource migration</strong> - This option has been added as a distractor. AWS Support cannot help with IT resources migration.</p>
</div>

**Question 27**

27. Which of the following improves the availability for a fleet of EC2 instances?
*  A. Deploy the EC2 instances across different AWS Regions of the same Availability Zone
*  B. Deploy the EC2 instances across different Availability Zones in the same AWS Region
*  C. Deploy the EC2 instances in the same Availability Zone across two different AWS Regions
*  D. Deploy the EC2 instances in the same Availability Zone of an AWS Region

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Deploy the EC2 instances across different Availability Zones in the same AWS Region</strong></p>
 <p>AWS has the concept of a Region, which is a physical location around the world where AWS clusters data centers. Each AWS Region consists of multiple (two or more), isolated, and physically separate AZ's within a geographic area. Each AZ has independent power, cooling, and physical security and is connected via redundant, ultra-low-latency networks.</p>
 <p>An Availability Zone (AZ) is one or more discrete data centers with redundant power, networking, and connectivity in an AWS Region. An AWS Region refers to a physical location around the world where AWS clusters data centers. AZ’s give customers the ability to operate production applications and databases that are more highly available, fault tolerant, and scalable than would be possible from a single data center. All AZ’s in an AWS Region are interconnected with high-bandwidth, low-latency networking, over fully redundant, dedicated metro fiber providing high-throughput, low-latency networking between AZ’s.</p>
 <p>AWS Regions and Availability Zones Explained: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q47-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/about-aws/global-infrastructure/regions_az/">https://aws.amazon.com/about-aws/global-infrastructure/regions_az/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Deploy the EC2 instances in the same Availability Zone of an AWS Region</strong> - Deploying EC2 instances within the same AZ will not improve availability.</p>
 <p><strong>Deploy the EC2 instances in the same Availability Zone across two different AWS Regions</strong> - An Availability Zone cannot belong to two different AWS Regions. So this option is incorrect.</p>
 <p><strong>Deploy the EC2 instances across different AWS Regions of the same Availability Zone</strong> - You cannot have an AWS Region inside an Availability Zone. So this option is incorrect.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/about-aws/global-infrastructure/regions_az/">https://aws.amazon.com/about-aws/global-infrastructure/regions_az/</a></p>
</div>

**Question 28**

28. Which of the following AWS services are regional in scope? (Select two)
*  A. AWS Identity and Access Management (IAM)
*  B. AWS WAF
*  C. AWS Lambda
*  D. Amazon CloudFront
*  E. Amazon Rekognition

**Answer** C, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p>Most of the services that AWS offers are Region specific. But few services, by definition, need to be in a global scope because of the underlying service they offer. AWS IAM, Amazon CloudFront, Route 53 and WAF are some of the global services.</p>
 <p><strong>AWS Lambda</strong> - AWS Lambda is a compute service that lets you run code without provisioning or managing servers. AWS Lambda executes your code only when needed and scales automatically, from a few requests per day to thousands per second. Lambda is a regional service.</p>
 <p><strong>Amazon Rekognition</strong> - With Amazon Rekognition, you can identify objects, people, text, scenes, and activities in images and videos, as well as detect any inappropriate content. Amazon Rekognition also provides highly accurate facial analysis and facial search capabilities that you can use to detect, analyze, and compare faces for a wide variety of user verification, people counting, and public safety use cases. Rekognition is a regional service.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Identity and Access Management (IAM)</strong> - AWS Identity and Access Management (IAM) enables you to manage access to AWS services and resources securely. Using IAM, you can create and manage AWS users and groups, and use permissions to allow and deny their access to AWS resources.</p>
 <p><strong>Amazon CloudFront</strong> - Amazon CloudFront is a fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency, high transfer speeds, all within a developer-friendly environment.</p>
 <p><strong>AWS WAF</strong> - By using AWS WAF, you can configure web access control lists (Web ACLs) on your CloudFront distributions or Application Load Balancers to filter and block requests based on request signatures.</p>
 <p>As mentioned earlier, these three services are global in scope.</p>
 <p>Exam Alert:</p>
 <p><strong>Amazon S3</strong> - Amazon S3 is a unique service in the sense that it follows a global namespace but the buckets are regional. You specify an AWS Region when you create your Amazon S3 bucket. This is a regional service.</p>
</div>

**Question 29**

29. An AWS user is trying to launch an EC2 instance in a given region. What is the region-specific constraint that the Amazon Machine Image (AMI) must meet so that it can be used for this EC2 instance?
*  A. An AMI is a global entity, so the region is not applicable
*  B. You must use an AMI from the same region as that of the EC2 instance. The region of the AMI has no bearing on the performance of the EC2 instance
*  C. You should use an AMI from the same region, as it improves the performance of the EC2 instance
*  D. You can use an AMI from a different region, but it degrades the performance of the EC2 instance

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>You must use an AMI from the same region as that of the EC2 instance. The region of the AMI has no bearing on the performance of the EC2 instance</strong></p>
 <p>An Amazon Machine Image (AMI) provides the information required to launch an instance. You must specify an AMI when you launch an instance. You can launch multiple instances from a single AMI when you need multiple instances with the same configuration.</p>
 <p>The AMI must be in the same region as that of the EC2 instance to be launched. If the AMI exists in a different region, you can copy that AMI to the region where you want to launch the EC2 instance. The region of AMI has no bearing on the performance of the EC2 instance.</p>
 <p>Amazon Machine Images (AMI) Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q34-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>You can use an AMI from a different region, but it degrades the performance of the EC2 instance</strong></p>
 <p><strong>You should use an AMI from the same region, as it improves the performance of the EC2 instance</strong></p>
 <p><strong>An AMI is a global entity, so the region is not applicable</strong></p>
 <p>These three options contradict the details provided earlier in the explanation, so these options are incorrect.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html</a></p>
</div>

**Question 30**

30. Which of the following use cases is best suited for Amazon Elastic File System (EFS) Standard–Infrequent Access (Standard–IA) storage class?
*  A. Object storage for workloads that need sub-second latency speeds for accessing the data
*  B. Use as boot volume for highly available Amazon EC2 instances
*  C. Storing files in an accessible location to satisfy audit requirements
*  D. Storing data in a single AWS Availability Zone

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option: <strong>Storing files in an accessible location to satisfy audit requirements</strong> - The Standard–IA storage class reduces storage costs for files that are not accessed every day. It does this without sacrificing the high availability, high durability, elasticity, and POSIX file system access that Amazon EFS provides.</p>
 <p>AWS recommends Standard-IA storage if you need your full dataset to be readily accessible and want to automatically save on storage costs for files that are less frequently accessed. Examples include keeping files accessible to satisfy audit requirements, performing historical analysis, or performing backup and recovery. Standard-IA storage is compatible with all Amazon EFS features, and is available in all AWS Regions where Amazon EFS is available.</p>
 <p>Incorrect options:</p>
 <p><strong>Storing data in a single AWS Availability Zone</strong> - EFS One Zone storage class is used to store data in a single AWS Availability Zone. Data stored in this storage class may be lost in the event of a disaster or other fault that affects all copies of the data within the Availability Zone, or in the event of Availability Zone destruction.</p>
 <p><strong>Object storage for workloads that need sub-second latency speeds for accessing the data</strong> - EFS is a file system service and not an object storage service. You should use S3 for object storage. So, this option is incorrect.</p>
 <p><strong>Use as boot volume for highly available Amazon EC2 instances</strong> - Amazon EFS cannot be used as a boot volume for Amazon EC2 instances. For boot volumes, Amazon Elastic Block Storage (Amazon EBS) volumes are used.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/efs/latest/ug/storage-classes.html">https://docs.aws.amazon.com/efs/latest/ug/storage-classes.html</a></p>
</div>

**Question 31**

31. Which AWS service protects your AWS account by monitoring malicious activity and detecting threats?
*  A. CloudWatch
*  B. CloudTrail
*  C. GuardDuty
*  D. Trusted Advisor

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>GuardDuty</strong></p>
 <p>GuardDuty is a threat detection service that monitors malicious activity and unauthorized behavior to protect your AWS account. GuardDuty analyzes billions of events across your AWS accounts from AWS CloudTrail (AWS user and API activity in your accounts), Amazon VPC Flow Logs (network traffic data), and DNS Logs (name query patterns). Security findings are retained and made available through the Amazon GuardDuty console and APIs for 90-days. After 90-days, the findings are discarded. To retain findings for longer than 90-days, you can enable AWS CloudWatch Events to automatically push findings to an Amazon S3 bucket in your account or another data store for long-term retention.</p>
 <p>How GuardDuty Works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/product-page-diagram-Amazon-GuardDuty_how-it-works.4370200b49eddc34d3a55c52c584484ceb2d532b.png?raw=true"> via - <a href="https://aws.amazon.com/guardduty/">https://aws.amazon.com/guardduty/</a></p>
 <p>Incorrect options:</p>
 <p><strong>CloudTrail</strong> - AWS CloudTrail is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account. With CloudTrail, you can log, continuously monitor, and retain account activity related to actions across your AWS infrastructure. Think account-specific activity and audit; think CloudTrail. CloudTrail cannot detect threats to your AWS account.</p>
 <p><strong>CloudWatch</strong> - Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers. CloudWatch provides data and actionable insights to monitor your applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health. Think resource performance monitoring, events, and alerts; think CloudWatch. CloudWatch cannot detect threats to your AWS account.</p>
 <p><strong>Trusted Advisor</strong> - AWS Trusted Advisor is an online tool that provides you real-time guidance to help you provision your resources following AWS best practices. Whether establishing new workflows, developing applications, or as part of ongoing improvement, recommendations provided by Trusted Advisor regularly help keep your solutions provisioned optimally. Trusted Advisor cannot detect threats to your AWS account.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/guardduty">https://aws.amazon.com/guardduty</a></p>
</div>

**Question 32**

32. Amazon CloudWatch billing metric data is stored in which AWS Region?
*  A. US East (N. Virginia) - us-east-1
*  B. In the AWS Region where the AWS account is created
*  C. In the AWS Region where the AWS resource is provisioned
*  D. US West (N. California) - us-west-1

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>US East (N. Virginia) - us-east-1</strong></p>
 <p>You can monitor your estimated AWS charges by using Amazon CloudWatch. Billing metric data is stored in the US East (N. Virginia) Region and represents worldwide charges. This data includes the estimated charges for every service in AWS that you use, in addition to the estimated overall total of your AWS charges.</p>
 <p>Incorrect options:</p>
 <p><strong>In the AWS Region where the AWS account is created</strong></p>
 <p><strong>In the AWS Region where the AWS resource is provisioned</strong></p>
 <p><strong>US West (N. California) - us-west-1</strong></p>
 <p>These three options contradict the details provided earlier in the explanation, so these options are incorrect.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html">https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html</a></p>
</div>

**Question 33**

33. Which AWS service can be used as an in-memory database with high-performance and low latency?
*  A. Amazon ElastiCache
*  B. Amazon Athena
*  C. Amazon DynamoDB
*  D. Amazon RDS

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon ElastiCache</strong></p>
 <p>Amazon ElastiCache allows you to seamlessly set up, run, and scale popular open-Source compatible in-memory data stores in the cloud. Build data-intensive apps or boost the performance of your existing databases by retrieving data from high throughput and low latency in-memory data stores. Amazon ElastiCache is a popular choice for real-time use cases like Caching, Session Stores, Gaming, Geospatial Services, Real-Time Analytics, and Queuing. ElastiCache cannot be used for online analytical processing.</p>
 <p>How ElastiCache Works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/product-page-diagram_ElastiCache_how-it-works.ec509f8b878f549b7fb8a49669bf2547878303f6.png?raw=true"> via - <a href="https://aws.amazon.com/elasticache/">https://aws.amazon.com/elasticache/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon RDS</strong> - Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while automating time-consuming administration tasks such as hardware provisioning, database setup, patching, and backups. RDS cannot be used as an in-memory database.</p>
 <p><strong>Amazon DynamoDB</strong> - Amazon DynamoDB is a NoSQL database that supports key-value and document data models and enables developers to build modern, serverless applications that can start small and scale globally to support petabytes of data and tens of millions of read and write requests per second. DynamoDB supports both key-value and document data models. This enables DynamoDB to have a flexible schema, so each row can have any number of columns at any point in time. This allows you to easily adapt the tables as your business requirements change, without having to redefine the table schema as you would in relational databases. DynamoDB cannot be used as an in-memory database.</p>
 <p><strong>Amazon Athena</strong> - Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. Athena is serverless, so there is no infrastructure to manage, and you pay only for the queries that you run. Athena cannot be used as an in-memory database.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/elasticache/">https://aws.amazon.com/elasticache/</a></p>
</div>

**Question 34**

34. As a Cloud Practitioner, which S3 storage class would you recommend for data archival?
*  A. S3 Intelligent-Tiering
*  B. S3 Glacier
*  C. S3 Standard
*  D. S3 One Zone-IA

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>S3 Glacier</strong></p>
 <p>Amazon S3 Glacier is a secure, durable, and extremely low-cost Amazon S3 cloud storage class for data archiving and long-term backup. It is designed to deliver 99.999999999% durability, and provide comprehensive security and compliance capabilities that can help meet even the most stringent regulatory requirements.</p>
 <p>You can further review the use-cases for S3 Glacier: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q14-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/glacier/">https://aws.amazon.com/glacier/</a></p>
 <p>S3 Storage Classes Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q14-i2.jpg?raw=true"> via - <a href="https://aws.amazon.com/s3/storage-classes/">https://aws.amazon.com/s3/storage-classes/</a></p>
 <p>Incorrect options:</p>
 <p><strong>S3 Standard</strong> - S3 Standard offers high durability, availability, and performance object storage for frequently accessed data. It is not suitable for data archival.</p>
 <p><strong>S3 Intelligent-Tiering</strong> - The S3 Intelligent-Tiering storage class is designed to optimize costs by automatically moving data to the most cost-effective access tier, without performance impact or operational overhead. It works by storing objects in two access tiers: one tier that is optimized for frequent access and another lower-cost tier that is optimized for infrequent access. It is not suitable for data archival.</p>
 <p><strong>S3 One Zone-IA</strong> - S3 One Zone-IA is for data that is accessed less frequently, but requires rapid access when needed. Unlike other S3 Storage Classes which store data in a minimum of three Availability Zones (AZs), S3 One Zone-IA stores data in a single AZ. It is not suitable for data archival.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/glacier/">https://aws.amazon.com/glacier/</a></p>
 <p><a href="https://aws.amazon.com/s3/storage-classes/">https://aws.amazon.com/s3/storage-classes/</a></p>
</div>

**Question 35**

35. Data encryption is automatically enabled for which of the following AWS services? (Select two)?
*  A. Amazon EBS volumes
*  B. Amazon Redshift
*  C. AWS Storage Gateway
*  D. Amazon S3 Glacier
*  E. Amazon EFS drives

**Answer** C, D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon S3 Glacier</strong> - Amazon S3 Glacier (S3 Glacier), is a storage service optimized for infrequently used data, or "cold data. Data at rest stored in S3 Glacier is automatically server-side encrypted using 256-bit Advanced Encryption Standard (AES-256) with keys maintained by AWS.</p>
 <p><strong>AWS Storage Gateway</strong> - AWS Storage Gateway is a hybrid cloud storage service that gives you on-premises access to virtually unlimited cloud storage. All data transferred between the gateway and AWS storage is encrypted using SSL (for all three types of gateways - File, Volume and Tape Gateways).</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon EBS volumes</strong> - Amazon EBS volumes are not encrypted, by default. You can configure your AWS account to enforce the encryption of the new EBS volumes and snapshot copies that you create.</p>
 <p><strong>Amazon Redshift</strong> - Encryption is an optional setting in Amazon Redshift. When you enable encryption for a cluster, the data-blocks and system metadata are encrypted for the cluster and its snapshots.</p>
 <p><strong>Amazon EFS drives</strong> - Encryption is not a default setting, but an optional configuration for EFS drives. Amazon EFS supports two forms of encryption for file systems, encryption of data in transit and encryption at rest.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/storagegateway/faqs/">https://aws.amazon.com/storagegateway/faqs/</a></p>
 <p><a href="https://docs.aws.amazon.com/amazonglacier/latest/dev/DataEncryption.html">https://docs.aws.amazon.com/amazonglacier/latest/dev/DataEncryption.html</a></p>
</div>

**Question 36**

36. An IT company is on a cost-optimization spree and wants to identify all EC2 instances that are under-utilized. Which AWS services can be used off-the-shelf to address this use-case without needing any manual configurations? (Select two)
*  A. AWS Trusted Advisor
*  B. AWS Cost Explorer
*  C. Amazon CloudWatch
*  D. AWS Cost and Usage Reports
*  E. AWS Budgets

**Answer** A, B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Trusted Advisor</strong></p>
 <p>AWS Trusted Advisor is an online tool that provides real-time guidance to help provision your resources following AWS best practices. Whether establishing new workflows, developing applications, or as part of ongoing improvement, recommendations provided by Trusted Advisor regularly help keep your solutions provisioned optimally. AWS Trusted Advisor analyzes your AWS environment and provides best practice recommendations in five categories: Cost Optimization, Performance, Security, Fault Tolerance, Service Limits.</p>
 <p>AWS Trusted Advisor checks the Amazon Elastic Compute Cloud (Amazon EC2) instances that were running at any time during the last 14 days and alerts you if the daily CPU utilization was 10% or less and network I/O was 5 MB or less on 4 or more days.</p>
 <p>How Trusted Advisor Works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/AWS-trusted-advisor.5b9909d5f29f680eeb12ccff536e8d88d8701304.png?raw=true"> via - <a href="https://aws.amazon.com/premiumsupport/technology/trusted-advisor/">https://aws.amazon.com/premiumsupport/technology/trusted-advisor/</a></p>
 <p>How AWS Trusted Advisor identifies low utilization Amazon EC2 instances: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q28-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/premiumsupport/technology/trusted-advisor/best-practice-checklist/#Cost_Optimization">https://aws.amazon.com/premiumsupport/technology/trusted-advisor/best-practice-checklist/#Cost_Optimization</a></p>
 <p><strong>AWS Cost Explorer</strong></p>
 <p>AWS Cost Explorer has an easy-to-use interface that lets you visualize, understand, and manage your AWS costs and usage over time. AWS Cost Explorer includes a default report that helps you visualize the costs and usage associated with your top five cost-accruing AWS services, and gives you a detailed breakdown of all services in the table view. The reports let you adjust the time range to view historical data going back up to twelve months to gain an understanding of your cost trends.</p>
 <p>The rightsizing recommendations feature in Cost Explorer helps you identify cost-saving opportunities by downsizing or terminating EC2 instances. You can see all of your underutilized EC2 instances across member accounts in a single view to immediately identify how much you can save.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Cost and Usage Reports</strong> - The AWS Cost and Usage Reports (AWS CUR) contains the most comprehensive set of cost and usage data available. You can use Cost and Usage Reports to publish your AWS billing reports to an Amazon Simple Storage Service (Amazon S3) bucket that you own. You can receive reports that break down your costs by the hour or month, by product or product resource, or by tags that you define yourself. Cost and Usage Reports cannot be used to identify under-utilized EC2 instances.</p>
 <p><strong>Amazon CloudWatch</strong> - Amazon CloudWatch can be used to create alarm to monitor your estimated charges. When you enable the monitoring of estimated charges for your AWS account, the estimated charges are calculated and sent several times daily to CloudWatch as metric data. You can choose to receive alerts by email when charges have exceeded a certain threshold. Think resource performance monitoring, events, and alerts; think CloudWatch. CloudWatch cannot be used to identify under-utilized EC2 instances without manually configuring an alarm with the appropriate threshold to track the EC2 utilization, so this option is incorrect.</p>
 <p><strong>AWS Budgets</strong> - AWS Budgets gives the ability to set custom budgets that alert you when your costs or usage exceed (or are forecasted to exceed) your budgeted amount. You can also use AWS Budgets to set reservation utilization or coverage targets and receive alerts when your utilization drops below the threshold you define. Budgets can be created at the monthly, quarterly, or yearly level, and you can customize the start and end dates. You can further refine your budget to track costs associated with multiple dimensions, such as AWS service, linked account, tag, and others. AWS Budgets cannot be used to identify under-utilized EC2 instances without manually configuring coverage targets, so this option is incorrect.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/premiumsupport/technology/trusted-advisor/best-practice-checklist/#Cost_Optimization">https://aws.amazon.com/premiumsupport/technology/trusted-advisor/best-practice-checklist/#Cost_Optimization</a></p>
 <p><a href="https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/ce-rightsizing.html">https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/ce-rightsizing.html</a></p>
</div>

**Question 37**

37. A research lab wants to optimize the caching capabilities for its scientific computations application running on EC2 instances. Which EC2 storage option is best suited for this use-case?
*  A. Amazon S3
*  B. Amazon EBS
*  C. Amazon EC2 Instance Store
*  D. Amazon EFS

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon EC2 Instance Store</strong></p>
 <p>An Instance Store provides temporary block-level storage for your EC2 instance. This storage is located on disks that are physically attached to the host computer. Instance store is ideal for the temporary storage of information that changes frequently, such as buffers, caches, scratch data, and other temporary content, or for data that is replicated across a fleet of instances, such as a load-balanced pool of web servers. Instance storage is temporary, data is lost if instance experiences failure or is terminated.</p>
 <p>Instance Store Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q18-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/InstanceStorage.html">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/InstanceStorage.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon EBS</strong> - Amazon Elastic Block Store (EBS) is an easy to use, high-performance block storage service designed for use with Amazon Elastic Compute Cloud (EC2) for both throughput and transaction-intensive workloads at any scale. A broad range of workloads, such as relational and non-relational databases, enterprise applications, containerized applications, big data analytics engines, file systems, and media workflows are widely deployed on Amazon EBS. EBS is not a good fit for caching information on EC2 instances.</p>
 <p><strong>Amazon EFS</strong> - Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed, elastic NFS file system. It is built to scale on-demand to petabytes without disrupting applications, growing and shrinking automatically as you add and remove files, eliminating the need to provision and manage capacity to accommodate growth. Amazon EFS is designed to provide massively parallel shared access to thousands of Amazon EC2 instances, enabling your applications to achieve high levels of aggregate throughput and IOPS with consistent low latencies. EFS is not a good fit for caching information on EC2 instances.</p>
 <p><strong>Amazon S3</strong> - Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance. S3 is not a good fit for caching information on EC2 instances.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/InstanceStorage.html">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/InstanceStorage.html</a></p>
</div>

**Question 38**

38. Which of the following AWS services offer block-level storage? (Select two)
*  A. EFS
*  B. EBS
*  C. S3
*  D. Instance Store
*  E. ECS

**Answer** B, D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>EBS</strong> - Amazon Elastic Block Store (EBS) is an easy to use, high-performance block storage service designed for use with Amazon Elastic Compute Cloud (EC2) for both throughput and transaction-intensive workloads at any scale. A broad range of workloads, such as relational and non-relational databases, enterprise applications, containerized applications, big data analytics engines, file systems, and media workflows are widely deployed on Amazon EBS.</p>
 <p><strong>Instance Store</strong> - An instance store provides temporary block-level storage for your EC2 instance. This storage is located on disks that are physically attached to the host computer. Instance store is ideal for the temporary storage of information that changes frequently, such as buffers, caches, scratch data, and other temporary content, or for data that is replicated across a fleet of instances, such as a load-balanced pool of web servers. Instance storage is temporary, data is lost if instance experiences failure or is terminated. EC2 instance store cannot be used for file sharing between instances.</p>
 <p>Incorrect options:</p>
 <p><strong>EFS</strong> - Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed, elastic NFS file system. It is built to scale on-demand to petabytes without disrupting applications, growing and shrinking automatically as you add and remove files, eliminating the need to provision and manage capacity to accommodate growth. Amazon EFS is designed to provide massively parallel shared access to thousands of Amazon EC2 instances, enabling your applications to achieve high levels of aggregate throughput and IOPS with consistent low latencies.</p>
 <p><strong>S3</strong> - Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance. This means customers of all sizes and industries can use it to store and protect any amount of data for a range of use cases, such as websites, mobile applications, backup and restore, archive, enterprise applications, IoT devices, and big data analytics.</p>
 <p><strong>ECS</strong> - Amazon Elastic Container Service (ECS) is a highly scalable, high-performance container management service that supports Docker containers and allows you to easily run applications on a managed cluster of Amazon EC2 instances. This is not a storage service and has been added as a distractor.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/ebs/">https://aws.amazon.com/ebs/</a></p>
 <p><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/InstanceStorage.html">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/InstanceStorage.html</a></p>
</div>

**Question 39**

39. Which AWS service can be used for online analytical processing?
*  A. Amazon DynamoDB
*  B. Amazon Redshift
*  C. Amazon ElastiCache
*  D. Amazon RDS

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon Redshift</strong></p>
 <p>Amazon Redshift is a fast, fully managed cloud data warehouse that makes it simple and cost-effective to analyze all your data using standard SQL and your existing Business Intelligence (BI) tools. It allows you to run complex analytic queries against terabytes to petabytes of structured data, using sophisticated query optimization, columnar storage on high-performance storage, and massively parallel query execution.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon RDS</strong> - Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while automating time-consuming administration tasks such as hardware provisioning, database setup, patching, and backups.</p>
 <p>Customers use Amazon RDS databases primarily for online-transaction processing (OLTP) workload while Redshift is used primarily for reporting and analytics.</p>
 <p><strong>Amazon DynamoDB</strong> - Amazon DynamoDB is a NoSQL database that supports key-value and document data models and enables developers to build modern, serverless applications that can start small and scale globally to support petabytes of data and tens of millions of read and write requests per second. DynamoDB supports both key-value and document data models. This enables DynamoDB to have a flexible schema, so each row can have any number of columns at any point in time. This allows you to easily adapt the tables as your business requirements change, without having to redefine the table schema as you would in relational databases. DynamoDB cannot be used for online analytical processing.</p>
 <p><strong>Amazon ElastiCache</strong> - Amazon ElastiCache allows you to seamlessly set up, run, and scale popular open-Source compatible in-memory data stores in the cloud. Build data-intensive apps or boost the performance of your existing databases by retrieving data from high throughput and low latency in-memory data stores. Amazon ElastiCache is a popular choice for real-time use cases like Caching, Session Stores, Gaming, Geospatial Services, Real-Time Analytics, and Queuing. ElastiCache cannot be used for online analytical processing.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/redshift/faqs/">https://aws.amazon.com/redshift/faqs/</a></p>
</div>

**Question 40**

40. Which of the following capabilities does Amazon Rekognition provide as a ready-to-use feature?
*  A. Convert images into greyscale
*  B. Human pose detection
*  C. Identify objects in a photo
*  D. Resize images quickly

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Identify objects in a photo</strong></p>
 <p>With Amazon Rekognition, you can identify objects, people, text, scenes, and activities in images and videos, as well as detect any inappropriate content. Amazon Rekognition also provides highly accurate facial analysis and facial search capabilities that you can use to detect, analyze, and compare faces for a wide variety of user verification, people counting, and public safety use cases.</p>
 <p>Amazon Rekognition Use-Cases:</p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q10-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/rekognition/">https://aws.amazon.com/rekognition/</a></p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q10-i2.jpg?raw=true"> via - <a href="https://aws.amazon.com/rekognition/">https://aws.amazon.com/rekognition/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Convert images into greyscale</strong></p>
 <p><strong>Resize images quickly</strong></p>
 <p><strong>Human pose detection</strong></p>
 <p>Amazon Rekognition does not do image processing tasks such as converting images to greyscale or resizing images. Human pose detection is not available in Amazon Rekognition.</p>
 <p>Reference:</p>
</div>

**Question 41**

41. A research group wants to provision an EC2 instance for a flexible application that can be interrupted. As a Cloud Practitioner, which of the following would you recommend as the MOST cost-optimal option?
*  A. Spot Instance
*  B. Reserved Instance
*  C. Dedicated Host
*  D. On-Demand Instance

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Spot Instance</strong> - A Spot Instance is an unused EC2 instance that is available for less than the On-Demand price. Because Spot Instances enable you to request unused EC2 instances at steep discounts (up to 90%), you can lower your Amazon EC2 costs significantly. Spot Instances are well-suited for data analysis, batch jobs, background processing, and other flexible tasks that can be interrupted. These can be terminated at short notice, so these are not suitable for critical workloads that need to run at a specific point in time.</p>
 <p>EC2 Pricing Options Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q56-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/ec2/pricing/">https://aws.amazon.com/ec2/pricing/</a></p>
 <p>Incorrect options:</p>
 <p><strong>On-Demand Instance</strong> - An On-Demand Instance is an instance that you use on-demand. You have full control over its lifecycle — you decide when to launch, stop, hibernate, start, reboot, or terminate it. There is no long-term commitment required when you purchase On-Demand Instances. There is no upfront payment and you pay only for the seconds that your On-Demand Instances are running. The price per second for running an On-Demand Instance is fixed. On-demand instances cannot be interrupted. However, On-demand instances are not as cost-effective as spot instances, so this option is not correct.</p>
 <p><strong>Reserved Instance</strong> - Reserved Instances provide you with significant savings (up to 75%) on your Amazon EC2 costs compared to On-Demand Instance pricing. Reserved Instances are not physical instances, but rather a billing discount applied to the use of On-Demand Instances in your account. You can purchase a Reserved Instance for a one-year or three-year commitment, with the three-year commitment offering a bigger discount. Reserved instances cannot be interrupted. Reserved instances are not as cost-effective as spot instances, so this option is not correct.</p>
 <p><strong>Dedicated Host</strong> - Amazon EC2 Dedicated Hosts allow you to use your eligible software licenses from vendors such as Microsoft and Oracle on Amazon EC2 so that you get the flexibility and cost-effectiveness of using your licenses, but with the resiliency, simplicity, and elasticity of AWS. An Amazon EC2 Dedicated Host is a physical server fully dedicated for your use, so you can help address corporate compliance requirement. They're not cost-efficient compared to spot instances. So this option is not correct.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/ec2/pricing/">https://aws.amazon.com/ec2/pricing/</a></p>
</div>

**Question 42**

42. AWS Lambda pricing is based on which of the following criteria? (Select two)
*  A. Number of requests for the lambda function
*  B. The number of lines of code for the lambda function
*  C. The language runtime of the lambda function
*  D. The time it takes for the lambda function to execute
*  E. The size of the deployment package for the lambda function

**Answer** A, D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>Number of requests for the lambda function</strong></p>
 <p><strong>The time it takes for the lambda function to execute</strong></p>
 <p>AWS Lambda lets you run code without provisioning or managing servers. With Lambda, you can run code for virtually any type of application or backend service - all with zero administration. Just upload your code and Lambda takes care of everything required to run and scale your code with high availability.</p>
 <p>With AWS Lambda, you pay only for what you use. You are charged based on the number of requests for your functions and the duration, the time it takes for your code to execute. Lambda counts a request each time it starts executing in response to an event notification or invoke call, including test invokes from the console. Duration is calculated from the time your code begins executing until it returns or otherwise terminates, rounded up to the nearest 100ms.</p>
 <p>Incorrect options:</p>
 <p><strong>The language runtime of the lambda function</strong> - Lambda supports many programming language runtimes such as NodeJS, Python, Go, C# etc. The pricing for a lambda function is not dependent on the language runtime of the lambda function.</p>
 <p><strong>The number of lines of code for the lambda function</strong> - The pricing for a lambda function is not dependent on the number of lines of code for the lambda function.</p>
 <p><strong>The size of the deployment package for the lambda function</strong> - The pricing for a lambda function is not dependent on the size of the deployment package for the lambda function.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/lambda/pricing/">https://aws.amazon.com/lambda/pricing/</a></p>
</div>

**Question 43**

43. A customer is running a comparative study of pricing models of Amazon EFS and Amazon EBS that are used with the Amazon EC2 instances that host the application. Which of the following statements are correct regarding this use-case? (Select two)
*  A. Amazon EBS Snapshot storage pricing is based on the amount of space your data consumes in EBS
*  B. Amazon EC2 data transfer charges will apply for all EBS direct APIs for Snapshots
*  C. Amazon EBS Snapshots are stored incrementally, which means you are billed only for the changed blocks stored
*  D. With AWS Backup, you pay only for the amount of EFS backup storage you use in a month, you need not pay for restoring this data
*  E. You will pay a fee each time you read from or write data stored on the EFS - Infrequent Access storage class

**Answer** C, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>You will pay a fee each time you read from or write data stored on the EFS - Infrequent Access storage class</strong> - The Infrequent Access storage class is cost-optimized for files accessed less frequently. Data stored on the Infrequent Access storage class costs less than Standard and you will pay a fee each time you read from or write to a file.</p>
 <p><strong>Amazon EBS Snapshots are stored incrementally, which means you are billed only for the changed blocks stored</strong> - Amazon EBS Snapshots are a point in time copy of your block data. For the first snapshot of a volume, Amazon EBS saves a full copy of your data to Amazon S3. EBS Snapshots are stored incrementally, which means you are billed only for the changed blocks stored.</p>
 <p>Incorrect options:</p>
 <p><strong>Amazon EC2 data transfer charges will apply for all EBS direct APIs for Snapshots</strong> - When using EBS direct APIs for Snapshots, additional EC2 data transfer charges will apply only when you use external or cross-region data transfers.</p>
 <p><strong>Amazon EBS Snapshot storage pricing is based on the amount of space your data consumes in EBS</strong> - Snapshot storage is based on the amount of space your data consumes in Amazon S3. Because Amazon EBS does not save empty blocks, it is likely that the snapshot size will be considerably less than your volume size. Copying EBS snapshots is charged for the data transferred across regions. After the snapshot is copied, standard EBS snapshot charges apply for storage in the destination region.</p>
 <p><strong>With AWS Backup, you pay only for the amount of EFS backup storage you use in a month, you need not pay for restoring this data</strong> - To back up your Amazon EFS file data you can use AWS Backup, a fully-managed backup service that makes it easy to centralize and automate the back up of data across AWS services. With AWS Backup, you pay only for the amount of backup storage you use and the amount of backup data you restore in the month. There is no minimum fee and there are no set-up charges.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/efs/pricing/">https://aws.amazon.com/efs/pricing/</a></p>
 <p><a href="https://aws.amazon.com/ebs/pricing/">https://aws.amazon.com/ebs/pricing/</a></p>
</div>

**Question 44**

44. A financial services company must meet compliance requirements that mandate storing multiple copies of data in geographically distant locations. As the company uses S3 as its main storage service, which of the following represents the MOST resource-efficient solution for this use-case?
*  A. Use Cross-Region replication (CRR) to replicate data between distant AWS Regions
*  B. For every new object, trigger a lambda function to write data into a bucket in another AWS Region
*  C. Run a daily job on an EC2 instance to copy objects into another Region
*  D. Use Same-Region replication (SRR) to replicate data between distant AWS Regions

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Use Cross-Region replication (CRR) to replicate data between distant AWS Regions</strong></p>
 <p>Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance.</p>
 <p>Replication enables automatic, asynchronous copying of objects across Amazon S3 buckets. Buckets that are configured for object replication can be owned by the same AWS account or by different accounts. You can copy objects between different AWS Regions or within the same Region.</p>
 <p>Although Amazon S3 stores your data across multiple geographically distant Availability Zones by default, compliance requirements might dictate that you store data at even greater distances. Cross-Region Replication (CRR) allows you to replicate data between distant AWS Regions to satisfy these requirements.</p>
 <p>Incorrect options:</p>
 <p><strong>Use Same-Region replication (SRR) to replicate data between distant AWS Regions</strong> - SRR is used to copy objects across Amazon S3 buckets in the same AWS Region, so this option is incorrect.</p>
 <p>Exam Alert:</p>
 <p>Please review the differences between SRR and CRR: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q8-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/replication.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/replication.html</a></p>
 <p><strong>For every new object, trigger a lambda function to write data into a bucket in another AWS Region</strong> - Although this solution is feasible, it's not resource efficient as the lambda is used to do something which S3 CRR can achieve off-the-shelf.</p>
 <p><strong>Run a daily job on an EC2 instance to copy objects into another Region</strong> - Creating a daily job on EC2 instance to copy objects into another Region involves a lot of development effort. It is much better to use S3 CRR for this task.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/replication.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/replication.html</a></p>
</div>

**Question 45**

45. A cyber-security agency uses AWS Cloud and wants to carry out security assessments on their own AWS infrastructure without any prior approval from AWS. Which of the following describes/facilitates this practice?
*  A. Penetration Testing
*  B. AWS Secrets Manager
*  C. Network Stress Testing
*  D. Amazon Inspector

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Penetration Testing</strong></p>
 <p>AWS customers can carry out security assessments or penetration tests against their AWS infrastructure without prior approval for few common AWS services. Customers are not permitted to conduct any security assessments of AWS infrastructure, or the AWS services themselves.</p>
 <p>Incorrect options:</p>
 <p><strong>Network Stress Testing</strong> - AWS considers "network stress test" to be when a test sends a large volume of legitimate or test traffic to a specific intended target application. The endpoint and infrastructure are expected to be able to handle this traffic.</p>
 <p><strong>Amazon Inspector</strong> - Amazon Inspector is an automated, security assessment service that helps you check for unintended network accessibility of your Amazon EC2 instances and for vulnerabilities on those EC2 instances. Amazon Inspector assessments are offered to you as pre-defined rules packages mapped to common security best practices and vulnerability definitions.</p>
 <p><strong>AWS Secrets Manager</strong> - AWS Secrets Manager helps you protect secrets needed to access your applications, services, and IT resources. The service enables you to easily rotate, manage, and retrieve database credentials, API keys, and other secrets throughout their lifecycle. Users and applications retrieve secrets with a call to Secrets Manager APIs, eliminating the need to hardcode sensitive information in plain text.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/security/penetration-testing/">https://aws.amazon.com/security/penetration-testing/</a></p>
</div>

**Question 46**

46. A medical device company is looking for a durable and cost-effective way of storing their historic data. Due to compliance requirements, the data must be stored for 10 years. Which AWS Storage solution will you suggest?
*  A. AWS Storage Gateway
*  B. S3 Glacier Deep Archive
*  C. Amazon EFS
*  D. S3 Glacier

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>S3 Glacier Deep Archive</strong></p>
 <p>S3 Glacier Deep Archive is Amazon S3’s lowest-cost storage class and supports long-term retention and digital preservation for data that may be accessed once or twice in a year. It is designed for customers — particularly those in highly-regulated industries, such as the Financial Services, Healthcare, and Public Sectors — that retain data sets for 7-10 years or longer to meet regulatory compliance requirements. S3 Glacier Deep Archive can also be used for backup and disaster recovery use cases. It has a retrieval time (first byte latency) of 12 to 48 hours.</p>
 <p>S3 Glacier Deep Archive Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q35-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/s3/storage-classes/">https://aws.amazon.com/s3/storage-classes/</a></p>
 <p>Incorrect options:</p>
 <p><strong>S3 Glacier</strong> - Amazon S3 Glacier is a secure, durable, and extremely low-cost Amazon S3 cloud storage class for data archiving and long-term backup. It is designed to deliver 99.999999999% durability, and provide comprehensive security and compliance capabilities that can help meet even the most stringent regulatory requirements. Glacier Deep Archive is a better fit as it is more cost-optimal than Glacier for the given use-case.</p>
 <p><strong>AWS Storage Gateway</strong> - AWS Storage Gateway is a hybrid cloud storage service that gives you on-premises access to virtually unlimited cloud storage. All data transferred between the gateway and AWS storage is encrypted using SSL (for all three types of gateways - File, Volume and Tape Gateways). Storage Gateway cannot be used for data archival.</p>
 <p><strong>Amazon EFS</strong> - Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed elastic NFS file system for use with AWS Cloud services and on-premises resources. It is built to scale on-demand to petabytes without disrupting applications, growing and shrinking automatically as you add and remove files, eliminating the need to provision and manage capacity to accommodate growth.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/s3/storage-classes/">https://aws.amazon.com/s3/storage-classes/</a></p>
</div>

**Question 47**

47. Which AWS services support High Availability by default? (Select two)
*  A. EFS
*  B. Instance Store
*  C. Redshift
*  D. DynamoDB
*  E. EBS

**Answer** A, D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>DynamoDB</strong> - Amazon DynamoDB is a key-value and document database that delivers single-digit millisecond performance at any scale. It's a fully managed, multi-Region, multi-master, durable database with built-in security, backup and restore, and in-memory caching for internet-scale applications. All of your data is stored on solid-state disks (SSDs) and is automatically replicated across multiple Availability Zones in an AWS Region, providing built-in high availability and data durability.</p>
 <p>DynamoDB High Availability: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q12-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html">https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html</a></p>
 <p><strong>EFS</strong> - Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed elastic NFS file system for use with AWS Cloud services and on-premises resources. It is built to scale on-demand to petabytes without disrupting applications, growing and shrinking automatically as you add and remove files, eliminating the need to provision and manage capacity to accommodate growth. Amazon EFS is a regional service storing data within and across multiple Availability Zones (AZs) for high availability and durability.</p>
 <p>EFS High Availability: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q12-i2.jpg?raw=true"> via - <a href="https://aws.amazon.com/efs/faq/">https://aws.amazon.com/efs/faq/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Redshift</strong> - Amazon Redshift is a fast, fully managed cloud data warehouse that makes it simple and cost-effective to analyze all your data using standard SQL and your existing Business Intelligence (BI) tools.</p>
 <p>Amazon Redshift only supports Single-AZ deployments: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q12-i3.jpg?raw=true"> via - <a href="https://aws.amazon.com/redshift/faqs/">https://aws.amazon.com/redshift/faqs/</a></p>
 <p><strong>EBS</strong> - Amazon Elastic Block Store (EBS) is an easy to use, high-performance block storage service designed for use with Amazon Elastic Compute Cloud (EC2) for both throughput and transaction-intensive workloads at any scale. EBS volumes are replicated within an Availability Zone (AZ) and can easily scale to petabytes of data.</p>
 <p><strong>Instance Store</strong> - As Instance Store volumes are tied to an EC2 instance, they are also single AZ entities.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/efs/faq/">https://aws.amazon.com/efs/faq/</a></p>
 <p><a href="https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html">https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html</a></p>
 <p><a href="https://aws.amazon.com/redshift/faqs/">https://aws.amazon.com/redshift/faqs/</a></p>
 <p><a href="https://aws.amazon.com/ebs/">https://aws.amazon.com/ebs/</a></p>
</div>

**Question 48**

48. What is the primary benefit of deploying an RDS database in a Read Replica configuration?
*  A. Read Replica reduces database usage costs
*  B. Read Replica improves database scalability
*  C. Read Replica protects the database from a regional failure
*  D. Read Replica enhances database availability

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Read Replica improves database scalability</strong></p>
 <p>Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a relational database in the cloud. Read Replicas allow you to create read-only copies that are synchronized with your master database. Read Replicas are used for improved read performance. You can also place your read replica in a different AWS Region closer to your users for better performance. Read Replicas are an example of horizontal scaling of resources.</p>
 <p>Read Replica Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q31-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/rds/features/multi-az/">https://aws.amazon.com/rds/features/multi-az/</a></p>
 <p>Exam Alert:</p>
 <p>Please review the differences between Multi-AZ, Multi-Region and Read Replica deployments for RDS: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q31-i2.jpg?raw=true"> via - <a href="https://aws.amazon.com/rds/features/multi-az/">https://aws.amazon.com/rds/features/multi-az/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Read Replica enhances database availability</strong> -Amazon RDS Multi-AZ deployments provide enhanced availability and durability for RDS database (DB) instances, making them a natural fit for production database workloads. When you provision a Multi-AZ DB Instance, Amazon RDS automatically creates a primary DB Instance and synchronously replicates the data to a standby instance in a different Availability Zone (AZ). Read Replica cannot enhance database availability.</p>
 <p><strong>Read Replica protects the database from a regional failure</strong> - You need to use RDS in Multi-Region deployment configuration to protect from a regional failure. Read Replica cannot protect from a regional failure.</p>
 <p><strong>Read Replica reduces database usage costs</strong> - RDS with Read Replicas increases the database costs compared to the standard deployment. So this option is incorrect.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/rds/features/multi-az/">https://aws.amazon.com/rds/features/multi-az/</a></p>
</div>

**Question 49**

49. A financial services enterprise plans to enable Multi-Factor Authentication (MFA) for its employees. For ease of travel, they prefer not to use any physical devices to implement MFA. Which of the below options is best suited for this use case?
*  A. Hardware MFA device
*  B. Virtual MFA device
*  C. U2F security key
*  D. Soft Token MFA device

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Virtual MFA device</strong></p>
 <p>A software app that runs on a phone or other device and emulates a physical device. The device generates a six-digit numeric code based upon a time-synchronized one-time password algorithm. The user must type a valid code from the device on a second webpage during sign-in. Each virtual MFA device assigned to a user must be unique. A user cannot type a code from another user's virtual MFA device to authenticate.</p>
 <p>Google Authenticator is an example of a Virtual MFA device: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q36-i1.jpg?raw=true"></p>
 <p>Incorrect options:</p>
 <p><strong>U2F security key</strong> - A device that you plug into a USB port on your computer. U2F is an open authentication standard hosted by the FIDO Alliance. When you enable a U2F security key, you sign in by entering your credentials and then tapping the device instead of manually entering a code.</p>
 <p><strong>Hardware MFA device</strong> - A hardware device that generates a six-digit numeric code based upon a time-synchronized one-time password algorithm. The user must type a valid code from the device on a second webpage during sign-in. Each MFA device assigned to a user must be unique. A user cannot type a code from another user's device to be authenticated.</p>
 <p><strong>Soft Token MFA device</strong> - This is a made-up option and has been added as a distractor.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa.html">https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa.html</a></p>
</div>

**Question 50**

50. Gmail is an example of which of the following Cloud Computing Models?
*  A. Function as a Service (FaaS)
*  B. Platform as a Service (PaaS)
*  C. Infrastructure as a Service (IaaS)
*  D. Software as a Service (SaaS)

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Software as a Service (SaaS)</strong></p>
 <p>Software as a Service (SaaS) provides you with a complete product that is run and managed by the service provider. With a SaaS offering, you don’t have to think about how the service is maintained or how the underlying infrastructure is managed. You only need to think about how you will use that particular software. Gmail is an example of a SaaS service.</p>
 <p>Overview of Cloud Computing Types: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q26-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/types-of-cloud-computing/">https://aws.amazon.com/types-of-cloud-computing/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Infrastructure as a Service (IaaS)</strong> - Infrastructure as a Service (IaaS) contains the basic building blocks for cloud IT. It typically provides access to networking features, computers (virtual or on dedicated hardware), and data storage space. IaaS gives the highest level of flexibility and management control over IT resources. EC2 is an example of an IaaS service.</p>
 <p><strong>Platform as a Service (PaaS)</strong> - Platform as a Service (PaaS) removes the need to manage underlying infrastructure (usually hardware and operating systems), and allows you to focus on the deployment and management of your applications. You don’t need to worry about resource procurement, capacity planning, software maintenance, patching, or any of the other undifferentiated heavy lifting involved in running your application. Beanstalk is an example of a PaaS service.</p>
 <p><strong>Function as a Service (FaaS)</strong> - Function as a service (FaaS) is a category of cloud computing services that provides a platform allowing customers to develop, run, and manage application functionalities without the complexity of building and maintaining the infrastructure typically associated with developing and launching an app. Lambda is an example of a FaaS service.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/types-of-cloud-computing/">https://aws.amazon.com/types-of-cloud-computing/</a></p>
</div>

**Question 51**

51. Under the AWS Shared Responsibility Model, which of the following is the responsibility of a customer regarding lambda functions?
*  A. Maintain versions of a lambda function
*  B. Maintain all runtime environments for lambda functions
*  C. Configure networking infrastructure for the lambda functions
*  D. Patch underlying OS for the lambda function infrastructure

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Maintain versions of a lambda function</strong></p>
 <p>Under the Shared Responsibility Model, AWS is responsible for protecting the infrastructure that runs all of the services offered in the AWS Cloud. This infrastructure is composed of the hardware, software, networking, and facilities that run AWS Cloud services.</p>
 <p>Under the Shared Responsibility Model, Customer's responsibility is determined by the AWS Cloud services that a customer selects. For abstracted services, such as Amazon S3 and Amazon DynamoDB, AWS operates the infrastructure layer, the operating system, and platforms, and customers access the endpoints to store and retrieve data. Customers are responsible for managing their data (including encryption options), classifying their assets, and using IAM tools to apply the appropriate permissions.</p>
 <p>For the given use-case, the customer is responsible for maintaining the versions of a lambda function.</p>
 <p>Shared Responsibility Model Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/Shared_Responsibility_Model_V2.59d1eccec334b366627e9295b304202faf7b899b.jpg?raw=true"> via - <a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Patch underlying OS for the lambda function infrastructure</strong></p>
 <p><strong>Maintain all runtime environments for lambda functions</strong></p>
 <p><strong>Configure networking infrastructure for the lambda functions</strong></p>
 <p>As mentioned earlier, all these options fall under the ambit of AWS as far as the Shared Responsibility Model is concerned.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
</div>

**Question 52**

52. Which AWS service can be used to automate code deployment to EC2 instances as well as on-premises instances?
*  A. AWS CodeCommit
*  B. AWS CodeDeploy
*  C. AWS CloudFormation
*  D. AWS CodePipeline

**Answer** B

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS CodeDeploy</strong></p>
 <p>AWS CodeDeploy is a service that automates code deployments to any instance, including Amazon EC2 instances and instances running on-premises. AWS CodeDeploy makes it easier for you to rapidly release new features, helps you avoid downtime during deployment, and handles the complexity of updating your applications. You can use AWS CodeDeploy to automate deployments, eliminating the need for error-prone manual operations, and the service scales with your infrastructure so you can easily deploy to one instance or thousands.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS CodeCommit</strong> - AWS CodeCommit is a fully-managed source control service that hosts secure Git-based repositories. It makes it easy for teams to collaborate on code in a secure and highly scalable ecosystem. CodeCommit eliminates the need to operate your own source control system or worry about scaling its infrastructure. It cannot be used to automate code deployment.</p>
 <p><strong>AWS CloudFormation</strong> - AWS CloudFormation allows you to use programming languages or a simple text file to model and provision, in an automated and secure manner, all the resources needed for your applications across all regions and accounts. It cannot be used to automate code deployment.</p>
 <p><strong>AWS CodePipeline</strong> - AWS CodePipeline is a continuous delivery service that enables you to model, visualize, and automate the steps required to release your software. With AWS CodePipeline, you model the full release process for building your code, deploying to pre-production environments, testing your application and releasing it to production.</p>
 <p>AWS CodePipeline integrates with AWS services such as AWS CodeCommit, Amazon S3, AWS CodeBuild, AWS CodeDeploy, AWS Elastic Beanstalk, AWS CloudFormation, AWS OpsWorks, Amazon ECS, and AWS Lambda. To further elucidate, CodePipeline cannot by itself deploy the code, it can integrate with CodeDeploy for the actual deployment.</p>
 <p>How CodePipeline Works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/product-page-diagram_CodePipeLine.7b8dd19eb6478b7f6f747d936c2f0b0b66757bbf.png?raw=true"> via - <a href="https://aws.amazon.com/codepipeline/">https://aws.amazon.com/codepipeline/</a></p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/codedeploy/">https://aws.amazon.com/codedeploy/</a></p>
</div>

**Question 53**

53. Which AWS service will you use if you have to move large volumes of on-premises data to AWS Cloud from a remote location with limited bandwidth?
*  A. AWS Snowball
*  B. AWS Direct Connect
*  C. AWS Transit Gateway
*  D. AWS Virtual Private Network (VPN)

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Snowball</strong></p>
 <p>AWS Snowball, a part of the AWS Snow Family, is a data migration and edge computing device. If you have large quantities of data you need to migrate into AWS, offline data transfer with AWS Snowball can overcome the challenge of limited bandwidth, and avoid the need to lease additional bandwidth. Snowball moves terabytes of data in about a week. You can use it to move things like databases, backups, archives, healthcare records, analytics datasets, IoT sensor data and media content, especially when network conditions prevent realistic timelines for transferring large amounts of data both into and out of AWS.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Virtual Private Network (VPN)</strong> - A VPN connection refers to the connection between your Virtual Private Cloud and your on-premises network. By default, instances that you launch into an Amazon VPC can't communicate with your own (remote) network. You can enable access to your remote network from your VPC by creating an AWS Site-to-Site VPN (Site-to-Site VPN) connection, and configuring routing to pass traffic through the connection. VPN aids regular connectivity of AWS and your private om-premises network, it is not a data migration solution.</p>
 <p><strong>AWS Direct Connect</strong> - AWS Direct Connect is a cloud service solution that makes it easy to establish a dedicated network connection from your premises to AWS. You can use AWS Direct Connect to establish a private virtual interface from your on-premise network directly to your Amazon VPC, providing you with a private, high bandwidth network connection between your network and your VPC. This connection is private and does not go over the public internet. It takes at least a month to establish this physical connection. It is not feasible to set up AWS Direct Connect in remote locations.</p>
 <p><strong>AWS Transit Gateway</strong> - AWS Transit Gateway connects VPCs and on-premises networks through a central hub. This simplifies your network and puts an end to complex peering relationships. It acts as a cloud router – each new connection is only made once. VPC peering across large connections is made possible using Transit Gateway without ending up with a complex VPC peering network. Transit Gateway is not a data migration solution.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/snowball/">https://aws.amazon.com/snowball/</a></p>
</div>

**Question 54**

54. Which AWS Support plan guarantees a case response time of 15 minutes when Business Critical systems are down?
*  A. Business
*  B. Developer
*  C. Basic
*  D. Enterprise

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Enterprise</strong> - AWS Enterprise Support provides customers with concierge-like service where the main focus is helping the customer achieve their outcomes and find success in the cloud. With Enterprise Support, you get 24x7 technical support from high-quality engineers, tools and technology to automatically manage the health of your environment, consultative architectural guidance delivered in the context of your applications and use-cases, and a designated Technical Account Manager (TAM) to coordinate access to proactive/preventative programs and AWS subject matter experts. This plan provides Enhanced Technical Support as follows:</p>
 <p>24x7 access to Cloud Support Engineers via phone, chat, and email. You can have an unlimited number of contacts that can open an unlimited amount of cases. Response times are as follows:</p>
 <p>General Guidance - &lt; 24 hours</p>
 <p>System Impaired - &lt; 12 hours</p>
 <p>Production System Impaired - &lt; 4 hours</p>
 <p>Production System Down - &lt; 1 hour</p>
 <p>Business Critical System Down - &lt;15 min</p>
 <p>Benefits of AWS Enterprise Support Plan: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/ES graphic.4eefb3e4efe68c6e1b0ddc5a0da81f1b80fa3664.png?raw=true"> via - <a href="https://aws.amazon.com/premiumsupport/plans/enterprise/">https://aws.amazon.com/premiumsupport/plans/enterprise/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Business</strong> - AWS recommends Business Support if you have production workloads on AWS and want 24x7 phone, email, and chat access to technical support and architectural guidance in the context of your specific use-cases. You get full access to AWS Trusted Advisor Best Practice Checks. This plan does not guarantee any specific response time for Business Critical systems.</p>
 <p><strong>Developer</strong> - AWS recommends Developer Support if you are testing or doing early development on AWS and want the ability to get email-based technical support during business hours as well as general architectural guidance as you build and test. You do not get access to Infrastructure Event Management with this plan. This plan does not guarantee any specific response time for Business Critical systems.</p>
 <p><strong>Basic</strong> - The basic plan only provides access to the following:</p>
 <p>Customer Service &amp; Communities - 24x7 access to customer service, documentation, whitepapers, and support forums. AWS Trusted Advisor - Access to the 7 core Trusted Advisor checks and guidance to provision your resources following best practices to increase performance and improve security. AWS Personal Health Dashboard - A personalized view of the health of AWS services, and alerts when your resources are impacted. This plan does not guarantee any specific response time for Business Critical systems.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/premiumsupport/plans/enterprise/">https://aws.amazon.com/premiumsupport/plans/enterprise/</a></p>
</div>

**Question 55**

55. Which of the following statements are true about Cost Allocation Tags in AWS Billing? (Select two)
*  A. Tags helps in organizing resources and are a mandatory configuration item to run reports
*  B. For each resource, each tag key must be unique, and each tag key can have only one value
*  C. For each resource, each tag key must be unique, but can have multiple values
*  D. Only user-defined tags need to be activated before they can appear in Cost Explorer or on a cost allocation report
*  E. You must activate both AWS generated tags and user-defined tags separately before they can appear in Cost Explorer or on a cost allocation report

**Answer** B, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>For each resource, each tag key must be unique, and each tag key can have only one value</strong></p>
 <p><strong>You must activate both AWS generated tags and user-defined tags separately before they can appear in Cost Explorer or on a cost allocation report</strong></p>
 <p>A Cost Allocation Tag is a label that you or AWS assigns to an AWS resource. Each tag consists of a key and a value. For each resource, each tag key must be unique, and each tag key can have only one value. You can use tags to organize your resources, and cost allocation tags to track your AWS costs on a detailed level.</p>
 <p>AWS provides two types of cost allocation tags, an AWS generated tags and user-defined tags. AWS defines, creates, and applies the AWS generated tags for you, and you define, create, and apply user-defined tags. You must activate both types of tags separately before they can appear in Cost Explorer or on a cost allocation report.</p>
 <p>AWS Cost Allocation Tags Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q64-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/cost-alloc-tags.html">https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/cost-alloc-tags.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Tags helps in organize resources and are a mandatory configuration item to run reports</strong> - Tags definitely help organize resources as per an organization's requirement; they are not mandatory though.</p>
 <p><strong>For each resource, each tag key must be unique, but can have multiple values</strong> - For each resource, each tag key must be unique, and each tag key can have only one value.</p>
 <p><strong>Only user-defined tags need to be activated before they can appear in Cost Explorer or on a cost allocation report</strong> - As explained above, both kinds of tags (user-defined and AWS generated) need to be activated separately before they can appear in report generation.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/cost-alloc-tags.html">https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/cost-alloc-tags.html</a></p>
</div>

**Question 56**

56. AWS Trusted Advisor analyzes your AWS environment and provides best practice recommendations for which of the following categories? (Select two)?
*  A. Change Management
*  B. Elasticity
*  C. Cost Optimization
*  D. Documentation
*  E. Service Limits

**Answer** C, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>Cost Optimization</strong></p>
 <p><strong>Service Limits</strong></p>
 <p>AWS Trusted Advisor is an online tool that provides real-time guidance to help provision your resources following AWS best practices. Whether establishing new workflows, developing applications, or as part of ongoing improvement, recommendations provided by Trusted Advisor on a regular basis help keep your solutions provisioned optimally. AWS Trusted Advisor analyzes your AWS environment and provides best practice recommendations in five categories: Cost Optimization, Performance, Security, Fault Tolerance, Service Limits.</p>
 <p>How Trusted Advisor Works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/AWS-trusted-advisor.5b9909d5f29f680eeb12ccff536e8d88d8701304.png?raw=true"> via - <a href="https://aws.amazon.com/premiumsupport/technology/trusted-advisor/">https://aws.amazon.com/premiumsupport/technology/trusted-advisor/</a></p>
 <p>AWS Trusted Advisor Recommendations: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q43-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/premiumsupport/technology/trusted-advisor/">https://aws.amazon.com/premiumsupport/technology/trusted-advisor/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Elasticity</strong></p>
 <p><strong>Documentation</strong></p>
 <p><strong>Change Management</strong></p>
 <p>These three options are made-up and have no importance in the context of AWS Trusted Advisor.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/premiumsupport/technology/trusted-advisor/">https://aws.amazon.com/premiumsupport/technology/trusted-advisor/</a></p>
</div>

**Question 57**

57. Which of the following is correct regarding the AWS Shield Advanced pricing?
*  A. AWS Shield Advanced is a free service for AWS Business Support plan
*  B. AWS Shield Advanced is a free service for all AWS Support plans
*  C. AWS Shield Advanced offers protection against higher fees that could result from a DDoS attack
*  D. AWS Shield Advanced is a free service for AWS Enterprise Support plan

**Answer** C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Shield Advanced offers protection against higher fees that could result from a DDoS attack</strong></p>
 <p>AWS Shield Advanced offers some cost protection against spikes in your AWS bill that could result from a DDoS attack. This cost protection is provided for your Elastic Load Balancing load balancers, Amazon CloudFront distributions, Amazon Route 53 hosted zones, Amazon Elastic Compute Cloud instances, and your AWS Global Accelerator accelerators.</p>
 <p>AWS Shield Advanced is a paid service for all customers, irrespective of the Support plan.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Shield Advanced is a free service for AWS Enterprise Support plan</strong></p>
 <p><strong>AWS Shield Advanced is a free service for AWS Business Support plan</strong></p>
 <p><strong>AWS Shield Advanced is a free service for all AWS Support plans</strong></p>
 <p>These three options contradict the details provided earlier in the explanation, so these options are incorrect.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/waf/latest/developerguide/ddos-overview.html">https://docs.aws.amazon.com/waf/latest/developerguide/ddos-overview.html</a></p>
</div>

**Question 58**

58. Which of the following AWS services specialize in data migration from on-premises to AWS Cloud? (Select two)
*  A. Site-to-Site VPN
*  B. Snowball
*  C. Transit Gateway
*  D. Direct Connect
*  E. Database Migration Service

**Answer** B, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>Snowball</strong> - AWS Snowball is a data transport solution that accelerates moving terabytes to petabytes of data into and out of AWS services using storage devices designed to be secure for physical transport.</p>
 <p><strong>Database Migration Service</strong> - AWS Database Migration Service helps you migrate databases from on-premises to AWS quickly and securely. The source database remains fully operational during the migration, minimizing downtime to applications that rely on the database. The AWS Database Migration Service can migrate your data to and from the most widely used commercial and open-source databases.</p>
 <p>You can do both homogeneous and heterogeneous database migration using Database Migration Service: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/product-page-diagram_AWS-DMS_homogeneous-database-migrations-1.703dcf071fa58120bcd52b9194f9bf7d9a3d9110.png?raw=true"> via - <a href="https://aws.amazon.com/dms/">https://aws.amazon.com/dms/</a></p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/product-page-diagram_AWS-DMS_heterogeneous-database-migrations-2.3616bac30ab86d4310ddadfdec5d6e6ba4d8b81d.png?raw=true"> via - <a href="https://aws.amazon.com/dms/">https://aws.amazon.com/dms/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Site to Site VPN</strong> - AWS Site-to-Site VPN creates a secure connection between your data center or branch office and your AWS cloud resources. This connection goes over the public internet. Site to Site VPN is a connectivity service and it does not specialize in data migration.</p>
 <p><strong>Direct Connect</strong> - AWS Direct Connect creates a dedicated private connection from a remote network to your VPC. This is a private connection and does not use the public internet. Takes at least a month to establish this connection. Direct Connect is a connectivity service and it does not specialize in data migration.</p>
 <p><strong>Transit Gateway</strong> - AWS Transit Gateway connects VPCs and on-premises networks through a central hub. This simplifies your network and puts an end to complex peering relationships. It acts as a cloud router – each new connection is only made once. As you expand globally, inter-Region peering connects AWS Transit Gateways using the AWS global network. Your data is automatically encrypted and never travels over the public internet. Transit Gateway is a connectivity service and it does not specialize in data migration.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/getting-started/projects/migrate-petabyte-scale-data/services-costs/">https://aws.amazon.com/getting-started/projects/migrate-petabyte-scale-data/services-costs/</a></p>
 <p><a href="https://aws.amazon.com/dms/">https://aws.amazon.com/dms/</a></p>
 <p><a href="https://aws.amazon.com/vpn/">https://aws.amazon.com/vpn/</a></p>
 <p><a href="https://aws.amazon.com/directconnect/">https://aws.amazon.com/directconnect/</a></p>
</div>

**Question 59**

59. According to the AWS Shared Responsibility Model, which of the following are responsibilities of the customer (select 2)?
*  A. Compliance validation of Cloud infrastructure
*  B. Operating system patches and updates of an EC2 instance
*  C. Enabling data encryption of data stored in S3 buckets
*  D. AWS Global Network Security
*  E. Ensuring AWS employees cannot access customer data

**Answer** B, C

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p>Under the Shared Responsibility Model, AWS is responsible for protecting the infrastructure that runs all of the services offered in the AWS Cloud. This infrastructure is composed of the hardware, software, networking, and facilities that run AWS Cloud services. Customer's responsibility is determined by the AWS Cloud services that a customer selects.</p>
 <p>Security and Compliance is a shared responsibility between AWS and the customer. This shared model can help relieve the customer’s operational burden as AWS operates, manages and controls the components from the host operating system and virtualization layer down to the physical security of the facilities in which the service operates.</p>
 <p><strong>Operating system patches and updates of an EC2 instance</strong> - Security "in" the cloud is the responsibility of the customer. A service such as Amazon Elastic Compute Cloud (Amazon EC2) is categorized as Infrastructure as a Service (IaaS) and, as such, requires the customer to perform all of the necessary security configuration and management tasks.</p>
 <p><strong>Enabling data encryption of data stored in S3 buckets</strong> - In the Shared Responsibility Model, customers are responsible for managing their data (including encryption options), classifying their assets, and using IAM tools to apply the appropriate permissions.</p>
 <p>Shared Responsibility Model Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/Shared_Responsibility_Model_V2.59d1eccec334b366627e9295b304202faf7b899b.jpg?raw=true"> via - <a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
 <p>Incorrect options:</p>
 <p><strong>AWS Global Network Security</strong> - Cloud infrastructure management is the responsibility of AWS.</p>
 <p><strong>Ensuring AWS employees cannot access customer data</strong> - Ensuring protection of customer data and keeping it safe from AWS employees is the responsibility of AWS.</p>
 <p><strong>Compliance validation of Cloud infrastructure</strong> - Cloud security and compliance are the responsibilities of AWS.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model/</a></p>
</div>

**Question 60**

60. A multi-national company has its business-critical data stored on a fleet of Amazon EC2 instances, in various countries, configured in region-specific compliance rules. To demonstrate compliance, the company needs to submit historical configurations on a regular basis. Which AWS service is best suited for this requirement?
*  A. Amazon Macie
*  B. Amazon GuardDuty
*  C. AWS CloudTrail
*  D. AWS Config

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AWS Config</strong></p>
 <p>AWS Config provides a detailed view of the configuration of AWS resources in your AWS account. This includes how the resources are related to one another and how they were configured in the past so that you can see how the configurations and relationships change over time. AWS Config is designed to help you oversee your application resources in the following scenarios: Resource Administration, Auditing and Compliance, Managing and Troubleshooting Configuration Changes, Security Analysis.</p>
 <p>How AWS Config Works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/product-page-diagram-Config_how-it-works.bd28728a9066c55d7ee69c0a655109001462e25b.png?raw=true"> via - <a href="https://aws.amazon.com/config/">https://aws.amazon.com/config/</a></p>
 <p>Incorrect options:</p>
 <p><strong>Amazon Macie</strong> - Amazon Macie is a fully managed data security and data privacy service that uses machine learning and pattern matching to discover and protect your sensitive data in AWS. Macie helps identify and alert you to sensitive data, such as personally identifiable information (PII). This service is an added security feature for data privacy and is not the best fit for the current requirement.</p>
 <p><strong>AWS CloudTrail</strong> - AWS CloudTrail is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account. With CloudTrail, you can log, continuously monitor, and retain account activity related to actions across your AWS infrastructure. CloudTrail provides an event history of your AWS account activity, including actions taken through the AWS Management Console, AWS SDKs, command-line tools, and other AWS services.</p>
 <p>Config is focused on the configuration of your AWS resources and reports with detailed snapshots on how your resources have changed. Whereas CloudTrail focuses on the events or API calls, that drive those changes. It focuses on the user, application, and activity performed on the system.</p>
 <p><strong>Amazon GuardDuty</strong> - Amazon GuardDuty is a threat detection service that monitors malicious activity and unauthorized behavior to protect your AWS account. GuardDuty analyzes billions of events across your AWS accounts from AWS CloudTrail, Amazon VPC Flow Logs, and DNS Logs. Its a threat detection service and not a configuration management and tracking service.</p>
 <p>References:</p>
 <p><a href="https://aws.amazon.com/config/">https://aws.amazon.com/config/</a></p>
 <p><a href="https://docs.aws.amazon.com/config/latest/developerguide/WhatIsConfig.html">https://docs.aws.amazon.com/config/latest/developerguide/WhatIsConfig.html</a></p>
</div>

**Question 61**

61. Which of the following statements are CORRECT regarding Security Groups and Network Access Control Lists (NACLs)? (Select two)
*  A. A NACL contains a numbered list of rules and evaluates these rules in the increasing order while deciding whether to allow the traffic
*  B. A Security Group is stateless, that is, the return traffic must be explicitly allowed
*  C. A Security Group contains a numbered list of rules and evaluates these rules in the increasing order while deciding whether to allow the traffic
*  D. A NACL is stateful, that is, it automatically allows the return traffic
*  E. A Security Group is stateful, that is, it automatically allows the return traffic

**Answer** A, E

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct options:</p>
 <p><strong>A Security Group is stateful, that is, it automatically allows the return traffic</strong></p>
 <p><strong>A NACL contains a numbered list of rules and evaluates these rules in the increasing order while deciding whether to allow the traffic</strong></p>
 <p>A security group acts as a virtual firewall for your instance to control inbound and outbound traffic. Security groups act at the instance level, not at the subnet level. Security groups are stateful — if you send a request from your instance, the response traffic for that request is allowed to flow in regardless of inbound security group rules. A security group evaluates all rules before deciding whether to allow traffic.</p>
 <p>Security Group Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q15-i1.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html">https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html</a></p>
 <p>A Network Access Control List (NACL) is an optional layer of security for your VPC that acts as a firewall for controlling traffic in and out of one or more subnets (i.e. it works at subnet level). A network ACL contains a numbered list of rules. A NACL evaluates the rules in order, starting with the lowest numbered rule, to determine whether traffic is allowed in or out of any subnet associated with the network ACL. The highest number that you can use for a rule is 32766. AWS recommends that you start by creating rules in increments (for example, increments of 10 or 100) so that you can insert new rules where you need to later on.</p>
 <p>Network Access Control List (NACL) Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q15-i2.jpg?raw=true"> via - <a href="https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html">https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>A Security Group contains a numbered list of rules and evaluates these rules in the increasing order while deciding whether to allow the traffic</strong></p>
 <p><strong>A NACL is stateful, that is, it automatically allows the return traffic</strong></p>
 <p><strong>A Security Group is stateless, that is, the return traffic must be explicitly allowed</strong></p>
 <p>These three options contradict the details provided earlier in the explanation, so these options are incorrect.</p>
 <p>References:</p>
 <p><a href="https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html">https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html</a></p>
 <p><a href="https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html">https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html</a></p>
</div>

**Question 62**

62. Which of the following statements is correct regarding the AWS Elastic File System (EFS) storage service?
*  A. EC2 instances can access files on an EFS file system across many Availability Zones, Regions and VPCs
*  B. EC2 instances can access files on an EFS file system across many Availability Zones but not across VPCs and Regions
*  C. EC2 instances can access files on an EFS file system only in one Availability Zone
*  D. EC2 instances can access files on an EFS file system across many Availability Zones and VPCs but not across Regions

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>EC2 instances can access files on an EFS file system across many Availability Zones, Regions and VPCs</strong></p>
 <p>Amazon EFS is a regional service storing data within and across multiple Availability Zones (AZs) for high availability and durability. Amazon EC2 instances can access your file system across AZs, regions, and VPCs, while on-premises servers can access using AWS Direct Connect or AWS VPN.</p>
 <p>Amazon EFS Overview: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q23-i1.jpg?raw=true"> via - <a href="https://aws.amazon.com/efs/">https://aws.amazon.com/efs/</a></p>
 <p>Incorrect options:</p>
 <p><strong>EC2 instances can access files on an EFS file system only in one Availability Zone</strong></p>
 <p><strong>EC2 instances can access files on an EFS file system across many Availability Zones but not across VPCs and Regions</strong></p>
 <p><strong>EC2 instances can access files on an EFS file system across many Availability Zones and VPCs but not across Regions</strong></p>
 <p>These three options contradict the details provided earlier in the explanation, so these options are incorrect.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/efs/">https://aws.amazon.com/efs/</a></p>
</div>

**Question 63**

63. A startup runs its proprietary application on docker containers. As a Cloud Practitioner, which AWS service would you recommend so that the startup can run containers and still have access to the underlying servers?
*  A. Amazon Elastic Container Service (Amazon ECS)
*  B. Amazon Elastic Container Registry (ECR)
*  C. AWS Lambda
*  D. AWS Fargate

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>Amazon Elastic Container Service (Amazon ECS)</strong> - Amazon Elastic Container Service (Amazon ECS) is a highly scalable, fast, container management service that makes it easy to run, stop, and manage Docker containers on a cluster. This is not a fully managed service and you can manage the underlying servers yourself.</p>
 <p>Incorrect options:</p>
 <p><strong>AWS Fargate</strong> - AWS Fargate is a serverless compute engine for containers. It works with both Amazon Elastic Container Service (ECS) and Amazon Elastic Kubernetes Service (EKS). Fargate makes it easy for you to focus on building your applications. Fargate removes the need to provision and manage servers, lets you specify and pay for resources per application, and improves security through application isolation by design. With Fargate, you do not have access to the underlying servers, so this option is incorrect.</p>
 <p>How Fargate Works: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/Product-Page-Diagram_Fargate@2x.a20fb2b15c2aebeda3a44dbbb0b10b82fb89aa6a.png?raw=true"> via - <a href="https://aws.amazon.com/fargate/">https://aws.amazon.com/fargate/</a></p>
 <p><strong>AWS Lambda</strong> - AWS Lambda is a compute service that lets you run code without provisioning or managing servers. AWS Lambda executes your code only when needed and scales automatically, from a few requests per day to thousands per second. Lambda does not support running container applications.</p>
 <p><strong>Amazon Elastic Container Registry (ECR)</strong> - Amazon Elastic Container Registry (ECR) can be used to store, manage, and deploy Docker container images. Amazon ECR eliminates the need to operate your container repositories. ECR does not support running container applications.</p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/fargate/">https://aws.amazon.com/fargate/</a></p>
</div>

**Question 64**

64. Which feature of AWS Cloud offers the ability to innovate faster and rapidly develop, test and launch software applications?
*  A. Agility
*  B. Cost savings
*  C. Ability to deploy globally in minutes
*  D. Elasticity

**Answer** A

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p>Cloud computing is the on-demand delivery of IT resources over the Internet with pay-as-you-go pricing. Instead of buying, owning, and maintaining physical data centers and servers, you can access technology services, such as computing power, storage, and databases, on an as-needed basis from a cloud provider like Amazon Web Services (AWS).</p>
 <p><strong>Agility</strong> - Agility refers to the ability of the cloud to give you easy access to a broad range of technologies so that you can innovate faster and build nearly anything that you can imagine. You can quickly spin up resources as you need them – from infrastructure services, such as compute, storage, and databases, to Internet of Things, machine learning, data lakes and analytics, and much more.</p>
 <p>Incorrect options:</p>
 <p><strong>Elasticity</strong> - With cloud computing elasticity, you don’t have to over-provision resources upfront to handle peak levels of business activity in the future. Instead, you provision the number of resources that you actually need. You can scale these resources up or down instantly to grow and shrink capacity as your business needs change.</p>
 <p><strong>Cost savings</strong> - The cloud allows you to trade capital expenses (such as data centers and physical servers) for variable expenses, and only pay for IT as you consume it. Plus, the variable expenses are much lower than what you would pay to do it yourself because of the economies of scale.</p>
 <p><strong>Ability to deploy globally in minutes</strong> - With the cloud, you can expand to new geographic regions and deploy globally in minutes. For example, AWS has infrastructure all over the world, so you can deploy your application in multiple physical locations with just a few clicks. Putting applications in closer proximity to end users reduces latency and improves their experience.</p>
 <p>Exam Alert:</p>
 <p>Please review the benefits of Cloud Computing: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q51-i1.jpg?raw=true"></p>
 <p><img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/pt3-q51-i2.jpg?raw=true"> via - <a href="https://aws.amazon.com/what-is-cloud-computing/">https://aws.amazon.com/what-is-cloud-computing/</a></p>
 <p>Reference:</p>
 <p><a href="https://aws.amazon.com/what-is-cloud-computing/">https://aws.amazon.com/what-is-cloud-computing/</a></p>
</div>

**Question 65**

65. Which of the following AWS entities provides the information required to launch an EC2 instance?
*  A. EBS
*  B. EFS
*  C. Lambda
*  D. AMI

**Answer** D

**Explanation**
<div data-purpose="safely-set-inner-html:rich-text-viewer:html" id="question-explanation" class="rt-scaffolding">
 <p>Correct option:</p>
 <p><strong>AMI</strong></p>
 <p>An Amazon Machine Image (AMI) provides the information required to launch an instance. You must specify an AMI when you launch an instance.</p>
 <p>An AMI includes the following:</p>
 <p>One or more EBS snapshots, or, for instance-store-backed AMIs, a template for the root volume of the instance (for example, an operating system, an application server, and applications).</p>
 <p>Launch permissions that control which AWS accounts can use the AMI to launch instances.</p>
 <p>A block device mapping that specifies the volumes to attach to the instance when it's launched.</p>
 <p>The following diagram summarizes the AMI lifecycle: <img src="https://github.com/robertoplatz/aws_certified_practitioner_exam/blob/main/questions/exam03/images/ami_lifecycle.png?raw=true"> via - <a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html</a></p>
 <p>Incorrect options:</p>
 <p><strong>Lambda</strong> - AWS Lambda lets you run code without provisioning or managing servers. You pay only for the compute time you consume.</p>
 <p><strong>EFS</strong> - Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed elastic NFS file system for use with AWS Cloud services and on-premises resources. It is built to scale on-demand to petabytes without disrupting applications, growing and shrinking automatically as you add and remove files, eliminating the need to provision and manage capacity to accommodate growth.</p>
 <p><strong>EBS</strong> - Amazon Elastic Block Store (EBS) is an easy to use, high-performance block storage service designed for use with Amazon Elastic Compute Cloud (EC2) for both throughput and transaction-intensive workloads at any scale.</p>
 <p>Reference:</p>
 <p><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html</a></p>
</div>

**Question 66**