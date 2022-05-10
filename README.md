# Daten und Information - Docker und Container Basics

Ein Kurs zum Einstieg in die Cloud Computing mittels Docker und Container. Dabei werden die zentralen Konzepte angesprochen und kleine Übungen bereitgestellt.

## Lektüre
0. Syllabus
1. Einführung in die Internet of Things (IoT)
2. Cloud Computing
3. Docker 

## Software
- <a href="https://www.docker.com">Docker</a>

### Definition Docker

*Docker ist eine Freie Software zur Isolierung von Anwendungen mit Hilfe von Containervirtualisierung. Docker vereinfacht die Bereitstellung von Anwendungen, weil sich Container, die alle nötigen Pakete enthalten, leicht als Dateien transportieren und installieren lassen.* Quelle: Wikipedia, 2022

- Lizenz: Apache-Lizenz, Version 2.0, proprietäre Lizenz
- Betriebssystem: Linux, Microsoft Windows, macOS, Unix-ähnliches System
- Aktuelle Version: 20.10.14; (23. März 2022)
- Entwickler: Docker, Inc
- Kategorie: Sandboxing
- Programmiersprache: Go


## Git

Es besteht eine weitere Möglichkeit die Unterlagen auf deinem Computer zu laden. Mit folgenden Befehlen auf der Terminal-Befehlszeile kannst du allesamt Unterlagen dieses Repositories auf deinem Computer ablegen resp. das nennt man in diesem Sinne "das Repository klonen". Damit du immer die aktuellsten Unterrichtsunterlagen auf deinem Computer hast, kannst du mit dem darauffolgendem Befehl auf deiner Terminal-Befehlszeile "git pull" was so viel bedeutet wie "git ziehen" tippen.


Auf deinem Computer:

Dieses Repository klonen:

```
$ git clone https://github.com/dxiai/actup-Docker-und-Container-Basics
```

Aktualisieren Sie Ihre lokale Kopie vor jeder Unterrichtsstunde:

```
$ cd ./actup-Docker-und-Container-Basics
$ git pull
```

## Denkfabrig - Thinktank: Fragen, die während dem Lernen von digitalen Tools auftauchen: 

- Was ist eine Befehlszeile oder eine Eingeabeaufforderung? und wo finde ich sie auf meinem Computer? 
[Das Öffnen oder Beenden von Terminal auf dem Mac](https://support.apple.com/de-ch/guide/terminal/apd5265185d-f365-44cb-8b09-71a064a42125/mac).

*Das Dialogfeld „Ausführen“, das sich mit der Tastenkombination [Win] + [R] öffnen lässt, ermöglicht es, jedes beliebige Windows-Programm durch Eingabe des Namens zu starten. Geben Sie hier „cmd“ ein und klicken Sie auf „OK“, um die Eingabeaufforderung zu öffnen.* Source: [Das Öffnen oder Beenden der Eingabeaufforderung](https://www.ionos.de/digitalguide/server/tools/eingabeaufforderung-oeffnen/). 
- Warum schreiben wir unsere Befehle auf einer Kommandozeile auf, um Aufgaben mit Git zu erledigen? *Die Kommandozeilenversion ist auf jedem Rechner installiert und verfügbar.* [Git und die Kommandozeile](https://git-scm.com/book/de/v2/Erste-Schritte-Die-Kommandozeile).

### ZHAW Moodle Layouts

Das ZHAW Moodle verwendet Bootstrap 4 unbeschränkt. Es können alle Funktionen von Bootstrap genutzt werden. 

> Wichtig: Moodle's markdown interpreter versteht das Quote-Präfix `>` nicht. 

> Wichtig: Moodle's markdown interpreter erlaubt kein Markdown in HTML Code. Falls Bootstrap Alerts und Buttons o.ä. verwendet werden, muss der **gesamte** Inhalte als HTML formatiert werden.

Das ZHAW Moodle verwendet die standard [fontawesome 4.7.0 free Icons](https://fontawesome.com/v4.7.0/icons/). 

Ausserdem wird ein spezieller Satz von Glyphicons verwendet. Das einzige Symbol in dieser Auswahl, das sinnvoll verwendet werden kann, ist das ZHAW Logo: Z.B. `<i class="glyphicon glyphicon-zhaw"></i>`.

## Lizenz

Dieser Kurs ist unter [CC BY NC SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/) lizensiert.
