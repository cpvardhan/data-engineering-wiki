---
title: 📚 Course Library
---

<style>
/* -----------------------------------------------------------------
   Base Styles & Best Practices
-------------------------------------------------------------------*/
*,
*::before,
*::after {
  box-sizing: border-box;
}

/* -----------------------------------------------------------------
   2x2 Responsive Grid Wrapper
-------------------------------------------------------------------*/
.grid.cards {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 2rem;
  max-width: 700px;
  margin: 2rem auto;
  padding: 0;
}

@media (max-width: 768px) {
  .grid.cards {
    grid-template-columns: 1fr;
    gap: 1.5rem;
    margin: 1.5rem 1rem;
  }
}

/* -----------------------------------------------------------------
   Card as horizontal split: icon | text
-------------------------------------------------------------------*/
.card-link {
  display: flex;
  height: 120px;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  transition: transform .2s ease, box-shadow .2s ease;
  text-decoration: none;
  align-items: center;
}
.card-link:hover {
  transform: translateY(-6px);
  box-shadow: 0 8px 16px rgba(0,0,0,0.15);
}

.card-img {
  flex: 0 0 120px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: rgba(255,255,255,0.2);
  height: 100%;
}
.card-img img {
  width: 65px;
  height: 65px;
  object-fit: contain;
}

.card-text {
  flex: 1;
  padding: 0 1rem;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
  font-weight: 600;
  font-size: 1.1rem;
  text-align: center;
}

/* -----------------------------------------------------------------
   Alternating Color Themes
-------------------------------------------------------------------*/
.card-blue   { background-color: #0288d1; color: #fff; }
.card-yellow { background-color: #fbc02d; color: #3E2723; }
.card-teal   { background-color: #009688; color: #fff; }
.card-orange { background-color: #f57c00; color: #fff; }
</style>

# 📚 Course Library

<div class="grid cards">

  <a href="courses/sql-admin/sql-admin-overview/" class="card-link card-blue">
    <div class="card-img">
      <img src="/assets/logos/sql-admin.png" alt="SQL Admin Icon">
    </div>
    <div class="card-text">SQL Admin</div>
  </a>

  <a href="courses/python/python-overview/" class="card-link card-yellow">
    <div class="card-img">
      <img src="/assets/logos/python.png" alt="Python Icon">
    </div>
    <div class="card-text">Python</div>
  </a>

  <a href="courses/power-bi-service/powerbi-service-overview/" class="card-link card-teal">
    <div class="card-img">
      <img src="/assets/logos/powerbi.png" alt="Power BI Icon">
    </div>
    <div class="card-text">Power BI Service & Admin</div>
  </a>

  <a href="cheat-sheets/cheatsheet-overview/" class="card-link card-orange">
    <div class="card-img">
      <img src="/assets/logos/cheatsheet.png" alt="Cheat Sheets Icon">
    </div>
    <div class="card-text">Cheat Sheets</div>
  </a>

</div>
