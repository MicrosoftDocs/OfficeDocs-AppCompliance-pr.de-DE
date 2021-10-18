---
title: Anwendungsinformationen für WorkplaceBuddy von WorkplaceBuddy
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für WorkplaceBuddy, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 47d67f1f294781a8b1b80462046d3dd0c0ec5e5a
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60444741"
---
# <a name="workplacebuddy"></a>WorkplaceBuddy

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 23. Juni 2021</p>

* <a href="https://teams.microsoft.com/l/app/6fef6052-d84d-4071-b679-8b542512a621" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001238" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von WorkplaceBuddy für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | WorkplaceBuddy |
| ID | WA200001238 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | WorkplaceBuddy |
| URL der Partnerwebsite | [https://www.workplacebuddy.com](https://www.workplacebuddy.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.workplacebuddy.com](https://www.workplacebuddy.com) |
| URL der Datenschutzrichtlinie | [https://www.workplacebuddy.com/privacy-policy.pdf](https://www.workplacebuddy.com/privacy-policy.pdf) |
| URL der Nutzungsbedingungen | [https://www.workplacebuddy.com/terms-of-use.pdf](https://www.workplacebuddy.com/terms-of-use.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von WorkplaceBuddy darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | Delegiert | Wir synchronisieren diese Daten, um WorkplaceBuddy-Registerkarten bei Teams funktionieren zu lassen und bestimmte Benutzer mit dem Chatbot anzusprechen. | Nur Name, ID und Mitglieder | [39073da9-c47c-4da8-b57a-3786461db8f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/39073da9-c47c-4da8-b57a-3786461db8f4) |
>| Group.Read.All | Delegiert | Wir synchronisieren diese Daten, um WorkplaceBuddy-Registerkarten bei Teams funktionieren zu lassen und bestimmte Benutzer mit dem Chatbot anzusprechen. | Nur Name, ID und Mitglieder | [39073da9-c47c-4da8-b57a-3786461db8f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/39073da9-c47c-4da8-b57a-3786461db8f4) |
>| User.Read | Delegiert | Wir synchronisieren diese Daten, um Benutzern die Anmeldung zu ermöglichen | Name, E-Mail, Profilbild, ID | [39073da9-c47c-4da8-b57a-3786461db8f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/39073da9-c47c-4da8-b57a-3786461db8f4) |
>| User.ReadBasic.All | Delegiert | Wir synchronisieren diese Daten, um Benutzern die Anmeldung zu ermöglichen | Name, E-Mail, Profilbild, ID | [39073da9-c47c-4da8-b57a-3786461db8f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/39073da9-c47c-4da8-b57a-3786461db8f4) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Wir benötigen diese Daten, um eine personalisierte Erfahrung zu bieten. | Name, E-Mail, ID | Wir benötigen diese Daten, um eine personalisierte Erfahrung zu bieten. |


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


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von WorkplaceBuddy darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden in der Checkliste für die Microsoft Identity Platform Integration überprüft und berücksichtigt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
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
