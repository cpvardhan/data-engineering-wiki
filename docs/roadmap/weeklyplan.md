# 📅 30-Week Azure Data-Engineering Study Plan

Each week ~15–20 hrs. Click a week to expand details.

---

### Week 1 🚀 Data-Warehouse Overview; Inmon vs Kimball; Fact/Grain Choices (20 h)

* 📖 Read IBM’s “What is a Data Warehouse?” (1 h)
* 📖 Read Inmon’s *Building the Data Warehouse* Intro & Chapter 1 (2 h)
* 📖 Read Kimball Toolkit Chapters 1–2 (star schemas & conformed dims) (2 h)
* 📹 Watch “Inmon vs Kimball” on YouTube (45 min)
* 📝 Sketch 3 fact-table grains for a sample domain (1 h)
* 💻 Hands-on: design ERD for transactional & snapshot facts (2 h)
* 📝 Build one-page Inmon vs Kimball cheat-sheet (2 h)
* 🎓 Create Anki flashcards for key terms (1 h)
* 📝 Answer 5 mini “design a DW” prompts (2 h)
* 📚 Review & record yourself explaining both approaches (2.5 h)

### Week 2 🔄 Slowly Changing Dimensions (Types 1–6) (18 h)

* 📖 Read Kimball Toolkit Ch 3 on SCD patterns (2 h)
* 📖 Read blog posts on Types 4 & 6 from Kimball Group (1 h)
* 💻 Hands-on: implement SCD 1/2/3 in SQL on sample data (3 h)
* 💻 Build a Python/Polars pipeline for SCD 2 with history table (3 h)
* 📝 Write an SQL stored proc for Type 2 merge logic (2 h)
* 🎓 Flashcards: pros/cons of each SCD type (1 h)
* 📝 Scenario Q&A: 10 design prompts (2 h)
* 📚 Review & refine your implementations (4 h)

### Week 3 ⚡ Advanced SQL Performance Tuning (18 h)

* 📖 Read *SQL Performance Explained* Ch 2–4 (3 h)
* 💻 Hands-on: run EXPLAIN on 10 analytical queries (2 h)
* 💻 Add & test clustered/non-clustered/columnstore indexes (3 h)
* 💻 Implement range & hash partitioning; test pruning (2 h)
* 📖 Deep dive into columnstore indexes blog (1 h)
* 🔨 Mini-Project: optimize a dashboard query on 1 GB dataset (4 h)
* 🎓 Flashcards: index & partition concepts (1 h)
* 📝 Self-quiz on tuning strategies (2 h)

### Week 4 🧩 OLAP vs Relational; Materialized Views & ETL Mapping (16 h)

* 📖 Read articles on OLAP cube architectures (1 h)
* 💻 Create & refresh materialized views in Postgres (2 h)
* 📝 Draft source-to-target mapping doc for OLTP→DW (2 h)
* 📖 Read Kimball ETL mapping templates (1 h)
* 🔨 Mini-Project: build SSAS cube vs relational report, compare perf (5 h)
* 🎓 Flashcards: OLAP vs OLTP trade-offs (1 h)
* 📝 Write summary of best practices (2 h)
* 📚 Review & self-test (2 h)

### Week 5 🐼 pandas vs Polars – Performance & Memory (16 h)

* 📖 Read pandas & Polars docs on IO & lazy APIs (2 h)
* 💻 Benchmark CSV→Parquet with pandas vs Polars (3 h)
* 📖 Deep dive into Polars lazy mode (1 h)
* 💻 Hands-on: build a sample ETL in both libs; measure memory (3 h)
* 🔨 Mini-Project: Polars pipeline to clean & write Parquet (4 h)
* 🎓 Flashcards: key API differences (1 h)
* 📝 Write a short comparison blog snippet (2 h)

### Week 6 🛠️ ETL Design Patterns & Idempotency (16 h)

