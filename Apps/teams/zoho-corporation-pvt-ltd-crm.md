---
title: Anwendungsinformationen für Zoho CRM von Zoho Corporation Pvt Ltd
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Zoho CRM, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security#A0 und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2e04101b9b993f17decec407aa3dbcc603b136f5
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096222"
---
# <a name="zoho-crm"></a>Zoho CRM

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://teams.microsoft.com/l/app/003a8a54-9d27-41cd-9c28-aec5875a3497" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382094" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Der Zoho Corporation Pvt Ltd an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Zoho CRM |
| ID | WA104382094 |
| Funktionen | Bot, Registerkarte, Messaging-Erweiterung |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Zoho Corporation Pvt Ltd |
| URL der Partnerwebsite | [https://www.zoho.com/](https://www.zoho.com/) |
| URL Teams Anwendungsinfoseite | [https://www.zoho.com/crm/help/microsoft-teams-integration.h...](https://www.zoho.com/crm/help/microsoft-teams-integration.html) |
| URL der Datenschutzrichtlinie | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| URL der Nutzungsbedingungen | [https://www.zoho.com/crm/zohocrm-terms.html](https://www.zoho.com/crm/zohocrm-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von der Zoho Corporation Pvt Ltd. bereitgestellt, um zu erfahren, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegierte | Die Kalenderordner-ID wird gespeichert, um die Kontakte von Zoho CRM mit Microsoft &amp; umgekehrt zu synchronisieren. Kalenderinformationen wie event_name, event_location, participant_details werden gespeichert. | Ermöglicht dem Benutzer das Synchronisieren von Office365-Ereignissen mit Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.ReadWrite | delegierte | Die Kontaktordner-ID wird gespeichert, um die Kontakte von Zoho CRM mit Microsoft &amp; zu synchronisieren, umgekehrt. Kontaktinformationen wie first_name, last_name, E-Mail-Adresse werden gespeichert. | Ermöglicht dem Benutzer das Synchronisieren von Office365-Kontakten mit Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | delegierte |  | Ermöglicht dem Benutzer das Importieren der Office365-Datei in Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.All | delegierte |  | Ermöglicht dem Benutzer das Importieren der Office365-Datei in Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | delegierte | UserPrincipalName wird zur Benutzeridentifikation gespeichert | Ermöglicht dem Benutzer das Importieren der Office365-Datei in Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | delegierte | Benutzereigenschaften wie first_name, last_name, E-Mail-Adresse. | Grundlegende Profile aller Benutzer lesen | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | delegierte | UserPrincipaName wird für den Benutzereinzug gespeichert | Anzeigen der E-Mail-Adresse des Benutzers | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | delegierte |  | Den Zugriff auf Daten beibehalten, auf die Sie ihr Zugriff gewährt haben | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Profil | delegierte |  | Grundlegendes Profil des Benutzers anzeigen | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Auf EUII wird nicht zugegriffen.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir sammeln EUII/PII nicht in Telemetrie und Protokollen. Wir verfügen über Skripts, um nach sichtbaren Daten zu suchen und sie zu warnen.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Der Kunde kann die Daten auswählen, die über EAR (Encryption At Rest) mit Certaat-Einschränkungen verschlüsselt werden müssen. Kennwörter werden standardmäßig als Hash verwendet. Der logische Zugriff auf die Server erfolgt über ein isoliertes &amp; dediziertes Netzwerk und ist hochgradig gesichert und


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

