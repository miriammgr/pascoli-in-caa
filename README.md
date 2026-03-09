
# Pascoli in Comunicazione Aumentativa e Alternativa (CAA)

![Lighthouse Accessibility](https://img.shields.io/badge/Lighthouse_Accessibility-100-brightgreen)
![Lighthouse SEO](https://img.shields.io/badge/Lighthouse_SEO-100-brightgreen)
![Lighthouse Best Practices](https://img.shields.io/badge/Lighthouse_Best_Practices-96-green)
![Lighthouse Performance Mobile](https://img.shields.io/badge/Lighthouse_Performance_Mobile-82-yellow)
![WAVE Accessibility](https://img.shields.io/badge/WAVE_Accessibility-10/10-brightgreen)
![Project](https://img.shields.io/badge/Project-University-blue)

---

# Descrizione

Questo progetto è un piccolo **sito web educativo** che rende accessibili tre poesie di **Giovanni Pascoli** attraverso la **Comunicazione Aumentativa e Alternativa (CAA)**.

Il sito presenta le poesie:

- *La mia sera*
- *Il gelsomino notturno*
- *La cavalla storna*

Ogni poesia è disponibile:

- nel **testo originale**
- in una **versione adattata in CAA**

L'obiettivo è facilitare la comprensione del contenuto poetico per bambini e ragazzi con bisogni comunicativi speciali.

Il sito include inoltre un **gioco interattivo** che aiuta gli utenti a riconoscere le emozioni presenti nelle poesie.

---

# Demo

Il sito può essere visualizzato qui:

*https://miriammgr.github.io/pascoli-in-caa/*

---

# Contesto accademico

Progetto realizzato per l'esame del corso:

**Tecnologie Assistive per la Didattica (6 CFU)**  
Università di Pisa – A.A. 2025/2026

---

# Obiettivi del progetto

Il progetto ha due obiettivi principali.

## Accessibilità cognitiva

Rendere le poesie di Pascoli più comprensibili per bambini con **disturbo dello spettro autistico**, attraverso:

- uso di pittogrammi
- associazione tra immagini e testo
- struttura semplificata dei contenuti

## Accessibilità digitale

Rendere il sito utilizzabile anche da persone con **disabilità visive**, migliorando:

- struttura semantica del codice
- navigazione da tastiera
- compatibilità con screen reader

---

# Tecnologie utilizzate

- **Mobirise** per la struttura iniziale del sito
- **Bootstrap** (framework generato da Mobirise)
- **HTML5**
- **CSS**
- **JavaScript**

Il codice generato da Mobirise è stato successivamente **modificato manualmente** per:

- migliorare la struttura semantica del codice
- aumentare la compatibilità con tecnologie assistive
- implementare un **gioco interattivo** per il riconoscimento delle emozioni nelle poesie

---

# Funzionalità del sito

Il sito include:

- Versione originale delle poesie
- Versione delle poesie in **Comunicazione Aumentativa e Alternativa**
- Gioco interattivo per associare le poesie alle emozioni che trasmettono
- Struttura pensata per utenti con disabilità visive
- Navigazione utilizzabile da tastiera
- Skip link per saltare al contenuto principale

---

# Accessibilità

Il progetto include diversi accorgimenti per migliorare l'accessibilità:

- uso di **tag semantici HTML** (`main`, `nav`, `section`)
- presenza di **skip link**
- immagini con **testo alternativo**
- struttura compatibile con **screen reader**
- navigazione accessibile da tastiera
- utilizzo di attributi **ARIA** quando necessario
- attenzione alla leggibilità e alla gerarchia dei contenuti

---

# Valutazione dell'accessibilità (WAVE)

L'accessibilità del sito è stata verificata con lo strumento:

**WAVE – Web Accessibility Evaluation Tool**

Risultati principali:

- **Errors:** 0  
- **Contrast Errors:** 0  
- **Alerts:** 1  
- **Features rilevate:** 6  
- **Elementi strutturali:** 18  
- **Elementi ARIA:** 19  

**AIM Score: 10 / 10**

Il risultato indica che non sono stati rilevati errori automatici di accessibilità e che la struttura semantica del sito è compatibile con tecnologie assistive come gli screen reader.

---

# Valutazione Lighthouse

Il sito è stato analizzato con **Google Lighthouse** per verificare qualità del codice, accessibilità e prestazioni.

I test sono stati eseguiti in **modalità incognito** per evitare interferenze dovute alle estensioni del browser.

## Risultati Desktop

- **Performance:** 99  
- **Accessibility:** 100  
- **Best Practices:** 96  
- **SEO:** 100  

## Risultati Mobile

- **Performance:** 82  
- **Accessibility:** 100  
- **Best Practices:** 96  
- **SEO:** 100  

Il punteggio massimo di **accessibilità (100)** conferma che il sito è progettato per essere utilizzabile anche con tecnologie assistive.

La differenza tra performance desktop e mobile è dovuta al fatto che Lighthouse simula dispositivi mobili con:

- CPU meno potente
- connessioni di rete più lente

Questo tipo di simulazione è più severo e può influenzare il caricamento delle immagini e delle risorse generate automaticamente dal framework utilizzato.

---

# Struttura del progetto
Pascoli-CAA
│
├── index.html
├── mia-sera.html
├── cavalla-storna.html
├── gelsomino-notturno.html
│
├── assets/
│ ├── css
│ ├── js
│ ├── images
│ └── bootstrap
│
└── README.md


---

# Autrice

**Miriam Grande**  
Studentessa di Informatica Umanistica  
Università di Pisa
