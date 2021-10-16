---
title: Anwendungsinformationen für ezTeam von EnterprizID Inc
ms.author: elmalova
author: elenamalova
ms.date: 03/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für ezTeam, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 0c7b8022a8d629af9dbce0c2f97c381b4a15ca2b
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414661"
---
# <a name="ezteam"></a>ezTeam

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 24. Februar 2021</p>

* <a href="https://teams.microsoft.com/l/app/b02f0b53-d3b7-4d53-85a9-f820f5ab33c7" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002546" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von EnterprizID Inc. an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | ezTeam |
| ID | WA200002546 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | EnterprizID Inc |
| URL der Partnerwebsite | [https://enterprizid.com](https://enterprizid.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://enterprizid.com/discover/](https://enterprizid.com/discover/) |
| URL der Datenschutzrichtlinie | [https://enterprizid.com/privacy-policy/](https://enterprizid.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://enterprizid.com/terms-of-use/](https://enterprizid.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von EnterprizID Inc. bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.Read.All | Delegiert | Liste der auf Teams verfügbaren Apps, sodass sie auf Teams Anforderungserstellungsprozess angezeigt werden kann | Nicht zutreffend | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Application.Read.All | Delegiert | Ermöglicht der App das Lesen von Anwendungen und Dienstprinzipalen im Auftrag des angemeldeten Benutzers. | Nicht zutreffend | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.AccessAsUser.All | Delegiert | Ermöglicht der App den gleichen Zugriff auf Informationen im Verzeichnis wie dem angemeldeten Benutzer. | Nicht zutreffend | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.Read.All | Delegiert | Ermöglicht der App, Daten im Verzeichnis Ihrer Organisation zu lesen, z. B. Benutzer, Gruppen und Apps. | Teams Besitz- und Mitgliedschaftsinformationen  | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.Read.All | Anwendung | Ermöglicht der App, Daten im Verzeichnis Ihrer Organisation ohne einen angemeldeten Benutzer zu lesen, z. B. Benutzer, Gruppen und Apps. | Nicht zutreffend | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.ReadWrite.All | Delegiert | Ermöglicht der App, Daten im Verzeichnis Ihrer Organisation zu lesen und zu schreiben, z. B. Benutzer und Gruppen | Nicht zutreffend | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.ReadWrite.All | Anwendung | Ermöglicht der App, Daten im Verzeichnis Ihrer Organisation ohne angemeldeten Benutzer zu lesen und zu schreiben, z. B. Benutzer und Gruppen. Ermöglicht nicht das Löschen eines Benutzers oder einer Gruppe. | Nicht zutreffend | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Files.Read.All | Anwendung | Die App kann alle Dateien in allen Websitesammlungen ohne angemeldeten Benutzer lesen. | Datenmenge unter Endbenutzergovernance in GB | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.Create | Anwendung | Ermöglicht der App, Gruppen ohne angemeldeten Benutzer zu erstellen. | Details zu neuen Gruppeneigenschaften. | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.Read.All | Delegiert | Die App kann Gruppen aufführen und deren Eigenschaften sowie alle Gruppenmitgliedschaften im Namen des angemeldeten Benutzers lesen. Wird verwendet, um "My Teams" zu ermitteln.  | Nicht zutreffend | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.Read.All | Anwendung | Ermöglicht der App das Lesen von Gruppeneigenschaften und Mitgliedschaften sowie das Lesen des Kalenders und der Unterhaltungen für alle Gruppen, ohne dass ein Benutzer angemeldet ist. | Nicht zutreffend | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.ReadWrite.All | Delegiert | Die App kann Gruppen erstellen und alle Gruppeneigenschaften und -mitgliedschaften im Namen des angemeldeten Benutzers lesen.  | Nicht zutreffend | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.ReadWrite.All | Anwendung | Ermöglicht der App, Gruppen zu erstellen, alle Gruppeneigenschaften und Mitgliedschaften zu lesen, Gruppeneigenschaften und Mitgliedschaften zu aktualisieren und Gruppen zu löschen. Ermöglicht der App auch das Lesen und Schreiben von Gruppenkalendern und Unterhaltungen.  | Letzte Aktivität des Teams. | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| GroupMember.Read.All | Anwendung | Ermöglicht der App das Lesen von Mitgliedschaften und grundlegender Gruppeneigenschaften für alle Gruppen ohne angemeldeten Benutzer. | Nicht zutreffend | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| GroupMember.ReadWrite.All | Anwendung | Ermöglicht der App das Auflisten von Gruppen, das Lesen grundlegender Eigenschaften sowie das Lesen und Aktualisieren der Mitgliedschaft derjenigen Gruppen, auf die diese App ohne angemeldeten Benutzer Zugriff hat. | Nicht zutreffend | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| People.Read.All | Anwendung | Ermöglicht der App, die bewertete Liste relevanter Personen eines beliebigen Benutzers ohne angemeldeten Benutzer zu lesen. | Nicht zutreffend | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Reports.Read.All | Delegiert | Die App kann alle Dienstverwendungsberichte im Namen des angemeldeten Benutzers lesen. | Nicht zutreffend | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Reports.Read.All | Anwendung | Die App kann alle Dienstverwendungsberichte ohne angemeldeten Benutzer lesen. | Letzte Benutzeraktivität pro Gruppe | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Sites.ReadWrite.All | Anwendung | Die App kann Dokumente und Listenelemente in allen Websitesammlungen ohne angemeldeten Benutzer erstellen, lesen, aktualisieren und löschen. | Die 10 wichtigsten Websites nach Größe für jeden Benutzer | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| User.Read | Delegiert | Allows users to sign-in to the app, and allows the app to read the profile of signed-in users. | Nicht zutreffend | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| User.Read.All | Anwendung | Ermöglicht der App, Benutzerprofile ohne angemeldeten Benutzer zu lesen. | Nicht zutreffend | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| offline_access | Delegiert | Ermöglicht der App, die Daten anzuzeigen und zu aktualisieren, auf die Sie zugriffen, auch wenn Benutzer die App derzeit nicht verwenden.  | Bot-Benachrichtigungen | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| openid | Delegiert | Damit können Benutzer sich mit Ihren Geschäfts- oder Schulkonten bei der App anmelden, und die App kann grundlegende Benutzerprofilinformationen lesen. | Nicht zutreffend | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Profil | Delegiert | Ermöglicht der App, das grundlegende Profil Ihrer Benutzer (Name, Bild, Benutzername) anzuzeigen. | Nicht zutreffend | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Benachrichtigungen über Willkommensnachricht, Genehmigungs- und Nachweisprozesse | Wir speichern den Anzeigenamen der Identitäten.  | Unser Tool ermöglicht Endbenutzern das Erstellen von Anforderungen für verschiedene Dienstelemente, und wir speichern den Anzeigenamen des Antragstellers. Eine Anforderung würde einem Genehmigungsworkflow folgen, und wir benötigen den Anzeigenamen der genehmigenden Person, um in den Anforderungsdetails angezeigt zu werden. Darüber hinaus listen wir in den Mitgliedern eines Teamzertifizierungsprozesses den Anzeigenamen der Mitglieder auf. |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>EndUser and Organization Full Name. Aufbewahrungs- und Entfernungsrichtlinien finden Sie https://enterprizid.com/privacy-policy im &quot; Abschnitt "Aufbewahrung Ihrer personenbezogenen &quot; Daten".

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir haben privileged Access Management (PMA) in Azure aktiviert, und Identitäten mit Berechtigungen zum Herstellen einer Verbindung mit den Ressourcen verwenden 2FA, um die Sicherheit zu erhöhen. Wir verwenden Azure als Cloudpartneranbieter und unterliegen dem Datenschutz und den Nutzungsbedingungen von Azure.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von EnterprizID Inc. bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

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
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>- Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

