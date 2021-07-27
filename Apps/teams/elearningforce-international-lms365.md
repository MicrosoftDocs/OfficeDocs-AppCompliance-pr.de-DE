---
title: Anwendungsinformationen für LMS365 von ELEARNINGFORCE International
ms.author: elmalova
author: elenamalova
ms.date: 03/18/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Complianceinformationen für LMS365, die Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security Informationen zum App-Katalog und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4a4690496c4da8fd31de70bfa796d15d73dba844
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521768"
---
# <a name="lms365"></a>LMS365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: March 18, 2021</p>

* <a href="https://teams.microsoft.com/l/app/d136f17e-df84-47f2-97a4-13aa24c0c647" target="_blank">Anzeigen in Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381467" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von ELEARNINGFORCE International für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | LMS365 |
| ID | WA104381467 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | ELEARNINGFORCE International |
| URL der Partnerwebsite | [https://www.elearningforce.com](https://www.elearningforce.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| URL der Datenschutzrichtlinie | [https://www.elearningforce.com/privacy](https://www.elearningforce.com/privacy) |
| URL der Nutzungsbedingungen | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von ELEARNINGFORCE International darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| GroupMember.Read.All | Anwendung | Keine | Ermöglicht der App, AD-Gruppenmitglieder zu erweitern, was erforderlich ist, um eine Gruppe von Benutzern für die Kurse zu registrieren. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| Mail.Send | Delegiert | Keine | Die Berechtigung wird während der Konfiguration des E-Mail-Kontos für Benachrichtigungen dynamisch angefordert. Ermöglicht der App das Senden von Benachrichtigungs-E-Mails | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| RoleManagement.Read.Directory | Anwendung | Keine | Ermöglicht der App, während der Mandantenbereitstellung SharePoint Domäne abzurufen. Die Domäne wird für die URL-Erstellung verwendet. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| User.Invite.All | Delegiert | Keine | Ermöglicht der App, externe Benutzer im Namen des aktuell angemeldeten Benutzers einzuladen. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| User.Read | Delegiert | Keine | Melden Sie sich an, und lesen Sie das Benutzerprofil. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| User.Read.All | Delegiert | Keine | Ermöglicht der App, das vollständige Profil des aktuell angemeldeten Benutzers zu lesen. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| User.Read.All | Anwendung | Ermöglicht der App das Lesen des vollständigen Benutzerprofils. Es&#8217;benötigt, um Benutzer&#8217; Manager zu lesen, um Hierarchieberichte zu erstellen. | Die folgenden personenbezogenen Daten werden in einer dedizierten Datenbank für den jeweiligen Kunden gespeichert, der für die Dashboard-Funktionen des Verwaltungsmanagers für Lernende innerhalb der Anwendung verwendet &amp; wird. Kontoname, Anzeigename des Benutzers, E-Mail-Adresse, Abteilung, Position, Office, Land, Stadt, Manager-ID/E-Mail | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| Profil | Delegiert | Keine | Zeigen Sie das grundlegende Profil des Benutzers an. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, können zusätzliche microsoft-APIs außer Microsoft Graph verwenden, um Organisationsdaten zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft auf, Graph diese App verwendet.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Wir verwenden den Vornamen nur, um eine personalisierte Nachricht anzuzeigen, wenn der Bot den Benutzer empfängt. | Personenbezogene Daten werden in einer dedizierten Azure-Datenbank für den jeweiligen Kunden gespeichert, der für die Dashboard-Funktionen von Student Management &amp; Manager innerhalb der LMS365-Anwendung verwendet wird. | Kontoname, Anzeigename des Benutzers, E-Mail-Adresse, Abteilung, Position, Office, Land, Stadt, Manager-ID/E-Mail |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Ja, wir verwenden Insights Log Analytics-Telemetriedaten/-protokolle, die nur für Das Aufnehmen von Problemen verwendet werden und eine Aufbewahrungsrichtlinie von 90 Tagen haben, nach der alle Daten gelöscht werden.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>LMS365 ist mit einer Bereinigungsfunktion ausgestattet, die alle personenbezogenen Daten aus der LMS365-Datenbank des Clients entfernt.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von ELEARNINGFORCE International darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Geräteplattformen, Gerätestatus, Client-Apps |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
