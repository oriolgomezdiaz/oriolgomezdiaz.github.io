---
title: "Desenvolupament d'Aplicacions Multiplataforma"
permalink: /dam/
layout: splash
author_profile: false
header:
  overlay_image: "ima-dam.jpg"
  overlay_filter: 0.5
  caption: "Cicle Formatiu de Grau Superior"


<style>
.grid-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(45%, 1fr)); /* Intenta fer 2 columnes, si no cap, en fa 1 */
  gap: 20px; /* Espai entre caixes */
  margin-top: 20px;
}

.grid-item {
  background-color: #f2f3f4; /* Color de fons gris clar */
  border: 1px solid #e0e0e0;
  border-radius: 8px; /* Cantonades rodones */
  padding: 25px;
  text-align: center;
  transition: transform 0.2s; /* Efecte suau en passar el ratolí */
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.grid-item:hover {
  transform: translateY(-5px); /* Es mou una mica amunt en passar el ratolí */
  box-shadow: 0 8px 12px rgba(0,0,0,0.15);
}

.grid-item h3 {
  margin-top: 0;
  color: #2c3e50;
  font-size: 1.4em;
}

.grid-btn {
  display: inline-block;
  margin-top: 15px;
  padding: 10px 20px;
  background-color: #17a2b8; /* Color blau (info) */
  color: white !important;
  text-decoration: none !important;
  border-radius: 4px;
  font-weight: bold;
}

.grid-btn:hover {
  background-color: #138496; /* Blau més fosc en passar el ratolí */
}
</style>

<br>
<div style="text-align: center; font-size: 1.2em; margin-bottom: 20px;">
  Benvinguts als recursos docents de DAM. Selecciona un mòdul per començar:
</div>

<div class="grid-container">

  <div class="grid-item">
    <h3>⚙️ 0483 - Sistemes Informàtics</h3>
    <p>La base del maquinari. Virtualització, Linux, Windows i Xarxes.</p>
    <a href="/dam/sistemes-informatics/" class="grid-btn">Accedir al material</a>
  </div>
  
  <div class="grid-item">
    <h3>💾 Digitalització aplicada al sector productiu</h3>
    <p>Transformació digital. Indústria 4.0, Cloud, IoT i Seguretat.</p>
    <a href="/dam/digitalitzacio/" class="grid-btn">Accedir al material</a>
  </div>

  <div class="grid-item">
    <h3>🏢 0491 - Sistemes de Gestió Empresarial </h3>
    <p>Implantació d'ERPs i CRMs. Odoo, Python i APIs.</p>
    <a href="/dam/sge/" class="grid-btn">Accedir al material</a>
  </div>

  <div class="grid-item">
    <h3>🖥️ 0488 - Desenvolupament d'interfícies</h3>
    <p>Capa visual d'aplicacions. JavaFX, Figma, Usabilitat i UX/UI.</p>
    <a href="/dam/interficies/" class="grid-btn">Accedir al material</a>
  </div>

</div>
<br>