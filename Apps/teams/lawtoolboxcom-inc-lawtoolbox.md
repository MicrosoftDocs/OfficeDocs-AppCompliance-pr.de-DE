---
title: Anwendungsinformationen für LawToolBox von LawToolBox.com Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Alle verfügbaren Sicherheits- und Complianceinformationen für LawToolBox, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f738fb665687934f677d0bc3a5105e41831106ac
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/30/2021
ms.locfileid: "52093381"
---
# <a name="lawtoolbox"></a>LawToolBox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://teams.microsoft.com/l/app/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381656" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von LawToolBox.com Inc. an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | LawToolBox |
| ID | WA104381656 |
| Funktionen | Bot, Registerkarte, Messaging-Erweiterung |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | LawToolBox.com Inc. |
| URL der Partnerwebsite | [https://www.lawtoolbox.com](https://www.lawtoolbox.com) |
| URL Teams Anwendungsinfoseite | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718) |
| URL der Datenschutzrichtlinie | [https://www.lawtoolbox.com/privacy-policy/](https://www.lawtoolbox.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von LawToolBox.com Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | delegierte |  | [Optional] Lesen des Kalenders des Benutzers. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Calendars.ReadWrite | delegierte |  | So erstellen Sie Kalender einladen in den Kalender des Benutzers. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Calendars.ReadWrite.Shared | delegierte |  | So erstellen Sie kalender einladen in freigegebenen Kalender. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Contacts.ReadWrite | delegierte |  | [Optional]- zum Lesen von Benutzerkontakten und Verbinden von Benutzern von Kontaktliste zu Gruppe. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Contacts.ReadWrite.Shared | delegierte |  | [Optional]- zum Lesen freigegebener Kontakte für Benutzer, um die Liste der für den Fall relevanten Kontakte zu bedienen. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Directory.AccessAsUser.All | delegierte |  | [Optional] Lesen Sie Gruppen- und Benutzerinformationen als Benutzer. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Directory.ReadWrite.All | delegierte |  | [Optional] Lesen Sie Gruppen- und Benutzerinformationen als Benutzer. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.Read | delegierte |  | [Optional] Lesen der Benutzerinformationen OneDrive. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.Read.All | delegierte |  | [Optional]-Benutzerinformationen OneDrive. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.ReadWrite | delegierte |  | [Optional]-Lesen und Ändern von Dateien in der OneDrive. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.ReadWrite.All | delegierte |  | [Optional] Lese-/Schreibzugriff auf die OneDrive, die der Matter zugeordnet ist. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Group.ReadWrite.All | delegierte | GroupID, GroupName, GroupEmail | Wir erstellen eine Gruppe für jede in unserem System erstellte Angelegenheit. Dies hilft dem Benutzer, informationen im Zusammenhang mit Der Sache in der Gruppe zu speichern, die wiederum ihre Daten in ihrem eigenen Mandanten speichert. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.Read | delegierte |  | [Optional] [InProgress] Lesen Der E-Mail-Adresse des Benutzers für Dinge. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.ReadWrite | delegierte |  | [Optional] [InProgress] Lese-/Schreibzugriff für Benutzer. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.ReadWrite.Shared | delegierte |  | [Optional] [InProgress] Lese-/Schreibzugriff für Benutzer. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.Send | delegierte |  | [Optional] [InProgress] Sendetermine für E-Mails als Benutzer. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Tasks.ReadWrite.Shared | delegierte |  | [Optional]-[InProgress] Read Write Deadlines as Task for users. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.Read | delegierte |  | Lesen der Informationen des Benutzers. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.ReadWrite | delegierte |  | Benutzerinformationen mit Lese-/Schreibzugriff. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.ReadWrite.All | delegierte |  | Benutzerinformationen mit Lese-/Schreibzugriff. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| email | delegierte | E-Mail, Office365 UserID, ObjectID, TenantID. | Lesen der E-Mail-Adresse des Benutzers. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Profil | delegierte |  | Benutzerprofilinformationen lesen. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| So identifizieren Sie den neu hinzugefügten Benutzer im Team und suchen nach einem potenziellen Vorsprung | E-Mail, UserId |  |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Benutzer-E-Mail,UserID, AccessToken, Gruppeninformationen in unserem Debugprotokoll

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir behalten Falldatensätze bei, es sei denn, wir erhalten eine Anforderung zum Löschen der Daten.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

