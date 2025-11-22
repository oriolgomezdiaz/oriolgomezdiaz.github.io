---
title: "Administració de Sistemes Informàtics en Xarxa"
permalink: /asix/
layout: splash
author_profile: false
header:
  overlay_image: "ima-database.jpg"
  overlay_filter: 0.5
  caption: "Infraestructura i Dades"
---

<style>
.grid-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(45%, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.grid-item {
  background-color: #f2f3f4;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  padding: 25px;
  text-align: center; /* Centra el títol i el botó */
  transition: transform 0.2s;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  display: flex;
  flex-direction: column;
  justify-content: space-between; /* Això ajuda a alinear els botons a baix */
}

.grid-item:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 12px rgba(0,0,0,0.15);
  border-color: #28a745; /* Verd quan passes el ratolí */
}

.grid-item h3 {
  margin-top: 0;
  color: #2c3e50;
  font-size: 1.4em;
}

.grid-item p {
  text-align: justify; /* Text justificat perquè es llegeixi millor el paràgraf llarg */
  font-size: 0.95em;
}

.grid-btn {
  display: inline-block;
  margin-top: 15px;
  padding: 10px 20px;
  background-color: #28a745; /* VERD per diferenciar d'ASIX */
  color: white !important;
  text-decoration: none !important;
  border-radius: 4px;
  font-weight: bold;
  align-self: center; /* Centra el botó horitzontalment */
}

.grid-btn:hover {
  background-color: #218838; /* Verd més fosc */
}
</style>

<br>
<div style="text-align: center; font-size: 1.2em; margin-bottom: 30px; max-width: 900px; margin-left: auto; margin-right: auto;">
  Benvinguts a l'àrea d'<strong>ASIX</strong>. <br>
  Aquí trobareu la documentació tècnica i tallers pràctics per dominar el disseny de bases de dades i la seva administració avançada en entorns de producció.
</div>

<div class="grid-container">

  <div class="grid-item">
    <h3>📊 0372 - Gestió de Bases de Dades</h3>
    <p>El mòdul estableix els fonaments per a l'arquitectura de la informació. L'alumnat aprèn a modelar la realitat (Model E/R i Normalització) fins a la seva implementació física. S'aprofundeix en el domini del llenguatge <strong>SQL</strong> per a la definició d'estructures i manipulació de dades, així com la lògica de negoci (procediments) i la integritat de la informació.</p>
    <a href="/asix/gbd/" class="grid-btn">Accedir al material</a>
  </div>
  
  <div class="grid-item">
    <h3>🔒 0377 - Administració de SGBD</h3>
    <p>Aprofundim en les tasques crítiques per garantir el rendiment i la seguretat. El curs capacita per instal·lar i configurar motors, gestionar el control d'accés (usuaris i rols) i automatitzar tasques administratives. Es posa focus en l'<strong>optimització</strong> (índexs, monitoratge) i la implementació d'entorns d'alta disponibilitat (rèpliques i clústers).</p>
    <a href="/asix/asgbd/" class="grid-btn">Accedir al material</a>
  </div>

</div>
<br>