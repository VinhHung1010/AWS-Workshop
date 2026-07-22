---
title: "Week 4 Worklog"
date: 2026-05-11
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---



### Week 4 Objectives:

* Understand advanced Amazon S3 data architecture (Access Points, Storage Classes, CORS) and large-scale enterprise data migration mechanisms (Snow Family).
* Gain practical experience in automated cross-resource backups, seamless on-premises virtual machine (VM) migrations to AWS, and hybrid Storage Gateway integrations.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                         |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 17  | **Studied AWS Storage Optimization & Archival Concepts:** <br> - **Module 04-02:** Analyzed S3 Access Points and S3 Storage Classes (Standard, Intelligent-Tiering, Standard-IA, One Zone-IA, Glacier families) <br> - **Module 04-03:** Explored S3 Static Website hosting, CORS configs, Access Control mechanisms (IAM, Bucket Policies, ACLs), and object performance <br> - **Module 04-04:** Evaluated AWS Snow Family (Snowcone, Snowball Edge, Snowmobile), Storage Gateway architectures, and AWS Backup workflows | 11/5/2026 | 11/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 18  | **Completed Comprehensive AWS Backup Management Labs:** <br> - **Module 04-Lab13-02.1 & 02.2:** Created an S3 Bucket and deployed backend infrastructure for testing <br> - **Module 04-Lab13-03 to 06:** Configured Backup Plans (schedules, retention policies), set up notification alert metrics, tested structural data restore procedures, and cleaned up lab resources | 12/5/2026 | 12/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 19  | **Completed On-Premises to Cloud Virtual Machine Migration Labs:** <br> - **Module 04-Lab14-01 & 14-02.1:** Configured VMware Workstation and exported on-premises VMs <br> - **Module 04-Lab14-02.2 to 02.4:** Uploaded VM files to S3, imported VMs to AWS as custom AMIs via VM Import/Export services, and deployed functional EC2 nodes <br> - **Module 04-Lab14-03.1 to 05:** Configured S3 Bucket ACLs, practiced reverse EC2 instance exporting back to VM format, and executed thorough resource cleanup | 13/5/2026 | 13/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 20  | **Practiced and Consolidated Core VM Migration Workflows:** <br> - Reviewed and performed end-to-end hands-on migration labs (**Module 04-Lab14-02.1 to Module 04-Lab14-05**) <br> - Solidified proficiency in exporting local VMs, uploading disk files to S3 buckets, converting images to production-ready AMIs, configuring necessary S3 bucket ACL permissions, and tearing down temporary environments | 14/5/2026 | 14/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 21  | **Completed Hybrid Storage Gateway Connectivity Labs:** <br> - **Module 04-Lab24-2.1 & 24-2.2:** Initialized an AWS Storage Gateway appliance and provisioned hybrid File Shares <br> - **Module 04-Lab24-2.3 & 24-3:** Mounted cloud-backed file shares directly onto on-premises systems (SMB/NFS) and conducted rigorous environment resource cleanup protocols | 15/5/2026 | 15/5/2026 | https://cloudjourney.awsstudygroup.com/ |


### Week 2 Achievements:

* **Mastered advanced Amazon S3 data optimization and storage placement strategies**, learning to map distinct application request pathways via S3 Access Points and optimize infrastructure budgets using granular S3 Storage Classes—ranging from S3 Standard to deep archival Glacier tiers.

* **Developed deep knowledge in securing object storage and web distribution**, gaining capabilities in hosting S3 static websites, resolving cross-domain asset restrictions via CORS configurations, and setting multi-layered security gates using IAM, Bucket Policies, ACLs, and Block Public Access controls.

* **Acquired foundational expertise in handling large-scale datacenter physical migrations and hybrid components**, evaluating storage capabilities via the AWS Snow Family (Snowcone, Snowball Edge, Snowmobile) and managing central backup disaster recovery procedures.

* **Successfully deployed centralized data protection and tracking controls**, utilizing AWS Backup to design rule-based schedules, establishing proactive alert monitoring notifications, and executing data restore validations to maintain strict business continuity.

* **Executed complete enterprise-grade cloud migration workflows using AWS VM Import/Export services**, successfully converting local physical/virtual architecture from VMware environments into cloud-native Amazon Machine Images (AMIs) and deploying functional production EC2 instances.

* **Implemented cross-environment network access management**, properly defining complex S3 Bucket ACL parameters to authorize secure secure disk image translations between bare-metal datacenters and AWS hypervisors.

* **Successfully integrated hybrid storage file-sharing infrastructures**, deploying AWS Storage Gateway to connect local systems directly with Amazon S3 cloud fabrics, mounting live network volumes over SMB/NFS file systems, and validating hybrid data synchronization workflows.

* **Maintained cost-effective cloud governance practices**, carrying out meticulous end-of-lab cleanups (terminating EC2 instances, cleaning out heavy S3 migration packages, wiping temporary AMIs, and purging Storage Gateway appliances) to optimize account billing.