---
title: Anwendungsinformationen für Smartsheet von Smartsheet
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Smartsheet, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ddf77e7e73cc0bef1a21e72d1db328a4845a12f5
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551525"
---
# <a name="smartsheet"></a>Smartsheet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://teams.microsoft.com/l/app/f4d81e8e-4500-44c2-8328-9e06cbe037c5" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104380975" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Smartsheet Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Smartsheet |
| ID | WA104380975 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Smartsheet |
| URL der Partner-Website | [https://help.smartsheet.com/articles/2476201](https://help.smartsheet.com/articles/2476201) |
| URL Teams Anwendungsinfoseite | [https://help.smartsheet.com/articles/2476201-interact-with-...](https://help.smartsheet.com/articles/2476201-interact-with-smartsheet-items-in-microsoft-teams) |
| URL der Datenschutzrichtlinie | [https://www.smartsheet.com/privacy](https://www.smartsheet.com/privacy) |
| URL der Nutzungsbedingungen | [https://www.smartsheet.com/user-agreement](https://www.smartsheet.com/user-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Smartsheet darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | Delegiert | Keine. | Ermöglicht unserer App, Apps im Auftrag des Benutzers zu installieren. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Directory.Read.All | Delegiert | tenantId zum Abrufen von Informationen, die in der Benutzeroberfläche angezeigt werden sollen. | Ermöglicht es uns, zu lesen, welche Apps dieser Mandant verwendet, damit wir überprüfen können, ob wir die App für sie installieren müssen. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.Read.All | Delegiert | teamId/groupId für die Nachrichtenübermittlung. | Ermöglicht unserer App das Lesen grundlegender Informationen über eine Gruppe (oder Teams Team) sowie Unterhaltungen. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.ReadWrite.All | Delegiert | teamId/groupId für die Nachrichtenübermittlung. | Ermöglicht unserer App, neue Unterhaltungen in Teams zu starten. Diese Berechtigung beinhaltet auch den oben genannten Read.All-Bereich, aber wir brauchen diese auch aus technischen Gründen. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| User.Read.All | Delegiert | Userid. | Ermöglicht es uns, grundlegende Informationen über einen Benutzer während des Auth-Prozesses zu lesen. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| offline_access | Delegiert | refreshToken. | Ermöglicht unserer App, Aktualisierungstoken zu empfangen und das Auth-Token im Namen des Benutzers zu aktualisieren, wenn er die App verwendet. | c68947ae-a07f-44ce-9a13-7b559251731d |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mithilfe anderer Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, können zusätzliche Microsoft-APIs verwenden, die nicht microsoft Graph sind, um unternehmensbezogene identifizierbare Informationen (OII) zu sammeln oder zu verarbeiten. Listen Sie alle Microsoft-APIs auf, die nicht von Microsoft Graph diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Rechtfertigung für das Sammeln von OII?** | **Wird OII gespeichert?** | **Rechtfertigung für die Speicherung von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Bot Framework-APIs | Ja | Wir verwenden die Bot Framework-API, um Nachrichten als App für die Teams-App zu übermitteln. Smartsheet speichert userId-Informationen, um nachzuverfolgen, mit wem der Smartsheet-Bot spricht. |  | Keine |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Smartsheet speichert Informationen in einem verschlüsselten Ruhezustand in unserer Produktionsrechenzentrumsumgebung, die mit Equinix gehostet wird, und in AWS S3, wo wir Kundenanlagen in privaten verschlüsselten Buckets speichern. |  | Wir verwenden die Bot-Framework-API, um Nachrichten als App für die Teams-App zu übermitteln. Smartsheet speichert userId-Informationen, um nachzuverfolgen, mit wem der Smartsheet-Bot spricht. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Smartsheet verwendet es, um zu verfolgen, wer der Bot spricht. Während des ersten Auth-Flows erstellen wir einen Bot-Datensatz für den Benutzer im Smartsheet-Benachrichtigungssystem. | Für Smartsheet für Teams-Bot speichern wir Benutzer-E-Mails und UserId von Teams, um zu helfen, nachzuverfolgen, mit wem der Bot spricht.  Smartsheet speichert tenantIds, um Listengruppen aufzulisten, zu denen der Benutzer im Verzeichnis gehört, und groupIds für die Nachrichtenübermittlung. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Nein

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Smartsheet verschlüsselt alle gespeicherten Benutzerinformationen und unsere Administratoren müssen 2FA verwenden. Smartsheet fungiert als SaaS-Anbieter ohne Sicht und überprüfen standardmäßig nicht die Inhalte, die Kunden hochladen oder in die Plattform eingeben.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

