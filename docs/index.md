<!-- =======================  Course Library cards  ======================= -->
<link rel="stylesheet" href="webpage_style.css">

<style>
/* ---- 2×2 grid layout ---- */
.grid.cards           {
    display: grid;
    grid-template-columns: repeat(2, 1fr);   /* always 2 columns  */
    gap: 2rem;                               /* more breathing room */
    max-width: 700px;                        /* centres nicely on wide screens */
    margin: 0 auto;
}

.card-link            {                       /* full-button look */
    display: block;
    text-align: center;
    background: #fff;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 2px 10px #0003;
    transition: transform .15s ease;
    text-decoration: none;
}

.card-link:hover      { transform: translateY(-6px); }

.card-link img        {                       /* bigger image area */
    width: 100%;
    height: 200px;        /* adjust ↓ to taste */
    object-fit: contain; /* keeps logo aspect ratio */
    display: block;
}
</style>

## 📚 Course Library

<div class="grid cards" markdown="1">

[![SQL Admin](assets/logos/sql-admin.png){: loading="lazy" }](courses/sql-admin/){ .card-link }

[![Python](assets/logos/python.png){: loading="lazy" }](courses/python/){ .card-link }

[![Power BI Admin](assets/logos/powerbi.png){: loading="lazy" }](courses/power-bi-service/powerbi-service-cheatsheet.html){ .card-link }

[![Cheat Sheets](assets/logos/cheat-sheet.png){: loading="lazy" }](cheat-sheets/){ .card-link }

</div>
