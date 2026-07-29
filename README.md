# ⚔️ Tracker Iniziativa D&D

Un tracker di iniziativa per il combattimento in D&D (e giochi di ruolo simili), pensato per essere semplice, veloce e completamente gratuito. Funziona interamente nel browser, senza bisogno di installazioni, account o connessione a database esterni.

**[👉 Apri il tracker](https://kattafa.github.io/iniziativometro/)**

---

## ✨ Funzionalità

- **Aggiunta rapida dei personaggi**: nome + valore di iniziativa
- **Ordinamento automatico** decrescente per iniziativa, aggiornato ad ogni modifica
- **Eliminazione personaggi** con un click sulla ✕ rossa
- **Indicatore di turno** (freccia ➤): cliccandola si passa al personaggio successivo
- **Contatore Round**: al termine del giro, il round aumenta automaticamente e si riparte dal personaggio con iniziativa più alta
- **Codice colore per lo stato del turno**:
  - 🟡 Giallo → deve ancora agire
  - 🟢 Verde → sta agendo ora
  - 🔴 Rosso → ha già agito in questo round
- **Gestione incantesimi attivi**: ogni personaggio può avere più incantesimi in corso, ciascuno con nome e durata (in round)
  - La durata si riduce automaticamente di 1 ad ogni passaggio di turno
  - Allo scadere (0 round), l'incantesimo viene rimosso in automatico
  - Possibilità di rimuovere manualmente un incantesimo in qualsiasi momento
- **Pulsante Reset**: azzera tutto e riporta il tracker allo stato iniziale
- **Completamente responsive**: ottimizzato per smartphone, tablet e desktop

## 🖥️ Come si usa

1. Inserisci il nome del personaggio e il suo valore di iniziativa, poi clicca **Aggiungi** (o premi Invio)
2. La lista si ordina automaticamente dal valore di iniziativa più alto al più basso
3. Clicca la freccia ➤ accanto al personaggio in verde per passare al turno successivo
4. Aggiungi incantesimi con il pulsante **+ Incantesimo** sotto ogni personaggio, indicando nome e durata in round
5. Usa **Reset** per iniziare un nuovo combattimento da zero

Nessun dato viene salvato: alla chiusura o al ricaricamento della pagina il tracker si azzera. È pensato per essere usato "live" durante la sessione.

## 🛠️ Tecnologie

- HTML, CSS e JavaScript puro (vanilla), nessuna dipendenza esterna
- Un unico file, facilmente modificabile e ospitabile ovunque

## 📄 Licenza

Libero da usare e modificare per le proprie sessioni di gioco.
