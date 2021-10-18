---
title: Anwendungsinformationen für Tryane Analytics von Tryane
ms.author: elmalova
author: elenamalova
ms.date: 09/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Tryane Analytics, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 95ea304fb12ba9efc9d98d547347330326dee6be
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430344"
---
# <a name="tryane-analytics"></a>Tryane Analytics

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 27. August 2021</p>

* <a href="https://teams.microsoft.com/l/app/87631b95-fcd9-46e9-8d86-3d5205c04fec" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001827" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Tryane für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Tryane Analytics |
| ID | WA200001827 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Tryane |
| URL der Partnerwebsite | [https://www.tryane.com](https://www.tryane.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://tryane.com/en/produit/tat/](https://tryane.com/en/produit/tat/) |
| URL der Datenschutzrichtlinie | [https://tryane.com/tryane-analytics/privacy_policy.html](https://tryane.com/tryane-analytics/privacy_policy.html) |
| URL der Nutzungsbedingungen | [https://analytics.tryane.com/docs/en/terms_of_use.html](https://analytics.tryane.com/docs/en/terms_of_use.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Tryane bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | Anwendung | Kanalnamen und zusätzliche Eigenschaften | Alle Kanäle mit Namen, Beschreibungen auflisten | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| ChannelMessage.Read.All | Anwendung | Anzahl der vom Benutzer geposteten Nachrichten | Auflisten aller Kanalnachrichten&#8217; Metadaten | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| Directory.Read.All | Anwendung | Liste der Benutzer, die auf Ms Teams zugreifen | Identifizieren von Benutzern mit einer Teamlizenz im Mandanten | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| Member.Read.Hidden | Anwendung | Liste der Mitglieder | Abrufen einer Liste aller Teams, Team-&#8217;Mitglieder und ausgeblendeter Mitgliedschaften | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| Reports.Read.All | Anwendung | Tägliche Benutzeraktivitäten in Teams | Alle Benutzeraktivitäten in Teams lesen | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| Team.ReadBasic.All | Anwendung | Team-ID, Teamname, Kanal-ID, Kanalname | Auflisten aller Kanäle und Teams-Eigenschaften | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| User.Read | Delegiert | Benutzer-ID, Name, E-Mail-Adresse, Erstellungsdatum. Wir speichern diese Daten, um Nutzungsanalysen zu Teams | Identifizieren des aktuellen Benutzers während des Abonnements | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In unseren IT-Sicherheitsrichtlinien beschriebene Organisationsregel und Codierungsstandards verhindern, dass EUII und OII in den Protokollen angezeigt werden

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Where/How: Azure/Azure Database for PostgreSQL servers Wer can access it: our application and the database administrators Authorization control: 
 - Individuelle Autorisierungssteuerung: RBAC
 - Systemautorisierungssteuerung: private Endpunkte in virtuellen Azure-Netzwerken

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Tryane bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>- Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
