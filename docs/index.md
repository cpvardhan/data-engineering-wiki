<!-- =======================  Course Library cards ======================= -->
<link rel="stylesheet" href="webpage_style.css">

<style>
/* --- 2 × 2 grid with larger rectangular buttons ----------------------- */
.grid.cards {
    display: grid;
    grid-template-columns: repeat(2, 1fr);   /* always two columns   */
    gap: 2rem;
    max-width: 700px;                        /* nice centred width   */
    margin: 0 auto;
}

.card-link {
    display: block;
    background: #fff;
    border-radius: 12px;                     /* keep or drop if you want square corners */
    overflow: hidden;
    box-shadow: 0 2px 10px #0003;
    transition: transform .15s ease;
    text-decoration: none;                   /* remove underline flash on click */
}

.card-link:hover { transform: translateY(-6px); }

.card-link img {
    width: 100%;       /* let the logo keep its natural rectangle */
    height: auto;      /* so no distortion */
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
