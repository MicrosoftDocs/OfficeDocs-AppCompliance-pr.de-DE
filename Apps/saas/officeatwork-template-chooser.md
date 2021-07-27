---
title: Anwendungsinformationen für die Vorlagenauswahl nach Officeatwork
ms.author: elmalova
author: elenamalova
ms.date: 06/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für die Vorlagenauswahl, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7980401493799d010b83a5bdaec1c95247efd511
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/22/2021
ms.locfileid: "53522258"
---
# <a name="template-chooser"></a>Template Chooser

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 22, 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/officeatwork-ag.template-chooser" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von officeatwork an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Template Chooser |
| ID | officeatwork-ag.template-chooser |
| Name des Partnerunternehmens | officeatwork |
| URL der Partnerwebsite | [https://www.officeatwork.com](https://www.officeatwork.com) |
| URL der Datenschutzrichtlinie | [https://links.officeatwork.com/officeatwork-privacystatement](https://links.officeatwork.com/officeatwork-privacystatement) |
| URL der Nutzungsbedingungen | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Office-Mitarbeitern darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.ReadWrite.All | Delegiert | Es werden keine Daten gespeichert. | Favoriten: um Daten für die Benutzer OneDrive lesen und schreiben zu können; OneDrive: Um Daten für die Benutzer OneDrive lesen und schreiben zu können. | [dae2eacf-3eb5-4440-baff-984fbd5cae68](https://docs.microsoft.com/microsoft-365-app-certification/azure/dae2eacf-3eb5-4440-baff-984fbd5cae68) |
>| Group.ReadWrite.All | Delegiert | Es werden keine Daten gespeichert. | Teams: Um Daten in einer Gruppe lesen und schreiben zu können. | [dae2eacf-3eb5-4440-baff-984fbd5cae68](https://docs.microsoft.com/microsoft-365-app-certification/azure/dae2eacf-3eb5-4440-baff-984fbd5cae68) |
>| GroupMember.Read.All | Delegiert | Es werden keine Daten gespeichert. | SharePoint Online: Benutzerberechtigung zum Aktivieren des Lesens von Daten aus SharePoint Online. | [dae2eacf-3eb5-4440-baff-984fbd5cae68](https://docs.microsoft.com/microsoft-365-app-certification/azure/dae2eacf-3eb5-4440-baff-984fbd5cae68) |
>| Sites.Read.All | Delegiert | Es werden keine Daten gespeichert. | SharePoint Online: Zum Aktivieren des Lesens von Daten aus SharePoint Online. | [dae2eacf-3eb5-4440-baff-984fbd5cae68](https://docs.microsoft.com/microsoft-365-app-certification/azure/dae2eacf-3eb5-4440-baff-984fbd5cae68) |
>| User.Read | Delegiert | Es werden keine Daten gespeichert. | Sing-In: So aktivieren Sie die Officeatwork-App, um die grundlegenden Eigenschaften des Benutzers zu lesen. | [dae2eacf-3eb5-4440-baff-984fbd5cae68](https://docs.microsoft.com/microsoft-365-app-certification/azure/dae2eacf-3eb5-4440-baff-984fbd5cae68) |
>| User.Read.All | Delegiert | Es werden keine Daten gespeichert. | Teams: Um herauszufinden, zu welchen Gruppen ein Benutzer gehört. | [dae2eacf-3eb5-4440-baff-984fbd5cae68](https://docs.microsoft.com/microsoft-365-app-certification/azure/dae2eacf-3eb5-4440-baff-984fbd5cae68) |
>| offline_access | Delegiert | Es werden keine Daten gespeichert. | Sing-In: Um die automatische Anmeldung über Aktualisierungstoken wie ohne zu aktivieren, müssten sich Benutzer jedes Mal manuell anmelden, wenn sie die Officeatwork-App starten. Dieser Bereich ist nur für Nicht-SSO-aktivierte Hostanwendungen erforderlich. | [dae2eacf-3eb5-4440-baff-984fbd5cae68](https://docs.microsoft.com/microsoft-365-app-certification/azure/dae2eacf-3eb5-4440-baff-984fbd5cae68) |
>| openid | Delegiert | Es werden keine Daten gespeichert. | Sing-In: Damit sich Benutzer mit ihrem Organisations- und/oder Microsoft-Konto bei der OfficeAtwork-App anmelden können | [dae2eacf-3eb5-4440-baff-984fbd5cae68](https://docs.microsoft.com/microsoft-365-app-certification/azure/dae2eacf-3eb5-4440-baff-984fbd5cae68) |
>| Profil | Delegiert | Es werden keine Daten gespeichert. | Sing-In: Um den angemeldeten Benutzer in der Officeatwork-App anzuzeigen. Dadurch kann sichergestellt/bestätigt werden, welches Konto für die Anmeldung bei der Officeatwork-App verwendet wurde. | [dae2eacf-3eb5-4440-baff-984fbd5cae68](https://docs.microsoft.com/microsoft-365-app-certification/azure/dae2eacf-3eb5-4440-baff-984fbd5cae68) |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise zusätzliche Andere Microsoft-APIs als Microsoft Graph zum Sammeln oder Verarbeiten von organisationsbezogenen Informationen (OII). Listen Sie alle anderen Microsoft-APIs als Microsoft auf, Graph diese App verwendet.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint-REST-APIs | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Ja, Ereignisse enthalten die oid- und tenantId und werden an Azure AppInsights gesendet. Die Ereignisse werden nach 90 Tagen automatisch gelöscht. Wenn ein Kunde möchte, dass diese Daten gelöscht werden, kann er den link in der Datenschutzerklärung verwenden, um die Löschung dieser Daten zu initiieren.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die Anwendungseinstellungsdaten (Featurekennzeichen, Anzeigename der Organisation, Mandanten-ID, Liste der Administratoroide) werden in einer Azure Cosmos DB-Instanz (eine Datei pro Mandant) gespeichert. Die DB-Dateien sind verschlüsselt, und der Zugriff ist auf ausgewählte Bürotechniker und Supportmitarbeiter beschränkt. Der Kunde kann mithilfe der Admin Center Web App auf die Einstellungsdaten der Officeatwork-App zugreifen und diese bearbeiten.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35385' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35385" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Officeatwork darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Sicherheitsstandards |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Nein |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>- Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
