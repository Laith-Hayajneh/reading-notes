# AWS: S3 and Lambda

## Describe “The Cloud”

The definition for the cloud can seem murky, but essentially, it’s a term used to describe a global network of servers, each with a unique function. The cloud is not a physical entity, but instead is a vast network of remote servers around the globe which are hooked together and meant to operate as a single ecosystem. These servers are designed to either store and manage data, run applications, or deliver content or a service such as streaming videos, web mail, office productivity software, or social media. Instead of accessing files and data from a local or personal computer, you are accessing them online from any Internet-capable device—the information will be available anywhere you go and anytime you need it.

## What is a container (as it relates to computers and servers)?

A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings.

## What is auto-scaling?

AWS Auto Scaling monitors your applications and automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost. Using AWS Auto Scaling, it’s easy to setup application scaling for multiple resources across multiple services in minutes.

## What is bandwidth?

Bandwidth is often mistaken for internet speed when it's actually the volume of information that can be sent over a connection in a measured amount of time – calculated in megabits per second (Mbps).

## How do cloud providers compute service costs?

The three biggest cost centers related to a cloud environment include network, compute, and storage.
Compute: Cost per GB of Virtual RAM
Each organization has a unique set of requirements including use of CPU. Most providers calculate the cost of CPU by determining the respective company’s cost per GB of virtual RAM, which includes:

Hardware operation: Providers look at the total amount of virtual RAM deployed in their public clouds and then divide that into the cost per rack unit of your hardware. Your costs may include licensing and usage-based subscription costs, depending on your virtual operating system.
Hardware acquisition: This computation tells your provider how much it costs to acquire hardware for each GB of virtual RAM that you’ll be using. They also depreciate these costs over the hardware lifecycle.
Your individual cloud computing infrastructure costs aren’t all that go into your price quote. Like IaaS cloud users, your quote includes a share of what it costs to power and cool the underlying infrastructure for the IaaS platform in the datacenter. Your price quote may also include charges related to software licenses, hosting, support and other service components. Sharing these costs with other organizations in the public cloud is what makes IaaS so cost-effective.

[How do cloud providers compute service costs](https://www.soscanhelp.com/blog/how-much-does-business-cloud-storage-cost)

## Terms

| Term                            | Def                   |
| :-------------                  |   :----------         |
| Server Instances|A server instance is a collection of SQL Server databases which are run by a solitary SQL Server service or instance. The details of each server instance can be viewed on the service console which can be web-based or command-line based. The instances are not linked with each other and can be controlled or managed separately.|
|Containers|A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings.|
|Cloud Services|Cloud services are infrastructure, platforms, or software that are hosted by third-party providers and made available to users through the internet|
|Cloud Architecture|defines the technology components that are combined to build a cloud, where resources are pooled through virtualization technology and shared across a network |
|AWS|AWS is made up of many different cloud computing products and services. The highly profitable division of Amazon provides servers, storage, networking, remote computing, email, mobile development, and security. AWS can be broken into three main products: EC2, Amazon’s virtual machine service, Glacier, a low-cost cloud storage service, and S3, Amazon’s storage system. |
|EC2/Beanstalk vs Heroku|Heroku and AWS Elastic Beanstalk, solutions (production configurations) is that they have comparable features and pricing. One big difference is that Heroku’s pricing takes exponential price jumps as one adds common additional features, e.g., auto-scaling, where-as AWS pricing is fairly linear. On the other hand, Heroku is generally simpler to get up and running as AWS has a fairly steep initial learning curve.|
