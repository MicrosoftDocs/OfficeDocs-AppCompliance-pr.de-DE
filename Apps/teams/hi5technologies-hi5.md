---
title: Anwendungsinformationen für Hi5 von Hi5Technologies
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Hi5, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 983f86210f224bc492f54a7ab65192dee5b4ad6c
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552116"
---
# <a name="hi5"></a>Hi5

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 3. November 2020</p>

* <a href="https://teams.microsoft.com/l/app/ca334a56-72b5-4613-81d4-77b1148df03c" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001610" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Hi5Technologies Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Hi5 |
| ID | WA200001610 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Hi5 Technologies |
| URL der Partner-Website | [https://www.get5.io/](https://www.get5.io/) |
| URL der Datenschutzrichtlinie | [https://www.get5.io/privacy](https://www.get5.io/privacy) |
| URL der Nutzungsbedingungen | [https://www.get5.io/terms](https://www.get5.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Hi5Technologies darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegiert | Wir speichern nur sitzungsbezogene Benutzerinformationen von Teams und der Benutzer muss dies durch Hinzufügen von Benachrichtigungen genehmigen (sie können diese jederzeit entfernen). Es werden keine weiteren Informationen gespeichert. | Erforderlich für SSO-Anmeldung und Authentifizierung auf unserem Server | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| email | Delegiert | Wir speichern nur sitzungsbezogene Benutzerinformationen von Teams und der Benutzer muss dies durch Hinzufügen von Benachrichtigungen genehmigen (sie können diese jederzeit entfernen). Es werden keine weiteren Informationen gespeichert. | Erforderlich für SSO-Anmeldung und Authentifizierung auf unserem Server | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| offline_access | Delegiert | Wir speichern nur sitzungsbezogene Benutzerinformationen von Teams und der Benutzer muss dies durch Hinzufügen von Benachrichtigungen genehmigen (sie können diese jederzeit entfernen). Es werden keine weiteren Informationen gespeichert. | Bleibt dabei, dass der Benutzer die richtigen Informationen sieht und wir die richtigen Informationen an andere Personen senden können, die demselben Unternehmen/Arbeitsbereich beitreten. | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| openid | Delegiert | Wir speichern nur sitzungsbezogene Benutzerinformationen von Teams und der Benutzer muss dies durch Hinzufügen von Benachrichtigungen genehmigen (sie können diese jederzeit entfernen). Es werden keine weiteren Informationen gespeichert. | Erforderlich für SSO-Anmeldung und Authentifizierung auf unserem Server | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| Profil | Delegiert | Wir speichern nur sitzungsbezogene Benutzerinformationen von Teams und der Benutzer muss dies durch Hinzufügen von Benachrichtigungen genehmigen (sie können diese jederzeit entfernen). Es werden keine weiteren Informationen gespeichert. | Erforderlich für SSO-Anmeldung und Authentifizierung auf unserem Server | 7cb50e3e-0427-409e-90d2-638eb28217c3 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| So benachrichtigen Sie den Benutzer in einem Kanal, dass ihm ein Hi5 | Es werden keine Informationen gespeichert, der Benutzer wird nur von der Karte zurück gesendet in den Kanal |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Nein, Hi5 ist lediglich iFramed in und alle Daten werden sicher gespeichert.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Wir verwenden OAuth und bieten 3 Login-Optionen:
- Googles SSO (OAuth).
- Microsoft SSO (OAuth).
- Unsere eigene Verschlüsselung, die eine Kombination aus SHA und AES-Verschlüsselung ist.
Nach der Authentifizierung und Anmeldung gewährt Ihnen Ihre Berechtigungsstufe Zugriff auf autorisierte Abschnitte innerhalb der Hi5-Plattform.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

