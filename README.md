# Kreuzbandrisse
## Europas Fussball und die Kreuzbandrisse - ein Überblick über die vergangenen acht Saisons

Diese Datenrecherche entsprang der Beobachtung, dass sich in der Saison 2018/19 ungewöhnlich viele Super-League-Spieler das Kreuzband rissen. Ist dies Zufall? Ein Analyse der Kreuzbandrisszahlen auf Transfermarkt.ch, einer umfassenden Fussball-Datenseite, soll Auskunft darüber geben. Umfangreiche Stichproben legen den Schluss nahe, dass die Daten spätestens ab der Saison 2011/12 in europäischen Ligen zuverlässig erfasst sind. In diesem Zeitraum analysieren wir die Verletztendaten.

## Vorgehen
Um an die Daten heranzukommen, werden zunächst alle Spieler, die seit 2011 in den zwei höchsten Ligen der Länder Schweiz, Österreich, Portugal, Spanien, Italien, Deutschland, Frankreich, England und Schottland gespielt haben, extrahiert. Über jeden Spieler ist auf transfermarkt.ch eine Verletzungshistorie erfasst, die wir nach Kreuzbandrissen untersuchen. Rund 1400 Risse gab es unter den gut 36000 erfassten Spielern. Auf der Transfermarkt-Hauptseite der rund 1400 Betroffenen extrahieren wir Infos wie Club, Liga und Alter zum Zeitpunkt des Risses.

## Phyton-Script
Die Analyse wurde mit Phyton-Code vorgenommen. Das Script ist unter der obigen jpynb-Datei einsehbar. Die Liste mit allen Spielern, die seit 2011/12 zumindest zwischenzeitlich in einer der ausgewählten Ligen Fussball gespielt haben und sich ein Kreuzband gerissen haben, sind in der obigen csv-Datei zu finden.

## Ergebnis
Tatsächlich ist eine erhöhte Kreuzbandriss-Rate in der Super League erkennbar. In der höchsten Schweizer Liga haben sich seit der Saison 2011/12 55 Spieler das Kreuzband gerissen, pro Team im Schnitt 5,5. In den Top-Five-Ligen Europas liegt dieser Wert weit tiefer, nämlich zwischen 2,5 (Ligue 1) und 4,2 (La Liga). Was das Resultat relativiert: In der laufenden Saison (2019/20) hat sich noch kein Spieler der Super League das Kreuzband gerissen (Stand 13.12.2019). Beginnt die angestrebte bessere Präventionsarbeit zu greifen? Der Effekt muss jedoch über einen längeren Zeitraum beobachtet werden.
Was bei der Auswertung zudem auffiel: Die Pausenzeiten nach einem Kreuzbandriss divergieren von Liga zu Liga stark. So wird in Italien und Frankreich weit weniger lange gewartet als in der Super League, bis ein Spieler wieder zum Einsatz kommt. Besonders in der Super League hat die Wartezeit in den vergangenen Jahren zugenommen. Weiter: Im August passieren die meisten Risse. Und: Während "nur" jeder 30. Fussballprofi sein Kreuzband reisst, erleidet jeder 10. der Vorbelasteten einen weiteren Riss.

## Auskunftspersonen
Sowohl von Lukas Weisskopf (Sportarzt und Kreuzband-Experte) als auch von Simon Storm (Leiter Athletik und Physiotherapie FC St.Gallen) deutet die tiefere Quoten in grossen Ligen auf bessere medizinische Betreuung in diesen Ligen hin, schlicht aufgrund der finanziellen Möglichkeiten. Die längere Wartezeit in der Super League ist für Storm keine Überraschung: Er nimmt ebenfalls wahr, dass Vereine ihren Spielern länger Zeit geben. Weisskopf ergänzt: "Jeden Monat, den man nach einem halben Jahr Pause noch länger bis zur Rückkehr wartet, verkleinert das Risiko auf einen zweiten Riss um 50 Prozent."

## Probleme der Datenanalyse
Informationen, welche Art der Spielsituation (contact/non-contact) zum Riss führten, fehlen. Zudem sind genauere Informationen zum Kreuzbandriss nicht erfasst (ist Meniskus/Knorpel beschädigt? Zusätzlich ein Aussenband?). Dies relativiert die Aussagen zu Rückkehrzeit in den Ligen zu einem gewissen Grad. Aufgrund der relativ grossen Datenlage erhalten die formulierten Tendenzen aber Gewicht. 
Nicht auszuschliessen ist zudem, dass gewisse Kreuzbandrisse nicht erfasst sind. Stichproben (Suche nach Medienberichten zu Kreuzbandrissen in den verschiedenen Ländern und abgleich mit den Transfermarkt-Daten) haben aber keine nicht erfassten Kreuzbandrisse gezeigt.



