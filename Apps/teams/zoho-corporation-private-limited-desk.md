---
title: Anwendungsinformationen für Zoho Desk von Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 04/30/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Zoho Desk, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2882f70ce6c44de4b797ae15bee2bec446212a82
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414340"
---
# <a name="zoho-desk"></a>Zoho Desk

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/091ec948-c0ee-4d56-aa9e-51c3d8316a9c" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382044" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Zoho Corporation Private Limited für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Zoho Desk |
| ID | WA104382044 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Zoho Corporation Private Limited |
| URL der Partnerwebsite | [https://www.zoho.com/desk](https://www.zoho.com/desk) |
| URL der Seite mit Teams Anwendungsinformationen | [https://help.zoho.com/portal/kb/zoho-desk](https://help.zoho.com/portal/kb/zoho-desk) |
| URL der Datenschutzrichtlinie | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| URL der Nutzungsbedingungen | [https://www.zoho.com/terms.html](https://www.zoho.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Zoho Corporation Private Limited zur Verfügung gestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.Read | Delegiert |  | Benutzerdateien lesen. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Files.Read.All | Delegiert |  | Lesen Sie alle Dateien, auf die der Benutzer zugreifen kann. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read | Delegiert |  | Melden Sie sich an, und lesen Sie das Benutzerprofil. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.ReadBasic.All | Delegiert |  | Lesen sie die grundlegenden Profile aller Benutzer. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| email | Delegiert |  | Zeigen Sie die E-Mail-Adresse des Benutzers an. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| offline_access | Delegiert |  | Behalten Sie den Zugriff auf Daten bei, auf die Sie ihr Zugriff gewährt haben. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Profil | Delegiert |  | Zeigen Sie das grundlegende Profil des Benutzers an. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Nein

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>1) Auf der Benutzeroberfläche gibt es eine Option zum Löschen der Entitäten, Administratoren und Agents innerhalb des Zoho Desks, die Löschoptionen haben, können dies ausführen. 2) Wir haben auch Optionen zum Exportieren, mit denen der Administrator exportieren und für ihren Zweck erreichen kann.  3) Wir führen die Überwachung im Back-End durch, auf Kundenanforderung können diese Informationen bereitgestellt werden.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/28308' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/28308" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


