# TimeShift

Web app per la gestione di ore lavorate e movimenti economici per cliente.

**Stack**: FastAPI + SQLAlchemy + SQLite (backend), nginx + vanilla JS + Tailwind + Chart.js (frontend).

**Avvio**: `docker compose up --build` → http://localhost

---

## TODO

- [ ] **Movimento di ripareggiamento saldo conto** — Se il saldo del conto non corrisponde a quello reale (es. conto a 180 ma in realtà è 160), poter ripareggiare il conto e generare automaticamente un movimento di ripareggiamento
- [ ] **Ore specifiche nelle attività** — Quando si crea un'attività, poter specificare l'orario di svolgimento (es. 9:00-12:00) oppure solo il numero di ore impiegate
- [ ] **Filtri su base mensile** — Aggiungere filtri mensili per visualizzare attività, movimenti e statistiche per mese
- [ ] **Clienti a 0€/ora** — Permettere la creazione di clienti con tariffa oraria a 0€ (attività non retribuite / pro bono)
- [ ] **Collegamento attività lavorative ↔ movimenti** — Collegare le attività lavorative ai movimenti economici corrispondenti
