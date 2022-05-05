---
title: Übersicht über Wrike für Office-Dokumente
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Wrike für Office Dokumente, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c4407cdf68b92369e45c798ef76e051980e6c23a
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225619"
---
# <a name="wrike-for-office-documents-overview"></a>Übersicht über Wrike für Office-Dokumente

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Letzte Aktualisierung durch den Entwickler am: 23. März 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379841" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Wrike Inc. an Microsoft bereitgestellte Informationen:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | Wrike für Office Dokumente |
| ID | WA104379841 |
| unterstützte Office 365 Clients | Excel 2016 oder höher auf Windows, Word 2013 oder höher auf Windows, PowerPoint 2013 oder höher auf Windows, Excel 2016 oder höher auf Mac, Excel im Web, Word 2016 oder höher auf dem Mac, Word im Web, PowerPoint 2016 oder höher auf dem Mac, PowerPoint im Web |
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

Auflisten aller [Microsoft Graph Berechtigungen](/graph/permissions-reference), die diese App benötigt.

>Diese Anwendung verwendet keine Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise andere Microsoft-APIs als Microsoft Graph, um Organisationsinformationen (OII) zu sammeln oder zu verarbeiten. Auflisten aller anderen Microsoft-APIs als Microsoft Graph, die diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Begründung für das Sammeln von OII?** | **Ist OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| JavaScript-API für Office | Ja | Das Add-In verwendet die Office.js-API zur Integration in die Office Anwendung. |  | In den Datenbanken von Wrike werden keine Organisationsdaten gespeichert. |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder freigibt, listen Sie den von der App nicht von Microsoft stammenden Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII wird übertragen an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike hat die Integrationen mit den folgenden Anbietern, die Zugriff auf einige Daten haben: Marketo ist E-Mail-Lead-Erfassungsdienste - nur Namen und E-Mails werden ihnen bereitgestellt. Outreach ist cloudbasiertes Vertriebsengagement – ihnen werden nur Namen und E-Mails zur Verfügung gestellt. Salesforce CRM-System – enthält Kontaktinformationen und Abrechnungsinformationen (keine vertraulichen Daten) von Kunden. Zuora – Abrechnungs- und Rechnungskunden. Es gibt eine DPA für alle Anbieter. |  | Wir verwenden JS Office API, sammeln/verarbeiten/speichern jedoch keine Organisationsinformationen. |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder Endbenutzer-identifizierbare Informationen (EUII) in den Telemetriedaten oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Aufbewahrungs- und Entfernungsrichtlinien gelten?

>Nein

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren der Organisation ihre Informationen in Partnersystemen steuern können? z.B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wrike verfügt über eine mehrinstanzenfähige Architektur, die Kunden logisch durch Zugriffssteuerung basierend auf Kundenmetadaten&#8217; Daten trennt. Diese Metadaten sind dem jeweiligen Mandanten und seinen Zugriffsrechten gemäß den rollenbasierten Zugriffsregeln innerhalb des spezifischen Wrike-Kontos zugeordnet. Daten sind logisch isoliert und getrennt, und der Zugriff auf Daten ist nur über die Anwendung verfügbar, um Sicherheit und Datenschutz zu gewährleisten. Die Sicherheit auf Anwendungsebene verhindert, dass Mandanten auf Anwendungsdaten zugreifen oder diese ändern, die einem anderen Mandanten gehören. Die Wrike-Anwendung verfügt über umfassende Authentifizierungs-, rollenbasierte Zugriffssteuerungs-, Autorisierungs- und Datenfreigabe- und -steuerungsmechanismen (siehe https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles und https://help.wrike.com/hc/en-us/articles/209602969) die nur autorisierten Benutzern den Datenzugriff erlauben. Darüber hinaus wird die verschlüsselung im Ruhezustand für Benutzerdateien angewendet, die über Webanwendung und API auf Wrike-Server im Dateispeicher hochgeladen werden. die Dateien werden automatisch mithilfe der AES-256-Bit-Verschlüsselung verschlüsselt. Darüber hinaus werden alle Server im Ruhezustand mithilfe der Dateisystemverschlüsselung verschlüsselt, und darüber hinaus bietet Wrike Lock-Add-In für Verschlüsselungsschlüssel, die von einem Kunden verwaltet werden, siehe https://www.wrike.com/add-on-wrike-lock/ und https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock. Als zusätzliche Ebene der Datensicherheit bietet Wrike Überwachungs- und Berichterstellungsfunktionen, die es Administratoren ermöglichen, vollständige Sicherheitsüberprüfungen durchzuführen und gleichzeitig die Sichtbarkeit der Ereignisse in ihrem Wrike-Konto zu verbessern, weitere Details finden Sie unter https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports. Schließlich bietet Wrike Funktionen, die die präzise Nachverfolgung von Zugriffsrollen ermöglichen, um Kunden bei der vollständigen Überwachung vorhandener Datenfreigaben zu helfen. Details finden Sie unter https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports.
Der Zugriff auf Kundendaten kann in zwei Fällen berücksichtigt werden:
- Zugriff durch das Wrike-Supportteam: Für den Fall der Problembehandlung oder der Überprüfung des Problems ist der Support für den Zugriff auf Ihr Konto erforderlich. dieser Zugriff kann nur von Ihnen gewährt werden. Dies wird durch ein vom System generiertes Sicherheitstoken ermöglicht, das Sie außerhalb des Bandes an unser Supportteam bereitstellen, sodass der Support für einen begrenzten Zeitraum tiefer in die Lösung Ihres Problems eintauchen kann. Dieser systemische Ansatz gewährleistet zusätzliche Vertraulichkeit für Ihre in Wrike gespeicherten Daten.
- Zugriff durch das Wrike Operational-Team: Das Wrike Operational-Team ist für die Wartung und Unterstützung der Produktionsumgebung einschließlich Überwachung, Patching und Aktualisierung, Bereitstellung der neuen Builds an die Produktion usw. verantwortlich. Der Zugriff in diesem Fall ist sowohl aus verfahrenstechnischen als auch aus technischen Aspekten strengstens untersagt, und starke Autorisierungskontrollen, einschließlich, aber nicht beschränkt auf VPN, 2FA und persönliches Zertifikat, sind vorhanden, darüber hinaus wird es in Details mithilfe von HIDS (Host-based Intrusion Detection System) überwacht und vom Wrike Operational Security-Team überprüft. Im Falle von Amazon KMS (Wrike Lock-Funktionalität) werden die Kundendaten verschlüsselt in der Wrike-Datenbank gespeichert, sodass die Daten nicht direkt oder indirekt vom Wrike Operational-Team verfügbar sind, da die Daten über den Zugriff auf die Amazon-KMS des Kunden entschlüsselt werden können, die nur vom Kunden verwaltet und kontrolliert wird.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational Identifiable Information) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">Auf einer neuen Registerkarte anzeigen</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

