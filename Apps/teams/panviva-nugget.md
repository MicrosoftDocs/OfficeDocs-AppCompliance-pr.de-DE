---
title: Anwendungsinformationen für Nugget von Panviva
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Nugget, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 7c32714b99ec38c2328c1443fb8747ac8b516a3e
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429693"
---
# <a name="nugget"></a>Nugget

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: October 12, 2020</p>

* <a href="https://teams.microsoft.com/l/app/4e85cc82-5187-4059-af36-a49e7db32bee" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001737" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Panviva für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Nugget |
| ID | WA200001737 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Panviva |
| URL der Partnerwebsite | [https://www.panviva.com](https://www.panviva.com) |
| URL der Datenschutzrichtlinie | [https://www.panviva.com/privacy-policy/](https://www.panviva.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://www.panviva.com/terms-and-conditions](https://www.panviva.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Panviva darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>Diese Anwendung verwendet microsoft Graph nicht.


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Ja.
Teams Benutzer-ID gespeichert wird: Dies ist erforderlich, damit wir Informationen darüber abrufen können, in welchem Mandanten er sich befindet und ob der Benutzer Administrator ist oder nicht.
Teams Organisations-ID: Diese wird gespeichert, damit wir die Benutzer in einem Mandanten abrufen und die Abonnementdetails für diesen bestimmten Mandanten abrufen können.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir verwenden Azure CosmosDB, um alle Anwendungsdaten zu speichern. Für den Zugriff auf die Daten benötigen Sie einen Endpunkt und einen Schlüssel, die beide in den Konfigurationsdienst eingefügt werden, der für den Zugriff auf die Daten verwendet wird. Der Konfigurationsdienst verarbeitet Anforderungen nur mit einem Bearertoken, das er in der Anforderung von unserem Bot-App-Dienst empfängt. Dieses Token wurde ursprünglich von Okta erstellt, wenn sich ein Benutzer auf der Team-Benutzeroberfläche beim Bot anmeldet. Auf diese Daten können Panviva-Administratoren zugreifen, die sich mit der 2-Faktor-Authentifizierung bei der Microsoft Azure Plattform anmelden müssen. E-Mails und Vornamen des Benutzers werden in OKTA gespeichert und können nur mit einem privaten Schlüssel aufgerufen werden, der in einem Schlüsseltresor gespeichert ist, auf den der Konfigurationsdienst dann zugreifen kann. Nur der Konfigurationsdienst hat Zugriff auf den Schlüsseltresor über die Verwendung von verwalteten Identitäten, um keine Anmeldeinformationen in der App zu speichern.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36079' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36079" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

