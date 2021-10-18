---
title: Anwendungsinformationen für Easy2Meet von Easy2Meet B.V.
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Easy2Meet, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 164890c1ceebe1cae7567ca5f6d05b38d3c8361b
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60432920"
---
# <a name="easy2meet"></a>Easy2Meet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 21, 2021</p>

* <a href="https://teams.microsoft.com/l/app/8dbb8c54-678e-4c02-bc35-0f393416e532" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003277" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen von Easy2Meet B.V. an Microsoft:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Easy2Meet |
| ID | WA200003277 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Easy2Meet B.V. |
| URL der Partnerwebsite | [https://www.easy2meet.eu](https://www.easy2meet.eu) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.easy2meet.eu](https://www.easy2meet.eu) |
| URL der Datenschutzrichtlinie | [https://www.easy2meet.eu/hubfs/PrivacyStatement.pdf](https://www.easy2meet.eu/hubfs/PrivacyStatement.pdf) |
| URL der Nutzungsbedingungen | [https://www.easy2meet.eu/hubfs/PDF%20contractueel/Easy2Meet...](https://www.easy2meet.eu/hubfs/PDF%20contractueel/Easy2Meet%20General%20Terms%20and%20Conditions%20Sept%202020%20EN.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Easy2Meet B.V. bereitgestellt. Darüber, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | Delegiert | Wir benötigen Benutzerinformationen zum Verwalten von Benutzern und Besprechungen in Easy2Meet | E-Mail und Name. Wir benötigen dies, um Benutzer und Besprechungen zu verwalten. | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |
>| email | Delegiert | So zeigen Sie E-Mail-Adres des aktuellen Benutzers an. Wir benötigen die E-Mail-Adres, um Besprechungseinladungen zu senden. | E-Mail und Name. Wir benötigen dies, um Benutzer und Besprechungen zu verwalten. | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |
>| openid | Delegiert | wir sammeln hier keine Daten. Wir verwenden dies zum Anmelden des Benutzers | wir sammeln hier keine Daten. Wir verwenden dies zum Anmelden des Benutzers. | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |
>| Profil | Delegiert | Wir benötigen Benutzerinformationen zum Verwalten von Benutzern und Besprechungen in Easy2Meet | E-Mail und Name. Wir benötigen dies, um Benutzer und Besprechungen zu verwalten. | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise zusätzliche Andere Microsoft-APIs als Microsoft Graph, um organisationsspezifische Informationen (OII) zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft auf, Graph diese App verwendet.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint Online | Nein |  |  |  |  |
>| MS Exchange Online | Nein |  |  |  |  |

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

>Überwachung

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Easy2Meet B.V. bereitgestellt. Darüber, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

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
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
