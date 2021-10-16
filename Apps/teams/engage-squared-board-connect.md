---
title: Anwendungsinformationen für Board-Verbinden von Engage Squared
ms.author: elmalova
author: elenamalova
ms.date: 07/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Board Verbinden, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 576d4b4b8107d0e4807818b44faf983d99ee98d1
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414671"
---
# <a name="board-connect"></a>Board Connect

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 5, 2021</p>

* <a href="https://teams.microsoft.com/l/app/e8f06a4e-cefe-4b1e-a24b-c97bea471130" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001955" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Engage Squared für Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Board Connect |
| ID | WA200001955 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Engage Squared |
| URL der Partnerwebsite | [https://engagesq.com](https://engagesq.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://boardconnect.app](https://boardconnect.app) |
| URL der Datenschutzrichtlinie | [https://boardconnect.app/privacy/](https://boardconnect.app/privacy/) |
| URL der Nutzungsbedingungen | [https://boardconnect.app/terms](https://boardconnect.app/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Engage Squared bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | Delegiert | Damit die App Benutzerkalender so aktualisieren kann, dass sie die Teilnahmeantworten ihrer Board-Besprechung widerspiegelt, die über die App übermittelt wurden. | In unserem Azure-Tabellenspeicher werden keine Daten gespeichert. | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| Group.ReadWrite.All | Delegiert | Damit die App Gruppenkalenderereignisse erstellen, aktualisieren und löschen kann. | Wir speichern die ID der Gruppe zusammen mit der Mandanten-ID – diese wird aus Lizenzierungsperspektive gespeichert und verwendet, damit wir überprüfen können, ob die Organisation für Board Verbinden lizenziert ist. Wir verwenden dies auch, um nachzuverfolgen, wie viele Installationen der Anwendungen innerhalb des Mandanten vorhanden sind, da dies mit unserem Lizenzierungsmodell inLine ist. | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| Sites.Manage.All | Delegiert | Damit die App Listen und Bibliotheken erstellen kann, verwalten Sie Listenelemente und Dokumente in einer Teamwebsitesammlung. | Keine | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| User.Read | Delegiert | So ermöglichen Sie Benutzern, sich bei der App anzumelden und der App das Lesen des Profils des aktuell angemeldeten Benutzers zu ermöglichen. | In unserem Azure-Tabellenspeicher werden keine Daten von diesem Endpunkt gespeichert. | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| User.ReadBasic.All | Delegiert | Damit die App einen grundlegenden Satz von Profileigenschaften anderer Benutzer im Namen des angemeldeten Benutzers lesen kann, um dies in der App anzuzeigen. Dazu gehören Anzeigename, Vor- und Nachname, E-Mail-Adresse und Foto. | Keine, Daten werden nicht in unserem Azure-Tabellenspeicher gespeichert. | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| offline_access | Delegiert | Um der App das Abrufen eines Aktualisierungstokens zu ermöglichen, das sie verwenden kann, um ein neues Zugriffstoken abzurufen, wenn das aktuelle abläuft. | Keine, Daten werden nicht in unserem Azure-Tabellenspeicher gespeichert | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

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

>2FA für alle Administratoren, auf die nur zwei angemeldete Quadratbenutzer zugreifen können

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36435' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36435" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Engage Squared bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

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
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>– Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/> |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

