---
title: Anwendungsinformationen für LMS365 von ELEARNINGFORCE International
ms.author: elmalova
author: elenamalova
ms.date: 02/25/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für LMS365, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 44ed1631c7d0221b463f518f2494b7a8744eef30
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552216"
---
# <a name="lms365"></a>LMS365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 25. Februar 2021</p>

* <a href="https://teams.microsoft.com/l/app/d136f17e-df84-47f2-97a4-13aa24c0c647" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381467" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die ELEARNINGFORCE International Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | LMS365 |
| ID | WA104381467 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | ELEARNINGFORCE International |
| URL der Partner-Website | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| URL Teams Anwendungsinfoseite | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| URL der Datenschutzrichtlinie | [https://www.elearningforce.com/privacy](https://www.elearningforce.com/privacy) |
| URL der Nutzungsbedingungen | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von ELEARNINGFORCE International darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember.Read.All | Anwendung | Keine | Ermöglicht der App das Erweitern von AD-Gruppenmitgliedern, die zum Registrieren einer Benutzergruppe für die Kurse erforderlich sind. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Mail.Send | Delegiert | Keine | Die Berechtigung wird beim Konfigurieren des E-Mail-Kontos für die Benachrichtigung dynamisch angefordert. Ermöglicht App das Senden von Benachrichtigungs-E-Mails | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| RoleManagement.Read.Directory | Anwendung | Keine | Ermöglicht App, während der Mandantenbereitstellung SharePoint Domäne abzubekommen. Die Domäne wird für die URL-Erstellung verwendet. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Invite.All | Delegiert | Keine | Ermöglicht App das Einladen externer Benutzer im aktuellen angemeldeten Benutzernamen | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read | Delegiert | Keine | Melden Sie sich an und lesen Sie das Benutzerprofil. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | Delegiert | Keine | Ermöglicht App, das vollständige Profil des aktuell angemeldeten Benutzers zu lesen. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | Anwendung | Ermöglicht App das Lesen des vollständigen Benutzerprofils. Es&#8217;erforderlich ist, Benutzer&#8217; Manager zu lesen, um Hierarchieberichte zu erstellen. | Die folgenden personenbezogenen Daten werden in einer dedizierten Datenbank für den jeweiligen Kunden gespeichert, der für die Learner Management &amp; Manager Dashboard-Funktionalität in der Anwendung verwendet wird. Kontoname, Benutzeranzeigename, E-Mail-Adresse, Abteilung, Jobtitel, Office, Land, Stadt, Manager-ID/E-Mail | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Profil | Delegiert | Keine | Zeigen Sie das Basisprofil des Benutzers an. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mithilfe anderer Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, können zusätzliche Microsoft-APIs verwenden, die nicht microsoft Graph sind, um unternehmensbezogene identifizierbare Informationen (OII) zu sammeln oder zu verarbeiten. Listen Sie alle Microsoft-APIs auf, die nicht von Microsoft Graph diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Rechtfertigung für das Sammeln von OII?** | **Wird OII gespeichert?** | **Rechtfertigung für die Speicherung von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Wir verwenden den Vornamen nur, um eine personalisierte Nachricht anzuzeigen, wenn der Bot den Benutzer begrüßt. | Persönliche Daten werden in einer dedizierten Azure-Datenbank für den jeweiligen Kunden gespeichert, der für die Learner Management &amp; Manager Dashboard-Funktionalität in der LMS365-Anwendung verwendet wird. | Kontoname, Benutzeranzeigename, E-Mail-Adresse, Abteilung, Jobtitel, Office, Land, Stadt, Manager-ID/E-Mail |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Ja, wir verwenden Insights Log Analytics-Telemetriedaten/-protokolle, die nur für die Fehlerbehebung verwendet werden und eine 90-Tage-Aufbewahrungsrichtlinie haben, nach der alle Daten gelöscht werden.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>LMS365 ist mit einer Bereinigungsfunktion ausgestattet, mit der alle personenbezogenen Daten aus der LMS365-Datenbank des Clients entfernt werden.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von ELEARNINGFORCE International darüber bereitgestellt, wie diese App authentifizierung, Autorisierung, Best Practices für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Können Sie sich in Microsoft Identifizplattform (Azure AD) integrieren?  | Ja |
| Haben Sie alle in der Checkliste für die Microsoft Identity Platform-Integration beschriebenen bewährten Methoden überprüft und eingehalten?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Conditional Access-Richtlinien? | Ja |
| Auflisten der unterstützten Richtlinientypen | Geräteplattformen, Gerätestatus, Client-Apps |
| Fordert Ihre App die geringsten Berechtigungsberechtigungen für Ihr Szenario an? | Ja |
| Gibt die statisch registrierten Berechtigungen Ihrer App die Berechtigungen wieder, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Multi-Tenancy? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle für Ihre App registrierten Unified Resource Identifier (URI) umleiten? | Ja |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann zu, dass Aufrufe erfolgreich sind, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
