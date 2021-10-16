---
title: Anwendungsinformationen für E-Mail-TeamMate von harmon.ie
ms.author: elmalova
author: elenamalova
ms.date: 08/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Email TeamMate, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c36dba77d67a638c035b34cea1d88113fb082466
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411640"
---
# <a name="email-teammate"></a>Email TeamMate

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 10, 2021</p>

* <a href="https://teams.microsoft.com/l/app/3ae27f31-ceea-4d13-a212-cdc9d786eae1" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002338" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von harmon.ie an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Email TeamMate |
| ID | WA200002338 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | harmon.ie |
| URL der Partnerwebsite | [https://harmon.ie](https://harmon.ie) |
| URL der Seite mit Teams Anwendungsinformationen | [https://harmon.ie](https://harmon.ie) |
| URL der Datenschutzrichtlinie | [https://harmon.ie/legal/privacy-policy](https://harmon.ie/legal/privacy-policy) |
| URL der Nutzungsbedingungen | [https://harmon.ie/legal/teammate-eula](https://harmon.ie/legal/teammate-eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von harmon.ie darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Chat.Read | Delegiert | Von TeamMate erforderlich, um Chatmitglieder einer bestimmten Unterhaltung abzurufen, um Dateien freizugeben, die in SharePoint/One-Laufwerk mit den Chatmitgliedern der Unterhaltung gespeichert sind | keine | [74a31d8c-1ee9-4fb8-bc22-640ba5f457f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/74a31d8c-1ee9-4fb8-bc22-640ba5f457f4) |
>| Files.ReadWrite.All | Delegiert | Von TeamMate zum Speichern von E-Mail-Anlagen &amp; in SharePoint/Teams/OneDrive erforderlich | keine | [74a31d8c-1ee9-4fb8-bc22-640ba5f457f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/74a31d8c-1ee9-4fb8-bc22-640ba5f457f4) |
>| Mail.ReadWrite | Delegiert | TeamMate muss die E-Mails des Benutzers anzeigen und auf in Teams gespeicherte E-Mails antworten. | keine | [74a31d8c-1ee9-4fb8-bc22-640ba5f457f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/74a31d8c-1ee9-4fb8-bc22-640ba5f457f4) |
>| People.Read | Delegiert | TeamMate muss nach E-Mails von Personen suchen und Personen vorschlagen, mit denen Sie häufig Kontakt aufnehmen. | keine | [74a31d8c-1ee9-4fb8-bc22-640ba5f457f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/74a31d8c-1ee9-4fb8-bc22-640ba5f457f4) |
>| User.Read | Delegiert | ermöglicht Benutzern die Anmeldung bei TeamMate mit ihrem Konto und ermöglicht TeamMate, grundlegende Benutzerprofilinformationen anzuzeigen. | keine | [74a31d8c-1ee9-4fb8-bc22-640ba5f457f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/74a31d8c-1ee9-4fb8-bc22-640ba5f457f4) |
>| User.ReadBasic.All | Delegiert | Von TeamMate erforderlich, um E-Mail-Adressen von Chatmitgliedern aufzulösen, in der Reihenfolge, in der die in OneDrive gespeicherten Freigabedateien mit ihnen gespeichert sind  | keine | [74a31d8c-1ee9-4fb8-bc22-640ba5f457f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/74a31d8c-1ee9-4fb8-bc22-640ba5f457f4) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Nutzungsdaten und Benutzer upn

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>-

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36364' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36364" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von harmon.ie darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

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
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

