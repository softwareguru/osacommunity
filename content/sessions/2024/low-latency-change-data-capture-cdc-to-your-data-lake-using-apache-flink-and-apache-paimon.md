---
title: "Low latency Change Data Capture (CDC) to your data lake, using Apache Flink and Apache Paimon"
slug: low-latency-change-data-capture-cdc-to-your-data-lake-using-apache-flink-and-apache-paimon
speakers:
 - Ali Alemi
 - Subham Rakshit
topics: 
 - Open Source
 - Data ingestion
day: 20241
room: B
timeslot: 18
time_start: 2024-11-19T20:00:00.000Z
time_end:   2024-11-19T20:30:00.000Z
gridarea: 13/3/14/4
slides: 2024/Low-latency-Change-Data-Capture-(CDC)-to-your-data-lake,-using-Apache-Flink-and-Apache-Paimon.pdf
video: https://youtu.be/X3Dk07_i-7c
---

Change Data Capture (CDC) from various source databases to a data lake is critical for analytics workload. However different CDC mechanism exists and there are trade-offs with the approach. While using open table formats, you could get around the issue of record-level upserts and deletes but compaction of the data, schema evolution along with latency with Merge-on-Read is still a big challenge. In this session, we will share how you could use Apache Paimon and Apache Flink to build your CDC pipeline that overcomes these challenges and do a low latency sync of CDC data. We will also cover partial-update merge engine and changelog tracking of streaming data. Finally, we will compare Apache Paimon with Apache Hudi and Apache Iceberg and provide prescriptive guidance when to use one over the other.
 
Join this session and learn how Apache Paimon differs in the approach of solving the CDC problem.