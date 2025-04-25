# 👥 Benutzer\*innenverwaltung
> Hinweis: Diese Ansicht ist nur für Administrator\*innen sichtbar.

## Rollen in der aula Software

>Kurz erklärt: Das Rollensystem in der aula-Software bestimmt, welche Aufgaben und Rechte die verschiedenen Rollen haben. Es legt fest, wer welche Aktionen ausführen und welche Bereiche einsehen darf.

<details>
<summary>1. <strong>Gast</strong></summary>
<p>Kann Inhalte einsehen, aber nicht aktiv teilnehmen.</p>
</details>

<details>
<summary>2. <strong>Nutzer*in</strong></summary>
<p>Nutzer*innen können eigene Ideen einbringen, mit anderen Nutzer*innen über Vorschläge diskutieren und in Abstimmungen entscheiden, welche Ideen weiterverfolgt werden sollen.
</p>
</details>

<details>
<summary>3. <strong>Moderator*in</strong></summary>
<p>Moderator*innen in der aula-Beteiligungssoftware sind Schüler\*innen und Lehrkräfte, die sicherstellen, dass sich alle an der Schule aktiv und respektvoll beteiligen können. Sie kümmern sich um die Plattform, achten auf die Einhaltung der Verhaltensregeln und unterstützen andere Nutzer*innen, um eine konstruktive und positive Atmosphäre zu fördern. Es ist sinnvoll, viele Moderator*innen an der Schule zu haben, damit sie sich die Aufgaben gut aufteilen können – idealerweise zwei Moderator*innen pro Klasse.
</p>
</details>

<details>
<summary>4. <strong>Super-Moderator*in</strong></summary>
<p>Hat Moderationsrechte, wie die Moderator\*inne allerdings nicht beschränkt auf einen/oder mehrere Räume, sondern kann alle Räume und ihre Inhalt sehen. Zusätzlich können Supermoderator*innen die Menüpunkte Ideen und Boxen einsehen, um zusätzlich einen Gesamtüberblick zuhalten. </p>
</details>

<details>
<summary>5. <strong>Prüfer*in</strong></summary>
<p>Überprüft Ideen.</p>
</details>

<details>
<summary>6. <strong>Admin</strong></summary>
<p>Verwaltet die Plattform.</p>
</details>

<details>
<summary>7. <strong>Tech-Admin</strong></summary>
<p>Kann grundlegende Änderungen an der Schul-Instanz vornehmen, z.B. die Instanz offline schalten oder Betriebszeiten festlegen. Mit dem Tech-Admin-Account sind keine Inhalte sichtbar. Diesen Account kann bspw. auch ein externer Dienstleister nutzen, denn der Tech-Admin hat keinen Einblick auf die inhaltliche Ebene der erstellten Ideen etc.</p>
</details>

### Stimmrecht

Das Stimmrecht bezeichnet die Möglichkeit, in der Abstimmungsphase über eine Idee abzustimmen. Während Nutzer\*innen immer ein Stimmrecht haben, gibt es für Moderator\*innen, Super-Moderator\*innen und Prüfer\*innen jeweils eine Variante mit und ohne Stimmrecht.

| **Mit Stimmrecht**                 | **Ohne Stimmrecht**         |
|----------------------------------|--------------------------|
| Nutzer\*in                        | Gast                    |
| Moderator\*in mit Stimmrecht      | Moderator\*in            |
| Super-Moderator\*in mit Stimmrecht | Super-Moderator\*in      |
| Prüfer\*in mit Stimmrecht         | Prüfer\*in               |
|                                  | Admin                   |
|                                  | Tech-Admin              |

## Benutzer\*innen erstellen

## 👤 Einzelne\*r Benutzer\*in anlegen

Einzelne Benutzer\*innen können im **Benutzer-Menü** erstellt werden.  
Beim Anlegen erhält der/die Benutzer\*in folgende Eigenschaften:

### 📄 Benutzer\*in-Eigenschaften

- **Anzeigename**  
  → Der Name, der beim Kommentieren oder beim Erstellen einer Idee angezeigt wird.
- **Echter Name**
- **Benutzername**  
  → Login-Name
- **Optional:** E-Mail-Adresse  
- **Optional:** Beschreibung
- **Benutzerrolle** *(siehe Standard-Setup unter 1.2)*
- **Status**  
  Es gibt vier mögliche Status:
    - Aktiv *(Standard)*
    - Inaktiv
    - Gesperrt
    - Archiviert
- **Optional:** Zuordnung zu einem Raum oder mehreren Räumen

---

### 🛠️ Benutzer*in anlegen – Schritt-für-Schritt

