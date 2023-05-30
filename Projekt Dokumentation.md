# Projekt-Dokumentation

Gruppe Grapefruit Angelov, Koelewijn, Jeanneret Winsky, Oesch

| Datum                        | Version | Zusammenfassung                                               |
| ---------------------------- | ------- | ------------------------------------------------------------- |
| 09.05.23                     | 0.0.1   | Heute haben wir Userstorys, Testfälle und Diagramme erstellt. |
| 16.05.23                     | 0.02    | Heute haben wir Planen, Entscheiden und Realisieren erstellt. |
| 223.05.2023 | 1.0.0   | Erste Version wurde fertiggestellt                                     |
| 20.05.2023 | 1.1.0   |Dark mode und No Emoji button wurden hinzugefügt, aber noch nicht implementiert                                         |

## 1 Informieren

### 1.1 Ihr Projekt

Unser Ziel ist es, eine benutzerfreundliche Website zu entwickeln, die Menschen, die das Programmieren erlernen möchten, helfen kann. Wir möchten Lernenden dabei helfen, ihre Programmierkenntnisse zu erweitern und Probleme effektiv zu lösen.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ        | Beschreibung                                                                                                                                                                                        |
| ---- | --------------- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1    | Muss            | Funktional | Als Benutzer möchte ich einen funktionierenden Link haben, um auf die Webseite zugreifen zu können.                                                                                                 |
| 2    | Muss            | Funktional | Als Benutzer möchte ich die verschiedenen Kategorien von häufigen Programmierfehlern auf der Webseite sehen, um gezielt nach Informationen suchen zu können.                                        |
| 3    | Muss            | Funktional | Als Benutzer möchte ich detaillierte Informationen zu jedem Programmierfehler in einer Kategorie erhalten, um besser verstehen zu können, warum der Fehler auftritt und wie ich ihn vermeiden kann. |
| 4    | Muss            | Funktional | Als Benutzer möchte ich praktische Tipps und Ratschläge erhalten, wie ich bestimmte Programmierfehler in meiner Projektdokumentation oder Lernbericht vermeiden kann.                               |
| 5    | Muss            | Funktional | Als Benutzer möchte ich eine benutzerfreundliche Navigation haben, um mühelos zwischen den verschiedenen Kategorien von Programmierfehlern zu wechseln.                                             |
| 6    | Kann            | Qualität   | Als Benutzer möchte ich die Möglichkeit haben, den Dark Mode auf der Webseite zu aktivieren, um den Benutzer optische Einstellungen zu ermöglichen.                                                 |
| 7    | Kann            | Qualität   | Als Benutzer möchte ich eine leicht verständliche und ansprechende Benutzeroberfläche erleben, die es mir ermöglicht, schnell auf die gesuchten Informationen zuzugreifen.                          |
| 8    | Kann            | Qualität   | Als Benutzer möchte ich die Möglichkeit haben, Code-Snippets zu öffnen, um die Erklärungen besser zu verstehen.                                                                                     |

### 1.3 Testfälle

| TC-№ | Ausgangslage                                         | Eingabe                                         | Erwartete Ausgabe                                                                                    |
| ---- | ---------------------------------------------------- | ----------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| 1.1  | Der Browser ist geöffnet.                            | Der Link wird eingegeben.                       | Die Webseite wird angezeigt.                                                                         |
| 2.1  | Die Webseite ist geladen                             | -                                               | Verschiedene Kategorien werden angezeigt.                                                            |
| 2.2  | Die Startseite ist geladen                           | Kategorie "Häufige C# Probleme" wird angeklickt | Man wird weitergeleitet auf die Seite mit "Häufige C# Probleme".                                      |
| 3.1  | Die Seite "Häufige C# Probleme" ist geladen          | -                                               | Detaillierte Informationen zu den Programmierfehlern aus dieser Kategorie werden angezeigt.          |
| 4.1  | Die Seite "Häufige Lernbericht Probleme" ist geladen | -                                               | Tipps und Ratschläge zur Fehlervermeidung sind gut strukturiert und leicht verständlich dargestellt. |
| 5.1  | Die Seite "Häufige Lernbericht Probleme" ist geladen | Kategorie "Häufige C# Probleme" wird angeklickt | Man wird weitergeleitet auf die Seite mit "Häufige C# Probleme".                                      |
| 6.1  | Unterseite oder Startseite ist geladen               | Im Footer wird Darkmode angeklickt              | Die Farben der Seite werden auf Dunkel eingestellt.                                                  |
| 7.1  | Startseite ist geladen                               | -                                               | Es gibt eine Benutzerfreundlichkeit und visuelle Attraktivität.                                      |
| 8.1  | Die Seite "Häufige C# Probleme" ist geladen          | Der Button "Code" wird angeklickt               | Eine Fläche wird ausgefahren mit einem Beispielscode.                                                 |

