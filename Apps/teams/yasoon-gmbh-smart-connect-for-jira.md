---
title: Anwendungsinformationen für Smart Verbinden for Jira by yasoon GmbH
ms.author: elmalova
author: elenamalova
ms.date: 01/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Smart Verbinden für Jira, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 6fb1be576d588727c75f14d72db48bc3a7a8aeb5
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550735"
---
# <a name="smart-connect-for-jira"></a>Smart Connect for Jira

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 22. Januar 2021</p>

* <a href="https://teams.microsoft.com/l/app/6402de97-ce33-4386-bf28-b37e9e139c09" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002055" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die die yasoon GmbH Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Smart Connect for Jira |
| ID | WA200002055 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | yasoon GmbH |
| URL der Partner-Website | [https://yasoon.com](https://yasoon.com) |
| URL Teams Anwendungsinfoseite | [https://yasoon.com/microsoft-teams-for-jira/](https://yasoon.com/microsoft-teams-for-jira/) |
| URL der Datenschutzrichtlinie | [https://yasoon.com/privacy-policy-services](https://yasoon.com/privacy-policy-services) |
| URL der Nutzungsbedingungen | [https://yasoon.com/terms-of-use](https://yasoon.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von der yasoon GmbH darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Channel.ReadBasic.All | Delegiert | Die Berechtigung wird verwendet, damit der Benutzer einen dieser verbundenen Kanäle in Jira auswählen kann. | Channel-ID, für Caching-Zwecke | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| ChannelMessage.Read.Group | Anwendung | Ermöglicht der App, verknüpfte Kanalnachrichten in Jira anzuzeigen. | Nachrichten-IDs zum Verknüpfen von Nachrichten mit Jira-Problemen | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| ChannelMessage.Send | Delegiert | Es werden keine Daten verwendet, diese API wird verwendet, damit der Benutzer auf Kanalnachrichten von Jira antworten kann. | Keine | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| ChannelSettings.Read.Group | Anwendung | Wird verwendet, um Detailinformationen zu einem Kanal zu suchen. | Keine | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| Chat.ReadWrite | Delegiert | Wird verwendet, um dem Benutzer zu ermöglichen, neue Antworten zu Chats hinzuzufügen und Chatnachrichten von Jira anzuzeigen. | Keine | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| Member.Read.Group | Anwendung | Wird für Berechtigungsprüfungen verwendet, kann die App die Teammitgliedschaft von Benutzern überprüfen. | Keine | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| Team.ReadBasic.All | Delegiert | Die Berechtigung wird verwendet, damit der Benutzer eines dieser verbundenen Teams in Jira auswählen kann. | Team-IDs für Caching-Zwecke | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| TeamSettings.Read.Group | Anwendung | Ermöglicht der App, Teameinstellungen zu lesen, um bestimmte Standardeinstellungen zu beachten. | Keine | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| User.ReadBasic.All | Delegiert | Ermöglicht es dem Benutzer, Kollegen in einer Kanalnachricht zur -Mention auszuwählen | Keine | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Atlassian Jira und möglicherweise einer unserer Auftragnehmer, können Sie hier sehen: https://go.yasoon.com/contractors | Nachrichtenmetadaten (IDs, Zeitstempel), Benutzer- und Organisationsmetadaten (Benutzer-, Organisations-, Organisations-, Organisations-E-Mail-Adressen) und Benutzer-E-Mail-Adressen | Unterstützung der App-Funktionalität (z. B. Abgleich von Atlassian-Konten mit Office Konten) und schnellere Problembehandlung durch unseren Support. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Abgleich der Benutzer Teams Kontos mit dem Atlassian Jira-Konto | Nein |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Benutzermetadaten (id)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Wir arbeiten nur mit Diensten, die strenge Datenschutzgarantien bieten. 

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von der yasoon GmbH darüber bereitgestellt, wie diese App mit Authentifizierung, Autorisierung, Best Practices für die Anwendungsregistrierung und anderen Identitätskriterien umgeht.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Können Sie sich in Microsoft Identifizplattform (Azure AD) integrieren?  | Ja |
| Haben Sie alle in der Checkliste für die Microsoft Identity Platform-Integration beschriebenen bewährten Methoden überprüft und eingehalten?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Conditional Access-Richtlinien? | Nein |
| Fordert Ihre App die geringsten Berechtigungsberechtigungen für Ihr Szenario an? | Ja |
| Gibt die statisch registrierten Berechtigungen Ihrer App die Berechtigungen wieder, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Multi-Tenancy? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle für Ihre App registrierten Unified Resource Identifier (URI) umleiten? | Ja |
| Was vermeiden Sie für Ihre App? | - Wildcard-Umleitungs-URIs,<br/>- OAuth2 Implizite Flow, es sei denn, dies ist für ein SPA erforderlich<br/>- Ressourcenbesitzer-Kennwortanmeldeinformationen (ROPC)-Flow |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
