# Modul 06 - Rollup Columns und Delivery Plans

## Ziel dieses Moduls
In diesem Modul lernen die Teilnehmenden, wie sie in Azure DevOps Services Fortschritt und zeitliche Planung auf einer hoeheren Ebene sichtbar machen. Nach dem Lab koennen sie:

1. in der **Backlog**-Ansicht Hierarchien sichtbar machen
2. mit **Rollup Columns** Fortschritt und Summen darstellen
3. erkennen, wie sich **Epic**, **Feature** und **Product Backlog Item** gegenseitig ergaenzen
4. einen **Delivery Plan** erstellen
5. zeitliche Ablaeufe und Teamplanung visuell nachvollziehen

## Szenario
In den bisherigen Modulen wurden viele einzelne Arbeitselemente angelegt, strukturiert, importiert und in Sprints eingeplant. Nun geht es darum, diese Informationen fuer Projektmanagement und Steuerung uebersichtlich sichtbar zu machen.

Dieses Modul zeigt deshalb zwei besonders hilfreiche Funktionen:

- **Rollup Columns** fuer Fortschritt und Hierarchie in der Backlog-Ansicht
- **Delivery Plans** fuer die zeitliche Visualisierung geplanter Arbeit

## Voraussetzungen
- Modul 01 bis Modul 05 wurden abgeschlossen
- Es existieren bereits **Epics**, **Features**, **Product Backlog Items**, **Sprints** und **Tasks**
- Zugriff auf die Azure DevOps Services Organisation **tuvsud10**
- Die Menuefuehrung ist grundsaetzlich **Englisch**

Auch in dieser deutschen Anleitung werden die tatsaechlichen **englischen UI-Begriffe** aus Azure DevOps Services verwendet.

---

## Uebung 1 - Die Hierarchie im Backlog sichtbar machen

### Ziel
Sie bereiten die Backlog-Ansicht so vor, dass Zusammenhaenge zwischen den Ebenen besser erkennbar sind.

### Schritte
1. Wechseln Sie zu **Boards > Backlogs**.
2. Waehlen Sie ueber den **Team selector** Ihr eigenes Team aus.
3. Stellen Sie sicher, dass Sie in einer Ansicht arbeiten, in der **Epics**, **Features** und **Product Backlog Items** sinnvoll genutzt werden.
4. Oeffnen Sie bei Bedarf **View options** oder die Anzeigeoptionen des Backlogs.
5. Aktivieren Sie dort die Darstellung, mit der Sie **Parents**, untergeordnete Ebenen oder die Hierarchie sichtbar machen koennen.
6. Klappen Sie einige Elemente auf, damit Sie die vorhandene Struktur besser sehen.

### Erwartetes Ergebnis
Sie koennen in der Backlog-Ansicht erkennen, wie hoehere und niedrigere Ebenen miteinander zusammenhaengen.

---

## Uebung 2 - Rollup Columns hinzufuegen

### Ziel
Sie erweitern die Backlog-Ansicht um automatische Fortschritts- und Summeninformationen.

### Schritte
1. Bleiben Sie in **Boards > Backlogs**.
2. Oeffnen Sie **Column options** oder die Funktion zum Anpassen der sichtbaren Spalten.
3. Waehlen Sie dort **Add rollup column**.
4. Fuegen Sie mindestens eine oder mehrere **Rollup Columns** hinzu.
5. Probieren Sie sinnvolle Werte aus, zum Beispiel:
   - Anzahl untergeordneter Elemente
   - Fortschritt abgeschlossener Arbeit
   - Summen zu Aufwand oder Restaufwand, falls in Ihrer Ansicht verfuegbar
6. Ordnen Sie die neuen Spalten so an, dass sie gut lesbar sind.
7. Speichern oder uebernehmen Sie die Aenderungen.

### Erwartetes Ergebnis
Die Backlog-Ansicht zeigt jetzt zusaetzliche Kennzahlen, mit denen Sie Fortschritt und Umfang besser einschaetzen koennen.

---

## Uebung 3 - Den Fortschritt ueber mehrere Ebenen interpretieren

### Ziel
Sie lernen, wie Rollup Columns fuer Projektsteuerung genutzt werden koennen.

