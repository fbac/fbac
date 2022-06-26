# Francisco de Borja Aranda Castillejo

## Contents
- [Francisco de Borja Aranda Castillejo](#francisco-de-borja-aranda-castillejo)
  - [Contents](#contents)
  - [Who am I?](#who-am-i)
  - [My skill set](#my-skill-set)
  - [Certifications](#certifications)
  - [Studies](#studies)
- [Experience](#experience)
  - [[Red Hat] Recent and present roles (2016+)](#red-hat-recent-and-present-roles-2016)
    - [Principal Software Engineer (Jan 2021 - present)](#principal-software-engineer-jan-2021---present)
    - [Principal Software Maintenance Engineer (Jul 2020 - Jan 2021)](#principal-software-maintenance-engineer-jul-2020---jan-2021)
    - [Platform Consultant (Feb 2016 - Nov 2017)](#platform-consultant-feb-2016---nov-2017)
  - [Older positions (2008-2016)](#older-positions-2008-2016)

## Who am I?

<img style="float: left;" src="avatar.jpg" width="200" height="200">

```bash
I'm a Software Engineer who is passionate about technology and how to talk with computers at the lowest level.
And weirdly enough, I enjoy reading RFC to *really* understand how current computers and standards are built.

I enjoy working from low level projects for operating systems, networking to contributing to modern projects such as Kubernetes, OpenShift... in general everything that represents a challenge and growing. 
Developing my skills is a constant, and I have strong foundations in computer sciences, operating systems and networking, and I'm always aiming for more knowledge.

In my career I've worked as Linux System Administrator, Software Engineer, Consultant, and I've always loved working with linux and open-source technologies. I'm a hard-worker, maybe a bit obsessive and inquisitive when it comes to find why and how "something" is doing "something". 
And I'm always eager to just jump on the documentation until I'm capable of understanding and debugging whatever I have in front of me, even if it's an embedded system, a network protocol or a piece of code.

I code in a variety of languages such as C, go, python and java, and I have scripting skills in good old bash. 
My most used language is golang as it's the language I'm using the most currently. But also I really enjoy coding in C (it's just... awesome) and lately I'm really interested in Rust, learning it and I'll look for projects written in it to contribute in the future.
```

## My skill set

- **Operating Systems**
  - Strong foundations in Computer Sciences and OS architectures/design.
  - Experience building simple kernel modules and debugging kernel issues.
  - Packaging (rpm, deb).
  - Experience with linux linkers and libraries, ld, elf (and dwarf) formats and low-level basic knowledge.
  - Debugging performance issues using perf.
  - Experience debugging application performance with HeatMap and FlameGraph.
  - Little/mid experience with systemtamp and basic ebpf tools. (I'm really interested on this field right now)
  - Deep understanding in container runtimes, docker daemon and the OCI Runtime Specification (and associated repositories)
    - Focused in cri-o, podman, skopeo and buildah.
  - Experiece with storage and distributed storage, such as Ceph and Gluster.
  - Virtualization with kvm on daily basis.
  - Experience working with databases:
    - Relational: postgresql and mysql.
    - key-value: etcd and redis.
  
- **Networking**

  - Strong foundations in tcp/ip stack, specially L4 - L7.
  - Linux networking stack and understating of netfilters, capable of debugging low level issues at OS level.
  - Experience implementing and configuring many protocols such as dns, dhcp, pxe, http/s and many other basic protocols.
  - Experience with cloud loadbalancers (AWS, GCE, OpenStack) and many other networking services such as haproxy, httpd, nginx, memcached and varnish.
  - SDN experience with openshift-sdn and ovn-kubernetes.
  - Understanding of openvswitch and openflow.
  - Experience with certificates and CA's, tls, openssl.

- **Distributed Systems**
  - Deep experience with Kubernetes and OpenShift.
    - Creating scalable and resilient architectures with disaster recovery, backup plans, documented day 2 operations, etc.
    - Installing, configuring, managing such platforms and applications on top on that.
    - Debugging issues of every kind, from malfunctions to performance issues.

- **Development**
  - My strongest language is golang.
    - Secondary languages python and C.
    - Little experienced in java and node.js, and even assembly.
    - Knowledge in html, javascript, css... sometimes I do some frontend stuff.
  - In the near future I plan to start developing in Rust. (soon!)
  - Experience with cmake, automake and llvm.
  - Experience debugging with gdb and delve.
  - In the past, as fun personal projects I've developed my own kernel modules (from the initial hello_world.ko to modules catching keystrokes), some IoT experiments
  - Contributed to Kubernetes, OpenShift, openshift-sdn, OpenShift HAProxy Ingress Router and some other repositories.
  - Using git on a daily basis, working with big teams where the git workflow is fine-grained and important to follow.
  - Strong foundations in algorithms, data structures and computer sciences to achieve better results and more performant applications.

- **CI/CD**
  - Experienced in many tools, such as:
    - Github Actions
    - Prow
    - Jenkins
    - Tekton, as part of Kubernetes CI/CD pipelines.
  - Experience in creating testing suites, unit test and pipelines for the products/tools I'm involved in developing.

- **Automation**
  - configuration management with puppet.
  - experience automating with ansible, saltstack and chef.

## Certifications

- [Certified Kubernetes Administrator](https://training.linuxfoundation.org/certification/verify/)
  - ID: LF-sw1tb6myak

- [Red Hat Certifications](https://rhtapps.redhat.com/verify/?certId=140-120-114) ID: 140-120-114
  - Red Hat Certified System Administrator
  - Red Hat Certified Engineer
  - Red Hat Certificate of Expertise in Configuration Management
  - Red Hat Certified Specialist in OpenShift Administration
  - Red Hat Certified Specialist in Containerized Application Development
  - Red Hat Certified Specialist in Ceph Storage Administration
  - Red Hat Certified in Ansible Automation
  - Red Hat Certified Architect

- CCNA: Cisco Certified Networking Administrator

## Studies

- (2006 - 2008) I.E.S Politécnico Jesús Marín [ Computer Sciences Superior Degree on Systems Administration](https://politecnicomalaga.com/oferta-educativa/formacion-profesional/administracion-de-sistemas-informaticos-en-red)

- (2017 - 2022) [Universitat Oberta de Catalunya](https://www.uoc.edu/portal/en/index.html) - Computer Sciences Bachelor's Degree -
  - currently studying: it's almost finished.
  - the final project for getting the degree will be a "toy" programming language and its own compiler.

# Experience

## [Red Hat] Recent and present roles (2016+)

### Principal Software Engineer (Jan 2021 - present)

```bash
[*] Responsabilities:
- Creating products for Red Hat:
    - Quality, performance and resiliency are top priorities.
    - Integrating many products to achieve the stakeholders desired results.

- Currently working on a newborn open source product, which has achieved the minimum viable product as a set of devscripts in bash, and that will be refactored in go. 
For this task, the Principal Software Engineer role is needed to have an architectural vision on how the product will be based on Product Management spectations and roadmap.
    - Owners of the product: everything is thought and designed from the ground-up by the team, we are the owners and the builders.
    - The final golang architecture is designed and owned by us.
    - Aiming to have a pluggable and resilient Kubernetes Operator, written in go.

- Everything is built by the team.
    - Heavy usage of virtualization, baremetal hosts and kvm.
    - Networking created, configured and managed from the ground-up.
    - CI/CD based in github actions and tekton pipelines.
        - Introducin prow soon to achieve better results.
    - git workflow, branching and release model created by us to achieve a resilient workflow for a mid/large team in the future.
```

### Principal Software Maintenance Engineer (Jul 2020 - Jan 2021)

```bash
Before Principal Software Maintenance Engineer:
    - Senior Software Maintenance Engineer (Oct 2018 - Jun 2020)
    - Software Maintenance Engineer (Nov 2017 - Oct 2018)
```

```bash
[*] Responsabilities:

- Debugging complex issues to help customers using OpenShift and Kubernetes.
    - Issues can be anywhere from networking, to kernel, firmware, hardware to operating system or application stack.
    - Heavy usage of perf, heatmaps, ebpf and systemptap scripts.
    - Heavy usage of gdb to debug goroutines when needed, specially during container runtimes debugging.
    - Shipping my own custom binaries in container images to debug complex parts of the code on-site with the customer.

- Specialized in debugging issues in Openshift-SDN, kernel, container runtimes and networking.
    - Heavy usage of tshark, wireshark and many basic networking tools.

- Heavy usage and deep understanding of OpenShift, Kubernetes, k3s, podman, crictl, docker.

- go: bugfixing and feature backporting from main branches to supported stable branches, for different components such as OpenShift and openshift-sdn or ovn-kubernetes.

- Installation and configuration of OpenShift clusters, CI/CD, OS and the full stack.

- Deployment, managing and debugging of services on top of OpenShift.
```

### Platform Consultant (Feb 2016 - Nov 2017)

```bash
Main mission:

- Install, configuration and managing of high quality complex distributed systems.
  - Focused in Red Hat products, mainly OpenShift, RHEL, OpenStack, Satellite, Ceph.
- Installation and configuration of OpenShift and Kubernetes clusters.
- Installation and configuration of applications on top of OCP / Kubernetes.
- Enabling CI/CD and automation to create productive development environments.
- Automating tasks, from provisioning to service configuration, through ansible and puppet.
- Developing tools and scripts in python and golang.
- Debugging complex issues at OS, kernel, network or Kubernetes level.
```

## Older positions (2008-2016)

```bash
DevOps Engineer @ BQ (Jun 2015 - Jan 2016)
Linux System Administrator @ Telefónica de España (Jun 2012 - Jun 2015)
Linux System Administrator @ IBM (Jan 2012 - Jun 2012)
Linux System Administrator @ BBVA (Aug 2011 - Dec 2011)
Linux System Administrator @ Ingenia (Sep 2008 - Aug 2010)
(Internship) Linux System Administrator @ Ingenia (Mar 2008 - Jun 2008)
```

More information about older positions in [my linkedin](https://www.linkedin.com/in/fbac/).
