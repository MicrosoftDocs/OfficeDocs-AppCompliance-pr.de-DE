---
title: Anwendungsinformationen für atSpoke by Townsend Street Labs, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
description: Alle verfügbaren Sicherheits- und Complianceinformationen für atSpoke, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: b3c5c511fb7f74c9e2e7217ae10508b4ce560842
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/30/2021
ms.locfileid: "52093579"
---
# <a name="atspoke"></a>atSpoke

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 3. Juni 2020</p>

* <a href="https://teams.microsoft.com/l/app/dfaf15dc-4e94-4484-a25d-79358fe70d8b" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001454" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Der Stadt,Street Labs, Inc. an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | atSpoke |
| ID | WA200001454 |
| Funktionen | Bot |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Townsend Street Labs, Inc. |
| URL der Partnerwebsite | [https://www.atspoke.com](https://www.atspoke.com) |
| URL der Datenschutzrichtlinie | [https://www.atspoke.com/privacy-policy/](https://www.atspoke.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://www.atspoke.com/terms-of-service](https://www.atspoke.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Den Stadtentwicklungslabors, Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | delegierte | atSpoke speichert die Microsoft-Gruppen-ID | Ermöglicht das Lesen und Schreiben von Gruppeninformationen zwischen atSpoke und Microsoft Teams.  | dfaf15dc-4e94-4484-a25d-79358fe70d8b |
>| User.ReadWrite.All | delegierte | atSpoke speichert die Benutzer-E-Mail und die Benutzer-ID | Ermöglicht das Lesen und Schreiben von Benutzerinformationen zwischen atSpoke und Microsoft Teams. | dfaf15dc-4e94-4484-a25d-79358fe70d8b |
>| offline_access | delegierte | atSpoke speichert dafür keine Daten. | Dies wird für die Hintergrundsynchronisierung verwendet. | dfaf15dc-4e94-4484-a25d-79358fe70d8b |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Ja, wir verwenden Dienste von Drittanbietern für die betriebliche Effizienz. Google, Inc.: Auf logischen Volumes gespeicherte Daten, Speichersicherungen im systemeigenen Google Cloud-Netzwerk, Dienst- und API-Protokolle oder Anwendungsprotokolle. Protokollierte Transaktionsereignisse können Benutzerbezeichner, Kontaktinformationen und Kundeninhalte enthalten. MongoDB, Inc.: In cloudbasierten Datenbanksammlungen gespeicherte Daten. – Kundeninhalte, die Von Benutzern eingereichte Anforderungen, Antworten auf von Benutzern hinzugefügte Anforderungen und von Benutzern hinzugefügte Wissensartikel umfassen. - Benutzerbezeichner (Name, E-Mail, Avatar und Telefonnummer, die zum Erstellen eines Spoke-Benutzerkontos verwendet werden). Mailgun Technologies, Inc.: Benutzer-ID und Kontaktinformationen zum Senden von E-Mail-Kommunikation (d. h. Name und E-Mail). Twilio, Inc.: Benutzertelefonnummer und Kundeninhalte: Inhalte, die mithilfe der Dienste von Twilio&#8217;ausgetauscht werden, z. B. Text, Nachrichtentexte, Sprach- und Videomedien, Bilder und Sound. Mixpanel, Inc.: Die übertragenen personenbezogenen Daten umfassen Namen, E-Mails, IP-Adressen und personenbezogene Daten, die in Nachrichteninhalten enthalten sind. Cloudinary, Inc.: Dateibasierte Kundeninhalte, die von Endbenutzern übermittelt werden. Elasticsearch, Inc.: Protokollierte Anwendungstransaktionsereignisse können abgeschnittenen Text aus Kundeninhalten enthalten. Stitch, Inc.: Kontaktinformationen, Nutzungsinformationen, nicht herkömmliche Bezeichner der autorisierten Benutzer des Abonnenten und alle anderen personenbezogenen Daten, die der Teilnehmer oder seine autorisierten Benutzer an die Plattform übermitteln. Mode Analytics, Inc.: Benutzerbezeichnerinformationen zur Bereitstellung von Analysen pro Benutzer. DataDog: Protokollierte Anwendungstransaktionsereignisse können abgeschnittenen Text aus Kundeninhalten enthalten. Protokollaufbewahrung beträgt 14 Tage. Fullstory, Inc.: Aufzeichnungen von Aktionen auf unserer Webbenutzeroberfläche; enthält das Benutzerkonto von Spoke zu Identifikationszwecken. |  | Wir verwenden die Bot Framework REST-API. Wir verwenden diese API, um Nachrichten an den askSpoke-Botdienst zu senden und zu empfangen. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Es ermöglicht atSpoke, Benutzer aus Microsoft Teams benutzer zu erstellen und Berechtigungen zu definieren. | atSpoke speichert nur die E-Mail, damit Microsoft Teams Benutzer sich bei atSpoke als gültiger Benutzer anmelden können. |  |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In unseren Anwendungsprotokollen sind der Vor- und Nachname eines Benutzers, die E-Mail-Adresse des Benutzers und die azure zugewiesene Objekt-ID für Benutzer und Gruppen enthalten. Protokolle werden nur für 14 Tage aufbewahrt, an dem sie automatisch ablaufen. Der Protokollzugriff ist vor Manipulationen geschützt, und nur bestimmte Mitarbeiter haben Zugriff auf das Anzeigen der Protokolle.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die Anwendungsdaten werden in einer verwalteten MongoDB-Instanz gespeichert. Der Zugriff auf den verwalteten Dienst Atlas MongoDB Database wird über einen standardisierten Benutzerzugriffsanforderungsprozess bereitgestellt, der Genehmigungen erfordert. Regelmäßige Benutzerzugriffsüberprüfungen werden mit der Verwaltung durchgeführt. Wir beschränken die Anzahl der Mitarbeiter mit Zugriff auf vertrauliche Kundendaten und erlauben keine direkte Änderung von Daten von Computern.&#8232; Der Remotezugriff auf diese Datenbank erfordert eine mehrstufige Authentifizierung. Die Datenbank und alle Sicherungen werden im Ruhetag mithilfe der AES-256-Bit-Verschlüsselung verschlüsselt.


#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

