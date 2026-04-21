# Modul 03 - Import, Massenbearbeitung, Queries und Charts

## Ziel dieses Moduls
In diesem Modul lernen die Teilnehmenden, wie groessere Mengen an Arbeitselementen in Azure DevOps Services importiert und anschliessend strukturiert ausgewertet werden. Nach dem Lab koennen sie:

1. vorbereitete **CSV-Dateien** in Azure DevOps importieren
2. mehrere Work Items per **Massenbearbeitung** gleichzeitig anpassen
3. importierte Elemente in den richtigen **Area Path** ihres Teams verschieben
4. eigene **Queries** erstellen und speichern
5. eine **Chart** auf Basis einer Query anlegen und interpretieren

## Szenario
Im Alltag kommen neue Projektaufgaben oft nicht einzeln, sondern gesammelt aus einer Liste oder einer Vorabplanung. In diesem Modul uebernehmen die Teilnehmenden genau so einen Fall: Sie importieren eine groessere Menge an vorbereiteten Product Backlog Items aus einer CSV-Datei.

Da sich weiterhin jeweils **zwei Teilnehmende ein Projekt teilen**, gibt es zwei getrennte Datensaetze. Nach dem Import werden die Elemente per Massenbearbeitung in den richtigen Teamkontext gebracht. Anschliessend werden Queries und eine Chart erstellt, um die neue Datenmenge sinnvoll auszuwerten.

## Voraussetzungen
- Modul 01 und Modul 02 wurden abgeschlossen
- Sie haben bereits ein eigenes Team mit Ihrem **Vornamen**
- Fuer Ihr Team existiert bereits ein passender **Area Path**
- Zugriff auf die Azure DevOps Services Organisation **tuvsud10**
- Die Menuefuehrung ist grundsaetzlich **Englisch**

## Dateien fuer dieses Modul
Die CSV-Dateien liegen in diesem Modulordner unter `assets`:

- `nutzer-a-workitems.de.csv`
- `nutzer-b-workitems.de.csv`
- `user-a-workitems.en.csv`
- `user-b-workitems.en.csv`

## Wichtiger Hinweis vor dem Start
Klaeren Sie **vor dem Import**, wer in Ihrer Zweiergruppe **Nutzer A** und wer **Nutzer B** ist. Jede Person darf **nur die eigene Datei** importieren. So vermeiden Sie doppelte oder falsch zugeordnete Daten im gemeinsamen Projekt.

Auch in der deutschen Anleitung werden die tatsaechlichen **englischen UI-Begriffe** aus Azure DevOps Services verwendet.

---

## Uebung 1 - Die richtige CSV-Datei auswaehlen

### Ziel
Sie waehlen den korrekten Importdatensatz fuer Ihre Rolle aus.

### Schritte
1. Stimmen Sie sich mit Ihrer Partnerin oder Ihrem Partner ab:
   - eine Person ist **Nutzer A**
   - eine Person ist **Nutzer B**
2. Oeffnen Sie den Modulordner mit den bereitgestellten CSV-Dateien.
3. Waehlen Sie die Datei, die zu Ihrer Sprache und Ihrer Rolle passt:
   - deutsch: `nutzer-a-workitems.de.csv` oder `nutzer-b-workitems.de.csv`
   - englisch: `user-a-workitems.en.csv` oder `user-b-workitems.en.csv`
4. Pruefen Sie kurz, dass die Titel in der Datei mit dem passenden Praefix beginnen, also zum Beispiel:
   - `Nutzer A - ...`
   - `Nutzer B - ...`
5. Schliessen Sie die Datei wieder, ohne den Inhalt unnoetig zu veraendern.

### Erwartetes Ergebnis
Jede Person weiss eindeutig, welche CSV-Datei sie spaeter importiert.

---

## Uebung 2 - Die Work Items importieren

### Ziel
Sie importieren eine groessere Menge an Product Backlog Items in das gemeinsame Projekt.

### Schritte
1. Melden Sie sich in **tuvsud10** an und oeffnen Sie das Projekt Ihrer Zweiergruppe.
2. Wechseln Sie zu **Boards > Work Items**.
3. Suchen Sie die Funktion **Import work items**. Je nach Ansicht befindet sie sich:
   - direkt als Schaltflaeche
   - oder im **...**-Menue
