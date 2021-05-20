---
title: Anwendungsinformationen für AVA von AvePoint, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für AVA, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6176bc86a6d382285623d3e3286852afd4a4ff96
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552366"
---
# <a name="ava"></a>AVA

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 23. März 2020</p>

* <a href="https://teams.microsoft.com/l/app/93106045-6f96-41e3-8a9d-694b6bbcac60" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381883" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von AvePoint, Inc. an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | AVA |
| ID | WA104381883 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | AvePoint, Inc. |
| URL der Partnerwebsite | [https://www.avepoint.com](https://www.avepoint.com) |
| URL Teams Anwendungsinfoseite | [https://www.avepoint.com/support/](https://www.avepoint.com/support/) |
| URL der Datenschutzrichtlinie | [https://www.avepoint.com/privacy-policy](https://www.avepoint.com/privacy-policy) |
| URL der Nutzungsbedingungen | [https://www.avepoint.com/company/terms-of-use](https://www.avepoint.com/company/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von AvePoint, Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite.Shared | delegierte | Keine | Durchsuchen der E-Mails des Benutzers und Verschieben der E-Mail in einen angegebenen Ordner | 6f30434d-3cfa-4cf8-9810-6fcf79ae750a |
>| User.Read | delegierte |  Zugriffstoken des Benutzers – wird für die Suche und Wiederherstellung von Benutzerdaten verwendet | Ermöglicht es dem Benutzer, sich zu anmelden und der App das Zugriffstoken zu geben. | 6f30434d-3cfa-4cf8-9810-6fcf79ae750a |
>| User.ReadWrite | delegierte | DisplayName, UserPrincipalName, JobTitle, Organization, Country, MySiteUrl – Aufzeichnen der grundlegenden Informationen des Benutzers, der die App verwendet hat | Grundlegende Profilinformationen des Benutzers erhalten | 6f30434d-3cfa-4cf8-9810-6fcf79ae750a |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mithilfe anderer Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 können zusätzliche Microsoft-APIs als Microsoft Graph verwenden, um identifizierbare Informationen (OII) der Organisation zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft Graph diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint-REST-APIs | Ja | Suchdatei in der Wiederherstellen und Wiederherstellung dieser Dateien auf der persönlichen Website des Benutzers. Erfordert die Berechtigung AllSites.Manage. |  | Keine |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Auf EUII wird nicht zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Ja, die E-Mail- und Mandanten-ID des Benutzers werden in Protokollen angezeigt. Die Protokolle werden an gesicherten Speicherorten gespeichert, und nur autorisierte Mitarbeiter können während der Problembehandlung darauf zugreifen. Die Protokolle werden nach 60 Tagen zu Sicherheitsüberwachungszwecken archiviert und nach einem Jahr gelöscht.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die Daten der Anwendung werden in Azure SQL-Datenbank und Azure Storage. Azure SQL und Azure Storage verschlüsselung sind aktiviert.
Nur autorisierte Administratoren können auf die Daten zugreifen. MFA ist erforderlich, damit sich die Administratoren anmelden können. Die Vorgänge werden überwacht. Ip-Whitelisting wird auch verwendet, um den Zugriff auf die Daten einzuschränken.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35842' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35842" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

