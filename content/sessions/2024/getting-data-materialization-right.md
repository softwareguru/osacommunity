---
title: "Getting data materialization right"
slug: getting-data-materialization-right
speakers:
 - Gian Merlino
topics: 
 - Databases

day: 20243
room: B
timeslot: 14
time_start: 2024-11-21T19:10:00.000Z
time_end:   2024-11-21T19:40:00.000Z
gridarea: 10/3/11/4
slides: 
video: https://youtu.be/l_c1H7b0Tlc
---

Materialization moves computation from query time to ingest time by creating specialized derived tables, or materialized views, that are simpler than the source tables and are geared towards supporting specific workloads. This is one of the most powerful and common techniques for speeding up OLAP workloads. You can implement materialization in various ways, including built-in "materialized view" or "projection" features in many databases, as well as with third-party stream processors and workflow orchestrators that sit outside the database.
 
But materialization isn't all smooth sailing. While it can boost performance, it also adds complexity and reduces flexibility in your data infrastructure. The cost implications are nuanced: typically, compute costs at query time go down, but storage costs may go up. Additionally, repopulating large materialized datasets can be expensive, and ensuring users see a consistent view of the data can be challenging.
  
In this talk, we'll cover the various ways that you can manage materialization in a data system. We’ll discuss when to use materialization, the complexities that can arise, and how to handle them. We’ll also examine how materialization is implemented across various systems and weigh the trade-offs between performance, cost, and simplicity.