---
ms.author: oromalle
title: Microsoft 365-Zertifizierung – Leitfaden für die anfängliche Dokumentenübermittlung
author: orionomalley
manager: tonybal
description: Die anfängliche Dokumentenübermittlung ist Teil der Vorbewertungsphase der Zertifizierung.
keywords: app certification teams Microsoft 365 security compliance m365 initial document submission
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 8cb7ac4711b7399ae24b76794c251e3cae845e94
ms.sourcegitcommit: a615b7893956a0737e30e477d2870fd99e514ea5
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/20/2022
ms.locfileid: "65618583"
---
# <a name="microsoft-365-ceritification---initial-document-submission-guide"></a>Microsoft 365 Ceritification – Leitfaden für die anfängliche Dokumentübermittlung

Die anfängliche Dokumentenübermittlung ist Teil der Vorbewertungsphase der Zertifizierung. Die bereitgestellten Informationen geben Zertifizierungsanalysten den Hintergrund, der erforderlich ist, um zu ermitteln, welche Steuerelemente und Systemkomponenten für Ihre Bewertung in den Anwendungsbereich fallen. Dieses Dokument soll nur als Beispiel dafür dienen, was von ihrer ursprünglichen Dokumentübermittlung erwartet wird. Die von Ihnen bereitgestellte Dokumentation hängt davon ab, wie Ihre Lösung entwickelt, implementiert und verwaltet wird.

## <a name="what-is-the-hosting-environment-or-service-model-used-to-run-your-app"></a>Was ist die Hostingumgebung oder das Dienstmodell, die zum Ausführen Ihrer App verwendet wird?
- Infrastructure as a Service (IaaS) ist ein Clouddienstmodell, bei dem Ihr Clouddienstanbieter Ihre Infrastrukturkomponenten hostet, ISVs jedoch weiterhin für die bereitstellung und verwaltung der Komponenten einzeln verantwortlich sind, z. B. virtuelle Computer/Betriebssysteme, Datenspeicher und Netzwerkkomponenten. Beispiele hierfür sind Azure Virtual Machine und Azure Disk Storage.
- Platform as a Service (PaaS) ist ein Clouddienstmodell, bei dem die Infrastrukturkomponenten vom Clouddienstanbieter verwaltet werden. ISVs sind nur für die Bereitstellung ihrer eigenen Anwendungen und Dienste verantwortlich. Beispiele hierfür sind Azure-App Services, Azure Functions und Azure CDN.
- ISV Hosted in this context means that no cloud service provider is used. Der ISV verwaltet physisch eigene Server, Datenträger und Netzwerke unabhängig voneinander lokal.
- Hybrid bedeutet in diesem Zusammenhang, dass eines der oben genannten Modelle verwendet wird. Einige ISVs können z. B. eine Mischung aus IaaS-Diensten und PaaS-Diensten verwenden, um ihre App zu unterstützen, oder sie verfügen über einige lokale ISV Hosted-Komponenten und lagern andere an einen Clouddienstanbieter aus. Wenn Sie eins von mehreren Dienstmodellen verwenden, wählen Sie "Hybrid" aus.

## <a name="penetration-test-report"></a>Penetrationstestbericht

Bitte geben Sie den vollständigen Penetrationstestbericht mit den Datumsangaben an, dass er innerhalb der letzten 12 Monate abgeschlossen wurde. 
-   Dieser Bericht muss aus manuellen Penetrationstests erstellt werden, er kann nicht die Ausgabe eines automatisierten Überprüfungs-/Testtools sein.
-   Dieser Bericht muss die Umgebung enthalten, die die Bereitstellung der App/add unterstützt, zusammen mit jeder zusätzlichen Umgebung, die den Betrieb der App/Add-Ins unterstützt.


## <a name="system-component-inventory"></a>Systemkomponenteninventar

Ein aktueller Inventroy aller Systemkomponenten, die von der unterstützenden Infrastruktur genutzt werden. Dies wird verwendet, um beim Sampling bei der Durchführung der Bewertungsphase zu helfen. Wenn Ihre Umgebung PaaS enthält, wäre es hilfreich, wenn Sie Details zu allen genutzten PaaS-Diensten bereitstellen können.

**Hinweis:** IaaS/PaaS hätte keine Hardware, die unter dem ISVs-Steuerelement wäre.  Geben Sie in diesem Fall eine Liste oder einen Screenshot aller virualen Ressourcen an.

**Beispiel:**

|Objektname|Objekttyp|Beschreibung|Hersteller|Modell|
|---|---|---|---|---|
|D212|Windows Computer|Virtueller Computer|Nicht zutreffend|Nicht zutreffend|
|LT101|Laptop|Arbeitsstation|Microsoft|Surface 3|
|C2938|Option|Option|Nicht zutreffend|Nicht zutreffend|
|LXM2|Linux-Computer|Testcomputer|Nicht zutreffend|Nicht zutreffend|


## <a name="software-inventory"></a>Softwareinventar

Eine aktuelle Bestandsaufnahme aller Softwareressourcen, einschließlich aller Software, die in der In-Scope-Umgebung zusammen mit den Versionen verwendet wird.

**Beispiel:**

