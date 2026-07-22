---
title: "Week 8 Worklog"
date: 2026-06-08
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---



### Week 8 Objectives:

* Master foundational and advanced cloud database paradigms, comparing transactional (OLTP) and analytical (OLAP) workloads across managed relational platforms and in-memory caching solutions.
* Acquire hands-on experience architectural design by preparing isolated network infrastructures and securely deploying integrated multi-tier database-driven application environments on AWS.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                         |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 37  | **Database Concepts Review:** <br> - Reviewed fundamental relational and non-relational database models <br> - Studied primary/foreign keys, indexes, and constraints <br> - Compared OLTP vs OLAP database workloads and cloud database deployment architectures | 8/6/2026 | 8/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 38  | **Managed Relational Databases Study:** <br> - Studied Amazon RDS managed database services <br> - Explored Amazon Aurora architecture and performance advantages <br> - Analyzed Multi-AZ high availability deployments, Read Replicas, and backup/recovery mechanisms | 9/6/2026 | 9/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 39  | **Data Warehousing & Caching Architectures:** <br> - Learned about Amazon Redshift cloud data warehouse solution for business analytics <br> - Studied Amazon ElastiCache (Redis and Memcached) and caching mitigation strategies to reduce database workloads | 10/6/2026 | 10/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 40  | **Completed RDS Networking Infrastructure Labs:** <br> - **Module 06-Lab05-2.1 to 2.4:** Configured custom networking components for Amazon RDS, created dedicated Security Groups for EC2 and database access, and provisioned DB Subnet Groups | 11/6/2026 | 11/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 41  | **Completed Multi-Tier Application & Database Deployment Labs:** <br> - **Module 06-Lab05-3 to 5:** Launched EC2 nodes, created Amazon RDS database instances within a VPC, established secure secure cross-tier security rules, and deployed a live sample application <br> - **Module 06-Lab05-6 & 7:** Conducted manual backup/restore validation testing for disaster recovery, and executed thorough final resource cleanup | 12/6/2026 | 12/6/2026 | https://cloudjourney.awsstudygroup.com/ |


### Week 8 Achievements:

* **Solidified core database engineering fundamentals**, mastering structural differences between relational and non-relational schemas, data normalization constraints, and target use cases for transactional (OLTP) versus analytical (OLAP) system configurations.

* **Developed deep theoretical competencies in AWS managed database topologies**, evaluating the architectural scalability of Amazon RDS and the performance/storage replication advantages of cloud-native Amazon Aurora.

* **Gained specialized insight into big data analytics and low-latency response architectures**, learning to deploy cloud data warehouses via Amazon Redshift and leverage in-memory caching layers via Amazon ElastiCache (Redis/Memcached) to offload heavy read database operations.

* **Successfully designed secure isolated network boundaries for database tiers**, provisioning custom DB Subnet Groups across isolated private subnets and establishing restrictive multi-layered firewall pathways via precise Security Group pairings.

* **Successfully deployed a complete database-driven application architecture on AWS**, integrating a live web application layer hosted on Amazon EC2 with a managed backend engine powered by Amazon RDS.

* **Mastered operational disaster recovery and data retention protocols**, validating data lifecycle safety rules by creating manual backup recovery snapshots and executing full recovery restorations to guarantee uninterrupted business application continuity.

* **Enforced continuous cloud cost optimization principles**, systematically running thorough post-lab cleanup routines to terminate active compute nodes and wipe database cluster storage instances to prevent unnecessary account billings.