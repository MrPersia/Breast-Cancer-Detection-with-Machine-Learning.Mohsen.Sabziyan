# Breast Cancer Detection with Machine Learning

Dieses Projekt befasst sich mit der Anwendung von Machine Learning-Algorithmen zur Brustkrebsdiagnose. Der Datensatz stammt aus dem Breast Cancer Wisconsin (Diagnostic) Dataset von [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)).

## Über den Datensatz
Der Datensatz enthält Merkmale, die aus Bildern von feinen Nadelbiopsien der Brust extrahiert wurden. Die Merkmale werden verwendet, um zwischen malignen (bösartigen) und benignen (gutartigen) Tumoren zu unterscheiden. Die Zielvariable ist binär, wobei 0 für maligne und 1 für benign steht.

### Merkmale
- Mean Radius
- Mean Texture
- Mean Perimeter
- ...
- Worst Fractal Dimension

### Klassifikationsalgorithmen
- Logistische Regression
- Support Vector Machine (SVM)
- Entscheidungsbaum
- Random Forest
- Naive Bayes

## Ergebnisse
Nach dem Training und Testen der Algorithmen ergaben sich folgende Ergebnisse:

### Logistische Regression
- Genauigkeit: 96.49%
- F1-Score (Malignant): 0.95
- F1-Score (Benign): 0.97

### Support Vector Machine (SVM)
- Genauigkeit: 94.74%
- F1-Score (Malignant): 0.93
- F1-Score (Benign): 0.96

### Entscheidungsbaum
- Genauigkeit: 92.98%
- F1-Score (Malignant): 0.91
- F1-Score (Benign): 0.94

### Random Forest
- Genauigkeit: 96.49%
- F1-Score (Malignant): 0.95
- F1-Score (Benign): 0.97

### Naive Bayes
- Genauigkeit: 97.37%
- F1-Score (Malignant): 0.96
- F1-Score (Benign): 0.98

Der Naive Bayes Algorithmus zeigte die beste Leistung mit einer Genauigkeit von 97.37% und hohen F1-Scores für beide Klassen.

## Verwendung
1. Klonen Sie dieses Repository: `git clone https://github.com/dein-benutzername/breast-cancer-detection.git`
2. Wechseln Sie in das Verzeichnis: `cd breast-cancer-detection`
3. Installieren Sie die erforderlichen Pakete: `pip install -r requirements.txt`
4. Führen Sie das Jupyter Notebook aus: `jupyter notebook breast_cancer_detection.ipynb`
5. Experimentieren Sie mit den Algorithmen und dem Code!

## Quellen
- [UCI Machine Learning Repository - Breast Cancer Wisconsin (Diagnostic) Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- [Scikit-learn Dokumentation](https://scikit-learn.org/stable/documentation.html)
