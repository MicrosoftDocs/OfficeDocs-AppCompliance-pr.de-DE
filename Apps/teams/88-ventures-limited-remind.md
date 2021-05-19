---
title: Anwendungsinformationen für Remind by 88 Ventures Limited
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Remind, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8e2124ed68b2e9d750c8bc6a229eca0ccad200b5
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552446"
---
# <a name="remind"></a>Remind

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 28. September 2020</p>

* <a href="https://teams.microsoft.com/l/app/88546d4f-9973-4716-98e4-cd181c04bc2d" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001444" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen von 88 Ventures Limited an Microsoft:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Remind |
| ID | WA200001444 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | 88 Ventures Limited |
| URL der Partner-Website | [https://www.teamsreminder.app](https://www.teamsreminder.app) |
| URL der Datenschutzrichtlinie | [https://www.teamsreminder.app/#privacy](https://www.teamsreminder.app/#privacy) |
| URL der Nutzungsbedingungen | [https://www.teamsreminder.app/#terms](https://www.teamsreminder.app/#terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von 88 Ventures Limited darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | Delegiert | Keine in der Datenbank gespeicherten Informationen | Ermöglicht Administratoren das Durchsuchen des Benutzerverzeichnisses der Organisation für Benutzer, die öffentliche Erinnerungen festgelegt haben | 88546d4f-9973-4716-98e4-cd181c04bc2d |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| (1) Wenn ein Benutzer eine Erinnerung für eine Nachricht festlegt, versucht der Bot, den Namen der Person zu erhalten, die die Nachricht ursprünglich gesendet hat, um diese Informationen in der Erinnerungsliste des Benutzers anzuzeigen (2) Wenn ein Benutzer eine Erinnerung für einen anderen Kanal oder Chat-Mitglied festlegt, versucht der Bot, die Identität (Benutzer oder Bot) und den Namen des genannten Benutzers zu erhalten, um sie in der Erinnerungsliste des Benutzers anzuzeigen. | (1) Wenn ein Benutzer eine Erinnerung für eine Nachricht festlegt, versucht der Bot, den Namen der Person zu erhalten, die die Nachricht ursprünglich gesendet hat, um diese Informationen in der Erinnerungsliste des Benutzers anzuzeigen (2) Wenn ein Benutzer eine Erinnerung für einen anderen Kanal oder Chat-Mitglied festlegt, versucht der Bot, die Identität (Benutzer oder Bot) und den Namen des genannten Benutzers zu erhalten, um sie in der Erinnerungsliste des Benutzers anzuzeigen. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Kein EEUI und OII wird mit Telemetrie- oder Protokollierungsfunktionen geteilt

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Verschlüsselung im Ruhezustand, Zwei-Faktor-Authentifizierung (2FA) zur Einschränkung des Zugriffs auf unsere IT-Infrastruktur und auf Kundendaten, geschützte IP-Bereiche zwischen Systemen

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

