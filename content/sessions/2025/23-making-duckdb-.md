---
title: "Making DuckDB with Arrow Flight and the Airport Extension"
slug: making-ducdb-arrow
speakers:
 - Rusty Conover
topics: 
 - Data Storage & Query
day: 20252
room: B
timeslot: 23
time_start: 2025-11-05T17:15:00.000Z
time_end: 2025-11-05T17:25:00.000Z
gridarea: 3/3/4/4
draft: true
---

Airport is a DuckDB community extension developed by Query.Farm that adds Apache Arrow Flight support to DuckDB.

In plain terms:
👉 It lets DuckDB query, modify, and store data through Arrow Flight servers — remote, high-performance data endpoints that speak gRPC and Arrow IPC.

You can think of it as “network tables for DuckDB.”
Instead of reading files from disk, you can query live data over the network just like local tables.