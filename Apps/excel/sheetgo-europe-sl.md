---
title: Anwendungsinformationen für Sheetgo von SHEETGO EUROPE SL
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Sheetgo, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: cba1d32ef248cc8228a0e38e1dc953dd07f4e5ad
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52548725"
---
# <a name="sheetgo"></a>Sheetgo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 3. November 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA200002128" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von SHEETGO EUROPE SL an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Sheetgo |
| ID | WA200002128 |
| Office 365 unterstützten Clients | Excel 2016 oder höher auf mac, Excel 2016 oder höher auf Windows, Excel im Web |
| Partnerunternehmensname | SHEETGO EUROPE SL |
| URL der Partnerwebsite | [https://appsource.microsoft.com/marketplace/apps?product=of...](https://appsource.microsoft.com/marketplace/apps?product=office) |
| URL der Datenschutzrichtlinie | [https://www.sheetgo.com/legal/privacy](https://www.sheetgo.com/legal/privacy) |
| URL der Nutzungsbedingungen | [https://www.sheetgo.com/legal/terms](https://www.sheetgo.com/legal/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von SHEETGO EUROPE SL darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>Diese Anwendung verwendet keine Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| MongoDB: Record system and user data to function, Google BigQuery: Record system logs usage, Google Firestore: A system which maintains and orchestras the state of our microservices, Stripe: Payment system |  | Diese Anwendungen verwenden keine zusätzlichen Microsoft-APIs |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Telemetrie/Protokolle enthalten die E-Mail-Adresse des Benutzers nur als endbenutzeridentifizierbare Informationen. Auf Anfrage des Benutzers führt das Anwendungsunterstützungsteam eine interne automatische Routine aus, die E-Mail-Adressen über Telemetrie-/Protokolldaten hinweg verwischen und die Benutzerdaten nicht mehr identifizierbar macht.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>MongoDB: Aufzeichnen von System- und Benutzerdaten für die Funktion von Google BigQuery: Systemprotokolle aufzeichnen Verwendung Google Firestore: Ein System, das den Status unserer Mikrodienste verwaltet und orchestriert. Die einzigen wichtigen Daten dieser Diensttransit sind die Benutzeranmeldeinformationen, die mit AES256 Stripe: Payment System verschlüsselt werden.
 
Alle übertragenen Daten verwenden HTTPS für sichere Verbindungen, und alle vertraulichen Daten werden mit AES256 verschlüsselt.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

