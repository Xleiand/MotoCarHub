# MotoCarHub

## 📌 Descrizione del Progetto

**MotoCarHub** è un'applicazione progettata per rivoluzionare il mercato della compravendita di auto e moto, sia nuove che usate. Offre un ambiente sicuro e affidabile dove privati e rivenditori verificati possono pubblicare annunci, confrontare prezzi, valutare veicoli e contattare direttamente i venditori.

Grazie a un’interfaccia intuitiva e a funzionalità avanzate, MotoCarHub semplifica l’incontro tra domanda e offerta nel mercato delle due e quattro ruote.

---

## 🎯 Obiettivo

L'obiettivo è creare una piattaforma:

- Sicura e accessibile
- Intuitiva da usare
- Trasparente nel processo di acquisto/vendita
- Ricca di strumenti utili per l'utente

---

## 🧑‍💼 Target

- Privati (acquirenti o venditori)
- Rivenditori professionisti
- Amministratori del sistema
- Potenziali acquirenti interessati a preventivi finanziari o assicurativi

---

## 🔍 Analisi dei Competitor

1. **AutoScout24**: piattaforma europea molto nota con strumenti avanzati di ricerca.
2. **Subito.it**: marketplace italiano generalista, include sezioni per auto e moto.
3. **Facebook Marketplace**: accessibile ma poco regolamentato, usato sia da privati che da rivenditori.

---

## ✅ Requisiti Funzionali

### 👤 Registrazione

- Inserimento di: nome utente, email, password
- Scelta tra utente privato o rivenditore
- Per i rivenditori: inserimento sito web e luogo sede

### 📢 Inserimento Annuncio

- Foto del veicolo
- Tipo di veicolo (auto/moto)
- Marca, modello
- Caratteristiche tecniche
- Descrizione dettagliata
- Luogo
- Prezzo
- Numero di telefono (opzionale)

### 🔎 Ricerca con Filtri

- Per tipologia: solo auto / solo moto
- Marca e modello
- Prezzo
- Chilometraggio
- Anno
- Potenza
- Tipo venditore
- Luogo

### 💬 Chat interna

- Sistema di messaggistica per contattare privati/rivenditori
- Possibilità di **inviare, modificare e cancellare** messaggi

### ⭐ Salvataggio

- Salvare **annunci**
- Salvare **ricerche**

### 🔔 Notifiche

- In caso di:
  - Sconto su un annuncio salvato
  - Pubblicazione di annunci compatibili con le ricerche salvate

---

## 🚫 Requisiti Non Funzionali

- **Compatibilità**: Android, iOS, Windows
- **Prestazioni**: Tempi di risposta brevi
- **Sicurezza**: protezione dei dati e delle comunicazioni
- **Verifica venditori**: controllo identità e approvazione degli annunci

---

## ⚙️ Funzionalità Avanzate

- 🔒 Verifica rivenditori e annunci
- 📈 Calcolo del valore di mercato del veicolo
- 🚨 Rilevamento annunci sospetti (AI, regole)
- 💰 Calcolo preventivi per finanziamento/assicurazione
- 🛠️ Stima costi manutenzione futuri
- 🧾 Verifica storia del veicolo (VIN o targa)
- 🕒 Suggerimenti per orari migliori di pubblicazione
- 🚗 Prenotazione test drive per rivenditori professionisti

---

## 🛠️ Tecnologie Utilizzate

### 🌐 Frontend

- React Native
- React.js o Vue.js

### 🔙 Backend

- Django (Python)

### 🗃️ Database

- MongoDB
- Elasticsearch

### 🔔 Notifiche & Realtime

- Firebase Cloud Messaging (FCM)
- Socket.io

### 📊 Analisi

- Google Analytics

---

## 🧩 Ruoli degli Utenti

| Ruolo         | Funzionalità chiave                                                                      |
|---------------|------------------------------------------------------------------------------------------|
| **Privato**   | Registrazione, pubblicazione annunci, ricerca, salvataggio, chat, notifiche             |
| **Rivenditore**| Come privato + verifica identità, sito aziendale, gestione test drive                   |
| **Acquirente**| Ricerca, salvataggio, contatto venditore, stima valore, finanziamenti, manutenzione     |
| **Admin**     | Moderazione utenti e annunci, verifica sicurezza, gestione piattaforma                   |

---

## 📌 Diagramma UML

_⚠️ UML da completare successivamente._

---

## 🧠 Note Finali

- Alcune funzionalità erano **scritte ma non identificate chiaramente come funzionalità**: sono ora elencate correttamente.
- Aggiunti i **dettagli sulle azioni nella chat** (invio, modifica, eliminazione).
- Specificati i **target** e chiariti i ruoli.
