---
title: Application Information for yuccaHR by Yucca Technologies GmbH
ms.author: elmalova
author: elenamalova
ms.date: 07/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für yuccaHR, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: f8c41d6300413db28561f03a71d62c48e52bb63f
ms.sourcegitcommit: d5c60e66355ffa8fb84565e565f8bb15a665a099
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/24/2021
ms.locfileid: "59785535"
---
# <a name="yuccahr"></a>yuccaHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 5, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c3c1cd11-5b38-4de4-9081-44573d9383bf" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003242" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Von Yucca Technologies GmbH an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | yuccaHR |
| ID | WA200003242 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Yucca Technologies GmbH |
| URL der Partnerwebsite | [https://www.yuccahr.com](https://www.yuccahr.com) |
| URL der Datenschutzrichtlinie | [https://www.yuccahr.com/privacy-policy](https://www.yuccahr.com/privacy-policy) |
| URL der Nutzungsbedingungen | [https://www.yuccahr.com/privacy-policy](https://www.yuccahr.com/privacy-policy) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Yucca Technologies GmbH zur Verfügung gestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | Anwendung |  Erstellen von Terminen zum Kennenlernen von zwei Mitarbeitern basierend auf kostenlosen Zeitfenstern.  | - | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| Channel.ReadBasic.All | Anwendung | Konfigurieren einer Kampagne. (Mitarbeiternetzwerk) | Objectid. So fordern Sie die Kanalressource an. | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| ChannelMember.Read.All | Anwendung | ObjectIds of the members in the channel to start a match making campaign. | Objectid. Um den Abgleich zwischen Mitarbeitern nachzuverfolgen. | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| Group.Read.All | Anwendung |   Konfiguration der Kampagne (Mitarbeiternetzwerk). | Objectid. So fordern Sie die Teamressource an. | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| MailboxSettings.Read | Anwendung | Bestimmung der bevorzugten Sprache und Navigation für den Chat mit dem jeweiligen Mitarbeiter. | - | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| User.Read.All | Anwendung | Name, ObjectId, UserPrinzipalName. Navigation zum Chat mit dem jeweiligen Mitarbeiter. | - | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Personenbezogene Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Verwenden der E-Mail zum Planen und Suchen von kostenlosen Zeitfenstern. | Nein |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Der Kunde kann die Löschung der im Dienst gespeicherten Daten anfordern, indem er eine Anforderung an support@yuccahr.com sendet. Die Daten werden innerhalb einer Woche gelöscht.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Yucca Technologies GmbH bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Nein |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
