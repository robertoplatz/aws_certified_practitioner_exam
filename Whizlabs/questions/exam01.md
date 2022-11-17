# AWS Certified Cloud Practitioner Exam

## Whizlabs - Exam 01

**Question 1**

1. Which AWS service provides infrastructure security optimization recommendations?
*  A. AWS Application Programming Interface(API)
*  B. Reserved Instances
*  C. AWS Trusted Advisor
*  D. Amazon Elastic Compute Cloud (Amazon EC2) SpotFleet

**Answer** C

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer – C</p>
  <p>The AWS documentation mentions the following:</p>
  <p>&nbsp;An online resource to help you reduce cost, increase performance, and improve security by optimizing your AWS environment, Trusted Advisor provides real time guidance to help you provision your resources following AWS best practices</p>
  <p>For more information on the AWS Trusted Advisor, please refer to the below URL:</p>
  <ul>
   <li><a href="https://aws.amazon.com/premiumsupport/trustedadvisor/" target="_blank">https://aws.amazon.com/premiumsupport/trustedadvisor/</a></li>
  </ul>
  <p>Choices A, B, and D are incorrect. They are not related to infrastructure security optimization.</p>
 </div>
</div>

**Question 2**

2. A file-sharing service uses Amazon S3 to store files uploaded by users. Files are accessed with random frequency.Popular ones are downloaded every day whilst others not so often and some rarely. What is the most cost-effective Amazon S3 object storage class to implement?
*  A. Amazon S3 Standard
*  B. Amazon S3 Glacier
*  C. Amazon S3 One Zone-Infrequently Accessed
*  D. Amazon S3 Intelligent-Tiering

**Answer** D

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer – D</strong></p>
  <p>S3 Intelligent-Tiering is a new Amazon S3 storage class designed for customers who want to optimize storage costs automatically when data access patterns change, without performance impact or operational overhead. S3 Intelligent-Tiering is the first cloud object storage class that delivers automatic cost savings by moving data between two access tiers — frequent access and infrequent access — when access patterns change, and is ideal for data with unknown or changing access patterns.</p>
  <p>S3 Intelligent-Tiering stores objects in two access tiers: one tier optimized for frequent access and another lower-cost tier optimized for infrequent access. For a small monthly monitoring and automation fee per object, S3 Intelligent-Tiering monitors access patterns and moves objects that have not been accessed for 30 consecutive days to the infrequent access tier. There are no retrieval fees in S3 Intelligent-Tiering. If an object in the infrequent access tier is accessed later, it is automatically moved back to the frequent access tier. No additional tiering fees apply when objects are moved between access tiers within the S3 Intelligent-Tiering storage class. S3 Intelligent-Tiering is designed for 99.9% availability and 99.999999999% durability, and offers the same low latency and high throughput performance of S3 Standard.</p>
  <p><a href="https://aws.amazon.com/about-aws/whats-new/2018/11/s3-intelligent-tiering/" target="_blank">https://aws.amazon.com/about-aws/whats-new/2018/11/s3-intelligent-tiering/</a></p>
  <ul>
   <li><strong>Option A&nbsp;is incorrect</strong> because Amazon S3 Standard would be an inefficient class for storing those objects that will be accessed rarely.</li>
   <li><strong>Option B&nbsp;is incorrect</strong> because storing objects that are frequently accessed in Amazon S3 Glacier would present operational bottlenecks since these objects would not be available instantly. 
    <ul style="list-style-type:circle">
     <li><a href="https://aws.amazon.com/s3/storage-classes/" target="_blank">https://aws.amazon.com/s3/storage-classes/</a></li>
    </ul></li>
   <li><strong>Option C&nbsp;is incorrect</strong> because storing those objects that are rarely accessed and those that would be accessed frequently in Amazon S3 One Zone-Infrequently Accessed would be inefficient.</li>
  </ul>
 </div>
</div>

**Question 3**

3. Which AWS service can be deployed to enhance read performance for applications while reading data from NoSQL database?
*  A. Amazon Route 53
*  B. Amazon DynamoDB Accelerator
*  C. Amazon CloudFront
*  D. AWS Greengrass

**Answer** B

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer – B</strong></p>
  <p>Amazon DynamoDB Accelerator (DAX) is a caching service for DynamoDB which can be deployed in VPC in a region where DynamoDB is deployed. For read-heavy applications, DAX can be deployed to increase throughput by providing in-memory caching.</p>
  <ul>
   <li><strong>Option A is incorrect </strong>because<strong>&nbsp;</strong>Amazon Route 53 is an AWS DNS service and cannot improve the performance of DynamoDB.</li>
   <li><strong>Option C is incorrect&nbsp;</strong>because&nbsp;Amazon CloudFront is a global content delivery network that cannot be applied to a DynamoDB table.</li>
   <li><strong>Option D is incorrect&nbsp;</strong>because<strong>&nbsp;</strong>AWS Greengrass is data caching software for connected devices.</li>
  </ul>
  <p>For more information on caching solutions with AWS, refer to the following URL:</p>
  <ul>
   <li><a href="https://aws.amazon.com/caching/aws-caching/">https://aws.amazon.com/caching/aws-caching/</a></li>
  </ul>
 </div>
</div>

**Question 4**

4. An organization utilizes a software suitethat consists of a multitude of underlying microservices hosted on the cloud. The application is frequently giving runtime errors. Which service will help in the troubleshooting process?
*  A. AWS CloudTrail
*  B. AWS CloudWatch
*  C. AWS X-Ray
*  D. Amazon OpenSearch Service

**Answer** C

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer – C</strong></p>
  <p>AWS X-Ray is a service that collects data about requests that your application serves and provides tools that you can use to view, filter, and gain insights into that data to identify issues and opportunities for optimization. AWS X-Ray helps developers analyze and debug production, distributed applications, such as those built using a microservices architecture.</p>
  <p><a href="https://aws.amazon.com/xray/" target="_blank">https://aws.amazon.com/xray/</a></p>
  <p><strong>Option A&nbsp;is INCORRECT</strong> because AWS CloudTrail primarily records user or API activity, ‘who has done what.’ It logs, continuously monitors, and retains account activity related to actions across AWS infrastructure. CloudTrail provides event history in the AWS account activity but NOT that of the interaction of software microservices within a suite.</p>
  <p><a href="https://aws.amazon.com/cloudtrail/" target="_blank">https://aws.amazon.com/cloudtrail/</a></p>
  <p><strong>Option B&nbsp;is INCORRECT</strong> because AWS CloudWatch does the primary function of monitoring and NOT debugging. It collates data and actionable insights to monitor applications. It also&nbsp;responds to system-wide performance changes, optimizes resource utilization, and gets a unified view of operational health. However, the service does neither debug nor logs errors that occur amongst software microservices within a suite.</p>
  <p><a href="https://aws.amazon.com/cloudwatch/" target="_blank">https://aws.amazon.com/cloudwatch/</a></p>
  <p><strong>Option D&nbsp;is INCORRECT</strong> because Amazon OpenSearch Service is a managed service that makes it easy to deploy, operate, and scale OpenSearch clusters in the AWS Cloud.&nbsp;It automatically detects and replaces failed OpenSearch Service nodes, reducing the overhead associated with self-managed infrastructures.&nbsp;</p>
  <p><a href="https://docs.aws.amazon.com/opensearch-service/latest/developerguide/what-is.html" target="_blank">https://docs.aws.amazon.com/opensearch-service/latest/developerguide/what-is.html</a></p>
 </div>
</div>

**Question 5**

5. According to the AWS, what is the benefit of Elasticity?
*  A. Minimize storage requirements by reducing logging and auditing activities
*  B. Create systems that scale to the required capacity based on changes in demand
*  C. Enable AWS to automatically select the most cost-effective services.
*  D. Accelerate the design process because recovery from failure is automated, reducing the need for testing

**Answer** B

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>&nbsp;</p>
  <p>Answer – B</p>
  <p>The concept of Elasticity is the means of an application having the ability to scale up and scale down based on demand. An example of such a service is the Autoscaling service</p>
  <p>For more information on AWS Autoscaling service, please refer to the below URL:</p>
  <ul>
   <li><a href="https://aws.amazon.com/autoscaling/" target="_blank">https://aws.amazon.com/autoscaling/</a></li>
  </ul>
  <p>A, C and D are incorrect. Elasticity will not have positive effects on storage, cost or design agility.</p>
  <p>&nbsp;</p>
 </div>
</div>

**Question 6**

6. Which tool can you use to forecast your AWS spending?
*  A. AWS Organizations
*  B. Amazon Dev Pay
*  C. AWS Trusted Advisor
*  D. AWS Cost Explorer

**Answer** D

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer – D</p>
  <p>The AWS Documentation mentions the following.</p>
  <p>Cost Explorer is a free tool that you can use to view your costs. You can view data up to the last 12&nbsp;months. You can&nbsp;forecast how much you are likely to spend for the next 12 months&nbsp;and get recommendations for what Reserved Instances to purchase. You can use Cost Explorer to see patterns in how much you spend on AWS resources over time, identify areas that need further inquiry, and see trends that you can use to understand your costs. You also can specify time ranges for the data&nbsp;and view time data by day or by month.</p>
  <p>For more information on the AWS Cost Explorer, please refer to the below URL:</p>
  <ul>
   <li><a href="http://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/cost-explorer-what-is.html" target="_blank">http://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/cost-explorer-what-is.html</a></li>
  </ul>
  <p>A, B and C are incorrect. These services do not relate to billing and cost.</p>
 </div>
</div>

**Question 7**

7. Which of the following is an optional Security layer attached to a subnet within a VPC for controlling traffic in &amp; out of the VPC?
*  A. VPC Flow Logs
*  B. Web Application Firewall
*  C. Security Group
*  D. Network ACL

**Answer** D

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer – D</strong></p>
  <p>Network ACL can be additionally configured on subnet level to control traffic in &amp; out of the VPC.</p>
  <ul>
   <li><strong>Option A is incorrect.&nbsp;</strong>VPC Flow Logs will capture information about IP traffic in &amp; out of VPC. This will not be used for controlling purposes.</li>
   <li><strong>Option B is incorrect.&nbsp;</strong>Web Application Firewall (WAF) can be configured to protect web applications from common security threats. It can be deployed on devices such as Amazon CloudFront, Application Load Balancer and&nbsp;Amazon API Gateway.</li>
   <li><strong>Option C is incorrect.</strong>&nbsp;Security Groups are attached at instance level &amp; not at the subnet level.</li>
  </ul>
  <p>For more information on security within VPC, refer to the following URL:</p>
  <ul>
   <li><a href="https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Security.html#VPC_Security_Comparison">https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Security.html#VPC_Security_Comparison</a></li>
  </ul>
 </div>
</div>

**Question 8**

8. Which of the following is a customer responsibility under AWS Shared Responsibility Model?
*  A. Patching of host OS deployed on Amazon S3.
*  B. Logical Access controls for underlying infrastructure.
*  C. Physical security of the facilities.
*  D. Patching of guest OS deployed on Amazon EC2 instance.

