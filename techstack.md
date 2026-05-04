## Ziel des Techstacks

Der Techstack beschreibt mögliche Technologien für die technische Umsetzung des Sitzplatzbuchungssystems. Ziel ist ein webbasiertes System, das von Mitarbeitenden über den Browser genutzt werden kann.

---

## Frontend

Für das Frontend kann eine moderne Webtechnologie verwendet werden.

Mögliche Technologien:

- HTML
- CSS
- JavaScript
- React oder Angular

### Begründung

Ein webbasiertes Frontend ermöglicht die Nutzung des Systems über verschiedene Geräte und Browser. Mitarbeitende können das System ohne lokale Installation verwenden.

---

## Backend

Für das Backend kann eine serverseitige Anwendung eingesetzt werden.

Mögliche Technologien:

- Java mit Spring Boot
- Node.js mit Express
- C# mit ASP.NET Core

### Begründung

Das Backend verarbeitet Buchungen, prüft Verfügbarkeiten, verhindert Doppelbuchungen und verwaltet Benutzerrechte.

## Git-Nachweis

Diese Zeile wurde lokal ergänzt, um git diff, git add, git commit und git push nachzuweisen.

---

## Datenbank

Für die Speicherung der Sitzplätze, Buchungen und Benutzerdaten kann eine relationale Datenbank verwendet werden.

Mögliche Technologien:

- PostgreSQL
- MySQL
- Microsoft SQL Server

### Begründung

Eine relationale Datenbank eignet sich gut für strukturierte Daten wie Standorte, Stockwerke, Sitzplätze, Benutzer und Buchungen.

---

## Authentifizierung

Die Anmeldung sollte über bestehende Mitarbeiterkonten erfolgen.

Mögliche Technologien:

- Single Sign-on
- LDAP
- Azure Active Directory
- OAuth 2.0 / OpenID Connect

### Begründung

Durch die Nutzung bestehender Mitarbeiterkonten kann sichergestellt werden, dass nur berechtigte Personen Zugriff auf das System erhalten.

---

## Datenschutz und Sicherheit

Da es sich um eine Krankenkasse handelt, ist der Schutz personenbezogener Daten besonders wichtig.

Wichtige Maßnahmen:

- Rollenbasierte Berechtigungen
- Zugriff nur auf eigene Buchungen
- Verschlüsselte Verbindung über HTTPS
- Protokollierung administrativer Änderungen
- Minimierung personenbezogener Daten
- Regelmäßige Prüfung der Zugriffsrechte

---

## Deployment

Das System kann als Webanwendung auf einem internen Server oder in einer sicheren Cloud-Umgebung betrieben werden.

Mögliche Varianten:

- Interner Unternehmensserver
- Private Cloud
- Containerisierung mit Docker

### Begründung

Ein zentral betriebenes System erleichtert Wartung, Updates und Zugriffskontrolle.
