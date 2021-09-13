---
title: Anwendungsinformationen für Die Prioritätsmatrix von Appfluence Inc
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Priority Matrix, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: e88ba3c98c9ab444f2500ed09013071a6b5ab2c3
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/12/2021
ms.locfileid: "59279968"
---
# <a name="priority-matrix"></a>Priority Matrix

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Zuletzt aktualisiert vom Entwickler am: 23. Juni 2021</p>

* <a href="https://teams.microsoft.com/l/app/5be2b320-a5b7-4221-893c-dee506e4e365" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382005" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Von Appfluence Inc. an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Priority Matrix |
| ID | WA104382005 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | Appfluence Inc |
| URL der Partnerwebsite | [https://appfluence.com/office-365-project-management-integr...](https://appfluence.com/office-365-project-management-integration/) |
| URL der Seite mit Teams Anwendungsinformationen | [https://appfluence.com/project-management-integration-for-m...](https://appfluence.com/project-management-integration-for-microsoft-teams/) |
| URL der Datenschutzrichtlinie | [https://appfluence.com/privacy/](https://appfluence.com/privacy/) |
| URL der Nutzungsbedingungen | [https://appfluence.com/eula](https://appfluence.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Appfluence Inc. bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | Delegiert | Nur wenn ein neuer Benutzer zum Konto hinzugefügt wird, speichern wir seine E-Mails. | Bei der Erstellung eines neuen Kontos wird dies verwendet, um andere Teammitglieder vorzuschlagen. | [5be2b320-a5b7-4221-893c-dee506e4e365](https://docs.microsoft.com/microsoft-365-app-certification/azure/5be2b320-a5b7-4221-893c-dee506e4e365) |
>| User.ReadBasic.All | Delegiert | Nur wenn ein neuer Benutzer zum Konto hinzugefügt wird, speichern wir seine E-Mails. | Bei der Erstellung eines neuen Kontos wird dies verwendet, um andere Teammitglieder vorzuschlagen. | [5be2b320-a5b7-4221-893c-dee506e4e365](https://docs.microsoft.com/microsoft-365-app-certification/azure/5be2b320-a5b7-4221-893c-dee506e4e365) |
>| offline_access | Delegiert | Wir speichern das Anmeldetoken, um Anforderungen im Auftrag des Benutzers auszuführen. | Aktualisieren Sie das Token, ohne den Benutzer zu stören. (Prioritätsmatrix für Teams) | [5be2b320-a5b7-4221-893c-dee506e4e365](https://docs.microsoft.com/microsoft-365-app-certification/azure/5be2b320-a5b7-4221-893c-dee506e4e365) |
>| Files.Read.All | Delegiert | Wir speichern keine Dateiinformationen, es sei denn, der Benutzer erstellt explizit und wissentlich ein Priority Matrix-Element, das mit der Originaldatei verknüpft ist. | In unserer One-on-One-Funktion (verfügbar über unsere Web-App und auch unsere Outlook/Teams-Add-Ins) verwenden wir dieses Feature, um SharePoint/OneDrive Dateien hervorzuheben, die von zwei Benutzern in unserem System gemeinsam genutzt werden, um Besprechungen und die allgemeine Zusammenarbeit zu vereinfachen. | [affadfb6-f17b-428f-97f9-9aae3b6175bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/affadfb6-f17b-428f-97f9-9aae3b6175bc) |
>| User.Read | Delegiert | Grundlegende Benutzerprofilinformationen (Anzeigename, Vorname, Nachname, E-Mail, Avatar) werden von uns gespeichert. | Rufen Sie den Namen, die E-Mail-Adresse, den Avatar des Benutzers ab, um sein Konto bei uns zu personalisieren. | [affadfb6-f17b-428f-97f9-9aae3b6175bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/affadfb6-f17b-428f-97f9-9aae3b6175bc) |
>| openid | Delegiert | Wir speichern die SSO-Verbindung, um den Anmeldemodus für den Benutzer anzugeben. | Um Benutzer über einmaliges Anmelden anzumelden. | [affadfb6-f17b-428f-97f9-9aae3b6175bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/affadfb6-f17b-428f-97f9-9aae3b6175bc) |
>| Calendars.Read | Delegiert | Eine kleine Anzahl von Kalenderereignissen wird in Aufgaben umgewandelt, die in unserem System gespeichert sind. | Lesen Sie Kalenderereignisse, damit sie in unserer 1:1-Ansicht angezeigt werden können. Auch zum Initialisieren neuer Konten.  | [d76f016f-52c7-41b5-835b-900361d7040c](https://docs.microsoft.com/microsoft-365-app-certification/azure/d76f016f-52c7-41b5-835b-900361d7040c) |
>| Mail.Read | Delegiert | In unserem System erstellte Aufgaben werden mit einem Link zur ursprünglichen Nachricht gespeichert. | Wird in unserem Outlook-Add-In verwendet, um E-Mails in Aufgaben umzuwandeln und freigegebene Arbeit in der 1:1-Ansicht anzuzeigen. | [d76f016f-52c7-41b5-835b-900361d7040c](https://docs.microsoft.com/microsoft-365-app-certification/azure/d76f016f-52c7-41b5-835b-900361d7040c) |
>| Tasks.Read | Delegiert | Einige Outlook/Planner-Aufgaben werden in unserem System repliziert, um neuen Benutzern zu helfen. | Wir starten neue Benutzerkonten mit ihren Graph Aufgaben. | [d76f016f-52c7-41b5-835b-900361d7040c](https://docs.microsoft.com/microsoft-365-app-certification/azure/d76f016f-52c7-41b5-835b-900361d7040c) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Der Bot kann Aufgaben erstellen und sie einem bestimmten Teamkameraden zuweisen. Dazu muss er seinen Namen kennen. | Nein |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Ja, wir verwenden die E-Mail-Adresse des Benutzers als eindeutige ID in unserem System, die zum Nachverfolgen von Anwendungsfehlern und zum Nachverfolgen wichtiger Ereignisse im System (Downloads, Anmeldungen, Anwendungsversionen usw.) verwendet wird, damit unser Kundendienstteam eine prompte Antwort auf Kundenanfragen bereitstellen kann. Im Rahmen unserer DSGVO-Compliance löschen wir alle Kundendaten innerhalb von 2 Wochen nach einer Löschungsanforderung, obwohl wir dies in der Praxis am selben Tag tun, da wir interne Skripts haben, um dies halbautomatisch zu tun.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Anwendungsdaten werden sicher in einer verschlüsselten Datenbank gespeichert, wobei der Zugriff auf eine kleine Gruppe von Administratoren beschränkt ist. Um den Zugriff weiter zu sichern, erzwingen wir die zweistufige Authentifizierung, beschränken den Zugriff auf eine kontrollierte Gruppe von IP-Adressen und suchen die Datenbank in ihrem eigenen privaten Subnetz, auf das direkt über das offene Internet zugegriffen werden kann.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Appfluence Inc. bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/><br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
