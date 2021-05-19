---
title: Anwendungsinformationen für Soapbox von Soapbox
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Soapbox, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen sowie Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6e2b43df38aac6307c36c4a2cc8d00fe1c3fb629
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552776"
---
# <a name="soapbox"></a>Soapbox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://teams.microsoft.com/l/app/b49e7913-3b3f-4125-adde-2b698fc12c8b" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381501" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Soapbox Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Soapbox |
| ID | WA104381501 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Soapbox |
| URL der Partner-Website | [https://soapboxhq.com](https://soapboxhq.com) |
| URL Teams Anwendungsinfoseite | [https://msteams.services.soapboxhq.com/faqs](https://msteams.services.soapboxhq.com/faqs) |
| URL der Datenschutzrichtlinie | [https://soapboxhq.com/privacy-policy/microsoft-teams](https://soapboxhq.com/privacy-policy/microsoft-teams) |
| URL der Nutzungsbedingungen | [https://soapboxhq.com/terms-of-service](https://soapboxhq.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Soapbox darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Delegiert | Sync-Token. | Kalenderzugriff ist erforderlich, um SoapBox-Meetings mit Kalenderereignissen zu synchronisieren |  |
>| User.Read | Delegiert | Name, E-Mail, Microsoft-Benutzer-ID. | Name und E-Mail werden verwendet, um SoapBox-Benutzer zu erstellen. |  |
>| offline_access | Delegiert |  | Offlinezugriff auf Kalender ist erforderlich, um SoapBox-Benachrichtigungen zeitrelevant für synchronisierte Kalenderereignisse zu machen. |  |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Die App greift auf Team Roster und Chat Roster wir verwenden, um Team-Kanäle in SoapBox mit Mitgliedern des Teams / Chat zu erstellen | Name, E-Mail, Microsoft-Benutzer-ID der Benutzer, um das Erscheinungsbild der App für Microsoft-Teambenutzer zu verbessern und sicherzustellen, dass jeder Benutzer vollständig an der Besprechungssoftware teilnehmen kann. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Ja. Name, E-Mail und Microsoft-Benutzer-ID werden in unserer einheitlichen Protokollierungsplattform für maximal 30 Tage angezeigt, um Probleme zu identifizieren und Benutzern bei der Nutzung der Plattform zu helfen. Nach 30 Tagen werden die Daten von den Protokollierungsservern entfernt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Unsere primäre Infrastruktur wird in AWS in einem privaten Netzwerk gespeichert. Wir haben auch Bots auf Heroku und Azure konfiguriert. Der Zugriff auf Server ist mit SSH-Schlüsselanforderungen eingeschränkt. Alle Anfragen sind über SSL (TLS 1.3). Wir verwenden signierte Anfragen, um sicherzustellen, dass der Datenverkehr von unseren Bots zur Plattform sicher ist. Die Daten werden im Ruhezustand verschlüsselt. Mitarbeiter von Dev ops benötigen 2FA für den Zugriff auf ihre Konten

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35464' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35464" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

