---
title: Anwendungsinformationen für monday.com nach monday.com
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für monday.com, deren Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
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

* <a href="https://teams.microsoft.com/l/app/eab2d3ce-6d6a-4415-abc4-5f40a8317b1f" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001798" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von monday.com Microsoft zur Verfügung gestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | monday.com |
| ID | WA200001798 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | monday.com |
| URL der Partner-Website | [https://monday.com](https://monday.com) |
| URL der Datenschutzrichtlinie | [https://monday.com/privacy](https://monday.com/privacy) |
| URL der Nutzungsbedingungen | [https://monday.com/terms/tos](https://monday.com/terms/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von monday.com darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>Diese Anwendung verwendet keine Microsoft-Graph.


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| monday.com verwendet die folgenden Unterprozessoren für die Leistung seines Dienstes:&#160;https://monday.com/terms/subprocessors |  | monday.com verwendet keine APIs. Für die Leistung unseres Dienstes verwenden wir die folgenden Microsoft-Frameworks (wie in unserer Antwort oben beschrieben): &#8216;Botbuilder&#8217; &#8216;Botframework-Connector&#8217; &#8216;-micorosft/teams-js&#8217; |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird kein EUII abgerufen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>monday.com speichert Anwendungsprotokolle, die von Benutzern generierte Inhalte für einen begrenzten Zeitraum enthalten, damit unser &amp; FD-Personal Fehler und vom Benutzer gemeldete Probleme beheben kann. Sicherheitsprotokolle, die IP-Adressen enthalten, werden gemäß unserer Datenaufbewahrungsrichtlinie für einen längeren Zeitraum aufbewahrt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>monday.com Service wird in der AWS-Infrastruktur in Nord-Virginia in mehreren Availability Zones gehostet, wobei ein DR-Standort in einer anderen Region eingerichtet ist. Bestimmte Sicherungsdaten werden auf GCP (USA, Multi-Region) gespeichert. Der Zugriff auf den monday.com-Dienst wird von den Administratoren der Benutzerorganisation gesteuert und durch die Verwendung der folgenden Funktionen erreicht:
- Benutzertypen
- Berechtigungen auf Kontoebene
- Arbeitsbereiche
- Board-Typen
- Berechtigungen auf Board-Ebene
- Berechtigungen auf Spaltenebene monday.com unterstützt die folgenden Authentifizierungsmethoden:
- Anmeldeinformationen
- Google SSO (für Pro Plan)
- Okta, OneLogin und benutzerdefinierte SAML 2.0 (für die Enterprise Plan) 2FA über SMS oder über eine Authentifikator-App können optional von den Kontoadministratoren über das Admin-Panel der Plattform aktiviert werden.
Alle ruhenden Daten werden mit AES-256 verschlüsselt. Alle Daten, die über offene Netzwerke übertragen werden, werden mit TLS 1.3 (mindestens TLS 1.2) verschlüsselt.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

