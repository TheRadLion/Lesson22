<template>
  <div id="app">
      <header>
          <h2>My Awards</h2>
      <img id="logo" alt="Active Martial Arts Logo" src="./assets/ActiveLogo.png">
      </header>
        
      <section>
      <nav>
          <ul>
          <li><a href="#">My Awards</a></li>
          <li><a href="#">My Next Award</a></li>
          <li><a href="#">Studio Website</a></li>
          </ul>
      </nav>
        
      <article>
          <h1>My Awards</h1>
          <ul>
          <li class="card">
              <img src="./assets/clouds-fight-jumping-62376.jpg" style="width:100%">
              <div class="container">
                  <h4><b>High Kick</b></h4> 
                  <p>Kick over your head 10 times in under 10 seconds.</p> 
              </div>
          </li>
          </ul>
      </article>
      </section>
        
      <footer>
      <p>copyright Active Martial Arts</p>
      </footer>
  </div>
</template>

<script>

</script>

<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: #666;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: white;
}

/* Container for flexboxes */
section {
  display: -webkit-flex;
  display: flex;
}

/* Style the navigation menu */
nav {
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
  background: #ccc;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

/* Style the content */
article {
  -webkit-flex: 3;
  -ms-flex: 3;
  flex: 3;
  background-color: #f1f1f1;
  padding: 10px;
}

/* Style the footer */
footer {
  background-color: #777;
  padding: 10px;
  text-align: center;
  color: white;
}

/* Responsive layout - makes the menu and the content (inside the section) sit on top of each other instead of next to each other */
@media (max-width: 600px) {
  section {
    -webkit-flex-direction: column;
    flex-direction: column;
  }
}
</style>
