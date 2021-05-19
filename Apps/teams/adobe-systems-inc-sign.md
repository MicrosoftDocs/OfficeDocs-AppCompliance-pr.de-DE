---
title: Anwendungsinformationen für Adobe Sign von Adobe Systems Inc.
ms.author: elmalova
author: elenamalova
ms.date: 03/01/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Adobe Sign, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7cb238a768ae020e13865748be5d0df96ebb35ca
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552426"
---
# <a name="adobe-sign"></a>Adobe Sign

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Zuletzt aktualisiert vom Entwickler am: 1. März 2021</p>

* <a href="https://teams.microsoft.com/l/app/0f56a9d1-f502-40f9-a9e8-816d7adbb68b" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381233" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Adobe Systems Inc. Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Adobe Sign |
| ID | WA104381233 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Adobe Systems Inc. |
| URL der Partner-Website | [https://acrobat.adobe.com/us/en/sign.html](https://acrobat.adobe.com/us/en/sign.html) |
| URL Teams Anwendungsinfoseite | [https://helpx.adobe.com/sign/help/adobesign_microsoft_teams...](https://helpx.adobe.com/sign/help/adobesign_microsoft_teams.html) |
| URL der Datenschutzrichtlinie | [https://www.adobe.com/privacy/policy.html](https://www.adobe.com/privacy/policy.html) |
| URL der Nutzungsbedingungen | [https://www.adobe.com/legal/licenses-terms.html](https://www.adobe.com/legal/licenses-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Adobe Systems Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | Delegiert | So füllen Sie das angehängte Dokument, Absender- und Empfänger-E-Mails sowie Nachrichteninhalte aus E-Mails an Adobe-Zeichen, um sie zur Signatur zu senden. Dadurch wird dem Benutzer Zeit gespart, diese Felder in Adobe Sign erneut einzugeben. Nachdem eine Vereinbarung unterzeichnet wurde, verfassen wir automatisch eine neue E-Mail, damit der Benutzer eine E-Mail senden kann, um seine Empfänger darüber zu informieren, dass die Transaktion durchgeführt wird. | Adobe Sign speichert die Anhänge als temporäre Dateien, die einen Ablauf von 24 Stunden haben. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| People.Read | Delegiert | Um die E-Mail-Adresse in der Erfahrung "Senden für Signatur" automatisch zu &quot; &quot; füllen, müssen Benutzer nicht die gesamten E-Mails eingeben, indem Sie einige Anfangsbuchstaben eingeben. | Adobe Sign speichert nur Empfänger-E-Mails und displayName in den Vereinbarungen. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| User.Read | Delegiert | Um das Profil des Benutzers zu lesen und sein Profil (im Grunde seine E-Mail-Adresse und Benutzerid) mit unserer Datenbank abzugleichen, damit sie Adobe Sign verwenden können. | Um das Profil des Benutzers zu lesen und sein Profil (im Grunde seine E-Mail-Adresse und Benutzerid) mit unserer Datenbank abzugleichen, damit sie Adobe Sign verwenden können. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| offline_access | Delegiert | So aktualisieren Sie das Zugriffstoken, wenn das aktuelle Token abgelaufen ist. Wenn sich der Benutzer beispielsweise in einem &quot; Fenster "Senden für Signatur" befindet und es zu lange &quot; inaktiv lässt, müssen wir ein neues Token aktualisieren, um den Benutzer aktiv zu halten. | So aktualisieren Sie das Zugriffstoken, wenn das aktuelle Token abgelaufen ist. Wenn sich der Benutzer beispielsweise in einem &quot; Fenster "Senden für Signatur" befindet und es zu lange &quot; inaktiv lässt, müssen wir ein neues Token aktualisieren, um den Benutzer aktiv zu halten. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| openid | Delegiert | E-Mail und UserId. So melden Sie den Benutzer an, um seine Zustimmung zur Verwendung der Adobe Sign-App sicherzustellen.  | E-Mail ist die eindeutige Kennung für Benutzer in Adobe Sign. Wir speichern die E-Mail-ID, damit wir alle Aktivitäten dieses Benutzers seinem Adobe Sign-Eintrag zuordnen können.  | 72d5ac5d-a427-408b-907d-72da3f33dd1 |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mithilfe anderer Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, können zusätzliche Microsoft-APIs verwenden, die nicht microsoft Graph sind, um unternehmensbezogene identifizierbare Informationen (OII) zu sammeln oder zu verarbeiten. Listen Sie alle Microsoft-APIs auf, die nicht von Microsoft Graph diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Rechtfertigung für das Sammeln von OII?** | **Wird OII gespeichert?** | **Rechtfertigung für die Speicherung von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Teams Api | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Zur Anpassung von Chat-Nachrichten und Authentifizierung | UserPrincipalName, Name, E-Mail und objectId | Wir speichern diese Informationen zur Anpassung asynchroner Antworten und Authentifizierungszwecken |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Unsere Protokolle enthalten ausreichende Informationen, um Kundenprobleme identifizieren und beheben zu können. Protokolle werden 90 Tage lang aufbewahrt, und der Zugriff ist eingeschränkt. Unsere Datenbank speichert gehashte Identifikationsinformationen für die Authentifizierung, während der Benutzer offline ist. Die Datenbankaufbewahrungsrichtlinie ist 30 Tage nach der letzten Verwendung

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Wir haben keine Kunden-Admin-Interaktion in unserem System für Microsoft Teams Anwendung.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Adobe Systems Inc. zur Verfügung gestellt, wie diese App authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Können Sie sich in Microsoft Identifizplattform (Azure AD) integrieren?  | Ja |
| Haben Sie alle in der Checkliste für die Microsoft Identity Platform-Integration beschriebenen bewährten Methoden überprüft und eingehalten?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Conditional Access-Richtlinien? | Nein |
| Fordert Ihre App die geringsten Berechtigungsberechtigungen für Ihr Szenario an? | Ja |
| Gibt die statisch registrierten Berechtigungen Ihrer App die Berechtigungen wieder, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Multi-Tenancy? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle für Ihre App registrierten Unified Resource Identifier (URI) umleiten? | Ja |
| Was vermeiden Sie für Ihre App? | - Wildcard-Umleitungs-URIs,<br/>- OAuth2 Implizite Flow, es sei denn, dies ist für ein SPA erforderlich<br/>- Ressourcenbesitzer-Kennwortanmeldeinformationen (ROPC)-Flow |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann zu, dass Aufrufe erfolgreich sind, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
