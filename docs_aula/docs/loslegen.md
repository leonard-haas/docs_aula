# 🚀 Loslegen mit aula

<!-- Wird vermutlich noch überarbeitet und verändert. -->

> **Wichtig: Diese Anleitung richtet sich an Schulen, die die Software auf den aula-Servern verwenden.**

**Kurz erklärt** Hier erfährst du, wie du die Schul-Instanz aufsetzt und welche ersten Schritte du durchführen musst.

### Die ersten beiden Nutzer\*innen

Jede Instanz die von aula bereitgestellt wird, generiert zunächst zwei Nutzer\*innen den Tech-Admin und den Admin (mehr über die Rollen erfährst du [hier](benutzerverwaltung.md)). Deshalb benötigt aula zu Anfang zwei Personen, die diese Rollen übernehmen und ihre zugehörigen Email-Adressen, um die Instanz freigeben zu können.

### Die E-Mail mit alle notwendigen Informationen:

Die beiden Nutzer\*innen erhalten im Anschluss eine Email in der sich die wichtigsten Informationen finden:

- Schulcode: Jede Instanz hat ihren eigenen Code
- Benutzername
- Link für das Erstellen eines neuen Passworts (magic link)

<img src="/screenshots/welcome_mail.png" alt="Erste Mail Admin" style="height: 300px;">

## Die ersten Schritte:

### Nutzer ohne E-Mail Addresse

1. Gehe auf [neu.aula.de](https://neu.aula.de)
2. Dort wirst du zuerst nach deinem Schulcode gefragt.
3. Nachdem du den Code eingegeben hast, wird er automatisch in deinem Browser gespeichert.
4. Gib dein Benutzername und das temporäres Passwort ein.
5. Nun kannst du ein neues Passwort festlegen und bestätigen.
6. Zum Schluss kannst du dich mit dem neuen Passwort einloggen.

### Nutzer mit E-Mail Addresse

1. Klicke auf den Passwort-Link den du bekommen hast.
2. Nun kannst du ein neues Passwort festlegen und bestätigen.
3. Jetzt kannst du dich mit dem neuen Passwort einloggen.

Du benötigst den Schulcode wenn du dich auf einen anderen Gerät einloggst.

Geschafft!

## Die Grundlage schaffen: Räume anlegen

Um die Struktur der Schule in aula abbilden zu können, müssen von den Administrator\*innen Räume angelegt werden.

### Einen Raum erstellen

1. Gehe im Menü auf "Räume".
2. Klicke auf Raum hinzufügen.
3. Richte den Raum ein:
   3.1 Gebe einen Namen für den Raum ein.
   3.2 Optional: Füge eine Beschreibung zum Raum hinzu.
   3.3 Optional: Wähle ein Beispiel Bild aus.
   3.4 Optional: Füge einzelne Benutzer\*innen hinzu. (Beachte das du mit dem CSV Import auch mehrere Benutzer\*innen hinzufügen kannst).
4. Bestätige deine Eingaben durch das klicken auf BESTÄTIGEN

<img src="/screenshots/raum_hinzufügen.png" alt="Raum erstellen" style="height: 300px;">

## Mehrere Benutzer\*innen mit CSV Tabellen anlegen

> 💡 Wenn du zum ersten Mal alle Benutzer\*innen für eure Schule in aula anlegen möchtest, ist es am einfachsten, die CSV-Importfunktion zu nutzen. Wir empfehlen, zunächst einen Test-Nutzer\*in anzulegen, bevor die gesamte Schule hinzugefügt wird. So können Sie sich mit dem Onboarding neuer Benutzer\*innen vertraut machen.

Mit dieser Funktion kannst du mehrere Benutzer\*innen auf einmal erstellen – z.B. eine ganze Klasse – und ihnen direkt den richtigen Raum (z. B. Klasse 7a) und eine Rolle (z. B. Nutzer\*in oder Supermoderator\*in) zuweisen.

Am besten hast du für jede Klasse eine eigene CSV-Tabelle, in der die benötigten Benutzerdaten(s.u.) der Schüler\*innen stehen. Diese Tabellen kannst du dann nacheinander hochladen, um alle Benutzer\*innen systematisch zur Plattform hinzuzufügen.

> 💡 CSV ist ein offenes Dateiformat, das du problemlos mit Microsoft Excel oder anderen Office-Produkten erstellen kannst.

### Benutzerdaten für den CSV-Importer

Um den CSV-Importer zu verwenden, müssen die Spalten in einem bestimmten Format vorliegen. Als Referenz kannst du eine Beispieldatei direkt in der CSV-Importer-Oberfläche herunterladen.

Zu Anfang kannst du den echten Namen auch in die ersten drei Spalten einfügen.

| Anzeigename | Echter Name | Benutzername | E-Mail (optional) | Über mich (optional) |
| ----------- | ----------- | ------------ | ----------------- | -------------------- |

### Anleitung zur Nutzung des CSV-Importers

1. In der Menüleiste klicke auf **Konfigurationen**.
2. Vermutlich musst du in der Ansicht etwas herrunterscrollen, dann siehst du einen Button mit **Benutzer**.
3. Klicke im ausgeklappten Menü auf **Datei-Upload**.
4. Wähle die csv-Datei aus, die der oben genannten Formatvorlage entsprechen muss (!).
5. Nach der Auswahl der Datei siehst du eine Vorschau aller Benutzer\*innen, die mit dieser Datei importiert werden.
6. Wähle eine Benutzerrolle aus, die auf alle Benutzer\*innen in der Vorschau angewendet wird.
7. Wähle einen Raum aus, in dem die Benutzer\*innen mit dieser Rolle hinzugefügt werden sollen.
8. Klicke auf **Bestätigen**.
9. _Optional:_ Überprüfe im Benutzermenü, ob der Import erfolgreich war.

<img src="/screenshots/csv_importer.png" alt="CSV-Import" style="height: 300px;">

## Die erste Idee erstellen

Nach dem du jetzt Räume, Rollen und Nutzer\*innen erstellt hast kannst du auch schon loslegen und (probeweise) eine erste Idee erstellen.

1. Gehe in einen beliebigen Raum den du erstellt hast.
2. Klicke auf das Symbol mit der grünen Glühbirne.
3. Fülle die folgenden Felder aus:

- **Titel (Pflichtfeld):** Gib einen Titel für die Idee ein.
- **Inhalt (Pflichtfeld):** Beschreibe die Idee im zweiten Feld ausführlich.
- **Kategorie (Optional):** Wähle eine passende Kategorie für die Idee aus.
- **Status (Pflichtfeld):** Der Status sollte in den meisten Fällen auf **„Aktiv“** gesetzt bleiben.

4. Bestätige deine Eingaben, um die Idee zu erstellen.

---

Du hast deine erste Idee erstellt! 🎉
