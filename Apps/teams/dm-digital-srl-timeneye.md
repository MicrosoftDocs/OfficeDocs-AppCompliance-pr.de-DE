---
title: Anwendungsinformationen für Time diamonde von DM Digital SRL
ms.author: elmalova
author: elenamalova
ms.date: 09/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Timeyane, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 30c0543469970b94d1020a3c1c64f668ab833075
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412445"
---
# <a name="timeneye"></a>Timeneye

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 31, 2021</p>

* <a href="https://teams.microsoft.com/l/app/015bf4ec-bc37-4931-9862-ef8686da652b" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001950" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von DM Digital SRL für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Timeneye |
| ID | WA200001950 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | DM Digital SRL |
| URL der Partnerwebsite | [https://www.dmdigital.it](https://www.dmdigital.it) |
| URL der Datenschutzrichtlinie | [https://www.timeneye.com/privacy-policy](https://www.timeneye.com/privacy-policy) |
| URL der Nutzungsbedingungen | [https://www.timeneye.com/terms-and-conditions](https://www.timeneye.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von DM Digital SRL bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | Delegiert | Start/Ende des Ereignisses DateTime, Ereignisbeantrager, Ereignis-ID, Ereignisweb-URI. Generieren Sie Vorschläge basierend auf Kalenderereignissen. | Start/Ende des Ereignisses DateTime, Ereignisbeantrager, Ereignis-ID, Ereignisweb-URI. Sie können einen generierten Vorschlag mit dem relevanten Kalenderereignis verknüpfen. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Calendars.Read.Shared | Delegiert | Start/Ende des Ereignisses DateTime, Ereignisbeantrager, Ereignis-ID, Ereignisweb-URI. Wir verwenden diese Informationen, um Vorschläge basierend auf Kalenderereignissen zu generieren. | Start/Ende des Ereignisses DateTime, Ereignisbeantrager, Ereignis-ID, Ereignisweb-URI. Wir verwenden diese Informationen, um einen generierten Vorschlag mit dem relevanten Kalenderereignis zu verknüpfen. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Directory.Read.All | Delegiert | Die Gruppen-IDs des Benutzers. Wir verwenden diese Informationen, um die Gruppen zu überprüfen, in denen der Benutzer Mitglied ist, damit wir die Planer seiner Gruppen synchronisieren können. | Die Gruppen-IDs des Benutzers. Wir verwenden diese Informationen, um die Gruppen zu überprüfen, in denen der Benutzer Mitglied ist, damit wir die Planer seiner Gruppen synchronisieren können. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Group.Read.All | Delegiert | Gruppenname, Gruppen-ID. Wir verwenden diese Informationen beim Synchronisieren der Planner-Projekte. | Gruppenname, Gruppen-ID.  | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Tasks.Read | Delegiert | Aufgabenlistenname, Aufgabenlisten-ID. Wir verwenden diese Informationen beim Synchronisieren der Planner-Projekte. | Aufgabenlistenname, Aufgabenlisten-ID. Wir verwenden diese Informationen beim Synchronisieren der Planner-Projekte. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| User.Read | Delegiert | E-Mail, Name. Wir verwenden diese Informationen, um uns beim Benutzer anzumelden/das Benutzerkonto zu erstellen. | E-Mail, Name. Wir verwenden diese Informationen, um uns beim Benutzer anzumelden/das Benutzerkonto zu erstellen. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| User.ReadBasic.All | Delegiert | Benutzername, E-Mail. Wir verwenden diese Informationen, damit der Benutzer andere Benutzer aus Planner/Microsoft in unseren Dienst importieren kann. | Benutzername, E-Mail. Grundlegende Informationen, die erforderlich sind, um einen neuen Benutzer in unserem Dienst zu erstellen. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| email | Delegiert | E-Mail. Wir verwenden diese Informationen, um uns beim Benutzer anzumelden/das Benutzerkonto zu erstellen. | E-Mail. Wir verwenden diese Informationen, um uns beim Benutzer anzumelden/das Benutzerkonto zu erstellen. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| offline_access | Delegiert | Erforderliche Berechtigung zum Synchronisieren des Planners/Kalenders, während der Benutzer nicht online ist. | Erforderliche Berechtigung zum Synchronisieren des Planners/Kalenders, während der Benutzer nicht online ist. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| openid | Delegiert | id_token. Anmelden des Benutzers über Microsoft SSO | id_token. Anmelden des Benutzers über Microsoft SSO. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Profil | Delegiert | E-Mail, Name. Wir verwenden diese Informationen, um uns beim Benutzer anzumelden/das Benutzerkonto zu erstellen. | E-Mail, Name. Wir verwenden diese Informationen, um uns beim Benutzer anzumelden/das Benutzerkonto zu erstellen. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise zusätzliche Andere Microsoft-APIs als Microsoft Graph zum Sammeln oder Verarbeiten von organisationsbezogenen Informationen (OII). Auflisten aller anderen Microsoft-APIs als Microsoft Graph diese App verwendet wird.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Outlook Kalender-API | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Benutzername und E-Mail, Firmenabrechnungsdetails. Wenn das Konto/der Benutzer gelöscht wird, werden die Informationen entfernt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir geben keine sinnvollen Informationen an unsere Partnersysteme weiter, mit Ausnahme der E-Mail-Adresse des Benutzers für Support-, Ticket- und Abrechnungszwecke. Die Informationen werden nach dem Löschen des Kontos auf unserem System gelöscht.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von DM Digital SRL bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
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
| Verwendet Ihre App veraltete APIs? | Ja |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

