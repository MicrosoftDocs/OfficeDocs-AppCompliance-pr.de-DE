---
title: Anwendungsinformationen für Link- und Kommunikationsprodukte
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für LinkAufsteller, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 37a82564e1dc0a716d31eeb6bd7f7a8b2de510fb
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60444693"
---
# <a name="link-spotter"></a>Link Spotter

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 27, 2021</p>

* <a href="https://teams.microsoft.com/l/app/9e486bb8-9633-48ba-8416-71da1d30cd08" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003092" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Communarray-Produkten für Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Link Spotter |
| ID | WA200003092 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Communardo Products |
| URL der Partnerwebsite | [https://www.communardo.com](https://www.communardo.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://communardo.atlassian.net/wiki/spaces/LINK/overview](https://communardo.atlassian.net/wiki/spaces/LINK/overview) |
| URL der Datenschutzrichtlinie | [https://www.communardo.com/privacy-statement/](https://www.communardo.com/privacy-statement/) |
| URL der Nutzungsbedingungen | [https://www.communardo.com/customer-agreement/](https://www.communardo.com/customer-agreement/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Communverständnis-Produkten bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | Delegiert | Überprüfen der Kanalmitgliedschaft des aktuellen Benutzers | Keine | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| ChannelMessage.Read.All | Anwendung | Urls innerhalb von Nachrichten, Nachrichten-ID, Antwort-zu-Nachrichten-ID, Kanal-ID, Autor-ID... Diese Informationen sind erforderlich, da Graph keine leistungsfähige Möglichkeit bietet, alle links, die in Nachrichten in einem Kanal veröffentlicht wurden, abzurufen. Daher müssen Nachrichten aktiv analysiert werden, um die Linkfunktionalität auf unserer Registerkarte Teams bereitzustellen. | Urls innerhalb von Nachrichten, Nachrichten-ID, Antwort-zu-Nachrichten-ID, Kanal-ID, Autor-ID | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| User.Read | Delegiert | Anmelden und Benutzerprofil lesen | keine | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| User.Read.All | Anwendung | Bestimmen Sie, wie viele Benutzer über eine Teams Lizenz verfügen. Wird verwendet, um die Platzgröße des kostenpflichtigen App-Quellabonnements für den Kundenmandanten zu aktualisieren. | Keine | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| User.ReadBasic.All | Delegiert | Anzeigen des Profilbilds und des Namens des Nachrichtenautors in der App | keine | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| email | Delegiert | OpenID Connect | keine | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| offline_access | Delegiert | OpenID Connect | keine | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| openid | Delegiert | OpenID Connect | keine | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| Profil | Delegiert | OpenID Connect | keine | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise zusätzliche Andere Microsoft-APIs als Microsoft Graph zum Sammeln oder Verarbeiten von organisationsbezogenen Informationen (OII). Auflisten aller anderen Microsoft-APIs als Microsoft Graph diese App verwendet wird.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Marketplace-API (SaaS-Erfüllungs-API) | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Mandanten-ID, Kanal-ID, Benutzer können die Daten direkt entfernen, Daten werden nach 90 Tagen automatisch gelöscht

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Löschen, Endbenutzerrichtlinie

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Commun über die Behandlung von Authentifizierung, Autorisierung, bewährten Methoden für die Anwendungsregistrierung und andere Identitätskriterien durch diese App bereitgestellt.

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
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>– Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
