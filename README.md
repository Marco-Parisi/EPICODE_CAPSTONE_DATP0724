# EPICODE Capstone

Il progetto ha lo scopo di esplorare e confrontare diverse soluzioni di machine learning applicate alla **classificazione** di dati tabulari. In particolare, l'analisi si concentra sulla capacità dei modelli di distinguere tre classi di oggetti astronomici: **Galassie**, **Quasar** e **Stelle**, utilizzando i dati del catalogo SDSS (Sloan Digital Sky Survey).

## Obiettivi 
- Addestrare e valutare le prestazioni predittive dei modelli.
- Stimare i costi per l’addestramento dei modelli sul servizio cloud computing **Azure Machine Learning**.

*L'addestramento iniziale viene eseguito su un computer personale con specifiche hardware riportate alla fine.*    

## Tecnologie

- **SQL** per l'estrazione dei dati del database SDSS.

- **Python** JupyterLab, strumento principale utilizzato per la manipolazione, esplorazione dei dati e per l'addestramento e la valutazione dei modelli.
    
- **Power BI** per la visualizzazione interattiva dei risultati e la previsione costi di Azure ML.
  
## Modelli Scelti

Per svolgere questo task sono stati scelti due modelli di machine learning, **Random Forest** e **XGBoost**, e due modelli di deep learning, **Multilayer Perceptron** e **Tabular Transformer**. Ognuno di essi è stato valutato in base al numero di oggetti correttamente identificati per ciascuna classe e alle metriche di classificazione F1 Score e Balanced Accuracy.

### Hardware utilizzato
- **CPU**: Intel Core i7-12700K
- **GPU**: NVIDIA RTX 3060 12GB GDDR6
- **RAM**: 32GB DDR5

---

## Anteprima del Report in Power BI
![Analisi Modelli ML-1](https://github.com/user-attachments/assets/0f777dfd-8c1f-42b8-920f-520e13b206f4)
