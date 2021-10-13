---
title: Application Information for LawToolBox Deadline &amp; Matter Management – Outlook von LawToolBox.com Inc.
ms.author: elmalova
author: elenamalova
ms.date: 10/07/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für LawToolBox Deadline &amp; Matter Management – Outlook, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: a68d1a5f726e097e8a22639ac15420fc801da3b4
ms.sourcegitcommit: 1d47df35430334cfc0c60f7ea0b62392b99b7cbf
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/13/2021
ms.locfileid: "60285979"
---
# <a name="lawtoolbox-deadlines-amp-matter-management---outlook"></a>LawToolBox Deadline &amp; Matter Management – Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: October 7, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104120953" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von LawToolBox.com Inc. an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | LawToolBox Deadline &amp; Matter Management – Outlook |
| ID | WA104120953 |
| Office 365 unterstützten Clients | Outlook 2013 oder höher auf Windows, Outlook 2016 oder höher auf Dem Mac Outlook im Web |
| Name des Partnerunternehmens | LawToolBox.com Inc. |
| URL der Partnerwebsite | [https://www.lawtoolbox.com](https://www.lawtoolbox.com) |
| URL der Datenschutzrichtlinie | [https://www.lawtoolbox.com/privacy-policy/](https://www.lawtoolbox.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://www.lawtoolbox.com/customersupport/2019/LawToolBox_...](https://www.lawtoolbox.com/customersupport/2019/LawToolBox_End_User_License_Agreement_and_SLA_LAWTOOLBOX_2019_APR.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von LawToolBox.com Inc. bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | Delegiert | Diese Berechtigung ist für den Zugriff auf die Kontakte des Benutzers&#8217;eingeschränkt, auf die er bereits Zugriff hat, &#8211; wir verwenden dies, um Benutzern das Abrufen ihrer eigenen Kalenderinformationen zu ermöglichen. | [Optional] Lesezugriff auf den Kalender des Benutzers. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Calendars.ReadWrite | Delegiert | Diese Berechtigung ist für den Zugriff auf die Kontakte des Benutzers&#8217;eingeschränkt, auf die er bereits Zugriff hat, &#8211; wir verwenden dies, um Benutzern das Abrufen eigener Kalenderinformationen und das Schreiben in Kalender zu ermöglichen. | Zum Erstellen einer Kalenderseinladung in den Kalender des Benutzers. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Calendars.ReadWrite.Shared | Delegiert | Diese Berechtigung ist für den Zugriff auf die Kontakte des Benutzers&#8217;eingeschränkt, auf die er bereits Zugriff hat, &#8211; wir verwenden dies, um Benutzern das Abrufen ihrer eigenen Kalenderinformationen zu ermöglichen. | Zum Erstellen einer Kalenderseinladung in einen freigegebenen Kalender. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Contacts.ReadWrite | Delegiert | Diese Berechtigung beschränkt den Zugriff auf die Kontakte des Benutzers&#8217;, auf die er bereits Zugriff hat.  Wir verwenden diese Berechtigung, damit Benutzer ihre O365-Kontakte durchsuchen und zu LawToolBox hinzufügen können &#8211; wir keinen Kontakt automatisch hinzufügen (dies kann widerrufen werden, wenn Sie dieses Feature nicht wünschen und Kontakte manuell hinzugefügt werden können. | [Optional]- um Benutzerkontakte zu lesen und Benutzer aus der Kontaktliste mit der Gruppe zu verbinden. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Contacts.ReadWrite.Shared | Delegiert | wir verwenden diese Berechtigung, um benutzern das Durchsuchen freigegebener O365-Kontakte und das Hinzufügen zu LawToolBox zu ermöglichen, &#8211; wir keine Kontakte automatisch hinzufügen | [Optional]- leset freigegebene Kontakte von Benutzern, um die Liste der für den Fall relevanten Kontakte zu erstellen. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Directory.AccessAsUser.All | Delegiert | verwenden wir im Verwaltungsportal, um eine Liste der Benutzer aus dem O365-Mandanten abzurufen, die Ihrem Konto hinzugefügt werden sollen. | [Optional] Lesen von Gruppen- und Benutzerinformationen als Benutzer. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Directory.ReadWrite.All | Delegiert | verwenden wir im Verwaltungsportal, um eine Liste der Benutzer aus dem O365-Mandanten abzurufen, die Ihrem Konto hinzugefügt werden sollen. | [Optional] Lesen von Gruppen- und Benutzerinformationen als Benutzer. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.Read | Delegiert | Dadurch kann das Add-In die Benutzerdateien lesen und auflisten, auf die der Benutzer bereits Zugriff hat. | [Optional] Lesezugriff auf die OneDrive des Benutzers. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.Read.All | Delegiert | wir verwenden diese Berechtigung zum Lesen und Auflisten der Benutzerdateien, auf die der Benutzer bereits Zugriff hat | [Optional]-OneDrive des Benutzers lesen. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.ReadWrite | Delegiert | Wir lesen Dateien aus Teams, Gruppen und OneDrive für Besprechungen (wenn Sie sie widerrufen, verhindert dies, dass unser Add-In dateien in unseren Apps auflistet) | [Optional]- Lesen und Ändern von Dateien im OneDrive eines Benutzers. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.ReadWrite.All | Delegiert | wir lesen Dateien aus Teams, Gruppen und OneDrive für Besprechungen (wenn Sie sie widerrufen, verhindert LTB, dass in unseren Apps dateien aufgeführt werden).  Der Benutzer kann das Add-In nur zum Lesen und Auflisten der Benutzerdateien verwenden, auf die der Benutzer bereits Zugriff hat. | [Optional] Lese-/Schreibzugriff auf die OneDrive Datei des Benutzers, die der Frage zugeordnet ist. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Group.ReadWrite.All | Delegiert | GroupID, GroupName, GroupEmail | Wir erstellen eine Gruppe für jede in unserem System erstellte Frage. Auf diese Weise können Benutzer relevante Informationen in der Gruppe speichern, wodurch ihre Daten wiederum in ihrem eigenen Mandanten gespeichert werden. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.Read | Delegiert | wir verwenden diese Berechtigung, um PACER-E-Mails in unserem Outlook-Add-In zu lesen, um diese Frage automatisch zu öffnen, und um Kontakte aus Ihrer E-Mail zu lesen, die unserem Kontaktsystem hinzugefügt werden sollen. | [Optional] [InProgress] Lesen sie die E-Mail-Adresse des Benutzers für "Matters". | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.ReadWrite | Delegiert | wir verwenden diese Berechtigung, um PACER-E-Mails in unserem Outlook-Add-In zu lesen, um diese Frage automatisch zu öffnen, und um Kontakte aus Ihrer E-Mail zu lesen, die unserem Kontaktsystem hinzugefügt werden sollen. | [Optional] [InProgress] Lese-/Schreibzugriff auf E-Mails für Benutzer. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.ReadWrite.Shared | Delegiert | wir verwenden diese Berechtigung, um PACER-E-Mails in unserem Outlook-Add-In zu lesen, um diese Frage automatisch zu öffnen, und um Kontakte aus Ihrer E-Mail zu lesen, die unserem Kontaktsystem hinzugefügt werden sollen. | [Optional] [InProgress] Lese-/Schreibzugriff auf E-Mails für Benutzer. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.Send | Delegiert | Wir verwenden diese sendenden E-Mails als Benutzer, um es einem Benutzer zu ermöglichen, sich selbst Berichte nur über Daten zu senden, auf die er bereits auf unserem System zugriff hat. | [Optional] [InProgress] Senden von Stichtagen per E-Mail als Benutzer. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Tasks.ReadWrite.Shared | Delegiert | Diese Berechtigung ist auf den Benutzer&#8217;Aufgaben beschränkt, auf die er bereits Zugriff hat, &#8211; wir verwenden diese, um Benutzern das Abrufen und Aktualisieren ihrer eigenen AUFGABENinformationen zu ermöglichen. | [Optional]-[InProgress] Lesezugriff auf Schreibtermine als Aufgabe für Benutzer. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.Read | Delegiert | Wird verwendet, um zuletzt verwendete Kontakte vorzuschlagen, die Besprechungen oder Kontakten hinzugefügt werden sollen. | Lesen der Benutzerinformationen. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.ReadWrite | Delegiert | Wird verwendet, um zuletzt verwendete Kontakte vorzuschlagen, die Besprechungen oder Kontakten hinzugefügt werden sollen. | Lese-/Schreibzugriff auf Benutzerinformationen. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.ReadWrite.All | Delegiert | dies ist erforderlich, um die Teams-API zu lesen, Teams zu erstellen, ein Kalenderereignis zu erstellen, Kanäle zu erstellen, Teams Dateifreigabefeature | Lese-/Schreibzugriff auf Benutzerinformationen. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| email | Delegiert | E-Mail, Office365 UserID, ObjectID, TenantID. | Lesezugriff auf die E-Mail-Adresse des Benutzers. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Profil | Delegiert | dies ist für die SSO-Authentifizierung erforderlich – wir verwenden diese Berechtigung auch zum Abrufen von Bildern und Namen, die auf dem M365-Mandanten gespeichert sind, damit der Benutzer weiß, dass er sich in der richtigen Toolbox befindet | Lesen von Benutzerprofilinformationen. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Benutzer-E-Mail, UserID, AccessToken, Gruppeninformationen in unserem Debugprotokoll

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir speichern Falldatensätze, es sei denn, wir erhalten eine Anforderung zum Löschen der Daten.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von LawToolBox.com Inc. bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden in der Checkliste für die Microsoft Identity Platform Integration überprüft und berücksichtigt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Für eine bessere Kontrolle kann der Administrator App-Berechtigungen implementieren |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | ,<br/>- Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/> |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
