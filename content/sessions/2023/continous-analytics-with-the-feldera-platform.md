---
title: "Continous Analytics with the Feldera Platform"
slug: continous-analytics-with-the-feldera-platform
speakers:
 - Mihai Budiu
time_start: 2023-12-14T09:40:00-04:00
time_end: 2023-12-14T09:50:00-04:00
track: Databases
images:
 - /images/sessions/2023/MihaiBudiu.jpg
draft: true
---

The Feldera Continuous Analytics platform enables users to use SQL to express standing queries (as database views). The platform is deployed as a service that receives change streams data and provides as a result near instantaneous updates to all the standing queries as streams of output changes. Feldera is based on Database Stream Processor (DBSP), a new theoretical foundation for incremental view maintenance. DBSP is a language to express streaming computations, and it recently won the best paper award at the 2023 Very Large Databases Conference. The DBSP runtime is available as open-source under an MIT license: https://github.com/feldera/feldera. In this presentation we describe the core concepts of DBSP and how the Feldera is implemented on top of DBSP. We claim that the existing dichotomy between streaming databases and traditional databases is an artificial one, and that both concepts can be naturally unified.