---
title: Anwendungsinformationen für Die Reichweite von LiveTiles
ms.author: elmalova
author: elenamalova
ms.date: 03/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 'Alle verfügbaren Sicherheits- und Complianceinformationen für Reach, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security Informationen zum #A0 sowie Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.'
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 81a3afa06f4843c68a5e32da49f7e7be09e0684a
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252455"
---
# <a name="reach"></a>Reach

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 22. März 2021</p>

* <a href="https://teams.microsoft.com/l/app/5df8ebd2-bf7b-4fb5-bb35-0bfbf5d10a23" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002045" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von LiveTiles an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Reach |
| ID | WA200002045 |
| Funktionen | Registerkarte |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | LiveTiles |
| URL der Partnerwebsite | [https://livetilesglobal.com](https://livetilesglobal.com) |
| URL Teams Anwendungsinfoseite | [https://livetilesglobal.com/products/livetiles-reach/](https://livetilesglobal.com/products/livetiles-reach/) |
| URL der Datenschutzrichtlinie | [https://livetilesglobal.com/privacy-policy](https://livetilesglobal.com/privacy-policy) |
| URL der Nutzungsbedingungen | [https://livetilesglobal.com/eula](https://livetilesglobal.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von LiveTiles darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| TeamsActivity.Send | Anwendung | keine | Keine | a7c1920d-3ac0-42db-9757-078a2b321fd8  |
>| User.Read | delegierte | User DisplayName, User Email Address, UPN. Erforderlich, um Benutzern die Anmeldung bei der App zu ermöglichen und grundlegende Informationen des angemeldeten Benutzers wie den Anzeigenamen zu erhalten. Die E-Mail-Adresse wird zum Senden von E-Mail-Benachrichtigungen verwendet.  | User DisplayName, User Email Address, UPN. Erforderlich, um Benutzern die Anmeldung bei der App zu ermöglichen und grundlegende Informationen des angemeldeten Benutzers wie den Anzeigenamen zu erhalten. Die E-Mail-Adresse wird zum Senden von E-Mail-Benachrichtigungen verwendet.  | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| User.ReadBasic.All | delegierte | User DisplayName, User Email Address, UPN, User Department, User Job Title, User Mobile Telefon Number, User Business Telefon Number, User Office Location. Erforderlich, um Benutzern die Suche nach anderen Benutzern in der App (Phonebook) zu ermöglichen und die grundlegenden Profil- und Kontaktinformationen anderer Benutzer zu sehen.  | keine | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| Directory.Read.All | Anwendung | Gruppenmitgliedschaft, AD-Gruppen in Directory. Gruppenmitgliedschaften von Benutzern werden in einem Cache gespeichert, um Anrufe an Microsoft Graph zu minimieren. Erforderlich, damit Benutzer nach Active Directory-Gruppen suchen können. Darüber hinaus ist diese Berechtigung erforderlich, damit die Anwendung die AD-Gruppenmitgliedschaft von Benutzern in Webaufträgen des Back-End-Servers auflösen kann. | Gruppenmitgliedschaft von Benutzern. Gruppenmitgliedschaften von Benutzern werden in einem Cache gespeichert, um Anrufe an Microsoft Graph zu minimieren. Erforderlich, damit Benutzer nach Active Directory-Gruppen suchen können. Darüber hinaus ist diese Berechtigung erforderlich, damit die Anwendung die AD-Gruppenmitgliedschaft von Benutzern in Webaufträgen des Back-End-Servers auflösen kann.  | d492530a-8cff-481c-90da-9c3c3f1be7da  |
>| User.Read.All | Anwendung | Daten, die aus dem Benutzerprofil abgerufen werden, hängen von der in der App angegebenen Featurekonfiguration für Zielgruppenzieleinstellungen ab. Erforderlich, damit die App Benutzerprofile ohne angemeldeten Benutzer lesen kann. Das Lesen von Profildaten ist für das Feature zum Ziel von Informationen in der Anwendung erforderlich, damit die Informationen bestimmten Benutzern basierend auf einem bestimmten Wert für die Profileigenschaft angezeigt werden.  | keine | d492530a-8cff-481c-90da-9c3c3f1be7da  |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| SendGrid, OneSignal | E-Mail-Adresse, Anzeigename | Senden von Benachrichtigungen per E-Mail und mobilen Pushbenachrichtigungen an den Benutzer |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Auf EUII wird nicht zugegriffen.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>E-Mail-Adresse, UPN. max. 60 Tage Aufbewahrung, danach werden sie entfernt

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die Administratoren können sich für jede Anfrage an den Support wenden.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von LiveTiles dazu bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden geprüft und befolgt, die in der Prüfliste Microsoft Identity Platform aufgeführt sind?  | Nein |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Mehrstufige Authentifizierung, Einschränken von Benutzerstandorten und IP-Bereichen |
| Bittet Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordern wird? | Ja |
| Unterstützt Ihre App mehrere Mandanzfähigkeiten? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle umgeleiteten Unified Resource Identifier (URI), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | - UrIs für die Platzhalterumleitung,<br/>- OAuth2 Implizite Flow, es sei denn, dies ist für eine SPA erforderlich<br/>– Fluss mit Kennwortanmeldeinformationen (Password Credential, ROPC) des Ressourcenbesitzers |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann den Erfolg von Aufrufen zu, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
