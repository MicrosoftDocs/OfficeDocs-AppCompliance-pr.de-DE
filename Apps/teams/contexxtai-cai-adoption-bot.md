---
title: Anwendungsinformationen für C.AI Adoption Bot von contexxt.ai
ms.author: elmalova
author: elenamalova
ms.date: 05/06/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für C.AI Adoption Bot, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5bb11c96f750701128470f3e1c61ea0f5d476233
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521838"
---
# <a name="cai-adoption-bot"></a>C.AI Adoption Bot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 6, 2021</p>

* <a href="https://teams.microsoft.com/l/app/f5323aab-3063-46cb-b632-ee01d95de494" target="_blank">Anzeigen in Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002633" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von contexxt.ai an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | C.AI Adoption Bot |
| ID | WA200002633 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | contexxt.ai |
| URL der Partnerwebsite | [https://contexxt.ai](https://contexxt.ai) |
| URL der Seite mit Teams Anwendungsinformationen | [https://contexxt.ai/cai-adoption-bot/](https://contexxt.ai/cai-adoption-bot/) |
| URL der Datenschutzrichtlinie | [https://contexxt.ai/privacy-policy](https://contexxt.ai/privacy-policy) |
| URL der Nutzungsbedingungen | [https://contexxt.ai/terms-of-use](https://contexxt.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von contexxt.ai darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | Anwendung | Die Verfügbarkeit des Benutzers kann Tipps zum richtigen Zeitpunkt und nicht zu Fokuszeiten senden, z. B. | Die Verfügbarkeit des anonymisierten Benutzers kann Tipps zum richtigen Zeitpunkt und nicht zu Fokuszeiten senden, z. B. | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| ChannelMessage.Read.All | Anwendung | Microsoft Teams Kanalmetadaten, z. B. privat oder nicht, oder die Anzahl der Unterhaltungen pro Kanal, um die Nutzung von Teams zu analysieren | Anonymisierte Microsoft Teams Kanalmetadaten, z. B. privat oder nicht oder die Anzahl der Unterhaltungen pro Kanal, um die Nutzung von Teams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Chat.Read.All | Anwendung | Microsoft Teams Chatmetadaten, z. B. ob eine Nachricht ge gefällt wurde oder wie viele Gruppen- und 1:1-Chats vorhanden sind, um die Nutzung von Teams | Anonymisierte Microsoft Teams Chatmetadaten, z. B. ob eine Nachricht gefällt oder wie viele Gruppen- und 1:1-Chats vorhanden sind, um die Nutzung von Teams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Directory.Read.All | Anwendung | Benutzerobjekt-ID zum Senden von Tipps zum späteren Senden von Benutzerinformationen. | Hashed (anonymized) Object-ID of the user for being being able sending tips to specifi user later. | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Group.Read.All | Anwendung | Microsoft Teams Metadaten, z. B. die Menge der Teams und Kanäle zum Analysieren der Nutzung von Teams | Microsoft Teams Metadaten, z. B. die Menge der Teams und Kanäle zum Analysieren der Nutzung von Teams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Mail.Read | Anwendung | Microsoft Exchange Metadaten, z. B. E-Mails und Gruppen im Vergleich zu 1:1-E-Mails, um die Nutzung von Exchange zu analysieren (im Vergleich zu Teams) | Anonymisierte Microsoft Exchange Metadaten, z. B. E-Mails und Gruppen im Vergleich zu 1:1-E-Mails, um die Nutzung von Exchange zu analysieren (im Vergleich zu Teams) | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| User.Read.All | Anwendung | Microsoft Teams Chat- und Unterhaltungsmetadaten, z. B. wenn ein Benutzer erwähnt wurde, um die Nutzung von Teams | Anonymisierte Microsoft Teams Chat- und Unterhaltungsmetadaten, z. B. wenn ein Benutzer erwähnt wurde, um die Nutzung von Teams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| In Bot Framework wird die Benutzer-ID automatisch übertragen und kann automatisch mit dem Benutzer kommunizieren. Zusätzliche Nutzungsdaten aus C.AI Adoption Analytics werden verwendet, um die Lernerfahrung für den Benutzer zu individualisieren. Daher werden nur geeignete und hilfreiche Tipps an die Benutzer gesendet, die diese Tipps möglicherweise nicht kennen. | Nein |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Organisationen können Lizenzen für ihre Benutzer verwalten (zuweisen/entfernen). Organisationen können verschiedene Rollen zuweisen, um ihre Lizenzen zu verwalten. Administratoren können jederzeit die Löschung ihrer Daten anfordern.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/37589' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/37589" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von contexxt.ai darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

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
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
