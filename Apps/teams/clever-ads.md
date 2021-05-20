---
title: Anwendungsinformationen für Clever Ads by Clever Ads
ms.author: elmalova
author: elenamalova
ms.date: 04/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Clever Ads, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 0b092ef8ab27bec0a2f5c3bf294b301a71d1649a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552276"
---
# <a name="clever-ads"></a>Clever Ads

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 24. April 2020</p>

* <a href="https://teams.microsoft.com/l/app/ac2b56c0-f2a5-4e90-b618-882f8d3596f0" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001182" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Clever Ads an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Clever Ads |
| ID | WA200001182 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Clever Ads |
| URL der Partnerwebsite | [https://www.cleverads.com/](https://www.cleverads.com/) |
| URL der Datenschutzrichtlinie | [https://www.cleverads.com/privacy-policy](https://www.cleverads.com/privacy-policy) |
| URL der Nutzungsbedingungen | [https://www.cleverads.com/terms-conditions](https://www.cleverads.com/terms-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Clever Ads bereitgestellt, um zu erfahren, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegierte | User.Read: Wir speichern UPN, AzureObjectId, um den Benutzer zu identifizieren. | User.Read ermöglicht dem Benutzer die Anmeldung bei unserem App-Dashboard. Wir verwenden UPN, AzureObjectId zum Anmelden des Benutzers. | ac2b56c0-f2a5-4e90-b618-882f8d3596f0 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Die App zugrifft auf die Liste, um zu ermitteln, ob ein Benutzer zum Team gehört oder nicht, und nachrichten, die vom Benutzer an seine Teams geplant wurden. | Wir speichern die Benutzer-ID, azureObjectId, UPN, tenantId, conversationId und serviceUrl, damit wir Nachrichten an den Benutzer oder das Team senden und ihn identifizieren können, wenn wir auf die Dashboardregisterkarte zugreifen. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir speichern keine Organisatorischen Informationen in unseren Telemetrie- oder Protokollen. Wir protokollieren einfach Benutzeraktionen, z. B. das Senden einer Nachricht an den Bot oder das Klicken auf eine Schaltfläche, auch in diesen Protokollen ist die ID des Benutzers unsere interne Benutzer-ID, die nicht mit der microsoft teams-ID verknüpft ist.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Anwendungsdaten werden in einer in der Google Cloud gehosteten MySQL-Datenbank gespeichert, das Sicherungssystem wird für unsere Datenbanken hinzugefügt und sie werden mithilfe von PMA und geschützten IPs verarbeitet.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35867' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35867" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

