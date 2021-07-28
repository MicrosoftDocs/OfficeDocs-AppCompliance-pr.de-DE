---
title: Anwendungsinformationen für monday.com nach monday.com
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für monday.com, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 7d929b4d9c66aea657d2beb64fa77f31921f59ac
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525459"
---
# <a name="mondaycom"></a>monday.com

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 28, 2020</p>

* <a href="https://teams.microsoft.com/l/app/eab2d3ce-6d6a-4415-abc4-5f40a8317b1f" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001798" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von monday.com an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | monday.com |
| ID | WA200001798 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | monday.com |
| URL der Partnerwebsite | [https://monday.com/](https://monday.com/) |
| URL der Datenschutzrichtlinie | [https://monday.com/terms/privacy](https://monday.com/terms/privacy) |
| URL der Nutzungsbedingungen | [https://monday.com/terms/tos](https://monday.com/terms/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von monday.com darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>Diese Anwendung verwendet microsoft Graph nicht.


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| monday.com verwendet die folgenden Unterprozessoren für die Leistung des Diensts: &#160;https://monday.com/terms/subprocessors |  | monday.com verwendet keine APIs. Wir verwenden die folgenden Microsoft-Frameworks für die Leistung unseres Diensts (wie in unserer Antwort oben beschrieben): &#8216;Botbuilder&#8217; &#8216;Botframework-Connector&#8217; &#8216;@micorosft/teams-js&#8217; |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>monday.com speichert Anwendungsprotokolle, die benutzerseitig generierte Inhalte für einen begrenzten Zeitraum enthalten, um es unserem R &amp; D-Personal zu ermöglichen, Fehler und vom Benutzer gemeldete Probleme zu beheben. Sicherheitsprotokolle, die IP-Adressen enthalten, werden gemäß unserer Datenaufbewahrungsrichtlinie für einen längeren Zeitraum aufbewahrt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>monday.com Dienst wird in der AWS-Infrastruktur in Nordskann über mehrere Verfügbarkeitszonen hinweg gehostet, wobei ein DR-Standort in einer anderen Region eingerichtet ist. Bestimmte Sicherungsdaten werden auf GCP (USA, mehrere Regionen) gespeichert. Der Zugriff auf den monday.com Dienst wird von den Administratoren der Benutzerorganisation gesteuert und mithilfe der folgenden Features erreicht:
- Benutzertypen
- Berechtigungen auf Kontoebene
- Arbeitsbereiche
- Boardtypen
- Berechtigungen auf Boardebene
- Berechtigungen auf Spaltenebene monday.com unterstützen die folgenden Authentifizierungsmethoden:
- Anmeldeinformationen
- Google SSO (für Pro Plan)
- Okta, OneLogin und benutzerdefinierte SAML 2.0 (für den Enterprise-Plan) 2FA per SMS oder über eine Authentifikator-App können optional von den Kontoadministratoren über den Administratorbereich der Plattform aktiviert werden.
Alle ruhenden Daten werden mit AES-256 verschlüsselt. Alle Daten, die über offene Netzwerke übertragen werden, werden mit TLS 1.3 verschlüsselt (mindestens TLS 1.2).

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

