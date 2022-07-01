# mobdproject

Il progetto è eseguito in ambiente Python, sottoforma di notebook Jupyter.
Il gestore di pacchetti utilizzato è Anaconda.
Per quanto riguarda le librerie, l'unica che è stata importata manualmente è SMOTE da imblearn.over_sampling.
Per farlo è bastato scrivere sulla PowerShell di Anaconda il seguente comando:

**conda install -c conda-forge imbalanced-learn**

Istruzioni per l'esecuzione:
- inserire il file di test "test_set.csv" nella stessa directory contenente il notebook e il file "train.csv"
- come riportato nella cella di markdown "Caricamento e pulizia dataset", nella riga 17 della prima cella di codice, cambiare opportunamente il separatore per la lettura del test set (, o ;)
- infine eseguire il run dell'intero codice