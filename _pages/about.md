---
title: "About"
layout: splash
permalink: /about

feature_row:
  - image_path: /assets/images/team/1.png
    alt: "Marco Arena"
    title: "Marco Arena"
    excerpt: "Fondatore"  

partners:
  - image_url: https://conoscerelinux.org/
    image_path: /assets/images/logos/conoscerelinux.png
    alt: Conoscere Linux
  - image_url: https://www.comune.modena.it/makeitmodena
    image_path: /assets/images/logos/makeitmodena.png
    alt: Make it Modena
---

<br />

> When you’re surrounded by people who share a passionate commitment around a common purpose, anything is possible – **Howard Schultz**

<figure>
  <img
  src="/assets/images/about/itcppcon19-crowd.jpg"
  alt="Italian C++ Conference 2019, Milano (240 partecipanti)">
  <figcaption>Italian C++ Conference 2019, Milano (240 partecipanti)</figcaption>
</figure>

Ciao!

*Italian C++ Community* è la comunità Italiana dedicata al linguaggio di programmazione C++. Il punto di riferimento di professionisti, aziende e studenti che hanno l'interesse comune di condividere esperienze e idee sullo sviluppo software fatto con il C++ in Italia.

Creata nel **2013** da un’idea originale di [Marco Arena](http://it.linkedin.com/in/marcoarena), primo italiano a pubblicare un articolo su [isocpp.org](https://isocpp.org/), il sito internazionale dello standard C++. La **storia della community** è raccontata accuratamente [in questa pagina dedicata](https://italiancpp.org/story).

La **missione di ++it**:

*   diffondere risorse riguardanti la conoscenza e l'evoluzione del C++;
*   organizzare eventi e attività di approfondimento in Italia sullo sviluppo in C++;
*   coinvolgere e connettere tra loro tutti coloro che nutrono un interesse sul C++;
*   realizzare occasioni di incontro tra aziende, professionisti e studenti interessati al C++;
*   accogliere e aiutare coloro che desiderano [imparare](/learn) a sviluppare in C++;
*   supportare e fare da hub per eventi e incontri sul C++ in Italia, non organizzati direttamente da noi.

**++it** sviluppa costantemente la sua missione attraverso **proposte di interazione**, ovvero attività e canali di comunicazione:

* I **canali social** (che trovi in calce ad ogni pagina), per restare aggiornati sui nostri eventi e, talvolta, sulle notizie e risorse riguardanti il C++;

*   [Server Discord](/discord), per interagire con gli altri partecipanti e per ricevere aggiornamenti su **news**, **risorse consigliate**, **eventi**, **offerte di lavoro** riguardanti il C++;

*   Organizzazione di [eventi](/archivio-eventi) di stampo internazionale e meetup ricorrenti sul territorio;

*   [Mappa interattiva](https://www.google.com/maps/@45.7186146,-0.9182294,5z/data=!3m1!4b1!4m2!6m1!1s1kq4qEWdgLfxmDj2QOc8jIgH3yZc) dei C++-isti italiani e le aziende nel mondo.

Per approfondire le nostre proposte di interazione, visita la [pagina dedicata](/join).

#### Chi può partecipare?

Chiunque! Professionisti, appassionati, docenti, studenti, veterani, neofiti, imprenditori, italiani all’estero...

L’unico requisito per partecipare è prendere visione delle [informazioni legali](/privacy-policy) e rispettare il [Codice di Condotta](/coc).

[➕ Iscriviti](/join){: .btn .btn--primary .btn--large}

* * * 

### Magic C++ Moments!

Una galleria dedicata agli incontri con le *personalità del C++* fatti in diversi anni di attività.

<style>
.mosaic-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
  gap: 8px;
  padding: 1rem 0;
}
.mosaic-item {
  position: relative;
  overflow: hidden;
  border-radius: 8px;
  aspect-ratio: 1 / 1;
  cursor: pointer;
  background: #eee;
}
.mosaic-item img {
  width: 100%; height: 100%;
  object-fit: cover; display: block;
  transition: transform 0.3s ease;
}
.mosaic-item:hover img { transform: scale(1.06); }
.mosaic-item .caption-overlay {
  position: absolute; inset: 0;
  background: rgba(0,0,0,0);
  display: flex; align-items: flex-end;
  padding: 10px;
  transition: background 0.25s ease;
}
.mosaic-item:hover .caption-overlay { background: rgba(0,0,0,0.52); }
.mosaic-item .caption-text {
  color: #fff; font-size: 12px; line-height: 1.4;
  opacity: 0; transition: opacity 0.25s ease;
}
.mosaic-item:hover .caption-text { opacity: 1; }
.lightbox-backdrop {
  display: none; position: fixed; inset: 0;
  background: rgba(0,0,0,0.88); z-index: 9999;
  align-items: center; justify-content: center; padding: 24px;
}
.lightbox-backdrop.open { display: flex; }
.lightbox-inner {
  position: relative; max-width: min(820px, 100%);
  width: 100%; display: flex; flex-direction: column;
  align-items: center; gap: 12px;
}
.lightbox-inner img {
  max-height: 70vh; max-width: 100%;
  border-radius: 12px; object-fit: contain; display: block;
}
.lightbox-caption {
  color: rgba(255,255,255,0.85); font-size: 14px;
  text-align: center; max-width: 560px; line-height: 1.5;
}
.lightbox-close {
  position: absolute; top: -14px; right: -14px;
  width: 32px; height: 32px; border-radius: 50%;
  background: rgba(255,255,255,0.15);
  border: 1px solid rgba(255,255,255,0.3);
  color: #fff; font-size: 18px; cursor: pointer;
  display: flex; align-items: center; justify-content: center;
}
.lightbox-nav {
  position: absolute; top: 50%; transform: translateY(-50%);
  width: 36px; height: 36px; border-radius: 50%;
  background: rgba(255,255,255,0.13);
  border: 1px solid rgba(255,255,255,0.25);
  color: #fff; font-size: 22px; cursor: pointer;
  display: flex; align-items: center; justify-content: center;
}
.lightbox-nav.prev { left: -48px; }
.lightbox-nav.next { right: -48px; }
.lightbox-counter {
  position: absolute; bottom: -28px; left: 50%;
  transform: translateX(-50%);
  color: rgba(255,255,255,0.5); font-size: 12px;
}
</style>

<div class="mosaic-grid" id="mosaicGrid"></div>

<div class="lightbox-backdrop" id="lightbox">
  <div class="lightbox-inner">
    <button class="lightbox-close" id="lbClose">&times;</button>
    <button class="lightbox-nav prev" id="lbPrev">&#8249;</button>
    <img id="lbImg" src="" alt="" />
    <p class="lightbox-caption" id="lbCaption"></p>
    <button class="lightbox-nav next" id="lbNext">&#8250;</button>
    <span class="lightbox-counter" id="lbCounter"></span>
  </div>
</div>

<script>
const photos = [
  { src: "assets/images/about/bjarne2016.jpg",   alt: "Con Bjarne Stroustrup e Jens Weller a Meeting C++ 2016" },
  { src: "assets/images/about/herb2016.jpg",     alt: "Con Herb Sutter ad Issaquah (Meeting Standard ISO)" },
  { src: "assets/images/about/scott2014.jpg",    alt: "Con Scott Meyers a Meeting C++ 2014" },
  { src: "assets/images/about/bartosz2014.jpg",  alt: "Con Bartosz Milewski ai CDays14 di Roma" },
  { src: "assets/images/about/michael2016.jpg",  alt: "Con Michael Wong a Meeting C++ 2016" },
  { src: "assets/images/about/cdays14.jpg",      alt: "Community Days 2014 with the special guest Ale Contenti" },
  { src: "assets/images/about/chandler2016.jpg", alt: "Con Chandler Carruth ad Issaquah (Meeting Standard ISO)" },
  { src: "assets/images/about/eric2016.jpg",     alt: "Con Eric Niebler ad Issaquah (Meeting Standard ISO)" },
  { src: "assets/images/about/hartmut2014.jpg",  alt: "Con Hartmut Kaiser a Meeting C++ 2014" },
  { src: "assets/images/about/jj2015.jpg",       alt: "Con Joel Falcou & James McNellis a Meeting C++ 2015" },
  { src: "assets/images/about/herb-mug.jpg",     alt: "Herb Sutter ci manda un selfie con la nostra mug!" },
  { src: "assets/images/about/scott-mug.jpg",    alt: "Scott Meyers ci manda un selfie con la nostra mug!" },
  { src: "assets/images/about/bartosz-cdays.jpg",alt: "Bartosz Milewski ai CDays14 Roma!" },
  { src: "assets/images/about/kate2017.jpg",     alt: "Con Kate Gregory a Meeting C++ 2017" },
  { src: "assets/images/about/sean2017.jpg",     alt: "Con Sean Parent a Meeting C++ 2017" },
  { src: "assets/images/about/dan2018.jpg",      alt: "Con Dan Saks a Meeting C++ 2018" },
  { src: "assets/images/about/andrei2018.jpg",   alt: "Con Andrei Alexandrescu a Meeting C++ 2018" },
  { src: "assets/images/about/nico2018.jpg",     alt: "Con Nicolai Josuttis a Meeting C++ 2018" },
];

const grid = document.getElementById('mosaicGrid');
const lb = document.getElementById('lightbox');
const lbImg = document.getElementById('lbImg');
const lbCaption = document.getElementById('lbCaption');
const lbCounter = document.getElementById('lbCounter');
let current = 0;

photos.forEach((p, i) => {
  const item = document.createElement('div');
  item.className = 'mosaic-item';
  item.innerHTML = `<img src="${p.src}" alt="${p.alt}" loading="lazy"><div class="caption-overlay"><span class="caption-text">${p.alt}</span></div>`;
  item.addEventListener('click', () => openLightbox(i));
  grid.appendChild(item);
});

function openLightbox(i) {
  current = i; updateLightbox();
  lb.classList.add('open');
  document.body.style.overflow = 'hidden';
}
function closeLightbox() {
  lb.classList.remove('open');
  document.body.style.overflow = '';
}
function updateLightbox() {
  const p = photos[current];
  lbImg.src = p.src; lbImg.alt = p.alt;
  lbCaption.textContent = p.alt;
  lbCounter.textContent = (current + 1) + ' / ' + photos.length;
}
function navigate(dir) {
  current = (current + dir + photos.length) % photos.length;
  updateLightbox();
}

document.getElementById('lbClose').addEventListener('click', closeLightbox);
document.getElementById('lbPrev').addEventListener('click', () => navigate(-1));
document.getElementById('lbNext').addEventListener('click', () => navigate(1));
lb.addEventListener('click', e => { if (e.target === lb) closeLightbox(); });
document.addEventListener('keydown', e => {
  if (!lb.classList.contains('open')) return;
  if (e.key === 'Escape') closeLightbox();
  if (e.key === 'ArrowLeft') navigate(-1);
  if (e.key === 'ArrowRight') navigate(1);
});
</script>
