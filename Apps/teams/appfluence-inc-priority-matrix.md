---
title: Anwendungsinformationen für Prioritätsmatrix von Appfluence Inc
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Priority Matrix, die Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: ccd03dd271cfafb55fd99fc65f4820a9d8787e83
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/06/2021
ms.locfileid: "52250874"
---
# <a name="priority-matrix"></a>Priority Matrix

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Zuletzt aktualisiert vom Entwickler am: 17. November 2020</p>

* <a href="https://teams.microsoft.com/l/app/5be2b320-a5b7-4221-893c-dee506e4e365" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382005" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Appfluence Inc an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Priority Matrix |
| ID | WA104382005 |
| Funktionen | Bot, Registerkarte, Messaging-Erweiterung, Connector |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Appfluence Inc |
| URL der Partnerwebsite | [https://appfluence.com](https://appfluence.com) |
| URL Teams Anwendungsinfoseite | [https://appfluence.com/project-management-integration-for-m...](https://appfluence.com/project-management-integration-for-microsoft-teams/) |
| URL der Datenschutzrichtlinie | [https://appfluence.com/privacy](https://appfluence.com/privacy) |
| URL der Nutzungsbedingungen | [https://appfluence.com/eula](https://appfluence.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Appfluence Inc darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | delegierte | Nur wenn dem Konto ein neuer Benutzer hinzugefügt wird, speichern wir seine E-Mails. | Bei der Erstellung neuer Konten wird dies verwendet, um andere Teammitglieder vorschlagen zu können. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| User.ReadBasic.All | delegierte | Nur wenn dem Konto ein neuer Benutzer hinzugefügt wird, speichern wir seine E-Mails. | Bei der Erstellung neuer Konten wird dies verwendet, um andere Teammitglieder vorschlagen zu können. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| offline_access | delegierte | Wir speichern das Anmeldetoken, um Anforderungen im Namen des Benutzers durchzuführen. | Aktualisieren Sie das Token, ohne den Benutzer zu stört. (Prioritätsmatrix für Teams) | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| Files.Read.All | delegierte | Wir speichern keine Dateiinformationen, es sei denn, der Benutzer erstellt explizit und wissentlich ein Prioritätsmatrixelement, das mit der Ursprünglichen Datei verknüpft ist. | In unserem One-on-One-Feature (verfügbar über unsere Web-App und auch unsere Outlook/Teams-Add-Ins) verwenden wir dieses Feature, um SharePoint/OneDrive-Dateien zu markieren, die von zwei Benutzern in unserem System gemeinsam genutzt werden, um Besprechungen und eine allgemeine Zusammenarbeit zu erleichtern. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| User.Read | delegierte | Grundlegende Benutzerprofilinformationen (Anzeigename, Vorname, Nachname, E-Mail, Avatar) werden von uns gespeichert. | Holen Sie sich den Namen, die E-Mail-Adresse, den Avatar des Benutzers, um ihr Konto bei uns zu personalisieren. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| openid | delegierte | Wir speichern die SSO-Verbindung, um den Anmeldemodus für den Benutzer anzugeben. | Zum Anmelden von Benutzern über einmaliges Anmelden. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| Calendars.Read | delegierte | Eine kleine Anzahl von Kalenderereignissen werden in Aufgaben verwandelt, die in unserem System gespeichert sind. | Lesen Sie Kalenderereignisse, damit sie in unserer 1:1-Ansicht angezeigt werden können. Auch, um neue Konten zu initialisieren.  | d76f016f-52c7-41b5-835b-900361d7040c |
>| Mail.Read | delegierte | In unserem System erstellte Aufgaben werden mit einem Link zur ursprünglichen Nachricht gespeichert. | Wird in unserem Outlook verwendet, um E-Mails in Aufgaben zu verwandeln und freigegebene Arbeit in der 1:1-Ansicht anzeigen. | d76f016f-52c7-41b5-835b-900361d7040c |
>| Tasks.Read | delegierte | Einige Outlook/Planner-Aufgaben werden in unserem System repliziert, um neuen Benutzern zu helfen. | Wir bootstrapen neue Benutzerkonten mit ihren Graph Aufgaben. | d76f016f-52c7-41b5-835b-900361d7040c |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Der Bot kann Aufgaben erstellen und einem bestimmten Teamkollegen zuweisen. Dazu muss er seinen Namen kennen. | Nein |  |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Ja, wir verwenden die E-Mail des Benutzers als eindeutige ID in unserem System, und dies wird verwendet, um Anwendungsfehler nachverfolgt und wichtige Ereignisse im System nachverfolgt (Downloads, Anmeldungen, Anwendungsversionen usw.), damit unser Kundendienstteam eine prompte Antwort auf Kundenanfragen bereitstellen kann. Im Rahmen der Einhaltung der DSGVO löschen wir alle Kundendaten innerhalb von 2 Wochen nach einer Löschungsanforderung, obwohl wir dies in der Praxis am gleichen Tag tun, da wir über interne Skripts verfügen, um dies halbautomatisch zu tun.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Anwendungsdaten werden sicher in einer verschlüsselten Datenbank gespeichert, der Zugriff ist auf eine kleine Gruppe von Administratoren beschränkt. Um den Zugriff weiter zu sichern, erzwingen wir die 2-Faktor-Authentifizierung, beschränken den Zugriff auf eine kontrollierte Gruppe von IP-Adressen und suchen die Datenbank in einem eigenen privaten Subnetz, auf das direkt über das offene Internet zugegriffen werden kann.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Appfluence Inc. darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden geprüft und befolgt, die in der Prüfliste Microsoft Identity Platform aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Bittet Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordern wird? | Ja |
| Unterstützt Ihre App mehrere Mandanzfähigkeiten? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle umgeleiteten Unified Resource Identifier (URI), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | - UrIs für die Platzhalterumleitung,<br/><br/>– Fluss mit Kennwortanmeldeinformationen (Password Credential, ROPC) des Ressourcenbesitzers |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann den Erfolg von Aufrufen zu, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
