---
title: Anwendungsinformationen für Tryane Analytics von Tryane
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Tryane Analytics, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 265fa798414c907f25690252e1714bebfdbdde1b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551105"
---
# <a name="tryane-analytics"></a>Tryane Analytics

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 28. September 2020</p>

* <a href="https://teams.microsoft.com/l/app/87631b95-fcd9-46e9-8d86-3d5205c04fec" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001827" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Tryane Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Tryane Analytics |
| ID | WA200001827 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Tryane |
| URL der Partner-Website | [https://tryane.com/en/produit/tat/](https://tryane.com/en/produit/tat/) |
| URL der Datenschutzrichtlinie | [https://tryane.com/tryane-analytics/privacy_policy.html](https://tryane.com/tryane-analytics/privacy_policy.html) |
| URL der Nutzungsbedingungen | [https://tryane.com/tryane-analytics/terms_of_use.html](https://tryane.com/tryane-analytics/terms_of_use.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Tryane darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ActivityFeed.Read | Anwendung |  | Lesen aller Benutzeraktivitäten in Teams | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Channel.ReadBasic.All | Anwendung |  | Alle Listen alle Kanäle mit Namen, Beschreibungen | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| ChannelMessage.Read.All | Anwendung |  | Auflisten aller Kanäle nachrichten&#8217; Metadaten | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Directory.Read.All | Anwendung |  | Identifizieren von Benutzern mit einer Teamlizenz im Mandanten | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Member.Read.Hidden | Anwendung |  | Abrufen einer Liste aller Teams, Team-&#8217;-Mitglieder und versteckter Mitgliedschaften | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Reports.Read.All | Anwendung |  | Lesen aller Benutzeraktivitäten in Teams | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Team.ReadBasic.All | Anwendung |  | Auflisten aller Kanäle und Teams-Eigenschaften | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| User.Read | Delegiert | Benutzer-ID, Name, E-Mail-Adresse, Erstellungsdatum. Wir speichern diese Daten, um Nutzungsanalysen auf Teams | Identifizieren des aktuellen Benutzers während des Abonnements | 9b03f15d-1219-4b2f-9699-640be54e1319 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird kein EUII abgerufen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Organisationsregel, die in unserer IT-Sicherheitsrichtlinie beschrieben wird, und Codierungsstandards verhindern, dass EUII und OII in den Protokollen erscheinen

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Wo/Wie: Azure/Azure-Datenbank für PostgreSQL-Server Wer darauf zugreifen können: unsere Anwendung und die Datenbankadministratoren Autorisierungssteuerung: 
 - Individuelle Berechtigungskontrolle: RBAC
 - Systemautorisierungssteuerung: Private Endpunkte in azurblauen virtuellen Netzwerken

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

