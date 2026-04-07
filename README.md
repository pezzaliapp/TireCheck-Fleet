# TireCheck Fleet

Diagnosi pneumatici fleet con intelligenza artificiale.  
Foto → Analisi → Decisione → Scheda PDF firmabile.

---

## 🚀 Cos’è

TireCheck Fleet è una Progressive Web App (PWA) progettata per officine truck, flotte, trasporto persone e trasporto merci.

Permette di:
- analizzare lo stato di usura di pneumatici camion, autobus, eurocargo, trailer e semirimorchi
- estrarre automaticamente misura e DOT dal fianco gomma
- registrare asse, lato, tipo asse e montaggio singolo/gemellato
- generare schede PDF firmabili
- documentare lo stato del pneumatico per controllo interno, preventivo o tutela operativa
- inviare i dati a Make.com tramite webhook

---

## 🧠 Funzionalità principali

### 📸 Scansione doppia
- Tread / battistrada → analisi usura
- Sidewall / fianco → lettura misura + DOT truck

### 🤖 Analisi AI
- profondità stimata
- usura uniforme o irregolare
- pattern di usura
- condizione fianco
- urgenza
- commento tecnico per officina/flotta

### 🚚 Dati mezzo
- targa / ID mezzo
- tipo mezzo
- asse
- lato
- tipo asse
- montaggio singolo o gemellato
- km mezzo
- cliente / flotta

### 📄 Scheda PDF
- generazione immediata
- firma cliente o operatore
- dati officina integrati
- formato adatto a controllo flotta

### 📴 Modalità offline (parziale)
Funziona senza internet per:
- apertura app
- storico
- inserimento dati

Non funziona senza internet per:
- analisi immagini
- lettura misura e DOT
- invio webhook
- ricerca assistenza vicina

---

## 💰 API Gemini

L’app usa Google Gemini Vision API.

### Piano gratuito
- nessun costo
- nessuna carta richiesta
- adatto a test e demo

### Piano a pagamento
- più stabilità
- più throughput
- ideale per officine e flotte

L’app non include costi propri di AI:
ogni utente inserisce la propria API key.

---

## ⚙️ Architettura

/project
├── index.html
├── manifest.json
├── sw.js
├── LICENSE.txt

---

## 🧩 Tecnologie
- HTML5 / CSS3 / Vanilla JS
- Progressive Web App (PWA)
- Service Worker
- Google Gemini Vision API
- jsPDF
- Geolocation API
- LocalStorage

---

## ⚙️ Configurazione

### 1. API Gemini
Crea la tua API key su:
aistudio.google.com

### 2. Webhook (opzionale)
Per integrazione con:
- Make.com
- CRM
- automazioni interne

### 3. Dati officina
- nome
- telefono
- indirizzo
- P.IVA

---

## 🔐 Privacy
- API key salvata solo localmente
- immagini inviate direttamente a Google
- nessun server intermedio PezzaliApp

---

## ⚠️ Limiti
- analisi basata su immagini
- non sostituisce controllo fisico professionale
- precisione dipende dalla qualità foto e dall’inquadratura
- per soglie legali e decisioni di messa in servizio serve sempre verifica professionale

---

## 🧑‍💻 Autore

Alessandro Pezzali  
pezzaliAPP

---

## 📜 Licenza

Licenza proprietaria.

Uso gratuito consentito.  
Copia, modifica o redistribuzione vietate senza autorizzazione.

Vedi LICENSE.txt per dettagli.
