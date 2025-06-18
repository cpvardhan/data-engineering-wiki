# 📚 Course Library
 

<div class="grid cards">

<a href="courses/sql-admin/" class="card-link card-blue">
  <div class="card-img">
    <img src="assets/logos/sql-admin.png" alt="SQL Admin Icon">
  </div>
  <div class="card-text">SQL&nbsp;Admin</div>
</a>

<a href="courses/python/" class="card-link card-yellow">
  <div class="card-img">
    <img src="assets/logos/python.png" alt="Python Icon">
  </div>
  <div class="card-text">Python</div>
</a>

<a href="courses/power-bi-service/powerbi-service-cheatsheet.html" class="card-link card-teal">
  <div class="card-img">
    <img src="assets/logos/powerbi.png" alt="Power BI Icon">
  </div>
  <div class="card-text">Power BI&nbsp;Service&nbsp;&amp;&nbsp;Admin</div>
</a>

<a href="cheat-sheets/" class="card-link card-orange">
  <div class="card-img">
    <img src="assets/logos/cheatsheet.png" alt="Cheat Sheets Icon">
  </div>
  <div class="card-text">Cheat Sheets</div>
</a>

</div>

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
  /* Two columns of equal fraction on large screens */
  grid-template-columns: repeat(2, 1fr);
  gap: 2rem;
  max-width: 700px;
  margin: 2rem auto; /* Add space around the grid */
  padding: 0;
}

/* --- Media Query for smaller screens (e.g., mobile) --- */
@media (max-width: 768px) {
  .grid.cards {
    /* Switch to a single column layout */
    grid-template-columns: 1fr;
    gap: 1.5rem;
    margin: 1.5rem 1rem; /* Adjust margin for smaller screens */
  }
}

/* -----------------------------------------------------------------
   Card as a horizontal split: icon | text
-------------------------------------------------------------------*/
.card-link {
  display: flex;
  height: 120px; /* Set a consistent height for all cards */
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  transition: transform .2s ease, box-shadow .2s ease;
  text-decoration: none;
  align-items: center; /* Vertically align icon and text */
}

.card-link:hover {
  transform: translateY(-6px);
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.15);
}

/* --- Left-side icon area ----------------------------------- */
.card-img {
  flex: 0 0 120px; /* Give the icon a fixed width container */
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: rgba(255, 255, 255, 0.2); /* Subtle highlight for icon area */
  height: 100%;
}

.card-img img {
  height: 65px;  /* Set your desired icon height */
  width: 65px;   /* Set your desired icon width */
  object-fit: contain; /* Ensures the icon scales correctly */
}

/* --- Right-side text label area ---------------------------- */
.card-text {
  flex: 1; /* Allows text to fill the remaining space */
  padding: 0 1rem; /* Add horizontal padding */
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  font-weight: 600;
  font-size: 1.1rem;
  text-align: center;
}

/* -----------------------------------------------------------------
   Alternating Color Themes for Cards
-------------------------------------------------------------------*/
/* Theme 1: Blue */
.card-blue {
  background-color: #0288d1;
  color: #ffffff;
}

/* Theme 2: Yellow */
.card-yellow {
  background-color: #fbc02d;
  color: #3E2723; /* Dark brown text for contrast */
}

/* Theme 3: Teal */
.card-teal {
  background-color: #009688;
  color: #ffffff;
}

/* Theme 4: Orange */
.card-orange {
    background-color: #f57c00;
    color: #ffffff;
}

</style> 