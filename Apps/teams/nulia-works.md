---
title: Anwendungsinformationen für Nulia Works von Nulia
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Nulia Works, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4d176b18a8089d9107f30b7581bcca69daf0871e
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521308"
---
# <a name="nulia-works"></a>Nulia Works

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 11, 2021</p>

* <a href="https://teams.microsoft.com/l/app/e49e0f69-600c-460c-80b3-8809a9d97a4c" target="_blank">Anzeigen in Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002051" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Nulia für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Nulia Works |
| ID | WA200002051 |
| unterstützte Office 365-Clients | Microsoft Teams |
| Name des Partnerunternehmens | Nulia |
| URL der Partnerwebsite | [https://nulia.com](https://nulia.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://nulia.com/product](https://nulia.com/product) |
| URL der Datenschutzrichtlinie | [https://nulia.com/privacy](https://nulia.com/privacy) |
| URL der Nutzungsbedingungen | [https://nulia.com/terms](https://nulia.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Nulia darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | Anwendung | Wir verwenden die gesammelten Daten, um den Benutzerfortschritt bei Fähigkeiten und Ergebnissen zu bewerten. Wir erfassen Nutzungsanzahlen für mehrere O365-Workloads. | Wir speichern alle gesammelten Daten im Blobspeicher. Wir verwenden diese Daten, um Die Benutzer anhand von Fähigkeiten und Ergebnisfortschritten zu bewerten. Beispielsweise zählen wir die Anzahl der Kalenderereignisse, die ein Benutzer hat. Dieser Wert wirkt sich auf den Fortschritt ihrer Fähigkeiten aus. | [Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Unser Nulia-Mandant verwendet beispielsweise die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Contacts.Read | Anwendung | Wir verwenden die gesammelten Daten, um den Benutzerfortschritt bei Fähigkeiten und Ergebnissen zu bewerten. Wir erfassen Nutzungsanzahlen für mehrere O365-Workloads. | Wir speichern alle gesammelten Daten im Blobspeicher. Wir verwenden diese Daten, um Die Benutzer anhand von Fähigkeiten und Ergebnisfortschritten zu bewerten. Beispielsweise zählen wir die Anzahl der Kontakte, die ein Benutzer erstellt hat. Dieser Wert wirkt sich auf den Fortschritt ihrer Fähigkeiten aus. | [Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Unser Nulia-Mandant verwendet beispielsweise die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Files.Read.All | Anwendung | Wir verwenden die gesammelten Daten, um den Benutzerfortschritt bei Fähigkeiten und Ergebnissen zu bewerten. Wir erfassen Nutzungsanzahlen für mehrere O365-Workloads. | Wir speichern alle gesammelten Daten im Blobspeicher. Wir verwenden diese Daten, um Die Benutzer anhand von Fähigkeiten und Ergebnisfortschritten zu bewerten. Beispielsweise zählen wir die Anzahl der Dateien, die ein Benutzer mit dem Computer synchronisiert. Dieser Wert wirkt sich auf den Fortschritt ihrer Fähigkeiten aus. | [Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Unser Nulia-Mandant verwendet beispielsweise die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Group.Read.All | Anwendung | Wir verwenden die gesammelten Daten, um den Benutzerfortschritt bei Fähigkeiten und Ergebnissen zu bewerten. Wir erfassen Nutzungsanzahlen für mehrere O365-Workloads. | Wir speichern alle gesammelten Daten im Blobspeicher. Wir verwenden diese Daten, um Die Benutzer anhand von Fähigkeiten und Ergebnisfortschritten zu bewerten. Beispielsweise wird aus den Gruppen abgerufen, wie viele Teams ein Benutzer gehört. Dieser Wert wirkt sich auf den Fortschritt ihrer Fähigkeiten aus. | [Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Unser Nulia-Mandant verwendet beispielsweise die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Mail.Read | Anwendung | Wir verwenden die gesammelten Daten, um den Benutzerfortschritt bei Fähigkeiten und Ergebnissen zu bewerten. Wir erfassen Nutzungsanzahlen für mehrere O365-Workloads. | Wir speichern alle gesammelten Daten im Blobspeicher. Wir verwenden diese Daten, um Die Benutzer anhand von Fähigkeiten und Ergebnisfortschritten zu bewerten. Beispielsweise zählen wir die Anzahl der benutzerdefinierten E-Mail-Ordner, die ein Benutzer erstellt hat. Dieser Wert wirkt sich auf den Fortschritt ihrer Fähigkeiten aus. | [Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Unser Nulia-Mandant verwendet beispielsweise die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| MailboxSettings.Read | Anwendung | Wir verwenden die gesammelten Daten, um den Benutzerfortschritt bei Fähigkeiten und Ergebnissen zu bewerten. Wir erfassen Nutzungsanzahlen für mehrere O365-Workloads. | Wir speichern alle gesammelten Daten im Blobspeicher. Wir verwenden diese Daten, um Die Benutzer anhand von Fähigkeiten und Ergebnisfortschritten zu bewerten. Beispielsweise wird angezeigt, ob ein Benutzer eine Abwesenheitsantwort festgelegt hat. Dieser Wert wirkt sich auf den Fortschritt ihrer Fähigkeiten aus. | [Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Unser Nulia-Mandant verwendet beispielsweise die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Notes.Read | Anwendung | Wir verwenden die gesammelten Daten, um den Benutzerfortschritt bei Fähigkeiten und Ergebnissen zu bewerten. Wir erfassen Nutzungsanzahlen für mehrere O365-Workloads. | Wir speichern alle gesammelten Daten im Blobspeicher. Wir verwenden diese Daten, um Die Benutzer anhand von Fähigkeiten und Ergebnisfortschritten zu bewerten. Beispielsweise zählen wir die Anzahl der Notizbücher, die ein Benutzer freigegeben hat. Dieser Wert wirkt sich auf den Fortschritt ihrer Fähigkeiten aus. | [Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Unser Nulia-Mandant verwendet beispielsweise die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Reports.Read.All | Anwendung | Wir verwenden die gesammelten Daten, um den Benutzerfortschritt bei Fähigkeiten und Ergebnissen zu bewerten. Wir erfassen Nutzungsanzahlen für mehrere O365-Workloads. | Wir speichern alle gesammelten Daten im Blobspeicher. Wir verwenden diese Daten, um Die Benutzer anhand von Fähigkeiten und Ergebnisfortschritten zu bewerten. Beispielsweise rufen wir aus den Benutzerberichten ab, wie viele Teams Nachrichten sie an einem Tag gesendet haben. Dieser Wert wirkt sich auf den Fortschritt ihrer Fähigkeiten aus. | [Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Unser Nulia-Mandant verwendet beispielsweise die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Sites.Read.All | Anwendung | Wir verwenden die gesammelten Daten, um den Benutzerfortschritt bei Fähigkeiten und Ergebnissen zu bewerten. Wir erfassen Nutzungsanzahlen für mehrere O365-Workloads. | Wir speichern alle gesammelten Daten im Blobspeicher. Wir verwenden diese Daten, um Die Benutzer anhand von Fähigkeiten und Ergebnisfortschritten zu bewerten. Beispielsweise zählen wir die Anzahl der Websitesammlungen, die der Benutzer erstellt hat. Dieser Wert wirkt sich auf den Fortschritt ihrer Fähigkeiten aus. | [Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Unser Nulia-Mandant verwendet beispielsweise die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| User.Read | Anwendung | Wir zeigen den Anzeigenamen, die Abteilung und das Profilbild des Benutzers an. | Wir speichern den Anzeigenamen und die Abteilung in unserer Datenbank, damit wir nicht jedes Mal auf die Graph treffen müssen. Das Profilbild wird nicht gespeichert. | [Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Unser Nulia-Mandant verwendet beispielsweise die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Organization.Read.All | Anwendung | Wir erfassen den Namen des Mandanten und Yammer Basis-URL. Wir verwenden dies, um Yammer zu starten, wenn der Benutzer auf eine Schaltfläche "Ausprobieren" in unserer App klickt, &quot; die sich auf Yammer Aktivitäten &quot; bezieht. | Wir speichern alle gesammelten Daten im Blobspeicher. Wir verwenden dies beispielsweise, um Yammer zu starten, wenn der Benutzer in unserer App auf eine Schaltfläche "Ausprobieren" klickt, &quot; die sich auf Yammer Aktivitäten &quot; bezieht. | [Wir verwenden die gesammelten Daten, um den Benutzerfortschritt bei Fähigkeiten und Ergebnissen zu bewerten. Wir erfassen Nutzungsanzahlen für mehrere O365-Workloads.](https://docs.microsoft.com/microsoft-365-app-certification/azure/We use the data collected to score user progress on skills and Outcomes. We collect usage counts across multiple O365 workloads.) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir steuern keine Daten auf Partnersystemen

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Nulia darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
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
