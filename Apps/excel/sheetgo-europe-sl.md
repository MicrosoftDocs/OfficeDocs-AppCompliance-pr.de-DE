---
title: Anwendungsinformationen für Sheetgo von SHEETGO EUROPE SL
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Sheetgo, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
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

* <a href="https://appsource.microsoft.com/product/office/WA200002128" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen von SHEETGO EUROPE SL an Microsoft:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Sheetgo |
| ID | WA200002128 |
| Office 365 unterstützten Clients | Excel 2016 oder später auf Mac, Excel 2016 oder später Windows, Excel im Web |
| Name des Partnerunternehmens | SHEETGO EUROPE SL |
| URL der Partner-Website | [https://appsource.microsoft.com/marketplace/apps?product=of...](https://appsource.microsoft.com/marketplace/apps?product=office) |
| URL der Datenschutzrichtlinie | [https://www.sheetgo.com/legal/privacy](https://www.sheetgo.com/legal/privacy) |
| URL der Nutzungsbedingungen | [https://www.sheetgo.com/legal/terms](https://www.sheetgo.com/legal/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von SHEETGO EUROPE SL darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>Diese Anwendung verwendet keine Microsoft-Graph.


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| MongoDB: System- und Benutzerdaten aufzeichnen, um zu funktionieren, Google BigQuery: Aufzeichnungssystem protokolliert Nutzung, Google Firestore: Ein System, das den Zustand unserer Microservices pflegt und orchestriert, Stripe: Zahlungssystem |  | Diese Anwendungen verwenden keine zusätzlichen Microsoft-APIs |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Telemetriedaten/-protokolle enthalten die E-Mail-Adresse des Benutzers nur als identitätsstiftende Endbenutzerinformationen. Auf Anfrage des Benutzers führt das Anwendungssupportteam eine interne automatische Routine aus, die E-Mail-Adressen über Telemetriedaten/Protokolle hinweg verwischt und die Benutzerdaten nicht mehr identifizierbar macht.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>MongoDB: Zeichnen Sie System- und Benutzerdaten auf, um Google BigQuery zu funktionieren: Aufzeichnungssystemprotokolle Nutzung Google Firestore: Ein System, das den Zustand unserer Microservices verwaltet und orchestriert. Die einzigen kritischen Daten, die dieser Dienst transitist, sind die Benutzeranmeldeinformationen, die mit AES256 Stripe: Payment System verschlüsselt werden.
 
Alle Daten während der Übertragung verwenden HTTPS für sichere Verbindungen und alle sensiblen Daten werden mit AES256 verschlüsselt

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

