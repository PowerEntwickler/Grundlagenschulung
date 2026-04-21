# Modul 02 - Teams, Backlogs und Hierarchien

## Ziel dieses Moduls
In diesem Modul lernen die Teilnehmenden, wie sie in einem gemeinsam genutzten Azure-DevOps-Projekt mit eigenen Teams und Hierarchien arbeiten. Nach dem Lab koennen sie:

1. ein eigenes **Team** auf Basis ihres **Vornamens** anlegen
2. verstehen, dass Teams eigene **Backlogs** und **Boards** haben
3. den Zusammenhang zwischen **Team**, **Area Path** und sichtbaren Work Items nachvollziehen
4. bestehende Work Items dem richtigen Team zuordnen
5. mit **Backlog Levels** wie **Epic**, **Feature** und **Product Backlog Item** arbeiten
6. Beziehungen und Hierarchien zwischen Work Items herstellen

## Szenario
Im ersten Modul wurden bereits erste Product Backlog Items fuer ein gemeinsames Projekt angelegt. Jetzt wird das Projekt genauer strukturiert: Jede Person der Zweiergruppe richtet ihr eigenes Team ein und ordnet ihre bisherigen Aufgaben diesem Team zu.

Anschliessend werden groessere Planungselemente wie **Epics** und **Features** angelegt, damit aus einzelnen Aufgaben eine nachvollziehbare Struktur entsteht.

## Voraussetzungen
- Modul 01 wurde abgeschlossen
- Zugriff auf die Azure DevOps Services Organisation **tuvsud10**
- Zugriff auf das Projekt Ihrer Zweiergruppe
- Die Menuefuehrung ist grundsaetzlich **Englisch**
- Es existieren bereits mehrere Product Backlog Items aus Modul 01

## Hinweis zur Zusammenarbeit
Jede Person legt ein eigenes Team mit dem **eigenen Vornamen** an, zum Beispiel:

`Maria`

Falls in einer Gruppe zufaellig der gleiche Vorname vorkommt, ergaenzen Sie zusaetzlich den ersten Buchstaben des Nachnamens, zum Beispiel `MariaS`.

Auch in der deutschen Anleitung werden die tatsaechlichen **englischen UI-Begriffe** aus Azure DevOps Services verwendet.

---

## Uebung 1 - Vorhandene Work Items sichten

### Ziel
Sie verschaffen sich einen Ueberblick ueber die bereits vorhandenen Product Backlog Items aus Modul 01.

### Schritte
1. Melden Sie sich in der Organisation **tuvsud10** an.
2. Oeffnen Sie das Projekt Ihrer Zweiergruppe.
3. Wechseln Sie zu **Boards > Work Items**.
4. Suchen Sie die Work Items, die Sie im ersten Modul mit Ihrem Vornamen angelegt haben, zum Beispiel:
   - `[IhrVorname] Kick-off-Termin vorbereiten`
   - `[IhrVorname] Stakeholderliste erstellen`
   - `[IhrVorname] Kommunikationsplan abstimmen`
5. Oeffnen Sie eines dieser Work Items und schauen Sie sich das Feld **Area Path** an.
6. Schliessen Sie das Work Item wieder.

### Erwartetes Ergebnis
Sie sehen, dass die bisherigen Work Items zwar vorhanden sind, aber noch nicht unbedingt einer eigenen Teamstruktur zugeordnet wurden.

---

## Uebung 2 - Ein eigenes Team anlegen

### Ziel
Sie erstellen ein eigenes Team innerhalb des gemeinsamen Projekts.

### Schritte
1. Klicken Sie links unten auf **Project settings**.
2. Oeffnen Sie den Bereich **Teams**.
3. Klicken Sie auf **New team**.
4. Tragen Sie als Teamnamen Ihren **Vornamen** ein, zum Beispiel:
   `Maria`
5. Setzen Sie den Haken bei **Create an area path with the name of the team**.
6. Falls ein Beschreibungsfeld vorhanden ist, koennen Sie optional eintragen:
   `Persoenliches Trainingsteam fuer Modul 02`
7. Bestaetigen Sie mit **Create**.
8. Pruefen Sie anschliessend, ob Ihr neues Team in der Teamliste sichtbar ist.

### Erwartetes Ergebnis
Im Projekt existiert nun ein eigenes Team mit Ihrem Vornamen, und gleichzeitig wurde automatisch ein passender **Area Path** angelegt.

---

## Uebung 3 - Den automatisch erzeugten Area Path pruefen und Ihrem Team zuordnen