4. Waehlen Sie Ihre zuvor festgelegte CSV-Datei aus.
5. Starten Sie den Import.
6. Warten Sie, bis Azure DevOps die Vorschau oder das Ergebnis anzeigt.
7. Kontrollieren Sie stichprobenartig einige importierte Titel mit Ihrem Praefix, zum Beispiel:
   - `Nutzer A - Kick-off Agenda finalisieren`
   - `Nutzer A - Stakeholderliste ueberarbeiten`
8. Klicken Sie auf **Save items**, damit die importierten Elemente tatsaechlich gespeichert werden.
9. Schliessen Sie anschliessend den Importdialog.

### Erwartetes Ergebnis
Die Work Items aus Ihrer CSV-Datei sind jetzt im gemeinsamen Projekt vorhanden.

---

## Uebung 3 - Importierte Elemente per Massenbearbeitung anpassen

### Ziel
Sie lernen, mehrere Work Items gleichzeitig zu bearbeiten.

### Schritte
1. Bleiben Sie in **Boards > Work Items**.
2. Oeffnen Sie, falls der Filterbereich noch nicht sichtbar ist, oben rechts das **Filter**-Icon.
3. Verwenden Sie als Filter **Filter by keyword** und geben Sie Ihren passenden Nutzernamen ein, also zum Beispiel:
   - `Nutzer A`
   - oder `Nutzer B`
4. Fahren Sie bei jedem passenden Work Item mit der Maus links neben die ID und setzen Sie dort den Haken.
5. Wiederholen Sie dies, bis alle relevanten importierten Work Items markiert sind.
6. Klicken Sie eines der markierten Elemente mit der rechten Maustaste an und waehlen Sie **Open selected items in Queries**.
7. Die Ansicht sollte sich nun zu **Queries** aendern und Ihre ausgewaehlten Work Items anzeigen.
8. Klicken Sie eines der angezeigten Work Items an und druecken Sie anschliessend **STRG+A**, damit alle sichtbaren Work Items ausgewaehlt werden.
9. Klicken Sie erneut mit der rechten Maustaste und waehlen Sie **Edit**.
10. Aendern Sie in einem gemeinsamen Bearbeitungsschritt mindestens diese Felder:
   - **Area Path** auf Ihren eigenen Teambereich mit Ihrem Vornamen
   - optional **Assigned To** auf sich selbst
   - optional einen zusaetzlichen **Tag** wie `import-modul-03`
11. Speichern Sie die Aenderungen fuer alle markierten Elemente.
12. Kontrollieren Sie stichprobenartig zwei oder drei Work Items, ob die Anpassungen wirklich uebernommen wurden.

### Erwartetes Ergebnis
Sie haben mehrere Elemente gleichzeitig bearbeitet und damit die Grundlage fuer die spaetere Auswertung geschaffen.

---

## Uebung 4 - Die importierten Work Items in den eigenen Teamkontext bringen

### Ziel
Sie stellen sicher, dass die importierten Elemente im richtigen Team-Backlog und Board sichtbar werden.

### Schritte
1. Oeffnen Sie **Boards > Backlogs**.
2. Wechseln Sie ueber den **Team selector** auf Ihr eigenes Team mit Ihrem Vornamen.
3. Pruefen Sie, ob Ihre importierten Work Items jetzt im Backlog Ihres Teams sichtbar sind.
4. Falls nicht alle Elemente sichtbar sind, kontrollieren Sie erneut deren **Area Path**.
5. Korrigieren Sie fehlende oder falsche Zuordnungen bei Bedarf erneut ueber eine **Massenbearbeitung**.
6. Wechseln Sie anschliessend zu **Boards > Boards** und pruefen Sie die Sichtbarkeit dort ebenfalls.

### Erwartetes Ergebnis
Ihre importierten Work Items erscheinen jetzt im Teamkontext Ihres eigenen Backlogs und Boards.

---

## Uebung 5 - Eine erste Query fuer die importierten Elemente erstellen

### Ziel
Sie erstellen eine wiederverwendbare Abfrage fuer Ihre importierten Daten.

### Schritte
1. Wechseln Sie zu **Boards > Queries**.
2. Erstellen Sie eine neue Query vom Typ **Flat list of work items**.
3. Geben Sie der Query einen aussagekraeftigen Namen, zum Beispiel:
   `Meine importierten PBIs`