**Answer** D

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer – D</strong></p>
  <p>Under the AWS shared responsibility model,&nbsp;AWS takes care of infrastructure configuration &amp; management while customers must take care of the resources they launched within AWS.</p>
  <ul>
   <li><strong>Option A is incorrect.&nbsp;</strong>Amazon S3 is part of the infrastructure layer &amp; Patching of host OS/Configuration for Amazon S3 is responsibility of AWS.</li>
   <li><strong>Option B is incorrect.</strong>&nbsp;AWS has the responsibility for the Logical Access controls for the underlying infrastructure.</li>
   <li><strong>Option C is incorrect.</strong>&nbsp;Physical Security of the facilities is AWS responsibility.</li>
  </ul>
  <p>For more information on Shared responsibility model, refer to the following URL:</p>
  <ul>
   <li><a href="https://aws.amazon.com/compliance/shared-responsibility-model/">https://aws.amazon.com/compliance/shared-responsibility-model</a></li>
  </ul>
 </div>
</div>

**Question 9**

9. What is the AWS feature that enables fast, easyand secure transfers of files over long distances between your client and your Amazon S3 bucket?
*  A. File Transfer
*  B. HTTP Transfer
*  C. Amazon S3 Transfer Acceleration
*  D. S3 Acceleration

**Answer** C

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer – C</p>
  <p>The AWS Documentation mentions the following.</p>
  <p>Amazon S3 Transfer Acceleration enables fast, easy, and secure transfers of files over long distances between your client and an S3 bucket. Transfer Acceleration takes advantage of Amazon CloudFront’s globally distributed edge locations. As the data arrives at an edge location, data is routed to Amazon S3 over an optimized network path.</p>
  <p>For more information on S3 transfer acceleration, please visit the Link:</p>
  <ul>
   <li><a href="http://docs.aws.amazon.com/AmazonS3/latest/dev/transfer-acceleration.html" target="_blank">http://docs.aws.amazon.com/AmazonS3/latest/dev/transfer-acceleration.html</a></li>
  </ul>
  <p>Options A, B and D are incorrect. These features deal with transferring data but not between clients and an S3 bucket.</p>
 </div>
</div>

**Question 10**

10. Which of the following services can be used to optimize performance for global users totransfer large-sized data objects to a centralizedAmazon S3 bucket in us-west-1 region?
*  A. Enable S3 Transfer Acceleration on Amazon S3 bucket.
*  B. Use Amazon CloudFront Put/Post commands
*  C. Use Multipart upload
*  D. Use Amazon ElastiCache

**Answer** A

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer – A</strong></p>
  <p>S3 Transfer Acceleration can optimise performance for data transfer between users &amp; objects in Amazon S3 bucket. Transfer acceleration uses CloudFront edge location to provide accelerated data transfer to users.</p>
  <ul>
   <li><strong>Option B is incorrect </strong>as Amazon CloudFront Put/Post commands can be used for small-sized objects but for large-sized data objects, S3 Transfer Acceleration provides better performance.</li>
   <li><strong>Option C is incorrect</strong> as users should use Multipart uploads for all data objects exceeding 100 megabytes.&nbsp;But for better performance, S3 transfer acceleration should be enabled.</li>
   <li><strong>Option D is incorrect</strong> as for global users accessing S3 bucket, S3 Transfer Acceleration is a better choice..&nbsp;</li>
  </ul>
  <p>For more information on Amazon S3 Transfer Acceleration, refer to the following URLs:</p>
  <ul>
   <li><a href="https://aws.amazon.com/s3/faqs/#s3ta">https://aws.amazon.com/s3/faqs/#s3ta</a></li>
   <li><a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/optimizing-performance.html">https://docs.aws.amazon.com/AmazonS3/latest/dev/optimizing-performance.html</a></li>
  </ul>
 </div>
</div>

**Question 11**

11. There is a requirement to store objects. The objects must be downloadable via a URL. Which storage option would you choose?
*  A. Amazon S3
*  B. Amazon Glacier
*  C. Amazon Storage Gateway
*  D. Amazon EBS

**Answer** A

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer - A</p>
  <p>Amazon S3 is the perfect storage option. It also provides the facility of assigning a URL to each object which can be used to download the object.</p>
  <ul>
   <li>For more information on AWS S3, please visit the Link: 
    <ul>
     <li><a href="https://aws.amazon.com/s3/" target="_blank">https://aws.amazon.com/s3/</a></li>
    </ul></li>
   <li>B is incorrect. Glacier is for archival and long-term storage.</li>
  </ul>
  <p>This question is to check the user understanding of AWS S3 service terminology and use cases.&nbsp;Objects are stored in S3 and&nbsp;should be downloadable via a URL. It's not possible with EBS.</p>
 </div>
</div>

**Question 12**

12. There is a requirement to host a database server for a minimum period of one year. Which of the following would result in the least cost?
*  A. Spot Instances
*  B. On-Demand
*  C. No Upfront costs Reserved
*  D. Partial Upfront costs Reserved

**Answer** D

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer - D</p>
  <p>If the database is going to be used for a minimum of one year at least, it is better to get Reserved Instances. You can save on costs if you use partial upfront options.</p>
  <ul>
   <li>For more information on AWS Reserved Instances, please visit the Link: 
    <ul>
     <li><a href="https://aws.amazon.com/ec2/pricing/reserved-instances/" target="_blank">https://aws.amazon.com/ec2/pricing/reserved-instances/</a></li>
    </ul></li>
  </ul>
  <p>&nbsp;</p>
  <ul>
   <li><strong>A is incorrect</strong>. Spot instances can be terminated with fluctuations in market prices. Unless the question specifies a use case where high availability is not a requirement, this cannot be assumed.</li>
   <li><strong>B is incorrect</strong>. On-Demand is not the most cost-efficient solution.</li>
   <li><strong>C is incorrect</strong>. No upfront payment is required.&nbsp;However, it's a costlier option than Partial/All upfront payment.</li>
  </ul>
  <p>&nbsp;</p>
  <ul>
   <li>For more information on the Reserved Instances Payment option, please check below AWS Docs: 
    <ul>
     <li><a href="https://docs.aws.amazon.com/aws-technical-content/latest/cost-optimization-reservation-models/reserved-instance-payment-options.html" target="_blank">https://docs.aws.amazon.com/aws-technical-content/latest/cost-optimization-reservation-models/reserved-instance-payment-options.html</a></li>
    </ul></li>
  </ul>
  <p><strong>Note:</strong></p>
  <ul>
   <li>Reserved Instances do not renew automatically.&nbsp;When they expire, you can continue using the EC2 instance without interruption.&nbsp;But you are charged On-Demand rates. In the above example, when the Reserved Instances that cover the T2 and C4 instances expire, you go back to paying the On-Demand rates until you terminate the instances or purchase new Reserved Instances that match the instance attributes. 
    <ul>
     <li><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-reserved-instances.html" target="_blank">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-reserved-instances.html</a></li>
    </ul></li>
  </ul>
 </div>
</div>

**Question 13**

13. During an organization’s information systems audit, the administrator is requested to provide a dossier of security and compliance reports and online service agreements between the organization and AWS. Which service can they utilize to acquire this information?
*  A. AWS Artifact
*  B. AWS Resource Center
*  C. AWS Service Catalog
*  D. AWS Directory Service

**Answer** A

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer – A</strong></p>
  <p>AWS Artifact is a comprehensive resource center to have access to the AWS’ auditor-issued reports and security and compliance documentation from several renowned independent standard organizations.</p>
  <p><a href="https://aws.amazon.com/artifact/" target="_blank">https://aws.amazon.com/artifact/</a></p>
  <ul>
   <li><strong>Option B&nbsp;is INCORRECT.</strong>&nbsp;AWS Resource Center is a&nbsp; repository of tutorials, whitepapers, digital training, and&nbsp;project use&nbsp;cases that aid in learning the core concepts of Amazon Web Services.</li>
  </ul>
  <p><a href="https://aws.amazon.com/getting-started/" target="_blank">https://aws.amazon.com/getting-started/</a></p>
  <ul>
   <li><strong>Option C is INCORRECT.</strong>&nbsp;AWS Service Catalog allows organizations to create and save their own IT service catalogs for further use. But&nbsp;they have to be approved by AWS. IT service catalogs can be multi-tiered application architectures.</li>
  </ul>
  <p><a href="https://docs.aws.amazon.com/servicecatalog/latest/adminguide/introduction.html" target="_blank">https://docs.aws.amazon.com/servicecatalog/latest/adminguide/introduction.html</a></p>
  <ul>
   <li><strong>Option D&nbsp;is INCORRECT.</strong>&nbsp;AWS Directory Service is an AWS tool that provides multiple ways to use Amazon Cloud Directory and Microsoft Active Directory with other AWS services.</li>
  </ul>
  <p><a href="https://docs.aws.amazon.com/directoryservice/latest/admin-guide/what_is.html" target="_blank">https://docs.aws.amazon.com/directoryservice/latest/admin-guide/what_is.html</a></p>
 </div>
</div>

**Question 14**

14. A new department has recently joined the organization and the administrator needs to compose access permissions for the group of users. Given that they have various roles and access needs, what is the best-practice approach when granting access?
*  A. After gathering information on their access needs, the administrator should allow every user to access the most common resources and privileges on the system.
*  B. The administrator should grant all users the same permissions and then grant more upon request.&nbsp;
*  C. The administrator should grant all users the least privilege and add more privileges to only to those who need it.
*  D. Users should have no access and be granted temporary access on the occasions that they need to execute a task.

**Answer** C

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer – C</strong></p>
  <p>The best-practice for AWS Identity Access Management (IAM) is to grant the least amount of permissions on the system only to execute the required tasks of the user’s role. Additional permissions can be granted per user according to the tasks they wish to perform on the system.</p>
  <p><a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege" target="_blank">https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege</a></p>
  <ul>
   <li><strong>Option A&nbsp;is incorrect</strong> because granting users access to the most common resources presents security vulnerabilities, especially from those who have access to resources they do not need.</li>
   <li><strong>Option B&nbsp;is incorrect</strong> because granting users the same privileges on the system means other users might get access to resources they do not need to carry out their job functions. This presents a security risk.</li>
   <li><strong>Option D&nbsp;is incorrect</strong> because the users are part of the organisation; it will be cumbersome for the administrator to create temporal access passes for internal staff constantly.</li>
  </ul>
 </div>
</div>

**Question 15**

15. There is an external audit being carried out on your company. The auditor needs to have a log of 'who made the requests' to the AWS resources fromthe company’s account. Which of the following services can assist in providing these details?
*  A. Amazon CloudWatch
*  B. AWS CloudTrail
*  C. Amazon&nbsp;EC2
*  D. Amazon&nbsp;SNS

