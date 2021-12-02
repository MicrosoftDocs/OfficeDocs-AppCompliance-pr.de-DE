---
ms.author: oromalle
title: Microsoft 365-Zertifizierung – Leitfaden für die ursprüngliche Dokumentübermittlung
author: orionomalley
description: detaillierte Ansicht des Microsoft 365-Zertifizierungsübermittlungshandbuchs
keywords: App-Zertifizierungsteams Microsoft 365 M365-Erstübermittlung von Dokumenten zur Sicherheitscompliance
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 0f879ce6b02fb469b0210500e4706d468ccb4011
ms.sourcegitcommit: 3e72bc447a90cd8b0313dab55f6a9374be8ae358
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 12/01/2021
ms.locfileid: "61261677"
---
# <a name="microsoft-365-ceritification---initial-document-submission-guide"></a>Microsoft 365 Ceritification – Leitfaden für die ursprüngliche Dokumentübermittlung

Die anfängliche Dokumentübermittlung ist Teil der Phase vor der Bewertung der Zertifizierung. Anhand der bereitgestellten Informationen erhalten Zertifizierungsanalysten den Hintergrund, der erforderlich ist, um zu ermitteln, welche Steuerelemente und Systemkomponenten für Ihre Bewertung im Umfang sind. Dieses Dokument dient nur als Beispiel für das, was von Ihrer anfänglichen Dokumentübermittlung erwartet wird. Die von Ihnen bereitgestellte Dokumentation hängt davon ab, wie Ihre Lösung erstellt, implementiert und verwaltet wird.

## <a name="what-is-the-hosting-environment-or-service-model-used-to-run-your-app"></a>Welche Hostingumgebung oder welches Dienstmodell wird zum Ausführen Ihrer App verwendet?
- Infrastructure as a Service (IaaS) ist ein Clouddienstmodell, bei dem Ihr Clouddienstanbieter Ihre Infrastrukturkomponenten hostet, ISVs jedoch weiterhin für die individuelle Bereitstellung und Verwaltung der Komponenten verantwortlich sind, z. B. virtuelle Computer/Betriebssysteme, Datenspeicher und Netzwerkkomponenten. Beispiele hierfür sind Azure Virtual Machine und Azure Disk Storage.
- Platform as a Service (PaaS) ist ein Clouddienstmodell, bei dem die Infrastrukturkomponenten vom Clouddienstanbieter verwaltet werden. ISVs sind nur für die Bereitstellung ihrer eigenen Anwendungen und Dienste verantwortlich. Beispiele hierfür sind Azure App Services, Azure Functions und Azure CDN.
- Isv Hosted in this context means that no cloud service provider is used. Der ISV verwaltet seine eigenen Server, Datenträger und Netzwerke lokal unabhängig voneinander.
- Hybrid bedeutet in diesem Zusammenhang, dass eines der oben genannten Modelle verwendet wird. Einige ISVs entscheiden sich beispielsweise dafür, eine Mischung aus IaaS-Diensten und PaaS-Diensten zu verwenden, um ihre App zu unterstützen, oder sie verfügen möglicherweise über lokale ISV-gehostete Komponenten und lagern andere an einen Clouddienstanbieter aus. Wenn Sie eines von mehreren Dienstmodellen verwenden, wählen Sie Hybrid aus.

## <a name="penetration-test-report"></a>Penetrationstestbericht

Bitte fügen Sie den vollständigen Penetrationstestbericht mit Datumsangaben hinzu, die angeben, dass er innerhalb der letzten 12 Monate abgeschlossen wurde. 
-   Dieser Bericht muss aus manuellen Penetrationstests erstellt werden, er kann nicht die Ausgabe eines automatisierten Überprüfungs-/Testtools sein.
-   Dieser Bericht muss die Umgebung enthalten, die die Bereitstellung der App/des Add-Ins unterstützt, sowie alle zusätzlichen Umgebungen, die den Betrieb der App/Add-Ins unterstützen.


## <a name="system-component-inventory"></a>Systemkomponenteninventar

Eine aktuelle Neustrukturung aller Systemkomponenten, die von der unterstützenden Infrastruktur verwendet werden. Dies wird verwendet, um beim Sampling bei der Durchführung der Bewertungsphase zu helfen. Wenn Ihre Umgebung PaaS umfasst, wäre es hilfreich, wenn Sie Details zu allen genutzten PaaS-Diensten angeben können.

**Hinweis:** IaaS/PaaS hätte keine Hardware, die der ISVs-Steuerung unterliegt.  Geben Sie in diesem Fall eine Liste oder einen Screenshot aller virualen Ressourcen an.

**Beispiel:**

|Objektname|    Objekttyp| Beschreibung|    Hersteller|   Modell|
|-|-|-|-|-|
|D212|  Windows Computer|   Virtueller Computer|    Nicht zutreffend| Nicht zutreffend|
|LT101| Laptop| Arbeitsstation|    Microsoft|  Surface 3|
|C2938| Option| Option|Nicht zutreffend|Nicht zutreffend|     
|LXM2|  Linux-Computer|  Testcomputer|Nicht zutreffend|Nicht zutreffend|       


