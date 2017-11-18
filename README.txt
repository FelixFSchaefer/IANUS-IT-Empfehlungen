2017-11-18

This are the LaTeX source files for the IT-Empfehlungen für den nachhaltigen Umgang mit digitalen Daten in den Altertumswissenschaften by IANUS (https://www.ianus-fdz.de/it-empfehlungen/).

A CC-BY-SA license applies

Description of files and folders (German)

In diesem Ordner sind alle tex-Dateien der IT-Empfehlungen enthalten, die für die Erzeugung des PDFs benötigt werden.

Kern ist die Datei IT-Empfehlungen.tex
Dort werden mit dem include-Befehl (\include{}) weitere tex-Dateien eingebunden.
Aktuell sind dies:
    deckblatt.tex
    metadatenblatt.tex
	einleitung.tex
	projektphasen.tex
	dateiformate.tex
	methoden.tex
	glossar.tex
	anhang.tex
    
Da ich (Martina) mit TeXnicCenter arbeite, gibt es außerdem die Projektdatei IT-Empfehlungen.tcp, die alle oben genannten Dateien zu einem Projekt zusammenfasst.
	
Außerdem werden in diese Seiten weitere Seiten eingebunden, die sich in den Unterordnern befinden.
Aktuelle Unterordner:
    dateiformate
	methoden
	projektphasen
    
Alle verwendeten Bilder befinden sich in dem Ordner:
	bilder
Damit klar ist, in welchem Kapitel die Bilder verwendet werden, steht als erstes ein Kürzel (ein paar Ausnahmen gibt es): 3D_Bump ist also ein Bild für das Kapitel über 3D und Virtual Reality. Hier folgt eine Auflistung der Kürzel und deren Auflösung:
3D - 3D und Virtual Reality
audio - Audio
datenbanken - Datenbanken
PDF - PDF-Dokumente
RG - Rastergrafiken
rti - RTI
tabelle - Tabellen
text - Textdokumente
vektor - Vektorgrafiken
video - Video
web - Webseiten
    
Zusätzlich befinden sich die Logos für das Deckblatt in dem Ordner:
    deckblattLogos

Die Bilder und Logos werden zusätzlich in dem Bildordner von IANUS abgelegt

Für die Erstellung einer PDF/A-1b-Datei wird die Datei IT-Empfehlungen.xmpdata benötigt, in der Metadaten zu den IT-Empfehlungen gespeichert sind.
    
Alle weiteren Dateien in diesem Ordner (diese ausgenommen) werden bei der Erzeugung des PDFs erstellt und könnten daher auch problemlos gelöscht werden.

In dem Ordner "Musterkapitel-Abschnitte" befinden sich die Dateien für das Musterkapitel und Auszüge einzelner Abschnitte aus vorhergehenden Versionen.

In dem Ordner "Abschnitte-web" befinden sich Abschnitte, die für das Web aufbereitet wurden und dort zum Download zur Verfügung stehen. Dazu gehören auch vollständige Dokumente, die unterschiedliche Versionen der IT-Empfehlungen darstellen.

In dem Ordner "Kurzfassung" befinden sich die Dateien zur Erstellung der Kurzfassung der IT-Empfehlungen. Für die Kurzfassung der IT-Empfehlungen wurden die Dateien zu den Dateiformaten in einen Übersichtsteil und einen vertiefenden Teil aufgesplittet (z.B. 3d-uebersicht.tex und 3d.tex). In der vollständigen Fassung werden alle Dateien eingebunden, in der Kurzfassung nur die mit "-uebersicht". Auch die Inhalte in den Projektphasen wurden aufgesplittet, wobei dabei teilweise drei Dateien enstanden sind: dateiverwaltung.tex wurde z.B. zu dateiverwaltung.tex, dateiverwaltung-benennungVersionierung.tex und dateiverwaltung-praxis.tex. Der Grund dafür ist, dass der Teil mit einem praktischen Beispiel in der Kurzfassung ausgelassen wurde.

Die Datei zur Erstellung der Kurzfassung liegt in dem Ordner 'Kurzfassung' in dem Ordner der IT-Empfehlungen.

Es wurden außerdem Hilfs-Labels eingefügt, da die Referenzen auf die Vollfassung verweisen.

