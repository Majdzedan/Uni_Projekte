# Anleitung: Universitätsprojekte dokumentieren

Diese Anleitung hilft Ihnen dabei, Ihre Universitätsprojekte professionell zu dokumentieren und in diesem Repository zu organisieren.

## Warum dokumentieren?

- **Für Bewerbungen:** Zeigen Sie potenziellen Arbeitgebern Ihre Fähigkeiten und Erfahrungen
- **Für sich selbst:** Behalten Sie den Überblick über Ihre Lernerfolge
- **Für andere:** Teilen Sie Ihr Wissen und Ihre Erfahrungen

## Schritt-für-Schritt Anleitung

### 1. Projektordner erstellen

Erstellen Sie einen neuen Ordner mit einem aussagekräftigen Namen:

```bash
mkdir mein-projekt
cd mein-projekt
```

**Namenskonventionen:**
- Verwenden Sie Kleinbuchstaben
- Trennen Sie Wörter mit Bindestrichen
- Beispiele: `datenbank-projekt`, `ki-chatbot`, `webentwicklung-shop`

### 2. Basis-Struktur anlegen

```bash
mkdir images
mkdir code
```

- `images/` - Für Screenshots, Diagramme, Fotos
- `code/` - Für Quellcode (optional)

### 3. README.md erstellen

Kopieren Sie die `TEMPLATE.md` als Ausgangspunkt:

```bash
cp ../TEMPLATE.md README.md
```

### 4. Projektdetails ausfüllen

Öffnen Sie die `README.md` und ersetzen Sie die Platzhalter mit Ihren Informationen:

#### Wichtige Abschnitte:

**Übersicht:**
- Semester und Zeitraum
- Kursname
- Teamgröße

**Beschreibung:**
- Was war das Ziel?
- Welches Problem wurde gelöst?
- Warum war das Projekt wichtig?

**Methodik:**
- Wie sind Sie vorgegangen?
- Welche Schritte haben Sie unternommen?
- Welche Entscheidungen mussten getroffen werden?

**Ergebnisse:**
- Was haben Sie erreicht?
- Welche konkreten Outputs gibt es?
- Gibt es messbare Erfolge?

**Herausforderungen:**
- Welche Probleme traten auf?
- Wie haben Sie diese gelöst?
- Was haben Sie daraus gelernt?

### 5. Bilder hinzufügen

Legen Sie Ihre Bilder im `images/` Ordner ab und binden Sie sie ein:

```markdown
![Beschreibung](./images/bild.png)
```

**Tipps für gute Visualisierungen:**
- Verwenden Sie beschreibende Dateinamen
- Optimieren Sie Bildgrößen (nicht zu groß)
- Fügen Sie aussagekräftige Alternativtexte hinzu
- Formate: PNG für Screenshots, JPG für Fotos

### 6. Code organisieren (optional)

Falls Ihr Projekt Code enthält:

```
code/
├── main.py (oder main.java, etc.)
├── utils.py
├── requirements.txt (für Python)
└── README.md (Ausführungsanleitung)
```

**Code-Dokumentation:**
- Fügen Sie Kommentare hinzu
- Erstellen Sie eine requirements.txt / package.json
- Dokumentieren Sie die Installation und Ausführung

### 7. Hauptliste aktualisieren

Fügen Sie Ihr Projekt zur Liste in der Haupt-README.md hinzu:

```markdown
### Mein Projekt
- **Semester:** WS 2023/24
- **Kurs:** Kursname
- **Beschreibung:** Kurze Zusammenfassung
- [→ Zum Projekt](./mein-projekt/)
```

## Best Practices

### Für Bewerbungen optimieren

1. **Fähigkeiten hervorheben:** Betonen Sie verwendete Technologien und erworbene Skills
2. **Quantifizierbare Ergebnisse:** Nennen Sie Zahlen, wo möglich (z.B. "20% Effizienzsteigerung")
3. **Problemlösungskompetenz:** Zeigen Sie, wie Sie Herausforderungen gemeistert haben
4. **Teamarbeit:** Bei Gruppenprojekten: Beschreiben Sie Ihre spezifische Rolle

### Schreibstil

- **Klar und präzise:** Vermeiden Sie unnötigen Fachjargon
- **Aktiv statt passiv:** "Ich entwickelte..." statt "Es wurde entwickelt..."
- **Strukturiert:** Verwenden Sie Listen und Absätze
- **Professionell:** Achten Sie auf Rechtschreibung und Grammatik

### Visuelle Gestaltung

- **Konsistent:** Gleiche Formatierung in allen Projekten
- **Übersichtlich:** Nutzen Sie Überschriften und Absätze
- **Visuell ansprechend:** Fügen Sie Bilder und Diagramme hinzu
- **Lesbar:** Nicht zu viel Text in einem Abschnitt

## Checkliste vor dem Commit

- [ ] README.md vollständig ausgefüllt
- [ ] Alle Bilder im `images/` Ordner
- [ ] Code im `code/` Ordner (falls vorhanden)
- [ ] Rechtschreibung und Grammatik geprüft
- [ ] Links funktionieren
- [ ] Projekt in Haupt-README.md eingetragen
- [ ] Sensible Daten entfernt (Passwörter, API-Keys, etc.)

## Projekttypen und Anpassungen

### Theoretische Arbeit (ohne Code)

Wenn Ihr Projekt keinen Code enthält:
- Fokus auf Methodik und Ergebnisse
- Mehr Visualisierungen und Diagramme
- Detaillierte Beschreibung des theoretischen Ansatzes
- Löschen Sie den Code-Abschnitt in der README

### Praktisches Projekt (mit Code)

Wenn Ihr Projekt hauptsächlich Code ist:
- Gute Code-Dokumentation
- Ausführungsanleitung
- Screenshots der Anwendung
- Erklärung der Architektur

### Forschungsprojekt

Für Forschungsprojekte:
- Forschungsfrage klar formulieren
- Methodik detailliert beschreiben
- Ergebnisse mit Daten untermauern
- Limitationen und Ausblick

### Gruppenprojekt

Bei Teamarbeit:
- Ihre spezifische Rolle beschreiben
- Teamgröße und -zusammensetzung
- Arbeitsteilung erklären
- Ihren Beitrag hervorheben

## Hilfreiche Ressourcen

- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Markdown Syntax](https://docs.github.com/en/get-started/writing-on-github)
- [Wie schreibe ich gute README.md](https://www.makeareadme.com/)

## Fragen?

Bei Fragen zur Dokumentation können Sie:
- Die `beispiel-projekt/` Referenz ansehen
- Die `TEMPLATE.md` als Ausgangspunkt nutzen
- Andere erfolgreiche GitHub-Portfolios als Inspiration verwenden

---

**Viel Erfolg beim Dokumentieren Ihrer Projekte!** 🎓
