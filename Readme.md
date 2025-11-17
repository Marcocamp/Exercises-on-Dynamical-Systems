# Exercises on Dynamical Systems

Materiale tecnico dedicato allo studio e alla simulazione di sistemi dinamici continui e discreti.  
Il repository raccoglie esercizi, notebook e script Python utilizzati per analizzare modelli matematici, integrare equazioni differenziali e studiare le proprietà dinamiche dei sistemi.

L’obiettivo è fornire un supporto pratico allo studio universitario della teoria dei sistemi, del controllo e della modellistica.

---

## Contenuto del repository

- `Esercizi/` — script Python con implementazioni di modelli dinamici, simulazioni numeriche e analisi delle risposte.
- `img/` — immagini e figure prodotte durante gli esercizi.
- `LICENSE` — licenza Apache-2.0.

---

## Prerequisiti teorici

Gli esercizi fanno riferimento a concetti fondamentali della teoria dei sistemi dinamici, tra cui:

- equazioni differenziali ordinarie (ODE) e formulazione in spazio di stato;
- sistemi lineari e non lineari;
- stabilità e comportamento asintotico;
- risposta libera e risposta forzata;
- integrazione numerica (metodi di Runge–Kutta tramite `scipy.integrate`).

Il livello richiesto è compatibile con un corso universitario di Automatica o Sistemi Dinamici.

---

## Dipendenze software

Gli esempi utilizzano tipicamente:

- Python ≥ 3.12.11
- Control  
- NumPy  
- SciPy  
- Matplotlib  
- Jupyter Notebook

Se disponibile il file `requirements.txt`, è possibile installare tutto tramite:

```bash
pip install -r requirements.txt
