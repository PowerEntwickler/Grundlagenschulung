# Modul 01 - Grundlagen Arbeitselemente erzeugen

## 🎯 Ziel dieses Moduls
In diesem Modul lernen die Teilnehmenden die wichtigsten Grundfunktionen von Azure DevOps Boards kennen. Nach dem Lab können sie:

1. sich in **Boards**, **Backlogs** und **Work Items** orientieren
2. **Product Backlog Items (PBI)** an mehreren Stellen anlegen
3. **Kommentare** erfassen
4. **Anhänge** hochladen
5. den **Status/State** eines Work Items ändern

## 🧭 Szenario
Sie unterstützen ein Projektmanagement-Team bei der Vorbereitung eines neuen Mobilitätsprojekts. Die ersten organisatorischen Aufgaben sollen in Azure DevOps Boards sauber dokumentiert und nachverfolgt werden.

Die Übungen sind bewusst **nicht entwicklungsbezogen**. Stattdessen arbeiten Sie mit einfachen Projektmanagement-Beispielen wie Kick-off, Stakeholderliste und Kommunikationsplanung.

## ✅ Voraussetzungen
- Zugriff auf die Azure DevOps Services Organisation **tuvsud10**
- Zugriff auf das Projekt, das Ihrer Zweiergruppe zugewiesen wurde
- Berechtigung zum Erstellen und Bearbeiten von Work Items
- Ein Browser und eine kleine Beispieldatei für einen späteren Anhang, zum Beispiel ein PDF, Word-Dokument oder Bild
- Die Menüführung in Azure DevOps ist im Training grundsätzlich **Englisch**

## 💡 Hinweis zum Prozess
Dieses Grundlagenmodul verwendet bewusst den Work-Item-Typ **Product Backlog Item**, um die Bedienung von Azure DevOps Boards möglichst einfach zu erklären. In späteren Modulen können dieselben Grundschritte auf den Prozess **TUV Scrum for Mobility** mit eigenen Work-Item-Typen übertragen werden.

## 🤝 Hinweis zur Zusammenarbeit
Jeweils **zwei Teilnehmende teilen sich ein Projekt**. Damit Sie sich nicht gegenseitig Work Items überschreiben oder schwer unterscheiden können, verwenden Sie in den Beispieltiteln bitte Ihren **eigenen Vornamen**, zum Beispiel:

`[Maria] Kick-off-Termin vorbereiten`

Auch in dieser deutschen Anleitung werden die tatsächlichen **englischen Menübegriffe** aus Azure DevOps Services verwendet, damit die Navigation im System leichter nachvollziehbar ist.

---

## Übung 1 - Orientierung in Azure DevOps Boards

### 🎯 Ziel
Sie lernen, wo sich die wichtigsten Bereiche befinden.

### 🔧 Schritte
1. Melden Sie sich in Ihrer Azure DevOps Organisation an.
2. Wählen Sie die Organisation **tuvsud10** aus.
3. Öffnen Sie das Projekt, das Ihrer Zweiergruppe für die Schulung zugewiesen wurde.
4. Klicken Sie in der linken Navigation auf **Boards**.
5. Öffnen Sie nacheinander:
   - **Boards > Backlogs**
   - **Boards > Boards**
   - **Boards > Work Items**
6. Schauen Sie sich in jedem Bereich kurz an, wo neue Einträge erzeugt werden können.
7. Kehren Sie anschliessend zu **Boards > Backlogs** zurück.

### 🟢 Erwartetes Ergebnis
Sie wissen nun, an welchen Stellen Sie Backlogs, das Board und die zentrale Liste der Work Items finden.

---

## Übung 2 - Ein Product Backlog Item im Backlog anlegen

### 🎯 Ziel
Sie erstellen Ihr erstes Work Item direkt im Backlog.

### 🔧 Schritte
1. Bleiben Sie in **Boards > Backlogs**.
2. Prüfen Sie, dass die passende Backlog-Ebene angezeigt wird. Wenn mehrere Ebenen sichtbar sind, wählen Sie die Ebene für **Product Backlog Items** oder die vom Trainer genannte Ebene.
3. Klicken Sie auf **New Work Item**, **Neues Arbeitselement** oder direkt auf die Eingabezeile unterhalb der Liste.
4. Tragen Sie als Titel ein:
   `[IhrVorname] Kick-off-Termin vorbereiten`
5. Öffnen Sie das neu angelegte Work Item.
6. Füllen Sie mindestens diese Felder:
   - **Title**: ist bereits gesetzt
   - **Description**: `Kick-off planen, Agenda vorbereiten und Teilnehmende abstimmen.`
   - **Assigned To**: tragen Sie sich selbst ein, falls sinnvoll
7. Speichern Sie das Work Item mit **Save** oder **Speichern**.

### 🟢 Erwartetes Ergebnis
Ein erstes Product Backlog Item wurde direkt aus dem Backlog angelegt und gespeichert.

---

## Übung 3 - Ein Product Backlog Item auf dem Board anlegen

### 🎯 Ziel
Sie erstellen ein weiteres Work Item an einer anderen Stelle, direkt auf dem Kanban-Board.

### 🔧 Schritte
1. Wechseln Sie zu **Boards > Boards**.
2. Suchen Sie die linke, erste Statusspalte, zum Beispiel **New**, **To Do** oder eine ähnliche Startspalte.
3. Klicken Sie in dieser Spalte auf **New item**, **+** oder **Neues Element**.
4. Erfassen Sie den Titel:
   `[IhrVorname] Stakeholderliste erstellen`
