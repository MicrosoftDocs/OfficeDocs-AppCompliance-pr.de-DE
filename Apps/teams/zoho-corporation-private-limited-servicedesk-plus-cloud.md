---
title: Anwendungsinformationen für ServiceDesk Plus Cloud von Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Alle verfügbaren Sicherheits- und Complianceinformationen für ServiceDesk Plus Cloud, die Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3a0123395ff8f6991648c25e6d6e7e10a8d1f3a7
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096145"
---
# <a name="servicedesk-plus-cloud"></a>ServiceDesk Plus Cloud

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://teams.microsoft.com/l/app/04fdcea1-3511-499c-966d-099d59aef45f" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000037" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Zoho Corporation Private Limited an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | ServiceDesk Plus Cloud |
| ID | WA200000037 |
| Funktionen | Bot, Registerkarte, Messaging-Erweiterung |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Zoho Corporation Private Limited |
| URL der Partnerwebsite | [https://www.manageengine.com/products/service-desk](https://www.manageengine.com/products/service-desk) |
| URL Teams Anwendungsinfoseite | [https://help.sdpondemand.com/servicedeskplus_cloud_for_teams](https://help.sdpondemand.com/servicedeskplus_cloud_for_teams) |
| URL der Datenschutzrichtlinie | [https://www.manageengine.com/privacy.html](https://www.manageengine.com/privacy.html) |
| URL der Nutzungsbedingungen | [https://ondemand.manageengine.com/terms.html](https://ondemand.manageengine.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Zoho Corporation Private Limited bereitgestellt, um zu erfahren, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Anwendung |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | delegierte |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | delegierte |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | delegierte | E-Mail-ID des Benutzers. | Ermöglicht dem Benutzer die Anmeldung und gewährt app Zugriff auf seinen UPN, um die automatische Anmeldung zu aktivieren. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read.All | Anwendung |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | delegierte | E-Mail-ID, Name, Mitarbeiter-ID, Jobtitel, Telefon, Mobil, Website, Abteilung, Locale, Profilfoto des Benutzers. | Ermöglicht das Importieren der grundlegenden Informationen von Benutzern aus Azure Active Directory. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | delegierte | E-Mail-ID des Benutzers. | Zeigen Sie die E-Mail-Adresse des Benutzers an. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | delegierte |  | Behalten Sie den Zugriff auf Daten bei, auf die Sie zugriffen haben. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Profil | delegierte |  | Zeigen Sie das grundlegende Profil des Benutzers an. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Auf EUII wird nicht zugegriffen.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir sammeln EUII/PII nicht in Telemetrie-/Protokollen. Wir verfügen über Skripts, die nach Mustern suchen und Warnungen zur Behebung dieser Warnungen enthalten.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Alle Daten werden bei REST verschlüsselt. Nur autorisierte Personen haben Zugriff auf das System, das ohnehin zugriffsgeschützt ist und für alle Arten von Zugriff vollständig überwacht wird. MFA für den Zugriff vorhanden, autorisierte Konten werden in einem Unternehmensverzeichnis und Host verwaltet


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

