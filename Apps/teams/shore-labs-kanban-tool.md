---
title: Application Information for Labs von Labs
ms.author: elmalova
author: elenamalova
ms.date: 06/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für das Tool "Centers", seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: b73351d77f68cf00b904d95336f83d8089095791
ms.sourcegitcommit: 78e63c8004c49fa95d80618b9fee424f1084e43d
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/19/2021
ms.locfileid: "58404576"
---
# <a name="kanban-tool"></a>Tool "Aus dem Werkzeug"

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 15, 2021</p>

* <a href="https://teams.microsoft.com/l/app/b3c15d4f-1972-4836-a1eb-7575dd56a17e" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002121" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Labs für Microsoft bereitgestellte Informationen:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | Tool "Aus dem Werkzeug" |
| ID | WA200002121 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | Shore Labs |
| URL der Partnerwebsite | [https://www.shorelabs.com](https://www.shorelabs.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://kanbantool.com](https://kanbantool.com) |
| URL der Datenschutzrichtlinie | [https://kanbantool.com/policy/privacy](https://kanbantool.com/policy/privacy) |
| URL der Nutzungsbedingungen | [https://kanbantool.com/policy/terms-of-service](https://kanbantool.com/policy/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Labs zur Verfügung gestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | Delegiert | Die E-Mail-Adresse des Benutzers für Kommunikation, Identitätsabgleich und Zustellung von Benachrichtigungen. | E-Mail-Adresse. | [4e820d60-9e62-403c-accd-857b987cc13c](https://docs.microsoft.com/microsoft-365-app-certification/azure/4e820d60-9e62-403c-accd-857b987cc13c) |
>| Team.ReadBasic.All | Delegiert | Bezeichner und Namen der Teams, bei denen der Benutzer ein direktes Mitglied ist. Sie werden verwendet, um Benutzern automatisch die richtigen Gruppen im Tool "Werkzeug" zuzuweisen. | Teambezeichner und Namen, bei denen der angemeldete Benutzer ein direktes Mitglied ist, werden Gruppen im Tool "Gif" zugeordnet. Dies ermöglicht die gruppenbasierte Zugriffsverwaltung und Freigabe von Boards zwischen verschiedenen Teams in derselben Organisation. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| User.Read | Delegiert | Grundlegende Unternehmensinformationen von angemeldeten Benutzern. Es wird verwendet, um die Kontodetails für neue Konten aufzufüllen und Benutzer zu erkennen, die zu Ihrer Organisation gehören, um Funktionen für einzelne Sign-On bereitzustellen. | Name und ein eindeutiger Microsoft-Bezeichner Ihrer Organisation. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| offline_access | Delegiert | Ermöglicht die Funktion "Anmelden mit Microsoft" und die Synchronisierung von Daten, auf die Sie der App Zugriff gewährt haben, nach der Anmeldung des Benutzers. | Behalten Sie den Zugriff auf die Daten bei, auf die Sie ihr Zugriff gewährt haben. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| openid | Delegiert | Öffnen Sie ID-Token, die es Benutzern ermöglichen, sich mit ihren Geschäfts-, Schul- oder Unikonten über die Schaltfläche "Bei Microsoft anmelden" bei der App anzumelden. | Ein unveränderlicher Bezeichner für ein Benutzerkonto im Microsoft-Identitätssystem. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| Profil | Delegiert | Benutzername zum automatischen Auffüllen im Tool "Werkzeuge" und Synchronisierung mit Änderungen in Microsoft Teams. | Der vollständige Name des Benutzers. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Das Tool Verwendet die folgenden Unterprozessoren für die Leistung des Diensts: https://kanbantool.com/policy/privacy#appointed-subprocessors |   | Wir verwenden diese Drittanbieter, um die technische Infrastruktur bereitzustellen und zu verwalten und bei der Abrechnung und Zahlungsverarbeitung zu unterstützen. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir erfassen automatisch technische Informationen über Ihr Konto und Ihre Aktivität im Dienst. Diese Informationen werden in internen Protokolldateien gespeichert und können OII- und EUII-Daten enthalten, wenn sie Teil der von Ihnen durchgeführten Aktivität waren. Wir geben keine Protokolldateien für Dritte frei. Der Zweck der Erfassung von Protokolldaten besteht aus rechtlichen und behördlichen Gründen, um die Quelle potenzieller Sicherheitsverstöße oder Missbrauch des Diensts zu identifizieren, die Anforderungsrate zu begrenzen und leistungsbezogene Profilerstellung durchzuführen.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Kontoadministratoren haben Vollzugriff, einschließlich der Möglichkeit, personenbezogene Daten im Zusammenhang mit ihrem Konto zu ändern und zu entfernen, und sind die eigentlichen Datenverantwortlichen.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Labs zur Verfügung gestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Response** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | ,<br/>– Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
