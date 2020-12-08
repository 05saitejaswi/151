# 151 =AWS
Amazon Web Services (AWS) is a subsidiary of Amazon providing on-demand cloud computing platforms and APIs to individuals, companies, and governments, on a metered pay-as-you-go basis.

Key Term                                                                          	Definition
                                                 The Cloud	A collection of servers on the internet that store and manage data, run apps, and deliver content such as email or                                                      videos.
                                                 
                                                 
 Cloud Computing                                 Cloud Computing	The delivery of software and storage over the Internet (i.e. the cloud).
 
 
Public Cloud	                                   Public CloudCloud computing resources shared amongst multiple customers, with applications and data still separate.


Private Cloud	                                   Private Cloud Cloud computing resources that are dedicated to only one entity. This is most similar to how on-premises resources                                                    operate, but with the resources still hosted off-site by a third party.


Hybrid Cloud	                                   Hybrid Cloud Utilizing a mix of public and private cloud resources.


Cloud Developer                                	Developers who build cloud applications or utilize other cloud resources in their applications. They are responsible for ensuring                                                 applications run efficiently in the cloud, requiring appropriate authentication to access, and identifying appropriate      
                                                resources to use.

Microsoft Azure	                                A public computing platform provided by Microsoft, with many products spanning many categories, such as Compute, Analytics,                                                         Databases, A.I. and Machine Learning.

Azure Portal                                  	The browser-based and GUI version of working with Azure resources.

Elasticity	                                    The ability to scale up or down resources to match demand.

On-Premises                                    	The non-cloud option where companies host all their necessary compute, storage and other resources on-site.

Infrastructure as a Service (Iaas)	             Removes the expense of up-front costs of hardware, software and test environments, as the cloud provider is instead responsible                                                   for providing physical hardware.

Platform as a Service (Paas)	                 Handles networking, provides middleware and development & database tools, in addition to the physical hardware provided at the                                                    IaaS  level.

Software as a Service (Saas)	               Provides end-users access to online cloud solutions, without the need to build or support the underlying applications themselves.


Key Term                                                             	Definition
Subscription	                                   Multiple of these can exist within a single Azure account; often used for billing and other management purposes.

Resource Group	                               Help to organize resources you use, such as Virtual Machines, App Services or storage, in order to make resource management                                                      easier. Groups are often set up for different projects or regions.

Region                                       	Locations of Azure data centers around the world. The closer the region of app resources is to the end user, the lower the latency                                                experienced.

ARM Templates                                 	Created within Azure Resource Manager to more easily spin up a set of given resources multiple times.


Virtual Machines	                             An Azure IaaS option giving you full access to the underlying operating system of a compute resource. These can be either Windows                                              or Linux machines, with great availability, scalability and redundancy. These require more on-going maintenance and up-keep by cloud                                              developers.

App Service                                    	An Azure PaaS option allowing developers to focus more on their apps than the underlying infrastructure. It is an HTTP-based                                                     service for hosting web applications, REST APIs, and mobile back ends. It supports multiple languages and continuous deployment.                                                While they are good for scaling, there is also a limit of up to 14 GB or 4 CPU cores on the highest tier.

App Service Plan                           	Contains certain settings of an App Service, such as region, number of VM instances (App Services still run on VMs, but the developer                                             does not have control of the underlying VM, and the app may share the VM with other apps), size of those instances, and pricing tier.

Azure Batch                             	Used for running large-scale and high-performance compute applications beyond the capabilities of an App Service.


Azure Functions                         	A serverless, event-driven, compute-on-demand platform (covered in a later course).

Container Instances	A platform for deploying serverless docker containers (covered in a later course), without the container orchestration provided by AKS (see below).
Service Fabric	Microsoft's own distributed systems platform, similar to Kubernetes.
Azure Kubernetes Service (AKS)	Microsoft's own platform for hosting and managing Kubernetes, including deploying docker containers into clusters (covered in a later course).
