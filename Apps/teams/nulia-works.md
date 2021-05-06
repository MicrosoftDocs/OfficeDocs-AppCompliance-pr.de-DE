---
title: Anwendungsinformationen für Nulia Works by Nulia
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Nulia Works, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security#A0 und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9650ee1b5595967b9bc11cce5ed29addacb264e3
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/06/2021
ms.locfileid: "52250603"
---
# <a name="nulia-works"></a>Nulia Works

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 11. März 2021</p>

* <a href="https://teams.microsoft.com/l/app/e49e0f69-600c-460c-80b3-8809a9d97a4c" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002051" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Nulia an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Nulia Works |
| ID | WA200002051 |
| Funktionen | Registerkarte, Connector |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Nulia |
| URL der Partnerwebsite | [https://nulia.com](https://nulia.com) |
| URL Teams Anwendungsinfoseite | [https://nulia.com/product](https://nulia.com/product) |
| URL der Datenschutzrichtlinie | [https://nulia.com/privacy](https://nulia.com/privacy) |
| URL der Nutzungsbedingungen | [https://nulia.com/terms](https://nulia.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Nulia darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | Anwendung | Wir verwenden die gesammelten Daten, um den Fortschritt der Benutzer bei Fähigkeiten und Ergebnissen zu erzielen. Wir erfassen Verwendungsanzahlen für mehrere O365-Workloads. | Wir speichern alle daten, die wir im Blobspeicher sammeln. Wir verwenden diese Daten, um Die Benutzer über den Qualifikations- und Ergebnisfortschritt zu benoten. Beispielsweise zählen wir die Anzahl der Kalenderereignisse, die ein Benutzer hat. Dieser Wert wirkt sich auf den Qualifikationsfortschritt aus. | Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Beispielsweise verwendet unser Nulia-Mandant die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Contacts.Read | Anwendung | Wir verwenden die gesammelten Daten, um den Fortschritt der Benutzer bei Fähigkeiten und Ergebnissen zu erzielen. Wir erfassen Verwendungsanzahlen für mehrere O365-Workloads. | Wir speichern alle daten, die wir im Blobspeicher sammeln. Wir verwenden diese Daten, um Die Benutzer über den Qualifikations- und Ergebnisfortschritt zu benoten. Beispielsweise zählen wir die Anzahl der Kontakte, die ein Benutzer erstellt hat. Dieser Wert wirkt sich auf den Qualifikationsfortschritt aus. | Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Beispielsweise verwendet unser Nulia-Mandant die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Files.Read.All | Anwendung | Wir verwenden die gesammelten Daten, um den Fortschritt der Benutzer bei Fähigkeiten und Ergebnissen zu erzielen. Wir erfassen Verwendungsanzahlen für mehrere O365-Workloads. | Wir speichern alle daten, die wir im Blobspeicher sammeln. Wir verwenden diese Daten, um Die Benutzer über den Qualifikations- und Ergebnisfortschritt zu benoten. Beispielsweise zählen wir die Anzahl der Dateien, die ein Benutzer mit seinem Computer synchronisiert. Dieser Wert wirkt sich auf den Qualifikationsfortschritt aus. | Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Beispielsweise verwendet unser Nulia-Mandant die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Group.Read.All | Anwendung | Wir verwenden die gesammelten Daten, um den Fortschritt der Benutzer bei Fähigkeiten und Ergebnissen zu erzielen. Wir erfassen Verwendungsanzahlen für mehrere O365-Workloads. | Wir speichern alle daten, die wir im Blobspeicher sammeln. Wir verwenden diese Daten, um Die Benutzer über den Qualifikations- und Ergebnisfortschritt zu benoten. Beispielsweise rufen wir aus den Gruppen ab, zu Teams zu der ein Benutzer gehört. Dieser Wert wirkt sich auf den Qualifikationsfortschritt aus. | Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Beispielsweise verwendet unser Nulia-Mandant die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Mail.Read | Anwendung | Wir verwenden die gesammelten Daten, um den Fortschritt der Benutzer bei Fähigkeiten und Ergebnissen zu erzielen. Wir erfassen Verwendungsanzahlen für mehrere O365-Workloads. | Wir speichern alle daten, die wir im Blobspeicher sammeln. Wir verwenden diese Daten, um Die Benutzer über den Qualifikations- und Ergebnisfortschritt zu benoten. Beispielsweise zählen wir die Anzahl der benutzerdefinierten E-Mail-Ordner, die ein Benutzer erstellt hat. Dieser Wert wirkt sich auf den Qualifikationsfortschritt aus. | Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Beispielsweise verwendet unser Nulia-Mandant die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| MailboxSettings.Read | Anwendung | Wir verwenden die gesammelten Daten, um den Fortschritt der Benutzer bei Fähigkeiten und Ergebnissen zu erzielen. Wir erfassen Verwendungsanzahlen für mehrere O365-Workloads. | Wir speichern alle daten, die wir im Blobspeicher sammeln. Wir verwenden diese Daten, um Die Benutzer über den Qualifikations- und Ergebnisfortschritt zu benoten. Beispielsweise wird angezeigt, ob ein Benutzer über einen Nicht-Office-Antwortsatz verfügt. Dieser Wert wirkt sich auf den Qualifikationsfortschritt aus. | Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Beispielsweise verwendet unser Nulia-Mandant die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Notes.Read | Anwendung | Wir verwenden die gesammelten Daten, um den Fortschritt der Benutzer bei Fähigkeiten und Ergebnissen zu erzielen. Wir erfassen Verwendungsanzahlen für mehrere O365-Workloads. | Wir speichern alle daten, die wir im Blobspeicher sammeln. Wir verwenden diese Daten, um Die Benutzer über den Qualifikations- und Ergebnisfortschritt zu benoten. Beispielsweise zählen wir die Anzahl von Notizbüchern, die ein Benutzer freigegeben hat. Dieser Wert wirkt sich auf den Qualifikationsfortschritt aus. | Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Beispielsweise verwendet unser Nulia-Mandant die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Reports.Read.All | Anwendung | Wir verwenden die gesammelten Daten, um den Fortschritt der Benutzer bei Fähigkeiten und Ergebnissen zu erzielen. Wir erfassen Verwendungsanzahlen für mehrere O365-Workloads. | Wir speichern alle daten, die wir im Blobspeicher sammeln. Wir verwenden diese Daten, um Die Benutzer über den Qualifikations- und Ergebnisfortschritt zu benoten. Beispielsweise rufen wir aus den Benutzerberichten ab, wie viele Teams sie an einem Tag gesendet haben. Dieser Wert wirkt sich auf den Qualifikationsfortschritt aus. | Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Beispielsweise verwendet unser Nulia-Mandant die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Sites.Read.All | Anwendung | Wir verwenden die gesammelten Daten, um den Fortschritt der Benutzer bei Fähigkeiten und Ergebnissen zu erzielen. Wir erfassen Verwendungsanzahlen für mehrere O365-Workloads. | Wir speichern alle daten, die wir im Blobspeicher sammeln. Wir verwenden diese Daten, um Die Benutzer über den Qualifikations- und Ergebnisfortschritt zu benoten. Beispielsweise zählen wir die Anzahl der Websitesammlungen, die vom Benutzer erstellt wurden. Dieser Wert wirkt sich auf den Qualifikationsfortschritt aus. | Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Beispielsweise verwendet unser Nulia-Mandant die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| User.Read | Anwendung | Wir zeigen den Anzeigenamen, die Abteilung und das Profilbild des Benutzers an. | Anzeigename und Abteilung werden in unserer Datenbank gespeichert, sodass wir nicht jedes Mal auf Graph zugreifen müssen. Das Profilbild wird nicht gespeichert. | Wir erstellen eine neue Anwendungs-ID für jeden Kunden. Beispielsweise verwendet unser Nulia-Mandant die Anwendungs-ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Organization.Read.All | Anwendung | Wir erfassen den Namen des Mandanten und Yammer Basis-URL. Wir verwenden dies, um Yammer zu starten, wenn der Benutzer in unserer App im Zusammenhang mit Yammer &quot; &quot; klickt. | Wir speichern alle daten, die wir im Blobspeicher sammeln. Dies wird beispielsweise verwendet, um Yammer zu starten, wenn der Benutzer in unserer App im Zusammenhang mit Yammer &quot; &quot; klickt. | Wir verwenden die gesammelten Daten, um den Fortschritt der Benutzer bei Fähigkeiten und Ergebnissen zu erzielen. Wir erfassen Verwendungsanzahlen für mehrere O365-Workloads. |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Auf EUII wird nicht zugegriffen.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Daten auf Partnersystemen werden nicht kontrolliert

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Nulia darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden geprüft und befolgt, die in der Prüfliste Microsoft Identity Platform aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Bittet Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordern wird? | Ja |
| Unterstützt Ihre App mehrere Mandanzfähigkeiten? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle umgeleiteten Unified Resource Identifier (URI), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | - UrIs für die Platzhalterumleitung,<br/>- OAuth2 Implizite Flow, es sei denn, dies ist für eine SPA erforderlich<br/>– Fluss mit Kennwortanmeldeinformationen (Password Credential, ROPC) des Ressourcenbesitzers |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann den Erfolg von Aufrufen zu, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
