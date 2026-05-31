# Fußball-Taktik-Tool — KONTEXT
*Erstellt: 31.05.2026*

## 🎯 Projektbeschreibung
Digitales Taktik-Board für den **Blomberger SV A-Jugend** Team. Ermöglicht interaktive Spielerpositionierung, Taktik-Planung und Szenario-Management für Training und Spielanalyse.

## 👤 Zielgruppe
- **Hauptnutzer:** Rafael Maaßen (Trainer BSV)
- **Sekundär:** Andere Trainer, Spieler für Selbstanalyse
- **Kontext:** Vereinstraining, Spielvorbereitung, Taktik-Besprechungen

## 🏗️ Technische Architektur

### Frontend (Standalone Web-App)
- **Technologie:** Pure HTML5/CSS3/JavaScript
- **Framework:** Vanilla JS (keine Abhängigkeiten)
- **Design:** Dark Theme mit BSV-Vereinsfarben (#22c55e Grün)
- **Layout:** Responsive, Touch-optimiert

### Datenstruktur
```javascript
{
  "timestamp": "ISO-Date",
  "scenarios": {
    "1": {
      "players": {
        "Spielername": {
          "name": "string",
          "number": "string", 
          "x": float,  // Position X
          "y": float   // Position Y
        }
      }
    }
  }
}
```

### Features
- **Drag & Drop:** Spieler frei positionierbar
- **Szenario-Management:** Speichern, Laden, Wechseln zwischen Szenarien
- **Export:** JSON-Format für Datenpersistierung
- **Responsive:** Funktioniert auf Desktop & Tablet
- **Offline:** Komplett lokale Anwendung

## 📁 Datei-Organisation

### Hauptdateien
| Datei | Zweck | Format |
|-------|-------|--------|
| `A-Jgd-Blomberger-taktik-profi_10.html` | Hauptanwendung | HTML/CSS/JS |
| `blomberger-taktik-*.json` | Gespeicherte Taktiken | JSON |

### Dokumentation
| Datei | Zweck | Format |
|-------|-------|--------|
| `blomberger_taktik_leitfaden.pdf` | Ausführliche Anleitung | PDF |
| `taktikboard_kurzanleitung.html` | Web-Anleitung | HTML |
| `taktikboard_kurzanleitung.pdf` | Druck-Anleitung | PDF |

## 🎨 Design-System
- **Farbschema:** 
  - Hintergrund: `#090d16` (Dunkelblau)
  - Akzent: `#22c55e` (BSV-Grün)
  - Text: `#f8fafc` (Hellgrau)
- **Typografie:** System Fonts (Apple/Segoe UI)
- **Layout:** Modern, minimalistisch, professionell

## 🚀 Deployment & Usage
- **Hosting:** Lokal (Datei im Browser öffnen)
- **URL:** `file:///C:/Users/rafae/Claude.Dateien/PROJEKTE/Fussball-Taktik-Tool/A-Jgd-Blomberger-taktik-profi_10.html`
- **Backup:** JSON-Dateien regelmäßig sichern
- **Sharing:** HTML-Datei auf USB-Stick oder per E-Mail

## 🔧 Entwicklungshistorie
- **Version 10:** Aktuelle stabile Version
- **Features V10:** Vollständiges Taktik-Board mit allen Grundfunktionen
- **Entwickelt:** Für spezifische Bedürfnisse BSV A-Jugend
- **Spielerliste:** Echte Spielernamen bereits integriert

## 📈 Erweiterungsmöglichkeiten
- **Animation:** Spielzüge mit Bewegungspfaden
- **PDF-Export:** Taktiken als PDF speichern
- **Cloud-Sync:** Online-Synchronisation zwischen Geräten
- **Multi-Team:** Support für mehrere Teams/Ligen
- **Spielanalyse:** Integration von Spielstatistiken

## 🔒 Sicherheit & Datenschutz
- **Lokal:** Alle Daten bleiben auf dem Rechner
- **Keine Server:** Keine externe Datenübertragung
- **Privacy:** Spielernamen nur lokal gespeichert
- **Backup:** JSON-Dateien regelmäßig sichern empfohlen

---
*Tool entwickelt für professionelle Taktik-Planung im Amateurfußball*