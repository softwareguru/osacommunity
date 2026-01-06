---
title: "A Roundup of Observability Datastores"
slug: a-roundup-of-observability-datastores
speakers:
 - Josh Lee
topics:
day: 20251
room: A
timeslot: 10
time_start: 2025-11-04T18:30:00.000Z
time_end: 2025-11-04T19:00:00.000Z
gridarea: 7/2/8/3
video: https://youtu.be/9CCRHT8Pj48
slides: 
---

From plain-old Postgres to the LGTM stack, ELK, Cassandra, and ClickHouse®, the landscape of telemetry storage options is as vast as it is overwhelming. With so many choices, how do we decide which datastore is right for the job? In this talk, Joshua will guide attendees through the foundational principles of telemetry—covering metrics, traces, logs, profiles, and wide events—and break down the strengths and limitations of different database technologies for each use case.

We’ll examine how traditional relational databases like Postgres can still hold their own, where ELK and CockroachDB fit into the picture, and why specialized stacks like LGTM (Loki, Grafana, Tempo, Mimir) are so popular in modern observability pipelines. And, of course, we’ll highlight the growing role of ClickHouse® as a versatile and high-performance option for logs, traces, and more and VictoriaMetrics as a drop-in replacement for Prometheus. By the end of this session, attendees will have a clearer understanding of the trade-offs between these datastores and how to make informed decisions based on the unique requirements of their systems. Whether you’re building an observability stack from scratch or looking to optimize an existing setup, this tour of the observability datastore landscape will leave you better equipped to navigate the options.