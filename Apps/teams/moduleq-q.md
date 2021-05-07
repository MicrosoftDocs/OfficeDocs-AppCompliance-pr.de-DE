---
title: Anwendungsinformationen für F nach ModulQ
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: 'Alle verfügbaren Sicherheits- und Complianceinformationen für F, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security Informationen zum #A0 sowie Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.'
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2821009fea219a32a935dba7043d5ba0a48b826c
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252405"
---
# <a name="q"></a>Q

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 17. März 2020</p>

* <a href="https://teams.microsoft.com/l/app/72bb25c7-3644-4318-8249-a08e5493a520" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381433" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von ModuleQ an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Q |
| ID | WA104381433 |
| Funktionen | Bot, Registerkarte |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | ModuleQ |
| URL der Partnerwebsite | [https://moduleq.com](https://moduleq.com) |
| URL der Datenschutzrichtlinie | [https://moduleq.com/privacy-policy/](https://moduleq.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://moduleq.com/terms-of-service/](https://moduleq.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von ModuleQ bereitgestellt, um zu erfahren, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | Anwendung | Speichert Besprechungsdaten, mit Ausnahme des Nachrichtentexts und der Anlagen | Ermöglicht der Anwendung das Lesen der Kalenderereignisse eines Benutzers, um die geschäftlichen Prioritäten des Benutzers intelligent zu verstehen. | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Group.Read.All | delegierte | Keine | Ermöglicht der App die Interaktion in einem Team für die Freigabe von Inhalten. | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Mail.Read | Anwendung | Speichert E-Mail-Daten, mit Ausnahme des Nachrichtentexts und der Anlagen | Ermöglicht der Anwendung das Lesen der E-Mails eines Benutzers, um die Geschäftlichen Prioritäten des Benutzers intelligent zu verstehen. | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read | delegierte | Benutzer-E-Mail- und Authentifizierungstoken | Ermöglicht es dem Benutzer, sich zu anmelden und sein Office 365 mit seinem ModuleQ-Konto zu verknüpfen. | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read.All | delegierte | Keine | Erlauben Sie der App, die Liste der Teams, zu denen der Benutzer gehört, zu erhalten. Nur für die Freigabe verwendet  | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Auf EUII wird nicht zugegriffen.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir protokollieren eine interne Benutzer-GUID sowie Organisationsnamen und Domänen. Derzeit gibt es keine Archiv- oder Löschsteuerelemente.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Daten werden in der Microsoft Azure in mehreren Mikrodiensten gemäß ihrer Funktion gespeichert. Alle benutzeridentifizierbaren Daten werden clientseitig mit der AES-256-Verschlüsselung verschlüsselt, bevor sie für den Speicher übertragen werden. Daten können von Technikern zu Debuggingzwecken mit Genehmigung durch unsere Geschäftsleitung angezeigt werden. Der Zugriff auf Daten wird über ein internes VPN gesteuert.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

