# Modul 04 - Kanban-Board anpassen

## Ziel dieses Moduls
In diesem Modul lernen die Teilnehmenden, wie sie ihr eigenes Kanban-Board in Azure DevOps Services sinnvoll konfigurieren. Nach dem Lab koennen sie:

1. das eigene Team-Board oeffnen und anpassen
2. eigene **Columns** anlegen oder umbenennen
3. **Swimlanes** fuer unterschiedliche Prioritaeten oder Arbeitsarten nutzen
4. ein **WIP Limit** setzen und interpretieren
5. eine **Definition of Done** fuer einzelne Spalten hinterlegen
6. eine Spalte in **Doing** und **Done** aufteilen
7. mit **Styles** und **Tag colors** die Sichtbarkeit verbessern

## Szenario
Nach dem Import und der ersten Auswertung in Modul 03 liegt nun eine groessere Menge an Arbeitselementen im Team vor. Damit diese im Tagesgeschaeft besser gesteuert werden koennen, wird jetzt das Kanban-Board des eigenen Teams konfiguriert.

Ziel ist nicht nur eine schoenere Ansicht, sondern ein Board, das den Arbeitsfluss im Projektmanagement wirklich unterstuetzt.

## Voraussetzungen
- Modul 01 bis Modul 03 wurden abgeschlossen
- Sie haben ein eigenes Team mit Ihrem **Vornamen**
- In Ihrem Team-Backlog und auf Ihrem Team-Board sind bereits mehrere Product Backlog Items sichtbar
- Zugriff auf die Azure DevOps Services Organisation **tuvsud10**
- Die Menuefuehrung ist grundsaetzlich **Englisch**

## Hinweis zur Zusammenarbeit
Obwohl sich zwei Teilnehmende ein Projekt teilen, arbeitet in diesem Modul jede Person auf dem **eigenen Team-Board**. Dadurch stoeren sich die Anpassungen moeglichst wenig gegenseitig.

Auch in dieser deutschen Anleitung werden die tatsaechlichen **englischen UI-Begriffe** aus Azure DevOps Services verwendet.

## Kompakte Best Practices fuer dieses Modul

- Verwenden Sie nur so viele **Columns** wie wirklich noetig, damit das Board uebersichtlich bleibt.
- Nutzen Sie moeglichst nur **eine oder zwei Swimlanes** zusaetzlich zur Standardsicht.
- Setzen Sie **WIP Limits** bewusst niedrig und realistisch.
- Formulieren Sie die **Definition of Done** kurz, konkret und pruefbar.
- Nutzen Sie **Styles** und **Tag colors** sparsam, damit wichtige Signale nicht untergehen.

---

## Uebung 1 - Das eigene Team-Board oeffnen

### Ziel
Sie oeffnen bewusst das Board Ihres eigenen Teams.

### Schritte
1. Melden Sie sich in **tuvsud10** an.
2. Oeffnen Sie das Projekt Ihrer Zweiergruppe.
3. Wechseln Sie zu **Boards > Boards**.
4. Waehlen Sie ueber den **Team selector** oben links Ihr eigenes Team mit Ihrem Vornamen aus.
5. Pruefen Sie, ob nun die Work Items angezeigt werden, die Ihrem Team ueber den **Area Path** zugeordnet sind.
6. Sehen Sie sich kurz die vorhandenen Spalten des Boards an.

### Erwartetes Ergebnis
Sie befinden sich nun auf dem Kanban-Board Ihres eigenen Teams und koennen dessen Konfiguration anpassen.

---

## Uebung 2 - Eigene Columns anlegen oder anpassen

### Ziel
Sie lernen, wie ein Board an den tatsaechlichen Arbeitsablauf des Teams angepasst werden kann.

### Schritte
1. Bleiben Sie auf **Boards > Boards**.
2. Oeffnen Sie die **Board settings** oben rechts.
3. Wechseln Sie in den Bereich **Columns**.
4. Schauen Sie sich die vorhandenen Standardspalten an, zum Beispiel **New**, **Approved**, **Committed** oder aehnliche Namen.
5. Benennen Sie bei Bedarf eine Spalte so um, dass sie fuer den Trainingskontext besser verstaendlich ist.
6. Ergaenzen Sie mindestens eine zusaetzliche eigene Spalte, zum Beispiel:
   - `In Review`
   - oder `Waiting`
7. Speichern Sie die Aenderung.
8. Wechseln Sie zurueck auf das Board und pruefen Sie, ob die neue oder angepasste Spaltenstruktur sichtbar ist.

### Erwartetes Ergebnis
Das Board enthaelt jetzt Spalten, die besser zu Ihrem Arbeitsablauf passen.

---

## Uebung 3 - Eine Column in Doing und Done aufteilen

### Ziel
Sie lernen eine wichtige Moeglichkeit kennen, den Arbeitsfortschritt innerhalb einer Spalte sichtbarer zu machen.

### Schritte
1. Oeffnen Sie erneut die **Board settings**.
2. Gehen Sie in den Bereich **Columns**.
3. Waehlen Sie eine geeignete Arbeitsspalte aus, zum Beispiel **Committed** oder **In Review**.
4. Aktivieren Sie die Option, die Spalte in **Doing** und **Done** zu unterteilen.
5. Speichern Sie die Aenderung.
6. Wechseln Sie zurueck auf das Board.
7. Beobachten Sie, dass die betroffene Spalte nun in zwei Teilbereiche aufgeteilt ist.

