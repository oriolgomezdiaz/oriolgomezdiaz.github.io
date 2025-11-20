---
title: "0377 - Administració de SGBD"
permalink: /asix/asgbd/
layout: single
author_profile: false
toc: true
toc_label: "Índex de Continguts"
toc_icon: "database"
toc_sticky: true
header:
  overlay_image: "https://images.unsplash.com/photo-1544383835-bda2bc66a55d?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80"
  overlay_filter: 0.5
  caption: "Administració avançada de dades"
---

Benvinguts al mòdul d'**Administració de Sistemes Gestors de Bases de Dades (ASGBD)**. En aquest mòdul aprofundim en la gestió professional de servidors de bases de dades, centrant-nos principalment en **MySQL Server**. Aprendrem des de la instal·lació i configuració segura fins a l'optimització de consultes i el desplegament d'arquitectures d'alta disponibilitat.

**⚠️ Requisits previs:** Per realitzar les pràctiques necessitareu:
* **Virtualització:** Un ordinador amb suport per a màquines virtuals (VirtualBox) per simular entorns de xarxa.
* **Sistemes Operatius:** Imatge ISO d'Ubuntu Server.
* **Clients SQL:** Tenir instal·lat **MySQL Workbench** .

---

## ⚙️ Bloc 1: Instal·lació i Arquitectura

En aquest bloc introductori analitzem l'arquitectura interna d'un SGBD, els motors d'emmagatzematge i realitzem la instal·lació en diferents entorns.

### 📘 Apunts i Teoria
* **Tema 1: Arquitectura i Instal·lació.**
    * Funcions del SGBD, fitxers de registre (Logs) i Diccionari de Dades.
    * Motors d'emmagatzematge: Diferències entre **InnoDB** i **MyISAM**.
    * [📄 Descarregar Apunts T1 (PDF)](/assets/pdfs/Apunts_GS_0377_1.1_IEDIB.pdf){: .btn .btn--success .btn--small}

### 📺 Vídeos explicatius
* [▶️ Instal·lació de MySQL Server sobre Ubuntu](https://youtu.be/VIDEO_ID)

### 🛠️ Exercicis i Pràctiques
1.  **Pràctica 1:** Instal·lació de MySQL a Linux i Windows.
2.  **Pràctica 2:** Configuració de variables de sistema i buffers.
3.  **Pràctica 3:** Connexió remota segura amb Workbench.
    * [📥 Descarregar Guió Pràctiques Bloc 1](/assets/pdfs/asgbd-practica1.pdf){: .btn .btn--warning}

---

## 🔒 Bloc 2: Seguretat i Gestió d'Usuaris

Ens centrem en el control d'accés, la gestió de privilegis i com assegurar les connexions.

### 📘 Apunts i Teoria
* **Tema 2: Autenticació i Permisos.**
    * Taules de concessió de permisos (`user`, `db`, `tables_priv`)[cite: 53].
    * Gestió de Rols i limitació de recursos per usuari[cite: 557].
    * Connexions segures amb **TLS/SSL**[cite: 597].
    * [📄 Descarregar Apunts T2 (PDF)](/assets/pdfs/Apunts_GS_0377_2.1_IEDIB.pdf){: .btn .btn--success .btn--small}

### 📺 Vídeos explicatius
* [▶️ Creació d'usuaris](https://youtu.be/Ddpy5NRpb9o)

### 🛠️ Exercicis i Pràctiques
1.  **Pràctica 4:** Implementació de Rols i polítiques de contrasenyes.
    * [📥 Descarregar Guió Pràctiques Bloc 2](/assets/pdfs/asgbd-practica2.pdf){: .btn .btn--warning}

---

## ⚡ Bloc 3: Programació i Optimització

Aprenem a automatitzar tasques dins del servidor i a millorar el rendiment de les consultes.

### 📘 Apunts i Teoria
* **Tema 3: Rutines i Optimització.**
    * [cite_start]**Programació:** Procediments emmagatzemats, Funcions i Triggers[cite: 2386, 3071].
    * [cite_start]**Esdeveniments:** Automatització de tasques (Event Scheduler)[cite: 3561].
    * [cite_start]**Optimització:** Ús d'índexs (B-Tree) i anàlisi de consultes amb `EXPLAIN`[cite: 3755, 4108].
    * [📄 Descarregar Apunts T3 (PDF)](/assets/pdfs/Apunts_GS_0377_3.1_IEDIB.pdf){: .btn .btn--success .btn--small}

### 📺 Vídeos explicatius
* [▶️ Creació d'un Trigger d'auditoria]()
* [▶️ Analitzant consultes lentes amb EXPLAIN]()

### 🛠️ Exercicis i Pràctiques
1.  **Pràctica 6:** Creació d'una bateria de procediments i triggers per a una botiga online.
2.  **Pràctica 7:** Optimització de consultes complexes mitjançant índexs.
    * [📥 Descarregar Guió Pràctiques Bloc 3](/assets/pdfs/asgbd-practica3.pdf){: .btn .btn--warning}

---

## 🌐 Bloc 4: Alta Disponibilitat i Clústers

Arquitectures avançades per garantir la disponibilitat de les dades i el balanceig de càrrega.

### 📘 Apunts i Teoria
* **Tema 4: Replicació i Distribució.**
    * Tipus de replicació: Mestre-Esclau i Mestre-Mestre.
    * **MySQL NDB Cluster:** Arquitectura de nodes (MGM, Data, SQL).
    * **InnoDB Cluster:** Ús de MySQL Router i Group Replication[cite: 1826].
    * [📄 Descarregar Apunts T4 (PDF)](/assets/pdfs/Apunts_GS_0377_4.1_IEDIB.pdf){: .btn .btn--success .btn--small}

### 📺 Vídeos explicatius
* [▶️ Configuració d'una replicació Mestre-Esclau pas a pas]()
* [▶️ Desplegament d'un clúster InnoDB amb MySQL Shell]()

### 🛠️ Exercicis i Pràctiques
1.  **Pràctica 8:** Configuració de replicació asíncrona entre dues màquines virtuals.
2.  **Pràctica 9:** Instal·lació i prova de fallades en un NDB Cluster.
    * [📥 Descarregar Guió Pràctiques Bloc 4](/assets/pdfs/asgbd-practica4.pdf){: .btn .btn--warning}