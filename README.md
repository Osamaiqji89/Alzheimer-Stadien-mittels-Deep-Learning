# Alzheimer MRT Klassifikation mit Deep Learning

Klassifikation von Alzheimer-Stadien mittels Convolutional Neural Network (CNN) anhand von Gehirn-MRT-Aufnahmen.

## Überblick

Dieses Projekt implementiert ein selbst entwickeltes CNN zur automatisierten Klassifikation von vier Alzheimer-Stadien:

| Klasse | Beschreibung |
|--------|--------------|
| NonDemented | Gesund |
| VeryMildDemented | Sehr leichte Demenz |
| MildDemented | Leichte Demenz |
| ModerateDemented | Moderate Demenz |

Zusätzlich wird ein **Autoencoder** implementiert, um die wesentlichen Merkmale der MRT-Bilder in einem komprimierten latenten Raum zu analysieren.

## Datensatz

- **Quelle:** [Kaggle - Alzheimer MRI Dataset](https://www.kaggle.com/datasets/tourist55/alzheimers-dataset-4-class-of-images)
- **Umfang:** ~6.400 vorverarbeitete MRT-Bilder
- **Klassen:** 4 Alzheimer-Stadien

## Technologien

- **Python 3.x**
- **PyTorch** - Deep Learning Framework
- **Torchvision** - Bildverarbeitung
- **NumPy / Pandas** - Datenmanipulation
- **Matplotlib / Seaborn** - Visualisierung
- **scikit-learn** - Metriken und Evaluation
- **KaggleHub** - Datensatz-Download

## Installation

```bash
pip install torch torchvision numpy pandas matplotlib seaborn scikit-learn kagglehub tqdm pillow
```

## Projektstruktur

```
├── Alzheimer_MRI_Klassifikation.ipynb  # Hauptnotebook
└── README.md
```

## Inhalt des Notebooks

1. **Einleitung** - Motivation und Zielsetzung
2. **Theoretische Grundlagen** - CNNs, Autoencoder, Metriken
3. **Implementierung**
   - Datenladung und Exploration
   - Datenvorverarbeitung und Augmentation
   - CNN-Architektur
   - Modelltraining
   - Autoencoder
4. **Ergebnisse und Diskussion**
5. **Zusammenfassung und Ausblick**

## Ausführung

1. Notebook in Jupyter oder VS Code öffnen
2. Alle Zellen sequentiell ausführen
3. GPU wird automatisch erkannt (falls verfügbar)

## Autor

**Sultan**  
Studiengang: Angewendete Künstliche Intelligenz  
Modul: Deep Learning (WiSe 2025/26)

## Lizenz

Dieses Projekt wurde im Rahmen einer akademischen Arbeit erstellt.
