---
title: "Reinventing Kafka in the Data Streaming Era"
slug: reinventing-kafka-in-the-data-streaming-era
date: 2023-11-26
authors:
 - Jun Rao
time_start: 2023-12-12T08:30:00-04:00
time_end: 2023-12-12T09:00:00-04:00
track: Infrastructure
images:
 - JunRao.jpg
featured: true 
slides: 2023/ReinventingKafka.pdf
---

Many enterprises are adopting data streaming platforms to take actions on what's happening in the business in real time. Apache Kafka is becoming the standard for building this platform. In this talk, I will first provide an overview of Kafka and its eco-system: with Kafka as the storage layer, systems like Apache Flink as the real time processing layer, and an integration layer that connects any data sources and sinks. Then, I will talk about a couple of recent innovations. The first one is on how Cloud makes the adoption of the data streaming platform much easier and how we are evolving Kafka to be more cloud-native. The second one is on the two phase-commit support in Kafka and Flink and how it allows event-driven applications to be more easily built with the exactly-once semantic. 