<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Module-4 – Streaming & Data Quality</title>
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
        <h1>Module-4 – Streaming &amp; Data Quality</h1>

        <h2>🎯 Objectives</h2>
        <ul>
            <li>Build robust streaming pipelines using Spark Structured Streaming.</li>
            <li>Ingest from Azure Event Hubs or Kafka.</li>
            <li>Implement data-quality checks with Great Expectations &amp; dbt.</li>
        </ul>

        <h2>🗓️ Weekly Plan</h2>
        <ul class="weekly-plan">
            <li><strong>Week 13</strong> – Lambda vs Kappa; Event Hubs fundamentals.</li>
            <li><strong>Week 14</strong> – Structured Streaming: triggers, checkpoints, watermarking.</li>
            <li><strong>Week 15</strong> – Stateful ops: windowed aggregates, late data handling.</li>
            <li><strong>Week 16</strong> – Data quality: GE suites; dbt tests & lineage.</li>
        </ul>

        <h2>🔑 Key Concepts</h2>
        <h3>Ingestion Systems</h3>
        <ul>
            <li>Event Hubs vs Kafka: partitions, consumer groups.</li>
        </ul>
        <h3>Structured Streaming API</h3>
        <ul>
            <li><code>readStream</code>/<code>writeStream</code>, output modes, triggers.</li>
        </ul>
        <h3>Fault Tolerance</h3>
        <ul>
            <li>Checkpoints & write-ahead logs for exactly-once.</li>
        </ul>
        <h3>Stateful Processing</h3>
        <ul>
            <li>Window functions, watermark & state cleanup.</li>
        </ul>
        <h3>Data Quality Frameworks</h3>
        <ul>
            <li>Great Expectations expectations & checkpoints.</li>
            <li>dbt tests: unique, not_null, relationships.</li>
        </ul>

        <h2>🔨 Mini-Projects</h2>
        <ul class="mini-projects">
            <li><strong>JSON Stream → Lakehouse</strong>: consume events → Bronze/Silver Delta.</li>
            <li><strong>Late Data Handling</strong>: manage late events with watermark.</li>
            <li><strong>Quality Suite</strong>: build GE validations + dbt test report.</li>
        </ul>

        <h2>📚 Resources</h2>
        <ul class="resources">
            <li>Spark Structured Streaming guide</li>
            <li>Great Expectations docs</li>
            <li>dbt official documentation</li>
        </ul>
    </div>
</body>
</html>
