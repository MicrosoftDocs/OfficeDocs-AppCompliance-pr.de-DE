---
title: Application Information for Wunder365 for Office by JiJi Technologies Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/15/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Wunder365 für Office, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 85e7b014e9bbc5754016bd83a7734ff2481aa8dc
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/02/2021
ms.locfileid: "53283289"
---
# <a name="wunder365-for-office"></a>Wunder365 für Office

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 15, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA200001529" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von JiJi Technologies Private Limited to Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Wunder365 für Office |
| ID | WA200001529 |
| Office 365 unterstützten Clients | Excel 2016 oder höher auf dem Mac, Excel 2013 oder höher auf Windows, Excel im Web, Word 2016 oder höher auf Mac, Word im Web, Word 2013 oder höher auf Windows, OneNote im Web |
| Name des Partnerunternehmens | JiJi Technologies Private Limited |
| URL der Partnerwebsite | [https://www.jijitechnologies.com](https://www.jijitechnologies.com) |
| URL der Datenschutzrichtlinie | [https://www.wunder365.com/office-addin-privacy-policy](https://www.wunder365.com/office-addin-privacy-policy) |
| URL der Nutzungsbedingungen | [https://www.wunder365.com/terms-of-service](https://www.wunder365.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von JiJi Technologies Private Limited darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | Delegiert | Es werden keine Daten gespeichert. | Um Planner-Aufgaben abzurufen/zu aktualisieren, stellen Sie Aufgabenupdates im Teamkanal bereit | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| Mail.Send | Delegiert | Es werden keine Daten gespeichert. | Zulassen, dass die App E-Mail-Benachrichtigungen an Benutzer sendet | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| offline_access | Delegiert | Es werden keine Daten gespeichert. | So halten Sie den Benutzer angemeldet. | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| openid | Delegiert | Es werden keine Daten gespeichert. | Ermöglicht Benutzern die Anmeldung mit einem Organisationskonto | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| Profil | Delegiert | UPN, Benutzer-ID, E-Mail-ID, Mandanten-ID für lizenzierungsüberprüfung, kostenlose Lizenz. | Ermöglicht Benutzern die Anmeldung mit einem Organisationskonto | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir melden uns bei Azure Application Insights an. Wir protokollieren die Mandanten-ID und die E-Mail-ID des Benutzers, um Probleme zu identifizieren und Kunden bei der Lösung von Problemen zu unterstützen.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Alle Webanwendungen und Storage Ressourcen befinden sich in einem Abonnement, das nicht mit unserem Unternehmens-AAD verbunden ist, mit nur Administratoren, die Zugriff auf die Ressourcen haben. 2FA ist für diese Administratoren erforderlich. 


#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von JiJi Technologies Private Limited darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Mehrstufige Authentifizierung für Benutzer mit Administratorrollen, Mehrstufige Authentifizierung für Azure-Verwaltungsaufgaben, Blockieren von Anmeldungen für Benutzer, die versuchen, Legacyauthentifizierungsprotokolle zu verwenden, Anfordern vertrauenswürdiger Speicherorte für die Azure AD Multi-Factor Authentication-Registrierung, Blockieren oder Gewähren des Zugriffs von bestimmten Speicherorten, Blockieren riskanten Anmeldeverhaltens |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>- Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
