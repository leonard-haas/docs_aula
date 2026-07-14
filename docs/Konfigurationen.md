# Konfigurationen / Tech-Admin-Panel

> Das Konfigurationsmenü in der Menüleiste ist identisch mit dem Panel, auf das der Tech-Admin Zugriff hat.

---

## Admin-Panel

Das Admin-Panel zeigt eine aufklappbare Liste mit erweiterten Einstellungsmöglichkeiten an:

1. **[💡 Ideen-Kategorien](#kategorien-fur-ideen)**
2. **[🗳️ Abstimmung](#abstimmung-quorum)**
3. **[👤 Benutzer](#benutzer-csv-import)**
4. **[👥 Gruppe](#gruppen)**
5. **[🗓️ Geplante Aktionen](#geplante-aktionen)**
6. **[🖥️ System](#system)**
7. **[⚠️ Gefahrenzone](#gefahrenbereich-instanz-loschen)**

---

## Kategorien für Ideen

Ideen können mit Kategorien thematisch gruppiert werden.

### Kategorie erstellen

1. In der Zeile **Ideen** auf den **Pfeil nach unten** klicken.
2. Auf **„Neue Kategorie erstellen“** klicken.
3. Eingeben:
   - Name der Kategorie
   - Bild auswählen
4. Eingaben bestätigen.

### Kategorie bearbeiten

1. In der Zeile **Ideen** auf den **Pfeil nach unten** klicken.
2. Auf das **Symbol der Kategorie** klicken, die bearbeitet werden soll.
3. Änderungen vornehmen.
4. Änderungen bestätigen.

### Kategorie löschen

1. Auf den **Pfeil-nach-unten-Button** in der Zeile **Ideen** klicken.
2. Auf das **Kreuz-Symbol** innerhalb der zu löschenden Kategorie klicken.
3. Warnmeldung im Pop-up-Fenster bestätigen.

---

## Abstimmung (Quorum)

Das Quorum ist ein globaler Prozentwert, der für alle Räume gilt.
Es zeigt an, wie viele Stimmen (in %) für eine Idee erforderlich sind –
**nur visuell**, es gibt **keine automatische Durchsetzung**.

Im **„Idee“**-Bereich gibt es zwei Schieberegler:

- Wilde-Ideen-Phase
- Abstimmungsphase

### Quorum einstellen

1. Schieberegler anklicken und ziehen (in 5%-Schritten).
2. Auf **Speichern** klicken.

---

## Benutzer (CSV-Import)

### CSV-Import-Schnittstelle

**Buttons:**

- Datei hochladen
- Beispieldatei herunterladen
- Bestätigen
- Abbrechen

**Dropdowns:**

- Räume auswählen
- Benutzer-Rolle festlegen

**Benötigte CSV-Felder:**

- `realname` (erforderlich)
- `displayname` (erforderlich)
- `username` (erforderlich)
- `email` (optional)
- `about_me` (optional)

### Benutzer\*innen importieren

1. Klicke in der Menüleiste auf **"Konfigurationen"**.
2. Vermutlich musst du in der Ansicht etwas herunterscrollen, dann siehst du einen Button mit **"Benutzer"**.
3. Klicke im ausgeklappten Menü auf **Datei-Upload**.
4. Wähle die CSV-Datei (Format: UTF-8) aus, die der oben genannten Formatvorlage entspricht.
5. Nach der Auswahl der Datei siehst du eine Vorschau aller Benutzer\*innen, die mit dieser Datei importiert werden.
6. Wähle eine Benutzerrolle aus, die auf alle Benutzer\*innen in der Vorschau angewendet wird.
7. Wähle einen oder mehrere Räume aus, in denen die Benutzer\*innen mit dieser Rolle hinzugefügt werden sollen.
8. _Optional:_ Du kannst einen bestimmten Zeitpunkt terminieren, wann die Onboarding-E-Mail verschickt werden soll. Klicke dazu auf das Feld **"Einladungsdatum für neue Benutzer"**.
9. Klicke auf **Bestätigen**.
10. _Optional:_ Überprüfe im Benutzermenü, ob der Import erfolgreich war.

<img src="/screenshots/csv_importer.png" alt="Oberfläche des CSV-Importers mit Vorschau der Benutzer*innen" style="height: 300px;">


---

## Gruppen

Mehrere Benutzer\*innen können zu Gruppen zusammengefasst werden – z. B. für Nachrichten (siehe [Nachrichten-schreiben](Administrationsbereich.md#nachrichten-schreiben)).

### Gruppe erstellen

1. In der Zeile **Gruppe** auf den **Pfeil nach unten** klicken.
2. Auf **Gruppe hinzufügen** klicken.
3. Eingeben:
   - Gruppenname
   - Beschreibung
4. Benutzer\*innen auswählen.
5. Bestätigen.

### Gruppe bearbeiten

1. In der Zeile **Gruppe** auf den **Pfeil nach unten** klicken.
2. Gewünschte Gruppe auswählen.
3. Änderungen vornehmen.
4. Bestätigen.

### Gruppe löschen

1. **Pfeil-nach-unten-Taste** in „Gruppe“.
2. **Kreuzsymbol** in gewünschter Gruppe anklicken.
3. **Löschbestätigung** im Pop-up-Fenster.

---

## Geplante Aktionen

Ermöglicht das Planen von Aktionen für ein zukünftiges Datum – z. B. das Sperren von Benutzer\*innen oder das Versetzen der Instanz in den Ferienmodus.

### Ansicht für geplante Aktionen

**Wer:** Admin, Tech-Admin

1. Klicke auf **Geplante Aktionen**.
2. Bereich **System** auswählen.
3. Aktion auswählen:
   - **System:** Status ändern oder löschen
     - Status: _aktiv_, _inaktiv_, _Wochenende_, _Ferien_, _Feiertag_
4. Datum wählen.
5. **Bestätigen**.


### Anwendungsbeispiele für geplante Aktionen

<!-- #### Benutzer sperren (und reaktivieren)

1. Bereich: **Benutzer\*in**
2. Benutzerstatus auf **gesperrt** setzen.
3. Menü: **Konfigurationen → Geplante Aktionen**
4. Bereich: **Benutzer**
5. Status: **aktiv**
6. Datum wählen.
7. Bestätigen. -->

#### Schule in Ferienmodus setzen

1. Menü: **Konfigurationen → Geplante Aktionen**
2. Bereich: **System**
3. Befehl: **Status**
4. Status: **Ferien**
5. Datum einstellen.
6. Bestätigen.

## System

### Instanzstatus ändern

**Wer:** Admin, Tech-Admin

1. Menü: **Konfigurationen → System**
2. Status wählen:
  - _Aktiv_
  - _Inaktiv_
  - _Wochenende_
  - _Ferien_
  - _Feiertag_

### 🔄 Backup erstellen und wiederherstellen

**Wer:** Admin, Tech-Admin

Wir hosten die Daten und erstellen täglich automatisierte Datenbackups. Diese Backups sind verschlüsselt und werden an drei Speicherorten in Deutschland repliziert. Schulen, die unsere Hosting-Lösung nutzen, müssen keine eigenen Backups erstellen, da dies nur die Komplexität der Pflege erhöht.

👉 Wenn du den Zustand deines Systems auf einen früheren Zeitpunkt zurücksetzen möchtest, schreib uns bitte an [support@aula.de](mailto:support@aula.de). Wir können die Speicherung von Backups nicht länger als 30 Tage garantieren.

## ⚠️ Gefahrenbereich (Instanz löschen) ⚠️

**Wer:** Admin, Tech-Admin

1. Klicke auf Gefahrenzone.
2. Anschließend auf **Konto löschen**.
3. Bestätige die Löschung der Instanz.
