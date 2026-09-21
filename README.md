# Einheitsführer-App v19

Korrektur des Führungskreislaufs: Beim Start eines Einsatzes wird der erste Führungskreislauf sofort mit Erkundung initialisiert. Auch bei älteren/inkonsistenten gespeicherten Daten wird eine fehlende Runde automatisch angelegt. Eine Lageänderung startet weiterhin eine neue Runde bei Erkundung.


## v19
- Einsatzende: harte Sperre bei offenen Aufträgen oder laufender Atemschutzüberwachung
- Nach Abschluss wird der aktive Einsatz auf null gesetzt
- Abgeschlossener Einsatz wird vollständig ins Einsatzarchiv verschoben
- Einsatzarchiv mit Detailansicht für abgeschlossene Einsätze
- Standardbesetzung bleibt vom Einsatzabschluss getrennt
