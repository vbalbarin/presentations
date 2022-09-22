---
marp: true
theme: default
size: 16:9
_class: lead
paginate: true
backgroundColor: #fff
style: |
    section{
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


footer: '![wl_footer](https://github.com/vbalbarin/presentations/raw/main/wright-laboratory-computing-overview/assets/WL_Footer.png)'

---

# **Wright Laboratory Computing Overview**

Vincent Balbarin
September 19, 2022

---

## On-premises Computing

- Linux servers associated with specific groups and collaboration teams
- Workstations in laboratories
- Personal devices

<!--
Speaker's notes:
- The WL servers have publicly accessible IP addresses.
- They support SSH login only.
- Computation and storage
- Please contact me for access
-->
---

## Yale Center for Research Computing

- The YCRC is an independent center that manages and maintains HPC systems for high throughput parallel processing
-  Many of the WL research community will use the Grace cluster, which is distributed over >900 nodes with access to >4 PB parallel storage
- Accounts are available to all researchers. Please contact me for more information.

---

## Yale University ITS Access to Public Cloud Platforms

- Integration with university identity--CAS/Shibboleth or Microsoft Azure AD
- Enterprise agreement and business agreement backing
- Private network connections from on-premises networks to cloud virtualnetworks
- Access to platform services such as machine learning, hpc, cognitive services
- Support for the three primary public clouds

---

## Data Storage

- Local network accessible storage
- Storage@Yale tiered storage
- Google Shared Drives
- Cloud based object storage

---

## File Transfer Services

- Globus
   - Inter-institutional and intra-institutional file transfer
   - Identity based
   - Support for scheduled background
- `rsync` processes over Yale networks
- Currently evaluating Rucio Data and Storage Management

---

## Communication and Collaboration Platforms

- Slack
- Zoom
- EliApps (Google)
- Github
- Indico
- eLog
- DocDB
- Moin Wiki

---

## Workshops

- Introduction to Yale Spinup-Service and Cloud Computing
- Introduction to Git Workflow and Github
- Containerized Workloads with Docker and Podman
- Introduction to Cloud-based Data Analysis

---

## Support

- General computing support
- Hardware recommendations
- Assistance in obtaining Yale ITS support whenever appropriate
- Assitance with HPC through the YCRC
- Identity and access to computing resources
- Software installation and configuration

---

## Contact

- Electronically
   - The help-wlab@elilists.yale.edu distribution list
   - The `#computing` Slack channel in [wrightlab.slack.com](wrightlab.slack.com)
- In person at WL-235