---
title: Application Information for In Case of Crisis by RockDove Solutions, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 08/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für "Im Falle einer Krise", die Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: d6cb978afddcd7b87851ac515e0594757d63fb21
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412795"
---
# <a name="in-case-of-crisis"></a>Im Falle einer Krise

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 27. August 2021</p>

* <a href="https://teams.microsoft.com/l/app/cf430644-447e-4572-8467-3892596d05c7" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003194" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von RockDove Solutions, Inc. an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Im Falle einer Krise |
| ID | WA200003194 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | RockDove Solutions, Inc. |
| URL der Partnerwebsite | [https://www.rockdovesolutions.com](https://www.rockdovesolutions.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.rockdovesolutions.com/in-case-of-crisis/in-case...](https://www.rockdovesolutions.com/in-case-of-crisis/in-case-of-crisis-platform) |
| URL der Datenschutzrichtlinie | [https://www.rockdovesolutions.com/privacy-policy](https://www.rockdovesolutions.com/privacy-policy) |
| URL der Nutzungsbedingungen | [https://www.rockdovesolutions.com/terms-of-use](https://www.rockdovesolutions.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von RockDove Solutions, Inc. bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | Delegiert | Dadurch wird voll auf den Kalender eines Benutzers zugegriffen. Unsere App zeigt die Beschreibung, den Konferenzlink sowie das Start- und Enddatum an. Unsere App ermöglicht es einem Benutzer auch, ein Ereignis im Outlook-Kalender zu erstellen. | In Zukunft können Ereignis-IDs in der Datenbank gespeichert werden. | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| Channel.ReadBasic.All | Delegiert | Ermöglicht den Zugriff auf einen Benutzerkanal.  Die Benutzerliste der Kanäle wird zum Auswählen eines Kanals verwendet, in den eine Datei hochgeladen werden soll. | Nicht zutreffend | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| Files.ReadWrite | Delegiert | Nicht zutreffend | Nicht zutreffend | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| Files.ReadWrite.All | Delegiert | Wir ermöglichen Benutzern das Hochladen von Dateien aus der Problemverwaltung in Teams | Nicht zutreffend | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| Sites.ReadWrite.All | Delegiert | Dies ist erforderlich, um in einen privaten Kanal hochzuladen. | Nicht zutreffend | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| Team.ReadBasic.All | Delegiert | Die Liste der Teams ist erforderlich, um die Liste der Kanäle abzurufen, zu denen der Benutzer gehört. Dadurch können wir die Liste der verfügbaren Uploadkanäle anzeigen. | Nicht zutreffend | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| email | Delegiert | Sie müssen die E-Mails des Benutzers nach der Authentifizierung abrufen, um sie mit E-Mails in unserer Datenbank zu vergleichen. Wenn der Benutzer kein Konto in unserem System hat, erstellen wir ein Konto. | Wir speichern die E-Mail-Adresse und erstellen dafür ein App-Konto. | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| offline_access | Delegiert | Dadurch können wir das Graph-Zugriffstoken aktualisieren. | Nicht zutreffend | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| openid | Delegiert | Erforderliche Berechtigung zur Authentifizierung über openid | Nicht zutreffend | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| AWS | E-Mail-Adresse des Organisationsbenutzers für Authentifizierung und Kommunikation | E-Mail-Adressen werden in unserem Dienst als Benutzernamen verwendet, und wir verwenden AWS für unseren SMTP-Anwendungs-E-Mail-Server. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>E-Mail-Adressen werden als primärer Benutzername in unserem System verwendet.  Die Aufbewahrung von Benutzerinformationen für unsere Clients wird beibehalten, während der Client aktuell ist, und entfernt, nachdem er seinen Servicevertrag nicht mehr verlängert hat.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir bieten unseren Kunden ein Partnerverwaltungsportal zur Verwaltung (Einfügen, Ersetzen, Löschen, Überwachen, Archivieren von Unternehmensinformationen, die in unserem Dienst freigegeben sind).

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von RockDove Solutions, Inc. bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/><br/> |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

