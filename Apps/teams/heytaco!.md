---
title: Anwendungsinformationen für HeyTaco! von HeyTaco!
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
description: Alle verfügbaren Sicherheits- und Complianceinformationen für HeyTaco!, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 08b99f83abb4031719759544622437004b9aa56c
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095104"
---
# <a name="heytaco"></a>HeyTaco!

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 3. November 2020</p>

* <a href="https://teams.microsoft.com/l/app/be8d11cf-265a-4974-9912-4ff28c29fc21" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001346" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von HeyTaco bereitgestellte Informationen! an Microsoft:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | HeyTaco! |
| ID | WA200001346 |
| Funktionen | Bot, Registerkarte |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | HeyTaco! |
| URL der Partnerwebsite | [https://www.heytaco.chat](https://www.heytaco.chat) |
| URL der Datenschutzrichtlinie | [https://www.heytaco.chat/privacy](https://www.heytaco.chat/privacy) |
| URL der Nutzungsbedingungen | [https://www.heytaco.chat/terms](https://www.heytaco.chat/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von HeyTaco bereitgestellt! Informationen dazu, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| email | delegierte | wird verwendet, um Benutzer für Datenübertragungen von Slack zu MS zu Teams | Wird verwendet, um Benutzer für Datenübertragungen von Slack zu MS Team zu matchen | be8d11cf-265a-4974-9912-4ff28c29fc21 |
>| openid | delegierte | wird verwendet, um eine Person bei HeyTaco zu signieren! | wird verwendet, um eine Person bei HeyTaco zu signieren! | be8d11cf-265a-4974-9912-4ff28c29fc21 |
>| Profil | delegierte | Wird zum Erfassen von Benutzername, Profilbild, Zeitzonenversatz, Mandanten-ID und Team-ID verwendet | Wird verwendet, um Benutzernamen, Avatare, Zeitzonenversatz, Mandanten-ID und Team-ID zu erfassen. | be8d11cf-265a-4974-9912-4ff28c29fc21 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Um dem Benutzer zu sagen, dass er ein Taco erhalten hat und von wem es kommt. | E-Mail-Adresse (für Migrations-Tacos von einer Plattform zu einer anderen) Name (zur Begrüßung des Benutzers) Profilbild (zur Anzeige auf der Bestenliste) Zeitzone (zum ordnungsgemäßen Anzeigen von auf der Aktivitätsseite angegebenen Tacos) Mandanten-ID (Zum Aggregieren von Daten nach Mandanten) Team-ID (Zum Aggregieren von Daten nach Team)  |  |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>EUII und OII sind nicht mit einer Protokollierung verbunden. Nur Fehlertypen und Aktionstypen.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>HeyTaco! Datenbanken und Datensicherungen werden auf Amazon Web Services (AWS) gehostet. 

Die Rechenzentrumsvorgänge von Amazon wurden unter ISO 27001, SOC 1 und SOC 2/SSAE 16/ISAE 3402 (zuvor SAS 70 Typ II), PCI Level 1, FISMA Moderate und Sarbanes-Oxley (SOX) akkreditiert.

Wenn Sie Informationen über unseren Dienst übermitteln, werden Ihre Informationen sowohl im Ruhedienst als auch während der Übertragung durch sichere Verbindungen geschützt und verschlüsselt. Wir implementieren eine Vielzahl von Sicherheitsmaßnahmen, um die Sicherheit Ihrer persönlichen Informationen zu gewährleisten.

Wir verfügen über privileged Access Management, um Daten auf unseren Servern zu schützen.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

