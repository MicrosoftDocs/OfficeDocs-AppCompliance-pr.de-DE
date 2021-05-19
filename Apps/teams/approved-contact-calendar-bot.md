---
title: Anwendungsinformationen für Kalender BOT durch genehmigten Kontakt
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Kalender BOT, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 7e34564a01f326390ce807373e33818bef877c3e
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553416"
---
# <a name="calendar-bot"></a>Calendar Bot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://teams.microsoft.com/l/app/f02fddc9-159a-4d58-9800-d94c4f64bfe8" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381271" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Genehmigter Kontakt an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Calendar Bot |
| ID | WA104381271 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Approved Contact |
| URL der Partner-Website | [https://approvedcontact.com](https://approvedcontact.com) |
| URL der Datenschutzrichtlinie | [https://approvedcontact.com/Privacy%20Policy%20Bot.pdf](https://approvedcontact.com/Privacy%20Policy%20Bot.pdf) |
| URL der Nutzungsbedingungen | [https://approvedcontact.com/Terms%20of%20use.pdf](https://approvedcontact.com/Terms%20of%20use.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Genehmigter Kontakt darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Delegiert | Für den Kalender BOT speichern wir Benutzer Frei/Gebucht-Zeit für die Suche nach freien Zeiten für mehrere Personen.  | Wir lesen und vergleichen Frei/Gebucht-Zeit und planen Besprechungen. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| Contacts.Read | Delegiert | Ja, wir speichern Kontaktinformationen. | Importieren und Synchronisieren von Kontakten. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.Read | Delegiert | Ja | Grundlegende Profilinformationen. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.ReadBasic.All | Delegiert | Nein | Wird zum Anzeigen von Mitarbeiterprofilen, zum Vergleichen freier Zeiten und zum Planen von Konferenzräumen verwendet. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| offline_access | Delegiert | Ja, Frei/Gebucht-Zeiten für Offline-Benutzer. | Rufen Sie Graph an, wenn der Benutzer unsere Website nicht aktiv nutzt. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| openid | Delegiert | Nein | Office 365 Sso. | adef9811-448f-4dd5-88d9-68734050fe58 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Wir verwenden den Dienstplan, um Frei/Gebucht-Zeiten für alle im Team zu vergleichen, um Besprechungen zu einem offenen Zeitpunkt zu planen. | Wir speichern einfach die E-Mail-Adresse, damit wir Frei/Gebucht-Zeiten vergleichen können. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Ja, wir protokollieren E-Mail-Adressen für die Verbindung von Lizenzkäufen mit Commercial Appsource. Wir bieten Ihnen die Möglichkeit, diese Informationen aus unseren Protokollen zu löschen.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Nur Entwickler haben Zugriff auf unsere Protokolle. Wir erzwingen 2FA für den Zugriff auf alle Entwicklungsplattformen.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

