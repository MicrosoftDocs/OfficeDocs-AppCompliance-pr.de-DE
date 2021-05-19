---
title: Anwendungsinformationen für Prezi Video von Prezi
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Prezi Video, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8b689869b4c8799d396a61ccbecd0d1b4a4e5c51
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552836"
---
# <a name="prezi-video"></a>Prezi Video

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 23. Juni 2020</p>

* <a href="https://teams.microsoft.com/l/app/78bbd675-511e-41a2-9a1a-8793920efa9e" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001577" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Prezi Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Prezi Video |
| ID | WA200001577 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Prezi |
| URL der Partner-Website | [https://prezi.com](https://prezi.com) |
| URL der Datenschutzrichtlinie | [https://prezi.com/privacy-policy/201910_NL/](https://prezi.com/privacy-policy/201910_NL/) |
| URL der Nutzungsbedingungen | [https://prezi.com/terms-of-use/201910_NL/](https://prezi.com/terms-of-use/201910_NL/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Prezi darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>Diese Anwendung verwendet keine Microsoft-Graph.


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Für Details besuchen Sie bitte https://prezi.com/privacy-policy/ |  | Die folgenden APIs/SDK werden für die Integration zusammen mit der 1 verwendet. Botbuilder-SDK (python): Mit diesem SDK speichern wir die Azure Active Directory-Objekt-ID (von der API als aad_object_id bezeichnet). Wir benötigen diese Informationen, um einen Microsoft Teams Benutzer allen Prezi Video-bezogenen Inhalten zuzuordnen, die auf prezi.com erstellt wurden.  2. Botbuilder-js (javascript): Mit diesem SDK werden keine Microsoft Teams bestimmten Daten gesammelt. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Der Bot greift nicht auf die genannten Dienstplaninformationen zu. | Der Bot greift nicht auf die genannten Dienstplaninformationen zu. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>In den Protokollen der Anmeldung sind weder EUII noch OII zu finden.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Wir speichern die folgenden Informationen in einer RDS-Datenbank:

1. Azure Active Directory Objekt-ID (von der API als aad_object_id bezeichnet) wird gespeichert, um einen Microsoft Teams Benutzer&#8217;s Videos abzurufen. Die aad_object_id wird mit dem offiziellen Botbuilder sdk von Microsoft&#8217;auf unseren Servern sicher abgerufen.

2. Videolinks, die auf prezi.com erstellt wurden. Auf prezi.com erstellte Inhalte werden gemäß Abschnitt 14 in der folgenden URL gespeichert: https://prezi.com/privacy-policy/ 

Zugriffsrechte auf externe Systeme mit hohem Risiko (wie AWS) werden über eine einheitliche Identitäts- und Zugriffsverwaltungsplattform eines Drittanbieters (OneLogin) verwaltet.

Kennwortrichtlinien und mehrstufige Authentifizierung werden für das Personal in der einheitlichen Identitäts- und Zugriffsverwaltungsplattform erzwungen. Von Fall zu Fall ist von den Office-IP-Adressen keine mehrstufige Authentifizierung erforderlich.

Auf Services und Datenbanken, die von AWS gehostet werden, kann standardmäßig von überall nicht aus zugegriffen werden. explizite eingehende Regeln müssen manuell hinzugefügt werden.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

