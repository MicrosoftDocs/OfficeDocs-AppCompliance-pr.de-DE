---
title: Anwendungsinformationen für InCaseIT von Pilotech AS
ms.author: elmalova
author: elenamalova
ms.date: 09/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für InCaseIT, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 424df0e4c31f8a35c4d2e095f9f95c618274fa23
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429893"
---
# <a name="incaseit"></a>InCaseIT

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 3, 2021</p>

* <a href="https://teams.microsoft.com/l/app/4420b597-c1d5-4d40-ba81-2b2a78575c81" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003265" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Pilotech AS für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | InCaseIT |
| ID | WA200003265 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Pilotech AS |
| URL der Partnerwebsite | [https://incaseit.com](https://incaseit.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/t...](https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/topic/introduction-to-incaseit-version-2-0) |
| URL der Datenschutzrichtlinie | [https://www.incaseit.com/privacy-policy/](https://www.incaseit.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/t...](https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/topic/1-4-terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Pilotech AS darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | Delegiert | Die einzigen verwendeten Daten sind die explizite Bestätigung durch die Benutzer, der Anwendung die Verwendung eines Zugriffstokens zum Aufrufen der Graph-API zu erlauben. | Unsere Anwendung speichert nur einen Link zur geplanten Besprechung, um den Benutzern die Barrierefreiheit der Besprechung zu erleichtern.  Beispiel. 1. Erstellen sie geplante Teams Besprechung. 2. Speichern Sie den Besprechungslink in Datenbank 3. Verwenden Sie den Besprechungslink für eine Schaltfläche in der Anwendung, um einfachen Zugriff auf die Besprechung zu erhalten. | [9af6eceb-6a8b-4710-b51d-dde2ac01cc71](https://docs.microsoft.com/microsoft-365-app-certification/azure/9af6eceb-6a8b-4710-b51d-dde2ac01cc71) |
>| OnlineMeetings.ReadWrite | Delegiert | Die einzigen verwendeten Daten sind die explizite Bestätigung durch die Benutzer, der Anwendung die Verwendung eines Zugriffstokens zum Aufrufen der Graph-API zu erlauben. | Unsere Anwendung speichert nur einen Link zur Onlinebesprechung, um den Benutzern die Barrierefreiheit der Besprechung zu erleichtern.  Beispiel. 1. Erstellen Sie eine Teams Onlinebesprechung. 2. Speichern Sie den Besprechungslink in Datenbank 3. Verwenden Sie den Besprechungslink für eine Schaltfläche in der Anwendung, um einfachen Zugriff auf die Besprechung zu erhalten. | [9af6eceb-6a8b-4710-b51d-dde2ac01cc71](https://docs.microsoft.com/microsoft-365-app-certification/azure/9af6eceb-6a8b-4710-b51d-dde2ac01cc71) |
>| User.Read | Delegiert | Die einzigen verwendeten Daten sind die explizite Bestätigung durch die Benutzer, der Anwendung die Verwendung eines Zugriffstokens zum Aufrufen der Graph-API zu erlauben. | Es werden keine Daten mit der Berechtigung "User.Read" gespeichert. | [9af6eceb-6a8b-4710-b51d-dde2ac01cc71](https://docs.microsoft.com/microsoft-365-app-certification/azure/9af6eceb-6a8b-4710-b51d-dde2ac01cc71) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>EUII könnte in Anwendungsprotokollen angezeigt werden, wenn während einer Krise Mitteilungen an die internen Risikomanagementteams gesendet werden. Die Entfernungsrichtlinien für Protokolle besteht darin, dass wir maximal 3 Monate Protokolle speichern. Diese können zwar bei Bedarf auf Anforderung gelöscht werden. 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir haben Datenschutzvereinbarungen mit allen unseren Partnern und Unterauftragsverarbeitern, die die Einhaltung der DSGVO-Bestimmungen hinsichtlich der Position als Datenverarbeiter und Datenunterverarbeiter sicherstellen.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Pilotech AS darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden in der Checkliste für die Microsoft Identity Platform Integration überprüft und berücksichtigt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/><br/> |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
