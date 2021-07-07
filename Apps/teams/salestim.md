---
title: Anwendungsinformationen für SalesTim von SalesTim
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Complianceinformationen für SalesTim, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ada23e0899e67432b0718ec34f32c236e8768a18
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/02/2021
ms.locfileid: "53283069"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: October 27, 2020</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von SalesTim an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | SalesTim |
| ID | WA200001393 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | SalesTim |
| URL der Partnerwebsite | [https://www.salestim.com/](https://www.salestim.com/) |
| URL der Datenschutzrichtlinie | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| URL der Nutzungsbedingungen | [https://www.salestim.com/legal/tos/](https://www.salestim.com/legal/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von SalesTim darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | Delegiert | NEIN | Zulassen, dass die App ihre eigenen Pakete im Unternehmens-App-Katalog installiert und aktualisiert. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | Delegiert | Wir&#8217;nur einige Benutzer-IDs speichern, nicht Profildaten. | Ermöglicht es einem Benutzer, andere Benutzer an verschiedenen Stellen in der Anwendung auszuwählen, z. B. genehmigende Personen in einem Workflow auszuwählen. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | Delegiert | Wir&#8217;nur Gruppen/Teams-IDs speichern, wir&#8217;keine Gruppen-/Teams-Inhalte speichern. | Ermöglicht der App, Gruppen zu erstellen, alle Gruppeneigenschaften und Mitgliedschaften im Namen des angemeldeten Benutzers zu lesen. Darüber hinaus können Gruppenbesitzer ihre eigenen Gruppen verwalten, und Gruppenmitglieder können Gruppeninhalte aktualisieren. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | Delegiert | Wir&#8217;die Metadaten dieser Aktion speichern, z. B. Benachrichtigungsdatum, Empfänger (nur ID), Anforderungs-ID. | Ermöglicht der App das Senden von Benachrichtigungs-E-Mails, z. B. während eines Genehmigungsworkflows. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | Delegiert | Wir verwenden einige Azure-Dienste zum Speichern von Daten, insbesondere Redis in Azure und Cosmos DB | Ermöglicht der App, die Laufwerke (Dateien und Ordner), die einem Team zugeordnet sind, während eines Teambereitstellungsprozesses zu verwalten. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | Delegiert | Wir&#8217;nur einige Benutzer-IDs speichern, nicht Profildaten. | Ermöglicht der App, den vollständigen Satz von Profileigenschaften, Berichten und Vorgesetzten eines beliebigen Benutzers zu lesen. Es wird insbesondere während des Zielgruppenadressierungsprozesses verwendet, um einige Inhalte basierend auf dem aktuellen Benutzerprofil zu filtern. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| offlineaccess | Delegiert | Nein | Ermöglicht der App, einige Hintergrundvorgänge und Aktionen als Benutzer auszuführen. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wir verwenden Intercom als Hauptunterstützungsanwendung. Die Intercom kann einige grundlegende Benutzerprofilinformationen enthalten, wie hier beschrieben: https://developers.salestim.com/platform/datamanagement.html#support-data |  | Wir verwenden GitHub-APIs, um Probleme automatisch aus unserer Produktionsumgebung zu generieren. Außerdem speichern wir einige technische Protokolle in GitHub (wie hier beschrieben: https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) . Diese Probleme und Protokolle können einige grundlegende Benutzerprofilinformationen enthalten. Diese Probleme und Protokolle werden alle 15 Tage automatisch gelöscht. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Alle gesammelten Daten werden hier beschrieben: https://developers.salestim.com/platform/datamanagement.html#application-data Wie beschrieben, werden Protokolle vorübergehend für 15 Tage gespeichert und dann automatisch gelöscht.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die meisten Daten werden in Azure Cosmos DB gespeichert.
Der Zugriff auf die Produktionsumgebung ist auf zwei Personen beschränkt, und diese Administratorkonten werden durch MFA erzwungen.
Diese Konten sind dedizierend und unterscheiden sich von unseren Unternehmenskonten.
Ruhenden Daten werden in allen azure-Diensten verschlüsselt, die wir verwenden.
Bereitstellungen in Produktionsumgebungen werden über einen dedizierten geschützten Branch in unserer GitHub-Umgebung automatisiert, in dem nur zwei Personen Änderungen genehmigen können.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

