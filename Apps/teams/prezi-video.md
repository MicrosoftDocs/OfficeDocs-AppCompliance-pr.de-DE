---
title: Anwendungsinformationen für Prezi Video von Prezi
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Prezi Video, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security#A0 und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
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

* <a href="https://teams.microsoft.com/l/app/78bbd675-511e-41a2-9a1a-8793920efa9e" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001577" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Prezi an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Prezi Video |
| ID | WA200001577 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Prezi |
| URL der Partnerwebsite | [https://prezi.com](https://prezi.com) |
| URL der Datenschutzrichtlinie | [https://prezi.com/privacy-policy/201910_NL/](https://prezi.com/privacy-policy/201910_NL/) |
| URL der Nutzungsbedingungen | [https://prezi.com/terms-of-use/201910_NL/](https://prezi.com/terms-of-use/201910_NL/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Prezi darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>Diese Anwendung verwendet keine Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Weitere Informationen finden Sie unter https://prezi.com/privacy-policy/ |  | Die folgenden APIs/SDK werden für die Integration zusammen mit 1 verwendet. Botbuilder-SDK (python): Mit diesem SDK speichern wir die Azure Active Directory-Objekt-ID (von der API als aad_object_id). Wir benötigen diese Informationen, um Microsoft Teams benutzerbezogenen Inhalten von Prezi Video zu zuordnungen, die auf prezi.com.  2. Botbuilder-js (javascript): Microsoft Teams werden keine bestimmten Daten mit diesem SDK erfasst. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Der Bot hat keinen Zugriff auf die erwähnten Rosterinformationen. | Der Bot hat keinen Zugriff auf die erwähnten Rosterinformationen. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Protokollen der Anwendung werden keine EUII oder OII angezeigt.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir speichern die folgenden Informationen in einer RDS-Datenbank:

1. Azure Active Directory Objekt-ID (von der API als aad_object_id bezeichnet) wird gespeichert, um ein Microsoft Teams-&#8217;-Videos zu erhalten. Die aad_object_id wird mit dem offiziellen Botbuilder sdk von Microsoft&#8217;auf unseren Servern sicher abgerufen.

2. Videolinks, die auf prezi.com. Inhalte, die auf prezi.com erstellt werden, werden nach Abschnitt 14 in der folgenden URL gespeichert: https://prezi.com/privacy-policy/ 

Zugriffsrechte auf externe Systeme mit hohem Risiko (z. B. AWS) werden über eine einheitliche Identitäts- und Zugriffsverwaltungsplattform (OneLogin) eines Drittanbieters verwaltet.

Kennwortrichtlinie und mehrstufige Authentifizierung werden für das Personal in der einheitlichen Identitäts- und Zugriffsverwaltungsplattform erzwungen. Von Fall zu Fall ist die mehrstufige Authentifizierung von den Office-IP-Adressen nicht erforderlich.

Von AWS gehostete Dienste und Datenbanken sind standardmäßig von keinem beliebigen Ort aus zugänglich. Explizite eingehende Regeln müssen manuell hinzugefügt werden.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

