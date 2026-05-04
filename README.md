# sitzplatzbuchung-krankenkasse
Beispielprojekt für die Einsendeaufgabe DVC-E1: Versionsverwaltung

## 1. Repository erstellt

Ich habe ein öffentliches GitHub-Repository für die Einsendeaufgabe DVC-E1 erstellt.

Repository-Link:
https://github.com/DEINNAME/sitzplatzbuchung-krankenkasse

Nachweis:
Das Repository ist öffentlich sichtbar und enthält eine README.md.

## 2. Eigenes Projekt hochgeladen

Ich habe ein eigenes Beispielprojekt zum Thema Sitzplatzbuchungssystem für eine Krankenkasse erstellt.

Folgende Projektdateien wurden angelegt:

- `README.md`
- `mission.md`
- `roadmap.md`
Kurzer Testeintrag für git pull.

## 3. Relevante Git-Methoden angewendet

Ich habe die in der Lerneinheit genannten relevanten Git-Methoden praktisch angewendet. Das GitHub-Repository und die Commit-Historie dienen als Nachweis. Zusätzlich habe ich Screenshots der Konsolenausgaben erstellt und in diesem Repository abgelegt.

Die Screenshots befinden sich im Ordner:

`screenshots/`

### Verwendete Befehle

- `git status` – Zustand des Arbeitsverzeichnisses geprüft
- `git diff` – Änderungen vor dem Commit angezeigt
- `git add` – Dateien zur Staging Area hinzugefügt
- `git commit` – Änderungen lokal gespeichert
- `git push` – lokale Änderungen nach GitHub hochgeladen
- `git pull` – Änderungen von GitHub lokal übernommen
- `git mv` – Datei versioniert umbenannt
- `git rm` – Datei versioniert gelöscht
- `git log --oneline` – Commit-Historie angezeigt
- `git branch` – Branch erstellt bzw. angezeigt
- `git checkout` – Branch gewechselt
- `git merge` – Branch in `main` zusammengeführt

### Screenshot-Nachweise

## 4. Zeitreisen mit Git

Ich habe mit Git eine Zeitreise durchgeführt. Dafür habe ich zuerst mit `git log --oneline` einen älteren Commit gesucht und anschließend mit folgendem Befehl ausgecheckt:

```bash
git checkout 7fe67bd

## 5. Branches erstellen, wechseln und mergen

Ich habe zwei unterschiedliche, aber ähnliche Branches erstellt:

- `feature-login-pin`
- `feature-login-chipkarte`

Auf dem ersten Branch wurde ein Login per PIN dokumentiert. Auf dem zweiten Branch wurde ein Login per Chipkarte dokumentiert. Danach bin ich zwischen den Branches hin und her gewechselt und habe beide Branches wieder in den Hauptbranch `main` gemerged.

Verwendete Befehle:

```bash
git checkout -b feature-login-pin
git add feature-login-pin.md
git commit -m "Feature Login mit PIN hinzufügen"

git checkout main
git checkout -b feature-login-chipkarte
git add feature-login-chipkarte.md
git commit -m "Feature Login mit Chipkarte hinzufügen"

git checkout feature-login-pin
git checkout feature-login-chipkarte
git checkout main

git merge feature-login-pin
git merge feature-login-chipkarte
git push
