---
title: "Week 10 Worklog"
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---



### Week 10 Objectives:

* Design and implement an end-to-end cloud-native data analytics pipeline on AWS, spanning streaming data ingestion, automated cataloging, serverless querying, and business intelligence visualization.
* Gain comprehensive hands-on experience integrating core AWS analytics services including Kinesis Data Firehose, AWS Glue, Amazon Athena, and Amazon QuickSight into a unified data engineering workflow.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                         |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 47  | **Streaming Data Ingestion Pipeline:** <br> - Created an Amazon S3 bucket for incoming raw streaming storage <br> - Provisioned and configured an Amazon Kinesis Data Firehose delivery stream <br> - Generated real-time sample data to test and validate pipeline ingestion paths | 22/6/2026 | 22/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 48  | **Automated Data Schema Discovery:** <br> - Created an AWS Glue Crawler to scan raw data inside Amazon S3 <br> - Automatically discovered datasets, generated metadata, and populated the AWS Glue Data Catalog <br> - Validated the accuracy of table structures and data schemas | 23/6/2026 | 23/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 49  | **Data Processing Workflow Execution:** <br> - Reviewed and explained application code logic used within the data processing stream <br> - Configured target S3 locations for processed output storage <br> - Initialized session connections required for processing services and executed workflows | 24/6/2026 | 24/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 50  | **Serverless Data Warehouse Querying:** <br> - Configured Amazon Athena to interface with S3 data layers <br> - Executed serverless SQL queries directly against schemas defined in the Glue Data Catalog <br> - Validated and analyzed large structural datasets without instance management | 25/6/2026 | 25/6/2026 | https://cloudjourney.awsstudygroup.com/ |
| 51  | **Business Intelligence & Lifecycle Management:** <br> - Connected Amazon QuickSight to active Athena datasets <br> - Built operational charts and business reports via interactive dashboards <br> - Performed standard cleanup routines to tear down the analytics infrastructure and control costs | 26/6/2026 | 26/6/2026 | https://cloudjourney.awsstudygroup.com/ |


### Week 10 Achievements:

* **Engineered robust serverless streaming ingestion architectures**, successfully configuring Amazon Kinesis Data Firehose delivery streams to capture, batch, and deliver high-volume streaming data into Amazon S3 storage origins.

* **Mastered automated metadata discovery and cataloging rules**, leveraging AWS Glue Crawlers to automatically parse unstructured datasets, infer exact table structures, and build centralized data definitions within the AWS Glue Data Catalog.

* **Developed deep competencies in data processing workflow logic**, evaluating underlying processing codes, establishing secure runtime connections, and routing transformed output datasets back to persistent object storage targets.

* **Implemented operational serverless log analytics frameworks**, using Amazon Athena to perform distributed, complex SQL queries directly over compressed data lakes mapped by the Glue catalog schema.

* **Successfully delivered end-to-end Business Intelligence (BI) visualization setups**, connecting Amazon QuickSight directly to active Athena query schemas to produce functional dashboard matrices and rich operational reports for corporate stakeholders.

* **Demonstrated absolute proficiency in the modern AWS Data Engineering stack**, successfully constructing a comprehensive data lifecycle pathway from raw real-time streaming data ingestion to executive data analytics dashboards.

* **Maintained cost-effective cloud governance practices**, executing rigorous post-lab environment cleanups (deleting active Kinesis streams, dropping Glue metadata tables, cleaning out test S3 data buckets, and closing BI connections) to prevent idle billing charges.