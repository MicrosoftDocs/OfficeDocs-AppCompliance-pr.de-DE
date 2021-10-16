---
title: Anwendungsinformationen für isLucid durch UAB Lucid Agreements
ms.author: elmalova
author: elenamalova
ms.date: 09/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für isLucid, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 7270fa4f4a08ca820d1fe7452dea13fb107f2294
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414902"
---
# <a name="islucid"></a>isLucid

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 9. August 2021</p>

* <a href="https://teams.microsoft.com/l/app/a5711b63-5e70-4e4e-b040-0d714b64f684" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002385" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von UAB Lucid-Vereinbarungen für Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | isLucid |
| ID | WA200002385 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | UAB Lucid-Vereinbarungen |
| URL der Partnerwebsite | [https://islucid.com](https://islucid.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://islucid.com](https://islucid.com) |
| URL der Datenschutzrichtlinie | [https://islucid.com/privacy-policy/](https://islucid.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://islucid.com/eula/](https://islucid.com/eula/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von UAB Lucid Agreements darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calls.AccessMedia.All | Beide | Mit einer benutzerspezifischen Zustimmung für jeden Anruf (initiierte Transkription) greift er auf den Audiodatenstrom zu. Der Audiodatenstrom wird an einen Transkriptionsdienst weitergeleitet, damit Benutzer weitere Funktionen erhalten. | App speichert in einem separaten Container in Azure (Blobspeicher und Cosmos DB für jeden Client separat) Transkription und zugehörige Metainformationen. Dies ist erforderlich, um weiteren Zugriff auf besprechungsinformationen für den Benutzer bereitzustellen, der die Anwendung verwendet hat und in der bestimmten Besprechung war. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Calls.JoinGroupCall.All | Beide | Mit einer benutzerspezifischen Zustimmung für jeden Anruf (initiierte Transkription) greift er auf den Audiodatenstrom zu. Der Audiodatenstrom wird an einen Transkriptionsdienst weitergeleitet, damit Benutzer weitere Funktionen erhalten. | App speichert in einem separaten Container in Azure (Blobspeicher und Cosmos DB für jeden Client separat) Transkription und zugehörige Metainformationen. Dies ist erforderlich, um weiteren Zugriff auf besprechungsinformationen für den Benutzer bereitzustellen, der die Anwendung verwendet hat und in der bestimmten Besprechung war. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Group.ReadWrite.All | Beide | Wenn der Benutzer die Integration in Microsoft Planner verwendet, um Aufgaben aus dem Anruf zu erstellen und automatisch in MS Planner zu speichern, sammelt isLucid für diese benutzerverfügbaren Gruppen, Pläne und zugewiesenen Personen. Ohne diese Berechtigung wäre der Benutzer nicht in der Lage, eine Aufgabe aus der Transkription mithilfe von "isLucid" zu erstellen. | Aufgabentitel, Aufgabenersteller, Aufgabenzeitstempel, Aufgabenbeschreibung werden gespeichert, damit Benutzer Zugriff auf den Verlauf von Aufgaben erhalten können, die aus einer bestimmten Besprechung erstellt wurden. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| OnlineMeetings.Read.All | Beide | Die Anwendung sammelt Besprechungstitel, damit Benutzer später (wenn die Besprechung abgeschlossen ist) frühere Transkripte und Aufgaben einfacher finden können. | Besprechungstitel, Zeitstempel der Besprechung, Besprechungsorganisator | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Tasks.ReadWrite | Beide | Wenn der Benutzer die Integration in Microsoft Planner verwendet, um Aufgaben aus dem Anruf zu erstellen und automatisch in MS Planner zu speichern, sammelt isLucid für diese benutzerverfügbaren Gruppen, Pläne und zugewiesenen Personen. Ohne diese Berechtigung wäre der Benutzer nicht in der Lage, eine Aufgabe aus der Transkription mithilfe von "isLucid" zu erstellen. | Aufgabentitel, Aufgabenersteller, Aufgabenzeitstempel, Aufgabenbeschreibung werden gespeichert, damit Benutzer Zugriff auf den Verlauf von Aufgaben erhalten können, die aus einer bestimmten Besprechung erstellt wurden. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| User.ReadWrite.All | Beide | Wenn der Benutzer die Integration in Microsoft Planner verwendet, um Aufgaben aus dem Anruf zu erstellen und automatisch in MS Planner zu speichern, sammelt isLucid für diese benutzerverfügbaren Gruppen, Pläne und zugewiesenen Personen. Ohne diese Berechtigung wäre der Benutzer nicht in der Lage, eine Aufgabe aus der Transkription mithilfe von "isLucid" zu erstellen. | Aufgabentitel, Aufgabenersteller, Aufgabenzeitstempel, Aufgabenbeschreibung werden gespeichert, damit Benutzer Zugriff auf den Verlauf von Aufgaben erhalten können, die aus einer bestimmten Besprechung erstellt wurden. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| openid | Beide | Benutzer-ID, Mandanten-ID, die gesammelt werden, um Azure Active Directory Anmeldefunktionen für unsere Benutzer bereitzustellen | Benutzer-ID, Mandanten-ID für weitere Rechteverwaltung | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| hubspot.com | Name, Nachname, E-Mail und Telefon Anzahl der neu registrierten Benutzer | Wir verwenden Hubspot CRM für die Verwaltung von Vertriebsinformationen |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Bot aktiviert das Senden des Audiodatenstroms an den Transkriptionsdienst. Um eine lesbare Transkription bereitzustellen, müssen wir Den Benutzern (Lautsprechern) Audio zuordnen. Ohne Angabe solcher Informationen sind Transkripte nutzlos. | Name, Nachname, Status, wenn es sich um ein Gastkonto oder ein Microsoft-Konto handelt | Bot aktiviert das Senden des Audiodatenstroms an den Transkriptionsdienst. Um eine lesbare Transkription bereitzustellen, müssen wir Den Benutzern (Lautsprechern) Audio zuordnen. Informationen zu Besprechungsteilnehmern sind auch relevant, damit Benutzer sehen können, wer an der Besprechung teilgenommen hat. |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Benutzer, die unseren Dienst verwenden, generieren Transkripte. In Transkripten werden Besprechungsteilnehmer (Namen, Nachnamen) vorgestellt. Während des Anrufs kann möglicherweise alles erwähnt werden. Wir speichern diese Daten für Benutzer, solange sie unsere Dienste nutzen. Sobald der Client die Verwendung von uns beendet hat, löschen wir innerhalb von 30 Tagen alle zugehörigen Daten.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir steuern keine Daten auf unseren Clients, wenn der Client isLucid als gehostete Lösung erwirbt. Für SaaS-Lösungen ermöglichen wir Es Benutzern, die Nutzung unserer Dienste abzubrechen, und dann löschen wir Cosmos db isntance, die dem Partner zugeordnet ist. Wir sind dabei, auch Informationen an die Compliance-API zu senden.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von UAB Lucid Agreements darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>- Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Ja |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

