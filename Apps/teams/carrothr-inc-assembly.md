---
title: Anwendungsinformationen für die Assembly von CarrotHR Inc.
ms.author: elmalova
author: elenamalova
ms.date: 05/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für assembly, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f8d63c77c3fd9b52353ce22954dfa4dadb8dea2f
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/22/2021
ms.locfileid: "53522052"
---
# <a name="assembly"></a>Assembly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 21, 2021</p>

* <a href="https://teams.microsoft.com/l/app/3e674b5f-ba5d-41cc-8b06-e065b4394aeb" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002271" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von CarrotHR Inc. für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Assembly |
| ID | WA200002271 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | CarrotHR Inc. |
| URL der Partnerwebsite | [https://www.joinassembly.com](https://www.joinassembly.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.joinassembly.com/about](https://www.joinassembly.com/about) |
| URL der Datenschutzrichtlinie | [https://joinassembly.com/privacy-policy](https://joinassembly.com/privacy-policy) |
| URL der Nutzungsbedingungen | [https://joinassembly.com/terms-of-service](https://joinassembly.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von CarrotHR Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | Delegiert | Zulassen, dass benutzer app zu einem neu erstellten Kanal aus unserer App zuweisen | Wir speichern die Kanal-ID, um unsere App mit dem richtigen Kanal zu synchronisieren. | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| Directory.Read.All | Anwendung | Halten Sie unsere Profile synchron, damit Mitglieder in der Assembly ordnungsgemäß durchsuchbar sind | Alle zusätzlichen Profilinformationen, die möglicherweise verfügbar sind, um Mitglieder in der Assembly durchsuchbar zu halten | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| Group.Read.All | Delegiert | Wir beobachten die Daten, um sicherzustellen, dass sie unsere App der richtigen Gruppe zuweisen können. | Wir speichern keine Gruppen | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| Teams.ReadBasic.All | Anwendung | Möglichkeit, unsere App der richtigen Teamregisterkarte zuzuweisen | Wir speichern keine Teams, an die wir angefügt werden.  | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| TeamsTab.Create | Anwendung | Wir verwenden dies, um zu ermöglichen, dass unsere App ordnungsgemäß an einen Kanal/ein Team angefügt wird. | Wir sammeln oder speichern keine Registerkartendaten. | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| email | Delegiert | Die E-Mail-Adresse des Benutzers, damit wir ihm Zugriff auf sein spezifisches Konto gewähren können | Die E-Mail-Adresse des Benutzers, damit wir ihm Zugriff auf sein spezifisches Konto gewähren und Identitäten abgleichen können | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| Profil | Delegiert | Benutzername zum automatischen Auffüllen der Assembly und zur Synchronisierung mit Änderungen in Microsoft Teams | Vollständiger Name des Benutzers | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Löschen, Aufbewahrung, Überwachung, Archivierung

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39111' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39111" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von CarrotHR Inc. darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Nein |
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