**Answer** B

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer - B</strong></p>
  <p>Using CloudTrail, one can monitor all the API activity conducted on all AWS services.</p>
  <p>The AWS Documentation additionally mentions the following.</p>
  <p>AWS CloudTrail is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account.<br> With CloudTrail, you can log, continuously monitor, and retain account activity related to actions across your AWS infrastructure. CloudTrail provides the event history of your AWS account activity, including actions taken through the AWS Management Console, AWS SDKs, command-line tools, and other AWS services. This event history simplifies security analysis, resource change tracking, and troubleshooting.</p>
  <p>For more information on AWS CloudTrail, please refer to the below URL:</p>
  <ul>
   <li><a href="https://aws.amazon.com/cloudtrail/" target="_blank">https://aws.amazon.com/cloudtrail/</a></li>
  </ul>
 </div>
</div>

**Question 16**

16. Which of the following features can be used to preview changes to be made to an AWS resource which will be deployed using the AWS CloudFormation template?
*  A. AWS CloudFormation Drift Detection
*  B. AWS CloudFormation Change Sets
*  C. AWS CloudFormation Stack Sets
*  D. AWS CloudFormation Intrinsic Functions

**Answer** B

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer – B</strong></p>
  <p>AWS CloudFormation Change&nbsp;Set&nbsp;can be used to preview changes to AWS resources when a stack is executed.</p>
  <ul>
   <li><strong>Option A is incorrect</strong> as AWS CloudFormation Drift Detection is used to detect any changes made to resources outside of CloudFormation templates. It would not be able to preview changes that will be made by CloudFormation Templates.</li>
   <li><strong>Option C is incorrect </strong>as these are groups of stacks that are managed together.</li>
   <li><strong>Option D is incorrect</strong> as these Intrinsic Functions are used for assigning values to properties in CloudFormation templates.</li>
  </ul>
  <p>For more information on AWS CloudFormation, refer to the following URL:</p>
  <ul>
   <li><a href="https://aws.amazon.com/cloudformation/features/">https://aws.amazon.com/cloudformation/features/</a></li>
  </ul>
 </div>
</div>

**Question 17**

17. Which of the following is the responsibility of the customer to ensurethe availability and backup of the EBS volumes?
*  A. Delete&nbsp;the data and create a new EBS volume.
*  B. Create&nbsp;EBS snapshots.
*  C. Attach&nbsp;new volumes to EC2 Instances.
*  D. Create&nbsp;copies of EBS Volumes.

**Answer** B

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Answer – B</strong></p>
  <p>Snapshots are&nbsp;<em>incremental</em>&nbsp;backups, which means that only the blocks on the device that have changed after your most recent snapshot are saved.&nbsp;<br> When you create an EBS volume based on a snapshot, the new volume begins as an exact replica of the original volume that was used to create the snapshot. The replicated volume loads data in the background so that you can begin using it immediately.</p>
  <p><strong>Option A is incorrect</strong> because there is no need for backup of the volumes if data is already deleted.</p>
  <p><strong>Option C is incorrect </strong>because attaching more EBS volumes doesn't ensure availability, if there is no snapshot then the volume cannot be available to a different availability zone.</p>
  <p><strong>Option D is incorrect</strong> EBS volumes cannot be copied, they can only be replicated using snapshots.</p>
  <p>For more information on EBS Snapshots, please refer to the below URL:</p>
  <ul>
   <li><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSSnapshots.html" target="_blank">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSSnapshots.html</a></li>
  </ul>
 </div>
</div>

**Question 18**

18. When designing a highly available architecture, what is the difference between vertical scaling (scaling-up) and horizontal scaling (scaling-out)?
*  A. Scaling up provides for high availability whilst scaling out brings fault-tolerance.
*  B. Scaling out is not cost-effective compared to scaling up.
*  C. Scaling up adds more resources to an instance, scaling out adds more instances.
*  D. Autoscaling groups require scaling up whilst launch configurations use scaling out.

**Answer** C

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Correct Answer – C</p>
  <p>In high availability architectures, Autoscaling is used to give elasticity to the design. Horizontal scaling (scaling-out) uses Autoscaling groups to increase processing capacity in response to changes in preset threshold parameters. It could involve adding more EC2 instances of a web server. Vertical scaling (scaling-up), which can create a single point of failure, involves adding more resources to a particular instance to meet demand.</p>
  <ul>
   <li><a href="https://docs.aws.amazon.com/autoscaling/plans/userguide/what-is-aws-auto-scaling.html" target="_blank">https://docs.aws.amazon.com/autoscaling/plans/userguide/what-is-aws-auto-scaling.html</a></li>
   <li><strong>Option A&nbsp;is INCORRECT.</strong>&nbsp;Scaling-up does not provide high availability.&nbsp;Adding more resources to one instance is often not a best-practice in architecture design.</li>
   <li><strong>Option B&nbsp;is INCORRECT.</strong>&nbsp;Scaling-out is cost-effective since it involves adding more resources in response to demand and reducing resources (scaling down) when demand is low.</li>
   <li><strong>Option D&nbsp;is INCORRECT.</strong>&nbsp;All Autoscaling groups require a launch configuration based on what resources would be provisioned or deprovisioned to meet predefined parameters.</li>
  </ul>
 </div>
</div>

**Question 19**

19. Your company is planning to move to the AWS Cloud. You need to give a presentation on the cost perspective when moving existing resources to the AWS Cloud. ConsideringAmazon EC2, which of the following is an advantage from the cost perspective?
*  A. Having the ability of automated backups of the EC2 instance, so that you don’t need to worry about the maintenance costs.
*  B. The ability to choose low cost AMI’s to prepare the EC2 Instances.
*  C. The ability to only pay for what you use.
*  D. Ability to tag instances to reduce the overall cost.

**Answer** C

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer - C</p>
  <p>One of the advantages of EC2 Instances is the per-second billing concept. This is also given in the AWS documentation.</p>
  <p>With per-second billing, you pay for only what you use. It takes the cost of unused minutes and seconds in an hour off of the bill.&nbsp;So, you can focus on improving your applications instead of maximizing usage to the hour especially if you manage instances running for irregular periods of time, such as dev/testing, data processing, analytics, batch processing and gaming applications.</p>
  <p>For more information on EC2 Pricing, please refer to the below URL:</p>
  <ul>
   <li><a href="https://aws.amazon.com/ec2/pricing/" target="_blank">https://aws.amazon.com/ec2/pricing/</a></li>
  </ul>
  <p>&nbsp;</p>
 </div>
</div>

**Question 20**

20. When designing a system, you use the principle of “design for failure and nothing will fail”. Which of the following services/features of AWS can assist in supporting this design principle?Choose 3 answers from the options given below.
*  A. Availability Zones
*  B. Regions
*  C. Elastic Load Balancer
*  D. Pay as you go

**Answer** A, B, C

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer – A, B and C</p>
  <p>Each AZ is a set of one or more data centers. By deploying your AWS resources to multiple Availability zones, you are designing with failure in mind. So if one AZ were to go down, the other AZ’s would still be up and running. Hence your application would be more fault-tolerant.</p>
  <p>For disaster recovery scenarios, one can move or make resources run in other regions.</p>
  <p>And finally, one can use the Elastic Load Balancer to distribute load to multiple backend instances within a particular region.</p>
  <p>For more information on AWS Regions and AZ’s, please refer to the below URL:</p>
  <ul>
   <li><a href="http://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Concepts.RegionsAndAvailabilityZones.html" target="_blank">http://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Concepts.RegionsAndAvailabilityZones.html</a></li>
  </ul>
  <p>&nbsp;</p>
 </div>
</div>

**Question 21**

21. Your design team is planning to design an application that will be hosted on the AWS Cloud. One of their main non-functional requirements is given below:
* Reduce inter-dependencies so failures do not impact other components.
  Which of the following concepts does this requirement relate to?<!--[if !supportLists]-->
*  A. Integration
*  B. Decoupling
*  C. Aggregation
*  D. Segregation

**Answer** B

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer – B</p>
  <p>The entire concept of decoupling components ensures that the different components of applications can be managed and maintained separately. If all components are tightly coupled, the entire application would go down when one component goes down. Hence it is always a better practice to decouple application components.</p>
  <p>For more information on a decoupled architecture, please refer to the below URL:</p>
  <ul>
   <li><a href="http://whatis.techtarget.com/definition/decoupled-architecture" target="_blank">http://whatis.techtarget.com/definition/decoupled-architecture</a></li>
  </ul>
  <p>&nbsp;</p>
 </div>
</div>

**Question 22**

22. Which of the following security requirements are managed by AWS? Select 3 answers from the options given below.
*  A. Password Policies
*  B. User permissions
*  C. Physical security
*  D. Disk disposal
*  E. Hardware patching

**Answer** C, D, E

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer – C, D and E</p>
  <p>As per the Shared Responsibility Model, the Patching of the underlying hardware and physical security of AWS resources is the responsibility of AWS.</p>
  <p>For more information on AWS Shared Responsibility Model, please refer to the below URL-</p>
  <ul>
   <li><a href="https://aws.amazon.com/compliance/shared-responsibility-model/" target="_blank">https://aws.amazon.com/compliance/shared-responsibility-model/</a></li>
  </ul>
  <p>Disk disposal-</p>
  <p>&nbsp;</p>
  <p>Storage Device Decommissioning: When a storage device has reached the end of its useful life, AWS procedures include a decommissioning process designed to prevent customer data from being exposed to unauthorized individuals. AWS uses the techniques detailed in DoD 5220.22-M (“National Industrial Security Program Operating Manual “) or NIST 800-88 (“Guidelines for Media Sanitization”) to destroy data as part of the decommissioning process. All decommissioned magnetic storage devices are degaussed and physically destroyed in accordance with industry-standard practices.</p>
  <p>&nbsp;</p>
  <p>For more information on Disk disposal, please refer to the below URL-</p>
  <p>&nbsp;</p>
  <p>&nbsp;</p>
  <ul>
   <li><a href="https://d0.awsstatic.com/whitepapers/aws-security-whitepaper.pdf" data-lf-fd-inspected-kn9eq4r6mbl4rlvp="true">https://d0.awsstatic.com/whitepapers/aws-security-whitepaper.pdf</a></li>
  </ul>
  <p>&nbsp;</p>
  <p>&nbsp;</p>
 </div>
</div>

**Question 23**

23. You are planning on deploying a video-based application onto the AWS Cloud. Users across the world will access these videos. Which of the below services can help efficiently stream the content to the users across the globe?
*  A. Amazon SES
*  B. Amazon Cloudtrail
*  C. Amazon CloudFront
*  D. Amazon S3

**Answer** C

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer – C</p>
  <p>The AWS Documentation mentions the following:</p>
  <p>Amazon CloudFront is a web service that gives businesses and web application developers an easy and cost-effective way to distribute content with low latency and high data transfer speeds. Like other AWS services, Amazon CloudFront is a self-service, pay-per-use offering, requiring no long term commitments or minimum fees. With CloudFront, your files are delivered to end-users using a global network of edge locations.</p>
  <p>For more information on CloudFront, please visit the link:</p>
  <ul>
   <li><a href="https://aws.amazon.com/cloudfront/" target="_blank">https://aws.amazon.com/cloudfront/</a></li>
  </ul>
  <p>&nbsp;</p>
 </div>
</div>

**Question 24**

