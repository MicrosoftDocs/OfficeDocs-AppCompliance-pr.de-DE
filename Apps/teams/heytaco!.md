---
title: Anwendungsinformationen für HeyTaco! von HeyTaco!
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für HeyTaco!, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 66739977ba4aa3eef7456d4ec60530f94065a2b9
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553126"
---
# <a name="heytaco"></a>HeyTaco!

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 3. November 2020</p>

* <a href="https://teams.microsoft.com/l/app/be8d11cf-265a-4974-9912-4ff28c29fc21" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001346" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen zur Verfügung gestellt von HeyTaco! zu Microsoft:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | HeyTaco! |
| ID | WA200001346 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | HeyTaco! |
| URL der Partner-Website | [https://www.heytaco.chat](https://www.heytaco.chat) |
| URL der Datenschutzrichtlinie | [https://www.heytaco.chat/privacy](https://www.heytaco.chat/privacy) |
| URL der Nutzungsbedingungen | [https://www.heytaco.chat/terms](https://www.heytaco.chat/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von HeyTaco zur Verfügung gestellt! darüber, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| email | Delegiert | verwendet, um Benutzer für Datenübertragungen von Slack zu MS Teams | verwendet, um Benutzer für Datenübertragungen von Slack zu MS Team abzugleichen | be8d11cf-265a-4974-9912-4ff28c29fc21 |
>| openid | Delegiert | verwendet, um Person bei HeyTaco anmelden! | verwendet, um Person bei HeyTaco anmelden! | be8d11cf-265a-4974-9912-4ff28c29fc21 |
>| Profil | Delegiert | verwendet, um Benutzernamen, Profilbild, Zeitzonenversatz, Mandanten-ID und Team-ID zu erfassen | verwendet, um Benutzernamen, Avatar, Timezone-Offset, Mandanten-ID und Team-ID zu erfassen | be8d11cf-265a-4974-9912-4ff28c29fc21 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Um dem Benutzer zu sagen, dass er einen Taco erhalten hat und von wem er stammt. | E-Mail-Adresse (für Migrations-Tacos von einer Plattform zur anderen) Name (zur Begrüßung des Benutzers) Profilbild (für die Anzeige auf der Bestenliste) Timezone (um Tacos auf der Aktivitätsseite korrekt anzuzeigen) Mandanten-ID (zum Aggregieren von Daten nach Mandanten) Team-ID (zum Aggregieren von Daten nach Team)  |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>EUII und OII sind nicht mit einem Holzeinschlag verbunden. Nur Fehlertypen und Aktionstypen.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>HeyTaco! Datenbanken und Datensicherungen werden auf Amazon Web Services (AWS) gehostet. 

Amazons Rechenzentrumsbetrieb wurde nach ISO 27001 , SOC 1 und SOC 2/SSAE 16/ISAE 3402 (früher SAS 70 Type II ), PCI Level 1 , FISMA Moderate und Sarbanes-Oxley (SOX) akkreditiert.

Wenn Sie Informationen über unseren Dienst übermitteln, werden Ihre Informationen sowohl im Ruhezustand als auch während der Übertragung durch sichere Verbindungen geschützt und verschlüsselt. Wir implementieren eine Vielzahl von Sicherheitsmaßnahmen, um die Sicherheit Ihrer personenbezogenen Daten zu gewährleisten.

Wir verfügen über Privileged Access Management, um Daten auf unseren Servern zu schützen.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

