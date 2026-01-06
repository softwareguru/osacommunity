---
title: "Ingesting and analyzing millions of events per second in real-time using open source tools"
slug: ingesting-and-analyzing-millions-of-events-per-second-in-real-time-using-open-source-tools
speakers:
 - Javier Ramirez
topics:
 - Data ingestion
 - Open source
day: 20243
room: A
timeslot: 10
time_start: 2024-11-21T18:30:00.000Z
time_end:   2024-11-21T19:00:00.000Z
gridarea: 8/2/9/3
slides:
video: https://youtu.be/QsG42AyFu0k
---

Teams of all shapes and sizes benefit from near real-time analytics. In this session, I will present a project template that can serve as the foundation to build one such high performing system, powered by Apache Kafka, QuestDB, Grafana OSS, and Jupyter Notebook.
 
The first step of a data pipeline is ingestion, and even though we could directly ingest into a fast database, I will use Apache Kafka to ingest data. We will see how to use Python, JavaScript, and Go to send messages into Kafka.
 
Now, we need an analytics database, and for real-time data, a time-series database seems like a good match. I will demonstrate how to use QuestDB, an Apache 2.0 licensed project, to ingest and query data in milliseconds or faster.
 
Data analytics often require a graphical dashboard. For this purpose, I will use Grafana OSS, where we will create a couple of real-time charts updating several times per second.
 
And, of course, it's 2024, so you might want to delve into some data science. No worries. I will demonstrate how Jupyter Notebook can be used to read from your database and perform interactive data exploration and time-series forecasting.
 
This will be a demo-driven presentation and all the code is open sourced at https://github.com/questdb/time-series-streaming-analytics-template. You can use it as a starting point for your streaming data projects.