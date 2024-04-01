---
title: "Maximizing Query Speed and Minimizing Costs in Data Lakes with Open-Source Caching"
slug: maximizing-query-speed-and-minimizing-costs-in-data-lakes-with-open-source-caching
authors:
 - Beinan Wang
time_start: 2023-12-13T12:30:00-04:00
time_end: 2023-12-13T13:00:00-04:00
track: Infrastructure
images:
 - BeinanWang.jpg
---

As data lakes scale in complexity and size, companies face challenges with slow and inconsistent data access, rapidly growing storage costs, and high operation costs when migrating to the cloud. In this talk, we discuss an open-source caching framework we designed to improve performance by 1.5x and reduce storage costs by millions per year. The framework leverages tools like Hadoop, Parquet, Hudi, and Alluxio and applies to both on-prem and cloud environments.
 
 
 
 By the end of the session, you will learn:
 
 
 
 The challenges of performance and cost in large-scale data lakes
 
 Architectural considerations for caching to accelerate queries, maximize cache hit rates, and reduce storage costs
 
 Leveraging open-source tools like Alluxio for performant caching on high-density HDDs
 
 Advanced techniques like segmented file caching, affinity-based scheduling, and cache filtering to optimize cache usage
 
 Monitoring cache usage and working sets with metrics and traces