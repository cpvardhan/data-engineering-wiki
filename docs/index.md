<!-- =======================  Course Library cards  ======================= -->
<link rel="stylesheet" href="webpage_style.css">

<style>
/* --- simple card grid (add to webpage_style.css once you’re happy) --- */
.grid.cards      { display:grid; gap:1.5rem;
                   grid-template-columns:repeat(auto-fit,minmax(160px,1fr)); }

.card-link       { display:block; text-align:center; background:#fff;
                   border-radius:12px; overflow:hidden; box-shadow:0 2px 8px #0002;
                   transition:transform .15s ease; text-decoration:none; }

.card-link:hover { transform:translateY(-4px); }

.card-link img   { width:100%; height:auto; display:block; }

.card-label      { padding:.75rem 0 .9rem; font-weight:600;
                   font-size:.95rem; color:#343a40; }
</style>

## 📚 Course Library

<div class="grid cards" markdown="1">

[<!-- SQL Admin -->
![SQL Admin](assets/logos/sql-admin.png){: loading="lazy" }
<span class="card-label">SQL Admin</span>](courses/sql-admin/){ .card-link }

[<!-- Python -->
![Python](assets/logos/python.png){: loading="lazy" }
<span class="card-label">Python</span>](courses/python/){ .card-link }

[<!-- Power BI Admin -->
![Power BI Admin](assets/logos/powerbi.png){: loading="lazy" }
<span class="card-label">Power BI Admin</span>](courses/power-bi-service/powerbi-service-cheatsheet.html){ .card-link }

[<!-- Cheat Sheets -->
![Cheat Sheets](assets/logos/cheat-sheet.png){: loading="lazy" }
<span class="card-label">Cheat Sheets</span>](cheat-sheets/){ .card-link }

</div>
