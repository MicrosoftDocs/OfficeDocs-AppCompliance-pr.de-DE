---
title: Anwendungsinformationen für Hi5 by Hi5Technologies
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Hi5, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
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

* <a href="https://teams.microsoft.com/l/app/ca334a56-72b5-4613-81d4-77b1148df03c" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001610" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Hi5Technologies an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Hi5 |
| ID | WA200001610 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Hi5 Technologies |
| URL der Partnerwebsite | [https://www.get5.io/](https://www.get5.io/) |
| URL der Datenschutzrichtlinie | [https://www.get5.io/privacy](https://www.get5.io/privacy) |
| URL der Nutzungsbedingungen | [https://www.get5.io/terms](https://www.get5.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Hi5Technologies darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegierte | Wir speichern nur die Sitzungsinformationen der Benutzer Teams und der Benutzer muss dies durch Hinzufügen von Benachrichtigungen genehmigen (er kann diese jederzeit entfernen). Es werden keine weiteren Informationen gespeichert. | Erforderlich für die SSO-Anmeldung und -Authentifizierung für unseren Server | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| email | delegierte | Wir speichern nur die Sitzungsinformationen der Benutzer Teams und der Benutzer muss dies durch Hinzufügen von Benachrichtigungen genehmigen (er kann diese jederzeit entfernen). Es werden keine weiteren Informationen gespeichert. | Erforderlich für die SSO-Anmeldung und -Authentifizierung für unseren Server | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| offline_access | delegierte | Wir speichern nur die Sitzungsinformationen der Benutzer Teams und der Benutzer muss dies durch Hinzufügen von Benachrichtigungen genehmigen (er kann diese jederzeit entfernen). Es werden keine weiteren Informationen gespeichert. | Behält bei, dass dem Benutzer die richtigen Informationen angezeigt werden, und wir können die richtigen Informationen an andere Senden, die dem gleichen Unternehmen/Arbeitsbereich beitreten. | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| openid | delegierte | Wir speichern nur die Sitzungsinformationen der Benutzer Teams und der Benutzer muss dies durch Hinzufügen von Benachrichtigungen genehmigen (er kann diese jederzeit entfernen). Es werden keine weiteren Informationen gespeichert. | Erforderlich für die SSO-Anmeldung und -Authentifizierung für unseren Server | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| Profil | delegierte | Wir speichern nur die Sitzungsinformationen der Benutzer Teams und der Benutzer muss dies durch Hinzufügen von Benachrichtigungen genehmigen (er kann diese jederzeit entfernen). Es werden keine weiteren Informationen gespeichert. | Erforderlich für die SSO-Anmeldung und -Authentifizierung für unseren Server | 7cb50e3e-0427-409e-90d2-638eb28217c3 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| So benachrichtigen Sie den Benutzer in einem Kanal, dass er einen Hi5 erhalten hat | Es werden keine Informationen gespeichert, der Benutzer wird nur von der karte @ angezeigt, die im Kanal zurückgeschickt wird. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Nein, Hi5 ist lediglich iFramed in und alle Daten werden sicher gespeichert.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir verwenden OAuth und stellen 3 Anmeldeoptionen zur Verfügung:
- Googles SSO (OAuth).
- Microsoft SSO (OAuth).
- Unsere eigene Verschlüsselung, die eine Kombination aus SHA- und AES-Verschlüsselung ist.
Nachdem Sie sich authentifiziert und angemeldet haben, gewährt Ihnen Ihre Berechtigungsstufe Zugriff auf autorisierte Abschnitte innerhalb der Hi5-Plattform.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

