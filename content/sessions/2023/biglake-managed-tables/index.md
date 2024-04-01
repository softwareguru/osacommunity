---
title: "Build a fully-managed OSS compatible lakehouse with BigLake Managed Tables"
authors:
 - Jeffrey Nelson
time_start: 2023-12-12T12:30:00-04:00
time_end: 2023-12-12T13:00:00-04:00
track: Data ingestion
images:
 - JeffreyNelson.jpg
video: https://youtu.be/nQ6jqpgGlb0?feature=shared
---

Open table formats like Apache Iceberg, Apache Hudi, and Delta Lake use embedded metadata, stored alongside data on object stores to provide transactionally consistent DML and time travel features. This metadata is usually backed by a transaction log also stored in object storage. While this approach of maintaining a transaction log on an object store provides simplicity to build an open ecosystem, workloads that require high-throughput write and DML are often limited. This is because commits to the transaction log can throttle write performance and throughput.
 
BigLake Managed Tables seek to improve the open lakehouse experience by leveraging parts of BigQuery’s infrastructure to add new value to open table formats, while retaining OSS compatibility for compute and storage. Users can expect the features they find in familiar cloud data warehouses like fine-grained access control, time travel, and high-throughput streaming. But BigLake Managed Tables keeps all data in open file formats, and automatically takes care of cataloging, adaptive file sizing, garbage collection, and Apache Iceberg snapshotting for OSS engine readers.
 
This presentation will begin by laying out the current state of open lakehouse table formats. It will discuss the pros and cons of existing technologies and introduce how BigLake Managed Tables (BLMT) proposes to solve gaps in OSS and high-throughput workloads. The presentation will contain a focus on how BLMT uses OSS from the analytics engines (e.g. Spark, Trino, Flink) and storage (e.g. Apache Iceberg) perspectives.