## <a name="software-inventory"></a>Softwareinventar

Eine aktuelle Bestandsaufnahme aller Softwareressourcen, einschließlich aller Software, die in der In-Scope-Umgebung zusammen mit den Versionen verwendet wird.

**Beispiel:**

|Software|  Publisher|  Version|     Zweck|
|-|-|-|-|
|Windows Server|    Microsoft 2016 | Build 14393| Serverbetriebssystem für die Produktionsumgebung|.
|Linux Ubuntu|  Nicht zutreffend|    16.04 (Xenial)| Serverbetriebssystem, das in der DMZ verwendet wird.|
|Esxi|  Vmware| 6.5.0 (Build 13004031)| Wird zur Unterstützung der virtuellen Server verwendet.|
|Mysql (Windows)|   Nicht zutreffend|    8.0.2.1|    Datenbankserver zum Speichern des Chatverlaufs.|
|Tomcat|        Apache| 7.0.92| Kundenportal.|
|IIS|   Microsoft|  10.0|   Unterstützt die APIs.|


## <a name="third-party-dependencies"></a>Abhängigkeiten von Drittanbietern

Dokumentation, in der alle Abhängigkeiten aufgeführt sind, die von der App/dem Add-In mit den aktuell ausgeführten Versionen verwendet werden.

**Beispiel:**

|Webabhängigkeiten|  Aktuelle verwendete Version|
|-|-|
|Jquery|    3.5.1|
|React| 16.13.1|
|Bootstrap| 4.5.2|
|Express|   4.17.1|
|Angular|   10.0.14|
|AngularJS| 1.8.0|


## <a name="public-ip-addresses"></a>Öffentliche IP-Adressen

Ausführliche Informationen zu allen öffentlichen IP-Adressen und URLs, die von der unterstützenden Infrastruktur verwendet werden. Dies muss den vollständigen routingfähigen IP-Bereich enthalten, der der Umgebung zugeordnet ist, es sei denn, eine angemessene Segmentierung wurde implementiert, um den verwendeten Bereich aufzuteilen (angemessene Nachweise für die Segmentierung sind erforderlich).

**Beispiel:**

|URLs|  IP-Adresse|
|-|-|
|https://portal.contoso.com |40.113.200.201 |
|https://filesapi.contoso.com|  40.113.200.201|
|https://customerapi.contoso.com|   40.113.200.202|
|https://bot.contoso.com|   40.113.200.202|
|Nicht verfügbar (Jump Server)| 40.113.200.200|


## <a name="resource-endpoints"></a>Ressourcenendpunkte

API-Name Endpunktadresse Contoso Customer API    https://customerapi.contoso.com Contoso Bot Service Contoso Files https://bot.contoso.com API   https://filesapi.contoso.com

Eine vollständige Liste aller API-Endpunkte, die von Ihrer App verwendet werden, einschließlich intern entwickelter und externer Ressourcenendpunkte. Um den Umgebungsbereich besser verstehen zu können, stellen Sie API-Endpunktspeicherorte in Ihrer Umgebung bereit.

**Beispiel:**

|API-Name|  Endpunktadresse|
|-|-|
|Contoso-Kunden-API|  https://customerapi.contoso.com|
|Contoso Bot Service|   https://bot.contoso.com|
|Contoso-Datei-API| https://filesapi.contoso.com|
|Microsoft Graph| https://graph.microsoft.com/v1.0/|


## <a name="architectural-diagram"></a>Architekturdiagramm

Ein logisches Architekturdiagramm, das eine allgemeine Übersicht über die unterstützende Infrastruktur Ihrer App/Ihres Add-Ins darstellt. Dies muss alle Hostingumgebungen und unterstützende Infrastruktur umfassen, die die App/das Add-In unterstützt. Dieses Diagramm MUSS alle verschiedenen unterstützenden Systemkomponenten innerhalb der Umgebung darstellen, damit Zertifizierungsanalysten die Systeme im Umfang verstehen und bei der Bestimmung des Samplings helfen können. Geben Sie außerdem an, welcher Hostingumgebungstyp verwendet wird. ISV hosted, IaaS, PaaS oder Hybrid. Wo PaaS verwendet wird, geben Sie bitte die verschiedenen PaaS-Dienste an, die verwendet werden, um die unterstützenden Dienste innerhalb der Umgebung bereitzustellen.

![Architekturdiagramm](../media/Architecturaldiagram.png)

## <a name="data-flow-diagram"></a>Diagramm "Daten Flow"

Flow Diagramme, die Folgendes detailliert darstellen:
-   Datenflüsse zu und von der App/dem Add-In (einschließlich Kundendaten).
-   Datenflüsse innerhalb der unterstützenden Infrastruktur (sofern zutreffend)
-   Diagramme, in denen hervorgehoben wird, wo und welche Daten gespeichert werden, wie Daten an externe Dritte übergeben werden (einschließlich Details zu dritten Parteien), und wie Daten während der Übertragung über offene/öffentliche Netzwerke und im Ruhezustand geschützt werden.

![Diagramm "Daten Flow"](../media/Dataflowdiagram.png)



