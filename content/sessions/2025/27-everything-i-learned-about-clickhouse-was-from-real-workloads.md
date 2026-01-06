---
title: "Everything I Learned About ClickHouse® was From Real Workloads"
slug: everything-i-learned-about-clickhouse-was-from-real-workloads
speakers:
 - Udi Rot
topics: 
 - Data Storage & Query
day: 20252
room: B
timeslot: 27
time_start: 2025-11-05T18:00:00.000Z
time_end: 2025-11-05T18:30:00.000Z
gridarea: 5/3/6/4
video: https://youtu.be/_VbAO-ejBk8
slides: 
---

After years of pushing ClickHouse® to its outer limits in real-world observability workloads, we've learned a lot - sometimes the hard way - about getting the most out of your analytics system. But before you dive into inverted indexes, object storage, and terabyte-scale performance tuning, it's critical to get the basics right. 

This talk starts at the beginning, walking through the fundamentals that make ClickHouse® such a powerful engine for analytical workloads, the performance advantages of columnar storage, how its architecture supports horizontal scaling, and why it's ideal for high-throughput, low-latency queries. We’ll share how our observability platform ingests and queries billions of logs, traces, and metrics using these core principles (and yours can too!).

Then dive into the deep end, covering some advanced and novel techniques we’ve developed over time. You’ll learn how we use custom inverted indexes for rare-event querying, materialized views for real-time aggregations, secondary index tuning, and cost-efficient object storage integration. Along the way, we’ll highlight performance optimization strategies grounded in real-world data scale.