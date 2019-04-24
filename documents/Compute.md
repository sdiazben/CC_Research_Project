# Compute


<p align="justify"> Compute refers to the capacity the providers have to offer resources and services for developers to deploy and run the applications built by them. In this case, both offer very similar services with given characteristics differentiating them. </p> 

<p align="justify"> Amazon AWS main compute services are EC2, Elastic Beanstalk and AWS Lambda. On the other hand, Microsoft Azure correspondingly provides Azure VM, App Service and Functions: </p> 

Service | AWS | Azure
--------| ----| ------
**Virtual Servers (IaaS)** | <a href= "https://aws.amazon.com/ec2/"> Elastic Compute Cloud (EC2) </a> | <a href= "https://azure.microsoft.com/en-gb/services/virtual-machines/"> Virtual Machines (VM) </a>
**Containers and orchestrators (CaaS)**|<a href= "https://aws.amazon.com/ecs/features/">EC2 Container Service (ECS)</a></br><br><a href= "https://aws.amazon.com/eks/">Elastic Container Service for Kubernetes (EKS)</a></br>|<a href="https://docs.microsoft.com/en-us/azure/container-service/">Azure Container Service</a></br><br><a href= "https://azure.microsoft.com/en-gb/services/kubernetes-service/">Azure Kubernetes Service (AKS)</a></br>
**Platforms (PaaS)**|<a href= "https://aws.amazon.com/elasticbeanstalk/">Elastic Beanstalk</a>|<a href= "https://azure.microsoft.com/en-gb/services/app-service/">App Service</a>
**Functions (FaaS)**|<a href= "https://aws.amazon.com/lambda/">AWS Lambda</a>|<a href= "https://azure.microsoft.com/en-gb/blog/introducing-azure-functions/">Azure Functions</a>
**Scalability**|<a href= "https://aws.amazon.com/autoscaling/">AWS Auto Scaling</a>|<a href= "https://azure.microsoft.com/en-gb/services/virtual-machine-scale-sets/">Virtual Machine Scale Sets</a></br><br> <a href= "https://azure.microsoft.com/en-gb/features/autoscale/">Auto Scaling</a></br><br><a href= "https://docs.microsoft.com/en-us/azure/app-service/web-sites-scale">App Service Scale Capability (PAAS)</a></br>



## EC2 (Elastic Compute Cloud) vs. VM (Virtual Machines)

<p align="justify"> These are defined as infrastructure (IaaS) services that offer resizable compute capacity in the cloud. To do so, both provide virtual machines or instances (as its referred to in AWS) that contain virtual CPU, virtual memory, temporary storage, and networking capacity and give a customer the flexibility to choose the appropriate mix of resources for workloads. These can be persisted in Block Store (EBS), a block storage volumes service,  in the case of AWS; and Blob Storage, storage for unstructured data service, in the case of Azure. Additionally, both EC2 and VM offer six types of instances with different purposes: </p> 

- General Purpose: Balanced CPU-to-memory ratio
- Compute-optimised: High CPU-to-memory ratio
- Memory-optimised: High memory-to-CPU ratio. Great for database servers
- Storage optimised: High disk throughput and IO
- GPU: Specialized for heavy graphic rendering and video editing
- High performance compute: fastest and most powerful CPU

Each has specific <a href= "https://araihan.wordpress.com/2018/08/02/amazon-ec2-and-azure-virtual-machine-instance-comparison/">references for these in both Windows and Linux OS. </a>

<p align="justify"> When talking about the differences, the first one is that AWS user can configure their own VMs, chose a pre-configured operating template called Amazon Machine Image (<a href= "https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html">AMI</a>) or even customize their own AMIs. In contrast, while Azure users choose the Virtual Hard Disk (<a href= "https://docs.microsoft.com/en-us/azure/virtual-machines/linux/managed-disks-overview">VHD</a>), equivalent to a machine instance, to create a VM; this can be can be pre-configured by Microsoft, the user or a third party. </p> 
