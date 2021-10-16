---
title: Anwendungsinformationen für HeyTaco! von HeyTaco!
ms.author: elmalova
author: elenamalova
ms.date: 09/09/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für HeyTaco!, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: e52056b40599ab98a69a6a93e7b2187ddf5f3765
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412374"
---
# <a name="heytaco"></a>HeyTaco!

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/be8d11cf-265a-4974-9912-4ff28c29fc21" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001346" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen von HeyTaco! an Microsoft:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | HeyTaco! |
| ID | WA200001346 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | HeyTaco! |
| URL der Partnerwebsite | [https://www.heytaco.chat](https://www.heytaco.chat) |
| URL der Datenschutzrichtlinie | [https://www.heytaco.chat/privacy](https://www.heytaco.chat/privacy) |
| URL der Nutzungsbedingungen | [https://www.heytaco.chat/terms](https://www.heytaco.chat/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von HeyTaco bereitgestellt! Darüber, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | Delegiert | wird verwendet, um den Benutzer für Datenübertragungen von Slack an MS-Teams | wird verwendet, um den Benutzer für Datenübertragungen von Slack an MS Team zuzuordnen | [be8d11cf-265a-4974-9912-4ff28c29fc21](https://docs.microsoft.com/microsoft-365-app-certification/azure/be8d11cf-265a-4974-9912-4ff28c29fc21) |
>| openid | Delegiert | wird verwendet, um eine Person bei HeyTaco anzumelden! | wird verwendet, um eine Person bei HeyTaco anzumelden! | [be8d11cf-265a-4974-9912-4ff28c29fc21](https://docs.microsoft.com/microsoft-365-app-certification/azure/be8d11cf-265a-4974-9912-4ff28c29fc21) |
>| Profil | Delegiert | Wird verwendet, um Benutzernamen, Profilbild, Zeitzonenversatz, Mandanten-ID und Team-ID zu erfassen. | Wird verwendet, um Benutzernamen, Avatare, Zeitzonenversatz, Mandanten-ID und Team-ID zu erfassen. | [be8d11cf-265a-4974-9912-4ff28c29fc21](https://docs.microsoft.com/microsoft-365-app-certification/azure/be8d11cf-265a-4974-9912-4ff28c29fc21) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Um dem Benutzer mitzuteilen, dass er einen Taco erhalten hat und von wem er stammt. | E-Mail-Adresse (für Migrations-Tasos von einer Plattform zu einer anderen) Name (zur Begrüßung des Benutzers) Profilbild (zur Anzeige in der Bestenliste) Zeitzone (zum ordnungsgemäßen Anzeigen der auf der Aktivitätsseite angegebenen Taktos) Mandanten-ID (Zum Aggregieren von Daten nach Mandant) Team-ID (zum Aggregieren von Daten nach Team)  |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>EUII und OII sind mit keiner Protokollierung verbunden. Nur Fehlertypen und Aktionstypen.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>HeyTaco! Datenbanken und Datensicherungen werden auf Amazon Web Services (AWS) gehostet. 

Die Rechenzentrumsvorgänge von Amazon wurden gemäß ISO 27001, SOC 1 und SOC 2/SSAE 16/ISAE 3402 (zuvor SAS 70 Typ II), PCI Level 1, FISMA Moderate und Sarbanes-Oxley (SOX) akkreditiert.

Wenn Sie Informationen über unseren Dienst übermitteln, werden Ihre Informationen sowohl im Ruhezustand als auch während der Übertragung über sichere Verbindungen geschützt und verschlüsselt. Wir implementieren eine Vielzahl von Sicherheitsmaßnahmen, um die Sicherheit Ihrer persönlichen Informationen aufrechtzuerhalten.

Wir haben Privileged Access Management eingerichtet, um Daten auf unseren Servern zu schützen.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


