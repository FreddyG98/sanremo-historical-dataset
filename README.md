# 🎤 Dataset Storico Festival di Sanremo (1951 - 2025)

## 📌 Background del Progetto
Questo dataset nasce dall'esigenza di colmare una mancanza di dati strutturati, completi e facilmente accessibili sul Festival di Sanremo all'interno della community di Data Science e Analytics. I dataset attualmente disponibili online si sono rivelati parziali, non aggiornati o presentavano forti incongruenze di formattazione.

Per ovviare a questo problema, ho provveduto a una campagna di **Data Sourcing manuale ed estrazione mirata** direttamente dalle tabelle storiche di Wikipedia, integrando e verificando le informazioni anno per anno. Il risultato è un set di dati pulito, normalizzato e pronto all'uso per attività di Data Exploration, Data Visualization (Power BI/Tableau) o analisi statistiche con Python/R.

---

## 📂 Struttura del Dataset
Il database è suddiviso in moduli verticali (file Excel) per garantire una corretta modularità e facilitare i processi di modellazione dei dati (Star Schema / Snowflake):

* **`Sanremo_Generale_Conduttori.xlsx`**: Anagrafica delle edizioni, location storiche (Teatro Ariston, Casinò di Sanremo) e conduttori/co-conduttori principali.
* **`Sanremo_Vincitori.xlsx`**: Tracciamento storico dei primi tre classificati, titolo del brano, autore e categoria di riferimento.
* **`Sanremo_Partecipanti.xlsx`**: Elenco completo di tutti gli artisti scesi in gara nel corso delle edizioni.
* **`Sanremo_Classifiche.xlsx`**: Posizionamenti finali e metriche di scoring della competizione.
* **`Sanremo_Share_Popolarita.xlsx`**: Dati auditel, share televisivo delle singole serate e metriche di impatto mediatico della kermesse.

---

## 🛠️ Tecnologie e Metodologia
* **Data Sourcing**: Estrazione e validazione manuale da sorgenti web enciclopediche.
* **Data Cleansing**: Normalizzazione delle stringhe (nomi artisti, titoli brani), gestione dei valori nulli (es. edizioni senza eliminatorie o categorie unificate) ed eliminazione dei duplicati operata direttamente su foglio di calcolo.
* **Data Format**: Microsoft Excel (.xlsx), ideale per l'importazione diretta in database relazionali o software di Business Intelligence.

---

## 💡 Idee di Utilizzo per la Community
Il dataset è liberamente utilizzabile per progetti di:
1. **Analisi dei Trend**: Come sono cambiati lo share e l'audience del Festival con l'avvento dei social e del Fantasanremo?
2. **Network Analysis**: Quali conduttori o artisti hanno collezionato più presenze o collaborazioni storiche?
3. **Predizione dei Vincitori**: Studio delle metriche storiche per identificare pattern ricorrenti nei brani podisti.

---

## 👤 Autore

**FreddyG98**

Data Analyst certificato Microsoft:

* Microsoft Certified: Azure Fundamentals (**AZ-900**)
* Microsoft Certified: Azure Data Fundamentals (**DP-900**)

Progetto sviluppato come dimostrazione pratica di:

```text
Data Sourcing from Public Web Sources
Manual Data Extraction and Validation
Historical Data Collection
Data Cleaning and Normalization
Data Quality Checks
Missing Values Management
Duplicate Detection and Removal
Data Standardization
Structured Dataset Design
Microsoft Excel Data Management
Modular Data Organization
Preparation for Relational Data Modeling
Star Schema and Snowflake Schema Readiness
Business Intelligence Data Preparation
Exploratory Data Analysis Dataset Preparation
Data Documentation for Analytics Projects
```
