---
title: "Community Series recap: Dashtool - A data build tool designed for using Iceberg Materialized Views for data"
description: "Dashtool is a valuable addition for teams looking to optimize their data transformation processes while embracing modern, scalable, and efficient data architectures."
date: 2024-12-03
images: ["event-dashtool.png"]
categories: ["News"]

---

<div class="py-3">
  <div class="row">
  <div class="col-12 pb-3 pe-lg-5">
    <h1 style="font-size:2.5rem;padding-bottom:15px">Community Series recap: Dashtool - A data build tool designed for using Iceberg Materialized Views for data</h1>
    <div class="ratio ratio-16x9" style="max-width:890px;">
     <iframe src="https://www.youtube.com/embed/tksTFG2YoZM?si=-q4UhhRapEjInVHL" allowfullscreen></iframe>
    </div>
  </div>
</div>
</div>


<h3>Summary:</h3>
<p>This session, part of the Open Source Analytics (OSA) Conference 2024 series, introduced Dashtool, an open-source data build tool aimed at simplifying the creation, transformation, and orchestration of data pipelines. It leverages Apache Iceberg Materialized Views to efficiently manage data transformations and updates. The tool allows users to define transformations using declarative SQL SELECT statements, making it accessible to both engineers and analysts. Similar to tools like dbt or SQLMesh, Dashtool analyzes SQL files to build a Directed Acyclic Graph (DAG) and creates corresponding Iceberg Materialized Views for each transformation.</p>

<p>In addition, Dashtool integrates seamlessly with orchestrators like Argo Workflows, enabling automated workflows to keep Materialized Views synchronized with the latest data. By utilizing powerful open-source technologies such as Apache Arrow, Apache Iceberg, and DataFusion, it enhances both performance and scalability in Lakehouse architectures.</p>

<h4>Why is Dashtool needed?</h4>
<ol><li><b>Simplified Data Pipeline Management:</b> With its declarative approach, Dashtool reduces the complexity of designing and managing data workflows, saving time and effort.</li>
<li><b>Efficient Data Processing:</b> Leveraging Iceberg Materialized Views ensures transformations are incremental and efficient, reducing the cost of reprocessing data.</li>
<li><b>Integration with Modern Architectures:</b> Dashtool supports the Lakehouse paradigm, bridging the gap between traditional data lakes and data warehouses.</li>
<li><b>Automation and Orchestration:</b> Its integration with workflow orchestration tools ensures reliable and repeatable data processing.</li>
<li><b>Flexibility:</b> By working natively with SQL, it provides a user-friendly and adaptable interface for a wide range of data use cases.</li>
<li><b>Open-Source Innovation:</b> Built on open-source foundations, Dashtool encourages transparency, community collaboration, and adaptability to evolving needs.</li></ol>

<p>Dashtool is a valuable addition for teams looking to optimize their data transformation processes while embracing modern, scalable, and efficient data architectures.</p>

<p style="font-size:15px;">Disclaimer: This summary was generated using AI and is intended for informational purposes only. Please refer to the original session or material for complete accuracy and context.</p><br />
