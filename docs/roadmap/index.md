---
title: 🚀 Learning Road-map
---

Welcome to the **30-week Azure Data-Engineering Road-map**.  
Click any module card for detailed weekly tasks & resources.

<style>
  .roadmap-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 1.75rem;
    max-width: 900px;
    margin: 2rem auto;
    padding: 0;
  }
  @media (max-width: 768px) {
    .roadmap-grid { grid-template-columns: 1fr; }
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

  /* Gradients */
  .grad-blue   { background: linear-gradient(135deg,#0166d6 0%,#33b1e0 100%); }
  .grad-yellow { background: linear-gradient(135deg,#f6b63c 0%,#ffd65b 100%); color: #212121; }
  .grad-teal   { background: linear-gradient(135deg,#00897b 0%,#26a69a 100%); }
  .grad-orange { background: linear-gradient(135deg,#f57c00 0%,#ff9e42 100%); }
</style>

<div class="roadmap-grid" markdown="1">

[<span class="module-card grad-blue">
  <span class="module-img"><img src="/assets/timeline/phase1_dw_sql_foundations.png" alt="Module-1"></span>
  <span class="module-body"><span class="module-title">Module-1 DW & SQL Foundations</span></span>
</span>](module1.md)

[<span class="module-card grad-yellow">
  <span class="module-img"><img src="/assets/timeline/phase2_python_etl_ci_cd.png" alt="Module-2"></span>
  <span class="module-body"><span class="module-title">Module-2 Python ETL & CI</span></span>
</span>](module2.md)

[<span class="module-card grad-teal">
  <span class="module-img"><img src="/assets/timeline/phase3_spark_delta_performance.png" alt="Module-3"></span>
  <span class="module-body"><span class="module-title">Module-3 Spark & Delta Performance</span></span>
</span>](module3.md)

[<span class="module-card grad-orange">
  <span class="module-img"><img src="/assets/timeline/phase4_streaming_data_quality.png" alt="Module-4"></span>
  <span class="module-body"><span class="module-title">Module-4 Streaming & Data Quality</span></span>
</span>](module4.md)

[<span class="module-card grad-blue">
  <span class="module-img"><img src="/assets/timeline/phase5_azure_lakehouse.png" alt="Module-5"></span>
  <span class="module-body"><span class="module-title">Module-5 Azure Lakehouse</span></span>
</span>](module5.md)

[<span class="module-card grad-yellow">
  <span class="module-img"><img src="/assets/timeline/phase6_adf_synapse_orchestration.png" alt="Module-6"></span>
  <span class="module-body"><span class="module-title">Module-6 ADF & Synapse</span></span>
</span>](module6.md)

[<span class="module-card grad-teal">
  <span class="module-img"><img src="/assets/timeline/phase7_fabric_lakehouse_realtime.png" alt="Module-7"></span>
  <span class="module-body"><span class="module-title">Module-7 Fabric Lakehouse & Real-Time</span></span>
</span>](module7.md)

[<span class="module-card grad-orange">
  <span class="module-img"><img src="/assets/timeline/phase8_interview_system_design.png" alt="Module-8"></span>
  <span class="module-body"><span class="module-title">Module-8 Interview & System Design</span></span>
</span>](module8.md)

</div>
