---
title: "Week 7 Worklog"
date: 2026-06-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---



### Week 7 Objectives:

* Deepen expertise in advanced AWS Identity and Access Management (IAM), focusing on temporary credentials, multi-factor condition constraints, and cross-account or administrative role assumption.
* Implement production-grade cloud security audits, encryption strategies using AWS KMS for object storage, and centralized log analytics via AWS CloudTrail and Amazon Athena.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                         |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 32  | **Completed IAM Role Assumption & EC2 Access Labs:** <br> - **Module 05-Lab28-5.1 to 5.2.5:** Switched roles, initiated secure EC2 access pathways, created EC2 instances, edited resource tags, and verified policy constraints <br> - **Module 05-Lab28-6:** Cleaned up active lab infrastructure | 1/6/2026 | 1/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 33  | **Completed Policy Restriction & Principle of Least-Privilege Labs:** <br> - **Module 05-Lab30-3 to Lab30-5:** Created restriction policies, provisioned limited IAM users, and vigorously tested permission boundaries <br> - **Module 05-Lab30-6:** Executed post-lab environment cleanup | 2/6/2026 | 2/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 34  | **Completed Cryptography, Governance Auditing, and Log Analytics Labs:** <br> - **Module 05-Lab33-2.1 to 4.2:** Configured KMS encryption keys, provisioned S3 buckets, and uploaded encrypted data objects <br> - **Module 05-Lab33-5.1 to 5.3:** Set up AWS CloudTrail logging and deployed Amazon Athena for granular log query analytics | 3/6/2026 | 3/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 35  | **Completed Encrypted Data Sharing & Enterprise IAM Cross-Access Labs:** <br> - **Module 05-Lab33-6 & 33-7:** Tested secure sharing protocols for KMS-encrypted S3 data, followed by resource cleanup <br> - **Module 05-Lab44-2 to 4.2:** Formed IAM groups, created separate IAM users, ran permission checks, and initialized administrative Switch Role configurations | 4/6/2026 | 4/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 36  | **Completed Advanced Context Restrictions & Key Management Labs:** <br> - **Module 05-Lab44-4.3.1 to 5:** Restricted switch role operations using IP-address and time-based conditions, followed by cleanup <br> - **Module 05-Lab48-1.1 to 4:** Deployed EC2/S3, generated short-term access keys, compared static credentials against IAM Roles via the AWS CLI, and performed environment cleanup | 5/6/2026 | 5/6/2026 | https://cloudjourney.awsstudygroup.com/ |


### Week 7 Achievements:

* **Mastered secure resource authorization via dynamic IAM Roles**, successfully applying role-assumption mechanics and temporary security credentials to replace high-risk long-term authentication variables.

* **Advanced capabilities in constructing rigid security baselines**, designing complex, granular IAM policies to enforce the Principle of Least Privilege (PoLP) while setting strict permission boundaries.

* **Implemented comprehensive cloud data governance and cryptography setups**, managing encryption keys dynamically via AWS Key Management Service (KMS) to secure sensitive object stores inside Amazon S3.

* **Operationalized real-time infrastructure auditing and security monitoring infrastructures**, linking active AWS CloudTrail tracking engines with distributed Amazon S3 log buckets to preserve non-repudiable transaction histories.

* **Developed advanced security log analysis mechanisms**, orchestrating serverless SQL query protocols in Amazon Athena to parse, inspect, and identify specific system activities out of compiled CloudTrail audit trails.

* **Engineered multi-layered enterprise user access models**, establishing group-based administration policies, launching designated administrative roles, and configuring secure profile-switching frameworks.

* **Hardened environment network boundaries using context-aware policy conditions**, successfully restricting administrative role-switching access variables based on precise source IP addresses and specific time-window brackets.

* **Demonstrated operational proficiency in CLI credential configurations**, evaluating programmatic authentication approaches to prove the security advantages of EC2 IAM instances over hard-coded access keys.

* **Enforced continuous cloud cost optimization principles**, consistently executing resource deletion protocols across all lab components to avoid unnecessary billing charges.