---
marp: true
theme: default
size: 16:9

backgroundColor: #fff
style: |
    .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
    }

    section {
      justify-content: flex-start;
    }

    section::after {
      font-size: 0.6em;
      text-shadow: 1px 1px 0 #fff;
      left: 50%;
      transform: translateX(-50%);
      content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
    } 

    footer {
      bottom: 10px
    }


footer: '![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png)'


---

<div class="columns"><div>

# **Introduction to Yale Spinup and Cloud Computing**
Vincent Balbarin
September 27, 2022

</div><div>

![img w:450 h:450](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/wright-laboratory-spinup/yale_spinup_logo.png)

</div></div>


---
<!-- paginate: true -->
<style>
blockquote {
    border-top: 0.1em dashed #555;
    font-size: 60%;
    margin-top: 50px;
}
sup {
  font-size: 65%;
}
</style>

## Key Traits of Cloud Computing<sup>1</sup>

* Self-provisioning
* Shared
* Elastic/Ephemeral
* Accessible
* Metered

> 1. Peter Mell; Timothy Grance (September 2011). The NIST Definition of Cloud Computing (Technical report). National Institute of Standards and Technology: U.S. Department of Commerce.

<!-- 

notes:
. How are the traits different from previous computing paradigms?
. How is this any different from the servers at WL? A mainframe?

-->

---

## Implementation

* Identity and role-based access controls
* Policy
* Automated provisioning and configuration of workloads
* Wide area networks
* Service instrumentation

<!-- 

## notes:
* How does one implement this?
* How is this different from logging into Meitner?
* Declarative, not procedural

-->

----

## Yale Spinup

* Application layer over a shared AWS account
* Yale governance
  * CAS/Shibboleth identity
  * Enterprise and business agreement with Amazon
  * Automated creation and configuration adhering to institutional standards
  * Shared responsibility
* Enables self-service

<!-- 

notes:

. Spinup leverages institional identity.
. The enteprise and business agreement guarantees a s certain level of service and protection and a negotiated cost.
. Spinup implements reporting for usage, billing and chargback.
. Amazon offers many services which can be difficult to implement; automation makes commonly used ones easy to consume by configuring them to Yale standards. Shared responsibility
. We deploy resources only to pre-authorize regions (US East 1/N. Virginia)

-->

---

## Demonstration Spinup Web Application

[![spinup w:768px h:435px ](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/wright-laboratory-spinup/yale_spinup_login.png)](https://spinup.internal.yale.edu)

<!-- 

## notes:

. The portal can be reached from campus or VPN IP addresses
. CAS
. Demonstrate management features
. Demonstrate profile information and ssh key for owner.
. ** Important, users will be periodically requested to read the shared responsibility document **
. User home
   . Create Space
   . Create a Team
. New space. A space is a logical container for a set of related resources owned by the creator of that space.
. A team is a collection of users that can granted priveleges to a space.
. Overview of resources
. NB, at the service level only creator-owners have privileges, IE a Team member has the rights to create and delete servers. That person must explicity grant (useradd) at resource level.
. Go over some ot the tabs along the top.

-->

---

## Infrastructure as a Service (IaaS): Server Instances

* Virtual servers hosted in Amazon EC2
* Cost directly proportional to provisioned resource
* Only charged for uptime and storage
* Regular snapshots

---

## Demonstration: Spinup EC2 Instances

<!-- 

## notes:

. Select image, tryit
. Launch
. Show ssh
. Remind folks that only createor is root; must add others
. Best practice add another key
. Manage costs by deleting or shutting off instances
. Show snapshots.
. Remind folks that they are responsible for

-->

---

## Platform as a Service (PaaS): Databases

* Provisioned to clustered database environment or to a fully managed instance
* Backups fully managed
* No need for patching
* Support for common databases

---

## Demonstration: Spinup Database Services

---

## Storage

* S3 object storage
* NFS volumes through Amazon Elastic File System (EFS)
* Static websites

<!--

## notes:

. Talk about durability and availability; data can be spread across a region/regions
. Access via https
. NB, access keys should be cycled.
. Pay only for what you use
. Current cost for S3 12 USD/(500 GB * 30 days); for glacier 2 USD(500 GB * 30 days)
. NFS endpoints are available only to the space
. Storage grows and shrinks
. Policy to move less accessed data to cooler (less pricy storage)

-->

---

## Demonstration: Spinup Storage Services

---

## Containers

<div class="columns"><div>

* Isolation of application from host
* All dependencies encapsulated
* Achieve greater densitity and utilization
* Drawbacks
  * Complicated infrastructure
  * Orchestration of interrelated services
  * Stateless


</div><div>

![img w:528 h:400](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/wright-laboratory-spinup/mediawiki_containers.png)

</div></div>

<!-- 

notes:

. Docker and podman allow you to package up the runtime environment (OS components and application components).
. Each container is specific to a component--ie, database, middle tier, application.
. No need to patch or update. Specify new image and the orchestration takes down running container.
. Docker swarm lets you run on local system or instance--you have to maintain host
. Kubernetes is a complete solution that provides control plane for scalout of instances and takes care of orchestration and communication between components.

-->
---

## Demonstration: Spinup Container Services

<!--

. Test-API pattern
. Persistent volume
. Database as service
. Stateless application
. Stop and start and redploy

-->

---

## Conclusion

* Constitutes an ideal environment to learn cloud computing.
* Provides convenient and secured access to the AWS cloud.
* Provides a stepping-off point for the other clouds that Yale offers


---

## Resources

* [Yale Spinup Selfservice FAQ](https://yaleits.atlassian.net/wiki/spaces/spinup/pages/470614243/Spinup+Selfservice+FAQ)
* **#spinup** channel in [Yale University Slack](https://yale.slack.com/) 


