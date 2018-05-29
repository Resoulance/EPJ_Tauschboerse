# EPJ_Tauschboerse

# [Core]
* Login
* User mit Liste
** "need"-Item
** "have"-Item
* 1 - 1 Tausch
* Suche nach "need"-Item 

# [Optional]
**[high]
* Transaction History
* Item entfernen (because of damage, nicht mehr vorhanden)
* Check auf inaktiver User => wird weniger gewichtet/priotisiert
* Statistik(Most Need, Most Have, etc...)

**[mid]
* Kommunikation
**Nachrichtenbox

* Rate users (trustworthy, ...)
**[low]
* User Registration
* Best Match bei Mehrfachsuche
* n - n Tausch
* Werteinschätzung
* Random swap, when users subscribe
* Page to simply add all the cards or whatever item which will be exchanged 
* Simple wrapper, which opens our responsive website in an android app
    * for iOS as well
*Security
**Admin Panel
***Ban users

# [mögliche Technologien]
* Front End
** Typescript
** HTML / Handlebars
** SASS
*** Font Awesome
* Back End
** Node JS??? (Angular??? React??)
*** Express
*** Passport.js
** Database: Postgres würd ich vorschlagen / (Mongo DB, NoSQL)
** Grunt

# [Testing] - noch offen
* Karma for JS??? Just for Angular? Without Angular Mocha? => spreedy fragen

# [Server] - Server wird von der HSR bereit gestellt
* Für JIRA für Zeitverwaltung 
* Node.JS with tomcat (Application Server)

# [Dokumentation & Projektverwaltung]
* LaTex, just if no word document is required
* JIRA [https://de.atlassian.com/software/jira/core] - Zeitverwaltung (anstatt RedMine)

# [Code Verwaltung] - wird privat gestellt sobald Projektantrag akzeptiert wird
* Private Github repository [https://github.com/Resoulance/EPJ_Tauschboerse]

# [Screens]
* Login-Screen
* Bildersuche-Screen
* Ergebnis-Screen -> Ergebnisse mit Liste von Usern, die das Bild haben-Screen 
* Bilder-anbieten-Screen
* Transaktions-Screen -> Alle Bilder die getauscht wurden, werden angezeigt.

# [Actors]
* Anbieter
* Sucher

# [Use Cases - Brief]
* Use Case Suchen nach Panini-Bilder
** Auf dem Bildersuche-Screen gibt es ein Input-Feld. In dieses Input-Feld kann der User sein gewünschtes Panini-Bild (Nummer) eingeben und mit Button "Suchen" suchen.

* Use Case Tausch-Request erstellen
** Wenn ein Bild gefunden wurde mit Use Case "Suchen nach Panini-Bilder", werden alle User, die das Bild besitzen, angezeigt. Der Suchende kann einen Bild-Besitzer auswählen und mit dem Button "Tauschen" auf dem Ergebnis-Screen einen Request an den Bildbesitzer absetzen.

* Use Case Tauschbilder anbieten
** Wenn ein User ein Bild tauschen möchte, gibt er die Nummer(n) des Bildes auf dem Bilder-anbieten-Screen in einem Eingabefeld ein. Diese werden vom System erfasst und anderen Mitgliedern bei einem Tasuch-Request angezeigt. 

* Use Case Tauschbilder tauschen
** Nach dem Tausch-Request nimmt der Anbieter den Request an. Der Tausch wird im System vermerkt. Eine Bestätigung wird auf dem Transaktionsscreen beiden Usern angezeigt.

# [Helpful links]
* https://www.ctl.io/developers/blog/post/build-user-authentication-with-node-js-express-passport-and-mongodb


