# Modul 02 - Teams, Backlogs und Hierarchien

## Ziel dieses Moduls
In diesem Modul lernen die Teilnehmenden, wie sie in einem gemeinsam genutzten Azure-DevOps-Projekt mit eigenen Teams und Hierarchien arbeiten. Nach dem Lab können sie:

1. ein eigenes **Team** auf Basis ihres **Vornamens** anlegen
2. verstehen, dass Teams eigene **Backlogs** und **Boards** haben
3. den Zusammenhang zwischen **Team**, **Area Path** und sichtbaren Work Items nachvollziehen
4. bestehende Work Items dem richtigen Team zuordnen
5. mit **Backlog Levels** wie **Epic**, **Feature** und **Product Backlog Item** arbeiten
6. Beziehungen und Hierarchien zwischen Work Items herstellen

## Szenario
Im ersten Modul wurden bereits erste Product Backlog Items für ein gemeinsames Projekt angelegt. Jetzt wird das Projekt genauer strukturiert: Jede Person der Zweiergruppe richtet ihr eigenes Team ein und ordnet ihre bisherigen Aufgaben diesem Team zu.

Anschliessend werden größere Planungselemente wie **Epics** und **Features** angelegt, damit aus einzelnen Aufgaben eine nachvollziehbare Struktur entsteht.

## Voraussetzungen
- Modul 01 wurde abgeschlossen
- Zugriff auf die Azure DevOps Services Organisation **tuvsud10**
- Zugriff auf das Projekt Ihrer Zweiergruppe
- Die Menüführung ist grundsätzlich **Englisch**
- Es existieren bereits mehrere Product Backlog Items aus Modul 01

## Hinweis zur Zusammenarbeit
Jede Person legt ein eigenes Team mit dem **eigenen Vornamen** an, zum Beispiel:

`Maria`

Falls in einer Gruppe zufällig der gleiche Vorname vorkommt, ergänzen Sie zusätzlich den ersten Buchstaben des Nachnamens, zum Beispiel `MariaS`.

Auch in der deutschen Anleitung werden die tatsächlichen **englischen UI-Begriffe** aus Azure DevOps Services verwendet.

---

## Übung 1 - Vorhandene Work Items sichten

### Ziel
Sie verschaffen sich einen Überblick über die bereits vorhandenen Product Backlog Items aus Modul 01.

### Schritte
1. Melden Sie sich in der Organisation **tuvsud10** an.
2. Öffnen Sie das Projekt Ihrer Zweiergruppe.
3. Wechseln Sie zu **Boards > Work Items**.
4. Suchen Sie die Work Items, die Sie im ersten Modul mit Ihrem Vornamen angelegt haben, zum Beispiel:
   - `[IhrVorname] Kick-off-Termin vorbereiten`
   - `[IhrVorname] Stakeholderliste erstellen`
   - `[IhrVorname] Kommunikationsplan abstimmen`
5. Öffnen Sie eines dieser Work Items und schauen Sie sich das Feld **Area Path** an.
6. Schliessen Sie das Work Item wieder.

### Erwartetes Ergebnis
Sie sehen, dass die bisherigen Work Items zwar vorhanden sind, aber noch nicht unbedingt einer eigenen Teamstruktur zugeordnet wurden.

---

## Übung 2 - Ein eigenes Team anlegen

### Ziel
Sie erstellen ein eigenes Team innerhalb des gemeinsamen Projekts.

### Schritte
1. Klicken Sie links unten auf **Project settings**.
2. Öffnen Sie den Bereich **Teams**.
3. Klicken Sie auf **New team**.
4. Tragen Sie als Teamnamen Ihren **Vornamen** ein, zum Beispiel:
   `Maria`
5. Setzen Sie den Haken bei **Create an area path with the name of the team**.
6. Falls ein Beschreibungsfeld vorhanden ist, können Sie optional eintragen:
   `Persönliches Trainingsteam für Modul 02`
7. Bestätigen Sie mit **Create**.
8. Prüfen Sie anschliessend, ob Ihr neues Team in der Teamliste sichtbar ist.

### Erwartetes Ergebnis
Im Projekt existiert nun ein eigenes Team mit Ihrem Vornamen, und gleichzeitig wurde automatisch ein passender **Area Path** angelegt.

---

## Übung 3 - Den automatisch erzeugten Area Path prüfen und Ihrem Team zuordnen

### Ziel
Sie lernen, wie Teams über Area Paths mit ihren Backlogs und Boards verbunden sind.

