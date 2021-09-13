---
title: Anwendungsinformationen für Learn von Witivio
ms.author: elmalova
author: elenamalova
ms.date: 03/31/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Learn, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f931e75f0a5736ffa49c7366d9928db774c4bdbf
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/12/2021
ms.locfileid: "59283805"
---
# <a name="learn"></a>Informationen

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 31. März 2020</p>

* <a href="https://teams.microsoft.com/l/app/2d96b540-aa26-431b-bc31-222321c762e3" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001308" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Witivio für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Informationen |
| ID | WA200001308 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Witivio |
| URL der Partnerwebsite | [https://www.witivio.com](https://www.witivio.com) |
| URL der Datenschutzrichtlinie | [https://www.witivio.com/en/privacy](https://www.witivio.com/en/privacy) |
| URL der Nutzungsbedingungen | [https://witivio.com/en/terms-of-use](https://witivio.com/en/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Witivio darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | Delegiert | Nicht zutreffend | Wir erfassen den UPN und die AAD-ID für die Autorisierung. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |
>| User.ReadBasic.All | Delegiert | Nicht zutreffend | Wir erfassen den UPN und die AAD-ID für die Autorisierung. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |
>| openid | Delegiert | Nicht zutreffend | Wir erfassen den UPN und die AAD-ID für die Autorisierung. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |
>| Profil | Delegiert | Nicht zutreffend | Wir erfassen den UPN und die AAD-ID für die Autorisierung. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Wir verwenden die Liste für: 1) Autorisierung (Zugriff auf den Bot gewähren), 2) den Vornamen erkennen, um eine benutzerfreundliche UX bereitzustellen, 3) Um die Chatlogs für den Geschäftsadministrator des Bots zu verwalten | Nicht verfügbar. Oder Bots sind nur persönlich |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Die Telemetrie des Bots enthält den UPN und die AAD-ID fr-Diagnose.
Nur PROD/Run-Administratoren haben Zugriff auf die Produktionstelemetrie. Die Protokolle werden 90 Tage lang gespeichert und können auf Anforderung in einem dedizierten Portal support.witivio.com oder per E-Mail an dpo@witivio.com

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Witivio verwendet nur Azure-Komponenten, die in der Region Nordeuropa bereitgestellt werden. Wir verwenden Anwendungsinblicke und Cosmos DB für Datenanalyse und -speicherung.
Witivio verwendet MFA für alle Benutzer, einschließlich Administratoren. Administratoren verfügen über ein Benutzerkonto (für Arbeitsstation) und ein privilegiertes Konto für den Zugriff auf Azure-Ressourcen.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

