# Data-Mining-Project

## Descrizione del Progetto

Questo repository ospita un progetto di Data Mining finalizzato all'analisi comparativa e approfondita di quattro dataset distinti.
L'obiettivo primario del lavoro è l'applicazione di tecniche di **classificazione** avanzate, testando e valutando le performance di diversi modelli predittivi su ciascuno dei dataset selezionati.

Il flusso di lavoro include:
1.  Analisi esplorativa dei dati (EDA).
2.  Pre-processing e pulizia dei dati.
3.  Addestramento di modelli di classificazione.
4.  Valutazione delle performance (Accuracy, Precision, Recall, F1-Score).

## Datasets

I dati utilizzati per questo studio provengono da OpenML. Di seguito i dettagli e i collegamenti diretti alle fonti ufficiali:

* **Banknote Authentication**
    * *Descrizione:* Dati estratti da immagini di banconote per valutarne l'autenticità.
    * 🔗 [Link al dataset (OpenML ID: 1462)](https://openml.org/search?type=data&id=1462)

* **Ionosphere**
    * *Descrizione:* Dati radar raccolti a Goose Bay, Labrador, per classificare i ritorni radar dall'atmosfera.
    * 🔗 [Link al dataset (OpenML ID: 59)](https://openml.org/search?type=data&id=59)

* **WDBC (Wisconsin Diagnostic Breast Cancer)**
    * *Descrizione:* Caratteristiche calcolate da un'immagine digitalizzata di un aspirato con ago sottile (FNA) di una massa mammaria.
    * 🔗 [Link al dataset (OpenML ID: 1510)](https://openml.org/search?type=data&id=1510)

* **Seismic-Bumps**
    * *Descrizione:* Dati sismici per prevedere eventi pericolosi in miniere di carbone.
    * 🔗 [Link al dataset (OpenML ID: 1500)](https://openml.org/search?type=data&id=1500)

## Tecnologie Utilizzate

* **Linguaggio:** Python 3.x
* **Librerie principali:**
    * Scikit-learn (Modellazione e Preprocessing)
    * Pandas (Manipolazione dati)
    * NumPy (Calcolo numerico)
    * Matplotlib / Seaborn (Visualizzazione dati)

## Come Eseguire il Progetto

1.  Installare le dipendenze:
    ```bash
    pip install -r requirements.txt
    ```
2.  Eseguire i notebook di analisi:
    ```bash
    jupyter notebook
    ```

## Risultati Attesi

Per ogni dataset verranno prodotti:
* Matrici di confusione.
* Confronto delle metriche di classificazione tra i diversi modelli testati.
* Analisi dell'importanza delle feature (dove applicabile).

---
*Progetto realizzato per il corso di Data Mining*