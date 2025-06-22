<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>📚 Data Engineering Wiki</title>
  <style>
    /* ───────────────────── Base Styles ───────────────────── */
    * { box-sizing: border-box; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
      margin: 0;
      line-height: 1.5;
      padding-bottom: 4rem;
    }
    h1, h2 { margin: 2rem 0 1rem; text-align: center; }

    /* ───────────────────── Module-Card Grid─────────────── */
    .module-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 1.75rem;
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    @media (max-width: 768px) {
      .module-grid { grid-template-columns: 1fr; }
    }

    .module-card {
      display: flex;
      height: 160px;
      border-radius: 16px;
      overflow: hidden;
      box-shadow: 0 6px 16px rgba(0,0,0,0.12);
      text-decoration: none;
      transition: transform .2s ease, box-shadow .2s ease;
    }
    .module-card:hover {
      transform: translateY(-6px);
      box-shadow: 0 10px 22px rgba(0,0,0,0.18);
    }

    .module-img {
      flex: 0 0 50%;
      height: 100%;
    }
    .module-img img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .module-body {
      flex: 1;
      display: flex;
      justify-content: center;
      align-items: center;
      color: #fff;
      text-align: center;
      padding: 0 .75rem;
    }
    .module-title {
      font-size: 1rem;
      font-weight: 700;
      line-height: 1.2;
    }

    /* ───────────────────── Gradients ───────────────────── */
    .grad-blue   { background: linear-gradient(135deg,#0166d6 0%,#33b1e0 100%); }
    .grad-yellow { background: linear-gradient(135deg,#f6b63c 0%,#ffd65b 100%); color:#212121; }
    .grad-teal   { background: linear-gradient(135deg,#00897b 0%,#26a69a 100%); }
    .grad-orange { background: linear-gradient(135deg,#f57c00 0%,#ff9e42 100%); }
  </style>
</head>
<body>

  <!-- ───────────────────────── About Me ───────────────────────── -->
  <h1>👋 About Me</h1>
  <div style="max-width:720px;margin:0 auto;padding:0 1rem;">
    <p>
      Welcome to my data-engineering wiki! I'm a Power BI Developer with 3 years of experience,
      now diving deep into Azure data engineering and Microsoft Fabric.
    </p>
    <p>
      This site is my public knowledge base & portfolio as I up-skill from analyst to full-stack DE.
      Let’s connect on <a href="https://www.linkedin.com/in/cpvardhan/">LinkedIn</a>.
    </p>
  </div>

  <!-- ───────────────────────── Course Library ───────────────────────── -->
  <h2>🗂️ Course Library</h2>
  <div class="module-grid">
    <a href="courses/sql-admin/sql-admin-overview/" class="module-card grad-blue">
      <div class="module-img">
        <img src="assets/logos/sql-admin.png" alt="SQL Admin">
      </div>
      <div class="module-body">
        <span class="module-title">SQL Admin</span>
      </div>
    </a>

    <a href="courses/python/python-overview/" class="module-card grad-yellow">
      <div class="module-img">
        <img src="assets/logos/python.png" alt="Python">
      </div>
      <div class="module-body">
        <span class="module-title">Python</span>
      </div>
    </a>

    <a href="courses/power-bi-service/powerbi-service-overview/" class="module-card grad-teal">
      <div class="module-img">
        <img src="assets/logos/powerbi.png" alt="Power BI">
      </div>
      <div class="module-body">
        <span class="module-title">Power BI Service & Admin</span>
      </div>
    </a>

    <a href="cheat-sheets/cheatsheet-overview/" class="module-card grad-orange">
      <div class="module-img">
        <img src="assets/logos/cheatsheet.png" alt="Cheat Sheets">
      </div>
      <div class="module-body">
        <span class="module-title">Cheat Sheets</span>
      </div>
    </a>
  </div>

  <!-- ───────────────────────── Road-map Grid ───────────────────────── -->
  <h2>🗺️ Learning Road-map (30 weeks)</h2>
  <p style="text-align:center;">Click any module card for detailed tasks & resources.</p>
  <div class="module-grid">
    <a href="roadmap/module1/" class="module-card grad-blue">
      <div class="module-img">
        <img src="assets/timeline/phase1_dw_sql_foundations.png" alt="Module-1">
      </div>
      <div class="module-body">
        <span class="module-title">Module-1 DW & SQL Foundations</span>
      </div>
    </a>

    <a href="roadmap/module2/" class="module-card grad-yellow">
      <div class="module-img">
        <img src="assets/timeline/phase2_python_etl_ci_cd.png" alt="Module-2">
      </div>
      <div class="module-body">
        <span class="module-title">Module-2 Python ETL & CI</span>
      </div>
    </a>

    <a href="roadmap/module3/" class="module-card grad-teal">
      <div class="module-img">
        <img src="assets/timeline/phase3_spark_delta_performance.png" alt="Module-3">
      </div>
      <div class="module-body">
        <span class="module-title">Module-3 Spark & Delta Performance</span>
      </div>
    </a>

    <a href="roadmap/module4/" class="module-card grad-orange">
      <div class="module-img">
        <img src="assets/timeline/phase4_streaming_data_quality.png" alt="Module-4">
      </div>
      <div class="module-body">
        <span class="module-title">Module-4 Streaming & Data Quality</span>
      </div>
    </a>

    <a href="roadmap/module5/" class="module-card grad-blue">
      <div class="module-img">
        <img src="assets/timeline/phase5_azure_lakehouse.png" alt="Module-5">
      </div>
      <div class="module-body">
        <span class="module-title">Module-5 Azure Lakehouse</span>
      </div>
    </a>

    <a href="roadmap/module6/" class="module-card grad-yellow">
      <div class="module-img">
        <img src="assets/timeline/phase6_adf_synapse_orchestration.png" alt="Module-6">
      </div>
      <div class="module-body">
        <span class="module-title">Module-6 ADF & Synapse</span>
      </div>
    </a>

    <a href="roadmap/module7/" class="module-card grad-teal">
      <div class="module-img">
        <img src="assets/timeline/phase7_fabric_lakehouse_realtime.png" alt="Module-7">
      </div>
      <div class="module-body">
        <span class="module-title">Module-7 Fabric Lakehouse & Real-Time</span>
      </div>
    </a>

    <a href="roadmap/module8/" class="module-card grad-orange">
      <div class="module-img">
        <img src="assets/timeline/phase8_interview_system_design.png" alt="Module-8">
      </div>
      <div class="module-body">
        <span class="module-title">Module-8 Interview & System Design</span>
      </div>
    </a>
  </div>

</body>
</html>
