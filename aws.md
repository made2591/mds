### AWS - My notes

#### Concepts
__Region__: it is a physical location with 2 or more availability zone;
__Availability Zone__: it is a set of 1 or more discrete data centers, with redundant power, connectivity and in separated facilities;
__Edge Locations__: endpoints used to caching content;

#### Services - An overview

##### Compute
__EC2__: virtual or physical dedicated machine;
__ECS__: docker container service;
__Elastic Beanstalk__: provision machines, load balancer, etc for developer who don't want / can't deal with AWS services.
__Lambda__: function as a service, only code without any machines;
__Lightsail__: you want a server, with fixed IP address, without VPC, security group, etc;
__Batch__: batch computing, run a job;

##### Storage
__S3__: simple storage service, buckets, with file;
__EFS__: elastic file system, mountable on EC2 machine;
__Glacier__: historical archival;
__Snowball__: to transfer huge amount of data over data center;
__Storage Gateway__: virtual machine installed in your datacenter to transfer data in your VPC, four different types;

##### Databases
__RDS__: MySQL, PostgreSQL, Aurora, Oracle, Relational Databases;
__DynamoDB__: NoSQL at scale;
__Elasticache__: caching query to your database;
__Red Shift__: for data warehouse, complex query for business intelligence;

##### Migration
__AWS Migration Hub__: tracking service to track your application and some service during migration to AWS;
__Application Discovery Service__: automatic scan tools, to discover your application, what dependencies, for instance if you have a sharepoint server depending on a mysql server and / or a domain server, etc;
__Database Migration Service__: Oracle hates this. Migrate Database: Migration HUB let you visualize how your migration done with this service or Server Migration Service is going;
__Server Migration Service__: migrate physical and virtual server to the cloud;
__Snowball__: is between storage and migration;

##### Networking and Content Delivery
__VPC__: virtual private cloud, is a sort of virtual datacenter in which you can configure firewalls, AZ, network, route tables, it is complicated but powerfull;
__CloudFront__: is CDN, media access (video, images), cloud front can move your content near to the users to reduce latency;
__Route53__: is Amazon DNS service;
__API Gateway__: is a way to create APIs;
__Direct Connect__: is used to create a direct line from your office into Amazon or directly connect into your VPC;

##### Developer Tools
__CodeStar__: is a way of getting a group of developer to work toghether, managing your code, you basically setup your code etc;
__CodeCommit__: store your code, is a source control service;
__CodeBuild__: compile, run test, and produce packages ready to deploy;
__CodeDeploy__: automates application deploying in virtual instances in the cloud or even on-premise instances and lambda;
__CodePipeline__: continous delivery service to store model and visualize automatic steps to release software;
__X-Ray__: debug and analysize serverless application mainly;
__Cloud9__: IDE inside your browser, bought from an external company and integrated in AWS Cloud Services;

##### Management Tools
__CloudWatch__: important for sysops administrator exam, logs (raw) everythings;
__CloudFormation__: is a way of scripting infrastructure and deploy a website, a sharepoint server, joomla setup, and reuse the code to redeploy over;
__CloudTrail__: click in management console, trigger everything, log _changes_ for a week;
__Config__: monitors the configuration of the entire AWS environment, monitor configuration, and create snapshot of configuration;
__OpsWorks__: is similar to Elastic Beanstalk but does a lot more, chef and puppet to automate environment, covered in depth in sysops;
__Service Catalog__: manage catalog of service allowed by your company / for compliance / any other reason and keep track of what you can do in term of services approved, etc;
__Systems Manager__: is an interface to managing resources, group resources in department, etc;
__Trusted Advisor__: advise on security, if your not using service as much as you can, save money, etc;
__Managed Services__: if you don't want to care about ec2, load balancer;

##### Media Services
__Elastic Transcoder__: takes the video, resize to look on android, iphone, ipad, etc;
__Media Convert__: is a file based video transconding service to create video to be broadcasted;
__Media Live__: create HQ video streams to broadcast;
__Media Package__: prepare and protects video before going to Internet;
__Media Store__: optimize video to deliver on demand;
__Media Tailor__: allow advertising in video streams without losing quality;

##### Machine Learning
__SageMaker__: help developer to use deep learning;
__Comprehend__: does sentiment analysis on data;
__DeepLens__: is an artificial camera than can figure out what is looking out;
__Lex__: create bot with intent and actions to comunicate with customers;
__Machine Learning__: throught dataset to get statistics and result;
__Polly__: takes text and turn into speech;
__Rekognition__: is does image and video recognition;
__Amazon Translate__: translation service;
__Amazon Transcribe__: automatic speech recognition to text;

##### Analytics
__Athena__: run SQL query in your S3 buckets, you have Excel or CSV, spreadsheets, you want to find out information, you can create model to query your file;
__EMR__: Elastic map reduce used to process huge amount of data;
__CloudSearch__: search service;
__ElasticSearch Service__: search service;
__Kinesis__: is a way of ingesting large amount of data in AWS, such as social media feed or tweets, media in social, hashtag for your company; 
__Kinesis Video Streams__: people streaming video to ingest video from devices, etc;
__QuickSight__: is a business intelligent tool;
__Data Pipeline__: to move your data from your env to AWS;
__Glue__: is used to do what you can do with an ETL, so ingest data but first transform;
























