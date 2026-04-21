# Modul 05 - Sprints planen und Sprint-Backlog nutzen

## Ziel dieses Moduls
In diesem Modul lernen die Teilnehmenden, wie sie in Azure DevOps Services mit Sprints und Sprint-Backlogs arbeiten. Nach dem Lab koennen sie:

1. in der Projektkonfiguration **drei Sprints** anlegen
2. die Sprints unter dem eigenen **Teamnamen** gruppieren
3. die Sprints dem eigenen Team zuordnen
4. bestehende Work Items einem Sprint zuweisen
5. im **Sprint Backlog** zu den Items passende **Tasks** anlegen
6. fuer diese Tasks **Remaining Work** pflegen

## Szenario
Nach der Strukturierung der Backlogs, Queries und des Kanban-Boards wird nun der naechste Schritt im Projektmanagement geuebt: die zeitliche Planung der Arbeit in Sprints.

Jede Person richtet fuer das eigene Team eine saubere Sprintstruktur ein, plant bestehende Arbeitselemente in diese Sprints ein und bricht die Arbeit im Sprint Backlog in konkrete Aufgaben herunter.

## Voraussetzungen
- Modul 01 bis Modul 04 wurden abgeschlossen
- Sie haben ein eigenes Team mit Ihrem **Vornamen**
- Es gibt bereits mehrere Work Items in Ihrem Teamkontext
- Zugriff auf die Azure DevOps Services Organisation **tuvsud10**
- Die Menuefuehrung ist grundsaetzlich **Englisch**

## Wichtiger Hinweis
In diesem Modul arbeiten Sie mit **Iteration Paths**. Diese sind etwas anderes als **Area Paths**:

- **Area Path** = welchem Team- oder Fachbereich ein Work Item gehoert
- **Iteration Path** = in welchem Sprint oder Zeitraum es bearbeitet werden soll

Auch in dieser deutschen Anleitung werden die tatsaechlichen **englischen UI-Begriffe** aus Azure DevOps Services verwendet.

## Feste Sprinttermine fuer dieses Training
Verwenden Sie in diesem Modul die folgenden Datumswerte:

1. **Sprint 1:** 20.04.2026 bis 01.05.2026
2. **Sprint 2:** 04.05.2026 bis 15.05.2026
3. **Sprint 3:** 18.05.2026 bis 29.05.2026

---

## Uebung 1 - Die Sprint-Struktur in der Projektkonfiguration anlegen

### Ziel
Sie legen drei Sprints unter Ihrem eigenen Teamnamen an.

### Schritte
1. Melden Sie sich in **tuvsud10** an und oeffnen Sie das Projekt Ihrer Zweiergruppe.
2. Klicken Sie links unten auf **Project settings**.
3. Oeffnen Sie - je nach sichtbarer Navigation - **Project configuration** oder den Bereich **Iterations**.
4. Legen Sie zunaechst einen uebergeordneten Eintrag mit Ihrem Teamnamen an, also mit Ihrem **Vornamen**, zum Beispiel:
   `Maria`
5. Legen Sie unter diesem Eintrag drei untergeordnete Sprints an:
   - `Sprint 1`
   - `Sprint 2`
   - `Sprint 3`
6. Tragen Sie fuer die drei Sprints die festgelegten Datumswerte ein:
   - **Sprint 1:** Start `20.04.2026`, End `01.05.2026`
   - **Sprint 2:** Start `04.05.2026`, End `15.05.2026`
   - **Sprint 3:** Start `18.05.2026`, End `29.05.2026`
7. Speichern Sie die Konfiguration.

### Erwartetes Ergebnis
Unter Ihrem Teamnamen existiert jetzt eine klare Sprintstruktur mit drei zeitlich definierten Sprints.

---

## Uebung 2 - Die Sprints Ihrem Team zuordnen

### Ziel
Sie machen die angelegten Sprints fuer Ihr Team nutzbar.

### Schritte
1. Wechseln Sie aus den **Project settings** wieder in den Bereich **Boards**.
2. Oeffnen Sie **Boards > Backlogs**.
3. Waehlen Sie ueber den **Team selector** Ihr eigenes Team mit Ihrem Vornamen aus.
4. Oeffnen Sie unter **Boards** den Bereich **Team configuration**.
5. Wechseln Sie dort in den Bereich **Iterations**.
6. Fuegen Sie nacheinander die drei eben erstellten Sprintpfade Ihres Teams hinzu, zum Beispiel:
   - `Maria\\Sprint 1`
   - `Maria\\Sprint 2`
   - `Maria\\Sprint 3`
7. Speichern Sie die Auswahl, falls Azure DevOps dies verlangt.
8. Kontrollieren Sie anschliessend, ob die Sprints Ihrem Team zugeordnet sind.

### Erwartetes Ergebnis
Ihr Team kann jetzt mit den eigenen Sprints in **Boards > Sprints** arbeiten.

---

## Uebung 3 - Work Items den Sprints zuordnen