* 📖 Read articles on config-driven pipelines (1 h)
* 💻 Build YAML/JSON-driven ETL framework (3 h)
* 💻 Implement watermarking & safe retry logic (2 h)
* 🔨 Mini-Project: generic CSV→DB loader with idempotency (5 h)
* 🎓 Flashcards: design pattern names & use-cases (1 h)
* 📝 Self-review & refine code (4 h)

### Week 7 ⚙️ Testing & Logging in Python (16 h)

* 📖 Read pytest docs on fixtures & parametrization (1 h)
* 💻 Write unit tests for ETL transforms (3 h)
* 📖 Read Python logging cookbook (1 h)
* 💻 Implement structured JSON logging & retries (2 h)
* 🔨 Mini-Project: add tests & logs to your Week 6 pipeline (6 h)
* 🎓 Review test coverage & log outputs (2 h)
* 📝 Quiz yourself on pytest & logging concepts (1 h)

### Week 8 🚦 CI Basics with GitHub Actions (14 h)

* 📖 Read GH Actions Python CI guide (1 h)
* 💻 Create `.github/workflows/ci.yml` to run pytest & flake8 (3 h)
* 📖 Read Poetry packaging docs (1 h)
* 💻 Configure Poetry & lock file for your project (2 h)
* 🔨 Mini-Project: integrate CI into your Week 7 repo (5 h)
* 🎓 Review CI logs & fix failures (2 h)

### Weeks 9–12 🔥 Spark & Delta Performance Module (~18 h/wk)

* **Week 9** – Spark internals (DAG, stages, executors): read *Spark: The Definitive Guide* Ch 1–2, watch internals video, hands-on DAG inspection, mini-project Spark job (18 h)
* **Week 10** – Joins & shuffles: read docs on broadcast vs sort-merge, fix skewed joins, project on sample dataset (18 h)
* **Week 11** – AQE & caching: read official blog, enable AQE, benchmark with/without cache, mini-project (18 h)
* **Week 12** – Delta Lake deep dive: read Delta Lake guide, implement MERGE/Z-ordering, time-travel queries, project (18 h)

### Weeks 13–16 🌊 Streaming & Data Quality Module (~17 h/wk)

* **Week 13** – Lambda vs Kappa & Event Hubs basics: articles & hands-on ingestion (17 h)
* **Week 14** – Structured Streaming APIs: triggers, output modes, checkpoints, code labs (17 h)
* **Week 15** – Stateful processing: window ops, watermark cleanup, demos (17 h)
* **Week 16** – Data quality frameworks: Great Expectations suites & dbt tests, quality dashboard (17 h)

### Weeks 17–20 🏞️ Azure Lakehouse Module (~16 h/wk)

* **Week 17** – ADLS Gen2 setup & security (RBAC, ACLs, firewall) (16 h)
* **Week 18** – Databricks workspace, clusters & notebooks (16 h)
* **Week 19** – Unity Catalog governance & lineage (16 h)
* **Week 20** – Medallion pattern: implement Bronze/Silver/Gold pipeline (16 h)

### Weeks 21–24 🔧 ADF & Synapse Module (~16 h/wk)

* **Week 21** – ADF pipelines: linked services, datasets, triggers (16 h)
* **Week 22** – Mapping Data Flows: transformations & expressions (16 h)
* **Week 23** – Synapse SQL pools: serverless vs dedicated tuning (16 h)
* **Week 24** – CI/CD: ARM templates & Git integration for ADF/Synapse (16 h)

### Weeks 25–28 🌐 Fabric Lakehouse & Real-Time Module (~16 h/wk)

* **Week 25** – Fabric architecture: OneLake & shortcuts (16 h)
* **Week 26** – Fabric Data Factory pipelines & notebooks (16 h)
* **Week 27** – DirectLake in Power BI: live query patterns (16 h)
* **Week 28** – Governance & lifecycle: roles, promotion pipelines (16 h)

### Weeks 29–30 🎯 Interview & System Design Module (~15 h/wk)

* **Week 29** – Résumé & LinkedIn optimization; project storytelling (15 h)
* **Week 30** – Mock interviews: STAR, technical Q&A & system-design drills (15 h)