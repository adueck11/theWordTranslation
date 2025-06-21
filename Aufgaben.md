# Allgemeines
- Sprache in theWord aktualisieren (auch bei geäffneten Dialogfenstern): CTRL+SHIFT+L 

# Aufgaben
- [ ] Entsprechung der Zeilen prüfen - Vergleich mit english.lng
- [ ] Namen der Variablen abgleichen 
- [ ] Einheitliche Schreibweise für Tasten: 
	- Strg, STRG, Shift, SHIFT, Umschalt, Enter
	- Deutsch oder Englisch? 
	- Großbuchstaben? 
- [ ] Vereinheitlichen: 
	- Popup / Pop-Up
	- Skin / Oberfläche
	- ''theWord'' statt ''The Word''
	- z.B. statt Bsp, zB
- [ ] Fehler: 
	- Zeile 1001: Einstellungen zur Bibelansicht -> User Toggles: nur Englisch zeigt in Überschrift den Bibelnamen an, Deutsch nicht 
	- ab Zeile 1021: Überschrift "lblBGloss.Caption" auskommentiert - nicht aktiv
	- Zeilen 1099 + 1100 noch notwendig? Keine Punkte im Menü sichtbar - actImportNotes.Caption und actImportNotes.Hint
- [ ] Im Bibelleseplan sind viele Texte nicht in der Sprachdatei zu finden

# Gelöschte Strings
- chkAutosizeImages.Hint='Aktivieren Sie diese Option, wenn das Modul große Bilder enthält. Dadurch kann der Endbenutzer die Schaltfläche ''Automatische Größenanpassung'' in der Buchansicht aktivieren, die die Größe der Bilder automatisch an den verfügbaren Platz in der Buchansicht anpasst. '#13#13' Beachten Sie, dass diese Option auch für jedes einzelne Bild eingestellt werden kann. Beachten Sie, dass diese Option auch auf der Ebene der einzelnen Bilder gesetzt werden kann. Die Option pro Bild hat Vorrang vor dieser Option, die für alle Bilder gilt, für die die spezifische Option NICHT gesetzt ist.'#13#13'Diese Option ist nur für Nicht-Benutzermodule verfügbar.'
- cmdCenterNode.Caption='Selektierten Knoten in der Ansicht zentrieren'
- tbitemTabContext.Hint='Aktuelle Einstellung Bibel, und allgemeine Einstellungen aktuelles Fenster und Bibel-Werkzeugkasten'
- actSync.Caption='Synchronisieren mit'
- actSync.Hint='Auf den schwarzen Pfeil klicken, um eine oder mehrere Bibelansichten auszuwählen, mit denen diese Ansicht synchronisiert werden soll.'#13#13'Der Button selbst dient als Schalter, und wechselt zwischen Synchronisierung AN/AUS.'
- actOptions.Caption='Einstellungen zur Bibelansicht...'
- actShowHideViewerIcons.Caption='Icons anzeigen/verbergen'
- actOptions.Hint='Optionen für Bibelansicht'
- 

#Dialog to select Bible modules to display in parallel (Compare).
#in Bible view, click on the arrow of the 'Compare' button, from the popup
#select 'Select Bible texts for parallel view...'
[TfrmParallelSelect]
#parallel bible select
cmdParSelUp.Hint='nach oben'
cmdParSelDown.Hint='nach unten'
cmdParSelCheck.Hint='Alles auswäh&len'
cmdParSelUncheck.Hint='Alles abwählen'
cmdParSelOK.Hint='Speichern'
lblHor.Caption='Bibelmodule für die Spaltenansicht auswählen'
chkHor.Caption='Diese Auswahl auch für die Zeilenansicht verwenden'
lblVer.Caption='Bibelmodule für die Zeilenansicht auswählen'
chkVer.Caption='Diese Auswahl auch für die Spaltenansicht verwenden'
chkDescr.Caption='Beschreibungen anzeigen'

# Englisch oder Deutsch?
- Identifier oder Kennung? 
- Skin 

