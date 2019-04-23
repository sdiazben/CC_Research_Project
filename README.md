# Amazon AWS vs Microsoft Azure
By: Buse Özer and Sara Díaz 

<p align="center"><img src="./images/awsVsAzure.jpg"/></p>

<p align="justify">
 Nowadays the need of online resources in the cloud has become crucial for companies throughout different industries. These offer the advantage of being scalable and dynamical to arising and on-demand needs without having huge impact on the cost. Although many platforms have risen to offer these services, Microsoft Azure and Amazon AWS are among the main key players. But what differentiates them? Is one better than the other? When should a company use one or the other? This research project looks to answer this questions by first understanding each of them and then comparing their main features.
</p>



## Microsoft Azure

<p align="justify"> Azure is a private and public cloud platform that offers a set of services all developed by Microsoft Inc. since 2010. This services help IT specialist to build, deploy and manage applications.
</p>

### Services

Its most popular services include: 

<p align="center"><img src="./images/azureproducts.png"/></p>
 
<p align="justify"> By 2019, Azure counts with 54 regions to host its operations, more than any other cloud provider. Database products like SQL Azure DB are present in 46 of this locations (85% of the total). This gives clients the opportunity to choose a desired location according to their needs of response and latency times, as well as IT knowledge in the region, risk of natural disaster occurrence, etc. </p> 
 
<p align="center"><img src="https://azurecomcdn.azureedge.net/cvt-a27fc75dcc932103683fbfcee92c51b694a67773a46466966b5fee3e80c103ce/images/shared/regions-map-large.svg"/></p>

In general it divides its services in into two main groups - infrastructure and Platform Services: 

<p align="center"><img src="./images/ServicesSchema.png"/></p>

The platform services are also supported by Security and Management services as well as a they can be deployed on hybrid cloud services (public and private clouds).

### Architecture

<p align="justify"> Azure uses a technology called Virtualization which separates the coupling between a computer’s hardware and operating system by using a layer named a Hypervisor, which emulates a computer’s functions and CPU within virtual machines. These virtual machines can run both Windows and Linux operating systems and optimize the abstracted hardware. </p>

<p align="center"><img src="./images/awsArch.png"/>
To better understand these concept, Azure provides the following <a href="https://www.microsoft.com/en-us/videoplayer/embed/RE2ixGo">video</a></p>

<p align="justify"> Each of its data centers distributed around the world contains many racks which containing servers and each of this implements this Hypervisor technology to run multiple virtual machines. A network switch provides connectivity between the servers.  create it within the servers. After this the user can access it and all its functions. Each server within the rack runs a special piece of software called the Fabric Controller, which, at the same time, is connected to another software called the Orchestrator which manages every activity in Azure included, but not limited, to user requests. These request are created by using the web API, which is more popularly accedes through the Azure Portal (there are other ways to access it). The request is packaged and sent to the Fabric Controller. </p>

## Amazon Web Services (AWS)

<p align="justify">  Amazon Web Services (AWS) is a cloud service platform, which provides services in different domains such as compute, storage, delivery and other functionality which help business to scale and grow. </p>

### Services
 
<p align="justify"> AWS allows users to use different variety of services to create and deploy applications in the cloud platform. These services are designed in such a way that they work with each other and produce a scalable and efficient outcome. AWS was launched in 2006 and has been one of the key players in the industry. Like other cloud platforms offer various advantages such as management overhead reduction, cost minimization etc. Within its main services are: </p>

<p align="center"><img src="./images/AWSservices.png"/></p>

<p align="justify"> AWS spans 61 Availability Zones within 20 geographic regions around the world, with announced plans for 15 more Availability Zones and five more Regions (Bahrain, Cape Town, Hong Kong SAR, Jakarta, and Milan). </p>

<p align="center"><img src="https://d1.awsstatic.com/about-aws/regions/Global%20Infrastructure%20Map-Jakarta%20and%20Hong%20Kong_update.1fcad512779992000de22e2e3344c3839d2a8d6b.png"/></p>
 
## Table of Contents  
[Headers](#headers)  
[Emphasis](#emphasis)  
...snip...    
<a name="headers"/>

  
 
