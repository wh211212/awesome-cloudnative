# <img src="https://raw.githubusercontent.com/wh211212/Cloud-Native/master/Images/cloudnativelog.png" width="500" alt="Cloud Native">

[![jaywcjlove/sb](https://jaywcjlove.github.io/sb/lang/chinese.svg)](README-cn.md)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> An awesome & curated list of best applications and tools for Cloud Native.

> This Awesome Repository is highly inspired from cncf's [landscape](https://github.com/cncf/landscape) & [Awesome](https://github.com/Awesome-Windows/Awesome).

> *Items marked with ![Open-Source Software][OSS Icon] are open-source software. Items marked with ![Freeware][Freeware Icon] are free.*

<!-- <img src="https://raw.githubusercontent.com/wh211212/Cloud-Native/master/Images/cloudnativelog.png" width="500" alt="Cloud Native"> -->

## Cloud Native Services

# <img src="https://raw.githubusercontent.com/wh211212/Cloud-Native/master/Images/CloudNativeLandscape_latest.png" width="800" alt="cloud native">

# <img src="https://raw.githubusercontent.com/wh211212/Cloud-Native/master/Images/TableOfContents.png" width="600" alt="cloud native">

## Components 

- [Cloud](#Cloud)
- [Provisioning](#Provisioning)
- [Runtime](#Runtime)
- [Orchestration & Management](#Orchestration&Management)
- [Application Definition & Development](#Application-Definition-Development)
- [Platform](#Platform)
- [Serverless](#Serverless)
- [Observability & Analysis](#Observability&Analysis)

## Cloud

- [Public](https://www.redhat.com/en/topics/cloud-computing/what-is-public-cloud) - A public cloud is a pool of virtual resources—developed from hardware owned and managed by a third-party company—that is automatically provisioned and allocated among multiple clients through a self-service interface.
	- [Alibaba Cloud](https://www.alibabacloud.com/) - Alibaba Cloud develops highly scalable cloud computing and data management services.
	- [Amazon Web Services](https://aws.amazon.com) - Amazon Web Services provides information technology infrastructure services to businesses in the form of web services.
	- [Azure Cloud](https://azure.microsoft.com) - Microsoft is a software corporation that develops, manufactures, licenses, supports, and sells a range of software products and services.
	- [Baidu Cloud](https://cloud.baidu.com/) - Baidu is a Chinese website and search engine that enables individuals to obtain information and find what they need.
	- [DigitalOcean](https://www.digitalocean.com/) - DigitalOcean is an IaaS company that delivers a seamless way for developers and businesses to deploy and scale any application in the cloud.
	- [Fujitsu K5](https://www.fujitsu.com/global/solutions/cloud/k5/) - Fujitsu provides information technology and communications solutions.
	- [Google Cloud](https://cloud.google.com) - Google is a multinational corporation that is specialized in internet-related services and products.
	- [Huawei Cloud](https://www.huaweicloud.com/) - Huawei Technologies provides infrastructure application software and devices with wireline, wireless, and IP technologies.
	- [IBM Cloud](https://www.ibm.com/cloud/) - IBM is an IT technology and consulting firm providing computer hardware, software, and infrastructure and hosting services.
	- [Oracle Cloud](https://cloud.oracle.com) - Oracle is a computer technology corporation developing and marketing computer hardware systems and enterprise software products.
	- [Joyent Cloud](https://www.joyent.com/) - Your Cloud, Your Way
	- [Packet Cloud](https://www.packet.net/) - Packet is a bare metal cloud built for developers. 8 minute deploys, no hypervisor, & full automation support from 15 global data centers.
	- [Tencent Cloud](https://cloud.tencent.com) - Tencent is a Chinese internet service portal offering value-added internet, mobile, telecom, and online advertising services.
	- [Citrix Cloud](https://citrix.cloud.com/) - Move Faster, Work Better, Lower IT Costs
	- [Heroku ](https://www.heroku.com) - Heroku is a cloud platform based on a managed container system, with integrated data services and a powerful ecosystem, for deploying and running modern apps.
  - [Rackspace]https://www.rackspace.com/() - CERTIFIED TO MANAGE THE WORLD’S LEADING CLOUDS. BECAUSE ONE SIZE DOESN’T FIT ALL.

- [Private](https://azure.microsoft.com/en-us/overview/what-is-a-private-cloud/) - The private cloud is defined as computing services offered either over the Internet or a private internal network and only to select users instead of the general public. Also called an internal or corporate cloud, private cloud computing gives businesses many of the benefits of a public cloud - including self-service, scalability, and elasticity - with the additional control and customization available from dedicated resources over a computing infrastructure hosted on-premises.
	- [Openstack](https://www.openstack.org/) - Repository containing OpenStack repositories
	- [Scaleway](https://www.scaleway.com/) - Scaleway is the world's first Cloud Computing IaaS platform
	- [Foreman](https://www.theforeman.org/) - an application that automates the lifecycle of servers
	- [Digital Bebar](http://rebar.digital/) - Digital Rebar Provision is a simple but powerful Golang executable that provides a complete API-driven DHCP/PXE/TFTP provisioning system.
	- [MAAS](https://maas.io/) - Official MAAS repository mirror. (Do not submit pull requests or bugs here; use Launchpad instead.)
	- [VMware](VMware) - VMware is a software company providing cloud and virtualization services.
	
- [Hybrid](https://azure.microsoft.com/en-us/overview/what-is-hybrid-cloud-computing/) - A hybrid cloud is a computing environment that combines a public cloud and a private cloud by allowing data and applications to be shared between them.
	- [Ensono](https://www.ensono.com) - Complete hybrid IT services – from cloud to mainframe. Operate for today. Optimize for tomorrow.
	- [Dellemc](https://www.dellemc.com/) - Dell EMC is a powerful part of Dell Technologies' commitment to your transformation
	- [Hpe](https://www.hpe.com/us/en/solutions/cloud.html) - Hybrid Cloud Solutions
	- [Scalr](https://www.scalr.com/) - The Hybrid Cloud Management Platform
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
	- [Ansible](https://www.ansible.com/) - Ansible is designed around the way people work and the way people work together.
	- [Chef](https://www.chef.io) - Ship better software, faster.Enable collaboration and continuous automation across your infrastructure, applications, and compliance for all your apps and infrastructure. 
	- [LniuxKit](https://github.com/linuxkit/linuxkit) - A toolkit for building secure, portable and lean operating systems for containers
	- [CFEngine](https://cfengine.com/) - CFEngine Community
	- [Puppet](https://puppet.com/) - Server automation framework and application
	- [Rundeck](https://www.rundeck.com/) - Enable Self-Service Operations: Give specific users access to your existing tools, services, and scripts
	- [Saltstack](https://saltstack.com/) - Intelligent automation for a software-defined world

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
	  
- [Secure Images](https://docs.imgix.com/setup/securing-images)
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
  > Network Segmentation and Policy,SDN & APIs (eg CNI, libnetwork)
  
  Incubating CNCF Projects
  - [CNI](https://github.com/containernetworking) - Container Network Interface - networking for Linux containers
  
  CNCF Member Products/Projects
  - [Aporeto](https://www.aporeto.com/) - Cloud Native Security for Containers and Microservices
  - [Cannl](https://github.com/projectcalico/canal) - Policy based networking for cloud native applications
  - [Contiv](https://contiv.github.io/) - Container networking for various use cases
  - [Flannel](https://github.com/coreos/flannel/) - flannel is a network fabric for containers, designed for Kubernetes
  - [NSX](https://www.vmware.com/products/nsx.html) - VMware is a software company providing cloud and virtualization services.
  - [Open vSwitch](https://openvswitch.org/) - Open vSwitch is a multilayer software switch licensed under the open source Apache 2 license.
  - [OpenContrial](http://www.opencontrail.org/) - An open-source network virtualization platform for the cloud.
  - [Project Calico](https://www.projectcalico.org/) - Cloud native application connectivity and network policy 
  - [Weave Net](https://www.weave.works/oss/net/) - Simple, resilient multi-host Docker networking and more.
  
  Non-CNCF Member Products/Projects
  - [Aviatrix](https://aviatrix.com/) - The company develops software that enables enterprises to build hybrid clouds by easily
  - [Big Switch Networks](https://www.bigswitch.com/) - Big Switch Networks is the Next-Generation Data Center Networking Company, designing intelligent, agile and flexible networks 
  - [Cilium](https://www.cilium.io/) - HTTP, gRPC, and Kafka Aware Security and Networking for Containers with BPF and XDP
  - [Cumulus](https://cumulusnetworks.com/) - Cumulus Networks, a software company, designs, and sells Linux operating systems for networking hardware.
  - [GuardiCoreCentra](https://www.guardicore.com/workloads-protection-hybrid-clouds/) - GuardiCore provides network security solutions for software defined data centers.
  - [MidoNet](https://www.midonet.org/) - MidoNet is an Open Source network virtualization system for Openstack clouds
  - [Nuage Networks](http://www.nuagenetworks.net/) - Nuage Networks Fundamentals: Software Defined Networking for the Datacenter and Beyond.
  - [Plumgrid](https://www.vmware.com/products/nsx.html) - PLUMgrid is involved in virtual networking and SDN/NFV to deliver cloud infrastructure solutions that transform businesses. 
  - [Romana](http://romana.io/) - The Romana Project - Installation scripts, documentation, issue tracker and wiki. Start here.
  - [SnapRoute](https://snaproute.com/) - SnapRoute is an open networking stack company.   
    
- Cloud-Native Storage
  > Volume Drivers/Plugins,Local Storage Management,Remote Storage Access
  
  Sandbox CNCF Projects
  - [Rook](https://rook.io/) - File, Block, and Object Storage Services for your Cloud-Native Environments
  
  CNCF Member Products/Projects 
  - [Ceph](https://ceph.com/) - Ceph is a unified, distributed storage system designed for excellent performance, reliability and scalability.
  - [Container Storage Interface](https://github.com/container-storage-interface/spec) - Container Storage Interface (CSI) Specification.
  - [Dell EMC](https://www.dellemc.com) - IT and Workforce Transformation. Made real every day.
  - [Diamanti](https://diamanti.com/) - Diamanti is the first container platform with plug and play network and persistent storage that seamlessly integrates the most widely adopted software stack - standard open source Kubernetes and Docker - so there is no vendor lock-in. QoS on network and storage maximizes container density. 
  - [Gluster](https://www.gluster.org/) - Gluster is free and open source softeare scalable network filesystem.
  - [Hatchway](https://vmware.github.io/hatchway/) - Persistent Storage for Cloud Native Applications
  - [Kasten](https://kasten.io/) - Kasten is on a mission to dramatically simplify operational management of stateful cloud-native applications.
  - [Manta](https://github.com/Illumina/manta) - Structural variant and indel caller for mapped sequencing data
  - [Minio](https://minio.io/) - Minio is a high performance distributed object storage server, designed for large-scale private cloud infrastructure. Minio is widely deployed across the world with over 64.2M+ docker pulls.
  - [NetApp](https://www.netapp.com) - NetApp HCI. All New and Available Now.
  - [OpenEBS](https://www.openebs.io) - OpenEBS is an open source storage platform that provides persistent and containerized block storage for DevOps and container environments.
  - [Portworx](https://portworx.com/) - The Solution for Stateful Containers in Production. Designed for DevOps.
  - [Rex-Ray](https://rexray.readthedocs.io) - REX-Ray is an open source, storage management solution designed to support container runtimes such as Docker and Mesos.
  - [StorageOS](https://storageos.com/) - Enterprise persistent storage for containers and the cloud.
  
  Non-CNCF Member Products/Projects
  - [Datera](https://datera.io/) - Datera is an application-driven data infrastructure company.
  - [Hedving](https://www.hedviginc.com/) - Modern storage for the modern business.
  - [Infinit](https://www.infinit.sh/) - The Elle coroutine-based asynchronous C++ development framework.
  - [LeoFS](https://leo-project.net/leofs/) - The LeoFS Storage System
  - [OpenIO](https://www.openio.io/) - OpenIO Software Defined Storage
  - [Pure Storage](https://www.purestorage.com/) - Pure Storage is an all-flash enterprise storage company that enables broad deployment of flash in data centers.
  - [Quobyte](https://www.quobyte.com/) - Data Center File System. Fast and Reliable Software Storage
  - [Robin Systems](https://robinsystems.com/) - Data-Centric Compute and Storage Containerization Infrastructure Software
  - [Sheepdog](https://sheepdog.github.io/sheepdog/) - Distributed Storage System for QEMU
  - [Springpath](http://springpathinc.com/) - Springpath is hyperconvergence software that turns standard servers of choice into a single pool of compute and storage resources.
  - [Swift](https://docs.openstack.org/swift/latest/) - OpenStack Storage (Swift)
  
- Container Runtime
  > The new CF Container Runtime gives you more granular control and management of containers with Kubernetes.
  
  Incubating CNCF Projects 
  - [containerd](https://containerd.io/) 
  - [rkt](https://github.com/rkt/rkt) - rkt is a pod-native container engine for Linux. It is composable, secure, and built on standards.
  
  CNCF Member Products/Projects
  - [CRI-O](http://cri-o.io/) - Open Container Initiative-based implementation of Kubernetes Container Runtime Interface
  - [Intel Clear Containers](https://clearlinux.org/containers) - OCI (Open Containers Initiative) compatible runtime using Virtual Machines
  - [Ixd](https://linuxcontainers.org/lxd/) - Daemon based on liblxc offering a REST API to manage containers
  - [Pouch](https://github.com/alibaba/pouch) - Pouch is an open-source project created to promote the container technology movement.
  - [runc](https://www.opencontainers.org/) - CLI tool for spawning and running containers according to the OCI specification
  - [SmartOS](https://www.joyent.com/smartos) - Converged Container and Virtual Machine Hypervisor
    
  Non-CNCF Member Products/Projects  
  - [Kata Containers](https://katacontainers.io/) - Kata Containers runtimes
  - [RunV](https://github.com/hyperhq/runv) - Hypervisor-based Runtime for OCI
  - [Singularity](https://www.sylabs.io/) - Singularity: Application containers for Linux       
  
## Orchestration & Management

- Scheduling & Orchestration

  Graduated CNCF Projects
  - [Kubernetes](https://kubernetes.io/) - Kubernetes is an open-source system for automating deployment, scaling, and management of containerized applications
  
  CNCF Member Products/Projects
  - [ECS](https://aws.amazon.com/ecs/) - Amazon Web Services provides information technology infrastructure services to businesses in the form of web services.
  - [Docker Swarm](https://docs.docker.com/engine/swarm/) -  Swarm: a Docker-native clustering system 
  - [Microsoft Azure Service Fabric](https://docs.microsoft.com/en-us/azure/service-fabric/) - Service Fabric is a distributed systems platform for packaging, deploying, and managing stateless and stateful distributed applications and containers at large scale.   
    
  Non-CNCF Member Products/Projects
  - [Mesos](https://mesos.apache.org/) - Mirror of Apache Mesos
  - [Nomad](https://www.nomadproject.io/) - Nomad is a flexible, enterprise-grade cluster scheduler designed to easily integrate into existing workflows.       
    
- Coordination & Service Discovery

  Incubating CNCF Projects
  - [CoreDNS](https://coredns.io/) - CoreDNS is a DNS server that chains plugins.
    
  CNCF Member Products/Projects
  - [ContainerPilot](https://www.joyent.com/containerpilot) - A service for autodiscovery and configuration of applications running in containers
  - [etcD](https://coreos.com/etcd/) - Distributed reliable key-value store for the most critical data of a distributed system
  - [VMware Haret](https://github.com/vmware/haret) - A strongly consistent distributed coordination system, built using proven protocols & implemented in Rust.
      
  Non-CNCF Member Products/Projects
  - [Apache Zookeeper](https://zookeeper.apache.org/) - Apache ZooKeeper is an effort to develop and maintain an open-source server which enables highly reliable distributed coordination.
  - [Consul](https://www.consul.io/) - Consul is a distributed, highly available, and data center aware solution to connect and configure applications across dynamic, distributed infrastructure.
  - [Eureka](https://github.com/Netflix/eureka) - AWS Service registry for resilient mid-tier load balancing and failover.
  - [SkyDNS](https://github.com/skynetservices/skydns) - DNS service discovery for etcd
  - [SmartStack](https://medium.com/airbnb-engineering/smartstack-service-discovery-in-the-cloud-4b8a080de619) - A transparent service discovery framework for connecting an SOA       

- Service Management

  - [Envoy](https://envoyproxy.github.io/) - C++ front/service proxy
  - [gRPC](https://grpc.io/) - The C based gRPC (C++, Python, Ruby, Objective-C, PHP, C#)
  - [Linkerd](https://linkerd.io/) - Production-grade feature-rich service mesh for any platform
  - [3Scale](https://www.3scale.net/) - 3scale api gateway reloaded
  - [Ambassador](https://www.getambassador.io/) - open source Kubernetes-native API gateway for microservices built on the Envoy Proxy
  - [Avi Networks](https://avinetworks.com/) - Avi Networks is a Silicon Valley startup with proven track record in building virtualization, networking and software solutions.
  - [Conduit](https://conduit.io/) - Ultralight service mesh for Kubernetes
  - [F5](https://f5.com/) -  F5 Networks provides application delivery networking technology that optimizes the delivery of network-based applications.
  - [Heptio Contour](https://github.com/heptio/contour) - Contour is a Kubernetes ingress controller for Lyft's Envoy proxy.
  - [Kong](https://www.konghq.com/) - 🐒 The Microservice API Gateway
  - [NGINX](https://www.nginx.com/) - application delivery for the modern web
  - [Open Service Broker API](https://www.openservicebrokerapi.org/) - Open Service Broker API Specification
  - [Turbine Labs](https://www.turbinelabs.io/) - Turbine Labs
  - [Apache Thrift](https://thrift.apache.org/) - Mirror of Apache Thrift
  - [Avro](https://avro.apache.org/) - Apache Avro
  - [Backplane](https://www.backplane.io/) - A service that unifies discovery, routing, and load balancing for web servers written in any language, running in any cloud or datacenter.
  - [HAProxy](https://www.haproxy.org/) - The Reliable, High Performance TCP/HTTP Load Balancer     
  - [Hystrix](https://github.com/Netflix/Hystrix) - Hystrix is a latency and fault tolerance library designed to isolate points of access to remote systems, services and 3rd party libraries, stop cascading failure and enable resilience in complex distributed systems where failure is inevitable.
  - [Istio](https://istio.io/) -  An open platform to connect, manage, and secure microservices.
  - [Netflix Zuul](https://github.com/Netflix/zuul) - Zuul is a gateway service that provides dynamic routing, monitoring, resiliency, security, and more.
  - [Open Policy Agent (OPA)](https://www.openpolicyagent.org/) - An open source project to policy-enable your service.  
  - [Ribbon](https://github.com/Netflix/ribbon) - Ribbon is a Inter Process Communication (remote procedure calls) library with built in software load balancers. 
  - [Traefik](https://traefik.io/) - Træfik, a modern reverse proxy
  - [Vamp](https://vamp.io/) - Vamp - canary releasing and autoscaling for microservice systems.    

## Application Definition & Development

- Database & Data Warehouse
  
  Incubating CNCF Projects
  - [Vitess](https://vitess.io/) - Vitess is a database clustering system for horizontal scaling of MySQL.
  
  CNCF Member Products/Projects
  - [Cloudhbase](https://www.couchbase.com/) - Lightweight, embedded, syncable NoSQL database engine for iOS (and Mac!) apps.
  - [IBM DB2](https://www.ibm.com/analytics/us/en/db2/) - IBM is an IT technology and consulting firm providing computer hardware, software, and infrastructure and hosting services.
  - [Iguazio](https://www.iguazio.com/) - iguazio's Continuous Analytics Data Platform has redesigned the data stack to accelerate performance in big data, IoT and cloud-native apps.
  - [Infinispan](http://infinispan.org/) - Infinispan is an open source data grid platform and highly scalable NoSQL cloud data store.
  - [Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server) - Microsoft is a software corporation that develops, manufactures, licenses, supports, and sells a range of software products and services.
  - [MySQL](https://www.oracle.com/mysql/index.html) - MySQL Server, the world's most popular open source database, and MySQL Cluster, a real-time, open source transactional database.
  - [Oracle](https://developer.oracle.com/) - Oracle is a computer technology corporation developing and marketing computer hardware systems and enterprise software products.
  - [RethinkDB](https://www.rethinkdb.com/) - The open-source database for the realtime web.
  - [SQL Data Warehouse](https://azure.microsoft.com/en-us/services/sql-data-warehouse/) - Microsoft is a software corporation that develops, manufactures, licenses, supports, and sells a range of software products and services.
  - [YugaByte DB](https://www.yugabyte.com/product/yugabytedb/) - YugaByteDB is a transactional, high-performance database for building distributed cloud services. It currently supports Redis API (as a true DB) and Cassandra API, with SQL coming very soon.
  
  Non-CNCF Member Products/Projects
  - [ArangoDB](https://www.arangodb.com/) - 🥑 ArangoDB is a native multi-model database with flexible data models for documents, graphs, and key-values. Build high performance applications using a convenient SQL-like query language or JavaScript extensions.
  - [BigchainDB](https://www.bigchaindb.com/) - Meet BigchainDB. The blockchain database.
  - [CarbonData](https://carbondata.apache.org/) - Mirror of Apache CarbonData
  - [Cassandra](https://cassandra.apache.org/) - Mirror of Apache Cassandra
  - [CockroachDB](https://www.cockroachlabs.com/) - CockroachDB - the open source, cloud-native SQL database.
  - [Crate.io](https://crate.io/) - CrateDB is a distributed SQL database that makes it simple to store and analyze massive amounts of machine data in real-time.
  - [Druid](http://druid.io/) - Column oriented distributed data store ideal for powering interactive applications.
  - [Hadoop](https://hadoop.apache.org/) - Mirror of Apache Hadoop
  - [MariaDB](https://mariadb.org/) - MariaDB server is a community developed fork of MySQL server. Started by core members of the original MySQL team, MariaDB actively works with outside developers to deliver the most featureful, stable, and sanely licensed open SQL server in the industry.
  - [MemSQL](https://www.memsql.com/) - A real-time data warehouse you can run everywhere
  - [MongoDB](https://www.mongodb.com/) - MongoDB is a document database with the scalability and flexibility that you want with the querying and indexing that you need
  - [NomsDB](https://github.com/attic-labs/noms) - The versioned, forkable, syncable database
  - [OrientDB](https://orientdb.com/why-orientdb/) - OrientDB is the most versatile DBMS supporting Graph, Document, Reactive, Full-Text, Geospatial and Key-Value models in one Multi-Model product. OrientDB can run distributed (Multi-Master), supports SQL, ACID Transactions, Full-Text indexing and Reactive Queries. OrientDB Community Edition is Open Source using a liberal Apache 2 license.
  - [Pachyderm](https://www.pachyderm.io/) - Reproducible Data Science at Scale!
  - [Pilosa](https://www.pilosa.com/) - Pilosa is an open source, distributed bitmap index that dramatically accelerates queries across multiple, massive data sets.
  - [PostgreSQL](https://www.postgresql.org/) - PostgreSQL is a powerful, open source object-relational database system.
  - [Presto](https://prestodb.io/) - Distributed SQL query engine for big data
  - [Qubole](https://www.qubole.com/) - Qubole delivers a Self-Service Platform for Big Data Analytics built on Amazon, Microsoft, Google and Oracle Clouds.
  - [Redis](https://redis.io/) - Redis is an in-memory database that persists on disk. The data model is key-value, but many different kind of values are supported: Strings, Lists, Sets, Sorted Sets, Hashes, HyperLogLogs, Bitmaps.
  - [Scylla](https://www.scylladb.com/) - NoSQL data store using the seastar framework, compatible with Apache Cassandra
  - [Snowflake](https://www.snowflake.net/) - Snowflake is the only data warehouse built for the cloud.
  - [Software AG](https://www.softwareag.com/us/default.html) - Software AG provides business process management, data management, and consulting services worldwide.
  - [Starburst](https://www.starburstdata.com/) - Starburst (www.starburstdata.com) is the enterprise Presto company offering an SQL-on-Anything analytics platform. 
  - [TiDB](https://pingcap.com/index) - TiDB is a distributed HTAP database compatible with the MySQL protocol.
  - [Vertica](https://www.vertica.com/) - Vertica Systems develops data management solutions for storing databases and allowing clients to conduct real-time and ad hoc queries.         

- Streaming

  Incubating CNCF Projects
  - [NATS](https://nats.io/) - High-Performance server for NATS, the cloud native messaging system.

  CNCF Member Products/Projects
  - [Amazon Kinesis](https://aws.amazon.com/kinesis/) - Amazon Web Services provides information technology infrastructure services to businesses in the form of web services.
  - [CloudEvents](https://openevents.io/) - CloudEvents Specification
  - [Google Cloud Dataflow](https://cloud.google.com/dataflow/) - Google is a multinational corporation that is specialized in internet-related services and products.
  - [Heron](https://twitter.github.io/heron/) - Heron is a realtime, distributed, fault-tolerant stream processing engine from Twitter
  
  Non-CNCF Member Products/Projects  
  - [Apache Apex](https://apex.apache.org/) - Mirror of Apache Apex core
  - [Apache NiFi](https://nifi.apache.org/) - Mirror of Apache NiFi
  - [Apache RocketMQ](https://rocketmq.apache.org/) - Mirror of Apache RocketMQ
  - [Apache Spark](https://spark.apache.org/) - Mirror of Apache Spark
  - [Apache Storm](https://storm.apache.org/) - Mirror of Apache Storm
  - [Flink](https://flink.apache.org/) - Mirror of Apache Flink	  
  - [Kafka](https://kafka.apache.org/) - Mirror of Apache Kafka
  - [Pulsar](https://pulsar.apache.org/) - Pulsar - distributed pub-sub messaging system
  - [RabbitMQ](https://www.rabbitmq.com/) - RabbitMQ is the most widely deployed open source message broker.
  - [StreamSets](https://streamsets.com/) - StreamSets DataCollector - Continuous big data ingest infrastructure. 	   
                  
- Source Code Management

  - [GitHub](https://github.com/) - GitHub is a web-based Git repository hosting service offering distributed revision control and source code management functionality of Git.
  - [GitLab](https://gitlab.com/) - GitLab CE | Please open new issues in our issue tracker on GitLab.com
  - [Visual Studio Team Services](https://www.visualstudio.com/team-services/) - Microsoft is a software corporation that develops, manufactures, licenses, supports, and sells a range of software products and services.
  - [Bitbucket](https://bitbucket.org/) - Atlassian provides collaboration software for teams with products including JIRA, Confluence, HipChat, Bitbucket, and Stash.
	                  
- Application Definition
  - [Bitnami](https://bitnami.com/) - Loved by Devs, Trusted by Ops. Easy to use cloud images, containers, and VMs that work on any platform
  - [Docker Compose](https://docs.docker.com/compose/) - Define and run multi-container applications with Docker
  - [Habitat](https://www.habitat.sh/) - Modern applications with built-in automation
  - [OpenAPI](https://www.openapis.org/) - The OpenAPI Specification Repository
  - [Telepresence](https://www.telepresence.io/) - Local development against a remote Kubernetes or OpenShift cluster
  - [Apache Brooklyn](https://brooklyn.apache.org/) - Apache Brooklyn
  - [KubeVirt](https://www.kubevirt.io/) - A virtualization API and runtime add-on for Kubernetes in order to define and manage virtual machines.
  - [Packer](https://www.packer.io/) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
  
- CI & CD

  > Continuous integration and continuous delivery are two approaches to software development that are designed to improve code quality and enable rapid delivery and deployment of code.
  
  CNCF Member Products/Projects
  - [Argo](https://applatix.com/open-source/argo/) - Get stuff done with container-native workflows for Kubernetes.
  - [Cloud 66 Skycap](https://www.cloud66.com/containers/skycap) - Ops tools for Devs. Build, deliver, deploy and manage any applications on any cloud or server.
  - [Cloudbees](https://www.cloudbees.com/) - CloudBees offers CloudBees Jenkins Enterprise, an enterprise-grade continuous delivery platform powered by Jenkins.
  - [Codefresh](https://codefresh.io/) - Codefresh is a continuous delivery and collaboration platform for containers and microservices.
  - [Codeship](https://codeship.com/) - CloudBees offers CloudBees Jenkins Enterprise, an enterprise-grade continuous delivery platform powered by Jenkins.
  - [Concourse](https://concourse.ci/) - BOSH release and development workspace for Concourse
  - [ContainerOps](https://containerops.org/) - DevOps Orchestration Platform 
  - [Habitus](https://www.habitus.io/) - A Build Flow Tool for Docker
  - [Runner](https://docs.gitlab.com/runner/) - GitLab Runner is the open source project that is used to run your jobs and send the results back to GitLab. 
  - [Weave Flux](https://www.weave.works/oss/flux/) - A tool for deploying container images to Kubernetes services
  - [Wercker](https://www.wercker.com/) - The Wercker CLI can be used to execute pipelines locally for both local development and easy introspection.
  
  Non-CNCF Member Products/Projects
  - [Appveyor](https://www.appveyor.com/) - Appveyor Systems Inc. aim is to give powerful continuous integration and deployment tools to every .NET developer.  
  - [Bamboo](https://www.atlassian.com/software/bamboo/) - Atlassian provides collaboration software for teams with products including JIRA, Confluence, HipChat, Bitbucket, and Stash.
  - [BuddyBuild](https://www.buddybuild.com/) - Buddybuild is a Vancouver-based app tools company focused on continuous integration and debugging tools.
  - [Buildkite](https://buildkite.com/) - The Buildkite Agent is an open-source toolkit written in Golang for securely running build jobs on any device or network
  - [CircleCI](https://circleci.com/) - CircleCI provides software teams the confidence to build, test, and deploy across numerous platforms.
  - [Distelli](https://www.distelli.com/) - True Continuous Delivery from Source Control to Servers.
  - [Drone](http://try.drone.io/) - Drone is a Continuous Delivery platform built on Docker, written in Go
  - [Jenkins](https://jenkins.io/) - Build great things at any scale
  - [Octopus Deploy](https://octopus.com/) - Octopus Deploy is a user-friendly release management
  - [OpenStack Zuul CI](https://zuul-ci.org/) - The Gatekeeper, or a project gating system
  - [Semaphore](https://semaphoreci.com/) - Hosted continuous integration and deployment service
  - [Shippable](https://www.shippable.com/) - Shippable helps companies ship code faster by giving them a powerful continuous integration platform built natively on Docker.
  - [Solano Labs](https://www.solanolabs.com/) - Continuous Integration & Deployment       
  - [Spinnaker](https://www.spinnaker.io/) - Spinnaker is an open source, multi-cloud continuous delivery platform for releasing software changes with high velocity and confidence.
  - [Travis](https://travis-ci.com/) - The Ember web client for Travis CI
  - [XL Deploy](https://xebialabs.com/products/xl-deploy/) - XebiaLabs develops enterprise-scale Continuous Delivery and DevOps software.    
  
## Platform

- Certified Kubernetes - Distribution
  - [Apprenda Kismatic Enterprise Toolkit (KET)](https://apprenda.com/kismatic/)
  - [Appscode Pharmer](https://appscode.com/products/pharmer/)
  - [Caicloud Compass](https://caicloud.io/products/compass)
  - [Canonical Distribution of Kubernetes](https://www.ubuntu.com/kubernetes)
  - [Cloud Foundry Container Runtime](https://www.cloudfoundry.org/container-runtime/)
  - [CoreOS bootkube](https://github.com/kubernetes-incubator/bootkube)
  - [DaoCloud Enterprise](https://www.daocloud.io/)
  - [Diamanti Converged Container Infrastructure](https://diamanti.com/products/)
  - [Docker EE/CE](https://www.docker.com/kubernetes)
  - [Ghostcloud EcOS](https://www.ghostcloud.cn/ecos-kubernetes/)
  - [Giant Swarm Managed Kubernetes](https://giantswarm.io/product/)
  - [Google Kube-Up](https://github.com/kubernetes/kubernetes/tree/master/cluster)
  - [Heptio Quickstart for Kubernetes](https://aws.amazon.com/quickstart/architecture/heptio-kubernetes/)
  - [IBM Cloud Private](https://www.ibm.com/cloud-computing/products/ibm-cloud-private/)
  - [inwinSTACK kube-ansible](https://github.com/inwinstack/kube-ansible)
  - [Joyent Triton for Kubernetes](https://www.joyent.com/triton/compute)
  - [kube-spawn](https://github.com/kinvolk/kube-spawn)
  - [Kublr](https://kublr.com/)
  - [Loodse Kubermatic](https://cloud.kubermatic.io/)
  - [Mesosphere Kubernetes on DC/OS](https://mesosphere.com/kubernetes/)
  - [Mirantis Cloud Platform](https://www.mirantis.com/software/kubernetes/)
  - [Netease Container Service Dedicated](https://www.163yun.com/product/container-service-dedicated)
  - [OpenShift](https://www.openshift.com/)
  - [Oracle Linux Container Services](https://blogs.oracle.com/linux/announcing-oracle-linux-container-services-for-use-with-kubernetes)
  - [Oracle Terraform Kubernetes Installer](https://github.com/oracle/terraform-kubernetes-installer)
  - [Pivotal Container Service (PKS)](https://pivotal.io/platform/pivotal-container-service)
  - [Platform9 Managed Kubernetes](https://platform9.com/managed-kubernetes/)
  - [QFusion](http://www.woqutech.com/product.html)
  - [Rancher](https://rancher.com/)
  - [Samsung Kraken](https://samsung-cnct.github.io/)
  - [StackPointCloud](https://stackpoint.io/)
  - [SUSE CaaS Platform](https://www.suse.com/products/caas-platform)
  - [Tectonic](https://coreos.com/tectonic)
  - [VMWare Pivotal Container Service (PKS)](https://www.vmware.com/radius/pivotal-container-services/)
  - [Weaveworks kubeadm](https://kubernetes.io/docs/setup/independent/create-cluster-kubeadm/)
  - [WiseCloud](http://www.wise2c.com/solution)
  - [Typhoon](https://typhoon.psdn.io/)
          
- Certified Kubernetes - Platform
  - [Alauda EE](http://www.alauda.cn/product/detail/id/144.html)
  - [Alibaba Cloud Container Service](https://www.alibabacloud.com/product/container-service?spm=a3c0i.7911826.709257.dproducta4.1010a3feFbGgBW)
  - [Azure (ACS) Engine](https://github.com/Azure/acs-engine)
  - [Azure Container Service (AKS)](https://azure.microsoft.com/en-us/services/container-service/)
  - [Baidu Cloud Container Engine](https://cloud.baidu.com/product/cce.html)
  - [BoCloud BeyondcentContainer](http://bocloud.com.cn/product_container.html)
  - [Cisco Container Platform](https://www.cisco.com/c/en/us/products/cloud-systems-management/container-platform/index.html)
  - [EasyStack Kubernetes Service (EKS)](https://easystack.cn/eks/)
  - [eKing Cloud Container Platform](http://www.haihangyun.com/landing)
  - [Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine/)
  - [HarmonyCloud Container Platform](http://harmonycloud.cn/)
  - [Hasura](https://hasura.io/)
  - [Huawei Cloud Container Engine (CCE)](https://www.huaweicloud.com/en-us/product/cce.html)
  - [IBM Cloud Container Service](https://console.bluemix.net/docs/containers/cs_ov.html#cs_ov)
  - [Nirmata Managed Kubernetes](https://www.nirmata.com/)
  - [Oracle Container Engine](https://cloud.oracle.com/containers/engine/features)
  - [SAP Certified Gardener](https://cloudplatform.sap.com/index.html)
  - [Tencent Cloud Container Service (CCS)](https://cloud.tencent.com/product/ccs?lang=en)
  - [TenxCloud Container Engine (TCE)](https://tenxcloud.com/enterprise.html)
  - [ZTE TECS](https://sdnfv.zte.com.cn/en/products/126)  

- Non-Certified Kubernetes
  - [Amazon Elastic Container Service for Kubernetes (EKS)](https://aws.amazon.com/eks/)
  - [Cloud 66 Maestro](https://www.cloud66.com/containers/maestro)
  - [Containership](https://containership.io/)
  - [Gravitatonal Telekube](https://gravitational.com/telekube/)
  - [Huawei FusionStage](http://e.huawei.com/us/solutions/technical/cloud-computing)
  - [Navops](https://www.navops.io/)
  - [Supergiant](https://supergiant.io/)
  - [goPaddle](https://www.gopaddle.io/#/)
  - [Stratoscale Symphony](https://www.stratoscale.com/products/symphony/)
  
- PaaS & Container Service
  - [Apcera](https://www.apcera.com/) - Ericsson is a technology company that provides and operates telecommunications networks, television and video systems, and related services.
  - [Cloud Foundry Application Runtime](https://www.cloudfoundry.org/application-runtime/) - Cloud Foundry Application Runtime utilizes containers as part of its DNA, and has since before Docker popularized containers. The new CF Container Runtime gives you more granular control and management of containers with Kubernetes.
  - [Datawire](https://www.datawire.io/) - An early stage startup that's focused on making it easy for developers to build resilient microservices.
  - [Exoscale](https://www.exoscale.ch/) - Exoscale is the cloud hosting platform for SaaS companies, developers and systems administrators.
  - [Galactic Fog](http://www.galacticfog.com/) - Build Future-Proof Applications. Simplify integration. Run applications anywhere. Adapt to changes instantly.
  - [Heroku](https://www.heroku.com/) - Salesforce is a global cloud computing company that develops CRM solutions and provides business software on a subscription basis.
  - [Atomist](Atomist) - Atomist make microservice applications Easy and fun to build, through a cloud-based service.
  - [Clouber](https://www.clouber.io/) - Clouber is a provider of mCenter, an Application Modernization/Migration / Management platform across hybrid (public and private) clouds.
  - [Convox](https://convox.com/) - Launch a Private Cloud in Minutes.
  - [Empire](http://engineering.remind.com/) - A PaaS built on top of Amazon EC2 Container Service (ECS)
  - [Flynn](https://flynn.io/) - A next generation open source platform as a service (PaaS
  - [Hyper](https://www.hyper.sh/) - Hyper.sh is a secure container cloud service.
  - [JHipster](https://www.jhipster.tech/) - Open Source application generator for creating Spring Boot + Angular projects in seconds!
  - [Kontena](https://kontena.io/) - The developer friendly container and micro services platform. Works on any cloud, easy to setup, simple to use.
  - [Lightbend](https://www.lightbend.com/) - Lightbend (formerly Typesafe) is dedicated to helping developers build Reactive applications on the JVM.
  - [No Code](https://github.com/kelseyhightower/nocode) - The best way to write secure and reliable applications. Write nothing; deploy nowhere.
  - [PaaSTA](https://github.com/Yelp/paasta) - An open, distributed platform as a service
  - [Platform.sh](https://platform.sh/) - Platform.sh is an automated, continuous-deployment high-availability cloud hosting solution
  - [Portainer](https://portainer.io/) - Simple management UI for Docker
  - [Scalingo](https://scalingo.com/) - Scalingo a Docker Platform Service Transform your code as Docker container & run it on our cloud, making it instantly available & scalable.
  - [Tsuru](https://tsuru.io/) - Open source, extensible and Docker-based Platform as a Service (PaaS).

## Serverless

- Security
  - [PureSec](https://www.puresec.io/) - PureSec is the world's leading Serverless Security Runtime Environment
  - [Snyk](https://snyk.io/) - Snyk is a security company helping to monitor app vulnerabilities.
  
- Libraries
  - [Python Lambda](https://aws.amazon.com/lambda/) - A toolkit for developing and deploying serverless Python code in AWS Lambda.

- Tools
  - [Architect](https://arc.codes/) - 🔑 cloud function signatures for http handlers, pubsub, scheduled functions and table triggers
  - [Dashbird](https://www.dashbird.io/) - AWS Lambda monitoring & debugging platform. Serverless observability & troubleshooting. Serverless monitoring.
  - [IOpipe](https://www.iopipe.com/) - IOpipe provides a toolbox for developing, monitoring, and operating serverless applications.
  - [Microcule](https://github.com/Stackvana) - SDK and CLI for spawning streaming stateless HTTP microservices in multiple programming languages
  - [Node Lambda](https://github.com/motdotla/node-lambda) - Command line tool to locally run and deploy your node.js application to Amazon Lambda
  - [Stackery](https://www.stackery.io/) - Run serverless in production with Stackery's serverless operations console.
  - [Thundra](https://www.thundra.io/) - IT Alert and Notifications Management
  
- Frameworks
  - [AWS Chalice](https://github.com/aws/chalice) - Python Serverless Microframework for AWS
  - [SAM Local](https://github.com/awslabs/serverless-application-model) - AWS Serverless Application Model (AWS SAM) prescribes rules for expressing Serverless applications on AWS.
  - [Serverless](https://serverless.com/) - Serverless Framework – Build web, mobile and IoT applications with serverless architectures using AWS Lambda, Azure Functions, Google CloudFunctions & more! 
  - [Spring Cloud Function](https://cloud.spring.io/spring-cloud-function/) - Pivotal is a software company that provides digital transformation technology and services.
  - [Apex](http://apex.run/) - Build, deploy, and manage AWS Lambda functions with ease (with Go support!).
  - [Bustle Shep](https://www.bustle.com/labs) - A framework for building JavaScript Applications with AWS API Gateway and Lambda
  - [ClaudisJS](https://claudiajs.com/) - Deploy Node.js projects to AWS Lambda and API Gateway easily
  - [Dawson](https://github.com/dawson-org) - A serverless web framework for Node.js on AWS (CloudFormation, CloudFront, API Gateway, Lambda)
  - [Flogo](http://flogo.io/) - Ultralight Edge Microservices Framework
  - [Gordon](http://jorgebastida.com/) - λ Gordon is a tool to create, wire and deploy AWS Lambdas using CloudFormation
  - [GunIO Zappa](https://www.zappa.io/) - Serverless Python
  - [KappaIO](https://github.com/garnaat/kappa) - What precedes Lambda 
  - [Mitoc Group Deep](https://docs.deep.mg/) - Full-stack JavaScript Framework for Cloud-Native Web Applications (perfect for Serverless use cases)
  - [Sparta](https://gosparta.io/) - A GO FRAMEWORK FOR AWS LAMBDA 
  
- Platforms

  CNCF Member Products/Projects 
  - [AWS Lambda](https://aws.amazon.com/lambda/) - Amazon Web Services provides information technology infrastructure services to businesses in the form of web services.
  - [Azure Functions](https://azure.microsoft.com/en-us/services/functions//) - Microsoft is a software corporation that develops, manufactures, licenses, supports, and sells a range of software products and services.
  - [Google Cloud Functions](https://cloud.google.com/functions/) - https://cloud.google.com/functions/
  - [IBM Cloud Functions](https://console.bluemix.net/openwhisk/) - IBM is an IT technology and consulting firm providing computer hardware, software, and infrastructure and hosting services.
  - [Twilio Functions](https://www.twilio.com/functions) - Twilio is a cloud communication company that enables users to use standard web languages to build voice, VoIP, and SMS apps via a web API.
  
  Non-CNCF Member Products/Projects
  - [Algorithmia](https://algorithmia.com/serverless-ai-layer) - Algorithmia is an open marketplace for algorithms, enabling developers to create tomorrows smart applications today.
  - [Apache OpenWhisk](https://openwhisk.apache.org/) - Apache OpenWhisk is a serverless event-based programming service and an Apache Incubator project.
  - [AppScale](https://www.appscale.com/) - AppScale is an easy-to-manage serverless platform for building and running scalable web and mobile applications on any infrastructure.
  - [Clay](https://www.clay.run/) - Rapid Prototyping for Developers
  - [Hyper Func](https://docs.hyper.sh/Feature/container/func.html) - Hyper.sh is a secure container cloud service.
  - [Iron.io](https://www.iron.io/) - Iron.io is a scalable cloud-based message queue and processing platform for building distributed cloud applications.
  - [Nano Lambda](http://nano-lambda.com/) - Explore deploying code in lambda.Run server-side code with an API call.
  - [Overclock](https://www.ovrclk.com/) - Overclock Labs develops protocols, tools, and infrastructure to make foundational elements of the internet open, decentralized, and simple
  - [OVH Functions](https://labs.ovh.com/ovh-functions) - OVH.com is an independent French company that offers web, dedicated, and cloud hosting solutions.
  - [PubNub Functions](https://www.pubnub.com/products/functions/) - The PubNub Data Stream Network enables mobile and web developers to build and scale realtime apps.
  - [Spotinst Functions](https://spotinst.com/products/spotinst-functions/) - Our SaaS optimization platform delivers significant cost reduction for AWS and GCE, while maintaining high availability and performance.
  - [StdLib](https://stdlib.com/) - StdLib Service Creation, Deployment, and Management Tools
  - [Syncano](https://syncano.io/#/) - A serverless application platform to build powerful realtime apps more efficiently.
  - [Weblab](https://weblab.io/) - Microservices at your fingertips
  - [Webtask](https://webtask.io/) - Webtasks is a simple, lightweight, and secure way of running isolated backend code that removed or reduces the need for a backend.
  - [Zeit Now](https://zeit.co/now) - Now – Realtime Global Deployments
            
- Hybrid Platforms
  - [Galactic Fog Gestalt](http://www.galacticfog.com/product/) - Build Future-Proof Applications. Simplify integration. Run applications anywhere. Adapt to changes instantly.
  - [Nuclio](https://nuclio.io/) - High-Performance Serverless event and data processing platform
  - [Binaris](https://www.binaris.com/) - A high-performance serverless platform for interactive and real-time applications.
  - [Cloudboost](https://www.cloudboost.io/) - One Complete NoSQL Database Service for your app.
  - [Fn](https://fnproject.io/) - The container native, cloud agnostic serverless platform.
  - [fx](https://minghe.me/) - fx is a tool to help you do Function as a Service with painless on your own servers
  - [LunchBadger](https://www.lunchbadger.com/) - LunchBadger is a multi-cloud platform for microservices and serverless.        
  
- Kubernetes-Native Platforms
  - [Fission](https://fission.io/) - Fast Serverless Functions for Kubernetes
  - [Oracle Application Container Cloud](https://cloud.oracle.com/acc) - Oracle is a computer technology corporation developing and marketing computer hardware systems and enterprise software products.
  - [Riff](https://projectriff.io/) - riff is for functions
  - [Funktion](https://funktion.fabric8.io/) - a CLI tool for working with funktion
  - [Kubeless](http://kubeless.io/) - Kubernetes Native Serverless Framework
  - [OpenFAAS](https://www.openfaas.com/) - OpenFaaS - Serverless Functions Made Simple for Docker & Kubernetes
  - [OpenLambda](https://open-lambda.org/)  -  An open source serverless computing platform
  - [PubNub](https://www.pubnub.com/docs/blocks-catalog) - The PubNub Data Stream Network enables mobile and web developers to build and scale realtime apps.
  
## Observability & Analysis

- Monitoring

  CNCF Member Products/Projects 
  - [Prometheus](https://prometheus.io/) - The Prometheus monitoring system and time series database.
  - [Amazon CloudWatch](https://aws.amazon.com/cloudwatch/) - Amazon Web Services provides information technology infrastructure services to businesses in the form of web services.
  - [Datadog](https://www.datadoghq.com/) - Datadog offers a cloud-scale monitoring service.
  - [Dynatrace](https://www.dynatrace.com/) - Dynatrace transform how Web and non-Web business-critical applications are monitored, managed, and optimized throughout their lifecycle.
  - [Google Stackdriver](https://cloud.google.com/stackdriver/) - Google is a multinational corporation that is specialized in internet-related services and products.  
  - [Grafana](https://grafana.com/) - The tool for beautiful monitoring and metric analytics & dashboards for Graphite, InfluxDB & Prometheus & More
  - [InfluxDB](https://www.influxdata.com/) - Scalable datastore for metrics, events, and real-time analytics
  - [Instana](https://www.instana.com/) - Instana is an APM solution that automatically monitors dynamic modern apps.
  - [Lighstep](https://lightstep.com/) - LightStep's mission is to cut through the scale and complexity of today's software to help organizations stay in control of their systems.
  - [Log Analytics](https://azure.microsoft.com/en-us/services/log-analytics/) - Microsoft is a software corporation that develops, manufactures, licenses, supports, and sells a range of software products and services.
  - [Netsil](https://netsil.com/) - Observability and Monitoring for Modern Cloud Applications
  - [SignalFX](https://signalfx.com/) - Advanced monitoring platform for modern applications
  - [Snap](https://snap-telemetry.io/) - A powerful open telemetry framework.Easily collect, process, and publish telemetry data at scale.
  - [SysDig](https://sysdig.com/) - Linux system exploration and troubleshooting tool with first class support for containers
  - [Weave Cloud](https://www.weave.works/product/cloud/) - Weaveworks provides a simple and consistent way to connect and manage containers and microservices.
  
  Non-CNCF Member Products/Projects
  - [AppDynamics](https://www.appdynamics.com/) - AppDynamics develops application performance management (APM) solutions that deliver problem resolution for highly distributed applications.
  - [AppNeta](https://www.appneta.com/) - AppNeta is the only app performance monitoring company with solutions for apps you develop, SaaS apps you use & networks that deliver them.
  - [Axibase](https://axibase.com/) - Purpose-built solution for analyzing and reporting on massive volumes of time-series data collected at high frequency.
  - [Catchpoint Systems](https://www.catchpoint.com/) - Catchpoint is a leading digital experience intelligence company.
  - [Centreon](https://www.centreon.com/en/) - Centreon is a network, system, applicative supervision and monitoring tool.
  - [Cobe](https://cobe.io/) - Cobe delivers an aggregated view of every element related to your business.
  - [CoScale](https://www.coscale.com/) - Full stack performance monitoring. Built for container and microservices applications. Powered by anomaly detection.
  - [Graphite](https://graphiteapp.org/) - A highly scalable real-time graphing system
  - [Honeybadger](https://www.honeybadger.io/) - Exception, uptime, and performance monit.
  - [Icinga](https://www.icinga.com/) - Monitoring as code
  - [IronDB](https://www.circonus.com/irondb/) - Realtime Monitoring and Analytics
  - [Librato](https://www.librato.com/) - Real time operations analytics for metrics from any source
  - [Meros](https://meros.io/) - Meros is creating enterprise monitoring and management tools for Docker
  - [Nagios](https://www.nagios.com/) - The Industry Standard In IT Infrastructure Monitoring.
  - [New Relic](https://newrelic.com/) - New Relic is a leading digital intelligence company, delivering full-stack visibility and analytics to enterprises around the world.
  - [NodeSource](https://nodesource.com/) - Building products focused on Node.js security and performance for the Enterprise.
  - [OpBeat](https://opbeat.com/) - Opbeat is joining forces with Elastic.
  - [OpenTSDB](http://opentsdb.net/) - A scalable, distributed Time Series Database.
  - [OpsClarity](https://www.opsclarity.com/) - Intelligent Monitoring for Modern Applications and Data Infrastructure
  - [Outlyer](https://www.outlyer.com/) - Infrastructure monitoring platform made for DevOps and microservices.
  - [Rocana](https://www.rocana.com/) - Rocana is a San Francisco, CA-based provider of root cause analysis software company
  - [Sensu](https://sensuapp.org/) - Monitoring for today's infrastructure.
  - [Sentry](https://sentry.io/) - Sentry is a cross-platform crash reporting and aggregation platform.
  - [Server Density](https://www.serverdensity.com/) - Monitoring agent for Server Density (Linux, FreeBSD and OS X)
  - [StackRox](https://www.stackrox.com/) - StackRox delivers the industry's only adaptive threat protection for containers.
  - [StackState](https://www.stackstate.com/) - The market-leading Algorithmic IT Operations platform
  - [Tingyun](http://www.tingyun.com/tingyun_app.html) - Observability and Analysis, Monitoring
  - [Wavefront](https://www.wavefront.com/) - Wavefront is a hosted platform for ingesting, storing, visualizing and alerting on time series data.
  - [Zabbix](https://www.zabbix.com/) - The Ultimate Enterprise - class Monitoring Platform  
    
- Logging

  - [Fluentd](https://www.fluentd.org/) - Fluentd: Unified Logging Layer (project under CNCF)
  - [Humio](https://www.humio.com/) - Log everything, answer anything
  - [Splunk](https://www.splunk.com/) - Splunk provides operational intelligence software that monitors, reports, and analyzes real-time machine data.
  - [Elastic](https://www.elastic.co/) - Open Source, Distributed, RESTful Search Engine.
  - [Graylog](https://www.graylog.org/) - Free and open source log management
  - [Loggly](https://www.loggly.com/) - Loggly parses your log files, shows you the code in GitHub which caused the log errors. 10,000+ customers, including 1/3 of the Fortune 500.
  - [Logz](https://logz.io/) - Logz.io is an enterprise-grade ELK as a service with alerts, unlimited scalability, and predictive fault detection.
  - [Loom Systems](https://www.loomsystems.com/) - Predict & Prevent Problems in the Digital Business
  - [Sematext](https://sematext.com/) -  Sematext is a Search and Big Data analytics products and services company.
  - [Sumo Logic](https://www.sumologic.com/) - Sumo Logic, a log management and analytics service, transforms big data into sources of operations, security and compliance intelligence.

- Tracing

  - [Jaeger](http://jaegertracing.io/) - CNCF Jaeger, a Distributed Tracing System
  - [OpenTracing](http://opentracing.io/) - OpenTracing API for Go
  - [Spring Cloud Sleuth](https://cloud.spring.io/spring-cloud-sleuth/) - Distributed tracing for spring cloud
  - [Appdash](https://github.com/sourcegraph/appdash) - Application tracing system for Go, based on Google's Dapper.
  - [SkyWalking](http://skywalking.io/) - A distributed tracing system, and APM ( Application Performance Monitoring )
  - [Zipkin](https://zipkin.io/) - Zipkin is a distributed tracing system
 

## Contribute

Contributions are most welcome, please adhere to the [contribution guidelines](Contributing.md).

**[⬆ back to top](#components)**

## MIT License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

This project is licensed with MIT [MIT LICENSE](https://choosealicense.com/licenses/mit/#).