### Ziel
Sie lernen, wie Teams ueber Area Paths mit ihren Backlogs und Boards verbunden sind.

### Schritte
1. Bleiben Sie in **Project settings**.
2. Oeffnen Sie den Bereich **Teams** und waehlen Sie Ihr neues Team aus.
3. Oeffnen Sie dort die Team-Konfiguration fuer **Areas**.
4. Pruefen Sie, ob bereits ein Area Path mit Ihrem Vornamen vorhanden und ausgewaehlt ist.
5. Dieser Eintrag sollte automatisch existieren, weil Sie zuvor den Haken bei **Create an area path with the name of the team** gesetzt haben.
6. Falls der Bereich noch nicht als Standard fuer Ihr Team aktiv ist, waehlen Sie ihn jetzt aus.
7. Speichern Sie die Einstellung, falls Azure DevOps dies verlangt.

### Erwartetes Ergebnis
Ihr Team ist jetzt mit dem automatisch erzeugten eigenen Area Path verknuepft. Damit kann das Team sein eigenes Backlog und Board erhalten.

---

## Uebung 4 - Bestehende Work Items in Ihr Team verschieben

### Ziel
Sie ordnen Ihre bisherigen Aufgaben dem richtigen Team zu.

### Schritte
1. Wechseln Sie zurueck zu **Boards > Work Items**.
2. Oeffnen Sie das erste Work Item mit Ihrem Vornamen.
3. Suchen Sie das Feld **Area Path**.
4. Aendern Sie den Wert auf den Area Path Ihres Teams, also auf den Eintrag mit Ihrem Vornamen.
5. Speichern Sie das Work Item.
6. Wiederholen Sie diese Schritte fuer die weiteren Work Items aus Modul 01, die zu Ihnen gehoeren.
7. Achten Sie darauf, dass Sie nur Ihre eigenen Work Items anpassen und nicht die des anderen Teilnehmers.

### Erwartetes Ergebnis
Ihre bisherigen Product Backlog Items sind nun ueber den Area Path Ihrem persoenlichen Team zugeordnet.

---

## Uebung 5 - Eigenes Backlog und Board des Teams aufrufen

### Ziel
Sie erkennen, dass jedes Team in Azure DevOps eigene Sichten auf Arbeitselemente besitzt.

### Schritte
1. Oeffnen Sie zuerst **Boards > Backlogs**.
2. Beobachten Sie kurz, welche Elemente in der aktuellen Ansicht angezeigt werden.
3. Wechseln Sie nun oben links in der Projektansicht zum **Team selector**.
4. Waehlen Sie Ihr eigenes Team mit Ihrem Vornamen aus.
5. Pruefen Sie, wie sich die angezeigten Work Items im Backlog dadurch veraendern.
6. Wechseln Sie anschliessend zu **Boards > Boards**.
7. Beobachten Sie, ob auf dem Board jetzt hauptsaechlich die Work Items sichtbar sind, die Ihrem Team ueber den Area Path zugeordnet wurden.
8. Falls Ihre Elemente nicht sichtbar sind, kontrollieren Sie erneut den **Area Path** Ihrer Work Items und die Teamkonfiguration.

### Erwartetes Ergebnis
Sie haben verstanden, dass Teams eigene Backlogs und Boards besitzen und dass der Area Path steuert, welche Elemente dort erscheinen.

---

## Typische Stolpersteine

- Wenn im Backlog oder Board die falschen Elemente erscheinen, pruefen Sie zuerst den **Team selector** oben links.
- Wenn Ihre eigenen Work Items im Team nicht sichtbar sind, kontrollieren Sie den **Area Path** der Elemente.
- Wenn Sie sowohl Ihre als auch fremde Elemente sehen, wurde meist noch nicht sauber nach Team und Area Path getrennt.

---

## Uebung 6 - Mit Backlog Levels arbeiten: Epic und Features anlegen

### Ziel
Sie lernen die verschiedenen Planungsebenen in Azure DevOps kennen.

### Schritte
1. Bleiben Sie in **Boards > Backlogs** innerhalb Ihres Teams.
2. Oeffnen Sie den Auswahlbereich fuer die Backlog-Ebene.
3. Wechseln Sie zuerst auf die Ebene **Epics**.
4. Erzeugen Sie ein neues Epic mit einem Titel wie:
   `[IhrVorname] Projektvorbereitung Mobilitaet`
5. Wechseln Sie anschliessend auf die Ebene **Features**.
6. Legen Sie mindestens zwei Features an, zum Beispiel:
   - `[IhrVorname] Kick-off und Governance`
   - `[IhrVorname] Stakeholder und Kommunikation`
