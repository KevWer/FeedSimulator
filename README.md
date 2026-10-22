# Feed-Simulator

Interaktive Live-Demo zum Referat „Die Entwicklung des Medienkonsums“ (Wahrnehmungs- und Medienpsychologie, Master Medieninformatik).

Die Demo zeigt vereinfacht, wie ein personalisierter Feed aus Interaktionen lernt und dadurch enger wird.

## Bedienung

| Aktion | Maus | Tastatur |
| --- | --- | --- |
| Beitrag liken | „Gefällt mir“ | `→` oder `L` |
| Beitrag überspringen | „Überspringen“ | `←` oder `S` |
| Automatische Demo starten/stoppen | „Demo starten“ | `D` |
| Personalisierung an/aus | Schalter | `P` |
| Neu starten | „Neu starten“ | `R` |

## Modell

- Jedes Thema startet mit dem Gewicht 1,0.
- Like: Gewicht + 2,5. Überspringen: Gewicht × 0,6.
- Der nächste Beitrag wird nach Gewicht ausgelost (mit 5 % Zufall).
- „Vielfalt“ ist die normierte Shannon-Entropie der Themen in den letzten 12 Beiträgen.

Das Modell dient nur der Veranschaulichung und ist angelehnt an Narayanan (2023), *Understanding Social Media Recommendation Algorithms*, Knight First Amendment Institute. Echte Plattformen nutzen deutlich mehr Signale.

## Starten

`index.html` im Browser öffnen. Es wird nichts installiert und keine Daten werden gespeichert oder gesendet. Ohne Internet fehlen nur die Webfonts.

Alle Accounts und Beiträge sind frei erfunden.

© 2026 Kevin Werner
