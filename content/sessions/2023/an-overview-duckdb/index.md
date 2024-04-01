---
title: "An Overview of DuckDB"
authors:
 - Gabor Szarnyas
time_start: 2023-12-13T09:10:00-04:00
time_end: 2023-12-13T09:40:00-04:00
track: Databases
images:
 - GaborSzarnyas.jpg
slides: 2023/DuckDB.pdf 
---

DuckDB is an analytical database management system. It runs in-process, which makes its configuration trivial and eliminates any overhead between the client application and the database. DuckDB is open-source and highly portable with integrations for Python, R, Java, Julia, and 10+ other languages. DuckDB has top-notch support for data formats (CSV, Parquet, JSON, Iceberg) and data sources (https, s3, gcs, etc.). This talk will introduce the DuckDB system, explain its key design decisions, and demonstrate how it is able to scale even on a single laptop.