---
title: Anwendungsinformationen für 365Projekte von 365Apps
ms.author: elmalova
author: elenamalova
ms.date: 03/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für 365Projects, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d760c1c5bacf37fa23e26f4a9a15eb7dbbd75bb1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553466"
---
# <a name="365projects"></a>365Projects

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. März 2021</p>

* <a href="https://teams.microsoft.com/l/app/a9c31598-b014-4e20-b3bd-3d275fa738d3" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002160" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von 365Apps an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | 365Projects |
| ID | WA200002160 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | 365Apps |
| URL der Partner-Website | [https://365projects.app](https://365projects.app) |
| URL Teams Anwendungsinfoseite | [https://365projects.app](https://365projects.app) |
| URL der Datenschutzrichtlinie | [https://365projects.app/privacy](https://365projects.app/privacy) |
| URL der Nutzungsbedingungen | [https://365projects.app/eula](https://365projects.app/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von 365Apps darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Channel.ReadBasic.All | Delegiert | Kanäle innerhalb des Teams, um das Projekt mit dem Kanal zu verknüpfen | Kanäle innerhalb des Teams, um das Projekt mit dem Kanal zu verknüpfen | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| Group.Read.All | Delegiert | Teamplaner/Planer-Aufgaben erhalten, ist es besser, wenn ein weiterer Bereich mit den geringsten Berechtigungen es der App ermöglicht, Benutzerpläne und Pläne zu erhalten, aber leider gibt es keine Bereiche, die dies zulassen | nicht in DB speichern | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| Group.ReadWrite.All | Anwendung | Erstellen Teams  | nicht in DB gespeichert | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| People.Read | Delegiert | Benutzernamen, um sie als Teammitglieder hinzuzufügen oder ihnen Aufgaben zuzuweisen | Benutzer-GuiD wird in der Aufgabenzuweisung gespeichert | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| Team.ReadBasic.All | Delegiert | Joined Team Names, um das Projekt mit Teams Channel zu verknüpfen | Team Guid wird in den Projektmetadaten gespeichert, um den Link | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| User.Read | Delegiert | Abrufen von Benutzerinformationen zum Anzeigen im Header  | Benutzer-E-Mail wird als Eigentümer gespeichert, wenn der Mandant zum ersten Mal bereitgestellt wird | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| User.Read.All | Delegiert | Lesen von Benutzern zum Aktualisieren der Aufgabenzuweisung | Nur Benutzer GuiD wird gespeichert keine persönlichen identifizierten Informationen werden in der DB gespeichert | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird kein EUII abgerufen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>In den Anwendungstelemetrie- oder Protokollprotokollen sind keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>App speichert keine Benutzerdaten außer Guid des App-Administrators (erster Benutzer verwendet die App innerhalb des Mandanten) 

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von 365Apps darüber bereitgestellt, wie diese App authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Können Sie sich in Microsoft Identifizplattform (Azure AD) integrieren?  | Ja |
| Haben Sie alle in der Checkliste für die Microsoft Identity Platform-Integration beschriebenen bewährten Methoden überprüft und eingehalten?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Conditional Access-Richtlinien? | Nein |
| Fordert Ihre App die geringsten Berechtigungsberechtigungen für Ihr Szenario an? | Ja |
| Gibt die statisch registrierten Berechtigungen Ihrer App die Berechtigungen wieder, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Multi-Tenancy? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle für Ihre App registrierten Unified Resource Identifier (URI) umleiten? | Ja |
| Was vermeiden Sie für Ihre App? | ,<br/>- OAuth2 Implizite Flow, es sei denn, dies ist für ein SPA erforderlich<br/> |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann zu, dass Aufrufe erfolgreich sind, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