### Ziel
Sie planen bestehende Arbeitselemente in konkrete Zeitraeume ein.

### Schritte
1. Wechseln Sie zu **Boards > Backlogs**.
2. Oeffnen Sie rechts das Panel **Planning**, falls es noch nicht sichtbar ist.
3. Suchen Sie Ihre eigenen Work Items mit Ihrem Vornamen oder mit Ihrem Nutzer-Praefix aus den frueheren Modulen.
4. Ziehen Sie passende Work Items ueber das **Planning**-Panel in einen der neu angelegten Sprints.
5. Ordnen Sie einige Elemente **Sprint 1**, einige **Sprint 2** und einige **Sprint 3** zu.
6. Pruefen Sie stichprobenartig bei einem Work Item, ob der **Iteration Path** nun passend gesetzt wurde.

### Erwartetes Ergebnis
Ihre Work Items sind jetzt auf mehrere Sprints verteilt und zeitlich eingeplant.

---

## Uebung 4 - Das Sprint Backlog oeffnen

### Ziel
Sie wechseln von der allgemeinen Backlog-Sicht in die sprintbezogene Planung.

### Schritte
1. Wechseln Sie zu **Boards > Sprints**.
2. Waehlen Sie ueber den **Team selector** Ihr eigenes Team aus.
3. Oeffnen Sie links oder oben **Sprint 1**.
4. Pruefen Sie, ob dort nun die Work Items angezeigt werden, die Sie diesem Sprint ueber **Iteration Path** zugeordnet haben.
5. Falls Elemente fehlen, kontrollieren Sie den **Iteration Path** der betreffenden Work Items erneut.

### Erwartetes Ergebnis
Sie sehen nun das Sprint Backlog Ihres Teams fuer den ausgewaehlten Sprint.

---

## Uebung 5 - Tasks zu Sprint-Items hinzufuegen

### Ziel
Sie zerlegen ein Sprint-Item in konkrete Arbeitsschritte.

### Schritte
1. Bleiben Sie in **Boards > Sprints** innerhalb von **Sprint 1**.
2. Suchen Sie ein Product Backlog Item, das Sie bereits in diesen Sprint eingeplant haben.
3. Klicken Sie unter diesem Element auf die Funktion zum Hinzufuegen einer neuen Aufgabe, zum Beispiel auf **+** oder **Add Task**.
4. Verwenden Sie dafuer den Work-Item-Typ **Task**.
5. Legen Sie mindestens zwei Tasks fuer ein Work Item an, zum Beispiel:
   - `Agenda entwerfen`
   - `Teilnehmende abstimmen`
6. Wiederholen Sie den Vorgang fuer mindestens ein weiteres Work Item im Sprint.

### Erwartetes Ergebnis
Mindestens zwei Sprint-Items wurden in kleinere, konkrete Tasks heruntergebrochen.

---

## Uebung 6 - Remaining Work setzen

### Ziel
Sie pflegen den geschaetzten Restaufwand fuer die Sprint-Tasks.

### Schritte
1. Oeffnen Sie einen der neu angelegten Tasks.
2. Suchen Sie das Feld **Remaining Work**.
3. Tragen Sie einen sinnvollen Aufwand ein, zum Beispiel:
   - `2`
   - `4`
   - `6`
4. Speichern Sie den Task.
5. Wiederholen Sie das fuer die weiteren Tasks Ihres Sprint Backlogs.
6. Wechseln Sie anschliessend bei Bedarf auf das **Taskboard**, um die Aufgaben und ihre Aufwaende im Sprintkontext zu sehen.

### Erwartetes Ergebnis
Die Tasks im Sprint enthalten jetzt konkrete Werte fuer **Remaining Work** und koennen besser geplant und nachverfolgt werden.

---

## Typische Stolpersteine

- Wenn das **Planning**-Panel nicht sichtbar ist, pruefen Sie, ob Sie wirklich in **Boards > Backlogs** arbeiten.
- Wenn ein Sprint im Sprint Backlog leer bleibt, ist meist der **Iteration Path** der Work Items noch nicht korrekt gesetzt.
- **Remaining Work** ist fuer die Sprintplanung besonders auf **Task**-Ebene sinnvoll und sollte dort gepflegt werden.

---

## Abschlusskontrolle
Am Ende dieses Moduls sollten Sie folgende Ergebnisse sehen:

1. drei Sprints unter Ihrem eigenen **Teamnamen**
2. die Sprints sind Ihrem Team zugeordnet
3. mehrere Work Items wurden ueber den **Iteration Path** auf die Sprints verteilt
4. im **Sprint Backlog** wurden neue **Tasks** angelegt
5. fuer die Tasks wurden Werte in **Remaining Work** gepflegt

Wenn diese Punkte sichtbar sind, haben Sie die Grundlagen von Sprintplanung, Sprint Backlog und Aufwandspflege in Azure DevOps erfolgreich abgeschlossen.
