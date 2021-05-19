---
title: Anwendungsinformationen für Zoho Sprints von Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Zoho Sprints, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: fc19b083312c4c8222b894ae6bb35b0bbdd5314e
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552676"
---
# <a name="zoho-sprints"></a>Zoho Sprints

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://teams.microsoft.com/l/app/153059f1-912e-45d6-a13a-037675d66974" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000188" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Zoho Corporation Private Limited an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Zoho Sprints |
| ID | WA200000188 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Zoho Corporation Private Limited |
| URL der Partner-Website | [https://www.zoho.com/sprints/](https://www.zoho.com/sprints/) |
| URL der Datenschutzrichtlinie | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| URL der Nutzungsbedingungen | [https://www.zoho.com/terms.html](https://www.zoho.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Zoho Corporation Private Limited darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Delegiert | alendar Ordner-ID wird gespeichert, um die Kontakte von Zoho Sprints mit Microsoft umgekehrt zu &amp; synchronisieren. |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.ReadWrite | Delegiert | Kontakte Ordner-ID wird gespeichert, um die Kontakte zu synchronisieren. |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.All | Delegiert |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | Delegiert | UserPrincipalName wird zur Benutzeridentifikation gespeichert. | Lesezugriff auf Dateien, die der Benutzer auswählt | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | Delegiert |  | Anmelden und Benutzerprofil lesen | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | Delegiert |  | Erlauben Sie Benutzern, Office365-Benutzer in Zoho Sprints zu importieren. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | Delegiert |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | Delegiert |  | Den Zugriff auf Daten beibehalten, auf die Sie ihr Zugriff gewährt haben | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird kein EUII abgerufen.


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

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35375' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35375" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

