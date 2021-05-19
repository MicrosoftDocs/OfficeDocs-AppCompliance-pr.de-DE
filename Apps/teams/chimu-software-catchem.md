---
title: Anwendungsinformationen für CatchEm von Chimu Software
ms.author: elmalova
author: elenamalova
ms.date: 03/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für CatchEm, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 55b248c8f99e18d08ddf60dec177ce92b543f008
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552316"
---
# <a name="catchem"></a>CatchEm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 27. März 2021</p>

* <a href="https://teams.microsoft.com/l/app/fc686a41-3bd0-45b3-a56d-f278888fd694" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002639" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Chimu Software Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | CatchEm |
| ID | WA200002639 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Chimu Software |
| URL der Partner-Website | [https://www.chimusoftware.com](https://www.chimusoftware.com) |
| URL Teams Anwendungsinfoseite | [https://catchem.apps.chimusoftware.com/help](https://catchem.apps.chimusoftware.com/help) |
| URL der Datenschutzrichtlinie | [https://www.chimusoftware.com/apps/catchem/privacy.html](https://www.chimusoftware.com/apps/catchem/privacy.html) |
| URL der Nutzungsbedingungen | [https://www.chimusoftware.com/apps/catchem/termsofuse.html](https://www.chimusoftware.com/apps/catchem/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Chimu Software darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Chat.ReadBasic | Delegiert | Diese Berechtigung ist erforderlich, um die Kontakte eines Anwendungsbenutzers zu ermitteln. AadObjectId: So identifizieren Sie einen Benutzer eindeutig. TenantId: um festzustellen, ob ein Kontakt intern oder extern für den Benutzer ist. DisplayName, GivenName, Nachname: um Kontakte zu Anwendungsbenutzern zu identifizieren. E-Mail, UserPrincipalName: um zwischen Kontakten mit demselben Namen zu unterscheiden und &quot; die Click-to-Chat-Funktionalität &quot; zuzulassen. Neueste Chat-ID: So aktivieren &quot; Sie die Click-to-Chat-Funktionalität &quot; | Diese Berechtigung ist erforderlich, um die Kontakte eines Anwendungsbenutzers zu ermitteln. AadObjectId: So identifizieren Sie einen Benutzer eindeutig. TenantId: um festzustellen, ob ein Kontakt intern oder extern für den Benutzer ist. DisplayName, GivenName, Nachname: um Kontakte zu Anwendungsbenutzern zu identifizieren. E-Mail, UserPrincipalName: um zwischen Kontakten mit demselben Namen zu unterscheiden und &quot; die Click-to-Chat-Funktionalität &quot; zuzulassen. Neueste Chat-ID: So aktivieren &quot; Sie die Click-to-Chat-Funktionalität &quot; | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| People.Read | Delegiert | Verbesserung der Genauigkeit der Daten für externe Kontakte. DisplayName: um Kontakte zu Anwendungsbenutzern zu identifizieren. | Verbesserung der Genauigkeit der Daten für externe Kontakte. DisplayName: um Kontakte zu Anwendungsbenutzern zu identifizieren. | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| Presence.Read.All | Delegiert | Kontakte aktueller Anwesenheitsstatus | Nicht zutreffend | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| TeamsActivity.Send | Beide | So senden Sie Benachrichtigungen an Benutzer, wenn sich der Status eines Kontaktanwesenheitsstatus ändert | Nicht zutreffend | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| TeamsAppInstallation.ReadWriteSelfForUser | Delegiert | So aktivieren Sie automatische Aktualisierungen für die Anwendung | Nicht zutreffend | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| User.Read | Delegiert | AadObjectId: So identifizieren Sie einen Benutzer eindeutig. TenantId: um festzustellen, ob ein Kontakt intern oder extern für den Benutzer ist. DisplayName, GivenName, Nachname: um Kontakte zu Anwendungsbenutzern zu identifizieren. E-Mail, IM-Adressen, UserPrincipalName: um zwischen Kontakten mit demselben Namen zu unterscheiden und die &quot; Click-to-Chat-Funktionalität &quot; zuzulassen. Name des Unternehmens, Land: Analysen. AccountEnabled, DeletedDateTime: Automatisches Löschen von Benutzerdaten für deaktivierte Benutzer | AadObjectId: So identifizieren Sie einen Benutzer eindeutig. TenantId: um festzustellen, ob ein Kontakt intern oder extern für den Benutzer ist. DisplayName, GivenName, Nachname: um Kontakte zu Anwendungsbenutzern zu identifizieren. E-Mail, IM-Adressen, UserPrincipalName: um zwischen Kontakten mit demselben Namen zu unterscheiden und die &quot; Click-to-Chat-Funktionalität &quot; zuzulassen. Name des Unternehmens, Land: Analysen. AccountEnabled, DeletedDateTime: Automatisches Löschen von Benutzerdaten für deaktivierte Benutzer | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| User.ReadBasic.All | Delegiert | Verbesserung der Genauigkeit der Daten für interne Kontakte. AadObjectId: So identifizieren Sie einen Benutzer eindeutig. TenantId: um festzustellen, ob ein Kontakt intern oder extern für den Benutzer ist. DisplayName, GivenName, Nachname: um Kontakte zu Anwendungsbenutzern zu identifizieren. E-Mail, UserPrincipalName: um zwischen Kontakten mit demselben Namen zu unterscheiden und &quot; die Click-to-Chat-Funktionalität &quot; zuzulassen. | Verbesserung der Genauigkeit der Daten für interne Kontakte. AadObjectId: So identifizieren Sie einen Benutzer eindeutig. TenantId: um festzustellen, ob ein Kontakt intern oder extern für den Benutzer ist. DisplayName, GivenName, Nachname: um Kontakte zu Anwendungsbenutzern zu identifizieren. E-Mail, UserPrincipalName: um zwischen Kontakten mit demselben Namen zu unterscheiden und &quot; die Click-to-Chat-Funktionalität &quot; zuzulassen. | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| offline_access | Delegiert | Graph Sicherheitstoken, damit die Anwendung über Änderungen an der Kontaktpräsenz benachrichtigt und Kontaktlisten aktualisiert, wenn der Benutzer die Anwendung nicht aktiv verwendet | Graph Sicherheitstoken | fc686a41-3bd0-45b3-a56d-f278888fd694 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Die &quot; Funktion "Tag aus &quot; Nachricht" muss den Anzeigenamen des Kontakts verwenden, um es dem Anwendungsbenutzer anzuzeigen. | Der Anzeigename des Kontakts | So können Sie den Namen des Kontakts dem Anwendungsbenutzer zurückgeben |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>In den Anwendungstelemetrie- oder Protokollprotokollen sind keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Nicht zutreffend

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Chimu Software darüber bereitgestellt, wie diese App authentifizierung, Autorisierung, Bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Können Sie sich in Microsoft Identifizplattform (Azure AD) integrieren?  | Ja |
| Haben Sie alle in der Checkliste für die Microsoft Identity Platform-Integration beschriebenen bewährten Methoden überprüft und eingehalten?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Conditional Access-Richtlinien? | Nein |
| Fordert Ihre App die geringsten Berechtigungsberechtigungen für Ihr Szenario an? | Ja |
| Gibt die statisch registrierten Berechtigungen Ihrer App die Berechtigungen wieder, die Ihre App dynamisch und inkrementell anfordert? | Nein |
| Unterstützt Ihre App Multi-Tenancy? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle für Ihre App registrierten Unified Resource Identifier (URI) umleiten? | Ja |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann zu, dass Aufrufe erfolgreich sind, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
