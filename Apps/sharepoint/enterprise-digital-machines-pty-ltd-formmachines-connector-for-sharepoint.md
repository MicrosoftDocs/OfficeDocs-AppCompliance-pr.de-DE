---
title: Anwendungsinformationen für FormMachines Connector für SharePoint von ENTERPRISE DIGITAL MACHINES PTY LTD
ms.author: elmalova
author: elenamalova
ms.date: 09/25/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für FormMachines Connector für SharePoint, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3d5cab668924d0edfed32a807096be68519a775f
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410479"
---
# <a name="formmachines-connector-for-sharepoint"></a>FormMachines Connector für SharePoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 3, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA200000357" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von ENTERPRISE DIGITAL MACHINES PTY LTD an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | FormMachines Connector für SharePoint |
| ID | WA200000357 |
| Office 365 unterstützten Clients | SharePoint 2016 oder höher |
| Name des Partnerunternehmens | ENTERPRISE DIGITAL MACHINES PTY LTD |
| URL der Partnerwebsite | [https://www.formmachines.com](https://www.formmachines.com) |
| URL der Datenschutzrichtlinie | [https://www.formmachines.com?dirKey=fm-privacy](https://www.formmachines.com?dirKey=fm-privacy) |
| URL der Nutzungsbedingungen | [https://www.formmachines.com?dirKey=fm-terms-of-use](https://www.formmachines.com?dirKey=fm-terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von ENTERPRISE DIGITAL MACHINES PTY LTD darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | Delegiert | (Login, E-Mail, Azure Guid, displayName, first_login_date_time) | ermöglicht es Benutzern, sich anzumelden, und ermöglicht app-Zugriff auf ihren UPN, um die automatische Anmeldung zu ermöglichen, ermöglicht es uns, jeden Benutzer eindeutig zu identifizieren. | [8c87660f-d36f-41f6-b0ae-025253f380aa](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c87660f-d36f-41f6-b0ae-025253f380aa) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>. Wir protokollieren nur Fehler. In unserem Fehlerprotokoll protokollieren wir nur Fehlerinformationen. Welcher Client oder Kunde einen bestimmten Fehler ausgelöst hat, wird nicht erfasst. Nur Supporttechniker haben Zugriff auf Fehlerprotokolle. Fehlerprotokolle werden online angezeigt, nicht heruntergeladen und angezeigt. Fehlerprotokolle werden nach 30 Tagen automatisch gelöscht.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>. Daten werden in Azure US-basierten Rechenzentren gespeichert. Vom Client bereitgestellte Daten wie Vorlagen und Übermittlungen werden in der DATENBANK verschlüsselt. Dateianlagen werden in privaten Azure BLOB-Containern gespeichert, Benutzer müssen sich authentifizieren, bevor sie darauf zugreifen können. Wir haben maximal zwei Administratoren, die zur Problembehandlung und Bereitstellung auf unsere Produktionsressourcen zugreifen können. Diese beiden Administratorkonten sind von allen anderen Konten unterschiedlich partitioniert. Die Anzahl der Administratorzugriffe überschreitet nie zwei

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


