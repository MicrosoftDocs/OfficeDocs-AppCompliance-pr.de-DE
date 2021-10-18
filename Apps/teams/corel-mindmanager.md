---
title: Anwendungsinformationen für MindManager von Corel
ms.author: elmalova
author: elenamalova
ms.date: 06/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für MindManager, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f2c713ac6db2f8a1bb5bcfcd5d7c2a4056d9d045
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429172"
---
# <a name="mindmanager"></a>MindManager

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 3, 2021</p>

* <a href="https://teams.microsoft.com/l/app/cebe4a59-b076-47f3-a7bf-79148daf82f7" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002261" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Corel für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | MindManager |
| ID | WA200002261 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Corel |
| URL der Partnerwebsite | [https://www.mindmanager.com](https://www.mindmanager.com) |
| URL der Datenschutzrichtlinie | [https://www.corel.com/en/corel-privacy-policy/](https://www.corel.com/en/corel-privacy-policy/) |
| URL der Nutzungsbedingungen | [https://www.mindjet.com/go/mmcloudterms](https://www.mindjet.com/go/mmcloudterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Corel darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMessage.Send | Delegiert | Informationen zu Änderungen in einer MindManager-Datei, die dann als Nachricht gepostet werden können | Dateimetadaten, Dateiinhalt – für den Dateibrowser kann der Benutzer seine Dateien durchsuchen, um eine MindManager-Datei (MMAP) zu öffnen. | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| Chat.Send | Delegiert | Informationen zu Änderungen in einer MindManager-Datei, die dann als Nachricht gepostet werden können | Dateimetadaten, Dateiinhalt – für den Dateibrowser kann der Benutzer seine Dateien durchsuchen, um eine MindManager-Datei (MMAP) zu öffnen. | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| Files.ReadWrite | Delegiert | Websiteauflistung, Ordnerauflistung, Dateimetadaten, Dateiinhalt – für den Dateibrowser kann der Benutzer seine Dateien durchsuchen, um eine MindManager-Datei (MMAP) zu öffnen. | - Profildaten: um den Benutzer zu identifizieren und sein Profil anzuzeigen – Dateiinhalt: während der Gemeinsamen Bearbeitungssitzung (gemeinsame Bearbeitung in Echtzeit auf MindManager.mmap-Dateien) | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| Sites.ReadWrite.All | Delegiert | Websiteauflistung, Ordnerauflistung, Dateimetadaten, Dateiinhalt – für den Dateibrowser kann der Benutzer seine Dateien durchsuchen, um eine MindManager-Datei (MMAP) zu öffnen. | Dateiinhalt: während der gemeinsamen Bearbeitungssitzung (gemeinsame Bearbeitung in Echtzeit auf MindManager.mmap-Dateien) | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| User.Read | Delegiert | Profildaten: Um den Benutzer zu identifizieren und sein Profil anzuzeigen | Profildaten: Um den Benutzer zu identifizieren und sein Profil anzuzeigen | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| offline_access | Delegiert | Auf diese Weise können wir eine Datei später im Namen des Benutzers an dem ursprünglichen Speicherort speichern, falls erforderlich. | Dateiinhalt: während der gemeinsamen Bearbeitungssitzung (gemeinsame Bearbeitung in Echtzeit auf MindManager.mmap-Dateien) | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Amazon Web Services | Organisationsname, Organisationsdomäne | Die Organisation benötigt eine Kontoeinrichtung innerhalb unserer Anwendungsinfrastruktur, um die Anwendung in Teams |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Hier behandelt: https://www.mindjet.com/go/mmcloudterms

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/38778' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/38778" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Corel darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden in der Checkliste für die Microsoft Identity Platform Integration überprüft und berücksichtigt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>– Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
