---
title: Anwendungsinformationen für iGlobe CRM-Office 365 für Microsoft 365
ms.author: elmalova
author: elenamalova
ms.date: 06/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für iGlobe CRM-Office 365 für Microsoft 365, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 020e2ce913d50c72c401b4d08bc7810173faaa28
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225015"
---
# <a name="application-information-for-iglobe-crm-office-365-for-microsoft-365"></a>Anwendungsinformationen für iGlobe CRM-Office 365 für Microsoft 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Letzte Aktualisierung durch den Entwickler am: 22. Juni 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/17859280.iglobecrmoffice365" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von iGlobe an Microsoft bereitgestellt werden:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | iGlobe CRM-Office 365 für Microsoft 365 |
| ID | 17859280.iglobecrmoffice365 |
| Name des Partnerunternehmens | iGlobe |
| URL der Partnerwebsite | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| URL der Datenschutzrichtlinie | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL der Nutzungsbedingungen | [https://iglobecrm.com/content/iglobe-crm-office-365-end-use...](https://iglobecrm.com/content/iglobe-crm-office-365-end-user-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von iGlobe darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Auflisten aller [Microsoft Graph Berechtigungen](/graph/permissions-reference), die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegiert/Anwendung)** | **Werden Daten erfasst? Begründung für das Sammeln?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Zugriff auf Benutzerkalender beim Dressen eines Besprechungsberichts vom Canlendar in iGlobe | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Contacts.ReadWrite | Delegiert | Directory.AccessAsUser.All | Ermöglicht der App den gleichen Zugriff auf Informationen im Verzeichnis wie dem angemeldeten Benutzer. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.Read.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Überprüfen Sie die Berechtigung, und rufen Sie die Websites und Listen ab. Erstellen Sie Ordner, rufen Sie Dateien ab, und speichern Sie Dateien. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.ReadWrite.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Ermöglicht der App den gleichen Zugriff auf Informationen im Verzeichnis wie dem angemeldeten Benutzer. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Files.ReadWrite.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Lesen, Aktualisieren, Erstellen von Panneraufgaben, Lesen der zuletzt verwendeten und freigegebenen Dateien der Benutzer, So rufen Sie SharePoint Liste, Bibliotheken und Dateien ab. So speichern Sie Dateien und Daten in SharePoint Listen. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.Read.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Lesen, Aktualisieren, Erstellen von Panneraufgaben, Lesen der zuletzt verwendeten und freigegebenen Dateien der Benutzer, So rufen Sie SharePoint Liste, Bibliotheken und Dateien ab. So speichern Sie Dateien in SharePoint Listen. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.ReadWrite.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Lesen, Aktualisieren, Erstellen von Panneraufgaben, Lesen der zuletzt verwendeten und freigegebenen Dateien der Benutzer, So rufen Sie SharePoint Liste, Bibliotheken und Dateien ab. So speichern Sie Dateien in SharePoint Listen. Integration in iGlobe CRM Office 365 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Mail.ReadWrite | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Svae the eamil to iGlobe CRM and get informatiopn from iGlobe to a new e-amil | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Manage.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Erstellen, Bearbeiten und Löschen von Elementen und Listen in iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Read.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Lesen von Elementen in iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.ReadWrite.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Bearbeiten und Löschen von Elementen und Listen in iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Tasks.ReadWrite | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Erstellen einer Planner-Aufgabe aus iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| User.Read | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | So erhalten Sie Informationen zum iGlobe CRM für den speficischen Benutzer | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise andere Microsoft-APIs als Microsoft Graph, um Organisationsinformationen (OII) zu sammeln oder zu verarbeiten. Auflisten aller anderen Microsoft-APIs als Microsoft Graph, die diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Begründung für das Sammeln von OII?** | **Ist OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - Calendars.ReadWrite.All | Nein |  |  |  |  |
>| Exchange - Mail.Read.All | Nein |  |  |  |  |
>| Exchange – Contacts.Read | Nein |  |  |  |  |
>| Exchange – EWS. AccessAsUser.All | Nein |  |  |  |  |
>| Exchange - Tasks.ReadWrite | Nein |  |  |  |  |
>| SharePoint – AllSites.Manage | Nein |  |  |  |  |
>| SharePoint - AllSites.Read | Nein |  |  |  |  |
>| SharePoint -AllSites.Write | Nein |  |  |  |  |
>| SharePoint - MyFiles.Write | Nein |  |  |  |  |
>| SharePoint – Sites.Manage.All | Nein |  |  |  |  |
>| SharePoint - Sites.Read.All | Nein |  |  |  |  |
>| SharePoint - Sites.ReadWrite.All | Nein |  |  |  |  |
>| SharePoint - Sites.Search.All | Nein |  |  |  |  |
>| SharePoint - TermStore.Read.All | Nein |  |  |  |  |
>| SharePoint - TermStore.ReadWrite.All | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder freigibt, listen Sie den von der App nicht von Microsoft stammenden Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder Endbenutzer-identifizierbare Informationen (EUII) in den Telemetriedaten oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Aufbewahrungs- und Entfernungsrichtlinien gelten?

>iGlobe sammelt Daten, um effektiv zu arbeiten und Ihnen die besten Erfahrungen mit unseren Produkten und Dienstleistungen zu bieten. Für die Lizenzierung: Daten, die gesammelt werden, um Ihre Organisation&#8217;Lizenzierungskonto zu verwalten, z. B. wenn Sie ein kostenloses Add-In bereitstellen, ein Testabonnement erstellen oder ein Abonnement erwerben. Folgende Informationen werden gesammelt. 
- Zu finanziellen Zwecken: Firmenname und -adresse
- Abonnierte Benutzer: Benutzername und E-Mail

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren der Organisation ihre Informationen in Partnersystemen steuern können? z.B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Alle Daten befinden sich im eigenen Mandanten des Kunden. Es werden keine Anwendungsdaten gespeichert. Ein modernes Add-In wird in einem Sandkastenbrowser ausgeführt, &#8220;außerhalb des Prozesses&#8221;. Es interagiert mit Benutzerdaten mithilfe von Microsoft-Dienste. Das Add-In kann nur auf die Daten zugreifen, mit denen der Benutzer arbeitet.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational Identifiable Information) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163" target="_blank">Auf einer neuen Registerkarte anzeigen</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von iGlobe darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Response** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden überprüft und eingehalten, die in der Checkliste für die Microsoft Identity Platform Integration aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Sicherheitsstandards und andere allgemeine Richtlinien wie "Legacyauthentifizierung blockieren" * MFA für Administratoren anfordern* MFA für Azure-Verwaltung anfordern* MFA für alle Benutzer anfordern* |
| Fordert Ihre App Berechtigungen mit den geringsten Berechtigungen für Ihr Szenario an? | Ja |
| Entsprechen die statisch registrierten Berechtigungen Ihrer App genau den Berechtigungen, die ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrinstanzenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie den gesamten umleitenden Unified Resource Identifier (URI), der für Ihre App registriert ist? | Ja |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
