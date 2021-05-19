---
title: Anwendungsinformationen für ServiceDesk Plus Cloud von Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für ServiceDesk Plus Cloud, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 04797702995180e8a0a5305e88d49903eff80690
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550545"
---
# <a name="servicedesk-plus-cloud"></a>ServiceDesk Plus Cloud

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://teams.microsoft.com/l/app/04fdcea1-3511-499c-966d-099d59aef45f" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000037" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Zoho Corporation Private Limited an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | ServiceDesk Plus Cloud |
| ID | WA200000037 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Zoho Corporation Private Limited |
| URL der Partner-Website | [https://www.manageengine.com/products/service-desk](https://www.manageengine.com/products/service-desk) |
| URL Teams Anwendungsinfoseite | [https://help.sdpondemand.com/servicedeskplus_cloud_for_teams](https://help.sdpondemand.com/servicedeskplus_cloud_for_teams) |
| URL der Datenschutzrichtlinie | [https://www.manageengine.com/privacy.html](https://www.manageengine.com/privacy.html) |
| URL der Nutzungsbedingungen | [https://ondemand.manageengine.com/terms.html](https://ondemand.manageengine.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Zoho Corporation Private Limited darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Anwendung |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | Delegiert |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | Delegiert |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | Delegiert | E-Mail-ID des Benutzers. | Ermöglicht dem Benutzer die Anmeldung und gewährt der App Zugriff auf seinen UPN, um die automatische Anmeldung zu aktivieren. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read.All | Anwendung |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | Delegiert | E-Mail-ID, Name, Mitarbeiter-ID, Job-Titel, Telefon, Mobile, Website, Abteilung, Gebietsschema, Profilfoto des Benutzers. | Ermöglicht das Importieren der grundlegenden Informationen der Benutzer aus Azure Active Directory. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | Delegiert | E-Mail-ID des Benutzers. | Hier wird die E-Mail-Adresse des Benutzers angezeigt. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | Delegiert |  | Behalten Sie den Zugriff auf Daten aufrecht, auf die Sie ihr Zugriff gewährt haben. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Profil | Delegiert |  | Zeigen Sie das Basisprofil des Benutzers an. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird kein EUII abgerufen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Wir sammeln keine EUII / PII in Telemetrie / Protokolle. Wir haben Skripte an Ort und Stelle, die nach Mustern und Warnungen suchen, um es zu beheben

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Alle Daten werden bei REST verschlüsselt. Nur autorisierte Personen haben Zugang zu dem System, das ohnehin zugriffsgeschützt ist und für alle Arten von Zugriff vollständig geprüft ist. MFA für den Zugriff eingerichtet, werden autorisierte Konten in einem Unternehmensverzeichnis und


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

