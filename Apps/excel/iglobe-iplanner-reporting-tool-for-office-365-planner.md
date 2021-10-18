---
title: Application Information for iPlanner reporting tool for Office 365 Planner by iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Complianceinformationen für das iPlanner-Berichterstellungstool für Office 365 Planner, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 354eaa3d38bd05834d7083a52ee6f5b723aaab64
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428167"
---
# <a name="iplanner-reporting-tool-for-office-365-planner"></a>iPlanner-Berichterstellungstool für Office 365 Planner

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380686" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von iGlobe für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | iPlanner-Berichterstellungstool für Office 365 Planner |
| ID | WA104380686 |
| Office 365 unterstützten Clients | Excel 2016 oder höher auf Windows, Excel im Web, Excel 2016 oder höher auf Mac |
| Name des Partnerunternehmens | iGlobe |
| URL der Partnerwebsite | [https://iglobecrm.com/](https://iglobecrm.com/) |
| URL der Datenschutzrichtlinie | [https://instassl.iglobecrm.com/legal-information](https://instassl.iglobecrm.com/legal-information) |
| URL der Nutzungsbedingungen | [https://mipa.iglobe.dk/EULA](https://mipa.iglobe.dk/EULA) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von iGlobe darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | So erstellen Sie einen Kalendereintrag im Kalender des Benutzers&#8217;am Fälligkeitsdatum der Aufgabe. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Directory.AccessAsUser.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Um zu überprüfen, ob der Benutzer seine Zustimmung hat und Zugriff auf die Verwendung der API hat. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Directory.ReadWrite.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Um die Planner-Aufgabe Outlook To Do abzurufen, wurden E-Mails gekennzeichnet und aktualisiert. So erstellen Sie eine neue Planner-Aufgabe. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Files.ReadWrite.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | So greifen Sie auf die Datei als Anlage zu und laden Dateien in eine Aufgabe hoch. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.Read.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | So rufen Sie die Planliste ab und aktualisieren die Aufgabe. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.ReadWrite.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Aktualisieren Sie den Bucket und die Strichlinie, um die Planner-Aufgabe abzurufen und neue Aufgaben hinzuzufügen. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.Read | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | User.Read, um die Planner-Aufgabe Outlook To Do, gekennzeichnete E-Mails abzurufen und sie zu aktualisieren. So erstellen Sie eine neue Planner-Aufgabe | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.ReadWrite | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | So zeigen Sie die E-Mails an und senden E-Mails. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.ReadWrite.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Ruft den Betreff der E-Mail aus der ausgewählten E-Mail ab. Ermöglicht der App, Informationen aus der ausgewählten E-Mail abzurufen, sodass das Beschreibungsfeld in die Aufgabenbeschreibung kopiert und Anlagen aus der E-Mail oder der E-Mail selbst in die Aufgabe gespeichert werden können. Benachrichtigung senden. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Tasks.ReadWrite | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Um die angemeldeten Benutzer Outlook To Do und User.Read zu aktualisieren, rufen Sie die Planner-Aufgabe Outlook To Do, gekennzeichnete E-Mails ab und aktualisieren sie. So erstellen Sie eine neue Planner-Aufgabe. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Anmelden und Benutzerprofil lesen | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>iGlobe sammelt Daten, um effektiv zu arbeiten und Ihnen die besten Erfahrungen mit unseren Produkten und Diensten zu bieten. Für die Lizenzierung: Daten, die gesammelt werden, um Ihre Organisation&#8217;Lizenzierungskonto zu verwalten, z. B. wenn Sie ein kostenloses Add-In bereitstellen, ein Testabonnement erstellen oder ein Abonnement erwerben. Die folgenden Informationen werden gesammelt. 
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

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

