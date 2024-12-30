---
title: "Community Series recap: How modern engines unlock the full potential of Apache Superset"
description: "Sida Shen from StarRocks introduces advanced techniques for optimizing the use of Apache Superset, a leading open-source data visualization and analytics platform."
date: 2024-12-11
images: ["event-superset.png"]
categories: ["News"]

---

<div class="py-3">
  <div class="row">
  <div class="col-12 pb-3 pe-lg-5">
    <h1 style="font-size:2.5rem;padding-bottom:15px">Community Series recap: How modern engines unlock the full potential of Apache Superset</h1>
    <div class="ratio ratio-16x9" style="max-width:890px;">
     <iframe src="https://www.youtube.com/embed/He52l9ra1MY" allowfullscreen></iframe>
    </div>
  </div>
</div>
</div>


<h3>Summary:</h3>
<p>This session, part of the Open Source Analytics (OSA) Conference 2024 series, introduced advanced techniques for optimizing the use of Apache Superset, a leading open-source data visualization and analytics platform. The speaker, Sida Shen from StarRocks, covered the following key points:
</p>
<ol>
  <li><b>Introduction to Apache Superset:</b>
    <ul>
      <li>A lightweight, open-source platform for data exploration and visualization.</li>
      <li>Provides drag-and-drop dashboard creation without requiring coding.</li>
      <li>Focuses on leveraging existing data infrastructure without duplicating data.</li>
    </ul>
  </li>
  <li><b>Challenges in Using Superset:</b>
    <ul>
      <li>Performance issues such as slow dashboard loading and unpredictable query times.</li>
      <li>Complex architectures require separate data warehousing solutions for optimized performance.</li>
      <li>High costs and challenges in pre-computation pipelines for handling diverse datasets.</li>
    </ul>
  </li>
  <li><b>Optimizing Superset Performance:</b>
    <ul>
      <li>Discussed strategies such as data partitioning, indexing, and materialized views to improve query speed.</li>
      <li>Highlighted the importance of choosing the right compute engine optimized for analytics.</li>
    </ul>
  </li>
  <li><b>Features of StarRocks:</b>
    <ul>
      <li>A highly optimized open-source engine that supports advanced features like real-time data ingestion, columnar storage, and in-memory data shuffling.</li>
      <li>Delivers superior performance for analytical queries, even on complex workloads involving large datasets.</li>
    </ul>
  </li>
  <li><b>Materialized Views (MVs):</b>
    <ul>
      <li>Explained how StarRocks' materialized views can pre-compute and optimize queries automatically without requiring dashboard reconfiguration.</li>
      <li>Demonstrated dynamic query rewriting capabilities to improve user experience and efficiency.</li>
    </ul>
  </li>
  <li><b>Lakehouse Performance:</b>
    <ul>
      <li>Addressed the challenges of integrating data lakes with analytics, such as high latency and metadata inefficiencies.</li>
      <li>Showcased how StarRocks bridges the gap between data lakes and traditional warehouses, achieving near-parity in performance while maintaining flexibility.</li>
    </ul>
  </li>
  <li><b>Demo Highlights:</b>
    <ul>
      <li>Showcased Superset dashboards powered by StarRocks, emphasizing real-time query acceleration.</li>
      <li>Demonstrated the use of materialized views and query rewrites to drastically reduce execution times.</li>
    </ul>
  </li>
  <li><b>Future of Analytics:</b>
    <ul>
      <li>Discussed evolving trends in open formats (like Iceberg, Delta, and Hudi) and their potential to reduce dependency on proprietary data warehouses.</li>
      <li>Emphasized the importance of evolving table formats and real-time capabilities in lakehouse architectures.</li>
    </ul>
  </li>
</ol>


<p style="font-size:15px;">Disclaimer: This summary was generated using AI and is intended for informational purposes only. Please refer to the original session or material for complete accuracy and context.</p><br />
