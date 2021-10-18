---
title: Anwendungsinformationen für Luware Nimbus für Microsoft Teams von Luware AG
ms.author: elmalova
author: elenamalova
ms.date: 10/07/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Luware Nimbus für Microsoft Teams, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 34991a9d979fb497a02c074ade1bd8a7f8faea0d
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430535"
---
# <a name="luware-nimbus-for-microsoft-teams"></a>Luware Nimbus für Microsoft Teams

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: October 1, 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/luwareagzurich.advanced_routing_azure_marketplace" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Luware AG für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Luware Nimbus für Microsoft Teams |
| ID | luwareagzurich.advanced_routing_azure_marketplace |
| Name des Partnerunternehmens | Luware AG |
| URL der Partnerwebsite | [https://luware.com](https://luware.com) |
| URL der Datenschutzrichtlinie | [https://luware.com/en/privacy-policy](https://luware.com/en/privacy-policy) |
| URL der Nutzungsbedingungen | [https://luware.com/en/agreements/saas/](https://luware.com/en/agreements/saas/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Luware AG darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | Delegiert | Telefonzentralenkonsole: Lesen des Kalenders des angemeldeten Benutzers anzeigen Kalender mit Terminen | Keine | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Calendars.Read.Shared | Delegiert | Telefonzentralenkonsole: Lesen von freigegebenen Kalendern zum Anzeigen von Kalendern mit Terminen | Keine | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Contacts.Read | Delegiert | Telefonzentralenkonsole: Suchen in den Exchange Kontakten des angemeldeten Benutzers | Keine | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Contacts.Read.Shared | Delegiert | Telefonzentralenkonsole: Suchen in den freigegebenen Exchange-Kontakten | Keine | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| GroupMember.Read.All | Anwendung | Abrufen von Teammitgliedern, Lesen von Sicherheitsgruppen | Wir speichern diese Informationen, da Callcenter-Agents über Gruppenmitgliedschaften verwaltet werden. | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Presence.Read.All | Delegiert | Anzeigen der Anwesenheit in der Kontaktsuche auf der Telefonzentralen-Konsolenseite | Keine | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| User.Read | Delegiert | Abrufen von UserInformation (vom angemeldeten Benutzer) | Keine | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| User.Read.All | Beide | Nimbus-App – Rufen Sie CallerInformation ab. Bei einem internen Anruf an das Contact Center führen wir einen Reverse-Lookup dazu durch, wer es sein könnte, damit wir diese Informationen dem Agent anzeigen können. In der Attendant Console (mit delegierter Berechtigung) durchsuchen wir das gesamte interne Verzeichnis nach Übertragungszielen. | Für reporting REasons on who called the most, we store that data. | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| User.ReadBasic.All | Delegiert | Eingeschränkte Benutzersuche | Keine | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Calls.AccessMedia.All | Anwendung | Viele dieser Apps/Bots (eine pro Contact Center-Warteschlange): Abonnieren Sie DTMF-Töne, in denen der Kunde tatsächlich seine Position in der IVR auswählen kann. | Alle DTMF-Informationen für ausgewählte Möglichkeiten durch den IVR aus Gründen der Berichterstellung | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |
>| Calls.Initiate.All | Anwendung | Viele dieser Apps/Bots (eine pro Contact Center-Warteschlange): Tätigen eines Anrufs an den Agent  | Alle KDS-Informationen aus Gründen der Berichterstellung | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |
>| Calls.InitiateGroupCall.All | Anwendung | Viele dieser Apps/Bots (eine pro Contact Center-Warteschlange): Tätigen eines Anrufs an den Agent  | Alle KDS-Informationen aus Gründen der Berichterstellung | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |
>| Calls.JoinGroupCall.All | Anwendung | Viele dieser Apps/Bots (eine pro Contact Center-Warteschlange): Nehmen Sie an einem eskalierten Anruf teil, um Ankündigungen wiederzugeben | Alle KDS-Informationen aus Gründen der Berichterstellung | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Aggregierte Berichtsdaten (Anrufdetaildatensätze, Anruferinformationen, Anrufbehandlungs- und Anrufverlaufsdetails usw.): 24 Monate Konfigurationsdaten: Kundenvertragsdauer +30 Tage Anwendungsprotokolle: Temporäre Speicherung interner Anwendungsprotokolle (um unseren Supporttechnikern zu helfen, die Leistung und den Betrieb von Anwendungskomponenten zu beheben) 30 Tage.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>https://luware.com/en/privacy-policy/

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Luware AG darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Client-Apps, Benutzer und Gruppen |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>- Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
