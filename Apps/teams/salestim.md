---
title: Anwendungsinformationen für SalesTim von SalesTim
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für SalesTim, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c9094f50723c7094f895d21f8a9569dedbb5863b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553916"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Zuletzt aktualisiert vom Entwickler am: 27. Oktober 2020</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die SalesTim Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | SalesTim |
| ID | WA200001393 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | SalesTim |
| URL der Partner-Website | [https://www.salestim.com](https://www.salestim.com) |
| URL der Datenschutzrichtlinie | [https://www.salestim.com/legal/privacy](https://www.salestim.com/legal/privacy) |
| URL der Nutzungsbedingungen | [https://www.salestim.com/legal/tos](https://www.salestim.com/legal/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von SalesTim darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | Delegiert | NEIN | Erlauben Sie der App, eigene Pakete im Unternehmens-App-Katalog zu installieren und zu aktualisieren. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | Delegiert | Wir&#8217;nur einige Benutzer-IDs speichern, nicht Profildaten. | Ermöglicht es einem Benutzer, andere Benutzer an verschiedenen Stellen in der Anwendung auszuwählen, z. B. die Auswahl von Genehmigenden in einem Workflow. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | Delegiert | Wir&#8217;nur Gruppen-/Team-IDs speichern, wir&#8217;keine Gruppen-/Teaminhalte speichern. | Ermöglicht der App, Gruppen zu erstellen, alle Gruppeneigenschaften und Mitgliedschaften im Namen des angemeldeten Benutzers zu lesen. Darüber hinaus können Gruppenbesitzer ihre eigenen Gruppen verwalten, und Gruppenmitglieder können Gruppeninhalte aktualisieren. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | Delegiert | Wir&#8217;die Metadaten dieser Aktion, z. B. das Benachrichtigungsdatum, den Empfänger (nur ID), die Anforderungs-ID erneut speichern. | Ermöglicht der App, Benachrichtigungs-E-Mails z. B. während eines Genehmigungsworkflows zu senden. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | Delegiert | Wir verwenden einige Azure-Dienste zum Speichern von Daten, insbesondere Redis in Azure und Cosmos DB | Ermöglicht der App, die Laufwerke (Dateien und Ordner), die einem Team zugeordnet sind, während eines Teambereitstellungsprozesses zu verwalten. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | Delegiert | Wir&#8217;nur einige Benutzer-IDs speichern, nicht Profildaten. | Ermöglicht der App das Lesen des vollständigen Satzes von Profileigenschaften, Berichten und Managern eines beliebigen Benutzers. Es wird insbesondere während des Zielgruppen-Targeting-Prozesses verwendet, um einige Inhalte basierend auf dem aktuellen Benutzerprofil zu filtern. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Offlinezugriff | Delegiert | Nein | Ermöglicht der App, einige Hintergrundoperationen und Aktionen als Benutzer auszuführen. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wir verwenden Intercom als Hauptsupport-Anwendung. Intercom kann einige grundlegende Benutzerprofilinformationen enthalten, wie hier beschrieben: https://developers.salestim.com/platform/datamanagement.html#support-data |  | Wir verwenden GitHub APIs, um Probleme automatisch aus unserer Produktionsumgebung zu generieren. Wir speichern auch einige technische Protokolle in GitHub (wie hier beschrieben: https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) . Diese Probleme und Protokolle können einige grundlegende Benutzerprofilinformationen enthalten. Diese Probleme und Protokolle werden automatisch alle 15 Tage gelöscht. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird kein EUII abgerufen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Alle erhobenen Daten werden hier beschrieben: https://developers.salestim.com/platform/datamanagement.html#application-data Wie beschrieben werden Protokolle 15 Tage lang temporär gespeichert und dann automatisch gelöscht.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Die meisten Daten werden in Azure Cosmos DB gespeichert.
Der Zugriff auf die Produktionsumgebung ist auf zwei Personen beschränkt, und diese Administratorkonten werden von MFA erzwungen.
Diese Konten sind dedizierte und unterscheiden sich von unseren Unternehmenskonten.
Die Daten werden in allen Azure-Diensten, die wir verwenden, im Ruhezustand verschlüsselt.
Bereitstellungen in Produktionsumgebungen werden über einen dedizierten geschützten Zweig in unserer GitHub Umgebung automatisiert, in dem nur zwei Personen Änderungen genehmigen können.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