### 1.4 Diagramme

![image](https://user-images.githubusercontent.com/110892742/237027128-0436ffc0-cce7-4b0d-8912-13b972795c90.png)

![Web 1920 – 1](https://user-images.githubusercontent.com/110892283/237028839-798cb544-6e48-4dd8-80bb-85161727124d.png)

## 2 Planen

| AP-№ | Frist | Zuständig                 | Beschreibung                                                    | Geplante Zeit    |
| ---- | ----- | ------------------------- | --------------------------------------------------------------- | ---------------- |
| 1.A  |       | Koelewijn                 | GitHub Pages Webseite erstellen                                 | ⅓ Arbeitspakete  |
| 2.A  |       | Koelewijn                 | Erstellung der Startseite                                       | 4 Arbeitspakete  |
| 2.A  |       | Erstellung der Startseite | Implementierung des Dark Mode                                   | 4 Arbeitspakete  |
| 3.A  |       | Angelov                   | Verschönerung der Webseite mit Animationen                      | 4 Arbeitspakete  |
| 4.A  |       | Oesch                     | Erstellung der Kategorie Häufige C# Probleme                    | 4 Arbeitspakete  |
| 5.A  |       | Jeanneret Winsky          | Erstellung der Kategorie Häufige WinForms Probleme              | 4 Arbeitspakete  |
| 6.A  |       | Angelov                   | Erstellung der Kategorie Häufige Robocode Probleme              | 4 Arbeitspakete  |
| 7.A  |       | Oesch                     | Erstellung der Kategorie Häufige Projekt Dokumentation Probleme | 4 Arbeitspakete  |
| 8.A  |       | Koelewijn                 | Erstellung der Kategorie Häufige Lernbericht Probleme           | 1⅔ Arbeitspakete |
| 9.A  |       | Koelewijn                 | Erstellung der Kategorie Über Uns                               | 2 Arbeitspakete  |



Total: 32 Arbeitspakete

## 3 Entscheiden

Zuerst planten wir die Erstellung eines Marktplatzes, auf dem Programmierhilfe verkauft werden kann. Aufgrund der Einschränkung, nur CSS verwenden zu dürfen, war es uns jedoch nicht möglich, Benutzerinteraktionen einzubauen. Daher haben wir uns entschieden, stattdessen eine Webseite zu entwickeln, die häufige Programmierfehler behandelt, um Lernenden Unterstützung zu bieten.

Einige Funktionen, die wir implementieren wollten, wie zum Beispiel ein Copy-Button für Code-Snippets oder eine ausziehbare Funktion mit der Maus, konnten aufgrund dieser Einschränkungen leider nicht umgesetzt werden. Daher mussten wir einige der gewünschten Elemente überarbeiten.

## 4 Realisieren

| AP-№ | Datum | Zuständig        | geplante Zeit   | tatsächliche Zeit |
| ---- | ----- | ---------------- | --------------- | ----------------- |
| 1.A  |30.05.2023       | Koelewijn | 4 Arbeitspakete | 2 Arbeitspakete                   |
| 2.A  |16.05.23| Koelewijn        | 4 Arbeitspakete | 5 Arbeitspakete   |
| 3.A  |       | Angelov          | 4 Arbeitspakete |                   |
| 4.A  |       | Oesch            | 4 Arbeitspakete |                   |
| 5.A  |       | Jeanneret Winsky | 4 Arbeitspakete |                   |
| 6.A  |23.05.23| Angelov          | 4 Arbeitspakete |4 Arbeitspakete|
| 7.A  |       | Oesch            | 4 Arbeitspakete |                   |
| 8.A  |23.05.23| Koelewijn        | 2 Arbeitspakete | 1 Arbeitspaket    |
| 9.A  |16.05.23| Koelewijn        | 2 Arbeitspakete | 2 Arbeitspakete   |

## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
