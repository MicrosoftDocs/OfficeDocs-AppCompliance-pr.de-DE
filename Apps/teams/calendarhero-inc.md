---
title: Anwendungsinformationen für CalendarHero von CalendarHero Inc
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für CalendarHero, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d27858000c591c320cfadc301ea16ddf2fac89bd
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553317"
---
# <a name="calendarhero"></a>CalendarHero

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 17. März 2020</p>

* <a href="https://teams.microsoft.com/l/app/cac7469b-37cc-44f5-bf08-ff6654d35819" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000150" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von CalendarHero Inc. bereitgestellte Informationen für Microsoft:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | CalendarHero |
| ID | WA200000150 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | CalendarHero Inc |
| URL der Partnerwebsite | [https://calendarhero.com](https://calendarhero.com) |
| URL Teams Anwendungsinfoseite | [https://faq.zoom.ai/](https://faq.zoom.ai/) |
| URL der Datenschutzrichtlinie | [https://calendarhero.com/privacy](https://calendarhero.com/privacy) |
| URL der Nutzungsbedingungen | [https://calendarhero.com/terms-of-use](https://calendarhero.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von CalendarHero Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | both | Besprechungen werden in unserer mongoDB in Azure zwischengespeichert, Beschreibungen sind jedoch verschlüsselt. | Zugriff auf Kalenderereignisse des Benutzers. |  |
>| Contacts.ReadWrite | both | Kontaktname und E-Mail-Adresse. | Lesen Sie die Kontakte des Benutzers (damit wir sie zu einer Besprechung einladen können). |  |
>| Group.Read.All | both | Gruppenname und -mitglieder. | (Optional) Lesen von Unternehmensbenutzergruppen (für die Planung mit Gruppen). |  |
>| Mail.Read | both | Kontakt-E-Mail/Name, Häufigkeit/Recency von Interaktionen. | (Optional) wird verwendet, um E-Mail-Metadaten zu lesen, unter denen sich die wichtigsten Kontakte des Benutzers befinden (über Machine Learning). |  |
>| MailboxSettings.ReadWrite | both | Zeitzone des Benutzers. | Zeitzone des Benutzers. |  |
>| User.Read.All | both | E-Mail-Adresse des &amp; Benutzers (gespeichert als Kontakt). | (Optional) Lesen von Unternehmensbenutzern (für die Planung mit Kollegen) |  |
>| offline_access | Anwendung | Nein | Wir müssen unser Back-End jederzeit lesen und schreiben, ohne dass der Benutzer anwesend ist. |  |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Importieren von Namen/E-Mails von Kollegen, damit unser Besprechungs-Assistent-Bot Besprechungen mit ihnen planen kann | &amp;E-Mail-Namen. beide werden in unserer Datenbank für die schnelle Suche und für die teilweise Namens suchen (z. B. gespeichert. treffen mit Joe P) |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Die E-Mail-Adresse eines Benutzers und/oder Kontakts wird verwendet, um Ereignisse bei LogDNA, unserem Protokollierungsanbieter, zu protokollieren.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Alle Daten werden im Ms Azure Cloud Data Center in Quebec City, Kanada, gespeichert. Mehrere Felder werden mit AES256 verschlüsselt. Der Zugriff auf die Datenbank ist nur für Techniker und unsere Back-End-Server über Anmeldeinformationen auf Benutzer-/Dienstebene verfügbar.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

