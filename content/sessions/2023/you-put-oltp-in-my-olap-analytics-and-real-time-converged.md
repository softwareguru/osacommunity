---
title: "You put OLTP in my OLAP! Analytics and Real-time Converged"
slug: you-put-oltp-in-my-olap-analytics-and-real-time-converged
authors:
 - Felipe Mendes
time_start: 2023-12-14T11:10:00-04:00
time_end: 2023-12-14T11:40:00-04:00
track: Databases
images:
 - FelipeMendes.jpg
slides: 2023/YouPutOLTP.pdf 
---

Analytics (OLAP) and Real-time (OLTP) workloads serve distinctly different purposes. OLAP is optimized for data analysis and reporting, while OLTP is optimized for real-time low-latency traffic.
 
 
 
 Most databases are designed to primarily benefit from one of them. Worse, concurrently running both workloads under the same datastore will frequently introduce resource contention, where the workloads end up hurting each other, considerably dragging down the overall distributed system's performance.
 
 
 
 In this talk, we will share different strategies and approaches to mitigate the performance impacts perceived when OLAP and OLTP workloads are run to the extreme. We will present the problem of mixing OLTP and OLAP, and give an special attention to ScyllaDB Workload Prioritization and Workload Characterization features, built on top of seastar's isolation mechanisms, to explain the approach we took at ScyllaDB to allow both worlds to co-exist without any interference.