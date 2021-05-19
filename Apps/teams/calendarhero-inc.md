---
title: Anwendungsinformationen für CalendarHero von CalendarHero Inc
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für CalendarHero, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
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

* <a href="https://teams.microsoft.com/l/app/cac7469b-37cc-44f5-bf08-ff6654d35819" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000150" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die CalendarHero Inc. Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | CalendarHero |
| ID | WA200000150 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | CalendarHero Inc |
| URL der Partner-Website | [https://calendarhero.com](https://calendarhero.com) |
| URL Teams Anwendungsinfoseite | [https://faq.zoom.ai/](https://faq.zoom.ai/) |
| URL der Datenschutzrichtlinie | [https://calendarhero.com/privacy](https://calendarhero.com/privacy) |
| URL der Nutzungsbedingungen | [https://calendarhero.com/terms-of-use](https://calendarhero.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von CalendarHero Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Beide | Besprechungen werden in unserer mongoDB in Azure zwischengespeichert, Beschreibungen werden jedoch verschlüsselt. | Zugriff auf Kalenderereignisse des Benutzers. |  |
>| Contacts.ReadWrite | Beide | Name und E-Mail-Adresse der Kontakte. | Lesen Sie die Kontakte des Benutzers (damit wir sie zu einer Besprechung einladen können). |  |
>| Group.Read.All | Beide | Gruppenname und Mitglieder. | (Optional) lesen Sie Unternehmensbenutzergruppen (für die Planung mit Gruppen). |  |
>| Mail.Read | Beide | Kontakt E-Mail/Name, Häufigkeit/Korrektur von Interaktionen. | (Optional) wird verwendet, um E-Mail-Metadaten zu lesen, unter wem die wichtigsten Kontakte des Benutzers sind (über Machine Learning). |  |
>| MailboxSettings.ReadWrite | Beide | Zeitzone des Benutzers. | Zeitzone des Benutzers. |  |
>| User.Read.All | Beide | Name-E-Mail des Benutzers &amp; (als Kontakt gespeichert). | (Optional) Firmenbenutzer lesen (für die Planung mit Kollegen) |  |
>| offline_access | Anwendung | Nein | Wir müssen jederzeit unser Back-End lesen und schreiben, ohne dass der Benutzer anwesend ist. |  |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Importieren Sie Namen/E-Mails von Kollegen, damit unser Meeting-Assistenten-Bot Besprechungen mit ihnen planen kann | &amp;Namens-E-Mail. beide werden in unserer Datenbank für die schnelle Suche und für die teilweise Namenssuche (z.B. Treffen mit Joe P) |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Die E-Mail-Adresse eines Benutzers und/oder Kontakts wird verwendet, um Ereignisse bei LogDNA, unserem Protokollierungsanbieter, zu protokollieren.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Alle Daten werden im MS Azure Cloud-Rechenzentrum in Quebec City, Kanada, gespeichert. Mehrere Felder sind mit AES256 verschlüsselt. Der Zugriff auf die Datenbank ist nur für Ingenieure und unsere Back-End-Server über Benutzer-/Dienst-Level-Anmeldeinformationen verfügbar.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