24. Which of the following AWS services can be used to retrieve configuration changes made to AWS resources causing operational issues?
*  A. Amazon Inspector
*  B. AWS CloudFormation
*  C. AWS Trusted Advisor
*  D. AWS Config

**Answer** D

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer – D</strong></p>
  <p>AWS Config can be used to audit, evaluate configurations of AWS resources. If there are any operational issues, AWS config can be used to retrieve configurational changes made to AWS resources that may have caused these issues.</p>
  <ul>
   <li><strong>Option A is incorrect</strong> as Amazon Inspector can be used to analyze potential security threats for an Amazon EC2 instance against an assessment template with predefined rules. It does not provide historical data for configurational changes done to AWS resources.</li>
   <li><strong>Option B is incorrect</strong> as AWS CloudFormation provided templates to provision and&nbsp;configure resources in AWS.</li>
   <li><strong>Option C is incorrect</strong> as AWS Trusted Advisor can help optimize resources with AWS cloud with respect to cost, security, performance, fault tolerance, and&nbsp;service limits. It does not provide historical data for configurational changes done to AWS resources.</li>
  </ul>
  <p>For more information on AWS Config, refer to the following URL:</p>
  <ul>
   <li><a href="https://aws.amazon.com/config/faq/">https://docs.aws.amazon.com/config/latest/developerguide/WhatIsConfig.html</a></li>
  </ul>
 </div>
</div>

**Question 25**

25. An organization runs several EC2 instances inside a VPC using three subnets, one for Development, one for Test, and one for Production. The Security team has some concerns about the VPC configuration. It requires restricting communication across the EC2 instances using Security Groups.Which of the following options is true for Security Groups related to the scenario?
*  A. You can change a Security Group associated with an instance if the instance is in the running state.
*  B. You can change a Security Group associated with an instance if the instance is in the hibernate state.
*  C. You can change a Security Group only if there are no instances associated to it.
*  D. The only Security Group you can change is the Default Security Group.

**Answer** A

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Answer: A</strong></p>
  <ul>
   <li><strong>Option A is CORRECT</strong> because the AWS documentation mentions it in the section called&nbsp; “Changing an Instance’s Security Group” using the following sentence: “After you launch an instance into a VPC, you can change the security groups that are associated with the instance. You can change the security groups for an instance when the instance is in the running or stopped state.”</li>
   <li><strong>Option B is incorrect&nbsp;</strong>as You can change the security groups for an instance when the instance is in the running or stopped state, not hibernate state.</li>
   <li><strong>Option C is incorrect </strong>because there have to be some instances associated.</li>
   <li><strong>Option D is incorrect</strong> because other security groups can also be changed.</li>
  </ul>
  <p><strong>References:</strong></p>
  <ul>
   <li><a href="https://docs.aws.amazon.com/en_pv/vpc/latest/userguide/VPC_SecurityGroups.html" target="_blank">https://docs.aws.amazon.com/en_pv/vpc/latest/userguide/VPC_SecurityGroups.html</a></li>
  </ul>
 </div>
</div>

**Question 26**

26. Your company is planning to pay for an AWS Support plan. They have the following requirements as far as the support plan goes:
* 24x7 access to Cloud Support Engineers via email, chat &amp; phone.
* Response time of less than 15 minutes for any Mission-critical system faults.
  Which of the following plans will suffice to keep in mind the above requirement?
*  A. Basic
*  B. Developer
*  C. Business
*  D. Enterprise

**Answer** D

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Answer – D</strong><br> <br> Enterprise plan has Mission-critical faults support within 15 minutes. The question mentions less than 15 minutes for critical faults. Hence the correct answer is Enterprise.&nbsp;</p>
  <p><img alt="" src="./LMS _ Whizlabs_files/ccp-2-41.JPG" style="height:369px; width:850px"></p>
  <p>For more information on the support plans, please refer to the following link:</p>
  <ul>
   <li><a href="https://aws.amazon.com/premiumsupport/compare-plans/" target="_blank">https://aws.amazon.com/premiumsupport/compare-plans/</a></li>
  </ul>
 </div>
</div>

**Question 27**

27. Your company wants to move an existing Oracle database to the AWS Cloud. Which of the following services can help facilitate this move?
*  A. AWS Database Migration Service
*  B. AWS VM Migration Service
*  C. AWS Inspector
*  D. AWS Trusted Advisor

**Answer** A

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer - A</p>
  <p>The AWS Documentation mentions the following.</p>
  <p>AWS Database Migration Service helps you migrate databases to AWS quickly and securely. The source database remains fully operational during the migration, minimizing downtime to applications that rely on the database. The AWS Database Migration Service can migrate your data to and from the most widely used commercial and open-source databases.</p>
  <p>For more information on AWS Database migration, please refer to the below URL:</p>
  <ul>
   <li><a href="https://aws.amazon.com/dms/">https://aws.amazon.com/dms/</a></li>
  </ul>
  <p>&nbsp;</p>
 </div>
</div>

**Question 28**

28. On which of the following resources does Amazon Inspector performnetwork accessibility checks?
*  A. Amazon CloudFront
*  B. Amazon VPN
*  C. Amazon EC2 instance
*  D. Amazon VPC

**Answer** C

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer – C</strong></p>
  <p>Amazon Inspector provides two types of packages.&nbsp;Network reachability rules package checks network accessibility checks on Amazon EC2 instance. Host assessment rules package checks vulnerabilities on Amazon EC2 instance.</p>
  <ul>
   <li><strong>Options A, B &amp; D are incorrect</strong> as Amazon Inspector performs network accessibility checks on Amazon EC2 instance,&nbsp;not on Amazon CloudFront, Amazon VPN or&nbsp;Amazon VPC.</li>
  </ul>
  <p>For more information on Amazon Inspector, refer to the following URL:</p>
  <ul>
   <li><a href="https://aws.amazon.com/inspector/faqs/">https://aws.amazon.com/inspector/faqs/</a></li>
  </ul>
 </div>
</div>

**Question 29**

29. Which of the following services helps to achieve the computing elasticity in AWS?
*  A. AWS RDS
*  B. VPC Endpoint
*  C. AWS EC2 Auto Scaling Group
*  D. Amazon S3

**Answer** C

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer – C</p>
  <p>AWS EC2 Auto Scaling Group achieves the computing elasticity by scaling up/down the EC2 instances based on demand.</p>
  <p>For more information on the AWS Autoscaling service, please refer to the below URL:</p>
  <ul>
   <li><a href="https://aws.amazon.com/autoscaling/" target="_blank">https://aws.amazon.com/autoscaling/</a></li>
  </ul>
  <p>&nbsp;</p>
 </div>
</div>

**Question 30**

30. A live online game uses DynamoDB service in the backend to store real-time scores of the participants as they compete against each other from various parts of the world. Which data consistency option is the most appropriate to implement?
*  A. Strongly consistent
*  B. Eventually consistent
*  C. Strong Eventual consistency
*  D. Optimistic consistency

**Answer** A

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer – A</strong></p>
  <p>Since the gamers are from geographically distinct locations, the data will need to be immediately readable within a second as soon as it is&nbsp;written. Therefore strongly consistency is needed.</p>
  <p><a href="https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/HowItWorks.ReadConsistency.html" target="_blank">https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/HowItWorks.ReadConsistency.html</a></p>
  <p>&nbsp;</p>
  <ul>
   <li><strong>Option B&nbsp;is INCORRECT </strong>because the scenarios outline that the participants of the game are live. It will not suffice if any of them get updates on scores in less than real-time.</li>
   <li><strong>Option C&nbsp;is INCORRECT&nbsp;</strong>because&nbsp;strong eventual consistency is not applicable in DynamoDB.</li>
   <li><strong>Option D&nbsp;is INCORRECT&nbsp;</strong>because&nbsp;only two data consistency models are available with the DynamoDB service. Optimistic consistency is not supported.</li>
  </ul>
 </div>
</div>

**Question 31**

31. Which of the following services allows you to analyze EC2 Instances against pre-defined security templates to check for vulnerabilities?
*  A. AWS Trusted Advisor
*  B. AWS Inspector
*  C. AWS WAF
*  D. AWS Shield

**Answer** B

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer – B</p>
  <p>The AWS Documentation mentions the following.</p>
  <p>Amazon Inspector enables you to analyze the behavior of your AWS resources and helps you to identify potential security issues. Using Amazon Inspector, you can define a collection of AWS resources that you want to include in an assessment target. You can then create an <em>assessment template</em> and launch a security <em>assessment run</em> of this target.</p>
  <p>For more information on AWS Inspector, please refer to the below URL:</p>
  <ul>
   <li><a href="https://docs.aws.amazon.com/inspector/latest/userguide/inspector_introduction.html" target="_blank">https://docs.aws.amazon.com/inspector/latest/userguide/inspector_introduction.html</a></li>
  </ul>
  <p>&nbsp;</p>
 </div>
</div>

**Question 32**

32. You are planning to serve a web application on the AWS Platform by using EC2 Instances. Which of the below principles would you adopt to ensure that even if some of the EC2 Instances crash, you still have a working application?
*  A. Using a scalable system
*  B. Using an elastic system
*  C. Using a regional system
*  D. Using a fault tolerant system

**Answer** D

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer - D</p>
  <p>A fault-tolerant system is one that ensures that the entire system works as expected, even there are issues.</p>
  <p>For more information on designing fault-tolerant applications in AWS, please refer to the below URL:</p>
  <p><a href="https://d1.awsstatic.com/whitepapers/aws-building-fault-tolerant-applications.pdf?did=wp_card&amp;trk=wp_card" target="_blank" data-lf-fd-inspected-kn9eq4r6mbl4rlvp="true">https://d1.awsstatic.com/whitepapers/aws-building-fault-tolerant-applications.pdf?did=wp_card&amp;trk=wp_card</a></p>
  <p><a href="https://aws.amazon.com/premiumsupport/knowledge-center/autoscaling-fault-tolerance-load-balancer/" target="_blank">https://aws.amazon.com/premiumsupport/knowledge-center/autoscaling-fault-tolerance-load-balancer/</a></p>
  <p><a href="https://aws.amazon.com/whitepapers/?whitepapers-main.sort-by=item.additionalFields.sortDate&amp;whitepapers-main.sort-order=desc" target="_blank">https://aws.amazon.com/whitepapers/?whitepapers-main.sort-by=item.additionalFields.sortDate&amp;whitepapers-main.sort-order=desc</a></p>
  <p>&nbsp;</p>
 </div>
</div>

**Question 33**

33. Which of the following are best practiceswhen designing cloud-based systems?(Select TWO)
*  A. Build Tightly-coupled components.
*  B. Build loosely-coupled components.
*  C. Assume everything will fail.
*  D. Use as many services as possible.

**Answer** B, C

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Answer – B and C</strong></p>
  <p>Always build components that are loosely coupled. This is so that even if one component does fail, the entire system does not fail.</p>
  <p>If you build with the assumption that everything will fail, you will ensure that the right measures are taken to build a highly available and fault-tolerant system.</p>
  <p><strong>Option D is incorrect</strong> because using multiple services increases cost and operational burden, rather use&nbsp;less and efficient services like serverless storage services and serverless compute services.</p>
  <p>For more information on a well-architected framework, please refer to the below URL:</p>
  <ul>
   <li><a href="https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html" target="_blank">https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html</a></li>
  </ul>
 </div>
