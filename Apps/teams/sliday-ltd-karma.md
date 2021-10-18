---
title: Anwendungsinformationen für Karma von Sliday LTD
ms.author: elmalova
author: elenamalova
ms.date: 09/14/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Karma, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 781e9e6fd3ece314f2175fc23c116e6cf2a2b6b6
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430153"
---
# <a name="karma"></a>Karma

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/9ff28b02-ccc5-4cac-9d17-4cf6987c371f" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381640" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Sliday LTD für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Karma |
| ID | WA104381640 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Sliday LTD |
| URL der Partnerwebsite | [https://sliday.com](https://sliday.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://karmabot.readme.io/](https://karmabot.readme.io/) |
| URL der Datenschutzrichtlinie | [https://karmabot.readme.io/docs/privacy-policy-for-microsof...](https://karmabot.readme.io/docs/privacy-policy-for-microsoft-teams) |
| URL der Nutzungsbedingungen | [https://karmabot.readme.io/docs/terms-and-conditions](https://karmabot.readme.io/docs/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Sliday LTD darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | Anwendung | Vorname, Nachname und E-Mail-Adresse des Unternehmens. Vorname, Nachname für Berichterstellung mit Administratorzugriff. E-Mail-Adresse für kommunikation in Bezug auf Karma, Abrechnungszwecke und Herarchie. | Anzeigename der Administratorzustimmung. Melden Sie sich an, und lesen Sie das Benutzerprofil. Beschreibung der Administratorzustimmung. Ermöglicht Benutzern die Anmeldung bei der App und ermöglicht es der App, das Profil der angemeldeten Benutzer zu lesen. Außerdem kann die App grundlegende Unternehmensinformationen von angemeldeten Benutzern lesen. Anzeigename der Zustimmung des BenutzersSignieren und Lesen Ihres Profils. Beschreibung der Zustimmung des Benutzers. Ermöglicht es Ihnen, sich mit Ihrem Organisationskonto bei der App anzumelden und die App ihr Profil lesen zu lassen. Außerdem kann die App grundlegende Unternehmensinformationen lesen. | [9ff28b02-fg5-4cac-9d17-4cf6987c371f](https://docs.microsoft.com/microsoft-365-app-certification/azure/9ff28b02-ccc5-4cac-9d17-4cf6987c371f) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Vorname, Nachname und Firmen-E-Mail-Adresse Vorname, Nachname für administratorseitige Berichts-E-Mail-Adresse für die Kommunikation in Bezug auf Karma. Die Teilnehmerliste ist für Abrechnungszwecke und für die massive Aufteilung der Benutzer in separate Abgänge erforderlich. | Vorname, Nachname und Firmen-E-Mail-Adresse Vorname, Nachname für Berichterstellung mit Administratorzugriff. E-Mail-Adresse für die Kommunikation in Bezug auf Karma, Abrechnungszwecke und Die Hierarchie der Benutzer von Karma. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Mandanten-IDs und Benutzer-IDs werden in Protokollen gespeichert. Beide sind nicht identifizierbar.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>1. **Ist eine DLP-Lösung vorhanden? Was ist implementiert, um Datenlecks zu verhindern?**

JA, Daten werden sowohl während der Übertragung als auch im Ruhezustand verschlüsselt.

2. **Welche Art von Mechanismen implementieren Sie, um sicherzustellen, dass die Datenintegrität vor Fehlern, Beschädigungen oder Missbrauch geschützt ist und wie häufig sie gesteuert werden**

Auf allen Servern wird Hardware-RAID mit unterschiedlichen RAID-Ebenen ausgeführt, in jedem Fall sind jedoch mehrere Laufwerksfehler gleichzeitig erforderlich, damit ein Datenverlust auftritt. Wir sind besonders sicher und verfügen über automatische und manuelle Sicherungen. Datenbanken werden täglich automatisch gesichert und sieben Tage lang gespeichert.
Virtuelle Computer werden jede Woche automatisch gesichert und 1 Monat lang gespeichert.

**Momentaufnahmen und Sicherungen werden in einem internen nicht öffentlich sichtbaren Netzwerk gespeichert.**

3. **Beschreiben, wie Sie sicherstellen, dass die Daten des Kunden ordnungsgemäß von den Daten anderer Kunden in mehrinstanzenfähigen Lösungen getrennt sind und wie Sie steuern, dass Produktionsdaten nicht repliziert oder in Nicht-Produktionsumgebungen verwendet werden**

Gespeichert in verschiedenen Datenbanken.

4. **Welche Art von Verschlüsselung (Algorithmen, Protokolle, Schlüssellängen) für Daten während der Übertragung und ruhenden Daten vorschlagen**

Alle Während der Übertragung übertragenen Daten werden mit TLS oder SSL verschlüsselt. HTTP wird durch TLS 1.2- oder TLS 1.3-Datenbankdatenverkehr verschlüsselt, der durch SSL verschlüsselt wird.

Die Daten werden im Digital-Cloud-Center in den USA gespeichert.

5. **Beschreiben, wie Sie eindeutige Verschlüsselungsschlüssel (Prozess, Speicher, Nutzung, RACI, SOD) für Ihre eigene Verwendung und für jeden Ihrer Mandanten verwalten**

Behandelt vom digitalen Pazifik.

6. **Beschreiben Sie den am Ende des Anbieters eingerichteten Zugriffsverwaltungsprozess und weisen Sie darauf hin, wie Sie sicherstellen, dass nicht mehr erforderliche Zugriffe zeitnah entfernt werden und wie Sie die Angemessenheit der Berechtigungen für die Auftragsrolle steuern. Beschreiben Sie außerdem die Überprüfungsprozesse und die Häufigkeit ihrer Ausführung.**

Wir verwenden die zweistufige Authentifizierung, um auf die Systemsteuerung zuzugreifen. Nur 3 Personen haben Zugriff darauf, wir ändern jedes Monat Kennwörter, lassen Zugriffsprotokolle überwacht und stellen sicher, dass Personen, die nicht mehr mit uns arbeiten, ihre Konten von der Plattform entfernt haben.

7. **Stellen Sie das am Ende implementierte Verfahren bereit, um Ihre freigegebenen IDs (z. B. Stamm,Sys, System usw.), Gruppen-IDs (generische Konten, die z. B. von mehreren Personen verwendet werden, die zum selben Team gehören) und lokale Konten zu verwalten. Beschreiben, wie Sie die Nutzung privilegierter Konten und den Zugriff auf Sicherheitsgeräte einschränken, protokollieren und überwachen (z. B. Hypervisoren, Firewalls, Sicherheitsrisikoscanner, Netzwerk-Sniffer, APIs usw.), wie Sie sicherstellen, dass Benutzer, die das Team ändern oder verlassen, nicht mehr auf die Gruppen-ID zugreifen können und wie die Nachverfolgbarkeit dieser IDs ist**

Wir verwenden "1Password", um trennbare ID-&#8217;gemeinsam zu verwenden. Wir haben bei jedem Zugriff auf die freigegebene Ressource über ein freigegebenes Kennwortdepot einen separaten Aktivitätsfeed. Es sei denn, es ist absolut erforderlich, dass wir keine freigegebenen Konten verwenden und stattdessen einzelne Konten verwenden. Über eine freigegebene Anmeldung konnten keine Informationen in der Karma-Datenbank aufgerufen werden. 2FA wird verwendet, um auf 1Password zuzugreifen, um eine einzelne Anmeldung abzurufen.

8. **Beschreiben sie den Prozess, um sicherzustellen und zu überwachen, dass die Aufgabentrennung berücksichtigt wird und wie häufig sie gesteuert wird.**

Wir haben monatliche Besprechungen ausgeführt, in denen die Aufgabentrennung, die Bedeutung der dedizierten Anmeldung und 2FA für jede anmeldung behandelt werden.

Unser SIEM enthält: Firewallprotokolle, Webserverprotokolle und Anwendungsprotokolle. SIEM wird täglich und nach Empfang analysiert. Protokolle werden 1 Monat lang aufbewahrt und danach sicher entfernt.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

