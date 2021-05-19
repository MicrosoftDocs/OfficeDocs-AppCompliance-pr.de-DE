---
title: Anwendungsinformationen für Office2SharePoint für Office von iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Office2SharePoint für Office, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 1d1fccbab2aab91eacbc5a43ef79462dd536ff6e
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552646"
---
# <a name="office2sharepoint-for-office"></a>Office2SharePoint für Office

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Zuletzt aktualisiert vom Entwickler am: 17. November 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381787" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die iGlobe Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Office2SharePoint für Office |
| ID | WA104381787 |
| Office 365 unterstützten Clients | Excel 2016 oder später auf Mac, Excel 2016 oder später Windows, Excel im Web, Word 2016 oder später auf Mac, Word im Web, Word 2016 oder später Windows, PowerPoint 2016 oder später auf Mac, PowerPoint im Web, PowerPoint 2016 oder später Windows |
| Name des Partnerunternehmens | iGlobe |
| URL der Partner-Website | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| URL der Datenschutzrichtlinie | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL der Nutzungsbedingungen | [https://www.iglobecrm.com/content/end-user-license-agreemen...](https://www.iglobecrm.com/content/end-user-license-agreement-office2sharepoint) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von iGlobe darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.AccessAsUser.All | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | Ermöglicht der App den gleichen Zugriff auf Informationen im Verzeichnis wie dem angemeldeten Benutzer. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.Read.All | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | Suchen Sie nach Berechtigungen, und erhalten Sie die Sites und Listen. Erstellen Sie Ordner, rufen Sie Dateien ab und speichern Sie Dateien. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.ReadWrite.All | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | Suchen Sie nach Berechtigungen, und erhalten Sie die Sites und Listen. Erstellen Sie Ordner, rufen Sie Dateien ab und speichern Sie Dateien. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.Read.All | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | So erhalten Sie die Benutzergruppenwebsites. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.ReadWrite.All | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | So greifen Sie auf die ausgewählten E-Mails zu und erhalten die Anlagen. Aus der E-Mail oder von SharePoint oder Gruppen-Website zur E-Mail hinzufügen. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Mail.ReadWrite | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | So greifen Sie auf die ausgewählten E-Mails zu und erhalten die Anlagen. Aus der E-Mail oder von SharePoint oder Gruppen-Website zur E-Mail hinzufügen. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Manage.All | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | Ermöglicht der Anwendung das Erstellen oder Löschen von Dokumentbibliotheken und -listen in allen Websitesammlungen im Namen des angemeldeten Benutzers. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Read.All | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | Um die Benutzer SharePoint Website abzubekommen. Abrufen von Dateien und Speichern von Anlagen aus der ausgewählten E-Mail. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.ReadWrite.All | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | So erhalten Sie SharePoint Liste, Bibliotheken und Dateien. So speichern Sie Dateien in SharePoint Listen. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| User.Read | Delegiert | Es werden keine Daten in Anwendungsdatenbanken gespeichert. | So erhalten Sie die Benutzer SharePoint Websites, OneDrive und Gruppenwebsites. | 5971c986-9d39-409c-a6f8-1385b1f690ef |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mithilfe anderer Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, können zusätzliche Microsoft-APIs verwenden, die nicht microsoft Graph sind, um unternehmensbezogene identifizierbare Informationen (OII) zu sammeln oder zu verarbeiten. Listen Sie alle Microsoft-APIs auf, die nicht von Microsoft Graph diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Rechtfertigung für das Sammeln von OII?** | **Wird OII gespeichert?** | **Rechtfertigung für die Speicherung von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - EWS. AccessAsUser.Alle | Nein |  |  |  |  |
>| Exchange - Mail.ReadWrite | Nein |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | Nein |  |  |  |  |
>| SharePoint- AllSites.Manage | Nein |  |  |  |  |
>| SharePoint - AllSites.Write | Nein |  |  |  |  |
>| SharePoint - MyFiles.Write | Nein |  |  |  |  |
>| SharePoint - User.Read.All | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>iGlobe sammelt Daten, um effektiv zu arbeiten und Ihnen die besten Erfahrungen mit unseren Produkten und Dienstleistungen zu bieten. Für die Lizenzierung: Daten, die zur Verwaltung Ihrer Organisation&#8217;Lizenzkonto s gesammelt werden, z. B. wenn Sie ein kostenloses Add-In bereitstellen, ein Testabonnement erstellen oder ein Abonnement erwerben. Folgende Informationen werden gesammelt. Zu finanziellen Zwecken: Firmenname und Adresse Abonnierte Benutzer: Benutzername und E-Mail


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Alle Anwendungsdaten befinden sich auf dem eigenen Mandanten des Kunden und werden vom Mandantenadministrator wie alle anderen Dienste in Office 365 kontrolliert. Im Add-In werden keine Anwendungsdaten gespeichert. Ein modernes Add-In läuft in einem Sandkastenbrowser, &#8220;nicht mehr&#8221;. Das Add-In darf nur auf die Daten zugreifen, mit denen der Benutzer arbeitet. Es interagiert mit Benutzerdaten mit Microsoft-Dienste.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von iGlobe darüber bereitgestellt, wie diese App authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Können Sie sich in Microsoft Identifizplattform (Azure AD) integrieren?  | Ja |
| Haben Sie alle in der Checkliste für die Microsoft Identity Platform-Integration beschriebenen bewährten Methoden überprüft und eingehalten?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Conditional Access-Richtlinien? | Ja |
| Auflisten der unterstützten Richtlinientypen | Sicherheitsstandards und alle anderen allgemeinen Richtlinien wie Legacy-Authentifizierung blockieren* MFA für Administratoren erforderlich* MFA für Azure-Verwaltung erforderlich* MFA für alle Benutzer erforderlich* |
| Fordert Ihre App die geringsten Berechtigungsberechtigungen für Ihr Szenario an? | Ja |
| Gibt die statisch registrierten Berechtigungen Ihrer App die Berechtigungen wieder, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Multi-Tenancy? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle für Ihre App registrierten Unified Resource Identifier (URI) umleiten? | Ja |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
