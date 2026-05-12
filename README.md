[README.md](https://github.com/user-attachments/files/27656961/README.md)
# Tiffany & Benedikt – Sitzplan

## Dateien

| Datei | Beschreibung |
|---|---|
| `index.html` | Die komplette Sitzplan-App |
| `gaeste.csv` | Gästeliste mit Tischzuweisung |
| `fonts/` | Ordner für deine Schriftarten |

## Schriftarten einbinden

1. Erstelle einen Ordner `fonts/` im Repository
2. Lege diese Dateien dort ab:
   - `Humble.woff2` (empfohlen)
   - `Humble.woff`
   - `Humble.ttf`
3. Die `index.html` lädt sie automatisch von `fonts/Humble.*`

## Gästeliste aktualisieren

Öffne `gaeste.csv` und bearbeite sie:

```
Name,Tisch
Anna Müller,1
Peter Müller,1
Emma Fischer,2
...
```

**Regeln:**
- Erste Zeile muss `Name,Tisch` sein (Spaltenüberschriften)
- Pro Zeile: `Vollständiger Name,Tischnummer`
- Maximal 10 Gäste pro Tisch
- Tischnummern: 1–6

## GitHub Pages aktivieren

1. Repository auf GitHub erstellen
2. Alle Dateien hochladen
3. **Settings → Pages → Branch: main → / (root) → Save**
4. Nach ~2 Minuten ist die Seite unter `https://dein-name.github.io/repo-name` erreichbar

## Funktionen

- 🔍 **Suche**: Gast nach Name suchen → Tisch wird hervorgehoben
- 🎯 **Filter**: Einzelne Tische ein-/ausblenden
- 📂 **CSV-Import**: Gästeliste einfach in Excel bearbeiten, als CSV speichern, hochladen
