---
title: Anwendungsinformationen für FormMaschinen für SharePoint von ENTERPRISE DIGITAL MACHINES PTY LTD
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für FormMachines für SharePoint, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 4c423cac4f879ba4f73a9bba5f9004acb4cfa21a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553546"
---
# <a name="formmachines-for-sharepoint"></a>FormMachines für SharePoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 3. November 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA200000357" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen von ENTERPRISE DIGITAL MACHINES PTY LTD an Microsoft:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | FormMachines für SharePoint |
| ID | WA200000357 |
| Office 365 unterstützten Clients | SharePoint 2016 oder später |
| Name des Partnerunternehmens | ENTERPRISE DIGITAL MASCHINEN PTY LTD |
| URL der Partner-Website | [https://www.formmachines.com/](https://www.formmachines.com/) |
| URL der Datenschutzrichtlinie | [https://www.formmachines.com/?dirKey=fm-privacy](https://www.formmachines.com/?dirKey=fm-privacy) |
| URL der Nutzungsbedingungen | [https://www.formmachines.com/?dirKey=fm-terms-of-use](https://www.formmachines.com/?dirKey=fm-terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von ENTERPRISE DIGITAL MACHINES PTY LTD darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegiert | (Login, E-Mail, Azure Guid, displayName, first_login_date_time) | ermöglicht es dem Benutzer, sich anzumelden und gewährt App-Zugriff auf seinen UPN, um eine stille Anmeldung zu aktivieren, ermöglicht es uns, jeden Benutzer eindeutig zu identifizieren | 8c87660f-d36f-41f6-b0ae-025253f380aa |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>. Wir protokollieren nur Fehler . In unserem Fehlerprotokoll protokollieren wir nur fehlerbezogene Informationen. Welcher Kunde oder Kunde einen bestimmten Fehler ausgelöst hat, wird nicht erfasst. Nur Support-Techniker haben Zugriff auf Fehlerprotokolle . Fehlerprotokolle werden online angezeigt, nicht heruntergeladen und angezeigt. Fehlerprotokolle werden nach 30 Tagen automatisch gelöscht

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>. Daten werden in Azure US-basierten Rechenzentren gespeichert. Vom Client bereitgestellte Daten wie Vorlagen und Übermittlungen werden in der DB verschlüsselt. Dateianlagen werden in privaten Azure BLOB-Containern gespeichert, Benutzer müssen sich authentifizieren, bevor sie darauf zugreifen. Wir haben maximal zwei Administratoren, die auf unsere Produktionsressourcen zugreifen können, um Fehlerbehebung und Bereitstellung zu ermöglichen. Diese beiden Administratorkonten sind anders partitioniert als alle anderen Konten. Die Anzahl der Admin-Zugriffe wird nie zwei überschreiten

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

