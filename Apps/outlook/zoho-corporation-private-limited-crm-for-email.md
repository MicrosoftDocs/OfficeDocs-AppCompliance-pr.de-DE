---
title: Anwendungsinformationen für Zoho CRM für E-Mails von Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 09/04/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Zoho CRM für E-Mails, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2d18e904a02190310c94dde3010c2db103705b32
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410519"
---
# <a name="zoho-crm-for-email"></a>Zoho CRM für E-Mails

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379468" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Zoho Corporation Private Limited für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Zoho CRM für E-Mails |
| ID | WA104379468 |
| Office 365 unterstützten Clients | Outlook 2013 oder höher auf Windows, Outlook 2016 oder höher für Mac Outlook im Web |
| Name des Partnerunternehmens | Zoho Corporation Private Limited |
| URL der Partnerwebsite | [https://www.zoho.com/](https://www.zoho.com/) |
| URL der Datenschutzrichtlinie | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| URL der Nutzungsbedingungen | [https://www.zoho.com/crm/zohocrm-terms.html](https://www.zoho.com/crm/zohocrm-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Zoho Corporation Private Limited zur Verfügung gestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | Delegiert | Die Kalenderordner-ID wird gespeichert, um die Kontakte von Zoho CRM mit Microsoft &amp; zu synchronisieren. Kalenderinformationen wie event_name, event_location und participant_details werden gespeichert. | Ermöglicht es dem Benutzer, Office365-Ereignisse mit Zoho CRM zu synchronisieren. | [f6d7187a-b437-4eca-bc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| Contacts.ReadWrite | Delegiert | Die Kontaktordner-ID wird gespeichert, um die Kontakte von Zoho CRM mit Microsoft &amp; zu synchronisieren. Kontaktinformationen wie first_name, last_name und E-Mail-Adresse werden gespeichert. | Ermöglicht es dem Benutzer, Office365-Kontakte mit Zoho CRM zu synchronisieren. | [f6d7187a-b437-4eca-bc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| Files.Read | Delegiert |  | Ermöglicht dem Benutzer, die Office365-Datei in Zoho CRM zu importieren. | [f6d7187a-b437-4eca-bc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| Files.Read.All | Delegiert |  | Ermöglicht dem Benutzer, die Office365-Datei in Zoho CRM zu importieren. | [f6d7187a-b437-4eca-bc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| Files.Read.Selected | Delegiert | UserPrincipalName wird zur Benutzeridentifikation gespeichert. | Ermöglicht dem Benutzer, die Office365-Datei in Zoho CRM zu importieren. | [f6d7187a-b437-4eca-bc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| User.ReadBasic.All | Delegiert | Benutzereigenschaften wie first_name, last_name, E-Mail-Adresse. | Grundlegende Profile aller Benutzer lesen | [f6d7187a-b437-4eca-bc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| email | Delegiert | UserPrincipaName wird für die Einrückung des Benutzers gespeichert. | Anzeigen der E-Mail-Adresse des Benutzers | [f6d7187a-b437-4eca-bc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| offline_access | Delegiert |  | Den Zugriff auf Daten beibehalten, auf die Sie ihr Zugriff gewährt haben | [f6d7187a-b437-4eca-bc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| Profil | Delegiert |  | Anzeigen des grundlegenden Profils des Benutzers | [f6d7187a-b437-4eca-bc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir erfassen keine EUII/PII in Telemetrie und Protokollen. Wir verfügen über Skripts, nach denen gesucht und darauf hingewiesen werden kann, dass solche Daten korrigiert werden.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Der Kunde kann die Daten auswählen, die über EAR (Encryption At Rest) mit Certaat-Einschränkungen verschlüsselt werden müssen. Kennwörter werden standardmäßig mit einem Hash versehen. Der logische Zugriff auf die Server wird über ein isoliertes dediziertes Netzwerk bereitgestellt &amp; und ist hochgradig gesichert und


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


