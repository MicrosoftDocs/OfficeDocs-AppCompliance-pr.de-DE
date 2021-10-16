---
title: Anwendungsinformationen für CatchEm von Chimu Software
ms.author: elmalova
author: elenamalova
ms.date: 04/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für CatchEm, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: e31f99d6714482327267658bac0e61499572491e
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413877"
---
# <a name="catchem"></a>CatchEm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 27. März 2021</p>

* <a href="https://teams.microsoft.com/l/app/fc686a41-3bd0-45b3-a56d-f278888fd694" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002639" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Chimu Software für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | CatchEm |
| ID | WA200002639 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Chimu Software |
| URL der Partnerwebsite | [https://chimusoftware.com](https://chimusoftware.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://catchem.apps.chimusoftware.com/help](https://catchem.apps.chimusoftware.com/help) |
| URL der Datenschutzrichtlinie | [https://www.chimusoftware.com/apps/catchem/privacy.html](https://www.chimusoftware.com/apps/catchem/privacy.html) |
| URL der Nutzungsbedingungen | [https://www.chimusoftware.com/apps/catchem/termsofuse.html](https://www.chimusoftware.com/apps/catchem/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Chimu Software dazu bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Chat.ReadBasic | Delegiert | Diese Berechtigung ist erforderlich, um die Kontakte eines Anwendungsbenutzers zu ermitteln. AadObjectId: So identifizieren Sie einen Benutzer eindeutig. TenantId: Um festzustellen, ob ein Kontakt intern oder extern für den Benutzer ist. DisplayName, GivenName, Surname: to identify contacts to application users. E-Mail, UserPrincipalName: Zur Unterscheidung zwischen Kontakten mit demselben Namen und zum Zulassen von &quot; Klick-zu-Chat-Funktionen. &quot; Neueste Chat-ID: So aktivieren &quot; Sie die Chatfunktion "Klicken auf" &quot; | Diese Berechtigung ist erforderlich, um die Kontakte eines Anwendungsbenutzers zu ermitteln. AadObjectId: So identifizieren Sie einen Benutzer eindeutig. TenantId: Um festzustellen, ob ein Kontakt intern oder extern für den Benutzer ist. DisplayName, GivenName, Surname: to identify contacts to application users. E-Mail, UserPrincipalName: Zur Unterscheidung zwischen Kontakten mit demselben Namen und zum Zulassen von &quot; Klick-zu-Chat-Funktionen. &quot; Neueste Chat-ID: So aktivieren &quot; Sie die Chatfunktion "Klicken auf" &quot; | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| People.Read | Delegiert | Zur Verbesserung der Genauigkeit von Daten für externe Kontakte. DisplayName: zum Identifizieren von Kontakten zu Anwendungsbenutzern. | Zur Verbesserung der Genauigkeit von Daten für externe Kontakte. DisplayName: zum Identifizieren von Kontakten zu Anwendungsbenutzern. | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| Presence.Read.All | Delegiert | Kontakte aktueller Anwesenheitsstatus | Nicht zutreffend | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| TeamsActivity.Send | Beide | So senden Sie Benachrichtigungen an Benutzer, wenn sich der Anwesenheitsstatus eines Kontakts ändert | Nicht zutreffend | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| TeamsAppInstallation.ReadWriteSelfForUser | Delegiert | So aktivieren Sie automatische Updates für die Anwendung | Nicht zutreffend | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| User.Read | Delegiert | AadObjectId: So identifizieren Sie einen Benutzer eindeutig. TenantId: Um festzustellen, ob ein Kontakt intern oder extern für den Benutzer ist. DisplayName, GivenName, Surname: to identify contacts to application users. E-Mail, Chatadressen, UserPrincipalName: Zur Unterscheidung zwischen Kontakten mit demselben Namen und zum Zulassen von &quot; Klick-zu-Chat-Funktionen. &quot; CompanyName, Country: Analytics. AccountEnabled, DeletedDateTime: Automatisches Löschen von Benutzerdaten für deaktivierte Benutzer | AadObjectId: So identifizieren Sie einen Benutzer eindeutig. TenantId: Um festzustellen, ob ein Kontakt intern oder extern für den Benutzer ist. DisplayName, GivenName, Surname: to identify contacts to application users. E-Mail, Chatadressen, UserPrincipalName: Zur Unterscheidung zwischen Kontakten mit demselben Namen und zum Zulassen von &quot; Klick-zu-Chat-Funktionen. &quot; CompanyName, Country: Analytics. AccountEnabled, DeletedDateTime: Automatisches Löschen von Benutzerdaten für deaktivierte Benutzer | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| User.ReadBasic.All | Delegiert | Zur Verbesserung der Genauigkeit von Daten für interne Kontakte. AadObjectId: So identifizieren Sie einen Benutzer eindeutig. TenantId: Um festzustellen, ob ein Kontakt intern oder extern für den Benutzer ist. DisplayName, GivenName, Surname: to identify contacts to application users. E-Mail, UserPrincipalName: Zur Unterscheidung zwischen Kontakten mit demselben Namen und zum Zulassen von &quot; Klick-zu-Chat-Funktionen. &quot; | Zur Verbesserung der Genauigkeit von Daten für interne Kontakte. AadObjectId: So identifizieren Sie einen Benutzer eindeutig. TenantId: Um festzustellen, ob ein Kontakt intern oder extern für den Benutzer ist. DisplayName, GivenName, Surname: to identify contacts to application users. E-Mail, UserPrincipalName: Zur Unterscheidung zwischen Kontakten mit demselben Namen und zum Zulassen von &quot; Klick-zu-Chat-Funktionen. &quot; | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| offline_access | Delegiert | Graph Sicherheitstokens, damit die Anwendung kontaktbezogene Anwesenheitsänderungen benachrichtigen und Kontaktlisten aktualisieren kann, wenn der Benutzer die Anwendung nicht aktiv verwendet | Graph-Sicherheitstoken | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Das &quot; Tag aus der &quot; Nachrichtenfunktion muss den Anzeigenamen des Kontakts verwenden, um dem Anwendungsbenutzer angezeigt zu werden. | Anzeigename des Kontakts | So können Sie den Namen des Kontakts dem Anwendungsbenutzer zurückgeben |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Nicht zutreffend

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Chimu Software bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Nein |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

