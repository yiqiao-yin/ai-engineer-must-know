# Cloud Basics

## AWS

### What is AWS?
AWS (Amazon Web Services) is a comprehensive and broadly adopted cloud platform that offers over 200 fully featured services from data centers globally. It provides infrastructure as a service (IaaS), platform as a service (PaaS), and packaged software as a service (SaaS) solutions.

### Storage

#### What is S3 storage?
Amazon S3 (Simple Storage Service) is an object storage service that offers industry-leading scalability, data availability, security, and performance. This means customers of all sizes and industries can use it to store and protect any amount of data for a range of use cases, such as data lakes, websites, mobile applications, backup and restore, archive, enterprise applications, IoT devices, and big data analytics.

##### How does it work?
Amazon S3 allows people to store and retrieve any amount of data at any time from anywhere on the web. It gives any developer access to the same highly scalable, reliable, fast, inexpensive data storage infrastructure that Amazon uses to run its own global network of web sites.

##### What are some basic commands for it?
Basic commands for interacting with S3 via the AWS CLI include:
- `aws s3 cp` to copy files to and from S3.
- `aws s3 ls` to list S3 buckets and contents.
- `aws s3 mb` to create a new bucket.
- `aws s3 rm` to delete an object.

### Compute

#### What is basic compute such as running containers on EC2?
EC2 (Elastic Compute Cloud) allows users to run virtual servers and manage workloads. Running containers on EC2 involves deploying Docker containers on EC2 instances which provides scalable computing capacity in the Amazon Web Services (AWS) cloud.

#### What is ECR?
Amazon ECR (Elastic Container Registry) is a Docker container registry that makes it easy for developers to store, manage, and deploy Docker container images. It is integrated with Amazon ECS and Amazon EKS, simplifying your development to production workflow.

#### Why do people use it?
People use ECR for its scalability, reliability, and security. It allows developers to host and manage their Docker container images, perform vulnerability analysis, and simplify the deployment of containers in a highly available environment.

#### What is Docker? How to run Docker?
Docker is a platform that enables developers to package applications into containers—standardized executable components combining application source code with the operating system (OS) libraries and dependencies required to run that code in any environment. To run a Docker container, one typically uses commands like:
- `docker pull [image_name]`: to pull an image from Docker Hub.
- `docker run [options] [image_name]`: to run a container.

#### What are some famous compute services running AI and ML on AWS?
- **Amazon SageMaker:** A fully managed service that provides every developer and data scientist with the ability to build, train, and deploy machine learning models quickly.
- **Amazon Rekognition:** A service that makes it easy to add image and video analysis to your applications.
- **AWS DeepLens:** A deep learning-enabled video camera for developers.

### Network

#### What is API Call?
An API call is a request sent to a server to retrieve or modify data using an API. This can include requests to retrieve data, update data, or perform an action.

#### What is API Gateway?
AWS API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. It acts as a "front door" for applications to access data, business logic, or functionality from back-end services.

#### How to stand up API?
To set up an API in AWS API Gateway:
1. Define the API (Resources and Methods).
2. Set up authorizations as needed.
3. Deploy the API to a stage.
4. Monitor and manage the API as required.

#### What is VPC?
Amazon Virtual Private Cloud (VPC) lets you provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define. This virtual network closely resembles a traditional network that you'd operate in your own data center, with the benefits of using the scalable infrastructure of AWS.

## Azure

### What is Azure?
Azure is a cloud computing service created by Microsoft for building, testing, deploying, and managing applications and services through Microsoft-managed data centers. It provides software as a service (SaaS), platform as a service (PaaS), and infrastructure as a service (IaaS) and supports many different programming languages, tools, and frameworks, including both Microsoft-specific and third-party software and systems.

### Storage

#### What is Azure Blob Storage?
Azure Blob Storage is Microsoft's object storage solution for the cloud. Blob Storage is optimized for storing massive amounts of unstructured data, such as text or binary data.

##### How does it work?
Azure Blob Storage is designed to handle unstructured data at scale. It provides a scalable service where data is accessible via HTTP/HTTPS from anywhere in the world. Data can be managed from Azure's portal, PowerShell, Azure CLI, or an SDK of your choice.

##### What are some basic commands for it?
- `az storage blob upload`: Uploads a blob to a container.
- `az storage blob download`: Downloads a blob from a container.
- `az storage blob list`: Lists all blobs in a container.

### Compute

#### What is basic compute such as running containers on Azure VMs?
Azure Virtual Machines (VM) offer scalable computing resources. When running containers, Azure VMs serve as host machines that can run Docker, allowing containers to operate in a virtualized environment.

#### What is ACR?
Azure Container Registry (ACR) is a managed Docker registry service based on the open-source Docker Registry 2.0. ACR allows you to store and manage container images across all types of Azure deployments.

#### Why do people use it?
ACR is used for its private storage, simplified deployment, and integration into Azure's ecosystem. It supports standard Docker CLI commands and works with existing Docker tools. It's highly scalable and secure, making it ideal for managing private Docker container images.

#### What is Docker? How to run Docker on Azure?
Docker in Azure can be run by creating a container host VM or using Azure Kubernetes Service (AKS) for orchestration. To run Docker directly on a VM:
- Create a new Azure VM.
- Install Docker on the VM.
- Use Docker commands to pull, run, and manage containers.

#### What are some famous compute services running AI and ML on Azure?
- **Azure Machine Learning Service:** A cloud service that helps you manage the complete machine learning lifecycle.
- **Azure Databricks:** An Apache Spark-based analytics platform optimized for the Microsoft Azure cloud services platform.
- **Azure Cognitive Services:** A collection of APIs that allow systems to see, hear, speak, understand, and interpret human needs using natural methods of communication.

### Network

#### What is API Call?
Similar to AWS, an API call in Azure refers to sending a request to a service endpoint to perform an operation, which may involve retrieving, updating, or deleting data.

#### What is API Management?
Azure API Management is a fully managed service that enables customers to publish, secure, transform, maintain, and monitor APIs. It acts as a gateway between API consumers and back-end services, ensuring API security and scalability.

#### How to stand up API?
To set up an API in Azure API Management:
1. Import or create your API definitions.
2. Configure policies and security settings.
3. Deploy and publish the API through Azure's portal.

#### What is VNet?
Azure Virtual Network (VNet) is the fundamental building block for your private network in Azure. VNet enables many types of Azure resources, such as Azure Virtual Machines (VM), to securely communicate with each other, the internet, and on-premises networks.
