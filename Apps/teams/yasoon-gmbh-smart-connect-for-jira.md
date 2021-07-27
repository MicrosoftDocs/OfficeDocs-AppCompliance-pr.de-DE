---
title: Application Information for Smart Verbinden for Jira by yasoon GmbH
ms.author: elmalova
author: elenamalova
ms.date: 07/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Smart Verbinden für Jira, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a4a5a1ad980bba5214811bea5d981a1705ec4f1f
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/22/2021
ms.locfileid: "53528029"
---
# <a name="smart-connect-for-jira"></a>Smart Connect for Jira

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 21, 2021</p>

* <a href="https://teams.microsoft.com/l/app/6402de97-ce33-4386-bf28-b37e9e139c09" target="_blank">Anzeigen in Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002055" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von yasoon GmbH für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Smart Connect for Jira |
| ID | WA200002055 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | yasoon GmbH |
| URL der Partnerwebsite | [https://www.yasoon.com](https://www.yasoon.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://yasoon.com/microsoft-teams-for-jira/](https://yasoon.com/microsoft-teams-for-jira/) |
| URL der Datenschutzrichtlinie | [https://yasoon.com/privacy-policy-services/](https://yasoon.com/privacy-policy-services/) |
| URL der Nutzungsbedingungen | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474846970/Product_42949680957/Asset_3f25ec80-eacb-454f-8cc2-eeee583b65c6/170825EULAOfficeaddinEN.doc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von yasoon GmbH zur Verfügung gestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | Delegiert | Die Berechtigung wird verwendet, damit der Benutzer einen dieser verbundenen Kanäle in Jira auswählen kann. | Kanal-ID für Zwischenspeicherungszwecke | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| ChannelMessage.Read.Group | Anwendung | Ermöglicht der App, verknüpfte Kanalnachrichten in Jira anzuzeigen. | Nachrichten-IDs zum Verknüpfen von Nachrichten mit Jira-Problemen | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| ChannelMessage.Send | Delegiert | Es werden keine Daten verwendet, diese API wird verwendet, damit der Benutzer auf Kanalnachrichten von Jira antworten kann. | Keine | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| ChannelSettings.Read.Group | Anwendung | Wird zum Nachschlagen von Detailinformationen zu einem Kanal verwendet. | Keine | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| Chat.ReadWrite | Delegiert | Wird verwendet, um dem Benutzer das Hinzufügen neuer Antworten zu Chats und das Anzeigen von Chatnachrichten von Jira zu ermöglichen. | Keine | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| Member.Read.Group | Anwendung | Wird für Berechtigungsprüfungen verwendet und ermöglicht der App, die Teammitgliedschaft von Benutzern zu überprüfen. | Keine | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| Team.ReadBasic.All | Delegiert | Die Berechtigung wird verwendet, damit der Benutzer eines dieser beigetretenen Teams in Jira auswählen kann. | Team-IDs für Zwischenspeicherungszwecke | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| TeamSettings.Read.Group | Anwendung | Ermöglicht der App, Teameinstellungen zu lesen, um bestimmte Standardwerte zu berücksichtigen. | Keine | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| User.ReadBasic.All | Delegiert | Ermöglicht es dem Benutzer, Kollegen auszuwählen, um @-mention in einer Kanalnachricht zu erwähnen | Keine | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Atlassian Jira und möglicherweise einer unserer Vertragsnehmer sind hier zu sehen: https://go.yasoon.com/contractors | Nachrichtenmetadaten (IDs, Zeitstempel), Benutzer- und Organisationsmetadaten (Benutzer-IDs, Organisations-IDs) und E-Mail-Adressen des Benutzers | Unterstützung der App-Funktionalität (z. B. Abgleichen von Atlassian-Konten mit Office-Konten) und Ermöglichen unserer Unterstützung, Probleme schneller zu beheben. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Abgleich der Benutzer Teams Konto mit dem Benutzerkonto Atlassian Jira | Nein |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Benutzermetadaten (ID)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir arbeiten nur mit Diensten, die strenge Datenschutz-Garantien bieten. 

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von yasoon GmbH bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>– Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
