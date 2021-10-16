---
title: Anwendungsinformationen für die Confluence Cloud von Atlassian
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Confluence Cloud, die Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f73952983dd6b9788bcd61d71e55e5815de5f937
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411149"
---
# <a name="confluence-cloud"></a>Confluence Cloud

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 18, 2021</p>

* <a href="https://teams.microsoft.com/l/app/30bb610c-6321-40fe-a047-056e7d0dac96" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003113" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Atlassian für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Confluence Cloud |
| ID | WA200003113 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Atlassian |
| URL der Partnerwebsite | [https://www.atlassian.com](https://www.atlassian.com) |
| URL der Datenschutzrichtlinie | [https://www.atlassian.com/legal/privacy-policy](https://www.atlassian.com/legal/privacy-policy) |
| URL der Nutzungsbedingungen | [https://www.atlassian.com/licensing/marketplace/termsofuse](https://www.atlassian.com/licensing/marketplace/termsofuse) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Atlassian bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | Delegiert | - Wir lesen die Liste der Chatmitglieder in einer Besprechung, damit wir die Liste der eingeladenen Personen zur Besprechung kennen.   – Wir lesen die Benutzer&#8217; Namen und E-Mail-Adressen, die wir bedingt in unserer Besprechungs-App anzeigen. Zeigen Sie beispielsweise den Namen des aktuellen Benutzers an, der Besprechungsnotizen nimmt.   – Unsere App liest den Benutzer&#8217;Kalenderereignis, bei dem unsere App zu einer Besprechung hinzugefügt wurde, sodass wir grundlegende Informationen über die Besprechung haben, z. B. den Besprechungstitel. | Beispiele für Inhalte, die wir sammeln und speichern, sind: die Zusammenfassung und Beschreibung, die zu einem JIRA-Problem hinzugefügt wurden, die Seiten, die Sie in Confluence erstellen, Ihre Repositorys und Pull-Anforderungen in Bitbucket, Kommentare, die Sie in Verbindung mit einem Vorfall in Statuspage eingeben, und feedback, das Sie uns bereitstellen. Der Inhalt enthält auch die Dateien und Links, die Sie in die Dienste hochladen. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| Chat.ReadBasic | Delegiert |  - Wir lesen die Liste der Chatmitglieder in einer Besprechung, damit wir die Liste der eingeladenen Personen zur Besprechung kennen.   – Wir lesen die Benutzer&#8217; Namen und E-Mail-Adressen, die wir bedingt in unserer Besprechungs-App anzeigen. Zeigen Sie beispielsweise den Namen des aktuellen Benutzers an, der Besprechungsnotizen nimmt.   – Unsere App liest den Benutzer&#8217;Kalenderereignis, bei dem unsere App zu einer Besprechung hinzugefügt wurde, sodass wir grundlegende Informationen über die Besprechung haben, z. B. den Besprechungstitel. | Beispiele für Inhalte, die wir sammeln und speichern, sind: die Zusammenfassung und Beschreibung, die zu einem JIRA-Problem hinzugefügt wurden, die Seiten, die Sie in Confluence erstellen, Ihre Repositorys und Pull-Anforderungen in Bitbucket, Kommentare, die Sie in Verbindung mit einem Vorfall in Statuspage eingeben, und feedback, das Sie uns bereitstellen. Der Inhalt enthält auch die Dateien und Links, die Sie in die Dienste hochladen. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| User.ReadBasic.All | Delegiert | - Wir lesen die Liste der Chatmitglieder in einer Besprechung, damit wir die Liste der eingeladenen Personen zur Besprechung kennen.   – Wir lesen die Benutzer&#8217; Namen und E-Mail-Adressen, die wir bedingt in unserer Besprechungs-App anzeigen. Zeigen Sie beispielsweise den Namen des aktuellen Benutzers an, der Besprechungsnotizen nimmt.   – Unsere App liest den Benutzer&#8217;Kalenderereignis, bei dem unsere App zu einer Besprechung hinzugefügt wurde, sodass wir grundlegende Informationen über die Besprechung haben, z. B. den Besprechungstitel. | Beispiele für Inhalte, die wir sammeln und speichern, sind: die Zusammenfassung und Beschreibung, die zu einem JIRA-Problem hinzugefügt wurden, die Seiten, die Sie in Confluence erstellen, Ihre Repositorys und Pull-Anforderungen in Bitbucket, Kommentare, die Sie in Verbindung mit einem Vorfall in Statuspage eingeben, und feedback, das Sie uns bereitstellen. Der Inhalt enthält auch die Dateien und Links, die Sie in die Dienste hochladen. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| email | Delegiert | - Wir lesen die Liste der Chatmitglieder in einer Besprechung, damit wir die Liste der eingeladenen Personen zur Besprechung kennen.   – Wir lesen die Benutzer&#8217; Namen und E-Mail-Adressen, die wir bedingt in unserer Besprechungs-App anzeigen. Zeigen Sie beispielsweise den Namen des aktuellen Benutzers an, der Besprechungsnotizen nimmt.   – Unsere App liest den Benutzer&#8217;Kalenderereignis, bei dem unsere App zu einer Besprechung hinzugefügt wurde, sodass wir grundlegende Informationen über die Besprechung haben, z. B. den Besprechungstitel. | Beispiele für Inhalte, die wir sammeln und speichern, sind: die Zusammenfassung und Beschreibung, die zu einem JIRA-Problem hinzugefügt wurden, die Seiten, die Sie in Confluence erstellen, Ihre Repositorys und Pull-Anforderungen in Bitbucket, Kommentare, die Sie in Verbindung mit einem Vorfall in Statuspage eingeben, und feedback, das Sie uns bereitstellen. Der Inhalt enthält auch die Dateien und Links, die Sie in die Dienste hochladen. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| offline_access | Delegiert | - Wir lesen die Liste der Chatmitglieder in einer Besprechung, damit wir die Liste der eingeladenen Personen zur Besprechung kennen.   – Wir lesen die Benutzer&#8217; Namen und E-Mail-Adressen, die wir bedingt in unserer Besprechungs-App anzeigen. Zeigen Sie beispielsweise den Namen des aktuellen Benutzers an, der Besprechungsnotizen nimmt.   – Unsere App liest den Benutzer&#8217;Kalenderereignis, bei dem unsere App zu einer Besprechung hinzugefügt wurde, sodass wir grundlegende Informationen über die Besprechung haben, z. B. den Besprechungstitel. | Beispiele für Inhalte, die wir sammeln und speichern, sind: die Zusammenfassung und Beschreibung, die zu einem JIRA-Problem hinzugefügt wurden, die Seiten, die Sie in Confluence erstellen, Ihre Repositorys und Pull-Anforderungen in Bitbucket, Kommentare, die Sie in Verbindung mit einem Vorfall in Statuspage eingeben, und feedback, das Sie uns bereitstellen. Der Inhalt enthält auch die Dateien und Links, die Sie in die Dienste hochladen. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| openid | Delegiert |  - Wir lesen die Liste der Chatmitglieder in einer Besprechung, damit wir die Liste der eingeladenen Personen zur Besprechung kennen.   – Wir lesen die Benutzer&#8217; Namen und E-Mail-Adressen, die wir bedingt in unserer Besprechungs-App anzeigen. Zeigen Sie beispielsweise den Namen des aktuellen Benutzers an, der Besprechungsnotizen nimmt.   – Unsere App liest den Benutzer&#8217;Kalenderereignis, bei dem unsere App zu einer Besprechung hinzugefügt wurde, sodass wir grundlegende Informationen über die Besprechung haben, z. B. den Besprechungstitel. | Beispiele für Inhalte, die wir sammeln und speichern, sind: die Zusammenfassung und Beschreibung, die zu einem JIRA-Problem hinzugefügt wurden, die Seiten, die Sie in Confluence erstellen, Ihre Repositorys und Pull-Anforderungen in Bitbucket, Kommentare, die Sie in Verbindung mit einem Vorfall in Statuspage eingeben, und feedback, das Sie uns bereitstellen. Der Inhalt enthält auch die Dateien und Links, die Sie in die Dienste hochladen. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| Profil | Delegiert |  - Wir lesen die Liste der Chatmitglieder in einer Besprechung, damit wir die Liste der eingeladenen Personen zur Besprechung kennen.   – Wir lesen die Benutzer&#8217; Namen und E-Mail-Adressen, die wir bedingt in unserer Besprechungs-App anzeigen. Zeigen Sie beispielsweise den Namen des aktuellen Benutzers an, der Besprechungsnotizen nimmt.   – Unsere App liest den Benutzer&#8217;Kalenderereignis, bei dem unsere App zu einer Besprechung hinzugefügt wurde, sodass wir grundlegende Informationen über die Besprechung haben, z. B. den Besprechungstitel. | Beispiele für Inhalte, die wir sammeln und speichern, sind: die Zusammenfassung und Beschreibung, die zu einem JIRA-Problem hinzugefügt wurden, die Seiten, die Sie in Confluence erstellen, Ihre Repositorys und Pull-Anforderungen in Bitbucket, Kommentare, die Sie in Verbindung mit einem Vorfall in Statuspage eingeben, und feedback, das Sie uns bereitstellen. Der Inhalt enthält auch die Dateien und Links, die Sie in die Dienste hochladen. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |


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

>https://www.atlassian.com/trust/privacy/how-we-handle-your-data

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22926' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22926" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Atlassian darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Nein |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>– Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

