---
title: Anwendungsinformationen für Smartsheet von Smartsheet
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Smartsheet, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c97f12b0e1f423318c98419f11e7569c5285830d
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/02/2021
ms.locfileid: "53280937"
---
# <a name="smartsheet"></a>Smartsheet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/f4d81e8e-4500-44c2-8328-9e06cbe037c5" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA104380975" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Smartsheet für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Smartsheet |
| ID | WA104380975 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Smartsheet |
| URL der Partnerwebsite | [https://www.smartsheet.com](https://www.smartsheet.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://help.smartsheet.com/articles/2476201-interact-with-...](https://help.smartsheet.com/articles/2476201-interact-with-smartsheet-items-in-microsoft-teams) |
| URL der Datenschutzrichtlinie | [https://www.smartsheet/legal/privacy](https://www.smartsheet/legal/privacy) |
| URL der Nutzungsbedingungen | [https://Default Benutzervereinbarung: https://www.smartsheet.com/.. .](https://Default User Agreement: https://www.smartsheet.com/legal/user-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Smartsheet bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | Delegiert | Keine. | Ermöglicht unserer App, Apps im Namen des Benutzers zu installieren. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Directory.Read.All | Delegiert | tenantId zum Abrufen von Informationen, die auf der Benutzeroberfläche angezeigt werden sollen. | Ermöglicht uns zu lesen, welche Apps dieser Mandant verwendet, damit wir überprüfen können, ob wir die App für sie installieren müssen. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.Read.All | Delegiert | teamId/groupId für die Nachrichtenübermittlung. | Ermöglicht unserer App, grundlegende Informationen zu einer Gruppe (oder Teams Team) sowie Unterhaltungen zu lesen. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.ReadWrite.All | Delegiert | teamId/groupId für die Nachrichtenübermittlung. | Ermöglicht unserer App, neue Unterhaltungen in Teams zu starten. Diese Berechtigung umfasst auch den oben genannten Bereich "Read.All", aber wir benötigen diesen bereich auch aus technischen Gründen. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| User.Read.All | Delegiert | Userid. | Ermöglicht uns, grundlegende Informationen zu einem Benutzer während des Authentifizierungsprozesses zu lesen. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| offline_access | Delegiert | refreshToken. | Ermöglicht unserer App, Aktualisierungstoken zu empfangen und das Authentifizierungstoken im Namen des Benutzers zu aktualisieren, wenn er die App verwendet. | c68947ae-a07f-44ce-9a13-7b559251731d |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise zusätzliche andere Microsoft-APIs als Microsoft Graph zum Sammeln oder Verarbeiten von organisationsbezogenen Informationen (OII). Listen Sie alle anderen Microsoft-APIs als Microsoft auf, Graph diese App verwendet.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Bot Framework-APIs | Ja | Wir verwenden die Bot Framework-API, um Nachrichten als App für die Teams-App zu übermitteln. Smartsheet speichert UserId-Informationen, um nachzuverfolgen, mit wem der Smartsheet-Bot spricht. |  | Keine |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| SmartSheet speichert Informationen in einem verschlüsselten Ruhezustand innerhalb unserer Produktions-Rechenzentrumsumgebung, die mit Equinix gehostet wird, und in AWS S3, wo wir Kundenanlagen in privaten verschlüsselten Buckets speichern. |  | Wir verwenden die Bot-Framework-API, um Nachrichten als App für die Teams-App zu übermitteln. Smartsheet speichert UserId-Informationen, um nachzuverfolgen, mit wem der Smartsheet-Bot spricht. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Smartsheet verwendet es, um nachzuverfolgen, wer der Bot auch spricht. Während des anfänglichen Authentifizierungsflusses erstellen wir einen Bot-Eintrag für den Benutzer im Smartsheet-Benachrichtigungssystem. | Für Smartsheet für Teams Bot speichern wir Benutzer-E-Mails und UserId aus Teams, um nachzuverfolgen, mit wem der Bot spricht.  Smartsheet speichert Mandanten-Ids, um Gruppen aufzulisten, zu denen der Benutzer im Verzeichnis gehört, und groupIds für die Nachrichtenübermittlung. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Nein

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Smartsheet verschlüsselt alle gespeicherten Benutzerinformationen, und unsere Administratoren müssen 2FA verwenden. Smartsheet fungiert als SaaS-Anbieter ohne Ansicht, und standardmäßig überprüfen wir nicht die Inhalte, die Kunden hochladen oder in die Plattform eingeben möchten.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

