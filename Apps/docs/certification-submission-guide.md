---
ms.author: oromalle
title: Microsoft 365 Zertifizierungsübermittlungshandbuch
author: orionomalley
manager: tonybal
description: Microsoft 365 Zertifizierung bietet Unternehmen Sicherheit und Vertrauen, dass Daten und Datenschutz angemessen gesichert und geschützt sind.
keywords: App-Zertifizierungsteams Microsoft 365 Sicherheitscompliance m365
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: fd6082a482cdf5e4dc268f140b7f2a8de4d8880f
ms.sourcegitcommit: ec1d4f7013722fe672830e3664b0fb8b0f33bd37
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/12/2022
ms.locfileid: "64784524"
---
# <a name="microsoft-365-certification-submission-guide"></a>Microsoft 365 Zertifizierungsübermittlungshandbuch

**Inhalt dieses Artikels:**
- [Einführung](#introduction)
- [Voraussetzungen](#prerequisites) 
- [Microsoft 365 Zertifizierungsspezifikationsupdates](#microsoft-365-certification-specification-updates)
- [Zertifizierungsbereich](#certification-scope)
- [Zertifizierungsprozess](#certification-process)
- [Ursprüngliche Dokumentübermittlung](#initial-document-submission) 
- [Nachweiserfassungs- und Bewertungsaktivitäten](#evidence-collection-and-assessment-activities)
- [Zertifizierungskriterien](#app-certification-criteria)
- [Application Security](#application-security)
- [Betriebssicherheit](#operational-security) 
- [Datensicherheit und Datenschutz](#data-handling-security-and-privacy)
- [Überprüfung der optionalen externen Compliance-Frameworks](#optional-external-compliance-frameworks-review)
- [Anhang A](#appendix-a)
- [Anhang B](#appendix-b) 
- [Anhang C](#appendix-c) 
- [Anhang D](#appendix-d) 
- [Anhang E](#appendix-e) 
- [Anhang F](#appendix-f) 
- [Anhang G ](#appendix-g)
- [Weitere Informationen](#learn-more) 
- [Glossar](#glossary) 


## <a name="introduction"></a>Einführung

Im Rahmen des Microsoft 365 App Compliance-Programms bietet die Microsoft 365 Zertifizierung Unternehmen Sicherheit und Vertrauen, dass Daten und Datenschutz angemessen gesichert und geschützt sind, wenn Entwickler-Apps/-Add-Ins von Drittanbietern in die Microsoft 365 Plattform integriert werden. Anwendungen und Add-Ins, die die Validierung bestehen, werden **im gesamten Microsoft 365-Ökosystem Microsoft 365 zertifiziert**. 

Durch die Teilnahme am Microsoft 365 Zertifizierungsprogramm erklären Sie sich mit diesen ergänzenden Bedingungen einverstanden und müssen alle begleitenden Dokumentationen einhalten, die für Ihre Teilnahme am Microsoft 365 Zertifizierungsprogramm mit microsoft Corporation ("Microsoft", "wir", "uns" oder "unser") gelten. Sie versichern und garantieren uns, dass Sie berechtigt sind, diese ergänzenden Microsoft 365 Zertifizierungsbedingungen im Namen von sich selbst, einem Unternehmen und/oder einer anderen Entität zu akzeptieren, soweit zutreffend. Wir können diese Ergänzenden Bedingungen jederzeit ändern, ändern oder kündigen. Ihre fortgesetzte Teilnahme am Microsoft 365 Zertifizierungsprogramm nach jeder Änderung oder Änderung bedeutet, dass Sie den neuen ergänzenden Bedingungen zustimmen. Wenn Sie den neuen ergänzenden Bedingungen nicht zustimmen oder diese ergänzenden Bedingungen kündigen, müssen Sie die Teilnahme am Microsoft 365 Zertifizierungsprogramm beenden.

Dieses Dokument richtet sich an ISVs (Independent Software Vendors), um Informationen über den Microsoft 365 Zertifizierungsprozess, Voraussetzungen für den Beginn des Prozesses und Details zu bestimmten Sicherheitskontrollen bereitzustellen, die ISVs besitzen müssen.  Allgemeine Informationen zum Microsoft 365 App Compliance-Programm finden Sie auf der [Seite](../overview.md) Microsoft 365 App Compliance-Programm. 

> [!IMPORTANT]
> Derzeit gilt Microsoft 365 Zertifizierung für alle:
>* Microsoft Teams Anwendungen (Registerkarten, Bots usw.) .
>* SharePoint-Apps/-Add-Ins
>* Office-Add-Ins (Word, Excel, PowerPoint, Outlook, Project, OneNote)
>* Webapps

## <a name="prerequisites"></a>Voraussetzungen

### <a name="publisher-attestation"></a>Herausgebernachweis

Bevor Sie den Microsoft 365 Zertifizierungsprozess erhalten, müssen Sie Publisher Nachweis abgeschlossen haben. Sie können jedoch den Microsoft 365 Zertifizierungsprozess starten, bevor Sie Publisher Nachweis abschließen.  

### <a name="read-the-microsoft-365-certification-specification"></a>Lesen Der Microsoft 365-Zertifizierungsspezifikation

Microsoft empfiehlt allen ISVs (Independent Software Vendor), diese Microsoft 365 Zertifizierungsspezifikation vollständig zu lesen, um sicherzustellen, dass alle anwendbaren Steuerelemente von der In-Scope-Umgebung und der App/dem Add-In erfüllt werden. Dies trägt dazu bei, einen reibungslosen Bewertungsprozess sicherzustellen.

## <a name="microsoft-365-certification-specification-updates"></a>Microsoft 365 Zertifizierungsspezifikationsupdates 

Updates der Microsoft 365 Zertifizierungsspezifikation werden ungefähr alle sechs bis zwölf Monate erwartet. Diese Updates können neue Zielsicherheitsdomänen und/oder Sicherheitskontrollen einführen. Updates basieren auf Entwicklerfeedback, Änderungen der Bedrohungslandschaft und zur Erhöhung der Sicherheitsbaseline des Programms, sobald es reift. 

ISVs, die bereits mit der Microsoft 365 Zertifizierungsbewertung begonnen haben, können die Bewertung mit der Version der Microsoft 365 Zertifizierungsspezifikation fortsetzen, die beim Starten der Bewertung gültig war. Alle neuen Einreichungen, einschließlich der jährlichen Rezertifizierung, müssen anhand der veröffentlichten Version bewertet werden.

> [!NOTE]
> Sie müssen nicht alle Steuerelemente in dieser Microsoft 365 Zertifizierungsspezifikation einhalten, um eine Zertifizierung zu erhalten. Für jede der sicherheitsrelevanten Domänen, die in dieser Microsoft 365 Zertifizierungsspezifikation behandelt werden, gelten jedoch übergabeschwellenwerte (die nicht offengelegt werden). Einige Steuerelemente werden als "**Harter Fehler**" klassifiziert, was bedeutet, dass das Fehlen dieser Sicherheitskontrollen zu einer fehlgeschlagenen Bewertung führt. 

## <a name="certification-scope"></a>Zertifizierungsbereich

Die **Bereichsumgebung** ist die Umgebung, die die Bereitstellung des App-/Add-In-Codes unterstützt und alle Back-End-Systeme unterstützt, mit denen die App/das Add-In möglicherweise kommuniziert. Alle zusätzlichen verbundenen Umgebungen werden ebenfalls in den Bereich einbezogen, es sei denn, eine angemessene Segmentierung ist vorhanden, und die verbundenen Umgebungen können sich nicht auf die Sicherheit der In-Scope-Umgebung auswirken. Alle Notfallwiederherstellungsumgebungen müssen ebenfalls in den Anwendungsbereich der Bewertung einbezogen werden, da diese Umgebungen erforderlich wären, um den Dienst zu erfüllen, falls etwas mit der primären Umgebung geschieht.  Die  **termin-Scope-Systemkomponenten**  verweisen auf **ALLE** Geräte und Systeme, die in der In-Scope-Umgebung verwendet werden. In-Scope-Komponenten umfassen, sind aber nicht beschränkt auf:
* Die Webanwendung(en).
* Server.
* Firewalls (oder gleichwertig).
* Schalter.
* Lastenausgleichsgeräte.
* Virtuelle Infrastruktur.
* Webverwaltungsportale für Cloudanbieter 

> [!IMPORTANT]
> Die In-Scope-Umgebung muss über ein DMZ verfügen, und die unterstützende Umgebung der App/des Add-Ins muss aus den internen Geschäftssystemen und Unternehmensumgebungen segmentiert werden, wodurch der Umfang der Bewertungsaktivitäten nur auf die In-Scope-Systeme beschränkt wird. Zertifizierungsanalysten werden während der Bewertung Segmentierungstechniken überprüfen und Penetrationstestberichte überprüfen, die Tests enthalten sollten, um die Effektivität aller verwendeten Segmentierungstechniken zu überprüfen.

### <a name="infrastructure-as-a-service-iaas-platform-as-a-service-paas-and-software-as-a-service-saas"></a>Infrastructure as a Service (IaaS), Platform as a Service (PaaS) und Software as a Service (SaaS) 
Wenn IaaS und/oder PaaS verwendet werden, um die Infrastruktur der zu überprüfenden Bereitstellung von Anwendungs- oder Add-In-Code zu unterstützen, ist der Cloudplattformanbieter für einige der während des Zertifizierungsprozesses bewerteten Sicherheitskontrollen verantwortlich. Aus diesem Grund müssen Zertifizierungsanalysten durch externe Complianceberichte wie [PCI DSS] Attestation of Compliance (AOC), ISO27001 oder [SOC 2] Type II vom Anbieter der Cloudplattform unabhängige externe Überprüfungen der bewährten Sicherheitsmethoden erhalten. 

Anhang F enthält Details dazu, welche Sicherheitskontrollen wahrscheinlich anwendbar sind, basierend auf den folgenden Bereitstellungstypen und basierend darauf, ob die App/das Add-In M365-Daten exfiltriert oder nicht: 
* ISV Hosted 
* IaaS Hosted 
* PaaS/Serverless Hosted 
* Hybrid gehostet 
* Freigegeben gehostet 

Wenn IaaS oder PaaS bereitgestellt wird, müssen Sie nachweisen, dass die Umgebung innerhalb dieser Bereitstellungstypen gehostet wird.

### <a name="sampling"></a>Probenahme

Die Anforderung von Nachweisen zur Unterstützung der Zertifizierungsbewertung sollte auf einer Stichprobe der bereichsbezogenen Systemkomponenten unter Berücksichtigung verschiedener Betriebssysteme, primärer Funktion des Geräts und verschiedener Gerätetypen basieren. Zu Beginn des Zertifizierungsprozesses wird eine geeignete Stichprobe ausgewählt. Die folgende Tabelle sollte als Leitfaden für die Größe des Beispiels verwendet werden:

|Bevölkerungsgröße              | Beispiel                  |
|---------------------------- |-------------------------|
|<5|1|
|>5 & <10|2|
|>9 & <25|3|
|>24|4|

> [!NOTE]
>Wenn Abweichungen zwischen geräten identifiziert werden, die in der ersten Stichprobe enthalten sind, kann die Stichprobengröße während der Bewertung erhöht werden. 

## <a name="certification-process"></a>Zertifizierungsprozess

Bevor Sie den Zertifizierungsprozess starten, müssen Sie Ihren Publisher Nachweis erfolgreich abgeschlossen haben. Nach Abschluss des Microsoft 365 Zertifizierungsprozesses gehen Sie wie folgt vor:

### <a name="preparation"></a>Vorbereitung
1. Navigieren Sie zum Partner Center, und überprüfen Sie Ihre abgeschlossene [Publisher Dokumentation zum Nachweis](../docs/attestation.md). Bei Bedarf können Sie Ihre Antworten bearbeiten und aktualisieren. Wenn Sie dies tun, müssen Sie ihre Nachweisdokumentation jedoch erneut zur Genehmigung übermitteln. Wenn Ihre Übermittlung älter als drei Monate ist, müssen Sie Publisher Nachweis erneut zur Überprüfung und Überprüfung übermitteln. 
1. Lesen Sie sorgfältig den [Microsoft 365 Zertifizierungsübermittlungsleitfaden](../docs/certification-submission-guide.md) durch, um zu verstehen, was von Ihnen verlangt wird. Stellen Sie sicher, dass Sie die im Microsoft 365 Zertifizierungsübermittlungshandbuch angegebenen [Steuerungsanforderungen](../docs/certification-submission-guide.md#app-certification-criteria) erfüllen können.
1. Klicken Sie im Partner Center auf "Zertifizierung starten". Dadurch gelangen Sie zu Ihrem ursprünglichen Dokumentübermittlungsportal. Übermitteln Sie Ihre [ursprüngliche Dokumentübermittlung](../docs/certification-submission-guide.md#initial-document-submission). Dies hilft uns zu bestimmen, was für Ihre Bewertung im Rahmen ist, basierend auf der Architektur Ihrer App und der Verarbeitung von Kundendaten. Überprüfen Sie diese Seite häufig, um festzustellen, ob Ihre Übermittlung akzeptiert wurde.

>[!NOTE]
>Für alle Office-Apps können Sie auf unser [Benutzerhandbuch für Office-Apps](../docs/userguide.md) verweisen. Für alle WebApps können Sie auf unser [SaaS-App-Benutzerhandbuch](../docs/saasuserguide.md) verweisen.

### <a name="assessment"></a>Bewertung
1. Sobald Die erste Dokumentübermittlung akzeptiert wurde, wird die für Ihre App erforderliche Sicherheitssteuerung automatisch im Portal angezeigt. Sie müssen dann nachweisen, dass jedes Steuerelement vorhanden ist. Denken Sie daran, dass Sie **60 Tage** zeit erhalten, um alle Nachweise einzureichen. Ein Analyst überprüft Ihre Nachweise und genehmigt entweder das Steuerelement oder fordert neue oder zusätzliche Nachweise an. Überprüfen Sie diese Seite häufig, um festzustellen, ob Ihre Nachweise akzeptiert wurden.
### <a name="certification"></a>Zertifizierung
1. Nachdem Ihre Übermittlung von einem Analysten überprüft wurde, werden Sie über Ihre Zertifizierungsentscheidung benachrichtigt. Apps, die eine Zertifizierung erhalten, erhalten ein Badge für ihre Anwendung in **AppSource** und **Microsoft-Dokumentationsseiten** . Die vollständigen Vorteile der Zertifizierung finden Sie [hier](../docs/enterprise-app-certification-guide.md#program-benefits).

## <a name="review-and-re-certification"></a>Überprüfen und erneute Zertifizierung
Für den Fall, dass Ihre Bewerbung zu einem beliebigen Zeitpunkt [wesentliche Änderungen](../docs/certification-submission-guide.md#significant-changes) durchläuft, müssen Sie uns benachrichtigen.

Außerdem müssen Sie die Rezertifizierung auf jährlicher Basis durchlaufen. Dies erfordert die Erneutvalidierung der In-Scope-Steuerelemente für Ihre aktuelle Umgebung. Dieser Vorgang kann bis zu 90 Tage vor Ablauf Ihrer Zertifizierung beginnen. Ihre vorhandene Zertifizierung läuft nicht während des Rezertifizierungszeitraums ab. Die Erneute Zertifizierung über alle Programme hinweg läuft am 1-jährigen Bestehen Ihrer Microsoft 365-Zertifizierung ab.

Wenn Ihre Zertifizierung nicht vor dem Ablaufdatum verlängert wird, wird der Zertifizierungsstatus Ihrer Apps widerrufen. Alle Badging-, Symbole- und zugehörige Zertifizierungsbrandings werden aus Ihrer App entfernt, und Sie dürfen Ihre App nicht als Microsoft 365 zertifiziert anzeigen.


> [!IMPORTANT]
> **Übermittlungszeitrahmen:** Es wird erwartet, dass der Bewertungsprozess im Durchschnitt 30 Tage dauern sollte, vorausgesetzt, Sie können Ihren Übermittlungsstatus häufig überprüfen und rechtzeitig auf Kommentare und ergänzende Beweisanträge reagieren. Nach Dem Starten des Zertifizierungsprozesses ist es maximal 60 Tagen erlaubt, die Bewertung abzuschließen. Wenn nicht alle Übermittlungen innerhalb des Zeitraums von 60 Tagen abgeschlossen wurden, wird der Übermittlung ein Fehler ausgegeben, und der Prozess muss erneut gestartet werden. Diese Ergebnisse werden nicht veröffentlicht.


## <a name="initial-document-submission"></a>Ursprüngliche Dokumentübermittlung


Die anfängliche Dokumentenübermittlung hilft Zertifizierungsanalysten bei der Durchführung von Bereichsdefinitionen und bei der Ermittlung des Umfangs Ihrer Bewertung. Danach müssen Sie unterstützende Unterlagen und Nachweise übermitteln, die für die Durchführung der Bewertung verwendet werden. Ihre anfängliche Übermittlung muss die unten angegebenen Informationen enthalten. Weitere Anleitungen finden Sie [im Initital document Subnmission Guide](../docs/initialdocumentsubguide.md).

| **DocumentationOverview&nbsp;**     |   **Dokumentationsdetails**  |
| -------------------------| -----------------------------|
|**App-/Add-In-Beschreibung** | Eine Beschreibung des Zwecks und der Funktionalität der App/des Add-Ins. Dies sollte dem Zertifizierungsanalysten ein gutes Verständnis dafür vermitteln, wie die App/Das Add-In funktioniert und wie sie verwendet werden soll.
|**Penetrationstestbericht** |Ein Penetrationstestbericht wurde innerhalb der letzten 12 Monate abgeschlossen. Dieser Bericht muss die Umgebung enthalten, die die Bereitstellung der App/add unterstützt, sowie alle zusätzlichen Umgebungen, die den Betrieb der App/des Add-Ins unterstützen. **Hinweis:** Wenn Sie keine jährlichen Penetrationstests durchführen, können Sie diese im Rahmen des Zertifizierungsprozesses durchführen lassen.|
|**Architekturdiagramme**|Ein logisches Architekturdiagramm, das eine allgemeine Übersicht über die unterstützende Infrastruktur Ihrer App/Ihres Add-Ins darstellt. Dazu müssen **alle** Hostingumgebungen und die unterstützende Infrastruktur gehören, die die App/das Add-In unterstützt. Dieses Diagramm MUSS alle verschiedenen unterstützenden Systemkomponenten in der Umgebung darstellen, um Zertifizierungsanalysten dabei zu unterstützen, Systeme im Umfang zu verstehen und stichprobenartig zu ermitteln. Bitte geben Sie auch an, welcher Hostingumgebungstyp verwendet wird; ISV Hosted, IaaS, PaaS oder Hybrid. **Hinweis:** Wo SaaS verwendet wird, geben Sie bitte die verschiedenen SaaS-Dienste an, die verwendet werden, um die unterstützenden Dienste innerhalb der Umgebung bereitzustellen.|
|**Öffentlicher Fußabdruck** | Details **aller** öffentlichen IP-Adressen und URLs, die von der unterstützenden Infrastruktur verwendet werden. Dies muss den vollständigen routingfähigen IP-Bereich umfassen, der der Umgebung zugeordnet ist, es sei denn, es wurde eine angemessene Segmentierung implementiert, um den verwendeten Bereich aufzuteilen (angemessene Nachweise für die Segmentierung sind erforderlich).|
|**Datenflussdiagramme** |Flow Diagramme mit den folgenden Details:
||&#x2713; M365-Daten fließen in und aus der App/dem Add-In (einschließlich [EUII](#euii) und [OII](#oii) ).|
||&#x2713; M365-Datenflüsse innerhalb der unterstützenden Infrastruktur (sofern zutreffend)|
||&#x2713; Diagramme, in denen hervorgehoben wird, wo und welche Daten gespeichert werden, wie Daten an externe Dritte weitergegeben werden (einschließlich Details zu welchen Dritten) und wie Daten bei der Übertragung über offene/öffentliche Netzwerke und ruhende Netzwerke geschützt werden.|
|**API-Endpunktdetails**| Eine vollständige Auflistung aller API-Endpunkte, die von Ihrer App verwendet werden. Um den Umgebungsbereich zu verstehen, stellen Sie API-Endpunktspeicherorte in Ihrer Umgebung bereit.                                
|**Microsoft-API-Berechtigungen**| Bereitstellen einer Dokumentation mit **allen** Microsoft-APIs, die verwendet werden, zusammen mit den Berechtigungen, die für die Funktion der App/des Add-Ins angefordert werden, zusammen mit einer Begründung für die angeforderten Berechtigungen|
|**Datenspeichertypen** |Datenspeicherung und -verarbeitung von Dokumenten, die Folgendes beschreiben:|
||&#x2713; Inwieweit Ihre Kunden M365 Data [EUII](#euii) und [OII](#oii) empfangen und gespeichert werden|
||&#x2713; Der Zeitraum für die Datenaufbewahrung.|
||&#x2713; Warum die M365-Kundendaten erfasst werden.|
||&#x2713; Wo M365-Kundendaten gespeichert werden (sollten in den oben angegebenen Datenflussdiagrammen enthalten sein).|
|**Bestätigung der Compliance**|Unterstützende Dokumentation für externe Sicherheitsframeworks, die in der Übermittlung Publisher Nachweises enthalten sind oder bei der Überprüfung Microsoft 365 Zertifizierungssteuerelemente berücksichtigt werden sollen. Derzeit werden die folgenden drei Unterstützt:|
||&#x2713; [PCI DSS-Konformitätsnachweis](#pci-dss) (AOC).|
||&#x2713; [SOC 2-Berichte](#soc-2) vom Typ I/Typ II.|
||&#x2713; [ISMSIEC](#isms) /  - 1S0/IEC 27001 Statement of Applicability (SoA) und Zertifizierung.[](#iec)|
|**Webabhängigkeiten**|Dokumentation, in der alle Abhängigkeiten aufgeführt sind, die von der App/dem Add-In mit den aktuellen ausgeführten Versionen verwendet werden.|
|**Softwareinventur**|Ein aktueller Softwarebestand, der die gesamte in der Bereichsumgebung verwendete Software zusammen mit den Versionen enthält.|
|**Hardwareinventur**| Ein aktueller Hardwarebestand, der von der unterstützenden Infrastruktur verwendet wird. Dies wird verwendet, um beim Sampling bei der Durchführung der Bewertungsphase zu helfen. Wenn Ihre Umgebung PaaS enthält, stellen Sie Details zu den genutzten Diensten bereit.|

## <a name="evidence-collection-and-assessment-activities"></a>Nachweiserfassungs- und Bewertungsaktivitäten

Zertifizierungsanalysten müssen die Nachweise für alle Systemkomponenten innerhalb des definierten Beispielsatzes überprüfen. Zu den Arten von Nachweisen, die zur Unterstützung des Bewertungsprozesses erforderlich sind, gehören eine oder alle der folgenden:

**Beweissammlung**

* Erste Dokumentation, hervorgehoben im Abschnitt ["Ursprüngliche Dokumentationsübermittlung](#initial-document-submission) " oben 
* Richtliniendokumente 
* Verarbeiten von Dokumenten 
* Systemkonfigurationseinstellungen 
* Tickets ändern 
* Ändern von Steuerelementdatensätzen 
* Systemberichte

Es werden verschiedene Methoden verwendet, um die für den Abschluss des Bewertungsprozesses erforderlichen Nachweise zu sammeln.  Diese Beweissammlung kann folgendermaßen erfolgen: 
* Dokumente 
* Screenshots 
* Interviews 
* Bildschirmsharing 

Die verwendeten Methoden für die Beweissammlung werden während des Bewertungsprozesses bestimmt. Konkrete Beispiele für die in Ihrer Übermittlung erforderlichen Nachweise finden Sie im [Beispielnachweishandbuch](../docs/certification-sample-evidence-guide.md).

**Bewertungsaktivitäten**

Zertifizierungsanalysten überprüfen die von Ihnen bereitgestellten Nachweise, um festzustellen, ob Sie die Kontrollen in dieser Microsoft 365 Zertifizierungsspezifikation angemessen erfüllt haben. 

Wenn möglich, und um den Zeitaufwand für den Abschluss der Bewertung zu verringern, sollten alle oder alle dokumentationen, die in  [derInitial Documentation Submissions](#initial-document-submission)  beschrieben sind, im Voraus bereitgestellt werden.

Zertifizierungsanalysten werden zunächst die Nachweise aus der ursprünglichen Dokumentationsübermittlung und die Publisher Nachweisinformationen überprüfen, um die geeigneten Untersuchungslinien, die Stichprobengröße und die Notwendigkeit weiterer Nachweise zu ermitteln, wie oben beschrieben.  Zertifizierungsanalysten analysieren alle gesammelten Informationen, um Schlussfolgerungen darüber zu ziehen, wie und ob Sie die Kontrollen in dieser Microsoft 365 Zertifizierungsspezifikation erfüllen. 

## <a name="app-certification-criteria"></a>App-Zertifizierungskriterien

Ihre App, die unterstützende Infrastruktur und die unterstützende Dokumentation werden in den folgenden Sicherheitsdomänen bewertet:

1. [**Application Security**](#application-security)
1. [**Betriebssicherheit/sichere Bereitstellung**](#operational-security)
1. [**Datensicherheit und Datenschutz**](#data-handling-security-and-privacy)

Jede dieser Sicherheitsdomänen enthält bestimmte Schlüsselsteuerelemente, die eine oder mehrere spezifische Anforderungen umfassen, die im Rahmen des Bewertungsprozesses ausgewertet werden. Um sicherzustellen, dass Microsoft 365 Zertifizierung für Entwickler aller Größen inklusiv ist, wird jede der Sicherheitsdomänen mithilfe eines Bewertungssystems bewertet, um eine Gesamtbewertung aus jeder der Domänen zu ermitteln. Die Bewertungen für jedes der Microsoft 365 Zertifizierungssteuerelemente werden basierend auf dem wahrgenommenen Risiko, dass dieses Steuerelement nicht erfüllt wird, zwischen 1 (niedrig) und 3 (hoch) zugeordnet. Jede der Sicherheitsdomänen weist eine Mindestprozentsatzmarkierung auf, die als Bestanden gilt. Bestimmte Elemente dieser Spezifikation umfassen einige automatische Fehlerkriterien:

- API-Berechtigungen folgen nicht dem Prinzip der geringsten Rechte (PoLP).  
- Kein Penetrationstestbericht, wenn er erforderlich ist.
- Keine Schutzmaßnahmen gegen Schadsoftware
- Die mehrstufige Authentifizierung wird nicht zum Schutz des Administrativen Zugriffs verwendet.  
- Keine Patchprozesse.  
- Kein geeigneter [Datenschutzhinweis zur DSGVO](#gdpr) .  

## <a name="application-security"></a>Application Security

Die Anwendungssicherheitsdomäne konzentriert sich auf die folgenden drei Bereiche: 
* GraphAPI-Berechtigungsüberprüfung 
* Überprüfungen der externen Konnektivität
* Anwendungssicherheitstests 

### <a name="graphapi-permission-validation"></a>GraphAPI-Berechtigungsüberprüfung

Die GraphAPI-Berechtigungsüberprüfung wird durchgeführt, um zu überprüfen, ob die App/das Add-In keine überforderten Berechtigungen anfordert. Dazu wird manuell überprüft, welche Berechtigungen angefordert werden. Zertifizierungsanalysten verweisen auf diese Prüfungen mit der Übermittlung des Publisher-Nachweises und bewerten die angeforderte Zugriffsebene, um sicherzustellen, dass die Praktiken der "geringsten Rechte" eingehalten werden. Wenn Zertifizierungsanalysten glauben, dass diese Praktiken mit den geringsten Rechten nicht erfüllt werden, werden Zertifizierungsanalysten eine offene Diskussion mit Ihnen führen, um die geschäftliche Begründung für die angeforderten Berechtigungen zu überprüfen. Alle Abweichungen gegenüber Ihrer Publisher Während dieser Überprüfung gefundenen Nachweisübermittlung erhalten auch Feedback, damit Ihr Publisher Nachweis aktualisiert werden kann. 

### <a name="external-connectivity-checks"></a>Überprüfungen der externen Konnektivität

Im Rahmen der Bewertung führt ein Analyst einen einfachen Rundgang durch die Anwendungsfunktionen durch, um Verbindungen außerhalb von M365 zu identifizieren.  Alle Verbindungen, die nicht als Microsoft oder direkte Verbindungen mit Ihrem Dienst identifiziert werden, werden während der Bewertung gekennzeichnet und diskutiert.

### <a name="application-security-testing"></a>Anwendungssicherheitstests

Eine angemessene Überprüfung der Risiken, die mit Ihrer App/Ihrem Add-In und der unterstützenden Umgebung verbunden sind, ist von entscheidender Bedeutung, um Kunden die Sicherheit der App/des Add-Ins zu gewährleisten. Anwendungssicherheitstests in Form von Penetrationstests MÜSSEN durchgeführt werden, wenn Ihre Anwendung über Verbindungen mit diensten verfügt, die nicht von Microsoft veröffentlicht wurden. Wenn Ihre App eigenständig ohne Verbindung mit einem Nicht-Microsoft-Dienst oder -Back-End ausgeführt wird, ist kein Penetrationstest erforderlich.


**Penetrationstestbereich**

Penetrationstests **müssen** in der Live-Produktionsumgebung durchgeführt werden, die die Bereitstellung der App/des Add-Ins unterstützt (z. B. wo der App-/Add-In-Code gehostet wird, der in der Regel die Ressource in der Manifestdatei ist) zusammen mit jeder zusätzlichen Umgebung, die den Betrieb der App/des Add-Ins unterstützt (z. B. wenn die App/das Add-In mit anderen Webanwendungen außerhalb von Microsoft 365 spricht).  Bei der Definition des Bereichs muss darauf geachtet werden, dass alle "verbundenen" Systeme oder Umgebungen, die sich auf die Sicherheit der In-Scope-Umgebung auswirken können, auch in ALLE Penetrationstestaktivitäten einbezogen werden. 

Wenn Techniken verwendet werden, um die umgebungsbezogenen Umgebungen aus anderen Umgebungen zu segmentieren, MÜSSEN Penetrationstests die Effektivität dieser Segmentierungstechniken überprüfen. Dies muss im Penetrationstestbericht detailliert beschrieben werden. 

Penetrationstestberichte werden überprüft, um sicherzustellen, dass keine Sicherheitsrisiken vorhanden sind, die die  **folgendenautomatischen Fehlerkriterien** erfüllen, die in den folgenden Steuerelementen beschrieben sind.
 
**Anforderungen für Penetrationstests**


|**Kriterientyp**|**Penetrationstest-Steuerelemente**|
| -------------------------|-----------------------------|
|**Allgemeine Kriterien**| **Controls**|
|| Anwendungs- und Infrastrukturdurchdringungstests **MÜSSEN** jährlich (alle 12 Monate) und von einem seriösen unabhängigen Unternehmen durchgeführt werden. |
|| Die Behebung identifizierter kritischer und hoch riskanter Sicherheitsrisiken **MUSS** innerhalb eines Monats nach Abschluss der Penetrationstests oder früher, je nach dokumentierten Patchingprozess, abgeschlossen werden. |
|| Der vollständige externe Speicherbedarf (IP-Adressen, URLs, API-Endpunkte usw.) MUSS in den Bereich der Penetrationstests einbezogen werden und muss im Penetrationstestbericht dokumentiert werden. |
|| Webanwendungsdurchdringungstests MÜSSEN alle Sicherheitsklassen enthalten; beispielsweise die aktuellste OWASP Top 10 oder SANS Top 25 CWE. |
|| Ein Erneuter Test der identifizierten Sicherheitsrisiken durch das Unternehmen für Penetrationstests ist nicht erforderlich – Abhilfemaßnahmen und Selbstüberprüfungen sind jedoch ausreichend, ausreichende Nachweise, um eine ausreichende Behebung nachzuweisen **, MÜSSEN** während der Bewertung bereitgestellt werden.|
|**Kriterien für automatische Fehler:**|**Controls**|
|| Vorhandensein eines nicht unterstützten Betriebssystems. |
|| Vorhandensein standardmäßiger, aufzählbarer oder erratener Verwaltungskonten.|
|| Vorhandensein von SQL Injektionsrisiken.|
|| Vorhandensein von websiteübergreifendem Skripting.|
|| Vorhandensein von Sicherheitslücken beim Durchlaufen von Verzeichnissen (Dateipfad).|
|| Vorhandensein von HTTP-Sicherheitsrisiken, z. B. Headerantwortaufteilung, Anforderungsschmuggel und Desync-Angriffe.|
|| Vorhandensein der Offenlegung von Quellcode ( [einschließlichLFI](#lfi)).|
|| Alle kritischen oder hohen Werte gemäß den CVSS-Patchverwaltungsrichtlinien.|
|| Jede erhebliche technische Sicherheitsanfälligkeit, die leicht ausgenutzt werden kann, um eine große Menge an EUII oder OUI zu kompromittieren.|






> [!IMPORTANT]
>Berichte müssen in der Lage sein, genügend Sicherheit zu bieten, dass alles, was im Abschnitt "Anwendungssicherheitstestspezifikation" beschrieben ist, veranschaulicht werden kann.


**Anforderungen und Regeln für kostenlose Penetrationstests**

- Für ISVs, die derzeit keine Penetrationstests durchführen, können Penetrationstests kostenlos Microsoft 365 Zertifizierung durchgeführt werden. Microsoft wird die Kosten für einen Penetrationstest für bis zu 12 Tage manueller Tests anordnen und decken. Die Kosten für Penetrationstests werden basierend auf der Anzahl der Tage berechnet, die zum Testen der Umgebung erforderlich sind. Alle Aufwendungen, die mehr als 12 Testtage überschreiten, fallen in die Verantwortung des ISV. 
- ISVs müssen vor dem Durchgeführten Penetrationstest Nachweise einreichen und die Genehmigung für 50 % der kontrollen im Gültigkeitsbereich erhalten. Um zu beginnen, füllen Sie einfach Ihre ursprüngliche Dokumentübermittlung aus, und wählen Sie aus, dass Penetrationstests als Teil Ihrer Bewertung einbezogen werden sollen. Wenn Sie 50 % der Steuerelemente abgeschlossen haben, werden Sie kontaktiert, um den Umfang zu erreichen und Ihren Penetrationstest zu planen.
- Der nach Abschluss des Pentest ausgestellte Bericht wird dem ISV zur Verfügung gestellt, sobald er die Zertifizierung abgeschlossen hat. Dieser Bericht zusammen mit Ihrer Microsoft 365 Zertifizierung kann verwendet werden, um potenziellen Kunden zu zeigen, dass Ihre Umgebung sicher ist.
- ISVs werden auch dafür verantwortlich sein, zu zeigen, dass im Penetrationstest identifizierte Sicherheitsrisiken vor einer Zertifizierung behoben wurden, aber keinen sauberen Bericht erstellen müssen.

Sobald ein Penetrationstest angeordnet ist, ist der ISV für gebührenpflichtigen Umplanungen und Stornierungen wie folgt verantwortlich:

| **Zeitskala für Neuberechnungsgebühren** | **Anteil zahlbar** |
|------------------|------------------------|
| Erneutes Planen der Anforderung, die mehr als 30 Tage vor dem geplanten Startdatum empfangen wurde. | 0% zahlbar |
| Erneutes Planen der Anforderung, die 8 bis 30 Tage vor dem geplanten Startdatum empfangen wurde. | 25% Zahlbar |
| Planen Sie die Anfrage, die innerhalb von 2 bis 7 Tagen vor dem geplanten Startdatum empfangen wurde, mit einem festen Neubuchungsdatum.| 50% zahlbar |
| Erneutes Planen der Anforderung, die weniger als 2 Tage vor dem Startdatum empfangen wurde. | 100% Zahlbar |

| **Zeitskala für Stornierungsgebühren** | **Anteil zahlbar** |
|------------------|------------------------|
| Die Stornierungsanforderung wurde mehr als 30 Tage vor dem geplanten Startdatum empfangen. | 25% Zahlbar |
| Die Stornierungsanforderung wurde 8 bis 30 Tage vor dem geplanten Startdatum empfangen. | 50% zahlbar |
| Stornierungsanforderung, die innerhalb von 7 Tagen vor dem geplanten Startdatum empfangen wurde. | 90% Zahlbar |

## <a name="operational-security"></a>Betriebssicherheit

Diese Domäne misst die Ausrichtung der unterstützenden Infrastruktur- und Bereitstellungsprozesse Ihrer App mit bewährten Methoden für die Sicherheit.

### <a name="controls"></a>Steuerelemente

|**Steuerelementfamilie**| **Controls**|
| ------------------------|------------------------------ |
| **Schutz vor Schadsoftware – Antivirus**|Stellen Sie Eine Richtliniendokumentation bereit, die die Praktiken und Verfahren von Antivirensoftware regelt.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass Antivirensoftware auf allen getesteten Systemkomponenten ausgeführt wird.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass Antivirensignaturen in allen Umgebungen (innerhalb von 1 Tag) auf dem neuesten Stand sind.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass Antivirensoftware so konfiguriert ist, dass eine Überprüfung bei Zugriff oder eine regelmäßige Überprüfung über alle beispielbasierten Systemkomponenten hinweg durchgeführt wird. Hinweis: Wenn die Überprüfung bei Zugriff nicht aktiviert ist, muss mindestens die tägliche Überprüfung und Benachrichtigung aktiviert sein.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass Antivirensoftware so konfiguriert ist, dass Schadsoftware oder Quarantäne automatisch blockiert wird und alle systemspezifischen Komponenten benachrichtigt werden.|
|**Anwendungssteuerelemente**: NUR erforderlich, wenn herkömmliche Antischadsoftware nicht verwendet wird|Stellen Sie nachweisbare Nachweise dafür bereit, dass Anwendungen vor der Bereitstellung genehmigt wurden.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass eine vollständige Liste der genehmigten Anwendungen mit geschäftlicher Begründung vorhanden und verwaltet wird.|
||Stellen Sie unterstützende Dokumentationen bereit, in denen beschrieben wird, dass die Anwendungskontrolle software so konfiguriert ist, dass sie bestimmte Anwendungssteuerungsmechanismen erfüllt. (Beispiel: Zulässige Auflistung: Beispiel1, Beispiel3, Codesignatur)|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass die Anwendungssteuerung wie aus allen beispielierten Systemkomponenten dokumentiert konfiguriert ist.|
|**Patch-Management – Risikorangfolge**| Bereitstellungsrichtliniendokumentation, die bestimmt, wie neue Sicherheitslücken identifiziert und einer Risikobewertung zugewiesen werden.|
||Stellen Sie nachweisen, wie neue Sicherheitslücken identifiziert werden.|
||Stellen Sie Nachweise bereit, die belegen, dass allen Sicherheitsrisiken nach der Identifizierung eine Risikorangfolge zugewiesen wird.|
|**Patch-Managmeent - Patchen**|Bereitstellung einer Richtliniendokumentation für das Patchen von in-Scope-Systemkomponenten, die einen geeigneten minimalen Patchzeitrahmen für kritische, hohe und mittlere Sicherheitsrisiken umfasst; und Außerbetriebnahme von nicht unterstützten Betriebssystemen und Software.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass alle in die Stichprobe einbezogenen Systemkomponenten gepatcht werden.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass nicht unterstützte Betriebssysteme und Softwarekomponenten nicht in der Umgebung verwendet werden.|
|**Überprüfung von Sicherheitsrisiken**|Stellen Sie die vierteljährlichen Berichte zur Überprüfung von Sicherheitsrisiken in Infrastruktur und Webanwendungen bereit. Die Überprüfung muss für den gesamten öffentlichen Fußabdruck (IP-Adressen und URLs) und interne IP-Bereiche durchgeführt werden.|
||Stellen Sie nachweisbare Nachweise bereit, dass die Behebung von Sicherheitsrisiken, die während der Überprüfung von Sicherheitsrisiken erkannt wurden, im Einklang mit Ihrem dokumentierten Patching-Zeitrahmen gepatcht werden.|
|**Firewalls**|Stellen Sie Richtliniendokumentation bereit, die Die Firewallverwaltungspraktiken und -verfahren regelt.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass alle standardmäßigen Administratoranmeldeinformationen vor der Installation in Produktionsumgebungen geändert werden.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass Firewalls an der Grenze der Bereichsumgebung installiert und zwischen dem Umkreisnetzwerk (auch als DMZ, demilitarisierte Zone und überwachtes Subnetz bezeichnet) und internen vertrauenswürdigen Netzwerken installiert werden.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass der gesamte öffentliche Zugriff in der demilitarisierten Zone (DMZ) beendet wird.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass der gesamte datenverkehr, der über die Firewall zulässig ist, einen Genehmigungsprozess durchläuft.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass die Firewallregelbasis so konfiguriert ist, dass der Datenverkehr, der nicht explizit definiert ist, abgelegt wird.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass die Firewall nur eine starke Kryptografie auf allen Nicht-Konsolen-Verwaltungsschnittstellen unterstützt.|
||Stellen Sie nachweisbare Nachweise bereit, dass Sie mindestens alle 6 Monate Firewallregelüberprüfungen durchführen.|
|**Web Application Firewall (WAF) (OPTIONAL)**: Zusätzliches Guthaben wird für die Erfüllung der folgenden Steuerelemente belohnt.|Stellen Sie nachweisbare Beweise dafür bereit, dass die Web Application Firewall (WAF) so konfiguriert ist, dass böswilliger Datenverkehr aktiv überwacht, benachrichtigt und blockiert wird.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass die WAF SSL-Offloading unterstützt.|
||Stellen Sie nachweisbare Nachweise bereit, dass die WAF vor einigen oder allen der folgenden Klassen von Sicherheitsrisiken gemäß dem OWASP Core Rule Set (3.0 oder 3.1) geschützt ist. |
|**Steuerelement ändern**|Stellen Sie Richtliniendokumentation bereit, die Änderungssteuerungsprozesse regelt.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass Entwicklungs- und Testumgebungen die Trennung von Aufgaben von der Produktionsumgebung erzwingen.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass vertrauliche Produktionsdaten nicht in Entwicklungs- oder Testumgebungen verwendet werden.|
||Stellen Sie nachweisbare Nachweise bereit, dass dokumentierte Änderungsanforderungen Auswirkungen der Änderung, Details von Back-Out-Verfahren und der durchzuführenden Tests enthalten.|
||Stellen Sie nachweisbare Nachweise bereit, dass Änderungsanforderungen einem Autorisierungs- und Anmeldevorgang unterzogen werden.|
|**Sichere Softwareentwicklung/-bereitstellung**| Stellen Sie Richtlinien und Verfahren bereit, die die sichere Softwareentwicklung und -bereitstellung unterstützen, einschließlich sicherer Codierungsleitfaden für gängige Sicherheitsrisikenklassen wie OWASP Top 10 oder SANS Top 25 CWE.|
|| Stellen Sie nachweisbare Nachweise dafür bereit, dass Codeänderungen einem Überprüfungs- und Autorisierungsprozess durch einen zweiten Prüfer unterzogen werden.|
|| Stellen Sie nachweisbare Nachweise bereit, dass Entwickler jährlich eine sichere Softwareentwicklungsschulung absolvieren.|
|| Stellen Sie nachweisbare Nachweise dafür bereit, dass Code-Repositorys mit mehrstufiger Authentifizierung (Multi-Factor Authentication, MFA) gesichert sind.|
|| Stellen Sie nachweisbare Nachweise dafür bereit, dass Zugriffskontrollen zum Sichern von Code-Repositorys vorhanden sind.
|**Kontoverwaltung**| Stellen Sie Richtliniendokumentation bereit, die Die Kontoverwaltungspraktiken und -verfahren regelt.
||Stellen Sie nachweisbare Nachweise dafür bereit, dass Standardanmeldeinformationen in den beispielierten Systemkomponenten deaktiviert, entfernt oder geändert werden.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass die Kontoerstellung, -änderung und -löschung einen etablierten Genehmigungsprozess durchläuft.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass ein Prozess zum Deaktivieren oder Löschen von Konten vorhanden ist, die nicht innerhalb von 3 Monaten verwendet werden.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass eine Richtlinie für sichere Kennwörter oder andere geeignete Maßnahmen zum Schutz von Benutzeranmeldeinformationen vorhanden sind.  Folgendes sollte als Mindestrichtlinie verwendet werden: Mindestkennwortlänge von 8 Zeichen, Sperrschwelle für Konten von maximal 10 Versuchen, Kennwortverlauf von mindestens 5 Kennwörtern, Erzwingung der Verwendung eines sicheren Kennworts|
||Stellen Sie nachweisbare Nachweise bereit, dass eindeutige Benutzerkonten für alle Benutzer ausgestellt werden.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass die Grundsätze der geringsten Rechte innerhalb der Umgebung befolgt werden.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass ein Prozess zum Sichern oder Sichern von Dienstkonten vorhanden ist und dass der Prozess befolgt wird.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass MFA für alle Remotezugriffsverbindungen und alle Nicht-Konsolen-Verwaltungsschnittstellen konfiguriert ist.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass eine starke Verschlüsselung für alle Remotezugriffsverbindungen und alle Nicht-Konsolen-Verwaltungsschnittstellen konfiguriert ist, einschließlich des Zugriffs auf Code-Repositorys und Cloudverwaltungsschnittstellen.|
||Stellen Sie nachweisbare Nachweise bereit, dass MFA zum Schutz des Verwaltungsportals verwendet wird, das Sie zum Verwalten und Verwalten aller DNS-Einträge (Public Domain Name Service) verwenden.|
|**Angriffserkennung und -verhinderung (OPTIONAL):** Zusätzliches Guthaben wird für die Erfüllung der folgenden Kontrollen belohnt|Stellen Sie nachweisbare Nachweise dafür bereit, dass Intrusion Detection and Prevention Systems (IDPS) am Umfang der umgebungsbezogenen Umgebungen bereitgestellt wird.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass IDPS-Signaturen (innerhalb von 24 Stunden) auf dem neuesten Stand gehalten werden.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass IDPS so konfiguriert ist, dass die TLS-Überprüfung des gesamten eingehenden Webdatenverkehrs unterstützt wird.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass IDPS so konfiguriert ist, dass alle eingehenden Datenverkehrsströme überwacht werden.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass IDPS so konfiguriert ist, dass alle ausgehenden Datenverkehrsströme überwacht werden.|
|**Protokollierung von Sicherheitsereignissen** |Stellen Sie Richtliniendokumentation für bewährte Methoden und Verfahren bereit, die die Protokollierung von Sicherheitsereignissen regeln.|
|| Stellen Sie nachweisbare Nachweise bereit, die zeigen, dass die Protokollierung von Sicherheitsereignissen über alle beispielbasierten Systemkomponenten hinweg eingerichtet ist, um die folgenden Ereignisse zu protokollieren: Benutzerzugriff auf Systemkomponenten und die Anwendung, Alle Aktionen, die von einem Benutzer mit hoher Berechtigung ausgeführt werden, ungültiger logischer Zugriff versucht, Erstellung oder Änderung eines privilegierten Kontos, Manipulation von Ereignisprotokollen, Deaktivieren von Sicherheitstools (z. B. Antischadsoftware oder Ereignisprotokollierung),  Antischadsoftwareprotokollierung (z. B. Updates, Schadsoftwareerkennung und Scanfehler)., IDPS- und WAF-Ereignisse, falls konfiguriert|
||Stellen Sie nachweisbare Nachweise bereit, dass protokollierte Sicherheitsereignisse die folgenden Mindestinformationen enthalten: Benutzer, Ereignistyp, Datum und Uhrzeit, Erfolgs- oder Fehlerindikatoren, Bezeichnung, die das betroffene System identifiziert|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass alle in die Stichprobe einbezogenen Systemkomponenten zeitsynchron mit denselben primären und sekundären Servern synchronisiert werden.|
||Stellen Sie nachweisbare Nachweise bereit, wenn öffentlich zugängliche Systeme verwendet werden, dass Sicherheitsereignisprotokolle an eine zentralisierte Protokollierungslösung gesendet werden, die sich nicht im Umkreisnetzwerk befindet.|
||Stellen Sie nachweisbare Nachweise bereit, um zu zeigen, dass die zentralisierte Protokollierungslösung vor unbefugter Manipulation von Protokollierungsdaten geschützt ist.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass mindestens 30 Tage an Protokollierungsdaten für Sicherheitsereignisse sofort verfügbar sind, wobei 90 Tage Sicherheitsereignisprotokolle aufbewahrt werden.|
|**Überprüfen (Protokolldaten)** |Stellen Sie Richtliniendokumentation bereit, die die Protokollüberprüfungspraktiken und -verfahren regelt.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass Protokolle täglich von einem menschlichen oder automatisierten Tool überprüft werden, um potenzielle Sicherheitsereignisse zu identifizieren.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass potenzielle Sicherheitsereignisse und Anomalien untersucht und behoben werden.|
|**Alarmierung** | Stellen Sie Richtliniendokumentation bereit, die Benachrichtigungspraktiken und -verfahren für Sicherheitsereignisse regelt.|
|| Stellen Sie nachweisbare Beweise dafür bereit, dass Warnungen für die sofortige Triage für die folgenden Arten von Sicherheitsereignissen ausgelöst werden: Erstellung oder Änderung eines privilegierten Kontos, Viren- oder Schadsoftwareereignisse, Manipulation von Ereignisprotokollen, IDPS- oder WAF-Ereignisse|
||Stellen Sie nachweisbare Nachweise bereit, die zeigen, dass Mitarbeiter den ganzen Tag über zur Verfügung stehen, um auf Sicherheitswarnungen zu reagieren.|
|**Risikomanagement**|Stellen Sie nachweisbare Nachweise für die Einrichtung eines formalen Risikomanagementprozesses für die Informationssicherheit bereit.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass mindestens jährlich eine formale Risikobewertung stattfindet.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass die Risikobewertung der Informationssicherheit Bedrohungen, Sicherheitsrisiken oder das Entsprechende umfasst.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass die Risikobewertung der Informationssicherheit Auswirkungen, Wahrscheinlichkeitsrisikomatrix oder die entsprechende Risikomatrix umfasst.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass die Risikobewertung der Informationssicherheit ein Risikoregister und einen Behandlungsplan enthält.|
|**Reaktion auf Vorfälle**|Stellen Sie den Sicherheitsvorfallreaktionsplan (Security Incident Response Plan, IRP) bereit.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass das Sicherheits-IRP einen dokumentierten Kommunikationsprozess umfasst, um wichtige Interessengruppen wie Zahlungsmarken und Acquirer, Aufsichtsbehörden, Direktoren und Kunden rechtzeitig zu informieren.|
||Stellen Sie nachweisbare Beweise dafür bereit, dass alle Mitglieder des Vorfallreaktionsteams eine jährliche Schulung oder eine Tischübung abgeschlossen haben.|
||Stellen Sie nachweisbare Nachweise bereit, um zu zeigen, dass die Sicherheits-IRP basierend auf den gewonnenen Erkenntnissen oder organisatorischen Änderungen aktualisiert wurde.|

## <a name="data-handling-security-and-privacy"></a>Datensicherheit und Datenschutz

Daten, die zwischen dem Anwendungsbenutzer, zwischengeschalteten Diensten und den SYSTEMEN von ISV übertragen werden, müssen durch Verschlüsselung über eine TLS-Verbindung geschützt werden, die mindestens TLS v1.1 unterstützt. *Siehe* [**Anhang A**](#appendix-a).

Wo Ihre Anwendung M365-Daten abruft und speichert, müssen Sie ein Datenspeicherverschlüsselungsschema implementieren, das der Spezifikation gemäß [**Anhang B**](#appendix-a) folgt.

### <a name="controls"></a>Steuerelemente

|**Steuerelementfamilie**| **Controls** |
| -----------------------|-------------------------------- |
|**Daten während der Übertragung**| Nachweis, dass die TLS-Konfiguration die Verschlüsselungsanforderungen innerhalb der [TLS-Profilkonfigurationsanforderungen](../docs/certification-submission-guide.md#appendix-a) erfüllt oder übersteigt|
||Stellen Sie nachweisbare Beweise dafür bereit, dass die TLS-Komprimierung für alle öffentlich zugänglichen Dienste deaktiviert ist, die Webanforderungen verarbeiten.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass TLS HTTP strict transport security aktiviert und auf allen Websites auf >= 15552000 konfiguriert ist.|
|**Ruhedaten**| Stellen Sie nachweisbare Beweise dafür bereit, dass ruhenden Daten inline mit den Verschlüsselungsprofilanforderungen verschlüsselt werden, indem Sie Verschlüsselungsalgorithmen wie AES, Blowfish, TDES und Verschlüsselungsschlüsselgrößen von 128-Bit und 256-Bit verwenden.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass die Hashfunktion oder Nachrichtenauthentifizierung (HMAC-SHA1) nur verwendet wird, um ruhenden Daten inline mit den Verschlüsselungsprofilanforderungen zu schützen.|
||Stellen Sie einen Bestand bereit, in dem alle gespeicherten Daten angezeigt werden, einschließlich des Speicherorts und der Verschlüsselung, die zum Schutz der Daten verwendet werden.|
|**Datenaufbewahrung und -entsorgung**|Stellen Sie nachweisbare Nachweise dafür bereit, dass ein genehmigter und dokumentierter Datenaufbewahrungszeitraum formell festgelegt ist.|
||Stellen Sie nachweisbare Nachweise bereit, dass die aufbewahrten Daten mit dem definierten Aufbewahrungszeitraum übereinstimmen.|
||Stellen Sie nachweisbare Nachweise bereit, dass Prozesse zum sicheren Löschen von Daten nach dem Aufbewahrungszeitraum vorhanden sind.|
|**Datenzugriffsverwaltung**|Stellen Sie eine Liste aller Personen bereit, die Zugriff auf Daten oder Verschlüsselungsschlüssel haben, einschließlich der geschäftlichen Begründung.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass die in die Stichprobe einbezogenen Personen, die Zugriff auf Daten oder Verschlüsselungsschlüssel haben, formell genehmigt wurden, und geben Sie die für ihre Aufgaben erforderlichen Berechtigungen an.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass die in die Stichprobe einbezogenen Personen, die Zugriff auf Daten oder Verschlüsselungsschlüssel haben, nur über die in der Genehmigung enthaltenen Berechtigungen verfügen.|
||Stellen Sie eine Liste aller Drittanbieter bereit, für die Kundendaten freigegeben werden.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass für alle Drittanbieter, die Kundendaten nutzen, Freigabevereinbarungen bestehen.|
|**DSGVO** (falls zutreffend)| Stellen Sie ein dokumentiertes Verfahren zur Anforderung des Zugriffs auf Antragsteller (Sar) bereit, und stellen Sie Nachweise bereit, die belegen, dass betroffene Personen in der Lage sind, SARs zu erheben.|
||Stellen Sie nachweisbare Nachweise bereit, dass Sie bei der Reaktion auf eine SAR alle Standorte der Daten der betroffenen Personen identifizieren können.|
||Sie pflegen einen Datenschutzhinweis, der die Firmendetails (Name, Adresse usw.) enthalten sollte.|
||Sie pflegen einen Datenschutzhinweis, in dem die Arten von personenbezogenen Daten, die verarbeitet werden, erläutert werden sollen.|
||Sie führen einen Datenschutzhinweis, der die Rechtmäßigkeit der Verarbeitung personenbezogener Daten erklären sollte|
||Sie pflegen einen Datenschutzhinweis, der die Rechte der betroffenen Person im Detail erläutert: Auskunftsrecht, Auskunftsrecht der betroffenen Person, Recht auf Löschung, Recht auf Einschränkung der Verarbeitung, Recht auf Datenübertragbarkeit, Widerspruchsrecht, Rechte in Bezug auf automatisierte Entscheidungsfindung, einschließlich Profiling.|
|| Sie pflegen einen Datenschutzhinweis, der erklären soll, wie lange personenbezogene Daten aufbewahrt werden.|

## <a name="optional-external-compliance-frameworks-review"></a>Überprüfung der optionalen externen Compliance-Frameworks

Obwohl dies nicht erforderlich ist, können Sie, wenn Sie derzeit mit ISO 27001, PCI DSS oder SOC2 konform sind, diese Zertifizierungen verwenden, um einige der Microsoft 365 Zertifizierungssteuerelemente zu erfüllen. Zertifizierungsanalysten versuchen, vorhandene externe Sicherheitsframeworks an die Microsoft 365 Zertifizierungsspezifikation auszurichten. Wenn die unterstützende Dokumentation jedoch nicht sicher sein kann, dass Microsoft 365 Zertifizierungskontrollen als Teil der Externen Sicherheitsframeworks-Prüfung/-Bewertung bewertet wurden, müssen Sie zusätzliche Nachweise dafür bereitstellen, dass diese Kontrollen vorhanden sind.

Die Dokumentation muss hinreichend nachweisen, dass die bereichsinterne Umgebung für die Microsoft 365 Zertifizierung im Rahmen dieser externen Sicherheitsframeworks enthalten war. Die Validierung dieser Sicherheitsframeworks wird erfüllt, indem der Nachweis gültiger Zertifizierungen akzeptiert wird, die von seriösen externen Drittanbietern durchgeführt werden. Diese seriösen Unternehmen müssen Mitglied internationaler Akkreditierungsstellen für relevante Compliance-Programme sein. Siehe ISO-Zertifizierung und Konformitätsstandards für ISO 27001 und qualifizierte Sicherheitsbewerter (QSA) für PCI DSS.

In der folgenden Tabelle werden die externen Frameworks und die Dokumentation hervorgehoben, die von Zertifizierungsanalysten im Rahmen dieses Validierungsprozesses benötigt werden:

| **Standard** | **Anforderungen** |
| ----- | ----- |
| **[ISO 27001](#iso-27001)** | Eine öffentlich zugängliche Version der **Erklärung zur Anwendbarkeit (Statement of Applicability** , SOA) und eine Kopie des ausgestellten ISO 27001-Zertifikats sind erforderlich.  Das SOA fasst Ihre Position zu jedem der 114 Informationssicherheitskontrollen zusammen und wird verwendet, um zu ermitteln, ob ein Ausschluss von Steuerelementen erfolgt, die im ISO 27001-Zertifikat nicht zufriedenstellend beschrieben sind. Wenn dies nicht durch Die Überprüfung der öffentlich zugänglichen Version des SOA bestimmt werden kann, benötigt der Analyst möglicherweise Zugriff auf das vollständige SOA, wenn ISO 27001 verwendet wird, um einige der Steuerelemente der Microsoft 365 Zertifizierungsspezifikation zu überprüfen.  Neben der Validierung des Umfangs der ISO 27001-Bewertungsaktivitäten werden die Analysten auch die Gültigkeit des Prüfungsunternehmens wie oben beschrieben bestätigen.|
|**[PCI/DSS](#pci-dss)**| Es muss ein gültiges AOC-Dokument ( **Level 1 Attestation of Compliance** ) bereitgestellt werden, in dem die anwendungsbezogenen und Systemkomponenten eindeutig identifiziert werden.  Ein Selbstbewertungs-AOC **wird nicht** als Beweis für bewährte Methoden zur Einhaltung der Sicherheit akzeptiert. Das AOC wird verwendet, um zu bestimmen, welche der Microsoft 365 Zertifizierungsspezifikationskontrollen im Rahmen der PCI DSS-Bewertung ausgewertet und bestätigt wurden.|
|**[SOC 2](#soc-2)**|Der **SOC 2-Bericht (Typ I oder Typ II)** muss aktuell sein (ausgestellt innerhalb der letzten 15 Monate und der deklarierte Zeitraum, der innerhalb der letzten 27 Monate begonnen hat), um als Nachweis für die Konformität mit allen Bewertungskontrollen innerhalb dieser Microsoft 365 Zertifizierungsspezifikation verwendet zu werden.|

Wenn externe Sicherheitsframeworks in den Publisher Attestation aufgenommen wurden, müssen Zertifizierungsanalysten die Gültigkeit dieser Sicherheitscomplianceframeworks im Rahmen der Microsoft 365 Zertifizierungsbewertung überprüfen.

|**Framework** | **Zusätzliche Überlegungen** |
|-------------- | --------------------|
|ISO 27001| [**Anhang C**](#appendix-c): Nachweissammlung – Deltas für ISO 27001.|
|PCI/DSS | [**Anhang D**](#appendix-d): Nachweissammlung – Deltas für PCI DSS.|
|SOC 2| [**Anhang E**](#appendix-e): Beweissammlung – Deltas für SOC 2.|

> [!NOTE]
> Obwohl die oben genannten externen Sicherheitsstandards/Frameworks als Nachweis für einige der Microsoft 365 Zertifizierungskontrollen eingereicht werden können, bedeutet das Bestehen der Microsoft 365 Zertifizierung nicht, dass Sie erfolgreich eine Prüfung anhand dieser Standards/Frameworks bestehen. Die Microsoft 365-Zertifizierungsspezifikation ist nur eine kleine Teilmenge dieser Sicherheitsstandards/Frameworks, die Es Microsoft ermöglichen, ein Maß an Sicherheit in Bezug auf Ihren Sicherheitsstatus zu erhalten.


### <a name="requirements-to-use-external-compliance-frameworks"></a>Anforderungen für die Verwendung externer Complianceframeworks

&#x2713; Die App/Add-In-unterstützende Umgebung **UND** alle unterstützenden Geschäftsprozesse **MÜSSEN** im Rahmen von unterstützten externen Sicherheitscomplianceframeworks enthalten sein und müssen in der bereitgestellten Dokumentation klar angegeben werden.

&#x2713; Unterstützte externe Sicherheitscompliance-Frameworks **MÜSSEN** aktuell sein, d. h. innerhalb der letzten 12 Monate (oder innerhalb von 15 Monaten, wenn die erneute Bewertung derzeit durchgeführt wird und Nachweise erbracht werden können).

&#x2713; Unterstützte externe Sicherheitscompliance-Frameworks **MÜSSEN** von einem unabhängigen akkreditierten Unternehmen durchgeführt werden.

## <a name="appendix-a"></a>Anhang A

### <a name="tls-profile-configuration-requirements"></a>Konfigurationsanforderungen für TLS-Profile

Der gesamte Netzwerkdatenverkehr, ob innerhalb eines virtuellen Netzwerks, eines Clouddiensts oder eines Rechenzentrums, muss mit mindestens TLS v1.1 (TLS v1.2+ wird empfohlen) oder einem anderen anwendbaren Protokoll geschützt werden. Ausnahmen von dieser Anforderung sind:

* **HTTP-zu-HTTPS-Umleitung**. Ihre App kann über HTTP reagieren, um Clients an HTTPS umzuleiten, aber die Antwort darf keine vertraulichen Daten (Cookies, Header, Inhalte) enthalten. Es sind keine anderen HTTP-Antworten als Umleitungen zu HTTPS und Antworten auf Integritätsüberprüfungen zulässig. Siehe unten.
* **Integritätssonden**. Ihre App kann nur dann auf Integritätsüberprüfungen über HTTP reagieren **, wenn** HTTPS-Integritätsüberprüfungen von der Prüfpartei nicht unterstützt werden.
* **Zertifikatzugriff**. Der Zugriff auf CRL-, OCSP- und AIA-Endpunkte zum Zwecke der Zertifikatüberprüfung und Sperrüberprüfung ist über HTTP zulässig.
* **Lokale Kommunikation**. Ihre App kann HTTP (oder andere nicht geschützte Protokolle) für Kommunikationen verwenden, die das Betriebssystem nicht verlassen, z. g. Herstellen einer Verbindung mit einem Webserverendpunkt, der auf localhost verfügbar gemacht wird.

DIE TLS-Komprimierung **MUSS** deaktiviert sein.

## <a name="appendix-b"></a>Anhang B

### <a name="encryption-profile-configuration-requirements"></a>Konfigurationsanforderungen für Verschlüsselungsprofil

Nur kryptografische Grundtypen und Parameter sind wie folgt zulässig:

### <a name="symmetric-cryptography"></a>Symmetrische Kryptografie

**Verschlüsselung**

&emsp;&#x2713; nur AES, BitLocker, Blowfish oder TDES sind zulässig. Jede der unterstützten Schlüssellängen >=128 ist zulässig (128, 192 und 256 Bit) und kann verwendet werden (256-Bit-Tasten werden empfohlen).

&emsp;&#x2713; Nur der CBC-Modus ist zulässig. Jeder Verschlüsselungsvorgang muss einen neuen, zufällig generierten Initialisierungsvektor (IV) verwenden.

&emsp;&#x2713; Die Verwendung von Datenstromchiffren, z. B. RC4, **IST NICHT** zulässig.

**Hashfunktionen**

&emsp;&#x2713; Der gesamte neue Code muss SHA-256, SHA-384 oder SHA-512 (zusammenfassend als SHA-2 bezeichnet) verwenden. Die Ausgabe kann auf maximal 128 Bit gekürzt werden.

&emsp;&#x2713; SHA-1 kann nur aus Kompatibilitätsgründen verwendet werden.

&emsp;&#x2713; Verwendung von MD5, MD4, MD2 und anderen Hashfunktionen ist nicht zulässig, auch nicht für nicht kryptografische Anwendungen.

**Nachrichtenauthentifizierung**

&emsp;&#x2713; Der gesamte neue Code MUSS HMAC mit einer der genehmigten Hashfunktionen verwenden. Die Ausgabe von HMAC kann auf maximal 128 Bit gekürzt werden.

&emsp;&#x2713; HMAC-SHA1 kann nur aus Kompatibilitätsgründen verwendet werden.

&emsp;&#x2713; HMAC-Taste MUSS mindestens 128 Bit lang sein. 256-Bit-Tasten werden empfohlen.

### <a name="asymmetric-algorithms"></a>Asymmetrische Algorithmen

**Verschlüsselung**

&emsp;&#x2713; RSA ist zulässig. Der Schlüssel **MUSS** mindestens 2048 Bit lang sein, und der OAEP-Abstand muss verwendet werden. Die Verwendung des PKCS-Abstands ist nur aus Kompatibilitätsgründen zulässig.

**Signaturen**

&emsp;&#x2713; RSA ist zulässig. Der Schlüssel **MUSS** mindestens 2048 Bit lang sein, und DER PSS-Abstand muss verwendet werden. Die Verwendung des PKCS-Abstands ist nur aus Kompatibilitätsgründen zulässig.

&emsp;&#x2713;ECDSA ist zulässig. Der Schlüssel **MUSS** mindestens 256 Bit lang sein. NIST P-256, P-384 oder P-521 Kurve muss verwendet werden.

**Key Exchange**

&emsp;&#x2713; ECDH ist zulässig. Der Schlüssel **MUSS** mindestens 256 Bit lang sein. NIST P-256, P-384 oder P-521 Kurve muss verwendet werden.

&emsp;&#x2713; ECDH ist zulässig. Der Schlüssel **MUSS** mindestens 256 Bit lang sein. NIST P-256, P-384 oder P-521 Kurve muss verwendet werden.

## <a name="appendix-c"></a>Anhang C

### <a name="evidence-collection--delta-for-iso-27001"></a>Beweissammlung – Delta für ISO 27001

Wenn Sie die ISO27001-Compliance bereits erreicht haben, müssen die folgenden Deltas (Lücken), die nicht vollständig von ISO 27001 abgedeckt sind, mindestens im Rahmen dieser Microsoft 365 Zertifizierung überprüft werden.

> [!NOTE]
> Im Rahmen Ihrer Microsoft 365 Zertifizierungsbewertung ermittelt der Zertifizierungsanalyst, ob eines der zugeordneten ISO 27001-Steuerelemente nicht teil der ISO 27001-Bewertung war, und kann sich auch dafür entscheiden, Stichprobensteuerelemente zu erstellen, die als einbezogen angesehen wurden, um weitere Sicherheit zu gewährleisten. Alle Anforderungen, die in der ISO 27001 fehlen, müssen in Ihre Microsoft 365 Zertifizierungsbewertungsaktivitäten einbezogen werden.

**Schutz vor Schadsoftware – Virenschutz**

Wenn der Schutz vor Schadsoftware mithilfe der Anwendungssteuerung eingerichtet ist und innerhalb des ISO 27001-Berichts nachgewiesen wird, ist keine weitere Untersuchung erforderlich. Wenn keine Anwendungssteuerung vorhanden ist, müssen Zertifizierungsanalysten Nachweise von Anwendungskontrollmechanismen identifizieren und bewerten, um die Detonation von Schadsoftware in der Umgebung zu verhindern. Dies erfordert Folgendes:

* Zeigen Sie, dass Antivirensoftware auf allen beispielbasierten Systemkomponenten ausgeführt wird.

* Veranschaulichen Sie, dass Antivirensoftware in allen beispielbasierten Systemkomponenten konfiguriert ist, um Schadsoftware entweder automatisch zu blockieren, & zu isolieren oder zu benachrichtigen.

* Antivirensoftware **MUSS** so konfiguriert sein, dass alle Aktivitäten protokolliert werden.

**Patchverwaltung – Patching**

Da ISO 27001-Audits diese Kategorie nicht speziell bewerten, müssen Sie:

* Softwarekomponenten und Betriebssysteme, die vom Hersteller nicht mehr unterstützt werden **, DÜRFEN** nicht innerhalb der Umgebung verwendet werden. Unterstützende Richtlinien MÜSSEN vorhanden sein, um sicherzustellen, dass nicht unterstützte Softwarekomponenten/Betriebssysteme aus der Umgebung entfernt werden, und ein Prozess zur Identifizierung, wann Softwarekomponenten zum Ende der Lebensdauer wechseln müssen.

**Prüfung auf Schwachstellen**  

Da ISO 27001-Audits diese Kategorie nicht speziell bewerten, müssen Sie:

* Veranschaulichen, dass vierteljährliche interne und externe Sicherheitsrisikoüberprüfungen durchgeführt werden.

* Bestätigen Sie, dass die unterstützende Dokumentation für die Behebung von Sicherheitsrisiken basierend auf der Risikorangfolge und gemäß der Spezifikation wie folgt vorhanden ist:
 
 &#x2713; Alle Probleme mit kritischem und hohem Risiko im Einklang mit der Risikorangfolge für die interne Überprüfung beheben.
 
 &#x2713; alle kritischen, hohen und mittleren Risikoprobleme im Einklang mit der Risikorangfolge für externe Überprüfungen beheben.
 
 &#x2713; nachweisen, dass die Behebung im Einklang mit der dokumentierten Richtlinie zur Behebung von Sicherheitsrisiken erfolgt.

**Firewall – Firewalls (oder gleichwertige Technologien)**

Da ISO 27001-Audits diese Kategorie nicht speziell bewerten, müssen Sie:

* Veranschaulichen, dass Firewalls an der Grenze der Bereichsumgebung installiert sind.

* Demonstrieren, dass Firewalls zwischen dem DMZ und vertrauenswürdigen Netzwerken installiert sind.

*   Veranschaulichen, dass der gesamte öffentliche Zugriff in der DMZ beendet wird.

*   Veranschaulichen, dass standardmäßige Administratoranmeldeinformationen vor der Installation in der Liveumgebung geändert werden.

*   Veranschaulichen Sie, dass der gesamte zulässige Datenverkehr durch die Firewall(n) einen Autorisierungsprozess durchläuft, der zur Dokumentation des gesamten Datenverkehrs mit einer geschäftlichen Begründung führt.

*   Veranschaulichen Sie, dass alle Firewalls so konfiguriert sind, dass datenverkehrsabwerfend konfiguriert ist, der nicht explizit definiert ist.

*   Demonstrieren Sie, dass Firewalls nur eine starke Kryptografie auf allen nicht konsolenbasierten Verwaltungsschnittstellen unterstützen.

*   Veranschaulichen, dass die nicht konsolenbasierten Verwaltungsschnittstellen der Firewall, die dem Internet zur Verfügung gestellt werden, MFA unterstützen.

*   Nachweis, dass Firewallregelüberprüfungen mindestens alle 6 Monate durchgeführt werden

**Firewall – WebAnwendungsfirewalls (WAF)**  

Zusätzliche Gutschriften werden bereitgestellt, wenn ein WAF bereitgestellt wird, um den Schutz vor den unzähligen Bedrohungen und Sicherheitsrisiken der Webanwendung zu gewährleisten, denen die Anwendung ausgesetzt werden kann. Wenn eine WAF oder ähnliches vorhanden ist, müssen Sie folgende Aktionen ausführen:

* Veranschaulichen Sie, dass waf im aktiven Verteidigungsmodus konfiguriert ist oder mehr mit Warnungen überwacht wird.

* Veranschaulichen, dass WAF so konfiguriert ist, dass SSL-Offloading unterstützt wird.

* Ist gemäß dem OWASP Core Rule Set (3.0 oder 3.1) konfiguriert, um vor den meisten der folgenden Angriffstypen zu schützen:

&#x2713; Protokoll- und Codierungsprobleme.

&#x2713; Kopfzeileneinfügung, Anforderungsschmuggel und Antwortaufteilung.

&#x2713; Datei- und Pfad-Traversalangriffe.

&#x2713; Remote-Dateieinschlussangriffe (Remote File Inclusion, RFI).

&#x2713; Remotecodeausführungsangriffe.

&#x2713; PHP-Injection-Angriffe.

&#x2713; websiteübergreifende Skriptangriffe.

&#x2713; SQL-Injection-Angriffe.

&#x2713; Session-Fixation-Angriffe.

**Steuerelement ändern**

Da ISO 27001-Audits einige Elemente von Change Request-Prozessen nicht speziell bewerten, müssen Sie:

* Zeigen Sie, dass Änderungsanforderungen die folgenden Details aufweisen:

&#x2713; Dokumentierte Auswirkungen.

&#x2713; Details dazu, welche Funktionalitätstests durchgeführt werden sollen.

&#x2713; Details aller Back-Out-Prozeduren.

* Demonstrieren, dass Funktionalitätstests durchgeführt werden, nachdem die Änderungen abgeschlossen sind.

* Zeigen Sie, dass Änderungsanforderungen nach dem Testen der Funktionalität abgemeldet werden.

**Kontoverwaltung**

Da ISO 27001-Audits einige Elemente der Kontoverwaltungsprozesse nicht ausdrücklich bewerten, müssen Sie:

*   Veranschaulichen, wie &#x2713;s implementiert werden, um Replay-Angriffe (z. B. MFA, Kerberos) zu mindern.
*   Zeigen Sie, wie Konten, die in 3 Monaten nicht verwendet wurden, entweder deaktiviert oder gelöscht werden.
*   &#x2713; oder andere geeignete Gegenmaßnahmen müssen konfiguriert werden, um Benutzeranmeldeinformationen zu schützen. Die folgende Mindestkennwortrichtlinie sollte als Richtlinie verwendet werden:

&#x2713; Mindestkennwortlänge von 8 Zeichen.

&#x2713; Schwellenwert für die Kontosperrung von maximal 10 Versuchen.
 
&#x2713; Kennwortverlauf von mindestens fünf Kennwörtern.
 
&#x2713; Durchsetzung der Verwendung sicherer Kennwörter.
 
*   Veranschaulichen, dass MFA für alle Remotezugriffslösungen konfiguriert ist.

*   Demonstrieren, dass eine starke Verschlüsselung für alle Remotezugriffslösungen konfiguriert ist.

*   Wenn sich die Verwaltung des öffentlichen DNS außerhalb der bereichsbezogenen Umgebung befindet, MÜSSEN alle Benutzerkonten, die DNS-Änderungen vornehmen können, für die Verwendung von MFA konfiguriert sein.

**Angriffserkennung und -verhinderung (OPTIONAL)**

Da ISO 27001-Audits einige Elemente von Intrusion Detection and Prevention Services (IDPS)-Prozessen nicht speziell bewerten, müssen Sie folgende Aufgaben ausführen:

*   IDPS **SOLLTE** am Umkreis der unterstützenden Umgebung bereitgestellt werden.

*   IDPS-Signaturen **SOLLTEN** innerhalb des letzten Tages auf dem neuesten Stand gehalten werden.

*   IDPS **SOLLTE** für die TLS-Inspektion konfiguriert werden.

*   IDPS **SOLLTE** für DEN GESAMTEN eingehenden und ausgehenden Datenverkehr konfiguriert werden.

*   IDPS **SOLLTE** für Benachrichtigungen konfiguriert werden.

**Ereignisprotokollierung**

Da ISO 27001-Audits einige Elemente der Protokollierung von Sicherheitsereignissen nicht speziell bewerten, müssen Sie:

* Zeigen Sie, dass öffentlich zugängliche Systeme eine Protokollierung in einer zentralen Protokollierungslösung durchführen, die sich nicht innerhalb der DMZ befindet.

* Veranschaulichen Sie, wie Protokollierungsdaten im Wert von mindestens 30 Tagen sofort verfügbar sind, wobei 90 Tage aufbewahrt werden.

**Überprüfen (Protokollierungsdaten)**

Da ISO 27001-Audits einige Elemente dieser Kategorie nicht speziell bewerten, müssen Sie:

*   Veranschaulichen, wie tägliche Protokollüberprüfungen durchgeführt werden und wie Ausnahmen und Anomalien identifiziert werden, die zeigen, wie diese behandelt werden.

**Alarmierung**

Da ISO 27001-Audits einige Elemente dieser Kategorie nicht speziell bewerten, müssen Sie:

* Veranschaulichen, wie Sicherheitsereignisse so konfiguriert sind, dass Warnungen für die sofortige Triage ausgelöst werden.

* Demonstrieren, wie Mitarbeiter 24/7 verfügbar sind, um auf Sicherheitswarnungen zu reagieren.

**Risikomanagement**

Da ISO 27001-Audits einige Elemente von Risikobewertungsprozessen nicht speziell bewerten, müssen Sie:

* Demonstrieren, dass ein formaler Risikomanagementprozess eingerichtet ist.

**Reaktion auf Vorfälle**

Da ISO 27001-Audits einige Elemente der Richtlinien und Prozesse zur Reaktion auf Vorfälle nicht speziell bewerten, müssen Sie:

*   Zeigen Sie, dass der Plan/das Verfahren zur Reaktion auf Vorfälle Folgendes umfasst:

&#x2713; Spezifische Reaktionsverfahren für erwartete Bedrohungsmodelle.

&#x2713; Funktionen zur Behandlung von Vorfällen, die an das NIST Cybersecurity Framework (Identifizieren, Schützen, Erkennen, Reagieren, Wiederherstellen) ausgerichtet sind.
 
&#x2713; Das IRP deckt die In-Scope-Systeme ab.
 
&#x2713; jährliche Schulung für das Vorfallreaktionsteam.

## <a name="appendix-d"></a>Anhang D

### <a name="evidence-collection--deltas-for-pci-dss"></a>Beweissammlung – Deltas für PCI DSS

Wenn Sie die PCI DSS-Compliance bereits erreicht haben, müssen die folgenden Deltas (Lücken), die nicht vollständig von PCI DSS abgedeckt sind, mindestens im Rahmen dieser Microsoft 365 Zertifizierung überprüft werden.

> [!NOTE]
> Im Rahmen der Microsoft 365 Zertifizierungsbewertung wird der Zertifizierungsanalyst ermitteln, ob eines der zugeordneten PCI DSS-Steuerelemente nicht in die PCI DSS-Bewertung einbezogen wurde, und kann auch beschließen, Steuerelemente zu testen, die als einbezogen angesehen wurden, um weitere Sicherheit zu gewährleisten. Alle Anforderungen, die im PCI DSS fehlen, müssen in die Microsoft 365 Zertifizierungsbewertungsaktivitäten einbezogen werden.

**Schutz vor Schadsoftware – Anwendungssteuerung**

Wenn der Schutz vor Schadsoftware durch die Verwendung von Antivirensoftware besteht und im PCI DSS-Bericht nachgewiesen wird, ist keine weitere Untersuchung erforderlich. Wenn kein Antivirus vorhanden ist, müssen Zertifizierungsanalysten Nachweise von Anwendungskontrollmechanismen identifizieren und bewerten, um die Detonation von Schadsoftware in der Umgebung zu verhindern. Dies erfordert Folgendes: 

*   Veranschaulichen Sie, wie die Anwendungsgenehmigung durchgeführt wird, und bestätigen Sie, dass dies abgeschlossen ist.

*   Zeigen Sie, dass eine vollständige Liste der genehmigten Anwendungen mit geschäftlicher Begründung vorhanden ist.

*   Bereitstellen oder Veranschaulichen der unterstützenden Dokumentation, in der detailliert beschrieben wird, wie Die Anwendungskontrolle software so konfiguriert ist, dass sie bestimmte Anwendungssteuerungsmechanismen (z. B. Allowlisting, Codesignierung usw.) erfüllt.

*   Veranschaulichen Sie, dass die Anwendungssteuerung für alle Beispielsystemkomponenten wie dokumentiert konfiguriert ist.

**Patch-Management – Risikorangfolge**

Da PCI DSS-Audits diese Kategorie nicht speziell bewerten, müssen Sie:

* Veranschaulichen, wie die Risikobewertung von Sicherheitsrisiken durchgeführt wird.

**Prüfung auf Schwachstellen**

Da PCI DSS-Audits diese Kategorie nicht speziell bewerten, müssen Sie:

* Veranschaulichen, dass die Behebung im Einklang mit der dokumentierten Richtlinie zur Behebung von Sicherheitsrisiken erfolgt.

**Firewall – Firewalls (oder gleichwertige Technologien)**

Da PCI DSS-Audits diese Kategorie nicht speziell bewerten, müssen Sie:

* Demonstrieren Sie, dass Firewalls nur eine starke Kryptografie auf allen nicht konsolenbasierten Verwaltungsschnittstellen unterstützen.

* Veranschaulichen, dass die nicht konsolenbasierten Verwaltungsschnittstellen der Firewall, die dem Internet zur Verfügung gestellt werden, MFA unterstützen.

Zusätzliche Gutschriften werden bereitgestellt, wenn ein Web Application Firewall (WAF) bereitgestellt wird, um den Schutz vor den unzähligen Bedrohungen und Sicherheitsrisiken der Webanwendung zu gewährleisten, denen die Anwendung ausgesetzt werden kann. Wenn eine WAF oder ähnliches vorhanden ist, müssen Sie folgende Aktionen ausführen:

* Veranschaulichen Sie, dass waf im aktiven Verteidigungsmodus konfiguriert ist oder mehr mit Warnungen überwacht wird.

* Veranschaulichen, dass WAF so konfiguriert ist, dass SSL-Offloading unterstützt wird.

* Ist gemäß dem OWASP Core Rule Set (3.0 oder 3.1) konfiguriert, um vor den meisten der folgenden Angriffstypen zu schützen:

&#x2713; Protokoll- und Codierungsprobleme.

&#x2713; Kopfzeileneinfügung, Anforderungsschmuggel und Antwortaufteilung.

&#x2713; Datei- und Pfad-Traversalangriffe.

&#x2713; Remote-Dateieinschlussangriffe (Remote File Inclusion, RFI).

&#x2713; Remotecodeausführungsangriffe.

&#x2713; PHP-Injection-Angriffe.

&#x2713; websiteübergreifende Skriptangriffe.

&#x2713; SQL-Injection-Angriffe.

&#x2713; Session-Fixation-Angriffe.

**Steuerelement ändern**

Da PCI DSS-Audits einige Elemente von Change Request-Prozessen nicht speziell bewerten, müssen Sie:

* Zeigen Sie, dass Änderungsanforderungen ausgelöst werden, bevor sie in Produktionsumgebungen vorgenommen werden.

* Veranschaulichen, dass Änderungen autorisiert sind, bevor sie in die Produktion gehen.

* Demonstrieren, dass Funktionalitätstests durchgeführt werden, nachdem die Änderungen abgeschlossen sind.

* Zeigen Sie, dass Änderungsanforderungen nach dem Testen der Funktionalität abgemeldet werden.

**Sichere Softwareentwicklung/-bereitstellung**

Da PCI DSS-Audits nicht speziell auf einige Elemente sicherer Softwareentwicklungs- und Bereitstellungsprozesse zugreifen; Dies erfordert Folgendes:

* Code-Repositorys MÜSSEN durch MFA gesichert werden.

*   Es MÜSSEN angemessene Zugriffskontrollen vorhanden sein, um Code-Repositorys vor bösartigen Codeänderungen zu schützen.

**Kontoverwaltung**

Da PCI DSS-Audits einige Elemente der Kontoverwaltungsprozesse nicht speziell bewerten, müssen Sie:

* Veranschaulichen, wie die Autorisierungsmechanismen implementiert werden, um Replay-Angriffe zu mindern (z. B. MFA, Kerberos).

* Richtlinien für sichere Kennwörter oder andere geeignete Gegenmaßnahmen müssen konfiguriert werden, um Benutzeranmeldeinformationen zu schützen. Die folgende Mindestkennwortrichtlinie sollte als Richtlinie verwendet werden: 

&#x2713; Mindestkennwortlänge von 8 Zeichen.

&#x2713; Schwellenwert für die Kontosperrung von maximal 10 Versuchen.

&#x2713; Kennwortverlauf von mindestens fünf Kennwörtern.

&#x2713; Durchsetzung der Verwendung sicherer Kennwörter.

* Demonstrieren, dass eine starke Verschlüsselung für alle Remotezugriffslösungen konfiguriert ist.

* Wenn sich die Verwaltung des öffentlichen DNS außerhalb der bereichsbezogenen Umgebung befindet, MÜSSEN alle Benutzerkonten, die DNS-Änderungen vornehmen können, für die Verwendung von MFA konfiguriert sein.

**Angriffserkennung und -verhinderung (OPTIONAL)**

Da PCI DSS-Prüfungen einige Elemente von Intrusion Detection and Prevention Services (IDPS)-Prozessen nicht speziell bewerten, müssen Sie:

* IDPS SOLLTE für die TLS-Inspektion konfiguriert werden.

*   IDPS SOLLTE für DEN GESAMTEN eingehenden und ausgehenden Datenverkehr konfiguriert werden.

**Risikomanagement**

Da PCI DSS-Audits einige Elemente von Risikobewertungsprozessen nicht speziell bewerten, müssen Sie:

* Veranschaulichen Sie, dass die Risikobewertung Auswirkungs- und Wahrscheinlichkeitsmatrizen umfasst.

**Reaktion auf Vorfälle**

Da PCI DSS-Audits einige Elemente von Richtlinien und Prozessen zur Reaktion auf Vorfälle nicht speziell bewerten, muss der Entwickler folgende Aufgaben durchführen:

* Veranschaulichen Der Umgang mit Vorfällen richtet sich nach dem NIST Cybersecurity Framework (Identifizieren, Schützen, Erkennen, Reagieren, Wiederherstellen).

## <a name="appendix-e"></a>Anhang E

### <a name="evidence-collection---deltas-for-soc-2"></a>Beweissammlung – Deltas für SOC 2

Wenn Sie die SOC 2-Compliance bereits erreicht haben, müssen die folgenden Deltas (Lücken), die nicht vollständig von SOC 2 abgedeckt sind, im Rahmen dieser Microsoft 365 Zertifizierung überprüft werden.

> [!NOTE]
> Im Rahmen der Microsoft 365 Zertifizierungsbewertung ermittelt der Zertifizierungsanalyst, ob eines der zugeordneten SOC 2-Steuerelemente nicht in Ihre SOC 2-Bewertung einbezogen wurde, und kann auch beschließen, Steuerelemente zu testen, die als einbezogen angesehen wurden, um weitere Sicherheit zu gewährleisten. Alle Anforderungen, die in Ihrer SOC 2-Bewertung fehlen, müssen als Teil der Microsoft 365 Zertifizierungsbewertungsaktivitäten einbezogen werden.

**Schutz vor Schadsoftware – Anwendungssteuerung**

Wenn der Schutz vor Schadsoftware durch den Einsatz von Antivirensoftware besteht und in Ihrem SOC 2-Bericht nachgewiesen wird, ist keine weitere Untersuchung erforderlich. Wenn kein Antivirus vorhanden ist, müssen Zertifizierungsanalysten Nachweise von Anwendungskontrollmechanismen identifizieren und bewerten, um die Detonation von Schadsoftware in der Umgebung zu verhindern. Dies erfordert Folgendes:

* Bereitstellen oder Veranschaulichen der unterstützenden Dokumentation, in der detailliert beschrieben wird, wie Die Anwendungskontrolle software so konfiguriert ist, dass sie bestimmte Anwendungssteuerungsmechanismen (z. B. Allowlisting, Codesignierung usw.) erfüllt.

* Veranschaulichen Sie, wie die Anwendungsgenehmigung durchgeführt wird, und bestätigen Sie, dass dies abgeschlossen ist.

*   Zeigen Sie, dass eine vollständige Liste der genehmigten Anwendungen mit geschäftlicher Begründung vorhanden ist.

*   Veranschaulichen Sie, dass die Anwendungssteuerung für alle Beispielsystemkomponenten wie dokumentiert konfiguriert ist.

**Patchverwaltung – Patching**

Da SOC 2-Audits diese Kategorie nicht speziell bewerten, müssen Sie:

*   Jedes Low-, Medium-, High- oder Critical-Problem muss in normalen Patching-Aktivitätsfenstern gepatcht werden.

*   Softwarekomponenten und Betriebssysteme, die vom Hersteller nicht mehr unterstützt werden, DÜRFEN nicht innerhalb der Umgebung verwendet werden. Unterstützende Richtlinien MÜSSEN vorhanden sein, um sicherzustellen, dass nicht unterstützte Softwarekomponenten/Betriebssysteme aus der Umgebung entfernt werden, und ein Prozess zur Identifizierung, wann Softwarekomponenten das Ende der Lebensdauer erreichen, müssen vorhanden sein.

**Firewall – Firewalls**

Da BEI SOC 2-Prüfungen änderungssteuerelemente zu Firewallzugriffssteuerungslisten nicht speziell bewertet werden, müssen Sie folgende Aufgaben ausführen:

* Veranschaulichen Sie, dass der gesamte zulässige Datenverkehr durch die Firewall(n) einen Autorisierungsprozess durchläuft, der zur Dokumentation des gesamten Datenverkehrs mit einer geschäftlichen Begründung führt.

* Zeigen Sie, dass Firewallregelüberprüfungen mindestens alle sechs Monate durchgeführt werden.

Zusätzliche Gutschriften werden bereitgestellt, wenn ein Web Application Firewall (WAF) oder ähnliches bereitgestellt wird, um vor den unzähligen Bedrohungen und Sicherheitsrisiken der Webanwendung zu schützen, denen die Anwendung ausgesetzt werden kann. Wenn eine WAF oder ähnliches vorhanden ist, müssen Sie folgende Aktionen ausführen:

* Veranschaulichen Sie, dass waf im aktiven Verteidigungsmodus konfiguriert ist oder mehr mit Warnungen überwacht wird.

* Veranschaulichen, dass WAF so konfiguriert ist, dass SSL-Offloading unterstützt wird.

* Ist gemäß dem OWASP Core Rule Set (3.0 oder 3.1) konfiguriert, um vor den meisten der folgenden Angriffstypen zu schützen:

&emsp;&#x2713; Protokoll- und Codierungsprobleme.

&emsp;&#x2713; header injection, request smuggling, and response splitting.

&emsp;&#x2713; Datei- und Pfad-Traversalangriffe.

&emsp;&#x2713; Remote-Dateieinschlussangriffe (Remote File Inclusion, RFI).

&emsp;&#x2713; Remotecodeausführungsangriffe.

&emsp;&#x2713; PHP-Injection-Angriffe.

&emsp;&#x2713; websiteübergreifende Skriptangriffe.

&emsp;&#x2713; SQL-Injection-Angriffe.

&emsp;&#x2713; Session-Fixation-Angriffe.

**Steuerelement ändern**

Da BEI SOC 2-Audits einige Elemente von Änderungsanforderungsprozessen nicht speziell bewertet werden, muss der Entwickler folgende Aufgaben durchführen:

* Veranschaulichen, wie Entwicklungs-/Testumgebungen von der Produktionsumgebung getrennt sind, wodurch die Trennung von Aufgaben erzwungen wird.

* Veranschaulichen, wie Livedaten nicht in entwicklungs-/testumgebungen verwendet werden.

* Demonstrieren, dass Funktionalitätstests durchgeführt werden, nachdem die Änderungen abgeschlossen sind.

* Zeigen Sie, dass Änderungsanforderungen nach dem Testen der Funktionalität abgemeldet werden.

**Sichere Softwareentwicklung/-bereitstellung**

Da SOC 2-Audits nicht speziell auf einige Elemente sicherer Softwareentwicklungs- und Bereitstellungsprozesse zugreifen; Dies erfordert Folgendes:

*   Sie MÜSSEN über einen etablierten und dokumentierten Softwareentwicklungsprozess verfügen, der den gesamten Softwareentwicklungslebenszyklus abdeckt.

*   Entwickler MÜSSEN mindestens jährlich eine sichere Softwarecodierungsschulung absolvieren.

*   Code-Repositorys MÜSSEN durch MFA gesichert werden.

*   Es MÜSSEN angemessene Zugriffskontrollen vorhanden sein, um Code-Repositorys vor bösartigen Codeänderungen zu schützen.

**Kontoverwaltung**

Da BEI SOC2-Prüfungen einige Elemente der Kontoverwaltungsprozesse nicht speziell bewertet werden, müssen Sie:

*   Veranschaulichen, wie die Autorisierungsmechanismen implementiert werden, um Replay-Angriffe zu mindern (z. B. MFA, Kerberos).

*   Zeigen Sie, wie Konten, die in 3 Monaten nicht verwendet wurden, entweder deaktiviert oder gelöscht werden.

*   Richtlinien für sichere Kennwörter oder andere geeignete Gegenmaßnahmen müssen konfiguriert werden, um Benutzeranmeldeinformationen zu schützen. Die folgende Mindestkennwortrichtlinie sollte als Richtlinie verwendet werden:

&emsp;&#x2713; Mindestkennwortlänge von 8 Zeichen.

&emsp;&#x2713; Schwellenwert für die Kontosperrung von nicht mehr als 10 Versuchen.

&emsp;&#x2713; Kennwortverlauf von mindestens 5 Kennwörtern.

&emsp;&#x2713; Durchsetzung der Verwendung sicherer Kennwörter

*   Demonstrieren, dass eindeutige Benutzerkonten für alle Benutzer ausgestellt werden.

*   Wenn sich die Verwaltung des öffentlichen DNS außerhalb der bereichsbezogenen Umgebung befindet, MÜSSEN alle Benutzerkonten, die DNS-Änderungen vornehmen können, für die Verwendung von MFA konfiguriert sein.

**Angriffserkennung und -verhinderung (OPTIONAL).**

Da SOC 2-Audits einige Elemente der Prozesse der Intrusion Detection and Prevention Services (IDPS) nicht speziell bewerten, müssen Sie:

*   IDPS-Signaturen SOLLTEN innerhalb des letzten Tages auf dem neuesten Stand gehalten werden.

*   IDPS SOLLTE für TLS-Inspektion konfiguriert werden

*   IDPS SOLLTE für ALLE eingehenden und ausgehenden Datenverkehr konfiguriert werden

**Ereignisprotokollierung**

Da BEI SOC 2-Audits einige Elemente der Protokollierung von Sicherheitsereignissen nicht speziell bewertet werden, müssen Sie:

* Veranschaulichen, wie auf allen Systemkomponenten innerhalb des Beispielsatzes das folgende System konfiguriert ist, um die folgenden Ereignisse zu protokollieren

&emsp;&#x2713; Benutzerzugriff auf Systemkomponenten und die Anwendungen.

&emsp;&#x2713; Alle Aktionen, die von einem Benutzer mit hohen Berechtigungen ausgeführt werden.

&emsp;&#x2713; Ungültige logische Zugriffsversuche.

Veranschaulichen, dass protokollierte Ereignisse enthalten sind; mindestens die folgenden Informationen:

&emsp;&#x2713; Benutzer.

&emsp;&#x2713; Ereignistyp.

&emsp;&#x2713; Datum und Uhrzeit.

&emsp;&#x2713; Erfolgs-/Fehlerindikator.

&emsp;&#x2713; Bezeichnung, um das betroffene System zu identifizieren.

*   Veranschaulichen Sie, dass alle Systemkomponenten innerhalb des Beispielsatzes so konfiguriert sind, dass die Zeitsynchronisierung verwendet wird und dass diese mit den primären/sekundären Zeitservern identisch sind.

* Zeigen Sie, dass öffentlich zugängliche Systeme eine Protokollierung in einer zentralen Protokollierungslösung durchführen, die sich nicht innerhalb der DMZ befindet.

*   Zeigen Sie, dass öffentlich zugängliche Systeme eine Protokollierung in einer zentralen Protokollierungslösung durchführen, die sich nicht innerhalb der DMZ befindet.

* Veranschaulichen, wie die zentralisierte Protokollierungslösung vor unbefugter Manipulation von Protokollierungsdaten geschützt ist.

* Veranschaulichen, wie Protokollierungsdaten im Wert von mindestens 30 Tagen sofort verfügbar sind, wobei mindestens 90 Tage aufbewahrt werden.

**Risikomanagement**

Da BEI SOC2-Prüfungen einige Elemente von Risikobewertungsprozessen nicht speziell bewertet werden, müssen Sie:

* Nachweis, dass mindestens jährlich eine formale Risikobewertung durchgeführt wird.

*Reaktion auf Vorfälle.*

Da SOC2-Audits einige Elemente der Richtlinien und Prozesse für die Reaktion auf Vorfälle nicht speziell bewerten, müssen Sie:

* Zeigen Sie, dass der Plan/das Verfahren zur Reaktion auf Vorfälle Folgendes umfasst:

&emsp;&#x2713; Spezifische Reaktionsverfahren für erwartete Bedrohungsmodelle.

&emsp;&#x2713; dokumentierten Kommunikationsprozess, um eine rechtzeitige Benachrichtigung wichtiger Interessenträger (Zahlungsmarken/Acquirer, Aufsichtsbehörden, Direktoren, Kunden usw.) sicherzustellen.

## <a name="appendix-f"></a>Anhang F

### <a name="hosting-deployment-types"></a>Hostingbereitstellungstypen

Microsoft bestätigt, dass Sie Anwendungen bereitstellen und App-/Add-In-Code in verschiedenen Hostingumgebungen speichern. Die Gesamtverantwortung einiger Sicherheitskontrollen innerhalb der Microsoft 365 Zertifizierung hängt von der verwendeten Hostingumgebung ab. Anhang F untersucht allgemeine Bereitstellungstypen und ordnet diese den Sicherheitskontrollen zu, die im Rahmen des Bewertungsprozesses ausgewertet werden. Die folgenden Hostingbereitstellungstypen wurden identifiziert:

|Hostingtypen  |Beschreibung  |
|-----|------|
|**ISV Hosted**|Isv-gehostete Typen können so definiert werden, dass Sie für die Infrastruktur verantwortlich sind, die zur Unterstützung der App-/Add-In-Umgebung verwendet wird. Dies kann sich physisch in Ihren eigenen Rechenzentren oder Rechenzentren von Drittanbietern mit einem Co-Location-Dienst befinden. Letztendlich haben Sie die volle Eigenverantwortung und administrative Kontrolle über die unterstützende Infrastruktur und Betriebsumgebung.|
|**Infrastructure as a Service (IaaS)** (https://azure.microsoft.com/overview/what-is-iaas/)|Infrastructure as a Service ist ein Dienst, der bereitgestellt wird, bei dem die physische unterstützende Infrastruktur vom Clouddienstanbieter (Cloud Service Provider, CSP) in ihrem Auftrag verwaltet und verwaltet wird. In der Regel liegt die Verantwortung für Netzwerk, Speicher, physische Server und die Virtualisierungsinfrastruktur im Verantwortungsbereich des CSP. Das Betriebssystem, Middleware, Runtime, Daten und Anwendungen sind ihre Zuständigkeiten. Firewallfunktionen würden auch vom Drittanbieter verwaltet und verwaltet, die Wartung der Firewallregelbasis wäre jedoch in der Regel immer noch sache des Verbrauchers.|
|**Platform as a Service/Serverless (PaaS)** (https://azure.microsoft.com/overview/what-is-paas/)| Mit Platform as a Service werden Sie mit einer verwalteten Plattform bereitgestellt, die einen Dienst darstellt, der genutzt werden kann. Sie müssen keine Sysadmin-Funktionen ausführen, da das Betriebssystem und die unterstützende Infrastruktur vom CSP verwaltet werden. Dies wird in der Regel verwendet, wenn Organisationen sich nicht um die Präsentation eines Webdiensts kümmern möchten und sich stattdessen auf das Erstellen des Quellcodes der Webanwendung und das Veröffentlichen der Webanwendung in den in der Cloud verwalteten Webdiensten konzentrieren können.  Ein weiteres Beispiel kann ein Datenbankdienst sein, bei dem eine Verbindung zu einer Datenbank besteht, die unterstützende Infrastruktur und Datenbankanwendung jedoch vom Verbraucher abstrahiert wird.   **Hinweis: Serverlos und PaaS sind ähnlich, daher gelten für den Zweck des Microsoft 365 Zertifizierungshosting-Bereitstellungstyps serverlos und PasS als identisch.**|
|**Hybrid gehostet**|Mit dem hybrid gehosteten Typ können Sie mehrere gehostete Typen verwenden, um verschiedene Teile der unterstützenden Umgebung zu unterstützen. Dies kann eher der Fall sein, wenn Apps/Add-Ins über mehrere M365-Stapel hinweg verwendet werden. Obwohl die Microsoft 365-Zertifizierung unterstützt, wo Apps/Add-Ons über mehrere M365-Dienste hinweg entwickelt werden, müsste eine Bewertung der gesamten (app-/add-ins-übergreifenden) unterstützenden Umgebung entsprechend den jeweiligen "Gehosteten Typzuordnungen" bewertet werden. Gelegentlich können Sie unterschiedliche gehostete Typen für ein einzelnes Add-In verwenden, wo dies ausgeführt wird, muss die Anwendbarkeit von Kriterien weiterhin den Kriterien "Gehostete Typzuordnungen" für die verschiedenen gehosteten Typen entsprechen.|
|**Shared Hosting**|Shared Hosting ist der Ort, an dem Sie die Umgebung innerhalb einer Plattform hosten, die von mehreren einzelnen Verbrauchern gemeinsam genutzt wird. Die Microsoft 365 Zertifizierungsspezifikation wurde aufgrund der Einführung der Cloud nicht dazu geschrieben, das gemeinsame Hosting ist nicht üblich. Wenn Sie glauben, dass dies verwendet wird, wenden Sie sich bitte an Microsoft, da zusätzliche Anforderungen erstellt werden müssen, um die zusätzlichen Risiken unter dieser Art von Hostingtyp zu berücksichtigen.|


## <a name="appendix-g"></a>Anhang G

## <a name="learn-more"></a>Weitere Informationen

[Microsoft 365 App Compliance Program Overview](~/overview.md)  
[Was ist Microsoft 365 App Publisher Attestation?](~/docs/attestation.md)  
[Was ist Microsoft 365 Zertifizierung?](~/docs/enterprise-app-certification-guide.md)

## <a name="glossary"></a>Glossar

### <a name="aia"></a>AIA

*Autoritätsinformationszugriff ist ein Dienstspeicherortdeskriptor, der zum Suchen des Zertifikats der ausstellenden Zertifizierungsstelle verwendet wird.

### <a name="crl"></a>ZERTIFIKATSPERRLISTE

*Die Zertifikatsperrliste stellt eine Möglichkeit für einen SSL-Endpunkt (Secure Sockets Layer) bereit, um zu überprüfen, ob ein von einem Remotehost empfangenes Zertifikat gültig und vertrauenswürdig ist.

### <a name="cvss-score"></a>CVSS-Bewertung

*Common Vulnerability Scoring System ist ein veröffentlichter Standard, der die Sicherheitsanfälligkeit misst und eine numerische Bewertung basierend auf ihrem Schweregrad berechnet.

### <a name="cvss-patch-management-guidelines"></a>CVSS-Patchverwaltungsrichtlinien

* Kritisch (9,0 - 10,0)
* Hoch (7,0 - 8,9)
* Mittel (4,0 - 6,9)
* Niedrig (0,0 - 3,9)

### <a name="dmz"></a>DMZ

*Die demilitarisierte Zone ist ein physisches oder logisches Zwischennetzwerk, das direkt mit externen oder nicht-kompatiblen Netzwerken interagiert und gleichzeitig das interne, private Netzwerk des Hosts getrennt und isoliert hält.

### <a name="euii"></a>EUII

*Identifizierbare Informationen für Endbenutzer*.

### <a name="gdpr"></a>DSGVO

*Die Datenschutz-Grundverordnung ist eine Datenschutz- und Datenschutzverordnung der Europäischen Union (EU) für alle Eu-Bürgerdaten, unabhängig davon, wo sich Ihre Anwendungsstelle befindet.

### <a name="hsts"></a>HSTS

*HTTP Strict Transport Security verwendet einen HTTP-Antwortheader, der den Webbrowser anweist, nur über HTTPS auf Inhalte zuzugreifen.  Dies dient zum Schutz vor Downgrade-Angriffen und Cookie-Hijacking.

### <a name="iec"></a>IEC

*Internationale elektrotechnische Kommission.

### <a name="isms"></a>THEORIEN

*Information Security Management System.

### <a name="isv"></a>ISV

Unabhängige Sicherheitsanbieter sind Einzelpersonen und Organisationen, die Software entwickeln, vermarkten und verkaufen, die auf Software- und Hardwareplattformen von Drittanbietern ausgeführt wird.

### <a name="iso-27001"></a>ISO 27001

Ein Spezifikationsframework für das Informationssicherheits-Managementsystem für alle technischen Kontrollen in Risikomanagementrichtlinien und -verfahrensprozessen einer Organisation.

### <a name="lfi"></a>LFI

*Die lokale Dateieinschluss* ermöglicht es einem Angreifer, Dateien auf einem Server über den Webbrowser einzuschließen.

### <a name="nist"></a>NIST

Das *National Institute of Standards* (NIST), eine Nicht-Regulierungsbehörde des US-Handelsministeriums, bietet Organisationen des privaten Sektors in den USA Anleitungen zur Bewertung und Genehmigung ihrer Fähigkeit, Cyberangriffe zu verhindern, zu erkennen und darauf zu reagieren.

### <a name="non-significant-changes"></a>Nicht signifikante Änderungen

* Kleinere Fehlerbehebungen.
* Geringfügige Leistungsverbesserungen.
* Betriebssystem-/Bibliotheken-/Client- und Serveranwendungspatches.

### <a name="ocsp"></a>OCSP

*Das Onlinezertifikatstatusprotokoll* wird verwendet, um den Sperrstatus digitaler X.509-Zertifikate zu überprüfen.

### <a name="oii"></a>OII

*Organisationsidentifizierbare Informationen*.

### <a name="owasp"></a>OWASP

*Öffnen Sie die Project webanwendungssicherheit*.

### <a name="pci-dss"></a>PCI/DSS

*Payment Card Industry Data Security Standard*, eine Organisation, die weltweit Standards für die Sicherheit von Karteninhaberdaten aufrechterhält.

### <a name="pen-testing"></a>Stifttests

*Penetrationstests* sind eine Methode zum Testen einer Web-App, indem böswillige Angriffe simuliert werden, um Sicherheitslücken zu finden, die ein Angreifer ausnutzen könnte.

### <a name="saml"></a>SAML

*Security Assertion Markup Language* ist ein offener Standard für den Austausch von Authentifizierungs- und Autorisierungsdaten zwischen dem Benutzer, dem Identitätsanbieter und dem Dienstanbieter.

### <a name="sensitive-data"></a>Vertrauliche Daten

* Zugriffssteuerungsdaten.
* Kundeninhalte.
* Informationen zur Endbenutzeridentität.
* Supportdaten.
* Öffentliche personenbezogene Daten.
* Pseudonyme Informationen des Endbenutzers.

### <a name="significant-changes"></a>Wesentliche Änderungen

* Verlagerung der Hostingumgebung.
* Wichtige Modernisierungen der unterstützenden Infrastruktur; z. B. Implementierung einer neuen Firewall, wichtige Upgrades für frontorientierte Dienste usw.
* Hinzufügen von Funktionen und/oder Erweiterungen zu Ihrer App.
* Updates für Ihre App, die zusätzliche vertrauliche Daten erfassen.
* Änderungen an den Datenflüssen oder Autorisierungsmodellen Ihrer App
* Hinzufügen von API-Endpunkten oder API-Endpunktfunktionen.

### <a name="soc-2"></a>SOC 2

*Service Organization Control 2*, ein technisches Überwachungsverfahren, das aus fünf Trust Service Principles besteht, um sicherzustellen, dass Dienstanbieter die Daten und den Datenschutz für die Kunden einer Organisation sicher verwalten.

### <a name="ssl"></a>SSL

*Secure Sockets Layer*.

### <a name="tls"></a>TLS

*Transport Layer Security*.
