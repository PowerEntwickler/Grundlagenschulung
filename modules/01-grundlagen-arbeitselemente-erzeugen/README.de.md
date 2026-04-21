# Modul 01 - Grundlagen Arbeitselemente erzeugen

## Ziel dieses Moduls
In diesem Modul lernen die Teilnehmenden die wichtigsten Grundfunktionen von Azure DevOps Boards kennen. Nach dem Lab koennen sie:

1. sich in **Boards**, **Backlogs** und **Work Items** orientieren
2. **Product Backlog Items (PBI)** an mehreren Stellen anlegen
3. **Kommentare** erfassen
4. **Anhaenge** hochladen
5. den **Status/State** eines Work Items aendern

## Szenario
Sie unterstuetzen ein Projektmanagement-Team bei der Vorbereitung eines neuen Mobilitaetsprojekts. Die ersten organisatorischen Aufgaben sollen in Azure DevOps Boards sauber dokumentiert und nachverfolgt werden.

Die Uebungen sind bewusst **nicht entwicklungsbezogen**. Stattdessen arbeiten Sie mit einfachen Projektmanagement-Beispielen wie Kick-off, Stakeholderliste und Kommunikationsplanung.

## Voraussetzungen
- Zugriff auf die Azure DevOps Services Organisation **tuvsud10**
- Zugriff auf das Projekt, das Ihrer Zweiergruppe zugewiesen wurde
- Berechtigung zum Erstellen und Bearbeiten von Work Items
- Ein Browser und eine kleine Beispieldatei fuer einen spaeteren Anhang, zum Beispiel ein PDF, Word-Dokument oder Bild
- Die Menuefuehrung in Azure DevOps ist im Training grundsaetzlich **Englisch**

## Hinweis zum Prozess
Dieses Grundlagenmodul verwendet bewusst den Work-Item-Typ **Product Backlog Item**, um die Bedienung von Azure DevOps Boards moeglichst einfach zu erklaeren. In spaeteren Modulen koennen dieselben Grundschritte auf den Prozess **TUV Scrum for Mobility** mit eigenen Work-Item-Typen uebertragen werden.

## Hinweis zur Zusammenarbeit
Jeweils **zwei Teilnehmende teilen sich ein Projekt**. Damit Sie sich nicht gegenseitig Work Items ueberschreiben oder schwer unterscheiden koennen, verwenden Sie in den Beispieltiteln bitte Ihren **eigenen Vornamen**, zum Beispiel:

`[Maria] Kick-off-Termin vorbereiten`

Auch in dieser deutschen Anleitung werden die tatsaechlichen **englischen Menuebegriffe** aus Azure DevOps Services verwendet, damit die Navigation im System leichter nachvollziehbar ist.

---

## Uebung 1 - Orientierung in Azure DevOps Boards

### Ziel
Sie lernen, wo sich die wichtigsten Bereiche befinden.

### Schritte
1. Melden Sie sich in Ihrer Azure DevOps Organisation an.
2. Waehlen Sie die Organisation **tuvsud10** aus.
3. Oeffnen Sie das Projekt, das Ihrer Zweiergruppe fuer die Schulung zugewiesen wurde.
4. Klicken Sie in der linken Navigation auf **Boards**.
5. Oeffnen Sie nacheinander:
   - **Boards > Backlogs**
   - **Boards > Boards**
   - **Boards > Work Items**
6. Schauen Sie sich in jedem Bereich kurz an, wo neue Eintraege erzeugt werden koennen.
7. Kehren Sie anschliessend zu **Boards > Backlogs** zurueck.

### Erwartetes Ergebnis
Sie wissen nun, an welchen Stellen Sie Backlogs, das Board und die zentrale Liste der Work Items finden.

---

## Uebung 2 - Ein Product Backlog Item im Backlog anlegen

### Ziel
Sie erstellen Ihr erstes Work Item direkt im Backlog.

### Schritte
1. Bleiben Sie in **Boards > Backlogs**.
2. Pruefen Sie, dass die passende Backlog-Ebene angezeigt wird. Wenn mehrere Ebenen sichtbar sind, waehlen Sie die Ebene fuer **Product Backlog Items** oder die vom Trainer genannte Ebene.
3. Klicken Sie auf **New Work Item**, **Neues Arbeitselement** oder direkt auf die Eingabezeile unterhalb der Liste.
4. Tragen Sie als Titel ein:
   `[IhrVorname] Kick-off-Termin vorbereiten`
5. Oeffnen Sie das neu angelegte Work Item.
6. Fuellen Sie mindestens diese Felder:
   - **Title**: ist bereits gesetzt
   - **Description**: `Kick-off planen, Agenda vorbereiten und Teilnehmende abstimmen.`
   - **Assigned To**: tragen Sie sich selbst ein, falls sinnvoll
7. Speichern Sie das Work Item mit **Save** oder **Speichern**.

### Erwartetes Ergebnis
Ein erstes Product Backlog Item wurde direkt aus dem Backlog angelegt und gespeichert.

---

