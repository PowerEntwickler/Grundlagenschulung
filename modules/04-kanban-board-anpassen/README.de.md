# Modul 04 - Kanban-Board anpassen

## 🎯 Ziel dieses Moduls
In diesem Modul lernen die Teilnehmenden, wie sie ihr eigenes Kanban-Board in Azure DevOps Services sinnvoll konfigurieren. Nach dem Lab können sie:

1. das eigene Team-Board öffnen und anpassen
2. eigene **Columns** anlegen oder umbenennen
3. **Swimlanes** für unterschiedliche Prioritäten oder Arbeitsarten nutzen
4. ein **WIP Limit** setzen und interpretieren
5. eine **Definition of Done** für einzelne Spalten hinterlegen
6. eine Spalte in **Doing** und **Done** aufteilen
7. mit **Styles** und **Tag colors** die Sichtbarkeit verbessern

## 🧭 Szenario
Nach dem Import und der ersten Auswertung in Modul 03 liegt nun eine größere Menge an Arbeitselementen im Team vor. Damit diese im Tagesgeschäft besser gesteuert werden können, wird jetzt das Kanban-Board des eigenen Teams konfiguriert.

Ziel ist nicht nur eine schönere Ansicht, sondern ein Board, das den Arbeitsfluss im Projektmanagement wirklich unterstützt.

## ✅ Voraussetzungen
- [Modul 01](../01-grundlagen-arbeitselemente-erzeugen/README.de.md) bis [Modul 03](../03-import-massenbearbeitung-queries-charts/README.de.md) wurden abgeschlossen
- Sie haben ein eigenes Team mit Ihrem **Vornamen**
- In Ihrem Team-Backlog und auf Ihrem Team-Board sind bereits mehrere Product Backlog Items sichtbar
- Zugriff auf die Azure DevOps Services Organisation **tuvsud10**
- Die Menüführung ist grundsätzlich **Englisch**

## 🤝 Hinweis zur Zusammenarbeit
Obwohl sich zwei Teilnehmende ein Projekt teilen, arbeitet in diesem Modul jede Person auf dem **eigenen Team-Board**. Dadurch stören sich die Anpassungen möglichst wenig gegenseitig.

Auch in dieser deutschen Anleitung werden die tatsächlichen **englischen UI-Begriffe** aus Azure DevOps Services verwendet.

## 💡 Best Practices für dieses Modul

- Verwenden Sie nur so viele **Columns** wie wirklich nötig, damit das Board übersichtlich bleibt.
- Nutzen Sie möglichst nur **eine oder zwei Swimlanes** zusätzlich zur Standardsicht.
- Setzen Sie **WIP Limits** bewusst niedrig und realistisch.
- Formulieren Sie die **Definition of Done** kurz, konkret und prüfbar.
- Nutzen Sie **Styles** und **Tag colors** sparsam, damit wichtige Signale nicht untergehen.

---

## Übung 1 - Das eigene Team-Board öffnen

### 🎯 Ziel
Sie öffnen bewusst das Board Ihres eigenen Teams.

### 🔧 Schritte
1. Melden Sie sich in **tuvsud10** an.
2. Öffnen Sie das Projekt Ihrer Zweiergruppe.
3. Wechseln Sie zu **Boards > Boards**.
4. Wählen Sie über den **Team selector** oben links Ihr eigenes Team mit Ihrem Vornamen aus.
5. Prüfen Sie, ob nun die Work Items angezeigt werden, die Ihrem Team über den **Area Path** zugeordnet sind.
6. Sehen Sie sich kurz die vorhandenen Spalten des Boards an.

### 🟢 Erwartetes Ergebnis
Sie befinden sich nun auf dem Kanban-Board Ihres eigenen Teams und können dessen Konfiguration anpassen.

---

## Übung 2 - Eigene Columns anlegen oder anpassen

### 🎯 Ziel
Sie lernen, wie ein Board an den tatsächlichen Arbeitsablauf des Teams angepasst werden kann.

