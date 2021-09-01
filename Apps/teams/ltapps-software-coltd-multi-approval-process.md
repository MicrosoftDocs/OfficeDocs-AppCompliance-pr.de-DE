---
title: Application Information for Multi Approval Process LTAPPs by LTAPPs SOFTWARE CO., LTD
ms.author: elmalova
author: elenamalova
ms.date: 07/12/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für LTAPPs für mehrfache Genehmigungsprozesse, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c001622957b8f1a56b776cbe2db034cc9225ef5d
ms.sourcegitcommit: 90e6c1e10d55dc337c0884b63782cc14cf71b3c8
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/31/2021
ms.locfileid: "58836191"
---
# <a name="multi-approval-process-ltapps"></a>Multi Approval Process LTAPPs

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 12, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c1ab19ab-6a95-4f02-b42f-c1df3415e8a8" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003188" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von LTAPPs SOFTWARE CO., LTD für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Multi Approval Process LTAPPs |
| ID | WA200003188 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | LTAPPs SOFTWARE CO.,LTD |
| URL der Partnerwebsite | [https://ltaddins.com](https://ltaddins.com) |
| URL der Datenschutzrichtlinie | [https://ltaddins.com/privacypolicy.html](https://ltaddins.com/privacypolicy.html) |
| URL der Nutzungsbedingungen | [https://ltaddins.com/terms.html](https://ltaddins.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von LTAPPs SOFTWARE CO., LTD darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | Delegiert | Die Mandanten-ID der Benutzerinformationen &amp; | Die App speichert nur die Mandanten-ID.  Da das Add-In alle Daten auf Leave Request Pro App-SharePoint speichert, ist die App, die die Mandanten-ID verwendet hat, der Schlüssel, um die SharePoint App-URL zu finden. | [d2682b2a-2037-4545-94b6-3e7216ecca5f](https://docs.microsoft.com/microsoft-365-app-certification/azure/d2682b2a-2037-4545-94b6-3e7216ecca5f) |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, können zusätzliche andere Microsoft-APIs als Microsoft Graph verwenden, um organisationsspezifische Informationen (OII) zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft auf, Graph diese App verwendet.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint – AllSites.Read &amp; Write | Nein |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die App speichert die Daten des Clients nicht. Alle Daten von Clientspeichern auf der Clientwebsite (Sharepoint-Website). Daten werden nur über SharePoint Rest-API abgerufen/festgelegt, für &amp; die die Azure-App-Registrierung zur Authentifizierung verwendet wurde.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von LTAPPs SOFTWARE CO., LTD darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

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
| Was vermeiden Sie für Ihre App? | ,<br/>– Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/> |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
