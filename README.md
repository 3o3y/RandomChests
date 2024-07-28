RandomChests
Überblick

Mit diesem Plugin kannst du im Umkreis von xx Blöcken eine zufällige Anzahl von Kisten mit zufälligem Inhalt erstellen lassen. Perfekt für Abenteuer- und RPG-Server, um spannende und überraschende Elemente hinzuzufügen!
Features

-    Zufällige Kistenplatzierung: Platziere zufällig Kisten innerhalb eines festgelegten Bereichs.
-    Vielfältiger Inhalt: Jede Kiste wird mit zufälligen Items gefüllt, die in ihrer Seltenheit variieren.
-    Einfache Konfiguration: Stelle den Radius und die Anzahl der Kisten einfach ein.
-    Mehrere Befehle: Bietet mehrere Befehle zur Verwaltung der Kisten.

Installation

Lade die neueste Version des Plugins von der Release-Seite herunter.
Ziehe die .jar-Datei in den plugins-Ordner deines Minecraft-Servers.
Starte den Server neu.

Konfiguration

Nach der Installation findest du eine Konfigurationsdatei im Ordner plugins/RandomChests/config.yml. Hier kannst du die Wahrscheinlichkeiten und die Anzahl der Items einstellen.

Beispiel-Konfiguration:

chances:
  chanceLow: 1.0  # Wahrscheinlichkeit für das Auftreten von Items wie Früchte oder Holzbretter.
  chanceMiddle: 0.8  # Wahrscheinlichkeit für das Auftreten von Leder und Holz Ausrüstung.
  chanceHigh: 0.7  # Wahrscheinlichkeit für das Auftreten von Eisenketten und Stein Ausrüstung.
  chanceHeroic: 0.6  # Wahrscheinlichkeit für das Auftreten von Eisen Ausrüstung.
  chanceLegendary: 0.5  # Wahrscheinlichkeit für das Auftreten von Gold Ausrüstung.
  chanceUnique: 0.4  # Wahrscheinlichkeit für das Auftreten von Diamant Ausrüstung.
  chanceGOD: 0.25  # Wahrscheinlichkeit für das Auftreten von Netherite Ausrüstung.
  chanceBest: 0.1  # Wahrscheinlichkeit für das Auftreten von Dracheneiern usw.
  chanceSwords: 1.0  # Wahrscheinlichkeit für das Auftreten von Legendären Schwertern.

itemCounts:
  numLowMin: 4  # Mindestanzahl der Items mit niedriger Wahrscheinlichkeit.
  numLowMax: 9  # Höchstanzahl der Items mit niedriger Wahrscheinlichkeit.
  numMiddleMin: 2  # Mindestanzahl der Items mit mittlerer Wahrscheinlichkeit.
  numMiddleMax: 5  # Höchstanzahl der Items mit mittlerer Wahrscheinlichkeit.
  numHighMin: 1  # Mindestanzahl der Items mit hoher Wahrscheinlichkeit.
  numHighMax: 4  # Höchstanzahl der Items mit hoher Wahrscheinlichkeit.
  numHeroicMin: 1  # Mindestanzahl der heldenhaften Items.
  numHeroicMax: 3  # Höchstanzahl der heldenhaften Items.
  numLegendaryMin: 1  # Mindestanzahl der legendären Items.
  numLegendaryMax: 2  # Höchstanzahl der legendären Items.
  numHyperMin: 1  # Mindestanzahl der einzigartigen Items.
  numHyperMax: 2  # Höchstanzahl der einzigartigen Items.
  numGODMin: 0  # Mindestanzahl der gottgleichen Items.
  numGODMax: 1  # Höchstanzahl der gottgleichen Items.
  numBestMin: 0  # Mindestanzahl der besten Items.
  numBestMax: 1  # Höchstanzahl der besten Items.
  numSwordsMin: 1  # Mindestanzahl der Schwerter.
  numSwordsMax: 2  # Höchstanzahl der Schwerter.

Befehle

Das Plugin bietet mehrere Befehle zur Verwaltung der zufälligen Kisten:

-    /rcrandom x x
    Beschreibung: Spawnt eine zufällige Anzahl von Kisten im Umkreis von x Blöcken.
    Beispiel: /rcrandom 5 1 spawnt 1 Truhe im Umkreis von 5 Blöcken.
    Berechtigung: randomchest.random
    Fehlermeldung: Du hast leider keine Berechtigung dafür.
    Cooldown: 10 Sekunden

-    /rcsetchest <X> <Y> <Z>
    Beschreibung: Setzt eine Truhe an einem bestimmten Ort.
    Beispiel: /rcsetchest 100 64 -200 setzt eine Truhe bei den Koordinaten (100, 64, -200).
    Berechtigung: randomchest.xyz
    Fehlermeldung: Du hast leider keine Berechtigung dafür.
    Cooldown: 10 Sekunden

-    /rcdeleteall
    Beschreibung: Löscht alle zufällig erstellten Truhen.
    Berechtigung: randomchest.del
    Fehlermeldung: Du hast leider keine Berechtigung dafür.

## Entwicklungsfortschritt
- [x] Zufällige Kistenplatzierung
- [x] Konfigurierbarer Radius und Kistenanzahl
- [x] Unterschiedliche Kisteninhalte basierend auf Seltenheit
- [ ] Weitere Anpassungen der Kisteninhalte
- [ ] Unterstützung für verschiedene Minecraft-Versionen

Mitwirken

Beiträge sind willkommen! Du kannst Fehler melden, Feature-Vorschläge machen oder Pull-Requests einreichen. Besuche die Issues-Seite für mehr Informationen.