### 🔧 Schritte
1. Bleiben Sie auf **Boards > Boards**.
2. Öffnen Sie die **Board settings** oben rechts.
3. Wechseln Sie in den Bereich **Columns**.
4. Schauen Sie sich die vorhandenen Standardspalten an, zum Beispiel **New**, **Approved**, **Committed** oder ähnliche Namen.
5. Benennen Sie bei Bedarf eine Spalte so um, dass sie für den Trainingskontext besser verständlich ist.
6. Ergänzen Sie mindestens eine zusätzliche eigene Spalte, damit zum Beispiel Wartezeiten oder Abstimmungen sichtbar werden, zum Beispiel:
   - `In Review`
   - oder `Waiting`
7. Speichern Sie die Änderung.
8. Wechseln Sie zurück auf das Board und prüfen Sie, ob die neue oder angepasste Spaltenstruktur sichtbar ist.

### 🟢 Erwartetes Ergebnis
Das Board enthält jetzt Spalten, die besser zu Ihrem Arbeitsablauf passen.

---

## Übung 3 - Eine Column in Doing und Done aufteilen

### 🎯 Ziel
Sie lernen eine wichtige Möglichkeit kennen, den Arbeitsfortschritt innerhalb einer Spalte sichtbarer zu machen.

### 🔧 Schritte
1. Öffnen Sie erneut die **Board settings**.
2. Gehen Sie in den Bereich **Columns**.
3. Wählen Sie eine geeignete Arbeitsspalte aus, zum Beispiel **Committed** oder **In Review**.
4. Aktivieren Sie die Option, die Spalte in **Doing** und **Done** zu unterteilen.
5. Speichern Sie die Änderung.
6. Wechseln Sie zurück auf das Board.
7. Beobachten Sie, dass die betroffene Spalte nun in zwei Teilbereiche aufgeteilt ist.

### 🟢 Erwartetes Ergebnis
Sie sehen innerhalb einer Spalte genauer, was sich noch in Bearbeitung befindet und was in dieser Phase bereits abgeschlossen ist.

---

## Übung 4 - Swimlanes anlegen

### 🎯 Ziel
Sie strukturieren das Board zusätzlich nach Wichtigkeit oder Arbeitsart.

### 🔧 Schritte
1. Öffnen Sie die **Board settings**.
2. Wechseln Sie in den Bereich **Swimlanes**.
3. Schauen Sie sich die vorhandenen Swimlanes an.
4. Legen Sie mindestens eine neue Swimlane an, zum Beispiel:
   - `Dringend`
   - `Standard`
   - oder `Management Attention`
5. Speichern Sie die Änderung.
6. Wechseln Sie zurück auf das Board.
7. Verschieben Sie testweise ein oder zwei Work Items in eine andere Swimlane.

### 🟢 Erwartetes Ergebnis
Das Board ist nun zusätzlich in horizontale Bereiche gegliedert, um Arbeit unterschiedlicher Priorität sichtbarer zu machen.

---

## Übung 5 - Ein WIP Limit setzen

### 🎯 Ziel
Sie lernen, wie Work in Progress sichtbar begrenzt werden kann.

### 🔧 Schritte
1. Öffnen Sie wieder die **Board settings** und den Bereich **Columns**.
2. Wählen Sie eine Spalte aus, in der mehrere aktive Elemente liegen könnten, zum Beispiel **Committed** oder **In Review**.
3. Tragen Sie ein kleines **WIP Limit** ein, zum Beispiel `2` oder `3`.
4. Speichern Sie die Einstellung.
5. Wechseln Sie auf das Board und beobachten Sie, wie das WIP Limit in der Spalte dargestellt wird.
6. Besprechen Sie kurz für sich, was es bedeutet, wenn das Limit überschritten wird.

### 🟢 Erwartetes Ergebnis
Sie haben verstanden, dass ein WIP Limit dabei hilft, zu viele parallele Aufgaben sichtbar zu machen und zu vermeiden.

---

## Übung 6 - Eine Definition of Done hinterlegen

### 🎯 Ziel
Sie machen transparent, wann ein Arbeitsschritt wirklich als erledigt gelten soll.

