---
title: Anwendungsinformationen für Wrike für Office Dokumente von Wrike Inc.
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Wrike für Office Dokumente, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 87656417cb587e3778ddf85f2c20766b3a43cf86
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/02/2021
ms.locfileid: "53282339"
---
# <a name="wrike-for-office-documents"></a>Wrike for Office Documents

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Zuletzt aktualisiert vom Entwickler am: 23. März 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379841" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Wrike Inc. für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Wrike for Office Documents |
| ID | WA104379841 |
| Office 365 unterstützten Clients | Excel 2016 oder höher auf Windows, Word 2013 oder höher am Windows, PowerPoint 2013 oder höher auf Windows, Excel 2016 oder höher auf Mac, Excel im Web, Word 2016 oder höher auf Mac, Word im Web, PowerPoint 2016 oder höher auf dem Mac PowerPoint im Web |
| Name des Partnerunternehmens | Wrike Inc. |
| URL der Partnerwebsite | [https://www.wrike.com/](https://www.wrike.com/) |
| URL der Datenschutzrichtlinie | [https://www.wrike.com/privacy/](https://www.wrike.com/privacy/) |
| URL der Nutzungsbedingungen | [https://www.wrike.com/terms/](https://www.wrike.com/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Wrike Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>Diese Anwendung verwendet microsoft Graph nicht.

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, können zusätzliche andere Microsoft-APIs als Microsoft Graph verwenden, um Organisationsdaten zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft auf, Graph diese App verwendet.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| JavaScript-API für Office | Ja | Das Add-In verwendet die Office.js-API zur Integration in die Office Anwendung. |  | In den Datenbanken von Wrike werden keine Organisationsdaten gespeichert. |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike verfügt über die Integrationen mit den folgenden Anbietern, die Zugriff auf einige Daten haben: Marketo ist E-Mail-Lead, der Dienste erfasst – nur Namen und E-Mails werden ihnen zur Verfügung gestellt. Die Reichweite ist cloudbasiertes Vertriebsengagement – ihnen werden nur Namen und E-Mails bereitgestellt. Salesforce CRM-System – enthält Kontaktinformationen und Abrechnungsinformationen (keine vertraulichen Daten) von Kunden. Zuora – Abrechnungs- und Rechnungskunden. Es gibt eine Datenschutzbehörde für alle Anbieter. |  | Wir verwenden js Office API, aber wir sammeln/verarbeiten/speichern keine Organisationsinformationen. |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Nein

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wrike verfügt über eine mehrinstanzenfähige Architektur, die Kunden logisch&#8217; Daten über die Zugriffssteuerung basierend auf Kundenmetadaten trennt. Diese Metadaten sind dem jeweiligen Mandanten und seinen Zugriffsrechten gemäß den rollenbasierten Zugriffsregeln innerhalb des bestimmten Wrike-Kontos zugeordnet. Daten sind logisch isoliert und getrennt, und der Zugriff auf Daten ist nur über die Anwendung verfügbar, um Sicherheit und Datenschutz zu gewährleisten. Die Sicherheit auf Anwendungsebene verhindert, dass Mandanten auf Anwendungsdaten zugreifen oder diese ändern, die einem anderen Mandanten gehören. Wrikes Anwendung verfügt über umfassende Authentifizierungs-, rollenbasierte Zugriffssteuerungs-, Autorisierungs- und Datenfreigabe- und Steuerungsmechanismen (siehe https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles und https://help.wrike.com/hc/en-us/articles/209602969) die nur autorisierten Benutzern den Datenzugriff ermöglichen. Darüber hinaus wird die ruhenden Verschlüsselung für Benutzerdateien angewendet, die auf Wrike-Server im Dateispeicher über Webanwendung und API hochgeladen wurden. Die Dateien werden automatisch mit der 256-Bit-AES-Verschlüsselung verschlüsselt. Darüber hinaus werden alle Server im Ruhezustand mithilfe der Dateisystemverschlüsselung verschlüsselt, und darüber hinaus bietet Wrike Wrike Lock-Add-In für Verschlüsselungsschlüssel, die von einem Kunden verwaltet werden, siehe https://www.wrike.com/add-on-wrike-lock/ und https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock . Als zusätzliche Ebene der Datensicherheit bietet Wrike Überwachungs- und Berichtsfunktionen, mit denen Administratoren vollständige Sicherheitsüberprüfungen durchführen und gleichzeitig den Einblick in die Vorgänge in ihrem Wrike-Konto erhöhen können. Weitere Informationen finden Sie unter https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports . Schließlich bietet Wrike Funktionen, die die präzise Nachverfolgung von Zugriffsrollen ermöglichen, um Kunden bei der vollständigen Überwachung der vorhandenen Datenfreigabe zu unterstützen. Weitere Informationen finden Sie unter https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports .
Der Zugriff auf Kundendaten kann in zwei Fällen berücksichtigt werden:
- Zugriff durch das Wrike-Supportteam: bei der Problembehandlung oder -überprüfung muss der Support auf Ihr Konto zugreifen; Dieser Zugriff kann nur von Ihnen gewährt werden. Dies wird durch ein vom System generiertes Sicherheitstoken aktiviert, das Sie out of band für unser Supportteam bereitstellen, sodass der Support sich für einen begrenzten Zeitraum eingehender mit der Lösung Ihres Problems befassen kann. Dieser berauschte Ansatz gewährleistet zusätzliche Vertraulichkeit für Ihre in Wrike gespeicherten Daten.
- Zugriff durch wrike Operational team: Wrike Operational team is responsible to maintenance and support production environment including monitoring, patching and updating, delivery the new builds to production, etc. Der Zugriff ist in diesem Fall sowohl aus verfahrenstechnischen als auch aus technischen Aspekten strengstens untersagt, und strenge Autorisierungskontrollen, einschließlich, aber nicht beschränkter VPN- und 2FA-Zertifikate, werden darüber hinaus mithilfe von HIDS (Host-based Intrusion Detection System) detailliert überwacht und vom Wrike Operational Security-Team überprüft. Im Fall von Amazon KMS (Wrike Lock-Funktion) werden die Kundendaten verschlüsselt in der Wrike-Datenbank gespeichert, sodass die Daten nicht direkt oder indirekt vom Wrike Operational-Team verfügbar sind, da die Daten mithilfe des Zugriffs auf die Amazon-KMS des Kunden entschlüsselt werden können, die nur vom Kunden verwaltet und gesteuert werden.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

