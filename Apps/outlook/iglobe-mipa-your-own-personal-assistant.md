---
title: Anwendungsinformationen für MIPA – Ihr eigener persönlicher Assistent von iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/05/2020
ms.topic: article
ms.service: attestation
description: Alle verfügbaren Sicherheits- und Complianceinformationen für MIPA – Ihr eigener persönlicher Assistent, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 2b7a539c7e99c435d4df940e376f84dc89146e65
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095934"
---
# <a name="mipa---your-own-personal-assistant"></a>MIPA – Ihr eigener persönlicher Assistent

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Zuletzt aktualisiert vom Entwickler am: 5. November 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA200000062" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von iGlobe an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | MIPA – Ihr eigener persönlicher Assistent |
| ID | WA200000062 |
| Office 365 unterstützten Clients | Outlook 2013 oder höher auf Windows, Outlook 2016 oder höher auf dem Mac, Outlook im Web |
| Partnerunternehmensname | iGlobe |
| URL der Partnerwebsite | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| URL der Datenschutzrichtlinie | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL der Nutzungsbedingungen | [https://www.iglobecrm.com/content/end-user-license-agreemen...](https://www.iglobecrm.com/content/end-user-license-agreement-iglobe-mipa) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von iGlobe darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Lesen und Aktualisieren von Kalenderdingen | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Contacts.ReadWrite | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Lesen und Aktualisieren von Kalenderdingen | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Directory.AccessAsUser.All | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Lesen, Aktualisieren, Erstellen von Panner-Tasks. So überprüfen Sie, ob der Benutzer seine Zustimmung hat und Zugriff auf die Verwendung der API hat. | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Directory.ReadWrite.All | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Um die Planeraufgabe Outlook To Do, E-Mails gekennzeichnet und aktualisieren. So erstellen Sie eine neue Planner-Aufgabe. | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Files.ReadWrite.All | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Read, Update, Create Panner Tasks, Read the users recent and Shared files, To get SharePoint list, libraries and files. So speichern Sie Dateien in SharePoint Listen. | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Group.Read.All | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Read, Update, Create Panner Tasks, Read the users recent and Shared files, To get SharePoint list, libraries and files. So speichern Sie Dateien in SharePoint Listen. | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Group.ReadWrite.All | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Read, Update, Create Panner Tasks, Read the users recent and Shared files, To get SharePoint list, libraries and files. So speichern Sie Dateien in SharePoint Listen. Integration in iGlobe CRM Office 365 | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Mail.ReadWrite | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Lesen und Aktualisieren gekennzeichneter E-Mails | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| MailboxSettings.ReadWrite | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Vollständige Kalender lesen und aktualisieren, Gekennzeichnete E-Mails lesen und aktualisieren, Outlook To Do lesen und aktualisieren | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Tasks.ReadWrite | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Lesen und Aktualisieren von Kalenderdingen, Lesen und Outlook to Do Entreies | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| User.Read | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Lesen und Aktualisieren von Kalenderdingen, Lesen und Outlook to Do Entreies | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| User.Read.All | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Vollständige Kalender lesen und aktualisieren, Lese- und Outlook Zu erledigende Aufgaben, Lesen, Aktualisieren, Erstellen von Panneraufgaben | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| User.ReadBasic.All | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Vollständige Kalender lesen und aktualisieren, Lese- und Outlook Zu erledigende Aufgaben, Lesen, Aktualisieren, Erstellen von Panneraufgaben | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| User.ReadWrite | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Lesen und Aktualisieren von Kalenderdingen, Lesen und Outlook to Do Entreies | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| email | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Ermöglicht der App, die primäre E-Mail-Adresse Ihrer Benutzer zu lesen ( für SSO). | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| offline_access | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Ermöglicht der App, die Daten, auf die Sie zugriffen, zu sehen und zu aktualisieren, auch wenn Benutzer die App derzeit nicht verwenden. Dadurch wird der App keine zusätzlichen Berechtigungen erteilt ( für SSO). | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| openid | delegierte | In der Anwendungsdatenbank werden keine Daten gespeichert | Ermöglicht Benutzern die Anmeldung bei der App mit ihren Arbeits- oder Schulkonten und ermöglicht es der App, grundlegende Benutzerprofilinformationen (für SSO) zu sehen. | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Profil | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Vollständige Kalender lesen und aktualisieren, Lese- und Outlook Zu erledigende Aufgaben, Lesen, Aktualisieren, Erstellen von Panneraufgaben | e854ea05-68ab-4204-babe-db4a784fb4d16 |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mithilfe anderer Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 können zusätzliche Microsoft-APIs als Microsoft Graph verwenden, um identifizierbare Informationen (OII) der Organisation zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft Graph diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - Calendars.ReadWrite.All | Nein |  |  |  |  |
>| Exchange - EWS. AccessAsUser.All | Nein |  |  |  |  |
>| Exchange - Mail.Read | Nein |  |  |  |  |
>| Exchange - Mail.ReadWrite.All | Nein |  |  |  |  |
>| Exchange - MailboxSettings.Read | Nein |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | Nein |  |  |  |  |
>| Exchange – Tasks.ReadWrite | Nein |  |  |  |  |
>| SharePoint - MyFiles.Read | Nein |  |  |  |  |
>| SharePoint - MyFiles.Write | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="add-in-data-access"></a>Add-In-Datenzugriff

Listet die Berechtigungen auf, die diese App für den Zugriff auf die Daten Ihrer Organisation benötigt, die Begründung und den Zweck dieser Berechtigung (wofür verwendet die App diese Informationen?), und ob die App diese Informationen in ihren Datenbanken speichert.

>| **Berechtigung**  | **Beschreibung** |
>|:----------------|:----------------|
>| ReadWrite-Element | Dieses Add-In kann auf persönliche Informationen in der aktiven Nachricht zugreifen und diese ändern, z. B. text, betreff, absender, empfänger und Anlageninformationen. Diese Daten können an einen Drittanbieterdienst gesendet werden. Andere Elemente in Ihrem Postfach können&#8217;gelesen oder geändert werden. |
>| Senden von Daten | Kann Daten über das Internet senden |

#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>iGlobe sammelt Daten, um effektiv zu arbeiten und Ihnen die besten Erfahrungen mit unseren Produkten und Dienstleistungen zu bieten. Zur Lizenzierung: Daten, die zum Verwalten ihres&#8217;Ihres Lizenzierungskontos gesammelt werden, z. B. wenn Sie ein kostenloses Add-In bereitstellen, erstellen Sie ein Testabonnement oder erwerben ein Abonnement. Folgende Informationen werden gesammelt. - Für finanzielle Zwecke: Firmenname und Adresse- Abonnierte Benutzer: Benutzername und E-Mail

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

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

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
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordern wird? | Nein |
| Unterstützt Ihre App mehrere Mandanzfähigkeiten? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle umgeleiteten Unified Resource Identifier (URI), die für Ihre App registriert sind? | Ja |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
