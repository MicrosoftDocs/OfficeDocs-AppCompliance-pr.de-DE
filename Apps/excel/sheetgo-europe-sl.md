---
title: Anwendungsinformationen für Sheetgo von SHEETGO EUROPE SL
ms.author: elmalova
author: elenamalova
ms.date: 09/30/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Sheetgo, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 491049af0b675c477fce225476afb1e05919ae2a
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414811"
---
# <a name="sheetgo"></a>Sheetgo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 3. November 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA200002128" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von SHEETGO EUROPE SL für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Sheetgo |
| ID | WA200002128 |
| Office 365 unterstützten Clients | Excel 2016 oder höher auf dem Mac, Excel 2016 oder höher auf Windows Excel im Web |
| Name des Partnerunternehmens | SHEETGO EUROPE SL |
| URL der Partnerwebsite | [https://www.sheetgo.com/](https://www.sheetgo.com/) |
| URL der Datenschutzrichtlinie | [https://www.sheetgo.com/legal/privacy/](https://www.sheetgo.com/legal/privacy/) |
| URL der Nutzungsbedingungen | [https://www.sheetgo.com/legal/terms/](https://www.sheetgo.com/legal/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von SHEETGO EUROPE SL darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>Diese Anwendung verwendet microsoft Graph nicht.


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| MongoDB: Aufzeichnen von System- und Benutzerdaten zur Funktion, Google BigQuery: Aufzeichnen der Systemprotokolle, Google Firestore: Ein System, das den Status unserer Microservices verwaltet und orchestriert, Stripe: Payment-System |  | Diese Anwendungen verwenden keine zusätzlichen Microsoft-APIs |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Telemetrie/Protokolle enthalten die E-Mail-Adresse des Benutzers nur als Identifizierbarkeitsinformationen des Endbenutzers. Auf Anforderung des Benutzers führt das Anwendungssupportteam eine interne automatische Routine aus, die E-Mail-Adressen über Telemetrie/Protokolle hinweg verschwommen und die Benutzerdaten nicht mehr identifizierbar macht.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>MongoDB: Zeichnen Sie System- und Benutzerdaten auf, um Google BigQuery zu verwenden: Aufzeichnen von Systemprotokollen für die Nutzung von Google Firestore: Ein System, das den Status unserer Microservices verwaltet und orchestriert. Die einzigen kritischen Daten dieser Diensttransit sind die Benutzeranmeldeinformationen, die mit AES256 Stripe: Payment System verschlüsselt werden.
 
Alle Daten während der Übertragung verwenden HTTPS für sichere Verbindungen, und alle vertraulichen Daten werden mit AES256 verschlüsselt.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


