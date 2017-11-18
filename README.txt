2017-07-17

In diesem Ordner sind alle tex-Dateien der IT-Empfehlungen enthalten, die f�r die Erzeugung des PDFs ben�tigt werden.

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
    
Da ich (Martina) mit TeXnicCenter arbeite, gibt es au�erdem die Projektdatei IT-Empfehlungen.tcp, die alle oben genannten Dateien zu einem Projekt zusammenfasst.
	
Au�erdem werden in diese Seiten weitere Seiten eingebunden, die sich in den Unterordnern befinden.
Aktuelle Unterordner:
    dateiformate
	methoden
	projektphasen
    
Alle verwendeten Bilder befinden sich in dem Ordner:
	bilder
Damit klar ist, in welchem Kapitel die Bilder verwendet werden, steht als erstes ein K�rzel (ein paar Ausnahmen gibt es): 3D_Bump ist also ein Bild f�r das Kapitel �ber 3D und Virtual Reality. Hier folgt eine Auflistung der K�rzel und deren Aufl�sung:
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
    
Zus�tzlich befinden sich die Logos f�r das Deckblatt in dem Ordner:
    deckblattLogos

Die Bilder und Logos werden zus�tzlich in dem Bildordner von IANUS abgelegt

F�r die Erstellung einer PDF/A-1b-Datei wird die Datei IT-Empfehlungen.xmpdata ben�tigt, in der Metadaten zu den IT-Empfehlungen gespeichert sind.
    
Alle weiteren Dateien in diesem Ordner (diese ausgenommen) werden bei der Erzeugung des PDFs erstellt und k�nnten daher auch problemlos gel�scht werden.

In dem Ordner "Musterkapitel-Abschnitte" befinden sich die Dateien f�r das Musterkapitel und Ausz�ge einzelner Abschnitte aus vorhergehenden Versionen.

In dem Ordner "Abschnitte-web" befinden sich Abschnitte, die f�r das Web aufbereitet wurden und dort zum Download zur Verf�gung stehen. Dazu geh�ren auch vollst�ndige Dokumente, die unterschiedliche Versionen der IT-Empfehlungen darstellen.

In dem Ordner "Kurzfassung" befinden sich die Dateien zur Erstellung der Kurzfassung der IT-Empfehlungen. F�r die Kurzfassung der IT-Empfehlungen wurden die Dateien zu den Dateiformaten in einen �bersichtsteil und einen vertiefenden Teil aufgesplittet (z.B. 3d-uebersicht.tex und 3d.tex). In der vollst�ndigen Fassung werden alle Dateien eingebunden, in der Kurzfassung nur die mit "-uebersicht". Auch die Inhalte in den Projektphasen wurden aufgesplittet, wobei dabei teilweise drei Dateien enstanden sind: dateiverwaltung.tex wurde z.B. zu dateiverwaltung.tex, dateiverwaltung-benennungVersionierung.tex und dateiverwaltung-praxis.tex. Der Grund daf�r ist, dass der Teil mit einem praktischen Beispiel in der Kurzfassung ausgelassen wurde.

Die Datei zur Erstellung der Kurzfassung liegt in dem Ordner 'Kurzfassung' in dem Ordner der IT-Empfehlungen.

Es wurden au�erdem Hilfs-Labels eingef�gt, da die Referenzen auf die Vollfassung verweisen.

