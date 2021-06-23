# Softwaretechnik_Metriken

**Variante 1: Scanning gitHub Repo with Codacy**


* hab mich bei codacy angemeldet und als erstes mal das refactoring project per JSHint gescannt
* Es gab ein Haufen "Duplication" issues, klar waren ja auch ein "vorher" und ein "nachher" code zur gleichen zeit im Scan
* daher mit den "nachher" JavaScript Klassen  dieses Repository gestartet und bei Codacy gescannt
![alt a screenshot](https://github.com/TiloKar/Softwaretechnik_Metriken/blob/master/img/codacy_working.png "Codacy arbeitet" )
* ziemlich fiese noten kassiert:
![alt a screenshot](https://github.com/TiloKar/Softwaretechnik_Metriken/blob/master/img/codacy_meine_noten.png "Codacy arbeitet" )
* dann nachgesehen, wie konstruktiv die Kritik denn ist:
![alt a screenshot](https://github.com/TiloKar/Softwaretechnik_Metriken/blob/84f196c51061acdcc6b9e965acd57be66f288e3c/img/codacy_meine_fehler%20im%20detail.png "Codacy arbeitet" )
* Und gestaunt welche Tricks, da noch so möglich sind:
![alt a screenshot](https://github.com/TiloKar/Softwaretechnik_Metriken/blob/84f196c51061acdcc6b9e965acd57be66f288e3c/img/codacy_fehler_zusammenfassung.png "Codacy arbeitet" )
* Dann braucht es jetzt nur noch ein paar Algorithmen die Anforderungspapiere lesen und den code selbst schreiben...


**Variante 2: Live Linter im Atom-Editor**



Habe in meinem JS Editor ein Linter Package (JSCS, ESLint) installiert, welches Live beim coden scannt und hinsichtlich Rechtschreibung, Grammatik und Stil erzieht.
Für neuen Code ist es echt gold wert. Ein "Nachprüfen" von bereits bestehendem "schludrigen" Code ist sehr mühsam, da dann doch Ladezeiten die Tastenanschläge behindern.

Fazit: hätt ich das mal vorher gewusst...
![alt a screenshot](https://github.com/TiloKar/Softwaretechnik_Metriken/blob/master/img/live%20jscs%20linter%20im%20atom%20editor.png "Linter im Atom" )
