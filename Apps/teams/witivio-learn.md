---
title: Anwendungsinformationen für Learn von Witivio
ms.author: elmalova
author: elenamalova
ms.date: 03/31/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Informationen zu Sicherheits- und Complianceinformationen für Learn, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
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

* <a href="https://teams.microsoft.com/l/app/2d96b540-aa26-431b-bc31-222321c762e3" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001308" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Witivio Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Informationen |
| ID | WA200001308 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Witivio |
| URL der Partner-Website | [https://www.witivio.com/learn](https://www.witivio.com/learn) |
| URL der Datenschutzrichtlinie | [https://www.witivio.com/en/privacy](https://www.witivio.com/en/privacy) |
| URL der Nutzungsbedingungen | [https://witivio.com/en/terms-of-use](https://witivio.com/en/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Witivio darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegiert | Nicht zutreffend | Wir erheben die UPN und die AAD ID für die Autorisierung. | 8c5c0060-2892-4355-b0db-661f206028a9 |
>| User.ReadBasic.All | Delegiert | Nicht zutreffend | Wir erheben die UPN und die AAD ID für die Autorisierung. | 8c5c0060-2892-4355-b0db-661f206028a9 |
>| openid | Delegiert | Nicht zutreffend | Wir erheben die UPN und die AAD ID für die Autorisierung. | 8c5c0060-2892-4355-b0db-661f206028a9 |
>| Profil | Delegiert | Nicht zutreffend | Wir erheben die UPN und die AAD ID für die Autorisierung. | 8c5c0060-2892-4355-b0db-661f206028a9 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Wir verwenden den Dienstplan für: 1) Autorisierung (Zugriff auf den Bot gewähren), 2) den Vornamen erkennen, um eine freundliche UX bereitzustellen, 3) Um die Chatlogs für den Business-Administrator des Bots zu verwalten | N/A. Oder Bots sind nur persönlich |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Die Telemetrie des Bots enthält die UPN- und die AAD-ID-Diagnose.
Nur PROD/Run-Administratoren haben Zugriff auf die Produktionstelemetrie. Die Protokolle werden 90 Tage lang gespeichert und können auf Wunsch auf einem speziellen Portal support.witivio.com oder per E-Mail an dpo@witivio.com

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Witivio verwendet nur Azure-Komponenten, die in der Region "Nordeuropa" bereitgestellt werden. Wir verwenden Anwendungseinblicke und Cosmos DB für Datenanalysen und -speicherung.
Witivio verwendet MFA für alle Benutzer, einschließlich Administratoren. Administratoren verfügen über ein Benutzerkonto (für Arbeitsstation) und ein privilegiertes Konto für den Zugriff auf Azure-Ressourcen.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

