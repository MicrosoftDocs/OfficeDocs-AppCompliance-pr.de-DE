---
title: Anwendungsinformationen für DBit von Diamondsoft Solutions, LLC
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für DBit, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 23995f613c3c3b6d7b2ab7d161f8710ccddf07d0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553956"
---
# <a name="dbit"></a>DBit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 23. Juni 2020</p>

* <a href="https://teams.microsoft.com/l/app/b28bb657-8edd-47ae-a912-c5fc11b3e89e" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001536" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen von Diamondsoft Solutions, LLC an Microsoft:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | DBit |
| ID | WA200001536 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Diamondsoft Solutions, LLC |
| URL der Partner-Website | [https://www.dbit.io/index.html](https://www.dbit.io/index.html) |
| URL der Datenschutzrichtlinie | [https://www.dbit.io/privacypolicy.html](https://www.dbit.io/privacypolicy.html) |
| URL der Nutzungsbedingungen | [https://www.dbit.io/termsofuse.html](https://www.dbit.io/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Diamondsoft Solutions, LLC darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegiert | Wir speichern Graph Informationen nicht in unserem System oder in Datenbanken. | Anmelden und Benutzerprofil lesen | 1533d702-7604-463a-9fa3-63077c425e76 |
>| email | Delegiert | Wir speichern Graph Informationen nicht in unserem System oder in Datenbanken. | E-Mail-Adresse von Benutzern anzeigen | 1533d702-7604-463a-9fa3-63077c425e76 |
>| offline_access | Delegiert | Wir speichern Graph Informationen nicht in unserem System oder in Datenbanken. | Den Zugriff auf Daten beibehalten, auf die Sie ihr Zugriff gewährt haben | 1533d702-7604-463a-9fa3-63077c425e76 |
>| openid | Delegiert | Wir speichern Graph Informationen nicht in unserem System oder in Datenbanken. | Benutzer anmelden | 1533d702-7604-463a-9fa3-63077c425e76 |
>| Profil | Delegiert | Wir speichern Graph Informationen nicht in unserem System oder in Datenbanken. | Grundlegendes Profil von Benutzern anzeigen | 1533d702-7604-463a-9fa3-63077c425e76 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| So erstellen Sie eine Willkommensnachricht | Wir speichern keine Dienstplaninformationen in unserem System oder in Datenbanken. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Wir erfassen diese Informationen nicht.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Wir verwenden Azure Cache Redis, die maximale Lebensdauer von Daten im Cache beträgt 300 Minuten. Die Cachedatenelemente werden mit AES256 verschlüsselt. Nur der App-Dienst kann über SSL eine Verbindung mit Azure Cache Redis herstellen, die Verbindungszeichenfolge wird in Azure Environmental Variable gespeichert.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35912' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35912" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

