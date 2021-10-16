---
title: Anwendungsinformationen für kalender Pro von Witivio
ms.author: elmalova
author: elenamalova
ms.date: 09/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für kalender Pro, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 5f8b6dcbf99d26e867cc79194cb57c1393316a2b
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414862"
---
# <a name="calendar-pro"></a>Kalender Pro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 2, 2021</p>

* <a href="https://teams.microsoft.com/l/app/19a29a41-cbca-4152-a2af-dd9728ea35f1" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002152" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Witivio für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Kalender Pro |
| ID | WA200002152 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Witivio |
| URL der Partnerwebsite | [https://www.witivio.com](https://www.witivio.com) |
| URL der Datenschutzrichtlinie | [https://www.teams-pro.com/en/privacy-policy/](https://www.teams-pro.com/en/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://www.teams-pro.com/en/terms-of-use/](https://www.teams-pro.com/en/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Witivio darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | Delegiert | Die Daten werden verwendet. | Die Daten werden verwendet, um die Informationen auf der Benutzeroberfläche anzuzeigen. | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| User.ReadBasic.All | Delegiert | Die Daten werden verwendet. | Die Daten werden zum Auflisten von Personen zum Aktivieren der Personenauswahl verwendet. | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| email | Delegiert | Die E-Mail wird verwendet | Die E-Mail wird verwendet, um den Benutzer auf der Benutzeroberfläche zu identifizieren. | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| offline_access | Delegiert | Die Daten werden verwendet. | Der Offlinezugriff wird verwendet, um SSO mit Microsoft Teams | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| openid | Delegiert | Authentifizierung | OpenID wird für die Authentifizierung mit Microsoft Teams | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| Profil | Delegiert | Die Daten werden verwendet. | Profil wird verwendet, um SSO mit Microsoft Teams | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Die Telemetrie enthält den UPN und die AAD-ID für die Diagnose. Nur PROD/Run-Administratoren haben Zugriff auf die Produktionstelemetrie. Die Protokolle werden 90 Tage lang gespeichert und können auf Anforderung per E-Mail bei dpo@witivio.com

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Witivio verwendet nur Microsoft Azure Komponenten, die in der Region Nordeuropa bereitgestellt werden. Wir verwenden Anwendungsinblicke und Cosmos DB für Die Datenanalyse und -speicherung. Witivio verwendet MFA für alle Benutzer, einschließlich Administratoren. Administratoren verfügen über ein Benutzerkonto (für Arbeitsstation) und ein privilegiertes Konto für den Zugriff auf Azure-Ressourcen.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Witivio darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

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
| Was vermeiden Sie für Ihre App? | ,<br/>– Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/> |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

