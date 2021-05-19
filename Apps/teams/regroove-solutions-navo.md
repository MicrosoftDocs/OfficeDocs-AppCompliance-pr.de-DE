---
title: Anwendungsinformationen für Navo von Regroove Solutions
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Navo, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ef2c71df0559a5a3db4612df5acf86835efe1a71
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553936"
---
# <a name="navo"></a>Navo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 24. August 2020</p>

* <a href="https://teams.microsoft.com/l/app/d8653da2-4682-4b92-b659-485087957897" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001047" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Von Regroove Solutions für Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Navo |
| ID | WA200001047 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Regroove Solutions |
| URL der Partner-Website | [https://getnavo.com](https://getnavo.com) |
| URL der Datenschutzrichtlinie | [https://getnavo.com/privacy-policy/](https://getnavo.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://getnavo.com/terms-of-service/](https://getnavo.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Regroove Solutions darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | Anwendung | Wir speichern die Benutzeranzahl und fragen sie einmal pro Abrechnungszyklus ab. Wir verwenden auch die Miet-ID als ID für die Organisation. | Ermöglicht es uns zu zählen, wie viele Benutzer sich in der Miete befinden, die wir für Abrechnungszwecke verwenden. Außerdem können wir abfragen, in welchen Gruppen sich ein Benutzer befindet, sodass wir sicherheitsbeschneidend zum Schutz bestimmter Daten verwenden können. Wir fragen auch die Miet-ID der Organisation ab. | 75ce4e02-e37b-479c-81c7-438348a2a251 |
>| User.Read | Delegiert | Keine gespeicherten Daten | Anmelden und Benutzerprofil lesen | 75ce4e02-e37b-479c-81c7-438348a2a251 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wir speichern die Miet-ID und die Benutzeranzahl in Stripe. |  | User.Read | Delegiert | Anmelden und Benutzerprofil lesen - Keine Daten gespeichert |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird kein EUII abgerufen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Ja, in Application Insights speichern wir die benutzerauthentifizierte ID und die Benutzerkonto-ID (Tenancy-ID).

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Alle Daten, die wir selbst speichern (nicht über einen Dienst wie Stripe oder Application Insights), werden in einer Azure Cosmos-Datenbank gespeichert. Alle Administratoren verwenden 2FA, und der Zugriff ist auf eine Teilmenge unserer Mitarbeiter beschränkt.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35974' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35974" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

