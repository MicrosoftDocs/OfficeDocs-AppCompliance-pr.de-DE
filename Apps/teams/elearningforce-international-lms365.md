---
title: Anwendungsinformationen für LMS365 von ELEARNINGFORCE International
ms.author: elmalova
author: elenamalova
ms.date: 02/25/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für LMS365, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 03f831a0dd6c1b2b17b7ce12a3d421eb8fe1f10d
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252645"
---
# <a name="lms365"></a>LMS365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 25. Februar 2021</p>

* <a href="https://teams.microsoft.com/l/app/d136f17e-df84-47f2-97a4-13aa24c0c647" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381467" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von ELEARNINGFORCE International an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | LMS365 |
| ID | WA104381467 |
| Funktionen | Bot, Registerkarte, Messaging-Erweiterung |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | ELEARNINGFORCE International |
| URL der Partnerwebsite | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| URL Teams Anwendungsinfoseite | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| URL der Datenschutzrichtlinie | [https://www.elearningforce.com/privacy](https://www.elearningforce.com/privacy) |
| URL der Nutzungsbedingungen | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von ELEARNINGFORCE International darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember.Read.All | Anwendung | Keine | Ermöglicht der App das Erweitern von AD-Gruppenmitgliedern, die erforderlich sind, um benutzergruppen für die Kurse zu registrieren. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Mail.Send | delegierte | Keine | Die Berechtigung wird dynamisch beim Konfigurieren des E-Mail-Kontos für Benachrichtigungen angefordert. Ermöglicht der App das Senden von Benachrichtigungs-E-Mails | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| RoleManagement.Read.Directory | Anwendung | Keine | Ermöglicht der App das SharePoint während der Mandantenbereitstellung. Die Domäne wird für die URL-Erstellung verwendet. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Invite.All | delegierte | Keine | Ermöglicht der App das Einladen externer Benutzer im Namen des aktuell angemeldeten Benutzers | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read | delegierte | Keine | Melden Sie sich an, und lesen Sie das Benutzerprofil. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | delegierte | Keine | Ermöglicht der App, das vollständige Profil des aktuell angemeldeten Benutzers zu lesen. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | Anwendung | Ermöglicht der App das Lesen des vollständigen Benutzerprofils. Es&#8217;erforderlich, Benutzer und&#8217; zum Erstellen von Hierarchieberichten zu lesen. | Die folgenden personenbezogenen Daten werden in einer dedizierten Datenbank für den jeweiligen Kunden gespeichert, der für die Funktionalität des Learner Management &amp; Manager Dashboards innerhalb der Anwendung verwendet wird. Kontoname, Anzeigename des Benutzers, E-Mail-Adresse, Abteilung, Auftragstitel, Office, Land, Stadt, Manager-ID/E-Mail | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Profil | delegierte | Keine | Zeigen Sie das grundlegende Profil des Benutzers an. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mithilfe anderer Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 können zusätzliche Microsoft-APIs als Microsoft Graph verwenden, um identifizierbare Informationen (OII) der Organisation zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft Graph diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Wir verwenden den Vornamen nur, um eine personalisierte Nachricht zu zeigen, wenn der Bot den Benutzer begrüßt. | Personenbezogene Daten werden in einer dedizierten Azure-Datenbank für den jeweiligen Kunden gespeichert, der für die Funktionalität des Learner Management &amp; Manager Dashboards in der LMS365-Anwendung verwendet wird. | Kontoname, Anzeigename des Benutzers, E-Mail-Adresse, Abteilung, Auftragstitel, Office, Land, Stadt, Manager-ID/E-Mail |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Ja, wir verwenden Insights Log Analytics-Telemetrie/-protokolle, die nur zur Problemaufnahme verwendet werden und eine Aufbewahrungsrichtlinie von 90 Tagen haben, nach der alle Daten gelöscht werden.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>LMS365 ist mit einer Purge-Funktion ausgestattet, mit der personenbezogene Daten aus den Clients der LMS365-Datenbank entfernt werden.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von ELEARNINGFORCE International dazu bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden geprüft und befolgt, die in der Prüfliste Microsoft Identity Platform aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Geräteplattformen, Gerätestatus, Client-Apps |
| Bittet Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordern wird? | Ja |
| Unterstützt Ihre App mehrere Mandanzfähigkeiten? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle umgeleiteten Unified Resource Identifier (URI), die für Ihre App registriert sind? | Ja |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann den Erfolg von Aufrufen zu, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
