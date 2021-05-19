---
title: Anwendungsinformationen für Priority Matrix - E-Mails in Aufgaben von Appfluence Inc. umwandeln
ms.author: elmalova
author: elenamalova
ms.date: 04/16/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Priority Matrix - Verwandeln Sie E-Mails in Aufgaben, ihre Datenverarbeitungsrichtlinien, ihre Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9843ece5a330f4a8b8adb6f1388a4a26e12dbe21
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553756"
---
# <a name="priority-matrix---turn-emails-into-tasks"></a>Priority Matrix - E-Mails in Aufgaben umwandeln

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Zuletzt aktualisiert vom Entwickler am: 16. April 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381735" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Appfluence Inc an Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Priority Matrix - E-Mails in Aufgaben umwandeln |
| ID | WA104381735 |
| Office 365 unterstützten Clients | Outlook 2016 oder später Windows, Outlook 2016 oder später auf Mac, Outlook auf iOS, Outlook auf Android, Outlook im Web |
| Name des Partnerunternehmens | Appfluence Inc |
| URL der Partner-Website | [https://appfluence.com/](https://appfluence.com/) |
| URL der Datenschutzrichtlinie | [https://appfluence.com/privacy](https://appfluence.com/privacy) |
| URL der Nutzungsbedingungen | [https://appfluence.com/eula](https://appfluence.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Appfluence Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | Delegiert | Nur wenn ein neuer Benutzer zum Konto hinzugefügt wird, speichern wir seine E-Mail. | Bei der Erstellung neuer Konten verwenden wir dies, um andere Teammitglieder vorzuschlagen. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| User.ReadBasic.All | Delegiert | Nur wenn ein neuer Benutzer zum Konto hinzugefügt wird, speichern wir seine E-Mail. | Bei der Erstellung neuer Konten verwenden wir dies, um andere Teammitglieder vorzuschlagen. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| offline_access | Delegiert | Wir speichern das Login-Token, um Anfragen im Auftrag des Benutzers auszuführen | Aktualisieren Sie das Token, ohne den Benutzer zu beunruhigen. (Prioritätsmatrix für Teams) | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| Files.Read.All | Delegiert | Wir speichern keine Dateiinformationen, es sei denn, der Benutzer erstellt explizit und wissentlich ein Priority Matrix-Element, das mit der Originaldatei verknüpft ist. | In unserer One-on-One-Funktion (verfügbar über unsere Web-App und auch unsere Outlook/Teams-Add-Ins) verwenden wir diese Funktion, um SharePoint/OneDrive-Dateien hervorzuheben, die von zwei Benutzern in unserem System gemeinsam genutzt werden, um Meetings und die allgemeine Zusammenarbeit zu erleichtern. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| User.Read | Delegiert | Grundlegende Benutzerprofilinformationen (Anzeigename, Vorname, Nachname, E-Mail, Avatar) werden von uns gespeichert. | Holen Sie sich den Namen des Benutzers, E-Mail, Avatar, um ihr Konto bei uns zu personalisieren. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| openid | Delegiert | Wir speichern die SSO-Verbindung, um den Anmeldemodus für den Benutzer anzuzeigen. | Um sich per Single-Sign-On anzumelden. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| Calendars.Read | Delegiert | Eine kleine Anzahl von Kalenderereignissen werden in Aufgaben umgewandelt, die in unserem System gespeichert sind. | Lesen Sie Kalenderereignisse, damit sie in unserer 1:1-Ansicht angezeigt werden können. Auch, um neue Konten zu initialisieren.  | d76f016f-52c7-41b5-835b-900361d7040c |
>| Mail.Read | Delegiert | Wir speichern in unserem System erstellte Aufgaben mit einem Link zur ursprünglichen Nachricht. | Wird in unserem Outlook-Add-In verwendet, um E-Mails in Aufgaben umzuwandeln und freigegebene Arbeit in der 1:1-Ansicht anzuzeigen. | d76f016f-52c7-41b5-835b-900361d7040c |
>| Tasks.Read | Delegiert | Einige Outlook/Planer-Aufgaben werden in unserem System repliziert, um neuen Benutzern zu helfen. | Wir bootstrap neue Benutzerkonten mit ihren Graph Aufgaben. | d76f016f-52c7-41b5-835b-900361d7040c |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Ja, wir verwenden die E-Mail des Benutzers als ihre eindeutige ID in unserem System, die verwendet wird, um Anwendungsfehler nachzuverfolgen und wichtige Ereignisse im System (Downloads, Anmeldungen, Anwendungsversionen usw.) zu verfolgen, damit unser Kundenserviceeine eine schnelle Antwort auf Kundenanfragen geben kann. Im Rahmen unserer DSGVO-Compliance löschen wir alle Kundendaten innerhalb von 2 Wochen nach einer Löschungsanfrage, obwohl wir dies in der Praxis am selben Tag tun, da wir interne Skripte haben, um dies halbautomatisch zu tun.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Anwendungsdaten werden sicher in einer verschlüsselten Datenbank gespeichert, wobei der Zugriff auf eine kleine Gruppe von Administratoren beschränkt ist. Um den Zugriff weiter zu sichern, erzwingen wir die 2-Faktor-Authentifizierung, beschränken den Zugriff auf einen kontrollierten Satz von IP-Adressen und suchen die Datenbank in einem eigenen privaten Subnetz, auf das direkt aus dem offenen Internet nicht zugegriffen werden kann.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Appfluence Inc. darüber bereitgestellt, wie diese App authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Können Sie sich in Microsoft Identifizplattform (Azure AD) integrieren?  | Ja |
| Haben Sie alle in der Checkliste für die Microsoft Identity Platform-Integration beschriebenen bewährten Methoden überprüft und eingehalten?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Conditional Access-Richtlinien? | Nein |
| Fordert Ihre App die geringsten Berechtigungsberechtigungen für Ihr Szenario an? | Ja |
| Gibt die statisch registrierten Berechtigungen Ihrer App die Berechtigungen wieder, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Multi-Tenancy? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle für Ihre App registrierten Unified Resource Identifier (URI) umleiten? | Ja |
| Was vermeiden Sie für Ihre App? | - Wildcard-Umleitungs-URIs,<br/><br/>- Ressourcenbesitzer-Kennwortanmeldeinformationen (ROPC)-Flow |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann zu, dass Aufrufe erfolgreich sind, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
