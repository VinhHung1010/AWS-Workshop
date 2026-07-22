---
title: "Week 3 Worklog"
date: 2026-05-04
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---



### Week 3 Objectives:

* Master advanced inter-VPC routing topologies (VPC Peering, Transit Gateway) and core EC2 compute architectures including auto-scaling capabilities.
* Acquire hands-on experience in implementing data protection policies (AWS Backup), hybrid storage integrations (Storage Gateway), and advanced object storage features (Amazon S3 security, versioning, and replication).

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                         |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 11  | **Completed VPC Peering & Automation Labs:** <br> - **Lab 02-19.02.1 to 02-19.02.3:** Initialized CloudFormation for network infra, setup Security Groups, and deployed test EC2 instances <br> - **Lab 02-19.03 to 02-19.07:** Updated NACLs, created Peering Connection, configured Route Tables, enabled Cross-Peer DNS, and executed resource cleanup | 4/5/2026 | 4/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 12  | **Completed AWS Transit Gateway Labs:** <br> - **Lab 02-Lab20-01 & 02-Lab20-02:** Studied Transit Gateway architecture and prepared network configurations <br> - **Lab 02-Lab20-03 to 02-Lab20-07:** Created Transit Gateway, configured VPC Attachments & Route Tables, updated VPC routing, and cleaned up resources | 5/5/2026 | 5/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 13  | **Studied Core EC2 Compute Services (Modules 03-01-01 to 03-01-07):** <br> - Analyzed EC2 Instance Types, families, classifications, and AMI/Backup/Key Pair mechanisms <br> - Compared persistent storage (EBS) vs temporary storage (Instance Store) <br> - Explored automation via User Data/Metadata and elastic scalability via EC2 Auto Scaling Groups | 6/5/2026 | 6/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 14  | **Completed Data Protection & Storage Labs:** <br> - **Module 03-Lab13-01 to 03-Lab13-06:** Deployed AWS Backup, created automated Backup Plans (rules, retention policies), tested data restore integrity, and cleaned up resources <br> - **Module 03-Lab24-01.1 & 03-Lab24-01.2:** Created Amazon S3 bucket and launched an EC2 instance for Storage Gateway deployment | 7/5/2026 | 7/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 15  | **Completed Storage Gateway & S3 Static Web Hosting Labs:** <br> - **Module 03-Lab24-02.1 & 02.2:** Configured AWS Storage Gateway and file shares (SMB/NFS) <br> - **Module 03-Lab57-02.1 to 05:** Created S3 buckets, loaded data, enabled Static Website Hosting, and adjusted public access permissions/policies | 8/5/2026 | 8/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 16  | **Completed S3 Security & Advanced Management Labs:** <br> - **Module 03-Lab57-06 to 07.3:** Tested static website access, applied S3 Block Public Access, and verified bucket policy restrictions <br> - **Module 03-Lab57-08 to 11:** Enabled S3 Bucket Versioning, practiced object movement/organization, configured cross-bucket Replication, and conducted final resource cleanup | 9/5/2026 | 9/5/2026 | https://cloudjourney.awsstudygroup.com/ |


### Week 3 Achievements:

* **Mastered multi-VPC networking topologies and centralized routing control**, gaining hands-on experience with VPC Peering architectures and AWS Transit Gateway to manage cross-VPC communication, route tables, and attachments securely.

* **Acquired a deep understanding of core AWS EC2 compute architecture**, including workload-specific instance selections, AMI recovery provisioning, metadata automation, and high-availability setups utilizing EC2 Auto Scaling Groups coupled with load balancing.

* **Successfully deployed centralized data protection mechanisms**, leveraging AWS Backup to configure automated retention schedules and verifying backup volume data integrity through practical restore test routines.

* **Developed solid hybrid cloud storage integrations**, provisioning AWS Storage Gateway configurations and deploying SMB/NFS file shares to seamlessly bridge on-premises computing infrastructure with AWS storage layers.

* **Demonstrated proficiency in configuring and managing Amazon S3 services**, successfully enabling static website hosting capabilities and manipulating granular access permissions across public-facing structures.

* **Hardened object storage security infrastructures**, successfully managing S3 Block Public Access controls, implementing rigid bucket-level policies, and monitoring traffic behaviors under locked access profiles.

* **Implemented robust lifecycle and data resiliency strategies in S3**, utilizing Bucket Versioning to defend against accidental file deletions, managing file directories, and configuring cross-bucket Replication systems for disaster recovery.

* **Maintained continuous environment cost optimization**, executing comprehensive cleanup steps across all completed lab modules (including EC2 nodes, security groups, peering pathways, Transit Gateways, and storage structures) to prevent unnecessary billing charges.