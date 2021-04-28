---
ms.author: oromalle
title: Microsoft 365 Certification Submission Guide
author: orionomalley
description: Detaillierte Ansicht des Microsoft 365-Zertifizierungs-Übermittlungshandbuchs
keywords: App-Zertifizierungsteams Microsoft 365 Security Compliance m365
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 4d0f09b3a1dd6bde7022e93d08a491e2855d90a7
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/28/2021
ms.locfileid: "52071068"
---
# <a name="microsoft-365-certification-submission-guide"></a>Microsoft 365 Certification Submission Guide

**Inhalt dieses Artikels:**
- [Einführung](#introduction)
- [Voraussetzungen](#prerequisites) 
- [Updates für Microsoft 365-Zertifizierungsspezifikationen](#microsoft-365-certification-specification-updates)
- [Zertifizierungsbereich](#certification-scope)
- [Zertifizierungsprozess](#certification-process)
- [Compliance-Nachweise](#compliance-evidence) 
- [Anfängliche Dokumentübermittlung](#initial-document-submission) 
- [Aktivitäten zur Beweiserfassung und -bewertung](#evidence-collection-and-assessment-activities)
- [Zertifizierungskriterien](#app-certification-criteria)
- [Application Security](#application-security)
- [Betriebssicherheit](#operational-security) 
- [Datenverarbeitungssicherheit und Datenschutz](#data-handling-security-and-privacy)
- [Optionale Überprüfung externer Complianceframeworks](#optional-external-compliance-frameworks-review)
- [Anhang A](#appendix-a)
- [Anhang B](#appendix-b) 
- [Anhang C](#appendix-c) 
- [Anhang D](#appendix-d) 
- [Anhang E](#appendix-e) 
- [Anhang F](#appendix-f) 
- [Anhang G ](#appendix-g)
- [Weitere Informationen](#learn-more) 
- [Glossar](#glossary) 


## <a name="introduction"></a>Einführung

Die Microsoft 365-Zertifizierung ist Teil des Microsoft 365-App-Compliance-Programms und bietet Unternehmen die Sicherheit und Sicherheit, dass Daten und Datenschutz bei der Integration von Drittanbieter-Entwickler-Apps/-Add-Ins in die Microsoft 365-Plattform angemessen gesichert und geschützt werden. Anwendungen und Add-Ins, die die Validierung bestehen, werden als **Microsoft 365 Certified im** gesamten Microsoft 365-Ökosystem bezeichnet. 

Durch die Teilnahme am Microsoft 365-Zertifizierungsprogramm erklären Sie sich mit diesen ergänzenden Bedingungen einverstanden und verpflichten sich zur Einhaltung der zugehörigen Dokumentation, die für Ihre Teilnahme am Microsoft 365-Zertifizierungsprogramm mit der Microsoft Corporation ("Microsoft", "wir", "uns" oder "unser") gilt. Sie vertreten und garantieren uns, dass Sie die Befugnis haben, diese ergänzenden Microsoft 365-Zertifizierungsbedingungen im Namen Ihrer Person, eines Unternehmens und/oder einer anderen Entität zu akzeptieren, falls zutreffend. Wir können diese ergänzenden Bedingungen jederzeit ändern, ändern oder beenden. Ihre fortgesetzte Teilnahme am Microsoft 365-Zertifizierungsprogramm nach jeder Änderung oder Änderung bedeutet, dass Sie den neuen ergänzenden Bedingungen zustimmen. Wenn Sie den neuen ergänzenden Bedingungen nicht zustimmen oder diese ergänzenden Bedingungen beenden, müssen Sie die Teilnahme am Microsoft 365-Zertifizierungsprogramm beenden.

Dieses Dokument richtet sich an ISVs (Unabhängige Softwareanbieter), um Informationen über den Microsoft 365-Zertifizierungsprozess, die Voraussetzungen zum Starten des Prozesses und Details zu bestimmten Sicherheitskontrollen, die ISVs haben müssen, zur Verfügung zu stellen.  Allgemeine Informationen zum Microsoft 365 App Compliance-Programm finden Sie auf der Microsoft 365 App [Compliance-Programmseite](https://docs.microsoft.com/microsoft-365-app-certification/overview). 

> [!IMPORTANT]
> Derzeit ist die Microsoft 365-Zertifizierung eingeschränkt:
>* Microsoft Teams-Anwendungen (Registerkarten, Bots usw.) .
>* Sharepoint Apps/Add-ins
>* Office-Add-Ins (Word, Excel, PowerPoint, Outlook, Project, OneNote)

## <a name="prerequisites"></a>Voraussetzungen

### <a name="publisher-attestation"></a>Publisher Attestation

Bevor Sie den Microsoft 365-Zertifizierungsprozess erhalten, müssen Sie publisher attestation abgeschlossen haben. Sie können jedoch den Microsoft 365-Zertifizierungsprozess starten, bevor Sie publisher attestation abschließen.  

### <a name="read-the-microsoft-365-certification-specification"></a>Lesen der Microsoft 365-Zertifizierungsspezifikation

Microsoft empfiehlt allen ISVs (Unabhängiger Softwareanbieter), diese Microsoft 365-Zertifizierungsspezifikation vollständig zu lesen, um sicherzustellen, dass alle anwendbaren Steuerelemente von der umgebungsunabhängigen Umgebung und der App/dem Add-In erfüllt werden. Dadurch wird ein reibungsloser Bewertungsprozess sichergestellt.

## <a name="microsoft-365-certification-specification-updates"></a>Updates für Microsoft 365-Zertifizierungsspezifikationen 

Updates der Microsoft 365-Zertifizierungsspezifikation werden ungefähr alle sechs bis zwölf Monate erwartet. Diese Updates können neue Zielsicherheitsdomänen und/oder Sicherheitssteuerelemente einführen. Updates basieren auf Entwicklerfeedback, Änderungen an der Bedrohungslandschaft und erhöhen die Sicherheitsbasis des Programms, sobald es gereift ist. 

ISVs, die bereits mit der Microsoft 365-Zertifizierungsbewertung begonnen haben, können die Bewertung mit der Version der Microsoft 365-Zertifizierungsspezifikation fortsetzen, die beim Starten der Bewertung gültig war. Alle neuen Übermittlungen, einschließlich der jährlichen Rezertifizierung, müssen anhand der veröffentlichten Version bewertet werden.

> [!NOTE]
> Sie müssen nicht alle Steuerelemente in dieser Microsoft 365-Zertifizierungsspezifikation einhalten, um eine Zertifizierung zu erhalten. Für jede der sicherheitsdomänen, die in dieser Microsoft 365-Zertifizierungsspezifikation behandelt werden, werden jedoch Schwellenwerte übergeben (die nicht offengelegt werden). Einige Steuerelemente werden als **"Harter Fehler"** bezeichnet, was bedeutet, dass das Fehlen dieser Sicherheitssteuerelemente zu einer fehlgeschlagenen Bewertung führt. 

## <a name="certification-scope"></a>Zertifizierungsbereich

Die Umgebung im Bereich ist die Umgebung, die die Übermittlung des App-/Add-In-Codes unterstützt und alle **Back-End-Systeme** unterstützt, mit der die App/das Add-In möglicherweise kommuniziert. Alle zusätzlichen Umgebungen, die mit verbundenen Umgebungen verbunden sind, werden ebenfalls in den Bereich einbezogen, es sei denn, eine angemessene Segmentierung ist vorhanden, und die verbundenen Umgebungen können sich nicht auf die Sicherheit der umgebungsgebundenen Umgebung auswirken. Notfallwiederherstellungsumgebungen müssen ebenfalls in den Umfang der Bewertung einbezogen werden, da diese Umgebungen zur Erfüllung des Diensts erforderlich wären, falls etwas mit der primären Umgebung geschieht.  Der Begriff **systemin-scope-Komponenten** referenziert alle Geräte und Systeme, die innerhalb der   Bereichsumgebung verwendet werden.  Bereichsintegierte Komponenten umfassen, sind jedoch nicht auf Folgendes beschränkt:
* Die Webanwendungen.
* Server.
* Firewalls (oder äquivalent).
* Switches.
* Lastenausgleich.
* Virtuelle Infrastruktur.
* Webverwaltungsportale für Cloudanbieter 

> [!IMPORTANT]
> Die bereichsinterne Umgebung muss über eine DMZ verfügen, und die unterstützende Umgebung der App/des Add-Ins muss von den internen Geschäftssystemen und Unternehmensumgebungen segmentiert werden, wodurch der Umfang der Bewertungsaktivitäten auf die in-Scope-Systeme begrenzt wird. Zertifizierungsanalysten überprüfen die Segmentierungstechniken während der Bewertung zusammen mit der Überprüfung von Penetrationstestberichten, die Tests enthalten sollten, um die Effektivität aller verwendeten Segmentierungstechniken zu überprüfen.

### <a name="infrastructure-as-a-service-iaas-platform-as-a-service-paas-and-software-as-a-service-saas"></a>Infrastructure as a Service (IaaS), Platform as a Service (PaaS) und Software as a Service (SaaS) 
Wenn IaaS und/oder PaaS verwendet werden, um die Infrastruktur der zu überprüfenden Anwendung oder Add-In-Codezustellung zu unterstützen, ist der Cloudplattformanbieter für einige der während des Zertifizierungsprozesses bewerteten Sicherheitskontrollen verantwortlich. Daher müssen Zertifizierungsanalysten über externe Complianceberichte wie [PCI DSS](bookmark://pci-dss)   Attestation of Compliance (AOC), ISO27001 oder [SOC 2](bookmark://soc-2)Typ II unabhängige externe Überprüfung bewährter Sicherheitsmethoden durch den Cloudplattformanbieter   erhalten. 

Anhang F enthält Details dazu, welche Sicherheitssteuerelemente basierend auf den folgenden Bereitstellungstypen und basierend darauf anwendbar sein werden, ob die App/das Add-In M365-Daten exfiltiert oder nicht: 
* ISV Hosted 
* Gehostete IaaS 
* PaaS/Serverless Hosted 
* Hybrid gehostet 
* Shared Hosted 

Wo IaaS oder PaaS bereitgestellt wird, müssen Sie nachweisen, dass die Umgebung innerhalb dieser Bereitstellungstypen gehostet wird.

### <a name="sampling"></a>Sampling

Anträge auf Nachweise zur Unterstützung der Zertifizierungsbewertung sollten auf einer Stichprobe der systembezogenen Komponenten unter Berücksichtigung verschiedener Betriebssysteme, der primären Funktion des Geräts und verschiedener Gerätetypen basieren. Zu Beginn des Zertifizierungsprozesses wird ein geeignetes Beispiel ausgewählt. Die folgende Tabelle sollte als Leitfaden für die Größe der Stichprobe verwendet werden:

|Größe der Grundgesamtheit              | Beispiel                  |
|---------------------------- |-------------------------|
|<5|1|
|>5 & <10|2|
|>9 & <25|3|
|>24|4 |

> [!NOTE]
>Wenn Abweichungen zwischen geräten identifiziert werden, die in der ersten Stichprobe enthalten sind, kann die Stichprobengröße während der Bewertung erhöht werden. 

## <a name="certification-process"></a>Zertifizierungsprozess

Bevor Sie mit dem Zertifizierungsprozess beginnen, müssen Sie das Publisher Attestation erfolgreich gestartet oder abgeschlossen haben. Ihre Bestätigungsantworten werden zur Unterstützung des Microsoft 365-Zertifizierungsprozesses verwendet und gehen wie folgt vor: 

1. Überprüfen Der Publisher Attestation-Dokumentation, um die Anpassung an Ihre aktuelle Umgebung sicherzustellen 
2. Anfordern des Fortschritts zur Microsoft 365-Zertifizierung per E-Mail <AppCert@microsoft.com> 
3. Zertifizierungsanalysten öffnen einen Dialog, bevor sie den Microsoft 365-Zertifizierungsprozess starten   
4. Übermitteln der [ursprünglichen Dokumentübermittlung](#initial-document-submission)
5. Zertifizierungsanalyst stellt eine Liste der Steuerelemente zur Verfügung, für die Nachweise erforderlich sind, wodurch der Microsoft 365-Zertifizierungsprozess offiziell gestartet wird.
6. Übermitteln von Nachweisen, die belegen, dass alle In-Scope-Microsoft 365-Zertifizierungssteuerelemente innerhalb eines 60-Tage-Fensters erfüllt wurden, um die Microsoft 365-Zertifizierung zu vervollständigen 

> [!IMPORTANT]
> **Übermittlungszeitrahmen:** Es wird davon ausgegangen, dass der Bewertungsprozess im Durchschnitt 15 Tage dauern sollte, sofern Sie in der Lage sind, zeitnah auf Nachweisanforderungen zu reagieren. Microsoft empfiehlt, dass Sie sicherstellen, dass diese Zertifizierungsübermittlungsanleitung gelesen wurde, und dass Sie sicher sind, dass Sie die in ihr festgelegten Steuerelemente erfüllen können, und Sie können genügend Nachweise vor dem Starten des Zertifizierungsprozesses bereitstellen. Nach dem Starten des Zertifizierungsprozesses dürfen maximal 60 Tage die Bewertung abschließen, andernfalls sind bereits gesammelte Nachweise veraltet. Wenn nach ablaufendem 60-Tage-Zeitraum keine erfolgreiche Bewertung erreicht ist, wird für die Übermittlung ein Fehler ausgegeben, und der Prozess muss erneut gestartet werden. Wenn ein Fehler ausgegeben wird, weil die Microsoft 365-Zertifizierungsspezifikation nicht erfüllt ist oder der Zeitraum von 60 Tagen erreicht ist und nicht genügend Nachweise bereitgestellt werden, werden fehlerhafte Ergebnisse von Microsoft nicht veröffentlicht. 

## <a name="compliance-evidence"></a>Compliance-Nachweise

Obwohl dies nicht erforderlich ist, können Sie diese Zertifizierungen verwenden, um einige der Microsoft 365-Zertifizierungssteuerelemente zu erfüllen, wenn Sie derzeit andere externe Sicherheitsframeworks einhalten. Zertifizierungsanalysten überprüfen den Umfang und die Sicherheitssteuerungsabdeckung aller unterstützten externen Sicherheitsframeworks, um zu bestimmen, welche Steuerelemente von der Microsoft 365-Zertifizierungsbewertung ausgeschlossen werden können, vorausgesetzt, der Umfang der externen Sicherheitsframeworks umfasst die In-Scope-Umgebungen für die Microsoft 365-Zertifizierungsbewertung. 

Zertifizierungsanalysten versuchen, vorhandene externe Sicherheitsframeworks an die Microsoft 365-Zertifizierungsspezifikation auszurichten. Wenn die unterstützende Dokumentation jedoch nicht die Sicherheit bieten kann, dass Die Microsoft 365-Zertifizierungssteuerelemente im Rahmen der Externen Sicherheitsframework-Überwachung/-bewertung bewertet wurden, müssen Sie zusätzliche Nachweise dafür bereitstellen, dass diese Kontrollen bereits installiert sind. 

Derzeit umfassen die externen Sicherheitsframeworks, die zur Unterstützung der Microsoft 365-Zertifizierungsbewertung verwendet werden können:

*  [ISMS](#isms) / [IEC](#iec) – IS0/IEC 27001-Spezifikation 
*  [PCI DSS](#pci-dss)
*  [SOC 2](#soc-2)

Die Dokumentation muss angemessen belegen, dass die Bereichsumgebung für die Microsoft 365-Zertifizierung in den Bereich dieser externen Sicherheitsframeworks einbezogen wurde. Die Validierung dieser Sicherheitsframeworks wird durch die Annahme von Nachweisen gültiger Zertifizierungen durch seriöse externe Drittanbieterunternehmen erfüllt. Diese seriösen Unternehmen müssen Mitglieder internationaler Akkreditierungsstellen für relevante Complianceprogramme sein.Weitere Informationen finden Sie unter ISO-Zertifizierungs- und [Konformitätsstandards](https://www.iso.org/certification.html) für ISO 27001 und [Qualified Security Assessors](https://www.pcisecuritystandards.org/assessors_and_solutions/qualified_security_assessors) (QSA) für PCI DSS. 

In der folgenden Tabelle wird die Dokumentation aufgeführt, die von Zertifizierungsanalysten im Rahmen dieses Überprüfungsprozesses benötigt wird:

| **Standard** | **Anforderungen** |
| ----- | ----- |
| **[ISO 27001](#iso-27001)** | Eine öffentlich zugängliche Version der **Statement of Applicability** (SOA) und eine Kopie des ausgestellten ISO 27001-Zertifikats sind erforderlich.  Die SOA fasst Ihre Position zu jedem der 114 Informationssicherheitssteuerelemente zusammen und wird verwendet, um zu ermitteln, ob ein Ausschluss von Steuerelementen, die im ISO 27001-Zertifikat nicht zufriedenstellend detailliert sind, ausgeschlossen wird. Wenn dies nicht durch Überprüfen der öffentlich zugänglichen Version der SOA bestimmt werden kann, benötigt der Analyst möglicherweise Zugriff auf die vollständige SOA, wenn ISO 27001 verwendet wird, um einige der Microsoft 365-Zertifizierungsspezifikationssteuerelemente zu überprüfen.  Neben der Überprüfung des Umfangs der ISO 27001-Bewertungsaktivitäten bestätigen die Analysten auch die Gültigkeit des Überwachungsunternehmens wie oben beschrieben.|
|**[PCI/DSS](#pci-dss)**| Ein gültiges Dokument der Stufe **1 Attestation of Compliance** (AOC) muss eindeutig angegeben werden, in dem die Anwendungs- und Systemkomponenten des Bereichs eindeutig angegeben werden.  Ein Selbstbewertungs-AOC **wird nicht** als Nachweis bewährter Methoden für die Besprechungssicherheit akzeptiert. Das AOC wird verwendet, um zu bestimmen, welche der Microsoft 365-Zertifizierungsspezifikationssteuerelemente im Rahmen der PCI-DSS-Bewertung ausgewertet und bestätigt wurden.|
|**[SOC 2](#soc-2)**|Der **SOC 2-Bericht (Typ I** oder Typ II) muss aktuell sein (innerhalb der letzten 15 Monate ausgestellt und der deklarierte Zeitraum beginnt innerhalb der letzten 27 Monate), um als Nachweis der Konformität mit den Bewertungssteuerelementen innerhalb dieser Microsoft 365-Zertifizierungsspezifikation verwendet zu werden.|


## <a name="microsoft-365-certification"></a>Microsoft 365-Zertifizierung

Unterstützte externe Sicherheitsframeworks können als Nachweis für die Besprechung einiger Microsoft 365-Zertifizierungssteuerelemente verwendet werden. Bevor externe Sicherheitsframeworks berücksichtigt werden können, überprüfen Zertifizierungsanalysten den Umfang und die Sicherheitssteuerung des externen Sicherheitsframework mithilfe der oben eingereichten Dokumentation. 

Die folgenden Anhänge können verwendet werden, um zu ermitteln, wo potenzielle Lücken zwischen dem externen Sicherheitsframework und der Microsoft 365-Zertifizierungsspezifikation wie folgt vorhanden sind: 

|**Framework** | **Zusätzliche Überlegungen** |
|-------------- | --------------------|
|ISO 27001| [**Anhang C**](#appendix-c): Evidence Collection – Deltas für ISO 27001.|
|PCI/DSS | [**Anhang D**](#appendix-d): Evidence Collection – Deltas für PCI DSS.|
|SOC 2| [**Anhang E**](#appendix-e): Evidence Collection – Deltas für SOC 2.|

> [!NOTE]
> Obwohl die oben genannten externen Sicherheitsstandards/Frameworks als Nachweis für einige der Microsoft 365-Zertifizierungssteuerelemente übermittelt werden können, bedeutet das Bestehen der Microsoft 365-Zertifizierung nicht, dass Sie eine Prüfung für diese Standards/Frameworks erfolgreich bestehen. Die Microsoft 365-Zertifizierungsspezifikation ist nur eine kleine Teilmenge dieser Sicherheitsstandards/Frameworks, mit der Microsoft ein Maß an Sicherheit in Bezug auf Ihre Sicherheitslage erhalten kann.

## <a name="initial-document-submission"></a>Anfängliche Dokumentübermittlung

Die anfängliche Dokumentübermittlung hilft Zertifizierungsanalysten bei der Durchführung von Bereichsprüfungen und bei der Bestimmung des Umfangs ihrer Bewertung. Danach müssen Sie unterstützende Dokumentationen und Nachweise übermitteln, die zur Durchführung der Bewertung verwendet werden. Ihre anfängliche Übermittlung muss die unten angegebenen Informationen enthalten:

| **Übersicht über &nbsp; die Dokumentation**     |   **Dokumentationsdetails**  |
| -------------------------| -----------------------------|
|**App/Add-In-Beschreibung** | Eine Beschreibung des Zwecks und der Funktionalität der App/des Add-Ins. Dies sollte dem Zertifizierungsanalysten ein gutes Verständnis der Funktionsweise der App/des Add-Ins und der beabsichtigten Verwendung bieten.
|**Bericht über Penetrationstests** |Ein Penetrationstestbericht, der innerhalb der letzten 12 Monate abgeschlossen wurde. Dieser Bericht muss die Umgebung enthalten, die die Bereitstellung der App/des Hinzufügens unterstützt, sowie eine zusätzliche Umgebung, die den Betrieb der App/des Add-Ins unterstützt. **Hinweis:** Wenn Sie keine jährlichen Penetrationstests durchführen, können Sie sie über den Zertifizierungsprozess durchführen lassen.|
|**Architekturdiagramme**|Ein logisches Architekturdiagramm, das einen umfassenden Überblick über die unterstützende Infrastruktur Ihrer App/Ihres Add-Ins darstellt. Dies muss **alle Hostingumgebungen** und die unterstützende Infrastruktur umfassen, die die App/das Add-In unterstützt. Dieses Diagramm MUSS alle verschiedenen unterstützenden Systemkomponenten innerhalb der Umgebung darstellen, um Zertifizierungsanalysten dabei zu unterstützen, Systeme in ihrem Umfang zu verstehen und das Sampling zu bestimmen. Geben Sie auch an, welcher Hostingumgebungstyp verwendet wird. ISV Hosted, IaaS, PaaS oder Hybrid. **Hinweis:** Geben Sie an, wo SaaS verwendet wird, die verschiedenen SaaS-Dienste, die zum Bereitstellen der unterstützenden Dienste in der Umgebung verwendet werden.|
|**Öffentlicher Fußabdruck** | Detaillierte Informationen **zu allen** öffentlichen IP-Adressen und URLs, die von der unterstützenden Infrastruktur verwendet werden. Dies muss den vollständigen routingbaren IP-Bereich umfassen, der der Umgebung zugewiesen ist, es sei denn, es wurde eine angemessene Segmentierung implementiert, um den verwendeten Bereich aufteilen zu können (angemessene Nachweise für die Segmentierung sind erforderlich).|
|**Datenflussdiagramme** |Flussdiagramme mit folgenden Details:
||&#x2713; M365-Daten fließen zu und von der App/Dem-Add-In (einschließlich [EUII](#euii) und [OII](#oii) ).|
||&#x2713; M365 Datenflüsse innerhalb der unterstützenden Infrastruktur (sofern zutreffend)|
||&#x2713; Diagramme, in denen hervorgehoben wird, wo und welche Daten gespeichert werden, wie Daten an externe Dritte übergeben werden (einschließlich Details dazu, was Dritte sind) und wie Daten bei der Übertragung über offene/öffentliche Netzwerke und ruheende Netzwerke geschützt werden.|
|**Details zu API-Endpunkten**| Eine vollständige Auflistung aller VON Ihrer App verwendeten API-Endpunkte. Um den Umgebungsbereich zu verstehen, stellen Sie in Ihrer Umgebung API-Endpunktstandorte bereit.                                
|**Microsoft-API-Berechtigungen**| Bereitstellen einer Dokumentation, in der **alle** verwendeten Microsoft-APIs sowie die angeforderten Berechtigungen für die App/das Add-In sowie eine Begründung für die angeforderten Berechtigungen beschrieben werden|
|**Datenspeichertypen** |Datenspeicherung und -verarbeitung von Dokumenten, die:|
||&#x2713; In welchem Umfang werden Ihre Kunden M365 Data [EUII](#euii) und [OII](#oii) empfangen und gespeichert?|
||&#x2713; Der Aufbewahrungszeitraum für Daten.|
||&#x2713; Warum die Kunden-M365-Daten erfasst werden.|
||&#x2713; Wo Kunden-M365-Daten gespeichert werden (sollten in den oben angegebenen Datenflussdiagrammen enthalten sein).|
|**Konformitätsbestätigung**|Unterstützende Dokumentation für externe Sicherheitsframeworks, die in der Publisher Attestation-Übermittlung enthalten sind oder bei der Überprüfung von Microsoft 365-Zertifizierungssteuerelementen berücksichtigt werden müssen. Derzeit werden die folgenden drei unterstützt:|
||&#x2713; PCI [DSS](#pci-dss) Attestation of Compliance (AOC).|
||&#x2713; [SOC 2](#soc-2) Geben Sie I/Type II-Berichte ein.|
||&#x2713; [ISMS](#isms)  /  [IEC](#iec) - 1S0/IEC 27001 Statement of Applicability (SoA) and Certification.|
|**Webabhängigkeiten**|Dokumentation zur Auflistung aller Abhängigkeiten, die von der App/dem Add-In mit den aktuellen ausgeführten Versionen verwendet werden.|
|**Softwareinventar**|Ein aktuelles Softwareinventar, das die in der Umgebung verwendete Software zusammen mit den Versionen enthält.|
|**Hardwareinventar**| Ein aktuelles Hardwareinventar, das von der unterstützenden Infrastruktur verwendet wird. Dies wird verwendet, um bei der Durchführung der Bewertungsphase beim Sampling zu helfen. Wenn Ihre Umgebung PaaS umfasst, geben Sie Details zu den in Anspruch nehmenden Diensten an.|

## <a name="evidence-collection-and-assessment-activities"></a>Aktivitäten zur Beweiserfassung und -bewertung

Durch robuste Aktivitäten zur Erfassung und Bewertung von Nachweisen können Zertifizierungsanalysten Ihre Sicherheitslage bewerten, um ein angemessenes Maß an Datensicherheit und Einhaltung der Microsoft 365-Zertifizierungsspezifikationssteuerelemente zu erhalten. Zertifizierungsanalysten erreichen dies wie folgt: 

**Beweissammlung**

* Anfängliche Dokumentation, hervorgehoben im Abschnitt ["Erstdokumentationsübermittlung"](#initial-document-submission) oben 
* Richtliniendokumente 
* Verarbeiten von Dokumenten 
* Systemkonfigurationseinstellungen 
* Ändern von Tickets 
* Ändern von Steuerelementdatensätzen 
* Systemberichte

Es werden verschiedene Methoden verwendet, um die Nachweise zu sammeln, die zum Abschließen des Bewertungsprozesses erforderlich sind.  Diese Beweissammlung kann in der Form von: 
* Dokumente 
* Screenshots 
* Interviews 
* Bildschirmscharing 

Die verwendeten Beweiserfassungstechniken werden während des Bewertungsprozesses bestimmt. 

**Bewertungsaktivitäten**

Zertifizierungsanalysten überprüfen die von Ihnen zur Verfügung stellten Nachweise, um festzustellen, ob Sie die Kontrollen in dieser Microsoft 365-Zertifizierungsspezifikation ausreichend erfüllt haben. 

Wenn möglich und um den Zeitaufwand für die Bewertung zu reduzieren, [](#initial-document-submission)sollten alle oder alle Dokumentationen, die in der Erstdokumentationsübermittlung beschrieben sind, im Voraus   bereitgestellt werden.

Zertifizierungsanalysten überprüfen zunächst die Nachweise aus der ersten Dokumentationsübermittlung und die Informationen zum Herausgeberzertifikat, um geeignete Untersuchungslinien, die Stichprobengröße und die Notwendigkeit weiterer Nachweise wie oben beschrieben zu ermitteln.  Zertifizierungsanalysten analysieren alle gesammelten Informationen, um Schlussfolgerungen darüber zu ziehen, wie und ob Sie die Kontrollen in dieser Microsoft 365-Zertifizierungsspezifikation erfüllen. 

## <a name="app-certification-criteria"></a>Zertifizierungskriterien für Apps

Ihre App, die unterstützende Infrastruktur und die unterstützende Dokumentation werden in den folgenden Sicherheitsdomänen bewertet:

1. [**Application Security**](#application-security)
1. [**Betriebssicherheit/sichere Bereitstellung**](#operational-security)
1. [**Datenverarbeitungssicherheit und Datenschutz**](#data-handling-security-and-privacy)
1. [**Optionale Überprüfung des externen Complianceframework**](#optional-external-compliance-frameworks-review)

Jede dieser Sicherheitsdomänen umfasst bestimmte Schlüsselsteuerelemente, die eine oder mehrere spezifische Anforderungen umfassen, die im Rahmen des Bewertungsprozesses ausgewertet werden. Um sicherzustellen, dass die Microsoft 365-Zertifizierung für Entwickler aller Größen einschließlich ist, wird jede der vier Sicherheitsdomänen mithilfe eines Bewertungssystems bewertet, um eine Gesamtbewertung der einzelnen Domänen zu ermitteln. Die Ergebnisse für jedes Microsoft 365-Zertifizierungssteuerelement werden basierend auf dem wahrgenommenen Risiko, dass dieses Steuerelement nicht erfüllt wird, zwischen 1 (niedrig) und 3 (hoch) zugewiesen. Jede der vier Sicherheitsdomänen hat eine Mindestprozentmarke, um als Pass betrachtet zu werden. Zu bestimmten Elementen dieser Spezifikation gehören einige automatische Fehlerkriterien:

- API-Berechtigungen, die nicht dem Prinzip der geringsten Rechte (PoLP) folgen.  
- Kein Penetrationstestbericht, wenn er erforderlich ist.
- Keine Schutz vor Schadsoftware
- Mehrstufige Authentifizierung, die nicht zum Schutz des Administrativen Zugriffs verwendet wird.  
- Keine Patchprozesse.  
- Keine geeigneten [DSGVO-Datenschutzhinweise.](#gdpr)  

## <a name="application-security"></a>Application Security

Die Anwendungssicherheitsdomäne konzentriert sich auf die folgenden drei Bereiche: 
* GraphAPI-Berechtigungsüberprüfung 
* Externe Konnektivitätsprüfungen
* Anwendungssicherheitstests 

**GraphAPI-Berechtigungsüberprüfung**

Die GraphAPI-Berechtigungsüberprüfung wird durchgeführt, um zu überprüfen, ob die App/das Add-In keine überm lässigen Berechtigungen annimmt. Dazu wird manuell überprüft, welche Berechtigungen angefordert werden. Zertifizierungsanalysten verweisen auf diese Prüfungen mit der Publisher Attestation-Übermittlung und bewerten die angeforderte Zugriffsebene, um sicherzustellen, dass die Methoden mit den geringsten Rechten erfüllt werden. Wenn Zertifizierungsanalysten glauben, dass diese Praktiken mit den geringsten Rechten nicht erfüllt werden, führen Zertifizierungsanalysten eine offene Diskussion mit Ihnen, um die geschäftliche Begründung für die angeforderten Berechtigungen zu überprüfen. Alle abweichungen gegenüber Ihrer Publisher Attestation-Übermittlung, die während dieser Überprüfung gefunden wurden, erhalten auch Feedback, damit Ihr Publisher Attestation aktualisiert werden kann. 

**Externe Konnektivitätsprüfungen**

Im Rahmen der Bewertung führt ein Analyst einen kurzen Rundgang durch die Anwendungsfunktionalität durch, um Verbindungen außerhalb von M365 zu identifizieren.  Alle Verbindungen, die nicht als Microsoft- oder direkte Verbindungen zu Ihrem Dienst identifiziert werden, werden während der Bewertung gekennzeichnet und erörtert.

**Anwendungssicherheitstests**

Eine angemessene Überprüfung der Risiken im Zusammenhang mit Ihrer App/Add-In- und unterstützenden Umgebung ist unerlässlich, um Kunden die Sicherheit der App/des Add-Ins zu gewährleisten. Anwendungssicherheitstests in Form von Penetrationstests müssen durchgeführt werden, wenn Ihre Anwendung eine Verbindung mit einem Dienst hat, der nicht von Microsoft veröffentlicht wurde. Wenn Ihre App eigenständig ohne Verbindung zu einem Nicht-Microsoft-Dienst oder -Back-End funktioniert, ist kein Penetrationstest erforderlich.


### <a name="penetration-testing-scope"></a>Umfang der Penetrationstests

Penetrationstests  müssen die Umgebung umfassen, die die Bereitstellung der App/des #A0 unterstützt (z. B. wenn der App-/Add-In-Code gehostet wird, der in der Regel die Ressource innerhalb der Manifestdatei ist) sowie jede zusätzliche Umgebung, die den Betrieb der App/des #A1 unterstützt (z. B. wenn die App/das #A1 mit anderen Webanwendungen außerhalb von Microsoft 365 spricht).  Bei der Definition des Bereichs muss darauf achten, dass alle "verbundenen" Systeme oder Umgebungen, die sich auf die Sicherheit der Bereichsumgebung auswirken können, auch in ALLE Penetrationstests einbezogen werden. 

Wenn Techniken zum Segmentieren der umgebungsintegierten Umgebungen von anderen Umgebungen verwendet werden, müssen Penetrationstests die Effektivität dieser Segmentierungstechniken überprüfen. Dies muss im Penetrationstestbericht detailliert sein. 
 

### <a name="testspecification"></a>Testspezifikation 

|Testen | Steuerelemente |
|-------|-----------|
|**Penetrationstests**| Anwendungs- und Infrastrukturdurchdringungstests **müssen** jährlich (alle 12 Monate) stattfinden und von einem seriösen unabhängigen Unternehmen durchgeführt werden. Die Behebung identifizierter kritischer und risikobehebungsgefährdter Sicherheitsrisiken **muss** innerhalb eines Monats nach Abschluss der Penetrationstests abgeschlossen werden, oder je nach dokumentierten Patchingprozess früher.Der vollständige externe Footprint (IP-Adressen, URLs, API-Endpunkte usw.) MUSS in den Bereich der Penetrationstests einbezogen werden und muss im Penetrationstestbericht dokumentiert werden. Der vollständige externe Footprint (IP-Adressen, URLs, API-Endpunkte usw.) **MUSS** in den Bereich der Penetrationstests einbezogen werden und muss im Penetrationstestbericht dokumentiert werden.                                                                                                                                                                           Webanwendungsdurchdringungstests MÜSSEN alle Sicherheitsrisikoklassen enthalten. Beispielsweise die aktuelle OWASP Top 10 oder SANS Top 25 CWE.                                                                                                                                                                                Ein erneutes Testen identifizierter Sicherheitsrisiken durch das Penetrationstestunternehmen ist nicht erforderlich– Korrektur und Selbstüberprüfung  sind ausreichend, es müssen jedoch ausreichende Nachweise für eine ausreichende Behebung während der Bewertung bereitgestellt werden.|

### <a name="application-security-testing-reportreview"></a>Überprüfung des Berichts über Anwendungssicherheitstests

Penetrationstestberichte werden überprüft, um sicherzustellen, dass es keine Sicherheitsrisiken gibt, die die folgenden Kriterien für automatische **Fehler erfüllen:**

* Vorhandensein eines nicht unterstützten Betriebssystems. 

* Vorhandensein von standardmäßigen, aufzählbaren oder erratenen Administratorkonten.

* Vorhandensein von SQL Einspritzungsrisiken*.

* Vorhandensein von websiteübergreifendem Skripting.*

* Vorhandensein von Sicherheitsrisiken beim Verzeichnisqueren (Dateipfad).*

* Vorhandensein von #A0 (z. B. Kopfzeilenantwortteilung, Schleuseranforderung und Desync-Angriffe).*

* Vorhandensein der Offenlegung von Quellcode (einschließlich [LFI](#lfi)).*

* Alle kritischen oder hohen Bewertung gemäß den CVSS-Patchverwaltungsrichtlinien.

* Jede erhebliche technische Sicherheitslücke, die leicht ausgenutzt werden kann, um eine große Menge von EUII oder OUI zu gefährdeten.

*Unabhängig von der #A0

> [!IMPORTANT]
>Berichte müssen in der Lage sein, genügend Sicherheit zu bieten, damit alle im Abschnitt Anwendungssicherheitstestspezifikationen detaillierten Informationen demonstriert werden können.


### <a name="penetration-testing-requirements-and-cost"></a>Anforderungen und Kosten für Penetrationstests

Für ISVs, die derzeit keine Penetrationstests durchführen, sind Penetrationstests in der Microsoft 365-Zertifizierung enthalten. Microsoft organisiert und übertdeckt die Kosten eines Penetrationstests für bis zu 12 Tage manueller Tests. Die Kosten für Penetrationstests werden basierend auf der Anzahl der Tage berechnet, die zum Testen der Umgebung erforderlich sind. Alle Aufwendungen, die mehr als 12 Testtage überschreiten, sind sache des ISV. Der ISV ist auch für den Nachweis verantwortlich, dass im Penetrationstest identifizierte Sicherheitsrisiken vor der Zertifizierung behoben wurden, aber keinen sauberen Bericht erstellen müssen.

Sobald ein Penetrationstest durchgeführt wurde, ist der ISV für Gebühren im Zusammenhang mit der Neuplanung und Stornierung wie folgt verantwortlich:

| **Neuplanung der Gebührenzeitskala** | **Anteil zahlbar** |
|------------------|------------------------|
| Anforderung zum erneuten Planen, die mehr als 30 Tage vor dem geplanten Startdatum empfangen wurde. | 0 % Zahlbar |
| Erneutes Planen der Anforderung, die 8 bis 30 Tage vor dem geplanten Startdatum empfangen wurde. | 25 % Zahlbar |
| Planen Sie die Empfangene Anforderung innerhalb von 2 bis 7 Tagen vor dem geplanten Startdatum mit einem festen Neubuchungsdatum neu.| 50 % Zahlbar |
| Anforderung zum erneuten Planen, die weniger als 2 Tage vor dem Startdatum empfangen wurde. | 100 % Zahlbar |

| **Zeitskala für Stornierungsgebühr** | **Anteil zahlbar** |
|------------------|------------------------|
| Die Abbruchanforderung wurde mehr als 30 Tage vor dem geplanten Startdatum empfangen. | 25 % Zahlbar |
| Die Stornierungsanforderung wurde 8 bis 30 Tage vor dem geplanten Startdatum empfangen. | 50 % Zahlbar |
| Stornierungsanforderung, die innerhalb von 7 Tagen vor dem geplanten Startdatum empfangen wurde. | 90 % Zahlbar |

## <a name="operational-security"></a>Betriebssicherheit

Diese Domäne misst die Ausrichtung der unterstützenden Infrastruktur- und Bereitstellungsprozesse Ihrer App mit bewährten Sicherheitsmethoden.

### <a name="test-specification"></a>Testspezifikation

|Testen | Steuerelemente |
| ------------------------|------------------------------ |
| **Schutz vor Schadsoftware** | Sie müssen Schadsoftwareschutzmechanismen für alle Systeme in einem Bereich bereitstellen, die häufig von Schadsoftware betroffen sind. Diese Schutzmechanismen können die Verwendung von Antivirensoftware oder Anwendungskontrollestechniken umfassen, die vor Schadsoftware schützen. Wenn Antivirensoftware oder Anwendungssteuerung verwendet wird, muss sie die folgenden Kriterien erfüllen.                                                                                            Antivirensoftware (einschließlich Anti-Malware-Produkte) MUSS folgendes erfüllen: |
||&#x2713; Virenschutzsoftware wird auf allen Systemkomponenten innerhalb des Bereichs ausgeführt.|
||&#x2713; Antivirensoftware wird auf dem neuesten Stand gehalten (innerhalb von 30 Tagen).|
||&#x2713; Virensignaturen werden auf dem neuesten Stand (innerhalb von 1 Tag) gehalten.|
||&#x2713; Überprüfungen bei Zugriff und/oder regelmäßige Überprüfungen mit Benachrichtigungen müssen konfiguriert werden.  Wenn die Überprüfung bei Zugriff  verwendet wird, müssen auch wöchentliche Überprüfungen konfiguriert werden. Wenn die Überprüfung bei Zugriff jedoch nicht konfiguriert ist, muss die tägliche Überprüfung konfiguriert werden.|
||&#x2713; Antivirensoftware **muss** wie folgt konfiguriert werden.|
||&emsp;&#x25fc; Verdächtige Schadsoftware blockieren.|
||&emsp;&#x25fc; quarantäneverdächtiger Schadsoftware.|
||&emsp;&#x25fc; Stellen Sie eine Warnung zu verdächtiger Schadsoftware zur Verfügung.|
||&#x2713; Antivirensoftware **muss** so konfiguriert sein, dass alle Aktivitäten protokolliert werden.
||&#x2713; Richtlinien und Verfahren **müssen** zur Förderung starker Methoden zur Bekämpfung von Schadsoftware verwendet werden.|
||oder|
||Anwendungssteuerelemente müssen auf allen In-Scope-System konfiguriert werden, um folgendes zu erfüllen:|
||&#x2713; Alle zulässigen Anwendungen, die für Systemkomponenten in einem Bereich ausgeführt werden dürfen, MÜSSEN von der Organisation formal genehmigt werden.|
||&#x2713; Die Organisation MUSS eine vollständige Liste der genehmigten Anwendungen mit geschäftlicher Begründung für die Anwendung verwalten.|
||&#x2713; Bestimmte Anwendungskontrollesmechanismen MÜSSEN vollständig dokumentiert sein: d. h. Speicherorte auf der Whitelist; Codesignierung usw.|
||&#x2713; Anwendungssteuerelement MUSS als Dokument konfiguriert werden.|
||&#x2713; dokumentierter Prozess für Anwendungsgenehmigungen muss in der Anwendung gespeichert und überwacht werden können.|
|**Patchverwaltung**|Sie **müssen** über dokumentierte Patchrichtlinien und -verfahren verfügen, um sicherzustellen, dass das Patchen zeitnah durchgeführt wird. Es muss  ein robuster Prozess zur Identifizierung, Bewertung und Patches neuer Sicherheitsrisiken basierend auf der CVSS V3.1 **Recommended Risk Ranking Scores** oder einer entsprechenden Bewertungstaxonomie verwendet werden: 
||**Empfohlene Risikobewertungsbewertungen** (CVSS v3.1 Base Score Range)|
||&emsp;**Kritisch**: 9,0 - 10,0.|
||&emsp;**Hoch**: 7,0 - 8,9.|
||&emsp;**Mittel**: 4,0 - 6,9.|
||&emsp;**Niedrig**: 0,1 - 3,9.|
||&emsp;**Keine**: 0,0 |
|| **WICHTIG:** Der Prozess zum Identifizieren neuer Sicherheitsrisiken muss robust genug sein, um die Identifizierung und das Patchen von Sicherheitsrisiken im Einklang mit dem von Ihnen definierten dokumentierten Patchfenster zu ermöglichen. |
|**Patching**|&#x2713; Kritische, hohe oder mittlere Risikoprobleme müssen innerhalb eines vordefinierten und dokumentierten Zeitraums gepatcht werden, der vom  ISV festgelegt wurde, der das minimale Zeitfenster darstellt, bevor das Problem behoben werden muss.   Obwohl das Patchfenster vom ISV definiert wird, muss das Fenster innerhalb eines angemessenen Zeitrahmens sein. Beispielsweise wären drei Monate zum Patchen einer kritischen Sicherheitslücke nicht sinnvoll und daher innerhalb Ihrer Microsoft 365-Zertifizierungsbewertung abgelehnt.|
||&#x2713; Richtlinien und Verfahren, die die Art  und Weise  des Patchens beschreiben, müssen vorhanden sein und alle anwendbaren Betriebssysteme, Anwendungen und Softwarekomponenten enthalten, die in der Umgebung verwendet werden. Dies umfasst alle Webabhängigkeiten, die in der App/dem Add-In verwendet werden.|
||&#x2713; software components and operating systems not longer supported by the vendor **MUST** not be used within the environment. Unterstützende Richtlinien **MÜSSEN** verfügbar sein, um sicherzustellen, dass nicht unterstützte Softwarekomponenten/Betriebssysteme aus der Umgebung entfernt werden, und es muss ein Prozess zur Ermittlung des Ablaufs von Softwarekomponenten ausgeführt werden.|
|**Überprüfung von Sicherheitslücken**|Die Überprüfung von Sicherheitslücken muss Folgendes umfassen:|
||&#x2713; vierteljährliche Überprüfung externer Sicherheitslücken,  die auf den vollständigen öffentlichen Fußabdruck der umgebungsintegellen Umgebung (URLs UND IP-Adressen für die Infrastruktur- und Webanwendungsprüfung) durchgeführt wird.|
||&#x2713; vierteljährlich authentifizierte interne Sicherheitsrisikoprüfung, die für systeminterne Komponenten (nicht für PaaS) durchgeführt wird.|
||&#x2713; Eine dokumentierte Richtlinie zur Behebung  von Sicherheitsrisiken muss eingerichtet sein, um sicherzustellen, dass Systemkomponenten frei von bekannten Sicherheitsrisiken sind, indem Sie die Zeitachse zur Behebung von Sicherheitsrisiken basierend auf Ihren definierten CVSS **Recommended Risk Ranking Scores**(siehe oben) detailliert beschreiben.|
||&#x2713; fortlaufende Überprüfungen **müssen** durchgeführt werden, bis identifizierte Sicherheitsrisiken mit Risikorang innerhalb der erforderlichen Zeitachse gemäß der Bereinigungsrichtlinie des ISV behoben werden. Obwohl der Zeitplan für die Korrektur durch den ISV definiert wird, muss das Fenster innerhalb eines angemessenen Zeitrahmens sein. Beispielsweise wären drei Monate zur Behebung einer kritischen Sicherheitslücke nicht sinnvoll und daher innerhalb Ihrer Microsoft 365-Zertifizierungsbewertung abgelehnt.|
|**Firewalls**|In Ihrer unterstützenden Infrastruktur wird erwartet, dass eine Firewall (oder eine entsprechende Firewall, in der Clouddienste genutzt werden) wie folgt konfiguriert ist:|
||&#x2713; **muss** auf allen Internetverbindungen installiert sein, die die Umgebungen in einem Bereich verfügbar machen.|
||&#x2713; **muss** zwischen allen DMZs (Demilitarized Zones) und allen vertrauenswürdigen Netzwerken installiert werden.|
||&#x2713; Der öffentliche Zugriff **muss** in einer DMZ (Demilitarized Zone) beendet werden. |
||&#x2713; Administrative Standardanmeldeinformationen **müssen** vor der Installation in Produktionsumgebungen geändert werden.|
||&#x2713; Der datenverkehr, der über Bereichsfirewalls (in beide **Richtungen)** zulässig ist, MUSS einen Genehmigungsprozess durchgehen, und alle Protokolle, Dienste und Ports müssen mit geschäftlichen Begründungen dokumentiert werden.|
||&#x2713; Firewallregeln müssen in-line mit den dokumentierten zulässigen Regeln konfiguriert werden.|
||&#x2713; starke Kryptografie muss im Einklang mit  **Anhang B** auf allen administrativen Firewallschnittstellen aktiviert sein, die keine Konsolenschnittstellen sind.|
||&#x2713; Multi-Factor Authentication (MFA) **MUSS** für den Administratorzugriff der Firewall aktiviert sein.|
||&#x2713; **Firewallüberprüfungen MÜSSEN** mindestens alle sechs Monate durchgeführt werden.|
||Durch die Zertifizierungsanalyse wird die Firewallregelnbasis für das Vorhandensein von Datenverkehrsflüssen an potenzielle Dritte überprüft, um die externe Datenfreigabe von Drittanbietern zu überprüfen.  |
||**Web Application Firewall (WAF)**. Wenn eine WAF oder eine gleichwertige Maßnahme zum Schutz vor Webanwendungsbedrohungen und -sicherheitsrisiken bereitgestellt wird, wird eine zusätzliche Gutschrift bereitgestellt. Wenn vorhanden, sollten unterstützende Richtlinien und **Verfahren** zusammen mit den folgenden WAF-Konfigurationen vorhanden sein: |
||&#x2713; WAF sollte im aktiven Abwehrmodus (automatisches Blockieren identifizierter Angriffe) oder im Überwachungsmodus (aktive Überwachung/Untersuchung von Warnungen) ausgeführt werden.|
||&#x2713; WAF für die Unterstützung [](#ssl) des SSL-Offloadings konfiguriert.|
||&#x2713; WAF sollte entsprechend dem [OWASP-Kernregelsatz](#owasp) ****   (3.0 oder 3.1) konfiguriert werden, um vor den meisten der folgenden Bedingungen zu schützen:|
||&emsp;&#x25fc; Protokoll- und Codierungsprobleme.|
||&emsp;&#x25fc; Kopfzeileneinspritzung, Anforderungsschmuggler und Reaktionsteilung.|
||&emsp;&#x25fc; Datei- und Pfad-Traversalangriffe.|
||&emsp;&#x25fc; Remote file inclusion (RFI)-Angriffe.|
||&emsp;&#x25fc; Remotecodeausführungsangriffe.|
||&emsp;&#x25fc; PHP-Injection-Angriffe.|
||&emsp;&#x25fc; websiteübergreifende Skriptangriffe.|
||&emsp;&#x25fc; SQL-Injection-Angriffe.|
||&emsp;&#x25fc; Session-Fixation-Angriffe.|
|**Änderungssteuerung**|Richtlinien und Verfahren zur Änderungssteuerung **müssen** eingeführt werden, um sicherzustellen, dass Änderungen auf eine Weise implementiert werden, die auf die Aufrechterhaltung der Sicherheit, Stabilität und Integrität der Umgebung ausgerichtet ist. Die folgenden Änderungssteuerungskriterien **sind** erforderlich:|
||&#x2713; Aufgabentrennung– Entwicklungs- und **Testumgebungen MÜSSEN** von den Produktionsumgebungen getrennt sein.|
||&#x2713; Vertrauliche Daten aus **Produktionsumgebungen dürfen** nicht in Entwicklungs-/Testumgebungen verwendet werden.|
||&#x2713; Alle Änderungen MÜSSEN in einer Test-/Entwicklungsumgebung getestet werden, bevor sie in die Produktionsumgebung eingeführt werden.|
||&#x2713; Änderungsanforderungen **WERDEN vor**  dem Produktionswechsel ausgelöst und autorisiert.|
||&#x2713; Änderungsanforderungen müssen mindestens **Folgendes** umfassen:|
||&emsp;&#x25fc; Dokumentation der Auswirkungen.|
||&emsp;&#x25fc; dokumentierte Back-Out-Verfahren.|
||&#x2713; **Änderungsanforderungen MÜSSEN** als abgeschlossen gekennzeichnet werden, **nur** nachdem erfolgreiche Funktionstests durchgeführt wurden.|
|**Entwicklung/Bereitstellung sicherer Software**|Sicherheit muss im Vordergrund der Softwareentwicklungspraktiken stehen, um das Risiko der Einführung von Codierungsrisiken in die App/das Add-In zu minimieren, wodurch eine sichere Umgebung erhalten und Daten geschützt werden. Die folgenden sicheren Methoden für die **Softwareentwicklung müssen** verwendet werden: |
||&#x2713; Sie müssen über einen etablierten und dokumentierten Softwareentwicklungsprozess verfügen, der den gesamten Softwareentwicklungslebenszyklus deckt.|
||&#x2713; Alle Codeänderungen MÜSSEN einen Überprüfungs- und Autorisierungsprozess durch eine andere Person als den ursprünglichen Entwickler durchgehen.|
||&#x2713; Sichere Codierungsmethoden und Überprüfungstechniken **MÜSSEN** die [Sicherheitsrisikoklassen OWASP Top 10](https://owasp.org/www-project-top-ten) oder [SANS Top 25 CWE](https://www.sans.org/top25-software-errors) adressieren.|
||&#x2713; Entwickler müssen **sich mindestens** jährlich einer sicheren Softwarecodierungsschulung unterziehen.|
||&#x2713; **Coderepositorys MÜSSEN** durch MFA gesichert werden.|
||&#x2713; angemessene Zugriffskontrollen **müssen** zum Schutz von Coderepositorys vor änderungen an bösartigem Code bereitgestellt werden.|
||**Hinweis**: Microsoft hat den [Security Development Lifecycle](https://www.microsoft.com/en-us/securityengineering/sdl/) (SDL) veröffentlicht, den Microsoft folgt, um Sicherheitssicherheits- und Complianceanforderungen in seinen Produkten zu unterstützen. Sdl hilft Entwicklern, sicherere Software zu erstellen, indem sie die Anzahl und den Schweregrad von Sicherheitsrisiken in Software reduziert und gleichzeitig die Entwicklungskosten reduziert.|
|**Kontoverwaltung**| Die Verwaltung des Systemkomponentenkontos sowie unterstützende Richtlinien und **Verfahren** müssen folgende Anforderungen erfüllen: |
||&#x2713; Standardanmeldeinformationen (Anbieter oder ISV) **werden** entweder deaktiviert oder für alle Systemkomponenten im Bereich entfernt.|
||&#x2713; Kontoerstellung, -änderung und -löschung **MUSS** einen etablierten Genehmigungsprozess durchgehen.|
||&#x2713; Konten, die seit über 3 Monaten  nicht verwendet wurden, deaktiviert oder gelöscht werden müssen, muss ISV daher über einen Mechanismus verfügen, um dies zu erreichen.|
||&#x2713;Richtlinien für starke Kennwörter oder andere geeignete Gegenmaßnahmen **müssen** zum Schutz von Benutzeranmeldeinformationen konfiguriert werden. Die folgende Kennwortrichtlinie sollte als Richtlinie verwendet werden:|
||&emsp;&#x25fc; Minimale Kennwortlänge von acht Zeichen|
||&emsp;&#x25fc; Kontosperrungsschwellenwert von nicht mehr als 10 Versuchen|
||&emsp;&#x25fc; Kennwortverlauf von mindestens fünf Kennwörtern|
||&emsp;&#x25fc; Durchsetzung der Verwendung von starken Kennwörtern|
||&#x2713; für jeden Benutzer müssen eindeutige Benutzerkonten ausgestellt werden. es sind keine freigegebenen Konten zu verwenden.|
||&#x2713; Prinzipien der geringsten Rechte **müssen** für alle Benutzer gelten, sollte der dafür verwendete Mechanismus dokumentiert werden (d. h. die Verwendung von Gruppen). |
||&#x2713; Geeignete Dienstkontosentwennung muss dokumentiert und ausgeführt werden, z. B. interaktive Anmeldung deaktiviert, Anmeldungen auf bestimmte Hosts beschränkt usw.  |
||&#x2713; Remotezugriffslösungen **MÜSSEN :** |
||&emsp;&#x25fc; MFA (Multi Factor Authentication) verwenden|
||&emsp;&#x25fc; daten im Übertragungsschutzprofil verwenden, das das Konfigurationsprofil für die Daten während der Übertragung erfüllt oder überschreitet, wie in Anhang A beschrieben|
||&#x2713; Wenn sich die Verwaltung von öffentlichem DNS außerhalb der Bereichsumgebung befindet, müssen alle Benutzerkonten, die DNS-Änderungen vorgenommen haben, für die Verwendung von MFA konfiguriert sein.|
||**Hinweis:** Cloudverwaltungsportale müssen auch die geltenden Kontoverwaltungsanforderungen erfüllen, weitere Informationen finden Sie in Anhang F.|
|**Intrusion Detection and Prevention (OPTIONAL)**| Zusätzliches Guthaben wird erhalten, wenn IDPS (Intrusion Detection and Prevention System) am Umkreis der in-Scope-unterstützenden Umgebungen verwendet wird.  Zu den folgenden empfohlenen Steuerelementen gehören: |
||&#x2713; IDPS sollten am Umkreis der unterstützenden Umgebung bereitgestellt werden |
||&#x2713; IDPS-Signaturen sollten innerhalb des letzten Tages auf dem aktuellen Stand gehalten werden. |
||&#x2713; IDPS sollte für die TLS-Überprüfung konfiguriert werden |
||&#x2713; IDPS SOLLTE für den gesamten eingehenden und ausgehenden Datenverkehr konfiguriert werden |
||&#x2713; IDPS sollte für die Warnung konfiguriert werden |
|**Ereignisprotokollierung** |Die **Protokollierungsabdeckung MUSS** **ALLE Systemkomponenten** und Anwendungen umfassen, einschließlich Schadsoftwareschutzmechanismen. Die folgenden Ereignisse **MÜSSEN** protokolliert werden:|
||&emsp;&#x25fc; Benutzerzugriff auf Systemkomponenten und die Anwendung|
||&emsp;&#x25fc; Alle Von einem Benutzer mit hohen Berechtigungen ausgeführten Aktionen|
||&emsp;&#x25fc; Ungültige logische Zugriffsversuche|
||&emsp;&#x25fc; Erstellen/Ändern eines privilegierten Kontos|
||&emsp;&#x25fc; Manipulation von Ereignisprotokollen|
||&emsp;&#x25fc; Deaktivieren von Sicherheitstools; z. B. An-Malware- oder Ereignisprotokollierung|
||&emsp;&#x25fc; Anti-Malware-Protokollierung; z. B. Updates, Schadsoftwareerkennung, Scanfehler|
||&emsp;&#x25fc; IDPS/WAF-Ereignisse (sofern konfiguriert)|
||**Ereignisprotokolle MÜSSEN** die folgenden Informationen enthalten:|
||&emsp;&#x25fc; Benutzeridentifikation |
||&emsp;&#x25fc; Typ des Ereignisses |
||&emsp;&#x25fc; Datum und Uhrzeit |
||&emsp;&#x25fc; Erfolgs-/Fehlerindikator|
||&emsp;&#x25fc; Bezeichnung, um das betroffene System zu identifizieren |
||Die Zeitsynchronisierung **muss** für alle systemtechnischen Komponenten verwendet werden, um forensische Untersuchungen zu helfen.|
||Die Zeitsynchronisierung **MUSS** so konfiguriert sein, dass dieselbe primäre (und bei Bedarf sekundäre) Zeitquelle verwendet wird|
||Öffentlich zugängliche Systeme (Systeme innerhalb der DMZ) **MÜSSEN** Protokolle in ein internes zentrales Protokollierungsrepository schreiben. Das zentrale Protokollierungsrepository darf sich nicht innerhalb der DMZ befinden.|
||**Überwachungsprotokolle MÜSSEN** gesichert werden, um sicherzustellen, dass Protokolldaten von einem Bedrohungsakteur nicht geändert werden können. Der Zugriff auf das zentrale Protokollierungsrepository darf nur auf autorisiertes Personal beschränkt sein.|
||Protokolle **MÜSSEN** 30 Tage lang sofort verfügbar sein. **Protokollierungsdaten müssen** mindestens 90 Tage lang aufbewahrt werden.|
|**Überprüfen** |Überprüfungsprozesse sowie unterstützende Richtlinien und Verfahren **MÜSSEN** folgendes erfüllen:|
||&#x2713; Sie tägliche Protokollüberprüfungen durch, oder verwenden Sie automatisierte Protokollanalyse- und Warnungstechnologie, um Ereignisse aus allen Systemkomponenten im Bereich zu überprüfen, um potenzielle Sicherheitsereignisse zu identifizieren.|
||&#x2713; Potenzielle Sicherheitsereignisse **müssen** sofort nachgegangen werden.|
|**Warnung** |Warnungsprozesse sowie unterstützende Richtlinien und Verfahren **MÜSSEN** folgendes erfüllen: |
||&#x2713; Protokollierte Sicherheitsereignisse, die ein Risiko für die Sicherheit Ihrer Systeme, Vorgänge oder Daten darstellen, MÜSSEN eine sofortige Warnung auslösen, z. B. (keine vollständige Liste):|
||&emsp;&#x25fc; Erstellen/Ändern von Berechtigungskontos|
||&emsp;&#x25fc; Schadsoftwareereignisse|
||&emsp;&#x25fc; Deaktivieren von Sicherheitstools|
||&emsp;&#x25fc; Manipulation von Ereignisprotokollen|
||&emsp;&#x25fc; IDPS/WAF-Ereignisse (sofern konfiguriert) |
||&#x2713; Mitarbeiter müssen immer (24/7) verfügbar sein, um auf ausgelöste Warnungen zu reagieren.|
|**Risikomanagement**|Es muss eine Risikobewertungsmethode entwickelt und durchgeführt werden, die Folgendes umfasst:|
||&#x2713; Ein formal definierter Prozess.|
||&#x2713; mindestens jährlich durchgeführt.|
||&#x2713; Umfasst alle Ressourcen innerhalb der Umgebung in einem Bereich.|
||&#x2713; Identifiziert Bedrohungen und Sicherheitsrisiken für alle enthaltenen Ressourcen.|
||&#x2713; Umfasst die Verwendung von definierten Auswirkungs- und Wahrscheinlichkeitsmatrizen.|
||&#x2713; Führt zur Erstellung eines Risikoregisters und eines entsprechenden Risikobehandlungsplans.|
|**Reaktion auf Sicherheitsvorfälle**|Ein gründlicher Plan zur Reaktion auf Vorfälle **ist erforderlich** und **muss** mindestens Folgendes umfassen:|
||&#x2713; Mindestens die Abdeckung der in-Scope-Systemkomponenten und -anwendungen.|
||&#x2713; Spezifische Verfahren zur Reaktion auf Vorfälle für erwartete Bedrohungsmodelle.|
||&#x2713; dokumentierten Kommunikationsprozess, um sicherzustellen, dass alle wichtigen Beteiligten und alle relevanten externen Stellen, wie z. B., rechtzeitig benachrichtigt werden; Zahlungsmarken/-erwerber, Aufsichtsbehörden und Aufsichtsbehörden ([DSGVO](#gdpr)) im Einklang mit den vorgeschriebenen Berichtspflichten.|
||&#x2713; Die Reaktion auf Vorfälle wird basierend auf den erkenntnissen, organisatorischen Änderungen und branchenbezogenen Entwicklungen aktualisiert.|
||&#x2713; jährliche Schulung für Mitglieder des Vorfallreaktionsteams.|

## <a name="data-handling-security-and-privacy"></a>Datenverarbeitungssicherheit und Datenschutz

Daten, die zwischen dem Anwendungsbenutzer, den Zwischendiensten und den Systemen von ISV übertragen werden, müssen durch Verschlüsselung über eine TLS-Verbindung geschützt werden, die mindestens TLS v1.1 unterstützt. *Siehe* [**Anhang A**](#appendix-a).

Wo Ihre Anwendung M365-Daten abruft und speichert, müssen Sie ein Datenspeicherverschlüsselungsschema implementieren, das der Spezifikation gemäß [**Anhang B folgt.**](#appendix-a)

### <a name="test-specification"></a>Testspezifikation

|Testen | Steuerelemente |
| -----------------------|-------------------------------- |
|**Daten im Transit**| Bei der Übertragung vertraulicher Daten muss mindestens TLS 1.1 verwendet werden, mit einigen ausnahmen, die in Anhang A beschrieben sind.|
||Die Übertragung vertraulicher **Daten muss** entsprechend den in Anhang B beschriebenen Verschlüsselungsprofilen entsprechend verschlüsselt werden.|
||Die TLS-Komprimierung muss deaktiviert sein.|
||HSTS (HTTP Strict Transport Security) **MUSS** so konfiguriert sein, dass >= 15552000|
|**Daten im Ruhen**| Die Speicherung vertraulicher **Daten muss** in Einklang mit den in Anhang B beschriebenen Verschlüsselungsprofilen geschützt werden, die mindestanforderungen an Verschlüsselung, Algorithmen, Schlüsselgrößen, Hashing und Nachrichtenauthentifizierung abdecken.|
||Alle gespeicherten Datentypen MÜSSEN dokumentiert werden.|
|**Datenaufbewahrung und -entsorgung**|Die Speicherung vertraulicher **Daten muss** auf ein Minimum beschränkt werden, indem Richtlinien für die Aufbewahrung und Entsorgung von Daten, Verfahren und Prozesse umgesetzt werden, die mindestens Folgendes umfassen:|
||&#x2713; Speichermenge und Aufbewahrungszeit auf die Für rechtliche, behördliche und/oder geschäftliche Anforderungen erforderliche Menge dokumentieren und begrenzen.|
||&#x2713; Dokumentieren und Bereitstellen von Prozessen zum sicheren Löschen vertraulicher Daten, wenn sie nicht mehr benötigt werden, in Einklang mit dokumentierten Richtlinien.|
||&#x2713; Sie einen vierteljährlichen Prozess zum Identifizieren und sicheren Löschen gespeicherter vertraulicher Daten, die den definierten Aufbewahrungszeitraum überschreitet, dokumentieren und bereitstellen.|
|**Datenzugriffsverwaltung**|Das Einschränken des Datenzugriffs auf Personen mit einem berechtigten Geschäftsgrund hilft Organisationen, eine falsche Verarbeitung vertraulicher Daten durch Unerfahrenheit oder Bosheit zu verhindern. Vertrauliche Daten, die von der App/dem Add-In empfangen werden, und der Zugriff auf Verschlüsselungsschlüssel erfordern eine dokumentierte Genehmigung (elektronisch oder schriftlich) für autorisierte Parteien auf allen Zugriffsebenen für den Zugriff und müssen eine Liste der genehmigten und überprüften Berechtigungen enthalten, die die Richtlinie demonstrieren, enthält die angegebenen Anforderungen wie folgt: |
||&#x2713; Definieren von Zugriffsanforderungen und Berechtigungszuweisungen nur für Rollen, die einen solchen privilegierten Zugriff erfordern. |
||&#x2713; Einschränken des Zugriffs auf die geringsten Berechtigungen, die zum Ausführen von Aufgaben erforderlich sind.|
||&#x2713; Sicherstellen, dass Vereinbarungen zur Datenfreigabe mit allen Drittanbietern getroffen werden, die M365-Daten verwenden.|
|**DSGVO**| Im Rahmen des Microsoft 365-Zertifizierungsprozesses müssen Sie die Einhaltung der DSGVO nachweisen, indem Sie:|
||&#x2713; Bereitstellung einer unabhängigen Überprüfung der DSGVO-Konformität durch ein erfahrenes externes Auditunternehmen. Sie müssen den Bericht zur Überprüfung übermitteln oder dem Analysten das Anzeigen des Berichts erlauben. Der Bericht sollte genügend Details enthalten, um nicht nur die Bewertung des externen Prüfers zu überprüfen, sondern auch genügend Vertrauen bieten, dass die externe Überprüfung die Konformität mit der DSGVO bestätigt hat.|
||oder|
||&#x2713; Übermitteln weiterer Nachweise, um Zusätzliche Sicherheit für Ihre Verpflichtung zu Datenschutzgesetzen zu bieten, wie folgt:|
||&#x25fc; Ein dokumentierter Antrag auf Zugriffsanforderung (Subject Access Request, SAR) zur Erfüllung der Anforderungen von Kunden und zur Erfüllung der 30-Tage-Anforderung der DSGVO. Es wird empfohlen, geeignete Tools für die Datenermittlung zu verwenden, um sicherzustellen, dass ein SAR innerhalb dieser Zeitrahmen erfüllt wird. **Hinweis:** Wenn diese Tools nicht verwendet werden, müssen Sie die Funktionsweise dieser Tools demonstrieren und demonstrieren, wie die Prozesse die Ermittlung aller Informationen der person gewährleisten können.|
||&#x25fc;Datenschutzhinweise müssen auf der Website vorhanden sein und die folgenden Informationen enthalten:
||
||Wenn kein unabhängiger DSGVO-Bericht verfügbar ist, muss Folgendes vorhanden sein, um im Rahmen der M365-Zertifizierungsbewertung überprüft zu werden: |
||&#x2713; Ein dokumentierter Antrag auf Zugriffsanforderung (Subject Access Request, SAR) zur Erfüllung der Anforderungen von Kunden und zur Erfüllung der 30-Tage-Anforderung der DSGVO.  Es wird empfohlen, geeignete Tools für die Datenermittlung zu verwenden, um sicherzustellen, dass ein SAR innerhalb dieser Zeitrahmen erfüllt wird. Wenn diese Tools nicht verwendet werden, müssen Sie die Funktionsweise dieser Tools demonstrieren und demonstrieren, wie die Prozesse die Ermittlung aller Informationen der person sicherstellen können.|
||&#x2713; Datenschutzhinweise müssen auf der Website vorhanden sein und die folgenden Informationen enthalten:|
||&emsp;&emsp;&#x25a1; Die Kontaktdaten von Organisationen.|
||&emsp;&emsp;&#x25a1; Art der verarbeiteten personenbezogenen Daten.|
||&emsp;&emsp;&#x25a1; Rechtlichkeit der Verarbeitung personenbezogener Daten (*Artikel 6*).|
||&emsp;&emsp;&#x25a1; details of data subject's rights:|
||&emsp;&emsp;&#x25a1; Recht, informiert zu werden (*Artikel 13 und 14*).
||&emsp;&emsp;&#x25a1; zugriffsrecht der person person (*Artikel 15*).|
||&emsp;&emsp;&#x25a1; Recht auf Berichtigung (*Artikel 16*).|
||&emsp;&emsp;&#x25a1; Recht auf Löschung (*Artikel 17*).|
||&emsp;&emsp;&#x25a1; Recht auf Einschränkung der Verarbeitung (*Artikel 18*).|
||&emsp;&emsp;&#x25a1; Recht auf Datenportabilität (*Artikel 20*).|
||&emsp;&emsp;&#x25a1; Objektrecht (*Artikel 21*).|
||&emsp;&emsp;&#x25a1; Rechte im Zusammenhang mit automatisierter Entscheidungsmarkierung, einschließlich Profilerstellung (*Artikel 22*).|
||&#x2713; Für die Freigabe von Informationen an Dritte müssen Vereinbarungen getroffen werden, um sicherzustellen, dass die Verarbeitung der Daten der betroffenen Person den Datenschutzgesetzen unterliegt.|

## <a name="optional-external-compliance-frameworks-review"></a>Optionale Überprüfung externer Complianceframeworks

Wenn externe Sicherheitsframeworks im Publisher Attestation enthalten sind, müssen Zertifizierungsanalysten die Gültigkeit dieser Sicherheits-Compliance-Frameworks im Rahmen der Microsoft 365-Zertifizierungsbewertung überprüfen.
Zu den Nachweisen für die folgenden unterstützten externen Sicherheits-Compliance-Frameworks gehören:

* [ISMS](#isms) /  [IEC](#iec) – IS0/IEC 27001-Spezifikation</h5>
* [PCI DSS](#pci-dss)
* [SOC 2](#soc-2)

Die im Abschnitt [Compliance Evidence](#compliance-evidence) identifizierte Dokumentation wird zur Durchführung dieser Überprüfung verwendet.

### <a name="test-specifications"></a>Testspezifikationen

&#x2713; Die unterstützende App/Add-In-Umgebung UND  alle unterstützenden Geschäftsprozesse MÜSSEN in den Bereich aller unterstützten externen Sicherheits-Compliance-Frameworks einbezogen werden und müssen in der bereitgestellten Dokumentation klar angegeben werden. 

&#x2713; Unterstützte **Frameworks** für externe Sicherheitskonformität müssen aktuell sein, d. h. innerhalb der letzten 12 Monate (oder innerhalb von 15 Monaten, wenn die erneute Bewertung derzeit durchgeführt wird und Nachweise bereitgestellt werden können).

&#x2713; Unterstützten externen Sicherheits-Compliance-Frameworks **MUSS** von einem unabhängigen akkreditierten Unternehmen durchgeführt werden.

## <a name="appendix-a"></a>Anhang A

### <a name="tls-profile-configuration-requirements"></a>TLS-Profilkonfigurationsanforderungen

Der netzwerkbasierte Datenverkehr muss mindestens mit TLS v1.1 (empfohlen wird TLS v1.2+ empfohlen) oder einem anderen anwendbaren Protokoll geschützt werden, ob innerhalb eines virtuellen Netzwerks, eines Clouddiensts oder eines Rechenzentrums. Ausnahmen von dieser Anforderung sind:

* **HTTP-zu-HTTPS-Umleitung**. Ihre App kann über HTTP antworten, um Clients zu HTTPS umzuleiten, die Antwort darf jedoch keine vertraulichen Daten (Cookies, Kopfzeilen, Inhalte) enthalten. Es sind keine anderen HTTP-Antworten zulässig als Umleitungen zu HTTPS und Antworten auf Integritätsteste. Siehe unten.
* **Integritätstest .** Ihre App kann nur dann auf Integritätsüberprüfungen über **HTTP** reagieren, wenn HTTPS-Integritätsüberprüfungen von der prüfenden Seite nicht unterstützt werden.
* **Zertifikatzugriff**. Der Zugriff auf CRL-, OCSP- und AIA-Endpunkte zum Zweck der Zertifikatüberprüfung und Sperrüberprüfung ist über HTTP zulässig.
* **Lokale Kommunikation**. Ihre App kann HTTP (oder andere nicht geschützte Protokolle) für Kommunikationen verwenden, die das Betriebssystem nicht verlassen, z. B. g. Herstellen einer Verbindung mit einem Webserverendpunkt, der auf localhost verfügbar gemacht wird.

Die **TLS-Komprimierung muss** deaktiviert sein.

## <a name="appendix-b"></a>Anhang B

### <a name="encryption-profile-configuration-requirements"></a>Anforderungen an die Konfiguration von Verschlüsselungsprofilen

Es sind nur kryptografische Grundtypen und Parameter wie folgt zulässig:

### <a name="symmetric-cryptography"></a>Symmetrische Kryptografie

**Verschlüsselung**

&emsp;&#x2713; AES, BitLocker, Blowfish oder TDES sind zulässig. Alle unterstützten Schlüssellängen >=128 sind zulässig (128, 192 und 256 Bit) und können verwendet werden (256-Bit-Tasten werden empfohlen).

&emsp;&#x2713; nur der #A0 ist zulässig. Jeder Verschlüsselungsvorgang muss einen neuen, zufällig generierten Initialisierungsvektor (IV) verwenden.

&emsp;&#x2713; Verwendung von Datenstromchiffren, z. B. RC4, **IST NICHT** zulässig.

**Hashfunktionen**

&emsp;&#x2713; Alle neuen Codes müssen SHA-256, SHA-384 oder SHA-512 (zusammen sha-2 genannt) verwenden. Die Ausgabe kann auf nicht weniger als 128 Bit gekürzt werden.

&emsp;&#x2713; SHA-1 darf nur aus Kompatibilitätsgründen verwendet werden.

&emsp;&#x2713; Verwendung von MD5, MD4, MD2 und anderen Hashfunktionen IST NICHT zulässig, auch nicht für nicht kryptografische Anwendungen.

**Nachrichtenauthentifizierung**

&emsp;&#x2713; Für den neuen Code muss HMAC mit einer der genehmigten Hashfunktionen verwendet werden. Die Ausgabe von HMAC kann auf nicht weniger als 128 Bit gekürzt werden.

&emsp;&#x2713; HMAC-SHA1 darf nur aus Kompatibilitätsgründen verwendet werden.

&emsp;&#x2713; HMAC-Taste muss mindestens 128 Bit lang sein. 256-Bit-Tasten werden empfohlen.

### <a name="asymmetric-algorithms"></a>Asymmetrische Algorithmen

**Verschlüsselung**

&emsp;&#x2713; RSA ist zulässig. Der **Schlüssel muss** mindestens 2048 Bit lang sein, und der OAEP-Abstand muss verwendet werden. Die Verwendung von #A0 ist nur aus Kompatibilitätsgründen zulässig.

**Signatures**

&emsp;&#x2713; RSA ist zulässig. Der **Schlüssel muss** mindestens 2048 Bit lang sein, und der PSS-Abstand muss verwendet werden. Die Verwendung von #A0 ist nur aus Kompatibilitätsgründen zulässig.

&emsp;&#x2713;ECDSA ist zulässig. Der **Schlüssel muss** mindestens 256 Bit lang sein. NIST P-256, P-384 oder P-521-Kurve muss verwendet werden.

**Schlüsselaustausch**

&emsp;&#x2713; ECDH ist zulässig. Der **Schlüssel muss** mindestens 256 Bit lang sein. NIST P-256, P-384 oder P-521-Kurve muss verwendet werden.

&emsp;&#x2713; ECDH ist zulässig. Der **Schlüssel muss** mindestens 256 Bit lang sein. NIST P-256, P-384 oder P-521-Kurve muss verwendet werden.

## <a name="appendix-c"></a>Anhang C

### <a name="evidence-collection--delta-for-iso-27001"></a>Evidence Collection – Delta für ISO 27001

Wo Sie bereits die ISO27001-Compliance erreicht haben, müssen die folgenden Deltas (Lücken), die nicht vollständig von ISO 27001 abgedeckt sind, mindestens im Rahmen dieser Microsoft 365-Zertifizierung überprüft werden.

> [!NOTE]
> Im Rahmen Ihrer Microsoft 365-Zertifizierungsbewertung ermittelt der Zertifizierungsanalyst, ob eines der zugeordneten ISO 27001-Steuerelemente nicht bestandteil der ISO 27001-Bewertung war, und entscheidet möglicherweise auch, Stichprobensteuerelemente zu verwenden, die als eingeschlossen wurden, um weitere Sicherheit zu bieten. Alle Anforderungen, die in iso 27001 fehlen, müssen in Ihre Microsoft 365-Zertifizierungsbewertungsaktivitäten einbezogen werden.

**Schadsoftwareschutz – Virenschutz**

Wenn der Schadsoftwareschutz mithilfe der Anwendungssteuerung besteht und innerhalb des ISO 27001-Berichts bestätigt wird, ist keine weitere Untersuchung erforderlich. Wenn keine Anwendungssteuerung besteht, müssen Zertifizierungsanalysten Nachweise von Anwendungskontrollesmechanismen identifizieren und bewerten, um die Detonation von Schadsoftware in der Umgebung zu verhindern. Dazu müssen Sie:

* Zeigen Sie, dass Antivirensoftware für alle Systemkomponenten ausgeführt wird.

* Zeigen Sie, dass Der Virenschutz für alle Systemkomponenten konfiguriert ist, um Schadsoftware automatisch zu blockieren, & warnung zu isolieren oder zu warnen.

* Antivirensoftware **MUSS** so konfiguriert sein, dass alle Aktivitäten protokolliert werden.

**Patchverwaltung – Patching**

Da iso 27001-Prüfungen diese Kategorie nicht speziell bewerten, müssen Sie dazu:

* Softwarekomponenten und Betriebssysteme, die vom Hersteller nicht mehr unterstützt **werden, dürfen** nicht innerhalb der Umgebung verwendet werden. Unterstützende Richtlinien MÜSSEN verfügbar sein, um sicherzustellen, dass nicht unterstützte Softwarekomponenten/Betriebssysteme aus der Umgebung entfernt werden, und es muss ein Prozess zum Ermitteln des Ablaufs von Softwarekomponenten sein.

**Prüfung auf Schwachstellen**  

Da iso 27001-Prüfungen diese Kategorie nicht speziell bewerten, müssen Sie dazu:

* Zeigen Sie, dass vierteljährliche interne und externe Sicherheitsrisikoprüfungen durchgeführt werden.

* Bestätigen Sie, dass für die Behebung von Sicherheitsrisiken basierend auf der Risikorangfolge und gemäß der Spezifikation wie folgt unterstützende Dokumentation zur Behebung von Sicherheitsrisiken vor ort ist:
 
 &#x2713; Behebung aller kritischen und hohen Risikoprobleme in der Risikorangfolge für interne Überprüfungen.
 
 &#x2713; Behebung aller kritischen, hohen und mittleren Risikoprobleme in der Risikorangfolge für externe Überprüfungen.
 
 &#x2713; Sie, dass die Behebung in Einklang mit der dokumentierten Richtlinie zur Behebung von Sicherheitslücken durchgeführt wird.

**Firewall – Firewalls (oder gleichwertige Technologien)**

Da iso 27001-Prüfungen diese Kategorie nicht speziell bewerten, müssen Sie dazu:

* Zeigen Sie, dass Firewalls an der Grenze der umgebungsin-scope installiert sind.

* Demonstrieren, dass Firewalls zwischen der DMZ und vertrauenswürdigen Netzwerken installiert sind.

*   Zeigen Sie, dass der öffentliche Zugriff in der DMZ beendet wird.

*   Zeigen Sie, dass vor der Installation in der Liveumgebung standardmäßige Administratoranmeldeinformationen geändert werden.

*   Zeigen Sie, dass der gesamte zugelassene Datenverkehr über die Firewall einen Autorisierungsprozess durchgeht, der zur Dokumentation des datenverkehrs mit einer geschäftlichen Begründung führt.

*   Zeigen Sie, dass alle Firewalls so konfiguriert sind, dass Datenverkehr nicht explizit definiert wird.

*   Demonstrieren Sie, dass Firewalls nur starke Kryptografie auf allen administrativen Schnittstellen unterstützen, die keine Konsolen sind.

*   Zeigen Sie, dass die für das Internet verfügbar gemachten verwaltungstechnischen Schnittstellen der Firewall MFA unterstützen.

*   Nachweisen, dass Firewallregelüberprüfungen mindestens alle 6 Monate durchgeführt werden

**Firewall – Webanwendungsfirewalls (WAF)**  

Zusätzliche Guthaben werden bereitgestellt, wenn ein WAF bereitgestellt wird, um sich vor der Vielzahl von Webanwendungsbedrohungen und Sicherheitsrisiken zu schützen, denen die Anwendung ausgesetzt werden kann. Wenn ein WAF oder ähnliches vorhanden ist, müssen Sie:

* Zeigen Sie, dass der WAF im aktiven Abwehrmodus konfiguriert ist, oder überwachen Sie mehr mit Benachrichtigungen.

* Demonstrieren, dass der WAF für die Unterstützung der SSL-Offloading konfiguriert ist.

* Wird entsprechend dem OWASP-Kernregelsatz (3.0 oder 3.1) konfiguriert, um vor den meisten der folgenden Angriffstypen zu schützen:

&#x2713; Protokoll- und Codierungsprobleme.

&#x2713; Kopfzeileneinspritzung, Anforderungsschmuggler und Reaktionssplitting.

&#x2713; Datei- und Pfad-Traversalangriffe.

&#x2713; Remote file inclusion (RFI)-Angriffe.

&#x2713; Remotecodeausführungsangriffe.

&#x2713; PHP-Injection-Angriffe.

&#x2713; websiteübergreifende Skriptangriffe.

&#x2713; SQL-Injection-Angriffe.

&#x2713; Session-Fixation-Angriffe.

**Änderungssteuerung**

Da iso 27001-Prüfungen einige Elemente von Änderungsanforderungsprozessen nicht speziell bewerten, müssen Sie dazu:

* Zeigen Sie, dass Änderungsanforderungen die folgenden Details haben:

&#x2713; dokumentierte Auswirkungen.

&#x2713; Details dazu, welche Funktionstests durchgeführt werden sollen.

&#x2713; details of any back-out procedures.

* Zeigen Sie, dass Funktionstests nach Abschluss der Änderungen durchgeführt werden.

* Zeigen Sie, dass Änderungsanforderungen nach dem Durchführen von Funktionstests abgesenkt werden.

**Kontoverwaltung**

Da iso 27001-Prüfungen einige Elemente von Kontoverwaltungsprozessen nicht speziell bewerten, müssen Sie dazu:

*   Veranschaulichen, wie &#x2713;implementiert werden, um Wiedergabeangriffe zu mildern (z. B. MFA, Kerberos).
*   Veranschaulichen Sie, wie Konten, die in 3 Monaten nicht verwendet wurden, entweder deaktiviert oder gelöscht werden.
*   &#x2713; oder andere geeignete Gegenmaßnahmen müssen zum Schutz von Benutzeranmeldeinformationen konfiguriert werden. Die folgende Mindestkennwortrichtlinie sollte als Richtlinie verwendet werden:

&#x2713; Mindestkennwortlänge von 8 Zeichen.

&#x2713; Kontosperrungsschwellenwert von nicht mehr als 10 Versuchen.
 
&#x2713; Kennwortverlauf von mindestens fünf Kennwörtern.
 
&#x2713; erzwingt die Verwendung von starken Kennwörtern.
 
*   Zeigen Sie, dass MFA für alle Remotezugriffslösungen konfiguriert ist.

*   Zeigen Sie, dass eine starke Verschlüsselung für alle Remotezugriffslösungen konfiguriert ist.

*   Wenn sich die Verwaltung von öffentlichem DNS außerhalb der Umgebung befindet, müssen alle Benutzerkonten, die DNS-Änderungen vorgenommen haben, für die Verwendung von MFA konfiguriert sein.

**Intrusion Detection and Prevention (OPTIONAL)**

Da iso 27001-Prüfungen einige Elemente von Prozessen der Intrusion Detection and Prevention Services (IDPS) nicht speziell bewerten, müssen Sie dies wie folgt tun:

*   IDPS **SOLLTE** am Umkreis der unterstützenden Umgebung bereitgestellt werden.

*   **IDPS-Signaturen sollten** innerhalb des letzten Tages auf dem aktuellen Stand gehalten werden.

*   IDPS **SOLLTEN** für die TLS-Überprüfung konfiguriert werden.

*   IDPS **SOLLTE** für den gesamten eingehenden und ausgehenden Datenverkehr konfiguriert werden.

*   IDPS **SOLLTE** für die Warnung konfiguriert werden.

**Ereignisprotokollierung**

Da ISO 27001-Prüfungen einige Elemente von Sicherheitsereignisprotokollierungsprozessen nicht speziell bewerten, müssen Sie dazu:

* Zeigen Sie, dass sich öffentlich zugängliche Systeme bei einer zentralisierten Protokollierungslösung anmelden, die sich nicht innerhalb der DMZ befindet.

* Zeigen Sie, wie Protokollierungsdaten im Wert von mindestens 30 Tagen sofort verfügbar sind, während 90 Tage aufbewahrt werden.

**Überprüfen (Protokollierungsdaten)**

Da iso 27001-Prüfungen einige Elemente dieser Kategorie nicht speziell bewerten, müssen Sie dazu:

*   Zeigen Sie, wie tägliche Protokollüberprüfungen durchgeführt werden und wie Ausnahmen und Anomalien identifiziert werden, die zeigen, wie diese behandelt werden.

**Warnung**

Da iso 27001-Prüfungen einige Elemente dieser Kategorie nicht speziell bewerten, müssen Sie dazu:

* Veranschaulichen Sie, wie Sicherheitsereignisse so konfiguriert werden, dass Warnungen für die sofortige Triage ausgelöst werden.

* Zeigen Sie, wie Mitarbeiter rund um die Uhr zur Verfügung stehen, um auf Sicherheitswarnungen zu reagieren.

**Risikomanagement**

Da iso 27001-Prüfungen einige Elemente von Risikobewertungsprozessen nicht speziell bewerten, müssen Sie dazu:

* Nachweisen, dass ein formaler Risikomanagementprozess eingerichtet wurde.

**Reaktion auf Vorfälle**

Da iso 27001-Prüfungen einige Elemente von Richtlinien und Prozessen zur Reaktion auf Vorfälle nicht speziell bewerten, müssen Sie dazu:

*   Zeigen Sie, dass der Plan/die Prozedur für die Reaktion auf Vorfälle:

&#x2713; Spezifische Reaktionsverfahren für erwartete Bedrohungsmodelle.

&#x2713; Funktionen zur Behandlung von Vorfällen, die an das NIST Cybersecurity Framework ausgerichtet sind (Identifizieren, Schützen, Erkennen, Reagieren, Wiederherstellen).
 
&#x2713; Das IRP deckt die systeme in den Bereich ab.
 
&#x2713; jährliche Schulung für das Team für die Reaktion auf Vorfälle.

## <a name="appendix-d"></a>Anhang D

### <a name="evidence-collection--deltas-for-pci-dss"></a>Evidence Collection – Deltas für PCI DSS

Wo Sie bereits pci DSS-Compliance erreicht haben, müssen die folgenden Deltas (Lücken), die nicht vollständig von PCI DSS abgedeckt werden, mindestens im Rahmen dieser Microsoft 365-Zertifizierung überprüft werden.

> [!NOTE]
> Im Rahmen der Microsoft 365-Zertifizierungsbewertung ermittelt der Zertifizierungsanalyst, ob eines der zugeordneten PCI-DSS-Steuerelemente nicht teil der PCI-DSS-Bewertung enthalten war, und entscheidet sich möglicherweise auch für Stichprobensteuerelemente, die als enthalten gefunden wurden, um weitere Sicherheit zu bieten. Alle Anforderungen, die im PCI DSS fehlen, müssen in die Microsoft 365-Zertifizierungsbewertungsaktivitäten einbezogen werden.

**Schadsoftwareschutz – Anwendungssteuerung**

Wenn schadsoftwareschutz durch Verwendung von Antivirensoftware besteht und innerhalb des PCI DSS-Berichts bestätigt wird, ist keine weitere Untersuchung erforderlich. Wenn kein Virenschutz besteht, müssen Zertifizierungsanalysten Nachweise für Anwendungskontrollesmechanismen identifizieren und bewerten, um die Detonation von Schadsoftware in der Umgebung zu verhindern. Dazu müssen Sie: 

*   Demonstrieren Sie, wie die Anwendungsgenehmigung durchgeführt wird, und bestätigen Sie, dass dies abgeschlossen ist.

*   Zeigen Sie, dass eine vollständige Liste der genehmigten Anwendungen mit geschäftlicher Begründung vorhanden ist.

*   Die Bereitstellung oder Veranschaulichen der unterstützenden Dokumentation enthält ausführliche Informationen dazu, wie Die Anwendungskontrollessoftware so konfiguriert ist, dass sie bestimmten Anwendungskontrollesmechanismen (z. B. Whitelisting, Codesignierung usw.) entspricht.

*   Zeigen Sie, dass die Anwendungssteuerung für alle Systemkomponenten mit Beispielen als dokumentiert konfiguriert ist.

**Patchverwaltung – Risikobewertung**

Da PCI-DSS-Prüfungen diese Kategorie nicht speziell bewerten, müssen Sie dazu:

* Zeigen Sie, wie die Risikorangfolge von Sicherheitsrisiken durchgeführt wird.

**Prüfung auf Schwachstellen**

Da PCI-DSS-Prüfungen diese Kategorie nicht speziell bewerten, müssen Sie dazu:

* Zeigen Sie, dass die Behebung in Einklang mit der dokumentierten Richtlinie zur Behebung von Sicherheitslücken durchgeführt wird.

**Firewall – Firewalls (oder gleichwertige Technologien)**

Da PCI-DSS-Prüfungen diese Kategorie nicht speziell bewerten, müssen Sie dazu:

* Demonstrieren Sie, dass Firewalls nur starke Kryptografie auf allen administrativen Schnittstellen unterstützen, die keine Konsolen sind.

* Zeigen Sie, dass die für das Internet verfügbar gemachten verwaltungstechnischen Schnittstellen der Firewall MFA unterstützen.

Zusätzliche Guthaben werden bereitgestellt, wenn eine Webanwendungsfirewall (Web Application Firewall, WAF) bereitgestellt wird, um sich vor der Vielzahl von Webanwendungsbedrohungen und Sicherheitsrisiken zu schützen, denen die Anwendung ausgesetzt werden kann. Wenn ein WAF oder ähnliches vorhanden ist, müssen Sie:

* Zeigen Sie, dass der WAF im aktiven Abwehrmodus konfiguriert ist, oder überwachen Sie mehr mit Benachrichtigungen.

* Demonstrieren, dass der WAF für die Unterstützung des SSL-Offloadings konfiguriert ist.

* Wird entsprechend dem OWASP-Kernregelsatz (3.0 oder 3.1) konfiguriert, um vor den meisten der folgenden Angriffstypen zu schützen:

&#x2713; Protokoll- und Codierungsprobleme.

&#x2713; Kopfzeileneinspritzung, Anforderungsschmuggler und Reaktionssplitting.

&#x2713; Datei- und Pfad-Traversalangriffe.

&#x2713; Remote file inclusion (RFI)-Angriffe.

&#x2713; Remotecodeausführungsangriffe.

&#x2713; PHP-Injection-Angriffe.

&#x2713; websiteübergreifende Skriptangriffe.

&#x2713; SQL-Injection-Angriffe.

&#x2713; Session-Fixation-Angriffe.

**Änderungssteuerung**

Da PCI-DSS-Prüfungen einige Elemente von Änderungsanforderungsprozessen nicht speziell bewerten, müssen Sie dazu:

* Zeigen Sie, dass Änderungsanforderungen ausgelöst werden, bevor sie in Produktionsumgebungen vorgenommen werden.

* Zeigen Sie, dass Änderungen autorisiert sind, bevor Sie in die Produktion gehen.

* Zeigen Sie, dass Funktionstests nach Abschluss der Änderungen durchgeführt werden.

* Zeigen Sie, dass Änderungsanforderungen nach dem Durchführen von Funktionstests abgesenkt werden.

**Entwicklung/Bereitstellung sicherer Software**

Da PCI#A0 nicht speziell auf einige Elemente sicherer Softwareentwicklungs- und Bereitstellungsprozesse zugreifen; Dies erfordert für Sie:

* Coderepositorys MÜSSEN durch MFA gesichert werden.

*   Es müssen geeignete Zugriffssteuerelemente zum Schutz von Coderepositorys vor Böswilligen Codeänderungen bereitgestellt werden.

**Kontoverwaltung**

Da PCI-DSS-Prüfungen einige Elemente von Kontoverwaltungsprozessen nicht speziell bewerten, müssen Sie dazu:

* Veranschaulichen, wie die Autorisierungsmechanismen implementiert werden, um Wiedergabeangriffe zu mindern (z. B. MFA, Kerberos).

* Richtlinien für starke Kennwörter oder andere geeignete Gegenmaßnahmen müssen zum Schutz von Benutzeranmeldeinformationen konfiguriert werden. Die folgende Mindestkennwortrichtlinie sollte als Richtlinie verwendet werden: 

&#x2713; Mindestkennwortlänge von 8 Zeichen.

&#x2713; Kontosperrungsschwellenwert von nicht mehr als 10 Versuchen.

&#x2713; Kennwortverlauf von mindestens fünf Kennwörtern.

&#x2713; erzwingt die Verwendung von starken Kennwörtern.

* Zeigen Sie, dass eine starke Verschlüsselung für alle Remotezugriffslösungen konfiguriert ist.

* Wenn sich die Verwaltung von öffentlichem DNS außerhalb der Umgebung befindet, müssen alle Benutzerkonten, die DNS-Änderungen vorgenommen haben, für die Verwendung von MFA konfiguriert sein.

**Intrusion Detection and Prevention (OPTIONAL)**

Da PCI-DSS-Prüfungen einige Elemente von Intrusion Detection and Prevention Services (IDPS)-Prozessen nicht speziell bewerten, müssen Sie dazu:

* IDPS SOLLTEN für die TLS-Überprüfung konfiguriert werden.

*   IDPS SOLLTE für den gesamten eingehenden und ausgehenden Datenverkehr konfiguriert werden.

**Risikomanagement**

Da PCI-DSS-Prüfungen einige Elemente von Risikobewertungsprozessen nicht speziell bewerten, müssen Sie dazu:

* Nachweisen der Risikobewertung umfasst Auswirkungs- und Wahrscheinlichkeitsmatrizen.

**Reaktion auf Vorfälle**

Da PCI-DSS-Prüfungen einige Elemente von Richtlinien und Prozessen zur Reaktion auf Vorfälle nicht speziell bewerten, erfordert dies, dass der Entwickler:

* Demonstrieren Der Umgang mit Vorfällen entspricht dem NIST Cybersecurity Framework (Identifizieren, Schützen, Erkennen, Reagieren, Wiederherstellen).

## <a name="appendix-e"></a>Anhang E

### <a name="evidence-collection---deltas-for-soc-2"></a>Evidence Collection – Deltas für SOC 2

Wo Sie bereits die SOC 2-Compliance erreicht haben, müssen die folgenden Deltas (Lücken), die nicht vollständig von SOC 2 abgedeckt werden, im Rahmen dieser Microsoft 365-Zertifizierung überprüft werden.

> [!NOTE]
> Im Rahmen der Microsoft 365-Zertifizierungsbewertung ermittelt der Zertifizierungsanalyst, ob eines der zugeordneten SOC 2-Steuerelemente nicht teil ihrer SOC 2-Bewertung enthalten war, und entscheidet möglicherweise auch, Steuerelemente zu stichproben, die als eingeschlossen gefunden wurden, um weitere Sicherheit zu bieten. Alle Anforderungen, die in Ihrer SOC 2-Bewertung fehlen, müssen in die Microsoft 365-Zertifizierungsbewertungsaktivitäten einbezogen werden.

**Schadsoftwareschutz – Anwendungssteuerung**

Wenn schadsoftwareschutz durch Die Verwendung von Antivirensoftware besteht und in Ihrem SOC 2-Bericht bestätigt wird, ist keine weitere Untersuchung erforderlich. Wenn kein Virenschutz besteht, müssen Zertifizierungsanalysten Nachweise für Anwendungskontrollesmechanismen identifizieren und bewerten, um die Detonation von Schadsoftware in der Umgebung zu verhindern. Dazu müssen Sie:

* Die Bereitstellung oder Veranschaulichen der unterstützenden Dokumentation enthält ausführliche Informationen dazu, wie Die Anwendungskontrollessoftware so konfiguriert ist, dass sie bestimmten Anwendungskontrollesmechanismen (z. B. Whitelisting, Codesignierung usw.) entspricht.

* Demonstrieren Sie, wie die Anwendungsgenehmigung durchgeführt wird, und bestätigen Sie, dass dies abgeschlossen ist.

*   Zeigen Sie, dass eine vollständige Liste der genehmigten Anwendungen mit geschäftlicher Begründung vorhanden ist.

*   Zeigen Sie, dass die Anwendungssteuerung für alle Systemkomponenten mit Beispielen als dokumentiert konfiguriert ist.

**Patchverwaltung – Patching**

Da SOC 2-Prüfungen diese Kategorie nicht speziell bewerten, müssen Sie dazu:

*   Alle Probleme mit Low, Medium, High oder Critical müssen innerhalb normaler Patchingaktivitätsfenster gepatcht werden.

*   Softwarekomponenten und Betriebssysteme, die vom Hersteller nicht mehr unterstützt werden, dürfen nicht innerhalb der Umgebung verwendet werden. Unterstützende Richtlinien MÜSSEN verfügbar sein, um sicherzustellen, dass nicht unterstützte Softwarekomponenten/Betriebssysteme aus der Umgebung entfernt werden, und es muss ein Prozess zur Ermittlung des Ablaufs von Softwarekomponenten ausgeführt werden.

**Firewall – Firewalls**

Da SOC 2-Prüfungen änderungssteuerelemente in Firewallzugriffssteuerungslisten nicht speziell bewerten, müssen Sie dazu:

* Zeigen Sie, dass der gesamte zugelassene Datenverkehr über die Firewall einen Autorisierungsprozess durchgeht, der zur Dokumentation des datenverkehrs mit einer geschäftlichen Begründung führt.

* Zeigen Sie, dass Firewallregelüberprüfungen mindestens alle sechs Monate durchgeführt werden.

Zusätzliche Guthaben werden bereitgestellt, wenn eine Webanwendungsfirewall (Web Application Firewall, WAF) oder ähnliches bereitgestellt wird, um den Schutz vor der Vielzahl von Webanwendungsbedrohungen und Sicherheitsrisiken zu unterstützen, denen die Anwendung ausgesetzt werden kann. Wenn ein WAF oder ähnliches vorhanden ist, müssen Sie:

* Zeigen Sie, dass der WAF im aktiven Abwehrmodus konfiguriert ist, oder überwachen Sie mehr mit Benachrichtigungen.

* Demonstrieren, dass der WAF für die Unterstützung des SSL-Offloadings konfiguriert ist.

* Wird entsprechend dem OWASP-Kernregelsatz ((3.0 oder 3.1) konfiguriert, um vor den meisten der folgenden Angriffstypen zu schützen:

&emsp;&#x2713; Protokoll- und Codierungsprobleme.

&emsp;&#x2713; Kopfzeileneinspritzung, Anforderungsschmuggler und Reaktionsteilung.

&emsp;&#x2713; Datei- und Pfad-Traversalangriffe.

&emsp;&#x2713; Remote file inclusion (RFI)-Angriffe.

&emsp;&#x2713; Remotecodeausführungsangriffe.

&emsp;&#x2713; PHP-Injection-Angriffe.

&emsp;&#x2713; websiteübergreifende Skriptangriffe.

&emsp;&#x2713; SQL-Injection-Angriffe.

&emsp;&#x2713; Session-Fixation-Angriffe.

**Änderungssteuerung**

Da SOC 2-Audits einige Elemente von Änderungsanforderungsprozessen nicht speziell bewerten, muss der Entwickler dies tun:

* Zeigen Sie, wie Entwicklungs-/Testumgebungen von der Produktionsumgebung getrennt sind, um die Aufgabentrennung zu erzwingen.

* Zeigen Sie, wie Livedaten in den Entwicklungs-/Testumgebungen nicht verwendet werden.

* Zeigen Sie, dass Funktionstests nach Abschluss der Änderungen durchgeführt werden.

* Zeigen Sie, dass Änderungsanforderungen nach dem Durchführen von Funktionstests abgesenkt werden.

**Entwicklung/Bereitstellung sicherer Software**

Da SOC 2-Prüfungen nicht speziell auf einige Elemente sicherer Softwareentwicklungs- und Bereitstellungsprozesse zugreifen; Dies erfordert für Sie:

*   Sie MÜSSEN über einen etablierten und dokumentierten Softwareentwicklungsprozess verfügen, der den gesamten Softwareentwicklungslebenszyklus deckt.

*   Entwickler müssen mindestens jährlich eine Schulung zur sicheren Softwarecodierung durchlaufen.

*   Coderepositorys MÜSSEN durch MFA gesichert werden.

*   Es müssen geeignete Zugriffssteuerelemente zum Schutz von Coderepositorys vor Böswilligen Codeänderungen bereitgestellt werden.

**Kontoverwaltung**

Da bei SOC2-Prüfungen einige Elemente von Kontoverwaltungsprozessen nicht speziell bewertet werden, müssen Sie dazu:

*   Veranschaulichen, wie die Autorisierungsmechanismen implementiert werden, um Wiedergabeangriffe zu mindern (z. B. MFA, Kerberos).

*   Veranschaulichen Sie, wie Konten, die in 3 Monaten nicht verwendet wurden, entweder deaktiviert oder gelöscht werden.

*   Richtlinien für starke Kennwörter oder andere geeignete Gegenmaßnahmen müssen zum Schutz von Benutzeranmeldeinformationen konfiguriert werden. Die folgende Mindestkennwortrichtlinie sollte als Richtlinie verwendet werden:

&emsp;&#x2713; Minimale Kennwortlänge von 8 Zeichen.

&emsp;&#x2713; Kontosperrungsschwellenwert von nicht mehr als 10 Versuchen.

&emsp;&#x2713; Kennwortverlauf von mindestens 5 Kennwörtern.

&emsp;&#x2713; Durchsetzung der Verwendung von starken Kennwörtern

*   Zeigen Sie, dass eindeutige Benutzerkonten für alle Benutzer ausgegeben werden.

*   Wenn sich die Verwaltung von öffentlichem DNS außerhalb der Umgebung befindet, müssen alle Benutzerkonten, die DNS-Änderungen vorgenommen haben, für die Verwendung von MFA konfiguriert sein.

**Intrusion Detection and Prevention (OPTIONAL).**

Da SOC 2-Prüfungen einige Elemente von Prozessen der Intrusion Detection and Prevention Services (IDPS) nicht speziell bewerten, müssen Sie dies tun:

*   IDPS-Signaturen sollten innerhalb des letzten Tages auf dem aktuellen Stand gehalten werden.

*   IDPS SOLLTE für die TLS-Überprüfung konfiguriert werden

*   IDPS SOLLTE für den gesamten eingehenden und ausgehenden Datenverkehr konfiguriert werden

**Ereignisprotokollierung**

Da SOC 2-Prüfungen einige Elemente von Sicherheitsereignisprotokollierungsprozessen nicht speziell bewerten, müssen Sie dies tun:

* Veranschaulichen, wie das folgende System für alle Systemkomponenten innerhalb des Beispielsatzs so konfiguriert ist, dass die folgenden Ereignisse protokolliert werden

&emsp;&#x2713; Benutzerzugriff auf Systemkomponenten und die Anwendungen.

&emsp;&#x2713; Alle Aktionen, die von einem Benutzer mit hohen Berechtigungen ausgeführt werden.

&emsp;&#x2713; Ungültige logische Zugriffsversuche.

Nachweisen, dass protokollierte Ereignisse enthalten sind; mindestens die folgenden Informationen:

&emsp;&#x2713; Benutzer.

&emsp;&#x2713; Ereignistyp.

&emsp;&#x2713; Datum und Uhrzeit.

&emsp;&#x2713; Erfolgs-/Fehlerindikator.

&emsp;&#x2713; Bezeichnung, um das betroffene System zu identifizieren.

*   Zeigen Sie, dass alle Systemkomponenten im Beispielsatz für die Verwendung der Zeitsynchronisierung konfiguriert sind und dass diese mit den primären/sekundären Zeitservern identisch sind.

* Zeigen Sie, dass sich öffentlich zugängliche Systeme bei einer zentralisierten Protokollierungslösung anmelden, die sich nicht innerhalb der DMZ befindet.

*   Zeigen Sie, dass sich öffentlich zugängliche Systeme bei einer zentralisierten Protokollierungslösung anmelden, die sich nicht innerhalb der DMZ befindet.

* Zeigen Sie, wie die lösung für die zentralisierte Protokollierung vor nicht autorisierten Manipulationen von Protokollierungsdaten geschützt ist.

* Zeigen Sie, wie Protokollierungsdaten im Wert von mindestens 30 Tagen sofort verfügbar sind und mindestens 90 Tage aufbewahrt werden.

**Risikomanagement**

Da soc2-Prüfungen einige Elemente von Risikobewertungsprozessen nicht speziell bewerten, müssen Sie dazu:

* Nachweisen, dass mindestens jährlich eine formelle Risikobewertung durchgeführt wird.

*Reaktion auf Vorfälle.*

Da bei SOC2-Prüfungen einige Elemente von Richtlinien und Prozessen zur Reaktion auf Vorfälle nicht speziell bewertet werden, müssen Sie dies tun:

* Zeigen Sie, dass der Plan/die Prozedur für die Reaktion auf Vorfälle:

&emsp;&#x2713; Spezifische Reaktionsverfahren für erwartete Bedrohungsmodelle.

&emsp;&#x2713; dokumentierten Kommunikationsprozess, um eine zeitnahe Benachrichtigung wichtiger Beteiligter (Zahlungsmarken/-erwerber, Aufsichtsbehörden, Aufsichtsbehörden, Directors, Kunden usw.) sicherzustellen.

## <a name="appendix-f"></a>Anhang F

### <a name="hosting-deployment-types"></a>Hosten von Bereitstellungstypen

Microsoft bestätigt, dass Sie Anwendungen bereitstellen und App/Add-In-Code in verschiedenen Hostingumgebungen speichern. Die Gesamtverantwortung einiger Sicherheitssteuerelemente innerhalb der Microsoft 365-Zertifizierung hängt von der verwendeten Hostingumgebung ab. Anhang F untersucht allgemeine Bereitstellungstypen und ordnet diese den Sicherheitssteuerelementen zu, die im Rahmen des Bewertungsprozesses ausgewertet werden. Die folgenden Hostingbereitstellungstypen wurden identifiziert:

|  |  |
|-----|------|
|**ISV Hosted**|Von ISV gehostete Typen können als der Ort definiert werden, an dem Sie für die Infrastruktur verantwortlich sind, die zur Unterstützung der App/Add-In-Umgebung verwendet wird. Dies kann sich physisch in Ihren eigenen Rechenzentren oder Rechenzentren von Drittanbietern mit einem gemeinsamen Standortdienst befinden. Letztendlich verfügen Sie über den vollständigen Besitz und die administrative Kontrolle über die unterstützende Infrastruktur und Betriebsumgebung.|
|**Infrastructure as a Service (IaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-iaas/)|Infrastructure as a Service ist ein Dienst, der bereitgestellt wird, bei dem die physische unterstützende Infrastruktur vom Clouddienstanbieter (Cloud Service Provider, CSP) verwaltet und in ihrem Namen verwaltet wird. In der Regel liegt die Verantwortung für Netzwerke, Speicher, physische Server und die Virtualisierungsinfrastruktur in der Verantwortung des CSP. Das Betriebssystem, middleware, Runtime, Data and Applications sind die Verantwortlichkeiten von Ihnen. Firewallfunktionen würden auch vom Drittanbieter verwaltet und verwaltet, die Wartung der Firewallregelbasis würde jedoch in der Regel weiterhin in der Verantwortung der Verbraucher bleiben.|
|**Platform as a Service/Serverless (PaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-paas/)| Mit Platform as a Service werden Sie mit einer verwalteten Plattform bereitgestellt, die einen Dienst bietet, der genutzt werden kann. Sie müssen keine sysadmin-Funktionen ausführen, da das Betriebssystem und die unterstützende Infrastruktur vom CSP verwaltet wird. Dies würde in der Regel verwendet, wenn Organisationen sich keine Gedanken über die Darstellung eines Webdiensts machen möchten und sich stattdessen auf das Erstellen des Webanwendungs-Quellcodes und die Veröffentlichung der Webanwendung in den cloudver verwalteten Webdiensten konzentrieren können.  Ein weiteres Beispiel kann ein Datenbankdienst sein, bei dem eine Verbindung mit einer Datenbank besteht, die unterstützende Infrastruktur und Datenbankanwendung wird jedoch vom Verbraucher abstrahiert.   **Hinweis: Serverless und PaaS ähneln sich daher für den Zweck des Microsoft 365-Zertifizierungshostingbereitstellungstyps Serverless und PasS als identisch.**|
|**Hybrid gehostet**|Mit dem hybrid gehosteten Typ können Sie mehrere gehostete Typen verwenden, um verschiedene Teile der unterstützenden Umgebung zu unterstützen. Dies kann eher der Fall sein, wenn Apps/Add-Ins in mehreren M365-Stapeln verwendet werden. Obwohl die Microsoft 365-Zertifizierung unterstützt, wo Apps/Add-Ons über mehrere M365-Dienste hinweg entwickelt werden, müsste eine Bewertung der gesamten (app-/add-ins)unterstützenden Umgebung in Einklang mit den jeweiligen "Gehosteten Typzuordnungen" bewertet werden. Gelegentlich können Sie unterschiedliche gehostete Typen für ein einzelnes Add-In verwenden. Dort, wo dies ausgeführt wird, muss die Anwendbarkeit von Kriterien weiterhin den Kriterien "Gehostete Typzuordnungen" für die verschiedenen gehosteten Typen entsprechen.|
|**Freigegebenes Hosting**|Gemeinsam genutztes Hosting ist der Ort, an dem Sie die Umgebung innerhalb einer Plattform hosten, die von mehreren einzelnen Verbrauchern gemeinsam genutzt wird. Die Microsoft 365-Zertifizierungsspezifikation wurde aufgrund der Einführung der Cloud nicht in die Rechnung geschrieben, freigegebenes Hosting ist nicht üblich. Wenn Sie der Meinung sind, dass dies verwendet wird, wenden Sie sich bitte an Microsoft, da zusätzliche Anforderungen erstellt werden müssen, um die zusätzlichen Risiken dieses Hostingtyps zu berücksichtigen.|


## <a name="appendix-g"></a>Anhang G

### <a name="microsoft-365-certification-process-workflow"></a>Microsoft 365 Certification Process Workflow

![Workflow](ProcessFlow.jpg)

## <a name="learn-more"></a>Weitere Informationen

[Microsoft 365 App Compliance Program ( Übersicht)](~/overview.md)  
[Was ist Microsoft 365 App Publisher Attestation?](~/docs/attestation.md)  
[Was ist Microsoft 365-Zertifizierung?](~/docs/enterprise-app-certification-guide.md)

## <a name="glossary"></a>Glossar

### <a name="aia"></a>AIA

*Authority Information Access ist ein Dienststandortdeskriptor, der zum Suchen des Zertifikats der ausstellenden Zertifizierungsstelle verwendet wird.

### <a name="crl"></a>CRL

*Die Zertifikatsperrliste stellt eine Möglichkeit für einen #A0 (Secure Sockets Layer) zur Verfügung, um zu überprüfen, ob ein von einem Remotehost empfangenes Zertifikat gültig und vertrauenswürdig ist.

### <a name="cvss-score"></a>CVSS-Bewertung

*Common Vulnerability Scoring System ist ein veröffentlichter Standard, der die Sicherheitsanfälligkeit misst und eine numerische Bewertung basierend auf dem Schweregrad berechnet.

### <a name="cvss-patch-management-guidelines"></a>Richtlinien für die Verwaltung von CVSS-Patches

* Kritisch (9.0 - 10.0)
* Hoch (7,0 - 8,9)
* Mittel (4,0 - 6,9)
* Niedrig (0,0 - 3,9)

### <a name="dmz"></a>DMZ

*Demilitarisierte Zone ist ein physisches oder logisches Zwischennetzwerk, das direkt externe oder nicht proprietierte Netzwerke interagiert und gleichzeitig das interne, private Netzwerk des Hosts getrennt und isoliert hält.

### <a name="euii"></a>EUII

*Identifizierbare Endbenutzerinformationen*.

### <a name="gdpr"></a>DSGVO

*Die Datenschutz-Grundverordnung ist eine Datenschutz- und Datenschutzverordnung der Europäischen Union (EU) für alle Daten von EU-Bürgern, unabhängig davon, wo sich Ihre Anwendungswebsite befindet.

### <a name="hsts"></a>HSTS

*HTTP Strict Transport Security verwendet einen HTTP-Antwortheader, der den Webbrowser anweisen soll, nur auf Inhalte über HTTPS zu zugreifen.  Dies dient zum Schutz vor Herabstufungsangriffen und Cookie-Hijacking.

### <a name="iec"></a>IEC

*International Electrotechnical Commission.

### <a name="isms"></a>ISMS

*Information Security Management System.

### <a name="isv"></a>ISV

Unabhängige Sicherheitsanbieter sind Einzelpersonen und Organisationen, die Software entwickeln, vertreiben und verkaufen, die auf Software- und Hardwareplattformen von Drittanbietern ausgeführt wird.

### <a name="iso-27001"></a>ISO 27001

Ein Spezifikationsframework für das Informationssicherheitsverwaltungssystem für alle technischen Kontrollen in organisationen Risikomanagementrichtlinien und -verfahrensprozessen.

### <a name="lfi"></a>LFI

*Lokale Dateieinschluss* ermöglicht es einem Angreifer, Dateien über den Webbrowser auf einem Server zu enthalten.

### <a name="nist"></a>NIST

Das *National Institute of Standards* (NIST), eine nicht regulatorische Agentur des US-Amerikanischen Handelsministeriums, bietet Organisationen des privaten Sektors in den USA Anleitungen zum Bewerten und Genehmigen ihrer Fähigkeit, Cyberangriffe zu verhindern, zu erkennen und darauf zu reagieren.

### <a name="non-significant-changes"></a>Nicht signifikante Änderungen

* Kleinere Fehlerbehebungen.
* Geringfügige Leistungsverbesserungen.
* Betriebssysteme/Bibliotheken/Client- und Serveranwendungspatches.

### <a name="ocsp"></a>OCSP

*Das Onlinezertifikatstatusprotokoll* wird verwendet, um den Sperrstatus digitaler X.509-Zertifikate zu überprüfen.

### <a name="oii"></a>OII

*Identifizierbare Informationen der Organisation*.

### <a name="owasp"></a>OWASP

*Öffnen Sie Webanwendungssicherheitsprojekt*.

### <a name="pci-dss"></a>PCI/DSS

*Payment Card Industry Data Security Standard*, eine Organisation, die Standards für die Sicherheit von Karteninhaberdaten weltweit beibehält.

### <a name="pen-testing"></a>Stifttests

*Penetrationstests* sind eine Methode zum Testen einer Web-App, indem bösartige Angriffe simuliert werden, um Sicherheitsrisiken zu finden, die ein Angreifer ausnutzen könnte.

### <a name="saml"></a>SAML

*Security Assertion Markup Language* ist ein offener Standard für den Austausch von Authentifizierungs- und Autorisierungsdaten zwischen dem Benutzer, dem Identitätsanbieter und dem Dienstanbieter.

### <a name="sensitive-data"></a>Vertrauliche Daten

* Zugriffssteuerungsdaten.
* Kundeninhalte.
* Endbenutzeridentitätsinformationen.
* Supportdaten.
* Öffentliche personenbezogene Daten.
* Pseudonyme Informationen des Endbenutzers.

### <a name="significant-changes"></a>Wesentliche Änderungen

* Verlagerung der Hostingumgebung.
* Wichtige Upgrades der unterstützenden Infrastruktur; z. B. Implementierung einer neuen Firewall, größere Upgrades auf front-gerichtete Dienste usw.
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
