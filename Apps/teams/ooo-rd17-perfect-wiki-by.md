---
title: Application Information for Perfect Wiki by RD17 by OOO RD17
ms.author: elmalova
author: elenamalova
ms.date: 08/26/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Perfect Wiki von RD17, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: d6f3be273da609d1c50b8ec0f0869dcb88b56dd5
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428762"
---
# <a name="perfect-wiki-by-rd17"></a>Perfect Wiki von RD17

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 16, 2021</p>

* <a href="https://teams.microsoft.com/l/app/40906836-4323-4bbe-875e-3cbb134c40a2" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001679" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von OOO RD17 für Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Perfect Wiki von RD17 |
| ID | WA200001679 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | OOO RD17 |
| URL der Partnerwebsite | [https://perfectwikiforteams.com](https://perfectwikiforteams.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://perfectwikiforteams.com](https://perfectwikiforteams.com) |
| URL der Datenschutzrichtlinie | [https://docs.google.com/document/d/e/2PACX-1vQHouhjK2Qof_NK...](https://docs.google.com/document/d/e/2PACX-1vQHouhjK2Qof_NKFVucpN44PO30SFZHDfxWhu-u5wlZI56UW7v3bT-WCM4zH4ZaWGzQR7lnoUpVyU1S/pub) |
| URL der Nutzungsbedingungen | [https://docs.google.com/document/d/e/2PACX-1vTMQNAdgN7xy6n9...](https://docs.google.com/document/d/e/2PACX-1vTMQNAdgN7xy6n9tNvhDe8Sb2AF8A9v8jfG3gJ503cXzIq1nr_Zbq5aShN0mU49fvADgKZ8a58Oha-C/pub) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von OOO RD17 zur Verfügung gestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | Delegiert | "ChannelId" und "channelName" erhalten Informationen zum Anzeigen des Benutzers in der App. | Wir speichern "channelId" und "channelName", um sie später für den Benutzer anzuzeigen. | [b9604964-9c3a-483e-abf2-1b5cba495081](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9604964-9c3a-483e-abf2-1b5cba495081) |
>| Team.ReadBasic.All | Delegiert | Wir rufen die teamId des Benutzers und den Teamnamen ab. | teamId und teamName verwenden wir, um zu verstehen, welcher Teambenutzer gehört | [b9604964-9c3a-483e-abf2-1b5cba495081](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9604964-9c3a-483e-abf2-1b5cba495081) |
>| User.Read | Delegiert | userId, die verwendet wird, um zu verstehen, welcher Benutzer angemeldet ist | hashed userId, to login user and get associated data from DB | [b9604964-9c3a-483e-abf2-1b5cba495081](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9604964-9c3a-483e-abf2-1b5cba495081) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir verwenden die rollenbasierte Zugriffssteuerung für jeden Vorgang mit dem System des Partners.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von OOO RD17 bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>– Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
