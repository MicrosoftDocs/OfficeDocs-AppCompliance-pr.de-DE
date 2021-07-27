---
title: Anwendungsinformationen für die Reichweite von LiveTiles
ms.author: elmalova
author: elenamalova
ms.date: 03/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Reach, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d188c61f6f87dbe528219d82f1b58477b184da8a
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521464"
---
# <a name="reach"></a>Reach

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 22. März 2021</p>

* <a href="https://teams.microsoft.com/l/app/5df8ebd2-bf7b-4fb5-bb35-0bfbf5d10a23" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002045" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von LiveTiles für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Reach |
| ID | WA200002045 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | LiveTiles |
| URL der Partnerwebsite | [https://livetilesglobal.com](https://livetilesglobal.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://livetilesglobal.com/products/livetiles-reach/](https://livetilesglobal.com/products/livetiles-reach/) |
| URL der Datenschutzrichtlinie | [https://livetilesglobal.com/privacy-policy/](https://livetilesglobal.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://livetilesglobal.com/eula/](https://livetilesglobal.com/eula/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von LiveTiles darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| TeamsActivity.Send | Anwendung | keine | Keine | [a7c1920d-3ac0-42db-9757-078a2b321fd8 ](https://docs.microsoft.com/microsoft-365-app-certification/azure/a7c1920d-3ac0-42db-9757-078a2b321fd8 ) |
>| User.Read | Delegiert | User DisplayName, User Email Address, UPN. Erforderlich, damit sich Benutzer bei der App anmelden und grundlegende Informationen des angemeldeten Benutzers abrufen können, z. B. den Anzeigenamen. Die E-Mail-Adresse wird zum Senden von E-Mail-Benachrichtigungen verwendet.  | User DisplayName, User Email Address, UPN. Erforderlich, damit sich Benutzer bei der App anmelden und grundlegende Informationen des angemeldeten Benutzers abrufen können, z. B. den Anzeigenamen. Die E-Mail-Adresse wird zum Senden von E-Mail-Benachrichtigungen verwendet.  | [d492530a-8cff-481c-90da-9c3c3f1be7da](https://docs.microsoft.com/microsoft-365-app-certification/azure/d492530a-8cff-481c-90da-9c3c3f1be7da) |
>| User.ReadBasic.All | Delegiert | User DisplayName, User Email Address, UPN, User Department, User Job Title, User Mobile Telefon Number, User Business Telefon Number, User Office Location. Erforderlich, damit Benutzer in der App nach anderen Benutzern suchen (Phonebook) und die grundlegenden Profil- und Kontaktinformationen anderer Benutzer anzeigen können.  | keine | [d492530a-8cff-481c-90da-9c3c3f1be7da](https://docs.microsoft.com/microsoft-365-app-certification/azure/d492530a-8cff-481c-90da-9c3c3f1be7da) |
>| Directory.Read.All | Anwendung | Gruppenmitgliedschaft, AD-Gruppen im Verzeichnis. Die Gruppenmitgliedschaft von Benutzern wird in einem Cache gespeichert, um Aufrufe der Microsoft Graph-API zu minimieren. Erforderlich, damit Benutzer nach Active Directory-Gruppen suchen können. Darüber hinaus ist diese Berechtigung erforderlich, damit die Anwendung die AD-Gruppenmitgliedschaft von Benutzern in Webaufträgen des Back-Ends auflösen kann. | Gruppenmitgliedschaft von Benutzern. Die Gruppenmitgliedschaft von Benutzern wird in einem Cache gespeichert, um Aufrufe der Microsoft Graph-API zu minimieren. Erforderlich, damit Benutzer nach Active Directory-Gruppen suchen können. Darüber hinaus ist diese Berechtigung erforderlich, damit die Anwendung die AD-Gruppenmitgliedschaft von Benutzern in Webaufträgen des Back-Ends auflösen kann.  | [d492530a-8cff-481c-90da-9c3c3f1be7da ](https://docs.microsoft.com/microsoft-365-app-certification/azure/d492530a-8cff-481c-90da-9c3c3f1be7da ) |
>| User.Read.All | Anwendung | Die aus dem Benutzerprofil abgerufenen Daten hängen von der in der App angegebenen Konfiguration des Zielgruppenadressierungsfeatures ab. Erforderlich, damit die App Benutzerprofile ohne einen angemeldeten Benutzer lesen kann. Das Lesen von Profildaten ist für das Feature für die Informationsadressierung innerhalb der Anwendung erforderlich, damit die Informationen basierend auf einem bestimmten Profileigenschaftenwert für bestimmte Benutzer angezeigt werden.  | keine | [d492530a-8cff-481c-90da-9c3c3f1be7da ](https://docs.microsoft.com/microsoft-365-app-certification/azure/d492530a-8cff-481c-90da-9c3c3f1be7da ) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| SendGrid, OneSignal | E-Mail-Adresse, Anzeigename | Senden von Benachrichtigungen an Benutzer per E-Mail und mobilen Pushbenachrichtigungen |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>E-Mail-Adresse, UPN. max. 60 Tage Aufbewahrung, danach werden sie entfernt

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die Administratoren können sich bei jeder Anfrage an den Support wenden.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von LiveTiles darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Nein |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Mehrstufige Authentifizierung, Einschränken von Benutzerspeicherorten und IP-Bereichen |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>– Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
