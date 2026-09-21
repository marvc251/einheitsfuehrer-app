# Einheitsführer-App v15

Smartphone-/Tablet-PWA für den Einheitsführer, Feuerwehr Bebra / Hessen.

## In v15 zusammengeführt
- Globale, dauerhaft oben angeheftete Einsatzübersicht mit Einsatzstichwort, Meldebild, Einsatzort, Beginn und laufender Dauer.
- Einsatz-Schnellübersicht ausschließlich auf Home.
- Einsatzstart als erster Schritt mit Einsatzart, hessischem Einsatzstichwort und Meldebild, Einsatzort und Zusatzangaben.
- Alarmierte Kräfte/Parameter als reine Information aus dem hessischen Einsatzstichwort-Erlass; kein Soll-Ist-Vergleich.
- Standardbesetzung hierarchisch: Trupp vorhanden -> Truppführer/Truppmann einzeln anhaken -> Namen optional.
- Aktuelle Einsatzbesetzung wird beim Einsatzstart aus der Standardbesetzung kopiert und ist einsatzbezogen änderbar.
- Kräfteübersicht mit aktuellem Auftrag, Status und letzter Rückmeldung.
- Befehle werden mit dem jeweiligen Trupp verknüpft; neuer Auftrag ändert den alten auf „Geändert“.
- Rückmeldungen erlauben Einheitsführer, Melder, Maschinist sowie Truppführer/Truppmann der aktuellen Besetzung.
- Atemschutzüberwachung mit Truppauswahl und individuellem Luftvorrat je Atemschutzgeräteträger.
- Führungskreislauf als wiederholbare Runde; Lageänderung beendet die Runde und startet automatisch wieder bei Erkundung.
- Lagekarte mit OpenStreetMap-Kartenausschnitt, Zeichnen, Symbolpunkten, Versionierung und Chronik.
- Einsatzabschluss mit Übersicht, Einheitsführer, Unterschrift, Archiv und Bericht.
- Chronik immer mit Datum, Uhrzeit und Dauer seit Einsatzbeginn.
- Fotos aus der Einsatzdokumentation erscheinen im Einsatzbericht.

## Quellen / Orientierung
Die Einsatzstichworte sind an den hessischen gemeinsamen Runderlass zur Festlegung der Einsatzstichworte angelehnt (Inkrafttreten 01.01.2023, Außerkrafttreten 31.12.2029):
https://hlfs.hessen.de/sites/hlfs.hessen.de/files/2022-09/einsatzstichworteerl-16.pdf

Atemschutz ist an der in Hessen eingeführten FwDV 7 und den HLFS-Unterlagen orientiert:
https://hlfs.hessen.de/dienstvorschriften-fuer-den-brand-und-katastrophenschutz
https://hlfs.hessen.de/atemschutz-und-koerperschutz

Die App ist ein Führungs-/Dokumentationshilfsmittel und ersetzt keine örtlichen AAO, Dienstanweisungen oder Führungsentscheidungen.

## Test
`index.html` direkt auf GitHub Pages veröffentlichen. Für die Lagekarte werden Internetzugang, Leaflet und OpenStreetMap/Nominatim benötigt.
