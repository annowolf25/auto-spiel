# Freie Fahrt 3D

Ein 3D-Open-World-Autofahrspiel in **einer einzigen HTML-Datei** (`index.html`), optimiert für den Handy-Browser im Querformat.
Three.js wird über cdnjs geladen. Alle Modelle, Texturen, Geräusche und die ganze Welt entstehen per Code, es gibt keine weiteren Dateien.

## Spielen

`index.html` im Browser öffnen, zum Beispiel per GitHub Pages oder lokal per Doppelklick. Für Three.js wird eine Internetverbindung gebraucht.
Auf dem Handy am besten den Vollbild-Button (⛶) antippen und das Gerät quer halten.

### Steuerung

| Aktion | Touch | Tastatur |
| --- | --- | --- |
| Lenken | Joystick links (oder Pfeiltasten, umschaltbar im Menü) | A/D oder ←/→ |
| Gas | grüner Button rechts | W oder ↑ |
| Bremse / Rückwärts | roter Button | S oder ↓ |
| Handbremse (Driften) | gelber Button | Leertaste |
| Stunts in der Luft | Handbremse halten + Gas/Bremse (Salto) bzw. Lenken (Fassrolle); oder Joystick hoch/runter | Leertaste + W/S bzw. A/D |
| Kamera (Verfolger / weit / Cockpit) | 🎥 | C |
| Auto aufrichten | ⟲ | R |
| Garage (Autowahl) | 🚗 | G |
| Tag/Nacht | 🌙 / ☀️ | N |
| Ton an/aus | 🔊 | M |
| Vollbild | ⛶ | F |
| Minikarte zoomen | auf die Karte tippen | – |

## Inhalt

- **5 Autos** mit eigenen Werten für Tempo, Beschleunigung, Lenkung, Gewicht und Federung: Sportwagen *Blitz GT*, Monstertruck *Bigfoot*, Kleinwagen *Floh*, Rennwagen *Rakete* und Pickup *Ochse*.
- **Welt von 1600 × 1600 m** ohne Ladezeiten:
  - **Stadt:** Straßenraster mit Kreuzungen, Markierungen, Zebrastreifen, Gehwegen und Hochhäusern mit nachts beleuchteten Fenstern. Dazu Laternen (umfahrbar), Ampeln mit Schaltung, geparkte Autos, Parks mit Brunnen und ein Sprungplatz.
  - **Natur:** Hügel, Wälder, Felsen, ein Fluss mit Stahlbogen-Brücke, ein See, Feldwege und Wiesen.
  - **Landstraße** als Rundkurs von der Stadt durch die Natur.
  - **17 Rampen** in Stadt und Natur, zum Beispiel ein Flusssprung, ein Tafelberg und Schanzen.
  - **Stuntpark** mit Looping, Halfpipe, Mega-Rampe, Gap-Jump, Table, Wellenbahn und Quarterpipes.
- **Physik:** Starrkörper mit vier Raycast-Federbeinen, Reibungsellipse und unterschiedlichem Grip auf Asphalt, Erde, Gras und Sand. Sprünge, Landungen, Überschläge und Kollisionen mit Impuls und Drall gehören dazu.
- **HUD:** Tacho mit Drehzahl und Gang, drehende Minikarte, Sprungweite, Flugzeit, Höhe und Tricks. Rekorde werden im Browser gespeichert.
- **Tag/Nacht-Wechsel** mit Scheinwerfer-Spotlicht, Laternenlicht, Sternen und Mond.
- **Sound** über die Web Audio API: Motor (Tonhöhe nach Drehzahl), Reifenquietschen, Wind, Aufprall und Platschen.
- **Grafikstufen** Niedrig, Mittel und Hoch (Auflösung, Schatten, Sichtweite).