### Schritte
1. Bleiben Sie in **Project settings**.
2. Öffnen Sie den Bereich **Teams** und wählen Sie Ihr neues Team aus.
3. Öffnen Sie dort die Team-Konfiguration für **Areas**.
4. Prüfen Sie, ob bereits ein Area Path mit Ihrem Vornamen vorhanden und ausgewählt ist.
5. Dieser Eintrag sollte automatisch existieren, weil Sie zuvor den Haken bei **Create an area path with the name of the team** gesetzt haben.
6. Falls der Bereich noch nicht als Standard für Ihr Team aktiv ist, wählen Sie ihn jetzt aus.
7. Speichern Sie die Einstellung, falls Azure DevOps dies verlangt.

### Erwartetes Ergebnis
Ihr Team ist jetzt mit dem automatisch erzeugten eigenen Area Path verknüpft. Damit kann das Team sein eigenes Backlog und Board erhalten.

---

## Übung 4 - Bestehende Work Items in Ihr Team verschieben

### Ziel
Sie ordnen Ihre bisherigen Aufgaben dem richtigen Team zu.

### Schritte
1. Wechseln Sie zurück zu **Boards > Work Items**.
2. Öffnen Sie das erste Work Item mit Ihrem Vornamen.
3. Suchen Sie das Feld **Area Path**.
4. Ändern Sie den Wert auf den Area Path Ihres Teams, also auf den Eintrag mit Ihrem Vornamen.
5. Speichern Sie das Work Item.
6. Wiederholen Sie diese Schritte für die weiteren Work Items aus Modul 01, die zu Ihnen gehören.
7. Achten Sie darauf, dass Sie nur Ihre eigenen Work Items anpassen und nicht die des anderen Teilnehmers.

### Erwartetes Ergebnis
Ihre bisherigen Product Backlog Items sind nun über den Area Path Ihrem persönlichen Team zugeordnet.

---

## Übung 5 - Eigenes Backlog und Board des Teams aufrufen

### Ziel
Sie erkennen, dass jedes Team in Azure DevOps eigene Sichten auf Arbeitselemente besitzt.

### Schritte
1. Öffnen Sie zuerst **Boards > Backlogs**.
2. Beobachten Sie kurz, welche Elemente in der aktuellen Ansicht angezeigt werden.
3. Wechseln Sie nun oben links in der Projektansicht zum **Team selector**.
4. Wählen Sie Ihr eigenes Team mit Ihrem Vornamen aus.
5. Prüfen Sie, wie sich die angezeigten Work Items im Backlog dadurch verändern.
6. Wechseln Sie anschliessend zu **Boards > Boards**.
7. Beobachten Sie, ob auf dem Board jetzt hauptsächlich die Work Items sichtbar sind, die Ihrem Team über den Area Path zugeordnet wurden.
8. Falls Ihre Elemente nicht sichtbar sind, kontrollieren Sie erneut den **Area Path** Ihrer Work Items und die Teamkonfiguration.

### Erwartetes Ergebnis
Sie haben verstanden, dass Teams eigene Backlogs und Boards besitzen und dass der Area Path steuert, welche Elemente dort erscheinen.

---

## Typische Stolpersteine

- Wenn im Backlog oder Board die falschen Elemente erscheinen, prüfen Sie zuerst den **Team selector** oben links.
- Wenn Ihre eigenen Work Items im Team nicht sichtbar sind, kontrollieren Sie den **Area Path** der Elemente.
- Wenn Sie sowohl Ihre als auch fremde Elemente sehen, wurde meist noch nicht sauber nach Team und Area Path getrennt.

---

## Übung 6 - Mit Backlog Levels arbeiten: Epic und Features anlegen

### Ziel
Sie lernen die verschiedenen Planungsebenen in Azure DevOps kennen.

### Schritte
1. Bleiben Sie in **Boards > Backlogs** innerhalb Ihres Teams.
2. Öffnen Sie den Auswahlbereich für die Backlog-Ebene.
3. Wechseln Sie zuerst auf die Ebene **Epics**.
4. Erzeugen Sie ein neues Epic mit einem Titel wie:
   `[IhrVorname] Projektvorbereitung Mobilität`
5. Wechseln Sie anschliessend auf die Ebene **Features**.
6. Legen Sie mindestens zwei Features an, zum Beispiel:
   - `[IhrVorname] Kick-off und Governance`
   - `[IhrVorname] Stakeholder und Kommunikation`
