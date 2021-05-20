---
title: Anwendungsinformationen für Adobe Sign for Word und PowerPoint von Adobe Inc.
ms.author: elmalova
author: elenamalova
ms.date: 02/12/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Adobe Sign for Word und PowerPoint, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: aa9b4a19f83574d7d9428bbf979ac7ee1375227c
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553646"
---
# <a name="adobe-sign-for-word-and-powerpoint"></a>Adobe Sign for Word und PowerPoint

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Zuletzt aktualisiert vom Entwickler am: 12. Februar 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381155" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Adobe Inc. an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Adobe Sign for Word und PowerPoint |
| ID | WA104381155 |
| Office 365 unterstützten Clients | Word 2016 oder höher auf mac, PowerPoint 2013 Service Pack 1 oder höher auf Windows, Word 2013 Service Pack 1 oder höher auf Windows, Word im Web, PowerPoint im Web, PowerPoint 2016 oder höher auf dem Mac |
| Partnerunternehmensname | Adobe Inc. |
| URL der Partnerwebsite | [https://www.adobe.com/](https://www.adobe.com/) |
| URL der Datenschutzrichtlinie | [https://www.adobe.com/privacy/policies-business/esign.html](https://www.adobe.com/privacy/policies-business/esign.html) |
| URL der Nutzungsbedingungen | [https://support.office.com/client/61994a3b-2c87-41c4-a88d-a...](https://support.office.com/client/61994a3b-2c87-41c4-a88d-a6455efa362d?omkt=en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Adobe Inc. bereitgestellt, um zu erfahren, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | delegierte | So füllen Sie das angefügte Dokument, absender- und empfänger-E-Mails und Nachrichteninhalte aus E-Mails an Adobe unter, um sie zur Signatur zu senden. Dadurch wird dem Benutzer Zeit zum erneuten Einschreiben dieser Felder in Adobe Sign erspart. Nachdem ein Vertrag unterzeichnet wurde, verfassen wir automatisch eine neue E-Mail, damit der Benutzer eine E-Mail sendet, um seine Empfänger über die Transaktion zu informieren. | Adobe Sign speichern die Anlagen als temporäre Dateien, deren Ablauf 24 Stunden ist. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| People.Read | delegierte | Zum automatischen Ausfüllen der E-Mail-Adresse in der Funktion Signatur senden müssen Benutzer nicht die gesamten E-Mails eingeben, indem Sie einige Anfangsbuchstaben &quot; &quot; eingeben. | In Adobe Sign werden nur E-Mails und displayName von Empfängern in den Vereinbarungen gespeichert. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| User.Read | delegierte | Um das Profil des Benutzers zu lesen und sein Profil (im Wesentlichen seine E-Mail und userId) mit unserer Datenbank zu übereinstimmen, damit er Adobe Sign verwenden kann. | Um das Profil des Benutzers zu lesen und sein Profil (im Wesentlichen seine E-Mail und userId) mit unserer Datenbank zu übereinstimmen, damit er Adobe Sign verwenden kann. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| offline_access | delegierte | So aktualisieren Sie das Zugriffstoken, wenn das aktuelle Token abgelaufen ist. Wenn sich der Benutzer beispielsweise in einem Fenster zum Senden von Signaturen befindet und es zu lange inaktiv lässt, müssen wir ein neues Token aktualisieren, wenn &quot; der Benutzer aktiv &quot; ist. | So aktualisieren Sie das Zugriffstoken, wenn das aktuelle Token abgelaufen ist. Wenn sich der Benutzer beispielsweise in einem Fenster zum Senden von Signaturen befindet und es zu lange inaktiv lässt, müssen wir ein neues Token aktualisieren, wenn &quot; der Benutzer aktiv &quot; ist. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| openid | delegierte | E-Mail und UserId. So melden Sie sich an, um ihre Zustimmung für die Verwendung der Adobe Sign-App sicherzustellen.  | E-Mail ist der eindeutige Bezeichner für Benutzer in Adobe Sign. Wir speichern E-Mail-ID, damit wir alle Aktivitäten dieses Benutzers seinem Adobe Sign-Eintrag zuordnungen können.  | 72d5ac5d-a427-408b-907d-72da3f33dd1 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



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

Diese Informationen wurden von Adobe Inc. dazu bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

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
| Was vermeiden Sie für Ihre App? | - UrIs für die Platzhalterumleitung,<br/>- OAuth2 Implizite Flow, es sei denn, dies ist für eine SPA erforderlich<br/>– Fluss mit Kennwortanmeldeinformationen (Password Credential, ROPC) des Ressourcenbesitzers |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann den Erfolg von Aufrufen zu, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
