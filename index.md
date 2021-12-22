---
layout: default
---

# DevOps Solution Architect

<b>Career Objective:</b> Innovative IT professional offering vast experience leveraging software engineering and Agile/ DevOps methodologies to deliver highly effective and creative solutions to business and technological challenges. Utilizes highly attuned analytical skills to develop IT and business strategies employing cutting-edge technologies to increase productivity.

## Project - Germany's Automobile Manufacturer

### Situation
* The customer is facing major challenges regarding the efficient global distribution of his software workloads with respect to dealer and end-customer vehicle configurations
* As an automotive manufacturer the customer needs to take multiple markets and brands throughout the globe into account. For each market the accessibility (including low latencies) and stability of centrally provided services and APIs is essential to their business

### Opportunity

* As part of one the customer's first large public cloud initiatives we are building a fully automated public cloud platform in AWS based on Kubernetes that provides a generic foundation for any software workload that could potentially be shifted to the public cloud
* The entire platform can be set up from scratch in less than one hour and includes multiple aspects that simplify the platform operation such as:
* Monitoring based on Prometheus and Grafana
* HA mechanisms
* Log analysis based on Elasticsearch and Kibana
* CI/CD pipelines based on Jenkins and AWS Elastic Container Registry

### Action

* For the platform provisioning process we are using Terraform to create AWS resources
* Kops to create the Kubernetes cluster and Kubernetes configurations to create the cluster-internal resources.
* All of this is wrapped by additional automation scripts and abstracted and structured as individual tasks within a Makefile.

### Outcomes

* The customer is now able to provision a fully automated cloud platform that is suitable for use in production to any global AWS region
* The entire setup takes less than one hour and the architecture is build with focus on both high availability and cost efficiency on the AWS side
* Creating dedicated environments for its markets and brands that can host anything that can run within a container is now simple for the customer
* Currently we are working on reinforcing the reference architecture based on our ongoing experiences and on rolling out the solution to additional markets

### Technology Stack

* Cloud Technology AWS | EC2 | VPC/VPC Peering | Elastic File Systems | Elastic Container Registry | CloudFormation, Lambda | Git (SCM Tool) – Bitbucket | Jenkins | Kubernetes (Container Management Sys) | ELK Stack | Monitoring Stack (Prometheus, Grafana) | Bash Scripting

### Deliverables

* Decomposable Cloud Platform | Kubernetes Cluster setup | Infrastructure as Code | Jenkins setup on Kubernetes | Monitoring Stack on K8s cluster


## Project: Singapore's Couries Service (FedEx)

### Situation

* Multiple instances of outages and security compliance incidents due to missing critical patches 
* Bad PR globally because of outages
* No visibility of compliance status of IT estate
* Very long patching cycles
* Large number of audit violations due to deviation from defined baseline configurations

### Opportunity

* Automate patch management to reduce patching cycles and response time to critical software vulnerabilities
* Centralized compliance dashboard to provide view of patch level & configuration compliance status
* Desired state enforcement to ensure consistency of configuration & maintain highest level security posture
* Increase bandwidth and flexibility, allowing for faster growth in the infrastructure

### Action

* Implemented a solution for automated patch management and OS configuration management to integrate and work with existing customer workflows & tools using with:
  * Chef Automate 
  * Bitbucket
  * Inspec
  * Chef Vault
  * Bash Scripting
  * KitchenCI
  * Vagrant
  * HPE Educational Services

### Outcomes

* Lowered TCO by >40%
* Elimination of $400000 annual resources costs
* Lowered patching cycle times
* Improved compliance posture of IT infrastructure
* Reduced cycle time for provision of servers up to OS layer by 90%
* Improved reliability, agility, and speed to market through automated configuration management & Infrastructure as Code
* Reduced security vulnerabilities resulting in greater executive confidence

### Technology Stack

* Oracle Weblogic | Apache Tomcat | Jenkins CI + BlueOcean | Chef | Java | Groovy | Subversion | Bash scripting | Inspec | Chef Vault | Red Hat Enterprise Linux 6.x / 7.x | Windows Server 2008 / 2012 r2 | Oracle Database 12c | Red Hat Subscription Manager | Microsoft WSUS


### Deliverables

* Operations pipeline design | Jenkins setup with Blueocean | Role based access control | Jenkins pipeline configuration | Chef cookbook development | Inspec tests authoring | Manual gates configuration | Patch compliance scripts


# Data Science Enthusiast

## Project:  Fraud Detection

* Fraud detection is a set of processes and analyses that allow businesses to identify and prevent unauthorized financial activity. This can include fraudulent credit card transactions, identify theft, cyber hacking, insurance scams, and more.


## Project: Financial-Models-Numerical-Methods

* This is just a collection of topics and algorithms that in my opinion are interesting.
* It contains several topics that are not so popular nowadays, but that can be very powerful. Usually, topics such as PDE methods, LÃ©vy processes, Fourier methods or Kalman filter are not very popular among practitioners, who prefers to work with more standard tools.
The aim of these notebooks is to present these interesting topics, by showing their practical application through an interactive python implementation.
