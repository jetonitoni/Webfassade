---
name: Webfassade
description: Ruhige, dunkle Seite für Webfassade (Jeton Bardhaj). Kino-Schwarz, monochrom, ein einziger Akzent in Eisblau. Aufmerksamkeit entsteht durch echte Bilder, grosse gesperrte Schrift und Bewegung, nicht durch grelle Farben.
inspiration: Bugatti (Monochrom, breite Versalien, Bild als einzige Spannung) aus der DESIGN.md-Bibliothek, angepasst; Tesla für bildschirmfüllende Bilder.

colors:
  grund: "#0A0A0B"      # Seitenhintergrund, nie reines Schwarz
  flaeche: "#111113"    # Karten, Tafeln
  karte: "#161618"      # erhöhte Flächen, Eingabefelder
  linie: "#26262A"      # Haarlinien
  linie-2: "#38383D"    # kräftige Haarlinien, Rahmen
  weiss: "#F1F0ED"      # Überschriften, Hauptknopf
  text: "#C8C7C3"       # Fliesstext
  grau: "#9A999E"       # Nebentext, Etiketten
  grau-2: "#76757A"     # nur gross oder dekorativ (unter 4.5:1 bei kleinem Text)
  eis: "#C3D9F3"        # der einzige Akzent: Hervorhebung, Status offen, Fokus, Links

typography:
  schrift: "Mona Sans, variabel (Breite 75-125 %, Stärke 200-900), liegt in schriften/"
  anzeige: "Stärke 500, Breite 125 %, Versalien, Sperrung 0.02em"
  fliesstext: "Stärke 400, Breite 100 %, 17-18 px, Zeilenhöhe 1.65"
  etikett: "11 px, Stärke 600, Breite 125 %, Versalien, Sperrung 0.22em, höchstens 3 pro Seite"
  knopf: "13 px, Stärke 600, Breite 118 %, Versalien, Sperrung 0.1em"

shapes:
  knoepfe: "Pille (999px), Pfeil im eigenen Kreis"
  flaechen: "eckig (0px): Karten, Bilder, Eingabefelder, Etiketten"
  geraete: "Handy- und Browserrahmen behalten ihre Gerätrundung"

motion:
  weich: "cubic-bezier(.32,.72,0,1)"
  schnell: "cubic-bezier(.16,1,.3,1)"
  regeln: "Lenis für weiches Scrollen; alles Bewegte nur mit transform und opacity; bei «Bewegung reduzieren» steht alles still"
---

## Regeln

- Ein Akzent (Eisblau), keine zweite Farbe. Kein Rot, kein Violett, kein Leuchten.
- Einheitliche Beschriftung pro Ziel: «Entwurf anfragen» überall.
- Keine Gedankenstriche im sichtbaren Text, Mittelpunkt höchstens einmal pro Zeile.
- Symbole nur aus Phosphor Icons (light), nicht selbst zeichnen.
- Bilder: echte Arbeiten (Muster-Websites) und generierte Stimmungsbilder, nichts von fremden Servern laden.
- Jede Bewegung braucht einen Grund: Reihenfolge erzählen, Rückmeldung geben oder Aufmerksamkeit lenken.
