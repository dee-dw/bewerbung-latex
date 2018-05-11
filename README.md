# bewerbung-latex
Eine deutschsprachige Bewerbungvorlage mit LaTeX.

Die Vorlage unterliegt 
der Creative-Commons-Lizenz "Namensnennung-Weitergabe unter gleichen Bedingungen 4.0 International"
[http://creativecommons.org/licenses/by-sa/4.0/deed.de] und 
darf damit geändert und verteilt werden, solange man den Urheber nennt und die 
Lizenz beibehält. Das aus der Vorlage erstellte PDF unterliegt natürlich 
keinerlei Lizenzbeschränkungen.

Eine detaillierte Anleitung findet man in meinem Blog unter [http://www.deesaster.org/blog/index.php?/archives/2804].

## Motivation

Meine Motivation für die Erstellung der Bewerbungsvorlage war ursprünglich nur, 
dass Anschreiben, Lebenslauf und alle weiteren Seiten zusammengehörig aussehen 
sollten. Sehr viele der vorhandenen Lebenslauf-Pakete auf CTAN lieferten oft nur 
den Lebenslauf-Teil. Für das Anschreiben in der gleichen Schriftart und -größe 
sowie Kopf- und Fußzeilen musste weitere Arbeit investiert werden. Zusätzlich 
enthält meine Vorlage noch eine eigene „Meine Seite“ und einen 
„Motivationsseite”. Ob diese nach heutigem Bewerbungsstandard noch notwendig 
oder gewünscht sind, soll hier nicht diskutiert werden, da man zu dieser Frage 
von jedem Personalleiter eine andere Antwort zu hören bekommt.

Im Laufe der Jahre kam noch eine zweite Motivation dazu: Weil andere Benutzer 
die Vorlage rege nutzten, sollte sie so einfach wie möglich gestaltet sein. 
Insbesondere wollte ich auch Leute ansprechen, die nicht so viel 
TeX-Erfahrung haben. Aus diesem Grund besteht die Vorlage nur aus einer 
einzigen Datei, die der Schreiber editieren muss. Über entsprechende Kommentare 
wird im Dokument genau erklärt, wo ein Bewerber Daten anpassen muss. Da dass 
Zielpublikum dabei immer deutschsprachige Anwender waren, sind alle Makros und 
Befehle ebenfalls deutschsprachig verfasst.

## Aufbau der Dateien

Das Archiv der Bewerbungsvorlage enthält vier Dateien:

* **bewerbung.tex** – Die eigentliche Bewerbungsvorlage. Nur hierin werden Daten geändert.
* **bewerbung-latex.sty** – Die Style-Datei mit den benötigten Befehlen und Paketen. Diese Datei nicht anfassen!
* **foto-bewerber.png** – Das (optionales) Bewerberfoto.
* **signatur-bewerber.png** – Die (optionale) eingescannte Unterschrift.

Wie geschrieben muss ein Bewerber nur die Datei **bewerbung.tex**
anpassen.

## Aufbau der Bewerbung

Die Bewerbung gliedert sich in fünf Teile:

* Anschreiben
* Seite mit persönlichen Daten
* Lebenslauf
* Motivationsseite
* Anlagenverzeichnis

Die Datei **bewerbung.tex** ist entsprechend mit Kommentaren zum Ausfüllen
versehen.
