---
title: Anwendungsinformationen für iPlanner-Berichtstool für Office 365 Planner von iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Alle verfügbaren Sicherheits- und Complianceinformationen für das iPlanner-Berichterstellungstool für Office 365 Planner, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d6416261759acca5b77c6307c2267d11dd8eea4f
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/30/2021
ms.locfileid: "52093417"
---
# <a name="iplanner-reporting-tool-for-office-365-planner"></a>iPlanner-Berichtstool für Office 365 Planner

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380686" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von iGlobe an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | iPlanner-Berichtstool für Office 365 Planner |
| ID | WA104380686 |
| Office 365 unterstützten Clients | Excel 2016 oder höher auf Windows, Excel im Web, Excel 2016 oder höher auf dem Mac |
| Partnerunternehmensname | iGlobe |
| URL der Partnerwebsite | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| URL der Datenschutzrichtlinie | [https://iglobecrm.com/content/legal-information](https://iglobecrm.com/content/legal-information) |
| URL der Nutzungsbedingungen | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474836912/Product_42949680354/Asset_9d620695-979f-49e4-bc56-98259b0cdeb2/EULAPlanner.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von iGlobe darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Um einen Kalendereintrag im Benutzer zu erstellen,&#8217;kalender auf das Vorgangsfälligkeitsdatum. |  |
>| Directory.AccessAsUser.All | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | So überprüfen Sie, ob der Benutzer seine Zustimmung hat und Zugriff auf die Verwendung der API hat. |  |
>| Directory.ReadWrite.All | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Um die Planeraufgabe Outlook To Do, E-Mails gekennzeichnet und aktualisieren. So erstellen Sie eine neue Planner-Aufgabe. |  |
>| Files.ReadWrite.All | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | So greifen Sie auf Datei als Anlage zu und laden Sie Dateien in eine Aufgabe hoch. |  |
>| Group.Read.All | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | So erhalten Sie die Planliste und aktualisieren den Vorgang. |  |
>| Group.ReadWrite.All | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Um die Planeraufgabe zu erhalten und neue Aufgaben hinzuzufügen, aktualisieren Sie den Bucket und die Schwimmlinie. |  |
>| Mail.Read | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | User.Read, um die Planeraufgabe Outlook To Do, E-Mails gekennzeichnet und aktualisiert zu erhalten. So erstellen Sie eine neue Planner-Aufgabe |  |
>| Mail.ReadWrite | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | So zeigen Sie die E-Mails an und senden E-Mails. |  |
>| Mail.ReadWrite.All | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Den E-Mail-Betreff aus der ausgewählten E-Mail-Nachricht erhalten. Ermöglicht der App, Informationen aus der ausgewählten E-Mail zu erhalten, sodass das Beschreibungsfeld in die Aufgabenbeschreibung kopiert und Anlagen aus der E-Mail oder der E-Mail selbst in der Aufgabe gespeichert werden können. Benachrichtigung senden. |  |
>| Tasks.ReadWrite | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Um die angemeldeten Benutzer Outlook To Do benutzer.read zu aktualisieren, um die Planeraufgabe Outlook To Do zu erhalten, E-Mails zu gekennzeichnet und zu aktualisieren. So erstellen Sie eine neue Planner-Aufgabe. |  |
>| User.Read | delegierte | In Anwendungsdatenbanken werden keine Daten gespeichert. | Anmelden und Benutzerprofil lesen |  |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="add-in-data-access"></a>Add-In-Datenzugriff

Listet die Berechtigungen auf, die diese App für den Zugriff auf die Daten Ihrer Organisation benötigt, die Begründung und den Zweck dieser Berechtigung (wofür verwendet die App diese Informationen?), und ob die App diese Informationen in ihren Datenbanken speichert.

>| **Berechtigung**  | **Beschreibung** |
>|:----------------|:----------------|
>| ReadWrite Document | Kann Ihr Dokument lesen und änderungen vornehmen |
>| Senden von Daten | Kann Daten über das Internet senden |

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

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

