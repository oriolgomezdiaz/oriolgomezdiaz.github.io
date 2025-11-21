---
title: "Contacte"
permalink: /contacte/
layout: splash
author_profile: false
header:
  overlay_image: "https://images.unsplash.com/photo-1423666639041-f56000c27a9a?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80"
  overlay_filter: 0.5
  caption: "Parlem?"
---

<style>
.contact-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin-top: 30px;
  margin-bottom: 50px;
}

.contact-item {
  background-color: #ffffff;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  padding: 20px;
  text-align: center;
  transition: all 0.3s ease;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
}

.contact-item:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 15px rgba(0,0,0,0.1);
  border-color: #17a2b8;
}

.contact-icon {
  font-size: 2.5em;
  color: #2c3e50;
  margin-bottom: 10px;
}

.contact-btn {
  display: block;
  margin-top: 15px;
  padding: 8px 15px;
  background-color: #2c3e50;
  color: white !important;
  text-decoration: none !important;
  border-radius: 4px;
}

.contact-btn:hover {
  background-color: #17a2b8;
}

/* Estils del Formulari */
.form-container {
  max-width: 600px;
  margin: 0 auto;
  background: #f9f9f9;
  padding: 30px;
  border-radius: 8px;
  border: 1px solid #ddd;
}

.form-group {
  margin-bottom: 15px;
}

.form-group label {
  display: block;
  margin-bottom: 5px;
  font-weight: bold;
}

.form-group input, .form-group textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
  font-family: inherit;
}

.submit-btn {
  background-color: #17a2b8;
  color: white;
  border: none;
  padding: 12px 25px;
  font-size: 1.1em;
  border-radius: 4px;
  cursor: pointer;
  width: 100%;
}

.submit-btn:hover {
  background-color: #138496;
}
</style>

<div style="text-align: center; font-size: 1.2em; margin-bottom: 40px;">
  Tens algun dubte sobre els apunts? Vols col·laborar en algun projecte? <br>
  Pots contactar amb mi a través dels següents canals:
</div>

<div class="contact-grid">

  <div class="contact-item">
    <div class="contact-icon"><i class="fab fa-linkedin"></i></div>
    <h3>LinkedIn</h3>
    <p>Connectem professionalment.</p>
    <a href="https://www.linkedin.com/in/oriolgomezdiaz/" target="_blank" class="contact-btn">Veure Perfil</a>
  </div>

  <div class="contact-item">
    <div class="contact-icon"><i class="fas fa-envelope"></i></div>
    <h3>Correu Electrònic</h3>
    <p>Escriu-me directament.</p>
    <a href="mailto:el_teu_email@exemple.com" class="contact-btn">Enviar Email</a>
  </div>

  <div class="contact-item">
    <div class="contact-icon"><i class="fab fa-github"></i></div>
    <h3>GitHub</h3>
    <p>Revisa el meu codi.</p>
    <a href="https://github.com/oriolgomezdiaz" target="_blank" class="contact-btn">Veure Repositori</a>
  </div>

</div>

---

## 📬 Envia'm un missatge

Si ho prefereixes, pots utilitzar aquest formulari. Et respondré el més aviat possible.

<div class="form-container">
  <form action="https://formspree.io/f/LA_TEVA_ID_FORMSPREE" method="POST">
    
    <div class="form-group">
      <label for="name">Nom:</label>
      <input type="text" id="name" name="name" required placeholder="El teu nom">
    </div>

    <div class="form-group">
      <label for="email">Correu electrònic:</label>
      <input type="email" id="email" name="email" required placeholder="el_teu@email.com">
    </div>

    <div class="form-group">
      <label for="message">Missatge:</label>
      <textarea id="message" name="message" rows="5" required placeholder="Hola Oriol, et volia comentar..."></textarea>
    </div>

    <button type="submit" class="submit-btn">Enviar Missatge</button>
  </form>
</div>