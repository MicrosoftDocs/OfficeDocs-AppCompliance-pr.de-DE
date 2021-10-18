---
title: Anwendungsinformationen für atSpoke von Labs Street Labs, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 04/14/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für atSpoke, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 17fc89d254fd558c318c48de53456e9fa23054f7
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429823"
---
# <a name="atspoke"></a>atSpoke

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/dfaf15dc-4e94-4484-a25d-79358fe70d8b" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001454" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Derend Street Labs, Inc. an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | atSpoke |
| ID | WA200001454 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Townsend Street Labs, Inc. |
| URL der Partnerwebsite | [https://www.atspoke.com/](https://www.atspoke.com/) |
| URL der Datenschutzrichtlinie | [https://www.atspoke.com/privacy-policy/](https://www.atspoke.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://www.atspoke.com/terms-of-service/](https://www.atspoke.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Derend Street Labs, Inc. bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | Delegiert | atSpoke speichert die Microsoft-Gruppen-ID | Ermöglicht das Lesen und Schreiben von Gruppeninformationen zwischen atSpoke und Microsoft Teams.  | [dfaf15dc-4e94-4484-a25d-79358fe70d8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/dfaf15dc-4e94-4484-a25d-79358fe70d8b) |
>| User.ReadWrite.All | Delegiert | atSpoke speichert die Benutzer-E-Mail und Benutzer-ID | Ermöglicht das Lesen und Schreiben von Benutzerinformationen zwischen atSpoke und Microsoft Teams. | [dfaf15dc-4e94-4484-a25d-79358fe70d8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/dfaf15dc-4e94-4484-a25d-79358fe70d8b) |
>| offline_access | Delegiert | atSpoke speichert dafür keine Daten. | Dies wird für die Hintergrundsynchronisierung verwendet. | [dfaf15dc-4e94-4484-a25d-79358fe70d8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/dfaf15dc-4e94-4484-a25d-79358fe70d8b) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Ja, wir verwenden Dienste von Drittanbietern für die betriebliche Effizienz. Google, Inc.: Auf logischen Volumes gespeicherte Daten, Speichersicherungen im nativen Google Cloud-Netzwerk, Dienst- und API-Protokolle oder Anwendungsprotokolle. Protokollierte Transaktionsereignisse können Benutzer-IDs, Kontaktinformationen und Kundeninhalte enthalten. MongoDB, Inc.: Daten, die in cloudbasierten Datenbanksammlungen gespeichert sind. – Kundeninhalte, die Von Benutzern eingereichte Anforderungen, Antworten auf von Benutzern hinzugefügte Anforderungen und von Benutzern hinzugefügte Wissensartikel umfassen. – Benutzer-IDs (Name, E-Mail, Avatar und Telefonnummer, die zum Erstellen eines Spoke-Benutzerkontos verwendet werden). Mailgun Technologies, Inc.: Benutzer-ID und Kontaktinformationen zum Senden von E-Mail-Kommunikationen (z. B. Name und E-Mail). Twilio, Inc.: Telefonnummer des Benutzers und Kundeninhalte: Inhalte, die mithilfe von Twilio&#8217;-Diensten ausgetauscht werden, z. B. Text, Nachrichtentext, Sprach- und Videomedien, Bilder und Sound. Mixpanel, Inc.: Zu den übertragenen personenbezogenen Daten gehören Name, E-Mail, IP-Adresse und personenbezogene Daten, die in Nachrichteninhalten enthalten sind. Cloudinary, Inc.: Dateibasierte Kundeninhalte, die von Endbenutzern übermittelt werden. FlexibleSearch, Inc.: Protokollierte Anwendungstransaktionsereignisse können abgeschnittenen Text aus Kundeninhalten enthalten. Stitch, Inc.: Kontaktinformationen, Nutzungsinformationen, nicht herkömmliche Bezeichner der autorisierten Benutzer des Abonnenten und alle anderen personenbezogenen Daten, die der Abonnent oder seine autorisierten Benutzer an die Plattform übermitteln. Mode Analytics, Inc.: Informationen zu Benutzerbezeichnern, um Analysen pro Benutzer bereitzustellen. Data Dog: Protokollierte Anwendungstransaktionsereignisse können abgeschnittenen Text aus Kundeninhalten enthalten; Die Protokollaufbewahrung beträgt 14 Tage. Fullstory, Inc.: Aufzeichnungen von Aktionen, die auf unserer Web-Benutzeroberfläche ausgeführt wurden; umfasst das Benutzerkonto von Spoke zu Identifikationszwecken. |  | Wir verwenden die Bot Framework-REST-API. Wir verwenden diese API, um Nachrichten an den askSpoke-Botdienst zu senden und zu empfangen. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| AtSpoke kann Benutzer aus Microsoft Teams synchronisieren, um Benutzer zu erstellen und Berechtigungen zu definieren. | atSpoke speichert die E-Mail nur, damit Microsoft Teams Benutzer sich bei atSpoke als gültiger Benutzer anmelden können. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In unseren Anwendungsprotokollen sind der Vor- und Nachname eines Benutzers, die E-Mail-Adresse des Benutzers und die azure zugewiesene Objekt-ID für Benutzer und Gruppen enthalten. Protokolle werden nur 14 Tage lang aufbewahrt, ab dem Sie automatisch ablaufen. Der Protokollzugriff ist vor Manipulation geschützt, und nur bestimmte Mitarbeiter haben Zugriff, um die Protokolle anzuzeigen.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die Anwendungsdaten werden in einer verwalteten MongoDB-Instanz gespeichert. Der Zugriff auf den verwalteten Dienst Atlas MongoDB Database wird über einen standardisierten Benutzerzugriffsanforderungsprozess bereitgestellt, der Genehmigungen erfordert. Regelmäßige Überprüfungen des Benutzerzugriffs werden mit der Verwaltungsanmeldung durchgeführt. Wir schränken die Anzahl der Mitarbeiter mit Zugriff auf vertrauliche Kundendaten ein, und es ist nicht zulässig, Daten von Computern direkt zu ändern.&#8232; Remotezugriff auf diese Datenbank erfordert eine mehrstufige Authentifizierung. Die Datenbank und alle ruhenden Sicherungen werden mithilfe der AES-256-Bit-Verschlüsselung verschlüsselt.


#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

