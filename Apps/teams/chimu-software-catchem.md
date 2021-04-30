---
title: Anwendungsinformationen für CatchEm von Chimu Software
ms.author: elmalova
author: elenamalova
ms.date: 03/27/2021
ms.topic: article
ms.service: attestation
description: Alle verfügbaren Sicherheits- und Complianceinformationen für CatchEm, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: db41455aeab7dd5f4f453a0a5181ffeb860bd3fa
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095447"
---
# <a name="catchem"></a>CatchEm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 27. März 2021</p>

* <a href="https://teams.microsoft.com/l/app/fc686a41-3bd0-45b3-a56d-f278888fd694" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002639" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Chimu Software für Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | CatchEm |
| ID | WA200002639 |
| Funktionen | Bot, Registerkarte, Messaging-Erweiterung |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Chimu Software |
| URL der Partnerwebsite | [https://www.chimusoftware.com](https://www.chimusoftware.com) |
| URL Teams Anwendungsinfoseite | [https://catchem.apps.chimusoftware.com/help](https://catchem.apps.chimusoftware.com/help) |
| URL der Datenschutzrichtlinie | [https://www.chimusoftware.com/apps/catchem/privacy.html](https://www.chimusoftware.com/apps/catchem/privacy.html) |
| URL der Nutzungsbedingungen | [https://www.chimusoftware.com/apps/catchem/termsofuse.html](https://www.chimusoftware.com/apps/catchem/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Chimu Software bereitgestellt, um zu erfahren, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Chat.ReadBasic | delegierte | Diese Berechtigung ist erforderlich, um die Kontakte eines Anwendungsbenutzers zu bestimmen. AadObjectId: So identifizieren Sie einen Benutzer eindeutig. TenantId: Um zu ermitteln, ob ein Kontakt intern oder extern für den Benutzer ist. DisplayName, GivenName, Surname: Zum Identifizieren von Kontakten zu Anwendungsbenutzern. E-Mail, UserPrincipalName: Um die Unterscheidung zwischen Kontakten mit demselben Namen zu unterstützen und die Funktion zum Klicken &quot; auf chatten zu &quot; ermöglichen. Neueste Chat-ID: So aktivieren Sie &quot; die Funktion "Klicken auf &quot; Chat" | Diese Berechtigung ist erforderlich, um die Kontakte eines Anwendungsbenutzers zu bestimmen. AadObjectId: So identifizieren Sie einen Benutzer eindeutig. TenantId: Um zu ermitteln, ob ein Kontakt intern oder extern für den Benutzer ist. DisplayName, GivenName, Surname: Zum Identifizieren von Kontakten zu Anwendungsbenutzern. E-Mail, UserPrincipalName: Um die Unterscheidung zwischen Kontakten mit demselben Namen zu unterstützen und die Funktion zum Klicken &quot; auf chatten zu &quot; ermöglichen. Neueste Chat-ID: So aktivieren Sie &quot; die Funktion "Klicken auf &quot; Chat" | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| People.Read | delegierte | So verbessern Sie die Genauigkeit der Daten für externe Kontakte. DisplayName: Zum Identifizieren von Kontakten zu Anwendungsbenutzern. | So verbessern Sie die Genauigkeit der Daten für externe Kontakte. DisplayName: Zum Identifizieren von Kontakten zu Anwendungsbenutzern. | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| Presence.Read.All | delegierte | Aktueller Anwesenheitsstatus für Kontakte | Nicht zutreffend | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| TeamsActivity.Send | both | So senden Sie Benachrichtigungen an Benutzer, wenn sich der Anwesenheitsstatus eines Kontakts ändert | Nicht zutreffend | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| TeamsAppInstallation.ReadWriteSelfForUser | delegierte | So aktivieren Sie automatische Updates für die Anwendung | Nicht zutreffend | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| User.Read | delegierte | AadObjectId: So identifizieren Sie einen Benutzer eindeutig. TenantId: Um zu ermitteln, ob ein Kontakt intern oder extern für den Benutzer ist. DisplayName, GivenName, Surname: Zum Identifizieren von Kontakten zu Anwendungsbenutzern. E-Mail, Chatadressen, UserPrincipalName: Zur Unterscheidung zwischen Kontakten mit demselben Namen und zum Zulassen der Funktion zum &quot; &quot; Chatklicken. CompanyName, Country: Analytics. AccountEnabled, DeletedDateTime: automatisches Löschen von Benutzerdaten für deaktivierte Benutzer | AadObjectId: So identifizieren Sie einen Benutzer eindeutig. TenantId: Um zu ermitteln, ob ein Kontakt intern oder extern für den Benutzer ist. DisplayName, GivenName, Surname: Zum Identifizieren von Kontakten zu Anwendungsbenutzern. E-Mail, Chatadressen, UserPrincipalName: Zur Unterscheidung zwischen Kontakten mit demselben Namen und zum Zulassen der Funktion zum &quot; &quot; Chatklicken. CompanyName, Country: Analytics. AccountEnabled, DeletedDateTime: automatisches Löschen von Benutzerdaten für deaktivierte Benutzer | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| User.ReadBasic.All | delegierte | So verbessern Sie die Genauigkeit der Daten für interne Kontakte. AadObjectId: So identifizieren Sie einen Benutzer eindeutig. TenantId: Um zu ermitteln, ob ein Kontakt intern oder extern für den Benutzer ist. DisplayName, GivenName, Surname: Zum Identifizieren von Kontakten zu Anwendungsbenutzern. E-Mail, UserPrincipalName: Um die Unterscheidung zwischen Kontakten mit demselben Namen zu unterstützen und die Funktion zum Klicken &quot; auf chatten zu &quot; ermöglichen. | So verbessern Sie die Genauigkeit der Daten für interne Kontakte. AadObjectId: So identifizieren Sie einen Benutzer eindeutig. TenantId: Um zu ermitteln, ob ein Kontakt intern oder extern für den Benutzer ist. DisplayName, GivenName, Surname: Zum Identifizieren von Kontakten zu Anwendungsbenutzern. E-Mail, UserPrincipalName: Um die Unterscheidung zwischen Kontakten mit demselben Namen zu unterstützen und die Funktion zum Klicken &quot; auf chatten zu &quot; ermöglichen. | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| offline_access | delegierte | Graph, um der Anwendung zu ermöglichen, Änderungen an der Kontaktpräsenz zu benachrichtigen und Kontaktlisten zu aktualisieren, wenn der Benutzer die Anwendung nicht aktiv verwendet | Graph Sicherheitstoken | fc686a41-3bd0-45b3-a56d-f278888fd694 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Das Tag aus der Nachrichtenfunktionalität muss den Anzeigenamen des Kontakts verwenden, um &quot; &quot; dem Anwendungsbenutzer angezeigt zu werden. | Anzeigename des Kontakts | So können Sie den Namen des Kontakts dem Anwendungsbenutzer wieder präsentieren |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Nicht zutreffend

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Chimu Software dazu bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden geprüft und befolgt, die in der Prüfliste Microsoft Identity Platform aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Bittet Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordern wird? | Nein |
| Unterstützt Ihre App mehrere Mandanzfähigkeiten? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle umgeleiteten Unified Resource Identifier (URI), die für Ihre App registriert sind? | Ja |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann den Erfolg von Aufrufen zu, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