### 🔧 Schritte
1. Bleiben Sie in den **Board settings** im Bereich **Columns**.
2. Wählen Sie eine passende Spalte aus, zum Beispiel eine spätere Arbeitsphase oder den **Done**-Teil einer geteilten Spalte.
3. Hinterlegen Sie eine kurze **Definition of Done**, zum Beispiel:
   - `Beschreibung gepflegt`
   - `Zuständigkeit geklärt`
   - `Ergebnis dokumentiert`
   - `Nächster Schritt bekannt`
4. Speichern Sie die Einstellung.
5. Prüfen Sie anschliessend, ob die Definition für das Team leicht auffindbar ist.

### 🟢 Erwartetes Ergebnis
Für mindestens eine Board-Spalte ist jetzt klar definiert, wann ein Element diese Phase wirklich abgeschlossen hat.

---

## Übung 7 - Styles und Tag colors nutzen

### 🎯 Ziel
Sie verbessern die visuelle Erkennbarkeit wichtiger Informationen auf dem Board.

In Azure DevOps Services gibt es dafür zwei unterschiedliche Funktionen, die beide unter **Board settings > Styles** konfiguriert werden:

- **Card styles** = Regeln, die Karten auf Basis von Feldwerten einfärben, zum Beispiel wenn ein bestimmter Tag oder State gesetzt ist.
- **Tag colors** = feste Farben pro Tag, die überall dort wirken, wo der Tag angezeigt wird.

### 🔧 Schritte

**Teil A - Card styles**

1. Öffnen Sie die **Board settings** oben rechts.
2. Wechseln Sie zu **Styles** und dort zum Tab **Card styles**.
3. Klicken Sie auf **Add styling rule**.
4. Vergeben Sie einen sprechenden Namen, zum Beispiel `Kommunikation hervorheben`.
5. Definieren Sie die Bedingung, zum Beispiel **Tags** `Contains` `kommunikation`.
6. Wählen Sie eine klar sichtbare Hintergrund- oder Schriftfarbe.
7. Speichern Sie die Regel.

**Teil B - Tag colors**

1. Wechseln Sie im Dialog **Styles** zum Tab **Tag colors**.
2. Aktivieren Sie die Anzeige von Tag-Farben, falls eine entsprechende Option sichtbar ist.
3. Klicken Sie auf **Add tag color** und wählen Sie einen Tag, zum Beispiel `reporting`, `risiko` oder `kommunikation`.
4. Wählen Sie für den Tag eine prägnante Farbe aus der Palette.
5. Fügen Sie für ein oder zwei weitere Tags ebenfalls Farben hinzu.
6. Speichern Sie die Einstellungen.

**Teil C - Wirkung prüfen**

1. Gehen Sie zurück auf das Board.
2. Kontrollieren Sie, ob:
   - Work Items mit dem definierten Tag wie gewünscht durch **Card styles** eingefärbt sind
   - die **Tag colors** auf den einzelnen Karten sichtbar sind

### 🟢 Erwartetes Ergebnis
Wichtige Kategorien oder Themen sind auf dem Board jetzt schneller erkennbar, sowohl über Kartenhintergründe (**Card styles**) als auch über farbige Tags (**Tag colors**).

---

## ⚠️ Typische Stolpersteine

- Wenn das Board anders aussieht als erwartet, kontrollieren Sie zuerst den **Team selector**.
- Wenn keine farbliche Hervorhebung sichtbar ist, prüfen Sie, ob die betroffenen Work Items das passende **Tag** wirklich enthalten.
- Zu viele neue Columns oder Swimlanes machen das Board schnell unübersichtlich. Weniger ist hier meist besser.

---

## 🏁 Abschlusskontrolle
Am Ende dieses Moduls sollten Sie folgende Ergebnisse sehen:

1. ein auf Ihr Team zugeschnittenes **Kanban-Board**
2. angepasste oder neue **Columns**
3. mindestens eine geteilte Spalte mit **Doing** und **Done**
4. mindestens eine zusätzliche **Swimlane**
5. ein sichtbares **WIP Limit**
6. eine hinterlegte **Definition of Done**
7. sichtbare visuelle Hervorhebungen über **Card styles** und **Tag colors**

Wenn diese Punkte sichtbar sind, haben Sie die wichtigsten Grundlagen zur praktischen Nutzung des Kanban-Boards in Azure DevOps erfolgreich abgeschlossen.
