---
title: Application Information for Wieso von Wiesn
ms.author: elmalova
author: elenamalova
ms.date: 08/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Xaml, die Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a44620633f9eee6c5d5e18997a58158a16c5e801
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/12/2021
ms.locfileid: "59282071"
---
# <a name="senso"></a>Senso

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 2, 2021</p>

* <a href="https://teams.microsoft.com/l/app/3973b9d4-b50e-472d-8145-8967e01379b4" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002571" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Dero an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Senso |
| ID | WA200002571 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Senso |
| URL der Partnerwebsite | [https://www.senso.cloud](https://www.senso.cloud) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.senso.cloud/safeguarding-microsoft-teams/](https://www.senso.cloud/safeguarding-microsoft-teams/) |
| URL der Datenschutzrichtlinie | [https://www.senso.cloud/privacy](https://www.senso.cloud/privacy) |
| URL der Nutzungsbedingungen | [https://www.senso.cloud/eula](https://www.senso.cloud/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Dero bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | Anwendung | Lesen Sie die Kanalnamen und Beschreibungen für alle Kanäle, um zu ermitteln, wo eine Verletzung gekennzeichnet wurde.   | Wenn eine Verletzung auftritt, werden der Name des Absenders (von), die Namen der Empfänger (An), der Kanalname, das Datum, die Uhrzeit und die Nachrichten aus diesem Chatkanal protokolliert, um Kontext für einen Verstoß bereitzustellen.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| ChannelMember.Read.All | Anwendung | Lesen Sie die Mitgliederliste und Chatnachrichten aller Kanäle. | Wenn eine Verletzung auftritt, werden der Name des Absenders (von), die Namen der Empfänger (An), der Kanalname, das Datum, die Uhrzeit und die Nachrichten aus diesem Chatkanal protokolliert, um Kontext für einen Verstoß bereitzustellen.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| ChannelMessage.Read.All | Anwendung | Alle Kanalnachrichten lesen | Wenn eine Verletzung auftritt, werden der Name des Absenders (von), die Namen der Empfänger (An), der Kanalname, das Datum, die Uhrzeit und die Nachrichten aus diesem Chatkanal protokolliert, um Kontext für einen Verstoß bereitzustellen.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Chat.Read.All | Anwendung | Lesen aller Chatnachrichten | Wenn eine Verletzung auftritt, werden der Name des Absenders (von), die Namen der Empfänger (An), der Kanalname, das Datum, die Uhrzeit und die Nachrichten aus diesem Chatkanal protokolliert, um Kontext für einen Verstoß bereitzustellen.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Directory.Read.All | Anwendung | Verzeichnisdaten lesen | Wenn eine Verletzung auftritt, werden der Name des Absenders (von), die Namen der Empfänger (An), der Kanalname, das Datum, die Uhrzeit und die Nachrichten aus diesem Chatkanal protokolliert, um Kontext für einen Verstoß bereitzustellen.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Files.Read.All | Anwendung | Lesen von Dateien in allen Websitesammlungen | Wenn eine Verletzung auftritt, werden der Name des Absenders (von), die Namen der Empfänger (An), der Kanalname, das Datum, die Uhrzeit und die Nachrichten aus diesem Chatkanal protokolliert, um Kontext für einen Verstoß bereitzustellen.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| User.Read | Delegiert | Anmelden und Benutzerprofil lesen | Wird für einmaliges Anmelden verwendet | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| User.Read.All | Anwendung | Lesezugriff auf vollständige Profile aller Benutzer | Wenn eine Verletzung auftritt, werden der Name des Absenders (von), die Namen der Empfänger (An), der Kanalname, das Datum, die Uhrzeit und die Nachrichten aus diesem Chatkanal protokolliert, um Kontext für einen Verstoß bereitzustellen.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle Nicht-Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Senso.cloud verwendet die folgenden Unterprozessoren für die Leistung des Diensts: https://www.senso.cloud/privacy-policy/ Abschnitt 5. Offenlegung Ihrer personenbezogenen Daten. | Die Arten von Daten, die wir für Drittanbieterkonten und Drittanbieter freigeben, sind in Abschnitt 5 in der rechten Spalte der Tabelle https://www.senso.cloud/privacy-policy/) ( . | Die rechtmäßige Grundlage für die verarbeitung jeder basiert auf der Erfüllung eines Vertrags mit Ihnen oder erforderlich für unsere berechtigten Interessen (für die Ausführung unseres Geschäfts, Archivierungsdaten, Bereitstellung von Verwaltung und IT-Diensten, Netzwerksicherheit, um Betrug und Datenschutzverletzungen zu verhindern. Beispielsweise ist die Geschäftliche E-Mail-Adresse, die E-Mail-Adresse erforderlich, um die Benachrichtigungen über den Rechnungskontakt an den Kunden zu senden, oder wenn die Zahlung per Kreditkarte erfolgt, sind Informationen erforderlich, um beim Zugriff auf den Kundensupport Supporttickets zu erhalten. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Senso.cloud verwendet die folgenden Unterprozessoren für die Leistung des Diensts: https://www.senso.cloud/privacy-policy/ Abschnitt 5. Offenlegung Ihrer personenbezogenen Daten. | Die Arten von Daten, die wir für Drittanbieterkonten und Drittanbieter freigeben, sind in Abschnitt 5 in der rechten Spalte der Tabelle https://www.senso.cloud/privacy-policy/) ( . | Die rechtmäßige Grundlage für die verarbeitung jeder basiert auf der Erfüllung eines Vertrags mit Ihnen oder erforderlich für unsere berechtigten Interessen (für die Ausführung unseres Geschäfts, Archivierungsdaten, Bereitstellung von Verwaltung und IT-Diensten, Netzwerksicherheit, um Betrug und Datenschutzverletzungen zu verhindern. Beispielsweise ist die Geschäftliche E-Mail-Adresse, die E-Mail-Adresse erforderlich, um die Benachrichtigungen über den Rechnungskontakt an den Kunden zu senden, oder wenn die Zahlung per Kreditkarte erfolgt, sind Informationen erforderlich, um beim Zugriff auf den Kundensupport Supporttickets zu erhalten. |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Monitorso überwacht Chatnachrichten anhand von Schlüsselwort- und Bild-Bedrohungserkennungsbibliotheken.  Wenn eine Übereinstimmung auftritt, protokollieren wir die folgenden Informationen gegen den Auslöser des Verstoßes; Uhrzeit und Datum, Website-ID, Ausdruck/Bild, Schweregrad, Von, An, Kanalname, Status und auslösende Bibliothek zur Überprüfung durch den Endbenutzer.  Wir speichern personenbezogene Informationen nur so lange, wie dies zur Erfüllung der Zwecke erforderlich ist, für die wir sie gesammelt haben, einschließlich zum Zwecke der Erfüllung rechtlicher, betrieblicher, buchhalterischer oder Berichtsanforderungen.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Beschränkter Zugriff auf leitende Entwickler, gesperrte IP-Adressen, 2-Faktor-Authentifizierung und Überwachungsprotokolle.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/40112' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/40112" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Demo bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Rollenbasierte Zugriffsberechtigungen |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/><br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
