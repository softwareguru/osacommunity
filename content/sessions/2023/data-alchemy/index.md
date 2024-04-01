---
title: "Data Alchemy: Transforming Raw Data to Gold with Apache Hudi and DBT"
slug: data-alchemy-transforming-raw-data-to-gold-with-apache-hudi-and-dbt
authors:
 - Nadine Farah
time_start: 2023-12-12T11:10:00-04:00
time_end: 2023-12-12T11:40:00-04:00
track: Infrastructure
images:
 - NadineFarah.jpg
video: https://youtu.be/-fZQR9iAhqo?feature=shared
---

The medallion architecture graduates raw data sitting in operational systems into a set of refined tables in a series of stages, ultimately processing data to serve analytics from gold tables. While there is a deep desire to build this architecture incrementally, it is very challenging with current technologies available on lakehouses. Many technologies can’t efficiently update records or efficiently process incremental data without recomputing all the data to serve low-latency tables. Apache Hudi is a transactional data lake platform with full mutability support, including streaming upserts, and provides a powerful incremental processing framework. Apache Hudi powers the largest transactional data lakes in the industry, differentiating on fast upserts and change streams to only process and serve the change records. 
  
DBT incremental loading feature processes only new or updated records from the Bronze layer, reducing the processing time and resource usage. With Hudi’s new CDC feature, users can use DBT to transform change records as a result of inserts, updates and deletes from bronze to gold tables. In the talk, attendees will walk away with: 
 
 - The current challenges of building a medallion architecture at low-latency.
 - How the new Hudi CDC feature unlocks incremental processing on the lake.
 - How you can leverage DBT to transform changed records from inserts, updates and deletes to build a low latency medallion architecture.

