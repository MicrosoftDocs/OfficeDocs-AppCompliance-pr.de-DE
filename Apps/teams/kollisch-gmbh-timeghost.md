---
title: Bewerbungsinformationen für timeghost von K&#246;llisch GmbH
ms.author: elmalova
author: elenamalova
ms.date: 02/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für timeghost, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: ac22c7368da817caf44157bad920221791989245
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552036"
---
# <a name="timeghost"></a>timeghost

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 24. Februar 2021</p>

* <a href="https://teams.microsoft.com/l/app/e3956558-7399-4ec1-848a-c61a2aa95bc1" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001532" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen von K&#246;llisch GmbH an Microsoft:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | timeghost |
| ID | WA200001532 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Köllisch GmbH |
| URL der Partner-Website | [https://timeghost.io/](https://timeghost.io/) |
| URL Teams Anwendungsinfoseite | [https://timeghost.io](https://timeghost.io) |
| URL der Datenschutzrichtlinie | [https://timeghost.io/privacy-policy/](https://timeghost.io/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://timeghost.io/terms-and-conditions/](https://timeghost.io/terms-and-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von der K&#246;llisch GmbH darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | Delegiert | Titel, Startdatum, Enddatum, ID | Kalenderdaten werden bei Buchen eines Kalendereintrages auf einem Projekt gespeichert. | f6f894ce-5b44-4c9b-aff4-253d2fbe8a99 |
>| People.Read | Delegiert | E-Mail-Adresse | Die Daten werden um weitere Team-Mitglieder&#252;gen und die Avatare der Nutzer angezeigt. | f6f894ce-5b44-4c9b-aff4-253d2fbe8a99 |
>| User.Read | Delegiert | Vorname, Nachname, E-Mail-Adresse, Organisation, Telefonnummer, Rolle, Sprache, Location | Beim Anlegen eines Timeghost User-Profils werden diese Daten gespeichert, um die Benutzererfahrung zu verbessern. | f6f894ce-5b44-4c9b-aff4-253d2fbe8a99 |
>| User.ReadBasic.All | Delegiert | Um das Profilbild. | Keine Daten werden gespeichert. | f6f894ce-5b44-4c9b-aff4-253d2fbe8a99 |
>| openid | Delegiert | ID  | Speicherung der ID des Users zur Zuordnung des Users. | f6f894ce-5b44-4c9b-aff4-253d2fbe8a99 |
>| Profil | Delegiert | Vorname, Nachname, E-Mail-Adresse, Organisation, Telefonnummer, Rolle, Sprache, Location | Beim Anlegen eines Timeghost User-Profils werden diese Daten gespeichert, um die Benutzererfahrung zu verbessern. | f6f894ce-5b44-4c9b-aff4-253d2fbe8a99 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Sentry.io | Vorname, Nachname, E-Mail-Adresse, Firmenname  | Zur Fehlerermittlung, Zahlungs&#252;bermittlung |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird kein EUII abgerufen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>E-Mail-Adresse, Benutzer-ID

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Überwachung

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36447' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36447" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von der K&#246;llisch GmbH darüber bereitgestellt, wie diese App mit Authentifizierung, Autorisierung, Best Practices für die Anwendungsregistrierung und anderen Identitätskriterien umgeht.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Können Sie sich in Microsoft Identifizplattform (Azure AD) integrieren?  | Ja |
| Haben Sie alle in der Checkliste für die Microsoft Identity Platform-Integration beschriebenen bewährten Methoden überprüft und eingehalten?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | true |
| Unterstützt Ihre App Conditional Access-Richtlinien? | Nein |
| Fordert Ihre App die geringsten Berechtigungsberechtigungen für Ihr Szenario an? | Ja |
| Gibt die statisch registrierten Berechtigungen Ihrer App die Berechtigungen wieder, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Multi-Tenancy? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle für Ihre App registrierten Unified Resource Identifier (URI) umleiten? | Ja |
| Was vermeiden Sie für Ihre App? | - Wildcard-Umleitungs-URIs,<br/>- OAuth2 Implizite Flow, es sei denn, dies ist für ein SPA erforderlich<br/> |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann zu, dass Aufrufe erfolgreich sind, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
