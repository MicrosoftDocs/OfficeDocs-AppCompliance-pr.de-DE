---
title: Anwendungsinformationen für Adobe Sign von Adobe Systems Inc.
ms.author: elmalova
author: elenamalova
ms.date: 10/20/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Adobe Sign, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 13bb571bab1fa34a772aaf528579698b064c03cb
ms.sourcegitcommit: cab3c02db1b748f3502714d89bd9b65408fd9f54
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/22/2021
ms.locfileid: "60545595"
---
# <a name="adobe-sign"></a>Adobe Sign

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: October 20, 2021</p>

* <a href="https://teams.microsoft.com/l/app/0f56a9d1-f502-40f9-a9e8-816d7adbb68b" target="_blank">Anzeigen in Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381233" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Adobe Systems Inc. für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Adobe Sign |
| ID | WA104381233 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | Adobe Systems Inc. |
| URL der Partnerwebsite | [https://acrobat.adobe.com/us/en/sign.html](https://acrobat.adobe.com/us/en/sign.html) |
| URL Teams Anwendungsinformationsseite | [https://helpx.adobe.com/sign/help/adobesign_microsoft_teams...](https://helpx.adobe.com/sign/help/adobesign_microsoft_teams.html) |
| URL der Datenschutzrichtlinie | [https://www.adobe.com/privacy/policy.html](https://www.adobe.com/privacy/policy.html) |
| URL der Nutzungsbedingungen | [https://www.adobe.com/legal/terms.html](https://www.adobe.com/legal/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Adobe Systems Inc. bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Mail.ReadWrite | Delegiert | Zum Auffüllen des angefügten Dokuments, der Absender- und Empfänger-E-Mails und des Nachrichteninhalts von E-Mails an Adobe Sign, das zur Signatur gesendet werden soll. Dadurch wird dem Benutzer Zeit zum erneuten Eingeben dieser Felder in Adobe Sign gespart. Nachdem eine Vereinbarung signiert wurde, erstellen wir automatisch eine neue E-Mail, damit der Benutzer eine E-Mail sendet, um seine Empfänger darüber zu informieren, dass die Transaktion abgeschlossen ist. | Adobe Sign speichert die Anlagen als temporäre Dateien, die einen Ablauf von 24 Stunden haben. | [a9b0c190-bafb-49ca-a61a-dab99cf2c43b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9b0c190-bafb-49ca-a61a-dab99cf2c43b) |
>| People.Read | Delegiert | Zum automatischen Ausfüllen der E-Mail-Adresse in der &quot; Benutzeroberfläche "Zur Signatur senden" &quot; müssen Benutzer durch Die Eingabe einiger Anfangsbuchstaben nicht die gesamten E-Mails eingeben. | Adobe Sign speichert empfänger-E-Mails und displayName nur in den Vereinbarungen. | [a9b0c190-bafb-49ca-a61a-dab99cf2c43b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9b0c190-bafb-49ca-a61a-dab99cf2c43b) |
>| User.Read | Delegiert | Um das Profil des Benutzers zu lesen und sein Profil (im Wesentlichen seine E-Mail- und Benutzer-ID) mit unserer Datenbank abzugleichen, damit er Adobe Sign verwenden kann. | Um das Profil des Benutzers zu lesen und sein Profil (im Wesentlichen seine E-Mail- und Benutzer-ID) mit unserer Datenbank abzugleichen, damit er Adobe Sign verwenden kann. | [a9b0c190-bafb-49ca-a61a-dab99cf2c43b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9b0c190-bafb-49ca-a61a-dab99cf2c43b) |
>| offline_access | Delegiert | So aktualisieren Sie das Zugriffstoken, wenn das aktuelle abgelaufen ist. Wenn sich der Benutzer beispielsweise in einem &quot; Sendefenster für ein Signaturfenster befindet &quot; und es zu lange inaktiv lässt, müssen wir ein neues Token aktualisieren, um den Benutzer aktiv zu halten. | So aktualisieren Sie das Zugriffstoken, wenn das aktuelle abgelaufen ist. Wenn sich der Benutzer beispielsweise in einem &quot; Sendefenster für ein Signaturfenster befindet &quot; und es zu lange inaktiv lässt, müssen wir ein neues Token aktualisieren, um den Benutzer aktiv zu halten. | [a9b0c190-bafb-49ca-a61a-dab99cf2c43b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9b0c190-bafb-49ca-a61a-dab99cf2c43b) |
>| openid | Delegiert | E-Mail und UserId. So melden Sie sich an, um sicherzustellen, dass sie der Berechtigung zur Verwendung der Adobe Sign-App zustimmen.  | E-Mail ist der eindeutige Bezeichner für Benutzer in Adobe Sign. Wir speichern die E-Mail-ID, damit wir alle Aktivitäten dieses Benutzers seinem Adobe Sign-Eintrag zuordnen können.  | [a9b0c190-bafb-49ca-a61a-dab99cf2c43b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9b0c190-bafb-49ca-a61a-dab99cf2c43b) |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise zusätzliche Andere Microsoft-APIs als Microsoft Graph, um organisationsbezogene Informationen (OII) zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft auf, Graph diese App verwendet.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Teams API | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Zur Anpassung von Chatnachrichten und zur Authentifizierung | UserPrincipalName, Name, E-Mail und objectId | Wir speichern diese Informationen für die Anpassung asynchroner Antworten und Authentifizierungszwecke. |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Unsere Protokolle enthalten ausreichende Informationen, um Kundenprobleme zu identifizieren und zu beheben. Protokolle werden 90 Tage lang aufbewahrt, und der Zugriff ist eingeschränkt. In unserer Datenbank werden Hash-Identifikationsinformationen für die Authentifizierung gespeichert, während der Benutzer offline ist. Datenbankaufbewahrungsrichtlinie ist 30 Tage nach der letzten Verwendung

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir verfügen über keine Interaktion des Kundenadministrators in unserem System für Microsoft Teams Anwendung.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Adobe Systems Inc. darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

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
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>– Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