### Erwartetes Ergebnis
Sie sehen innerhalb einer Spalte genauer, was sich noch in Bearbeitung befindet und was in dieser Phase bereits abgeschlossen ist.

---

## Uebung 4 - Swimlanes anlegen

### Ziel
Sie strukturieren das Board zusaetzlich nach Wichtigkeit oder Arbeitsart.

### Schritte
1. Oeffnen Sie die **Board settings**.
2. Wechseln Sie in den Bereich **Swimlanes**.
3. Schauen Sie sich die vorhandenen Swimlanes an.
4. Legen Sie mindestens eine neue Swimlane an, zum Beispiel:
   - `Dringend`
   - `Standard`
   - oder `Management Attention`
5. Speichern Sie die Aenderung.
6. Wechseln Sie zurueck auf das Board.
7. Verschieben Sie testweise ein oder zwei Work Items in eine andere Swimlane.

### Erwartetes Ergebnis
Das Board ist nun zusaetzlich in horizontale Bereiche gegliedert, um Arbeit unterschiedlicher Prioritaet sichtbarer zu machen.

---

## Uebung 5 - Ein WIP Limit setzen

### Ziel
Sie lernen, wie Work in Progress sichtbar begrenzt werden kann.

### Schritte
1. Oeffnen Sie wieder die **Board settings** und den Bereich **Columns**.
2. Waehlen Sie eine Spalte aus, in der mehrere aktive Elemente liegen koennten, zum Beispiel **Committed** oder **In Review**.
3. Tragen Sie ein kleines **WIP Limit** ein, zum Beispiel `2` oder `3`.
4. Speichern Sie die Einstellung.
5. Wechseln Sie auf das Board und beobachten Sie, wie das WIP Limit in der Spalte dargestellt wird.
6. Besprechen Sie kurz fuer sich, was es bedeutet, wenn das Limit ueberschritten wird.

### Erwartetes Ergebnis
Sie haben verstanden, dass ein WIP Limit dabei hilft, zu viele parallele Aufgaben sichtbar zu machen und zu vermeiden.

---

## Uebung 6 - Eine Definition of Done hinterlegen

### Ziel
Sie machen transparent, wann ein Arbeitsschritt wirklich als erledigt gelten soll.

### Schritte
1. Bleiben Sie in den **Board settings** im Bereich **Columns**.
2. Waehlen Sie eine passende Spalte aus, zum Beispiel eine spaetere Arbeitsphase oder den **Done**-Teil einer geteilten Spalte.
3. Hinterlegen Sie eine kurze **Definition of Done**, zum Beispiel:
   - `Beschreibung gepflegt`
   - `Zustaendigkeit geklaert`
   - `Ergebnis dokumentiert`
   - `Naechster Schritt bekannt`
4. Speichern Sie die Einstellung.
5. Pruefen Sie anschliessend, ob die Definition fuer das Team leicht auffindbar ist.

### Erwartetes Ergebnis
Fuer mindestens eine Board-Spalte ist jetzt klar definiert, wann ein Element diese Phase wirklich abgeschlossen hat.

---

## Uebung 7 - Styles und Tag colors nutzen

### Ziel
Sie verbessern die visuelle Erkennbarkeit wichtiger Informationen auf dem Board.

### Schritte
1. Oeffnen Sie die **Board settings**.
2. Wechseln Sie in den Bereich **Styles**.
3. Legen Sie mindestens eine Regel an, die Work Items mit einem bestimmten **Tag** visuell hervorhebt, zum Beispiel:
   - `kommunikation`
   - `reporting`
   - `risiko`
4. Waehlen Sie eine gut sichtbare Hintergrund- oder Textfarbe fuer diese Regel.
5. Speichern Sie die Einstellung und gehen Sie zurueck auf das Board.
6. Pruefen Sie, ob Work Items mit dem entsprechenden Tag nun farblich hervorgehoben werden.
7. Falls in Ihrem Projekt **Tag colors** separat konfigurierbar sind, vergeben Sie zusaetzlich unterschiedliche Farben fuer wichtige Tags.

### Erwartetes Ergebnis
Wichtige Kategorien oder Themen sind auf dem Board jetzt schneller erkennbar.

---

## Typische Stolpersteine

- Wenn das Board anders aussieht als erwartet, kontrollieren Sie zuerst den **Team selector**.
- Wenn keine farbliche Hervorhebung sichtbar ist, pruefen Sie, ob die betroffenen Work Items das passende **Tag** wirklich enthalten.
- Zu viele neue Columns oder Swimlanes machen das Board schnell unuebersichtlich. Weniger ist hier meist besser.

---

## Abschlusskontrolle
Am Ende dieses Moduls sollten Sie folgende Ergebnisse sehen:

1. ein auf Ihr Team zugeschnittenes **Kanban-Board**
2. angepasste oder neue **Columns**
3. mindestens eine geteilte Spalte mit **Doing** und **Done**
4. mindestens eine zusaetzliche **Swimlane**
5. ein sichtbares **WIP Limit**
6. eine hinterlegte **Definition of Done**
7. sichtbare visuelle Hervorhebungen ueber **Styles** oder **Tag colors**

Wenn diese Punkte sichtbar sind, haben Sie die wichtigsten Grundlagen zur praktischen Nutzung des Kanban-Boards in Azure DevOps erfolgreich abgeschlossen.
