<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Module-6 – ADF & Synapse</title>
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
        <h1>Module-6 – ADF & Synapse</h1>

        <h2>🎯 Objectives</h2>
        <ul>
            <li>Build advanced ETL/ELT pipelines in Azure Data Factory.</li>
            <li>Tune Synapse serverless & dedicated SQL pools for performance & cost.</li>
            <li>Automate CI/CD for data workloads.</li>
        </ul>

        <h2>🗓️ Weekly Plan</h2>
        <ul class="weekly-plan">
            <li><strong>Week 21</strong> – ADF fundamentals: pipelines, activities, parameters.</li>
            <li><strong>Week 22</strong> – Mapping Data Flows: transformations & expression builder.</li>
            <li><strong>Week 23</strong> – Synapse Analytics: serverless vs dedicated tuning.</li>
            <li><strong>Week 24</strong> – CI/CD: ARM templates, Git integration, releases.</li>
        </ul>

        <h2>🔑Key Concepts</h2>
        <h3>ADF Core Concepts</h3>
        <ul>
            <li>Linked services, datasets, pipelines, triggers.</li>
        </ul>
        <h3>Integration Runtimes</h3>
        <ul>
            <li>Azure vs self-hosted IR, cost & performance trade-offs.</li>
        </ul>
        <h3>Mapping Data Flows</h3>
        <ul>
            <li>Derived columns, aggregations, join behavior.</li>
        </ul>
        <h3>Synapse Analytics</h3>
        <ul>
            <li>Serverless SQL pool vs dedicated SQL pool: MPP, DWUs, distributions.</li>
        </ul>
        <h3>CI/CD Practices</h3>
        <ul>
            <li>ARM templates, Git branch strategies, release pipelines.</li>
        </ul>

        <h2>🔨 Mini-Projects</h2>
        <ul class="mini-projects">
            <li><strong>End-to-End ADF</strong>: API → ADLS → Databricks → Synapse.</li>
            <li><strong>Complex Data Flow</strong>: multi-step transformation & error handling.</li>
            <li><strong>Pipeline CI</strong>: deploy via Azure DevOps or GitHub Actions.</li>
        </ul>

        <h2>📚 Resources</h2>
        <ul class="resources">
            <li>Azure Data Factory documentation</li>
            <li>Azure Synapse performance tuning guide</li>
            <li>Azure DevOps Pipelines docs</li>
        </ul>
    </div>
</body>
</html>
