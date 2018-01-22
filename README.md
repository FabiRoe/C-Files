# CPlusPlus-Files

1. Vorbereitung I



Entwerfen Sie einen konkreten Anwendungsfall und erstellen Sie zwei unterschiedlich strukturierte Datenquellen.

Mindestens eine Quelle soll im Format XML (mit DTD) angelegt werden.


Anwendungsfall:

Wir haben und für eine XML und TXT als Datenquelle entschieden.

Wir haben eine Film-Mediathek. Über die Datenbank lässt sich herauslesen, ob der jeweilige Film ausgeliehen ist und wo dieser sich befindet.



XML: 
film id:
preis:
type: DVD oder blue-ray
genre:
regisseur:
jahr:
schauspieler:
Bewertung: Daten von IMDb Bewertungen


TXT: 
id   status(0:ausgeliehen, 1:vorhanden)   ort



(Legen Sie die Datenquellen mit Blick auf Stufe IV an. Sie benötigen Daten, welche Sie im Rahmen einfacher Berechnungen verwenden können. (s. 8. & 9.))
--> Möglichkeiten: 
Daten veränderbar.

Option „Suchen“: Ermöglichen Sie eine Suche nach einer Kategorie innerhalb Ihrer Datenstruktur. (Property einer Class).
Beispiel:
Category: type: blue-ray, dvd
Search for: title, genre, bewertung, schauspieler, preis...


