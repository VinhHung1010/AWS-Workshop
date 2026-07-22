---
title: "Week 5 Worklog"
date: 2026-05-18
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---



### Week 5 Objectives:

* Master enterprise file system deployments using Amazon FSx, focusing on Multi-AZ high availability, resource administration, dynamic scaling, and storage optimization techniques.
* Advance core competencies in global content delivery and web application optimization by integrating Amazon S3 static web hosting securely with Amazon CloudFront CDN distributions.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                         |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 22  | **Completed Amazon FSx Initialization & Optimization Labs:** <br> - **Module 04-Lab25-2.2 & 25-2.3:** Provisioned SSD and HDD Multi-AZ enterprise file systems <br> - **Module 04-Lab25-3 & 25-4:** Configured custom network file shares and tested baseline storage performance metrics <br> - **Module 04-Lab25-5 & 25-6:** Monitored real-time file system throughput and enabled Data Deduplication for efficiency | 18/5/2026 | 18/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 23  | **Completed Advanced FSx Administration & Capacity Scaling Labs:** <br> - **Module 04-Lab25-7 to 25-9:** Enabled Shadow Copies for backup recovery, managed active user sessions/open files, and enforced user storage quotas <br> - **Module 04-Lab25-11 to 25-13:** Scaled file system throughput and storage capacity dynamically, followed by a complete environmental cleanup | 19/5/2026 | 19/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 24  | **Completed Amazon S3 Static Web Hosting Labs:** <br> - **Module 04-Lab57-2.1 & 57-2.2:** Created dedicated S3 buckets and loaded production website data objects <br> - **Module 04-Lab57-3 to 57-6:** Enabled the static website hosting feature, adjusted public access settings along with object permissions, and successfully tested live website accessibility | 20/5/2026 | 20/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 25  | **Completed CloudFront CDN Distribution & S3 Protection Labs:** <br> - **Module 04-Lab57-7.1:** Hardened storage endpoints by enabling global S3 Block Public Access settings <br> - **Module 04-Lab57-7.2 & 57-7.3:** Configured an Amazon CloudFront distribution edge network, integrated it with S3, and validated global caching functionality <br> - **Module 04-Lab57-8:** Enabled S3 Bucket Versioning for data resilience | 21/5/2026 | 21/5/2026 | https://cloudjourney.awsstudygroup.com/ |
| 26  | **Completed Multi-Region S3 Replication & Environment Cleanup Labs:** <br> - **Module 04-Lab57-9 & 57-10:** Organized object structures, managed internal file movements, and implemented automated Cross-Region Replication (CRR) <br> - **Module 04-Lab57-11:** Performed standard resource cleanup routines across the entire deployed storage framework | 22/5/2026 | 22/5/2026 | https://cloudjourney.awsstudygroup.com/ |


### Week 5 Achievements:

* **Acquired a deep architectural understanding of Amazon FSx enterprise deployments**, successfully launching high-availability Multi-AZ storage architectures across both performance-tier SSD and cost-tier HDD configurations.

* **Mastered advanced file system optimization techniques**, implementing Data Deduplication to significantly minimize storage footprints and actively tracking operational metrics via integrated performance monitoring frameworks.

* **Developed strong enterprise-level FSx administrative capabilities**, gaining hands-on proficiency in establishing data backup baselines via Shadow Copies, monitoring active network user sessions, maintaining open files, and regulating consumption through user storage quotas.

* **Demonstrated expertise in elastic storage infrastructure orchestration**, executing non-disruptive dynamic scaling procedures for both file system throughput and overall storage capacity configurations to handle fluctuating enterprise workloads.

* **Gained practical skills in deploying cloud-native web hosting structures**, executing the end-to-end workflow of configuring static website hosting on Amazon S3, manipulating granular public bucket boundary rules, and validating external object visibility.

* **Hardened web distribution security through Content Delivery Network (CDN) architectures**, leveraging Amazon CloudFront edge infrastructure to securely serve S3 assets, while locking down origin data endpoints via S3 Block Public Access controls.

* **Implemented multi-layered storage resiliency and disaster recovery designs**, configuring S3 Bucket Versioning to defend against accidental overrides and setting up automated Multi-Region Replication to achieve geographically redundant infrastructure.

* **Enforced continuous cloud cost optimization principles**, consistently following resource deletion protocols across all lab components (including the teardown of live FSx environments, CloudFront distribution points, and heavy S3 buckets) to ensure zero waste.