<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Module-5 – Azure Lakehouse</title>
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
        <h1>Module-5 – Azure Lakehouse</h1>

        <h2>🎯 Objectives</h2>
        <ul>
            <li>Secure & configure ADLS Gen2 storage.</li>
            <li>Use Azure Databricks & Unity Catalog for governance.</li>
            <li>Implement Bronze/Silver/Gold medallion pattern.</li>
        </ul>

        <h2>🗓️ Weekly Plan</h2>
        <ul class="weekly-plan">
            <li><strong>Week 17</strong> – ADLS Gen2: hierarchical namespace, RBAC, firewall.</li>
            <li><strong>Week 18</strong> – Databricks: workspace, clusters, notebooks, jobs.</li>
            <li><strong>Week 19</strong> – Unity Catalog: metastore, schemas, permissions.</li>
            <li><strong>Week 20</strong> – Lakehouse best practices & folder layout.</li>
        </ul>

        <h2>🔑Key Concepts</h2>
        <h3>ADLS Gen2 Features</h3>
        <ul>
            <li>Hierarchical namespace, storage tiers, lifecycle policies.</li>
        </ul>
        <h3>Security & Networking</h3>
        <ul>
            <li>RBAC vs POSIX ACLs, service principals, private endpoints.</li>
        </ul>
        <h3>Databricks Administration</h3>
        <ul>
            <li>All-purpose vs job clusters, autoscaling, init scripts.</li>
        </ul>
        <h3>Unity Catalog Governance</h3>
        <ul>
            <li>Centralized metastore, grant/revoke, lineage.</li>
        </ul>
        <h3>Medallion Architecture</h3>
        <ul>
            <li>Bronze (raw), Silver (clean), Gold (aggregates).</li>
        </ul>

        <h2>🔨 Mini-Projects</h2>
        <ul class="mini-projects">
            <li><strong>Secure ADLS</strong>: implement ACLs, private endpoint, firewall rules.</li>
            <li><strong>DBX Ingest Job</strong>: schedule notebook to load into Bronze.</li>
            <li><strong>Governance Demo</strong>: set up Unity Catalog roles & access.</li>
        </ul>

        <h2>📚 Resources</h2>
        <ul class="resources">
            <li>ADLS Gen2 documentation</li>
            <li>Databricks Unity Catalog guide</li>
            <li>Microsoft Fabric Lakehouse whitepapers</li>
        </ul>
    </div>
</body>
</html>
