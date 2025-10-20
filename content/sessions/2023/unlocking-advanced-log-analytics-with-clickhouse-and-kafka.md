---
title: "Unlocking Advanced Log Analytics With ClickHouse® and Kafka"
slug: unlocking-advanced-log-analytics-with-clickhouse-and-kafka
authors:
 - Arul Jegadish
time_start: 2023-12-13T10:30:00-04:00
time_end: 2023-12-13T11:00:00-04:00
track: Orchestration
images:
 - ArulJegadish.jpg
slides: 2023/LogAnalytics.pdf 
---

In the landscape of observability, logs reign as a fundamental pillar. Undoubtedly, they are among the most extensively employed telemetry signals. However, beneath their widespread usage by developers lies a complexity that cannot be ignored - logs are verbose, lack structure, and are hard to search and analyze. The pursuit of advanced analytics on this foundation can lead down a costly and intricate path. While tools like OpenSearch offer analytic features, their cost and operational complexity can be prohibitive. Conversely, tools like Loki, while cost-effective, fall short in delivering analytics capabilities.
 
Enter ClickHouse®, a formidable solution boasting exceptional analytical prowess and remarkable data compression capabilities, offering a compelling and cost-effective alternative. In this session, we will look at straightforward methods for harnessing the potential of ClickHouse® and Kafka to construct an advanced log analytics solution.
 
During our discussion, we will focus on key components of ClickHouse®, including the JSON data type, Kafka table engine, and materialized views. We will also demonstrate how Kafka can be utilized for log ingestion into ClickHouse®. Additionally, we'll highlight ClickHouse®'s impressive compression capabilities, which contribute to a cost-effective infrastructure.. This method can easily be scaled to handle several Billion log events.
 
Throughout the session, we will provide a comprehensive, end-to-end working example to illustrate the practical application of ClickHouse® and Kafka in the context of advanced log analytics.