<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Module-3 – Spark & Delta Performance</title>
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
        <nav><a href="../index.html">← Back to Road-map</a></nav>
        <h1>Module-3 – Spark &amp; Delta Performance</h1>

        <h2>🎯 Objectives</h2>
        <ul>
            <li>Master Spark DataFrame API &amp; Catalyst optimizer.</li>
            <li>Optimize jobs: partitioning, caching, broadcast joins, AQE.</li>
            <li>Leverage Delta Lake: ACID, schema evolution, time travel.</li>
        </ul>

        <h2>🗓️ Weekly Plan</h2>
        <ul class="weekly-plan">
            <li><strong>Week 9</strong> – Spark architecture: DAG, stages, tasks, executors.</li>
            <li><strong>Week 10</strong> – Performance tuning: shuffles, partitioning, bucketing, broadcast hints.</li>
            <li><strong>Week 11</strong> – AQE &amp; advanced caching strategies.</li>
            <li><strong>Week 12</strong> – Delta Lake deep dive: MERGE, Z-ordering, compaction, time travel.</li>
        </ul>

        <h2>🔑Key Concepts</h2>

        <h3>1. Spark APIs</h3>
        <ul>
            <li>RDD vs DataFrame vs Dataset.</li>
        </ul>
        <h3>2. Catalyst Optimizer</h3>
        <ul>
            <li>Logical plan → optimized logical → physical plan.</li>
        </ul>
        <h3>3. Joins & Shuffles</h3>
        <ul>
            <li>Broadcast joins vs shuffle joins, skew mitigation.</li>
        </ul>
        <h3>4. File Formats</h3>
        <ul>
            <li>Parquet internals, Delta Lake commit log.</li>
        </ul>
        <h3>5. Delta Lake Features</h3>
        <ul>
            <li>ACID transactions, time travel, schema evolution.</li>
        </ul>
        <h3>6. Partitioning & Z-Ordering</h3>
        <ul>
            <li>Static vs dynamic partitioning, Z-order clustering.</li>
        </ul>

        <h2>🔨 Mini-Projects</h2>
        <ul class="mini-projects">
            <li><strong>Taxi Data Pipeline</strong>: Ingest 1 GB CSV → Delta Bronze/Silver/Gold on ADLS Gen2.</li>
            <li><strong>Skew Handling</strong>: Benchmark &amp; fix a skewed join via broadcast/salting.</li>
            <li><strong>Delta Demo</strong>: Implement schema evolution &amp; time-travel queries.</li>
        </ul>

        <h2>📚 Resources</h2>
        <ul class="resources">
            <li>Databricks Spark documentation</li>
            <li>Delta Lake official guide</li>
            <li><em>Spark: The Definitive Guide</em> by Bill Chambers &amp; Matei Zaharia</li>
        </ul>
    </div>
</body>
</html>
