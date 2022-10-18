# 2022-10-Handbuch

#### Table of contents

1. [About](#About)
2. [Publikationsprozess](#Publikationsprozess)
    - [Für Erst-Publizierende](#Für-Erst-Publizierende)
    - [Publikationsprozess verstehen](#Publikationsprozess-verstehen)
    - [Publikationsvariante auswählen](#Publikationsvariante-auswählen)
3. [DCAT-AP-CH](#DCAT-AP-CH)
    - [DCAT als universelles Vokabular](#DCAT-als-universelles-Vokabular)
    - [Klassen](#Klassen)
4. [FAQ](#FAQ)
    - [DCAT als universelles Vokabular](#DCAT-als-universelles-Vokabular)
    - [Klassen](#Klassen)
5. [Glossar](#Glossar)
6. [Über das Handbuch](#Über-das-Handbuch)
    - [Kontakt](#Kontakt)
    - [Rechtliche Hinweise](#Rechtliche-Hinweise)

## About

Die I14Y Interoperabilitätsplattform ist ein zentrales Verzeichnis, das die Metadaten der dokumentierten Datensätze öffentlich zugänglich macht.
Metadaten sind wichtig, um den Kontext der Daten zu verstehen. Beschreibung, Struktur, Qualität, Standard und Verwendung der Daten sind zentral abgelegt. Angesichts der immer grösseren Datenmengen müssen sich öffentliche Verwaltungen und Unternehmen anpassen und neue Instrumente verwenden, um den digitalen Wandel voranzutreiben.
Über die I14Y Interoperabilitätsplattform können alle Nutzenden auf die verfügbaren Datenquellen zugreifen (frei oder mit entsprechendem Zugriffsrecht). Sie erleichtert es zudem, bereits erfasste Informationen zu erkennen und diese mehrfach zu verwenden (Once-Only-Prinzip). Die Schaffung neuer Dienste sowie die Durchführung neuer Datenanalysen werden somit unterstützt.

Der Metadatenkatalog der I14Y Interoperabilitätsplattform hat im Wesentlichen folgende Funktionen:

* Suchmaschine
* Metadatenregister
* Beschreibung Daten anhand von Metadaten
* Fachglossar

Die I14Y Interoperabilitätsplattform verwendet den Standard DCAT-AP.

Sie haben noch keine Daten auf [I14Y](https://www.i14y.admin.ch/de/home) veröffentlicht? Als Erst-Publizierende erklären wir Ihnen das Wichtigste rund um den Prozess und unterstützen Sie bei der Identifikation von geeigneten Daten.

* [Für Erst-Publizierende](#Für-Erst-Publizierende)

### Publikationsrichtlinien 

Am Anfang steht eine gute Vorbereitung. Bevor Sie Daten als Open Government Data publizieren können, müssen Sie sicherstellen, dass die Anforderungen für eine Publikation erfüllt sind. Die Richtlinien zeigen Ihnen auf welche diese Anforderungen sind.

TBD: Welche Richtlinien gibt es?

## Publikationsprozess

In diesem Kapitel erklären wir Ihnen, wie Sie Open Government Data publizieren. Folgende Punkte müssen Sie dabei beachten:

<img width="551" alt="Übersicht" src="https://user-images.githubusercontent.com/115873530/196399836-3fd80e95-3ce8-4030-a88b-e2ce99c71a9f.PNG">

* Ï14Y ist ein Metadatenkatalog. Hier wird auf publizierte Open Government Data in standardisierter, leicht verständlicher und wiederverwendbarer Form referenziert. Somit steigert sich ihre Sichtbarkeit.

* Der Swiss Data Steward (SDS) und der Local Data Steward (LDS) übernehmen das Controlling des gesamten Katalogs. Es ist allerdings an den publizierenden Organisationen oder Personen (Data Producer) sicherzustellen, dass die rechtlichen, technischen und organisatorischen Anforderungen eingehalten werden, siehe «OGD-Richtlinien».

* Bei der ersten Publikation wird für alle Publikationsvarianten ein Test-Ablauf in der «Abnahmeumgebung» von I14Y durchgeführt. Dies gibt datenpublizierenden Organisationen oder Personen die Möglichkeit, ihre Datasets und sämtliche weitere Informationen ausgiebig zu prüfen und allfällige Änderungen vorzunehmen. Ab der zweiten Publikation können Datenpublizierende immer wieder neue Daten selbstständig publizieren. Die Abnahmeumgebung steht jederzeit für Test-Publikationen zur Verfügung.

* Das User-Management wird zentral von eIAM sichergestellt. Neue Benutzerinnen und Benutzer oder Anpassungen an den bestehenden Berechtigungen werden darin erfasst.

Erst-Publizierende begleiten wir Schritt für Schritt durch den Prozess. Im ersten Schritt muss sich die neue Organisation und Benutzer/innen auf eIAM registrieren. Erst danach kann der Publikationsprozess starten.

Wenn Sie bereits als Nutzerinnen oder Nutzer auf eIAM registriert sind, können Sie direkt zu den Inhalten für registrierte Nutzerinnen und Nutzer springen. Dort können Sie direkt die geeignete Publikationsvariante für Ihre Daten auswählen.

**Für Erst-Publizierende**

* Login auf [I14Y](https://www.i14y.admin.ch/de/home) 

* Profil auf [I14Y](https://www.i14y.admin.ch/de/home) verwalten

**Für registrierte Nutzerinnen und Nutzer**

* [Publikationsprozess verstehen](#Publikationsprozess-verstehen) verstehen

* [Publikationsvariante auswählen](#Publikationsvariante-auswählen) auswählen

### Für Erst-Publizierende

Es freut uns, dass Sie Ihre Daten auf opendata.swiss publizieren wollen! Jeder Eintrag auf opendata.swiss «Dataset» sowie sämtliche Benutzerinnen und Benutzer sind einer Organisation zugeteilt. Sollten Sie noch keine Daten auf opendata.swiss publiziert haben, ist deshalb der erste Schritt, die Registrierung der Organisation und der Benutzerinnen und Benutzer. Nach erfolgter Registrierung können Sie über das Backend die Angaben zur Organisation vervollständigen und mit der Publikation der Datasets loslegen.

### Publikationsprozess verstehen

### Publikationsvariante auswählen

## DCAT-AP-CH

### DCAT als universelles Vokabular

### Klassen

| Klassenname | Bemerkung | URI und Referenz | 
|-------|------|---------------------------------------------------------------------|
| Katalog | Ein Katalog oder Repository, in dem die beschriebenen Datensätze oder Datendienste gespeichert sind. | [Katalog](#Katalog) |
| Dataset | Eine konzeptionelle Einheit, die die veröffentlichten Informationen darstellt. | [Dataset](#Dataset)|
| Distribution | A physical embodiment of the Dataset in a particular format. | [Distribution](#Distribution) |
| Data Service | Eine Sammlung von Vorgängen, die den Zugriff auf einen oder mehrere Datensätze oder Datenverarbeitungsfunktionen ermöglicht. | [Data Service](#Data-Service) |

| Klassenname | Bemerkung | URI und Referenz | 
|-------|------|---------------------------------------------------------------------|
| Public Service | TBD | [Public Service](#Public-Service) |

#### Katalog

#### Dataset

#### Dataservice

#### Distribution

#### Public Service

## FAQ

## Glossar

## Über das Handbuch

### Kontakt

### Rechtliche Hinweise

