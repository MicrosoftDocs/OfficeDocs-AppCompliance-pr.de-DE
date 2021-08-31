---
title: Anwendungsinformationen für Office2SharePoint für Office von iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 08/12/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Office2SharePoint für Office, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 12b87e9addae70858503bb2d32def94cae657be2
ms.sourcegitcommit: b1e752ea527ba6049cdc4f5d12cbd5b4dbd7f5b3
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/27/2021
ms.locfileid: "58672762"
---
# <a name="office2sharepoint-for-office"></a>Office2SharePoint für Office

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: August 12, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381787" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von iGlobe für Microsoft bereitgestellte Informationen:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | Office2SharePoint für Office |
| ID | WA104381787 |
| unterstützte Office 365-Clients | Excel 2016 oder höher auf Dem Mac, Excel 2016 oder höher auf Windows, Excel im Web, Word 2016 oder höher auf Mac, Word im Web, Word 2016 oder höher auf Windows, PowerPoint 2016 oder höher auf Mac, PowerPoint im Web, PowerPoint 2016 oder höher auf Windows |
| Name des Partnerunternehmens | iGlobe |
| URL der Partnerwebsite | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| URL der Datenschutzrichtlinie | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL der Nutzungsbedingungen | [https://www.iglobecrm.com/content/end-user-license-agreemen...](https://www.iglobecrm.com/content/end-user-license-agreement-office2sharepoint) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von iGlobe darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.AccessAsUser.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Ermöglicht der App den gleichen Zugriff auf Informationen im Verzeichnis wie dem angemeldeten Benutzer. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Directory.Read.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Suchen Sie nach Berechtigungen, und rufen Sie die Websites und Listen ab. Erstellen Sie Ordner, rufen Sie Dateien ab und speichern Sie Dateien. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Directory.ReadWrite.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Suchen Sie nach Berechtigungen, und rufen Sie die Websites und Listen ab. Erstellen Sie Ordner, rufen Sie Dateien ab und speichern Sie Dateien. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Group.Read.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | So rufen Sie die Gruppenwebsites der Benutzer ab. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Group.ReadWrite.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | So greifen Sie auf die ausgewählten E-Mails zu und rufen die Anlagen ab. Von der E-Mail oder von SharePoint oder Gruppenwebsite zu der E-Mail hinzufügen. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Mail.ReadWrite | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | So greifen Sie auf die ausgewählten E-Mails zu und rufen die Anlagen ab. Von der E-Mail oder von SharePoint oder Gruppenwebsite zu der E-Mail hinzufügen. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Sites.Manage.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | Ermöglicht der Anwendung, Dokumentbibliotheken und Listen in allen Websitesammlungen im Namen des angemeldeten Benutzers zu erstellen oder zu löschen. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Sites.Read.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | So rufen Sie die Benutzer SharePoint Website ab. Abrufen von Dateien und Speichern von Anlagen aus der ausgewählten E-Mail. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Sites.ReadWrite.All | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | So rufen Sie SharePoint Liste, Bibliotheken und Dateien ab. So speichern Sie Dateien in SharePoint Listen. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| User.Read | Delegiert | In Anwendungsdatenbanken werden keine Daten gespeichert. | So rufen Sie die Benutzer SharePoint Website, OneDrive und Gruppenwebsites ab. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, können zusätzliche andere Microsoft-APIs als Microsoft Graph verwenden, um organisationsspezifische Informationen (OII) zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft auf, Graph diese App verwendet.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Exchange – EWS. AccessAsUser.All | Nein |  |  |  |  |
>| Exchange – Mail.ReadWrite | Nein |  |  |  |  |
>| Exchange – MailboxSettings.ReadWrite | Nein |  |  |  |  |
>| SharePoint– AllSites.Manage | Nein |  |  |  |  |
>| SharePoint – AllSites.Write | Nein |  |  |  |  |
>| SharePoint – MyFiles.Write | Nein |  |  |  |  |
>| SharePoint – User.Read.All | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>iGlobe sammelt Daten, um effektiv zu arbeiten und Ihnen die besten Erfahrungen mit unseren Produkten und Diensten zu bieten. Für die Lizenzierung: Daten, die zur Verwaltung Ihres Unternehmens&#8217;Lizenzierungskontos gesammelt werden, z. B. wenn Sie ein kostenloses Add-In bereitstellen, ein Testabonnement erstellen oder ein Abonnement erwerben. Die folgenden Informationen werden gesammelt. Zu finanziellen Zwecken: Firmenname und Adresse abonnierte Benutzer: Benutzername und E-Mail


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Alle Anwendungsdaten befinden sich im eigenen Mandanten des Kunden und werden wie alle anderen Dienste in Office 365 vom Mandantenadministrator gesteuert. Im Add-In werden keine Anwendungsdaten gespeichert. Ein modernes Add-In wird in einem Sandkastenbrowser ausgeführt, &#8220;nicht mehr verarbeitet&#8221;. Das Add-In kann nur auf die Daten zugreifen, mit denen der Benutzer arbeitet. Es interagiert mit Benutzerdaten mithilfe von Microsoft-Dienste.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von iGlobe darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Response** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
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
