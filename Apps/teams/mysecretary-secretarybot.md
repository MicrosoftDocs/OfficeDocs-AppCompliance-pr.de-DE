---
title: Anwendungsinformationen für SecretaryBot von MySecretary
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Informationen zu Sicherheits- und Complianceinformationen für SecretaryBot, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: bff3e6ebffc94861dc4112375ac943124b4fe386
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551885"
---
# <a name="secretarybot"></a>SecretaryBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://teams.microsoft.com/l/app/256ff1bc-fd16-4f82-aeb3-8a6977ff2ec4" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381085" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die MySecretary Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | SecretaryBot |
| ID | WA104381085 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | MySecretary |
| URL der Partner-Website | [https://secretarybot.wordpress.com/](https://secretarybot.wordpress.com/) |
| URL Teams Anwendungsinfoseite | [https://secretarybot.wordpress.com/faq/](https://secretarybot.wordpress.com/faq/) |
| URL der Datenschutzrichtlinie | [https://secretarybot.wordpress.com/privacy-policy/](https://secretarybot.wordpress.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://secretarybot.wordpress.com/terms-of-use/](https://secretarybot.wordpress.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von MySecretary darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read.Shared | Delegiert |  | Holen Sie sich die Freizeitinformationen der Benutzer und ihrer Kollegen ab. |  |
>| Calendars.ReadWrite | Delegiert |  | Senden Sie eine Besprechungsanfrage anstelle des Benutzers. |  |
>| MailboxSettings.Read | Delegiert | Store Sprache zum Anzeigen der korrekten Langage. Zeitzone sparen, um MS Graph Kalender-API korrekt aufzurufen | Rufen Sie die Sprache und die Zeitzoneneinstellung des Benutzers ab. |  |
>| People.Read | Delegiert |  | Versuchen Sie, Kollegen zu finden, die enge Beziehungen zum Benutzer haben. |  |
>| User.Read | Delegiert | Store Benutzername, Stadt, Land und langauge für Benutzeranalysen. Store E-Mail, um den Kunden zu kontaktieren. Wir haben nie E-Mail-Adresse verwendet, aber kann für den Support verwenden. | Versuchen Sie, das Land und die bevorzugte Sprache des Benutzers zu finden. Es wird für die Sicherung für MailboxSettings.Read verwendet. |  |
>| email | Delegiert | Siehe weiter oben. | Zum Speichern von E-Mails. |  |
>| openid | Delegiert |  | Für OpenID-Authentifizierung. |  |
>| Profil | Delegiert | Speichern Sie OID, um die eindeutige ID des Benutzers im MS-Identitätssystem zu identifizieren. | Abrufen von Benutzernamen und OID. Versuchen Sie, OID für die Verbindung Outlook Addin in der Zukunft zu verwenden. |  |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Verwenden Sie diese Ausg.:A., um Teambesprechungen zu planen | Nein |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>OII- oder EUII-Daten werden in der Telemetrie oder in den Protokollen angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Wir bieten den Endbenutzern noch keine administrative Kontrolle, aber wenn Endbenutzer uns auffordern, Daten zu löschen, können wir ihrer Anfrage folgen.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

