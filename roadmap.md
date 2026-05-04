# roadmap.md

## Ziel der Roadmap

Die Roadmap beschreibt die ersten drei Iterationen für die Entwicklung des Sitzplatzbuchungssystems. Jede Iteration konzentriert sich auf einen klaren Funktionsbereich, damit das System schrittweise aufgebaut und überprüft werden kann.

---

## Iteration 1: Sitzplätze suchen und anzeigen

### Ziel

In der ersten Iteration soll die Grundlage geschaffen werden, damit Mitarbeitende freie Sitzplätze anhand von Standort, Datum und gegebenenfalls Stockwerk suchen können.

### Geplante Funktionen

- Auswahl des Standorts: Ingolstadt, München oder Wolfsburg
- Auswahl eines Datums oder Zeitraums
- Auswahl eines Stockwerks bei Standort Ingolstadt
- Anzeige freier Sitzplätze
- Anzeige wichtiger Sitzplatzinformationen, z. B. Standort, Stockwerk und Sitzplatznummer

### Ergebnis

Nach dieser Iteration können Mitarbeitende verfügbare Sitzplätze anzeigen lassen. Eine Buchung ist in dieser Iteration noch nicht zwingend erforderlich.

### Validierung

Die Funktion wird geprüft, indem verschiedene Kombinationen aus Standort, Datum und Stockwerk getestet werden. Dabei muss sichergestellt werden, dass nur verfügbare Sitzplätze angezeigt werden.

---

## Iteration 2: Sitzplatz buchen

### Ziel

In der zweiten Iteration soll die eigentliche Buchungsfunktion umgesetzt werden. Mitarbeitende sollen einen freien Sitzplatz für einen bestimmten Zeitraum reservieren können.

### Geplante Funktionen

- Auswahl eines freien Sitzplatzes
- Buchung eines Sitzplatzes
- Anzeige einer Buchungsbestätigung
- Verhinderung von Doppelbuchungen
- Speicherung der Buchung im System

### Ergebnis

Nach dieser Iteration können Mitarbeitende einen freien Sitzplatz buchen. Bereits gebuchte Sitzplätze stehen für denselben Zeitraum nicht mehr zur Verfügung.

### Validierung

Die Buchungsfunktion wird geprüft, indem ein Sitzplatz gebucht und anschließend erneut für denselben Zeitraum ausgewählt wird. Das System muss die zweite Buchung verhindern.

---

## Iteration 3: Buchungen verwalten und Datenschutz sicherstellen

### Ziel

In der dritten Iteration sollen Mitarbeitende ihre eigenen Buchungen einsehen und stornieren können. Zusät
