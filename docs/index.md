<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>📚 Course Library</title>
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
      height: 100px;               /* reduced height */
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
      flex: 0 0 80px;              /* reduced width */
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: rgba(255,255,255,0.2);
      height: 100%;
    }
    .card-img img {
      width: 48px;                 /* smaller icon */
      height: 48px;
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
       Card Color Themes (with forced text color)
    -------------------------------------------------------------------*/

    /* Deep blue theme with crisp white text */
    .card-blue {
      background-color: #0288d1;
      color: #ffffff !important;
    }
    .card-blue .card-text,
    a.card-blue {
      color: #ffffff !important;
    }

    /* Vibrant yellow theme—now with dark charcoal text */
    .card-yellow {
      background-color: #fbc02d;
      color: #212121 !important;
    }
    .card-yellow .card-text,
    a.card-yellow {
      color: #212121 !important;
    }

    /* Modern teal theme with clean white text */
    .card-teal {
      background-color: rgb(9, 152, 138);
      color: #ffffff !important;
    }
    .card-teal .card-text,
    a.card-teal {
      color: #ffffff !important;
    }

    /* Energetic orange theme with bold white text */
    .card-orange {
      background-color: #f57c00;
      color: #ffffff !important;
    }
    .card-orange .card-text,
    a.card-orange {
      color: #ffffff !important;
    }

  </style>
</head>
<body>

  <h1>👋 About Me</h1>
  <p>
    Welcome to my data engineering wiki! I'm a Power BI Developer with 3 years of experience, now diving into 
    data engineering and Microsoft Fabric from scratch. I created this site to store all my notes, handy 
    documents, and useful LinkedIn posts in one place.
  </p>
  <p>
    My goal is to master each topic end-to-end, from core concepts to complete interview preparation, using 
    only freely available resources. If you're on a similar learning path and want to connect, reach out on 
    <a href="https://www.linkedin.com/in/cpvardhan/">LinkedIn</a>.
  </p>

  <h2>🗂️ Course Library</h2>
  <div class="grid cards">

    <a href="courses/sql-admin/sql-admin-overview/" class="card-link card-blue">
      <div class="card-img">
        <img src="assets/logos/sql-admin.png" alt="SQL Admin Icon" />
      </div>
      <div class="card-text">SQL Admin</div>
    </a>

    <a href="courses/python/python-overview/" class="card-link card-yellow">
      <div class="card-img">
        <img src="assets/logos/python.png" alt="Python Icon" />
      </div>
      <div class="card-text">Python</div>
    </a>

    <a href="courses/power-bi-service/powerbi-service-overview/" class="card-link card-teal">
      <div class="card-img">
        <img src="assets/logos/powerbi.png" alt="Power BI Icon" />
      </div>
      <div class="card-text">Power BI Service & Admin</div>
    </a>

    <a href="cheat-sheets/cheatsheet-overview/" class="card-link card-orange">
      <div class="card-img">
        <img src="assets/logos/cheatsheet.png" alt="Cheat Sheets Icon" />
      </div>
      <div class="card-text">Cheat Sheets</div>
    </a>

  </div>

</body>
</html>
