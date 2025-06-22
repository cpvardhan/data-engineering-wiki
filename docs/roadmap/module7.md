<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Module-7 – Fabric Lakehouse & Real-Time</title>
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
        <h1>Module-7 – Fabric Lakehouse &amp; Real-Time</h1>

        <h2>🎯 Objectives</h2>
        <ul>
            <li>Leverage Microsoft Fabric’s OneLake unified storage.</li>
            <li>Build real-time dashboards via DirectLake &amp; KQL.</li>
            <li>Enforce workspace governance & item lifecycles.</li>
        </ul>

        <h2>🗓️ Weekly Plan</h2>
        <ul class="weekly-plan">
            <li><strong>Week 25</strong> – Fabric overview: OneLake & shortcuts.</li>
            <li><strong>Week 26</strong> – Fabric Data Factory pipelines & notebooks.</li>
            <li><strong>Week 27</strong> – DirectLake in Power BI: live query patterns.</li>
            <li><strong>Week 28</strong> – Governance: roles, promotion pipelines, lineage.</li>
        </ul>

        <h2>🔑Key Concepts</h2>
        <h3>Fabric Architecture</h3>
        <ul>
            <li>OneLake: single logical lake across workloads; Shortcuts.</li>
        </ul>
        <h3>Pipeline Orchestration</h3>
        <ul>
            <li>Fabric Data Factory: activities, triggers, monitoring.</li>
            <li>Notebook workflows: Python &amp; SQL scheduling.</li>
        </ul>
        <h3>DirectLake Mode</h3>
        <ul>
            <li>Live connection, query folding &amp; limitations.</li>
        </ul>
        <h3>Kusto Query Language (KQL)</h3>
        <ul>
            <li>Basic syntax: where, summarize, real-time tables.</li>
        </ul>
        <h3>Governance & Lifecycle</h3>
        <ul>
            <li>Workspace roles: Admin/Member/Viewer; Git integration; lineage.</li>
        </ul>

        <h2>🔨 Mini-Projects</h2>
        <ul class="mini-projects">
            <li><strong>OneLake Ingest</strong>: batch + streaming data into Lakehouse.</li>
            <li><strong>Real-Time Dashboard</strong>: DirectLake Power BI report.</li>
            <li><strong>Governance Setup</strong>: role-based access & deployment pipeline.</li>
        </ul>

        <h2>📚 Resources</h2>
        <ul class="resources">
            <li>Microsoft Fabric (DP-700/DP-600) documentation</li>
            <li>OneLake best practices</li>
            <li>Power BI DirectLake guide</li>
        </ul>
    </div>
</body>
</html>
