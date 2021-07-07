---
title: Anwendungsinformationen für Navo von Regroove Solutions
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Navo, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 11346ff15831615ac6b617d8d14f83f38c7de0a5
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/02/2021
ms.locfileid: "53283109"
---
# <a name="navo"></a>Navo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 24. August 2020</p>

* <a href="https://teams.microsoft.com/l/app/d8653da2-4682-4b92-b659-485087957897" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001047" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Regroove Solutions für Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Navo |
| ID | WA200001047 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Regroove Solutions |
| URL der Partnerwebsite | [https://regroove.ca ; https://getnavo.com](https://regroove.ca ; https://getnavo.com) |
| URL der Datenschutzrichtlinie | [https://getnavo.com/privacy-policy/](https://getnavo.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://getnavo.com/terms-of-service/](https://getnavo.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Regroove Solutions dazu bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | Anwendung | Wir speichern die Benutzeranzahl und fragen sie einmal pro Abrechnungszyklus ab. Wir verwenden auch die Mandanten-ID als ID für die Organisation. | Ermöglicht uns zu zählen, wie viele Benutzer im Mandanten sind, die wir für Abrechnungszwecke verwenden. Außerdem können wir abfragen, in welchen Gruppen sich ein Benutzer befindet, damit wir die Sicherheitskürzung verwenden können, um bestimmte Daten zu schützen. Außerdem fragen wir die Mandanten-ID der Organisation ab. | 75ce4e02-e37b-479c-81c7-438348a2a251 |
>| User.Read | Delegiert | Keine Daten gespeichert | Anmelden und Benutzerprofil lesen | 75ce4e02-e37b-479c-81c7-438348a2a251 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wir speichern die Mandanten-ID und die Benutzeranzahl in Stripe. |  | User.Read | Delegiert | Anmelden und Benutzerprofil lesen – keine Daten gespeichert |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Ja, in Anwendung Insights speichern wir die authentifizierte Benutzer-ID und die Benutzerkonto-ID (Mandanten-ID).

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Alle Daten, die wir speichern (nicht über einen Dienst wie Stripe oder Application Insights), werden in einer Azure Cosmos-Datenbank gespeichert. Alle Administratoren verwenden 2FA, und der Zugriff ist auf eine Teilmenge unserer Mitarbeiter beschränkt.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35974' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35974" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