### Schritte
1. Schauen Sie sich ein vorhandenes **Epic** an.
2. Pruefen Sie, welche **Features** und **Product Backlog Items** darunter sichtbar sind.
3. Vergleichen Sie die Werte in den Rollup-Spalten.
4. Achten Sie darauf, ob bereits sichtbar wird:
   - wie viele Elemente untergeordnet sind
   - wie viele davon schon weiterbearbeitet wurden
   - wo sich noch viele offene Themen sammeln
5. Wiederholen Sie diese Betrachtung fuer mindestens ein weiteres Epic oder Feature.

### Erwartetes Ergebnis
Sie verstehen, wie sich Fortschritt nicht nur auf Einzel-Work-Item-Ebene, sondern auch auf hoeheren Planungsebenen verfolgen laesst.

---

## Uebung 4 - Einen Delivery Plan erstellen

### Ziel
Sie erzeugen eine zeitliche Gesamtansicht ueber geplante Arbeit.

### Schritte
1. Wechseln Sie zu **Boards > Delivery Plans**.
2. Klicken Sie auf **New plan** oder **Create plan**.
3. Geben Sie dem Plan einen aussagekraeftigen Namen, zum Beispiel:
   `Delivery Plan [IhrVorname]`
4. Waehlen Sie Ihr eigenes Team fuer den Plan aus.
5. Stellen Sie sicher, dass die Planung auf den zuvor angelegten **Sprints** bzw. **Iterations** basiert.
6. Waehlen Sie bei Bedarf die relevanten Ebenen aus, zum Beispiel **Features** oder **Product Backlog Items**.
7. Speichern Sie den Plan.

### Erwartetes Ergebnis
Es wurde ein eigener Delivery Plan fuer Ihr Team angelegt.

---

## Uebung 5 - Den Delivery Plan konfigurieren und lesen

### Ziel
Sie nutzen den Delivery Plan, um zeitliche Zusammenhaenge besser zu verstehen.

### Schritte
1. Oeffnen Sie den gerade erstellten Delivery Plan.
2. Pruefen Sie, ob Arbeitselemente aus Ihren Sprints und Backlogs dort sichtbar sind.
3. Veraendern Sie bei Bedarf den sichtbaren Zeitraum oder den Zoom der Ansicht.
4. Beobachten Sie:
   - in welchem Sprint welche Arbeit liegt
   - ob mehrere Themen gleichzeitig laufen
   - ob es zeitliche Ballungen gibt
5. Beachten Sie dabei, dass **Rollup Columns** im Backlog sichtbar sind, waehrend der **Delivery Plan** vor allem die zeitliche Einordnung zeigt.
6. Falls moeglich, blenden Sie weitere relevante Ebenen oder Teams ein und vergleichen Sie die Planung.

### Erwartetes Ergebnis
Sie koennen nun zeitliche Ablaeufe im Projekt nicht nur als Liste, sondern als visuelle Planung lesen.

---

## Typische Stolpersteine

- Wenn **Rollup Columns** nicht angeboten werden, pruefen Sie, ob Sie wirklich in der **Backlog**-Ansicht und nicht auf einem Board oder in einer Query arbeiten.
- Wenn **Delivery Plans** nicht sichtbar ist, informieren Sie die Trainerperson. Je nach Organisation oder Berechtigung muss der Zugriff zuerst bereitstehen.
- Wenn im Delivery Plan keine Elemente erscheinen, kontrollieren Sie Teamauswahl, Sprintzuordnung und den verwendeten Zeitraum.

---

## Abschlusskontrolle
Am Ende dieses Moduls sollten Sie folgende Ergebnisse sehen:

1. eine Backlog-Ansicht mit sichtbarer **Hierarchie**
2. mindestens eine aktiv genutzte **Rollup Column**
3. eine bessere Einschaetzung des Fortschritts ueber **Epic**, **Feature** und **PBI**
4. einen angelegten **Delivery Plan**
5. eine visuelle Darstellung geplanter Arbeit ueber die Zeit

Wenn diese Punkte sichtbar sind, haben Sie die Grundlagen zu Rollup Columns und Delivery Plans in Azure DevOps erfolgreich abgeschlossen.
