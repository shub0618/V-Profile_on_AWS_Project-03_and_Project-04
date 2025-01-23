# Repository Index

## Overview
Welcome to the AWS Projects! This repository contains the projects, scripts, and documentation organized into distinct directories.
That were done by me while pursuing my DevOps Course.

This `README.md` provides an index of all key components of the repository to help you navigate and understand the contents.

> IMPORTANT NOTE


> We have a product called V-Profile. It is a website written in Java. Consists of multiple services.
> We will be deploying this product on virtual machines and cloud platforms using differnt services.
> The same code or the product has been used for all the projects but with the different approaches based on the differnt use cases.

> NOTE: The code is not written/developed by me, this code is from my instructor who has designed this code for the differnet scenarios.


## Directory Structure

The repository is organized as follows:

```plaintext
├── AWS(Lift and Shift)/
├── AWS(Refactor)/
├── Architecture/
├── LICENSE/
└── README.md
```

## (AWS Cloud Project set-up | LIFT & SHIFT)
This is an AWS cloud computing project.
The name of this project is lift and shift application workload, and we're going to lift our application, the vprofile and shift it on AWS cloud.
In this project, we are going to host and run it on AWS cloud for production. And we're going to use a lift and shift strategy for this.
After going through this project, we will learn how to run application workload on AWS cloud by using lift and shift strategy.
We're using AWS cloud computing and the services that we are going to use In this project are: 
- Starting with ec2 instances. Ec2 instances will be our VMs for Tomcat, rabbitmq, Memcache and mysql servers.
- We will be also using elastic load balancer, which will be replacement of our engine service.
- Will be using auto scaling service, which will automatically scale out and scale in our ec2 instances, which will automatically control our resources and also our cost.
- For storage, we will be using S3 or EFS
- so and also Route 53 for a private DNS service.
- Along with these we will be using few more services like IAM, ACM, EBS etc

## (Re-Architecting Web App on AWS Cloud [PAAS & SAASS])
So from our previous project, we have seen, we deployed the vprofile application stack on our local machine and also on AWS Cloud.
From our previous project, we already know how to host our Web application stack on AWS Cloud.And we used lift and shift strategy.
In this project, we will re architecture or refactor our services, this strategy is called re architecture or refactoring.
We're using AWS cloud computing and the services that we are going to use In this project are: 

Front-end
- Beanstalk for app server, LB, Scaling
- S3/EFS for storing the artifacts
- Cloudwatch for monitoring

Back-end
- RDS Instnace for DataBase [PAAS]
- Elastic Cache 
- Active MQ
- Route53 for DNS
- Cloudfront for content delivery network
In this Project, we will see how to run our Vprofile application on containers. Now this project is more of a trailer of what is coming next in Docker.
Everything is ready made over here. We just need to bring up the VM and run our Vprofile containers on it.
In this project, we will see how these things will run on the container together. We are going to run this entire setup on a virtual machine.
So in the virtual machine, you will have all these containers running and we will access it. And we bring up the containers using the docker compose file.

 
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



