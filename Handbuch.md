# 2022-10-Handbuch

#### Table of contents

1. [About](#About)
2. [Publikationsprozess](#Publikationsprozess)
    * [Für Erst-Publizierende](#Für-Erst-Publizierende)
    * [Publikationsprozess verstehen](#Publikationsprozess-verstehen)
    * [Publikationsvariante auswählen](#Publikationsvariante-auswählen)
3. [Aktualisierung der Daten](#Aktualisierung-der-Daten)
    * [Daten Updaten](#Daten-Updaten)
    * [Auskunft zu Daten geben](#Auskunft-zu-Daten-geben)
    * [Support und Feedback](#Support-und-Feedback)
4. [DCAT-AP-CH](#DCAT-AP-CH)
    * [DCAT als universelles Vokabular](#DCAT-als-universelles-Vokabular)
    * [Klassen](#Klassen)
      * [Katalog](#Katalog)
      * [Dataset](#Dataset)
      * [Dataservice](#Dataservice)
      * [Distribution](#Distribution)
      * [Public Service](#Public-Service)
5. [FAQ](#FAQ)
6. [Glossar](#Glossar)
7. [Über das Handbuch](#Über-das-Handbuch)
    * [Kontakt](#Kontakt)
    * [Rechtliche Hinweise](#Rechtliche-Hinweise)

## About

Die I14Y Interoperabilitätsplattform ist ein zentrales Verzeichnis, das die Metadaten der dokumentierten Datensätze öffentlich zugänglich macht.
Metadaten sind wichtig, um den Kontext der Daten zu verstehen. Beschreibung, Struktur, Qualität, Standard und Verwendung der Daten sind zentral abgelegt. Angesichts der immer grösseren Datenmengen müssen sich öffentliche Verwaltungen und Unternehmen anpassen und neue Instrumente verwenden, um den digitalen Wandel voranzutreiben.
Über die I14Y Interoperabilitätsplattform können alle Nutzenden auf die verfügbaren Datenquellen zugreifen (frei oder mit entsprechendem Zugriffsrecht, wobei der Zugriff via eIAM und KeyCloak geregelt wird). Sie erleichtert es zudem, bereits erfasste Informationen zu erkennen und diese mehrfach zu verwenden (Once-Only-Prinzip). Die Schaffung neuer Dienste sowie die Durchführung neuer Datenanalysen werden somit unterstützt.

Der Metadatenkatalog der I14Y Interoperabilitätsplattform hat im Wesentlichen folgende Funktionen:

<img width="547" alt="Übersicht_Public" src="https://user-images.githubusercontent.com/115873530/196630701-e9c57cc1-29bc-4733-8698-f326c7648434.PNG">

* Suchmaschine
* Metadatenregister (d.h. Katalog von Dataset, Data Service, Public Service, Nomenclature und Concept sowie des Geocat-Katalogs)
* Beschreibung Daten anhand von Metadaten
* Fachglossar

Die I14Y Interoperabilitätsplattform verwendet den Standard [DCAT-AP-CH](#DCAT-AP-CH)

Sie haben noch keine Daten auf [I14Y](https://www.i14y.admin.ch/de/home) veröffentlicht? Als [Für Erst-Publizierende](#Für-Erst-Publizierende) erklären wir Ihnen das Wichtigste rund um den Prozess und unterstützen Sie bei der Identifikation von geeigneten Daten.

### Publikationsrichtlinien 

Am Anfang steht eine gute Vorbereitung. Bevor Sie Daten als Metadaten publizieren können, müssen Sie sicherstellen, dass die Anforderungen für eine Publikation erfüllt sind. Die Richtlinien zeigen Ihnen auf welche diese Anforderungen sind.

TBD: Definition der Richtlinien.

## Publikationsprozess

In diesem Kapitel erklären wir Ihnen, wie Sie Metadaten publizieren im Metadatenkatalog von I14Y. Hier wird auf Open Government Data in standardisierter, leicht verständlicher und wiederverwendbarer Form referenziert, wodurch sich ihre Sichtbarkeit steigert. Folgende Punkte müssen Sie dabei beachten:

<img width="1116" alt="Übersicht_Publicication_Process" src="https://user-images.githubusercontent.com/115873530/196644821-a1dfa74f-1767-457c-ba1d-20435b8883cb.PNG">

1. Um Metadaten publizieren zu können, benütigen Sie (d.h. der Data Producer) Zugriff auf I14Y Admin. Das User-Management wird zentral von eIAM sichergestellt. Neue Benutzerinnen und Benutzer oder Anpassungen an den bestehenden Berechtigungen werden gemäss der Anleitung im Abschnitt [Für Erst-Publizierende](#Für-Erst-Publizierende) erfasst.

2. Sobald Sie Zugriff auf I14Y Admin haben, können Sie den gewünschten Metadatensatz im I14Y Admin erstellen.
   * Die Daten sollen als einfach nutzbare, maschinenlesbare Ressourcen aufbereitet sein, wodurch sie diese Daten rasch als Metadaten erfassen bzw. als Schnittstellen zum Abfragen im Datenkatalog bereitstellen können.
   * Bei der Erstellung wird für alle Publikationsvarianten ein Test-Ablauf in der «Abnahmeumgebung» von I14Y durchgeführt. Dies gibt datenpublizierenden Organisationen oder Personen die Möglichkeit, ihre Datasets und sämtliche weitere Informationen ausgiebig zu prüfen und allfällige Änderungen vorzunehmen. 
   * Es stehen verschiedene Datenklassen zur Verfügung, welche im Detail beschrieben werden im Abschnitt [Publikationsvariante auswählen](#Publikationsvariante-auswählen).

3. Sobald Sie den Metadatensatz erstellt haben, werden die Daten zur Qualitätssicherung durch den Swiss Data Steward (SDS) und den local Data Steward (LDS) geprüft.

4. Nachdem Sie Ihr finales Einverständnis gegeben haben, werden die Daten durch uns auf I14Y am gemeinsam definierten Go-Live Datum veröffentlicht. 

5. Sie haben die Möglichkeit, im Rahmen von Releases ihre Ressourcen und Metadaten zu aktualisieren, falls neue Daten oder Änderungen vorliegen. Das Vorgehen dazu wird erläutert im Abschnitt 

Der Swiss Data Steward (SDS) und der Local Data Steward (LDS) übernehmen das Controlling des gesamten Katalogs. Es ist allerdings an den publizierenden Organisationen oder Personen (Data Producer) sicherzustellen, dass die rechtlichen, technischen und organisatorischen Anforderungen eingehalten werden, siehe «Richtlinien».

> **Für Erst-Publizierende**

> > [Für Erst-Publizierende](#Für-Erst-Publizierende) begleiten wir Schritt für Schritt durch den Prozess. Im ersten Schritt muss sich die neue Organisation und Benutzer/innen auf eIAM registrieren. Erst danach kann der Erstellungs- und Publikationsprozess starten.

> **Für registrierte Nutzerinnen und Nutzer**

> > Wenn Sie bereits als Nutzerinnen oder Nutzer auf eIAM registriert sind, können Sie direkt zu den Inhalten für registrierte Nutzerinnen und Nutzer springen. Dort können Sie direkt die geeignete Publikationsvariante für Ihre Daten auswählen.

> > * [Publikationsprozess verstehen](#Publikationsprozess-verstehen) verstehen

> > * [Publikationsvariante auswählen](#Publikationsvariante-auswählen) auswählen

### Für Erst-Publizierende

Es freut uns, dass Sie Ihre Daten auf I14Y publizieren wollen! Jeder Eintrag auf I14Y «Dataset», «Dataservice» oder «Public Service» sowie sämtliche Benutzerinnen und Benutzer sind einer Organisation zugeteilt. Sollten Sie noch keine Daten auf I14Y publiziert haben, ist deshalb der erste Schritt, die Registrierung der Organisation und der Benutzerinnen und Benutzer auf eIAM. Nach erfolgter Registrierung können Sie  die Angaben zur Organisation vervollständigen und mit der Publikation der Datasets loslegen.

* TBD: Anleitung [eIAM](https://www.eiam.admin.ch/index.php?c=f!chlfaq!pub&l=de) 

* Login auf [I14Y](https://www.i14y.admin.ch/de/home) 

* Profil auf [I14Y](https://www.i14y.admin.ch/de/home) verwalten

### Publikationsprozess verstehen

Bevor Sie etwas publizieren können müssen Sie sich auf eIAM registriert haben. Nur mit diesem Login gelangen Sie zum Admin-Bereich auf I14Y, auf welchem Sie Metadatden erfassen und publizieren können.

Der Publikationsprozess selber besteht aus 4 Schritten. Wichtig zu wissen: Wenn Sie zum ersten Mal Daten publizieren, veröffentlichen Sie diese immer zuerst auf einer nicht-öffentlichen Umgebung, die für Test-Publikationen gedacht ist. Wir sprechen auch von «Abnahmeumgebung». Erst nach der finalen Freigabe werden die Datasets öffentlich auf I14Y publiziert, auf der sogenannten «Produktionsumgebung». Wenn Sie Daten bereits zum wiederholten Male publizieren, können Sie dies direkt in der Produktionsumgebung tun.

#### Daten publizieren – So funktioniert’s:

**1. Schritt: Publikationsvarianten auswählen**

Es gibt verschiedene [Publikationsvariante auswählen](#Publikationsvariante-auswählen), die Ihnen zur Verfügung stehen:

* [Dataset](#Dataset) manuell via Webformular erfassen

* [Dataservice](#Dataservice) via Webformular erfassen

* [Distribution](#Distribution) manuell via Webformular erfassen

* [Public Service](#Public-Service) via Webformular erfassen

* Geodaten via geocat.ch erfassen (Wichtig: Alle Geodaten müssen nach dieser Methode publiziert werden)

Gemeinsam mit der Geschäftsstelle I14Y identifizieren Sie, welche Publikationsvariante sich eignet, um einerseits Ihren Aufwand bei der Publikation zu minimieren und andererseits eine hohe Qualität der publizierten Einträge zu gewährleisten.

**2. Schritt: Metadaten auf I14Y erfassen**

Die Metadaten zu Ihren Daten können entweder manuell erfasst oder importiert werden auf I14Y, um diese den Nutzenden zur Verfügung zu stellen, so dass die publizierten Daten wiederverwendet werden können. Dieser Schritt wird je nach gewählter Methode unterschiedlich durchgeführt. Wenn Sie Ihren Datenkatalog als XML oder via Harvester importieren, müssen Ihre Datasets als XML-Datei im Format DCAT-AP-CH entweder direkt hochgeladen (XML Import) oder via URL an uns übergeben werden. Beim manuellen Erfassen sind die Felder im Admin-Bereich von I14Y direkt via Webformular auszufüllen. Nähere Informationen dazu finden Sie im Kapitel [Klassen](#Klassen) und [Publikationsvariante auswählen](#Publikationsvariante-auswählen) auswählen.

**3. Schritt: Prüfung der Daten**

Nachdem Sie alle erforderlichen Metadaten erfasst haben, ist es Zeit für Qualitätssicherung. Bei der Erstpublikation stellen wir gemeinsam sicher, dass alle Daten, Metadaten und Beschreibungen in der Abnahmeumgebung korrekt erfasst und dargestellt werden. Kontaktieren Sie uns, um die Prüfung der Daten zu planen. Durchschnittlich benötigen wir X Werktage, um die Daten und Metadaten zu prüfen.

**4. Schritt: Freigabe und Veröffentlichung**

Nachdem Sie Ihr finales Einverständnis gegeben haben, werden die Daten durch uns auf I14Y am gemeinsam definierten Go-Live Datum veröffentlicht. Dies gilt grundsätzlich nur bei der Erstpublikation. Bei wiederholten Publikationen können Sie die Veröffentlichung selbst vornehmen bzw. für ein spezifisches Datum terminieren. Benötigen Sie Unterstützung bei einer wiederholten Publikation, können Sie uns selbstverständlich jederzeit kontaktieren.

### Publikationsvariante auswählen

Um eine geeignete Publikationsvariante auszuwählen, kommt es auf die Art der Daten, den Umfang und das Aktualisierungsintervall an. Grundsätzlich sind Sie in Ihrer Wahl frei, allerdings bieten sich bei bestimmten Merkmalen bestimmte Varianten besser an. Die richtige Publikationsvariante wird gemeinsam mit uns, der Geschäftsstelle I14Y, definiert – sprechen Sie mit uns darüber. Hier finden Sie einige Richtwerte, die Ihnen bei der Wahl der Publikationsvariante helfen:

**Wenig Daten, seltene Aktualisierung:**
    - Metadaten manuell via Webformular erfassen

**Mehr als 10 Datasets, regelmässige Aktualisierung:**
    - Metadaten als XML-Datei importieren

**Grosse Anzahl Datasets, häufige Aktualisierung:**
    - Metadaten mit ??? automatisch hochladen
    
**Geodaten**
    - Geodaten sind ein Spezialfall. Um Geodaten publizieren zu können, müssen die Metadaten im Schweizer Geometadaten-Katalog geocat.ch erfasst sein. Metadaten via geocat.ch publizieren

## Aktualisierung der Daten

Nachdem Sie Daten auf I14Y publiziert haben, bleiben Sie weiterhin für Ihre Daten verantwortlich. Das umfasst genau zwei Aufgaben: Zum einen müssen Sie Ihre Daten regelmässig updaten. Zum anderen müssen Sie Anfragen von Nutzerinnen und Nutzern zu Ihren Daten beantworten.

### Daten-Updaten

Nach der Veröffentlichung kann es immer mal wieder zu Änderungen und Aktualisierungen Ihrer Metadaten kommen, beispielsweise durch die Publikation von neuen Ressourcen oder die Änderung der URL. Solche Änderungen der Metadaten müssen Sie im Admin-Bereich der Produktionsumgebung von I14Y der nachführen. Änderungen an Ihren physischen Daten müssen Sie uns nicht melden.

Wenn Sie hingegen Ihre Metadaten harvesten lassen, geschieht das Aktualisieren automatisch durch uns. Wir bitten Sie ausserdem regelmässig zu prüfen, ob Ihre Metadaten richtig bei uns ankommen. Gehen Sie dazu auf opendata.swiss und prüfen Sie die Seite Ihrer Organisation mitsamt Datasets.

### Auskunft zu Daten geben

Für das Beantworten von Fragen zu Ihren Daten sind Sie selbst verantwortlich. In jedem Dataset sind unter dem Feld «Kontaktstellen» E-Mails der Kontaktpersonen Ihrer Organisation eingetragen. Halten Sie diese Einträge bitte aktuell, damit Sie kontaktiert werden können. Allfällige Anfragen zu Ihren Daten, die direkt an I14Y gestellt werden, leiten wir an Sie weiter.

### Support und Feedback

Um die Support-Aktivitäten für Portal-Betreiber und datenpublizierende Organisationen möglichst effizient zu gestalten, wurden die wichtigsten Support-Prozesse festgelegt

TBD:

## DCAT-AP-CH

### DCAT als universelles Vokabular

Das in diesem Dokument spezifizierte Anwendungsprofil basiert auf der Spezifikation des Data Catalog Vocabulary (DCAT), das unter der Verantwortung des BFS entwickelt wurde. DCAT ist ein RDF-Vokabular, das die Interoperabilität zwischen im Web veröffentlichten Datenkatalogen erleichtern soll. Zusätzliche Klassen und Eigenschaften aus anderen bekannten Vokabularen werden bei Bedarf wiederverwendet.

Das DCAT-Vokabular besteht aus Klassen und Eigenschaften.

* Klassen sind Dinge im Internet: Nicht alle von ihnen haben URIs, aber es wird empfohlen, einen URI für sie bereitzustellen. Sie sind komplexe Dinge wie eine Person, eine Organisation, ein Datensatz, eine Website oder eine herunterladbare Datendatei.
* Klassen haben Eigenschaften: Die Eigenschaften sind die Attribute, die diese Dinge beschreiben. Einige Eigenschaften kommen in mehr als einer Klasse vor, z. B. ist ein Titel ein allgemeines Attribut. Andere Eigenschaften sind sehr speziell, wie z. B. ein Dateiformat, das nur für eine Datendatei sinnvoll ist.
* Eigenschaften können einfach oder komplex sein: Einige Eigenschaften sind Klassen. Zum Beispiel kann eine Organisation eine Website haben. Oder ein Datensatz kann einen Datenverlag haben. Im Allgemeinen kann man eine Klasse an ihrer Schreibweise erkennen: Ein Eigenschaftsname beginnt mit einem Kleinbuchstaben wie dcat:dataset , während eine Klasse mit einem Großbuchstaben wie dcat:Dataset beginnt.
Klassen und Eigenschaften werden verwendet, um die Metadaten strukturiert bereitzustellen.

### Klassen

Sowohl das Schweizerische Anwendungsprofil ("DCAT-AP CH") als auch das Europäische Anwendungsprofil ("DCAT-AP") sind um die folgenden 4 Hauptklassen herum aufgebaut:

| Klassenname | Bemerkung | URI und Referenz | 
|-------|------|---------------------------------------------------------------------|
| Katalog | Ein Katalog oder Repository, in dem die beschriebenen Datensätze oder Datendienste gespeichert sind. | [Katalog](#Katalog) |
| Dataset | Eine konzeptionelle Einheit, die die veröffentlichten Informationen darstellt. | [Dataset](#Dataset)|
| Distribution | A physical embodiment of the Dataset in a particular format. | [Distribution](#Distribution) |
| Data Service | Eine Sammlung von Vorgängen, die den Zugriff auf einen oder mehrere Datensätze oder Datenverarbeitungsfunktionen ermöglicht. | [Data Service](#Data-Service) |

The latest version of DCAT can be found [here](https://www.w3.org/TR/vocab-dcat-3/)

Im Kontext von I14Y wurde eine weitere Datenklasse hinzugefügt:

| Klassenname | Bemerkung | URI und Referenz | 
|-------|------|---------------------------------------------------------------------|
| Public Service | TBD | [Public Service](#Public-Service) |

<img width="953" alt="DCAT-Klassen" src="https://user-images.githubusercontent.com/115873530/196658047-910b1936-c023-4d50-bebe-94310c2ae687.PNG">

The la

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

