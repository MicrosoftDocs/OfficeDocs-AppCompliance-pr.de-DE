---
title: Anwendungsinformationen für AtBot von H3 Solutions, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für AtBot, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3f56d0b3eb19f5bed8f7092507c8605af936b911
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552136"
---
# <a name="atbot"></a>AtBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://teams.microsoft.com/l/app/7c01af81-ae7d-416e-98a3-c139cae8cfb0" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381219" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die H3 Solutions, Inc. Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | AtBot |
| ID | WA104381219 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | H3 Solutions, Inc. |
| URL der Partner-Website | [https://atbot.io](https://atbot.io) |
| URL Teams Anwendungsinfoseite | [https://admin.atbot.io/Docs/GettingStarted](https://admin.atbot.io/Docs/GettingStarted) |
| URL der Datenschutzrichtlinie | [https://admin.atbot.io/privacy](https://admin.atbot.io/privacy) |
| URL der Nutzungsbedingungen | [https://admin.atbot.io/terms](https://admin.atbot.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von H3 Solutions, Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | Anwendung | AAD-Gruppenname, AAD-Gruppen-GUID, UPN | Aufzählen von AAD-Gruppen, um das Sicherheitstrimmen von Bot-Fähigkeiten zu ermöglichen. Aufzählen von Benutzern, um Lizenzen anwenden zu können. Aufzählen von Benutzern, die als Administratoren/Mitwirkende hinzugefügt werden sollen | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| Directory.Read.All | Delegiert | AAD-Gruppenname, AAD-Gruppen-GUID, UPN | Aufzählen von AAD-Gruppen, um das Sicherheitstrimmen von Bot-Fähigkeiten zu ermöglichen. Aufzählen von Benutzern, um Lizenzen anwenden zu können. Aufzählen von Benutzern, die als Administratoren/Mitwirkende hinzugefügt werden sollen | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| People.Read | Delegiert | Nein | Aufzählen von Personen in einer Get Person-Aktion aus Flow.  Ermöglicht dem Bot, Personen vom /People-Endpunkt in Microsoft Graph abzurufen. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| User.Read | Delegiert | Mandanten-ID, UPN | Ermöglicht uns zugriff auf den Benutzer&#8217;Mandanten-ID und UPN, damit wir Flows/Logic Apps, die an die Benutzer erstellt wurden, die sie erstellt haben, binden können. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| email | Delegiert | Nein | Ermöglicht uns den Zugriff auf die E-Mail-Adresse des Benutzers. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| offline_access | Delegiert | Zugriffs-/Aktualisierungstoken. | Ermöglicht es uns, ein Aktualisierungstoken zu verwenden, um Benutzer angemeldet zu halten. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| openid | Delegiert | Nein | Ermöglicht Benutzern die Anmeldung. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| Profil | Delegiert | UPN | Zugriff auf den UPN des Benutzers. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Die Erstellung von Erwähnungen in botgenerierten Chat-Nachrichten | Nein |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Mandanten-ID, UPN Wir verwenden Application Insights und unsere Protokolle dauern 90 Tage, bevor sie automatisch archiviert werden. (https://docs.microsoft.com/azure/azure-monitor/app/data-retention-privacy)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Administratoren haben die Möglichkeit, Bot-Konfigurationen zu löschen, die AAD-Gruppennamen/GUIDs enthalten können.
Nach Dem widerrufenen Dienst werden alle UPNs aus der Lizenzdatenbank entfernt.
Weitere Informationen finden Sie unter "Azure Services" unter Data Residency.  Ein Großteil der kundenspezifischen Daten, die durch die Verwendung von AtBot erzeugt werden, wird im Mandanten des Kunden gespeichert, so dass die Administratoren dieses Mandanten die volle Kontrolle über die daten dort haben.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

