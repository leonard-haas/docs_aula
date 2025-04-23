# Konfigurationen / Tech-Admin-Panel

> Das Konfigurationsmenü in der Menüleiste ist identisch mit dem Panel, auf das der Tech-Admin Zugriff hat.

---

## Admin Panel

Das Admin Panel zeigt eine aufklappbare Liste mit erweiterten Einstellungsmöglichkeiten an:

1. [💡 Idee](#idee)  
2. [👤 Benutzer](#benutzer)  
3. [👥 Gruppe](#gruppe)  
4. [🗓️ Geplante Aktionen](#geplante-aktionen)  
5. [🖥️ System](#system)  
6. [⚠️ Gefahrenzone](#gefahrenzone)

---

## Kategorien für Ideen

Ideen können mit Kategorien thematisch gruppiert werden.

### Kategorie erstellen

1. In der Zeile **„Ideen“** auf den **Pfeil nach unten** klicken  
2. Auf **„Neue Kategorie erstellen“** klicken  
3. Eingeben:
   - Name der Kategorie  
   - Bild auswählen  
4. Eingaben bestätigen  

### Kategorie bearbeiten

1. In der Zeile **„Ideen“** auf den **Pfeil nach unten** klicken  
2. Auf das **Symbol der Kategorie** klicken, die bearbeitet werden soll  
3. Änderungen vornehmen  
4. Änderungen bestätigen  

### Kategorie löschen

1. Auf den **Pfeil-nach-unten-Button** in der Zeile **„Ideen“** klicken  
2. Auf das **Kreuz-Symbol** innerhalb der zu löschenden Kategorie klicken  
3. Warnmeldung im Popup-Fenster bestätigen  

---

## Abstimmung (Quorum)

Das Quorum ist ein globaler Prozentwert, der für alle Räume gilt.  
Es zeigt an, wie viele Stimmen (in %) für eine Idee erforderlich sind –  
**nur visuell**, es gibt **keine automatische Durchsetzung**.

### Im **„Idee“**-Bereich gibt es zwei Schieberegler:

- Wilde-Ideen-Phase  
- Abstimmungsphase  

### Quorum einstellen

1. Schieberegler anklicken und ziehen (in 5%-Schritten)  
2. Auf **„Speichern“** klicken  

---

## Benutzer (CSV-Import)

### CSV-Import-Schnittstelle

**Buttons:**

- Datei hochladen  
- Beispieldatei herunterladen  
- Bestätigen  
- Abbrechen  

**Dropdowns:**

- Raum auswählen  
- Benutzerebene festlegen  

**Benötigte CSV-Felder:**

- `realname` (erforderlich)  
- `displayname` (erforderlich)  
- `username` (erforderlich)  
- `email` (optional)  
- `about_me` (optional)  

### Benutzer importieren

1. Beispieldatei herunterladen  
2. CSV-Datei hochladen  
3. Raum + Benutzerrolle auswählen  
4. **Bestätigen**  
5. Optional: **Abbrechen**  

---

## Gruppen

Mehrere Benutzer können zu Gruppen zusammengefasst werden – z. B. für Nachrichten (siehe **Nachrichten**).

### Gruppe erstellen

1. In der Zeile **„Ideen“** auf den **Pfeil nach unten** klicken  
2. Auf **„Gruppe hinzufügen“** klicken  
3. Eingeben:
   - Gruppenname  
   - Beschreibung  
4. Benutzer auswählen  
5. Bestätigen  

### Gruppe bearbeiten

1. In der Zeile **„Ideen“** auf den **Pfeil nach unten** klicken  
2. Gewünschte Gruppe auswählen  
3. Änderungen vornehmen  
4. Bestätigen  

### Gruppe löschen

1. **Pfeil-nach-unten-Taste** in „Ideen“  
2. **Kreuzsymbol** in gewünschter Gruppe anklicken  
3. **Löschbestätigung** im Popup  

---

## Geplante Aktionen

Ermöglicht das Planen von Aktionen für ein zukünftiges Datum –  
z. B. Benutzer sperren oder Instanz in den Urlaubsmodus versetzen.

### Ansicht für geplante Aktionen

**Wer:** Admin, Tech-Admin

1. Klick auf **„Geplante Aktionen“**  
2. Bereich auswählen:
   - **System**  
   - **Benutzer**  
   - **Gruppe**  
3. Aktion auswählen:
   - **System:** Status ändern oder löschen  
     - Status: *aktiv*, *inaktiv*, *Wochenende*, *Urlaub*, *Feiertag*  
   - **Benutzer:** Login, Logout, Status ändern  
     - Status: *aktiv*, *inaktiv*, *gesperrt*  
   - **Gruppe:** Benutzer hinzufügen/entfernen  
4. Datum wählen  
5. **Bestätigen**  

### Anwendungsbeispiele für geplante Aktionen

#### Benutzer sperren (reaktivieren)

1. Bereich: **Benutzer**  
2. Benutzerstatus auf **gesperrt** setzen  
3. Menü: **Konfigurationen → Geplante Aktionen**  
4. Bereich: **Benutzer**  
5. Status: **aktiv**  
6. Datum wählen  
7. Bestätigen  

#### Schule in Ferienmodus setzen

1. Menü: **Konfigurationen → Geplante Aktionen**  
2. Bereich: **System**  
3. Befehl: **Status**  
4. Status: **Ferien**  
5. Datum einstellen  
6. Bestätigen  


## System

### Instanzstatus ändern

**Wer:** Admin, Tech-Admin  

1. Menü: **Konfigurationen → System**  
2. Status wählen:
   - *aktiv*  
   - *inaktiv*  
   - *Wochenende*  
   - *Urlaub*  
   - *Feiertag*  

---

### Backup erstellen

**Wer:** Admin, Tech-Admin  

Lädt einen SQL-Dump der Datenbank herunter.

1. Menü: **Konfigurationen → System**  
2. Auf **„Backup erstellen“** klicken  

---

### Backup wiederherstellen

Nur bei direktem Serverzugriff möglich (bei Selfhosting).  
**Ansonsten:** Bitte das Aula-Team kontaktieren.

---

## Instanz löschen

**Wer:** Admin, Technischer Admin


