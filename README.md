# Lichtverzug – Demo

Ein-Finger-Spiel: Eine Nachtfähre auf dem Wiener Donaukanal – in einer Welt, in der das Licht langsam ist.

**Spielen:** https://hasanbeg99.github.io/lichtverzug-demo/

- **Halten = fahren, Loslassen = stoppen. Fernes Licht ist alt.**
- Was nah ist, siehst du, wie es jetzt ist. Was weit weg ist, siehst du, wie es vor Sekunden war (Verzögerung = Entfernung / Lichtgeschwindigkeit).
- Jedes bewegte Objekt sendet sichtbare Lichtringe aus. Rote Ringe: Brücke/Tor schließt, grüne: öffnet. Erst wenn ein Ring ankommt, siehst du den neuen Zustand.
- Fern = Cyanotypie-Blau, nah = volle Farbe. Kollisionen zählen mit den wahren Positionen; beim Zusammenstoß wird kurz die Gegenwart gezeigt.
- 5 Stationen: Klappbrücke, weite Sicht + Schleuse, Frachter, Nebel (Licht 2,6× langsamer), Laterne (zeigt die Gegenwart im Umkreis). Leuchtrakete: 1× pro Fahrt überall die Gegenwart.
- **Nachtfahrt:** Endlosmodus mit Tagesroute (für alle gleich, per Datum), Fahrplan-Zeit und lokalem Bestwert.

Eine einzige Datei (`index.html`), keine externen Abhängigkeiten, Töne per WebAudio erzeugt.
