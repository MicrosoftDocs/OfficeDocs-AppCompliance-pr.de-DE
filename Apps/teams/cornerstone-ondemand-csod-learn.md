---
title: Anwendungsinformationen für CSOD Learn by Cornerstone OnDemand
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für CSOD Learn, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c1ffba5aaa75b590f85a1012a3ccfafe28e20bc7
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60434374"
---
# <a name="csod-learn"></a>CSOD Learn

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 1, 2021</p>

* <a href="https://teams.microsoft.com/l/app/81726ee9-4d27-47ad-8b22-08147c6f8613" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003020" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von "Cornerstone OnDemand" für Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | CSOD Learn |
| ID | WA200003020 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Cornerstone OnDemand |
| URL der Partnerwebsite | [https://www.cornerstoneondemand.com](https://www.cornerstoneondemand.com) |
| URL der Datenschutzrichtlinie | [https://www.cornerstoneondemand.com/client-privacy-policy/](https://www.cornerstoneondemand.com/client-privacy-policy/) |
| URL der Nutzungsbedingungen | [https://www.microsoft.com/en-us/microsoft-teams/group-chat-...](https://www.microsoft.com/en-us/microsoft-teams/group-chat-software) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von "Cornerstone OnDemand" bereitgestellt und darüber, wie diese App Organisationsdaten sammelt und speichert sowie die Kontrolle, über die Ihre Organisation über die von der App gesammelten Daten verfügt.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>Diese Anwendung verwendet microsoft Graph nicht.


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Organisationsdaten werden zwischen CSOD-Diensten und Microsoft gemeinsam genutzt. Weitere Informationen finden Sie in den Vertragsbedingungen mit CSOD. | Organisationsdaten werden zwischen CSOD-Diensten und Microsoft gemeinsam genutzt. Weitere Informationen finden Sie in den Vertragsbedingungen mit CSOD. | Der CSOD-Dienst verwendet Graph APIs nicht. Wir verwenden die Microsoft Frameworks botbuilder^4.9.2 für die Leistung des Diensts. OII-Daten werden vom Dienst verwendet, um den CSOD-Dienstverbraucher zu identifizieren. Weitere Informationen finden Sie in den Vertragsbedingungen mit CSOD. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Informationen hierzu finden Sie in den Vertragsbedingungen mit CSOD. | Endbenutzer-aadObjectId-Zuordnung zur internen CSOD-Benutzer-ID | Informationen hierzu finden Sie in den Vertragsbedingungen mit CSOD. |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Der CSOD-Dienst speichert Anwendungsprotokolle, die benutzerinteraktion mit der App für einen begrenzten Zeitraum enthalten, um Fehler und vom Benutzer gemeldete Probleme zu beheben. Einzelne Protokollanweisungen bestehen aus der internen Lms-Benutzer-ID des Endbenutzers, dem im CSOD-Dienst konfigurierten Organisationsnamen und der entsprechenden Aktion, die ausgeführt wird. v

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Der Zugriff auf den CSOD-Dienst wird von den Administratoren der Endbenutzerorganisation gesteuert. Weitere Informationen finden Sie in den Vertragsbedingungen mit CSOD.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von "Wirk onDemand" bereitgestellt und darüber, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
