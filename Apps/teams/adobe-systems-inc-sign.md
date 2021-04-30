---
title: Anwendungsinformationen für Adobe Sign by Adobe Systems Inc.
ms.author: elmalova
author: elenamalova
ms.date: 03/01/2021
ms.topic: article
ms.service: attestation
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Adobe Sign, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 04ac0c0c2c9f40371b32b3d48b361ec99b959ab0
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095647"
---
# <a name="adobe-sign"></a>Adobe Sign

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Zuletzt aktualisiert vom Entwickler am: 1. März 2021</p>

* <a href="https://teams.microsoft.com/l/app/0f56a9d1-f502-40f9-a9e8-816d7adbb68b" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381233" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Adobe Systems Inc. an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Adobe Sign |
| ID | WA104381233 |
| Funktionen | Bot, Registerkarte |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Adobe Systems Inc. |
| URL der Partnerwebsite | [https://acrobat.adobe.com/us/en/sign.html](https://acrobat.adobe.com/us/en/sign.html) |
| URL Teams Anwendungsinfoseite | [https://helpx.adobe.com/sign/help/adobesign_microsoft_teams...](https://helpx.adobe.com/sign/help/adobesign_microsoft_teams.html) |
| URL der Datenschutzrichtlinie | [https://www.adobe.com/privacy/policy.html](https://www.adobe.com/privacy/policy.html) |
| URL der Nutzungsbedingungen | [https://www.adobe.com/legal/licenses-terms.html](https://www.adobe.com/legal/licenses-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Adobe Systems Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | delegierte | So füllen Sie das angefügte Dokument, absender- und empfänger-E-Mails und Nachrichteninhalte aus E-Mails an Adobe unter, um sie zur Signatur zu senden. Dadurch wird dem Benutzer Zeit zum erneuten Einschreiben dieser Felder in Adobe Sign erspart. Nachdem ein Vertrag unterzeichnet wurde, verfassen wir automatisch eine neue E-Mail, damit der Benutzer eine E-Mail sendet, um seine Empfänger über die Transaktion zu informieren. | Adobe Sign speichern die Anlagen als temporäre Dateien, deren Ablauf 24 Stunden ist. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| People.Read | delegierte | Zum automatischen Ausfüllen der E-Mail-Adresse in der Funktion Signatur senden müssen Benutzer nicht die gesamten E-Mails eingeben, indem Sie einige Anfangsbuchstaben &quot; &quot; eingeben. | In Adobe Sign werden nur E-Mails und displayName von Empfängern in den Vereinbarungen gespeichert. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| User.Read | delegierte | Um das Profil des Benutzers zu lesen und sein Profil (im Wesentlichen seine E-Mail und userId) mit unserer Datenbank zu übereinstimmen, damit er Adobe Sign verwenden kann. | Um das Profil des Benutzers zu lesen und sein Profil (im Wesentlichen seine E-Mail und userId) mit unserer Datenbank zu übereinstimmen, damit er Adobe Sign verwenden kann. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| offline_access | delegierte | So aktualisieren Sie das Zugriffstoken, wenn das aktuelle Token abgelaufen ist. Wenn sich der Benutzer beispielsweise in einem Fenster zum Senden von Signaturen befindet und es zu lange inaktiv lässt, müssen wir ein neues Token aktualisieren, um den Benutzer &quot; &quot; aktiv zu halten. | So aktualisieren Sie das Zugriffstoken, wenn das aktuelle Token abgelaufen ist. Wenn sich der Benutzer beispielsweise in einem Fenster zum Senden von Signaturen befindet und es zu lange inaktiv lässt, müssen wir ein neues Token aktualisieren, um den Benutzer &quot; &quot; aktiv zu halten. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| openid | delegierte | E-Mail und UserId. So melden Sie sich an, um ihre Zustimmung für die Verwendung der Adobe Sign-App sicherzustellen.  | E-Mail ist der eindeutige Bezeichner für Benutzer in Adobe Sign. Wir speichern E-Mail-ID, damit wir alle Aktivitäten dieses Benutzers seinem Adobe Sign-Eintrag zuordnungen können.  | 72d5ac5d-a427-408b-907d-72da3f33dd1 |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mithilfe anderer Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 können zusätzliche Microsoft-APIs als Microsoft Graph verwenden, um identifizierbare Informationen (OII) der Organisation zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft Graph diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Teams API | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Zur Anpassung von Chatnachrichten und Authentifizierung | UserPrincipalName, Name, E-Mail und objectId | Wir speichern diese Informationen zur Anpassung asynchroner Antworten und Authentifizierungszwecke. |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Unsere Protokolle enthalten ausreichende Informationen, um Kundenprobleme identifizieren und beheben zu können. Protokolle werden für 90 Tage aufbewahrt, und der Zugriff ist eingeschränkt. Unsere Datenbankspeicher-Hashidentifikationsinformationen für die Authentifizierung, während der Benutzer offline ist. Datenbankaufbewahrungsrichtlinie liegt 30 Tage nach der letzten Verwendung

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>In unserem System gibt es keine Interaktion von Kundenadministratoren für Microsoft Teams Anwendung.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Adobe Systems Inc. dazu bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden geprüft und befolgt, die in der Prüfliste Microsoft Identity Platform aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Bittet Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordern wird? | Ja |
| Unterstützt Ihre App mehrere Mandanzfähigkeiten? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle umgeleiteten Unified Resource Identifier (URI), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | - UrIs für die Platzhalterumleitung,
<br />
- OAuth2 Implizite Flow, es sei denn, dies ist für eine SPA erforderlich
<br />
- Ablauf der Kennwortanmeldeinformationen (Password Credential, ROPC) des Ressourcenbesitzers | | Macht Ihre App Web-APIs verfügbar? | Ja | | Lässt Ihr Berechtigungsmodell nur dann den Erfolg von Aufrufen zu, wenn die Client-App die entsprechende Zustimmung erhält? | Ja | | Verwendet Ihre App Vorschau-APIs? | Keine | | Verwendet Ihre App veraltete APIs? | Keine |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
