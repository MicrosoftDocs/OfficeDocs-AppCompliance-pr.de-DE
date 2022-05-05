---
title: Anwendungsinformationen für LMS365
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Complianceinformationen für LMS365, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7136a0f4a71f54772dc250433686996f2d236a19
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/05/2022
ms.locfileid: "65224989"
---
# <a name="application-information-for-lms365-by-elearningforce-international-aps"></a>Anwendungsinformationen für LMS365 von ELEARNINGFORCE International Aps

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Letzte Aktualisierung durch den Entwickler am: 23. Juni 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/elearningforce.lms365_spfx" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von ELEARNINGFORCE International Aps an Microsoft bereitgestellt werden:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | LMS365 |
| ID | elearningforce.lms365_spfx |
| Name des Partnerunternehmens | ELEARNINGFORCE International Aps |
| URL der Partnerwebsite | [https://www.elearningforce.com](https://www.elearningforce.com) |
| URL der Datenschutzrichtlinie | [https://www.lms365.com/privacy](https://www.lms365.com/privacy) |
| URL der Nutzungsbedingungen | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von ELEARNINGFORCE International Aps darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Auflisten aller [Microsoft Graph Berechtigungen](/graph/permissions-reference), die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegiert/Anwendung)** | **Werden Daten erfasst? Begründung für das Sammeln?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember.Read.All | Anwendung | Keine | Ermöglicht der App, AD-Gruppenmitglieder zu erweitern, was erforderlich ist, um eine Gruppe von Benutzern für die Kurse zu registrieren. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Mail.Send | Delegiert | Keine | Die Berechtigung wird während der Konfiguration des E-Mail-Kontos für die Benachrichtigung dynamisch angefordert. Ermöglicht der App das Senden von Benachrichtigungs-E-Mails | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| RoleManagement.Read.Directory | Anwendung | Keine | Ermöglicht der App, während der Mandantenbereitstellung SharePoint Domäne abzurufen. Die Domäne wird für die URL-Erstellung verwendet. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Invite.All | Delegiert | Keine | Ermöglicht der App, externe Benutzer im Namen des aktuell angemeldeten Benutzers einzuladen. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read | Delegiert | Keine | Melden Sie sich an, und lesen Sie das Benutzerprofil. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | Delegiert | Keine | Ermöglicht der App, das vollständige Profil des aktuell angemeldeten Benutzers zu lesen. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | Anwendung | Ermöglicht der App das Lesen des vollständigen Benutzerprofils. Es&#8217;erforderlich, um Benutzer&#8217; Manager zu lesen, um Hierarchieberichte zu erstellen. | Die folgenden personenbezogenen Daten werden in einer dedizierten Datenbank für den jeweiligen Kunden gespeichert, der für die Funktionen des Learner Management &amp; Manager-Dashboards innerhalb der Anwendung verwendet wird. Kontoname, Benutzername, E-Mail-Adresse, Abteilung, Position, Office, Land, Ort, Manager-ID/E-Mail | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Profil | Delegiert | Keine | Zeigen Sie das grundlegende Profil des Benutzers an. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise andere Microsoft-APIs als Microsoft Graph, um Organisationsinformationen (OII) zu sammeln oder zu verarbeiten. Auflisten aller anderen Microsoft-APIs als Microsoft Graph, die diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Begründung für das Sammeln von OII?** | **Ist OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder freigibt, listen Sie den von der App nicht von Microsoft stammenden Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder Endbenutzer-identifizierbare Informationen (EUII) in den Telemetriedaten oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Aufbewahrungs- und Entfernungsrichtlinien gelten?

>Ja, wir verwenden Insights Log Analytics-Telemetrie/-Protokolle, die nur zur Problembeschießung verwendet werden und über eine Aufbewahrungsrichtlinie von 90 Tagen verfügen, nach der alle Daten gelöscht werden.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren der Organisation ihre Informationen in Partnersystemen steuern können? z.B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>LMS365 ist mit einer Bereinigungsfunktion ausgestattet, mit der alle personenbezogenen Daten aus der LMS365-Datenbank der Clients entfernt werden.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational Identifiable Information) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">Auf einer neuen Registerkarte anzeigen</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von ELEARNINGFORCE International Aps darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Response** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden überprüft und eingehalten, die in der Checkliste für die Microsoft Identity Platform Integration aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Geräteplattformen, Gerätestatus, Client-Apps |
| Fordert Ihre App Berechtigungen mit den geringsten Berechtigungen für Ihr Szenario an? | Ja |
| Entsprechen die statisch registrierten Berechtigungen Ihrer App genau den Berechtigungen, die ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrinstanzenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie den gesamten umleitenden Unified Resource Identifier (URI), der für Ihre App registriert ist? | Ja |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur den Erfolg von Aufrufen zu, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
