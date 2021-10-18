---
title: Anwendungsinformationen für Teamflect von Grepsi Software
ms.author: elmalova
author: elenamalova
ms.date: 08/26/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Teamflect, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 93fa21382d60f73ebed1a843700f34061e52fd43
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429623"
---
# <a name="teamflect"></a>Teamflect

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 17, 2021</p>

* <a href="https://teams.microsoft.com/l/app/e46015e9-f2ae-4dbc-be6b-f05043192e62" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001860" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Grepsi Software für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Teamflect |
| ID | WA200001860 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Grepsi Software |
| URL der Partnerwebsite | [https://teamflect.com](https://teamflect.com) |
| URL der Datenschutzrichtlinie | [https://www.teamflect.com/privacy](https://www.teamflect.com/privacy) |
| URL der Nutzungsbedingungen | [https://teamflect.com/terms](https://teamflect.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von der Software Von Grepsi bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | Anwendung | Wir verwenden diese Berechtigung für den Zugriff auf Benutzerkalender, um die 1:1-Besprechungen zu identifizieren. | Metadaten des Kalenderelements werden in unseren Datenbanken gespeichert. | [c5da92a9-873e-4ea1-86c7-03ec9c1384f0](https://docs.microsoft.com/microsoft-365-app-certification/azure/c5da92a9-873e-4ea1-86c7-03ec9c1384f0) |
>| Directory.Read.All | Delegiert | Unternehmensverzeichnis – wir verwenden diese Berechtigung, um Endbenutzern eine Liste ihrer Kollegen anzuzeigen, wenn sie eine Suche durchführen | n/v | [c5da92a9-873e-4ea1-86c7-03ec9c1384f0](https://docs.microsoft.com/microsoft-365-app-certification/azure/c5da92a9-873e-4ea1-86c7-03ec9c1384f0) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Mailjet | Organisationsdomäne | Wir verwenden Drittanbieter-E-Mail-Anbieter, um E-Mail-Benachrichtigungen an unsere Endbenutzer zu senden. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Unsere Bot-Anwendung sendet Benachrichtigungen an Endbenutzer. Als Teil dieser Benachrichtigungen verarbeitet und verarbeitet unser Bot Daten, aber dieser Bot wird auch in Microsoft Azure Datacenter gehostet und überträgt keine EUII-Daten außerhalb oder an Dienste von Drittanbietern. | Nein |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir speichern Benutzerdaten nur, solange sie unsere Anwendung weiterhin verwenden. Wir löschen alle Daten im Zusammenhang mit inaktiven Benutzern nach einem Zeitraum von 5 Jahren oder auf Anforderung des Endbenutzers.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir verwenden Microsoft Azure zum Hosten unserer Anwendungsserver und Datenbanken. Wir verwenden nur einen Drittanbieter-E-Mail-Dienst, um unseren Benutzern E-Mail-Benachrichtigungen zu übermitteln. Dieses Drittanbieter-E-Mail-System speichert die E-Mail-Adressen des Endbenutzers, wird jedoch gemäß unseren Datenaufbewahrungs- und Datenschutzrichtlinien von uns gesteuert.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Grepsi Software dazu bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | BlockAccess, RequireMFA |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>– Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
