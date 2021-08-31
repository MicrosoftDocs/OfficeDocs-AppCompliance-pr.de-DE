---
title: Anwendungsinformationen für TELUS Business Verbinden von RingCentral, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/04/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für TELUS Business Verbinden, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 4dcb3d75594ed7c09736be8e6291bbbead9393ef
ms.sourcegitcommit: 78e63c8004c49fa95d80618b9fee424f1084e43d
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/19/2021
ms.locfileid: "58404477"
---
# <a name="telus-business-connect"></a>TELUS Business Verbinden

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 4, 2021</p>

* <a href="https://teams.microsoft.com/l/app/d5001eed-f63e-4a7d-9b49-bf8272c934cd" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002300" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von RingCentral, Inc. für Microsoft bereitgestellte Informationen:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | TELUS Business Verbinden |
| ID | WA200002300 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | RingCentral, Inc. |
| URL der Partnerwebsite | [https://www.ringcentral.com](https://www.ringcentral.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://appsource.microsoft.com/en-us/product/office/WA2000...](https://appsource.microsoft.com/en-us/product/office/WA200002300) |
| URL der Datenschutzrichtlinie | [https://www.telus.com/en/about/privacy/](https://www.telus.com/en/about/privacy/) |
| URL der Nutzungsbedingungen | [https://telus.com/BusinessConnect/ServiceTerms](https://telus.com/BusinessConnect/ServiceTerms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von RingCentral, Inc. zur Verfügung gestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | Delegiert |  Ermöglicht der Anwendung, Besprechungseinladungen über ihren Kalender zu senden | Keine | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |
>| User.Read | Delegiert |  Ermöglicht der App, das grundlegende Profil eines Benutzers&#8217;(E-Mail, Name) zu lesen, um Kontaktüberstimmungen an unserem Ende zu erreichen. Und ermöglicht es Benutzern, sich anzumelden und ihr O365-Konto mit dem RingCentral-Konto zu verknüpfen. |  E-Mail, Vorname, Nachname | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |
>| User.Read.All | Delegiert | Ermöglicht der Anwendung, das vollständige Profil eines Benutzers mit Telefonnummern zu lesen, um Telefonanrufe mit unseren Diensten zu tätigen. | Keine | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |
>| offline_access | Delegiert |  Ermöglicht der Anwendung, das oauth-Token abzurufen und zu aktualisieren |  Zugriffstoken, Aktualisierungstoken für den Zugriff auf die MS-Graph-API | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Personenbezogene Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wenn wir eine andere Organisation verwenden, kontrollieren wir weiterhin Ihre persönlichen Informationen. Und wir verfügen über strenge Kontrollen, um sicherzustellen, dass es ordnungsgemäß geschützt&#8217;. Schließlich werden im abschnitt oben die Situationen beschrieben, in denen Ihre persönlichen Informationen an andere Organisationen, Behörden und Strafverfolgungsbehörden weitergegeben werden.  Wenn wir Ihre Informationen an andere Organisationen weitergeben,&#8217;wir sicherstellen, dass sie so weit wie möglich geschützt&#8217;.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von RingCentral, Inc. bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Response** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
