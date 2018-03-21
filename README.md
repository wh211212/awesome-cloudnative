# Cloud-Native

> 
## Components 

- [Cloud](#cloud)
- [Provisioning](#Provisioning)
- [Runtime](#Runtime)
- [Orchestration & Management](#Orchestration&Management)
- [Application Definition & Development](#Application-Definition-Development)
- [Platform](#Platform)
- [Serverless](#Serverless)
- [Observability & Analysis](#Observability&Analysis)

## Cloud

- [Public](https://www.redhat.com/en/topics/cloud-computing/what-is-public-cloud) - A public cloud is a pool of virtual resources—developed from hardware owned and managed by a third-party company—that is automatically provisioned and allocated among multiple clients through a self-service interface.
	- [Alibaba Cloud](https://www.aliyun.com/)
	- [AWS](https://aws.amazon.com)
	- [Microsoft Cloud](https://azure.microsoft.com)
	- [Baidu Cloud](https://cloud.baidu.com/)
	- [DigitalOcean](https://www.digitalocean.com/)
	- [Google Cloud](https://cloud.google.com)	
	- [Huawei Cloud](https://www.huaweicloud.com/)
	- [IBM Cloud](https://www.ibm.com/cloud/)
	- [Oracle Cloud](https://cloud.oracle.com)
	- [Joyent Cloud](https://www.joyent.com/)
	- [Packet Cloud](https://www.packet.net/)
	- [Tencent Cloud](https://cloud.tencent.com)
	- [Citrix Cloud](https://citrix.cloud.com/)

- [Private](https://azure.microsoft.com/en-us/overview/what-is-a-private-cloud/) - The private cloud is defined as computing services offered either over the Internet or a private internal network and only to select users instead of the general public. Also called an internal or corporate cloud, private cloud computing gives businesses many of the benefits of a public cloud - including self-service, scalability, and elasticity - with the additional control and customization available from dedicated resources over a computing infrastructure hosted on-premises.
	- [Openstack](https://www.openstack.org/)
	- [Scaleway](https://www.scaleway.com/)
	- [Foreman](https://www.theforeman.org/)
	- [Digital Bebar](http://rebar.digital/)
	- [MAAS](https://maas.io/)
	- [Digital Bebar](https://cloud.vmware.com/)	
	
- [Hybrid](https://azure.microsoft.com/en-us/overview/what-is-hybrid-cloud-computing/) - A hybrid cloud is a computing environment that combines a public cloud and a private cloud by allowing data and applications to be shared between them.
	- [Ensono](https://www.ensono.com)
	- [Dellemc](https://www.dellemc.com/)
	- [Bmc](https://www.bmc.com)
	- [Hpe](https://www.hpe.com/us/en/solutions/cloud.html)
	- [Interoute](https://www.interoute.com/)
	- [Scalr](https://www.scalr.com/)
	- [IBM Z hybrid cloud](https://www.ibm.com/it-infrastructure/z/capabilities/hybrid-cloud)	
	- [Rackspace Hybrid Cloud](https://www.rackspace.com/cloud/hybrid)	
	- [Microsoft Hybrid Cloud](https://azure.microsoft.com/en-us/overview/hybrid-cloud/)	
	- [VMware Hybrid Cloud](https://cloud.vmware.com/)	
	- [AWS Hybrid Cloud](https://aws.amazon.com/cn/enterprise/hybrid/)						

## Provisioning

- Container Registries
  > Container Registry is a private Docker repository that works with popular continuous delivery systems.
	- [ECR](https://aws.amazon.com/cn/ecr/) - Amazon Elastic Container Registry (ECR) is a secure, fully-managed Docker container registry that makes it easy for developers to store, manage, and deploy Docker container images.
	- [Azure Registry](https://azure.microsoft.com/en-us/services/container-registry/) - Manage a Docker private registry as a first-class Azure resource.
	- [Codefresh Registry](https://codefresh.io/registry-beta/) - Codefresh is a Docker-native CI/CD platform.Instantly build, test and deploy Docker images.
	- [Docker Registry](https://docs.docker.com/registry/) - Docker Trusted Registry (DTR) is a commercial product that enables complete image management workflow, featuring LDAP integration, image signing, security scanning, and integration with Universal Control Plane. DTR is offered as an add-on to Docker Enterprise subscriptions of Standard or higher.
	- [Google Container Registry](https://cloud.google.com/container-registry/) - High-speed, private Docker image storage on Google Cloud Platform
	- [Harbor](http://vmware.github.io/harbor/) - An Enterprise-class Container Registry Server based on Docker Distribution.
	- [JFrog Artifactory](https://jfrog.com/artifactory/) - Enterprise Universal Artifact Manager.
	- [Portus](http://port.us.org/) - Portus is an open source authorization service and user interface for the next generation Docker Registry.
	- [Project Atomic](https://www.projectatomic.io/) - Atomic Host provides immutable infrastructure for deploying to hundreds or thousands of servers in your private or public cloud. 
	- [QUAY Enterprise](https://coreos.com/quay-enterprise/) - One container registry for your entire enterprise. 
  
- Host Management & Tooling
  > Host management tool
	- [Ansible](https://www.ansible.com/)
	- [Chef](https://www.chef.io)  
	- [LniuxKit](https://github.com/linuxkit/linuxkit)
	- [CFEngine](https://cfengine.com/)  	
	- [Puppet](https://puppet.com/)  
	- [Rundeck](https://www.rundeck.com/)
	- [Saltstack](https://saltstack.com/)  

- Infrastructure Automation
  > Infrastructure automation makes servers and VM management more flexible, efficient, and scalable by converting management tasks and policy into code.
	- [AWS CloudFormation](https://aws.amazon.com/cn/cloudformation/)
	- [HOSH](https://bosh.io) - BOSH is an open source tool for release engineering, deployment, lifecycle management, and monitoring of distributed systems.
	- [Helm](https://helm.sh/) - Helm is the best way to find, share, and use software built for Kubernetes.
	- [Infrakit](https://github.com/docker/infrakit) - A toolkit for creating and managing declarative, self-healing infrastructure.
	- [Juju](https://jujucharms.com/) - Juju is an open source application modelling tool. Deploy, configure, scale and operate your software on public and private clouds.
	- [Cloud Coreo](https://www.cloudcoreo.com/) - A Platform for Modern Cloud Teams
	- [Cloudify](https://cloudify.co/) - Radically Simplifying Multi-Cloud Orchestration
	- [Kubicorn](http://kubicorn.io/) - Create, manage, snapshot, and scale Kubernetes infrastructure in the public cloud.
	- [ManageIQ](http://manageiq.org/) - Discover, Optimize, and Control your Hybrid IT
	- [Terraform](https://www.terraform.io/) - Write, Plan, and Create Infrastructure as Code
  
- [Key Management](https://en.wikipedia.org/wiki/Key_management)
  > Key management is the name of management of cryptographic keys in a cryptosystem.
	- [Knox](https://knox.apache.org/) - The Apache Knox™ Gateway is an Application Gateway for interacting with the REST APIs and UIs of Apache Hadoop deployments.The Knox Gateway provides a single access point for all REST and HTTP interactions with Apache Hadoop clusters.
	- [Oracle Policy Automation](https://www.oracle.com/applications/oracle-policy-automation/index.html) - Oracle Policy Automation is an end-to-end solution for capturing, managing, and deploying complex legislation and other document-based policies across channels and processes.
	- [Keywhiz](https://square.github.io/keywhiz/) - A system for distributing and managing secrets
	- [Lyft Confident](https://lyft.github.io/confidant/) - Confidant is a open source secret management service that provides user-friendly storage and access to secrets in a secure way, from the developers at Lyft.
	- [SPIFFE](https://spiffe.io/) - SPIFFE (Secure Production Identity Framework For Everyone) provides a secure identity, in the form of a specially crafted x509 certificate, to every workload in a modern production environment. SPIFFE removes the need for application-level authentication and authorization and complex network-level ACL configuration.
	- [Spire](https://github.com/spiffe/spire) - The SPIFFE Runtime Environment.
	- [Vault](https://www.vaultproject.io/) - A Tool for Managing Secrets. 
	  
- Secure Images
  > Secure your images so that you maintain control of how they are displayed on the Internet.
	- [Notary](https://github.com/theupdateframework/notary) - Notary is a project that allows anyone to have trust over arbitrary collections of data
	- [TUF](https://theupdateframework.github.io/) - A framework for securing software update systems
	- [Aqua](https://www.aquasec.com/) - The Aqua Container Security Platform provides development-to-production lifecycle controls for securing containerized applications that run on-premises or in the cloud, on Windows or Linux, supporting multiple orchestration environments.
	- [Clair](https://coreos.com/clair) - Clair is an open source project for the static analysis of vulnerabilities in appc and docker containers.
	- [OpenSCAP](https://www.open-scap.org/) - Discover a wide array of tools for managing system security and standards compliance.
	- [Twistlock](https://www.twistlock.com/) - Container Security for Docker, Kubernetes and Beyond
	- [Anchore](https://anchore.com/) - An open source complete solution for compliance, certification, security scanning, and auditing of public and private container images.
	- [anchore.io](https://anchore.io/) - Discover, Analyze, and Certify Container Images.
	- [Black Duck](https://www.blackducksoftware.com/)  - Complete Visibility. Automated Control.
	- [NeuVector](https://neuvector.com/) - Continuous Network Security for Kubernetes Containers
	- [Sonatype Nexus](https://www.sonatype.com/) - The world's best way to organize, store, and distribute software components.  	

## Runtime

- Cloud-Native Network
- Cloud-Native Storage
- Container Runtime

## Orchestration & Management

- Coordination & Service Discovery
- Scheduling & Orchestration
- Service Management

## Application Definition & Development

- Application Definition
- CI & CD
- Database & Data Warehouse
- Source Code Management
	- [Tutorials](https://github.com/ujjwalkarn/Machine-Learning-Tutorials)
- Streaming
	- [Spanish](https://github.com/dav009/awesome-spanish-nlp)
	
## Platform

- Certified Kubernetes - Distribution
- Certified Kubernetes - Platform
- Non-Certified Kubernetes
- PaaS & Container Service

## Serverless

- Frameworks
- Hybrid Platforms
- Kubernetes-Native Platforms
- Libraries
- Platforms
- Security
- Tools

## Observability & Analysis

- Monitoring
- Logging
- Tracing

## Books

- [Free Programming Books](https://github.com/EbookFoundation/free-programming-books)
- [Free Software Testing Books](https://github.com/ligurio/awesome-software-quality)
- [Go Books](https://github.com/dariubs/GoBooks)
- [R Books](https://github.com/RomanTsegelskyi/rbooks)
- [Mind Expanding Books](https://github.com/hackerkid/Mind-Expanding-Books)
- [Book Authoring](https://github.com/TalAter/awesome-book-authoring)
- [Elixir Books](https://github.com/sger/ElixirBooks)

## License
