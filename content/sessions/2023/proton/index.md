---
title: "Proton : A single binary to tackle streaming and historical analytics"
slug: proton-a-single-binary-to-tackle-streaming-and-historical-analytics
authors:
 - Ken Chen
time_start: 2023-12-14T11:00:00-04:00
time_end: 2023-12-14T11:10:00-04:00
track: Databases
video: https://youtu.be/Duh6MJz_CjU?feature=shared
---

Proton is a unified streaming and historical analytic engine which is built on top of ClickHouse® code base and is in one single binary. It is the core engine which empowers Timeplus core product and open sourced under apache v2 https://github.com/timeplus-io/proton.
 
 
 
 In this talk, I will cover its technical internals like watermarking, streaming query state management, its internal streaming store, and how it connects historical data with live streaming etc. In the meaning while, some core features like tumble / hop / session window processing, streaming join, aggregation, new designed materialized view etc will be presented as well. 
 
 
 
 Timeplus also dedicates to contribute Proton's streaming query processing features back to the ClickHouse® community and it is already in progress (Github issue https://github.com/ClickHouse/ClickHouse/issues/54776, and PR https://github.com/ClickHouse/ClickHouse/pull/54870).
 
 
 
 So we like to present the porting roadmap and hear the feedbacks from the community. We believe with the addition of streaming processing capability, ClickHouse® OSS will serve the community users better.