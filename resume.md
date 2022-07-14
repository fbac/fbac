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

<img style="float: left;  margin-right: 20px;" src="avatar.jpg" width="150" height="150">

I'm a Software Engineer who is driven by curiosity with a great passion towards technology and Open Source projects.

My strongest qualities are; being passionate about Computer Sciences, incredibly curious and having the constant need of developing my skills to new highs. I'm always eager to work in fast-paced environment where learning new skills along the way is a must. And finally, I'm an avid reader of books/documentation/RFC's and, luckily enough, a very fast learner.

I consider myself analytical, a hard-worker and a team player who loves to work with smart and curious people.

[[fbac.dev]](https://fbac.dev) [[github]](https://github.com/fbac) [[linkedin]](https://www.linkedin.com/in/fbac/)

## My skill set

- **Operating Systems**
  - Strong foundations in Computer Sciences and OS architectures/design.
  - Experience building simple kernel modules and debugging kernel issues.
  - Packaging (rpm, deb).
  - Experience with linux linkers and libraries, ld, elf (and dwarf) formats and low-level basic knowledge.
  - Debugging performance issues using perf.P{}
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
    - Debugging issues of every kind, from application malfunctions, discover bugs at any point (container runtime, apps, OS, etc.) to performance issues.
  - Knowledgeable in distributed systems theory and consensus algorithms.

- **Development**
  - My strongest language is golang.
    - Secondary languages are python and C.
    - Middle experienced in assembly, node.js and java.
    - Some knowledge in html, javascript, css.
  - In the near future I'll develop my Rust skills.
  - Experience with cmake, automake and llvm.
  - Experience debugging with gdb and delve.
  - I've developed my own kernel modules (from the initial hello_world.ko to modules catching keystrokes), and some IoT experiments.
  - Contributed to Kubernetes, OpenShift, openshift-sdn, OpenShift HAProxy Ingress Router and some other repositories.
  - Using git on a daily basis, working with big teams where the git workflow is fine-grained and important to follow.
  - Strong foundations in algorithms and data structures.
  - Knowledgeable in operating systems theory.
  - Knowledgeable in low level systems design to achieve optimal performance and low memory footprints in the programs I write.

- **CI/CD**
  - Experienced in CI/CD tools, such as:
    - Github Actions
    - Prow
    - Jenkins
    - Tekton, as part of Kubernetes CI/CD pipelines.
  - Experience in creating testing suites, unit test and pipelines for the products/tools I'm involved in developing.

- **Automation**
  - Configuration management with puppet.
  - Experience automating with ansible, saltstack and chef.
  - Infrastructure as a Service with Terraform.
    - Used as a cli and also as an import in go applications.

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
