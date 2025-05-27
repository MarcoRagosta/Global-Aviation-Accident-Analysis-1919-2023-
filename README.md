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
| Colonna        | Descrizione                                        |
| -------------- | -------------------------------------------------- |
| `date`         | Data dell'incidente                                |
| `type`         | Tipo/modello del velivolo                          |
| `registration` | Codice di registrazione dell’aeromobile            |
| `operator`     | Compagnia/ente operatore                           |
| `fatalities`   | Numero totale di vittime (equipaggio + passeggeri) |
| `location`     | Luogo specifico dell’incidente                     |
| `country`      | Nazione dell’incidente                             |
| `cat`          | Categoria ASN dell’incidente                       |

<br>

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

<br>

## Bonus: Cartogramma Geografico 🗺️ 
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

<br>

## Estensioni Future 🧪 
- Integrazione con fonti esterne (es. condizioni meteo, traffico aereo)
- Dashboard web interattiva per stakeholder IASS
- Modelli di previsione del rischio per area geografica e periodo
- Segmentazione degli incidenti per contesto operativo (commerciale, militare, privato)

<br>

## Licenza 🔐
Questo progetto è rilasciato sotto licenza MIT. Vedi il file LICENSE per i dettagli.

<br>

## Contributi 🤝 
I contributi sono benvenuti! Apri un'Issue per segnalare problemi o proporre funzionalità. Pull Request strutturate sono incoraggiate.
