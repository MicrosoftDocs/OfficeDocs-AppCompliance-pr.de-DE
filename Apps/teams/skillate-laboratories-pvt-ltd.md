---
title: Anwendungsinformationen für Skillate von Skillate Laboratories Pvt. Ltd.
ms.author: elmalova
author: elenamalova
ms.date: 01/12/2021
ms.topic: article
ms.service: attestation
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Skillate, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5775e9a2ea511498c03c68dab29bf4eb9bef43c2
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096153"
---
# <a name="skillate"></a>Skillate

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 12. Januar 2021</p>

* <a href="https://teams.microsoft.com/l/app/b24691df-ba35-42e7-bd57-a7c7e57e49d6" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002490" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Skillate Laboratories Pvt bereitgestellt werden. Ltd. an Microsoft:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Skillate |
| ID | WA200002490 |
| Funktionen | Bot, Registerkarte, Connector |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Skillate Laboratories Pvt. Ltd. |
| URL der Partnerwebsite | [https://skillate.com/](https://skillate.com/) |
| URL Teams Anwendungsinfoseite | [https://www.skillate.com/features/intelligent-hiring/](https://www.skillate.com/features/intelligent-hiring/) |
| URL der Datenschutzrichtlinie | [https://www.skillate.com/privacy-policy](https://www.skillate.com/privacy-policy) |
| URL der Nutzungsbedingungen | [https://www.skillate.com/terms-and-conditions](https://www.skillate.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Skillate Laboratories Pvt bereitgestellt. Ltd. darüber, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| email | delegierte | Die Daten werden gesammelt, um den Endbenutzer auf Skillate zu autorisieren. | Wir speichern die E-Mail-Adresse nur, um das Konto des Benutzers in der Skillate-App zu erstellen. | ed4df345-c860-4ffe-b614-0460d9106f0f |
>| openid | delegierte | Wir verwenden die API, um den Benutzer bei Microsoft mit SSO zu protokollieren | Wir speichern nur den Vor- und Nachnamen des Endbenutzers | ed4df345-c860-4ffe-b614-0460d9106f0f |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Wir verwenden E-Mail-Adresse nur zum Autorisieren der Benutzer zur Verwendung der Messagingerweiterung. | Beim Erstellen des Kontos speichern wir E-Mails, Vor- und Nachname. Während der App-Nutzung kann der Benutzer jedoch basierend auf kundenbezogenen Eingaben weitere Variablen hinzufügen. | Wir speichern nur E-Mails, Vor- und Nachnamen des Endbenutzers, um ein Konto zu autorisiert und zu erstellen.  |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Nicht zutreffend

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36380' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36380" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Skillate Laboratories Pvt bereitgestellt. Ltd. darüber, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden geprüft und befolgt, die in der Prüfliste Microsoft Identity Platform aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Bittet Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordern wird? | Ja |
| Unterstützt Ihre App mehrere Mandanzfähigkeiten? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle umgeleiteten Unified Resource Identifier (URI), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | - UrIs für die Platzhalterumleitung,
<br />
- OAuth2 Implizite Flow, es sei denn, dies ist für eine SPA erforderlich
<br />
- Ablauf der Kennwortanmeldeinformationen (Password Credential, ROPC) des Ressourcenbesitzers | | Macht Ihre App Web-APIs verfügbar? | Keine | | Verwendet Ihre App Vorschau-APIs? | Keine | | Verwendet Ihre App veraltete APIs? | Keine |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
