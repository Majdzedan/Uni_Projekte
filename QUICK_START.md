# Quick Start Guide

## Schnelleinstieg für neue Projekte

### 1. Neues Projekt erstellen

```bash
# Projektordner erstellen
mkdir mein-neues-projekt
cd mein-neues-projekt

# Unterordner anlegen
mkdir images
mkdir code

# Template kopieren
cp ../TEMPLATE.md README.md
```

### 2. README ausfüllen

Öffnen Sie `README.md` und ersetzen Sie:
- `[Projektname]` → Ihr Projektname
- `[z.B. WS 2023/24]` → Ihr Semester
- `[Name des Kurses/Moduls]` → Ihr Kurs
- Alle anderen `[Platzhalter]` mit Ihren Informationen

### 3. Bilder hinzufügen

```bash
# Bilder in den images Ordner kopieren
cp /pfad/zu/ihrem/bild.png images/

# In README.md einbinden:
# ![Beschreibung](./images/bild.png)
```

### 4. Code hinzufügen (optional)

```bash
# Code-Dateien in den code Ordner kopieren
cp /pfad/zu/ihrem/code.py code/

# requirements.txt für Python erstellen
pip freeze > code/requirements.txt
```

### 5. Projekt zur Hauptseite hinzufügen

Öffnen Sie die Haupt-`README.md` und fügen Sie unter "Projekte" hinzu:

```markdown
### Mein Projekt
- **Semester:** WS 2024/25
- **Kurs:** Kursname
- **Beschreibung:** Kurze Beschreibung
- [→ Zum Projekt](./mein-neues-projekt/)
```

### 6. Änderungen committen

```bash
git add .
git commit -m "Add [Projektname] project"
git push
```

## Hilfreiche Kommandos

```bash
# Repository-Struktur anzeigen
tree -L 2 -I '.git'

# Alle Markdown-Dateien finden
find . -name "*.md"

# Bilder finden
find . -name "*.png" -o -name "*.jpg"
```

## Tipps

- ✅ Verwenden Sie aussagekräftige Ordner- und Dateinamen
- ✅ Fügen Sie Bilder hinzu, um Ergebnisse zu visualisieren
- ✅ Dokumentieren Sie Herausforderungen und Lösungen
- ✅ Heben Sie Ihre spezifischen Beiträge hervor
- ✅ Prüfen Sie Rechtschreibung und Grammatik

## Ressourcen

- **Ausführliche Anleitung:** [ANLEITUNG.md](./ANLEITUNG.md)
- **Projekt-Template:** [TEMPLATE.md](./TEMPLATE.md)
- **Beispiel-Projekt:** [beispiel-projekt/](./beispiel-projekt/)

---

**Los geht's! 🚀**
