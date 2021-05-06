---
title: Anwendungsinformationen für Wrike für Office Dokumente von Wrike Inc.
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Wrike für Office-Dokumente, die Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c1304a161377b80c0248229aa1ef92f4f15e19d9
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251404"
---
# <a name="wrike-for-office-documents"></a>Wrike für Office Dokumente

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Zuletzt aktualisiert vom Entwickler am: 23. März 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379841" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Wrike Inc. an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Wrike für Office Dokumente |
| ID | WA104379841 |
| Office 365 unterstützten Clients | Excel 2016 oder höher auf Windows, Word 2013 oder höher auf Windows, PowerPoint 2013 oder höher auf Windows, Excel 2016 oder höher auf Mac, Excel im Web, Word 2016 oder höher auf Mac, Word im Web, PowerPoint 2016 oder höher auf Mac, PowerPoint im Web |
| Partnerunternehmensname | Wrike Inc. |
| URL der Partnerwebsite | [https://wrike.com/](https://wrike.com/) |
| URL der Datenschutzrichtlinie | [https://www.wrike.com/privacy](https://www.wrike.com/privacy) |
| URL der Nutzungsbedingungen | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Wrike Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>Diese Anwendung verwendet keine Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mithilfe anderer Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 können zusätzliche Microsoft-APIs als Microsoft Graph verwenden, um identifizierbare Informationen (OII) der Organisation zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft Graph diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| JavaScript-API für Office | Ja | Das Add-In verwendet die Office.js-API, um in die Office zu integrieren. |  | In den Datenbanken von Wrike werden keine Organisationsdaten gespeichert. |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike verfügt über die Integrationen mit den folgenden Anbietern, die Zugriff auf einige Daten haben: Marketo ist E-Mail-Leaderfassungsdienste – nur Namen und E-Mails werden ihnen bereitgestellt. Outreach ist cloudbasiertes Vertriebsengagement – nur Namen und E-Mails werden ihnen bereitgestellt. Salesforce CRM System – verfügt über Kontaktinformationen und Abrechnungsinformationen (keine vertraulichen Daten) von Kunden. Zuora – Abrechnungs- und Rechnungskunden. Es gibt ein DPA für alle Anbieter. |  | Wir verwenden JS Office-API, sammeln/verarbeiten/speichern jedoch keine Organisatorischen Informationen. |



#### <a name="add-in-data-access"></a>Add-In-Datenzugriff

Listet die Berechtigungen auf, die diese App für den Zugriff auf die Daten Ihrer Organisation benötigt, die Begründung und den Zweck dieser Berechtigung (wofür verwendet die App diese Informationen?), und ob die App diese Informationen in ihren Datenbanken speichert.

>| **Berechtigung**  | **Beschreibung** |
>|:----------------|:----------------|
>| ReadWrite Document | Kann Ihr Dokument lesen und änderungen vornehmen |
>| Senden von Daten | Kann Daten über das Internet senden |

#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Nein

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wrike verfügt über eine mehr mandantenbasierte Architektur, die kundenbasierte Daten&#8217; Zugriffssteuerung basierend auf Kundenmetadaten logisch trennt. Diese Metadaten sind dem jeweiligen Mandanten und seinen Zugriffsrechten gemäß den rollenbasierten Zugriffsregeln innerhalb des jeweiligen Wrike-Kontos zugeordnet. Daten sind logisch isoliert und getrennt, und der Zugriff auf Daten ist nur über die Anwendung verfügbar, um Sicherheit und Datenschutz zu gewährleisten. Die Sicherheit auf Anwendungsebene verhindert, dass Mandanten auf Anwendungsdaten eines anderen Mandanten zugreifen oder diese ändern. Die Anwendung von Wrike verfügt über umfangreiche Authentifizierungs-, rollenbasierte Zugriffssteuerungs-, Autorisierungs- und Datenfreigabe- und Kontrollmechanismen (siehe und die nur autorisierten Benutzern den Datenzugriff https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles https://help.wrike.com/hc/en-us/articles/209602969) ermöglichen. Darüber hinaus wird die ruhende Verschlüsselung für Benutzerdateien angewendet, die auf #A0 im Dateispeicher über Webanwendung und API hochgeladen wurden. die Dateien werden automatisch mithilfe der AES-256-Bit-Verschlüsselung verschlüsselt. Darüber hinaus werden alle Server im Ruhetag mithilfe der Dateisystemverschlüsselung verschlüsselt. Darüber hinaus bietet Wrike Wrike Lock-Add-In für den von einem Kunden verwalteten Verschlüsselungsschlüssel an, siehe https://www.wrike.com/add-on-wrike-lock/ und https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock . Als zusätzliche Ebene der Datensicherheit bietet Wrike Überwachungs- und Berichtsfunktionen, mit deren Rahmen Administratoren vollständige Sicherheitsüberprüfungen durchführen und gleichzeitig die Sichtbarkeit der Vorgänge in ihrem Wrike-Konto erhöhen können. Weitere Details finden Sie unter https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports . Schließlich bietet Wrike Funktionen, die die detaillierte Nachverfolgung von Zugriffsrollen ermöglichen, um Kunden dabei zu unterstützen, die vorhandene Datenfreigabe vollständig zu überwachen, siehe Details unter https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports .
Der Zugriff auf Kundendaten kann in zwei Fällen berücksichtigt werden:
- Zugriff durch das Wrike-Support-Team: Bei Problembehandlung oder Überprüfung des Problems ist Support erforderlich, um auf Ihr Konto zu zugreifen; dass der Zugriff nur von Ihnen gewährt werden kann. Dies wird durch ein vom System generiertes Sicherheitstoken aktiviert, das Sie unserem Supportteam out of band zur Verfügung stellen, sodass der Support sich für einen begrenzten Zeitraum tiefer in die Lösung Ihres Problems einmischen kann. Dieser systemische Ansatz gewährleistet zusätzliche Vertraulichkeit für Ihre in Wrike gespeicherten Daten.
- Zugriff durch das Wrike Operational-Team: Das Team von Wrike Operational ist für die Wartung und Unterstützung der Produktionsumgebung zuständig, einschließlich Überwachung, Patchen und Aktualisieren, Bereitstellung der neuen Builds an die Produktion usw. Der Zugriff in diesem Fall ist sowohl aus verfahrenstechnischen als auch aus technischen Aspekten strengstens untersagt, und strenge Autorisierungskontrollen, einschließlich, aber nicht beschränkter VPN-, 2FA- und persönlichen Zertifikate, werden ebenfalls in Details mithilfe von HIDS (Host-based Intrusion Detection System) überwacht und vom Wrike Operational Security-Team überprüft. Im Fall von Amazon KMS (Wrike Lock-Funktionalität) werden die Kundendaten verschlüsselt in der Wrike-Datenbank gespeichert, sodass die Daten nicht direkt oder indirekt vom Wrike Operational-Team verfügbar sind, da die Daten mithilfe des Zugriffs auf amazon KMS des Kunden entschlüsselt werden können, der nur vom Kunden verwaltet und gesteuert wird.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

