# EPJ_Tauschboerse

# [Core]
* Login
* User mit Liste (Tauschobjekte)
  * "required/wished"-Items
  * "possessed"-Items
* 1 - 1 Tausch
* Suche nach "required/wished"-Item 
* Collection - Wahl des System (Erweiterbarkeit)


# [Optional]
* [high]
   * Transaction History - Übersicht
   * Item entfernen (because of damage, nicht mehr vorhanden) - Qualität
   * Check auf inaktiver User => wird weniger gewichtet/priotisiert
   * Statistik(Most Need, Most Have, etc...)
   * https with lets encrypt

* [mid]
   * Kommunikation
      * Nachrichtenbox
   * Rate users (trustworthy, ...)

* [low]
   * User Registration
   * Best Match bei Mehrfachsuche
   * n - n Tausch
   * Multiple language support
   * Werteinschätzung
   * Random swap, when users subscribe
   * Page to simply add all the cards or whatever item which will be exchanged 
   * Simple wrapper, which opens our responsive website in an android app
      * for iOS as well
   * Security
      * Admin Panel
         * Ban users

* [Non Functional Requirements]
   * Accessablity (red green weakness, ...)

* [Limitation]
   * No IE and Edge support

# [ToolChain]
* Front End
   * Typescript
   * React
   * HTML / Handlebars
   * SASS
   * Font Awesome
   * CSS grid or Bootstrap
* Back End
   * Typescript
   * Node JS
      * Express
      * Passport.js
   * Database: PostgreSQL
   * Webpack
   * REST + Swagger [https://swagger.io/]
   
   eventuell Java mit Spring Boot
   
# [Continious Integration]
* ?Travis
* ?Jenkins
* ?TeamCity

# [Unit Testing]
* Jasmine

# [Server] - Server wird von der HSR bereit gestellt
* Für JIRA für Zeitverwaltung 
* ?Node.JS with tomcat (Application Server)

# [Projektverwaltung & Dokumentation]
* LaTex, just if no word document is required
* JIRA [https://de.atlassian.com/software/jira/core] - Zeitverwaltung (anstatt RedMine)

# [Code Verwaltung] - wird privat gestellt sobald Projektantrag akzeptiert wird
* Private Github repository [https://github.com/Resoulance/EPJ_Tauschboerse]

# [Dokumentation] - use cases, screens, UML
* use cases [https://github.com/Resoulance/EPJ_Tauschboerse/blob/master/doc/usecases.md]
* screens [https://github.com/Resoulance/EPJ_Tauschboerse/blob/master/doc/screens.md]
* UML

# [Helpful links]
* https://www.ctl.io/developers/blog/post/build-user-authentication-with-node-js-express-passport-and-mongodb


