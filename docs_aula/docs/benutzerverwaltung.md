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
<p>**Rollenbeschreibung für Moderator*innen in der Aula-Beteiligungssoftware:**

**Rolle: Moderator*in**

**Beschreibung:**

Moderator\*innen in der Aula-Beteiligungssoftware sind Schüler\*innen und Lehrkräfte, die sicherstellen, dass sich alle an der Schule aktiv und respektvoll beteiligen können. Sie kümmern sich um die Plattform, achten auf die Einhaltung der Verhaltensregeln und unterstützen andere Nutzer\*innen, um eine konstruktive und positive Atmosphäre zu fördern. Es ist sinnvoll, viele Moderator\*innen an der Schule zu haben, damit sie sich die Aufgaben gut aufteilen können – idealerweise zwei Moderator\*innen pro Klasse.</p>
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

>💡 Wenn du zum ersten Mal alle Benutzer\*innen für eure Schule in aula anlegen möchtest, ist es am einfachsten, die CSV-Importfunktion zu nutzen.

Mit dieser Funktion kannst du mehrere Benutzer\*innen auf einmal erstellen – z.B. eine ganze Klasse – und ihnen direkt den richtigen Raum (z. B. Klasse 7a) und eine Rolle (z. B. Nutzer\*in oder Supermoderator\*in) zuweisen.

Am besten hast du für jede Klasse eine eigene CSV-Tabelle, in der die benötigten Benutzerdaten(s.u.) der Schüler\*innen stehen. Diese Tabellen kannst du dann nacheinander hochladen, um alle Benutzer\*innen systematisch zur Plattform hinzuzufügen.

>💡 CSV ist ein offenes Dateiformat, das du problemlos mit Microsoft Excel oder anderen Office-Produkten erstellen kannst.

### Benutzerdaten für den CSV-Importer

Um den CSV-Importer zu verwenden, müssen die Spalten in einem bestimmten Format vorliegen. Als Referenz kannst du auch eine Beispieldatei in der CSV-Importer-Oberfläche herunterladen.

Zu Anfang kannst du den echten Namen auch in die ersten drei Spalten einfügen.

| Anzeigename | Echter Name | Benutzername | E-Mail (optional) | Über mich (optional) |
|------------|------------|--------------|--------------------|------------------|

### Anleitung zur Nutzung des CSV-Importers

1. In der Menuleiste klicke auf **Konfigurationen**.
2. Vermutlich musst du in der Ansicht etwas herrunterscrollen, dann siehst du einen Button mit **Benutzer**.
3. Klicke im ausgeklappten Menü auf **Datei-Upload**.
4. Wähle die Datei aus, die der oben genannten Formatvorlage entsprechen muss (!).
5. Nach der Auswahl der Datei siehst du eine Vorschau aller Benutzer\*innen, die mit dieser Datei importiert werden.
6. Wähle eine Benutzerrolle aus, die auf alle Benutzer\*innen in der Vorschau angewendet wird.
7. Wähle einen Raum aus, in dem die Benutzer\*innen mit dieser Rolle hinzugefügt werden sollen
8. Klicke auf **Bestätigen**.
9. *Optional:* Überprüfe im Benutzermenü, ob der Import erfolgreich war.

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

