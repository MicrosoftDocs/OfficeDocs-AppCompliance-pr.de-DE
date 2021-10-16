---
title: Anwendungsinformationen für MeasureUp by Media Interactiva-Lösungen
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für MeasureUp, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 19ce585f62580ae5aca1b1ee936980c8bed9a1e5
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410138"
---
# <a name="measureup"></a>MeasureUp

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 2, 2021</p>

* <a href="https://teams.microsoft.com/l/app/bb1f94be-57aa-452c-9073-7fbb6b8b1797" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003111" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen von Media Interactiva-Lösungen für Microsoft:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | MeasureUp |
| ID | WA200003111 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Media Interactiva Solutions |
| URL der Partnerwebsite | [https://www.measureup.com](https://www.measureup.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://docs.measureup.com](https://docs.measureup.com) |
| URL der Datenschutzrichtlinie | [https://www.measureup.com/privacy-policy](https://www.measureup.com/privacy-policy) |
| URL der Nutzungsbedingungen | [https://www.measureup.com/legal-notice](https://www.measureup.com/legal-notice) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Media Interactiva Solutions dazu bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | Delegiert | Profilinformationen zum Registrieren und Zulassen der Anmeldung. Wenn Benutzer auf die Anwendung zugreifen, sind die Daten aus dem Microsoft-Profil erforderlich, um das Benutzerprofil auf unserer Plattform zu erstellen. | Die App speichert personenbezogene Daten des Benutzers, z. B. den Namen, nachnamen und E-Mails, um den Benutzer auf unserer Plattform zu authentifizieren. Darüber hinaus werden beim Starten unserer Produkte einige Berichte mit dem Fortschritt dieser Starts gespeichert. | [481280f4-a4ed-4862-a5a1-4de59da9dca5](https://docs.microsoft.com/microsoft-365-app-certification/azure/481280f4-a4ed-4862-a5a1-4de59da9dca5) |
>| openid | Delegiert | Profilinformationen zum Registrieren und Zulassen der Anmeldung. Wenn Benutzer auf die Anwendung zugreifen, sind die Daten aus dem Microsoft-Profil erforderlich, um das Benutzerprofil auf unserer Plattform zu erstellen. | Die App speichert personenbezogene Daten des Benutzers, z. B. den Namen, nachnamen und E-Mails, um den Benutzer auf unserer Plattform zu authentifizieren. Darüber hinaus werden beim Starten unserer Produkte einige Berichte mit dem Fortschritt dieser Starts gespeichert. | [481280f4-a4ed-4862-a5a1-4de59da9dca5](https://docs.microsoft.com/microsoft-365-app-certification/azure/481280f4-a4ed-4862-a5a1-4de59da9dca5) |
>| Profil | Delegiert | Profilinformationen zum Registrieren und Zulassen der Anmeldung. Wenn Benutzer auf die Anwendung zugreifen, sind die Daten aus dem Microsoft-Profil erforderlich, um das Benutzerprofil auf unserer Plattform zu erstellen. | Die App speichert personenbezogene Daten des Benutzers, z. B. den Namen, nachnamen und E-Mails, um den Benutzer auf unserer Plattform zu authentifizieren. Darüber hinaus werden beim Starten unserer Produkte einige Berichte mit dem Fortschritt dieser Starts gespeichert. | [481280f4-a4ed-4862-a5a1-4de59da9dca5](https://docs.microsoft.com/microsoft-365-app-certification/azure/481280f4-a4ed-4862-a5a1-4de59da9dca5) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Media Interactiva Solutions dazu bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden in der Checkliste für die Microsoft Identity Platform Integration überprüft und berücksichtigt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Nein |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/><br/> |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

