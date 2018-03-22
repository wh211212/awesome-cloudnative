# <img src="https://raw.githubusercontent.com/wh211212/Cloud-Native/master/Images/cloudnativelog.png" width="500" alt="Cloud Native">

[![jaywcjlove/sb](https://jaywcjlove.github.io/sb/lang/chinese.svg)](README-cn.md)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> An awesome & curated list of best applications and tools for Cloud Native.

> This Awesome Repository is highly inspired from cncf's [landscape](https://github.com/cncf/landscape) & [Awesome](https://github.com/Awesome-Windows/Awesome).

> *Items marked with ![Open-Source Software][OSS Icon] are open-source software. Items marked with ![Freeware][Freeware Icon] are free.*

# <img src="https://raw.githubusercontent.com/wh211212/Cloud-Native/master/Images/cloudnativelog.png" width="500" alt="Cloud Native">

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

  CNCF Member Products/Projects
  - []()
  - []()
  - []()
	                  
- Application Definition
- CI & CD


	
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


## Contribute

Contributions are most welcome, please adhere to the [contribution guidelines](Contributing.md).

**[⬆ back to top](#applications)**


## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
