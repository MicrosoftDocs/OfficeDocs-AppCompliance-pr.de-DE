---
title: Anwendungsinformationen für den Urlaubs-Tracker von "Vacation Tracker"
ms.author: elmalova
author: elenamalova
ms.date: 02/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für den Urlaubs-Tracker, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 55d54fbb94141dec562a829fdc647279a3cc006e
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/22/2021
ms.locfileid: "53527541"
---
# <a name="vacation-tracker"></a>Vacation Tracker

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: February 5, 2021</p>

* <a href="https://teams.microsoft.com/l/app/eab5463e-8168-40ee-887a-7ac78de1d266" target="_blank">Anzeigen in Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002167" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Vacation Tracker für Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Vacation Tracker |
| ID | WA200002167 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | Vacation Tracker |
| URL der Partnerwebsite | [https://vacationtracker.io](https://vacationtracker.io) |
| URL der Seite mit Teams Anwendungsinformationen | [https://vacationtracker.io/vacation-calendar-tracker-featur...](https://vacationtracker.io/vacation-calendar-tracker-features/) |
| URL der Datenschutzrichtlinie | [https://vacationtracker.io/privacy-policy/](https://vacationtracker.io/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://vacationtracker.io/terms-of-service/](https://vacationtracker.io/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Vacation Tracker darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.Read.All | Delegiert | Wir lesen die IDs und Namen öffentlicher Kanäle, wenn Benutzer ihre wöchentlichen oder täglichen Benachrichtigungen festlegen. | Benutzer können einen Kanal auswählen, in dem sie tägliche oder wöchentliche Benachrichtigungen vom Vacation Tracker erhalten möchten. Wenn ein Benutzer den bevorzugten Kanal auswählt, wird die Kanal-ID gespeichert. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| Team.ReadBasic.All | Delegiert | Wir listen die Microsoft Teams Teams-Benutzer auf, die während der Registrierung beigetreten sind, damit Benutzer ein Team auswählen können, das sie für die Urlaubsverfolgung registrieren möchten. Sie können sich alternativ bei ihrer gesamten Organisation registrieren. | Wir speichern die Microsoft Teams Team-ID für ein ausgewähltes Team nur, wenn sich der Benutzer als einzelnes Team (nicht als ganze Organisation) für die Urlaubsverfolgung registriert. Wir verwenden Team-IDs, um einen angemeldeten Benutzer mit einem vorhandenen Konto im Urlaubs-Tracker zu verbinden. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| User.Read | Delegiert | Wir erfassen die grundlegenden Benutzerinformationen, einschließlich Name, ID und Mandanten-ID. Wir verwenden diese Daten, um angemeldete Benutzer mit ihrer Organisation im Urlaubs-Tracker zu verbinden. | Wir speichern den Namen, die ID und die Mandanten-ID des Benutzers. Wir verwenden diese Daten, um angemeldete Benutzer mit ihrer Organisation im Urlaubs-Tracker zu verbinden. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| User.Read.All | Delegiert | Unsere Benutzer können alle Benutzer aus ihrer Microsoft 365 Organisation oder Microsoft Teams Team importieren. Wir verwenden diese Berechtigung, um nur lizenzierte Benutzer für ein ausgewähltes Microsoft Teams Team oder eine ausgewählte Organisation zu importieren. | Wir speichern grundlegende Informationen zu importierten Benutzern, einschließlich name, E-Mail-Adresse und Benutzer-ID. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| User.ReadBasic.All | Delegiert | Wir ermöglichen Benutzern, die anderen Benutzer aus ihrer Organisation oder ihrem Microsoft Teams-Team zu importieren. Wir verwenden diese Berechtigung, um die verfügbaren Benutzer und ihre E-Mail-Adressen im Importpopup aufzulisten. | Wenn Benutzer ihre Kollegen auswählen, die in den Urlaubs-Tracker importiert werden sollen, speichern wir grundlegende Informationen zu diesen importierten Benutzern, einschließlich name, E-Mail-Adresse und Benutzer-ID. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| email | Delegiert | Wenn sich der Benutzer mit Microsoft AAD anmeldet, speichern wir seine E-Mail-Adresse als eindeutigen Bezeichner. | Wir speichern die E-Mails des Benutzers als eindeutigen Bezeichner. Wir verwenden diese E-Mail nicht für die Kommunikation, Benutzer geben ihre geschäftliche E-Mail-Adresse ein, die wir für die Kommunikation während der Registrierung verwenden. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| offline_access | Delegiert | Wir sammeln keine Daten mit dieser Berechtigung. Es wird verwendet, um den Zugriff auf Daten beizubehalten, auf die wir zugreifen dürfen. | Wir speichern keine Daten mit dieser Berechtigung. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| openid | Delegiert | Wir verwenden diese Berechtigung zum Anmelden oder Registrieren von Benutzern beim Urlaubs-Tracker. Wir sammeln keine bestimmten Daten mit dieser Berechtigung. | Wir verwenden diese Berechtigung zum Anmelden oder Registrieren von Benutzern beim Urlaubs-Tracker. Wir speichern keine bestimmten Daten mit dieser Berechtigung. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| Profil | Delegiert | Wir erfassen die grundlegenden Benutzerinformationen, einschließlich Name, ID und Mandanten-ID. Wir verwenden diese Daten, um angemeldete Benutzer mit ihrer Organisation im Urlaubs-Tracker zu verbinden. | Wir speichern den Namen, die ID und die Mandanten-ID des Benutzers. Wir verwenden diese Daten, um angemeldete Benutzer mit ihrer Organisation im Urlaubs-Tracker zu verbinden. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Stripe, AWS, Crisp, Customer.io, Segment, Amplitude, Google Tag Manager | Firmenname (wie vom Benutzer eingegeben) | Wenn sich ein Benutzer anmeldet, gibt er den Firmennamen ein, und dieser Name wird als Organisationsname im Produkt verwendet. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Der Bot kann die grundlegenden Informationen über den Benutzer sehen, der mit dem Bot kommuniziert. Diese Informationen werden jedoch nicht gespeichert oder verwendet. Wir verwenden nur die ID des Benutzers, die Unterhaltungs-ID und eine an unseren Bot gesendete Nachricht. | Wir speichern die E-Mail-Adresse des Benutzers, den Benutzernamen (gemäß Definition in Microsoft AAD) und das Profilfoto des Benutzers (von Microsoft AAD). | Wir verwenden eine E-Mail-Adresse als eindeutigen Bezeichner für unsere Benutzer sowie den Namen und das Profilfoto des Benutzers, damit Administratoren und genehmiger Personen aus demselben Unternehmen ihre Mitarbeiter in unserem Dashboard erkennen können.  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Name des Unternehmens und wird gemäß unserer standardmäßigen Ein-Jahres-Aufbewahrungsrichtlinie für diese Art von Daten beibehalten und entfernt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Zunächst erfassen wir die Mindestmenge an Daten, die von Benutzern benötigt werden. Dann teilen wir das möglichst minimale Maß mit unseren Partnern, und schließlich haben wir Richtlinien für die Datenaufbewahrung, sodass alle Daten innerhalb eines Jahres entfernt werden, falls zutreffend.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Vacation Tracker darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>– Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
