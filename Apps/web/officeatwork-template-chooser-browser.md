---
title: Anwendungsinformationen für den Vorlagenauswahlbrowser
ms.author: elmalova
author: elenamalova
ms.date: 06/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für den Vorlagenauswahlbrowser, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f6ec449ba2c90ebebaa662a3adca01d211a225fb
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/05/2022
ms.locfileid: "65221071"
---
# <a name="application-information-for-template-chooser-browser-by-officeatwork"></a>Anwendungsinformationen für den Vorlagenauswahlbrowser nach officeatwork

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Letzte Aktualisierung durch den Entwickler am: 22. Juni 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/officeatwork-ag.template-chooser-browser" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von officeatwork an Microsoft bereitgestellt werden:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | Vorlagenauswahlbrowser |
| ID | officeatwork-ag.template-chooser-browser |
| Name des Partnerunternehmens | officeatwork |
| URL der Partnerwebsite | [https://www.officeatwork.com](https://www.officeatwork.com) |
| URL der Datenschutzrichtlinie | [https://links.officeatwork.com/officeatwork-privacystatement](https://links.officeatwork.com/officeatwork-privacystatement) |
| URL der Nutzungsbedingungen | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von officeatwork darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Auflisten aller [Microsoft Graph Berechtigungen](/graph/permissions-reference), die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegiert/Anwendung)** | **Werden Daten erfasst? Begründung für das Sammeln?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | Delegiert | Es werden keine Daten gespeichert. | Favoriten: Um Daten für die Benutzer lesen und schreiben zu können, OneDrive; OneDrive: Zum Lesen und Schreiben von Daten an die Benutzer OneDrive. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| Group.ReadWrite.All | Delegiert | Es werden keine Daten gespeichert. | Teams: Um Daten in eine Gruppe lesen und schreiben zu können. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| GroupMember.Read.All | Delegiert | Es werden keine Daten gespeichert. | SharePoint Online: Benutzerberechtigung zum Aktivieren des Lesens von Daten aus SharePoint Online. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| Sites.Read.All | Delegiert | Es werden keine Daten gespeichert. | SharePoint Online: Zum Aktivieren des Lesens von Daten aus SharePoint Online. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| User.Read | Delegiert | Es werden keine Daten gespeichert. | Sing-In: Um der officeatwork-App das Lesen der grundlegenden Eigenschaften des Benutzers zu ermöglichen. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| User.Read.All | Delegiert | Es werden keine Daten gespeichert. | Teams: um herauszufinden, zu welchen Gruppen ein Benutzer gehört. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| offline_access | Delegiert | Es werden keine Daten gespeichert. | Sing-In: Um die automatische Anmeldung über Aktualisierungstoken zu aktivieren, müssten sich Benutzer wie ohne sie jedes einzelne Mal manuell anmelden, wenn sie die officeatwork-App starten. Dieser Bereich ist nur für Nicht-SSO-aktivierte Hostanwendungen erforderlich. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| openid | Delegiert | Es werden keine Daten gespeichert. | Sing-In: Benutzer können sich mit ihrem Organisations- und/oder Microsoft-Konto bei der officeatwork-App anmelden | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| Profil | Delegiert | Es werden keine Daten gespeichert. | Sing-In: Zum Anzeigen des angemeldeten Benutzers in der officeatwork-App. Dadurch kann sichergestellt/bestätigt werden, welches Konto für die Anmeldung bei der officeatwork-App verwendet wurde. | dae2eacf-3eb5-4440-baff-984fbd5cae68 |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise andere Microsoft-APIs als Microsoft Graph, um Organisationsinformationen (OII) zu sammeln oder zu verarbeiten. Auflisten aller anderen Microsoft-APIs als Microsoft Graph, die diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Begründung für das Sammeln von OII?** | **Ist OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint-REST-APIs | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder freigibt, listen Sie den von der App nicht von Microsoft stammenden Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder Endbenutzer-identifizierbare Informationen (EUII) in den Telemetriedaten oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Aufbewahrungs- und Entfernungsrichtlinien gelten?

>Ja, Ereignisse umfassen die oid- und tenantId-Eigenschaft und werden an Azure AppInsights gesendet. Die Ereignisse werden nach 90 Tagen automatisch gelöscht. Wenn ein Kunde diese Daten löschen lassen möchte, kann er den in der Datenschutzerklärung angegebenen Link verwenden, um die Löschung dieser Daten zu initiieren.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren der Organisation ihre Informationen in Partnersystemen steuern können? z.B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die Anwendungseinstellungsdaten (Featurekennzeichnungen, Anzeigename der Organisation, TenantId, Liste der Administratoren) werden in einer Azure Cosmos DB-Instanz (eine Datei pro Mandant) gespeichert. Die DB-Dateien sind verschlüsselt, und der Zugriff ist auf ausgewählte Office-Techniker und Supportmitarbeiter beschränkt. Der Kunde kann mithilfe der Admin Center Web App auf die OfficeAtwork-App-Einstellungsdaten zugreifen und diese bearbeiten.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational Identifiable Information) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35385' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35385" target="_blank">Auf einer neuen Registerkarte anzeigen</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von officeatwork darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Response** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden überprüft und eingehalten, die in der Checkliste für die Microsoft Identity Platform Integration aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Sicherheitsstandards |
| Fordert Ihre App Berechtigungen mit den geringsten Berechtigungen für Ihr Szenario an? | Ja |
| Entsprechen die statisch registrierten Berechtigungen Ihrer App genau den Berechtigungen, die ihre App dynamisch und inkrementell anfordert? | Nein |
| Unterstützt Ihre App Mehrinstanzenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie den gesamten umleitenden Unified Resource Identifier (URI), der für Ihre App registriert ist? | Ja |
| Was vermeiden Sie für Ihre App? | - Platzhalter-Umleitungs-URIs,<br/>- Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
