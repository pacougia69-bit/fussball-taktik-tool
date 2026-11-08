# Fußball-Taktik-Tool (Taktikboard)
Bereich: Fußball
Stand: 20.10.2026 (Quelle: STATUS.md/KONTEXT.md, letzte Änderung 16.07.2026). Hinweis: Rafael ist seit 01.07.2026 kein Trainer beim Blomberger SV mehr.

## Kurzfassung
Digitales Taktikboard für die A-Jugend des Blomberger SV: Spieler und Ball per Drag-and-Drop verschieben, Laufwege und Pässe als Pfeile zeichnen, bis zu 3 Szenarien speichern, Export und Import als JSON. Läuft komplett im Browser (ohne Server), auch auf Tablet und Handy.

## Zwei Versionen
- Private Arbeitskopie im Projektordner (V11) mit den echten Spielernamen. Nur lokal.
- Öffentliche, anonymisierte Version auf rmaassen.de/taktik-tool (Spieler 1 bis 11, weil die Spieler minderjährig sind). Seit 16.07.2026 PIN-geschützt und mit eingebautem Hilfe-Fenster.

## Aufbau, Kosten und Stolpersteine (Stand 30.10.2026)
- Gebaut mit: reinem HTML, CSS und JavaScript ohne Framework und ohne Server, dunkles Design in den BSV-Farben (Grün), für Touch ausgelegt. Szenarien werden im Browser gespeichert und als JSON exportiert. Projektstart am 31.05.2026, private Arbeitskopie zuletzt Version 11 (`A-Jgd-Blomberger-taktik-profi_11.html`), dazu Kurzanleitung und Leitfaden als PDF.
- Läuft auf: lokal als Datei und als anonyme Kopie auf rmaassen.de/taktik-tool (Teil der Homepage, PIN-geschützt, mit eingebautem Hilfe-Fenster seit 16.07.2026).
- Kosten: 0 €.
- Stolpersteine: Die öffentliche Kopie ist anonymisiert (Spieler 1 bis 11), weil die Spieler minderjährig sind. Echte Namen bleiben nur in der privaten Arbeitskopie. Wird eine Version geändert, muss die andere mit angepasst und die Homepage-Kopie deployt werden. Die Anleitung der Web-Version ist noch nicht in die lokale Version übernommen. Rafael ist seit 01.07.2026 kein Trainer mehr, das Tool bleibt aber verfügbar.

## Offen (Roadmap, kein Zeitdruck)
- Voice-Over mit KI-Stimme, Video-Export, weitere Taktiken speichern.
- Die Anleitung aus der Web-Version in die lokale Version übernehmen (nicht gemacht).
- Wird die Web-Version geändert, muss die Kopie auf rmaassen.de mit synchronisiert werden.
