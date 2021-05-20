---
title: Anwendungsinformationen für AtBot by H3 Solutions, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für AtBot, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
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

* <a href="https://teams.microsoft.com/l/app/7c01af81-ae7d-416e-98a3-c139cae8cfb0" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381219" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von H3 Solutions, Inc. an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | AtBot |
| ID | WA104381219 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | H3 Solutions, Inc. |
| URL der Partnerwebsite | [https://atbot.io](https://atbot.io) |
| URL Teams Anwendungsinfoseite | [https://admin.atbot.io/Docs/GettingStarted](https://admin.atbot.io/Docs/GettingStarted) |
| URL der Datenschutzrichtlinie | [https://admin.atbot.io/privacy](https://admin.atbot.io/privacy) |
| URL der Nutzungsbedingungen | [https://admin.atbot.io/terms](https://admin.atbot.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von H3 Solutions, Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | Anwendung | AAD-Gruppenname, AAD-Gruppen-GUID, UPN | Aufzählen von AAD-Gruppen, um eine Sicherheitskür der Bot-Fähigkeiten zu ermöglichen. Aufzählen von Benutzern, um Lizenzen anwenden zu können. Aufzählen von Benutzern, die als Administratoren/Mitwirkende hinzugefügt werden | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| Directory.Read.All | delegierte | AAD-Gruppenname, AAD-Gruppen-GUID, UPN | Aufzählen von AAD-Gruppen, um eine Sicherheitskür der Bot-Fähigkeiten zu ermöglichen. Aufzählen von Benutzern, um Lizenzen anwenden zu können. Aufzählen von Benutzern, die als Administratoren/Mitwirkende hinzugefügt werden | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| People.Read | delegierte | Nein | Enumerate people in a Get Person action from Flow.  Ermöglicht dem Bot das Abrufen von Personen vom /People-Endpunkt in Microsoft Graph. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| User.Read | delegierte | Mandanten-ID, UPN | Ermöglicht uns den Zugriff auf&#8217;Mandanten-ID und UPN, damit wir flows/Logic Apps, die erstellt wurden, an die Benutzer binden können, die sie erstellt haben. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| email | delegierte | Nein | Ermöglicht uns den Zugriff auf die E-Mail-Adresse des Benutzers. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| offline_access | delegierte | Zugriffs-/Aktualisierungstoken. | Ermöglicht es uns, ein Aktualisierungstoken zu verwenden, um Benutzer angemeldet zu halten. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| openid | delegierte | Nein | Ermöglicht Benutzern die Anmeldung. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| Profil | delegierte | UPN | Zugriff auf den UPN des Benutzers. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Erstellen von Erwähnungen in botgenerierten Chatnachrichten | Nein |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Mandanten-ID, UPN Wir verwenden Application Insights, und unsere Protokolle dauern 90 Tage, bevor sie automatisch archiviert werden. (https://docs.microsoft.com/azure/azure-monitor/app/data-retention-privacy)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Administratoren können Botkonfigurationen löschen, die AAD-Gruppennamen/GUIDs enthalten können.
Nach dem Abbruch des Diensts werden alle UPNs aus der Lizenzierungsdatenbank entfernt.
Weitere Informationen finden Sie unter "Azure Services" unter Data Residency.  Ein Teil der kundenspezifischen Daten, die über die Verwendung von AtBot erzeugt werden, werden im Mandanten des Kunden gespeichert, sodass Administratoren dieses Mandanten die vollständige Kontrolle über die Daten dort haben.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

