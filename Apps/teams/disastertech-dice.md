---
title: Anwendungsinformationen für DisasterTech DICE von DisasterTech
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für DisasterTech DICE, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 29d53402a9bbf635e83d6d262227a8363577e261
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552236"
---
# <a name="disastertech-dice"></a>DisasterTech DICE

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 24. August 2020</p>

* <a href="https://teams.microsoft.com/l/app/7df3e67b-ed62-48e9-a950-c95bd7ebce80" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001909" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die DisasterTech Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | DisasterTech DICE |
| ID | WA200001909 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | DisasterTech |
| URL der Partner-Website | [https://dice.disastertech.com](https://dice.disastertech.com) |
| URL der Datenschutzrichtlinie | [https://dice.disastertech.com/privacy.html](https://dice.disastertech.com/privacy.html) |
| URL der Nutzungsbedingungen | [https://dice.disastertech.com/tos.html](https://dice.disastertech.com/tos.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von DisasterTech darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegiert | Benutzer-E-Mail-Adresse, die zum Einrichten von Zugriffsrechten sowie zum Identifizieren von Benutzern nach Namen gespeichert ist | Ermöglicht dem Benutzer die Anmeldung und gewährt der App Zugriff auf seinen UPN, um eine stille Anmeldung sowie Teams Anmeldung zu aktivieren, sowie Benutzernamen und E-Mail-Adressen einzurichten. | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| email | Delegiert | Keine | Erforderlich für Teams Single Sign-On | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| offline_access | Delegiert | Keine | Erforderlich für Teams Single Sign-On | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| openid | Delegiert | Keine | Erforderlich für Teams Single Sign-On | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| Profil | Delegiert | Keine | Erforderlich für Teams einmaliges Anmelden. | 36d23b76-c58b-4a34-a60f-dceac6962bad |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird kein EUII abgerufen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Wir speichern den Benutzernamen, den Vornamen und den Nachnamen in einer postgreSQL-Datenbank, die von Azure gehostet wird, damit Benutzer in der Anwendung zusammenarbeiten können. Die Steuerelemente sind, dass nur Disaster Tech-Mitarbeiter direkten Zugriff auf die Datenbank haben. Wenn ein Benutzer aus der Anwendung entfernt wird, archivieren wir die Informationen. Die Nutzer behalten sich das Recht vor, ihre personenbezogenen Daten jederzeit aus dem System zu entfernen. Die Entfernung solcher Informationen würde jedoch auch ihre Verwendung der Anmeldung verbieten.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Die Anwendungsdaten werden in einer PostgreSQL-Datenbank in Azure gespeichert, die im Ruhezustand verschlüsselt ist. Kein Benutzer hat direkten Zugriff auf die Datenbank oder die Back-End-API. Alle API-Aufrufe sind mit einem Active Directory Access Token geschützt.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

