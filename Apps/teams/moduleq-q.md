---
title: Anwendungsinformationen für Q nach ModulQ
ms.author: elmalova
author: elenamalova
ms.date: 07/08/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Q, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a1a9995b6b723d7ed712f9a0fdbe9315ee53c7f0
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/12/2021
ms.locfileid: "59283304"
---
# <a name="q"></a>Q

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 8, 2021</p>

* <a href="https://teams.microsoft.com/l/app/72bb25c7-3644-4318-8249-a08e5493a520" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381433" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von ModuleQ an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Q |
| ID | WA104381433 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | ModuleQ |
| URL der Partnerwebsite | [https://moduleq.com](https://moduleq.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://moduleq.com/product](https://moduleq.com/product) |
| URL der Datenschutzrichtlinie | [https://moduleq.com/privacy-policy/](https://moduleq.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://moduleq.com/terms-of-service](https://moduleq.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von ModuleQ bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | Anwendung | speichert Besprechungsdaten, mit Ausnahme des Nachrichtentexts und aller Anlagen. | Ermöglicht der Anwendung, die Kalenderereignisse eines Benutzers zu lesen, um die geschäftlichen Prioritäten des Benutzers intelligent zu verstehen. | [418a1ee4-ca76-4b38-b4b3-8cca25417a6c](https://docs.microsoft.com/microsoft-365-app-certification/azure/418a1ee4-ca76-4b38-b4b3-8cca25417a6c) |
>| Group.Read.All | Delegiert | Keine | Ermöglicht der App, in einem Team zum Freigeben von Inhalten zu interagieren. | [418a1ee4-ca76-4b38-b4b3-8cca25417a6c](https://docs.microsoft.com/microsoft-365-app-certification/azure/418a1ee4-ca76-4b38-b4b3-8cca25417a6c) |
>| Mail.Read | Anwendung | speichert E-Mail-Daten, mit Ausnahme des Nachrichtentexts und aller Anlagen | Ermöglicht der Anwendung, die E-Mails eines Benutzers zu lesen, um die geschäftlichen Prioritäten des Benutzers intelligent zu verstehen. | [418a1ee4-ca76-4b38-b4b3-8cca25417a6c](https://docs.microsoft.com/microsoft-365-app-certification/azure/418a1ee4-ca76-4b38-b4b3-8cca25417a6c) |
>| User.Read | Delegiert | Benutzer-E-Mail- und Authentifizierungstoken | Ermöglicht dem Benutzer, sich anzumelden und sein Office 365-Konto mit dem ModuleQ-Konto zu verknüpfen. | [418a1ee4-ca76-4b38-b4b3-8cca25417a6c](https://docs.microsoft.com/microsoft-365-app-certification/azure/418a1ee4-ca76-4b38-b4b3-8cca25417a6c) |
>| User.Read.All | Delegiert | Keine | Zulassen, dass die App die Liste der Teams abruft, zu der der Benutzer gehört. Wird nur für die Freigabe verwendet  | [418a1ee4-ca76-4b38-b4b3-8cca25417a6c](https://docs.microsoft.com/microsoft-365-app-certification/azure/418a1ee4-ca76-4b38-b4b3-8cca25417a6c) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir protokollieren eine interne Benutzer-GUID sowie Organisationsnamen und Domänen. Es gibt derzeit keine Archiv- oder Löschsteuerelemente.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Daten werden in der Microsoft Azure Cloud über mehrere Microservices entsprechend ihrer Funktion gespeichert. Alle benutzerbezogenen Daten werden clientseitig mit der AES-256-Verschlüsselung verschlüsselt, bevor sie zur Speicherung übertragen werden. Daten können von Technikern zu Debugzwecken mit Genehmigung unserer Geschäftsleitung angezeigt werden. Der Zugriff auf Daten wird über ein internes VPN gesteuert.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von ModuleQ bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

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
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/><br/> |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
