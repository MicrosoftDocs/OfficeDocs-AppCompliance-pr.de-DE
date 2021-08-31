---
title: Anwendungsinformationen für die ChronoScope-Zeitverfolgung von Chrono Innovation
ms.author: elmalova
author: elenamalova
ms.date: 07/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für die ChronoScope-Zeitverfolgung, die Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 9e87baec293d3c18e48da28e1714fce9703f446f
ms.sourcegitcommit: 34fde42f42c623b37d1db154bf348bdc8b76a8c7
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/19/2021
ms.locfileid: "58407465"
---
# <a name="chronoscope-time-tracking"></a>ChronoScope-Zeitverfolgung

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 23, 2021</p>

* <a href="https://teams.microsoft.com/l/app/5b3ded07-fa1a-4fd8-a323-e5fe3f8cf740" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003095" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen von Chrono Innovation für Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | ChronoScope-Zeitverfolgung |
| ID | WA200003095 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | Chrono-Innovation |
| URL der Partnerwebsite | [https://www.chronoinnovation.com](https://www.chronoinnovation.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.chronoscope.app](https://www.chronoscope.app) |
| URL der Datenschutzrichtlinie | [https://www.chronoscope.app/privacy-policy](https://www.chronoscope.app/privacy-policy) |
| URL der Nutzungsbedingungen | [https://www.chronoscope.app/terms-of-service](https://www.chronoscope.app/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Chrono Innovation dazu bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AccessReview.Read.All | Anwendung | die Teams-Mandanten-ID, teams addObjectId und Teams-Benutzerkontoinformationen. Beim Verknüpfen von ChronoScope-Benutzern überprüfen wir, dass die E-Mail einem Teams Konto entspricht, sodass wir das Konto ohne manuellen Schritt des Benutzers verknüpfen können. | Teams-Mandanten-ID, Teams-AddObjectId und Teams-Benutzerkontoinformationen. Beim Verknüpfen von ChronoScope-Benutzern überprüfen wir, dass die E-Mail einem Teams Konto entspricht, sodass wir das Konto ohne manuellen Schritt des Benutzers verknüpfen können. | [9bc8244d-a186-4b12-809e-c47b3eee73c6](https://docs.microsoft.com/microsoft-365-app-certification/azure/9bc8244d-a186-4b12-809e-c47b3eee73c6) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Personenbezogene Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| um den Teams-Benutzer workspaWhen beim Verknüpfen von ChronoScope-Benutzern zu finden, überprüfen wir, dass die E-Mail einem Teams Konto entspricht, sodass wir das Konto ohne manuellen Schritt von "user.ce" in der Datenbank unserer Anwendung verknüpfen und diesen Teams-Benutzer authentifizieren können. | tenantId , Benutzerkontoinformationen wie userId , addObjectId , givenName ,email ,role,objectId | Beim Verknüpfen von ChronoScope-Benutzern überprüfen wir, dass die E-Mail einem Teams Konto entspricht, sodass wir das Konto ohne manuellen Schritt des Benutzers verknüpfen können. Um auch Pushbenachrichtigungen zu den vorab ausgefüllten Benutzerzeiteinträgen senden zu können, damit sie sie speichern/bearbeiten/löschen können. |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Informationen zu Zeiteinträgen. Chrono Innovation entfernt Kundendaten 90 Tage nach dem Löschen des ChronoScope-Kontos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Administratoren haben die volle Kontrolle über die Informationen, die sich in den Systemen eines Beliebigen Partners befinden.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Chrono Innovation dazu bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Response** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration aufgeführt sind, überprüft und berücksichtigt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>– Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/> |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
