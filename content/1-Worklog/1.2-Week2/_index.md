---
title: "Week 2 Worklog"
date: 2026-04-27
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---



### Week 2 Objectives:

* Master advanced AWS networking connectivity options, hybrid cloud integration, and load balancing services for high availability.
* Gain comprehensive hands-on lab experience in building secure VPC infrastructures, hybrid DNS routing via Route 53, and infrastructure automation using CloudFormation.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                         |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 6   | - Studied Site-to-Site VPN and Client-to-Site VPN for secure connections <br> - Explored AWS Direct Connect for dedicated private infrastructure networking <br> - Studied Elastic Load Balancing (ELB) mechanisms and types: ALB (Layer 7), NLB (Layer 4), CLB (Legacy), and GWLB (Firewalls/Appliances) | 27/4/2026 | 27/4/2026 | https://cloudjourney.awsstudygroup.com/ |
| 7   | **Completed Labs from Module 02:** <br> - **Lab 03-01:** Intro to Amazon VPC & AWS Site-to-Site VPN <br> - **Lab 03-01.1 to 03-01.4:** Subnets (Public/Private), Route Tables, Internet Gateway (IGW), and NAT Gateway <br> - **Lab 03-02.1 to 03-02.3:** Security Groups, Network ACLs (NACLs), and visualization via VPC Resource Map | 28/4/2026 | 28/4/2026 | https://cloudjourney.awsstudygroup.com/ |
| 8   | **Completed Infrastructure Setup & EC2 Deployment Labs:** <br> - **Lab 03.1 & 03.2:** Created VPC and designed public/private subnets (CIDR blocks) <br> - **Lab 03.3 & 03.4:** Attached IGW and configured outbound Route Tables <br> - **Lab 03.5 & 04.1:** Implemented Security Groups and deployed EC2 instances within custom subnets | 29/4/2026 | 29/4/2026 | https://cloudjourney.awsstudygroup.com/ |
| 9   | **Completed Connection Testing & Automation Labs:** <br> - **Lab 03-04.2 & 03-04.3:** Tested EC2 connectivity and configured NAT Gateway <br> - **Lab 03-04.5:** Configured secure remote access via EC2 Instance Connect Endpoint <br> - **Lab 02-10.01 to 02-10.02.3:** Set up Hybrid DNS with Route 53, generated key pairs, initialized CloudFormation automation, and refined Security Groups | 30/4/2026 | 30/4/2026 | https://cloudjourney.awsstudygroup.com/ |
| 10  | **Completed Hybrid DNS Endpoints & VPC Peering Labs:** <br> - **Lab 02-10.05 to 02-10.05.4:** Set up DNS, created Route 53 Outbound/Inbound Endpoints, defined Resolver Rules, and verified results <br> - **Lab 02-10.06:** Cleaned up unused resources for cost optimization <br> - **Lab 02-19.01 & 02-19.02.1:** Established VPC Peering connection and automated setup using CloudFormation | 1/5/2026 | 1/5/2026 | https://cloudjourney.awsstudygroup.com/ |


### Week 2 Achievements:

* **Acquired a solid understanding of AWS hybrid connectivity and traffic management**, mastering Site-to-Site VPN, Client-to-Site VPN, AWS Direct Connect, and Elastic Load Balancing (including ALB, NLB, CLB, and GWLB) to build scalable, highly available systems.

* **Successfully completed all hands-on labs from Module 02 (Lab 03-01 to Lab 03-02.3)**, establishing a functional VPC architecture with custom subnet segmentation, routing rules, internet access (IGW), and private subnet security (NAT Gateway).

* **Gained deep practical skills in network security mechanisms**, defining instance-level firewall configurations via Security Groups (stateful) and subnet-level traffic controls via Network ACLs (stateless), while using the VPC Resource Map for full architectural visualization.

* **Developed capabilities in secure remote management**, verifying EC2 network pathways via SSH and deploying EC2 Instance Connect Endpoints to access private resources without public IP exposure.

* **Mastered infrastructure automation and automation workflows** by leveraging AWS CloudFormation templates to provision network environments and VPC Peering linkages programmatically.

* **Implemented comprehensive Hybrid DNS architectures using Route 53**, successfully deploying Inbound and Outbound Endpoints along with custom Resolver Rules to handle cross-environment name resolution between on-premises structures and AWS.

* **Practiced effective resource lifecycle management**, executing rigorous environment cleanup protocols to ensure cost optimization and eliminate redundant infrastructure charges.