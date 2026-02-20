---
title: "10 Predictions for Data Infrastructure in 2026"
description: "What we see coming in the year ahead"
date: 2025-12-31
images: ["2026-predictions.jpg"]
categories: ["News"]
canonical: "https://columnar.tech/blog/2026-predictions"
---

<div class="py-3">
  <div class="row">
  <div class="col-12 pb-3 pe-lg-5">
    <h1 style="font-size:2.5rem;">10 Predictions for Data Infrastructure in 2026</h1>
    <p style="font-size:0.75em; margin-top: 5px;">By Ian Cook | December 31, 2025</p>
    <div class="ratio ratio-16x9 py-3" style="max-width:890px;">
      <img src="2026-predictions.jpg" alt="10 Predictions for Data Infrastructure in 2026" />
    </div>
  </div>
</div>
</div>

*This post was originally published on [Columnar](https://columnar.tech/blog/2026-predictions).*

As we close the books on 2025, the data infra landscape feels markedly different than it did twelve months ago. In a year of accelerating change, the industry has been defined by both high-profile disruptions and quiet, foundational shifts. At Columnar, our work to define the next era of data connectivity gives us a front-row seat to the structural movements happening below the surface. Here's what we see coming in 2026.

## Prediction 1: The boundaries between analytical and operational systems, which have blurred in recent years, will get even blurrier—but not in the way many anticipated.

There is a long history of prognosticating about the future of transactional (OLTP) and analytic (OLAP) data systems. Will they converge into a beautiful HTAP (hybrid transactional/analytical processing) dream, or are there deep fundamental reasons for them to forever remain separate? Is HTAP, like nuclear fusion, destined to be "always 30 years away"? 2025 certainly provided fodder for this discussion, notably with the acquisitions of Postgres companies by big analytic vendors (Neon by Databricks, Crunchy Data by Snowflake) and the preponderance of DuckDB/PostgreSQL mashups like the DuckDB Postgres Extension, pg_duckdb, pg_mooncake (created by Mooncake Labs, which was acquired by Databricks in 2025), and pg_lake (from Snowflake).

But we're less interested in this well-worn OLTP/OLAP discussion and more interested in the quiet transformation in how analytic systems are actually being used. Analytic data systems have become so widely integrated into operational and customer-facing applications that the name "analytic" is starting to seem like a vestige of a bygone era. Today, these systems provide the bedrock for applications far beyond traditional analytics, powering everything from autonomous AI agents to data-rich graphical consumer app experiences. These systems have been strained by needing to serve these new roles, which often come with orders of magnitude more users and less predictability than internal reporting workloads. But they have evolved, and it has been a boon for many data infrastructure vendors who have found a market vastly larger than the back-office analytics market of yesteryear. We expect this transformation to accelerate in 2026.

## Prediction 2: The Apache Arrow ecosystem will continue to grow rapidly, while revealing growing strain around funding and maintenance of critical shared infrastructure.

As Arrow approaches the 10th anniversary of its formation as an Apache Software Foundation (ASF) project in February, its success is undeniable. Many members of the core Arrow development community met in Paris this year for the inaugural Arrow Summit, reflecting on a project that has expanded its footprint across the entire data ecosystem. Several years ago, the core team stopped trying to update the Powered by Arrow page on the project website, because Arrow is now so deeply embedded in the stack that listing its users is like trying to list every phone that's equipped with a USB-C port. If you have a data stack, Arrow is almost certainly in it, even if you don't see it. The main Python library for Arrow alone is downloaded more than 250 million times per month.

However, as Arrow becomes ubiquitous, it risks neglect from a kind of bystander effect. Much of the funding for Arrow's development has come in bursts from venture-backed technology companies building products that use Arrow. But amidst the churn and shakeout of this competitive ecosystem, it is difficult to ensure the steady funding that keeps experienced developers focused on the project over the long term—especially on the unglamorous maintenance work that ensures the project is safe and reliable for developers to build with. Furthermore, the widespread emergence of vibe coding in 2025 lowered the barrier to entry for new contributors, thereby increasing the burden on the project's maintainers to review a flood of new code. This is why initiatives like the Arctos Alliance are so important for sustainable maintenance of Arrow, and why we expect the tension between widespread usage and maintainer capacity to come to a head in 2026.

## Prediction 3: ADBC adoption will broaden significantly, with more vendors, drivers, and clients converging on a common database connectivity layer.

Arrow Database Connectivity (ADBC) is still relatively young, but its embrace by major players like Databricks, dbt Labs, Microsoft, and Snowflake has propelled it into the spotlight. It is quickly becoming the standard interface for systems that need to move columnar query results efficiently. We are, full disclosure, very much talking our own book here: when we announced Columnar—a company built with ADBC at its core—and launched the ADBC Driver Foundry, it prompted a wave of interest from other projects and vendors looking to escape the poor performance and outdated developer experience of legacy connectivity APIs like ODBC and JDBC. Throughout 2026, we expect ADBC to continue its rapid ascent, increasingly solidifying its position as the default connectivity layer for analytic applications—which includes many operational, AI, and consumer-facing use cases as discussed above.

## Prediction 4: Awareness and use of Arrow will expand in the JavaScript and TypeScript ecosystem.

As Arrow has approached ubiquity and ADBC has cemented its status as a standard, one notable gap in the ecosystem has been the world of JavaScript, TypeScript, and the browser. Although there is an official implementation of Arrow for TS/JS, it hasn't received the same level of investment as most other core Arrow implementations. While there are notable examples of products that use Arrow to accelerate data transfer to and from the browser (including Streamlit and Perspective), the ecosystem remains fragmented. Despite the massive footprint of Node.js applications and the technical feasibility of using ADBC drivers from Node.js, the plumbing isn't quite ready for prime time. We expect this to change in 2026, driven by a growing awareness among full-stack developers that shipping JSON over the wire is a bottleneck, and by the emergence of TS/JS as a more mainstream option for building data-intensive applications.

## Prediction 5: Open table formats—especially Apache Iceberg—will climb the slope of enlightenment, emerging from hype and disillusionment to become proven infrastructure.

If you spent time on LinkedIn in 2025, you might have been confused by the discourse around open table formats. There were simultaneous declarations of imminent death for Iceberg and Delta Lake alongside declarations of their total dominance. We even saw the release of DuckLake, which was (depending on who you ask) either a brilliant reimagination of table formats or a return to the bad old days of Hive on Hadoop. But quietly in the background, away from the hot takes, open table formats became ever more mainstream. Iceberg, in particular, is thriving, with an extremely active developer and user community that now fills local meetups worldwide and convened for the inaugural Iceberg Summit in April. This momentum is matched by technical ambition, including the addition of a new Variant data type in Iceberg version 3, and massive operational scale: in its first year alone, Amazon S3 Tables for Iceberg grew to host over 400,000 tables, signaling that the standard has truly arrived in production. In 2026, we expect the noise to settle and the real work to continue.

## Prediction 6: Multi-engine data stacks will become increasingly mainstream as organizations prioritize faster innovation cycles, better interoperability, and cost savings.

Connected directly to the maturation of open table formats is the decoupling of storage and compute. This has moved beyond architecture diagrams and into production. Because data is now residing in vendor-neutral open formats like Iceberg, organizations are no longer locked into a single data warehouse vendor. In 2026, we will see further normalization of composable, multi-engine stacks. While scale-out clusters will retain their role for massive batch workloads, organizations will increasingly integrate agile engines like DuckDB and DataFusion—capitalizing not just on their efficiency, but on rapid release cycles that deliver cutting-edge features long before monolithic data warehouses can catch up.

## Prediction 7: The availability of composable open source building blocks like DuckDB and DataFusion will continue to fuel an explosion of innovation by vendors.

The most transformative impact of engines like DuckDB and DataFusion might not be in how data teams deploy them directly, but in how vendors use them to architect the next generation of data infrastructure tools. We are witnessing the end of the "monolithic black box" era, replaced by composable systems assembled from open source components. A vibrant ecosystem has already emerged on these foundations: from DataFusion-native innovators like Xorq, Spice AI, Bauplan Labs, and Embucket, to DuckDB-centric players ranging from MotherDuck to newer entrants like Greybeam, GizmoData, and Query.Farm. This shift extends to the giants, with Cloudflare's R2 SQL and dbt Labs' Fusion engine both building on DataFusion. In 2026, as the technical barrier to entry moves even lower, we expect to see more specialized tools challenging the incumbents.

## Prediction 8: As open standards like Arrow, Parquet, and Iceberg see broader adoption, they will be increasingly pulled between two competing forces: the need for simplicity and broad compatibility, and the pressure to innovate and expand.

Success brings new challenges. As Julien Le Dem notes in his post "Column Storage for the AI Era", standards eventually face a difficult trade-off. On one hand, there is a need for simplicity to maintain a dense compatibility matrix across dozens of implementations. On the other hand, there is immense pressure to innovate and incorporate new capabilities. In 2026, managing this tension will be the primary governance challenge for these projects: how to evolve without breaking the ecosystem that made them successful in the first place.

## Prediction 9: The most significant advances in data infrastructure will come not from entirely new systems, but from work on interoperability, standards, and the foundational plumbing required for coordination and efficiency at scale.

When anyone can vibe code an app using an LLM, software is no longer the scarce resource. The scarcity—and the bottleneck—shifts to coordination. As software creation gets cheaper, value shifts from who can build to what can connect. Millions of independently developed apps only matter if they can interoperate reliably, safely, and at scale. Without shared standards, these ecosystems devolve into piles of brittle adapters and slow glue code. Open standards turn individual creativity into collective efficiency by eliminating layers of translation. In 2026, the "boring" work of alignment will be the most high-leverage engineering work available.

## Prediction 10: As AI agents move into production, the industry will focus on the surprisingly hard problem of making tabular data fast, safe, and accessible.

While much of the AI hype focuses on unstructured data (text, video, images), the operational reality of agents requires them to interact with the structured truth of the business. As Wes McKinney pointed out in his recent post "Can LLMs give us AGI if they are bad at arithmetic?", there is a massive gap between the probabilistic nature of LLMs and the deterministic nature of tabular data analysis. In 2026, we will learn that simply slapping an MCP server on top of a data warehouse isn't enough. True agentic workflows require high-speed, type-safe, and governed access to analytical data, as well as deeper thinking about how to efficiently process tables for tool calls and context windows. Building the infrastructure to safely and easily support these high-performance workflows is the core mission driving our team at Columnar.

---

If 2025 was a year of experimentation, 2026 will be defined by operational rigor. From the maturation of foundational open standards to the mainstreaming of multi-engine architectures on decoupled storage, the industry is moving toward infrastructure that is robust, efficient, and capable of supporting the next generation of autonomous applications. The underlying plumbing has never mattered more, and we are excited to continue building it.