4. Definieren Sie passende Filter, zum Beispiel:
   - **Work Item Type** = `Product Backlog Item`
   - **Title** contains `Nutzer A` oder `Nutzer B`
   - **Area Path** = Ihr Teambereich
5. Fuehren Sie die Query aus.
6. Pruefen Sie, ob hauptsaechlich Ihre gerade importierten Elemente angezeigt werden.
7. Speichern Sie die Query.

### Erwartetes Ergebnis
Sie haben eine erste persoenliche Query erstellt, mit der Sie Ihre importierten Work Items schnell wiederfinden.

---

## Uebung 6 - Eine zweite Query fuer die Auswertung erstellen

### Ziel
Sie lernen, Queries gezielt fuer bestimmte Fragestellungen zu nutzen.

### Schritte
1. Erstellen Sie eine zweite Query, ebenfalls als **Flat list of work items**.
2. Vergeben Sie einen Namen wie:
   `Meine offenen importierten PBIs`
3. Verwenden Sie wieder Ihr Praefix und Ihren **Area Path** als Filter.
4. Ergaenzen Sie zusaetzlich mindestens einen weiteren Filter, zum Beispiel:
   - **State** <> `Done`
   - oder **Tags** contains `reporting`
   - oder **Tags** contains `communication`
5. Fuehren Sie die Query aus.
6. Vergleichen Sie das Ergebnis mit der ersten Query.
7. Speichern Sie auch diese Query.

### Erwartetes Ergebnis
Sie haben verstanden, dass Queries nicht nur zum Suchen dienen, sondern auch gezielt fuer Auswertungen aufgebaut werden koennen.

---

## Uebung 7 - Eine aussagekraeftige Chart auf Basis einer Query anlegen

### Ziel
Sie visualisieren Ihre importierten Arbeitselemente so, dass die Auswertung im Training direkt sinnvoll lesbar ist.

### Schritte
1. Oeffnen Sie eine Ihrer gespeicherten Queries, am besten die Query mit mehreren sichtbaren Ergebnissen.
2. Wechseln Sie in den Bereich **Charts**.
3. Klicken Sie auf **New chart** oder **Add chart**.
4. Waehlen Sie einen leicht verstaendlichen Diagrammtyp, zum Beispiel:
   - **Pie chart**
   - oder **Bar chart**
5. Stellen Sie die Chart vorzugsweise so ein, dass die Elemente nach **Tags** ausgewertet werden.
6. Geben Sie der Chart einen Namen wie:
   `Themen meiner importierten PBIs`
7. Speichern Sie die Chart.
8. Lesen Sie das Ergebnis kurz aus:
   - Welche Tags kommen besonders haeufig vor?
   - Welche Themen dominieren im importierten Backlog?
   - Wo liegen moegliche Schwerpunkte wie `planung`, `kommunikation` oder `reporting`?
9. Optional koennen Sie spaeter eine zweite Chart nach **State** anlegen, sobald einige Elemente manuell in andere Bearbeitungsstaende verschoben wurden.

### Erwartetes Ergebnis
Sie haben erfolgreich eine Chart auf Basis einer Query erstellt und koennen die Verteilung Ihrer importierten Arbeitselemente visuell auswerten.

---

## Typische Stolpersteine

- Wenn nach dem Import keine neuen Elemente sichtbar sind, wurde oft der Schritt **Save items** vergessen.
- Wenn Ihre importierten Elemente nicht im eigenen Backlog erscheinen, pruefen Sie zuerst **Area Path** und **Team selector**.
- Wenn die Chart kaum Unterschiede zeigt, gruppieren Sie zunaechst nach **Tags** statt nach **State**, weil alle CSV-Elemente anfangs auf **New** stehen.

---

## Abschlusskontrolle
Am Ende dieses Moduls sollten Sie folgende Ergebnisse sehen:

1. die korrekte CSV-Datei fuer **Nutzer A** oder **Nutzer B** wurde importiert
2. eine groessere Menge neuer **Product Backlog Items** ist im Projekt vorhanden
3. die importierten Elemente wurden per **Massenbearbeitung** angepasst
4. die Work Items sind Ihrem eigenen **Area Path** zugeordnet
5. mindestens **zwei gespeicherte Queries** wurden erstellt
6. mindestens **eine Chart** wurde gespeichert

Wenn diese Punkte sichtbar sind, haben Sie die Grundlagen zu Import, Massenbearbeitung, Queries und Charts in Azure DevOps erfolgreich abgeschlossen.
