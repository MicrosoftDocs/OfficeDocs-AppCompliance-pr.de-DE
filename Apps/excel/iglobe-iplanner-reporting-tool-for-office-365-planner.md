---
title: Anwendungsinformationen für iPlanner-Berichtstool für Office 365 Planner von iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für das iPlanner-Berichtstool für Office 365 Planner, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a577fcc75982703bfae0de740a7e69d9d13e509a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52548765"
---
# <a name="iplanner-reporting-tool-for-office-365-planner"></a>iPlanner-Berichtstool für Office 365 Planner

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380686" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die iGlobe Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | iPlanner-Berichtstool für Office 365 Planner |
| ID | WA104380686 |
| Office 365 unterstützten Clients | Excel 2016 oder später Windows, Excel im Web, Excel 2016 oder später auf Mac |
| Name des Partnerunternehmens | iGlobe |
| URL der Partner-Website | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| URL der Datenschutzrichtlinie | [https://iglobecrm.com/content/legal-information](https://iglobecrm.com/content/legal-information) |
| URL der Nutzungsbedingungen | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474836912/Product_42949680354/Asset_9d620695-979f-49e4-bc56-98259b0cdeb2/EULAPlanner.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von iGlobe darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | So erstellen Sie einen Kalendereintrag im&#8217;Kalender des Vorgangs am Fälligkeitsdatum des Vorgangs. |  |
>| Directory.AccessAsUser.All | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | Um zu überprüfen, dass der Benutzer die Zustimmung hat und Zugriff auf die Verwendung der API hat. |  |
>| Directory.ReadWrite.All | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | Um die Planeraufgabe Outlook To Do zu erhalten, haben Sie E-Mails gekennzeichnet und aktualisiert. So erstellen Sie eine neue Planeraufgabe. |  |
>| Files.ReadWrite.All | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | So greifen Sie auf die Datei als Anlage zu und laden Dateien in eine Aufgabe hoch. |  |
>| Group.Read.All | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | So erhalten Sie die Planliste und aktualisieren die Aufgabe. |  |
>| Group.ReadWrite.All | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | Um die Planeraufgabe zu erhalten und neue Aufgaben hinzuzufügen, aktualisieren Sie den Bucket und die Schwimmlinie. |  |
>| Mail.Read | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | User.Read, um die Planer-Aufgabe Outlook To Do, gekennzeichnete E-Mails und deren Aktualisierung zu erhalten. So erstellen Sie eine neue Planeraufgabe |  |
>| Mail.ReadWrite | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | So zeigen Sie die E-Mails an und senden E-Mails. |  |
>| Mail.ReadWrite.Alle | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | Holen Sie den E-Mail-Betreff aus der ausgewählten E-Mail ab. Ermöglicht der App, Informationen aus der ausgewählten E-Mail abzubekommen, sodass das Beschreibungsfeld in die Aufgabenbeschreibung kopiert und Anlagen aus der E-Mail oder der E-Mail selbst in die Aufgabe gespeichert werden können. Benachrichtigung senden. |  |
>| Tasks.ReadWrite | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | Um die angemeldeten Benutzer Outlook To Do und user.Read zu aktualisieren, um die Planeraufgabe Outlook To Do, gekennzeichnete E-Mails und deren Aktualisierung abzubekommen. So erstellen Sie eine neue Planeraufgabe. |  |
>| User.Read | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | Anmelden und Benutzerprofil lesen |  |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>iGlobe sammelt Daten, um effektiv zu arbeiten und Ihnen die besten Erfahrungen mit unseren Produkten und Dienstleistungen zu bieten. Für die Lizenzierung: Daten, die zur Verwaltung Ihrer Organisation&#8217;Lizenzkonto s gesammelt werden, z. B. wenn Sie ein kostenloses Add-In bereitstellen, ein Testabonnement erstellen oder ein Abonnement erwerben. Folgende Informationen werden gesammelt. 
- Zu finanziellen Zwecken: Firmenname und Anschrift
- Abonnierte Benutzer: Benutzername und E-Mail

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Alle Daten befinden sich auf dem eigenen Mandanten des Kunden. Es werden keine Anwendungsdaten gespeichert. Ein modernes Add-In läuft in einem Sandkastenbrowser, &#8220;nicht mehr&#8221;. Es interagiert mit Benutzerdaten mit Microsoft-Dienste. Das Add-In darf nur auf die Daten zugreifen, mit denen der Benutzer arbeitet.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