|Software|Publisher|Version|Zweck|
|---|---|---|---|
|Windows Server|Microsoft 2016 |Build 14393|Serverbetriebssystem für die Produktionsumgebung|
|Linux Ubuntu|Nicht zutreffend|16.04 (Xenial)|Serverbetriebssystem, das innerhalb der DMZ verwendet wird.|
|Esxi|Vmware|6.5.0 (Build 13004031)|Wird verwendet, um die virtuellen Server zu unterstützen.|
|Mysql (Windows)|Nicht zutreffend|8.0.2.1|Datenbankserver zum Speichern des Chatverlaufs.|
|Tomcat|Apache|7.0.92|Kundenportal.|
|IIS|Microsoft|10.0|Unterstützt die APIs.|


## <a name="third-party-dependencies"></a>Abhängigkeiten von Drittanbietern

Dokumentation, in der alle Abhängigkeiten aufgeführt sind, die von der App/dem Add-In mit den aktuellen ausgeführten Versionen verwendet werden.

**Beispiel:**

|Webabhängigkeiten|Aktuelle Version wird verwendet|
|----|----|
|Jquery|3.5.1|
|React|16.13.1|
|Bootstrap|4.5.2|
|Express|4.17.1|
|Angular|10.0.14|
|AngularJS|1.8.0|


## <a name="public-ip-addresses"></a>Öffentliche IP-Adressen

Details aller öffentlichen IP-Adressen und URLs, die von der unterstützenden Infrastruktur verwendet werden. Dies muss den vollständigen routingfähigen IP-Bereich umfassen, der der Umgebung zugeordnet ist, es sei denn, es wurde eine angemessene Segmentierung implementiert, um den verwendeten Bereich aufzuteilen (angemessene Nachweise für die Segmentierung sind erforderlich).

**Beispiel:**

|URLs|IP-Adresse|
|-|-|
|https://portal.contoso.com |40.113.200.201 |
|https://filesapi.contoso.com|40.113.200.201|
|https://customerapi.contoso.com|40.113.200.202|
|https://bot.contoso.com|40.113.200.202|
|N/V (Sprungserver)|40.113.200.200|


## <a name="resource-endpoints"></a>Ressourcenendpunkte

API Name Endpoint Address Contoso Customer API https://customerapi.contoso.com Contoso Bot Service https://bot.contoso.com Contoso Files APIhttps://filesapi.contoso.com

Eine vollständige Auflistung aller API-Endpunkte, die von Ihrer App verwendet werden, einschließlich intern entwickelter und externer Ressourcenendpunkte. Um den Umgebungsbereich zu verstehen, stellen Sie API-Endpunktspeicherorte in Ihrer Umgebung bereit.

**Beispiel:**

|API-Name|  Endpunktadresse|
|-|-|
|Contoso-Kunden-API|  https://customerapi.contoso.com|
|Contoso Bot Service|   https://bot.contoso.com|
|Contoso-Datei-API| https://filesapi.contoso.com|
|Microsoft Graph| https://graph.microsoft.com/v1.0/|


## <a name="architectural-diagram"></a>Architekturdiagramm

Ein logisches Architekturdiagramm, das eine allgemeine Übersicht über die unterstützende Infrastruktur Ihrer App/Ihres Add-Ins darstellt. Dazu müssen alle Hostingumgebungen und die unterstützende Infrastruktur gehören, die die App/das Add-In unterstützt. Dieses Diagramm MUSS alle verschiedenen unterstützenden Systemkomponenten in der Umgebung darstellen, um Zertifizierungsanalysten dabei zu unterstützen, Systeme im Umfang zu verstehen und stichprobenartig zu ermitteln. Bitte geben Sie auch an, welcher Hostingumgebungstyp verwendet wird; ISV Hosted, IaaS, PaaS oder Hybrid. Wo PaaS verwendet wird, geben Sie bitte die verschiedenen PaaS-Dienste an, die verwendet werden, um die unterstützenden Dienstleistungen innerhalb der Umgebung bereitzustellen.

![Architekturdiagramm](../media/Architecturaldiagram.png)

## <a name="data-flow-diagram"></a>Datenfluss Diagramm

Flow Diagramme mit den folgenden Details:
-   Daten fließen an und aus der App/dem Add-In (einschließlich Kundendaten).
-   Datenflüsse innerhalb der unterstützenden Infrastruktur (sofern zutreffend)
-   Diagramme, in denen hervorgehoben wird, wo und welche Daten gespeichert werden, wie Daten an externe Dritte weitergegeben werden (einschließlich Details zu welchen Dritten), und wie Daten bei der Übertragung über offene/öffentliche Netzwerke und ruhende Netzwerke geschützt werden.

![Datenfluss Diagramm](../media/Dataflowdiagram.png)

## <a name="external-certifications-soc2-pci-dss-iso27001---optional"></a>Externe Zertifizierungen (SOC2, PCI DSS, ISO27001) – OPTIONAL

Wenn Sie bereits eine SOC2-, PCI DSS- oder ISO27001-Zertifizierung erhalten haben und innerhalb der letzten 12 Monate einen Bericht ausgestellt haben, der den vollständigen Umfang der zu zertifizierenden Anwendung sowie die unterstützende Umgebung umfasst, können Sie dies während der ursprünglichen Dokumentenübermittlung übermitteln. Wir werden versuchen, es zu nutzen, um eine Teilmenge von Steuerelementen zu erfüllen und Ihre Bewertung zu beschleunigen. Dies ist jedoch nicht erforderlich, um eine Microsoft 365 Zertifizierung zu erhalten. 

