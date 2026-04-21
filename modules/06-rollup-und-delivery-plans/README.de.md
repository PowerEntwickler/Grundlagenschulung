# Modul 06 - Rollup Columns und Delivery Plans

## 🎯 Ziel dieses Moduls
In diesem Modul lernen die Teilnehmenden, wie sie in Azure DevOps Services Fortschritt und zeitliche Planung auf einer höheren Ebene sichtbar machen. Nach dem Lab können sie:

1. in der **Backlog**-Ansicht Hierarchien sichtbar machen
2. mit **Rollup Columns** Fortschritt und Summen darstellen
3. erkennen, wie sich **Epic**, **Feature** und **Product Backlog Item** gegenseitig ergänzen
4. einen **Delivery Plan** erstellen
5. zeitliche Abläufe und Teamplanung visuell nachvollziehen

## 🧭 Szenario
In den bisherigen Modulen wurden viele einzelne Arbeitselemente angelegt, strukturiert, importiert und in Sprints eingeplant. Nun geht es darum, diese Informationen für Projektmanagement und Steuerung übersichtlich sichtbar zu machen.

Dieses Modul zeigt deshalb zwei besonders hilfreiche Funktionen:

- **Rollup Columns** für Fortschritt und Hierarchie in der Backlog-Ansicht
- **Delivery Plans** für die zeitliche Visualisierung geplanter Arbeit

## ✅ Voraussetzungen
- [Modul 01](../01-grundlagen-arbeitselemente-erzeugen/README.de.md) bis [Modul 05](../05-sprints-planen-und-taskboard/README.de.md) wurden abgeschlossen
- Es existieren bereits **Epics**, **Features**, **Product Backlog Items**, **Sprints** und **Tasks**
- Zugriff auf die Azure DevOps Services Organisation **tuvsud10**
- Die Menüführung ist grundsätzlich **Englisch**

Auch in dieser deutschen Anleitung werden die tatsächlichen **englischen UI-Begriffe** aus Azure DevOps Services verwendet.

## 💡 Best Practices für dieses Modul

- **Rollup Columns** werden nur auf Portfolio- und Produkt-Backlogs angeboten, nicht im Sprint Backlog.
- **Progress by Work Items** zeigt Fortschritt anhand geschlossener Child Items, **Progress by Effort** nutzt Story Points oder Remaining Work - wählen Sie bewusst.
- **Delivery Plans** brauchen, dass jedes beteiligte Team eine eigene Sprint-Konfiguration hat. Ohne Iteration Paths bleibt der Plan leer.
- Rollup aggregiert ausschliesslich innerhalb desselben Projekts.
- Delivery-Plan-Einstellungen werden pro Benutzer gespeichert. Passen Sie sie vor einer Präsentation gezielt an.

---

## Übung 1 - Die Hierarchie im Backlog sichtbar machen

### 🎯 Ziel
Sie bereiten die Backlog-Ansicht so vor, dass Zusammenhänge zwischen den Ebenen besser erkennbar sind.

### 🔧 Schritte
1. Wechseln Sie zu **Boards > Backlogs**.
2. Wählen Sie über den **Team selector** Ihr eigenes Team aus.
3. Stellen Sie sicher, dass Sie in einer Ansicht arbeiten, in der **Epics**, **Features** und **Product Backlog Items** sinnvoll genutzt werden.
4. Öffnen Sie bei Bedarf **View options** oder die Anzeigeoptionen des Backlogs.
5. Aktivieren Sie dort die Darstellung, mit der Sie **Parents**, untergeordnete Ebenen oder die Hierarchie sichtbar machen können.
6. Klappen Sie einige Elemente auf, damit Sie die vorhandene Struktur besser sehen.

### 🟢 Erwartetes Ergebnis
Sie können in der Backlog-Ansicht erkennen, wie höhere und niedrigere Ebenen miteinander zusammenhängen.

---

## Übung 2 - Rollup Columns hinzufügen

### 🎯 Ziel
Sie erweitern die Backlog-Ansicht um automatische Fortschritts- und Summeninformationen.

### 🔧 Schritte
1. Bleiben Sie in **Boards > Backlogs**.
2. Öffnen Sie **Column options** oder die Funktion zum Anpassen der sichtbaren Spalten.
3. Wählen Sie dort **Add rollup column**.
4. Fügen Sie mindestens eine oder mehrere **Rollup Columns** hinzu.
5. Probieren Sie sinnvolle Werte aus, zum Beispiel:
   - Anzahl untergeordneter Elemente
   - Fortschritt abgeschlossener Arbeit
   - Summen zu Aufwand oder Restaufwand, falls in Ihrer Ansicht verfügbar
