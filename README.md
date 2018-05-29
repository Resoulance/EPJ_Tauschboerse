# EPJ_Tauschboerse

# [Core]
* Login
* In possession / owned item list  (when there are several matches: first match? list? based on what can the user choose? )
* ?? Is it possible to exchange non-duplicates? By user request -> optional? (Bei Panini klebt man die Bilder ein und somit kann man die Bilder nicht mehr weitertauschen)
* 1 - 1 Tausch


# [Optional]
* User Registration
* Transaction History
* Page to simply add all the cards or whatever item which will be exchanged 
* Remove cards (because of damage)
* Rate users (trustworthy, ...)
* Best Match bei Mehrfachsuche
* n - n Tausch
* Kommunikation
   *Nachrichtenbox
* Statistik(Most Need, Most Have, etc...)
* Werteinschätzung 
* Random swap, when users subscribe
* inactive user check => search exclusion
* Simple wrapper, which opens our responsive website in an android app
    * for iOS as well
* Admin Panel
    * Ban users

# [Technology]
* Front End
    * JavaScript oder typescript??
    * HTML / Handlebars
    * SASS
    * Font Awesome
* Back End
    * Node JS??? Angular??? React??
        * Express
        * Passport.js
    * Database: Postgres würd ich vorschlagen / (Mongo DB, NoSQL)
    * Grunt


# [Testing]
* Karma for JS??? Just for Angular? Without Angular Mocha?

# [Server]
* Für RedMine für Zeitverwaltung - Server wird von der HSR bereit gestellt
* Linux (debian or ubuntu)

# [Dokumentation]
* LaTex, just if no word document is required
* RedMine - Zeitverwaltung

# [Code Verwaltung]
* Private Github repository

# []



# [Helpful links]
* https://www.ctl.io/developers/blog/post/build-user-authentication-with-node-js-express-passport-and-mongodb



* [Screens]
* Login-Screen
* Bildersuche-Screen
* Ergebnisse mit Liste von Usern, die das Bild haben-Screen -> Ergebnis-Screen
* 


* Brief - Use Cases
* Use Case Suchen nach Panini-Bilder
* Auf dem Bildersuche-Screen gibt es ein Input-Feld. In dieses Input-Feld kann der User sein gewünschtes Panini-Bild (Nummer) eingeben und mit Button "Suchen" suchen.

Use Case Tausch-Request erstellen
* Wenn ein Bild gefunden wurde mit Use Case "Suchen nach Panini-Bilder", werden alle User, die das Bild besitzen, angezeigt. Der Suchende kann einen Bild-Besitzer auswählen und mit dem Button "Tauschen" auf dem Ergebnis-Screen einen Request an den Bildbesitzer absetzen.


