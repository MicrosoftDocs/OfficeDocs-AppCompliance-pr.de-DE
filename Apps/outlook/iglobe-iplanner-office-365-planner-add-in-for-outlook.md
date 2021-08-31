---
title: Anwendungsinformationen für iPlanner Office 365 Planner-Add-In für Outlook von iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 08/12/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Complianceinformationen für iPlanner Office 365 Planner-Add-In für Outlook, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3503b068b8835037b578837cb7f7f264a91135c6
ms.sourcegitcommit: b1e752ea527ba6049cdc4f5d12cbd5b4dbd7f5b3
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/27/2021
ms.locfileid: "58672462"
---
# <a name="iplanner-office-365-planner-add-in-for-outlook"></a>iPlanner Office 365 Planner-Add-In für Outlook

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: August 12, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380147" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von iGlobe für Microsoft bereitgestellte Informationen:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | iPlanner Office 365 Planner-Add-In für Outlook |
| ID | WA104380147 |
| unterstützte Office 365-Clients | Outlook 2013 oder höher auf Windows, Outlook 2016 oder höher für Mac Outlook im Web |
| Name des Partnerunternehmens | iGlobe |
| URL der Partnerwebsite | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| URL der Datenschutzrichtlinie | [https://iglobecrm.com/content/legal-information](https://iglobecrm.com/content/legal-information) |
| URL der Nutzungsbedingungen | [https://iglobecrm.com/content/end-user-license-agreement-ig...](https://iglobecrm.com/content/end-user-license-agreement-iglobe-iplanner-add-ins) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von iGlobe darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Um die Planner-Aufgabe abzurufen und neue Aufgaben hinzuzufügen, aktualisieren Sie den Bucket und die Strichlinie für den jeweiligen Benutzer | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Contacts.ReadWrite | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | zum Erstellen eines Termins im Kalender der Benutzer zum Fälligkeitsdatum der Aufgaben | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Directory.AccessAsUser.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Ermöglicht der App den gleichen Zugriff auf Informationen im Verzeichnis wie dem angemeldeten Benutzer. | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Files.Read | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | So greifen Sie auf Datei als Anlage zu und laden Dateien in eine Aufgabe hoch | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Files.ReadWrite.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Ruft den Betreff der E-Mail aus der ausgewählten E-Mail ab. Ermöglicht der App, Informationen aus der ausgewählten E-Mail abzurufen, sodass das Beschreibungsfeld in die Aufgabenbeschreibung kopiert und Anlagen aus der E-Mail oder der E-Mail selbst in die Aufgabe gespeichert werden können. | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Group.Read.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. |  um die Planner-Aufgabe abzurufen und neue Aufgaben hinzuzufügen, aktualisieren Sie den Bucket und die Strichlinie für den bestimmten Benutzer | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| User.Read | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Um die Planner-Aufgabe abzurufen und neue Aufgaben hinzuzufügen, aktualisieren Sie den Bucket und die Strichlinie für den jeweiligen Benutzer | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| User.ReadBasic.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. |  Suchen Sie nach Berechtigungen, und um die Planner-Aufgabe abzurufen und neue Aufgaben hinzuzufügen, aktualisieren Sie den Bucket und die Strichlinie für den jeweiligen Benutzer. | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Profil | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Um die Planner-Aufgabe abzurufen und neue Aufgaben hinzuzufügen, aktualisieren Sie den Bucket und die Strichlinie für den jeweiligen Benutzer | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, können zusätzliche andere Microsoft-APIs als Microsoft Graph verwenden, um organisationsspezifische Informationen (OII) zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft auf, Graph diese App verwendet.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Exchange – EWS. AccessAsUser.All | Nein |  |  |  |  |
>| Exchange – Mail.Read.All | Nein |  |  |  |  |
>| SharePoint – AllSites.Manage | Nein |  |  |  |  |
>| SharePoint – AllSites.Read | Nein |  |  |  |  |
>| SharePoint – AllSites.Write | Nein |  |  |  |  |
>| SharePoint – MyFiles.Read | Nein |  |  |  |  |
>| SharePoint – MyFiles.Write | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>iGlobe sammelt Daten, um effektiv zu arbeiten und Ihnen die besten Erfahrungen mit unseren Produkten und Diensten zu bieten. Für die Lizenzierung: Daten, die zur Verwaltung Ihres Unternehmens&#8217;Lizenzierungskontos gesammelt werden, z. B. wenn Sie ein kostenloses Add-In bereitstellen, ein Testabonnement erstellen oder ein Abonnement erwerben. Die folgenden Informationen werden gesammelt. 
- Zu finanziellen Zwecken: Name und Adresse des Unternehmens
- Abonnierte Benutzer: Benutzername und E-Mail

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Alle Daten befinden sich im eigenen Mandanten des Kunden. Es werden keine Anwendungsdaten gespeichert. Ein modernes Add-In wird in einem Sandkastenbrowser ausgeführt, &#8220;nicht mehr verarbeitet&#8221;. Es interagiert mit Benutzerdaten mithilfe von Microsoft-Dienste. Das Add-In kann nur auf die Daten zugreifen, mit denen der Benutzer arbeitet.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35757' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35757" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von iGlobe darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Response** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration aufgeführt sind, überprüft und berücksichtigt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Sicherheitsstandards und andere gängige Richtlinien wie "Legacyauthentifizierung blockieren"* MFA für Administratoren erforderlich* MFA für Azure-Verwaltung erforderlich* MFA für alle Benutzer erforderlich* |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
