<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Beobachtung: was gelesen wird und was daraus folgte

[English](README.en.md)

Wie global-law jedes Land beobachtet: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). Diese Seite zeigt dasselbe nur für Basel Stadt: jedes Lesen einer amtlichen Quelle, wann, und was daraus folgte (Vorschriften hinzugefügt, geändert und entfernt). Maschinenlesbar in [data/checks/](../data/checks/) (JSON Lines, Schema `lexifina-check/1`), in `git log` als Commits mit `Kind: check` und Monat für Monat in [checks/](checks/).

**Letzte Prüfung:** 2026-11-26 06:02 UTC, Basel Stadt: Systematische Sammlung (www.gesetzessammlung.bs.ch): 397 Adressen gelesen; 110 hinzugefügt, 0 geändert, 0 entfernt; Änderungen gefunden; 4 nicht veröffentlicht, davon 0 ohne Grund.

## Quellen

| Quelle | Ordner | Wie oft | Letzte erfolgreiche Prüfung | Letztes Ergebnis | Stand |
| --- | --- | --- | --- | --- | --- |
| [Basel Stadt: Systematische Sammlung (www.gesetzessammlung.bs.ch)](https://www.gesetzessammlung.bs.ch/) | `<act>/` | täglich | 2026-11-26 06:02 UTC | Änderungen gefunden | beobachtet |

## Die letzten 30 Tage

| Beginn (UTC) | Quelle | Gelesen | Hinzugefügt | Geändert | Entfernt | Nicht veröffentlicht (ohne Grund) | Ergebnis | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-26 05:49](checks/2026-11.md#ch-lexwork-basel-stadt-20261126t054926z) | lexwork-basel-stadt | 397 | 110 | 0 | 0 | 4 (0) | Änderungen gefunden | [193](https://github.com/lexifina/switzerland-basel-stadt-law/compare/719ea2dbe296...fd06bd9f7b8e) |
| [2026-11-25 06:04](checks/2026-11.md#ch-lexwork-basel-stadt-20261125t060422z) | lexwork-basel-stadt | 488 | 260 | 0 | 0 | 112 (0) | Änderungen gefunden | [260](https://github.com/lexifina/switzerland-basel-stadt-law/compare/067cc4896743...ecbdf8aea6af) |
| [2026-11-24 14:34](checks/2026-11.md#ch-lexwork-basel-stadt-20261124t143453z) | lexwork-basel-stadt | 270 | 260 | 2 | 0 | 263 (0) | die Prüfung ist fehlgeschlagen | — |
| [2026-11-24 11:55](checks/2026-11.md#ch-lexwork-basel-stadt-20261124t115546z) | lexwork-basel-stadt | 611 | 261 | 0 | 0 | 262 (0) | die Prüfung ist fehlgeschlagen | — |

## Selbst prüfen

```
python tools/checktrail.py                      # die letzte Prüfung jeder Quelle
python tools/checktrail.py --day 2026-11-23     # jede Prüfung eines Tages
python tools/checktrail.py --act <id>           # wann eine Vorschrift gesehen und veröffentlicht wurde
git log --grep='^Kind: check' --format='%ci %s'  # die Prüfungen in der Historie
```

Rechtskraft hat nur die amtliche Verkündung; die Texte hier sind Kopien zum Lesen und Suchen.
