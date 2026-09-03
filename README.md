# ⚡ Tesla Cost Charging

> Un'applicazione utility pensata per calcolare e stimare in anticipo il costo di una ricarica presso i Supercharger Tesla, inserendo manualmente la percentuale di partenza, quella di arrivo desiderata e il costo al kWh.

---

## ⚠️ Nota sullo Stato del Progetto

Questo progetto è **attualmente in fase di sviluppo/sperimentale** ed è nato per risolvere un'esigenza pratica legata ai costi di ricarica. 

* **Il blocco delle API Tesla:** Tesla ha reso l'accesso alle proprie API ufficiali a pagamento, destinandolo prevalentemente ad aziende e sviluppatori commerciali.
* **Come funziona attualmente:** A causa di questa limitazione, l'app si basa su un approccio manuale: inserendo la percentuale di batteria iniziale, quella finale desiderata e il costo al kWh, il sistema calcola subito la spesa stimata per la sosta.
* **La visione originale (con API aperte):** Con l'integrazione delle API ufficiali, l'esperienza sarebbe stata totalmente automatica: l'app avrebbe letto lo stato della batteria direttamente dall'auto e geolocalizzato il Supercharger selezionato sulla mappa, prelevando in autonomia la tariffa aggiornata al kWh.

---

## 🌟 Funzionalità Attuali

- **Stima dei Costi di Ricarica:** Calcolo basato sui delta di carica (batteria di partenza vs batteria desiderata) moltiplicati per la tariffa inserita.
- **Parametri Modificabili:** Gestione dei campi relativi al costo al kWh per confrontare diversi Supercharger o fasce orarie.
- **Approccio Minimalista:** Struttura leggera e immediata, ideale per calcoli al volo.

---

## 📸 Anteprima dell'App

| Schermata Principale |
| :---: |
| ![Tesla Home](teslahome.jpeg) |

---

## 🚀 Come iniziare (Sviluppo Locale)

Se desideri clonare e testare il progetto in locale:

1. Clona la repository:
   ```bash
   git clone https://github.com/giodma/tesla_cost_charging.git
   ```
2. Entra nella cartella del progetto:
   ```bash
   cd tesla_cost_charging
   ```
3. Installa le dipendenze ed esegui il server di sviluppo.

---

## 📄 Licenza

Progetto open-source sviluppato a scopo hobbistico. Contributi e idee per aggirare le limitazioni delle API sono i benvenuti!
