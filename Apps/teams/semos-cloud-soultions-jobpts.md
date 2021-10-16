---
title: Anwendungsinformationen für JobPts von Semos Cloud Remtions
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für JobPts, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: ca449f0fcc33f8b85feae5be0e022ba79fe965f0
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60408404"
---
# <a name="jobpts"></a>JobPts

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 7, 2021</p>

* <a href="https://teams.microsoft.com/l/app/601a47bc-f201-4398-a0cb-593ea081f265" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001849" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Semos Cloud-Verbindungen für Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | JobPts |
| ID | WA200001849 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Semos Cloud Solutions |
| URL der Partnerwebsite | [https://semoscloud.com](https://semoscloud.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://semoscloud.com/product/jobpts](https://semoscloud.com/product/jobpts) |
| URL der Datenschutzrichtlinie | [https://semoscloud.com/privacy-policy/](https://semoscloud.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://semoscloud.com/terms-of-use/](https://semoscloud.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Semos Cloud Remtions bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | Delegiert | Grundlegende Unternehmensinformationen lesen | Es werden keine Daten gespeichert. | [1ac9e5c6-4850-4864-96c5-b91e4512334e](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ac9e5c6-4850-4864-96c5-b91e4512334e) |
>| email | Delegiert | Dies wird zum Zuordnen von AzureAD-Benutzern zu Benutzern im JobPts-Tool verwendet. | Es werden keine Daten gespeichert. | [1ac9e5c6-4850-4864-96c5-b91e4512334e](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ac9e5c6-4850-4864-96c5-b91e4512334e) |
>| offline_access | Delegiert | Verwalten des Zugriffs auf Daten | Es werden keine Daten gespeichert. | [1ac9e5c6-4850-4864-96c5-b91e4512334e](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ac9e5c6-4850-4864-96c5-b91e4512334e) |
>| openid | Delegiert | Damit sich Benutzer mit ihrem Geschäftskonto anmelden können | Es werden keine Daten gespeichert. | [1ac9e5c6-4850-4864-96c5-b91e4512334e](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ac9e5c6-4850-4864-96c5-b91e4512334e) |
>| Profil | Delegiert | So können JobPts grundlegende Informationen des Benutzers anzeigen (Benutzername) | Es werden keine Daten gespeichert. | [1ac9e5c6-4850-4864-96c5-b91e4512334e](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ac9e5c6-4850-4864-96c5-b91e4512334e) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Abrufen von Informationen, welche Benutzer mit dem Bot kommunizieren | Nein |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir übertragen keine Daten an die Systeme des Partners

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Semos Cloud Remtions bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Mehrstufige Authentifizierung, Einschränken von Benutzerspeicherorten und IP-Bereichen |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>- Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

