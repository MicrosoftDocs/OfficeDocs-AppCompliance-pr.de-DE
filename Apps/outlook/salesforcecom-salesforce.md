---
title: Anwendungsinformationen für Salesforce nach salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Salesforce, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: b5999dd08ed27ce75bc958e431c0974e10830a3c
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281697"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von salesforce.com an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Salesforce |
| ID | WA104379334 |
| Office 365 unterstützten Clients | Outlook 2013 oder höher auf Windows, Outlook 2016 oder höher auf dem Mac Outlook im Web |
| Name des Partnerunternehmens | salesforce.com |
| URL der Partnerwebsite | [https://www.salesforce.com](https://www.salesforce.com) |
| URL der Datenschutzrichtlinie | [https://www.salesforce.com/company/privacy/](https://www.salesforce.com/company/privacy/) |
| URL der Nutzungsbedingungen | [https://store.office.com/en-us/WebAppLandingPage.aspx?p4=TC...](https://store.office.com/en-us/WebAppLandingPage.aspx?p4=TC&amp;p5=WA104379334&amp;cmu=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von salesforce.com darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>Diese Anwendung verwendet microsoft Graph nicht.

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, können zusätzliche andere Microsoft-APIs als Microsoft Graph verwenden, um Organisationsdaten zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft auf, Graph diese App verwendet.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| JavaScript-API für Office | Ja | Das Add-In verwendet Funktionen aus Office.js und EWS, um Inhalte und Anlagen zu einer E-Mail zu kopieren, die ein Outlook Benutzer sich bei Salesforce angemeldet hat. Ähnliche Funktionen werden auf kalenderseitiger Seite verwendet, um Termine in Salesforce zu protokollieren. |  | Das Add-In verwendet Funktionen wie getUserIdentityTokenAsync, um die aktuelle Outlook Benutzeridentität abzurufen. GetItem (.js and EWS) to get and set AdditionalProperties and the content of the current email message when saving to Salesforce records, GetAttachment (EWS) to retrieve the attachments from Exchange and add to the paired Salesforce email, UpdateItem (.js), GetFolder (.js) to get the drafts folder, CreateItem (.js), which is used to create a draft message. |  |
>| Exchange-Webdienste (Exchange Web Services, EWS) | Ja | Das Add-In verwendet Funktionen aus Office.js und EWS, um Inhalte und Anlagen zu einer E-Mail zu kopieren, die ein Outlook Benutzer sich bei Salesforce angemeldet hat. Ähnliche Funktionen werden auf kalenderseitiger Seite verwendet, um Termine in Salesforce zu protokollieren. |  | Das Add-In verwendet Funktionen wie getUserIdentityTokenAsync, um die aktuelle Outlook Benutzeridentität abzurufen. GetItem (.js and EWS) to get and set AdditionalProperties and the content of the current email message when saving to Salesforce records, GetAttachment (EWS) to retrieve the attachments from Exchange and add to the paired Salesforce email, UpdateItem (.js), GetFolder (.js) to get the drafts folder, CreateItem (.js), which is used to create a draft message. |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Nein

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Salesforce-Speicher wird im Sicherheitshandbuch unter https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

