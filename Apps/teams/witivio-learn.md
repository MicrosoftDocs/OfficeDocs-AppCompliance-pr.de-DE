---
title: Anwendungsinformationen für Learn by Witivio
ms.author: elmalova
author: elenamalova
ms.date: 03/31/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Learn, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: acb0b07f25bc3fa2e86246a061ff73d3152b9810
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550855"
---
# <a name="learn"></a>Informationen

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 31. März 2020</p>

* <a href="https://teams.microsoft.com/l/app/2d96b540-aa26-431b-bc31-222321c762e3" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001308" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Witivio an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Informationen |
| ID | WA200001308 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Witivio |
| URL der Partnerwebsite | [https://www.witivio.com/learn](https://www.witivio.com/learn) |
| URL der Datenschutzrichtlinie | [https://www.witivio.com/en/privacy](https://www.witivio.com/en/privacy) |
| URL der Nutzungsbedingungen | [https://witivio.com/en/terms-of-use](https://witivio.com/en/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Witivio darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegierte | Nicht zutreffend | Wir erfassen den UPN und die AAD-ID für die Autorisierung. | 8c5c0060-2892-4355-b0db-661f206028a9 |
>| User.ReadBasic.All | delegierte | Nicht zutreffend | Wir erfassen den UPN und die AAD-ID für die Autorisierung. | 8c5c0060-2892-4355-b0db-661f206028a9 |
>| openid | delegierte | Nicht zutreffend | Wir erfassen den UPN und die AAD-ID für die Autorisierung. | 8c5c0060-2892-4355-b0db-661f206028a9 |
>| Profil | delegierte | Nicht zutreffend | Wir erfassen den UPN und die AAD-ID für die Autorisierung. | 8c5c0060-2892-4355-b0db-661f206028a9 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Wir verwenden den Dienstplan für: 1) Autorisierung (Gewähren von Zugriff auf den Bot), 2) Erkennen des Vornamens, um eine benutzerfreundliche UX zur Verfügung zu stellen, 3) Zum Verwalten der Chatlogs für den Geschäftsadministrator des Bots | N/A. Oder Bots ist nur persönlich |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Die Telemetrie des Bots enthält den UPN und die AAD-ID fr-Diagnose.
Nur PROD/Run-Administratoren haben Zugriff auf die Produktionstelemetrie. Die Protokolle werden 90 Tage lang gespeichert und können auf Anfrage auf einem dedizierten Portal gelöscht support.witivio.com oder per E-Mail an dpo@witivio.com

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Witivio verwendet nur Azure-Komponenten, die in der Region "Nordeuropa" bereitgestellt werden. Wir verwenden Anwendungsinblicke und Cosmos DB für Datenanalyse und -speicherung.
Witivio verwenden MFA für alle Benutzer, einschließlich Administratoren. Administratoren verfügen über ein Benutzerkonto (für Die Arbeitsstation) und ein privilegiertes Konto für den Zugriff auf Azure-Ressourcen.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

