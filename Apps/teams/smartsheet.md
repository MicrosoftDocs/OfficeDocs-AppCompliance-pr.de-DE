---
title: Anwendungsinformationen für Smartsheet by Smartsheet
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Smartsheet, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 063dd29aea9265d89eb3ba735a376c7b1f0b64e3
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251124"
---
# <a name="smartsheet"></a>Smartsheet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://teams.microsoft.com/l/app/f4d81e8e-4500-44c2-8328-9e06cbe037c5" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104380975" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Smartsheet für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Smartsheet |
| ID | WA104380975 |
| Funktionen | Bot, Registerkarte |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Smartsheet |
| URL der Partnerwebsite | [https://help.smartsheet.com/articles/2476201](https://help.smartsheet.com/articles/2476201) |
| URL Teams Anwendungsinfoseite | [https://help.smartsheet.com/articles/2476201-interact-with-...](https://help.smartsheet.com/articles/2476201-interact-with-smartsheet-items-in-microsoft-teams) |
| URL der Datenschutzrichtlinie | [https://www.smartsheet.com/privacy](https://www.smartsheet.com/privacy) |
| URL der Nutzungsbedingungen | [https://www.smartsheet.com/user-agreement](https://www.smartsheet.com/user-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Smartsheet bereitgestellt, um zu erfahren, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | delegierte | Keine. | Ermöglicht unserer App, Apps im Auftrag des Benutzers zu installieren. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Directory.Read.All | delegierte | tenantId zum Abrufen von Informationen, die auf der Benutzeroberfläche angezeigt werden. | Ermöglicht es uns, zu lesen, welche Apps dieser Mandant verwendet, damit wir überprüfen können, ob wir die App für sie installieren müssen. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.Read.All | delegierte | teamId/groupId für die Nachrichtenzustellung. | Ermöglicht unserer App, grundlegende Informationen zu einer Gruppe (oder einem Teams) sowie Unterhaltungen zu lesen. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.ReadWrite.All | delegierte | teamId/groupId für die Nachrichtenzustellung. | Ermöglicht unserer App, neue Unterhaltungen in Teams zu starten. Diese Berechtigung umfasst auch den obigen Read.All-Bereich, aber wir benötigen diese auch aus technischen Gründen. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| User.Read.All | delegierte | userId. | Ermöglicht es uns, während des Authentifizierungsprozesses grundlegende Informationen zu einem Benutzer zu lesen. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| offline_access | delegierte | refreshToken. | Ermöglicht unserer App, Aktualisierungstoken zu empfangen und das Authentifizierungstoken im Namen des Benutzers zu aktualisieren, wenn sie die App verwenden. | c68947ae-a07f-44ce-9a13-7b559251731d |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mithilfe anderer Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 können zusätzliche Microsoft-APIs als Microsoft Graph verwenden, um identifizierbare Informationen (OII) der Organisation zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft Graph diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Bot-Framework-APIs | Ja | Wir verwenden die Bot Framework-API, um Nachrichten als App für die Teams-App zu senden. Smartsheet speichert userId-Informationen, um zu verfolgen, mit wem der Smartsheet-Bot spricht. |  | Keine |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Smartsheet speichert Informationen in einem verschlüsselten Ruhezustand in unserer produktionsdatencenterumgebung, die mit Equinix gehostet wird, und in AWS S3, in der wir Kundenanlagen in privaten verschlüsselten Buckets speichern. |  | Wir verwenden die Bot-Framework-API, um Nachrichten als App für die Teams-App zu senden. Smartsheet speichert userId-Informationen, um zu verfolgen, mit wem der Smartsheet-Bot spricht. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Smartsheet verwendet es, um zu verfolgen, wen der Bot auch redet. Während des anfänglichen Authentifizierungsflusses erstellen wir einen Botdatensatz für den Benutzer im Smartsheet-Benachrichtigungssystem. | Für Smartsheet für Teams-Bot speichern wir E-Mails und userId von Teams, um zu verfolgen, mit wem der Bot spricht.  In Smartsheet werden tenantIds gespeichert, um Gruppen auflisten zu können, in die der Benutzer teil des Verzeichnisses ist, und groupIds für die Nachrichtenzustellung. |  |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Nein

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Smartsheet verschlüsselt alle gespeicherten Benutzerinformationen, und unsere Administratoren müssen 2FA verwenden. Smartsheet agiert als Kein-Ansicht-SaaS-Anbieter, und standardmäßig überprüfen wir nicht die Inhalte, die Kunden zum Hochladen oder Eingeben in die Plattform wählen.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

