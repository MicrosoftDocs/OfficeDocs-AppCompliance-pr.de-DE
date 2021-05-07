---
title: Anwendungsinformationen für Tikit von Cireson
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Tikit, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c30afd0d75f8832bf94fedbf48cd64406a5a2a29
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252715"
---
# <a name="tikit"></a>Tikit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 11. März 2021</p>

* <a href="https://teams.microsoft.com/l/app/b13c40ee-e073-459e-96b5-3f3cca046a37" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002602" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Cireson an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Tikit |
| ID | WA200002602 |
| Funktionen | Bot, Messaging-Erweiterung |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Cireson |
| URL der Partnerwebsite | [https://tikit.ai](https://tikit.ai) |
| URL Teams Anwendungsinfoseite | [https://tikit.ai](https://tikit.ai) |
| URL der Datenschutzrichtlinie | [https://tikit.ai/privacy-statement](https://tikit.ai/privacy-statement) |
| URL der Nutzungsbedingungen | [https://tikit.ai/terms-service](https://tikit.ai/terms-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Cireson bereitgestellt, um zu erfahren, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Device.Read | Anwendung | Benutzerdiagramminformationen, die für einmaliges Anmelden über die Teams-Bot-Kommunikation verwendet werden  | Wir speichern Benutzerrollen, Familienname, Vorname, E-Mail, AAD-ID, Teams Benutzer-ID. Diese Information wird für anwendungsbasierte Authentifizierung, Sicherheit, RBAC, Teams-Integration, Teams-Benachrichtigungen und Benutzerbeziehungszuordnung verwendet.   | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.AccessAsUser.All | delegierte | Gruppennamen und Rollen für RBAC | Gruppenname &amp; Rollenname, müssen eine sichere zugeordnete Zugriffssteuerung bereitstellen. | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.Read.All | delegierte | Gruppennamen und Rollen für RBAC | Gruppenname &amp; Rollenname, müssen eine sichere zugeordnete Zugriffssteuerung bereitstellen. | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Group.Read.All | both | Gruppennamen und Rollen für RBAC | Gruppennamen und Rollen für RBAC | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read | delegierte | Benutzerrollen, Familienname, Vorname, E-Mail, AAD-ID, Teams- und Authentifizierungs-ID  | Benutzerrollen, Familienname, Vorname, E-Mail, AAD-ID, Teams- und Authentifizierungs-ID  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read.All | Anwendung | Benutzerrollen, Familienname, Vorname, E-Mail, AAD-ID, Teams- und Authentifizierungs-ID  | Benutzerrollen, Familienname, Vorname, E-Mail, AAD-ID, Teams- und Authentifizierungs-ID  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.ReadBasic.All | delegierte | Benutzerrollen, Familienname, Vorname, E-Mail, AAD-ID, Teams- und Authentifizierungs-ID  | Benutzerrollen, Familienname, Vorname, E-Mail, AAD-ID, Teams- und Authentifizierungs-ID  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| email | delegierte | Benutzer-E-Mail,die für die Anmeldung und die zugehörige Identifikation verwandter Entitäten verwendet wird. &quot;Zugewiesener Benutzer&quot; | Benutzer-E-Mail,die für die Anmeldung und die zugehörige Identifikation verwandter Entitäten verwendet wird. &quot;Zugewiesener Benutzer&quot; | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| openid | delegierte | für die Authentifizierung über MSAL pro Anforderung verwendet  | für die Authentifizierung über MSAL pro Anforderung verwendet  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Profil | delegierte | für die Authentifizierung über MSAL pro Anforderung verwendet  | für die Authentifizierung über MSAL pro Anforderung verwendet  | b13c40ee-e073-459e-96b5-3f3cca046a37 |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mithilfe anderer Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 können zusätzliche Microsoft-APIs als Microsoft Graph verwenden, um identifizierbare Informationen (OII) der Organisation zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft Graph diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| QnA Maker | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Name und E-Mail für Benutzerentitätsbeziehungen &quot; Ticket Requestor&quot;  | Name und E-Mail  | für Benutzerentitätsbeziehungen &quot; Ticket Requestor&quot;  |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir speichern Firmenname, Mandanten-ID, E-Mail, Bot-Client-ID in App-Einblicke, mit einer 30 dat-Aufbewahrungsrichtlinie.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir haben keine Daten in einem Partnersystem.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Cireson darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden geprüft und befolgt, die in der Prüfliste Microsoft Identity Platform aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Bittet Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordern wird? | Ja |
| Unterstützt Ihre App mehrere Mandanzfähigkeiten? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle umgeleiteten Unified Resource Identifier (URI), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | - UrIs für die Platzhalterumleitung,<br/>- OAuth2 Implizite Flow, es sei denn, dies ist für eine SPA erforderlich<br/>– Fluss mit Kennwortanmeldeinformationen (Password Credential, ROPC) des Ressourcenbesitzers |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann den Erfolg von Aufrufen zu, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
