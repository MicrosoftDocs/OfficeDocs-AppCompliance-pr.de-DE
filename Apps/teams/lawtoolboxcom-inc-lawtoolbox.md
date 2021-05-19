---
title: Anwendungsinformationen für LawToolBox von LawToolBox.com Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für LawToolBox, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2e97d65822a5baeb0cd78101660084e4142e98ea
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553006"
---
# <a name="lawtoolbox"></a>LawToolBox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://teams.microsoft.com/l/app/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381656" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die LawToolBox.com Inc. Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | LawToolBox |
| ID | WA104381656 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | LawToolBox.com Inc. |
| URL der Partner-Website | [https://www.lawtoolbox.com](https://www.lawtoolbox.com) |
| URL Teams Anwendungsinfoseite | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718) |
| URL der Datenschutzrichtlinie | [https://www.lawtoolbox.com/privacy-policy/](https://www.lawtoolbox.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von LawToolBox.com Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | Delegiert |  | [Optional] Lesen Sie den Kalender des Benutzers. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Calendars.ReadWrite | Delegiert |  | So erstellen Sie Kalendereinladungen im Kalender des Benutzers. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Calendars.ReadWrite.Shared | Delegiert |  | So erstellen Sie Kalendereinladungen in freigegebenen Kalender. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Contacts.ReadWrite | Delegiert |  | [Optional]- benutzerbezogene Kontakte zu lesen und Benutzer von Kontaktliste zu Gruppe zu verbinden. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Contacts.ReadWrite.Shared | Delegiert |  | [Optional]- um Benutzer gemeinsame Kontakte zu lesen, um die Liste der Kontakte zu bedienen, die für die Anfrage relevant sind. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Directory.AccessAsUser.All | Delegiert |  | [Optional] Lesen Sie Gruppen- und Benutzerinformationen als Benutzer. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Directory.ReadWrite.All | Delegiert |  | [Optional] Lesen Sie Gruppen- und Benutzerinformationen als Benutzer. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.Read | Delegiert |  | [Optional] Lesen Sie die OneDrive des Benutzers. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.Read.All | Delegiert |  | [Optional]-Lesen Sie die OneDrive des Benutzers. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.ReadWrite | Delegiert |  | [Optional]-Lesen und Ändern von Dateien im OneDrive eines Benutzers. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.ReadWrite.All | Delegiert |  | [Optional] Lese-/Schreibbenutzer OneDrive Datei, die der Materie zugeordnet ist. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Group.ReadWrite.All | Delegiert | GroupID, GroupName, GroupEmail | Wir erstellen eine Gruppe für jede Angelegenheit, die in unserem System erstellt wird. Dies hilft dem Benutzer, relevante Informationen in der Gruppe zu speichern, die wiederum ihre Daten in ihrem eigenen Mandanten speichert. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.Read | Delegiert |  | [Optional] [InProgress] Lesen Sie die E-Mail des Benutzers für Angelegenheiten. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.ReadWrite | Delegiert |  | [Optional] [InProgress] Lese-/Schreib-E-Mails für Benutzer. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.ReadWrite.Shared | Delegiert |  | [Optional] [InProgress] Lese-/Schreib-E-Mails für Benutzer. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.Send | Delegiert |  | [Optional] [InProgress] Senden Sie Deadlines per E-Mail als Benutzer. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Tasks.ReadWrite.Shared | Delegiert |  | [Optional]-[InProgress] Schreibfristen als Aufgabe für Benutzer lesen. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.Read | Delegiert |  | Lesen Sie die Benutzerinformationen. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.ReadWrite | Delegiert |  | Informationen zum Lesen/Schreiben von Benutzern. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.ReadWrite.All | Delegiert |  | Informationen zum Lesen/Schreiben von Benutzern. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| email | Delegiert | E-Mail, Office365-Benutzerid, ObjectID, TenantID. | Lesen Sie die E-Mail-Adresse des Benutzers. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Profil | Delegiert |  | Lesen Sie Benutzerprofilinformationen. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| So identifizieren Sie den neu hinzugekommenen Benutzer im Team und suchen nach einem potenziellen Lead | E-Mail, UserId |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Benutzer-E-Mail,UserID, AccessToken, Gruppeninformationen in unserem Debug-Protokoll

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Wir speichern Fallaufzeichnungen, es sei denn, wir erhalten eine Aufforderung zur Löschung der Daten.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

