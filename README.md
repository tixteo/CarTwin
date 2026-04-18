# CarTwin

**Il gemello digitale della tua auto.**

CarTwin è un'applicazione mobile (iOS + Android) che crea un profilo digitale completo del veicolo dell'utente a partire dal numero di telaio (VIN). L'app monitora lo stato dei componenti, suggerisce interventi di manutenzione e integra un catalogo di ricambi compatibili direttamente al suo interno.

---

## Il problema

Possedere un'auto significa gestire decine di scadenze: tagliando, revisione, assicurazione, componenti da sostituire a chilometraggio variabile. La maggior parte dei proprietari si affida al meccanico o al libretto di manutenzione, perdendo il controllo diretto sullo stato del proprio veicolo e spesso pagando più del dovuto per ricambi e interventi.

## La soluzione

CarTwin trasforma l'auto fisica in un gemello digitale monitorato in tempo reale:

- **Onboarding in 30 secondi** — basta inserire o scansionare il VIN
- **Dashboard intelligente** — stato di ogni componente con semaforo verde/giallo/rosso
- **Notifiche predittive** — l'app avvisa quando un componente si avvicina alla sostituzione
- **Catalogo ricambi integrato** — prezzi e acquisto in-app senza uscire dall'esperienza
- **Storico completo** — ogni intervento tracciato, utile anche per la rivendita

---

## Target di mercato

Proprietari privati di auto in **Italia ed Europa**, età 25-55, con almeno un'auto a km medio-alto (>30.000 km). Focus iniziale sui principali gruppi automobilistici europei:

- **Stellantis** (Fiat, Peugeot, Opel)
- **Volkswagen Group** (VW, Audi, Škoda)
- **BMW**
- **Mercedes-Benz**
- **Ford**

Copertura stimata: ~60% del parco circolante europeo.

---

## Stato del progetto

**Fase:** MVP completato, pre-lancio

- ✅ Architettura backend + frontend definita
- ✅ Design system e mockup delle schermate principali
- ✅ Database dei piani di manutenzione per 9 brand (234 componenti)
- ✅ Sistema di autenticazione e gestione sessioni
- ✅ Integrazione push notifications
- 🔄 In corso: integrazione affiliate marketplace ricambi
- 🔄 In corso: deploy produzione + pubblicazione store

**Lancio previsto:** Q3 2026

---

## Modello di business

- **Free tier** — 1 veicolo, notifiche base, dashboard completa
- **Premium** (abbonamento mensile/annuale) — multi-veicolo, storico esportabile, report avanzati
- **Affiliazione ricambi** — commissione su acquisti tramite marketplace partner

---

## Stack tecnologico

- **Mobile app:** Flutter (iOS + Android)
- **Backend:** NestJS + PostgreSQL + Redis
- **Infrastructure:** Docker, deploy su cloud managed
- **Push notifications:** Firebase Cloud Messaging
- **VIN decoding:** Vincario API

Il codice sorgente completo è mantenuto in un repository privato per proteggere la proprietà intellettuale del progetto.

---

## Contatti

Matteo Placentino — [Email](teoplace02@icloud.com)

*CarTwin è un progetto in sviluppo attivo. Per richieste di partnership o collaborazione, contattare via email.*
