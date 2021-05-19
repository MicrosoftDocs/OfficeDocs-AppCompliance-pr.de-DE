---
title: Anwendungsinformationen für atSpoke by Townsend Street Labs, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für atSpoke, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9a159ce3ac976eb1916cd94b3eb1cf002f8e13c1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551195"
---
# <a name="atspoke"></a>atSpoke

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 3. Juni 2020</p>

* <a href="https://teams.microsoft.com/l/app/dfaf15dc-4e94-4484-a25d-79358fe70d8b" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001454" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Townsend Street Labs, Inc. an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | atSpoke |
| ID | WA200001454 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Townsend Street Labs, Inc. |
| URL der Partner-Website | [https://www.atspoke.com](https://www.atspoke.com) |
| URL der Datenschutzrichtlinie | [https://www.atspoke.com/privacy-policy/](https://www.atspoke.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://www.atspoke.com/terms-of-service](https://www.atspoke.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Townsend Street Labs, Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | Delegiert | atSpoke speichert die Microsoft-Gruppen-ID | Ermöglicht das Lesen und Schreiben von Gruppeninformationen zwischen atSpoke und Microsoft Teams.  | dfaf15dc-4e94-4484-a25d-79358fe70d8b |
>| User.ReadWrite.All | Delegiert | atSpoke speichert die Benutzer-E-Mail und die Benutzer-ID | Ermöglicht das Lesen und Schreiben von Benutzerinformationen zwischen atSpoke und Microsoft Teams. | dfaf15dc-4e94-4484-a25d-79358fe70d8b |
>| offline_access | Delegiert | atSpoke speichert dafür keine Daten. | Dies wird für die Hintergrundsynchronisierung verwendet. | dfaf15dc-4e94-4484-a25d-79358fe70d8b |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Ja, wir nutzen Dienste von Drittanbietern für die betriebliche Effizienz. Google, Inc.: Daten, die auf logischen Volumes gespeichert werden, Speichersicherungen in nativen Google Cloud-Netzwerken, Dienst- und API-Protokolle oder Anwendungsprotokolle. Protokollierte Transaktionsereignisse können Benutzerkennungen, Kontaktinformationen und Kundeninhalte enthalten. MongoDB, Inc.: Daten, die in Cloud-basierten Datenbanksammlungen gespeichert sind. - Kundeninhalte, die Anfragen von Benutzern, Antworten auf von Benutzern hinzugefügte Anfragen und wissensbasierte Artikel von Benutzern umfassen. - Benutzerkennungen (Name, E-Mail, Avatar und Telefonnummer verwendet, um ein Spoke-Benutzerkonto zu erstellen). Mailgun Technologies, Inc.: Benutzerkennung und Kontaktinformationen zum Senden von E-Mail-Kommunikation (z. B. Name und E-Mail). Twilio, Inc.: Telefonnummer des Nutzers und Kundeninhalte: Inhalte, die durch die Nutzung von Twilio&#8217;s Services ausgetauscht werden, wie Text, Nachrichtentexte, Sprach- und Videomedien, Bilder und Ton. Mixpanel, Inc.: Die übermittelten personenbezogenen Daten umfassen Name, E-Mail, IP-Adresse und personenbezogene Daten, die im Nachrichteninhalt enthalten sind. Cloudinary, Inc.: Dateibasierte Kundeninhalte, die von Endbenutzern übermittelt werden. Elasticsearch, Inc.: Protokollierte Anwendungstransaktionsereignisse können abgeschnittenen Text aus Kundeninhalten enthalten. Stitch, Inc.: Kontaktinformationen, Nutzungsinformationen, nicht-traditionelle Kennungen der autorisierten Benutzer des Abonnenten und alle anderen personenbezogenen Daten, die der Abonnent oder seine autorisierten Benutzer an die Plattform übermitteln. Mode Analytics, Inc.: Benutzerkennungsinformationen, um Analysen pro Benutzer bereitzustellen. DataDog: Protokollierte Anwendungstransaktionsereignisse können abgeschnittenen Text aus Kundeninhalten enthalten. Protokollaufbewahrung beträgt 14 Tage. Fullstory, Inc.: Aufzeichnungen von Aktionen, die auf unserer Web-Benutzeroberfläche durchgeführt wurden; das Benutzerkonto von Spoke zu Identifikationszwecken. |  | Wir verwenden die Bot Framework REST-API. Wir verwenden diese API, um Nachrichten an den askSpoke-Bot-Dienst zu senden und zu empfangen. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Es ermöglicht atSpoke, Benutzer aus Microsoft Teams zu synchronisieren, um Benutzer zu erstellen und Berechtigungen zu definieren. | atSpoke speichert die E-Mail nur, damit Microsoft Teams Benutzer sich bei atSpoke als gültiger Benutzer anmelden können. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>In unseren Anwendungsprotokollen enthalten ist der Vor- und Nachname eines Benutzers, die E-Mail-Adresse des Benutzers und die Azure-Objekt-ID für Benutzer und Gruppen. Protokolle werden nur 14 Tage lang aufbewahrt, zu diesem Zeitpunkt ablaufen sie automatisch. Der Protokollzugriff ist vor Manipulationen geschützt, und nur bestimmte Mitarbeiter haben Zugriff auf die Protokolle.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Die Anwendungsdaten werden in einer verwalteten MongoDB-Instanz gespeichert. Der Zugriff auf den verwalteten Dienst Atlas MongoDB Database wird über einen standardisierten Benutzerzugriffsanforderungsprozess bereitgestellt, der Genehmigungen erfordert. Regelmäßige Benutzerzugriffsüberprüfungen werden mit Verwaltungssignoff durchgeführt. Wir beschränken die Anzahl der Mitarbeiter mit Zugriff auf sensible Kundendaten und erlauben keine direkten Änderung von Daten von Rechnern. &#8232; Der Remotezugriff auf diese Datenbank erfordert eine mehrstufige Authentifizierung. Die Datenbank und alle Sicherungen werden im Ruhezustand mit AES-256-Bit-Verschlüsselung verschlüsselt.


#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