5. Falls Azure DevOps nach dem Typ fragt, wählen Sie **Product Backlog Item**.
6. Öffnen Sie die neue Karte oder das neue Work Item.
7. Ergänzen Sie in der Beschreibung:
   `Wichtige interne und externe Ansprechpartner sammeln und dokumentieren.`
8. Speichern Sie die Änderung.

### 🟢 Erwartetes Ergebnis
Sie haben ein zweites Product Backlog Item direkt über das Board erstellt.

---

## Übung 4 - Ein Product Backlog Item über "Work Items" anlegen

### 🎯 Ziel
Sie lernen einen dritten Einstiegspunkt für neue Work Items kennen.

### 🔧 Schritte
1. Wechseln Sie zu **Boards > Work Items**.
2. Klicken Sie oben auf **New Work Item**.
3. Wählen Sie **Product Backlog Item** aus.
4. Erfassen Sie den Titel:
   `[IhrVorname] Kommunikationsplan abstimmen`
5. Tragen Sie in die Beschreibung ein:
   `Festlegen, wie Statusupdates im Projekt kommuniziert werden.`
6. Speichern Sie das Work Item.
7. Prüfen Sie anschliessend, ob das neue Element nun in der Work-Item-Liste erscheint.

### 🟢 Erwartetes Ergebnis
Sie haben nun Product Backlog Items über drei verschiedene Bereiche erstellt: **Backlog**, **Board** und **Work Items**.

---

## Übung 5 - Kommentare zu einem Work Item hinzufügen

### 🎯 Ziel
Sie dokumentieren eine kurze Rückmeldung direkt im Work Item.

### 🔧 Schritte
1. Öffnen Sie das Work Item `[IhrVorname] Kick-off-Termin vorbereiten`.
2. Suchen Sie den Bereich **Discussion** oder **History**.
3. Fügen Sie einen kurzen Kommentar hinzu, zum Beispiel:
   `Erster Vorschlag für den Termin wurde im Team abgestimmt.`
4. Speichern Sie den Kommentar, falls dies in Ihrer Ansicht erforderlich ist.
5. Kontrollieren Sie, ob der Kommentar anschliessend in der Historie sichtbar ist.

### 🟢 Erwartetes Ergebnis
Das Work Item enthält nun eine nachvollziehbare Rückmeldung in der Kommentar- oder Historienansicht.

---

## Übung 6 - Einen Anhang hochladen

### 🎯 Ziel
Sie verknüpfen zusätzliche Unterlagen mit einem Work Item.

### 🔧 Schritte
1. Öffnen Sie das Work Item `[IhrVorname] Stakeholderliste erstellen`.
2. Suchen Sie das Symbol oder den Bereich für **Attachments**.
3. Laden Sie eine kleine Beispieldatei hoch, zum Beispiel:
   - eine Agenda
   - ein PDF
   - ein Bild
4. Warten Sie, bis der Upload abgeschlossen ist.
5. Speichern Sie das Work Item erneut, falls nötig.

### 🟢 Erwartetes Ergebnis
Im Work Item ist jetzt mindestens ein Anhang sichtbar.

---

## Übung 7 - Den Status eines Work Items ändern

### 🎯 Ziel
Sie lernen, wie der Bearbeitungsstand gepflegt wird.

### 🔧 Schritte
1. Öffnen Sie das Work Item `[IhrVorname] Kommunikationsplan abstimmen`.
2. Suchen Sie das Feld **State**.
3. Ändern Sie den Wert auf den nächsten sinnvollen Bearbeitungsstand im Prozess **TUV Scrum for Mobility** (basiert auf Scrum), zum Beispiel:
   - `New` → `Approved`
   - `Approved` → `Committed`
   - `Committed` → `Done`
4. Speichern Sie die Änderung.
5. Wechseln Sie wieder zu **Boards > Boards** und beobachten Sie, ob sich die Karte in eine andere Spalte verschiebt.

### 🟢 Erwartetes Ergebnis
Sie haben verstanden, wie Azure DevOps den Fortschritt über den State bzw. Status sichtbar macht.

---

## ⚠️ Typische Stolpersteine

- Wenn der **State** nicht angepasst werden kann, gehört das Work Item meist einem anderen Prozesstyp als **Product Backlog Item**. Öffnen Sie in diesem Fall ein Work Item, das eindeutig als **Product Backlog Item** angelegt wurde.
- Wenn ein **Anhang** nach dem Hochladen nicht erscheint, wurde das Work Item meist noch nicht gespeichert. Klicken Sie erneut auf **Save**.
- Wenn ein **Kommentar** nicht in der Historie auftaucht, wurde er häufig nur getippt, aber nicht mit **Save** oder dem Kommentar-Button bestätigt.
- Wenn das neue Work Item nicht im Backlog erscheint, ist oft die **falsche Backlog-Ebene** ausgewählt. Prüfen Sie, dass die Ebene **Product Backlog Items** aktiv ist.

---

## 🏁 Abschlusskontrolle
Am Ende dieses Moduls sollten Sie folgende Ergebnisse sehen:

1. mindestens **drei Product Backlog Items**
2. ein Work Item mit **Kommentar**
3. ein Work Item mit **Anhang**
4. mindestens ein Work Item mit **geändertem Status**

Wenn alle Punkte sichtbar sind, haben Sie die absoluten Grundlagen von Azure DevOps Boards erfolgreich abgeschlossen.
