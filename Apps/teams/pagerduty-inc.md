---
title: Anwendungsinformationen für PagerDuty von PagerDuty, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 09/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für PagerDuty, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: a296483ba42328a306131aee8a2f29aed8d7006b
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412835"
---
# <a name="pagerduty"></a>PagerDuty

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 27. August 2021</p>

* <a href="https://teams.microsoft.com/l/app/c8c302dc-4e77-4536-890d-0c2bffbef9cc" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001637" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Von PagerDuty, Inc. an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | PagerDuty |
| ID | WA200001637 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | PagerDuty, Inc. |
| URL der Partnerwebsite | [https://www.pagerduty.com](https://www.pagerduty.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.pagerduty.com/integrations/microsoft-teams](https://www.pagerduty.com/integrations/microsoft-teams) |
| URL der Datenschutzrichtlinie | [https://www.pagerduty.com/privacy-policy/](https://www.pagerduty.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://www.pagerduty.com/service-terms-use/](https://www.pagerduty.com/service-terms-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von PagerDuty, Inc. zur Verfügung gestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| OnlineMeetings.ReadWrite | Delegiert | Von der Besprechungserstellung/-antwort verwenden wir solche Felder: join_web_url, audioConferencing. Diese Felder sind erforderlich, um dem Benutzer einen Link zu einer Besprechung oder alternative Möglichkeiten zum Herstellen einer Verbindung in einer Besprechung anzuzeigen. | Wir speichern: join_web_url, audioConferencing. Diese Felder sind erforderlich, um dem Benutzer einen Link zu einer Besprechung oder alternative Möglichkeiten zum Herstellen einer Verbindung in einer Besprechung anzuzeigen. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation.ReadForTeam | Delegiert | Wird zum Hinzufügen einer Pagerduty-App zum Chat verwendet. | Wird zum Hinzufügen einer Pagerduty-App zum Chat verwendet. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation.ReadWriteForTeam.All | Delegiert | Wird zum Hinzufügen einer Pagerduty-App zum Chat verwendet. | Wird zum Hinzufügen einer Pagerduty-App zum Chat verwendet. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsTab.ReadWrite.All | Delegiert | Verwenden zum Hinzufügen einer Pagerduty-App als Registerkarte in einer Besprechung | Verwenden zum Hinzufügen einer Pagerduty-App als Registerkarte in einer Besprechung | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.Read | Delegiert | Daten werden verwendet: ID, userPrincipalName . Es wird verwendet, um Microsoft Teams-Benutzer dazu zu bringen, sie einer Besprechung als Teilnehmer hinzuzufügen. | Daten werden verwendet: ID, userPrincipalName . Es wird verwendet, um Microsoft Teams-Benutzer dazu zu bringen, sie einer Besprechung als Teilnehmer hinzuzufügen. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.ReadBasic.All | Delegiert | Daten werden verwendet: ID, userPrincipalName . Es wird verwendet, um Microsoft Teams-Benutzer dazu zu bringen, sie einer Besprechung als Teilnehmer hinzuzufügen. | Daten werden verwendet: ID, userPrincipalName . Es wird verwendet, um Microsoft Teams-Benutzer dazu zu bringen, sie einer Besprechung als Teilnehmer hinzuzufügen. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| email | Delegiert | Verwendung für Autorisierungs- und Tokenanforderungen. Daten werden verwendet: access_token, refresh_token, expires_in, Bereich | access_token, refresh_token, expires_in, Bereich. Diese Daten sind erforderlich, um Informationen zu Benutzer- und Onlinebesprechungen zu erhalten. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| offline_access | Delegiert | Verwendung für Autorisierungs- und Tokenanforderungen. Daten werden verwendet: access_token, refresh_token, expires_in, Bereich | access_token, refresh_token, expires_in, Bereich. Diese Daten werden zum Abrufen von Informationen zu Benutzer- und Onlinebesprechungen verwendet. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| openid | Delegiert | Verwendung für Autorisierungs- und Tokenanforderungen. Daten werden verwendet: access_token, refresh_token, expires_in, Bereich | access_token, refresh_token, expires_in, Bereich. Diese Daten werden zum Abrufen von Informationen über Benutzer und zum Erstellen/Abrufen von Onlinebesprechungen verwendet. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| Profil | Delegiert | Verwendung für Autorisierungs- und Tokenanforderungen. Daten werden verwendet: access_token, refresh_token, expires_in, Bereich | access_token, refresh_token, expires_in, Bereich. Diese Daten werden zum Abrufen von Informationen über Benutzer und zum Erstellen/Abrufen von Onlinebesprechungen verwendet. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| OnlineMeetings.ReadWrite | Delegiert | Von der Besprechungserstellung/-antwort verwenden wir solche Felder: join_web_url, audioConferencing. Diese Felder sind erforderlich, um dem Benutzer einen Link zu einer Besprechung oder alternative Möglichkeiten zum Herstellen einer Verbindung in einer Besprechung anzuzeigen. | Wir speichern: join_web_url, audioConferencing. Diese Felder sind erforderlich, um dem Benutzer einen Link zu einer Besprechung oder alternative Möglichkeiten zum Herstellen einer Verbindung in einer Besprechung anzuzeigen. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation.ReadForTeam | Delegiert | Wird zum Hinzufügen einer Pagerduty-App zum Chat verwendet. | Wird zum Hinzufügen einer Pagerduty-App zum Chat verwendet. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation.ReadForTeam.All | Delegiert | Wird zum Hinzufügen einer Pagerduty-App zum Chat verwendet. | Wird zum Hinzufügen einer Pagerduty-App zum Chat verwendet. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsTab.ReadWrite.All | Delegiert | Verwenden zum Hinzufügen einer Pagerduty-App als Registerkarte in einer Besprechung | Verwenden zum Hinzufügen einer Pagerduty-App als Registerkarte in einer Besprechung | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.Read | Delegiert | Daten werden verwendet: ID, userPrincipalName . Es wird verwendet, um Microsoft Teams-Benutzer dazu zu bringen, sie einer Besprechung als Teilnehmer hinzuzufügen. | Daten werden verwendet: ID, userPrincipalName . Es wird verwendet, um Microsoft Teams-Benutzer dazu zu bringen, sie einer Besprechung als Teilnehmer hinzuzufügen. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.ReadBasic.All | Delegiert | Daten werden verwendet: ID, userPrincipalName . Es wird verwendet, um Microsoft Teams-Benutzer dazu zu bringen, sie einer Besprechung als Teilnehmer hinzuzufügen. | Daten werden verwendet: ID, userPrincipalName . Es wird verwendet, um Microsoft Teams-Benutzer dazu zu bringen, sie einer Besprechung als Teilnehmer hinzuzufügen. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| email | Delegiert | Verwendung für Autorisierungs- und Tokenanforderungen. Daten werden verwendet: access_token, refresh_token, expires_in, Bereich | access_token, refresh_token, expires_in, Bereich. Diese Daten sind erforderlich, um Informationen zu Benutzer- und Onlinebesprechungen zu erhalten. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| offline_access | Delegiert | Verwendung für Autorisierungs- und Tokenanforderungen. Daten werden verwendet: access_token, refresh_token, expires_in, Bereich | access_token, refresh_token, expires_in, Bereich. Diese Daten sind erforderlich, um Informationen zu Benutzer- und Onlinebesprechungen zu erhalten. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| openid | Delegiert | Verwendung für Autorisierungs- und Tokenanforderungen. Daten werden verwendet: access_token, refresh_token, expires_in, Bereich | access_token, refresh_token, expires_in, Bereich. Diese Daten werden zum Abrufen von Informationen über Benutzer und zum Erstellen/Abrufen von Onlinebesprechungen verwendet. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| Profil | Delegiert | Verwendung für Autorisierungs- und Tokenanforderungen. Daten werden verwendet: access_token, refresh_token, expires_in, Bereich | access_token, refresh_token, expires_in, Bereich. Diese Daten werden zum Abrufen von Informationen über Benutzer und zum Erstellen/Abrufen von Onlinebesprechungen verwendet. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Die Daten, die PagerDuty beibehält, sind auf Computerdaten aus Überwachungsprodukten beschränkt, und pii-Informationen sind auf: Unternehmens-E-Mail-Adresse, Vorname, Nachname und Telefonnummer beschränkt. Eine Liste der Unterauftragsverarbeiter mit Zugriff auf diese Daten finden Sie hier: https://www.pagerduty.com/subprocessors/ | Die Daten, die PagerDuty beibehält, sind auf Computerdaten aus Überwachungsprodukten beschränkt, und pii-Informationen sind auf: Unternehmens-E-Mail-Adresse, Vorname, Nachname und Telefonnummer beschränkt. Eine Liste der Unterauftragsverarbeiter mit Zugriff auf diese Daten finden Sie hier: https://www.pagerduty.com/subprocessors/ | Die Daten, die PagerDuty beibehält, sind auf Computerdaten aus Überwachungsprodukten beschränkt, und pii-Informationen sind auf: Unternehmens-E-Mail-Adresse, Vorname, Nachname und Telefonnummer beschränkt. Eine Liste der Unterauftragsverarbeiter mit Zugriff auf diese Daten finden Sie hier: https://www.pagerduty.com/subprocessors/ Weitere Informationen zum Datenschutz finden Sie hier: https://www.pagerduty.com/privacy-policy/ |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>PagerDuty setzt voraus, dass Sicherheitsstandards mindestens so streng sind wie die von PagerDuty verwalteten, von allen Anbietern, an die wir Daten übertragen, einschließlich einer vertraglichen Verpflichtung in Form einer signierten DPA. Weitere Informationen zu unseren Datensicherheitsstandards finden Sie hier: https://www.pagerduty.com/data-security-policy/

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von PagerDuty, Inc. darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

