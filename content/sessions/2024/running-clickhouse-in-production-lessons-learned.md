---
title: "Running ClickHouse® in Production – Lessons Learned"
slug: running-clickhouse-in-production-lessons-learned
speakers:
 - Noa Baron
topics:
 - Use cases
day: 20243
room: B
timeslot: 11
time_start: 2024-11-21T18:30:00.000Z
time_end:   2024-11-21T19:00:00.000Z
gridarea: 8/3/9/4
slides: 
video: https://youtu.be/7JbSX50Wp7s
---

When we chose ClickHouse® as our main data lake for analytics at Cato Networks, we envisioned it as a silver bullet solution for our data needs, promising effortless data ingestion and ready-to-query dashboards.
 
However, the journey from that initial setup to our current, sophisticated data platform has been filled with trials and tribulations, alongside valuable lessons.
 
We first used ClickHouse® as a black box magical persistence layer, simply feeding data points and querying ready-made GraphQL datasets. As our requirements grew more complex, our implementation evolved in complexity to meet these demands.
 
In this talk we’ll dive into the challenges and successes we encountered as a high-scale production user, such as making ClickHouse® a GDPR-compatible store, discovering its limitations as an enrichment engine, and leveraging it as a robust alternative to KSQL for streaming data.
 
Additionally, we’ll explore the necessity and implications of migrating our schema three separate times (three’s a charm!). Join us to learn from our experiences what to do and not to do with ClickHouse® in production.