7. Speichern Sie die neuen Elemente.
8. Schauen Sie sich bewusst an, dass **Epics**, **Features** und **Product Backlog Items** unterschiedliche Backlog Levels darstellen.

### Erwartetes Ergebnis
Sie haben ein Epic und mehrere Features angelegt und dabei die Backlog Levels in Azure DevOps kennengelernt.

---

## Übung 7 - Work Items in eine Hierarchie bringen

### Ziel
Sie verknüpfen einzelne Aufgaben mit übergeordneten Planungselementen.

Sie lernen dabei **zwei mögliche Wege** kennen. Probieren Sie nach Möglichkeit beide Varianten aus.

### Möglichkeit A - über die Mapping-Ansicht
1. Bleiben Sie in **Boards > Backlogs** innerhalb Ihres Teams.
2. Wählen Sie die Backlog-Ebene, auf der Ihre **Product Backlog Items** sichtbar sind.
3. Öffnen Sie die **Mapping**-Ansicht oder den Bereich für **Parent/Child**-Zuordnungen, falls diese in Ihrem Projekt sichtbar ist.
4. Lassen Sie sich die übergeordneten Ebenen anzeigen, damit Sie Ihre **Features** und Ihr **Epic** sehen können.
5. Ordnen Sie zunächst die angelegten **Features** Ihrem **Epic** zu.
6. Ordnen Sie anschliessend Ihre bestehenden **Product Backlog Items** den passenden **Features** zu.
7. Achten Sie darauf, dass jedes untergeordnete Element dem fachlich passenden übergeordneten Element zugeordnet wird.
8. Speichern Sie die Änderungen, falls Azure DevOps dies verlangt.

### Möglichkeit B - über das Öffnen des Work Items und Hinzufügen eines Links
1. Öffnen Sie eines Ihrer **Features** oder **Product Backlog Items** direkt.
2. Wechseln Sie im Work Item in den Bereich **Links** oder **Related Work**.
3. Klicken Sie auf **Add link** oder eine vergleichbare Schaltfläche.
4. Wählen Sie die passende Beziehungsart:
   - **Parent**, wenn das aktuelle Element einem übergeordneten Element zugeordnet werden soll
   - **Child**, wenn Sie ein untergeordnetes Element aus Sicht des übergeordneten Work Items hinzufügen
5. Suchen Sie das zu verknüpfende Work Item, zum Beispiel Ihr Epic oder eines Ihrer Features.
6. Übernehmen Sie den Link und speichern Sie das Work Item.
7. Wiederholen Sie diesen Vorgang, bis Ihre Struktur vollständig ist.

### Kontrolle nach beiden Varianten
1. Wechseln Sie erneut zwischen den Backlog Levels **Epics**, **Features** und **Product Backlog Items**.
2. Prüfen Sie, ob die Beziehungen korrekt dargestellt werden.
3. Öffnen Sie bei Bedarf einzelne Work Items erneut und kontrollieren Sie dort den Bereich **Links**.

### Beispiel für eine sinnvolle Struktur
- Epic: `[IhrVorname] Projektvorbereitung Mobilität`
  - Feature: `[IhrVorname] Kick-off und Governance`
    - PBI: `[IhrVorname] Kick-off-Termin vorbereiten`
  - Feature: `[IhrVorname] Stakeholder und Kommunikation`
    - PBI: `[IhrVorname] Stakeholderliste erstellen`
    - PBI: `[IhrVorname] Kommunikationsplan abstimmen`

### Erwartetes Ergebnis
Sie sehen nun eine nachvollziehbare Hierarchie von Epic über Feature bis hin zu den einzelnen Product Backlog Items und kennen zwei Wege, diese Beziehungen herzustellen.

---

## Abschlusskontrolle
Am Ende dieses Moduls sollten Sie folgende Ergebnisse sehen:

1. ein eigenes **Team** mit Ihrem Vornamen
2. ein passender **Area Path** für dieses Team
3. Ihre bestehenden Work Items im **eigenen Team-Backlog**
4. mindestens ein **Epic**
5. mindestens zwei **Features**
6. eine sichtbare **Hierarchie** zwischen Epic, Features und Product Backlog Items

Wenn diese Punkte sichtbar sind, haben Sie die Grundlagen zu Teams, Area Paths, Backlog Levels und Beziehungen in Azure DevOps erfolgreich abgeschlossen.
