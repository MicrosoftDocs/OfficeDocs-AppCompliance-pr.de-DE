---
title: Anwendungsinformationen für die Reichweite von LiveTiles
ms.author: elmalova
author: elenamalova
ms.date: 03/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Reach, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 83df050a6f58bc1d0b7d49239b40ddf2ba80849a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551996"
---
# <a name="reach"></a>Reach

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 22. März 2021</p>

* <a href="https://teams.microsoft.com/l/app/5df8ebd2-bf7b-4fb5-bb35-0bfbf5d10a23" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002045" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Von LiveTiles Microsoft zur Verfügung gestellt wird:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Reach |
| ID | WA200002045 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | LiveTiles |
| URL der Partner-Website | [https://livetilesglobal.com](https://livetilesglobal.com) |
| URL Teams Anwendungsinfoseite | [https://livetilesglobal.com/products/livetiles-reach/](https://livetilesglobal.com/products/livetiles-reach/) |
| URL der Datenschutzrichtlinie | [https://livetilesglobal.com/privacy-policy](https://livetilesglobal.com/privacy-policy) |
| URL der Nutzungsbedingungen | [https://livetilesglobal.com/eula](https://livetilesglobal.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von LiveTiles darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| TeamsActivity.Send | Anwendung | keine | Keine | a7c1920d-3ac0-42db-9757-078a2b321fd8  |
>| User.Read | Delegiert | BenutzerAnzeigename, Benutzer-E-Mail-Adresse, UPN. Erforderlich, damit sich Benutzer bei der App anmelden und grundlegende Informationen des angemeldeten Benutzers abrufen können, z. B. den Anzeigenamen. Die E-Mail-Adresse wird zum Senden von E-Mail-Benachrichtigungen verwendet.  | BenutzerAnzeigename, Benutzer-E-Mail-Adresse, UPN. Erforderlich, damit sich Benutzer bei der App anmelden und grundlegende Informationen des angemeldeten Benutzers abrufen können, z. B. den Anzeigenamen. Die E-Mail-Adresse wird zum Senden von E-Mail-Benachrichtigungen verwendet.  | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| User.ReadBasic.All | Delegiert | Benutzeranzeigename, Benutzer-E-Mail-Adresse, UPN, Benutzerabteilung, Benutzerjob-Titel, Benutzer-Mobil-Telefon-Nummer, Benutzer-Business-Telefon-Nummer, Benutzer-Office-Standort. Erforderlich, damit Benutzer in der App (Telefonbuch) nach anderen Benutzern suchen und das grundlegende Profil und die Kontaktinformationen anderer Benutzer anzeigen können.  | keine | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| Directory.Read.All | Anwendung | Gruppenmitgliedschaft, AD-Gruppen im Verzeichnis. Die Gruppenmitgliedschaft von Benutzern wird in einem Cache gespeichert, um Aufrufe von Microsoft Graph-API zu minimieren. Erforderlich, damit Benutzer nach Active Directory-Gruppen suchen können. Darüber hinaus ist diese Berechtigung erforderlich, damit die Anwendung die AD-Gruppenmitgliedschaft von Benutzern in Webaufträgen des Backends auflöst. | Gruppenmitgliedschaft von Benutzern. Die Gruppenmitgliedschaft von Benutzern wird in einem Cache gespeichert, um Aufrufe von Microsoft Graph-API zu minimieren. Erforderlich, damit Benutzer nach Active Directory-Gruppen suchen können. Darüber hinaus ist diese Berechtigung erforderlich, damit die Anwendung die AD-Gruppenmitgliedschaft von Benutzern in Webaufträgen des Backends auflöst.  | d492530a-8cff-481c-90da-9c3c3f1be7da  |
>| User.Read.All | Anwendung | Die aus dem Benutzerprofil abgerufenen Daten hängen von der in der App angegebenen Zielgruppen-Ausrichtungs-Featurekonfiguration ab. Erforderlich, damit die App Benutzerprofile ohne angemeldeten Benutzer lesen kann. Für die Informationsausrichtungsfunktion in der Anwendung ist das Lesen von Profildaten erforderlich, sodass die Informationen bestimmten Benutzern basierend auf einem bestimmten Profileigenschaftswert angezeigt werden.  | keine | d492530a-8cff-481c-90da-9c3c3f1be7da  |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| SendGrid, OneSignal | E-Mail-Adresse, Anzeigename | Senden von Benachrichtigungen an den Benutzer per E-Mail und mobile Push-Benachrichtigungen |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird kein EUII abgerufen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>E-Mail-Adresse, UPN. maximal 60 Tage Aufbewahrung, danach werden sie entfernt

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Die Administratoren können sich an den Support für jede Anfrage wenden.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von LiveTiles darüber bereitgestellt, wie diese App authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Können Sie sich in Microsoft Identifizplattform (Azure AD) integrieren?  | Ja |
| Haben Sie alle in der Checkliste für die Microsoft Identity Platform-Integration beschriebenen bewährten Methoden überprüft und eingehalten?  | Nein |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Conditional Access-Richtlinien? | Ja |
| Auflisten der unterstützten Richtlinientypen | Multi-Faktor-Authentifizierung, Einschränken von Benutzerstandorten und IP-Bereichen |
| Fordert Ihre App die geringsten Berechtigungsberechtigungen für Ihr Szenario an? | Ja |
| Gibt die statisch registrierten Berechtigungen Ihrer App die Berechtigungen wieder, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Multi-Tenancy? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle für Ihre App registrierten Unified Resource Identifier (URI) umleiten? | Ja |
| Was vermeiden Sie für Ihre App? | - Wildcard-Umleitungs-URIs,<br/>- OAuth2 Implizite Flow, es sei denn, dies ist für ein SPA erforderlich<br/>- Ressourcenbesitzer-Kennwortanmeldeinformationen (ROPC)-Flow |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann zu, dass Aufrufe erfolgreich sind, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