1. Klicke im Menü auf **Benutzer-Menü**
2. Klicke auf **NEUER BENUTZER**
3. Fülle das Formular mit den [oben genannten Angaben](#-benutzerin-eigenschaften) aus
4. Lege fest, welche Rolle der/die Benutzer\*in in welchem Raum haben soll, indem du auf **RAUM-REGELN FESTLEGEN** klickst
5. Wähle im **Pop-up-Fenster** für jeden Raum eine Rolle 
![Raum Rollen setzen](/screenshots/raumrollen_setzen.png)
6. Bestätige das Pop-up-Fenster
7. Bestätige die Erstellung des/der neuen Benutzer*in

### Mehrere Benutzer*innen anlegen (CSV-Datei)

Wenn du die gesamte Instanz zum ersten Mal mit allen Benutzer\*innen einrichtest, empfiehlt es sich, die **CSV-Importfunktion** zu verwenden. Damit kannst du **mehrere Benutzer*innen gleichzeitig** in einem bestimmten Raum mit einer bestimmten Rolle anlegen oder hinzufügen.  

CSV ist ein offenes Dateiformat, das z. B. mit Microsoft Excel oder anderen Tabellenkalkulationsprogrammen einfach erstellt werden kann.

Für den CSV-Import musst du ein bestimmtes Spaltenformat einhalten. Als Referenz kannst du im CSV-Importbereich auch eine **Beispieldatei herunterladen**.

| Anzeigename | Echter Name | Benutzername | E-Mail (optional) | Über mich (optional) |
| --- | --- | --- | --- | --- |

1. Klicke auf **Konfigurationen**
2. Wähle **Benutzer**
3. Klicke im aufgeklappten Menü auf **DATEI HOCHLADEN**
4. Wähle eine Datei, die dem oben beschriebenen Format entspricht
5. Nach dem Hochladen siehst du eine Vorschau der Benutzer*innen, die mit dieser Datei importiert werden
6. Wähle eine **Benutzerrolle**, die für alle Benutzer*innen in der Vorschau gelten soll
7. Wähle einen **Raum**, in dem diese Rolle gelten soll
8. Klicke auf **Bestätigen**
9. **Optional:** Überprüfe im Benutzer-Menü, ob der Import erfolgreich war

---

## Wie einzelne Benutzer\*innen zu aula finden

Der Onboarding-Prozess beschreibt, wie Benutzer*innen erstmals auf die Plattform zugreifen können. Es gibt zwei Möglichkeiten, wie eine Person sich nach der Erstellung ihres Kontos anmelden kann:

### Login per E-Mail

Wenn das Benutzerkonto mit einer E-Mail-Adresse erstellt wurde, erhält der/die Benutzer*in eine E-Mail mit einem sogenannten **Magic Link**. Dieser Link ist eine einmalige URL, mit der man sich **ohne Passwort sofort anmelden** kann.

Der erste Schritt beim Onboarding ist das **Festlegen eines neuen Passworts**.


### Login mit temporären Passwort

Wenn dem Konto ein temporäres Passwort zugewiesen wurde, kann man sich mit dem **Benutzernamen** und diesem **temporären Passwort** anmelden.

**Passwort-Erstellung:**

Nach dem ersten Zugang – egal ob per Magic Link oder temporärem Passwort – muss jede\*r Benutzer\*in ein **eigenes Passwort erstellen**. Dieses muss zur Bestätigung **zweimal eingegeben** werden, bevor der vollständige Zugriff auf die Plattform möglich ist.

### Registrierung

Alle Benutzerkonten müssen von einem\*r Administrator\*in erstellt werden   
> Hinweis: **Eine Selbstregistrierung ist derzeit nicht möglich**.


### Aktionen

#### Login mit Magic Link

**Wer:** Alle Rollen

1. Öffne die E-Mail von [admin@neu.aula.de](admin@neu.aula.de)  
2. Notiere dir den **Schulcode** und **Benutzernamen** aus der E-Mail  
3. Gehe auf **neu.aula.de**  
4. Gib den **Schulcode** ein  
    1. → Dieser Schritt ist optional, falls du den Instanzcode bereits eingegeben hast  
5. Füge den **Magic Link** in die Adresszeile des Browsers ein  
6. Gib ein neues Passwort **zweimal** ein  
7. Speichere das neue Passwort
8. Anschließend kannst du dich mit deinem Benutzer\*innennamen und neuem Passwort anmelden


#### Login mit temporärem Passwort

**Wer:** Alle Rollen

1. Gehe auf [neu.aula.de](neu.aula.de)
2. Gib den **Schulcode** ein  
    1. → Dieser Schritt ist optional, falls du den Instanzcode bereits eingegeben hast  
3. Gib deinen **Benutzernamen** und das **temporäre Passwort** ein  
4. Gib erneut das **temporäre Passwort** ein und danach das **neue Passwort** **zweimal**  
5. Speichere das neue Passwort  
6. Melde dich mit deinem **Benutzernamen** und dem **neuen Passwort** an  


#### Passwortliste drucken
**Wer:** Administrator*innen

> 💡 Diese Passwortlisten können ausgeschnitten und dann einzeln an die Schüler\*innen ausgegeben werden.

1. Klicke im Menü auf **Benutzer**
2. Klicke auf den Button mit dem Drucker-Symbol **PASSWORTLISTE**
3. Wähle im Pop-up-Fenster den gewünschten **Raum** oder **alle Räume** aus (Standard: alle)
4. Wähle **nur temporäre Passwörter** aus (Standard)
5. Bestätige deine Auswahl aus Schritt 3 und 4
6. Es öffnet sich ein neuer Tab mit der Passwortliste
7. Klicke oben rechts auf den **Drucken-Button**, um den Druck zu starten

