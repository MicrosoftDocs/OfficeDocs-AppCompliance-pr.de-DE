---
title: Anwendungsinformationen für StarLeaf Add-In für Outlook von StarLeaf
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für das StarLeaf-Add-In für Outlook, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f201131be32c743550a02a24e653f784a1d91817
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552476"
---
# <a name="starleaf-add-in-for-outlook"></a>StarLeaf Add-in für Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 24. August 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381343" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die StarLeaf Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | StarLeaf Add-in für Outlook |
| ID | WA104381343 |
| Office 365 unterstützten Clients | Outlook 2013 oder später Windows, Outlook 2016 oder später auf Mac, Outlook im Web |
| Name des Partnerunternehmens | StarLeaf |
| URL der Partner-Website | [https://www.starleaf.com/](https://www.starleaf.com/) |
| URL der Datenschutzrichtlinie | [https://www.starleaf.com/privacy-policy](https://www.starleaf.com/privacy-policy) |
| URL der Nutzungsbedingungen | [https://support.starleaf.com/legal-information/end-user-lic...](https://support.starleaf.com/legal-information/end-user-license-agreement-for-starleaf-applications) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von StarLeaf darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Anwendung | Wir speichern die iCalUId von Besprechungen, Uhrzeit/Datum der Besprechung, E-Mail-Adressen des Teilnehmers und eine Single-Value-Extended-Property, die wir über die benutzerdefinierte Eigenschaftenschnittstelle Office.js lesen und auf der Besprechung schreiben. Die iCalUId wird verwendet, um die Besprechung in einem Benutzer&#8217;Outlook-Kalender mit dem Video-Meeting auf unserem Dienst zu korrelieren. Die Uhrzeit/datum und die Teilnehmer werden verwendet, um ein Video-Meeting zur richtigen Zeit für die richtigen Personen in unserem Service zur Verfügung zu stellen. SVEP sind mit unserem O365 Add-In gewohnt, um Benutzern eine Schnittstelle zur Verfügung zu stellen, um Details über das Video-Meeting auf unserem Dienst wie die Aufzeichnung festzulegen. | wird verwendet, um Webhook-Benachrichtigungen zu abonnieren, um Benutzeränderungen an Ereignissen in ihren Kalendern nachzuverfolgen und unseren Dienst zu aktualisieren, um ihn konsistent zu halten. Es wird auch verwendet, um Ereignisse in seinem Kalender zu erstellen, wenn ein Benutzer mit unserer Teams App interagiert und eine Besprechung für unseren Dienst plant. | 6e86b349-768f-4953-ac2e-fb03f92db4be |
>| User.Read | Anwendung | wir speichern das oauth-Aktualisierungstoken, um sich anmelden zu können. Wir speichern die Benutzerprofil-ID, um mit zukünftigen OAuth-Versuchen dieses Benutzers vergleichen zu können und stellen sicher, dass wir ihre Daten nicht zweimal speichern&#8217;.  | Ermöglichen Sie es Benutzern, sich bei der App anzumelden und ermöglichen es unserer App, die E-Mail-Adresse des Benutzers&#8217;, um ihre Anmeldung mit einem Konto in unserem Dienst zu korrelieren.  | 6e86b349-768f-4953-ac2e-fb03f92db4be |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wenn technische Support-Probleme auftreten, können Organisationsdaten zur Fallverwaltung an SalesForce übertragen werden. Wenn der Benutzer die PSTN-Einwahlfunktion nutzt, fließt der Anruf durch Twilio, Plivo oder Voxbone |  | Nicht zutreffend |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Ja. Protokolle umfassen Benutzernamen, IP-Adressen, Anruf-Detail-Datensätze, Informationen über Verbindungsqualität (Paketverlust, Bitrate), Gerätetyp, Anruffortschritt. Die Informationen stehen dem technischen Support-Team und leitenden Entwicklern zur Diagnose von Serviceproblemen zur Verfügung. Die Daten werden nach 90 Tagen anonymisiert. Kontrollen zum Schutz dieser Daten werden gemäß unserer ISO/IEC 27001-Zertifizierung geprüft.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Die Daten werden auf StarLeaf-&#8217;eigenen Protokollservern im Rechenzentrum gespeichert, in dem sich der Nutzer&#8217;-Konto befindet, und in einem oder mehreren Rechenzentren innerhalb derselben Gerichtsbarkeit gesichert. Der Zugriff auf die Daten erfolgt über ein einzelnes Benutzerkonto mit benutzerfreundlichen Kennwörtern, die stark geprüft sind. StarLeaf&#8217;Dienstbenutzerkonten werden automatisch anhand der HR-Systeme und der Active Directory-Gruppen des Unternehmens überwacht, um das Sicherheits- und Compliance-Team zu warnen, wenn Anomalien gefunden werden.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