</div>

**Question 34**

34. Which services allow the customer to retain full administrative privileges of the underlying virtual infrastructure?
*  A. Amazon EC2
*  B. Amazon S3
*  C. Amazon Lambda
*  D. Amazon DynamoDB

**Answer** A

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer – A</p>
  <p>All of the other services are all managed by AWS as serverless components. Only you have complete control over the EC2 service. For more information on AWS EC2, please refer to the below URL:</p>
  <ul>
   <li><a href="https://aws.amazon.com/ec2/" target="_blank">https://aws.amazon.com/ec2/</a></li>
  </ul>
  <p>&nbsp;</p>
 </div>
</div>

**Question 35**

35. You have a mission-critical application that must be globally available at all times. If this is the case, which of the below deployment mechanisms would you employ?
*  A. Deployment to multiple edge locations
*  B. Deployment to multiple Availability Zones
*  C. Deployment to multiple Data Centers
*  D. Deployment to multiple Regions

**Answer** D

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer – D</p>
  <p>Regions represent different geographical locations and are suitable&nbsp;for hosting your application across multiple regions for disaster recovery.</p>
  <p>For more information on AWS Regions, please refer to the below URL:</p>
  <ul>
   <li><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html" target="_blank">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html</a></li>
  </ul>
  <p>&nbsp;</p>
 </div>
</div>

**Question 36**

36. Which of the following can be used to protect against DDoS attacks?Choose 2 answers from the options given below.
*  A. AWS EC2
*  B. AWS RDS
*  C. AWS Shield
*  D. AWS Shield Advanced

**Answer** C, D

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer – C and D</p>
  <p>The AWS Documentation mentions the following:</p>
  <p>AWS Shield - All AWS customers benefit from the automatic protections of AWS Shield Standard, at no additional charge. AWS Shield Standard defends against most common, frequently occurring network and transport layer DDoS attacks that target your web site or applications</p>
  <p>AWS Shield Advanced - For higher levels of protection against attacks targeting your web applications running on Amazon EC2, Elastic Load Balancing (ELB), CloudFront, and Route&nbsp;53 resources, you can subscribe to AWS Shield Advanced. AWS Shield Advanced provides expanded DDoS attack protection for these resources.</p>
  <p>For more information on AWS Shield, please refer to the below URL:</p>
  <ul>
   <li><a href="https://docs.aws.amazon.com/waf/latest/developerguide/ddos-overview.html" target="_blank">https://docs.aws.amazon.com/waf/latest/developerguide/ddos-overview.html</a></li>
  </ul>
  <p>&nbsp;</p>
 </div>
</div>

**Question 37**

37. Which of the following is a serverless compute offering from AWS?
*  A. AWS EC2
*  B. AWS Lambda
*  C. AWS SNS
*  D. AWS SQS

**Answer** B

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer – B</p>
  <p>The AWS Documentation mentions the following:</p>
  <p>AWS Lambda is a compute service that lets you run code without provisioning or managing servers. AWS Lambda executes your code only when needed and scales automatically, from a few requests per day to thousands per second.</p>
  <p>For more information on AWS Lambda, please refer to the below URL:</p>
  <ul>
   <li><a href="https://docs.aws.amazon.com/lambda/latest/dg/welcome.html" target="_blank">https://docs.aws.amazon.com/lambda/latest/dg/welcome.html</a></li>
  </ul>
  <p>&nbsp;</p>
 </div>
</div>

**Question 38**

38. Which of the following security services can be used to detect users' personal credit card numbers from data stored in Amazon S3?
*  A. Amazon Macie
*  B. Amazon GuardDuty
*  C. Amazon Inspector
*  D. AWS Shield

**Answer** A

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer – A</strong></p>
  <p>Explanation:&nbsp;Amazon Macie is a managed security service which can be used to detect personally identifiable information (PII) such as names, password, Credit card numbers from large amounts of data stored in Amazon S3 bucket.</p>
  <ul>
   <li><strong>Option B is incorrect</strong> as Amazon GuardDuty is used to identify threats by analyzing events from AWS CloudTrail, VPC Flow Logs, and DNS Logs. It cannot be used to detect PII from data stored in the Amazon S3 bucket.</li>
   <li><strong>Option C is incorrect</strong> as Amazon Inspector can analyze potential security threats for an Amazon EC2 instance against an assessment template with predefined rules.</li>
   <li><strong>Option D is incorrect </strong>as AWS Shield provides protection against DDOS attacks.</li>
  </ul>
  <p>For more information on Amazon Macie, refer to the following URLs:</p>
  <ul>
   <li><a href="https://aws.amazon.com/macie/features/">https://aws.amazon.com/macie/features/</a></li>
  </ul>
 </div>
</div>

**Question 39**

39. An online streaming company is prohibited from broadcasting its content in certain countries and regions in the world. Which Amazon Route 53 routing policy would be the most suitable in guaranteeing their compliance?
*  A. Geoproximity
*  B. Geolocation
*  C. Multi-value answer
*  D. Failover

**Answer** B

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer – B</strong></p>
  <p>Amazon Route 53 geolocation routing policy makes it possible for different types of content to be served depending on the browser's geographical location. In this use case, the streaming company can serve a restriction message if Amazon Route 53 detects origin requests from prohibited countries.</p>
  <p><a href="https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html#routing-policy-geo" target="_blank">https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html#routing-policy-geo</a></p>
  <ul>
   <li><strong>Option A&nbsp;is INCORRECT</strong> because geo-proximity allows for DNS traffic to be routed in accordance with a bias or preset preference rule. This allows the user to be served with content from resources closest to their geographical location. This routing manipulates DNS traffic flow only. This routing policy is not the most suitable. 
    <ul style="list-style-type:circle">
     <li><a href="https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html#routing-policy-geoproximity" target="_blank">https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html#routing-policy-geoproximity</a></li>
    </ul></li>
   <li><strong>Option C&nbsp;is INCORRECT</strong> because a multi-value answer primarily addresses the quality of service and resources queried in DNS requests. This routing policy is not the most suitable. 
    <ul style="list-style-type:circle">
     <li><a href="https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html#routing-policy-multivalue" target="_blank">https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html#routing-policy-multivalue</a></li>
    </ul></li>
   <li><strong>Option D&nbsp;is INCORRECT</strong> because failover allows for the automatic switch to healthy DNS resources if another becomes unavailable. It will not allow for the preferential serving of content based on the geographical location. This routing policy is not the most suitable. 
    <ul>
     <li><a href="https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html#routing-policy-multivalue" target="_blank">https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html#routing-policy-multivalue</a></li>
    </ul></li>
  </ul>
 </div>
</div>

**Question 40**

40. Which AWS service provides a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability?
*  A. AWS RDS
*  B. DynamoDB
*  C. Oracle RDS
*  D. Elastic Map Reduce

**Answer** B

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer: - B</p>
  <p>DynamoDB is a fully managed NoSQL offering provided by AWS. It is now available in most regions for users to consume.</p>
  <p>For more information on AWS DynamoDB, please refer to the below URL:</p>
  <ul>
   <li><a href="http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html" target="_blank">http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html</a></li>
  </ul>
  <p>&nbsp;</p>
 </div>
</div>

**Question 41**

41. In the AWS Billing and Management service, which tool can provide usage-based forecasts of estimated billing costs and usage for the coming months?
*  A. AWS Cost Explorer
*  B. AWS Bills
*  C. AWS Reports
*  D. Cost &amp; Usage Reports

**Answer** A

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer – A</strong></p>
  <p>AWS Cost Explorer can create user-defined&nbsp;custom forecasts for future usage patterns.</p>
  <p><a href="https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/ce-forecast.html" target="_blank">https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/ce-forecast.html</a></p>
  <p><a href="https://aws.amazon.com/about-aws/whats-new/2019/07/usage-based-forecasting-in-aws-cost-explorer/" target="_blank">https://aws.amazon.com/about-aws/whats-new/2019/07/usage-based-forecasting-in-aws-cost-explorer/</a></p>
  <ul>
   <li><strong>Option B&nbsp;is INCORRECT</strong> because AWS Bills will list the historical costs that would have been incurred over the past month with granular options. The tool will not give the usage-based forecasts as specified in the question.</li>
   <li><strong>Option C&nbsp;is INCORRECT</strong> because AWS Reports will give a composite overview of costs and usage. The tool gives a granular perspective of usage and billing but without usage-based forecasts.</li>
   <li><strong>Option D&nbsp;is INCORRECT</strong> because AWS Reports and Cost &amp; Usage Reports are the same tool. Option C. explanation outlines why it is inaccurate as a response to the question.</li>
  </ul>
 </div>
</div>

**Question 42**

42. Which of the following AWS managed database service provides processing power that is up to 5X faster than a traditional MySQL database?
*  A. MariaDB
*  B. Aurora
*  C. PostgreSQL
*  D. DynamoDB

**Answer** B

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer – B</p>
  <p>The AWS Documentation mentions the following:</p>
  <p>Amazon Aurora (Aurora) is a fully managed, MySQL- and PostgreSQL-compatible, relational database engine. It combines the speed and reliability of high-end commercial databases with the simplicity and cost-effectiveness of open-source databases. It delivers up to five times the throughput of MySQL and up to three times the throughput of PostgreSQL without requiring changes to most of your existing applications.</p>
  <p>For more information on AWS Aurora, please refer to the below URL:</p>
  <ul>
   <li><a href="https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Aurora.Overview.html" target="_blank">https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Aurora.Overview.html</a></li>
  </ul>
  <p>&nbsp;</p>
 </div>
</div>

**Question 43**

43. In the AWS Well-Architected Framework, which of the following is NOT a Security design principle to design solutions in AWS?
*  A. Apply Security only at the edge of the network.
*  B. Protect Data at rest &amp; in transit.
*  C. Implement a strong Identity foundation.
*  D. Enable Traceability.

**Answer** A

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer: A</strong></p>
  <p>Security needs to be applied at all network layers, like edge of network, VPC, all instances &amp; application with the VPC. Applying Security controls at the edge of the network is not an efficient security control &amp; against security design principles.</p>
  <p>As per AWS Well-Architected Framework, the following are the design principles for security in the cloud:</p>
  <p>·&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Implement a strong identity foundation.</p>
  <p>·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Enable traceability.</p>
  <p>·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Apply security at all layers.</p>
  <p>·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Automate security best practices.</p>
  <p>·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Protect data in transit and at rest.</p>
  <p>·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Keep people away from data.</p>
  <p>·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Prepare for security events.</p>
  <ul>
   <li><strong>Options B, C, &amp; D are incorrect</strong> as these are part of security design principles that need to be followed while implementing security controls in the cloud.</li>
  </ul>
  <p>For more information on Security Design Principle with AWS Well-Architected Framework, refer to the following URL:</p>
  <ul>
   <li><a href="https://docs.aws.amazon.com/wellarchitected/latest/framework/sec-design.html">https://docs.aws.amazon.com/wellarchitected/latest/framework/sec-design.html</a></li>
  </ul>
 </div>
