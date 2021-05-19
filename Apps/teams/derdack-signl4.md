---
title: Anwendungsinformationen für SIGNL4 von Derdack SIGNL4
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für SIGNL4, seine Datenverarbeitungsrichtlinien, die Informationen zum Katalogkatalog der Microsoft Cloud App Security-App und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a619327000c93e3292e266c8b025034370a8b623
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553206"
---
# <a name="signl4"></a>SIGNL4

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 6. August 2020</p>

* <a href="https://teams.microsoft.com/l/app/bd19c878-00b7-47cd-9b65-74a2def84427" target="_blank">Anzeigen im Teams-Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001239" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Derdack SIGNL4 Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | SIGNL4 |
| ID | WA200001239 |
| Unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | Derdack SIGNL4 |
| URL der Partner-Website | [https://www.signl4.com](https://www.signl4.com) |
| URL der Datenschutzrichtlinie | [https://www.signl4.com/privacy-policy/](https://www.signl4.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://www.signl4.com/terms_of_use/](https://www.signl4.com/terms_of_use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Derdack SIGNL4 darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft Graph-Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>Diese Anwendung verwendet Microsoft Graph nicht.


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle Nicht-Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Rekursiver E-Mail-Adresse, E-Mail-Adresse ist erforderlich, um Rechnungsbenachrichtigungen an den Kunden zu senden, wenn er die App verwendet. Twilio, Telefonnummern, Benachrichtigungen zum Senden von Benachrichtigungen per SMS |  | Azure Management-API, Azure Monitor-Warnungen werden gesammelt, Auflistung geschieht, weil die Systeme Benachrichtigungen für diese Warnungen senden |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird kein EUII abgerufen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>E-Mail-Adressinformationen sind in Protokollen enthalten. Auch zusätzliche Warnungsinhaltsdaten, die von der Organisation übermittelt werden, können in die Protokolle aufgenommen werden. Um dies zu verhindern, kann die Organisation das Konto in der App kündigen.
Die Daten in den Protokollen werden für support- und Problembehandlungsprobleme des Kunden mit der App benötigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Daten werden im Azure-Rechenzentrum in Europa gespeichert. Der Zugriff darauf ist für Administratoren möglich. 2FA mit AAD-Authentifizierung. Zugriffsschlüssel auf Speicherkonten werden auch zum Verwalten des Zugriffs verwendet.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App-Sicherheitsinformationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35955' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35955" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

