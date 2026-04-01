# Datenanalyse Projekt

## Übersicht

**Semester:** WS 2023/24  
**Kurs:** Einführung in Data Science  
**Dauer:** 3 Monate (Oktober 2023 - Januar 2024)  
**Team:** Einzelarbeit

## Beschreibung

Dieses Projekt befasste sich mit der Analyse von Verkaufsdaten eines fiktiven Online-Shops. Ziel war es, Verkaufstrends zu identifizieren und Empfehlungen für die Optimierung des Produktsortiments abzuleiten.

## Aufgabenstellung

Die Aufgabe bestand darin:
- Verkaufsdaten aus verschiedenen Quellen zu sammeln und zu bereinigen
- Explorative Datenanalyse durchzuführen
- Trends und Muster zu identifizieren
- Visualisierungen zu erstellen
- Handlungsempfehlungen abzuleiten

## Mein Beitrag

Als Einzelarbeit habe ich alle Aspekte des Projekts durchgeführt:
- Datenbereinigung und -vorbereitung
- Statistische Analysen
- Erstellung von Visualisierungen
- Dokumentation der Ergebnisse

## Methodik / Vorgehen

1. **Datensammlung:** Import der Rohdaten aus CSV-Dateien
2. **Datenbereinigung:** Behandlung von fehlenden Werten und Ausreißern
3. **Explorative Analyse:** Berechnung von Kennzahlen und Korrelationen
4. **Visualisierung:** Erstellung von Diagrammen zur Darstellung der Ergebnisse
5. **Interpretation:** Ableitung von Erkenntnissen und Empfehlungen

## Verwendete Technologien / Werkzeuge

- **Python** - Programmiersprache für die Datenanalyse
- **Pandas** - Datenmanipulation und -analyse
- **Matplotlib & Seaborn** - Datenvisualisierung
- **Jupyter Notebook** - Entwicklungsumgebung für explorative Analyse
- **NumPy** - Numerische Berechnungen

## Ergebnisse

Die Analyse ergab folgende Haupterkenntnisse:
- Saisonale Verkaufsspitzen im Dezember und während der Sommermonate
- Top 20% der Produkte generieren 80% des Umsatzes (Pareto-Prinzip)
- Starke Korrelation zwischen Rabattaktionen und Verkaufszahlen

### Visualisierungen

Die folgenden Visualisierungen veranschaulichen die Hauptergebnisse:

<!-- Beispiel für Bildeinbindung - ersetzen Sie mit echten Bildern -->
<!-- ![Verkaufstrends über Zeit](./images/verkaufstrends.png) -->
<!-- ![Top 10 Produkte](./images/top-produkte.png) -->

*Hinweis: Bilder können im `images/` Ordner abgelegt werden*

## Herausforderungen

**Challenge 1: Unvollständige Daten**  
Einige Datensätze enthielten fehlende Werte. Lösung: Ich habe verschiedene Imputationsstrategien getestet und mich für die Mittelwert-Imputation bei numerischen Werten entschieden.

**Challenge 2: Performance bei großen Datensätzen**  
Die Verarbeitung großer CSV-Dateien war zunächst langsam. Lösung: Optimierung durch chunked reading und Verwendung von effizienteren Datentypen.

## Gelernte Lektionen

- Vertiefte Kenntnisse in Pandas und Datenmanipulation
- Wichtigkeit der Datenqualität für aussagekräftige Analysen
- Effektive Visualisierung komplexer Daten
- Dokumentation und Reproduzierbarkeit von Analysen

## Weitere Informationen

Dieses Projekt war Teil des Kurses "Einführung in Data Science" und wurde mit der Note 1.3 bewertet.

---

## Code

Der vollständige Quellcode für dieses Projekt befindet sich im `code/` Ordner.

### Hauptdateien

- `code/data_analysis.py` - Hauptskript für die Datenanalyse
- `code/visualizations.py` - Funktionen für die Erstellung von Diagrammen
- `code/data_cleaning.py` - Datenbereinigungsfunktionen

### Ausführung

Falls Code vorhanden ist:

```bash
# Installation der Abhängigkeiten
pip install pandas matplotlib seaborn numpy

# Ausführung der Analyse
python code/data_analysis.py
```

*Hinweis: Dies ist ein Beispielprojekt. Ersetzen Sie den Inhalt mit Ihren tatsächlichen Projektdetails.*
