---
title: Bewerbungsinformationen für Sheetgo von SHEETGO EUROPE SL
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Sheetgo, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9cbad6d4fcd5f6e081187af10c3c8a69de7122ba
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225309"
---
# <a name="sheetgo"></a>Sheetgo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Letzte Aktualisierung durch den Entwickler am: 3. November 2020</p>

* <a href="https://teams.microsoft.com/l/app/583de270-58d0-4f94-af06-bf971f82fd94" target="_blank">Anzeigen im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002067" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von SHEETGO EUROPE SL an Microsoft bereitgestellte Informationen:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | Sheetgo |
| ID | WA200002067 |
| unterstützte Office 365 Clients | Microsoft Teams |
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

Auflisten aller [Microsoft Graph Berechtigungen](/graph/permissions-reference), die diese App benötigt.

>Diese Anwendung verwendet keine Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder freigibt, listen Sie den von der App nicht von Microsoft stammenden Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII wird übertragen an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| MongoDB: Aufzeichnen von System- und Nutzerdaten zur Funktion, Google BigQuery: Datensatzsystem protokolliert Nutzung, Google Firestore: Ein System, das den Zustand unserer Microservices aufrechterhält und orchestriert, Stripe: Payment system |  | Diese Anwendungen verwenden keine zusätzlichen Microsoft-APIs. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Endbenutzer-identifizierbare Informationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wurde. Nutzt diese App diese Funktion?

>Es wird kein EUII-Zugriff erfolgt.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder Endbenutzer-identifizierbare Informationen (EUII) in den Telemetriedaten oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Aufbewahrungs- und Entfernungsrichtlinien gelten?

>Telemetrie/Protokolle umfassen die E-Mail-Adresse des Benutzers nur als identifizierbare Informationen für den Endbenutzer. Auf Anforderung des Benutzers führt das Anwendungssupportteam eine interne automatische Routine aus, die E-Mail-Adressen über Telemetrie/Protokolle hinweg weichzeichnet und die Benutzerdaten nicht mehr identifizierbar macht.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren der Organisation ihre Informationen in Partnersystemen steuern können? z.B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>MongoDB: Aufzeichnen von System- und Benutzerdaten zur Funktion von Google BigQuery: Record system logs usage Google Firestore: Ein System, das den Zustand unserer Microservices aufrechterhält und orchestriert. Die einzigen wichtigen Daten, die dieser Dienst durchläuft, sind die Benutzeranmeldeinformationen, die mit AES256 Stripe: Payment system verschlüsselt sind.
 
Alle Daten während der Übertragung verwenden HTTPS für sichere Verbindungen, und alle vertraulichen Daten werden mit AES256 verschlüsselt.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational Identifiable Information) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141" target="_blank">Auf einer neuen Registerkarte anzeigen</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

