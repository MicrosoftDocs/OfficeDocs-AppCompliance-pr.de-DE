---
title: Anwendungsinformationen für Stapel von Crowd Cast, Ltd.
ms.author: elmalova
author: elenamalova
ms.date: 09/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Stapel, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: fa258f568d799ceb8891cd374aa33277dbc6c2c4
ms.sourcegitcommit: 3ac3366e04e24db2d12183ef212738d5b599f553
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/28/2021
ms.locfileid: "59975231"
---
# <a name="staple"></a>Grundnahrungsmittel

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 27, 2021</p>

* <a href="https://teams.microsoft.com/l/app/ac9ca94a-e666-4f61-959a-12c063e13e69" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003281" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Crowd Cast, Ltd. an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Grundnahrungsmittel |
| ID | WA200003281 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Crowd Cast, Ltd. |
| URL der Partnerwebsite | [https://crowdcast.jp/ja/](https://crowdcast.jp/ja/) |
| URL der Seite mit Teams Anwendungsinformationen | [https://intercom.help/staple/ja](https://intercom.help/staple/ja) |
| URL der Datenschutzrichtlinie | [https://crowdcast.jp/ja/privacy/](https://crowdcast.jp/ja/privacy/) |
| URL der Nutzungsbedingungen | [https://go.microsoft.com](https://go.microsoft.com) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Crowd Cast, Ltd. bereitgestellt. Darüber, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Organization.Read.All | Anwendung | Wird zum Sammeln der Mandanten-ID verwendet. Wird verwendet, um sicherzustellen, dass Benutzer, die sich bei unserer Plattform authentifizieren, Mitglied eines bestimmten Mandanten sind. | Mandanten-ID. Wird verwendet, um sicherzustellen, dass Benutzer, die sich bei unserer Plattform authentifizieren, Mitglied eines bestimmten Mandanten sind. | [ac9ca94a-e666-4f61-959a-12c063e13e69](https://docs.microsoft.com/microsoft-365-app-certification/azure/ac9ca94a-e666-4f61-959a-12c063e13e69) |
>| TeamsAppInstallation.ReadWriteSelfForUser.All | Anwendung | Teams App installiert sich selbst im Team des Benutzers | Nicht zutreffend | [ac9ca94a-e666-4f61-959a-12c063e13e69](https://docs.microsoft.com/microsoft-365-app-certification/azure/ac9ca94a-e666-4f61-959a-12c063e13e69) |
>| AppCatalog.Read.All | Delegiert | Liest den App-Katalog eines Benutzers, um festzustellen, ob die Teams-App installiert ist. | Nicht zutreffend | [bbdcd676-7448-453c-bec7-70e5384bc290](https://docs.microsoft.com/microsoft-365-app-certification/azure/bbdcd676-7448-453c-bec7-70e5384bc290) |
>| User.Read | Delegiert | Wird verwendet, um die ID eines Benutzers zu lesen, um sicherzustellen, dass Nachrichten an den richtigen Benutzer gesendet werden. | Benutzer-ID gespeichert, um proaktive Nachrichten an den Benutzer zu senden. | [bbdcd676-7448-453c-bec7-70e5384bc290](https://docs.microsoft.com/microsoft-365-app-certification/azure/bbdcd676-7448-453c-bec7-70e5384bc290) |
>| openid | Delegiert | Anmelden eines Benutzers, um seine grundlegenden Profilinformationen zu lesen | Nicht zutreffend | [bbdcd676-7448-453c-bec7-70e5384bc290](https://docs.microsoft.com/microsoft-365-app-certification/azure/bbdcd676-7448-453c-bec7-70e5384bc290) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Personenbezogene Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die Administratorsteuerdaten unserer Organisation in den Systemen eines Partners (AWS, Heroku).

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>No

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

Diese Informationen wurden von Crowd Cast, Ltd. bereitgestellt. Darüber, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | No |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | No |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | No |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>- Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | No |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
