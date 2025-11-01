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
  width: 24px;
  height: 24px;
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

<!-- ====== HEADER ====== -->
<div class="mpm-header">
  <div class="mpm-left">
    <img src="https://image2url.com/images/1762025496063-0ef24144-4fd1-4b80-b373-44888bc70f56.png">
    <span>18</span>
    <img src="https://image2url.com/images/1762025496063-0ef24144-4fd1-4b80-b373-44888bc70f56.png">
    <span>112</span>
  </div>

  <div class="mpm-center">
    <img src="URL_DU_LOGO" alt="Marins-Pompiers de Marseille">
  </div>

  <div class="mpm-right">
    <a href="#" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733579.png" alt="X"></a>
    <a href="#" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
    <a href="#" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" alt="YouTube"></a>
    <a href="#" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/145/145807.png" alt="LinkedIn"></a>
    <a href="#" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/1384/1384063.png" alt="Instagram"></a>
  </div>
</div>

<!-- ====== MENU DE NAVIGATION ====== -->
<nav class="mpm-nav">
  <ul>
    <li><a href="#">Découvrir l'unité</a>
      <ul>
        <li><a href="#">Présentation générale</a></li>
        <li><a href="#">Le commandement</a></li>
        <li><a href="#">Les formations</a></li>
        <li><a href="#">Le service médical</a></li>
        <li><a href="#">Les spécialités du Bataillon</a></li>
        <li><a href="#">L'expertise du Bataillon</a></li>
        <li><a href="#">Innovations</a></li>
        <li><a href="#">Rapport d'activité</a></li>
      </ul>
    </li>
    <li><a href="#">Actualités</a></li>
    <li><a href="#">Conseils</a></li>
    <li><a href="#">Rejoignez-nous</a></li>
    <li><a href="#">Contactez-nous</a></li>
  </ul>
</nav>
