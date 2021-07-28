---
title: Application Information for Fellow by Fellow Insights Inc
ms.author: elmalova
author: elenamalova
ms.date: 05/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für "Fellow", seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 581b41bdf80bcbdd77bb3406b35556308a13b8f9
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525639"
---
# <a name="fellow"></a>Fellow

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 21, 2021</p>

* <a href="https://teams.microsoft.com/l/app/f6671df0-1909-428c-91f7-1c42df04d3e4" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002576" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Von Fellow Insights Inc an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Fellow |
| ID | WA200002576 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | Fellow Insights Inc |
| URL der Partnerwebsite | [https://fellow.app](https://fellow.app) |
| URL der Datenschutzrichtlinie | [https://fellow.app/privacy-policy/](https://fellow.app/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://fellow.app/terms-of-use/](https://fellow.app/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Kollegen Insights Inc. bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | Beide | Mitmenschen stellen eine Verbindung mit den Kalendern des Benutzers her, um ihnen die Möglichkeit zu bieten, Notizen zu den Daten zu machen. | "Kollegen" speichert alle Ereignisdaten für den primären Kalender des Benutzers. Anlagen werden nicht gespeichert. Dies wird in Fellow verwendet, um eine kalenderbasierte Notizenerfahrung bereitzustellen. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Channel.ReadBasic.All | Delegiert | Wir erfassen die Namen von Kanälen, bei denen ein Benutzer Mitglied ist, um eine Liste der Kanäle anzuzeigen, an die er Notizen senden kann. | Die Namen und IDs von Kanälen, in denen ein Benutzer Mitglied ist, werden zwischengespeichert, um Benutzern das Senden von Notizen von "Fellow" an den angegebenen Kanal zu ermöglichen. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Directory.Read.All | Anwendung | Diese Daten werden nur gesammelt, wenn eine Administratorinstallation für die gesamte Organisation erfolgt. Wir verwenden die Verzeichnisdaten, um eine Liste von Benutzern zu synchronisieren und Automatisch Konten bereitzustellen. | Wenn und nur, wenn eine organisationsweite Installation vom Administrator innerhalb der Arbeitsbereichseinstellungen innerhalb von "Fellow" ausgeführt wird, haben Administratoren die Möglichkeit, die automatische Synchronisierung aller Benutzer aus Azure AD mit "Fellow" (automatische Bereitstellung) zu aktivieren. In diesem Fall speichern wir Benutzerinformationen wie ID, Name, E-Mail und Manager sowie Gruppenmitgliedschaften (für Teamverwaltungsfunktionen). | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Group.Read.All | Anwendung | Diese Daten werden nur gesammelt, wenn eine Administratorinstallation für die gesamte Organisation erfolgt. Wir verwenden die Verzeichnisdaten, um eine Liste von Benutzern zu synchronisieren und Automatisch Konten bereitzustellen. | Wenn und nur, wenn eine organisationsweite Installation vom Administrator innerhalb der Arbeitsbereichseinstellungen innerhalb von "Fellow" ausgeführt wird, haben Administratoren die Möglichkeit, die automatische Synchronisierung aller Benutzer aus Azure AD mit "Fellow" (automatische Bereitstellung) zu aktivieren. In diesem Fall speichern wir Benutzerinformationen wie ID, Name, E-Mail und Manager sowie Gruppenmitgliedschaften (für Teamverwaltungsfunktionen). | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| People.Read | Delegiert | Die Kontakte des Benutzers werden in bestimmten Kontaktanzeigenamen und E-Mail-Adressen gesammelt. Dies wird in Fellow verwendet, um eine Liste der Benutzer bereitzustellen, die zur Einladung zu einer Notiz/zum Freigeben einer Notiz einladen können. | Die Kontakte des Benutzers werden in bestimmten Kontaktanzeigenamen und E-Mail-Adressen gesammelt. Dies wird in Fellow verwendet, um eine Liste der Benutzer bereitzustellen, die zur Einladung zu einer Notiz/zum Freigeben einer Notiz einladen können. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| People.Read.All | Anwendung | Diese Daten werden nur gesammelt, wenn eine Administratorinstallation für die gesamte Organisation erfolgt. Die Kontakte des Benutzers werden in bestimmten Kontaktanzeigenamen und E-Mail-Adressen gesammelt. Dies wird in Fellow verwendet, um eine Liste der Benutzer bereitzustellen, die zur Einladung zu einer Notiz/zum Freigeben einer Notiz einladen können. | Wenn und nur, wenn eine organisationsweite Installation vom Administrator innerhalb der Arbeitsbereichseinstellungen innerhalb von "Fellow" ausgeführt wird, haben Administratoren die Möglichkeit, die automatische Synchronisierung aller Benutzer aus Azure AD mit "Fellow" (automatische Bereitstellung) zu aktivieren. In diesem Fall werden die Kontakte des Benutzers in bestimmten Kontaktanzeigenamen und E-Mail-Adressen gesammelt. Dies wird in Fellow verwendet, um eine Liste der Benutzer bereitzustellen, die zur Einladung zu einer Notiz/zum Freigeben einer Notiz einladen können. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Team.ReadBasic.All | Delegiert | Eine Liste der Teams, zu der der Benutzer gehört, wird gesammelt. Dies wird innerhalb von Mitmenschen verwendet, um es dem Benutzer zu ermöglichen, Notizen von Einem Anderen an ein Team zu senden. | Die Namen und IDs von Teams, in denen ein Benutzer Mitglied ist, werden zwischengespeichert, um Benutzern das Senden von Notizen von "Kollegen" an den angegebenen Teams-Kanal zu ermöglichen. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| User.Read | Delegiert | Grundlegende Benutzerinformationen werden gesammelt. Benutzername, E-Mail, Position. Diese Informationen werden in "Kollegen" zum Erstellen von Benutzerkonten und Unternehmenskonten verwendet. | Grundlegende Benutzerinformationen werden gespeichert. Benutzername, E-Mail, Position. Diese Informationen werden innerhalb von "Kollegen" verwendet, um Benutzerkonten und Unternehmenskonten zu verwalten. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| User.Read.All | Anwendung | Diese Daten werden nur gesammelt, wenn eine Administratorinstallation für die gesamte Organisation erfolgt. Wir verwenden die Verzeichnisdaten, um eine Liste von Benutzern zu synchronisieren und Automatisch Konten bereitzustellen. | Wenn und nur, wenn eine organisationsweite Installation vom Administrator innerhalb der Arbeitsbereichseinstellungen innerhalb von "Fellow" ausgeführt wird, haben Administratoren die Möglichkeit, die automatische Synchronisierung aller Benutzer aus Azure AD mit "Fellow" (automatische Bereitstellung) zu aktivieren. In diesem Fall speichern wir Benutzerinformationen wie ID, Name, E-Mail und Manager sowie Gruppenmitgliedschaften (für Teamverwaltungsfunktionen). | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| offline_access | Delegiert | Das Aktualisierungstoken des Benutzers, um den Zugriff auf Daten aufrechtzuerhalten, die über andere Bereiche gesammelt werden. | Das Aktualisierungstoken des Benutzers wird in der Datenbank gespeichert. Dies wird in Fellow verwendet, um Ereignisse im Hintergrund für die kalenderbasierte Notizenerfahrung sowie Benachrichtigungen für die Notizen bei geplanten Ereignissen zu synchronisieren. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Mitmenschen speichern Informationen, die direkt vom Benutzer bereitgestellt werden, einschließlich personenbezogener Daten. Außerdem speichert Er einige Informationen aus Drittanbietersystemen, z. B. OAuth-Daten, Kalenderdaten und PII, &amp; z. B. Namens-E-Mails. Wir bewahren alle Daten auf unbestimmte Zeit auf, solange dies für den Zweck, für den sie gesammelt wurden, erforderlich und gesetzlich zulässig ist. Wir löschen diese Informationen sicher zu einem früheren Zeitpunkt nach Eingang einer Anfrage von Benutzern. Protokolldaten werden 30 Tage lang aufbewahrt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Alle Datenübertragungen erfolgen über gesicherte APIs an unsere Back-End-Systeme. Der Mitarbeiter verwendet viele Kontrollen, um die Sicherheit und Vertraulichkeit seiner Systeme gemäß dem SOC 2-Framework gemäß AICPA zu gewährleisten. Die Kontrollen von Kollegen werden einer jährlichen Prüfung unterzogen, um die fortlaufende Compliance sicherzustellen. Ein SOC 2-Bericht kann auf Anforderung und NDA freigegeben werden.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39739' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39739" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Kollegen Insights Inc. bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | ,<br/><br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
