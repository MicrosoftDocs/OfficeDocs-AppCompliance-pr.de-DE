---
title: Anwendungsinformationen für Tikit von Cireson
ms.author: elmalova
author: elenamalova
ms.date: 06/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Tikit, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: b427ac7258c9849f6d003a6e9afe51f3db9fe784
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414741"
---
# <a name="tikit"></a>Tikit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 4, 2021</p>

* <a href="https://teams.microsoft.com/l/app/b13c40ee-e073-459e-96b5-3f3cca046a37" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002602" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Von Grapheson an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Tikit |
| ID | WA200002602 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Cireson |
| URL der Partnerwebsite | [https://tikit.ai](https://tikit.ai) |
| URL der Seite mit Teams Anwendungsinformationen | [https://tikit.ai](https://tikit.ai) |
| URL der Datenschutzrichtlinie | [https://tikit.ai/privacy-statement/](https://tikit.ai/privacy-statement/) |
| URL der Nutzungsbedingungen | [https://tikit.ai/terms-service/](https://tikit.ai/terms-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Ihnen zur Verfügung gestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Device.Read | Anwendung | Benutzerdiagramminformationen, die für einmaliges Anmelden über teams-Bot-Kommunikation verwendet werden  | Wir speichern Benutzerrollen, Vornamen, Vornamen, E-Mail, AAD-ID, Teams Benutzer-ID. Diese Informationen werden für Anwendungsauthentifizierung, Sicherheit, RBAC, Teams-Integration, Teams-Benachrichtigungen und Benutzerbeziehungszuordnung verwendet.   | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |
>| Directory.AccessAsUser.All | Delegiert | Gruppennamen und Rollen für RBAC | Rollenname des Gruppennamens, &amp; muss eine sichere zugeordnete Zugriffssteuerung bereitstellen. | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |
>| Directory.Read.All | Delegiert | Gruppennamen und Rollen für RBAC | Rollenname des Gruppennamens, &amp; muss eine sichere zugeordnete Zugriffssteuerung bereitstellen. | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |
>| Group.Read.All | Beide | Gruppennamen und Rollen für RBAC | Gruppennamen und Rollen für RBAC | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |
>| User.Read | Delegiert | Benutzerrollen, Familienname, Vorname, E-Mail, AAD-ID, Teams Benutzer-ID, die für die Authentifizierung verwendet wird  | Benutzerrollen, Familienname, Vorname, E-Mail, AAD-ID, Teams Benutzer-ID, die für die Authentifizierung verwendet wird  | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |
>| User.Read.All | Anwendung | Benutzerrollen, Familienname, Vorname, E-Mail, AAD-ID, Teams Benutzer-ID, die für die Authentifizierung verwendet wird  | Benutzerrollen, Familienname, Vorname, E-Mail, AAD-ID, Teams Benutzer-ID, die für die Authentifizierung verwendet wird  | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |
>| User.ReadBasic.All | Delegiert | Benutzerrollen, Familienname, Vorname, E-Mail, AAD-ID, Teams Benutzer-ID, die für die Authentifizierung verwendet wird  | Benutzerrollen, Familienname, Vorname, E-Mail, AAD-ID, Teams Benutzer-ID, die für die Authentifizierung verwendet wird  | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |
>| email | Delegiert | Benutzer-E-Mail, die für die Anmeldung und die zugehörige Identifikation verwandter Entitäten verwendet wird. &quot;Zugewiesener Benutzer&quot; | Benutzer-E-Mail, die für die Anmeldung und die zugehörige Identifikation verwandter Entitäten verwendet wird. &quot;Zugewiesener Benutzer&quot; | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |
>| openid | Delegiert | wird für die Authentifizierung über MSAL gemäß Anforderungen verwendet.  | wird für die Authentifizierung über MSAL gemäß Anforderungen verwendet.  | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |
>| Profil | Delegiert | wird für die Authentifizierung über MSAL gemäß Anforderungen verwendet.  | wird für die Authentifizierung über MSAL gemäß Anforderungen verwendet.  | [b13c40ee-e073-459e-96b5-3f3cca046a37](https://docs.microsoft.com/microsoft-365-app-certification/azure/b13c40ee-e073-459e-96b5-3f3cca046a37) |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise zusätzliche Andere Microsoft-APIs als Microsoft Graph, um organisationsspezifische Informationen (OII) zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft auf, Graph diese App verwendet.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| QnA Maker | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Name und E-Mail für Benutzerentitätsbeziehungen &quot; Ticket Requestor&quot;  | Name und E-Mail  | für Benutzerentitätsbeziehungen &quot; Ticket Requestor&quot;  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir speichern den Firmennamen, die Mandanten-ID, die E-Mail-Adresse, die Bot-Client-ID in App-Insights mit einer 30-dat-Aufbewahrungsrichtlinie.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>In einem Partnersystem sind keine Daten vorhanden.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von DerEnson bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Mehrstufige Authentifizierung, zulassen, dass nur in Intune registrierte Geräte auf bestimmte Dienste zugreifen, Benutzerspeicherorte und IP-Bereich einschränken |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>- Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

