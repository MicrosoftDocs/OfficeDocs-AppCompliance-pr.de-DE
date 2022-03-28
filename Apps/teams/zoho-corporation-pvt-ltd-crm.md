---
title: Anwendungsinformationen für Zoho CRM von Zoho Corporation Pvt Ltd
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 09/04/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Zoho CRM, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: cf56e9462093336c45902e3c368b4d8498f7a499
ms.sourcegitcommit: d8a3d237c4bd435183b9ce95c316b4d7ce9d7201
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/23/2022
ms.locfileid: "63773446"
---
# <a name="zoho-crm"></a>Zoho CRM

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/003a8a54-9d27-41cd-9c28-aec5875a3497" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382094" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Zoho Corporation Pvt Ltd an Microsoft bereitgestellt werden:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | Zoho CRM |
| ID | WA104382094 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | Zoho Corporation Pvt Ltd |
| URL der Partnerwebsite | [https://www.zoho.com/](https://www.zoho.com/) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.zoho.com/crm/help/microsoft-teams-integration.h...](https://www.zoho.com/crm/help/microsoft-teams-integration.html) |
| URL der Datenschutzrichtlinie | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| URL der Nutzungsbedingungen | [https://www.zoho.com/crm/zohocrm-terms.html](https://www.zoho.com/crm/zohocrm-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von der Zoho Corporation Pvt Ltd bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | Delegiert | Die Kalenderordner-ID wird gespeichert, um die Kontakte von Zoho CRM mit Microsoft &amp; zu synchronisieren. Kalenderinformationen wie event_name, event_location und participant_details werden gespeichert. | Ermöglicht es dem Benutzer, Office365-Ereignisse mit Zoho CRM zu synchronisieren. | f6d7187a-b437-4eca-bc5-c1331609fe07 |
>| Contacts.ReadWrite | Delegiert | Die Kontaktordner-ID wird gespeichert, um die Kontakte von Zoho CRM mit Microsoft &amp; zu synchronisieren. Kontaktinformationen wie first_name, last_name und E-Mail-Adressen werden gespeichert. | Ermöglicht es dem Benutzer, Office365-Kontakte mit Zoho CRM zu synchronisieren. | f6d7187a-b437-4eca-bc5-c1331609fe07 |
>| Files.Read | Delegiert |  | Ermöglicht dem Benutzer, die Office365-Datei in Zoho CRM zu importieren. | f6d7187a-b437-4eca-bc5-c1331609fe07 |
>| Files.Read.All | Delegiert |  | Ermöglicht dem Benutzer, die Office365-Datei in Zoho CRM zu importieren. | f6d7187a-b437-4eca-bc5-c1331609fe07 |
>| Files.Read.Selected | Delegiert | UserPrincipalName wird zur Benutzeridentifikation gespeichert. | Ermöglicht dem Benutzer, die Office365-Datei in Zoho CRM zu importieren. | f6d7187a-b437-4eca-bc5-c1331609fe07 |
>| User.ReadBasic.All | Delegiert | Benutzereigenschaften wie first_name, last_name, E-Mail-Adresse. | Grundlegende Profile aller Benutzer lesen | f6d7187a-b437-4eca-bc5-c1331609fe07 |
>| email | Delegiert | UserPrincipaName wird für die Einrückung des Benutzers gespeichert. | Anzeigen der E-Mail-Adresse des Benutzers | f6d7187a-b437-4eca-bc5-c1331609fe07 |
>| offline_access | Delegiert |  | Den Zugriff auf Daten beibehalten, auf die Sie ihr Zugriff gewährt haben | f6d7187a-b437-4eca-bc5-c1331609fe07 |
>| profile | Delegiert |  | Anzeigen des grundlegenden Profils des Benutzers | f6d7187a-b437-4eca-bc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Personenbezogene Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir erfassen keine EUII/PII in Telemetrie und Protokollen. Wir verfügen über Skripts, nach denen gesucht und darauf hingewiesen werden kann, dass solche Daten korrigiert werden.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Der Kunde kann die Daten auswählen, die über EAR (Encryption At Rest) mit Certaat-Einschränkungen verschlüsselt werden müssen. Kennwörter werden standardmäßig mit einem Hash versehen. Der logische Zugriff auf die Server wird über ein isoliertes &amp; dediziertes Netzwerk bereitgestellt und ist hochgradig gesichert und


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

