---
title: Anwendungsinformationen für Wunder365 von JiJi Technologies Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/15/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Wunder365, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c4b1e022c3ed482c3020284f07a7d1f986d7cbb3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552516"
---
# <a name="wunder365"></a>Wunder365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 15. Dezember 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA200000391" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von JiJi Technologies Private Limited für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Wunder365 |
| ID | WA200000391 |
| Office 365 unterstützten Clients | Outlook 2016 oder höher auf Windows, Outlook 2016 oder höher auf dem Mac, Outlook im Web |
| Partnerunternehmensname | JiJi Technologies Private Limited |
| URL der Partnerwebsite | [https://apps4.pro/](https://apps4.pro/) |
| URL der Datenschutzrichtlinie | [https://www.wunder365.com/outlook-addin-privacy-policy](https://www.wunder365.com/outlook-addin-privacy-policy) |
| URL der Nutzungsbedingungen | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von JiJi Technologies Private Limited darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | delegierte | Keine Gespeicherten Daten. | Um Planner-Aufgaben zu erhalten/zu aktualisieren, veröffentlichen Sie Vorgangsupdates im Teamkanal | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| Mail.Send | delegierte | Keine Gespeicherten Daten. | Zulassen, dass App E-Mail-Benachrichtigungen an Benutzer sendet | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| offline_access | delegierte | Keine Gespeicherten Daten. | So halten Sie den Benutzer angemeldet. | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| openid | delegierte | Keine Gespeicherten Daten. | Ermöglicht Benutzern die Anmeldung mit einem Organisationskonto | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| Profil | delegierte | UPN, Benutzer-ID, E-Mail-ID, Mandanten-ID für die Lizenzierungsüberprüfung, kostenlose Lizenz. | Ermöglicht Benutzern die Anmeldung mit einem Organisationskonto | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir protokollieren uns bei Azure Application Insights. Wir protokollieren die Mandanten-ID und die E-Mail-ID des Benutzers, um Probleme zu identifizieren und Kunden bei der Lösung von Problemen zu unterstützen.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Alle Webanwendungen und Storage befinden sich in einem Abonnement, das nicht mit unserem Unternehmens-AAD verbunden ist, mit nur Administratoren, die Zugriff auf die Ressourcen haben. 2FA ist für diese Administratoren erforderlich. 


#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von JiJi Technologies Private Limited darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden geprüft und befolgt, die in der Prüfliste Microsoft Identity Platform aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Erfordern einer mehrstufigen Authentifizierung für Benutzer mit Administratorrollen, Erfordern der mehrstufigen Authentifizierung für Azure-Verwaltungsaufgaben, Blockieren von Anmeldungen für Benutzer, die ältere Authentifizierungsprotokolle verwenden möchten, Erfordern vertrauenswürdiger Speicherorte für die Azure AD Multi-Factor Authentication-Registrierung, Blockieren oder Gewähren des Zugriffs von bestimmten Speicherorten, Blockieren des risikobelastenden Anmeldeverhaltens |
| Bittet Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordern wird? | Ja |
| Unterstützt Ihre App mehrere Mandanzfähigkeiten? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle umgeleiteten Unified Resource Identifier (URI), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | - UrIs für die Platzhalterumleitung,<br/>- OAuth2 Implizite Flow, es sei denn, dies ist für eine SPA erforderlich<br/>– Fluss mit Kennwortanmeldeinformationen (Password Credential, ROPC) des Ressourcenbesitzers |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