</div>

**Question 44**

44. Which of the following options is TRUE for AWS Database Migration Service (AWS DMS)?
*  A. AWS DMS can migrate databases from on-premise to AWS.
*  B. AWS DMS can migrate databases from AWS to on-premise.
*  C. AWS DMS can migrate databases from EC2 to Amazon RDS.
*  D. AWS DMS can have Amazon Redshift and Amazon DynamoDB as target databases.
*  E. All the above

**Answer** E

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Answer: E</strong></p>
  <p>All the options are CORRECT.</p>
  <p>Options are clearly described in the AWS DMS documentation at the link below.</p>
  <ul>
   <li><strong>Option A is TRUE</strong> and is the “most common” way to use AWS DMS.</li>
   <li><strong>Option B is TRUE</strong> and can be used to create a copy (or migrate) a database from AWS to the on-premise data center.</li>
   <li><strong>Option C is TRUE</strong> and can be used to migrate the IaaS solution (e.g., generated from a lift-and-shift wave) to a managed service like Amazon RDS.</li>
   <li><strong>Option D is TRUE,</strong> according to AWS documentation.</li>
  </ul>
  <p><strong>Diagram: </strong>none</p>
  <p><strong>References:</strong></p>
  <ul>
   <li><a href="https://aws.amazon.com/dms/" target="_blank">https://aws.amazon.com/dms/</a></li>
   <li><a href="https://aws.amazon.com/dms/faqs/" target="_blank">https://aws.amazon.com/dms/faqs/</a></li>
  </ul>
 </div>
</div>

**Question 45**

45. Which of the following services helps in governance, compliance, and risk auditing in AWS?
*  A. AWS CloudFormation
*  B. AWS CloudTrail
*  C. AWS CloudWatch
*  D. AWS SNS

**Answer** B

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer - B</p>
  <p>The AWS Documentation mentions the following:</p>
  <p>AWS CloudTrail is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account. With CloudTrail, you can log, continuously monitor, and retain account activity related to actions across your AWS infrastructure. CloudTrail provides event history of your AWS account activity, including actions taken through the AWS Management Console, AWS SDKs, command line tools, and other AWS services. This event history simplifies security analysis, resource change tracking, and troubleshooting.</p>
  <p>For more information on AWS CloudTrail, please refer to the below URL:</p>
  <ul>
   <li><a href="https://aws.amazon.com/cloudtrail/" target="_blank">https://aws.amazon.com/cloudtrail/</a></li>
  </ul>
  <p>&nbsp;</p>
 </div>
</div>

**Question 46**

46. Project team enhancing the security features of a banking application, requires implementing a threat detection service that continuously monitors malicious activitiesand unauthorized behaviors to protect AWS accounts, workloads, and data stored in Amazon S3. Which AWS services should the project team select?
*  A. AWS Shield
*  B. AWS Firewall Manager
*  C. Amazon GuardDuty
*  D. Amazon Inspector

**Answer** C

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Answer: C</strong></p>
  <ul>
   <li><strong>Option A is INCORRECT</strong>. AWS Shield is a managed Distributed Denial of Service (DDoS) protection service that safeguards applications running on AWS.</li>
   <li><strong>Option B is INCORRECT</strong>. AWS Firewall Manager is a security management service that allows you to centrally configure and manage firewall rules across your accounts and applications in AWS Organization.</li>
   <li><strong>Option C is CORRECT</strong>. Amazon GuardDuty is a threat detection service that continuously monitors malicious activities&nbsp;and unauthorized behaviors to protect your AWS accounts, workloads, and data stored in Amazon S3.</li>
   <li><strong>Option D is INCORRECT</strong>. Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS.</li>
  </ul>
  <p>&nbsp;<strong>Reference:</strong><a href="https://aws.amazon.com/guardduty/"><strong> </strong></a></p>
  <ul>
   <li><a href="https://aws.amazon.com/guardduty/" target="_blank">https://aws.amazon.com/guardduty/</a></li>
   <li><a href="https://aws.amazon.com/firewall-manager/" target="_blank">https://aws.amazon.com/firewall-manager/</a></li>
   <li><a href="https://aws.amazon.com/shield/" target="_blank">https://aws.amazon.com/shield/</a></li>
   <li><a href="https://aws.amazon.com/inspector/" target="_blank">https://aws.amazon.com/inspector/</a></li>
  </ul>
 </div>
</div>

**Question 47**

47. Which of the following are benefits of the AWS's Relational Database Service (RDS)? Choose the 2 correct answers from the options below.
*  A. Automated patches and backups
*  B. DB owner can resize the capacity accordingly
*  C. It allows you to store unstructured data
*  D. It allows you to store NoSQL data

**Answer** A, B

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer - A and B</p>
  <p>The AWS Documentation mentions the following:</p>
  <p>Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a&nbsp;<a href="https://aws.amazon.com/relational-database/" target="_blank">relational database</a>&nbsp;in the cloud. It provides cost-efficient and resizable capacity while automating time-consuming administration tasks such as hardware provisioning, database setup, patching and backups. It frees you to focus on your applications. So you can give them the fast performance, high availability, security and compatibility they need.</p>
  <p>For more information on AWS RDS, please visit the URL:</p>
  <ul>
   <li><a href="https://aws.amazon.com/rds/" target="_blank">https://aws.amazon.com/rds/</a></li>
  </ul>
 </div>
</div>

**Question 48**

48. Which AWS product provides a unified user interface, enabling easy management of software development activities in one place, along with, quick development, build, and deployment of applications on AWS?
*  A. Amazon CodeGuru.
*  B. AWS CodeBuild
*  C. AWS CodeArtifact
*  D. AWS CodeStar

**Answer** D

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Answer: D</strong></p>
  <ul>
   <li><strong>Option A is INCORRECT</strong>. Amazon CodeGuru is a developer tool powered by machine learning that provides intelligent recommendations for improving code quality and identifying an application’s most expensive lines of code.</li>
   <li><strong>Option B is INCORRECT</strong>. AWS CodeBuild is a fully managed continuous integration service that compiles source code, runs tests, and produces software packages that are ready to deploy.</li>
   <li><strong>Option C is INCORRECT</strong>. AWS CodeArtifact is a fully managed artifact repository service that makes it easy for organizations of any size to securely store, publish, and share software packages used in their software development process.</li>
   <li><strong>Option D is CORRECT</strong>. AWS CodeStar enables you to develop, build, and deploy applications on AWS quickly. AWS CodeStar provides a unified user interface, enabling you to manage your software development activities in one place easily.</li>
  </ul>
  <p><strong>Reference:</strong><a href="https://aws.amazon.com/codeguru/"><strong> </strong></a></p>
  <ul>
   <li><a href="https://aws.amazon.com/codeguru/" target="_blank">https://aws.amazon.com/codeguru/</a></li>
   <li>https://aws.amazon.com/codeartifact/</li>
   <li><a href="https://aws.amazon.com/codebuild/">https://aws.amazon.com/codebuild/</a></li>
   <li><a href="https://aws.amazon.com/codestar/?c=10&amp;pt=8" target="_blank">https://aws.amazon.com/codestar/</a></li>
  </ul>
 </div>
</div>

**Question 49**

49. If you wantto take a backup of an EBS Volume, what would you do?
*  A. Store the EBS volume in S3.
*  B. Store the EBS volume in an RDS database.
*  C. Create an EBS snapshot.
*  D. Store the EBS volume in DynamoDB.

**Answer** C

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer - C</p>
  <p>The AWS Documentation mentions the following:</p>
  <p>You can back up the data on your Amazon EBS volumes to Amazon S3 by taking point-in-time snapshots.</p>
  <p>For more information on EBS Snapshots, please visit the link:</p>
  <ul>
   <li><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSSnapshots.html" target="_blank">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSSnapshots.html</a></li>
  </ul>
  <p>&nbsp;</p>
 </div>
</div>

**Question 50**

50. Your Security Team has some security concerns about the application data stored on S3.The teamrequires you to introduce two improvements: (i) add “encryption at rest” and (ii) give them the possibility to monitor who has accessed the data and when the data have been accessed.Which of the followingAWS solution would you adopt to satisfy the requirement?
*  A. AWS Certificate Manager&nbsp;with CloudTrail.
*  B. Server-Side Encryption managed by S3 (SSE-S3)&nbsp;with CloudTrail.
*  C. Server-Side Encryption managed by customer (SSE-C)&nbsp;with CloudTrail.
*  D. Server-Side Encryption managed by KMS (SSE-KMS) with CloudTrail.

**Answer** D

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Answer: D</strong></p>
  <p>Amazon S3 is integrated with AWS CloudTrail, a service that provides a record of actions taken by a user, role, or an AWS service in Amazon S3.&nbsp;</p>
  <p>CloudTrail logs successful operations and attempted calls that failed, such as when the caller is denied access to a resource. Operations on&nbsp;KMS keys in other accounts&nbsp;are logged in both the caller account and the KMS key owner account.</p>
  <ul>
   <li><strong>Option A is INCORRECT</strong> AWS Certificate Manager is not a solution for encryption at rest. It is a service that lets you easily provision, manage, and deploy public and private Secure Sockets Layer/Transport Layer Security (SSL/TLS) certificates.&nbsp;Hence it is a solution for “encryption in transit”, not an “encryption at rest.”</li>
   <li><strong>Option B is INCORRECT</strong> because SSE-S3 does “encryption/decryption at rest”, but it does not offer monitoring capabilities (who/when encrypts/decrypts).</li>
   <li><strong>Option C is INCORRECT</strong> because SSE-C does “encryption/decryption at rest”, but it does not offer monitoring capabilities (who/when encrypts/decrypts).</li>
   <li><strong>Option D is CORRECT</strong> because SSE-KMS does “encryption/decryption at rest” and does offer monitoring capabilities.&nbsp;CloudTrail captures all API calls to AWS KMS as events, including calls from the AWS KMS console, AWS KMS APIs, the AWS Command Line Interface (AWS CLI), and AWS Tools for PowerShell.</li>
  </ul>
  <p><strong>References:</strong></p>
  <ul>
   <li><a href="https://docs.aws.amazon.com/kms/latest/developerguide/services-s3.html#sse">https://docs.aws.amazon.com/kms/latest/developerguide/services-s3.html#sse</a></li>
   <li><a href="https://docs.aws.amazon.com/kms/latest/developerguide/logging-using-cloudtrail.html">https://docs.aws.amazon.com/kms/latest/developerguide/logging-using-cloudtrail.html</a></li>
  </ul>
 </div>
</div>

**Question 51**

51. Which of the following statements regarding Amazon Athena are accurate? (Select TWO)
*  A. Amazon Athena queries data directly from Amazon S3.
*  B. Amazon Athena is not suitable for complex analysis such as large joins, window functions and arrays.
*  C. Amazon Athena resources are allocated in accordance to processing and memory requirements prior to deployment.
*  D. Amazon Athena is compatible with data formats such as CSV, JSON, ORC, AVRO and Parquet
*  E. Amazon Athena uses a variety of query languages including SQL, LDAP, JPQL as well as CQL.

