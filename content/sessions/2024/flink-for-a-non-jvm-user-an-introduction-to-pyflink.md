---
title: "Flink for a non-JVM user, an introduction to pyflink"
slug: flink-for-a-non-jvm-user-an-introduction-to-pyflink
speakers:
 - Diptiman Raichaudhuri
topics:
 - Open Source

day: 20241
room: A
timeslot: 17
time_start: 2024-11-19T20:00:00.000Z
time_end:   2024-11-19T20:30:00.000Z
gridarea: 13/2/14/3
slides: 2024/Flink-for-a-non-JVM-user,-an-introduction-to-pyflink.pdf
video: https://youtu.be/Tn4n9xKE1ug
---

Apache Flink has steadily established itself as the leader in stream processing technologies. With thousands of users implementing simple to advanced streaming use cases, the future of the flink community looks bright.
 
While Apache Flink runs on JVM, for non-JVM users Flink has a well defined pyflink port which helps python developers build sophisticated stream processing jobs. Today, most of the data engineers, data scientists and data analysts prefer using python as their main programming language of choice to build complex use cases.
 
In this session, I will explore Flink APIs wearing the non-JVM hat and will deep dive into pyflink Table APIs and UDFs. Pyflink appeals to python developers since complex stream processing techniques like windowing, event time semantics could be written in simple python DSLs,.
 
I will also look at how pyflink Table API and Flink SQL could work hand-in-hand in developing streaming pipelines. 
 
The session will also have a short demo showcasing how pyflink ingests fast moving data from Kafka and runs pyflink Table API DSLs to process such streams.