6. Ordnen Sie die neuen Spalten so an, dass sie gut lesbar sind.
7. Speichern oder übernehmen Sie die Änderungen.

### 🟢 Erwartetes Ergebnis
Die Backlog-Ansicht zeigt jetzt zusätzliche Kennzahlen, mit denen Sie Fortschritt und Umfang besser einschätzen können.

---

## Übung 3 - Den Fortschritt über mehrere Ebenen interpretieren

### 🎯 Ziel
Sie lernen, wie Rollup Columns für Projektsteuerung genutzt werden können.

### 🔧 Schritte
1. Schauen Sie sich ein vorhandenes **Epic** an.
2. Prüfen Sie, welche **Features** und **Product Backlog Items** darunter sichtbar sind.
3. Vergleichen Sie die Werte in den Rollup-Spalten.
4. Achten Sie darauf, ob bereits sichtbar wird:
   - wie viele Elemente untergeordnet sind
   - wie viele davon schon weiterbearbeitet wurden
   - wo sich noch viele offene Themen sammeln
5. Wiederholen Sie diese Betrachtung für mindestens ein weiteres Epic oder Feature.

### 🟢 Erwartetes Ergebnis
Sie verstehen, wie sich Fortschritt nicht nur auf Einzel-Work-Item-Ebene, sondern auch auf höheren Planungsebenen verfolgen lässt.

---

## Übung 4 - Einen Delivery Plan erstellen

### 🎯 Ziel
Sie erzeugen eine zeitliche Gesamtansicht über geplante Arbeit.

### 🔧 Schritte
1. Wechseln Sie zu **Boards > Delivery Plans**.
2. Klicken Sie auf **New plan** oder **Create plan**.
3. Geben Sie dem Plan einen aussagekräftigen Namen, zum Beispiel:
   `Delivery Plan [IhrVorname]`
4. Wählen Sie Ihr eigenes Team für den Plan aus.
5. Stellen Sie sicher, dass die Planung auf den zuvor angelegten **Sprints** bzw. **Iterations** basiert.
6. Wählen Sie bei Bedarf die relevanten Ebenen aus, zum Beispiel **Features** oder **Product Backlog Items**.
7. Speichern Sie den Plan.

### 🟢 Erwartetes Ergebnis
Es wurde ein eigener Delivery Plan für Ihr Team angelegt.

---

## Übung 5 - Den Delivery Plan konfigurieren und lesen

### 🎯 Ziel
Sie nutzen den Delivery Plan, um zeitliche Zusammenhänge besser zu verstehen.

### 🔧 Schritte
1. Öffnen Sie den gerade erstellten Delivery Plan.
2. Prüfen Sie, ob Arbeitselemente aus Ihren Sprints und Backlogs dort sichtbar sind.
3. Verändern Sie bei Bedarf den sichtbaren Zeitraum oder den Zoom der Ansicht.
4. Beobachten Sie:
   - in welchem Sprint welche Arbeit liegt
   - ob mehrere Themen gleichzeitig laufen
   - ob es zeitliche Ballungen gibt
5. Beachten Sie dabei, dass **Rollup Columns** im Backlog sichtbar sind, während der **Delivery Plan** vor allem die zeitliche Einordnung zeigt.
6. Falls möglich, blenden Sie weitere relevante Ebenen oder Teams ein und vergleichen Sie die Planung.

### 🟢 Erwartetes Ergebnis
Sie können nun zeitliche Abläufe im Projekt nicht nur als Liste, sondern als visuelle Planung lesen.

---

## ⚠️ Typische Stolpersteine

- Wenn **Rollup Columns** nicht angeboten werden, prüfen Sie, ob Sie wirklich in der **Backlog**-Ansicht und nicht auf einem Board oder in einer Query arbeiten.
- Wenn **Delivery Plans** nicht sichtbar ist, informieren Sie die Trainerperson. Je nach Organisation oder Berechtigung muss der Zugriff zuerst bereitstehen.
- Wenn im Delivery Plan keine Elemente erscheinen, kontrollieren Sie Teamauswahl, Sprintzuordnung und den verwendeten Zeitraum.

---

## 🏁 Abschlusskontrolle
Am Ende dieses Moduls sollten Sie folgende Ergebnisse sehen:

1. eine Backlog-Ansicht mit sichtbarer **Hierarchie**
2. mindestens eine aktiv genutzte **Rollup Column**
3. eine bessere Einschätzung des Fortschritts über **Epic**, **Feature** und **PBI**
4. einen angelegten **Delivery Plan**
5. eine visuelle Darstellung geplanter Arbeit über die Zeit

Wenn diese Punkte sichtbar sind, haben Sie die Grundlagen zu Rollup Columns und Delivery Plans in Azure DevOps erfolgreich abgeschlossen.
