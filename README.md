# LaTeX-Vorlage für Abschlussarbeiten 


##  GERNE WEITERGEBEN, FORKEN UND ÄNDERUNGEN PER PR HINZUFÜGEN :) 


Die Vorlage wurde von ursprünglich Andreas Männle zur Verfügung gestellt. Vielen Dank! 
Als Compiler ist Latexmk zu verwenden. Siehe Datei makefile

Die Vorlage wurde durch verschiedene Personen angepasst, dass sie ebenfalls für UNITS und ENITS verwendet werden kann.

Ich habe die Vorlage zuletzt von Selin aka. "Husky" :)

Viele Fehler der originalen Vorlage wurden durch mich behoben und viele Verbesserungen und Individualisierungen vorgenommen.

Die originale Vorlage kann man auf https://gitlab.com/emi-hsog/vorlage-abschlussarbeit-latex finden.

## preambel.tex
Hier werden alle Packages eingebunden, sowie die komplette Formatierung von dem Dokument vorgenommen. Änderungen sind hier nicht notwendig.

## thesis.tex
Die Datei thesis.tex ist die Hauptdatei des Projekts.
Hier werden die verschiedenen Kapitel eingebunden. Normalerweise sollten keine großen Veränderung in der Datei notwendig sein, abgesehen von dem Einbinden der Kapitel. Hier können auch Verzeichnisse, welche nicht verwendet werden (bsp. Listingsverzeichnis, Abkürzungsverzeichnis, Anhänge etc.) auskommentiert werden.
Alle Dateien die ihr einbinden wollt, müssen als .tex Datei vorhanden sein. Sie sind im Ordner Kapitel zu finden.

## docinfo.tex
In der Datei docinfo.tex werden alle Daten, welche für das Titelblatt verwendet werden eingetragen d.h. Titel, Autor, Jahr, Studiengang, Betreuer etc.
Hier wird ebenfalls die Zusammenfassung/Abstract geschrieben. Durch false/true können die Variablen für die Publikation und den Sperrvermerk gesetzt werden. Je nachdem wo ihr eure Thesis schreibt, kann ein Sperrvermerk gesetzt worden sein oder nicht. Muss zugeben, die Einstimmung für die Publikation kann ich nicht 100% nachvollziehen, aber ich würds einfach auf false setzen.

## titelblatt.tex
Hier sind alle Definitionen von den Fakultäten sowie auch Studiengänge erstellt worden. Da wir alle hier den gleichen Abschluss im gleichen Studiengang machen, habe ich die Fakultät Medien (M), sowie den Studiengang UNITS schon hinzugefügt. Also in dem Teil sollten keine Änderungen mehr notwendig sein, außer die Namen ändern sich.
Das Vorwort, die Eidesstattliche Erklärung, der Sperrvermerk und den Hinweis zu geschlechtsneutraler Pronomen können hier bearbeitet werden. 
