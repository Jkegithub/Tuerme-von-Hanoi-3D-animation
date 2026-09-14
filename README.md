# Türme von Hanoi 3D – Hanoi Edition

Ein interaktives 3D-Puzzlespiel im Browser. Die klassische Aufgabe „Türme von Hanoi“ wird mit einer animierten Stadtkulisse, Tag-Nacht-Zyklus, Monsunregen und räumlicher Klangatmosphäre verbunden.

## Spielziel

Alle Scheiben müssen vom linken auf den rechten Turm bewegt werden.

- Es darf immer nur die oberste Scheibe bewegt werden.
- Eine größere Scheibe darf nie auf einer kleineren liegen.
- Je nach Spielvariante gelten zusätzliche Zugregeln.

## Funktionen

- 3 bis 8 Scheiben
- frei dreh- und zoombare 3D-Szene
- animierter Tag-Nacht-Zyklus
- Regen, Gewitter, Vögel, Verkehr und weitere Umgebungsdetails
- drei Spielregeln:
  - Standard
  - nur Nachbartürme
  - nur im Uhrzeigersinn
- optimaler Hinweismodus mit visueller Turm-Markierung
- automatische Lösung mit Pause, Einzelschritt und drei Geschwindigkeiten
- dynamisch berechnete Mindestzugzahl für jede Variante
- lokale Bestzeiten und beste Zugzahlen
- Bestenliste mit Rücksetzfunktion
- separater Audio-Mixer für Stadt, Wetter, Vögel und Spieleffekte
- Speicherung von Spielregel, Scheibenzahl, Demo-Tempo und Audioeinstellungen
- responsive Bedienoberfläche für Desktop und Mobilgeräte

## Bedienung

### Maus oder Touch

1. Quellturm auswählen.
2. Zielturm auswählen.
3. Die oberste Scheibe wird bewegt, sofern der Zug erlaubt ist.

Die Kamera wird durch Ziehen gedreht und mit dem Mausrad beziehungsweise der Touch-Geste gezoomt.

### Tastatur

| Taste | Funktion |
|---|---|
| `1`, `2`, `3` | linken, mittleren oder rechten Turm auswählen |
| `H` | optimalen Hinweis anzeigen |
| `R` | Spiel neu starten |
| `Esc` | Auswahl oder Dialog schließen |
| `Leertaste` | Auto-Lösung pausieren oder fortsetzen |

## Start

Das Spiel benötigt keine Installation. `index.html` in einem aktuellen Browser öffnen und **Spiel starten** anklicken.

Für die Entwicklung empfiehlt sich ein lokaler Webserver, beispielsweise die Live-Preview- oder Live-Server-Funktion von Visual Studio Code.

Eine Internetverbindung wird für die extern eingebundenen JavaScript- und CSS-Bibliotheken benötigt. Der Verkehrssound wird bevorzugt aus der lokalen MP3-Datei geladen.

## Projektdateien

```text
HANOI/
├── index.html
├── traffic-heavy-busy-street-india.mp3
└── README.md
```

## Verwendete Bibliotheken

- Three.js für die 3D-Darstellung
- GSAP für Animationen
- Tone.js für Audio und Klangeffekte
- Tailwind CSS für die Bedienoberfläche

Die Bibliotheken werden derzeit über externe CDNs eingebunden.

## Speicherung

Bestwerte und Einstellungen werden ausschließlich im lokalen Browser-Speicher abgelegt. Sie sind an das jeweilige Browserprofil und die verwendete Seitenadresse gebunden.

## Lizenz und Audioquelle

Im Repository ist derzeit keine Projektlizenz dokumentiert. Vor einer Weitergabe oder Veröffentlichung sollten die Lizenz des Quellcodes sowie Herkunft und Nutzungsrechte der Audiodatei eindeutig ergänzt werden.
