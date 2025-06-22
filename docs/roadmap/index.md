<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>🚀 Learning Road-map</title>
  <style>
    /* ───────────────────── Base & Grid Styles ───────────────────── */
    * { box-sizing: border-box; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
      margin: 0;
      padding: 1rem;
      line-height: 1.5;
      background: #fafafa;
    }
    h1 {
      text-align: center;
      margin: 2rem 0 1rem;
    }
    p {
      text-align: center;
      margin-bottom: 2rem;
    }
    .module-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 1.75rem;
      max-width: 900px;
      margin: 0 auto 2rem;
    }
    @media (max-width: 768px) {
      .module-grid {
        grid-template-columns: 1fr;
      }
    }

    /* ───────────────────── Module-Card Styles ───────────────────── */
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
      align-items: center;
      justify-content: center;
      color: #fff;
      text-align: center;
      padding: 0 .75rem;
    }
    .module-title {
      font-size: 1rem;
      font-weight: 700;
      line-height: 1.2;
    }

    /* ───────────────────── Gradient Themes ───────────────────── */
    .grad-blue   { background: linear-gradient(135deg,#0166d6 0%,#33b1e0 100%); }
    .grad-yellow { background: linear-gradient(135deg,#f6b63c 0%,#ffd65b 100%); color: #212121; }
    .grad-teal   { background: linear-gradient(135deg,#00897b 0%,#26a69a 100%); }
    .grad-orange { background: linear-gradient(135deg,#f57c00 0%,#ff9e42 100%); }
  </style>
</head>
<body>

  <h1>🚀 Learning Road-map (30 weeks)</h1>
  <p>Click any module card for detailed weekly tasks & resources.</p>

  <div class="module-grid">

    <a href="module1/" class="module-card grad-blue">
      <div class="module-img">
        <img src="../assets/timeline/phase1_dw_sql_foundations.png" alt="Module-1">
      </div>
      <div class="module-body">
        <span class="module-title">Module-1 DW &amp; SQL Foundations</span>
      </div>
    </a>

    <a href="module2/" class="module-card grad-yellow">
      <div class="module-img">
        <img src="../assets/timeline/phase2_python_etl_ci_cd.png" alt="Module-2">
      </div>
      <div class="module-body">
        <span class="module-title">Module-2 Python ETL &amp; CI</span>
      </div>
    </a>

    <a href="module3/" class="module-card grad-teal">
      <div class="module-img">
        <img src="../assets/timeline/phase3_spark_delta_performance.png" alt="Module-3">
      </div>
      <div class="module-body">
        <span class="module-title">Module-3 Spark &amp; Delta Performance</span>
      </div>
    </a>

    <a href="module4/" class="module-card grad-orange">
      <div class="module-img">
        <img src="../assets/timeline/phase4_streaming_data_quality.png" alt="Module-4">
      </div>
      <div class="module-body">
        <span class="module-title">Module-4 Streaming &amp; Data Quality</span>
      </div>
    </a>

    <a href="module5/" class="module-card grad-blue">
      <div class="module-img">
        <img src="../assets/timeline/phase5_azure_lakehouse.png" alt="Module-5">
      </div>
      <div class="module-body">
        <span class="module-title">Module-5 Azure Lakehouse</span>
      </div>
    </a>

    <a href="module6/" class="module-card grad-yellow">
      <div class="module-img">
        <img src="../assets/timeline/phase6_adf_synapse_orchestration.png" alt="Module-6">
      </div>
      <div class="module-body">
        <span class="module-title">Module-6 ADF &amp; Synapse</span>
      </div>
    </a>

    <a href="module7/" class="module-card grad-teal">
      <div class="module-img">
        <img src="../assets/timeline/phase7_fabric_lakehouse_realtime.png" alt="Module-7">
      </div>
      <div class="module-body">
        <span class="module-title">Module-7 Fabric Lakehouse &amp; Real-Time</span>
      </div>
    </a>

    <a href="module8/" class="module-card grad-orange">
      <div class="module-img">
        <img src="../assets/timeline/phase8_interview_system_design.png" alt="Module-8">
      </div>
      <div class="module-body">
        <span class="module-title">Module-8 Interview &amp; System Design</span>
      </div>
    </a>

  </div>

</body>
</html>
