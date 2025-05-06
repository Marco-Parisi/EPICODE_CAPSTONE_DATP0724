# EPICODE Capstone

Il progetto prevede lo sviluppo e l'analisi comparativa di diversi modelli di Machine Learning per la classificazione automatica di oggetti astronomici, quali stelle, galassie e quasar, utilizzando i dati del catalogo SDSS (Sloan Digital Sky Survey).
    
---

## Obiettivi 
- Valutare le prestazioni predittive dei modelli
- Analizzare l'impatto computazionale in termini di tempi di addestramento, consumo energetico e stima delle emissioni di CO2. 

*Tutte le misurazioni energetiche vengono effettuate utilizzando un computer personale e rappresentano stime comparative tra i modelli piuttosto che valori assoluti.*    

---

## Tecnologie

- **SQL** per l'estrazione dei dati del database SDSS.

- **Python**, strumento principale, utilizzato per la manipolazione, esplorazione, addestramento e valutazione dei modelli.
    
- **Power BI** per la visualizzazione interattiva dei risultati su metriche energetiche e impatto ambientale.
    
---

## Modelli di Machine Learning

Per la classificazione degli oggetti astronomici sono stati adottati quattro modelli, scelti per rappresentare approcci eterogenei e confrontabili sia in termini prestazionali che computazionali:

- **Random Forest**: configurato per supportare la classificazione multiclasse e gestire lo sbilanciamento del dataset.
    
- **XGBoost (Extreme Gradient Boosting)**: per l’elevata precisione su dati strutturati e per l'efficienza computazionale.
    
- **FNN (Feedforward Neural Network)**: rete neurale profonda composta da più layer densi. Ottimizzata tramite una funzione di perdita pesata (`CrossEntropyLoss`) per gestire la distribuzione sbilanciata delle classi.
    
- **Transformer Tabellare (TabTransformer)**: architettura ispirata ai Transformer NLP, adattata a dati tabellari. Inclusa per confrontare un approccio moderno con i modelli più tradizionali.

---

### Hardware utilizzato
- **CPU**: Intel Core i7-12700K (TDP 125W)
- **GPU**: NVIDIA RTX 3060 12GB GDDR6 (TDP 170W)
- **RAM**: 32GB DDR5
