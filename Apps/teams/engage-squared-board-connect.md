---
title: Anwendungsinformationen für board Verbinden von Engage Squared
ms.author: elmalova
author: elenamalova
ms.date: 02/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Board Verbinden, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 6b314c6cc51515efced101ba986555d859dc4182
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553186"
---
# <a name="board-connect"></a>Board Connect

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Februar 2021</p>

* <a href="https://teams.microsoft.com/l/app/e8f06a4e-cefe-4b1e-a24b-c97bea471130" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001955" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Engage Squared an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Board Connect |
| ID | WA200001955 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Engage Squared |
| URL der Partnerwebsite | [https://boardconnect.app](https://boardconnect.app) |
| URL Teams Anwendungsinfoseite | [https://boardconnect.app](https://boardconnect.app) |
| URL der Datenschutzrichtlinie | [https://boardconnect.app/privacy](https://boardconnect.app/privacy) |
| URL der Nutzungsbedingungen | [https://boardconnect.app/terms](https://boardconnect.app/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Engage Squared bereitgestellt, um zu erfahren, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegierte | So ermöglichen Sie der App, Benutzerkalender so zu aktualisieren, dass sie ihre über die App übermittelten Antworten auf die Besprechungssitzungen widerspiegeln. | In unserem Azure-Tabellenspeicher werden keine Daten gespeichert. | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| Group.ReadWrite.All | delegierte | So ermöglichen Sie der App das Erstellen, Aktualisieren und Löschen von Gruppenkalenderereignissen. | Wir speichern die ID der Gruppe zusammen mit der Mandanten-ID – diese wird aus Lizenzierungssicht gespeichert und verwendet, damit wir überprüfen können, ob die Organisation für Board-Verbinden. Wir verwenden dies auch, um zu verfolgen, wie viele Installationen der Anwendungen innerhalb des Mandanten verfügbar sind, da dies inline mit unserem Lizenzierungsmodell ist. | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| Sites.Manage.All | delegierte | Damit die App Listen und Bibliotheken erstellen kann, verwalten Sie Listenelemente und Dokumente in einer Teamwebsitesammlung. | Keine | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| User.Read | delegierte | So ermöglichen Sie Benutzern, sich bei der App zu registrieren und der App zu erlauben, das Profil des aktuell angemeldeten Benutzers zu lesen. | In unserem Azure-Tabellenspeicher werden keine Daten von diesem Endpunkt gespeichert. | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| User.ReadBasic.All | delegierte | So können Sie der App erlauben, einen grundlegenden Satz von Profileigenschaften anderer Benutzer im Namen des angemeldeten Benutzers zu lesen, um dies in der App anzeigen zu können. Dazu gehören Anzeigename, Vor- und Nachname, E-Mail-Adresse und Foto. | Keine, Daten werden nicht in unserem Azure-Tabellenspeicher gespeichert | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| offline_access | delegierte | Damit die App ein Aktualisierungstoken erhalten kann, das sie verwenden kann, um ein neues Zugriffstoken zu erhalten, wenn das aktuelle Token abläuft. | Keine, Daten werden nicht in unserem Azure-Tabellenspeicher gespeichert | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Auf EUII wird nicht zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>2FA für alle Administratoren, auf die nur zwei benutzer mit einem Sprechplatz zugreifen können

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36435' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36435" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Engage Squared darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden geprüft und befolgt, die in der Prüfliste Microsoft Identity Platform aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Bittet Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordern wird? | Ja |
| Unterstützt Ihre App mehrere Mandanzfähigkeiten? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle umgeleiteten Unified Resource Identifier (URI), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | - UrIs für die Platzhalterumleitung,<br/>- OAuth2 Implizite Flow, es sei denn, dies ist für eine SPA erforderlich<br/> |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann den Erfolg von Aufrufen zu, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
