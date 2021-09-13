---
title: Anwendungsinformationen für CalendarHero von CalendarHero Inc
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für CalendarHero, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 41a7dd8a2cb7d900ac26b228c4cc2522d76da59c
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/12/2021
ms.locfileid: "59282194"
---
# <a name="calendarhero"></a>CalendarHero

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 17. März 2020</p>

* <a href="https://teams.microsoft.com/l/app/cac7469b-37cc-44f5-bf08-ff6654d35819" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000150" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Von CalendarHero Inc. an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | CalendarHero |
| ID | WA200000150 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | CalendarHero Inc |
| URL der Partnerwebsite | [https://zoom.ai](https://zoom.ai) |
| URL der Seite mit Teams Anwendungsinformationen | [https://faq.zoom.ai/](https://faq.zoom.ai/) |
| URL der Datenschutzrichtlinie | [https://zoom.ai/privacy-policy](https://zoom.ai/privacy-policy) |
| URL der Nutzungsbedingungen | [https://zoom.ai/terms-of-use](https://zoom.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von CalendarHero Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | Beide | Besprechungen werden in unserer mongoDB in Azure zwischengespeichert, Beschreibungen werden jedoch verschlüsselt. | Zugriff auf die Kalenderereignisse des Benutzers. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Contacts.ReadWrite | Beide | Kontaktname und E-Mail-Adresse. | Lesen Sie die Kontakte des Benutzers (damit wir sie zu einer Besprechung einladen können). | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.Read.All | Beide | Gruppenname und -mitglieder. | (Optional) Lesen von Unternehmensbenutzergruppen (für die Planung mit Gruppen). | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.Read | Beide | E-Mail/Name des Kontakts, Häufigkeit/Aktualität von Interaktionen. | (Optional) wird verwendet, um E-Mail-Metadaten zu lesen, unter wem sich die wichtigsten Kontakte des Benutzers befinden (über Machine Learning). | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| MailboxSettings.ReadWrite | Beide | Zeitzone des Benutzers. | Zeitzone des Benutzers. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read.All | Beide | E-Mail-Adresse des Benutzers &amp; (wird als Kontakt gespeichert). | (Optional) Lesen von Unternehmensbenutzern (für die Planung mit Kollegen) | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| offline_access | Anwendung | Nein | Wir müssen unser Back-End jederzeit lesen und schreiben, ohne dass der Benutzer anwesend ist. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Namen/E-Mails von Kollegen importieren, damit unser Besprechungsassistent-Bot Besprechungen mit ihnen planen kann | &amp;Name-E-Mail. Beide werden in unserer Datenbank für die Schnellsuche und für die teilweise Namenssuche gespeichert (z. B. Sich mit Joe P treffen) |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Die E-Mail-Adresse eines Benutzers und/oder Kontakts wird verwendet, um Ereignisse bei LogDNA, unserem Protokollierungsanbieter, zu protokollieren.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Alle Daten werden im MS Azure Cloud Data Center in Quebec City, Kanada, gespeichert. Mehrere Felder werden mit AES256 verschlüsselt. Der Zugriff auf die Datenbank ist nur für Techniker und unsere Back-End-Server über Anmeldeinformationen auf Benutzer-/Dienstebene verfügbar.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

