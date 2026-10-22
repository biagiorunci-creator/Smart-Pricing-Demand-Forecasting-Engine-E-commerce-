# E-Commerce Demand Forecasting & Smart Pricing Engine 📊🤖

## 🎯 Obiettivo del Progetto
Questo progetto dimostra un ciclo completo di analisi dati (End-to-End Data Pipeline) applicato al settore e-commerce. L'obiettivo è analizzare le performance storiche di vendita e sviluppare un modello di Machine Learning in grado di prevedere la domanda giornaliera, supportando il management nelle decisioni di approvvigionamento e pricing.

## 🛠️ Tech Stack & Competenze Utilizzate
* **Data Manipulation & Cleaning:** Python (Pandas)
* **Machine Learning:** Scikit-learn (Random Forest Regressor)
* **Data Visualization & Business Intelligence:** Power BI, Data Storytelling
* **Version Control:** Git / GitHub

## 🔄 Flusso di Lavoro (Data Pipeline)
1. **Data Cleaning & Feature Engineering:** Estrazione e pulizia dell'Online Retail Dataset (UCI). Rimozione di resi, gestione dei valori nulli e creazione di feature temporali (giorno, mese, stagionalità).
2. **Exploratory Data Analysis (EDA):** Identificazione dei trend di fatturato, clienti unici attivi e clusterizzazione geografica delle vendite (focus sul mercato UK).
3. **Machine Learning (Demand Forecasting):** Addestramento di un modello Random Forest sui dati storici (Dic 2010 - Set 2011) per prevedere i volumi di vendita giornalieri. Testing effettuato sul restante 20% del dataset (Ott - Nov 2011).
4. **Data Visualization:** Creazione di una dashboard direzionale in Power BI per il monitoraggio dei KPI finanziari e il confronto visivo tra vendite reali e proiezioni del modello.

## 📈 Dashboard & Insights
La dashboard interattiva (disponibile nel file `.pbix` e in formato PDF) permette al management di:
* Monitorare il fatturato storico globale (8,91 Mln £) e la base clienti (4K).
* Filtrare le performance storiche per singola nazione.
* Valutare l'accuratezza del modello predittivo confrontando le curve delle vendite reali con le stime dell'algoritmo nel periodo di test.

## 📁 Struttura del Repository
* `online_retail.csv`: Il dataset grezzo originale (Online Retail Dataset) utilizzato come base di partenza per l'analisi.
* `Smart Pricing & Demand Forecasting Engine (E-commerce).ipynb`: Notebook Jupyter con il codice Python per l'EDA e il training del modello ML.
* `Historical_Sales.csv` / `Forecast_Results.csv`: Dataset puliti ed esportati con standard di localizzazione europea per l'ingestion nei tool di BI.
* `Ecommerce_Dashboard.pbix`: Il file di progetto Power BI.
* `Dashboard_Preview.pdf`: Esportazione visiva della dashboard per rapida consultazione.

---
*Progetto sviluppato da [Biagio Runci](https://github.com/biagiorunci-creator)*