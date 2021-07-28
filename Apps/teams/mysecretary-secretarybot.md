---
title: Anwendungsinformationen für Denkbot von MySecretar
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Denbot, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8d7e2fce37cf43fe52cb050e85aa9e4fd5e00802
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525449"
---
# <a name="secretarybot"></a>SecretaryBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/256ff1bc-fd16-4f82-aeb3-8a6977ff2ec4" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381085" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von MySecre über Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | SecretaryBot |
| ID | WA104381085 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | MySecretary |
| URL der Partnerwebsite | [https://secretarybot.wordpress.com/](https://secretarybot.wordpress.com/) |
| URL der Seite mit Teams Anwendungsinformationen | [https://secretarybot.wordpress.com/faq/](https://secretarybot.wordpress.com/faq/) |
| URL der Datenschutzrichtlinie | [https://secretarybot.wordpress.com/privacy-policy/](https://secretarybot.wordpress.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://secretarybot.wordpress.com/terms-of-use/](https://secretarybot.wordpress.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von MySecre über die Erfassung und Speicherung von Organisationsdaten durch diese App und die Kontrolle ihrer Organisation über die von der App erfassten Daten bereitgestellt.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read.Shared | Delegiert |  | Abrufen von Informationen zur freien Zeit der Benutzer und ihrer Kollegen. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Calendars.ReadWrite | Delegiert |  | Besprechungsanfrage anstelle des Benutzers senden. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| MailboxSettings.Read | Delegiert | Store Sprache zum Anzeigen der korrekten Spracherkennung. Zeit sparen, um MS Graph Kalender-API korrekt aufzurufen | Abrufen der Einstellung für Sprache und Zeitzone des Benutzers. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| People.Read | Delegiert |  | Versuchen Sie, Kollegen zu finden, die starke Beziehungen zum Benutzer haben. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read | Delegiert | Store Benutzername, Stadt, Land und Sprache für Benutzeranalysen. Store E-Mail für die Kontaktaufnahme mit dem Kunden. Wir haben noch nie eine E-Mail-Adresse verwendet, können aber für Support verwendet werden. | Versuchen Sie, das Land und die bevorzugte Sprache des Benutzers zu finden. Es wird für die Sicherung für MailboxSettings.Read verwendet. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| email | Delegiert | Siehe weiter oben. | Zum Speichern von E-Mails. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| openid | Delegiert |  | Für die OpenID-Authentifizierung. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Profil | Delegiert | Speichern Sie OID, um die eindeutige ID des Benutzers im MS-Identitätssystem zu identifizieren. | Abrufen von Benutzername und OID. Versuchen Sie, in Zukunft OID zum Verbinden Outlook Add-Ins zu verwenden. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Verwenden Sie diese Informationen zum Planen von Teambesprechung | Nein |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>OII- oder EUII-Daten werden in den Telemetrie- oder Protokollen angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir bieten Endbenutzern noch keine administratorische Kontrolle, aber wenn Endbenutzer uns auffordern, Daten zu löschen, können wir ihrer Anforderung folgen.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

