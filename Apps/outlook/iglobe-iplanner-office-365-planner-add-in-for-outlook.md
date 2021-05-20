---
title: Anwendungsinformationen für iPlanner Office 365 Planner-Add-In für Outlook von iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Complianceinformationen für iPlanner Office 365 Planner-Add-In für Outlook, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c7eef95df6de269d9e383e604aa8ff32518584e1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552536"
---
# <a name="iplanner-office-365-planner-add-in-for-outlook"></a>iPlanner Office 365 Planner-Add-In für Outlook

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Zuletzt aktualisiert vom Entwickler am: 17. November 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380147" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von iGlobe an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | iPlanner Office 365 Planner-Add-In für Outlook |
| ID | WA104380147 |
| Office 365 unterstützten Clients | Outlook 2013 oder höher auf Windows, Outlook 2016 oder höher auf dem Mac, Outlook im Web |
| Partnerunternehmensname | iGlobe |
| URL der Partnerwebsite | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| URL der Datenschutzrichtlinie | [https://iglobecrm.com/content/legal-information](https://iglobecrm.com/content/legal-information) |
| URL der Nutzungsbedingungen | [https://iglobecrm.com/content/end-user-license-agreement-ig...](https://iglobecrm.com/content/end-user-license-agreement-iglobe-iplanner-add-ins) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von iGlobe darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Um die Planeraufgabe zu erhalten und neue Aufgaben hinzuzufügen, aktualisieren Sie den Bucket und die Schwimmlinie für den jeweiligen Benutzer | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Contacts.ReadWrite | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | So erstellen Sie einen Termin im Benutzerkalender zum Fälligkeitsdatum der Vorgänge | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Directory.AccessAsUser.All | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Ermöglicht der App den gleichen Zugriff auf Informationen im Verzeichnis wie dem angemeldeten Benutzer. | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Files.Read | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | So greifen Sie auf Datei als Anlage zu und laden Sie Dateien in eine Aufgabe hoch | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Files.ReadWrite.All | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Den E-Mail-Betreff aus der ausgewählten E-Mail-Nachricht erhalten. Ermöglicht der App, Informationen aus der ausgewählten E-Mail zu erhalten, sodass das Beschreibungsfeld in die Aufgabenbeschreibung kopiert und Anlagen aus der E-Mail oder der E-Mail selbst in der Aufgabe gespeichert werden können. | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Group.Read.All | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. |  Um die Planeraufgabe zu erhalten und neue Aufgaben hinzuzufügen, aktualisieren Sie den Bucket und die Schwimmlinie für den bestimmten Benutzer | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| User.Read | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Um die Planeraufgabe zu erhalten und neue Aufgaben hinzuzufügen, aktualisieren Sie den Bucket und die Schwimmlinie für den jeweiligen Benutzer | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| User.ReadBasic.All | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. |  Suchen Sie nach Berechtigungen, und erhalten Sie die Planeraufgabe, und fügen Sie neue Aufgaben hinzu, aktualisieren Sie den Bucket und die Schwimmlinie für den bestimmten Benutzer. | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Profil | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Um die Planeraufgabe zu erhalten und neue Aufgaben hinzuzufügen, aktualisieren Sie den Bucket und die Schwimmlinie für den jeweiligen Benutzer | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mithilfe anderer Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 können zusätzliche Microsoft-APIs als Microsoft Graph verwenden, um identifizierbare Informationen (OII) der Organisation zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft Graph diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - EWS. AccessAsUser.All | Nein |  |  |  |  |
>| Exchange - Mail.Read.All | Nein |  |  |  |  |
>| SharePoint - AllSites.Manage | Nein |  |  |  |  |
>| SharePoint - AllSites.Read | Nein |  |  |  |  |
>| SharePoint - AllSites.Write | Nein |  |  |  |  |
>| SharePoint - MyFiles.Read | Nein |  |  |  |  |
>| SharePoint - MyFiles.Write | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>iGlobe sammelt Daten, um effektiv zu arbeiten und Ihnen die besten Erfahrungen mit unseren Produkten und Dienstleistungen zu bieten. Zur Lizenzierung: Daten, die zum Verwalten ihres&#8217;Ihres Lizenzierungskontos gesammelt werden, z. B. wenn Sie ein kostenloses Add-In bereitstellen, erstellen Sie ein Testabonnement oder erwerben ein Abonnement. Folgende Informationen werden gesammelt. 
- Finanzieller Zweck: Name und Adresse des Unternehmens
- Abonnierte Benutzer: Benutzername und E-Mail

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Alle Daten sind im eigenen Mandanten des Kunden gespeichert. Es werden keine Anwendungsdaten gespeichert. Ein modernes Add-In wird in einem Sandkastenbrowser ausgeführt, &#8220;nicht mehr&#8221;. Es interagiert mit Benutzerdaten mithilfe Microsoft-Dienste. Das Add-In kann nur auf die Daten zugreifen, mit denen der Benutzer arbeitet.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35757' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35757" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von iGlobe dazu bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden geprüft und befolgt, die in der Prüfliste Microsoft Identity Platform aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Sicherheitseinstellungen und alle anderen gängigen Richtlinien wie Blockieren der Legacyauthentifizierung* MFA für Administratoren erforderlich* MFA für #A0 erforderlich* MFA für alle Benutzer erforderlich* |
| Bittet Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordern wird? | Ja |
| Unterstützt Ihre App mehrere Mandanzfähigkeiten? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle umgeleiteten Unified Resource Identifier (URI), die für Ihre App registriert sind? | Ja |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
