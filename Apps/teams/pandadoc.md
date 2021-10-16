---
title: Anwendungsinformationen für Diesdoc vonDoc
ms.author: elmalova
author: elenamalova
ms.date: 08/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für DoppelklickDoc, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 8d3a04daba9ebcbcf435f46beb6313c22310fe22
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60408980"
---
# <a name="pandadoc"></a>PandaDoc

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 19, 2021</p>

* <a href="https://teams.microsoft.com/l/app/769d6db6-6890-4f70-8088-5943fdeac3c5" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002927" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von DerDoc an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | PandaDoc |
| ID | WA200002927 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | PandaDoc |
| URL der Partnerwebsite | [https://www.pandadoc.com](https://www.pandadoc.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.pandadoc.com](https://www.pandadoc.com) |
| URL der Datenschutzrichtlinie | [https://www.pandadoc.com/privacy-notice/?utm_source=microso...](https://www.pandadoc.com/privacy-notice/?utm_source=microsoft-teams&amp;utm_medium=partner&amp;utm_campaign=2021-2-inbd-marketplace-websitevisit-pandadoc-privacy) |
| URL der Nutzungsbedingungen | [https://www.pandadoc.com/terms-of-use/](https://www.pandadoc.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Ihnen bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | Beide | zum Abrufen einer Listen-IDs von Kanälen für jeden zuvor empfangenen Befehl und zum Abrufen der Dateilaufwerk-IDs für jeden Kanal. | Daten werden nicht gespeichert | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| ChannelSettings.Read.All | Beide | zum Abrufen einer Listen-IDs von Kanälen für jeden zuvor empfangenen Befehl und zum Abrufen der Dateilaufwerk-IDs für jeden Kanal.  | Daten werden nicht gespeichert | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| ChannelSettings.ReadWrite.All | Beide | zum Abrufen einer Listen-IDs von Kanälen für jeden zuvor empfangenen Befehl und zum Abrufen der Dateilaufwerk-IDs für jeden Kanal. | Daten werden nicht gespeichert | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Directory.Read.All | Beide | So rufen Sie die IDs der Teams in Microsoft Teams ab, bei denen der Benutzer ein direktes Mitglied ist. Danach empfangen Sie Kanäle für jeden Befehlsbezeichner. | Daten werden nicht gespeichert. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Directory.ReadWrite.All | Beide | So rufen Sie die IDs der Teams in Microsoft Teams ab, bei denen der Benutzer ein direktes Mitglied ist. Danach empfangen Sie Kanäle für jeden Befehlsbezeichner. | Daten werden nicht gespeichert. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Files.Read | Beide | für SSO-Benutzer von Tab (Beispiel - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Erforderlich, um ein Benutzertoken mit Zugriff auf Microsoft Graph und weitere Benutzerdateien abzurufen. | Daten werden nicht gespeichert. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Files.Read.All | Beide | für SSO-Benutzer von Tab (Beispiel - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Erforderlich, um ein Benutzertoken mit Zugriff auf Microsoft Graph und weitere Benutzerdateien abzurufen. | Daten werden nicht gespeichert. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Files.Read.Selected | Beide | für SSO-Benutzer von Tab (Beispiel - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Erforderlich, um ein Benutzertoken mit Zugriff auf Microsoft Graph und weitere Benutzerdateien abzurufen. | Daten werden nicht gespeichert. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Group.Read.All | Beide | zum Abrufen einer Listen-IDs von Kanälen für jeden zuvor empfangenen Befehl und zum Abrufen der Dateilaufwerk-IDs für jeden Kanal. Dokumentation – https://docs.microsoft.com/en-us/graph/api/channel-list?view=graph-rest-1.0&amp ;tabs=http | Daten werden nicht gespeichert. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Group.ReadWrite.All | Beide | zum Abrufen einer Listen-IDs von Kanälen für jeden zuvor empfangenen Befehl und zum Abrufen der Dateilaufwerk-IDs für jeden Kanal. Dokumentation – https://docs.microsoft.com/en-us/graph/api/channel-list?view=graph-rest-1.0&amp ;tabs=http | Daten werden nicht gespeichert. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Team.ReadBasic.All | Beide | um IDs für die Teams in Microsoft Teams abzurufen, bei denen der Benutzer ein direktes Mitglied ist. Danach empfangen Sie Kanäle für jeden Befehlsbezeichner. Um die Dateitresor-IDs abzurufen, müssen Sie zuerst eine Liste der Teams abrufen, die der Benutzer eingegeben hat. | Daten werden nicht gespeichert. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamSettings.Read.All | Beide | So rufen Sie die IDs der Teams in Microsoft Teams ab, bei denen der Benutzer ein direktes Mitglied ist. Danach empfangen Sie Kanäle für jeden Befehlsbezeichner. Um die Dateitresor-IDs abzurufen, müssen Sie zuerst eine Liste der Teams abrufen, die der Benutzer eingegeben hat. | Daten werden nicht gespeichert. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamSettings.ReadWrite.All | Beide | oder rufen Sie IDs der Teams in Microsoft Teams ab, bei denen der Benutzer ein direktes Mitglied ist. Danach empfangen Sie Kanäle für jeden Befehlsbezeichner. Um die Dateitresor-IDs abzurufen, müssen Sie zuerst eine Liste der Teams abrufen, die der Benutzer eingegeben hat. | Daten werden nicht gespeichert. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamsAppInstallation.ReadWriteSelfForTeam.All | Beide | erforderlich, um die Anwendung auf einem Benutzer im Team zu installieren und den Bot im Chat zu installieren. | Daten werden nicht gespeichert. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamsAppInstallation.ReadWriteSelfForUser.All | Beide | erforderlich, um die Anwendung auf einem Benutzer im Team zu installieren und den Bot im Chat zu installieren. | Daten werden nicht gespeichert. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| User.Read | Beide | für SSO-Benutzer von Tab (Beispiel - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Erforderlich, um ein Benutzertoken mit Zugriff auf Microsoft Graph und weitere Benutzerdateien abzurufen. | Daten werden nicht gespeichert. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| User.Read.All | Beide |  zum Abrufen von IDs, bei denen die Teams in Microsoft Teams, bei denen der Benutzer ein direktes Mitglied ist. Danach empfangen Sie Kanäle für jeden Befehlsbezeichner. Um die Dateitresor-IDs abzurufen, müssen Sie zuerst eine Liste der Teams abrufen, die der Benutzer eingegeben hat. | Daten werden nicht gespeichert. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| User.ReadWrite.All | Beide |  zum Abrufen von IDs, bei denen die Teams in Microsoft Teams, bei denen der Benutzer ein direktes Mitglied ist. Danach empfangen Sie Kanäle für jeden Befehlsbezeichner. Um die Dateitresor-IDs abzurufen, müssen Sie zuerst eine Liste der Teams abrufen, die der Benutzer eingegeben hat. | Daten werden nicht gespeichert. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| email | Beide | für SSO-Benutzer von Tab (Beispiel - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Erforderlich, um ein Benutzertoken mit Zugriff auf Microsoft Graph und weitere Benutzerdateien abzurufen. | Daten werden nicht gespeichert. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| offline_access | Beide | für SSO-Benutzer von Tab (Beispiel - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Erforderlich, um ein Benutzertoken mit Zugriff auf Microsoft Graph und weitere Benutzerdateien abzurufen. | Daten werden nicht gespeichert. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| openid | Beide | für SSO-Benutzer von Tab (Beispiel - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Erforderlich, um ein Benutzertoken mit Zugriff auf Microsoft Graph und weitere Benutzerdateien abzurufen. | Daten werden nicht gespeichert. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Profil | Beide | für SSO-Benutzer von Tab (Beispiel - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Erforderlich, um ein Benutzertoken mit Zugriff auf Microsoft Graph und weitere Benutzerdateien abzurufen. | Daten werden nicht gespeichert. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise zusätzliche Andere Microsoft-APIs als Microsoft Graph, um organisationsspezifische Informationen (OII) zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft auf, Graph diese App verwendet.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Doc-API | Nein |  |  |  |  |
>| MS Graph | Nein |  |  |  |  |
>| Elementor | Nein |  |  |  |  |

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

>Unsere Lieferantenvereinbarungen erfüllen die jeweiligen Verpflichtungen unserer Kunden und unserer Lieferanten im Hinblick auf Datenschutz und Sicherheit, und wir werden jedes Jahr einer Sicherheits-/Datenschutzüberprüfung unserer wichtigsten Lieferanten unterzogen.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21283' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21283" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Ihnen bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden in der Checkliste für die Microsoft Identity Platform Integration überprüft und berücksichtigt?  | Nein |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Nein |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>- Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/> |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

