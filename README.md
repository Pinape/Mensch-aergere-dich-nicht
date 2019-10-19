# Mensch ärgere dich nicht 

<h4>Definitionen:</h4>

Status: <br>
• In Startposition <br>
• Auf Spielfeld <br>
• Im Haus <br>
Je nach Status gibt es Einschränkungen / sind nur bestimmte Methoden/Funktionen aufrufbar 

<h4>Userstorys</h4>

ID: 1 <br>
Titel: Farbauswahl der Spielfiguren <br>
Voraussetzungen: <br>
• Der User soll sich zu Beginn des Spiels eine von vier Farben aussuchen können <br>
Akzeptanzkriterien: <br>
• Es sind vier Buttons, in den Farben rot, grün, gelb und blau sichtbar
• Es wird eine Funktion aufgerufen, die dafür sorgt, dass die Spielfiguren des Users in der ausgewählten Farbe erscheinen

ID: 2 <br>
Titel: Ermitteln wer zuerst am Zug ist <br>
Voraussetzungen: <br>
• Der User erfährt, wann er mit dem ersten Zug dran ist <br>
Akzeptanzkriterien: <br>
• Funktion “1. Spieler ermitteln” wird aufgerufen 

ID: 3 <br>
Titel: Würfeln <br>
Voraussetzungen: <br>
• Es kann gewürfelt werden um die Figuren zu bewegen bzw. Um neue Figuren ins Spiel zu bringen <br>
Akzeptanzkriterien: <br>
• Funktion “Würfeln” wird aufgerufen (Gibt zufällig eine Zahl zwischen 1 und 6 aus) <br>
• Gewürfelte Zahl erscheint <br>
Wenn eine 6 gewürfelt wurde: <br>
  • Sind noch Figuren in der Startposition und ist das Startfeld frei? <br> -> wenn beide Bedingungen erfüllt sind, dann wird eine neue Figur aus der Startposition auf dem Startfeld platziert <br> 
  • Es sind keine Figuren mehr auf der Startposition (Startposition wird irrelevant) <br> -> Spieler kann erneut würfeln (Funktion wird erneut aufgerufen) <br>
  • Sind Figuren auf der Startposition und das Startfeld ist nicht frei? <br> -> Wenn beide Bedingungen erfüllt sind, dann muss eine andere Figur auf dem Spielfeld bewegt werden

ID: 4 <br>
Titel: Figurenauswahl <br>
Voraussetzungen: <br>
• Der User muss mindestens 2 Figuren auf dem Spielfeld haben <br>
Akzeptanzkriterien: <br>
• Der User wählt eine Figur auf dem Spielfeld aus, indem er auf sie klickt

ID: 5 <br>
Titel: Schlagen <br>
Voraussetzungen: <br>
• Der User kann die Figuren eines anderen Spielers vom Spielfeld räumen <br>
Akzeptanzkriterien: <br>
• Funktion “Schlagen” wird aufgerufen <br>
-> Eigene Figur wird auf dem Feld des Gegners platziert <br>
-> Spielfigur des Gegners wird in die Startposition zurück befördert <br>
• Button “Schlagen” erscheint sobald die Kriterien erfüllt sind <br>
-> Gewürfelte Zahl entspricht genau der Differenz an Feldern zum Standpunkt der gegnerischen Figur <br>
-> Zu schlagende Figur ist keine eigene 

ID: 6 <br>
Titel: Ins Haus einkehren <br>
Voraussetzungen: <br>
• Der User muss mindestens die Zahl gewürfelt haben, die benötigt wird, um auf das erste Feld des Hauses zu gelangen <br>
Akzeptanzkriterien: <br>
• Spielfigur wird ins Haus gezogen (erlangt Status Haus) <br>
• Spielfigur ist nicht mehr anwählbar


🛁
