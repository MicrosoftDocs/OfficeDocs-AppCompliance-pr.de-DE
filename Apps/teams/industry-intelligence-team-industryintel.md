---
title: Anwendungsinformationen für IndustryIntel nach Industry Intelligence Team
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für IndustryIntel, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6e2c1c35d0054df773b83fa2d31a95daceaee585
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553066"
---
# <a name="industryintel"></a>IndustryIntel

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 3. November 2020</p>

* <a href="https://teams.microsoft.com/l/app/beb2be89-a403-46fe-9a67-c1294c9f9740" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001907" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die vom Industry Intelligence Team an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | IndustryIntel |
| ID | WA200001907 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Industry Intelligence Team |
| URL der Partnerwebsite | [https://www.industryintel.com/public:about-us/our-team](https://www.industryintel.com/public:about-us/our-team) |
| URL der Datenschutzrichtlinie | [https://www.industryintel.com/public:legal/privacy-policy-m...](https://www.industryintel.com/public:legal/privacy-policy-msteams) |
| URL der Nutzungsbedingungen | [https://www.industryintel.com/public:legal/terms-of-use](https://www.industryintel.com/public:legal/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden vom Industry Intelligence Team darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>Diese Anwendung verwendet keine Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| So überprüfen Sie den Benutzer, ob der Benutzer Zugriff auf das Industry Intelligence-Netzwerk hat. Wenn der Benutzer erfolgreich überprüft wurde, kann der Benutzer die vollständige Funktion von Bot und Messaging Extension verwenden. | Wir haben nur die Teammitglied-ID gespeichert, die zum Zuordnen der ID w/ Industry Intelligence/internal user id verwendet wird. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Nein. Die Zuordnung des ms-Teams und des so-Teams erfolgt im So-Teams-Produkt. MS Teams sendet uns ihre identifizierbaren IDs, und wir speichern diese intern, um den Benutzer zu zuordnungen. Darüber hinaus sendet MS Teams eine JWT für Botanforderungen (verhindert Anforderungsfälschung) und Tab-Anforderungen überprüfen mithilfe des SO-Cookies.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Der Datenzugriff wird durch das IP-Bereichssystem geschützt und sicher authentifiziert. Daten werden logisch in ein eigenes SQL getrennt und in einer separaten Datenbank gespeichert. Ihre Daten werden in einem logisch separaten Datenspeicher gespeichert, auf den nur von Anforderungen für Ihr Team zugegriffen werden kann.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36080' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36080" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

