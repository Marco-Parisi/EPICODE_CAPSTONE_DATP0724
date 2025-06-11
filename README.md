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

## Anteprima del Report in Power BI
![Analisi Modelli ML-1](https://github.com/user-attachments/assets/0f777dfd-8c1f-42b8-920f-520e13b206f4)

### Fonte Dati

Questo progetto utilizza dati provenienti dallo Sloan Digital Sky Survey (SDSS), release DR17.  
Per maggiori informazioni sulle politiche di utilizzo dei dati, visitare il sito ufficiale: https://www.sdss.org/collaboration/citing-sdss/
  
Abdurro'uf et al. (2022), *The 17th Data Release of the Sloan Digital Sky Surveys: Complete Release of MaNGA, MaStar, and APOGEE-2 Data*, The Astrophysical Journal Supplement Series, 259(2), 35.  
DOI: [10.3847/1538-4365/ac4414](https://doi.org/10.3847/1538-4365/ac4414)

[Link al dataset](https://drive.google.com/file/d/1brT78QRggRkZhLIbCDpeoiFuwgm5_T0U/view?usp=sharing) ~ 700MB
