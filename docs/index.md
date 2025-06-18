<!-- =======================  Course Library cards  ======================= -->
<link rel="stylesheet" href="webpage_style.css">

<style>
/* -----------------------------------------------------------------
   2 × 2 grid wrapper –- unchanged
-------------------------------------------------------------------*/
.grid.cards      { display:grid; grid-template-columns:repeat(2,1fr);
                   gap:2rem; max-width:700px; margin:0 auto; }

/* -----------------------------------------------------------------
   Card as a horizontal split: 50 % logo | 50 % text
-------------------------------------------------------------------*/
.card-link       { display:flex;                 /* NEW: flex row       */
                   height:120px;                 /* set your preferred  */
                   background:#fff; border-radius:12px;
                   overflow:hidden; box-shadow:0 2px 10px #0003;
                   transition:transform .15s ease; text-decoration:none; }
.card-link:hover { transform:translateY(-6px); }

/* --- left-side image area --------------------------------------- */
.card-img        { flex:0 0 50%;                 /* fixed 50 % width    */
                   display:flex; justify-content:center; align-items:center;
                   background:#f1f3f4; }         /* subtle backdrop     */
.card-img img    { max-width:80%; max-height:80%; object-fit:contain; }

/* --- right-side label area -------------------------------------- */
.card-text       { flex:1; display:flex; justify-content:center;
                   align-items:center; font-weight:600; font-size:1rem;
                   color:#fff; }

/* colour themes for the right half ------------------------------- */
.sql       { background:#0288d1; }   /* light blue  */
.python    { background:#f9c74f; color:#502f00; }
.powerbi   { background:#ffb300; color:#472700; }
.cheat     { background:#009688; }   /* teal        */
</style>

## 📚 Course Library

<div class="grid cards" markdown="1">

<a href="courses/sql-admin/" class="card-link sql">
  <div class="card-img">
    <img src="assets/logos/sql-admin.png" alt="SQL Admin">
  </div>
  <div class="card-text">SQL&nbsp;Admin</div>
</a>

<a href="courses/python/" class="card-link python">
  <div class="card-img">
    <img src="assets/logos/python.png" alt="Python">
  </div>
  <div class="card-text">Python</div>
</a>

<a href="courses/power-bi-service/powerbi-service-cheatsheet.html" class="card-link powerbi">
  <div class="card-img">
    <img src="assets/logos/powerbi.png" alt="Power BI">
  </div>
  <div class="card-text">Power BI&nbsp;Admin</div>
</a>

<a href="cheat-sheets/" class="card-link cheat">
  <div class="card-img">
    <img src="assets/logos/cheatsheet.png" alt="Cheat Sheets">
  </div>
  <div class="card-text">Cheat Sheets</div>
</a>

</div>
