---
title: Anwendungsinformationen für Webex-Anruf von Cisco
ms.author: elmalova
author: elenamalova
ms.date: 01/04/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Webex Call, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 8cd5499529eb41a5a840c9a7792e9b47f9a6c877
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552286"
---
# <a name="webex-call"></a>Webex Call

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 4. Januar 2021</p>

* <a href="https://teams.microsoft.com/l/app/0924e969-85d8-4acb-8687-faacd6abd228" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001495" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Cisco Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Webex Call |
| ID | WA200001495 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Cisco |
| URL der Partner-Website | [https://www.cisco.com/c/en/us/solutions/collaboration/webex...](https://www.cisco.com/c/en/us/solutions/collaboration/webex-teams.html) |
| URL Teams Anwendungsinfoseite | [Nicht zutreffend](N/A) |
| URL der Datenschutzrichtlinie | [https://www.cisco.com/c/en/us/about/legal/privacy-full.html](https://www.cisco.com/c/en/us/about/legal/privacy-full.html) |
| URL der Nutzungsbedingungen | [https://www.cisco.com/c/en/us/products/universal-cloud-agre...](https://www.cisco.com/c/en/us/products/universal-cloud-agreement.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Cisco darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Chat.Read | Delegiert | Holen Sie sich Chat-Mitglieder, so könnte das andere Mitglied in privaten Chat mit Cisco WebEx anrufen | Die App würde KEINE Daten in ihren Datenbanken speichern | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |
>| Contacts.Read | Delegiert | Abrufen von Benutzerkontakten, damit Benutzer Kontakte mit Cisco WebEx aufrufen können | Die App würde KEINE Daten in ihren Datenbanken speichern | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |
>| User.Read | Delegiert | Erhalten Sie Benutzer-E-Mails, Telefone, damit sie Cisco WebEx starten können, um E-Mails oder Telefone anzurufen | Die App würde KEINE Daten in ihren Datenbanken speichern | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |
>| User.ReadBasic.All | Delegiert | Erhalten Sie Benutzer-E-Mails, Telefone, damit sie Cisco WebEx starten können, um E-Mails oder Telefone anzurufen | Die App würde KEINE Daten in ihren Datenbanken speichern | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |
>| User.ReadWrite | Delegiert | Diese Berechtigung besteht darin, Kurzwahlinformationen in der Benutzererweiterung zu speichern. | Die App würde KEINE Daten in ihren Datenbanken speichern  | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Diese Nachrichtenerweiterung würde Die E-Mail/Telefone von Chatmitgliedern lesen, damit benutzersie mit Cisco WebEx anrufen kann | Nein |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>In den Anwendungstelemetrie- oder Protokollprotokollen sind keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Diese App speicherte keine Benutzerdaten

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10549' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10549" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Cisco darüber bereitgestellt, wie diese App authentifizierung, Autorisierung, Bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Können Sie sich in Microsoft Identifizplattform (Azure AD) integrieren?  | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
