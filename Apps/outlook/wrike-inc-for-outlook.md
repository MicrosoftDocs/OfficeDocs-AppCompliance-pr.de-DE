---
title: Anwendungsinformationen für Wrike für Outlook von Wrike Inc.
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Wrike for Outlook, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 1ee6c98b2513459c588100a9b3b19ba529d98af0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553696"
---
# <a name="wrike-for-outlook"></a>Wrike für Outlook

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Zuletzt aktualisiert vom Entwickler am: 23. März 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381120" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Wrike Inc. Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Wrike für Outlook |
| ID | WA104381120 |
| Office 365 unterstützten Clients | Outlook 2013 oder später Windows, Outlook 2016 oder später auf Mac, Outlook auf iOS, Outlook im Web, Outlook auf Android |
| Name des Partnerunternehmens | Wrike Inc. |
| URL der Partner-Website | [https://wrike.com/](https://wrike.com/) |
| URL der Datenschutzrichtlinie | [https://www.wrike.com/security/privacy](https://www.wrike.com/security/privacy) |
| URL der Nutzungsbedingungen | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=de-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Wrike Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>Diese Anwendung verwendet keine Microsoft-Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mithilfe anderer Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, können zusätzliche Microsoft-APIs verwenden, die nicht microsoft Graph sind, um unternehmensbezogene identifizierbare Informationen (OII) zu sammeln oder zu verarbeiten. Listen Sie alle Microsoft-APIs auf, die nicht von Microsoft Graph diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Rechtfertigung für das Sammeln von OII?** | **Wird OII gespeichert?** | **Rechtfertigung für die Speicherung von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| JavaScript-API für Office | Ja | Das Add-In verwendet die Office.js-API, um sie in die Office-Anwendung zu integrieren. |  | In den Datenbanken von Wrike werden keine Organisationsdaten gespeichert. |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike hat die Integrationen mit folgenden Anbietern, die Zugriff auf einige Daten haben: Marketo ist E-Mail Lead Capturing Dienste - nur Namen und E-Mails werden ihnen zur Verfügung gestellt. Outreach ist Cloud-basiertes Vertriebsengagement – nur Namen und E-Mails werden ihnen zur Verfügung gestellt. Salesforce CRM-System - verfügt über Kontaktinformationen und Abrechnungsinformationen (keine sensiblen Daten) von Kunden. Zuora - Abrechnung und Fakturierung von Kunden. Für alle Kreditoren gibt es eine Dpa. |  | Wir verwenden JS Office API, aber wir sammeln/verarbeiten/speichern keine organisatorischen Informationen. |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Nein

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Wrike verfügt über eine Mehrmandantenarchitektur, die Kunden logisch&#8217; Daten durch Zugriffssteuerung basierend auf Kundenmetadaten trennt. Diese Metadaten sind dem bestimmten Mandanten und seinen Zugriffsrechten gemäß den rollenbasierten Zugriffsregeln innerhalb des jeweiligen Wrike-Kontos zugeordnet. Daten werden logisch isoliert und getrennt, und der Zugriff auf Daten ist nur über die Anwendung verfügbar, um Sicherheit und Datenschutz zu gewährleisten. Die Sicherheit auf Anwendungsebene verhindert, dass Mandanten auf Anwendungsdaten zugreifen oder diese ändern, die im Besitz eines anderen Mandanten sind. Wrikes Anwendung verfügt über umfangreiche Authentifizierung, rollenbasierte Zugriffssteuerung, Autorisierung sowie Datenfreigabe- und -steuerungsmechanismen (siehe https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles und https://help.wrike.com/hc/en-us/articles/209602969) ermöglicht den Datenzugriff nur für autorisierte Benutzer). Darüber hinaus wird die Verschlüsselung im Ruhezustand für Benutzerdateien angewendet, die über Webanwendung und API auf Wrike-Server im Dateispeicher hochgeladen werden. Die Dateien werden automatisch mit AES 256-Bit-Verschlüsselung verschlüsselt. Darüber hinaus werden alle Server im Ruhezustand mit Dateisystemverschlüsselung verschlüsselt, und darüber hinaus bietet Wrike Wrike Dasperik-Lock-Add-In für den Verschlüsselungsschlüssel an, der von einem Kunden verwaltet wird, siehe https://www.wrike.com/add-on-wrike-lock/ und https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock . Als zusätzliche Ebene der Datensicherheit bietet Wrike Audit- und Reporting-Funktionalität, mit der Administratoren vollständige Sicherheitsüberprüfungen durchführen können, während sie gleichzeitig die Transparenz der Ereignisse in ihrem Wrike-Konto erhöhen können. Weitere Details finden Sie unter https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports . Schließlich bietet Wrike Funktionen, die die detaillierte Nachverfolgung von Zugriffsrollen ermöglichen, um Kunden bei der vollständigen Überwachung vorhandener Datenfreigaben zu unterstützen, siehe Details unter https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports .
Der Zugriff auf Kundendaten kann in zwei Fällen in Betracht gezogen werden:
- Zugriff durch das Wrike Support-Team: Im Falle der Fehlerbehebung oder Überprüfung des Problems muss der Support auf Ihr Konto zugreifen. dass der Zugriff nur von Ihnen gewährt werden kann. Dies wird durch ein vom System generiertes Sicherheitstoken ermöglicht, das Sie unserem Support-Team aumgehend zur Verfügung stellen, sodass der Support ihr Problem für einen begrenzten Zeitraum vertiefen kann. Dieser systemische Ansatz gewährleistet zusätzliche Vertraulichkeit für Ihre in Wrike gespeicherten Daten.
- Zugriff durch Wrike Operational Team: Wrike Operational Team ist verantwortlich für die Wartung und Unterstützung der Produktionsumgebung einschließlich Überwachung, Patching und Aktualisierung, Lieferung der neuen Builds an die Produktion, etc. Der Zugriff in diesem Fall ist streng verboten, sowohl aus verfahrenstechnischen als auch aus technischen Aspekten, und starke Autorisierungskontrollen einschließlich, aber nicht beschränkt VPN, 2FA und persönliche Satnahmen sind vorhanden, außerdem wird es in Details mit HIDS (Host-based Intrusion Detection System) überwacht und vom Wrike Operational Security Team überprüft. Bei Amazon KMS (Wrike Lock-Funktionalität) werden die Kundendaten verschlüsselt in der Wrike-Datenbank gespeichert, so dass die Daten nicht direkt oder indirekt vom Wrike Operational-Team zur Verfügung stehen, da die Daten über den Zugriff auf die Amazon-KMS des Kunden entschlüsselt werden können, die nur vom Kunden verwaltet und kontrolliert wird.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

