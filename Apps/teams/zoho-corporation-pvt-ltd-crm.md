---
title: Anwendungsinformationen für Zoho CRM von Zoho Corporation Pvt Ltd
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Zoho CRM, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 5448307eeccd20e77b25282f299b52b094077b82
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550505"
---
# <a name="zoho-crm"></a>Zoho CRM

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://teams.microsoft.com/l/app/003a8a54-9d27-41cd-9c28-aec5875a3497" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382094" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Von Zoho Corporation Pvt Ltd an Microsoft zur Verfügung gestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Zoho CRM |
| ID | WA104382094 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Zoho Corporation Pvt Ltd |
| URL der Partner-Website | [https://www.zoho.com/](https://www.zoho.com/) |
| URL Teams Anwendungsinfoseite | [https://www.zoho.com/crm/help/microsoft-teams-integration.h...](https://www.zoho.com/crm/help/microsoft-teams-integration.html) |
| URL der Datenschutzrichtlinie | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| URL der Nutzungsbedingungen | [https://www.zoho.com/crm/zohocrm-terms.html](https://www.zoho.com/crm/zohocrm-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Zoho Corporation Pvt Ltd darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Delegiert | Die Kalenderordner-ID wird gespeichert, um die Kontakte von Zoho CRM mit Microsoft &amp; zu synchronisieren. Kalenderinformationen wie event_name, event_location, participant_details werden gespeichert. | Ermöglicht dem Benutzer, Office365-Ereignisse mit Zoho CRM zu synchronisieren. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.ReadWrite | Delegiert | Die Ordner-ID für Kontakte wird gespeichert, um die Kontakte von Zoho CRM mit Microsoft &amp; zu synchronisieren. Kontaktinformationen wie first_name, last_name, E-Mail-Adresse werden gespeichert. | Ermöglicht dem Benutzer die Synchronisierung von Office365-Kontakten mit Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | Delegiert |  | Ermöglicht dem Benutzer das Importieren der Office365-Datei in Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.All | Delegiert |  | Ermöglicht dem Benutzer das Importieren der Office365-Datei in Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | Delegiert | UserPrincipalName wird zur Benutzeridentifikation gespeichert | Ermöglicht dem Benutzer das Importieren der Office365-Datei in Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | Delegiert | Benutzereigenschaften wie first_name, last_name, E-Mail-Adresse. | Grundlegende Profile aller Benutzer lesen | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | Delegiert | UserPrincipaName wird für die Benutzerindentifizierung gespeichert | E-Mail-Adresse des Benutzers anzeigen | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | Delegiert |  | Den Zugriff auf Daten beibehalten, auf die Sie ihr Zugriff gewährt haben | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Profil | Delegiert |  | Grundlegendes Profil des Benutzers anzeigen | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird kein EUII abgerufen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Wir sammeln keine EUII / PII in Telemetrie und Protokollen. Wir haben Skripte zur Suche und Warnung, um solche Daten zu beheben, die sichtbar sind.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Der Kunde kann die Daten, die verschlüsselt werden müssen, über EAR (Encryption At Rest) mit Certaat-Einschränkungen auswählen. Kennwörter werden standardmäßig gehasht. Der logische Zugriff auf die Server erfolgt über ein isoliertes &amp; dediziertes Netzwerk und ist


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

