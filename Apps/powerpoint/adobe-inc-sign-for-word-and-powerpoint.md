---
title: Anwendungsinformationen für Adobe Sign for Word und PowerPoint von Adobe Inc.
ms.author: elmalova
author: elenamalova
ms.date: 02/12/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Adobe Sign for Word und PowerPoint, seine Datenverarbeitungsrichtlinien, die Informationen zum Microsoft Cloud App Security App-Katalog und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: aa9b4a19f83574d7d9428bbf979ac7ee1375227c
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553646"
---
# <a name="adobe-sign-for-word-and-powerpoint"></a>Adobe Sign für Word und PowerPoint

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Zuletzt aktualisiert vom Entwickler am: 12. Februar 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381155" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Adobe Inc. Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Adobe Sign für Word und PowerPoint |
| ID | WA104381155 |
| Office 365 unterstützten Clients | Word 2016 oder später auf Mac, PowerPoint 2013 Service Pack 1 oder höher auf Windows, Word 2013 Service Pack 1 oder höher Windows, Word im Web, PowerPoint im Web, PowerPoint 2016 oder später auf Mac |
| Name des Partnerunternehmens | Adobe Inc. |
| URL der Partner-Website | [https://www.adobe.com/](https://www.adobe.com/) |
| URL der Datenschutzrichtlinie | [https://www.adobe.com/privacy/policies-business/esign.html](https://www.adobe.com/privacy/policies-business/esign.html) |
| URL der Nutzungsbedingungen | [https://support.office.com/client/61994a3b-2c87-41c4-a88d-a...](https://support.office.com/client/61994a3b-2c87-41c4-a88d-a6455efa362d?omkt=en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Adobe Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | Delegiert | So füllen Sie das angehängte Dokument, Absender- und Empfänger-E-Mails sowie Nachrichteninhalte aus E-Mails an Adobe-Zeichen, um sie zur Signatur zu senden. Dadurch wird dem Benutzer Zeit gespart, diese Felder in Adobe Sign erneut einzugeben. Nachdem eine Vereinbarung unterzeichnet wurde, verfassen wir automatisch eine neue E-Mail, damit der Benutzer eine E-Mail senden kann, um seine Empfänger darüber zu informieren, dass die Transaktion durchgeführt wird. | Adobe Sign speichert die Anhänge als temporäre Dateien, die einen Ablauf von 24 Stunden haben. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| People.Read | Delegiert | Um die E-Mail-Adresse in der Erfahrung "Senden für Signatur" automatisch zu &quot; &quot; füllen, müssen Benutzer nicht die gesamten E-Mails eingeben, indem Sie einige Anfangsbuchstaben eingeben. | Adobe Sign speichert nur Empfänger-E-Mails und displayName in den Vereinbarungen. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| User.Read | Delegiert | Um das Profil des Benutzers zu lesen und sein Profil (im Grunde seine E-Mail-Adresse und Benutzerid) mit unserer Datenbank abzugleichen, damit sie Adobe Sign verwenden können. | Um das Profil des Benutzers zu lesen und sein Profil (im Grunde seine E-Mail-Adresse und Benutzerid) mit unserer Datenbank abzugleichen, damit sie Adobe Sign verwenden können. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| offline_access | Delegiert | So aktualisieren Sie das Zugriffstoken, wenn das aktuelle Token abgelaufen ist. Wenn sich der Benutzer beispielsweise in einem &quot; Fenster "Senden für Signatur" befindet und es zu lange &quot; inaktiv lässt, müssen wir ein neues Token aktualisieren, wenn der Benutzer aktiv ist. | So aktualisieren Sie das Zugriffstoken, wenn das aktuelle Token abgelaufen ist. Wenn sich der Benutzer beispielsweise in einem &quot; Fenster "Senden für Signatur" befindet und es zu lange &quot; inaktiv lässt, müssen wir ein neues Token aktualisieren, wenn der Benutzer aktiv ist. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| openid | Delegiert | E-Mail und UserId. So melden Sie den Benutzer an, um seine Zustimmung zur Verwendung der Adobe Sign-App sicherzustellen.  | E-Mail ist die eindeutige Kennung für Benutzer in Adobe Sign. Wir speichern die E-Mail-ID, damit wir alle Aktivitäten dieses Benutzers seinem Adobe Sign-Eintrag zuordnen können.  | 72d5ac5d-a427-408b-907d-72da3f33dd1 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



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

Diese Informationen wurden von Adobe Inc. darüber bereitgestellt, wie diese App authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

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