## Uebung 3 - Ein Product Backlog Item auf dem Board anlegen

### Ziel
Sie erstellen ein weiteres Work Item an einer anderen Stelle, direkt auf dem Kanban-Board.

### Schritte
1. Wechseln Sie zu **Boards > Boards**.
2. Suchen Sie die linke, erste Statusspalte, zum Beispiel **New**, **To Do** oder eine aehnliche Startspalte.
3. Klicken Sie in dieser Spalte auf **New item**, **+** oder **Neues Element**.
4. Erfassen Sie den Titel:
   `[IhrVorname] Stakeholderliste erstellen`
5. Falls Azure DevOps nach dem Typ fragt, waehlen Sie **Product Backlog Item**.
6. Oeffnen Sie die neue Karte oder das neue Work Item.
7. Ergaenzen Sie in der Beschreibung:
   `Wichtige interne und externe Ansprechpartner sammeln und dokumentieren.`
8. Speichern Sie die Aenderung.

### Erwartetes Ergebnis
Sie haben ein zweites Product Backlog Item direkt ueber das Board erstellt.

---

## Uebung 4 - Ein Product Backlog Item ueber "Work Items" anlegen

### Ziel
Sie lernen einen dritten Einstiegspunkt fuer neue Work Items kennen.

### Schritte
1. Wechseln Sie zu **Boards > Work Items**.
2. Klicken Sie oben auf **New Work Item**.
3. Waehlen Sie **Product Backlog Item** aus.
4. Erfassen Sie den Titel:
   `[IhrVorname] Kommunikationsplan abstimmen`
5. Tragen Sie in die Beschreibung ein:
   `Festlegen, wie Statusupdates im Projekt kommuniziert werden.`
6. Speichern Sie das Work Item.
7. Pruefen Sie anschliessend, ob das neue Element nun in der Work-Item-Liste erscheint.

### Erwartetes Ergebnis
Sie haben nun Product Backlog Items ueber drei verschiedene Bereiche erstellt: **Backlog**, **Board** und **Work Items**.

---

## Uebung 5 - Kommentare zu einem Work Item hinzufuegen

### Ziel
Sie dokumentieren eine kurze Rueckmeldung direkt im Work Item.

### Schritte
1. Oeffnen Sie das Work Item `[IhrVorname] Kick-off-Termin vorbereiten`.
2. Suchen Sie den Bereich **Discussion** oder **History**.
3. Fuegen Sie einen kurzen Kommentar hinzu, zum Beispiel:
   `Erster Vorschlag fuer den Termin wurde im Team abgestimmt.`
4. Speichern Sie den Kommentar, falls dies in Ihrer Ansicht erforderlich ist.
5. Kontrollieren Sie, ob der Kommentar anschliessend in der Historie sichtbar ist.

### Erwartetes Ergebnis
Das Work Item enthaelt nun eine nachvollziehbare Rueckmeldung in der Kommentar- oder Historienansicht.

---

## Uebung 6 - Einen Anhang hochladen

### Ziel
Sie verknuepfen zusaetzliche Unterlagen mit einem Work Item.

### Schritte
1. Oeffnen Sie das Work Item `[IhrVorname] Stakeholderliste erstellen`.
2. Suchen Sie das Symbol oder den Bereich fuer **Attachments**.
3. Laden Sie eine kleine Beispieldatei hoch, zum Beispiel:
   - eine Agenda
   - ein PDF
   - ein Bild
4. Warten Sie, bis der Upload abgeschlossen ist.
5. Speichern Sie das Work Item erneut, falls noetig.

### Erwartetes Ergebnis
Im Work Item ist jetzt mindestens ein Anhang sichtbar.

---

## Uebung 7 - Den Status eines Work Items aendern

### Ziel
Sie lernen, wie der Bearbeitungsstand gepflegt wird.

### Schritte
1. Oeffnen Sie das Work Item `[IhrVorname] Kommunikationsplan abstimmen`.
2. Suchen Sie das Feld **State**.
3. Aendern Sie den Wert auf den naechsten sinnvollen Bearbeitungsstand Ihres Projekts, zum Beispiel:
   - `New` nach `Approved`
   - `Approved` nach `Committed`
   - `To Do` nach `Doing`
4. Speichern Sie die Aenderung.
5. Wechseln Sie wieder zu **Boards > Boards** und beobachten Sie, ob sich die Karte in eine andere Spalte verschiebt.

### Erwartetes Ergebnis
Sie haben verstanden, wie Azure DevOps den Fortschritt ueber den State bzw. Status sichtbar macht.

---

## Abschlusskontrolle
Am Ende dieses Moduls sollten Sie folgende Ergebnisse sehen:

1. mindestens **drei Product Backlog Items**
2. ein Work Item mit **Kommentar**
3. ein Work Item mit **Anhang**
4. mindestens ein Work Item mit **geaendertem Status**

Wenn alle Punkte sichtbar sind, haben Sie die absoluten Grundlagen von Azure DevOps Boards erfolgreich abgeschlossen.
