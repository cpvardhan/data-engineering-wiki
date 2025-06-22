<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Module-2 – Python ETL & CI</title>
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
        <h1>Module-2 – Python ETL & CI</h1>

        <h2>🎯 Objectives</h2>
        <ul>
            <li>Build modular ETL pipelines in Python (Polars/pandas).</li>
            <li>Apply best practices: testing, logging, error handling.</li>
            <li>Set up CI/CD workflows for data code.</li>
        </ul>

        <h2>🗓️ Weekly Plan</h2>
        <ul class="weekly-plan">
            <li><strong>Week 5</strong> – pandas vs Polars; memory & performance trade-offs.</li>
            <li><strong>Week 6</strong> – ETL patterns: idempotency, config-driven pipelines.</li>
            <li><strong>Week 7</strong> – Code quality: pytest fixtures, structured logging, retry logic.</li>
            <li><strong>Week 8</strong> – CI basics: GitHub Actions for tests & linting; packaging with Poetry.</li>
        </ul>

        <h2>🔑 Subtopics & Key Concepts</h2>

        <h3>1. Data Libraries</h3>
        <ul>
            <li><strong>pandas</strong>: DataFrame basics, IO APIs, groupbys.</li>
            <li><strong>Polars</strong>: lazy vs eager execution, memory efficiency.</li>
            <li><strong>PyArrow</strong>: zero-copy IPC, Parquet integration.</li>
        </ul>

        <h3>2. ETL Design Patterns</h3>
        <ul>
            <li><strong>Incremental loads</strong>: watermark columns, CDC.</li>
            <li><strong>Idempotent pipelines</strong>: safe retries without duplicates.</li>
            <li><strong>Configuration</strong>: YAML/JSON configs, environment variables.</li>
        </ul>

        <h3>3. Testing & Error Handling</h3>
        <ul>
            <li><strong>pytest fixtures</strong>: reusable setup/teardown.</li>
            <li><strong>Mocking I/O</strong>: `monkeypatch`, `requests-mock`.</li>
            <li><strong>Logging</strong>: Python `logging` module, retry/backoff strategies.</li>
        </ul>

        <h3>4. Packaging & CI/CD</h3>
        <ul>
            <li><strong>Poetry</strong>: `pyproject.toml`, lock files.</li>
            <li><strong>GitHub Actions</strong>: workflows, matrix builds, artifacts.</li>
        </ul>

        <h2>🔨 Mini-Projects</h2>
        <ul class="mini-projects">
            <li><strong>CSV→Postgres ETL Library</strong>: create a Python package with unit tests, logging, error handling.</li>
            <li><strong>API Loader</strong>: fetch data from a REST API with retry & backoff.</li>
            <li><strong>CI Pipeline</strong>: configure GitHub Actions to run tests & lint on every push.</li>
        </ul>

        <h2>📚 Resources</h2>
        <ul class="resources">
            <li>Polars & pandas documentation</li>
            <li>pytest official guide</li>
            <li>GitHub Actions for Python projects</li>
        </ul>
    </div>
</body>
</html>
