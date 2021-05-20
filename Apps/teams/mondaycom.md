---
title: Anwendungsinformationen für monday.com von monday.com
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für monday.com, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 64fc8e948618b760a3f82ee9c1ac67a32de9afb6
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552926"
---
# <a name="mondaycom"></a>monday.com

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 28. September 2020</p>

* <a href="https://teams.microsoft.com/l/app/eab2d3ce-6d6a-4415-abc4-5f40a8317b1f" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001798" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von microsoft monday.com bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | monday.com |
| ID | WA200001798 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | monday.com |
| URL der Partnerwebsite | [https://monday.com](https://monday.com) |
| URL der Datenschutzrichtlinie | [https://monday.com/privacy](https://monday.com/privacy) |
| URL der Nutzungsbedingungen | [https://monday.com/terms/tos](https://monday.com/terms/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von monday.com darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>Diese Anwendung verwendet keine Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| monday.com verwendet die folgenden Unterverarbeiter für die Leistung des Diensts:&#160;https://monday.com/terms/subprocessors |  | monday.com verwendet keine APIs. Wir verwenden die folgenden Microsoft-Frameworks für die Leistung unseres Diensts (wie in unserer Antwort oben beschrieben): &#8216;botbuilder&#8217; &#8216;botframework-connector&#8217; &#8216;@micorosft/teams-js&#8217; |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Auf EUII wird nicht zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>monday.com speichert Anwendungsprotokolle, die von Benutzern generierte Inhalte für einen begrenzten Zeitraum enthalten, damit unsere Mitarbeiter für forschung und entwicklung Fehler und von Benutzern gemeldete Probleme behandeln &amp; können. Sicherheitsprotokolle, die IP-Adressen enthalten, werden nach unserer Datenaufbewahrungsrichtlinie für einen längeren Zeitraum aufbewahrt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>monday.com wird in der AWS-Infrastruktur in Nord-Virginia über mehrere Verfügbarkeitszonen hinweg gehostet, und eine Dr.-Dr.-Website wurde in einer anderen Region eingerichtet. Bestimmte Sicherungsdaten werden auf GCP (USA, multi-region) gespeichert. Der Zugriff auf den monday.com wird von den Administratoren der Benutzerorganisation gesteuert und wird durch die Verwendung der folgenden Features erreicht:
- Benutzertypen
- Berechtigungen auf Kontoebene
- Arbeitsbereiche
- Boardtypen
- Berechtigungen auf Boardebene
- Berechtigungen auf Spaltenebene monday.com die folgenden Authentifizierungsmethoden unterstützt:
- Anmeldeinformationen
- Google SSO (für Pro Plan)
- Okta, OneLogin und benutzerdefiniertes SAML 2.0 (für den Enterprise-Plan) 2FA über SMS oder über eine Authentifizierungs-App können optional von den Kontoadministratoren über den Administratorbereich der Plattform aktiviert werden.
Alle Ruhedaten werden mit AES-256 verschlüsselt. Alle Daten, die über offene Netzwerke übertragen werden, werden mit TLS 1.3 (mindestens TLS 1.2) verschlüsselt.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