**Answer** A, D

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer – A, D</strong></p>
  <p>Amazon Athena a serverless query service that does not need to build databases on dedicated Elastic Block Store (EBS) volumes. Instead, it builds tables from data read directly from Amazon S3 buckets. Amazon Athena does not store any of the data. The service is compatible with the regular data formats that include CSV, JSON, ORC, AVRO and Parquet.</p>
  <p><a href="https://docs.aws.amazon.com/athena/latest/ug/what-is.html" target="_blank">https://docs.aws.amazon.com/athena/latest/ug/what-is.html</a></p>
  <p><strong>Option B&nbsp;is incorrect</strong> because Amazon Athena can query Big Data, complex analysis such as large joins, window functions and arrays.</p>
  <p><strong>Option C&nbsp;is incorrect</strong> because Amazon Athena is serverless. Thus the service scales following the resource demands. No prior resource planning is necessary.</p>
  <p><strong>Option E&nbsp;is incorrect</strong> because Amazon Athena uses SQL only.</p>
 </div>
</div>

**Question 52**

52. An administrator is running a large deployment of AWS resources that are spread across several AWS Regions. They would like to keep track of configuration changes on all the resources and maintain a configuration inventory. What is the best service they can use?
*  A. AWS CloudFormation
*  B. Stacks and Templates
*  C. AWS Backup
*  D. AWS Config

**Answer** D

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer – D</strong></p>
  <p>AWS Config will meet the scenario&nbsp;requirements.&nbsp;The service allows the administrator to monitor and record configuration changes on AWS resources in their account. The service also allows the administrator to create a resource configuration inventory.</p>
  <p><a href="https://aws.amazon.com/config/" target="_blank">https://aws.amazon.com/config/</a></p>
  <ul>
   <li><strong>Option A&nbsp;is incorrect</strong> because AWS CloudFormation will allow the administrator to create templates of resources such as EC2 instances and RDS instances but not the actual configurations in these resources.</li>
   <li><strong>Option B&nbsp;is incorrect</strong> because Templates and Stacks form the basis of AWS CloudFormation.&nbsp;They aid in the automated deployment of whole environments but not the applications that run in them.</li>
   <li><strong>Option C&nbsp;is incorrect</strong> because AWS Backup is a fully managed service that allows the administrator to back up data in the cloud and on-premises. The service is not the most appropriate to monitor and record resource configuration changes.</li>
  </ul>
 </div>
</div>

**Question 53**

53. A company does not want to manage their database. Which of the following services is a fully managed NoSQL database provided by AWS?
*  A. AWS RDS
*  B. DynamoDB
*  C. Oracle RDS
*  D. Elastic Map Reduce

**Answer** B

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>Answer - B</p>
  <p>DynamoDB is a fully managed NoSQL offering provided by AWS. It is now available in most regions for users to consume.</p>
  <p>For more information on AWS DynamoDB, visit the below link:</p>
  <ul>
   <li><a href="https://aws.amazon.com/dynamodb/" target="_blank">https://aws.amazon.com/dynamodb/</a></li>
  </ul>
  <p>&nbsp;</p>
 </div>
</div>

**Question 54**

54. Whilst working on a collaborative project, an administrator would like to record the initial configuration and several authorized changes that engineers make to the route table of a VPC. What is the best method to achieve this?
*  A. Use of AWS Config
*  B. Use of VPC Flow Logs
*  C. Use of AWS CloudTrail
*  D. Use of an AWS Lambda function that is triggered to save a log file to an S3 bucket each time configuration changes are made.

**Answer** A

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer – A</strong></p>
  <p>AWS Config can be used to keep track of configuration changes on AWS resources, keeping multiple date-stamped versions in a reviewable history. This makes it the best method to meet the scenario requirements.</p>
  <p><a href="https://aws.amazon.com/config/" target="_blank">https://aws.amazon.com/config/</a></p>
  <ul>
   <li><strong>Option B&nbsp;is incorrect</strong> because VPC flow logs will only capture IP traffic-related information passing through and from network interfaces within the VPC. VPC flow logs will not be able to capture configuration changes made to route tables. 
    <ul style="list-style-type:circle">
     <li><a href="https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html" target="_blank">https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html</a></li>
    </ul></li>
   <li><strong>Option C&nbsp;is incorrect</strong> because AWS CloudTrail will capture identity access activity, event history into the AWS environment. Recording the actions and API calls are not best suited to keep a record of configurations. 
    <ul style="list-style-type:circle">
     <li><a href="https://aws.amazon.com/cloudtrail/" target="_blank">https://aws.amazon.com/cloudtrail/</a></li>
    </ul></li>
   <li><strong>Option D&nbsp;is incorrect</strong> because using a Lambda function to write configuration changes might meet the requirements, but it would not be the best method. AWS Config can deliver what is needed with much less administrative input.</li>
  </ul>
 </div>
</div>

**Question 55**

55. Which of the following is a template that contains the software configuration tolaunch an ec2 instance?
*  A. EBS Volumes
*  B. AMI
*  C. EC2 Snapshot
*  D. EBS Snapshot

**Answer** B

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p>&nbsp;</p>
  <p>Answer – B</p>
  <p>The AWS Documentation mentions the following</p>
  <p>An Amazon Machine Image (AMI) provides the information required to launch an instance, which is a virtual server in the cloud. You specify an AMI when you launch an instance, and you can launch as many instances from the AMI as you need. You can also launch instances from as many different AMIs as you need.</p>
  <p>For more information on Amazon Machine Images, please refer to the following link:</p>
  <ul>
   <li><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html" target="_blank">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html</a></li>
  </ul>
  <p>&nbsp;</p>
 </div>
</div>

**Question 56**

56. Security and Compliance is ashared responsibilitybetween AWS and the customer. Which amongst the below-listed options are AWS responsibilities?(Select TWO.)
*  A. Perform all the necessary security configuration and management tasks for Amazon Elastic Compute Cloud (Amazon EC2).
*  B. Patch management of the guest OS and applications
*  C. Security of the data in the AWS cloud
*  D. Security of the AWS cloud
*  E. Patch management within the AWS infrastructure

**Answer** D, E

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Answer: D and E</strong></p>
  <ul>
   <li><strong>Option A is INCORRECT</strong> because Amazon Elastic Compute Cloud (Amazon EC2) is categorized as Infrastructure as a Service (IaaS).&nbsp;Hence this is the customer's responsibility.</li>
   <li><strong>Option B is INCORRECT</strong>&nbsp;because AWS is responsible for patching and fixing flaws within the infrastructure.&nbsp;But customers are responsible for patching their guest OS and applications.</li>
   <li><strong>Option C is INCORRECT</strong> as Security of the data in the cloud is the customer's responsibility.</li>
   <li><strong>Option D is CORRECT</strong> as security of the cloud is AWS’s responsibility.</li>
   <li><strong>Option E is CORRECT</strong>. AWS is responsible for patching and fixing flaws within the infrastructure.</li>
  </ul>
  <p><strong>Reference:</strong><a href="https://aws.amazon.com/compliance/shared-responsibility-model/"><strong> </strong></a></p>
  <ul>
   <li><a href="https://aws.amazon.com/compliance/shared-responsibility-model/" target="_blank">https://aws.amazon.com/compliance/shared-responsibility-model/</a></li>
  </ul>
 </div>
</div>

**Question 57**

57. Which of the following tools can be used to check service limits for resources launched within AWS Cloud Infrastructure?
*  A. AWS Config
*  B. AWS Trusted Advisor
*  C. Amazon CloudWatch
*  D. AWS CloudTrail

**Answer** B

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer: B</strong></p>
  <p>AWS Trusted Advisor checks for service usage for all the resources within AWS Cloud and&nbsp;provides notifications.</p>
  <ul>
   <li><strong>Option A is incorrect</strong> as AWS Config can be used to audit, evaluate configurations of AWS resources.&nbsp;But it does not check service limits for resources.</li>
   <li><strong>Option C is incorrect </strong>as Amazon CloudWatch monitors AWS resources and&nbsp;applications on these resources.&nbsp;But it does not check service limits for resources.</li>
   <li><strong>Option D is incorrect</strong> as AWS CloudTrail is a logging service, recording activity made to AWS resources.&nbsp;But it does not check service limits for resources.</li>
  </ul>
  <p>For more information on AWS Trusted Advisor, refer to the following URL:</p>
  <ul>
   <li><a href="https://aws.amazon.com/premiumsupport/technology/trusted-advisor/">https://aws.amazon.com/premiumsupport/technology/trusted-advisor/</a></li>
  </ul>
 </div>
</div>

**Question 58**

58. Which of the following accurately describes a typical use case in which the AWS CodePipeline service can be utilized?
*  A. To compose code in an integrated development environment that enables developers to run, test and debug components of a dynamic microservice.
*  B. To compile and deploy a microservice onto Amazon EC2 instances or AWS Lambda functions.
*  C. To securely share code, collaborate on source code, version control and store binaries on an AWS fully-managed platform that scales seamlessly.
*  D. To orchestrate and automate the various phases involved in the release of application updates in-line with a predefined release model.

**Answer** D

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer:&nbsp; D</strong></p>
  <p>The question is looking for a typical use case for AWS CodePipeline.&nbsp;Option D is the most appropriate because AWS CodePipeline is typically utilized when orchestrating and automating the various phases involved in the release of application updates in-line with a release model that the developer defines.</p>
  <ul>
   <li><a href="https://aws.amazon.com/codepipeline/" target="_blank">https://aws.amazon.com/codepipeline/</a></li>
   <li>Option A is<strong> INCORRECT </strong>because composing code in an integrated development environment that enables developers to run, test, and debug components of a dynamic microservice is the typical AWS Cloud9 IDE function.</li>
   <li>Option B is<strong> INCORRECT </strong>because compiling and deploying microservices on Amazon EC2 instances or AWS Lambda functions are the typical functions of AWS CodeDeploy.</li>
   <li>Option C is<strong> INCORRECT </strong>because securely sharing code, collaborating on source code, version control and storing binaries on an AWS fully-managed platform describe&nbsp;the functions of CodeCommit.</li>
  </ul>
 </div>
</div>

**Question 59**

59. Your organization has planned to decommission its data centers. You have a task to migrate hundreds of TB of archived data and 22 TB of active data to S3 and EFS, as per the designed solution. Which of the below services will be best suited for this task?
*  A. AWS Data Sync
*  B. AWS Direct Connect
*  C. AWS Data Pipeline
*  D. AWS Migration Hub

