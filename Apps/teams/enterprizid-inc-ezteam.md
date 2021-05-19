---
title: Anwendungsinformationen für ezTeam von EnterprizID Inc
ms.author: elmalova
author: elenamalova
ms.date: 02/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für ezTeam, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen sowie Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
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

* <a href="https://teams.microsoft.com/l/app/b02f0b53-d3b7-4d53-85a9-f820f5ab33c7" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002546" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die EnterprizID Inc. Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | ezTeam |
| ID | WA200002546 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | EnterprizID Inc |
| URL der Partner-Website | [https://enterprizid.com](https://enterprizid.com) |
| URL Teams Anwendungsinfoseite | [https://enterprizid.com/discover/](https://enterprizid.com/discover/) |
| URL der Datenschutzrichtlinie | [https://enterprizid.com/privacy-policy/](https://enterprizid.com/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://enterprizid.com/terms-of-use/](https://enterprizid.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von EnterprizID Inc. darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.Read.All | Delegiert | Liste der apps, die unter Teams verfügbar sind, damit wir sie bei Teams Anforderungserstellungsprozess anzeigen können | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Application.Read.All | Delegiert | Ermöglicht der App das Lesen von Anwendungen und Dienstprinzipalen im Auftrag des angemeldeten Benutzers. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.AccessAsUser.All | Delegiert | Ermöglicht der App den gleichen Zugriff auf Informationen im Verzeichnis wie dem angemeldeten Benutzer. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | Delegiert | Ermöglicht der App, Daten im Verzeichnis Ihrer Organisation zu lesen, z. B. Benutzer, Gruppen und Apps. | Teams Eigentums- und Mitgliedschaftsinformationen  | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | Anwendung | Ermöglicht der App, Daten im Verzeichnis Ihrer Organisation ohne einen angemeldeten Benutzer zu lesen, z. B. Benutzer, Gruppen und Apps. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | Delegiert | Ermöglicht der App das Lesen und Schreiben von Daten im Verzeichnis Ihrer Organisation, z. B. Benutzer und Gruppen | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | Anwendung | Ermöglicht der App, Daten im Verzeichnis Ihrer Organisation ohne angemeldeten Benutzer zu lesen und zu schreiben, z. B. Benutzer und Gruppen. Ermöglicht nicht das Löschen eines Benutzers oder einer Gruppe. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Files.Read.All | Anwendung | Die App kann alle Dateien in allen Websitesammlungen ohne angemeldeten Benutzer lesen. | Datenmenge unter Endbenutzer-Governance in GB | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Create | Anwendung | Ermöglicht der App das Erstellen von Gruppen ohne angemeldeten Benutzer. | Details zu neuen Gruppeneigenschaften. | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | Delegiert | Die App kann Gruppen aufführen und deren Eigenschaften sowie alle Gruppenmitgliedschaften im Namen des angemeldeten Benutzers lesen. Wird verwendet, um Meine Teams zu bestimmen  | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | Anwendung | Ermöglicht der App das Lesen von Gruppeneigenschaften und Mitgliedschaften sowie das Lesen des Kalenders und der Unterhaltungen für alle Gruppen ohne angemeldeten Benutzer. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | Delegiert | Die App kann Gruppen erstellen und alle Gruppeneigenschaften und -mitgliedschaften im Namen des angemeldeten Benutzers lesen.  | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | Anwendung | Ermöglicht der App das Erstellen von Gruppen, das Lesen aller Gruppeneigenschaften und Mitgliedschaften, das Aktualisieren von Gruppeneigenschaften und Mitgliedschaften sowie das Löschen von Gruppen. Ermöglicht der App auch das Lesen und Schreiben von Gruppenkalendern und Unterhaltungen.  | Letzte Aktivität des Teams. | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| GroupMember.Read.All | Anwendung | Ermöglicht der App das Lesen von Mitgliedschaften und grundlegender Gruppeneigenschaften für alle Gruppen ohne angemeldeten Benutzer. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| GroupMember.ReadWrite.All | Anwendung | Ermöglicht der App das Auflisten von Gruppen, das Lesen grundlegender Eigenschaften sowie das Lesen und Aktualisieren der Mitgliedschaft derjenigen Gruppen, auf die diese App ohne angemeldeten Benutzer Zugriff hat. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| People.Read.All | Anwendung | Ermöglicht der App, die Liste der relevanten Personen eines beliebigen Benutzers ohne einen angemeldeten Benutzer zu lesen. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Reports.Read.All | Delegiert | Die App kann alle Dienstverwendungsberichte im Namen des angemeldeten Benutzers lesen. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Reports.Read.All | Anwendung | Die App kann alle Dienstverwendungsberichte ohne angemeldeten Benutzer lesen. | Letzte Benutzeraktivität pro Gruppe | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Sites.ReadWrite.All | Anwendung | Die App kann Dokumente und Listenelemente in allen Websitesammlungen ohne angemeldeten Benutzer erstellen, lesen, aktualisieren und löschen. | Top 10 Sites nach Größe für jeden Benutzer | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read | Delegiert | Allows users to sign-in to the app, and allows the app to read the profile of signed-in users. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read.All | Anwendung | Ermöglicht der App das Lesen von Benutzerprofilen ohne angemeldeten Benutzer. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| offline_access | Delegiert | Ermöglicht der App, die Daten anzuzeigen und zu aktualisieren, auf die Sie Zugriff gewährt haben, auch wenn Benutzer die App derzeit nicht verwenden.  | Bot-Benachrichtigungen | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| openid | Delegiert | Damit können Benutzer sich mit Ihren Geschäfts- oder Schulkonten bei der App anmelden, und die App kann grundlegende Benutzerprofilinformationen lesen. | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Profil | Delegiert | Ermöglicht der App, das Basisprofil Ihrer Benutzer anzuzeigen (Name, Bild, Benutzername) | Nicht zutreffend | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Begrüßung, Genehmigung und Bescheinigung verarbeitet Benachrichtigungen | Wir speichern den Anzeigenamen der Identitäten  | Unser Tool ermöglicht es Endbenutzern, Anfragen für verschiedene Serviceartikel zu erstellen, und wir speichern den Anzeigenamen des Anforderers. Eine Anforderung würde einem Genehmigungsworkflow folgen, und wir benötigen den Anzeigenamen der genehmigenden Person, um in den Anforderungsdetails angezeigt zu werden. Darüber hinaus listen wir in den Mitgliedern eines Teamzertifizierungsprozesses den Anzeigenamen der Mitglieder auf. |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>EndUser und Organisation Vollständiger Name. Aufbewahrungs- und Entfernungsrichtlinien finden Sie https://enterprizid.com/privacy-policy unter &quot; Aufbewahrung Ihrer personenbezogenen Daten &quot;

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Wir haben Privileged Access Management (PMA) in Azure aktiviert, und Identitäten mit Berechtigungen zum Herstellen einer Verbindung mit den Ressourcen verwenden 2FA, um die Sicherheit zu erhöhen. Wir verwenden Azure als unseren Cloud-Partneranbieter und unterliegen den Datenschutzbestimmungen und Nutzungsbedingungen von Azure.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von EnterprizID Inc. darüber bereitgestellt, wie diese App authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Können Sie sich in Microsoft Identifizplattform (Azure AD) integrieren?  | Ja |
| Haben Sie alle in der Checkliste für die Microsoft Identity Platform-Integration beschriebenen bewährten Methoden überprüft und eingehalten?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Conditional Access-Richtlinien? | Nein |
| Fordert Ihre App die geringsten Berechtigungsberechtigungen für Ihr Szenario an? | Ja |
| Gibt die statisch registrierten Berechtigungen Ihrer App die Berechtigungen wieder, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Multi-Tenancy? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle für Ihre App registrierten Unified Resource Identifier (URI) umleiten? | Ja |
| Was vermeiden Sie für Ihre App? | - Wildcard-Umleitungs-URIs,<br/>- OAuth2 Implizite Flow, es sei denn, dies ist für ein SPA erforderlich<br/>- Ressourcenbesitzer-Kennwortanmeldeinformationen (ROPC)-Flow |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann zu, dass Aufrufe erfolgreich sind, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
