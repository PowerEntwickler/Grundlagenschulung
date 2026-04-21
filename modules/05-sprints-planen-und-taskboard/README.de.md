# Modul 05 - Sprints planen und Sprint-Backlog nutzen

## 🎯 Ziel dieses Moduls
In diesem Modul lernen die Teilnehmenden, wie sie in Azure DevOps Services mit Sprints und Sprint-Backlogs arbeiten. Nach dem Lab können sie:

1. in der Projektkonfiguration **drei Sprints** anlegen
2. die Sprints unter dem eigenen **Teamnamen** gruppieren
3. die Sprints dem eigenen Team zuordnen
4. bestehende Work Items einem Sprint zuweisen
5. im **Sprint Backlog** zu den Items passende **Tasks** anlegen
6. für diese Tasks **Remaining Work** pflegen

## 🧭 Szenario
Nach der Strukturierung der Backlogs, Queries und des Kanban-Boards wird nun der nächste Schritt im Projektmanagement geübt: die zeitliche Planung der Arbeit in Sprints.

Jede Person richtet für das eigene Team eine saubere Sprintstruktur ein, plant bestehende Arbeitselemente in diese Sprints ein und bricht die Arbeit im Sprint Backlog in konkrete Aufgaben herunter.

## ✅ Voraussetzungen
- [Modul 01](../01-grundlagen-arbeitselemente-erzeugen/README.de.md) bis [Modul 04](../04-kanban-board-anpassen/README.de.md) wurden abgeschlossen
- Sie haben ein eigenes Team mit Ihrem **Vornamen**
- Es gibt bereits mehrere Work Items in Ihrem Teamkontext
- Zugriff auf die Azure DevOps Services Organisation **tuvsud10**
- Die Menüführung ist grundsätzlich **Englisch**

## ⚠️ Wichtiger Hinweis
In diesem Modul arbeiten Sie mit **Iteration Paths**. Diese sind etwas anderes als **Area Paths**:

- **Area Path** = welchem Team- oder Fachbereich ein Work Item gehört
- **Iteration Path** = in welchem Sprint oder Zeitraum es bearbeitet werden soll

Auch in dieser deutschen Anleitung werden die tatsächlichen **englischen UI-Begriffe** aus Azure DevOps Services verwendet.

## 📅 Feste Sprinttermine für dieses Training
Verwenden Sie in diesem Modul die folgenden Datumswerte:

1. **Sprint 1:** 20.04.2026 bis 01.05.2026
2. **Sprint 2:** 04.05.2026 bis 15.05.2026
3. **Sprint 3:** 18.05.2026 bis 29.05.2026

---

## Übung 1 - Die Sprint-Struktur in der Projektkonfiguration anlegen

### 🎯 Ziel
Sie legen drei Sprints unter Ihrem eigenen Teamnamen an.

### 🔧 Schritte
1. Melden Sie sich in **tuvsud10** an und öffnen Sie das Projekt Ihrer Zweiergruppe.
2. Klicken Sie links unten auf **Project settings**.
3. Öffnen Sie - je nach sichtbarer Navigation - **Project configuration** oder den Bereich **Iterations**.
4. Legen Sie zunächst einen übergeordneten Eintrag mit Ihrem Teamnamen an, also mit Ihrem **Vornamen**, zum Beispiel:
   `Maria`
5. Legen Sie unter diesem Eintrag drei untergeordnete Sprints an:
   - `Sprint 1`
   - `Sprint 2`
   - `Sprint 3`
6. Tragen Sie für die drei Sprints die festgelegten Datumswerte ein:
   - **Sprint 1:** Start `20.04.2026`, End `01.05.2026`
   - **Sprint 2:** Start `04.05.2026`, End `15.05.2026`
   - **Sprint 3:** Start `18.05.2026`, End `29.05.2026`
7. Speichern Sie die Konfiguration.

### 🟢 Erwartetes Ergebnis
Unter Ihrem Teamnamen existiert jetzt eine klare Sprintstruktur mit drei zeitlich definierten Sprints.

---

## Übung 2 - Die Sprints Ihrem Team zuordnen

### 🎯 Ziel
Sie machen die angelegten Sprints für Ihr Team nutzbar.

### 🔧 Schritte
1. Wechseln Sie aus den **Project settings** wieder in den Bereich **Boards**.
2. Öffnen Sie **Boards > Backlogs**.
3. Wählen Sie über den **Team selector** Ihr eigenes Team mit Ihrem Vornamen aus.
4. Klicken Sie oben rechts auf das Zahnrad-Symbol **Team settings** (Tooltip: *Configure team settings*). Der Dialog **Team Configuration** öffnet sich.
5. Wechseln Sie dort in den Tab **Iterations**.
6. Klicken Sie auf **Select iteration(s)** und fügen Sie nacheinander die drei eben erstellten Sprintpfade hinzu:
   - `Maria\Sprint 1`
   - `Maria\Sprint 2`
   - `Maria\Sprint 3`
7. Setzen Sie bei Bedarf **Maria\Sprint 1** als **Default iteration** für neue Work Items.
8. Schliessen Sie den Dialog.
9. Kontrollieren Sie, indem Sie zu **Boards > Sprints** wechseln, ob die drei Sprints jetzt verfügbar sind.

