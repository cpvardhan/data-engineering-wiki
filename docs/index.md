<!-- =======================  Course Library cards ======================= -->
<link rel="stylesheet" href="webpage_style.css">

<style>
/* 2 × 2 grid ----------------------------------------------------------- */
.grid.cards    { display:grid; grid-template-columns:repeat(2,1fr);
                 gap:2rem; max-width:700px; margin:0 auto; }

/* full-button look ---------------------------------------------------- */
.card-link     { display:block; background:#fff; border-radius:12px;
                 overflow:hidden; box-shadow:0 2px 10px #0003;
                 transition:transform .15s ease; text-decoration:none; }
.card-link:hover { transform:translateY(-6px); }

/* coloured badge (top bar) ------------------------------------------- */
.card-badge    { display:flex; align-items:center; gap:.5rem;
                 justify-content:center; height:56px; /* badge height  */
                 font-weight:600; color:#fff; font-size:.95rem; }
.badge-sql     { background:#0288d1; }   /* tweak colours as desired   */
.badge-python  { background:#f9c74f; color:#502f00; }
.badge-powerbi { background:#ffb300; color:#472700; }
.badge-cheat   { background:#0288d1; }

/* hide the lower label completely ------------------------------------ */
.card-label    { display:none; }
</style>

## 📚 Course Library

<div class="grid cards" markdown="1">

[<span class="card-badge badge-sql">
   <img src="assets/logos/sql-admin.png" alt="" width="20" height="20" loading="lazy">
   SQL Admin
 </span>](courses/sql-admin/){ .card-link }

[<span class="card-badge badge-python">
   <img src="assets/logos/python.png" alt="" width="20" height="20" loading="lazy">
   Python
 </span>](courses/python/){ .card-link }

[<span class="card-badge badge-powerbi">
   <img src="assets/logos/powerbi.png" alt="" width="20" height="20" loading="lazy">
   Power BI Service & Admin 
 </span>](courses/power-bi-service/powerbi-service-cheatsheet.html){ .card-link }

[<span class="card-badge badge-cheat">
   <img src="assets/logos/cheatsheet.png" alt="" width="20" height="20" loading="lazy">
   Cheat Sheets
 </span>](cheat-sheets/){ .card-link }

</div>
