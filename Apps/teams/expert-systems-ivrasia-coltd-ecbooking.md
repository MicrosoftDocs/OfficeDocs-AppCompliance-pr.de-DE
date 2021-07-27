---
title: Anwendungsinformationen für ecBooking von Expert Systems IVR (Asia) Co.Ltd.
ms.author: elmalova
author: elenamalova
ms.date: 12/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für ecBooking, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f36edd400f35d7e4ccbfef5edd0225855f73ab69
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521728"
---
# <a name="ecbooking"></a>ecBooking

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 28, 2020</p>

* <a href="https://teams.microsoft.com/l/app/fe9627db-f23e-42b1-b454-d4d1ca5af33e" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002096" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen von Expert Systems IVR (Asia) Co.Ltd. an Microsoft:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | ecBooking |
| ID | WA200002096 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | Expert Systems IVR (Asia) Co.Ltd. |
| URL der Partnerwebsite | [https://www.esi-asia.com](https://www.esi-asia.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/) |
| URL der Datenschutzrichtlinie | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/#1510822239639-efecac03-d43200b0-aa88) |
| URL der Nutzungsbedingungen | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/#1598241760681-29d114e0-5c2b) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Expert Systems IVR(Asia) Co.Ltd bereitgestellt. Darüber, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | Anwendung | Daten wie Benutzer-E-Mail, Benutzerereignisse werden gespeichert. Benutzerereignisse werden gesammelt, um die Verfügbarkeit von Räumen zu überprüfen und Ereignisse zu erstellen. | Die ID des Users-Ereignisses, der Standortname und die Details des anderen Ereignisses würden gespeichert. Daten werden gesammelt, um die Verfügbarkeit von Chatrooms zu überprüfen und Ereignisse zu erstellen. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| Mail.Send | Anwendung | Daten wie Benutzer-E-Mail. Benutzer-E-Mails werden zum Senden von Erinnerungs-E-Mails für Raumbuchungen gesammelt. | Daten wie Benutzer-E-Mail. Benutzer-E-Mails werden zum Senden von Erinnerungs-E-Mails für Raumbuchungen gesammelt. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| User.Read | Delegiert | Daten wie Benutzer-ID, Name und E-Mail. Benutzerdaten werden für die Anmeldung des Benutzers in der Anwendung gesammelt. | Daten wie Benutzer-ID, Name und E-Mail. Benutzerdaten werden für die Anmeldung des Benutzers in der Anwendung gesammelt. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| User.Read.All | Anwendung | Daten wie Benutzer-ID, Name und E-Mail. Benutzerdaten werden für die Anmeldung des Benutzers in der Anwendung gesammelt. | Daten wie Benutzer-ID, Name und E-Mail. Benutzerdaten werden für die Anmeldung des Benutzers in der Anwendung gesammelt. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| email | Delegiert | Daten wie Benutzer-E-Mail. Benutzer-E-Mails werden gesammelt, um die Verfügbarkeit des Benutzers zu überprüfen und Ereignisse zu erstellen. | Daten wie Benutzer-E-Mail. Benutzer-E-Mails werden gesammelt, um die Verfügbarkeit des Benutzers zu überprüfen und Ereignisse zu erstellen. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| openid | Delegiert | Die OpenID des Benutzers, damit sich der Benutzer bei der Anwendung anmelden kann. | Die OpenID des Benutzers, damit sich der Benutzer bei der Anwendung anmelden kann. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Daten wie Benutzer-E-Mail, Benutzerereignisse werden gespeichert. 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>In der Datenbank gespeicherte Daten.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36415' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36415" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Expert Systems IVR(Asia) Co.Ltd bereitgestellt. Darüber, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/><br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