### 🟢 Erwartetes Ergebnis
Ihr Team kann jetzt mit den eigenen Sprints in **Boards > Sprints** arbeiten.

---

## Übung 3 - Work Items den Sprints zuordnen

### 🎯 Ziel
Sie planen bestehende Arbeitselemente in konkrete Zeiträume ein.

### 🔧 Schritte
1. Wechseln Sie zu **Boards > Backlogs**.
2. Öffnen Sie rechts das Panel **Planning**, falls es noch nicht sichtbar ist.
3. Suchen Sie Ihre eigenen Work Items mit Ihrem Vornamen oder mit Ihrem Nutzer-Präfix aus den früheren Modulen.
4. Ziehen Sie passende Work Items über das **Planning**-Panel in einen der neu angelegten Sprints.
5. Ordnen Sie einige Elemente **Sprint 1**, einige **Sprint 2** und einige **Sprint 3** zu.
6. Prüfen Sie stichprobenartig bei einem Work Item, ob der **Iteration Path** nun passend gesetzt wurde.

### 🟢 Erwartetes Ergebnis
Ihre Work Items sind jetzt auf mehrere Sprints verteilt und zeitlich eingeplant.

---

## Übung 4 - Das Sprint Backlog öffnen

### 🎯 Ziel
Sie wechseln von der allgemeinen Backlog-Sicht in die sprintbezogene Planung.

### 🔧 Schritte
1. Wechseln Sie zu **Boards > Sprints**.
2. Wählen Sie über den **Team selector** Ihr eigenes Team aus.
3. Öffnen Sie links oder oben **Sprint 1**.
4. Prüfen Sie, ob dort nun die Work Items angezeigt werden, die Sie diesem Sprint über **Iteration Path** zugeordnet haben.
5. Falls Elemente fehlen, kontrollieren Sie den **Iteration Path** der betreffenden Work Items erneut.

### 🟢 Erwartetes Ergebnis
Sie sehen nun das Sprint Backlog Ihres Teams für den ausgewählten Sprint.

---

## Übung 5 - Tasks zu Sprint-Items hinzufügen

### 🎯 Ziel
Sie zerlegen ein Sprint-Item in konkrete Arbeitsschritte.

### 🔧 Schritte
1. Bleiben Sie in **Boards > Sprints** innerhalb von **Sprint 1**.
2. Suchen Sie ein Product Backlog Item, das Sie bereits in diesen Sprint eingeplant haben.
3. Klicken Sie unter diesem Element auf die Funktion zum Hinzufügen einer neuen Aufgabe, zum Beispiel auf **+** oder **Add Task**.
4. Verwenden Sie dafür den Work-Item-Typ **Task**.
5. Legen Sie mindestens zwei Tasks für ein Work Item an, zum Beispiel:
   - `Agenda entwerfen`
   - `Teilnehmende abstimmen`
6. Wiederholen Sie den Vorgang für mindestens ein weiteres Work Item im Sprint.

### 🟢 Erwartetes Ergebnis
Mindestens zwei Sprint-Items wurden in kleinere, konkrete Tasks heruntergebrochen.

---

## Übung 6 - Remaining Work setzen

### 🎯 Ziel
Sie pflegen den geschätzten Restaufwand für die Sprint-Tasks.

### 🔧 Schritte
1. Öffnen Sie einen der neu angelegten Tasks.
2. Suchen Sie das Feld **Remaining Work**.
3. Tragen Sie einen sinnvollen Aufwand ein, zum Beispiel:
   - `2`
   - `4`
   - `6`
4. Speichern Sie den Task.
5. Wiederholen Sie das für die weiteren Tasks Ihres Sprint Backlogs.
6. Wechseln Sie anschliessend bei Bedarf auf das **Taskboard**, um die Aufgaben und ihre Aufwände im Sprintkontext zu sehen.

### 🟢 Erwartetes Ergebnis
Die Tasks im Sprint enthalten jetzt konkrete Werte für **Remaining Work** und können besser geplant und nachverfolgt werden.

---

## ⚠️ Typische Stolpersteine

- Wenn das **Planning**-Panel nicht sichtbar ist, prüfen Sie, ob Sie wirklich in **Boards > Backlogs** arbeiten.
- Wenn ein Sprint im Sprint Backlog leer bleibt, ist meist der **Iteration Path** der Work Items noch nicht korrekt gesetzt.
- **Remaining Work** ist für die Sprintplanung besonders auf **Task**-Ebene sinnvoll und sollte dort gepflegt werden.

---

## 🏁 Abschlusskontrolle
Am Ende dieses Moduls sollten Sie folgende Ergebnisse sehen:

1. drei Sprints unter Ihrem eigenen **Teamnamen**
2. die Sprints sind Ihrem Team zugeordnet
3. mehrere Work Items wurden über den **Iteration Path** auf die Sprints verteilt
4. im **Sprint Backlog** wurden neue **Tasks** angelegt
5. für die Tasks wurden Werte in **Remaining Work** gepflegt

Wenn diese Punkte sichtbar sind, haben Sie die Grundlagen von Sprintplanung, Sprint Backlog und Aufwandspflege in Azure DevOps erfolgreich abgeschlossen.
