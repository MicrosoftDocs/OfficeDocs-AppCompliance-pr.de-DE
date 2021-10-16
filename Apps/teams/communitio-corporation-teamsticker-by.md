---
title: Anwendungsinformationen für TeamSticker von Communitio by Communitio Corporation
ms.author: elmalova
author: elenamalova
ms.date: 01/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für TeamSticker von Communitio, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d90eba269fb77fa8b86d20da16ef70baa72d686c
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411813"
---
# <a name="teamsticker-by-communitio"></a>TeamSticker by Communitio

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: January 5, 2021</p>

* <a href="https://teams.microsoft.com/l/app/bceca1f0-723f-44d0-b732-b3506c0a641d" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000894" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von der Communitio Corporation an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | TeamSticker by Communitio |
| ID | WA200000894 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Communitio Corporation |
| URL der Partnerwebsite | [https://www.teamsuite.biz](https://www.teamsuite.biz) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.teamsuite.biz/feature/](https://www.teamsuite.biz/feature/) |
| URL der Datenschutzrichtlinie | [https://www.teamsuite.biz/privacy/](https://www.teamsuite.biz/privacy/) |
| URL der Nutzungsbedingungen | [https://www.teamsuite.biz/terms/](https://www.teamsuite.biz/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von der Communitio Corporation darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Chat.ReadWrite | Anwendung |  Da Anwendungsbeiträge zum Chatten. | Die Anwendung speichert keine Daten. | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |
>| Group.ReadWrite.All | Beide | Anwendung sammelt Gruppen-ID und Gruppenname. | Die Anwendung speichert das Gruppen-ID- und Namenspaar. | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |
>| User.Read | Delegiert | Die Anwendung erfasst das Profilbild des Benutzers. | Die Anwendung speichert das Profilbild des Benutzers, um das Benutzersymbol anzuzeigen. | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |
>| User.Read.All | Beide | Die Anwendung sammelt die Objekt-ID/E-Mail/den Namen des Benutzers, um den Benutzer zum Senden der Karte zu finden. | Die Anwendung speichert in diesem Fall keine Daten. | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |
>| offline_access | Delegiert | Application collect user's api token to use User.Read / User.Read.All in background. | Die Anwendung speichert das API-Token des Benutzers, um User.Read /User.Read.All im Hintergrund zu verwenden. | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |
>| openid | Delegiert | Es werden keine Daten gesammelt. | Die Anwendung verwendet diese Berechtigung, um sich über openid anzumelden. | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |
>| Profil | Delegiert | Die Anwendung sammelt die ObjectId/E-Mail/den Namen des Benutzers. | Die Anwendung speichert die ObjectId/E-Mail/den Namen des Benutzers. | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise zusätzliche Andere Microsoft-APIs als Microsoft Graph zum Sammeln oder Verarbeiten von organisationsbezogenen Informationen (OII). Auflisten aller anderen Microsoft-APIs als Microsoft Graph diese App verwendet wird.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>|  Bot Framework-REST-API | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Da Sie über die Berechtigung "User.Read.All" verfügen. | Nein |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Nicht zutreffend

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36366' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36366" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von der Communitio Corporation darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>– Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

