---
title: "OLAP in your App: Integrating realtime & agentic analytics into your app"
speakers:
 - Chris Crane
topics: 
 - Crazy New Tech
day: 20251
room: A
timeslot: 6
time_start: 2025-11-04T17:30:00.000Z
time_end: 2025-11-04T18:00:00.000Z
gridarea: 5/2/6/3
video: https://youtu.be/41eQikJcuU0
slides: 2025/olap-in-your-app_-integrating-realtime-agentic-analytics-into-your-app.pdf
---

Modern analytics experiences demand “conversation-fast” backends—systems that serve the requests of an agent or LLM in real time at the speed of a natural conversation.

In this talk, we’ll get deep into an open-source reference architecture for powering conversational AI and real-time analytics in user-facing applications. We’ll get hands-on in the code, and explore practical patterns for integrating streaming and analytical infrastructure into your web application, including AI chat systems.

We’ll focus on a reference architecture that integrates transactional (Postgres) and analytical engines (ClickHouse®), along with RedPanda for streaming, a React web app frontend, and MCP interfaces for enabling LLM chat within the app.

The whole analytics stack is defined in code using the MooseStack open source framework. https://docs.fiveonefour.com/moose

This architecture ensures the low-latency responsiveness users expect with analytics visualizations and conversational AI, and a modern, local-first developer experience that integrates naturally into your stack.