**Answer** A

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Answer: A</strong></p>
  <ul>
   <li><strong>Option A</strong> is <strong>CORRECT</strong>. AWS Data Sync is a simple and fast way to move huge amounts of data (hundreds of terabytes) between on-prem storage to S3, EFS, FSx.</li>
   <li><strong>Option B</strong> is <strong>INCORRECT</strong>. AWS Direct Connect is an offering that helps run&nbsp;workloads that are heavy on bandwidth in AWS.&nbsp;AWS Direct Connect enables private and dedicated connections between the on-premises network and AWS. AWS Data Sync could be used over the internet or Direct Connect.</li>
   <li><strong>Option C</strong> is <strong>INCORRECT</strong>. AWS Data Pipeline is a web service that facilitates data processing and movement between various AWS services (like compute and storage). Data pipeline also works well with data sources that are on-premise. In the given data migration scenario, data sync is a more apt choice.</li>
   <li><strong>Option D</strong> is <strong>INCORRECT</strong>. AWS Migration Hub is a service that facilitates discovery of the existing applications and IT assets and provides a view to better plan and track application migrations.</li>
  </ul>
  <p><strong>Reference:</strong><a href="https://aws.amazon.com/datasync"><strong> </strong></a></p>
  <ul>
   <li><a href="https://aws.amazon.com/datasync" target="_blank">https://aws.amazon.com/datasync</a>/</li>
   <li><a href="https://aws.amazon.com/directconnect/" target="_blank">https://aws.amazon.com/directconnect/</a></li>
   <li><a href="https://aws.amazon.com/datapipeline/" target="_blank">https://aws.amazon.com/datapipeline/</a></li>
   <li><a href="https://aws.amazon.com/migration-hub/" target="_blank">https://aws.amazon.com/migration-hub/</a></li>
  </ul>
 </div>
</div>

**Question 60**

60. To maximize user satisfaction, you are asked to improve the performance of the application for local and global users. As part of this initiative, you must monitor the application endpoint health and route traffic to the most appropriate application endpoint. Which service will you prefer to use?
*  A. Amazon Global Accelerator
*  B. Amazon DAX accelerator
*  C. Amazon S3 transfer acceleration
*  D. AWS Direct Connect

**Answer** A

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Answer:</strong> <strong>A</strong></p>
  <p>Global accelerator is a networking service that utilizes AWS global network to optimize the “user to application” path. The performance benefits realized by the use of the Global accelerator can be tested using a speed comparison tool provided by AWS.</p>
  <p>Global accelerator differs from S3 transfer acceleration and DynamoDB accelerator.</p>
  <p>S3 transfer acceleration accelerates the transfers of files to the S3 bucket by utilizing edge locations.</p>
  <p>A fully managed DynamoDB Accelerator (DAX) is a highly available in-memory cache for&nbsp;Dynamodb.</p>
  <ul>
   <li><strong>Option D</strong> is <strong>INCORRECT</strong>. AWS Direct Connect is an AWS offering that simplifies setting up dedicated network connectivity between AWS and on-premises infrastructure.</li>
  </ul>
  <p><strong>Reference:&nbsp; </strong></p>
  <ul>
   <li><a href="https://aws.amazon.com/global-accelerator/" target="_blank">https://aws.amazon.com/global-accelerator/</a></li>
   <li><a href="https://aws.amazon.com/dynamodb/dax/" target="_blank">https://aws.amazon.com/dynamodb/dax/</a></li>
   <li><a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/transfer-acceleration.html" target="_blank">https://docs.aws.amazon.com/AmazonS3/latest/dev/transfer-acceleration.html</a></li>
   <li><a href="https://aws.amazon.com/directconnect/" target="_blank">https://aws.amazon.com/directconnect/</a></li>
  </ul>
 </div>
</div>

**Question 61**

61. Which AWS service offering uses machine learning and graph theory capability on automatically collected log data to help youconduct faster and efficient security investigations?
*  A. Amazon Macie
*  B. Amazon Detective
*  C. AWS Artifact
*  D. Amazon GuardDuty

**Answer** B

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Answer:</strong> <strong>B</strong></p>
  <p><strong>Option A</strong> is <strong>INCORRECT</strong>. Amazon Macie is a fully managed service from AWS that provides data security and privacy by utilizing Amazon’s machine learning and pattern matching capabilities.</p>
  <p><strong>Option B</strong> is <strong>CORRECT</strong>. Amazon Detective is a security service that uses machine learning capabilities on the automatically collected log data to help customers perform efficient and fast security investigations.</p>
  <p><strong>Option C</strong> is <strong>INCORRECT</strong>. AWS Artifact is a central resource for all the information about compliance. AWS artifact provides on-demand access to compliance reports at no additional cost.</p>
  <p><strong>Option D</strong> is <strong>INCORRECT</strong>. Amazon GuardDuty performs continuous monitoring to protect AWS account, S3 data and workloads from any malicious, unauthorized activities.</p>
  <p><strong>Reference:&nbsp; </strong></p>
  <ul>
   <li><a href="https://aws.amazon.com/macie/" target="_blank">https://aws.amazon.com/macie/</a></li>
   <li><a href="https://aws.amazon.com/detective/faqs/" target="_blank">https://aws.amazon.com/detective/faqs/</a></li>
   <li><a href="https://aws.amazon.com/artifact/" target="_blank">https://aws.amazon.com/artifact/</a></li>
   <li><a href="https://aws.amazon.com/guardduty/" target="_blank">https://aws.amazon.com/guardduty/</a></li>
  </ul>
 </div>
</div>

**Question 62**

62. An administrator is tasked to configure privileges for the new joiners in the department. The admin is selectively granting privileges and ensuring that not all the team members can access all the resources.Which principle is the administrator following?
*  A. Principle of privileged users
*  B. Least privilege of group principle
*  C. Best practices of permission advisory
*  D. Principle of least privilege

**Answer** D

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Answer: D</strong></p>
  <ul>
   <li><strong>Option A</strong> is <strong>INCORRECT</strong>. This is not a valid option.</li>
   <li><strong>Option B</strong> is <strong>INCORRECT</strong>. This is not a valid option.</li>
   <li><strong>Option C</strong> is <strong>INCORRECT</strong>. This is not a valid option.</li>
   <li><strong>Option D</strong> is <strong>CORRECT</strong>. The administrator follows the “Principle of least privilege” as not all the privileges are granted to all the new joiners. The privileges are being selectively granted.</li>
  </ul>
  <p>&nbsp;<strong>Reference:</strong></p>
  <ul>
   <li><a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege" target="_blank">https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege</a></li>
  </ul>
 </div>
</div>

**Question 63**

63. You are asked to suggest an appropriate Amazon S3 storage class for “data with unknown/changing access pattern”. Which one would you suggest?
*  A. Amazon S3 Intelligent-Tiering
*  B. Amazon S3 Standard
*  C. Amazon S3 Glacier
*  D. Amazon S3 Standard-Infrequent Access

**Answer** A

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Answer:</strong> <strong>A</strong></p>
  <ul>
   <li><strong>Option A</strong> is <strong>CORRECT</strong>. Amazon S3 Intelligent-Tiering is best suited for data with “unknown/changing access pattern”.</li>
   <li><strong>Option B</strong> is <strong>INCORRECT</strong>. S3 standard is ideal for general-purpose storage of frequently accessed data.</li>
   <li><strong>Option C</strong> is <strong>INCORRECT</strong>. Amazon S3 Glacier is preferable for archival of data for a long term.</li>
   <li><strong>Option D</strong> is <strong>INCORRECT</strong>. Amazon S3 Standard-Infrequent Access is better suited for less frequently accessed, long-lived data.</li>
  </ul>
  <p><strong>Reference:</strong><a href="https://aws.amazon.com/s3/storage-classes/"> </a></p>
  <ul>
   <li><a href="https://aws.amazon.com/s3/storage-classes/" target="_blank">https://aws.amazon.com/s3/storage-classes/</a></li>
  </ul>
 </div>
</div>

**Question 64**

64. A “Member AWS account” in an AWS Organization (using consolidated billing) wants to receive a cost breakdown report (product-wise daily report) so that the analysis of cost and usage could be done.Where can this report be configured to be delivered? (Select TWO)
*  A. S3 bucket owned by the member account
*  B. S3 bucket owned by the management&nbsp;account
*  C. AWS Management Console
*  D. Amazon Athena

**Answer** A, B

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Answer:</strong>&nbsp;<strong>A&nbsp;and B</strong></p>
  <p>Member account Cost &amp; Usage reports will have the same setting options - time granularity, report output, and S3 bucket designation - as management accounts.<br> The only difference will be that management account reports will continue to include all accounts in its AWS Organization while member account reports will have only their individual account’s cost &amp; usage data.</p>
  <p><strong>Option C is incorrect. </strong>AWS Management Console is a centralized management and governance console for all the AWS products.</p>
  <p><strong>Option D is incorrect.</strong>&nbsp;Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL.</p>
  <p><strong>Reference:</strong></p>
  <ul>
   <li><a href="https://docs.aws.amazon.com/cur/latest/userguide/what-is-cur.html" target="_blank">https://docs.aws.amazon.com/cur/latest/userguide/what-is-cur.html</a></li>
   <li><a href="https://aws.amazon.com/athena/" target="_blank">https://aws.amazon.com/athena/</a></li>
   <li><a href="https://aws.amazon.com/console/" target="_blank">https://aws.amazon.com/console/</a></li>
   <li><a href="https://aws.amazon.com/about-aws/whats-new/2020/12/cost-and-usage-report-now-available-to-member-linked-accounts/">https://aws.amazon.com/about-aws/whats-new/2020/12/cost-and-usage-report-now-available-to-member-linked-accounts/</a></li>
  </ul>
 </div>
</div>

**Question 65**

65. Which AWS service allows the following requirements:1- Running Docker containers2- Simple API calls to launch and stop container-based applications
*  A. AWS Elastic Beanstalk
*  B. AWS EKS
*  C. Amazon Elastic Container Service
*  D. AWS Fargate

**Answer** C

**Explanation**
<div class="explanation-block">
 <h6>Explanation:</h6>
 <div id="explanation_block__id">
  <p><strong>Correct Answer: C</strong></p>
  <p><strong>AWS Elastic Beanstalk: </strong>It is an easy-to-use service for deploying and scaling web applications. It cannot be used to run docker containers on it.</p>
  <p><strong>AWS EKS (Elastic Kubernetes Service):</strong> AWS EKS is a managed service that simplifies Kubernetes deployment on AWS by eliminating the need to install, operate, and/or maintain its own Kubernetes control plane.</p>
  <p><strong>Amazon Elastic Container Service: </strong>AWS ECS is a container management service that facilitates containers' management on the cluster, including running and stopping the containers. The container-based applications could be launched/stopped using simple API calls.</p>
  <p><strong>AWS Fargate: </strong>AWS Fargate is an “ECS and EKS compatible” serverless compute engine for containers.</p>
  <p><strong>Reference:</strong></p>
  <ul>
   <li><a href="https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html" target="_blank">https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html</a></li>
   <li><a href="https://docs.aws.amazon.com/AmazonECS/latest/developerguide/Welcome.html" target="_blank">https://docs.aws.amazon.com/AmazonECS/latest/developerguide/Welcome.html</a></li>
   <li><a href="https://aws.amazon.com/fargate/" target="_blank">https://aws.amazon.com/fargate/</a></li>
   <li><a href="https://aws.amazon.com/elasticbeanstalk/">https://aws.amazon.com/elasticbeanstalk/</a></li>
  </ul>
 </div>
</div>
