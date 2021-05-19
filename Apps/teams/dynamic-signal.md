---
title: Anwendungsinformationen für dynamisches Signal durch dynamisches Signal
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Dynamic Signal, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen sowie Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 0d3c59f6809bafe16eec2a1d709f40a980576b1b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552226"
---
# <a name="dynamic-signal"></a>Dynamic Signal

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://teams.microsoft.com/l/app/6f98619e-a822-4a74-8ee9-af6a358f2750" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000102" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Dynamic Signal Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Dynamic Signal |
| ID | WA200000102 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Dynamic Signal |
| URL der Partner-Website | [https://dynamicsignal.com](https://dynamicsignal.com) |
| URL Teams Anwendungsinfoseite | [https://support.dynamicsignal.com/hc/en-us/requests/new?tic...](https://support.dynamicsignal.com/hc/en-us/requests/new?ticket_form_id=360000290032) |
| URL der Datenschutzrichtlinie | [https://dynamicsignal.com/privacy/](https://dynamicsignal.com/privacy/) |
| URL der Nutzungsbedingungen | [https://dynamicsignal.com/terms-of-use/platform-terms-of-us...](https://dynamicsignal.com/terms-of-use/platform-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Dynamic Signal darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegiert | Dynamic Signal synchronisiert Benutzer von Azure AD mit seiner Plattform, um eine optimierte Aktivierung und Deaktivierung von Benutzern in Echtzeit zu ermöglichen. Daten werden in Dynamic Signal gespeichert, damit Benutzer diese Anwendung während der Synchronisierung verwenden können. | Leseberechtigungen eines bestimmten Benutzers zum Synchronisieren von Dynamic Signal-Plattformbenutzern mit Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| User.Read.All | Delegiert | Dynamic Signal synchronisiert Benutzer von Azure AD mit seiner Plattform, um eine optimierte Aktivierung und Deaktivierung von Benutzern in Echtzeit zu ermöglichen. Daten werden in Dynamic Signal gespeichert, damit Benutzer diese Anwendung während der Synchronisierung verwenden können. | Leseberechtigungen eines bestimmten Benutzers zum Synchronisieren von Dynamic Signal-Plattformbenutzern mit Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| offline_access | Delegiert | Dynamic Signal synchronisiert Benutzer von Azure AD mit seiner Plattform, um eine optimierte Aktivierung und Deaktivierung von Benutzern in Echtzeit zu ermöglichen. Daten werden in Dynamic Signal gespeichert, damit Benutzer diese Anwendung während der Synchronisierung verwenden können. | Behalten Sie den Zugriff auf die Gruppen und Teams des Mandanten bei. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| openid | Delegiert | Dynamic Signal synchronisiert Benutzer von Azure AD mit seiner Plattform, um eine optimierte Aktivierung und Deaktivierung von Benutzern in Echtzeit zu ermöglichen. Daten werden in Dynamic Signal gespeichert, damit Benutzer diese Anwendung während der Synchronisierung verwenden können. | Authentifizieren Sie Benutzer mit der Dynamic Signal Application. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| OpenID-Anmeldung mit openid directory.readwrite.all Zugriff auf die Domäne und Gruppen des Mandanten, Hinzufügen einer App zu einem Team offline_access Zugriff auf die Gruppen und Teams des Mandanten beibehalten | openid Zulassen einer unabhängigen Authentifizierung. directory.readwrite.all Zugriff auf die Domäne und Gruppen des Mandanten, fügen Sie eine App zu einem Team hinzu offline_access behalten Sie Zugriff auf die Gruppen und Teams des Mandanten Hinweis: Die Anwendung von Dynamic Signal verwendet den Teams-Bot, um Gruppen und Berechtigungen, die in Dynamic Signal erstellt wurden, auf Teams anzuwenden, damit ein Benutzer, der in Dynamic Signal aktiv ist, Zugriff auf dieselben Gruppen und Benutzer hat, die innerhalb Teams. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Die Dynamic Signal App und Platform nutzen Benutzerinformationen, um die Integration mit Microsoft Teams zu erleichtern. Diese Informationen stehen Benutzern mit entsprechenden Berechtigungen innerhalb der Dynamic Signal-Plattform zur Verfügung. Relevante Informationen sind Name, Anzeigename und E-Mail. Diese Informationen werden in den Dynamic Signal Plattformprotokollen gemäß den Richtlinien der jeweiligen Organisation mit der Dynamic Signal Lizenz gespeichert.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Die PII-Daten, die während der Registrierung gesammelt und innerhalb der Dynamic Signal-Plattform gespeichert werden, umfassen: Vorname, Nachname, E-Mail/Bezeichner und alle benutzerdefinierten Felder, die von der Marke und/oder Agenturpartnern eingerichtet werden. Wenn Mitglieder Facebook oder Twitter mit oAuth Registration verwenden, werden einige der offengelegten Nutzerdaten der Dynamic Signal-Plattform angezeigt, um Daten vorab auszufüllen. Diese Daten umfassen Name, Standort und Foto. Benutzer haben die Kontrolle darüber, welche Informationen und Daten den Benutzern auf den Bio-Seiten für die Community präsentiert werden. Mitglieder können das Laden von persönlichen oder Markenfotos, das Verbinden von sozialen Konten/Kanälen und Nutzungs-/Punkte im Programm, das auf der Bio-Seite angezeigt werden soll, in Anspruch ziehen.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

