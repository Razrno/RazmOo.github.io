<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Menu MPM</title>

<style>
/* ====== HEADER PRINCIPAL ====== */
.mpm-header {
  background-color: #0d1728;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 40px;
  font-family: Arial, sans-serif;
}
.mpm-left, .mpm-center, .mpm-right {
  display: flex;
  align-items: center;
  gap: 15px;
}
.mpm-left img, .mpm-right img {
  width: 32px;
  height: 32px;
}
.mpm-center img {
  height: 70px;
}
.mpm-left span {
  color: white;
  font-weight: bold;
  font-size: 18px;
}

/* ====== NAVIGATION ====== */
.mpm-nav {
  background-color: #0d1728;
  text-align: center;
  padding: 10px 0;
}
.mpm-nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: inline-flex;
  gap: 25px;
}
.mpm-nav ul li {
  position: relative;
}
.mpm-nav a {
  text-decoration: none;
  color: white;
  font-weight: bold;
  transition: color 0.3s;
}
.mpm-nav a:hover {
  color: #ffd700;
}

/* ====== SOUS-MENUS ====== */
.mpm-nav ul li ul {
  display: none;
  position: absolute;
  top: 30px;
  left: 0;
  background-color: #e0eef7;
  padding: 0;
  border-radius: 5px;
  overflow: hidden;
  min-width: 220px;
  z-index: 1000;
}
.mpm-nav ul li:hover ul {
  display: block;
}
.mpm-nav ul li ul li {
  display: block;
}
.mpm-nav ul li ul li a {
  display: block;
  padding: 10px;
  color: #0d1728;
  text-align: left;
}
.mpm-nav ul li ul li a:hover {
  background-color: #c8e0f3;
  color: #000;
}
</style>
</head>
<body>

<!-- ====== HEADER ====== -->
<header class="mpm-header">
  <div class="mpm-left">
    <a href="https://postimages.org/" target="_blank">
      <img src="https://i.postimg.cc/JzG0V9nM/Logo-18-112.png" border="0" alt="Logo 18 112">
    </a>
    <span>Marins-Pompiers de Marseille</span>
  </div>

  <div class="mpm-center">
    <a href="https://postimages.org/" target="_blank">
      <img src="https://i.postimg.cc/28LzK2DJ/logo-mpm.png" border="0" alt="Logo MPM">
    </a>
  </div>

  <div class="mpm-right">
    <a href="https://facebook.com" target="_blank">
      <img src="https://i.postimg.cc/KzhLB09d/facebook-icon.png" border="0" alt="Facebook">
    </a>
    <a href="https://instagram.com" target="_blank">
      <img src="https://i.postimg.cc/Xv36TfRj/instagram-icon.png" border="0" alt="Instagram">
    </a>
    <a href="https://twitter.com" target="_blank">
      <img src="https://i.postimg.cc/pdVzsjc5/twitter-icon.png" border="0" alt="Twitter">
    </a>
  </div>
</header>

<!-- ====== NAVIGATION ====== -->
<nav class="mpm-nav">
  <ul>
    <li><a href="#">Accueil</a></li>
    <li><a href="#">Interventions</a>
      <ul>
        <li><a href="#">Feux</a></li>
        <li><a href="#">Sauvetages</a></li>
        <li><a href="#">Secours</a></li>
      </ul>
    </li>
    <li><a href="#">Véhicules</a>
      <ul>
        <li><a href="#">Camions</a></li>
        <li><a href="#">Bateaux</a></li>
        <li><a href="#">Hélicoptères</a></li>
      </ul>
    </li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>

</body>
</html>