7. Speichern Sie die neuen Elemente.
8. Schauen Sie sich bewusst an, dass **Epics**, **Features** und **Product Backlog Items** unterschiedliche Backlog Levels darstellen.

### Erwartetes Ergebnis
Sie haben ein Epic und mehrere Features angelegt und dabei die Backlog Levels in Azure DevOps kennengelernt.

---

## Uebung 7 - Work Items in eine Hierarchie bringen

### Ziel
Sie verknuepfen einzelne Aufgaben mit uebergeordneten Planungselementen.

Sie lernen dabei **zwei moegliche Wege** kennen. Probieren Sie nach Moeglichkeit beide Varianten aus.

### Moeglichkeit A - ueber die Mapping-Ansicht
1. Bleiben Sie in **Boards > Backlogs** innerhalb Ihres Teams.
2. Waehlen Sie die Backlog-Ebene, auf der Ihre **Product Backlog Items** sichtbar sind.
3. Oeffnen Sie die **Mapping**-Ansicht oder den Bereich fuer **Parent/Child**-Zuordnungen, falls diese in Ihrem Projekt sichtbar ist.
4. Lassen Sie sich die uebergeordneten Ebenen anzeigen, damit Sie Ihre **Features** und Ihr **Epic** sehen koennen.
5. Ordnen Sie zunaechst die angelegten **Features** Ihrem **Epic** zu.
6. Ordnen Sie anschliessend Ihre bestehenden **Product Backlog Items** den passenden **Features** zu.
7. Achten Sie darauf, dass jedes untergeordnete Element dem fachlich passenden uebergeordneten Element zugeordnet wird.
8. Speichern Sie die Aenderungen, falls Azure DevOps dies verlangt.

### Moeglichkeit B - ueber das Oeffnen des Work Items und Hinzufuegen eines Links
1. Oeffnen Sie eines Ihrer **Features** oder **Product Backlog Items** direkt.
2. Wechseln Sie im Work Item in den Bereich **Links** oder **Related Work**.
3. Klicken Sie auf **Add link** oder eine vergleichbare Schaltflaeche.
4. Waehlen Sie die passende Beziehungsart:
   - **Parent**, wenn das aktuelle Element einem uebergeordneten Element zugeordnet werden soll
   - **Child**, wenn Sie ein untergeordnetes Element aus Sicht des uebergeordneten Work Items hinzufuegen
5. Suchen Sie das zu verknuepfende Work Item, zum Beispiel Ihr Epic oder eines Ihrer Features.
6. Uebernehmen Sie den Link und speichern Sie das Work Item.
7. Wiederholen Sie diesen Vorgang, bis Ihre Struktur vollstaendig ist.

### Kontrolle nach beiden Varianten
1. Wechseln Sie erneut zwischen den Backlog Levels **Epics**, **Features** und **Product Backlog Items**.
2. Pruefen Sie, ob die Beziehungen korrekt dargestellt werden.
3. Oeffnen Sie bei Bedarf einzelne Work Items erneut und kontrollieren Sie dort den Bereich **Links**.

### Beispiel fuer eine sinnvolle Struktur
- Epic: `[IhrVorname] Projektvorbereitung Mobilitaet`
  - Feature: `[IhrVorname] Kick-off und Governance`
    - PBI: `[IhrVorname] Kick-off-Termin vorbereiten`
  - Feature: `[IhrVorname] Stakeholder und Kommunikation`
    - PBI: `[IhrVorname] Stakeholderliste erstellen`
    - PBI: `[IhrVorname] Kommunikationsplan abstimmen`

### Erwartetes Ergebnis
Sie sehen nun eine nachvollziehbare Hierarchie von Epic ueber Feature bis hin zu den einzelnen Product Backlog Items und kennen zwei Wege, diese Beziehungen herzustellen.

---

## Abschlusskontrolle
Am Ende dieses Moduls sollten Sie folgende Ergebnisse sehen:

1. ein eigenes **Team** mit Ihrem Vornamen
2. ein passender **Area Path** fuer dieses Team
3. Ihre bestehenden Work Items im **eigenen Team-Backlog**
4. mindestens ein **Epic**
5. mindestens zwei **Features**
6. eine sichtbare **Hierarchie** zwischen Epic, Features und Product Backlog Items

Wenn diese Punkte sichtbar sind, haben Sie die Grundlagen zu Teams, Area Paths, Backlog Levels und Beziehungen in Azure DevOps erfolgreich abgeschlossen.
