---
title: Anwendungsinformationen für Zoho Sign von Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 04/30/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Zoho Sign, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9841df652531e49025ed8021527c6da1dd77d8a3
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413246"
---
# <a name="zoho-sign"></a>Zoho Sign

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/7a22873b-81e6-48ed-aee3-6f0e7dd5a104" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382011" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Zoho Corporation Private Limited für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Zoho Sign |
| ID | WA104382011 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Zoho Corporation Private Limited |
| URL der Partnerwebsite | [https://zoho.com](https://zoho.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.zoho.com/sign/help/teams-extension.html](https://www.zoho.com/sign/help/teams-extension.html) |
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
>| Contacts.ReadWrite | Delegiert |  | Haben Sie Vollzugriff auf Benutzerkontakte. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Contacts.ReadWrite.Shared | Delegiert |  | Lesen und Schreiben von Benutzerkontakten und freigegebenen Kontakten. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Files.ReadWrite | Delegiert |  | Vollzugriff auf Benutzerdateien. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Files.ReadWrite.All | Delegiert |  | Vollzugriff auf alle Dateien, auf die der Benutzer zugreifen kann. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Files.ReadWrite.Selected | Delegiert |  | Lesen und Schreiben von Dateien, die der Benutzer auswählt. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.ReadBasic.All | Delegiert |  | Lesen Sie die grundlegenden Profile aller Benutzer. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
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

>Wir erfassen keine EUII/PII in Telemetrie und Protokollen. Wir verfügen über Skripts, um nach solchen Daten zu suchen und darauf zu achten, dass diese daten sichtbar sind.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Kunden als Datenverantwortlicher haben immer Zugriff auf die Daten. Administratoren können Benutzer zu Zoho Sign hinzufügen oder daraus entfernen. Sie können alle in der Anwendung gespeicherten Informationen anzeigen, einschließlich vollständiger Überwachungsprotokolle und Nutzungsberichte. Sie können Daten und Benutzer löschen und die Kontrolle über Daten zwischen Benutzern übertragen.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35679' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35679" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


