---
title: Anwendungsinformationen für Weekly10 von Binary Limited
ms.author: elmalova
author: elenamalova
ms.date: 08/26/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Weekly10, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 9bdd5e42398270719c9f0ecd9814155974dbee6f
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411129"
---
# <a name="weekly10"></a>Weekly10

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 19, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c80cee99-d17f-4b2d-a2a4-57652ffd2a4b" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001441" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Binary Binary Binary Limited auf Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Weekly10 |
| ID | WA200001441 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Binary Geek Limited |
| URL der Partnerwebsite | [https://www.weekly10.com](https://www.weekly10.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.weekly10.com/integrations/microsoft-teams/](https://www.weekly10.com/integrations/microsoft-teams/) |
| URL der Datenschutzrichtlinie | [https://www.weekly10.com/terms/privacy](https://www.weekly10.com/terms/privacy) |
| URL der Nutzungsbedingungen | [https://www.weekly10.com/terms/customer](https://www.weekly10.com/terms/customer) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Binary Limited bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | Anwendung | Synchronisation von Benutzern von Azure AD in Wöchentlich10 (optional) | Benutzeridentitätsdaten: Benutzerprinzipalname, E-Mail, Vorname, Nachname und Vorgesetzter. | [2cc7f3cd-05e3-4ebb-b9f9-d92f1bcda7fb](https://docs.microsoft.com/microsoft-365-app-certification/azure/2cc7f3cd-05e3-4ebb-b9f9-d92f1bcda7fb) |
>| Calendars.ReadWrite | Anwendung | Überprüfen der Mitarbeiterverfügbarkeit und der automatisierten Buchung von Besprechungen (optional). | Verfügbarkeitszeiten für Mitarbeiter (keine Details) und wenn eine Besprechung gebucht wird, wird der Verweis auf diese Besprechung angezeigt. Diese Daten werden verwendet, um zu verstehen, ob ein Mitarbeiter nicht im Büro ist, um eine nahtlose Mitarbeitererfahrung zu erhalten, und um Besprechungen für 1:1-Zeit oder Leistungsüberprüfungen zu buchen. | [494610b2-b490-4f54-8384-312d6f9b4869](https://docs.microsoft.com/microsoft-365-app-certification/azure/494610b2-b490-4f54-8384-312d6f9b4869) |
>| User.Read | Delegiert | Überprüfung des Benutzers für SSO-Zwecke im Azure AD. | Abgesehen von Tokeninformationen werden keine zusätzlichen Daten aufbewahrt. | [6fd1421e-89e8-4a8b-bd01-9397656a50d5](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fd1421e-89e8-4a8b-bd01-9397656a50d5) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Wir greifen nur auf die Teams Benutzer-ID der Person zu. Dies bedeutet, dass der Bot auf eine bestimmte Weise auf diesen Benutzer reagieren kann. | Nein |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Organisationsname und Benutzernamen im Falle eines gemeldeten Fehlers oder Problems. Protokolle werden in diesem Format bis zu 30 Tage lang gespeichert und dann gelöscht.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Alle Daten, die sich in Weekly10 befinden, können von angegebenen Administratoren gesteuert werden. Beim Ändern von Richtlinien in Weekly10 wirkt sich dies direkt auf die Daten in Microsoft Azure (wo sich Clientdaten befinden) aus.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Binary Limited bereitgestellt, um zu erfahren, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden in der Checkliste für die Microsoft Identity Platform Integration überprüft und berücksichtigt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/><br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

