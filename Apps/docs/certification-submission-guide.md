---
ms.author: oromalle
title: Microsoft 365 Leitfaden für die Zertifizierungsübermittlung
author: orionomalley
description: Microsoft 365 Detaillierte Ansicht des Leitfadens für die Zertifizierungsübermittlung
keywords: App-Zertifizierungsteams Microsoft 365 Security Compliance m365
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 31c974a20e17daa0436826432429bd664a9a1f59dee6b351b587ae0b30cc6bac
ms.sourcegitcommit: 717ca5bc90981def8914c4cd1fad992f67be4d5b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/06/2021
ms.locfileid: "54750539"
---
# <a name="microsoft-365-certification-submission-guide"></a>Microsoft 365 Leitfaden für die Zertifizierungsübermittlung

**Inhalt dieses Artikels:**
- [Einführung](#introduction)
- [Voraussetzungen](#prerequisites) 
- [Microsoft 365 Updates der Zertifizierungsspezifikation](#microsoft-365-certification-specification-updates)
- [Zertifizierungsbereich](#certification-scope)
- [Zertifizierungsprozess](#certification-process)
- [Ursprüngliche Dokumentübermittlung](#initial-document-submission) 
- [Aktivitäten zur Sammlung und Bewertung von Nachweisen](#evidence-collection-and-assessment-activities)
- [Zertifizierungskriterien](#app-certification-criteria)
- [Application Security](#application-security)
- [Betriebssicherheit](#operational-security) 
- [Sicherheit und Datenschutz bei der Datenverarbeitung](#data-handling-security-and-privacy)
- [Optionale Überprüfung externer Compliance-Frameworks](#optional-external-compliance-frameworks-review)
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

Als Teil des Microsoft 365 App Compliance-Programms bietet die Microsoft 365-Zertifizierung Unternehmen die Gewissheit und das Vertrauen, dass Daten und Datenschutz bei der Integration von Drittanbieter-Entwickler-Apps/-Add-Ins in die Microsoft 365-Plattform angemessen geschützt und geschützt sind. Anwendungen und Add-Ins, die die Validierung bestehen, werden im gesamten Microsoft 365 Ökosystem **Microsoft 365 zertifiziert.** 

Durch die Teilnahme am Microsoft 365 Zertifizierungsprogramm erklären Sie sich mit diesen ergänzenden Bestimmungen einverstanden und halten alle Begleitdokumentationen ein, die für Ihre Teilnahme am Microsoft 365 Zertifizierungsprogramm mit der Microsoft Corporation gelten ("Microsoft", "wir", "uns" oder "unser"). Sie erklären und garantieren uns, dass Sie berechtigt sind, diese ergänzenden Bedingungen Microsoft 365 Zertifizierung im Namen von Sich selbst, eines Unternehmens und/oder einer anderen Entität zu akzeptieren, sofern zutreffend. Wir können diese ergänzenden Bestimmungen jederzeit ändern, ändern oder beenden. Ihre fortgesetzte Teilnahme am Microsoft 365 Zertifizierungsprogramm nach jeder Änderung oder Änderung bedeutet, dass Sie den neuen ergänzenden Bedingungen zustimmen. Wenn Sie den neuen ergänzenden Bestimmungen nicht zustimmen oder wenn wir diese ergänzenden Bedingungen kündigen, müssen Sie die Teilnahme am Microsoft 365 Zertifizierungsprogramm beenden.

Dieses Dokument richtet sich an ISVs (Unabhängige Softwareanbieter), um Informationen zum Microsoft 365 Zertifizierungsprozess, voraussetzungen für den Beginn des Prozesses und Details zu bestimmten Sicherheitskontrollen bereitzustellen, die ISVs besitzen müssen.  Allgemeine Informationen zum Microsoft 365 App Compliance-Programm finden Sie auf der [Seite](https://docs.microsoft.com/microsoft-365-app-certification/overview)Microsoft 365 App-Compliance-Programm. 

> [!IMPORTANT]
> Derzeit gilt Microsoft 365 Zertifizierung für alle:
>* Microsoft Teams Anwendungen (Registerkarten, Bots usw.) .
>* SharePoint-Apps/-Add-Ins
>* Office Add-Ins (Word, Excel, PowerPoint, Outlook, Project, OneNote)
>* Webapps

## <a name="prerequisites"></a>Voraussetzungen

### <a name="publisher-attestation"></a>Herausgebernachweis

Bevor Sie den Microsoft 365 Zertifizierungsprozess erhalten haben, müssen Sie Publisher Attestation abgeschlossen haben. Sie können jedoch den Microsoft 365 Zertifizierungsprozess starten, bevor Sie Publisher Attestation abschließen.  

### <a name="read-the-microsoft-365-certification-specification"></a>Lesen sie die Spezifikation der Microsoft 365-Zertifizierung

Microsoft empfiehlt allen ISVs (Unabhängiger Softwareanbieter), diese Microsoft 365 Zertifizierungsspezifikation vollständig zu lesen, um sicherzustellen, dass alle anwendbaren Steuerelemente von der Bereichsumgebung und der App/dem Add-In erfüllt werden. Dadurch wird ein reibungsloser Bewertungsprozess sichergestellt.

## <a name="microsoft-365-certification-specification-updates"></a>Microsoft 365 Updates der Zertifizierungsspezifikation 

Aktualisierungen der Spezifikation Microsoft 365 Zertifizierung werden ungefähr alle sechs bis zwölf Monate erwartet. Diese Updates können neue Zielsicherheitsdomänen und/oder Sicherheitskontrollen einführen. Updates basieren auf Entwicklerfeedback, Änderungen an der Bedrohungslandschaft und zur Erhöhung der Sicherheitsgrundwerte des Programms, sobald es reift. 

ISVs, die bereits mit der Microsoft 365 Zertifizierungsbewertung begonnen haben, können die Bewertung mit der Version der Microsoft 365 Zertifizierungsspezifikation fortsetzen, die beim Starten der Bewertung gültig war. Alle neuen Übermittlungen, einschließlich der jährlichen Rezertifizierung, müssen anhand der veröffentlichten Version bewertet werden.

> [!NOTE]
> Sie müssen nicht alle Steuerelemente in dieser Microsoft 365 Zertifizierungsspezifikation einhalten, um eine Zertifizierung zu erhalten. Das Überschreiten von Schwellenwerten (die nicht offengelegt werden) ist jedoch für jede der Sicherheitsdomänen vorhanden, die in dieser Microsoft 365 Zertifizierungsspezifikation behandelt werden. Einige Steuerelemente werden als **"Hard Fail"** klassifiziert, was bedeutet, dass das Fehlen dieser Sicherheitskontrollen zu einer fehlgeschlagenen Bewertung führt. 

## <a name="certification-scope"></a>Zertifizierungsbereich

Die **Bereichsumgebung** ist die Umgebung, die die Bereitstellung des App-/Add-In-Codes und alle Back-End-Systeme unterstützt, mit denen die App/das Add-In kommunizieren kann. Alle zusätzlichen verbundenen Umgebungen werden ebenfalls in den Bereich einbezogen, es sei denn, eine angemessene Segmentierung ist vorhanden, und die verbundenen Umgebungen können sich nicht auf die Sicherheit der Bereichsumgebung auswirken. Alle Notfallwiederherstellungsumgebungen müssen ebenfalls in den Umfang der Bewertung einbezogen werden, da diese Umgebungen erforderlich sind, um den Dienst zu erfüllen, wenn etwas mit der primären Umgebung geschieht.  Der Begriff  **"Systemkomponenten im Bereich"**   verweist auf **ALLE** Geräte und Systeme, die innerhalb der Bereichsumgebung verwendet werden. In-Scope-Komponenten umfassen, sind aber nicht beschränkt auf:
* Die Webanwendung(en).
* Server.
* Firewalls (oder gleichwertig).
* Schalter.
* Lastenausgleichsmodule.
* Virtuelle Infrastruktur.
* Webverwaltungsportale für Cloudanbieter 

> [!IMPORTANT]
> Die In-Scope-Umgebung muss über eine DMZ verfügen, und die unterstützende Umgebung der App/des Add-Ins muss aus den internen Geschäftssystemen und Unternehmensumgebungen segmentiert werden, wodurch der Umfang der Bewertungsaktivitäten auf die in-Scope-Systeme beschränkt wird. Zertifizierungsanalysten überprüfen die Segmentierungstechniken während der Bewertung zusammen mit der Überprüfung von Penetrationstestberichten, die Tests enthalten sollten, um die Effektivität der verwendeten Segmentierungstechniken zu überprüfen.

### <a name="infrastructure-as-a-service-iaas-platform-as-a-service-paas-and-software-as-a-service-saas"></a>Infrastructure as a Service (IaaS), Platform as a Service (PaaS) und Software as a Service (SaaS) 
Wenn IaaS und/oder PaaS verwendet werden, um die Infrastruktur der zu überprüfenden Anwendungs- oder Add-In-Codebereitstellung zu unterstützen, ist der Cloudplattformanbieter für einige der Sicherheitskontrollen verantwortlich, die während des gesamten Zertifizierungsprozesses bewertet werden. Daher müssen Zertifizierungsanalysten über externe Complianceberichte wie [PCI DSS](bookmark://pci-dss)   Attestation of Compliance (AOC), ISO27001 oder [SOC 2](bookmark://soc-2)Type II unabhängige externe Überprüfung bewährter Sicherheitsmethoden durch den Cloudplattformanbieter   erhalten. 

Anhang F enthält Details dazu, welche Sicherheitskontrollen wahrscheinlich basierend auf den folgenden Bereitstellungstypen und basierend darauf anwendbar sind, ob die App/das Add-In M365-Daten exfiltriert oder nicht: 
* ISV Hosted 
* IaaS Hosted 
* PaaS/Serverless Hosted 
* Hybrid gehostet 
* Freigegeben gehostet 

Wenn IaaS oder PaaS bereitgestellt wird, müssen Sie nachweisen, dass die Umgebung in diesen Bereitstellungstypen gehostet wird.

### <a name="sampling"></a>Probenahme

Anträge auf Nachweise zur Unterstützung der Zertifizierungsbewertung sollten auf einem Beispiel der in-Scope-Systemkomponenten unter Berücksichtigung verschiedener Betriebssysteme, primärer Funktionen des Geräts und verschiedener Gerätetypen basieren. Zu Beginn des Zertifizierungsprozesses wird ein geeignetes Beispiel ausgewählt. Die folgende Tabelle sollte als Leitfaden für die Größe des Beispiels verwendet werden:

|Population Size              | Beispiel                  |
|---------------------------- |-------------------------|
|<5|1|
|>5 & <10|2|
|>9 & <25|3|
|>24|4 |

> [!NOTE]
>Wenn Abweichungen zwischen den im ersten Beispiel enthaltenen Geräten erkannt werden, kann die Stichprobengröße während der Bewertung erhöht werden. 

## <a name="certification-process"></a>Zertifizierungsprozess

Bevor Sie mit dem Zertifizierungsprozess beginnen, müssen Sie Ihre Publisher Attestation erfolgreich abgeschlossen haben. Ihre Nachweisantworten werden zur Unterstützung des Microsoft 365 Zertifizierungsprozesses verwendet und gehen wie folgt vor:

## <a name="certification-process"></a>Zertifizierungsprozess

Bevor Sie mit dem Zertifizierungsprozess beginnen, müssen Sie den Publisher Attestation abgeschlossen haben. Nachdem Ihr Herausgebernachweis genehmigt wurde, erhalten Sie eine einführende E-Mail, in der Sie zur Teilnahme an Microsoft 365 Zertifizierung eingeladen werden.

### <a name="preparation"></a>Vorbereitung
1. Navigieren Sie zum Partner Center, und überprüfen Sie Die ausgefüllte [Publisher Nachweisdokumentation.]( https://docs.microsoft.com/microsoft-365-app-certification/docs/attestation) Bei Bedarf können Sie Ihre Antworten bearbeiten und aktualisieren. Wenn Sie dies jedoch tun, müssen Sie Ihre Nachweisdokumentation zur Genehmigung erneut übermitteln. Wenn Ihre Übermittlung älter als drei Monate ist, müssen Sie Publisher Nachweis zur Überprüfung und Überprüfung erneut übermitteln. 
1. Lesen Sie den [Microsoft 365 Leitfaden zur Zertifizierungsübermittlung](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide) sorgfältig durch, um zu verstehen, was von Ihnen benötigt wird. Stellen Sie sicher, dass Sie die Im Microsoft 365 Zertifizierungsübermittlungshandbuch angegebenen [Kontrollanforderungen]( https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide#app-certification-criteria) erfüllen können.
1. Klicken Sie im Partner Center auf "Zertifizierung starten". Dadurch gelangen Sie zu Ihrem anfänglichen Dokumentübermittlungsportal. Übermitteln Sie Ihre [ursprüngliche Dokumentübermittlung.](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide#initial-document-submission) Dies hilft uns zu bestimmen, was für Ihre Bewertung gilt, basierend auf der Architektur Ihrer App und der Behandlung von Kundendaten. Überprüfen Sie diese Seite häufig, um festzustellen, ob Ihre Übermittlung akzeptiert wurde.

>[!NOTE]
>Für alle Office-Apps können Sie auf unser [benutzerhandbuch für Office Apps](https://docs.microsoft.com/microsoft-365-app-certification/docs/userguide)verweisen. Für alle WebApps können Sie auf unser [SaaS-App-Benutzerhandbuch](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/saasuserguide)verweisen.

### <a name="assessment"></a>Bewertung
1. Nachdem Ihre anfängliche Dokumentübermittlung akzeptiert wurde, werden die für Ihre App erforderlichen Sicherheitskontrollen automatisch im Portal angezeigt. Anschließend müssen Sie für jedes Steuerelement Nachweise übermitteln, die belegen, dass das Steuerelement vorhanden ist. Denken Sie daran, dass Ihnen **60 Tage** zeit werden, um alle Nachweise zu übermitteln. Ein Analyst überprüft Ihre Nachweise und genehmigt entweder das Steuerelement oder fordert neue oder zusätzliche Nachweise an. Überprüfen Sie diese Seite häufig, um festzustellen, ob Ihre Nachweise akzeptiert wurden.
### <a name="certification"></a>Zertifizierung
1. Nachdem Ihre Übermittlung von einem Analysten überprüft wurde, werden Sie über Ihre Zertifizierungsentscheidung benachrichtigt. Apps, die eine Zertifizierung erhalten, erhalten ein Badge auf ihrer Anwendung auf **AppSource-** und **Microsoft-Dokumentseiten.** Sie können [hier](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide#program-benefits)die vorteile der Zertifizierung in vollem Umfang lesen.

## <a name="review-and-re-certification"></a>Überprüfen und erneute Zertifizierung
Für den Fall, dass Ihre Anwendung zu einem beliebigen Zeitpunkt [erhebliche Änderungen](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide#significant-changes) durchläuft, müssen Sie uns benachrichtigen.

Außerdem müssen Sie die erneute Zertifizierung auf jährlicher Basis durchlaufen. Dies erfordert die erneute Überprüfung der im Bereich enthaltenen Steuerelemente für Ihre aktuelle Umgebung. Dieser Prozess kann bis zu 90 Tage vor Ablauf Ihrer Zertifizierung beginnen. Ihre vorhandene Zertifizierung läuft während des Zeitraums der erneuten Zertifizierung nicht ab. Die erneute Zertifizierung in allen Programmen läuft am einjährigen Jahrestag Ihrer Microsoft 365-Zertifizierung ab.

Wenn Ihre Zertifizierung nicht vor dem Ablaufdatum verlängert wird, wird ihr App-Zertifizierungsstatus widerrufen. Alle Fehlerhaften, Symbole und zugehörigen Zertifizierungsbrandings werden aus Ihrer App entfernt, und Sie dürfen Ihre App nicht als Microsoft 365 zertifiziert anzeigen.


> [!IMPORTANT]
> **Übermittlungszeitrahmen:** Es wird erwartet, dass der Bewertungsprozess im Durchschnitt 30 Tage dauern sollte, vorausgesetzt, Sie können Ihren Übermittlungsstatus häufig überprüfen und innerhalb einer zeitnahen Weise auf Kommentare und ergänzende Nachweise reagieren. Nach Beginn des Zertifizierungsprozesses ist es maximal 60 Tage zulässig, die Bewertung abzuschließen. Wenn nicht alle Übermittlungen innerhalb des Zeitraums von 60 Tagen abgeschlossen wurden, tritt bei der Übermittlung ein Fehler auf, und der Prozess muss erneut gestartet werden. Diese Ergebnisse werden nicht veröffentlicht.


## <a name="initial-document-submission"></a>Ursprüngliche Dokumentübermittlung

Die anfängliche Dokumentübermittlung hilft Zertifizierungsanalysten bei der Durchführung von Bereichsdefinitionen und bei der Bestimmung des Umfangs Ihrer Bewertung. Danach müssen Sie unterstützende Dokumentationen und Nachweise übermitteln, die zur Durchführung der Bewertung verwendet werden. Ihre anfängliche Übermittlung muss die unten angegebenen Informationen enthalten:

| **&nbsp;Dokumentationsübersicht**     |   **Dokumentationsdetails**  |
| -------------------------| -----------------------------|
|**App-/Add-In-Beschreibung** | Eine Beschreibung des Zwecks und der Funktionalität der App/des Add-Ins. Dies sollte dem Zertifizierungsanalysten ein gutes Verständnis darüber vermitteln, wie die App/das Add-In funktioniert und was sie verwenden soll.
|**Penetrationstestbericht** |Ein Penetrationstestbericht, der innerhalb der letzten 12 Monate abgeschlossen wurde. Dieser Bericht muss die Umgebung enthalten, die die Bereitstellung der App/des Add-Ins unterstützt, sowie alle zusätzlichen Umgebungen, die den Betrieb der App/des Add-Ins unterstützen. **Hinweis:** Wenn Sie keine jährlichen Penetrationstests durchführen, können Sie entscheiden, ob sie über den Zertifizierungsprozess durchgeführt werden sollen.|
|**Architekturdiagramme**|Ein logisches Architekturdiagramm, das eine allgemeine Übersicht über die unterstützende Infrastruktur Ihrer App/Ihres Add-Ins darstellt. Dies muss **alle** Hostingumgebungen und unterstützende Infrastruktur umfassen, die die App/das Add-In unterstützt. Dieses Diagramm MUSS alle verschiedenen unterstützenden Systemkomponenten innerhalb der Umgebung darstellen, damit Zertifizierungsanalysten die Systeme im Umfang verstehen und bei der Bestimmung des Samplings helfen können. Geben Sie außerdem an, welcher Hostingumgebungstyp verwendet wird. ISV hosted, IaaS, PaaS oder Hybrid. **Hinweis:** Wo SaaS verwendet wird, geben Sie bitte die verschiedenen SaaS-Dienste an, die verwendet werden, um die unterstützenden Dienste innerhalb der Umgebung bereitzustellen.|
|**Öffentlicher Speicherbedarf** | Ausführliche Informationen **zu allen** öffentlichen IP-Adressen und URLs, die von der unterstützenden Infrastruktur verwendet werden. Dies muss den vollständigen routingfähigen IP-Bereich enthalten, der der Umgebung zugeordnet ist, es sei denn, eine angemessene Segmentierung wurde implementiert, um den verwendeten Bereich aufzuteilen (es sind angemessene Nachweise für die Segmentierung erforderlich).|
|**Datenflussdiagramme** |Flow Diagramme, die Folgendes detailliert darstellen:
||&#x2713; M365-Daten fließt zu und aus der App/dem Add-In (einschließlich [EUII](#euii) und [OII).](#oii)|
||&#x2713; M365-Datenflüsse innerhalb der unterstützenden Infrastruktur (sofern zutreffend)|
||&#x2713; Diagramme, in denen hervorgehoben wird, wo und welche Daten gespeichert werden, wie Daten an externe Dritte übergeben werden (einschließlich Details zu dritten Parteien) und wie Daten während der Übertragung über offene/öffentliche Netzwerke und im Ruhezustand geschützt werden.|
|**API-Endpunktdetails**| Eine vollständige Liste aller API-Endpunkte, die von Ihrer App verwendet werden. Um den Umgebungsbereich besser verstehen zu können, stellen Sie API-Endpunktspeicherorte in Ihrer Umgebung bereit.                                
|**Microsoft-API-Berechtigungen**| Bereitstellen einer Dokumentation, in der **alle** Microsoft-APIs aufgeführt sind, die zusammen mit den berechtigungen verwendet werden, die für die Funktion der App/des Add-Ins angefordert werden, zusammen mit einer Begründung für die angeforderten Berechtigungen|
|**Datenspeichertypen** |Datenspeicherung und Umgang mit Dokumenten, die:|
||&#x2713; In welchem Umfang ihre Kunden M365 Data [EUII](#euii) und [OII](#oii) empfangen und gespeichert werden|
||&#x2713; Der Datenaufbewahrungszeitraum.|
||&#x2713;, warum die M365-Daten des Kunden erfasst werden.|
||&#x2713; Wo Kunden-M365-Daten gespeichert werden (sollten in den oben angegebenen Datenflussdiagrammen enthalten sein).|
|**Bestätigung der Compliance**|Unterstützende Dokumentation für externe Sicherheitsframeworks, die in der Publisher Übermittlung des Nachweiss enthalten sind oder bei der Überprüfung Microsoft 365 Zertifizierungskontrollen berücksichtigt werden müssen. Derzeit werden die folgenden drei unterstützt:|
||&#x2713; [PCI DSS](#pci-dss) Attestation of Compliance (AOC).|
||&#x2713; [SOC 2-Berichte](#soc-2) vom Typ I/Typ II.|
||&#x2713; [ISMS](#isms)  /  [IEC](#iec) - 1S0/IEC 27001 Statement of Applicability (SoA) and Certification.|
|**Webabhängigkeiten**|Dokumentation, in der alle Abhängigkeiten aufgeführt sind, die von der App/dem Add-In mit den aktuell ausgeführten Versionen verwendet werden.|
|**Softwareinventar**|Ein aktuelles Softwareinventar, das alle in der In-Scope-Umgebung verwendeten Software zusammen mit den Versionen enthält.|
|**Hardwareinventur**| Eine aktuelle Hardwareinventur, die von der unterstützenden Infrastruktur verwendet wird. Dies wird verwendet, um beim Sampling bei der Durchführung der Bewertungsphase zu helfen. Wenn Ihre Umgebung PaaS umfasst, stellen Sie Details zu den genutzten Diensten bereit.|

## <a name="evidence-collection-and-assessment-activities"></a>Aktivitäten zur Sammlung und Bewertung von Nachweisen

Zertifizierungsanalysten müssen Nachweise für alle Systemkomponenten innerhalb des definierten Beispielsatzes überprüfen. Zu den Nachweistypen, die zur Unterstützung des Bewertungsprozesses erforderlich sind, gehören eine oder alle der folgenden:

**Beweissammlung**

* Ursprüngliche Dokumentation, hervorgehoben im Abschnitt "Übermittlung der [ersten Dokumentation"](#initial-document-submission) oben 
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
* Screensharing 

Die verwendeten Techniken für die Beweissammlung werden während des Bewertungsprozesses bestimmt. 

**Bewertungsaktivitäten**

Zertifizierungsanalysten überprüfen die von Ihnen bereitgestellten Nachweise, um festzustellen, ob Sie die Kontrollen in dieser Microsoft 365 Zertifizierungsspezifikation ausreichend erfüllt haben. 

Wenn möglich, und um den Zeitaufwand für den Abschluss der Bewertung zu reduzieren, sollte eine oder alle der in der übermittlung der [anfänglichen Dokumentation](#initial-document-submission)aufgeführten Dokumentation   vorab bereitgestellt werden.

Zertifizierungsanalysten überprüfen zunächst die Nachweise aus der ersten Übermittlung der Dokumentation und die Publisher Nachweisinformationen, um geeignete Untersuchungslinien, Stichprobengröße und die Notwendigkeit weiterer Nachweise zu identifizieren, wie oben beschrieben.  Zertifizierungsanalysten analysieren alle gesammelten Informationen, um Schlussfolgerungen darüber zu ziehen, wie und ob Sie die Steuerelemente in dieser Microsoft 365 Zertifizierungsspezifikation erfüllen. 

## <a name="app-certification-criteria"></a>App-Zertifizierungskriterien

Ihre App, unterstützende Infrastruktur und unterstützende Dokumentation werden in den folgenden Sicherheitsdomänen bewertet:

1. [**Application Security**](#application-security)
1. [**Betriebssicherheit/sichere Bereitstellung**](#operational-security)
1. [**Sicherheit und Datenschutz bei der Datenverarbeitung**](#data-handling-security-and-privacy)

Jede dieser Sicherheitsdomänen enthält bestimmte Schlüsselsteuerelemente, die eine oder mehrere spezifische Anforderungen umfassen, die im Rahmen des Bewertungsprozesses ausgewertet werden. Um sicherzustellen, dass Microsoft 365 Zertifizierung für Entwickler aller Größen inklusiv ist, wird jede Sicherheitsdomäne mithilfe eines Bewertungssystems bewertet, um eine Gesamtbewertung aus jeder der Domänen zu ermitteln. Bewertungen für jedes der Microsoft 365 Zertifizierungssteuerelemente werden basierend auf dem wahrgenommenen Risiko, dass dieses Steuerelement nicht erfüllt wird, zwischen 1 (niedrig) und 3 (hoch) zugewiesen. Jede der Sicherheitsdomänen hat eine Mindestprozentsatzmarkierung, die als Bestanden betrachtet wird. Zu bestimmten Elementen dieser Spezifikation gehören einige kriterien für automatische Fehler:

- API-Berechtigungen, die nicht dem Prinzip der geringsten Rechte (Least Privilege, PoLP) folgen.  
- Kein Penetrationstestbericht, wenn er erforderlich ist.
- Keine Antischadsoftware-Abwehr
- Mehrstufige Authentifizierung wird nicht zum Schutz des Administrativen Zugriffs verwendet.  
- Keine Patchingprozesse.  
- Kein geeigneter [DSGVO-Datenschutzhinweis.](#gdpr)  

## <a name="application-security"></a>Application Security

Die Anwendungssicherheitsdomäne konzentriert sich auf die folgenden drei Bereiche: 
* GraphAPI-Berechtigungsüberprüfung 
* Externe Konnektivitätsprüfungen
* Anwendungssicherheitstests 

### <a name="graphapi-permission-validation"></a>GraphAPI-Berechtigungsüberprüfung

Die GraphAPI-Berechtigungsüberprüfung wird durchgeführt, um zu überprüfen, ob die App/das Add-In nicht übermäßig eingeschränkte Berechtigungen anfordert. Dazu wird manuell überprüft, welche Berechtigungen angefordert werden. Zertifizierungsanalysten verweisen auf diese Überprüfungen mit der übermittlung Publisher Nachweis und bewerten die Zugriffsebene, die angefordert wird, um sicherzustellen, dass die Praktiken mit den geringsten Rechten erfüllt werden. Wenn Zertifizierungsanalysten der Meinung sind, dass diese "geringsten Rechte" nicht erfüllt werden, werden Zertifizierungsanalysten eine offene Diskussion mit Ihnen führen, um die geschäftliche Begründung für die angeforderten Berechtigungen zu überprüfen. Alle Abweichungen zu Ihrer Publisher Übermittlung des Nachweiss, die während dieser Überprüfung gefunden wurde, erhalten auch Feedback, damit Ihr Publisher Nachweis aktualisiert werden kann. 

### <a name="external-connectivity-checks"></a>Externe Konnektivitätsprüfungen

Im Rahmen der Bewertung führt ein Analyst einen einfachen Überblick über die Anwendungsfunktionalität durch, um Verbindungen außerhalb von M365 zu identifizieren.  Alle Verbindungen, die nicht als Microsoft oder direkte Verbindungen mit Ihrem Dienst identifiziert werden, werden während der Bewertung gekennzeichnet und besprochen.

### <a name="application-security-testing"></a>Anwendungssicherheitstests

Eine angemessene Überprüfung der mit Ihrer App/Ihrem Add-In verbundenen Risiken und der unterstützenden Umgebung ist wichtig, um Kunden die Sicherheit der App/des Add-Ins zu gewährleisten. Anwendungssicherheitstests in Form von Penetrationstests MÜSSEN durchgeführt werden, wenn Ihre Anwendung eine Verbindung mit einem Dienst hat, der nicht von Microsoft veröffentlicht wurde. Wenn Ihre App eigenständig ohne Konnektivität mit einem Anderen als Microsoft-Dienst oder Back-End ausgeführt wird, sind keine Penetrationstests erforderlich.


**Penetrationstests – Bereich**

Penetrationstestaktivitäten **MÜSSEN** die Umgebung umfassen, die die Bereitstellung der App/des Add-Ins unterstützt (z. B. wo der App-/Add-In-Code gehostet wird, bei dem es sich in der Regel um die Ressource in der Manifestdatei handelt) sowie alle zusätzlichen Umgebungen, die den Betrieb der App/des Add-Ins unterstützen (z. B. wenn die App/das Add-In mit anderen Webanwendungen außerhalb von Microsoft 365 spricht).  Bei der Definition des Bereichs muss darauf geachtet werden, dass alle "verbundenen" Systeme oder Umgebungen, die sich auf die Sicherheit der bereichsbezogenen Umgebung auswirken können, auch in alle Penetrationstestaktivitäten einbezogen werden. 

Wo Techniken verwendet werden, um die in-Scope-Umgebungen aus anderen Umgebungen zu segmentieren, MÜSSEN Penetrationstestaktivitäten die Effektivität dieser Segmentierungstechniken überprüfen. Dies muss im Penetrationstestbericht detailliert sein. 

Penetrationstestberichte werden überprüft, um sicherzustellen, dass keine Sicherheitsrisiken vorhanden sind, die die folgenden kriterien für **automatische Fehler** erfüllen, die in den folgenden Steuerelementen beschrieben sind.
 
**Anforderungen für Penetrationstests**

||**Penetrationsteststeuerelemente**|
| -------------------------|-----------------------------|
|**Allgemeine Kriterien**| **Controls**|
|| Anwendungs- und Infrastruktur-Penetrationstests **MÜSSEN** jährlich (alle 12 Monate) stattfinden und von einem unabhängigen Unternehmen durchgeführt werden. |
|| Die Behebung von identifizierten kritischen und risikoreichen Sicherheitsrisiken **MUSS** innerhalb eines Monats nach Abschluss der Penetrationstests abgeschlossen sein, oder je nach dokumentierten Patchingprozess früher. |
|| Der vollständige externe Speicherbedarf (IP-Adressen, URLs, API-Endpunkte usw.) MUSS in den Umfang der Penetrationstests einbezogen werden und muss im Penetrationstestbericht dokumentiert werden. |
|| Penetrationstests für Webanwendungen MÜSSEN alle Sicherheitsrisikoklassen enthalten. Beispielsweise die aktuelle OWASP Top 10 oder SANS Top 25 CWE. |
|| Eine erneute Überprüfung der identifizierten Sicherheitsrisiken durch das Penetrationstestunternehmen ist nicht erforderlich . Korrektur und Selbstüberprüfung sind jedoch ausreichend, um zu belegen, dass während der Bewertung ausreichend **Abhilfe** erforderlich ist.|
|**Kriterien für automatische Fehler:**|**Controls**|
|| Vorhandensein eines nicht unterstützten Betriebssystems. |
|| Vorhandensein von standardmäßigen, aufzählbaren oder erratenen Administratorkonten.|
|| Vorhandensein SQL Risiken bei der Einschleusung.|
|| Vorhandensein von websiteübergreifendem Skripting.|
|| Vorhandensein von Verzeichnisdurchquerungsrisiken (Dateipfad).|
|| Vorhandensein von HTTP-Sicherheitsrisiken, z. B. Header-Antwortteilung, Anforderungsaussetzung und Desync-Angriffe.|
|| Vorhandensein der Offenlegung des Quellcodes (einschließlich [LFI).](#lfi)|
|| Alle kritischen oder hohen Bewertungen gemäß den CVSS-Patchverwaltungsrichtlinien.|
|| Jede erhebliche technische Sicherheitslücke, die leicht ausgenutzt werden kann, um eine große Menge von EUII oder OUI zu kompromittieren.|






> [!IMPORTANT]
>Berichte müssen in der Lage sein, genügend Sicherheit zu bieten, dass alles, was im Abschnitt "Anwendungssicherheitstestspezifikation" beschrieben wird, veranschaulicht werden kann.


**Anforderungen und Kosten für Penetrationstests**

Für ISVs, die derzeit keine Penetrationstests durchführen, sind Penetrationstests in der Microsoft 365 Zertifizierung enthalten. Microsoft wird die Kosten für einen Penetrationstest für bis zu 12 Tage manueller Tests anordnen und übernehmen. Die Kosten für Penetrationstests werden basierend auf der Anzahl der Tage berechnet, die zum Testen der Umgebung erforderlich sind. Alle Ausgaben, die 12 Testtage überschreiten, liegen in der Verantwortung des ISV. Der ISV ist auch für den Nachweis verantwortlich, dass die im Penetrationstest identifizierten Sicherheitsrisiken vor der Zertifizierung behoben wurden, aber keinen sauberen Bericht erstellen müssen.

Sobald ein Penetrationstest eingerichtet wurde, ist der ISV für gebührenpflichtige Umplanungen und Stornierungen wie folgt verantwortlich:

| **Neuplanung der Gebührenzeitskala** | **Anteilszahlbar** |
|------------------|------------------------|
| Anforderung erneut planen, die mehr als 30 Tage vor dem geplanten Startdatum empfangen wurde. | 0 % Fällig |
| Anforderung erneut planen, die 8 bis 30 Tage vor dem geplanten Startdatum empfangen wurde. | 25 % Fällig |
| Erneutes Planen der Anforderung, die innerhalb von 2 bis 7 Tagen vor dem geplanten Startdatum mit einem festen Neubuchungsdatum eingegangen ist.| 50 % Fällig |
| Anforderung neu planen, die weniger als 2 Tage vor dem Startdatum empfangen wurde. | 100 % Fällig |

| **Stornierungsgebühr – Zeitskala** | **Anteilszahlbar** |
|------------------|------------------------|
| Die Abbruchanforderung wurde mehr als 30 Tage vor dem geplanten Startdatum empfangen. | 25 % Fällig |
| Die Abbruchanforderung wurde 8 bis 30 Tage vor dem geplanten Startdatum empfangen. | 50 % Fällig |
| Abbruchanforderung, die innerhalb von 7 Tagen vor dem geplanten Startdatum eingegangen ist. | 90 % Fällig |

## <a name="operational-security"></a>Betriebssicherheit

Diese Domäne misst die Ausrichtung der unterstützenden Infrastruktur und Bereitstellungsprozesse Ihrer App mit bewährten Methoden für die Sicherheit.

### <a name="controls"></a>Steuerelemente

|**Steuerelementfamilie**| **Controls**|
| ------------------------|------------------------------ |
| **Schutz vor Schadsoftware**|Bereitstellen von Richtliniendokumentationen, die Antivirenmethoden und -verfahren regeln.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass Antivirensoftware in allen beispielbasierten Systemkomponenten ausgeführt wird.|
||Liefern Sie demonstratablen Nachweis, dass Antivirensignaturen in allen Umgebungen (innerhalb von 1 Tag) auf dem neuesten Stand sind.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass Antivirensoftware so konfiguriert ist, dass Bei-Zugriff-Scans oder regelmäßige Überprüfungen für alle stichprobenbasierten Systemkomponenten durchgeführt werden. Hinweis: Wenn die Überprüfung bei Zugriff nicht aktiviert ist, muss mindestens die tägliche Überprüfung und Warnung aktiviert sein.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass Antivirensoftware so konfiguriert ist, dass Schadsoftware automatisch blockiert oder isoliert wird und warnungsübergreifend in allen beispielierten Systemkomponenten angezeigt wird.|
|**Anwendungssteuerelemente:** NUR erforderlich, wenn herkömmliche Antischadsoftware nicht verwendet wird|Stellen Sie demonstratable Nachweise dafür bereit, dass Anwendungen vor der Bereitstellung genehmigt werden.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass eine vollständige Liste genehmigter Anwendungen mit geschäftlicher Begründung vorhanden ist und beibehalten wird.|
||Stellen Sie unterstützende Dokumentation bereit, in der angegeben wird, dass die Anwendungsteuerungssoftware so konfiguriert ist, dass sie bestimmten Anwendungssteuerungsmechanismen entspricht. (Beispiel: Zugelassene Auflistung: Sample1, Sample3, Codesignatur)|
||Liefern Sie demonstratablen Nachweis, dass die Anwendungssteuerung als dokumentiert von allen beispielierten Systemkomponenten konfiguriert ist.|
|**Patchverwaltung – Risikobewertung**| Bereitstellen einer Richtliniendokumentation, die bestimmt, wie neue Sicherheitsrisiken identifiziert und einer Risikobewertung zugewiesen werden.|
||Bereitstellen von Nachweisen dafür, wie neue Sicherheitsrisiken identifiziert werden.|
||Stellen Sie Nachweise bereit, die belegen, dass allen Sicherheitsrisiken eine Risikorangfolge zugewiesen wurde, sobald sie identifiziert wurde.|
|**Patch Managmeent – Patching**|Bereitstellen einer Richtliniendokumentation für das Patchen von systeminternen Komponenten, die einen geeigneten minimalen Patching-Zeitrahmen für kritische, hohe und mittlere Sicherheitsrisiken enthält. und Außerbetriebnahme von nicht unterstützten Betriebssystemen und Software.|
||Liefern Sie demonstratablen Nachweis, dass alle stichprobenierten Systemkomponenten gepatcht werden.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass nicht unterstützte Betriebssysteme und Softwarekomponenten in der Umgebung nicht verwendet werden.|
|**Überprüfung von Sicherheitsrisiken**|Bereitstellen der vierteljährlichen Berichte zur Überprüfung von Infrastruktur- und Webanwendungsrisiken. Die Überprüfung muss auf den gesamten öffentlichen Speicherbedarf (IP-Adressen und URLs) und interne IP-Bereiche durchgeführt werden.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass die Behebung von Sicherheitsrisiken, die während der Überprüfung auf Sicherheitslücken erkannt wurden, in Übereinstimmung mit Ihrem dokumentierten Patching-Zeitrahmen gepatcht wird.|
|**Firewalls**|Bereitstellen von Richtliniendokumentation, die Die Methoden und Verfahren für die Firewallverwaltung regelt.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass alle standardmäßigen administrativen Anmeldeinformationen vor der Installation in Produktionsumgebungen geändert werden.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass Firewalls an der Begrenzung der Bereichsumgebung installiert und zwischen dem Umkreisnetzwerk (auch als DMZ, demilitarisierte Zone und überprüftes Subnetz bezeichnet) und internen vertrauenswürdigen Netzwerken installiert werden.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass der gesamte öffentliche Zugriff in der demilitarisierten Zone (DMZ) beendet wird.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass der gesamte über die Firewall zulässige Datenverkehr einen Genehmigungsprozess durchläuft.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass die Firewallregelbasis so konfiguriert ist, dass Datenverkehr nicht explizit definiert wird.|
||Liefern Sie nachweisbare Nachweise dafür, dass die Firewall nur starke Kryptografie auf allen administrativen Schnittstellen unterstützt, die keine Konsole sind.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass Sie firewallregelüberprüfungen mindestens alle 6 Monate durchführen.|
|**Webanwendungsfirewall (WAF) (OPTIONAL):** Zusätzliche Gutschriften werden für die Erfüllung der folgenden Steuerelemente honoriert.|Stellen Sie demonstratable Nachweise dafür bereit, dass die Webanwendungsfirewall (Web Application Firewall, WAF) so konfiguriert ist, dass schädlicher Datenverkehr aktiv überwacht, benachrichtigt und blockiert wird.|
||Liefern Sie nachweisbare Nachweise dafür, dass die WAF ssl-Offloading unterstützt.|
||Bereitstellen demonstratabler Nachweise, dass die WAF vor einigen oder allen der folgenden Klassen von Sicherheitsrisiken gemäß dem OWASP Core Rule Set (3.0 oder 3.1) schützt |
|**Änderungssteuerung**|Bereitstellen von Richtliniendokumentation, die Änderungskontrollprozesse steuert.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass Entwicklungs- und Testumgebungen eine Aufgabentrennung von der Produktionsumgebung erzwingen.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass vertrauliche Produktionsdaten in entwicklungs- oder Testumgebungen nicht verwendet werden.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass dokumentierte Änderungsanforderungen Auswirkungen der Änderung, Details zu Back-Out-Verfahren und durchzuführende Tests enthalten.|
||Stellen Sie demonstratable Nachweise bereit, dass Änderungsanforderungen einem Autorisierungs- und Abmeldeprozess unterzogen werden.|
|**Sichere Softwareentwicklung/Bereitstellung**| Bereitstellen von Richtlinien und Verfahren, die sichere Softwareentwicklung und -bereitstellung unterstützen, einschließlich Bewährter Methoden für sicheres Codieren für allgemeine Sicherheitsrisikoklassen wie OWASP Top 10 oder SANS Top 25 CWE.|
|| Stellen Sie demonstratable Nachweise dafür bereit, dass Codeänderungen einem Überprüfungs- und Autorisierungsprozess durch einen zweiten Prüfer unterzogen werden.|
|| Stellen Sie demonstratable Nachweise dafür bereit, dass Entwickler jährlich eine sichere Schulung zur Softwareentwicklung durchführen.|
|| Stellen Sie demonstratable Nachweise dafür bereit, dass Coderepositorys mit mehrstufiger Authentifizierung (MFA) gesichert sind.|
|| Stellen Sie demonstratable Nachweise dafür bereit, dass Zugriffssteuerungen vorhanden sind, um Coderepositorys zu sichern.
|**Kontoverwaltung**| Bereitstellen von Richtliniendokumentationen, die kontoverwaltungspraktiken und -verfahren regeln.
||Stellen Sie demonstratable Nachweise dafür bereit, dass Standardanmeldeinformationen in den beispielierten Systemkomponenten deaktiviert, entfernt oder geändert werden.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass die Kontoerstellung, -änderung und -löschung einen etablierten Genehmigungsprozess durchläuft.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass ein Prozess zum Deaktivieren oder Löschen von Konten vorhanden ist, die nicht innerhalb von 3 Monaten verwendet werden.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass eine Richtlinie für sichere Kennwörter oder andere geeignete Gegenmaßnahmen zum Schutz von Benutzeranmeldeinformationen vorhanden sind.  Als Mindestrichtlinie sollte Folgendes verwendet werden: Mindestlänge des Kennworts von 8 Zeichen, Kontosperrschwellenwert von höchstens 10 Versuchen, Kennwortverlauf von mindestens 5 Kennwörtern, Erzwingung der Verwendung von sicherem Kennwort|
|**Angriffserkennung und -verhinderung (OPTIONAL):** Zusätzliche Gutschriften werden für die Erfüllung der folgenden Steuerelemente honoriert.|Stellen Sie demonstratable Nachweise dafür bereit, dass Eindringerkennungs- und Verhinderungssysteme (Intrusion Detection and Prevention Systems, IDPS) am Umkreis der In-Scope-Umgebungen bereitgestellt werden.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass IDPS-Signaturen (innerhalb von 24 Stunden) auf dem aktuellen Stand gehalten werden.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass IDPS so konfiguriert ist, dass die TLS-Überprüfung des gesamten eingehenden Webdatenverkehrs unterstützt wird.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass IDPS so konfiguriert ist, dass alle eingehenden Datenverkehrsflüsse überwacht werden.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass IDPS so konfiguriert ist, dass alle ausgehenden Datenverkehrsflüsse überwacht werden.|
|**Protokollierung von Sicherheitsereignissen** |Bereitstellen einer Richtliniendokumentation für bewährte Methoden und Verfahren zur Steuerung der Protokollierung von Sicherheitsereignissen.|
|| Bereitstellen demonstratabler Nachweise, die zeigen, dass die Protokollierung von Sicherheitsereignissen in allen beispielierten Systemkomponenten eingerichtet ist, um die folgenden Ereignisse zu protokollieren: Benutzerzugriff auf Systemkomponenten und die Anwendung, alle Aktionen, die von einem Benutzer mit hohen Rechten ausgeführt werden, ungültiger logischer Zugriff versucht, privilegiertes Konto zu erstellen oder zu ändern, Ereignisprotokollmanipulation, Deaktivierung von Sicherheitstools (z. B. Antischadsoftware oder Ereignisprotokollierung),  Antischadsoftwareprotokollierung (z. B. Updates, Schadsoftwareerkennung und Scanfehler).,IDPS- und WAF-Ereignisse, falls konfiguriert|
||Stellen Sie demonstratable Nachweise bereit, dass protokollierte Sicherheitsereignisse die folgenden Mindestinformationen enthalten: Benutzer, Ereignistyp, Datum und Uhrzeit, Erfolgs- oder Fehlerindikatoren, Bezeichnung, die das betroffene System identifiziert|
||Stellen Sie demonstratable Nachweise dafür bereit, dass alle beispielierten Systemkomponenten zeitsynchron mit denselben primären und sekundären Servern synchronisiert sind.|
||Stellen Sie demonstratable Nachweise bereit, wenn öffentlich zugängliche Systeme verwendet werden, dass Sicherheitsereignisprotokolle an eine zentrale Protokollierungslösung gesendet werden, die sich nicht im Umkreisnetzwerk befindet.|
||Stellen Sie nachweisbare Nachweise bereit, um nachzuweisen, dass die zentrale Protokollierungslösung vor unbefugter Manipulation von Protokollierungsdaten geschützt ist.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass mindestens 30 Tage an Daten zur Protokollierung von Sicherheitsereignissen sofort verfügbar sind, wobei 90 Tage lang Sicherheitsereignisprotokolle aufbewahrt werden.|
|**Überprüfen (Protokolldaten)** |Bereitstellen einer Richtliniendokumentation, die die Verfahren und Verfahren für die Protokollüberprüfung regelt.|
||Liefern Sie nachweisbare Nachweise dafür, dass Protokolle täglich von einem menschlichen oder automatisierten Tool überprüft werden, um potenzielle Sicherheitsereignisse zu identifizieren.|
||Liefern Sie nachweisbare Nachweise dafür, dass potenzielle Sicherheitsereignisse und Anomalien untersucht und behoben werden.|
|**Alarmierung** | Bereitstellen von Richtliniendokumentation, die Die Praktiken und Verfahren zur Warnung von Sicherheitsereignissen regelt.|
|| Stellen Sie nachweisbare Nachweise dafür bereit, dass Warnungen für die sofortige Triage für die folgenden Arten von Sicherheitsereignissen ausgelöst werden: Erstellen oder Ändern eines privilegierten Kontos, Viren- oder Schadsoftwareereignisse, Ereignisprotokollmanipulation, IDPS- oder WAF-Ereignisse
|**Risikomanagement**|Stellen Sie demonstratable Nachweise dafür bereit, dass ein formaler Risikomanagementprozess für die Informationssicherheit eingerichtet wurde.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass mindestens jährlich eine formale Risikobewertung stattfindet.|
||Liefern Sie nachweisbare Nachweise dafür, dass die Risikobewertung zur Informationssicherheit Bedrohungen, Sicherheitsrisiken oder die entsprechende Bedrohungen umfasst.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass die Risikobewertung zur Informationssicherheit auswirkungen, eine Wahrscheinlichkeitsrisikomatrix oder ein entsprechendes Risiko umfasst.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass die Risikobewertung zur Informationssicherheit ein Risikoregister und einen Behandlungsplan umfasst.|
|**Reaktion auf Sicherheitsvorfälle**|Bereitstellen des Plans zur Reaktion auf Sicherheitsvorfälle (Security Incident Response Plan, IRP).|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass die Sicherheits-IRP einen dokumentierten Kommunikationsprozess umfasst, um eine zeitnahe Benachrichtigung an wichtige Interessengruppen wie Zahlungsmarken und Acquirer, Aufsichtsbehörden, Aufsichtsbehörden, Directors und Kunden sicherzustellen.|
||Stellen Sie nachweisbare Nachweise dafür bereit, dass alle Mitglieder des Vorfallreaktionsteams eine jährliche Schulung oder eine Übung auf der Obersten Tabelle abgeschlossen haben.|
||Stellen Sie nachweisbare Nachweise bereit, um zu zeigen, dass die Sicherheits-IRP basierend auf den gewonnenen Erkenntnissen oder organisatorischen Änderungen aktualisiert wird.|

## <a name="data-handling-security-and-privacy"></a>Sicherheit und Datenschutz bei der Datenverarbeitung

Daten, die sich während der Übertragung zwischen dem Anwendungsbenutzer, zwischengeschalteten Diensten und ISV-Systemen befinden, müssen durch Verschlüsselung über eine TLS-Verbindung geschützt werden, die mindestens TLS v1.1 unterstützt. *Siehe* [**Anhang A.**](#appendix-a)

Wo Ihre Anwendung M365-Daten abruft und speichert, müssen Sie ein Verschlüsselungsschema für den Datenspeicher implementieren, das der Spezifikation gemäß [**Anhang B**](#appendix-a)folgt.

### <a name="controls"></a>Steuerelemente

|**Steuerelementfamilie**| **Controls** |
| -----------------------|-------------------------------- |
|**Daten während der Übertragung**| Bereitstellen von demonstratablen Nachweisen, dass die TLS-Konfiguration die Verschlüsselungsanforderungen innerhalb der [TLS-Profilkonfigurationsanforderungen](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide#appendix-a) erfüllt oder überschreitet|
||Stellen Sie demonstratable Nachweise dafür bereit, dass die TLS-Komprimierung für alle öffentlich zugänglichen Dienste deaktiviert ist, die Webanforderungen verarbeiten.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass tls http strict transport security aktiviert und für >= 15552000 für alle Standorte konfiguriert ist.|
|**Daten im Ruhezustand**| Stellen Sie demonstratable Nachweise dafür bereit, dass ruhenden Daten inLine mit den Anforderungen an das Verschlüsselungsprofil verschlüsselt werden, indem Sie Verschlüsselungsalgorithmen wie AES, Auslöschung, TDES und Verschlüsselungsschlüsselgrößen von 128-Bit und 256-Bit verwenden.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass die Hashfunktion oder Nachrichtenauthentifizierung (HMAC-SHA1) nur verwendet wird, um ruhenden Daten inLine mit den Anforderungen des Verschlüsselungsprofils zu schützen.|
||Bereitstellen eines Inventars mit allen gespeicherten Daten, einschließlich Speicherort und Verschlüsselung, die zum Schutz der Daten verwendet werden.|
|**Datenaufbewahrung und -entsorgung**|Stellen Sie demonstratable Nachweise dafür bereit, dass ein genehmigter und dokumentierter Datenaufbewahrungszeitraum formell eingerichtet wurde.|
||Bereitstellen von demonstratablen Nachweisen, dass aufbewahrte Daten mit dem definierten Aufbewahrungszeitraum übereinstimmen.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass Prozesse vorhanden sind, um Daten nach dem Aufbewahrungszeitraum sicher zu löschen.|
|**Datenzugriffsverwaltung**|Stellen Sie eine Liste aller Personen mit Zugriff auf Daten oder Verschlüsselungsschlüssel bereit, einschließlich der geschäftlichen Begründung.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass die stichprobenierten Personen, die Zugriff auf Daten oder Verschlüsselungsschlüssel haben, formell genehmigt wurden, und geben Sie dabei die für ihre Auftragsfunktion erforderlichen Rechte an.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass die stichprobenierten Personen, die Zugriff auf Daten oder Verschlüsselungsschlüssel haben, nur über die in der Genehmigung enthaltenen Berechtigungen verfügen.|
||Stellen Sie eine Liste aller Drittanbieter bereit, für die Kundendaten freigegeben werden.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass alle Drittanbieter, die Kundendaten verwenden, Freigabevereinbarungen bestehen.|
|**DSGVO** (falls zutreffend)| Stellen Sie einen Sar-Prozess (Documented Subject Access Request) bereit und stellen Sie Nachweise bereit, die belegen, dass betroffene Personen in der Lage sind, SARs auszulösen.|
||Stellen Sie demonstratable Nachweise dafür bereit, dass Sie alle Speicherorte der Daten der betroffenen Personen identifizieren können, wenn Sie auf eine SAR reagieren.|
||Sie erhalten einen Datenschutzhinweis, der die Unternehmensdetails (Name, Adresse usw.) enthalten sollte.|
||Sie pflegen einen Datenschutzhinweis, der die Arten von personenbezogenen Daten, die verarbeitet werden, erläutern sollte.|
||Sie pflegen einen Datenschutzhinweis, der die Rechtmäßigkeit der Verarbeitung personenbezogener Daten erläutern sollte.|
||Sie pflegen einen Datenschutzhinweis, in dem die Rechte der betroffenen Person ausführlich erläutert werden: Recht auf Information, Recht auf Zugriff durch die betroffene Person, Recht auf Löschung, Recht auf Einschränkung der Verarbeitung, Recht auf Datenübertragbarkeit, Recht auf Auskunft, Rechte in Bezug auf automatisierte Entscheidungsfindung, einschließlich Profilerstellung.|
|| Sie erhalten einen Datenschutzhinweis, in dem erläutert werden sollte, wie lange personenbezogene Daten aufbewahrt werden.|

## <a name="optional-external-compliance-frameworks-review"></a>Optionale Überprüfung externer Compliance-Frameworks

Obwohl dies nicht erforderlich ist, können Sie, wenn Sie derzeit iso 27001, PCI DSS oder SOC2 entsprechen, diese Zertifizierungen verwenden, um einige der Microsoft 365 Zertifizierungssteuerelemente zu erfüllen. Zertifizierungsanalysten werden versuchen, vorhandene externe Sicherheitsframeworks an die Spezifikation Microsoft 365 Zertifizierung anzupassen. Wenn die unterstützende Dokumentation jedoch nicht sicherstellen kann, dass Microsoft 365 Zertifizierungskontrollen im Rahmen der Prüfung/Bewertung der externen Sicherheitsframeworks bewertet wurden, müssen Sie zusätzliche Nachweise dafür bereitstellen, dass die genannten Steuerelemente vorhanden sind.

Die Dokumentation muss angemessen belegen, dass die bereichsbezogene Umgebung für die Microsoft 365 Zertifizierung in den Bereich dieser externen Sicherheitsframeworks einbezogen wurde. Die Validierung dieser Sicherheitsframeworks wird erfüllt, indem der Nachweis gültiger Zertifizierungen durch seriöse externe Drittanbieter akzeptiert wird. Diese seriösen Unternehmen müssen Mitglieder internationaler Akkreditierungsstellen für relevante Complianceprogramme sein. Siehe ISO-Zertifizierungs- und -Konformitätsstandards für ISO 27001 und Qualified Security Assessors (QSA) für PCI DSS.

In der folgenden Tabelle werden die externen Frameworks und dokumentationen hervorgehoben, die von Zertifizierungsanalysten im Rahmen dieses Überprüfungsprozesses benötigt werden:

| **Standard** | **Anforderungen** |
| ----- | ----- |
| **[ISO 27001](#iso-27001)** | Eine öffentlich zugängliche Version der Erklärung zur Anwendbarkeit (Statement **of Applicability,** SOA) und eine Kopie des ausgestellten ISO 27001-Zertifikats sind erforderlich.  Das SOA fasst Ihre Position zu den einzelnen 114 Informationssicherheitssteuerelementen zusammen und wird verwendet, um festzustellen, ob ein Ausschluss von Steuerelementen, die nicht zufriedenstellend im ISO 27001-Zertifikat aufgeführt sind, ausgeschlossen wird. Wenn dies nicht durch Die Überprüfung der öffentlich zugänglichen Version des SOA ermittelt werden kann, benötigt der Analyst möglicherweise Zugriff auf das vollständige SOA, wenn ISO 27001 verwendet wird, um einige der steuerelemente Microsoft 365 Zertifizierungsspezifikation zu überprüfen.  Zusätzlich zur Überprüfung des Umfangs der ISO 27001-Bewertungsaktivitäten bestätigen die Analysten auch die Gültigkeit des Prüfungsunternehmens, wie oben beschrieben.|
|**[PCI/DSS](#pci-dss)**| Es muss ein gültiges AOC-Dokument **(Attestation of Compliance)** der Stufe 1 bereitgestellt werden, in dem die bereichsbezogenen Anwendungs- und Systemkomponenten eindeutig identifiziert werden.  Ein Selbstbewertungs-AOC **wird nicht** als Nachweis für bewährte Methoden für die Sicherheit akzeptiert. Der AOC wird verwendet, um zu bestimmen, welche der Microsoft 365 Zertifizierungsspezifikationssteuerelemente im Rahmen der PCI DSS-Bewertung ausgewertet und bestätigt wurden.|
|**[SOC 2](#soc-2)**|Der **BERICHT SOC 2 (Typ I oder Typ II)** muss aktuell sein (innerhalb der letzten 15 Monate ausgestellt und der deklarierte Zeitraum innerhalb der letzten 27 Monate begonnen), um als Nachweis für die Übereinstimmung mit den Bewertungssteuerelementen in dieser Microsoft 365 Zertifizierungsspezifikation verwendet zu werden.|

Wenn externe Sicherheitsframeworks in den Publisher Attestation aufgenommen wurden, müssen Zertifizierungsanalysten die Gültigkeit dieser Sicherheitscompliance-Frameworks im Rahmen der Microsoft 365 Zertifizierungsbewertung überprüfen.

|**Framework** | **Weitere Überlegungen** |
|-------------- | --------------------|
|ISO 27001| [**Anhang C:**](#appendix-c)Nachweissammlung – Deltas für ISO 27001.|
|PCI/DSS | [**Anhang D:**](#appendix-d)Nachweissammlung – Deltas für PCI DSS.|
|SOC 2| [**Anhang E:**](#appendix-e)Nachweissammlung – Deltas für SOC 2.|

> [!NOTE]
> Obwohl die oben genannten externen Sicherheitsstandards/-frameworks als Nachweis übermittelt werden können, um einige der Microsoft 365 Zertifizierungskontrollen zu erfüllen, bedeutet das Bestehen der Microsoft 365 Zertifizierung nicht, dass Sie erfolgreich eine Prüfung anhand dieser Standards/Frameworks bestehen. Die Microsoft 365-Zertifizierungsspezifikation ist nur eine kleine Teilmenge dieser Sicherheitsstandards/-frameworks, die es Microsoft ermöglichen, ein Maß an Sicherheit in Bezug auf Ihren Sicherheitsstatus zu erhalten.


### <a name="requirements-to-use-external-compliance-frameworks"></a>Anforderungen für die Verwendung externer Compliance-Frameworks

&#x2713; Die unterstützende App/Add-In-Umgebung **und** alle unterstützenden Geschäftsprozesse **MÜSSEN** in den Umfang der unterstützten externen Sicherheitscomplianceframeworks einbezogen werden und müssen in der bereitgestellten Dokumentation eindeutig angegeben werden.

&#x2713; Unterstützte externe Sicherheitscompliance-Frameworks **MÜSSEN** aktuell sein, d. h. innerhalb der letzten 12 Monate (oder innerhalb von 15 Monaten, wenn die erneute Bewertung derzeit durchgeführt wird und Nachweise bereitgestellt werden können).

&#x2713; Unterstützte externe Sicherheitscompliance-Frameworks **MÜSSEN** von einem unabhängigen akkreditierten Unternehmen durchgeführt werden.

## <a name="appendix-a"></a>Anhang A

### <a name="tls-profile-configuration-requirements"></a>TLS-Profilkonfigurationsanforderungen

Der gesamte Netzwerkdatenverkehr, sei es innerhalb eines virtuellen Netzwerks, Clouddiensts oder Rechenzentrums, muss mit mindestens TLS v1.1 (TLS v1.2+ wird empfohlen) oder einem anderen anwendbaren Protokoll geschützt werden. Ausnahmen von dieser Anforderung sind:

* **HTTP-to-HTTPS-Umleitung**. Ihre App kann über HTTP antworten, um Clients zu HTTPS umzuleiten, aber die Antwort darf keine vertraulichen Daten (Cookies, Header, Inhalte) enthalten. Außer Umleitungen zu HTTPS und Antworten auf Integritätsteste sind keine anderen HTTP-Antworten zulässig. Siehe unten.
* **Integritätstests**. Ihre App kann nur dann auf Integritätsprüfungen über HTTP **reagieren, wenn** HTTPS-Integritätstests von der Überprüfungspartei nicht unterstützt werden.
* **Zertifikatzugriff**. Der Zugriff auf CRL-, OCSP- und AIA-Endpunkte zum Zweck der Zertifikatüberprüfung und Sperrüberprüfung ist über HTTP zulässig.
* **Lokale Kommunikation**. Ihre App kann HTTP (oder andere nicht geschützte Protokolle) für Kommunikationen verwenden, die das Betriebssystem nicht verlassen, z. B. g. Herstellen einer Verbindung mit einem Webserverendpunkt, der auf localhost verfügbar gemacht wird.

TLS-Komprimierung **MUSS** deaktiviert sein.

## <a name="appendix-b"></a>Anhang B

### <a name="encryption-profile-configuration-requirements"></a>Konfigurationsanforderungen für Verschlüsselungsprofile

Nur kryptografische Grundtypen und Parameter sind wie folgt zulässig:

### <a name="symmetric-cryptography"></a>Symmetrische Kryptografie

**Verschlüsselung**

&emsp;&#x2713; sind nur AES, BitLocker, Ransom oder TDES zulässig. Alle unterstützten Tastenlängen >=128 sind zulässig (128, 192 und 256 Bit) und können verwendet werden (256-Bit-Schlüssel werden empfohlen).

&emsp;&#x2713; Nur CBC-Modus ist zulässig. Jeder Verschlüsselungsvorgang muss einen neuen, zufällig generierten Initialisierungsvektor (IV) verwenden.

&emsp;&#x2713; Die Verwendung von Datenstromchiffren, z. B. RC4, **ist NICHT** zulässig.

**Hashfunktionen**

&emsp;&#x2713; Der gesamte neue Code muss SHA-256, SHA-384 oder SHA-512 (zusammenfassend als SHA-2 bezeichnet) verwenden. Die Ausgabe kann auf nicht weniger als 128 Bit gekürzt werden.

&emsp;&#x2713; SHA-1 kann nur aus Kompatibilitätsgründen verwendet werden.

&emsp;&#x2713; Verwendung von MD5, MD4, MD2 und anderen Hashfunktionen IST NICHT zulässig, auch nicht für nicht kryptografische Anwendungen.

**Nachrichtenauthentifizierung**

&emsp;&#x2713; Der gesamte neue Code MUSS HMAC mit einer der genehmigten Hashfunktionen verwenden. Die Ausgabe von HMAC kann auf nicht weniger als 128 Bit gekürzt werden.

&emsp;&#x2713; HMAC-SHA1 kann nur aus Kompatibilitätsgründen verwendet werden.

&emsp;&#x2713; HMAC-Taste muss mindestens 128 Bit sein. Es werden 256-Bit-Schlüssel empfohlen.

### <a name="asymmetric-algorithms"></a>Asymmetrische Algorithmen

**Verschlüsselung**

&emsp;&#x2713; RSA ist zulässig. Der Schlüssel **muss** mindestens 2048 Bit sein, und der OAEP-Abstand muss verwendet werden. Die Verwendung des PKCS-Abstands ist nur aus Kompatibilitätsgründen zulässig.

**Signatures**

&emsp;&#x2713; RSA ist zulässig. Der Schlüssel **muss** mindestens 2048 Bit sein, und der PSS-Abstand muss verwendet werden. Die Verwendung des PKCS-Abstands ist nur aus Kompatibilitätsgründen zulässig.

&emsp;&#x2713;ECDSA ist zulässig. Der Schlüssel **muss** mindestens 256 Bit lang sein. NIST P-256-, P-384- oder P-521-Kurve muss verwendet werden.

**Key Exchange**

&emsp;&#x2713; ECDH ist zulässig. Der Schlüssel **muss** mindestens 256 Bit lang sein. NIST P-256-, P-384- oder P-521-Kurve muss verwendet werden.

&emsp;&#x2713; ECDH ist zulässig. Der Schlüssel **muss** mindestens 256 Bit lang sein. NIST P-256-, P-384- oder P-521-Kurve muss verwendet werden.

## <a name="appendix-c"></a>Anhang C

### <a name="evidence-collection--delta-for-iso-27001"></a>Nachweissammlung – Delta für ISO 27001

Wenn Sie die ISO27001-Compliance bereits erreicht haben, müssen die (Lücken) des folgenden Deltas, die nicht vollständig von ISO 27001 abgedeckt werden, mindestens im Rahmen dieser Microsoft 365-Zertifizierung überprüft werden.

> [!NOTE]
> Im Rahmen Ihrer Microsoft 365 Zertifizierungsbewertung ermittelt der Zertifizierungsanalyst, ob eines der zugeordneten ISO 27001-Steuerelemente nicht teil der ISO 27001-Bewertung war, und entscheidet sich möglicherweise auch für Beispielsteuerelemente, die als eingeschlossen eingestuft wurden, um weitere Zusicherungen zu bieten. Alle Anforderungen, die in der ISO 27001 fehlen, müssen in Ihre Microsoft 365 Zertifizierungsbewertungsaktivitäten einbezogen werden.

**Schutz vor Schadsoftware – Virenschutz**

Wenn der Schutz vor Schadsoftware mithilfe der Anwendungssteuerung eingerichtet wurde und innerhalb des ISO 27001-Berichts bestätigt wird, ist keine weitere Untersuchung erforderlich. Wenn keine Anwendungssteuerung vorhanden ist, müssen Zertifizierungsanalysten Nachweise für Anwendungskontrollmechanismen identifizieren und bewerten, um die Detonation von Schadsoftware in der Umgebung zu verhindern. Dazu müssen Sie:

* Demonstrieren Sie, dass Antivirensoftware in allen beispielweisen Systemkomponenten ausgeführt wird.

* Demonstrieren Sie, dass Antivirensoftware in allen beispielbasierten Systemkomponenten konfiguriert ist, um Schadsoftware automatisch zu blockieren, & Warnung unter Quarantäne zu stellen oder zu warnen.

* Antivirensoftware **MUSS** so konfiguriert sein, dass alle Aktivitäten protokolliert werden.

**Patchverwaltung – Patching**

Da ISO 27001-Audits diese Kategorie nicht spezifisch bewerten, müssen Sie folgende Aufgaben ausführen:

* Softwarekomponenten und Betriebssysteme, die vom Anbieter nicht mehr unterstützt **werden, DÜRFEN** in der Umgebung nicht mehr verwendet werden. Unterstützende Richtlinien MÜSSEN vorhanden sein, um sicherzustellen, dass nicht unterstützte Softwarekomponenten/Betriebssysteme aus der Umgebung entfernt werden, und ein Prozess zur Identifizierung, wann Softwarekomponenten enden, muss vorhanden sein.

**Prüfung auf Schwachstellen**  

Da ISO 27001-Audits diese Kategorie nicht spezifisch bewerten, müssen Sie folgende Aufgaben ausführen:

* Zeigen Sie, dass vierteljährlich interne und externe Sicherheitsrisikoüberprüfungen durchgeführt werden.

* Bestätigen Sie, dass unterstützende Dokumentation für die Behebung von Sicherheitsrisiken basierend auf der Risikobewertung und gemäß der Spezifikation wie folgt vorhanden ist:
 
 &#x2713; alle kritischen und hohen Risikoprobleme in Übereinstimmung mit der Risikorangfolge für die interne Überprüfung zu beheben.
 
 &#x2713; alle kritischen, hohen und mittleren Risikoprobleme in Übereinstimmung mit der Risikorangfolge für externe Scans zu beheben.
 
 &#x2713; Demonstrieren, dass die Behebung in Übereinstimmung mit der dokumentierten Richtlinie zur Behebung von Sicherheitsrisiken durchgeführt wird.

**Firewall – Firewalls (oder entsprechende Technologien)**

Da ISO 27001-Audits diese Kategorie nicht spezifisch bewerten, müssen Sie folgende Aufgaben ausführen:

* Demonstrieren Sie, dass Firewalls an der Grenze der Bereichsumgebung installiert sind.

* Demonstrieren Sie, dass Firewalls zwischen der DMZ und vertrauenswürdigen Netzwerken installiert sind.

*   Demonstrieren, dass der gesamte öffentliche Zugriff in der DMZ beendet wird.

*   Demonstrieren Sie, dass standard administrative Anmeldeinformationen vor der Installation in der Liveumgebung geändert werden.

*   Demonstrieren Sie, dass der gesamte zulässige Datenverkehr durch die Firewall(en) einen Autorisierungsprozess durchläuft, der in der Dokumentation des gesamten Datenverkehrs mit geschäftlicher Begründung resultiert.

*   Demonstrieren Sie, dass alle Firewalls so konfiguriert sind, dass Datenverkehr nicht explizit definiert wird.

*   Demonstrieren Sie, dass Firewalls nur starke Kryptografie auf allen administrativen Schnittstellen unterstützen, die keine Konsolen sind.

*   Demonstrieren Sie, dass die administrativen Schnittstellen der Firewall, die keine Konsolen sind, für die MFA für die Internetunterstützung verfügbar gemacht werden.

*   Demonstrieren, dass Firewallregelüberprüfungen mindestens alle 6 Monate durchgeführt werden

**Firewall – Webanwendungsfirewalls (WAF)**  

Zusätzliche Gutschriften werden bereitgestellt, wenn ein WAF bereitgestellt wird, um sich vor den Bedrohungen und Sicherheitsrisiken von Webanwendungen zu schützen, denen die Anwendung ausgesetzt sein kann. Wenn ein WAF oder ein ähnliches Element vorhanden ist, müssen Sie folgende Aufgaben ausführen:

* Demonstrieren Sie, dass waf im aktiven Abwehrmodus konfiguriert ist, oder überwachen Sie mehr mit Warnungen.

* Demonstrieren, dass waf für die Unterstützung von SSL-Offloading konfiguriert ist.

* Wird gemäß dem OWASP Core Rule Set (3.0 oder 3.1) konfiguriert, um sich vor den meisten der folgenden Angriffstypen zu schützen:

&#x2713; Protokoll- und Codierungsprobleme.

&#x2713; Headereinfügung, Anforderungs- und Antwortteilung.

&#x2713; Datei- und Pfaddurchlaufangriffe.

&#x2713; RFI-Angriffe (Remote File Inclusion).

&#x2713; Remotecodeausführungsangriffe.

&#x2713; PHP-Einschleusungsangriffe.

&#x2713; Websiteübergreifende Skriptangriffe.

&#x2713; SQL-Injection-Angriffe.

&#x2713; Session-Fixation-Angriffe.

**Änderungssteuerung**

Da iso 27001-Audits einige Elemente von Change Request-Prozessen nicht spezifisch bewerten, müssen Sie folgende Aufgaben ausführen:

* Demonstrieren Sie, dass Änderungsanforderungen die folgenden Details aufweisen:

&#x2713; Dokumentierte Auswirkungen.

&#x2713; Details dazu, welche Funktionalitätstests durchgeführt werden sollen.

&#x2713; Details zu allen Back-Out-Verfahren.

* Demonstrieren Sie, dass Funktionstests durchgeführt werden, nachdem die Änderungen abgeschlossen wurden.

* Demonstrieren Sie, dass Änderungsanforderungen nach dem Durchführen von Funktionstests abgemeldet werden.

**Kontoverwaltung**

Da bei ISO 27001-Audits einige Elemente von Kontoverwaltungsprozessen nicht speziell bewertet werden, müssen Sie folgende Aufgaben ausführen:

*   Veranschaulichen Sie, wie &#x2713;implementiert werden, um Replay-Angriffe zu minimieren (z. B. MFA, Kerberos).
*   Demonstrieren, wie Konten, die in 3 Monaten nicht verwendet wurden, entweder deaktiviert oder gelöscht werden.
*   &#x2713; oder andere geeignete Gegenmaßnahmen müssen konfiguriert werden, um Benutzeranmeldeinformationen zu schützen. Die folgende Mindestkennwortrichtlinie sollte als Richtlinie verwendet werden:

&#x2713; mindeste Kennwortlänge von 8 Zeichen.

&#x2713; Kontosperrschwellenwert von höchstens 10 Versuchen.
 
&#x2713; Kennwortverlauf von mindestens fünf Kennwörtern.
 
&#x2713; Erzwingung der Verwendung sicherer Kennwörter.
 
*   Demonstrieren, dass MFA für alle Remotezugriffslösungen konfiguriert ist.

*   Demonstrieren Sie, dass eine starke Verschlüsselung für alle Remotezugriffslösungen konfiguriert ist.

*   Wenn sich die Verwaltung von öffentlichem DNS außerhalb der bereichsbezogenen Umgebung befindet, MÜSSEN alle Benutzerkonten, die DNS-Änderungen vornehmen können, für die Verwendung von MFA konfiguriert sein.

**Angriffserkennung und -verhinderung (OPTIONAL)**

Da iso 27001-Audits einige Elemente von Intrusion Detection and Prevention Services (IDPS)-Prozessen nicht spezifisch bewerten, müssen Sie folgende Schritte ausführen:

*   IDPS **SOLLTEN** am Umkreis der unterstützenden Umgebung bereitgestellt werden.

*   IDPS-Signaturen **SOLLTEN** innerhalb des letzten Tages auf dem aktuellen Stand gehalten werden.

*   IDPS **SOLLTEN** für die TLS-Überprüfung konfiguriert werden.

*   IDPS **SOLLTE** für DEN GESAMTEN eingehenden und ausgehenden Datenverkehr konfiguriert werden.

*   IDPS **SOLLTEN** für die Warnung konfiguriert werden.

**Ereignisprotokollierung**

Da iso 27001-Audits einige Elemente von Prozessen zur Protokollierung von Sicherheitsereignissen nicht spezifisch bewerten, müssen Sie folgende Schritte ausführen:

* Demonstrieren Sie, dass sich öffentlich zugängliche Systeme bei einer zentralen Protokollierungslösung anmelden, die sich nicht in der DMZ befindet.

* Veranschaulichen Sie, wie die Protokollierungsdaten für mindestens 30 Tage sofort verfügbar sind, wobei 90 Tage aufbewahrt werden.

**Überprüfen (Protokollieren von Daten)**

Da einige Elemente dieser Kategorie von ISO 27001-Audits nicht speziell bewertet werden, müssen Sie folgende Aufgaben ausführen:

*   Zeigen Sie, wie tägliche Protokollüberprüfungen durchgeführt werden und wie Ausnahmen und Anomalien identifiziert werden, die zeigen, wie diese behandelt werden.

**Alarmierung**

Da einige Elemente dieser Kategorie von ISO 27001-Audits nicht speziell bewertet werden, müssen Sie folgende Aufgaben ausführen:

* Demonstrieren, wie Sicherheitsereignisse konfiguriert sind, um Warnungen für die sofortige Selektierung auszulösen.

* Demonstrieren Sie, wie Mitarbeiter 24/7 für die Reaktion auf Sicherheitswarnungen verfügbar sind.

**Risikomanagement**

Da iso 27001-Audits einige Elemente von Risikobewertungsprozessen nicht spezifisch bewerten, müssen Sie dazu Folgendes tun:

* Demonstrieren, dass ein formaler Risikomanagementprozess eingerichtet wird.

**Reaktion auf Vorfälle**

Da iso 27001-Audits einige Elemente von Richtlinien und Prozessen zur Behandlung von Sicherheitsvorfällen nicht spezifisch bewerten, müssen Sie folgende Aufgaben ausführen:

*   Demonstrieren Sie, dass der Plan/die Vorgehensweise zur Behandlung von Sicherheitsvorfällen Folgendes umfasst:

&#x2713; Spezifische Reaktionsverfahren für erwartete Bedrohungsmodelle.

&#x2713; Funktionen für die Behandlung von Sicherheitsvorfällen, die dem NIST Cybersecurity Framework (Identifizieren, Schützen, Erkennen, Reagieren, Wiederherstellen) entsprechen.
 
&#x2713; Die IRP deckt die im Umfang enthaltenen Systeme ab.
 
&#x2713; jährliche Schulung für das Vorfallreaktionsteam.

## <a name="appendix-d"></a>Anhang D

### <a name="evidence-collection--deltas-for-pci-dss"></a>Beweissammlung – Deltas für PCI DSS

Wenn Sie die PCI DSS-Compliance bereits erreicht haben, müssen die folgenden Deltas (Lücken), die nicht vollständig von PCI DSS abgedeckt werden, mindestens im Rahmen dieser Microsoft 365-Zertifizierung überprüft werden.

> [!NOTE]
> Im Rahmen der Microsoft 365 Zertifizierungsbewertung ermittelt der Zertifizierungsanalyst, ob eine der zugeordneten PCI DSS-Steuerelemente nicht in die PCI DSS-Bewertung einbezogen wurde, und kann auch entscheiden, Stichprobensteuerelemente zu verwenden, die als eingeschlossen eingestuft wurden, um weitere Zusicherungen zu bieten. Alle Anforderungen, die im PCI DSS fehlen, müssen in die Microsoft 365 Zertifizierungsbewertungsaktivitäten einbezogen werden.

**Schutz vor Schadsoftware – Anwendungssteuerung**

Wenn der Schutz vor Schadsoftware durch die Verwendung von Antivirensoftware eingerichtet wurde und innerhalb des PCI DSS-Berichts bestätigt wird, ist keine weitere Untersuchung erforderlich. Wenn kein Virenschutz vorhanden ist, müssen Zertifizierungsanalysten Nachweise für Anwendungskontrollmechanismen identifizieren und bewerten, um die Detonation von Schadsoftware in der Umgebung zu verhindern. Dazu müssen Sie: 

*   Demonstrieren Sie, wie die Anwendungsgenehmigung durchgeführt wird, und vergewissern Sie sich, dass dies abgeschlossen ist.

*   Demonstrieren Sie, dass eine vollständige Liste genehmigter Anwendungen mit geschäftlicher Begründung vorhanden ist.

*   Es wird eine unterstützende Dokumentation bereitgestellt oder veranschaulicht, in der detailliert beschrieben wird, wie die Anwendungsteuerungssoftware so konfiguriert ist, dass sie bestimmten Anwendungssteuerungsmechanismen entspricht (z. B. Whitelisting, Codesignatur usw.).

*   Demonstrieren Sie, dass die Anwendungssteuerung für alle beispielweisen Systemkomponenten als dokumentiert konfiguriert ist.

**Patchverwaltung – Risikobewertung**

Da PCI DSS-Audits diese Kategorie nicht spezifisch bewerten, müssen Sie dazu Folgendes tun:

* Veranschaulichen, wie die Risikobewertung von Sicherheitsrisiken durchgeführt wird.

**Prüfung auf Schwachstellen**

Da PCI DSS-Audits diese Kategorie nicht spezifisch bewerten, müssen Sie dazu Folgendes tun:

* Demonstrieren Sie, dass die Behebung in Übereinstimmung mit der dokumentierten Richtlinie zur Behebung von Sicherheitsrisiken durchgeführt wird.

**Firewall – Firewalls (oder entsprechende Technologien)**

Da PCI DSS-Audits diese Kategorie nicht spezifisch bewerten, müssen Sie dazu Folgendes tun:

* Demonstrieren Sie, dass Firewalls nur starke Kryptografie auf allen administrativen Schnittstellen unterstützen, die keine Konsolen sind.

* Demonstrieren Sie, dass die administrativen Schnittstellen der Firewall, die keine Konsolen sind, für die MFA für die Internetunterstützung verfügbar gemacht werden.

Zusätzliche Gutschriften werden bereitgestellt, wenn eine Webanwendungsfirewall (Web Application Firewall, WAF) bereitgestellt wird, um sich vor der Vielzahl von Webanwendungsbedrohungen und Sicherheitsrisiken zu schützen, denen die Anwendung ausgesetzt sein kann. Wenn ein WAF oder ein ähnliches Element vorhanden ist, müssen Sie folgende Aufgaben ausführen:

* Demonstrieren Sie, dass waf im aktiven Abwehrmodus konfiguriert ist, oder überwachen Sie mehr mit Warnungen.

* Demonstrieren, dass waf so konfiguriert ist, dass ssl-Offloading unterstützt wird.

* Wird gemäß dem OWASP Core Rule Set (3.0 oder 3.1) konfiguriert, um sich vor den meisten der folgenden Angriffstypen zu schützen:

&#x2713; Protokoll- und Codierungsprobleme.

&#x2713; Headereinfügung, Anforderungs- und Antwortteilung.

&#x2713; Datei- und Pfaddurchlaufangriffe.

&#x2713; RFI-Angriffe (Remote File Inclusion).

&#x2713; Remotecodeausführungsangriffe.

&#x2713; PHP-Einschleusungsangriffe.

&#x2713; websiteübergreifende Skriptingangriffe.

&#x2713; SQL-Injection-Angriffe.

&#x2713; Session-Fixation-Angriffe.

**Änderungssteuerung**

Da PCI DSS-Audits einige Elemente von Change Request-Prozessen nicht speziell bewerten, müssen Sie dazu Folgendes tun:

* Demonstrieren Sie, dass Änderungsanforderungen ausgelöst werden, bevor sie in Produktionsumgebungen ausgeführt werden.

* Demonstrieren Sie, dass Änderungen autorisiert sind, bevor sie in die Produktion gehen.

* Demonstrieren Sie, dass Funktionstests durchgeführt werden, nachdem die Änderungen abgeschlossen wurden.

* Demonstrieren Sie, dass Änderungsanforderungen nach dem Durchführen von Funktionstests abgemeldet werden.

**Sichere Softwareentwicklung/Bereitstellung**

Da PCI DSS-Audits nicht speziell auf einige Elemente sicherer Softwareentwicklungs- und Bereitstellungsprozesse zugreifen; Dies erfordert Folgendes:

* Coderepositorys MÜSSEN durch MFA gesichert werden.

*   Es MÜSSEN angemessene Zugriffssteuerungen vorhanden sein, um Coderepositorys vor Änderungen an bösartigem Code zu schützen.

**Kontoverwaltung**

Da bei PCI DSS-Audits einige Elemente von Kontoverwaltungsprozessen nicht speziell bewertet werden, müssen Sie dazu Folgendes tun:

* Demonstrieren, wie die Autorisierungsmechanismen implementiert werden, um Replay-Angriffe (z. B. MFA, Kerberos) zu minimieren.

* Richtlinien für sichere Kennwörter oder andere geeignete Gegenmaßnahmen müssen konfiguriert werden, um Benutzeranmeldeinformationen zu schützen. Die folgende Mindestkennwortrichtlinie sollte als Richtlinie verwendet werden: 

&#x2713; mindeste Kennwortlänge von 8 Zeichen.

&#x2713; Kontosperrschwellenwert von höchstens 10 Versuchen.

&#x2713; Kennwortverlauf von mindestens fünf Kennwörtern.

&#x2713; Erzwingung der Verwendung sicherer Kennwörter.

* Demonstrieren Sie, dass eine starke Verschlüsselung für alle Remotezugriffslösungen konfiguriert ist.

* Wenn sich die Verwaltung von öffentlichem DNS außerhalb der bereichsbezogenen Umgebung befindet, MÜSSEN alle Benutzerkonten, die DNS-Änderungen vornehmen können, für die Verwendung von MFA konfiguriert sein.

**Angriffserkennung und -verhinderung (OPTIONAL)**

Da PCI DSS-Audits einige Elemente von Intrusion Detection and Prevention Services (IDPS)-Prozessen nicht spezifisch bewerten, müssen Sie folgende Schritte ausführen:

* IDPS SOLLTEN für die TLS-Überprüfung konfiguriert werden.

*   IDPS SOLLTE für DEN GESAMTEN eingehenden und ausgehenden Datenverkehr konfiguriert werden.

**Risikomanagement**

Da PCI DSS-Audits einige Elemente von Risikobewertungsprozessen nicht speziell bewerten, müssen Sie dazu Folgendes tun:

* Veranschaulichen Sie, dass die Risikobewertung Auswirkungen und Wahrscheinlichkeitsmatrizen umfasst.

**Reaktion auf Vorfälle**

Da PCI DSS-Audits einige Elemente von Richtlinien und Prozessen zur Behandlung von Sicherheitsvorfällen nicht spezifisch bewerten, muss der Entwickler folgende Aufgaben durchführen:

* Vorführen der Funktionen für die Behandlung von Vorfällen, die am NIST Cybersecurity Framework ausgerichtet sind (Identifizieren, Schützen, Erkennen, Reagieren, Wiederherstellen).

## <a name="appendix-e"></a>Anhang E

### <a name="evidence-collection---deltas-for-soc-2"></a>Beweissammlung – Deltas für SOC 2

Wenn Sie die SOC 2-Compliance bereits erhalten haben, müssen die folgenden Deltas (Lücken), die nicht von SOC 2 abgedeckt werden, im Rahmen dieser Microsoft 365-Zertifizierung überprüft werden.

> [!NOTE]
> Im Rahmen der Microsoft 365 Zertifizierungsbewertung ermittelt der Zertifizierungsanalyst, ob eines der zugeordneten SOC 2-Steuerelemente nicht teil Ihrer SOC 2-Bewertung war, und entscheidet sich möglicherweise auch für Beispielsteuerelemente, die als eingeschlossen eingestuft wurden, um weitere Zusicherungen zu bieten. Alle Anforderungen, die in Ihrer SOC 2-Bewertung fehlen, müssen als Teil der Microsoft 365 Zertifizierungs-Bewertungsaktivitäten einbezogen werden.

**Schutz vor Schadsoftware – Anwendungssteuerung**

Wenn der Schutz vor Schadsoftware durch die Verwendung von Antivirensoftware eingerichtet wurde und in Ihrem SOC 2-Bericht bestätigt wird, ist keine weitere Untersuchung erforderlich. Wenn kein Virenschutz vorhanden ist, müssen Zertifizierungsanalysten Nachweise für Anwendungskontrollmechanismen identifizieren und bewerten, um die Detonation von Schadsoftware in der Umgebung zu verhindern. Dazu müssen Sie:

* Es wird eine unterstützende Dokumentation bereitgestellt oder veranschaulicht, in der detailliert beschrieben wird, wie die Anwendungsteuerungssoftware so konfiguriert ist, dass sie bestimmten Anwendungssteuerungsmechanismen entspricht (z. B. Whitelisting, Codesignatur usw.).

* Demonstrieren Sie, wie die Anwendungsgenehmigung durchgeführt wird, und vergewissern Sie sich, dass dies abgeschlossen ist.

*   Demonstrieren Sie, dass eine vollständige Liste genehmigter Anwendungen mit geschäftlicher Begründung vorhanden ist.

*   Demonstrieren Sie, dass die Anwendungssteuerung für alle beispielweisen Systemkomponenten als dokumentiert konfiguriert ist.

**Patchverwaltung – Patching**

Da SOC 2-Audits diese Kategorie nicht spezifisch bewerten, müssen Sie folgende Aufgaben ausführen:

*   Alle Probleme mit "Niedrig", "Mittel", "Hoch" oder "Kritisch" müssen in normalen Patching-Aktivitätsfenstern gepatcht werden.

*   Softwarekomponenten und Betriebssysteme, die vom Anbieter nicht mehr unterstützt werden, DÜRFEN in der Umgebung nicht mehr verwendet werden. Unterstützende Richtlinien MÜSSEN vorhanden sein, um sicherzustellen, dass nicht unterstützte Softwarekomponenten/Betriebssysteme aus der Umgebung entfernt werden, und es muss ein Prozess vorhanden sein, um zu ermitteln, wann Softwarekomponenten das Ende der Lebensdauer erreichen.

**Firewall – Firewalls**

Da BEI SOC 2-Audits änderungssteuerelemente in Firewall-Zugriffssteuerungslisten nicht speziell bewertet werden, müssen Sie folgende Aufgaben ausführen:

* Demonstrieren Sie, dass der gesamte zulässige Datenverkehr durch die Firewall(en) einen Autorisierungsprozess durchläuft, der in der Dokumentation des gesamten Datenverkehrs mit geschäftlicher Begründung resultiert.

* Demonstrieren Sie, dass Firewallregelüberprüfungen mindestens alle sechs Monate durchgeführt werden.

Zusätzliche Gutschriften werden bereitgestellt, wenn eine Webanwendungsfirewall (Waf) oder ähnliches bereitgestellt wird, um sich vor der Vielzahl von Webanwendungsbedrohungen und Sicherheitsrisiken zu schützen, denen die Anwendung ausgesetzt sein kann. Wenn ein WAF oder ein ähnliches Element vorhanden ist, müssen Sie folgende Aufgaben ausführen:

* Demonstrieren Sie, dass waf im aktiven Abwehrmodus konfiguriert ist, oder überwachen Sie mehr mit Warnungen.

* Demonstrieren, dass waf so konfiguriert ist, dass ssl-Offloading unterstützt wird.

* Wird gemäß dem OWASP Core Rule Set ((3.0 oder 3.1) konfiguriert, um sich vor den meisten der folgenden Angriffstypen zu schützen:

&emsp;&#x2713; Protokoll- und Codierungsprobleme.

&emsp;&#x2713; Headereinfügung, Anforderungs- und Antwortteilung.

&emsp;&#x2713; Datei- und Pfaddurchlaufangriffe.

&emsp;&#x2713; RFI-Angriffe (Remote File Inclusion).

&emsp;&#x2713; Remotecodeausführungsangriffe.

&emsp;&#x2713; PHP-Einschleusungsangriffe.

&emsp;&#x2713; websiteübergreifende Skriptingangriffe.

&emsp;&#x2713; SQL-Injection-Angriffe.

&emsp;&#x2713; Session-Fixation-Angriffe.

**Änderungssteuerung**

Da SOC 2-Audits einige Elemente von Change Request-Prozessen nicht speziell bewerten, muss der Entwickler folgende Aufgaben durchführen:

* Demonstrieren, wie Entwicklungs-/Testumgebungen von der Produktionsumgebung getrennt sind, die eine Aufgabentrennung erzwingt.

* Demonstrieren, wie Livedaten in entwicklungs-/testumgebungen nicht verwendet werden.

* Demonstrieren Sie, dass Funktionstests durchgeführt werden, nachdem die Änderungen abgeschlossen wurden.

* Demonstrieren Sie, dass Änderungsanforderungen nach dem Durchführen von Funktionstests abgemeldet werden.

**Sichere Softwareentwicklung/Bereitstellung**

Da SOC 2-Audits nicht speziell auf einige Elemente sicherer Softwareentwicklungs- und Bereitstellungsprozesse zugreifen; Dies erfordert Folgendes:

*   Sie MÜSSEN über einen etablierten und dokumentierten Softwareentwicklungsprozess verfügen, der den gesamten Softwareentwicklungslebenszyklus abdeckt.

*   Entwickler MÜSSEN mindestens einmal pro Jahr eine sichere Softwarecodierungsschulung durchführen.

*   Coderepositorys MÜSSEN durch MFA gesichert werden.

*   Es MÜSSEN angemessene Zugriffssteuerungen vorhanden sein, um Coderepositorys vor Änderungen an bösartigem Code zu schützen.

**Kontoverwaltung**

Da bei SOC2-Audits einige Elemente von Kontoverwaltungsprozessen nicht speziell bewertet werden, müssen Sie dazu Folgendes tun:

*   Demonstrieren, wie die Autorisierungsmechanismen implementiert werden, um Replay-Angriffe (z. B. MFA, Kerberos) zu minimieren.

*   Demonstrieren, wie Konten, die in 3 Monaten nicht verwendet wurden, entweder deaktiviert oder gelöscht werden.

*   Richtlinien für sichere Kennwörter oder andere geeignete Gegenmaßnahmen müssen konfiguriert werden, um Benutzeranmeldeinformationen zu schützen. Die folgende Mindestkennwortrichtlinie sollte als Richtlinie verwendet werden:

&emsp;&#x2713; mindeste Kennwortlänge von 8 Zeichen.

&emsp;&#x2713; Kontosperrschwellenwert von höchstens 10 Versuchen.

&emsp;&#x2713; Kennwortverlauf von mindestens 5 Kennwörtern.

&emsp;&#x2713; Erzwingung der Verwendung sicherer Kennwörter

*   Veranschaulichen Sie, dass eindeutige Benutzerkonten für alle Benutzer ausgestellt werden.

*   Wenn sich die Verwaltung von öffentlichem DNS außerhalb der bereichsbezogenen Umgebung befindet, MÜSSEN alle Benutzerkonten, die DNS-Änderungen vornehmen können, für die Verwendung von MFA konfiguriert sein.

**Angriffserkennung und -verhinderung (OPTIONAL).**

Da bei SOC 2-Audits einige Elemente von Intrusion Detection and Prevention Services (IDPS)-Prozessen nicht speziell bewertet werden, müssen Sie folgende Schritte ausführen:

*   IDPS-Signaturen SOLLTEN innerhalb des letzten Tages auf dem aktuellen Stand gehalten werden.

*   IDPS SOLLTEN für die TLS-Überprüfung konfiguriert werden

*   IDPS SOLLTE für DEN GESAMTEN eingehenden und ausgehenden Datenverkehr konfiguriert werden.

**Ereignisprotokollierung**

Da bei SOC 2-Audits einige Elemente der Prozesse zur Protokollierung von Sicherheitsereignissen nicht speziell bewertet werden, müssen Sie folgende Schritte ausführen:

* Demonstrieren, wie auf allen Systemkomponenten innerhalb des Beispielsatzes das folgende System konfiguriert ist, um die folgenden Ereignisse zu protokollieren

&emsp;&#x2713; Benutzerzugriff auf Systemkomponenten und die Anwendungen.

&emsp;&#x2713; Alle Aktionen, die von einem Benutzer mit hohen Rechten ausgeführt werden.

&emsp;&#x2713; Ungültige logische Zugriffsversuche.

Demonstrieren, dass protokollierte Ereignisse enthalten; mindestens die folgenden Informationen:

&emsp;&#x2713; Benutzer.

&emsp;&#x2713; Ereignistyp.

&emsp;&#x2713; Datum und Uhrzeit.

&emsp;&#x2713; Erfolgs-/Fehlerindikator.

&emsp;&#x2713; Bezeichnung, um das betroffene System zu identifizieren.

*   Demonstrieren Sie, dass alle Systemkomponenten innerhalb des Beispielsatzes für die Verwendung der Zeitsynchronisierung konfiguriert sind und dass diese mit den primären/sekundären Zeitservern identisch sind.

* Demonstrieren Sie, dass sich öffentlich zugängliche Systeme bei einer zentralen Protokollierungslösung anmelden, die sich nicht in der DMZ befindet.

*   Demonstrieren Sie, dass sich öffentlich zugängliche Systeme bei einer zentralen Protokollierungslösung anmelden, die sich nicht in der DMZ befindet.

* Demonstrieren, wie die zentrale Protokollierungslösung vor unbefugter Manipulation von Protokolldaten geschützt ist.

* Veranschaulichen Sie, wie die Protokollierungsdaten für mindestens 30 Tage sofort verfügbar sind, wobei mindestens 90 Tage aufbewahrt werden.

**Risikomanagement**

Da bei SOC2-Audits einige Elemente von Risikobewertungsprozessen nicht speziell bewertet werden, müssen Sie folgende Aufgaben ausführen:

* Zeigen Sie, dass mindestens einmal jährlich eine formale Risikobewertung durchgeführt wird.

*Reaktion auf Vorfälle.*

Da bei SOC2-Audits einige Elemente von Richtlinien und Prozessen zur Behandlung von Sicherheitsvorfällen nicht spezifisch bewertet werden, müssen Sie folgende Aufgaben ausführen:

* Demonstrieren Sie, dass der Plan/die Vorgehensweise zur Behandlung von Sicherheitsvorfällen Folgendes umfasst:

&emsp;&#x2713; Spezifische Reaktionsverfahren für erwartete Bedrohungsmodelle.

&emsp;&#x2713; dokumentierten Kommunikationsprozess, um eine zeitnahe Benachrichtigung der wichtigsten Beteiligten (Zahlungsmarken/Käufer, Aufsichtsbehörden, Aufsichtsbehörden, Directors, Kunden usw.) sicherzustellen.

## <a name="appendix-f"></a>Anhang F

### <a name="hosting-deployment-types"></a>Hosten von Bereitstellungstypen

Microsoft bestätigt, dass Sie Anwendungen bereitstellen und App-/Add-In-Code in verschiedenen Hostingumgebungen speichern werden. Die Gesamtverantwortlichkeiten einiger Sicherheitskontrollen innerhalb der Microsoft 365 Zertifizierung hängen von der verwendeten Hostingumgebung ab. Anhang F befasst sich mit allgemeinen Bereitstellungstypen und ordnet diese den Sicherheitssteuerelementen zu, die im Rahmen des Bewertungsprozesses ausgewertet werden. Die folgenden Hostingbereitstellungstypen wurden identifiziert:

|Hostingtypen  |Beschreibung  |
|-----|------|
|**ISV Hosted**|Isv hosted types can be defined as where you are responsible for the infrastructure used to support the app/add-in environment. Dies kann sich physisch in Ihren eigenen Rechenzentren oder in Rechenzentren von Drittanbietern mit einem Co-Location-Dienst befinden. Letztendlich haben Sie die vollständige Kontrolle über die unterstützende Infrastruktur und die Betriebsumgebung.|
|**Infrastructure as a Service (IaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-iaas/)|Infrastructure as a Service ist ein Dienst, der bereitgestellt wird, wobei die physische unterstützende Infrastruktur vom Clouddienstanbieter (CSP) in ihrem Auftrag verwaltet und verwaltet wird. In der Regel liegt die Verantwortung für Netzwerk, Speicher, physische Server und die Virtualisierungsinfrastruktur beim CSP. Das Betriebssystem, Middleware, Laufzeit, Daten und Anwendungen liegen in Ihrer Verantwortung. Firewallfunktionen würden auch vom Drittanbieter verwaltet und verwaltet, die Wartung der Firewallregelbasis würde jedoch in der Regel weiterhin in der Verantwortung der Verbraucher bleiben.|
|**Platform as a Service/Serverless (PaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-paas/)| Mit Platform as a Service erhalten Sie eine verwaltete Plattform, die einen Dienst darstellt, der genutzt werden kann. Sie müssen keine sysadmin-Funktionen ausführen, da das Betriebssystem und die unterstützende Infrastruktur vom CSP verwaltet werden. Dies wird in der Regel verwendet, wenn Organisationen sich nicht mit der Darstellung eines Webdiensts befassen möchten und sich stattdessen auf das Erstellen des Webanwendungsquellcodes und das Veröffentlichen der Webanwendung in den von der Cloud verwalteten Webdiensten konzentrieren können.  Ein weiteres Beispiel kann ein Datenbankdienst sein, bei dem eine Verbindung mit einer Datenbank besteht, die unterstützende Infrastruktur und Datenbankanwendung jedoch vom Consumer abstrahiert wird.   **Hinweis: Serverless und PaaS ähneln sich daher für den Zweck der Microsoft 365 Bereitstellungstyps "Serverless" und "PasS" als identisch eingestuft werden.**|
|**Hybrid gehostet**|Mit dem hybrid gehosteten Typ können Sie mehrere gehostete Typen verwenden, um verschiedene Teile der unterstützenden Umgebung zu unterstützen. Dies kann eher der Fall sein, wenn Apps/Add-Ins über mehrere M365-Stapel hinweg verwendet werden. Obwohl die Microsoft 365 Zertifizierung unterstützt, wo Apps/Add-Ons über mehrere M365-Dienste hinweg entwickelt werden, müsste eine Bewertung der gesamten unterstützenden Umgebung (app-/add-ins) in Übereinstimmung mit den entsprechenden "Gehosteten Typzuordnungen" bewertet werden. Gelegentlich können Sie unterschiedliche gehostete Typen für ein einzelnes Add-In verwenden, in dem dies ausgeführt wird. Die Anwendbarkeit von Kriterien muss dennoch den Kriterien "Gehostete Typzuordnungen" für die verschiedenen gehosteten Typen entsprechen.|
|**Freigegebenes Hosting**|Beim freigegebenen Hosting hosten Sie die Umgebung auf einer Plattform, die von mehreren einzelnen Consumern gemeinsam genutzt wird. Die Microsoft 365 Zertifizierungsspezifikation wurde aufgrund der Einführung der Cloud nicht zu diesem Zweck geschrieben, freigegebenes Hosting ist nicht üblich. Wenn Sie der Meinung sind, dass dies verwendet wird, wenden Sie sich an Microsoft, da zusätzliche Anforderungen erstellt werden müssen, um die zusätzlichen Risiken unter diesem Hostingtyp zu berücksichtigen.|


## <a name="appendix-g"></a>Anhang G

### <a name="microsoft-365-certification-process-workflow"></a>Microsoft 365 Zertifizierungsprozessworkflow

![Workflow](ProcessFlow.jpg)

## <a name="learn-more"></a>Mehr erfahren

[Microsoft 365 Übersicht über das App-Complianceprogramm](~/overview.md)  
[Was ist Microsoft 365 App Publisher Attestation?](~/docs/attestation.md)  
[Was ist Microsoft 365 Zertifizierung?](~/docs/enterprise-app-certification-guide.md)

## <a name="glossary"></a>Glossar

### <a name="aia"></a>Aia

*Authority Information Access ist eine Dienstspeicherortbeschreibung, die verwendet wird, um das Zertifikat der ausstellenden Zertifizierungsstelle zu finden.

### <a name="crl"></a>Zertifikatsperrliste

*Zertifikatsperrliste stellt eine Möglichkeit für einen SSL-Endpunkt (Secure Sockets Layer) bereit, um zu überprüfen, ob ein von einem Remotehost empfangenes Zertifikat gültig und vertrauenswürdig ist.

### <a name="cvss-score"></a>CVSS-Bewertung

*Common Vulnerability Scoring System ist ein veröffentlichter Standard, der die Sicherheitslücke misst und eine numerische Bewertung basierend auf seinem Schweregrad berechnet.

### <a name="cvss-patch-management-guidelines"></a>Richtlinien für die CVSS-Patchverwaltung

* Kritisch (9,0 - 10,0)
* Hoch (7,0 - 8,9)
* Mittel (4,0 - 6,9)
* Niedrig (0,0 - 3,9)

### <a name="dmz"></a>Dmz

*Demilitarized zone is a physical or logical intermediate network that interacts directly external or non-propriety networks while keeping the host's internal, private network separate and isolated.

### <a name="euii"></a>EUII

*Informationen zur Identifizierung durch Endbenutzer.*

### <a name="gdpr"></a>DSGVO

*Die Datenschutz-Grundverordnung ist eine Datenschutz- und Datenschutz-Verordnung der Europäischen Union (EU) für alle Daten von EU-Bürgern, unabhängig davon, wo sich Ihre Anwendungswebsite befindet.

### <a name="hsts"></a>HSTS

*HTTP Strict Transport Security verwendet einen HTTP-Antwortheader, der den Webbrowser anweist, nur auf Inhalte über HTTPS zuzugreifen.  Dies dient zum Schutz vor Downgrade-Angriffen und Cookie-Angriffen.

### <a name="iec"></a>Iec

*International Electrotechnical Commission.

### <a name="isms"></a>Theorien

*Information Security Management System.

### <a name="isv"></a>ISV

Unabhängige Sicherheitsanbieter sind Einzelpersonen und Organisationen, die Software entwickeln, vermarkten und verkaufen, die auf Software- und Hardwareplattformen von Drittanbietern ausgeführt wird.

### <a name="iso-27001"></a>ISO 27001

Ein Spezifikationsframework für informationssicherheitsverwaltungssystem für alle technischen Kontrollen in Risikomanagementrichtlinien und -verfahrensprozessen einer Organisation.

### <a name="lfi"></a>Lfi

*Die lokale Dateieinschluss* ermöglicht es einem Angreifer, Dateien über den Webbrowser auf einem Server einzuschließen.

### <a name="nist"></a>Nist

Das *National Institute of Standards* (NIST), eine nicht regulatorische Agentur des US-Handelsministeriums, bietet Organisationen des privaten Sektor in den USA Anleitungen zur Bewertung und Genehmigung ihrer Fähigkeit, Cyberangriffe zu verhindern, zu erkennen und darauf zu reagieren.

### <a name="non-significant-changes"></a>Nicht signifikante Änderungen

* Kleinere Fehlerbehebungen.
* Geringfügige Leistungsverbesserungen.
* Patches für Betriebssysteme/Bibliotheken/Clients und Serveranwendungen.

### <a name="ocsp"></a>Ocsp

Das *Onlinezertifikatstatusprotokoll* wird verwendet, um den Sperrstatus digitaler X.509-Zertifikate zu überprüfen.

### <a name="oii"></a>OII

*Organisationsbezogenen Informationen.*

### <a name="owasp"></a>Owasp

Öffnen Sie *die Webanwendungssicherheit Project*.

### <a name="pci-dss"></a>PCI/DSS

*Payment Card Industry Data Security Standard*, eine Organisation, die Standards für die Sicherheit von Karteninhaberdaten weltweit aufrechterhält.

### <a name="pen-testing"></a>Stifttests

*Penetrationstests* sind eine Methode zum Testen einer Web-App, indem böswillige Angriffe simuliert werden, um Sicherheitsrisiken zu finden, die ein Angreifer ausnutzen könnte.

### <a name="saml"></a>SAML

*Die Security Assertion Markup Language* ist ein offener Standard für den Austausch von Authentifizierungs- und Autorisierungsdaten zwischen dem Benutzer, dem Identitätsanbieter und dem Dienstanbieter.

### <a name="sensitive-data"></a>Vertrauliche Daten

* Zugriffssteuerungsdaten.
* Kundeninhalte.
* Informationen zur Endbenutzeridentität.
* Supportdaten.
* Öffentliche personenbezogene Daten.
* Pseudonyme Informationen für Endbenutzer.

### <a name="significant-changes"></a>Wesentliche Änderungen

* Verschiebung der Hostingumgebung.
* Wichtige Upgrades auf die unterstützende Infrastruktur; z. B. Implementierung einer neuen Firewall, wichtige Upgrades auf Front-Facing-Dienste usw.
* Hinzufügen von Funktionen und /oder Erweiterungen zu Ihrer App.
* Updates für Ihre App, die zusätzliche vertrauliche Daten erfassen.
* Änderungen an den Datenflüssen oder Autorisierungsmodellen Ihrer App
* Hinzufügen von API-Endpunkten oder API-Endpunktfunktionen.

### <a name="soc-2"></a>SOC 2

*Service Organization Control 2*, ein technisches Überwachungsverfahren, das aus fünf Vertrauensdienstprinzipien besteht, um sicherzustellen, dass Dienstanbieter die Daten und den Datenschutz für die Kunden einer Organisation sicher verwalten.

### <a name="ssl"></a>Ssl

*Secure Sockets Layer*.

### <a name="tls"></a>TLS

*Transport Layer Security*.
