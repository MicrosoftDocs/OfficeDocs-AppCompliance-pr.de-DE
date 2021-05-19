---
title: Anwendungsinformationen für Zoho Campaigns Tool für Marketingautomatisierung von Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für das Zoho Campaigns-Tool für die Marketingautomatisierung, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: e67de0ca2871d5432b5a29ead52194225bc51c9a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553686"
---
# <a name="zoho-campaigns-tool-for-marketing-automation"></a>Zoho Campaigns Tool für die Marketingautomatisierung

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380835" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Zoho Corporation Private Limited an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Zoho Campaigns Tool für die Marketingautomatisierung |
| ID | WA104380835 |
| Office 365 unterstützten Clients | Outlook 2013 oder später Windows, Outlook 2016 oder später auf Mac, Outlook im Web |
| Name des Partnerunternehmens | Zoho Corporation Private Limited |
| URL der Partner-Website | [https://www.zoho.com/](https://www.zoho.com/) |
| URL der Datenschutzrichtlinie | [https://zoho.com/privacy.html](https://zoho.com/privacy.html) |
| URL der Nutzungsbedingungen | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=de-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Zoho Corporation Private Limited darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | Delegiert | Die Kalender-ID wird gespeichert, um Ereignisse in diesem Kalender aus Zoho-Kampagnen zu erstellen. | Ermöglicht es dem Benutzer, Office365-Kalenderereignis in Zoho-Kampagnen zu importieren. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Calendars.ReadWrite | Delegiert |  | Ermöglicht es dem Benutzer, Zoho-Kampagnen-Ereignisse zum Office365-Kalender hinzuzufügen. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.Read | Delegiert |  So speichern Sie die Kontaktinformationen. | Ermöglicht dem Benutzer das Importieren von Office365-Kontakten in Zoho-Kampagnen. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.ReadWrite | Delegiert |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | Delegiert |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | Delegiert |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | Delegiert | E-Mail wird zur Benutzeridentifikation gespeichert. |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | Delegiert |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Profil | Delegiert |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Wir sammeln keine EUII / PII in Telemetrie und Protokollen. Wir haben Skripte zur Suche und Warnung, um zu beheben, dass solche Daten sichtbar sind.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Der Kunde kann die Daten, die verschlüsselt werden müssen, über EAR (Encryption At Rest) mit Certaat-Einschränkungen auswählen. Kennwörter werden standardmäßig gehasht. Der logische Zugriff auf die Server erfolgt über ein isoliertes &amp; dediziertes Netzwerk und ist


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/28293' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/28293" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

