---
title: "Aerodynamic Data Models: Flying Fast at Scale with DuckDB"
slug: aerodynamic-data-models-flying-fast-at-scale-with-duckdb
speakers:
 - Mike Driscoll
topics: 
 - Databases
day: 20241
room: Lightning talk
timeslot: 7
time_start: 2024-11-19T17:50:00.000Z
time_end:   2024-11-19T18:00:00.000Z
gridarea: 6/2/7/4
slides: 2024/Aerodynamic-Data-Models_-Flying-Fast-at-Scale-with-DuckDB.pdf
video: https://youtu.be/KCSKq9VQ8CY
---

At Rill, we rely on DuckDB to power uniquely fast dashboards for exploring time-series metrics. To achieve this interactivity, Rill’s dashboards generate up to 100 parallel queries in response to each user interaction.
 
In this lightning talk, we'll share a series of optimization and data modeling techniques that have been pivotal in achieving remarkably fast, sub-second response times using DuckDB.
 
Our primary tactics include employing parallel connections to facilitate simultaneous query processing and organizing data in a chronological order to enhance the effectiveness of min-max indexes. We also utilize enum types for more efficient handling of string column queries, along with config tunings. These approaches have collectively enabled us to enhance DuckDB's capability to handle larger datasets (100+ GBs) with sub-second query responses.
 
We invite you to join us in this insightful session to discover how these optimizations can significantly improve your data processing and query performance in DuckDB.