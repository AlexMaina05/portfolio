---
layout: default
title: Alex Maina - Portfolio
---

<style>
.switch-lang {
  margin: 1em 0;
}
.switch-lang button {
  padding: 0.5em 1em;
  margin-right: 0.5em;
  font-size: 1em;
  cursor: pointer;
  background: #eee;
  border: 1px solid #ccc;
  border-radius: 4px;
}
.switch-lang button.active {
  background: #28a745;
  color: #fff;
  border-color: #28a745;
}
.lang-it, .lang-en { display: none; }
</style>

<div class="switch-lang">
  <button id="btn-it" class="active" onclick="switchLang('it')">🇮🇹 Italiano</button>
  <button id="btn-en" onclick="switchLang('en')">🇬🇧 English</button>
</div>

<nav>
  <ul>
    <li><a href="#about">Chi sono / About</a></li>
    <li><a href="#skills">Competenze / Skills</a></li>
    <li><a href="#languages">Lingue / Languages</a></li>
    <li><a href="#interests">Interessi / Interests</a></li>
    <li><a href="#projects">Progetti / Projects</a></li>
    <li><a href="#contact">Contatti / Contact</a></li>
  </ul>
</nav>

<div class="lang-it">
# 👋 Ciao, sono **Alessandro**

Benvenuto nel mio portfolio!  
Sono uno sviluppatore web appassionato di tecnologia, con esperienza su HTML, Python e progetti open source.

---

## 👨‍💻 <a id="about"></a>Chi sono

- **Nome:** Alex Maina
- **GitHub:** [AlexMaina05](https://github.com/AlexMaina05)
- **Tecnologie principali:** HTML, Python, Web App Development
- **Progetti recenti:** Web app per gestione comande, sistema prenotazioni

---

## 🛠 <a id="skills"></a>Competenze

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python
- **Framework:** Jules (by Google), Flask (aggiungi altri se usati)
- **Tools:** Git, GitHub, Jekyll, VS Code
- **Altro:** Web App Development, Open Source, Deploy su GitHub Pages

---

## 🌐 <a id="languages"></a>Lingue

- **Italiano** (madrelingua)
- **Inglese** (buona conoscenza)

---

## 🤝 <a id="interests"></a>Interessi personali

- Tecnologia e innovazione
- Sviluppo di web app
- Open source & community tech
- Automazione e strumenti per la produttività
- Viaggi e scoperta di nuove culture
- Musica

---

## 🚀 <a id="projects"></a>I miei principali repository

- [alexmaina05.github.io](https://github.com/AlexMaina05/alexmaina05.github.io) — Il mio sito personale/portfolio
- [comande](https://github.com/AlexMaina05/comande) — Web app test basata su Jules (by Google)
- [AlexMaina05](https://github.com/AlexMaina05/AlexMaina05) — Profilo GitHub
- [Reservations](https://github.com/AlexMaina05/Reservations) — Applicazione per gestione prenotazioni
- [Comande2.0](https://github.com/AlexMaina05/Comande2.0) — Evoluzione del progetto “comande”

---

## 📂 Portfolio Progetti

### Comande
> Web based application test made with Jules (by Google).  
> [Vedi su GitHub](https://github.com/AlexMaina05/comande)

### Reservations
> App per la gestione delle prenotazioni.  
> [Vedi su GitHub](https://github.com/AlexMaina05/Reservations)

### Comande2.0
> Evoluzione del progetto “comande”.  
> [Vedi su GitHub](https://github.com/AlexMaina05/Comande2.0)

---

## 📫 <a id="contact"></a>Contatti

- **GitHub:** [github.com/AlexMaina05](https://github.com/AlexMaina05)
- **Email:** [maina@alexmaina.dev](mailto:maina@alexmaina.dev)
- **LinkedIn:** [Linkedin](https://www.linkedin.com/in/alessandro-mainardi-ab812823b/)

---

*Questo portfolio è generato automaticamente con GitHub Pages e Jekyll.*
</div>

<div class="lang-en">
# 👋 Hi, I'm **Alessandro**

Welcome to my portfolio!  
I'm a passionate web developer with experience in HTML, Python and open source projects.

---

## 👨‍💻 <a id="about"></a>About Me

- **Name:** Alex Maina
- **GitHub:** [AlexMaina05](https://github.com/AlexMaina05)
- **Main technologies:** HTML, Python, Web App Development
- **Recent projects:** Web app for order management, booking system

---

## 🛠 <a id="skills"></a>Skills

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python
- **Framework:** Jules (by Google), Flask (add others if needed)
- **Tools:** Git, GitHub, Jekyll, VS Code
- **Other:** Web App Development, Open Source, Deploy on GitHub Pages

---

## 🌐 <a id="languages"></a>Languages

- **Italian** (native)
- **English** (good proficiency)

---

## 🤝 <a id="interests"></a>Personal Interests

- Technology and innovation
- Web app development
- Open source & tech community
- Automation and productivity tools
- Traveling and discovering new cultures
- Music

---

## 🚀 <a id="projects"></a>My Main Repositories

- [alexmaina05.github.io](https://github.com/AlexMaina05/alexmaina05.github.io) — My personal site/portfolio
- [comande](https://github.com/AlexMaina05/comande) — Web app test based on Jules (by Google)
- [AlexMaina05](https://github.com/AlexMaina05/AlexMaina05) — GitHub Profile
- [Reservations](https://github.com/AlexMaina05/Reservations) — Booking management application
- [Comande2.0](https://github.com/AlexMaina05/Comande2.0) — Evolution of the "comande" project

---

## 📂 Project Portfolio

### Comande
> Web based application test made with Jules (by Google).  
> [See on GitHub](https://github.com/AlexMaina05/comande)

### Reservations
> Booking management app.  
> [See on GitHub](https://github.com/AlexMaina05/Reservations)

### Comande2.0
> Evolution of the "comande" project.  
> [See on GitHub](https://github.com/AlexMaina05/Comande2.0)

---

## 📫 <a id="contact"></a>Contacts

- **GitHub:** [github.com/AlexMaina05](https://github.com/AlexMaina05)
- **Email:** [maina@alexmaina.dev](mailto:maina@alexmaina.dev)
- **LinkedIn:** [Linkedin](https://www.linkedin.com/in/alessandro-mainardi-ab812823b/)

---

*This portfolio is automatically generated with GitHub Pages and Jekyll.*
</div>

<script>
function switchLang(lang) {
  document.querySelectorAll('.lang-it').forEach(e => e.style.display = lang === 'it' ? 'block' : 'none');
  document.querySelectorAll('.lang-en').forEach(e => e.style.display = lang === 'en' ? 'block' : 'none');
  document.getElementById('btn-it').classList.toggle('active', lang === 'it');
  document.getElementById('btn-en').classList.toggle('active', lang === 'en');
}
// Default: IT
switchLang('it');
</script>
