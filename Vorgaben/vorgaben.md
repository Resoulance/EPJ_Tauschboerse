# 1.3 Vorgaben für das Engineering-Projekt

Randbemerkung: Folgende Angaben sind aus dem Dokument hsr-epj-anleitung-v1.2.pdf

Die folgenden Vorgaben sind für alle Teams gegeben und müssen eingehalten werden:

* Dauer: ganzes Semester, d.h. 14 Wochen, bzw. im Frühjahrssemester 15 Wochen wegen
Feiertagen/Ferien.
* Teamgrösse: 3 bis 5, alle programmieren mit
* Zeitrahmen: 4 ECTS = 120 Stunden pro Teammitglied, d.h. 8.6h pro Person und Woche
(oder 8h x 15 Wochen)
* Mindestens 4 Lektionen gemeinsame Zeit (ganzes Team!) pro Woche, sonst funktionieren
die Zusammenarbeit und die Reviews mit dem Betreuer nicht.
* Selbstgewählte Aufgabe, welche vom Betreuer genehmigt werden muss, kein externer Kunde.
* Prozess: iterativer, inkrementeller Prozess (Phasen des RUP, Iterationen in Construction-
Phase agil nach Scrum)
* Einsatz der gelernten Engineering-Techniken (OOA, Testen, etc. siehe unten)
* Environment: Code-Repository (git, SVN) plus automatischer Build auf CI Server; Redmine
(oder JIRA, TFS) für Arbeitspakete und Zeitaufschreibung; die HSR stellt einen git-Server
plus pro Team einen virtuellen Server mit vorinstalliertem Redmine und Jenkins zur Verfügung
* Als Programmiersprache sollen Java, C#, eventuell C++, TypeScript oder Python eingesetzt
werden
* Jedes Team kriegt einen fest zugewiesenen Betreuer
* Regelmässige Reviews mit Betreuer (mindestens die fünf vorgegebenen Reviews), bei dem
das ganze Team anwesend ist; es gibt eine Teilnote pro Review
* Als Abschluss in der letzten Semesterwoche eine Präsentation vor Publikum mit Folien und
Demo, mit dem ganzen Team

# 3.1 Themenwahl

In der Regel wählt das Team das Thema, welches sie in Software umsetzen werden, selbst. Die
richtige Wahl der Projektidee ist enorm wichtig. Zum einen soll das Thema die Studierenden
ansprechen, damit es Spass macht (Motivation). Zum anderen darf das Projekt weder zu klein noch
zu gross sein. Aus der Lernpsychologie ist bekannt, dass der Schwierigkeitsgrad einer Aufgabe
sehr sorgfältig gewählt werden muss, damit eine hohe Motivation entstehen kann. Wählt man die
Aufgabe zu leicht, macht sie keinen Spass, weil es so einfach ist. Wählt man die Aufgabe zu schwer,
ist der Frust vorprogrammiert, die Teams verrennen sich, die Arbeit wird nicht fertig, kurzum, die
Motivation ist weg.

Es empfiehlt sich, die folgenden Punkte bei der Wahl der Aufgabe zu berücksichtigen:

* Umfang klein genug, aber ausbaufähig, d.h. kleiner wichtiger Kern mit mehreren Erweiterungsmöglichkeiten
* Gut mit Use Cases definierbar (Ausnahme: Games)
* Mittel-komplexes Domainmodell (4-12 Klassen)
* Mobile App + Server ist ideal für Architektur-Herausforderungen, ebenso Mehrspieler-Games
* Ohne externen Kunden, weil das erheblichen Mehraufwand bedeutet
* Keine neue, schwierige Technik (z.B. Machine Learning) die viel Einarbeitung erfordert
* objektorientiert – Problemdomain aus einigen (5-10) Klassen
* interessant genug (nicht nur CRUD)

Hinweis: Achtung, das Team soll sich nicht auf potentiell zeitfressende Experimente einlassen. Die
Einarbeitung in unbekannte Gebiete (z.B. Spieltheorie, KI) und Technologien (z.B. Angular oder
React Native) kann viel Zeit kosten und wird nicht entsprechend honoriert, da es kein vorrangiges
Ziel des Engineering-Projektes ist, neuste Technologien oder SE-ferne Themen zu lernen.

# 3.3 Projektantrag

Template auf Skripteserver, Inhalt (eine A4-Seite):
* Kurzname des Projektes
* Liste der Team-Mitglieder mit eMail-Adressen
* Die für das ganze Team möglichen Zeiten für Reviews und Präsentationen (alle anwesend!)
* Zielsetzung, Motivation
* Aufgabenstellung, kurze Beschreibung (1/2 Seite) der zu entwickelnden Software
* Verwendete Programmiersprache(n), Bibliotheken, Werkzeuge (soweit schon bekannt)

Es ist vorteilhaft, wenn der Projektantrag (u.a. auch in den SE2-Übungsstunden) mit einem Betreuer
vorbesprochen wird. Die Abgabe muss an d1keller@hsr.ch bis Freitagabend, 1. Semesterwoche
erfolgen.
Zum Anfang der 2. Semesterwoche erhalten die Teams die Genehmigung durch ein eMail; jetzt
kann ein VServer für das Team beantragt werden. Die Zuweisung des Betreuers erfolgt durch ein
eMail spätestens Mitte der 2. Semesterwoche. Ab dann können über die Einschreibelisten die
Termine mit dem Betreuer vereinbart werden.