
Das Hauptfile ist Liederbuch.tex

Es basiert auf LaTeX2e und den Standardpackages.
Die Texte enthalten teilweise Umlaute in Latin1 (iso8859-1) Kodierung,
da mir die Quellen schon mit Umlauten vorlagen und ich zu faul war,
sie umzuwandeln. Normalerweise d�rfte dies keine Probleme machen.

mit \Xon  bzw \Xoff kann man die Ausgabe von Akkorden an- und
ausschalten, also: Liederbuch.txt bearbeiten, dann neu �bersetzen.

Um sich ein h�bsches A5-Booklet zu machen, funktioniert ungef�hr
folgendes:

dvips -f < Liederbuch.dvi | psbook | psnup -2 > Liederbuch.a5.ps

Danach mu� man entweder zweiseitig drucken oder abwechselnd zun�chst
die geraden bzw. ungeraden Seiten.

Ich wei�, da� akkorde.sty noch weit davon entfernt ist, optimal zu
sein, aber bisher geht's.

Stony
    (42)