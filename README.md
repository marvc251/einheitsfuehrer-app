# Einheitsführer-App v14 – Überarbeitung

## Schwerpunkt dieser Version
- Die permanente obere Einsatzübersicht bleibt im Header.
- Die Einsatz-Schnellübersicht erscheint ausschließlich auf dem Homebild.
- Einsatzstichwort ist ein Dropdown, gefiltert nach Einsatzart.
- Meldebild ist ein Dropdown, gefiltert nach Einsatzstichwort.
- Die Auswahl wird in die permanente Einsatzübersicht übernommen.
- Einstellungen enthalten die Standardbesetzung und optionale Standardnamen.
- Beim Einsatzstart werden Standardbesetzung und Standardnamen als aktuelle Einsatzbesetzung übernommen.
- Lagekarten-Dokumentationsstand bleibt versioniert.

## Datenbasis
Die Einsatzstichwort-/Meldebildauswahl orientiert sich an der offiziellen hessischen Fassung des gemeinsamen Runderlasses zu Einsatzstichworten für Brand-, Hilfeleistungs- und Rettungsdiensteinsätze (gültig 01.01.2023 bis 31.12.2029).
Quelle: HLFS/HMdIS/HMSI.

## Testfokus
1. Einsatzart ändern.
2. Einsatzstichwort auswählen.
3. Prüfen, dass nur passende Meldebilder erscheinen.
4. Einsatz starten.
5. Prüfen, dass oben Stichwort, Meldebild, Ort, Beginn und Dauer erscheinen.
6. Auf andere Bereiche wechseln: nur die Einsatzübersicht bleibt oben; die Schnellübersicht ist dort nicht sichtbar.
7. Home öffnen: Schnellübersicht erscheint wieder.
8. Einstellungen → Standardbesetzung prüfen und speichern.
9. Neuen Einsatz starten und prüfen, ob Standardbesetzung übernommen wird.
