---
title: Anwendungsinformationen für StealthMail von Stealthmail Software Ltd
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 05/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für StealthMail, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a0a31e0eceafbaa4188587411503514692c4b743
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225569"
---
# <a name="stealthmail"></a>StealthMail

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Letzte Aktualisierung durch den Entwickler am: 31. März 2021</p>

* <a href="https://teams.microsoft.com/l/app/1ed0a549-c730-44c7-a984-a8c658fe9807" target="_blank">Anzeigen im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001748" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Stealthmail Software Ltd an Microsoft bereitgestellt werden:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | StealthMail |
| ID | WA200001748 |
| unterstützte Office 365 Clients | Microsoft Teams |
| Name des Partnerunternehmens | Stealthmail Software Ltd |
| URL der Partnerwebsite | [https://stealthmail.com](https://stealthmail.com) |
| URL der Teams Anwendungsinformationsseite | [https://stealthmail.com/product/teams](https://stealthmail.com/product/teams) |
| URL der Datenschutzrichtlinie | [https://stealthmail.com/privacy-statement](https://stealthmail.com/privacy-statement) |
| URL der Nutzungsbedingungen | [https://stealthmail.com/terms-and-conditions](https://stealthmail.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Stealthmail Software Ltd. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Auflisten aller [Microsoft Graph Berechtigungen](/graph/permissions-reference), die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (delegiert/Anwendung)** | **Werden Daten erfasst? Begründung für das Sammeln?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMessage.Read.All | Delegiert | Die Anwendung sendet die Nachricht an den Kanal mit dem Verweis auf erstellte sichere E-Mails. | Keiner | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| ChannelMessage.Send | Delegiert | Die Anwendung sendet die Nachricht an den Kanal mit dem Verweis auf erstellte sichere E-Mails. | Keiner | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| Chat.ReadWrite | Delegiert | Die Anwendung sendet die Nachricht, um mit dem Verweis auf erstellte sichere E-Mails zu chatten. | Keiner | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| GroupMember.Read.All | Delegiert | Die Anwendung ruft Kanalmitglieder ab, um sichere E-Mails für sie zu erstellen | Keiner | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| User.Read.All | Delegiert | Die Anwendung ruft Chatmitglieder ab, um sichere E-Mails für sie zu erstellen | Keiner | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| User.ReadBasic.All | Delegiert | Die Anwendung ruft Chatmitglieder ab, um sichere E-Mails für sie zu erstellen | Keiner | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| email | Delegiert | Benutzer authentifizieren | nichts speichern in Datenbank | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder freigibt, listen Sie den von der App nicht von Microsoft stammenden Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Endbenutzer-identifizierbare Informationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wurde. Nutzt diese App diese Funktion?

>Es wird kein EUII-Zugriff erfolgt.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder Endbenutzer-identifizierbare Informationen (EUII) in den Telemetriedaten oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Aufbewahrungs- und Entfernungsrichtlinien gelten?

>Keine OII oder EUII erscheinen in den Anwendungen Telemetrie oder Protokolle.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren der Organisation ihre Informationen in Partnersystemen steuern können? z.B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir haben keine Kontrolle über die Daten von Partnern in ihren Systemen.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational Identifiable Information) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/37867' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/37867" target="_blank">Auf einer neuen Registerkarte anzeigen</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Stealthmail Software Ltd. bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Response** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden überprüft und eingehalten, die in der Checkliste für die Microsoft Identity Platform Integration aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App Berechtigungen mit den geringsten Berechtigungen für Ihr Szenario an? | Ja |
| Entsprechen die statisch registrierten Berechtigungen Ihrer App genau den Berechtigungen, die ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrinstanzenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie den gesamten umleitenden Unified Resource Identifier (URI), der für Ihre App registriert ist? | Ja |
| Was vermeiden Sie für Ihre App? | - Platzhalter-Umleitungs-URIs,<br/>- Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur den Erfolg von Aufrufen zu, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
