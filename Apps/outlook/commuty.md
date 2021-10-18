---
title: Anwendungsinformationen für die Commuty-by-Commuty-Anwendung
ms.author: elmalova
author: elenamalova
ms.date: 10/07/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Commuty, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 60cfe397fcc43a029863e12bddacb6667877ca4e
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60444601"
---
# <a name="commuty"></a>Commuty

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: October 7, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003325" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Commuty an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Commuty |
| ID | WA200003325 |
| Office 365 unterstützten Clients | Outlook 2016 oder höher auf Windows, Outlook 2016 oder höher auf dem Mac Outlook im Web |
| Name des Partnerunternehmens | Commuty |
| URL der Partnerwebsite | [https://www.commuty.net](https://www.commuty.net) |
| URL der Datenschutzrichtlinie | [https://support.commuty.net/article/33-privacy-policy](https://support.commuty.net/article/33-privacy-policy) |
| URL der Nutzungsbedingungen | [https://support.commuty.net/article/32-terms-conditions](https://support.commuty.net/article/32-terms-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Commuty zur Verfügung gestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | Delegiert | Kalenderereignisse | Keine, es wird nur zum Synchronisieren von Commuty-Daten mit Outlook-Kalender verwendet. Daten werden immer auf einer Commuty-Benutzeroberfläche bereitgestellt (dies kann über unser Outlook-Add-In erfolgen). | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| email | Delegiert | E-Mail-Adresse | Keine, dies wird nur verwendet, um einen Commuty-Benutzer mit der AD-Identität zu verknüpfen. | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| offline_access | Delegiert | Nicht zutreffend | Nicht zutreffend | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| openid | Delegiert | Authentifizierung | Keine | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| Profil | Delegiert | Identität | Keine | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Allgemeine personenbezogene Daten (primäre E-Mail, eine sekundäre E-Mail, über die sie Benachrichtigungen erhalten können (optional), Vorname, Nachname, Telefon Nummer (optional), Profilbild (optional), bevorzugte Sprache, persönliche Adresse (optional, kann nur Die Stadt sein)), Parkdaten (Nummernschilder), Mobilitätsdaten: (Carpool-Pass, mehrere Heimarbeitstrips, Departure-Return Stunden (optional), Autoverfügbarkeit (optional), Stummschaltungen, Abwesenheitstage). Aufbewahrung: auf Benutzeranforderung ODER nach Vertragsende mit unserem Client

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Jeder Client von Commuty signieren unsere DPA ( https://dpa.commuty.net) , die eine kurze Ansicht dazu enthält.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Commuty bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden in der Checkliste für die Microsoft Identity Platform Integration überprüft und berücksichtigt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>- Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
