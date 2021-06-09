---
title: Anwendungsinformationen für die Vorwärtsarbeit mit Jira durch Verschieben der Arbeit nach vorn
ms.author: elmalova
author: elenamalova
ms.date: 05/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für move Work Forward with Jira, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a5ca2ec25650abba3f68a2ec543434c56d3c3d27
ms.sourcegitcommit: bb013192ff1a6db66c2ffe05cc83afc1d4140e76
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/09/2021
ms.locfileid: "52852054"
---
# <a name="move-work-forward-with-jira"></a>Vorwärtsarbeit mit Jira

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 5. Mai 2021</p>

* <a href="https://teams.microsoft.com/l/app/79ca2e8f-dd2c-40d5-897e-1b22d41038fe" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002855" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Move Work Forward an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Vorwärtsarbeit mit Jira |
| ID | WA200002855 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Verschieben der Arbeit nach vorn |
| URL der Partnerwebsite | [https://www.moveworkforward.com](https://www.moveworkforward.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.moveworkforward.com/product/microsoft-teams-jir...](https://www.moveworkforward.com/product/microsoft-teams-jira-connector) |
| URL der Datenschutzrichtlinie | [https://www.moveworkforward.com/privacy-policy](https://www.moveworkforward.com/privacy-policy) |
| URL der Nutzungsbedingungen | [https://www.moveworkforward.com/license-agreement/eula](https://www.moveworkforward.com/license-agreement/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Move Work Forward darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Channel.Create | Delegiert | Wird zum Erstellen eines Problemdiskussionskanals verwendet. | Die Web-URL des neu erstellten Kanals wird gespeichert, um in Jira für den schnellen Zugriff auf den Microsoft Teams Diskussionskanal anzuzeigen. | 39d845a0-3fa2-4fba-acc2-61afe40cfcea |
>| Channel.ReadBasic.All | Delegiert | Kanalname und -ID werden verwendet, um Benachrichtigungen von Jira an Microsoft Teams zu senden. | Die Kanal-ID und der Name werden gespeichert, um Benachrichtigungen von Jira zu Microsoft Teams zu konfigurieren. | 39d845a0-3fa2-4fba-acc2-61afe40cfcea |
>| Team.ReadBasic.All | Delegiert | Die Berechtigung wird verwendet, damit der Benutzer eines dieser beigetretenen Teams in Jira auswählen kann. | Team-ID und Name, die auf dem Konfigurationsbildschirm in Jira angezeigt werden sollen. | 39d845a0-3fa2-4fba-acc2-61afe40cfcea |
>| TeamsAppInstallation.ReadForTeam | Delegiert | Installierte Teams-Apps in Teams lesen. Beim Einrichten der Übermittlung an Microsoft Teams kann die App Teams senden, wobei der Bot installiert ist. | Nichts | 39d845a0-3fa2-4fba-acc2-61afe40cfcea |
>| User.Read | Delegiert | Ermöglicht dem Benutzer das Erstellen eines Diskussionskanals mit Kollegen und das @Erwähnen in einer Kanalnachricht | Nichts | 39d845a0-3fa2-4fba-acc2-61afe40cfcea |
>| email | Delegiert | E-Mails werden verwendet, um Atlassian- und Microsoft-Benutzern zu entsprechen. | Die E-Mail wird nicht gespeichert. Wird nur während des Abgleichsvorgangs verwendet. | 39d845a0-3fa2-4fba-acc2-61afe40cfcea |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Begrüßung der Benutzer anhand des Namens, wenn die App installiert wird. Passen Sie Microsoft Teams und Atlassian-Benutzer an. | Nein |  |


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

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39108' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39108" target="_blank">Ansicht auf einer neuen Registerkarte</a>

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
