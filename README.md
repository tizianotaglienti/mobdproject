# mobdproject

Il progetto è eseguito in ambiente Python, sottoforma di notebook Jupyter.
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/1200px-Jupyter_logo.svg.png" width=40px>

Il gestore di pacchetti utilizzato è Anaconda.
<img src="https://upload.wikimedia.org/wikipedia/en/c/cd/Anaconda_Logo.png" width=70px>

Per quanto riguarda le librerie, l'unica che è stata importata manualmente è SMOTE da imblearn.over_sampling.
Per farlo è bastato scrivere sulla PowerShell di Anaconda il seguente comando:

**conda install -c conda-forge imbalanced-learn**

Istruzioni per l'esecuzione:
- inserire il file di test "test_set.csv" nella stessa directory contenente il notebook, il file "train.csv", la cartella "pickles"
- eseguire il run del codice nel notebook *predict.ipynb*
