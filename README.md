# CodeNames_Excel
Inhalt

1.Voraussetzungen

2.Spielvorbereitung

	Teams
	
	Server.xlsm
	
	Geheimdienst.xlsm
	
	Spieler.xlsm
	
3.Spielen

4.Eigene Wörter hinzufügen

---------------------------------------------------------------------------------
1.Voraussetzungen
4 Spieler
Alle Spieler haben Netzwerkzugriff auf die Server-Datei zum Beispiel durch:
-Lokales Netzwerk
-Unternehmensnetzwerk
-VPN
-Hamachi
-…
---------------------------------------------------------------------------------
2.Spielvorbereitung

Teams
2 Gruppen vorher festlegen, inklusive der Geheimdienstchefs. Team Blau fängt grundsätzlich an. Dies sollte vorher besprechen werden, welche Gruppe welches Team ist. Dies kann jede Runde wechseln.

Server.xlsm
Ein Geheimdienstchef speichert die Server.xlsm an einem Pfad, auf den alle Spieler zugreifen können. Anschließend öffnet er die Server.xlsm.
Ggf. „Bearbeitung Aktivieren“
Ggf. „Inhalt aktvieren“
Auf den Button „Neue Wörter aufstellen“ drücken
Auf den Button „Neue Code-Karte erstellen“ drücken. 
Excel Tabelle schließen und speichern

Geheimdienst.xlsm
Anschließend müssen beide Geheimdienstchefs die Lokale Geheimdienst.xlsm öffnen.
Ggf. „Inhalt Aktivieren“ siehe: Server.xlsm
In die Zelle „C12“ den Pfad zur Server.xlsm angeben. 
Beispiel: „\\192.168.1.5\shared\Server.xlsm“
Auf den Button „Starten“ klicken und die Datei Excel Datei geöffnet lassen. Auf der Linken Seite werden die Geheimagenten beider Teams(rot/blau), Zivilisten(gelb) und der Attentäter(grau) dargestellt. Außerdem wird angezeigt, welches Team am Zug ist. Auf der rechten Seite ist das Spielfeld zu sehen, was die Spieler sehen.
Die Geheimdienstchefs sind nun bereit zum Spielen.
 
Spieler.xlsm
Die Spieler öffnen ihre lokale Spieler.xlsm
Ggf. „Inhalt aktivieren“. Siehe: Server.xlsm
Die Spieler tragen ebenfalls in Zelle „C12“ den Pfad zur Server.xlsm ein.
Anschließend auf den Button „Spiel starten“
---------------------------------------------------------------------------------

3.Spielen
Es gelten die gleichen Spielregeln wie beim richtigen Code-Names.
Team Blau fängt an. Der Geheimdienstchef übermittelt den Spielern Ein Wort mit Anzahl der Begriffe, die er meint. 
Spieler Team Blau trifft seine Auswahl über die Buttons „Auswahl“ im jeweiligen Feld. Möchte er seinen Zug beenden, drückt der Spieler den „Zug beenden“ Button.
Die Ansichten werden alle 5 Sekunden aktualisiert. Deswegen kann es sein, dass beim Drücken von Buttons einige Sekunden gewartet werden muss, damit man ein Ergebnis sieht.
---------------------------------------------------------------------------------

4.Eigene Wörter hinzufügen
Server.xlsm öffnen und in die Tabelle „Wortliste“ gehen. In der Tabelle Wörter hinzufügen und ID Fortlaufend schreiben.
