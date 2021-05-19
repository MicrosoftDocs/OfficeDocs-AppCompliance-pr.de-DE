---
title: Anwendungsinformationen für Studi.ly von inLogic-Office Store
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Studi.ly, deren Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 26a89739809e0d398db2a823bd714aa06a2d210d
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553056"
---
# <a name="studily"></a>Studi.ly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 24. August 2020</p>

* <a href="https://teams.microsoft.com/l/app/a1eca727-7b59-4439-b269-f4b800030518" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001668" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen von inLogic-Office Store an Microsoft:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Studi.ly |
| ID | WA200001668 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | inLogic-Office Store |
| URL der Partner-Website | [https://www.studi.ly](https://www.studi.ly) |
| URL der Datenschutzrichtlinie | [https://www.studi.ly/Studily_Privacy_Statement.pdf](https://www.studi.ly/Studily_Privacy_Statement.pdf) |
| URL der Nutzungsbedingungen | [https://www.studi.ly/Studily_Terms_Of_Use_v1.pdf](https://www.studi.ly/Studily_Terms_Of_Use_v1.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von inLogic-Office Store darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Delegiert | Wir speichern Klassen, Schulen und Mitglieder und Begriffe Informationen aus Bildung api in unserem api und Wir brauchen es, weil, wenn wir es jedes Mal aus Graph api, die unsere Anwendung Arbeit langsam macht. Wir synchronisieren es auf einem zeitbasierten Ereignis von Education API zu unserer Datenbank. |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.Read.All | Delegiert | Wir speichern Klassen, Schulen und Mitglieder und Begriffe Informationen aus Bildung api in unserem api und Wir brauchen es, weil, wenn wir es jedes Mal aus Graph api, die unsere Anwendung Arbeit langsam macht. Wir synchronisieren es auf einem zeitbasierten Ereignis von Education API zu unserer Datenbank. | Schreiben Sie das Verzeichnis in den Gruppen für Zuordnungen und Materialien. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.ReadWrite.All | Anwendung | Wir speichern Klassen, Schulen und Mitglieder und Begriffe Informationen aus Bildung api in unserem api und Wir brauchen es, weil, wenn wir es jedes Mal aus Graph api, die unsere Anwendung Arbeit langsam macht. Wir synchronisieren es auf einem zeitbasierten Ereignis von Education API zu unserer Datenbank. | Schreiben Sie das Verzeichnis in den Gruppen für Zuordnungen und Materialien. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.Read.All | Anwendung | Wir speichern Klassen, Schulen und Mitglieder und Begriffe Informationen aus Bildung api in unserem api und Wir brauchen es, weil, wenn wir es jedes Mal von graph api, die unsere Anwendung Arbeit langsam macht. Wir synchronisieren es auf einem zeitbasierten Ereignis von Education API zu unserer Datenbank. | Lesen Sie Bildungsklassen, Schule, Mitglieder und Bedingungen.Alle Klassen und Schulen eines Mandanten für die Synchronisierung in die App-Datenbank abrufen. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.ReadBasic | Delegiert | Wir speichern Klassen, Schulen und Mitglieder und Begriffe Informationen aus Bildung api in unserem api und Wir brauchen es, weil, wenn wir es jedes Mal aus Graph api, die unsere Anwendung Arbeit langsam macht. Wir synchronisieren es auf einem zeitbasierten Ereignis von Education API zu unserer Datenbank. | Lesen Sie Bildungsklassen, Schule, Mitglieder und Bedingungen.Alle Klassen und Schulen eines Mandanten für die Synchronisierung in die App-Datenbank abrufen. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.ReadWrite.All | Anwendung | Wir speichern Klassen, Schulen und Mitglieder und Begriffe Informationen aus Bildung api in unserem api und Wir brauchen es, weil, wenn wir es jedes Mal aus Graph api, die unsere Anwendung Arbeit langsam macht. Wir synchronisieren es auf einem zeitbasierten Ereignis von Education API zu unserer Datenbank. | Lesen Sie Bildungsklassen, Schule, Mitglieder und Bedingungen.Alle Klassen und Schulen eines Mandanten für die Synchronisierung in die App-Datenbank abrufen. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Files.ReadWrite.All | Delegiert | Wir speichern Klassen, Schulen und Mitglieder und Begriffe Informationen aus Bildung api in unserem api und Wir brauchen es, weil, wenn wir es jedes Mal aus Graph api, die unsere Anwendung Arbeit langsam macht. Wir synchronisieren es auf einem zeitbasierten Ereignis von Education API zu unserer Datenbank. | ReadWrite-Dateien von einem Laufwerk | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.Read.All | Delegiert | Wir speichern Klassen, Schulen und Mitglieder und Begriffe Informationen aus Bildung api in unserem api und Wir brauchen es, weil, wenn wir es jedes Mal aus Graph api, die unsere Anwendung Arbeit langsam macht. Wir synchronisieren es auf einem zeitbasierten Ereignis von Education API zu unserer Datenbank. | Diese Berechtigung ermöglichte es der App, verschiedene Claender-Ereignisse für Gruppen des Mandanten abzubekommen.,subject,start,end,extensions | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.ReadWrite.All | Beide | Wir speichern Klassen, Schulen und Mitglieder und Begriffe Informationen aus Bildung api in unserem api und Wir brauchen es, weil, wenn wir es jedes Mal aus Graph api, die unsere Anwendung Arbeit langsam macht. Wir synchronisieren es auf einem zeitbasierten Ereignis von Education API zu unserer Datenbank. | Diese Berechtigung ermöglichte es der App, verschiedene Claender-Ereignisse für Gruppen des Mandanten abzubekommen.,subject,start,end,extensions | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Member.Read.Hidden | Anwendung |  |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Sites.ReadWrite.All | Beide | Wir speichern Klassen, Schulen und Mitglieder und Begriffe Informationen aus Bildung api in unserem api und Wir brauchen es, weil, wenn wir es jedes Mal aus Graph api, die unsere Anwendung Arbeit langsam macht. Wir synchronisieren es auf einem zeitbasierten Ereignis von Education API zu unserer Datenbank. | ReadWrite-Dateien von einem Laufwerk | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.Read | Delegiert | Wir speichern Klassen, Schulen und Mitglieder und Begriffe Informationen aus Bildung api in unserem api und Wir brauchen es, weil, wenn wir es jedes Mal aus Graph api, die unsere Anwendung Arbeit langsam macht. Wir synchronisieren es auf einem zeitbasierten Ereignis von Education API zu unserer Datenbank. | Lesen von Benutzerinformationen | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.ReadBasic.All | Delegiert | Wir speichern Klassen, Schulen und Mitglieder und Begriffe Informationen aus Bildung api in unserem api und Wir brauchen es, weil, wenn wir es jedes Mal aus Graph api, die unsere Anwendung Arbeit langsam macht. Wir synchronisieren es auf einem zeitbasierten Ereignis von Education API zu unserer Datenbank. | Lesen von Benutzerinformationen | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird kein EUII abgerufen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Solche Daten werden nicht in den Protokollen angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Sie wird in der Azure cosmos-Datenbank gespeichert, und alle Verschlüsselungen und Speicher, die standardmäßig mit der cosmos-Datenbank verfügbar sind, gelten für diese Anwendung.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

