---
title: Anwendungsinformationen für Das StarLeaf-Add-In für Outlook von StarLeaf
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für das StarLeaf-Add-In für Outlook, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 1ae18b1e6d9f89f0680c4b50e0e144851f052b0b
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252926"
---
# <a name="starleaf-add-in-for-outlook"></a>StarLeaf-Add-In für Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 24. August 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381343" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von StarLeaf an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | StarLeaf-Add-In für Outlook |
| ID | WA104381343 |
| Office 365 unterstützten Clients | Outlook 2013 oder höher auf Windows, Outlook 2016 oder höher auf dem Mac, Outlook im Web |
| Partnerunternehmensname | StarLeaf |
| URL der Partnerwebsite | [https://www.starleaf.com/](https://www.starleaf.com/) |
| URL der Datenschutzrichtlinie | [https://www.starleaf.com/privacy-policy](https://www.starleaf.com/privacy-policy) |
| URL der Nutzungsbedingungen | [https://support.starleaf.com/legal-information/end-user-lic...](https://support.starleaf.com/legal-information/end-user-license-agreement-for-starleaf-applications) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von StarLeaf darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Anwendung | Wir speichern die iCalUId von Besprechungen, Uhrzeit/Datum der Besprechung, E-Mail-Adressen der Teilnehmer und eine Single-Value-Extended-Property, die wir über die benutzerdefinierte Eigenschaftenschnittstelle Office.js der Besprechung lesen und schreiben. Die iCalUId wird verwendet, um die Besprechung in&#8217;Outlook-Kalender mit der Videobetreff in unserem Dienst zu korrelieren. Uhrzeit/Datum und Teilnehmer werden verwendet, um den richtigen Personen in unserem Dienst zum richtigen Zeitpunkt eine Videobesprechung zur Verfügung zu stellen. SVEP werden mit unserem O365-Add-In verwendet, um benutzern eine Schnittstelle zum Festlegen von Details zur Videobetreffs in unserem Dienst wie z. B. Aufzeichnungen zur Verfügung zu stellen. | verwendet, um Webhookbenachrichtigungen zu abonnieren, um Benutzeränderungen an Ereignissen in ihren Kalendern nachverfolgt und unseren Dienst so zu aktualisieren, dass er konsistent bleibt. Es wird auch verwendet, um Ereignisse in ihrem Kalender zu erstellen, wenn ein Benutzer mit unserer Teams interagiert und eine Besprechung in unserem Dienst plant. | 6e86b349-768f-4953-ac2e-fb03f92db4be |
>| User.Read | Anwendung | Wir speichern das oauth-Aktualisierungstoken, um sich anmelden zu können. Wir speichern die Benutzerprofil-ID, um mit zukünftigen OAuth-Versuchen dieses Benutzers vergleichen zu können, und stellen sicher, dass&#8217;nicht zweimal speichern.  | Ermöglichen Sie Benutzern, sich bei der App anzumelden, und ermöglicht es unserer App, den Benutzer&#8217;E-Mail-Adresse zu erhalten, um seine Anmeldung mit einem Konto in unserem Dienst zu korrelieren.  | 6e86b349-768f-4953-ac2e-fb03f92db4be |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wenn technische Supportprobleme auftreten, können organisatorische Daten zur Fallverwaltung an SalesForce übertragen werden. Wenn der Benutzer das PstN-Einwahlfeature nutzt, wird der Anruf über Twilio, Plivo oder Voxbone fließen. |  | Nicht zutreffend |



#### <a name="add-in-data-access"></a>Add-In-Datenzugriff

Listet die Berechtigungen auf, die diese App für den Zugriff auf die Daten Ihrer Organisation benötigt, die Begründung und den Zweck dieser Berechtigung (wofür verwendet die App diese Informationen?), und ob die App diese Informationen in ihren Datenbanken speichert.

>| **Berechtigung**  | **Beschreibung** |
>|:----------------|:----------------|
>| ReadWrite-Element | Dieses Add-In kann auf persönliche Informationen in der aktiven Nachricht zugreifen und diese ändern, z. B. text, betreff, absender, empfänger und Anlageninformationen. Diese Daten können an einen Drittanbieterdienst gesendet werden. Andere Elemente in Ihrem Postfach können&#8217;gelesen oder geändert werden. |
>| Senden von Daten | Kann Daten über das Internet senden |

#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Ja. Protokolle umfassen Benutzernamen, IP-Adressen, Anrufdetaildatensätze, Informationen zur Verbindungsqualität (Paketverlust, Bitrate), Gerätetyp, Anruffortschritt. Die Informationen stehen dem technischen Supportteam und leitenden Entwicklern zur Diagnose von Dienstproblemen zur Verfügung. Die Daten werden nach 90 Tagen anonymisiert. Steuerelemente zum Schutz dieser Daten werden unter unserer ISO/IEC 27001-Zertifizierung überwacht.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die Daten werden auf den eigenen Protokollservern von StarLeaf&#8217;im Rechenzentrum gespeichert, in dem sich der Benutzer&#8217;seinem Konto befindet, und bis zu einem oder mehreren Rechenzentren innerhalb derselben Gerichtsbarkeit gesichert. Der Zugriff auf die Daten wird durch ein einzelnes Benutzerkonto mithilfe von Benutzerkennwörtern, die mit Stärke überprüft werden, verwendet. StarLeaf&#8217;Dienstbenutzerkonten werden automatisch für die Personalwesensysteme und die Active Directory-Gruppen des Unternehmens überwacht, um das Sicherheits- und Complianceteam zu warnen, wenn Anomalien gefunden werden.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

