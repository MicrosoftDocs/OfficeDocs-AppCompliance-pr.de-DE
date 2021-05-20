---
title: Anwendungsinformationen für ezTeam von EnterprizID Inc
ms.author: elmalova
author: elenamalova
ms.date: 02/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für ezTeam, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: da54d5a540fd43c2bdc25a6f4e31ba88520ecbc3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553176"
---
# <a name="ezteam"></a>ezTeam

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 24. Februar 2021</p>

* <a href="https://teams.microsoft.com/l/app/b02f0b53-d3b7-4d53-85a9-f820f5ab33c7" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002546" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von EnterprizID Inc an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | ezTeam |
| ID | WA200002546 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | EnterprizID Inc |
| URL der Partnerwebsite | [https://enterprizid.com](https://enterprizid.com) |
| URL Teams Anwendungsinfoseite | [https://enterprizid.com/discover/](https://enterprizid.com/discover/) |
| URL der Datenschutzrichtlinie | [https://enterprizid.com/privacy-policy/](https://enterprizid.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://enterprizid.com/terms-of-use/](https://enterprizid.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von EnterprizID Inc. bereitgestellt, um zu erfahren, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.Read.All | delegierte | Liste der apps, die unter Teams verfügbar sind, damit wir sie bei Teams Anforderungserstellungsprozess anzeigen können | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Application.Read.All | delegierte | Ermöglicht der App das Lesen von Anwendungen und Dienstprinzipalen im Auftrag des angemeldeten Benutzers. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.AccessAsUser.All | delegierte | Ermöglicht der App den gleichen Zugriff auf Informationen im Verzeichnis wie dem angemeldeten Benutzer. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | delegierte | Ermöglicht der App, Daten im Verzeichnis Ihrer Organisation zu lesen, z. B. Benutzer, Gruppen und Apps. | Teams Besitz- und Mitgliedschaftsinformationen  | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | Anwendung | Ermöglicht der App, Daten im Verzeichnis Ihrer Organisation ohne einen angemeldeten Benutzer zu lesen, z. B. Benutzer, Gruppen und Apps. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | delegierte | Ermöglicht der App das Lesen und Schreiben von Daten im Verzeichnis Ihrer Organisation, z. B. Benutzer und Gruppen | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | Anwendung | Ermöglicht der App, Daten im Verzeichnis Ihrer Organisation ohne angemeldeten Benutzer zu lesen und zu schreiben, z. B. Benutzer und Gruppen. Ermöglicht nicht das Löschen eines Benutzers oder einer Gruppe. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Files.Read.All | Anwendung | Die App kann alle Dateien in allen Websitesammlungen ohne angemeldeten Benutzer lesen. | Datenmenge unter Endbenutzer-Governance in GB | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Create | Anwendung | Ermöglicht der App das Erstellen von Gruppen ohne angemeldeten Benutzer. | Details zu neuen Gruppeneigenschaften. | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | delegierte | Die App kann Gruppen aufführen und deren Eigenschaften sowie alle Gruppenmitgliedschaften im Namen des angemeldeten Benutzers lesen. Wird verwendet, um My Teams  | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | Anwendung | Ermöglicht der App das Lesen von Gruppeneigenschaften und -mitgliedschaften sowie das Lesen des Kalenders und der Unterhaltungen für alle Gruppen ohne angemeldeten Benutzer. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | delegierte | Die App kann Gruppen erstellen und alle Gruppeneigenschaften und -mitgliedschaften im Namen des angemeldeten Benutzers lesen.  | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | Anwendung | Ermöglicht der App, Gruppen zu erstellen, alle Gruppeneigenschaften und -mitgliedschaften zu lesen, Gruppeneigenschaften und Mitgliedschaften zu aktualisieren und Gruppen zu löschen. Ermöglicht der App außerdem das Lesen und Schreiben von Gruppenkalendern und Unterhaltungen.  | Letzte Aktivität des Teams. | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| GroupMember.Read.All | Anwendung | Ermöglicht der App das Lesen von Mitgliedschaften und grundlegender Gruppeneigenschaften für alle Gruppen ohne angemeldeten Benutzer. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| GroupMember.ReadWrite.All | Anwendung | Ermöglicht der App das Auflisten von Gruppen, das Lesen grundlegender Eigenschaften sowie das Lesen und Aktualisieren der Mitgliedschaft derjenigen Gruppen, auf die diese App ohne angemeldeten Benutzer Zugriff hat. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| People.Read.All | Anwendung | Ermöglicht der App, die Bewertungsliste relevanter Personen aller Benutzer ohne angemeldeten Benutzer zu lesen. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Reports.Read.All | delegierte | Die App kann alle Dienstverwendungsberichte im Namen des angemeldeten Benutzers lesen. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Reports.Read.All | Anwendung | Die App kann alle Dienstverwendungsberichte ohne angemeldeten Benutzer lesen. | Letzte Benutzeraktivität pro Gruppe | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Sites.ReadWrite.All | Anwendung | Die App kann Dokumente und Listenelemente in allen Websitesammlungen ohne angemeldeten Benutzer erstellen, lesen, aktualisieren und löschen. | Die 10 am besten 10 Websites nach Größe für jeden Benutzer | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read | delegierte | Allows users to sign-in to the app, and allows the app to read the profile of signed-in users. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read.All | Anwendung | Ermöglicht der App das Lesen von Benutzerprofilen ohne angemeldeten Benutzer. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| offline_access | delegierte | Ermöglicht der App, die Daten, auf die Sie zugriffen, zu sehen und zu aktualisieren, auch wenn Benutzer die App derzeit nicht verwenden.  | Botbenachrichtigungen | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| openid | delegierte | Damit können Benutzer sich mit Ihren Geschäfts- oder Schulkonten bei der App anmelden, und die App kann grundlegende Benutzerprofilinformationen lesen. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Profil | delegierte | Ermöglicht der App, das grundlegende Profil Ihrer Benutzer (Name, Bild, Benutzername) zu sehen. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Benachrichtigungen zu Willkommensmeldungen, Genehmigungs- und Attestierungsprozessen | Wir speichern den Anzeigenamen der Identitäten  | Unser Tool ermöglicht Endbenutzern das Erstellen von Anfragen für verschiedene Dienstelemente, und wir speichern den Anzeigenamen des Ansendeers. Eine Anforderung würde einem Genehmigungsworkflow folgen, und wir benötigen den Anzeigenamen der Genehmigenden, um die Anforderungsdetails anzuzeigen. Darüber hinaus wird in den Mitgliedern eines Teamzertifizierungsprozesses der Anzeigename der Mitglieder aufgeführt. |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>EndUser und Vollständiger Name der Organisation. Aufbewahrungs- und Entfernungsrichtlinien finden Sie unter https://enterprizid.com/privacy-policy &quot; Aufbewahrung Ihrer personenbezogenen &quot; Daten.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir haben privilegierte Zugriffsverwaltung (Privileged Access Management, PMA) in Azure aktiviert, und Identitäten mit Berechtigungen zum Herstellen einer Verbindung mit den Ressourcen verwenden 2FA, um die Sicherheit zu erhöhen. Wir verwenden Azure als unseren Cloudpartneranbieter und unterliegen den Datenschutz- und Nutzungsbedingungen von Azure.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von EnterprizID Inc. darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden geprüft und befolgt, die in der Prüfliste Microsoft Identity Platform aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Bittet Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordern wird? | Ja |
| Unterstützt Ihre App mehrere Mandanzfähigkeiten? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle umgeleiteten Unified Resource Identifier (URI), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | - UrIs für die Platzhalterumleitung,<br/>- OAuth2 Implizite Flow, es sei denn, dies ist für eine SPA erforderlich<br/>– Fluss mit Kennwortanmeldeinformationen (Password Credential, ROPC) des Ressourcenbesitzers |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann den Erfolg von Aufrufen zu, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
