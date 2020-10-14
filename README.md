# Java

## Library writer

Entwickle ein kleines Programm, zum Verwalten deiner Lieblingsbücher. 

Dein Programm sollte mindestens die Klassen: 
* Book - Repräsentation eines Buches
* Author - Repräsentation eines Autors
* Genre - Enum zur Repräsentation von verschiedenen Genres
* LibraryWriter - Eine Klasse die eine Liste von Büchern in einem bestimmten Format in eine Datei schreibt. 

Schreib Unit Tests für den Writer, für mindestens diese Fälle:
* eine leere Liste von Büchern persistieren
* mindestens ein Buch mit mehreren Genres persistieren
* mindestens ein Buch mit einem Autor persistieren

Gib mindestens eine exemplarische Datei ab, die dein Programm geschrieben hat. 

Die geschrieben Datei könnte das folgende Format haben und muss mindestens diese Informationen beinhalten: 

```
1
Brandon Sanderson (US, 1975)
The Alloy of Law
Science-Fiction | Fantasy
9780765330420
Three hundred years after the events of the Mistborn trilogy, Scadrial is now on the verge of modernity, with railroads to supplement the canals, electric lighting in the streets and the homes of the wealthy, and the first steel-framed skyscrapers racing for the clouds.
4.2 stars
```

* Zeile 1 beschreibt wieviele Einträge in der Datei sind
Jeder Eintrag besteht aus folgenden Zeilen:
* eine Zeile beschreibt den Autor (Name, Ort und Geburtsjahr)
* eine Zeile für den Titel
* eine Zeile für die verschiedenen Genres zu denen dieses Buch gehört, mit einem spezifischen Trennzeichen getrennt (im Beispiel Pipe)
* eine Zeile für die ISBN13 
* eine Zeile für eine Kurzbeschreibung (am einfachsten ist es wenn du keine newlines in diesem Text verwendest)
* eine Zeile für die durchschnittliche Bewertung 

Eine gute Quelle für diese Infos zu bestimmten Büchern ist [goodreads](https://www.goodreads.com/)
