---
title: "QuestDB: The building blocks of a fast open-source time-series database"
slug: questdb-the-building-blocks-of-a-fast-open-source-time-series-database
authors:
 - Javier Ramirez
time_start: 2023-12-13T09:50:00-04:00
time_end: 2023-12-13T10:20:00-04:00
track: Databases
images:
 - JavierRamirez.jpg
slides: https://www.slideshare.net/supercoco9/questdb-the-building-blocks-of-a-fast-opensource-timeseries-database 
---

Traditionally, databases have treated timestamps just as another data type. However, when performing real-time analytics, timestamps should be first class citizens and we need rich time semantics to get the most out of our data. We also need to deal with ever growing datasets while keeping performant, which is as fun as it sounds.
 
It is no wonder time-series databases are now more popular than ever before. Join me in this session to learn about the internal architecture and building blocks of QuestDB, an open source time-series database designed for speed. 
 
We will learn how it deals with data ingestion, and which SQL extensions it implements for working with time-series efficiently.
 
We will also review a history of some of the changes we have gone over the past two years to deal with late and unordered data, non-blocking writes, read-replicas, or data deduplication.