# Global-Aviation-Accident-Analysis-1919-2023-
Un progetto commissionato da IASS – International Alliance for Safe Skies
📌 Descrizione del Progetto
La International Alliance for Safe Skies (IASS) ha incaricato lo sviluppo di un’analisi approfondita su oltre 100 anni di incidenti aerei al fine di identificare pattern ricorrenti, criticità sistemiche, e insight strategici utili a migliorare la sicurezza del volo a livello globale.

Il dataset fornito comprende circa 25.000 incidenti aerei registrati tra il 1919 e il 2023, ciascuno descritto da informazioni fondamentali relative al velivolo, al luogo, alla gravità dell'incidente e al contesto operativo.

## Obiettivi del Progetto 🎯
- Identificare trend temporali e geografici degli incidenti
- Valutare la sicurezza degli operatori aerei e dei tipi di velivoli
- Studiare l’impatto degli eventi storici, come l’11 Settembre, sulla frequenza degli incidenti
- Rilevare anomalie e cambiamenti comportamentali nei decenni
- Fornire alla IASS strumenti analitici e visuali per supportare strategie data-driven di prevenzione

## Descrizione del Dataset 🧾 
Ogni riga rappresenta un incidente aereo e contiene i seguenti campi:

### Colonna	Descrizione
#### date	-- Data dell'incidente
#### type	-- Tipo/modello del velivolo coinvolto
#### registration	-- Codice di registrazione dell’aeromobile
#### operator	-- Operatore dell’aeromobile (compagnia aerea, ente governativo, ecc.)
#### fatalities	-- Numero totale di vittime (inclusi equipaggio e passeggeri)
#### location	-- Luogo specifico in cui è avvenuto l’incidente
#### country	-- Nazione in cui è avvenuto l’incidente
#### cat	--	Categoria dell’incidente secondo la classificazione ASN


## Analisi e Insight Principali 📊 
L’analisi esplorerà i dati da molteplici prospettive, tra cui:
### Analisi Geografica 🌍 
- Nazioni con maggior numero di incidenti
- Mappa coropletica (cartogramma) degli incidenti per nazione
- Paesi con la più alta media di fatalità per incidente

### Analisi Temporale 📆 
- Evoluzione del numero di incidenti per anno e per decade
- Impatto dell’11 Settembre 2001 sulle tendenze post-2001
- Stagionalità e frequenza degli incidenti per giorno della settimana e mese

### Analisi per Operatore e Velivolo 🛫
- Operatori più coinvolti e operatori più sicuri
- Modelli di velivoli associati al maggior numero di morti
- Classificazione degli operatori per tasso di fatalità (incidenti fatali / incidenti totali)

### Analisi per Categoria ASN 🗃️
- Distribuzione delle categorie di incidente (cat)
- Gravità media per categoria
- Trend delle categorie nel tempo

### Bonus: Cartogramma Geografico 🗺️ 
È incluso un cartogramma interattivo per visualizzare:
- Il numero assoluto di incidenti per paese
- Il tasso di fatalità medio per incidente
- Heatmap temporale con filtri dinamici

### Tecnologie utilizzate per il cartogramma:
- GeoPandas per il join tra dati incidenti e shapefile
- Plotly o Folium per interattività e visualizzazione
- Supporto a esportazione HTML per uso in reportistica

### Tecnologie e Strumenti Utilizzati 🧰 
- Linguaggio: Python 3.10+
- Librerie principali: pandas, matplotlib, seaborn, plotly, geopandas, folium, datetime, numpy
- Ambiente: Jupyter Notebook
- Visualizzazione: Grafici statici e dinamici, mappe interattive

### Struttura della Repository 📂 
'''├── data/
│   └── aviation_accidents_1919_2023.csv        # Dataset principale
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb                  # Pulizia dati e formattazione
│   ├── 02_eda_overview.ipynb                   # Analisi esplorativa generale
│   ├── 03_temporal_analysis.ipynb              # Analisi temporale
│   ├── 04_geographical_analysis.ipynb          # Analisi geografica e cartogramma
│   ├── 05_operator_aircraft_analysis.ipynb     # Analisi per operatori e modelli
│   └── 06_category_analysis.ipynb              # Analisi per categoria ASN
│
├── outputs/
│   ├── plots/                                  # Grafici salvati
│   └── maps/                                   # Mappe e cartogrammi
│
├── src/
│   └── utils.py                                # Funzioni di supporto riutilizzabili
│
├── requirements.txt                            # Lista delle dipendenze
├── README.md                                   # Descrizione del progetto
└── LICENSE                                     # Licenza del progetto'''





### Estensioni Future 🧪 
- Integrazione con fonti esterne (es. condizioni meteo, traffico aereo)
- Dashboard web interattiva per stakeholder IASS
- Modelli di previsione del rischio per area geografica e periodo
- Segmentazione degli incidenti per contesto operativo (commerciale, militare, privato)

### Licenza 🔐
Questo progetto è rilasciato sotto licenza MIT. Vedi il file LICENSE per i dettagli.

### Contributi 🤝 
I contributi sono benvenuti! Apri un'Issue per segnalare problemi o proporre funzionalità. Pull Request strutturate sono incoraggiate.
