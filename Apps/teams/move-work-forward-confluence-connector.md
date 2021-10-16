---
title: Anwendungsinformationen für den Konfluence-Connector durch vorwärts gehende Arbeit
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Confluence Connector, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 62b34c18df1b792a9a1cb7269e7a7a0ad364fd70
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414506"
---
# <a name="confluence-connector"></a>Confluence Connector

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 22, 2021</p>

* <a href="https://teams.microsoft.com/l/app/3c9fd7ca-5386-4179-9bb7-7fcdcc373017" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001604" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Move Work Forward an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Confluence Connector |
| ID | WA200001604 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Move Work Forward |
| URL der Partnerwebsite | [https://www.moveworkforward.com](https://www.moveworkforward.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.moveworkforward.com/product/microsoft-teams-con...](https://www.moveworkforward.com/product/microsoft-teams-confluence-connector) |
| URL der Datenschutzrichtlinie | [https://moveworkforward.com/privacy-policy](https://moveworkforward.com/privacy-policy) |
| URL der Nutzungsbedingungen | [https://www.moveworkforward.com/license-agreement/eula](https://www.moveworkforward.com/license-agreement/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Move Work Forward darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | Delegiert | Kanalname und -ID werden verwendet, um Benachrichtigungen von Jira an Microsoft Teams zu senden. | Die Kanal-ID und der Name werden gespeichert, um Benachrichtigungen von Jira zu Microsoft Teams zu konfigurieren. | [f3943662-e828-40ed-9c6e-369680fe421f](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3943662-e828-40ed-9c6e-369680fe421f) |
>| Teams.ReadBasic.All | Delegiert | Die Berechtigung wird verwendet, damit der Benutzer eines dieser beigetretenen Teams in Jira auswählen kann. | Team-ID und Name, die auf dem Konfigurationsbildschirm in Jira angezeigt werden sollen. | [f3943662-e828-40ed-9c6e-369680fe421f](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3943662-e828-40ed-9c6e-369680fe421f) |
>| TeamsAppInstallation.ReadForTeam | Delegiert | Installierte Teams-Apps in Teams lesen. Beim Einrichten der Übermittlung an Microsoft Teams kann die App Teams senden, wobei der Bot installiert ist. | Nichts | [f3943662-e828-40ed-9c6e-369680fe421f](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3943662-e828-40ed-9c6e-369680fe421f) |
>| User.Read | Delegiert | Ermöglicht dem Benutzer das Erstellen eines Diskussionskanals mit Kollegen und das @Erwähnen in einer Kanalnachricht | Nichts | [f3943662-e828-40ed-9c6e-369680fe421f](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3943662-e828-40ed-9c6e-369680fe421f) |
>| email | Delegiert | E-Mails werden verwendet, um Atlassian- und Microsoft-Benutzern zu entsprechen. | Die E-Mail wird nicht gespeichert. Wird nur während des Abgleichsvorgangs verwendet. | [f3943662-e828-40ed-9c6e-369680fe421f](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3943662-e828-40ed-9c6e-369680fe421f) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Begrüßung der Benutzer anhand des Namens, wenn die App installiert wird. Microsoft Teams und Atlassian-Benutzer abgleichen. | Nein |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir protokollieren die Mandanten-URL, die in den Protokollen für bis zu 5 Tage gespeichert ist.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir arbeiten nur mit Diensten, die strenge Datenschutz-Garantien bieten.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Move Work Forward darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

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
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/><br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

