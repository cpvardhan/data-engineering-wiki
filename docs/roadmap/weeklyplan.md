<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width,initial-scale=1.0"/>
  <title>📅 30-Week Azure Data-Engineering Study Plan</title>
  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
      margin: 0; padding: 1rem;
      background: #f9f9f9; color: #333;
    }
    .container { max-width: 800px; margin: auto; }
    h1 { text-align: center; margin-bottom: 1rem; }
    details {
      background: #fff; border: 1px solid #ddd; border-radius: 6px;
      margin-bottom: 1rem; padding: 0.5rem 1rem;
    }
    summary {
      font-size: 1.1rem; font-weight: 600; cursor: pointer;
      padding: 0.5rem 0; list-style: none;
    }
    summary::-webkit-details-marker { display: none; }
    summary:before { content: "▶ "; display: inline-block; transform: rotate(0deg); transition: transform .2s; }
    details[open] summary:before { transform: rotate(90deg); }
    ul { margin: 0.5rem 0 1rem 1.5rem; }
    ul li { margin-bottom: 0.5rem; }
  </style>
</head>
<body>
  <div class="container">
    <h1>📅 30-Week Azure Data-Engineering Study Plan</h1>
    <p style="text-align:center;">Each week ~15–20 hrs. Click a week to expand details.</p>

    <!-- Week 1 -->
    <details>
      <summary>Week 1 🚀 Data-Warehouse Overview; Inmon vs Kimball; Fact/Grain Choices (20 h)</summary>
      <ul>
        <li>📖 Read IBM’s “What is a Data Warehouse?” (1 h)</li>
        <li>📖 Read Inmon’s *Building the Data Warehouse* Intro & Chapter 1 (2 h)</li>
        <li>📖 Read Kimball Toolkit Chapters 1–2 (star schemas & conformed dims) (2 h)</li>
        <li>📹 Watch “Inmon vs Kimball” on YouTube (45 min)</li>
        <li>📝 Sketch 3 fact-table grains for a sample domain (1 h)</li>
        <li>💻 Hands-on: design ERD for transactional & snapshot facts (2 h)</li>
        <li>📝 Build one-page Inmon vs Kimball cheat-sheet (2 h)</li>
        <li>🎓 Create Anki flashcards for key terms (1 h)</li>
        <li>📝 Answer 5 mini “design a DW” prompts (2 h)</li>
        <li>📚 Review & record yourself explaining both approaches (2.5 h)</li>
      </ul>
    </details>

    <!-- Week 2 -->
    <details>
      <summary>Week 2 🔄 Slowly Changing Dimensions (Types 1–6) (18 h)</summary>
      <ul>
        <li>📖 Read Kimball Toolkit Ch 3 on SCD patterns (2 h)</li>
        <li>📖 Read blog posts on Types 4 & 6 from Kimball Group (1 h)</li>
        <li>💻 Hands-on: implement SCD 1/2/3 in SQL on sample data (3 h)</li>
        <li>💻 Build a Python/Polars pipeline for SCD 2 with history table (3 h)</li>
        <li>📝 Write an SQL stored proc for Type 2 merge logic (2 h)</li>
        <li>🎓 Flashcards: pros/cons of each SCD type (1 h)</li>
        <li>📝 Scenario Q&A: 10 design prompts (2 h)</li>
        <li>📚 Review & refine your implementations (4 h)</li>
      </ul>
    </details>

    <!-- Week 3 -->
    <details>
      <summary>Week 3 ⚡ Advanced SQL Performance Tuning (18 h)</summary>
      <ul>
        <li>📖 Read *SQL Performance Explained* Ch 2–4 (3 h)</li>
        <li>💻 Hands-on: run EXPLAIN on 10 analytical queries (2 h)</li>
        <li>💻 Add & test clustered/non-clustered/columnstore indexes (3 h)</li>
        <li>💻 Implement range & hash partitioning; test pruning (2 h)</li>
        <li>📖 Deep dive into columnstore indexes blog (1 h)</li>
        <li>🔨 Mini-Project: optimize a dashboard query on 1 GB dataset (4 h)</li>
        <li>🎓 Flashcards: index & partition concepts (1 h)</li>
        <li>📝 Self-quiz on tuning strategies (2 h)</li>
      </ul>
    </details>

    <!-- Week 4 -->
    <details>
      <summary>Week 4 🧩 OLAP vs Relational; Materialized Views & ETL Mapping (16 h)</summary>
      <ul>
        <li>📖 Read articles on OLAP cube architectures (1 h)</li>
        <li>💻 Create & refresh materialized views in Postgres (2 h)</li>
        <li>📝 Draft source-to-target mapping doc for OLTP→DW (2 h)</li>
        <li>📖 Read Kimball ETL mapping templates (1 h)</li>
        <li>🔨 Mini-Project: build SSAS cube vs relational report, compare perf (5 h)</li>
        <li>🎓 Flashcards: OLAP vs OLTP trade-offs (1 h)</li>
        <li>📝 Write summary of best practices (2 h)</li>
        <li>📚 Review & self-test (2 h)</li>
      </ul>
    </details>

    <!-- Week 5 -->
    <details>
      <summary>Week 5 🐼 pandas vs Polars – Performance & Memory (16 h)</summary>
      <ul>
        <li>📖 Read pandas & Polars docs on IO & lazy APIs (2 h)</li>
        <li>💻 Benchmark CSV→Parquet with pandas vs Polars (3 h)</li>
        <li>📖 Deep dive into Polars lazy mode (1 h)</li>
        <li>💻 Hands-on: build a sample ETL in both libs; measure memory (3 h)</li>
        <li>🔨 Mini-Project: Polars pipeline to clean & write Parquet (4 h)</li>
        <li>🎓 Flashcards: key API differences (1 h)</li>
        <li>📝 Write a short comparison blog snippet (2 h)</li>
      </ul>
    </details>

    <!-- Week 6 -->
    <details>
      <summary>Week 6 🛠️ ETL Design Patterns & Idempotency (16 h)</summary>
      <ul>
        <li>📖 Read articles on config-driven pipelines (1 h)</li>
        <li>💻 Build YAML/JSON-driven ETL framework (3 h)</li>
        <li>💻 Implement watermarking & safe retry logic (2 h)</li>
        <li>🔨 Mini-Project: generic CSV→DB loader with idempotency (5 h)</li>
        <li>🎓 Flashcards: design pattern names & use-cases (1 h)</li>
        <li>📝 Self-review & refine code (4 h)</li>
      </ul>
    </details>

    <!-- Week 7 -->
    <details>
      <summary>Week 7 ⚙️ Testing & Logging in Python (16 h)</summary>
      <ul>
        <li>📖 Read pytest docs on fixtures & parametrization (1 h)</li>
        <li>💻 Write unit tests for ETL transforms (3 h)</li>
        <li>📖 Read Python logging cookbook (1 h)</li>
        <li>💻 Implement structured JSON logging & retries (2 h)</li>
        <li>🔨 Mini-Project: add tests & logs to your Week 6 pipeline (6 h)</li>
        <li>🎓 Review test coverage & log outputs (2 h)</li>
        <li>📝 Quiz yourself on pytest & logging concepts (1 h)</li>
      </ul>
    </details>

    <!-- Week 8 -->
    <details>
      <summary>Week 8 🚦 CI Basics with GitHub Actions (14 h)</summary>
      <ul>
        <li>📖 Read GH Actions Python CI guide (1 h)</li>
        <li>💻 Create `.github/workflows/ci.yml` to run pytest & flake8 (3 h)</li>
        <li>📖 Read Poetry packaging docs (1 h)</li>
        <li>💻 Configure Poetry & lock file for your project (2 h)</li>
        <li>🔨 Mini-Project: integrate CI into your Week 7 repo (5 h)</li>
        <li>🎓 Review CI logs & fix failures (2 h)</li>
      </ul>
    </details>

    <!-- Week 9-12 (Module 3) -->
    <details>
      <summary>Weeks 9–12 🔥 Spark & Delta Performance Module (~18 h/wk)</summary>
      <ul>
        <li><strong>Week 9</strong> – Spark internals (DAG, stages, executors): read *Spark: The Definitive Guide* Ch 1–2, watch internals video, hands-on DAG inspection, mini-project Spark job (18 h)</li>
        <li><strong>Week 10</strong> – Joins & shuffles: read docs on broadcast vs sort-merge, fix skewed joins, project on sample dataset (18 h)</li>
        <li><strong>Week 11</strong> – AQE & caching: read official blog, enable AQE, benchmark with/without cache, mini-project (18 h)</li>
        <li><strong>Week 12</strong> – Delta Lake deep dive: read Delta Lake guide, implement MERGE/Z-ordering, time-travel queries, project (18 h)</li>
      </ul>
    </details>

    <!-- Week 13-16 (Module 4) -->
    <details>
      <summary>Weeks 13–16 🌊 Streaming & Data Quality Module (~17 h/wk)</summary>
      <ul>
        <li><strong>Week 13</strong> – Lambda vs Kappa & Event Hubs basics: articles & hands-on ingestion (17 h)</li>
        <li><strong>Week 14</strong> – Structured Streaming APIs: triggers, output modes, checkpoints, code labs (17 h)</li>
        <li><strong>Week 15</strong> – Stateful processing: window ops, watermark cleanup, demos (17 h)</li>
        <li><strong>Week 16</strong> – Data quality frameworks: Great Expectations suites & dbt tests, quality dashboard (17 h)</li>
      </ul>
    </details>

    <!-- Week 17-20 (Module 5) -->
    <details>
      <summary>Weeks 17–20 🏞️ Azure Lakehouse Module (~16 h/wk)</summary>
      <ul>
        <li><strong>Week 17</strong> – ADLS Gen2 setup & security (RBAC, ACLs, firewall) (16 h)</li>
        <li><strong>Week 18</strong> – Databricks workspace, clusters & notebooks (16 h)</li>
        <li><strong>Week 19</strong> – Unity Catalog governance & lineage (16 h)</li>
        <li><strong>Week 20</strong> – Medallion pattern: implement Bronze/Silver/Gold pipeline (16 h)</li>
      </ul>
    </details>

    <!-- Week 21-24 (Module 6) -->
    <details>
      <summary>Weeks 21–24 🔧 ADF & Synapse Module (~16 h/wk)</summary>
      <ul>
        <li><strong>Week 21</strong> – ADF pipelines: linked services, datasets, triggers (16 h)</li>
        <li><strong>Week 22</strong> – Mapping Data Flows: transformations & expressions (16 h)</li>
        <li><strong>Week 23</strong> – Synapse SQL pools: serverless vs dedicated tuning (16 h)</li>
        <li><strong>Week 24</strong> – CI/CD: ARM templates & Git integration for ADF/Synapse (16 h)</li>
      </ul>
    </details>

    <!-- Week 25-28 (Module 7) -->
    <details>
      <summary>Weeks 25–28 🌐 Fabric Lakehouse & Real-Time Module (~16 h/wk)</summary>
      <ul>
        <li><strong>Week 25</strong> – Fabric architecture: OneLake & shortcuts (16 h)</li>
        <li><strong>Week 26</strong> – Fabric Data Factory pipelines & notebooks (16 h)</li>
        <li><strong>Week 27</strong> – DirectLake in Power BI: live query patterns (16 h)</li>
        <li><strong>Week 28</strong> – Governance & lifecycle: roles, promotion pipelines (16 h)</li>
      </ul>
    </details>

    <!-- Week 29-30 (Module 8) -->
    <details>
      <summary>Weeks 29–30 🎯 Interview & System Design Module (~15 h/wk)</summary>
      <ul>
        <li><strong>Week 29</strong> – Résumé & LinkedIn optimization; project storytelling (15 h)</li>
        <li><strong>Week 30</strong> – Mock interviews: STAR, technical Q&A & system-design drills (15 h)</li>
      </ul>
    </details>

  </div>
</body>
</html>
