# 🎓 Predict Students' Dropout and Academic Success

Questo progetto analizza i fattori che influenzano l'abbandono scolastico e il successo accademico degli studenti universitari, utilizzando tecniche di **Machine Learning** per prevedere se uno studente completerà gli studi o si ritirerà.

## 🚀 Obiettivo del Progetto
L'obiettivo è fornire uno strumento predittivo capace di identificare precocemente gli studenti a rischio, permettendo alle istituzioni accademiche di intervenire con strategie di supporto mirate.

## 📊 Struttura del Repository
Il progetto è diviso in tre fasi principali, ognuna documentata in un notebook dedicato:

1. **`01_data_analysis.ipynb`**: Analisi Esplorativa dei Dati (EDA) per comprendere le correlazioni tra background familiare, demografia e performance accademica.
2. **`02_data_cleaning.ipynb`**: Pulizia dei dati, gestione delle macro-categorie (Feature Engineering) e preparazione del dataset finale.
3. **`data_modeling.ipynb`**: Addestramento e confronto tra modelli di classificazione (Regressione Logistica e Random Forest) con analisi della confidenza delle previsioni.

## 🧠 Modelli e Risultati
Abbiamo testato diverse architetture ottenendo i seguenti risultati:

* **Regressione Logistica**: Modello scelto per la produzione grazie a un'**accuratezza del 92%** e un'ottima capacità di generalizzazione.
* **Random Forest**: Utilizzato per convalidare i risultati e identificare le feature più importanti.

### Variabili Decisive (Feature Importance)
L'analisi ha rivelato che i fattori più influenti per la previsione sono:
1. Voti e unità curriculari approvate nel **2° semestre**.
2. Performance accademica del **1° semestre**.
3. Stato dei pagamenti delle tasse scolastiche (**Tuition fees up to date**).

## 🛠️ Tecnologie Utilizzate
* **Linguaggio**: Python
* **Librerie**: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib
* **Ambiente**: Jupyter Notebook / VS Code

## 📈 Analisi della Confidenza
Il modello finale mostra una distribuzione delle probabilità molto netta, indicando una forte separazione tra le classi e un'alta affidabilità nelle previsioni sia per i casi di successo che per quelli di abbandono.

---
*Progetto realizzato come caso studio di analisi predittiva applicata all'istruzione.*
