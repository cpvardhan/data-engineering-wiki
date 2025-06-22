<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Module-1 – DW & SQL Foundations</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            max-width: 900px;
            margin: auto;
            background: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            color: #0056b3;
        }
        h1 {
            border-bottom: 2px solid #0056b3;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }
        h2 {
            margin-top: 30px;
            border-bottom: 1px solid #eee;
            padding-bottom: 5px;
        }
        ul {
            list-style-type: disc;
            margin-left: 20px;
        }
        ul ul {
            list-style-type: circle;
        }
        strong {
            color: #0056b3;
        }
        .weekly-plan strong {
            color: #333;
        }
        .mini-projects ul {
            list-style-type: decimal;
        }
        .resources ul {
            list-style-type: square;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Module-1 – DW & SQL Foundations</h1>

        <h2>🎯 Objectives</h2>
        <ul>
            <li>Grasp dimensional-modeling patterns (Kimball vs Inmon). </li>
            <li>Master advanced Slowly Changing Dimensions (Types 1–6). </li>
            <li>Optimize SQL queries for analytics. </li>
            <li>Design a small data-warehouse schema end-to-end.</li>
        </ul>

        <h2>🗓️ Weekly Plan</h2>
        <ul class="weekly-plan">
            <li><strong>Week 1</strong> – Data-warehouse overview; Inmon vs Kimball; fact/grain choices. </li>
            <li><strong>Week 2</strong> – Deep dive into SCD Types 1, 2, 3, 4, 6 (hybrids). </li>
            <li><strong>Week 3</strong> – SQL performance tuning: explain plans, indexing, partitioning. </li>
            <li><strong>Week 4</strong> – OLAP vs relational, materialized views, ETL mapping.</li>
        </ul>

        <h2>🔑 Subtopics & Key Concepts</h2>

        <h3>1. Schema Patterns</h3>
        <ul>
            <li><strong>Star schema</strong>: single fact table + conformed dimensions </li>
            <li><strong>Snowflake schema</strong>: normalized dimension tables </li>
            <li><strong>Galaxy schema</strong>: multiple fact tables sharing dims </li>
        </ul>

        <h3>2. Dimension Table Types</h3>
        <ul>
            <li><strong>Conformed dimensions</strong>: reused across facts </li>
            <li><strong>Junk dimensions</strong>: grouping low-cardinality flags </li>
            <li><strong>Degenerate dimensions</strong>: dimension stored in fact (no separate table) </li>
        </ul>

        <h3>3. Slowly Changing Dimensions (SCD)</h3>
        <ul>
            <li><strong>Type 1</strong>: overwrite old value </li>
            <li><strong>Type 2</strong>: add new row + versioning columns (<code>effective_date</code>, <code>end_date</code>) </li>
            <li><strong>Type 3</strong>: add new attribute column (e.g. <code>prev_address</code>) </li>
            <li><strong>Type 4</strong>: history table separate from current table </li>
            <li><strong>Type 6 (Hybrid)</strong>: combine Types 1/2/3 for specific use cases </li>
        </ul>

        <h3>4. Fact Table Granularity</h3>
        <ul>
            <li><strong>Transaction facts</strong>: one row per event </li>
            <li><strong>Periodic snapshot facts</strong>: one row per period summary </li>
            <li><strong>Accumulating snapshot facts</strong>: track process lifecycle </li>
        </ul>

        <h3>5. Keys & Indexing</h3>
        <ul>
            <li><strong>Surrogate vs natural keys</strong>: hidden identity vs business key </li>
            <li><strong>Clustered vs non-clustered indexes</strong> </li>
            <li><strong>Columnstore indexes</strong>: for high-performance analytics </li>
        </ul>

        <h3>6. Partitioning Strategies</h3>
        <ul>
            <li><strong>Range partitioning</strong>: by date or numeric range </li>
            <li><strong>List/hHash partitioning</strong>: by category or hash function </li>
            <li>Benefits: improved prune, maintenance, parallelism </li>
        </ul>

        <h3>7. Materialized Views</h3>
        <ul>
            <li><strong>Pre-computed aggregations</strong> </li>
            <li><strong>Refresh modes</strong>: on-demand vs incremental </li>
            <li>Use-cases: speeding up complex joins/aggregates </li>
        </ul>

        <h2>🔨 Mini-Projects</h2>
        <ul class="mini-projects">
            <li><strong>Retail DW Prototype</strong>: Model & implement a 3-star schema in Postgres (DDL + ERD). </li>
            <li><strong>SCD Pipeline</strong>: Load CSV to Type-2 dimension with history tracking. </li>
            <li><strong>SQL Tuning Lab</strong>: Optimize 10 complex analytical queries on a 1 GB dataset.</li>
        </ul>

        <h2>📚 Resources</h2>
        <ul class="resources">
            <li>Ralph Kimball’s Dimensional Modeling Techniques </li>
            <li><em>SQL Performance Explained</em> by Markus Winand </li>
            <li>PostgreSQL docs: partitioning & indexing </li>
        </ul>
    </div>
</body>
</html>