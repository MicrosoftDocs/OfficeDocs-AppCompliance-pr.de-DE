---
title: Anwendungsinformationen für Prezi Video von Prezi
ms.author: elmalova
author: elenamalova
ms.date: 05/15/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Prezi Video, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security Informationen zum App-Katalog und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: b85c9508c1090afd8faa2c86cff23f58af70f03d
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430394"
---
# <a name="prezi-video"></a>Prezi Video

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 23, 2020</p>

* <a href="https://teams.microsoft.com/l/app/78bbd675-511e-41a2-9a1a-8793920efa9e" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001577" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Prezi an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Prezi Video |
| ID | WA200001577 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Prezi |
| URL der Partnerwebsite | [https://prezi.com](https://prezi.com) |
| URL der Datenschutzrichtlinie | [https://prezi.com/privacy-policy/](https://prezi.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://prezi.com/terms-of-use/](https://prezi.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Prezi darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>Diese Anwendung verwendet microsoft Graph nicht.


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Weitere Informationen finden Sie unter https://prezi.com/privacy-policy/ |  | Die folgenden APIs/SDK werden für die Integration zusammen mit der 1 verwendet. Botbuilder-SDK (python): Mit diesem SDK speichern wir die Azure Active Directory Objekt-ID (von der API als aad_object_id bezeichnet). Wir benötigen diese Informationen, um einen Microsoft Teams Benutzer allen Prezi-Videoinhalten zuzuordnen, die auf prezi.com erstellt wurden.  2. Botbuilder-js (javascript): Mit diesem SDK werden keine Microsoft Teams spezifischen Daten gesammelt. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Der Bot greift nicht auf die erwähnten Listeninformationen zu. | Der Bot greift nicht auf die erwähnten Listeninformationen zu. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Protokollen der Anwendung werden keine EUII oder OII angezeigt.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die folgenden Informationen werden in einer RDS-Datenbank gespeichert:

1. Azure Active Directory Objekt-ID (die von der API als aad_object_id bezeichnet wird) wird gespeichert, um die Videos eines Microsoft Teams Benutzers&#8217;abzurufen. Die aad_object_id wird mithilfe des offiziellen Botbuilder-SDKs von Microsoft&#8217;auf unseren Servern sicher abgerufen.

2. Videolinks, die auf prezi.com erstellt wurden. Auf prezi.com erstellte Inhalte werden gemäß Abschnitt 14 in der folgenden URL gespeichert: https://prezi.com/privacy-policy/ 

Zugriffsrechte auf externe Systeme mit hohem Risiko (z. B. AWS) werden über eine einheitliche Identitäts- und Zugriffsverwaltungsplattform (OneLogin) eines Drittanbieters verwaltet.

Die Kennwortrichtlinie und die mehrstufige Authentifizierung werden für das Personal in der einheitlichen Identitäts- und Zugriffsverwaltungsplattform erzwungen. Die mehrstufige Authentifizierung ist für die Office-IP-Adressen von Fall zu Fall nicht erforderlich.

Von AWS gehostete Dienste und Datenbanken sind standardmäßig von überall aus nicht zugänglich. Explizite eingehende Regeln müssen manuell hinzugefügt werden.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

