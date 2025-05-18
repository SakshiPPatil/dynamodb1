# dynamodb
------------------------------------------------------------------------
Amazon DynamoDB is a serverless, fully managed NoSQL database service provided by Amazon Web Services (AWS).In which we can add and reterive any amount of data.DynamoDB supports key-value and document data models.<br>
The AWS Free Tier for DynamoDB provides 25 GB of data storage. Additionally, it includes 25 provisioned Write Capacity Units (WCUs) and 25 provisioned Read Capacity Units (RCUs), which can handle up to 200 million requests per month.

Key Features: <br/>
--------------------------------------------------------------------------------------------------------------
**Serverless and Fully Managed:** <br/>
DynamoDB is managed by AWS, eliminating the need for users to manage servers, databases, or operating systems.<br/> 
<br/>
**NoSQL Database:** <br/>
It supports key-value and document data models, allowing for flexible data storage and retrieval. <br/> 
<br/>
**High Scalability and Performance:** <br/>
DynamoDB can handle massive amounts of data and high traffic levels with consistent single-digit millisecond latency.
<br/>
**Built-in Security and Availability:** <br/> 
It offers built-in features like encryption, access control, and multi-region replication for data protection and high availability.<br/>  
**Pay-as-you-go Pricing:** <br/>
You only pay for the resources you use, making it cost-effective for applications with varying workloads.<br/>  
**Global Deployment:** <br/>
DynamoDB is available in multiple AWS regions, allowing you to deploy your applications globally with low latency.<br/>  
**Various Data Models:** <br/> 
Supports key-value and document data models, allowing for flexible data storage and retrieval.<br/>  
**Global Secondary Indexes:**  
Allows for flexible queries based on attributes other than the primary key.<br/>  

-----------------------------------------------------------------------------------------------------------------------------

<h3>Key points in dynamodb:</h3>

**read capacity unit:** <br/>
DynamoDB measures read operations in RCUs, which determine the amount of data you can read per second. <br/>

**Strongly Consistent Read Cost:** <br/>
A strongly consistent read consumes one RCU per 4KB of data read per second. For example, a strongly consistent read of a 5KB item would consume 2 RCUs (one for 4KB and another for the remaining 1KB). <br/>

**Eventually Consistent Read Cost:** <br/>
1 Read Capacity Unit (RCU)=2(eventually consistent reads of up to 4 KB/s per read)
<br/>
![Screenshot 2025-05-18 162615](https://github.com/user-attachments/assets/491046f4-2bcf-4402-9a78-59876190d0a0)
<br/>

**write capacity unit:** <br/>
DynamoDB measures write operations in WCUs, which determine the amount of data you can store per second. <br/>
![Screenshot 2025-05-18 174859](https://github.com/user-attachments/assets/b68edb66-1315-4fdc-b6c3-83080a923aac)
<br/>
